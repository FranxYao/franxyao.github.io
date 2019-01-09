## Attempts on the Speech Emotion Transfer Task

----

Yao Fu, Columbia University 

yao.fu@columbia.edu

WED JAN 09TH 2018 



First, for the record, this is not a successful project, neither this post will give you the demo nor show you how to perform Emotion Transfer on voice. This post is a list of what we have tried, the reasons that we think why things do not work, and what should we do in the future. 

Our conclusion is: to perform speech emotion transfer, it is not a good idea to do this on a small dataset. It is suggested to try this on a large dataset, or to first perform ASR and then perfrom Emotional TTS. 

Here is the story:

### Motivation

We have already seen the successful neural style transfer models on both [image style transfer](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf) and [text sentiment transfer](https://arxiv.org/abs/1703.00955). So the people in Speech might be natural to think if a transfer task can be done in this area. Previously, before the neural network era, people have already performed successful Speaker Identity Transfer (a.k.a. Voice Conversion) with Gaussian Mixture Models. Compared with the speaker identity, emotion is another dimention of speech, and might be more challenging than the speaker identity: one can transfer the speaker identity frame by frame, but one cannot transfer the emotion frame by frame because the emotion is the "global" quality of an utterance. When this comes to modeling, one may want a model capable of capturing the _global structure_ or the _long term dependency_ in voice. So the problem is: we what to perform the emotion transfer with an utterance level model (in contrast to the frame level). 

In terms of the research contribution, since it seems that no one has done this before, I think perhaps simply getting things work will give you a paper on Interspeech. 

### Datasets, Models, and Experiments 

In the Columbia Speech Lab, people prefer doing things with smaller datasets (for the apparent computation power reasons). If we want to do this in the TTS way, we need very large amount of data and GPU hours. However, the previous attempts on Voice Conversion shows that one can transfer the speakers identity with only moderate amount of data. In our experiments, we tried the [EPSaT dataset](https://catalog.ldc.upenn.edu/LDC2002S28) and the [Mandarin Affective Speech dataset](https://catalog.ldc.upenn.edu/LDC2007S09). Both of them are of thousands of utterances (K-levels). However, as mentioned in the above, you may want to try a M-level or G-level dataset with emotion labels. We think that if Emotion Transfer is comparable to Voice Conversion, we may also do this with smaller datasets.

But it turned out that this assumption is wrong. The Emotion Transfer task is not comparable to the VC task. We have tried multiple approaches. The model architectures include Feed Forward Networks, CNNs, and Transformers (we did not test LSTMs and WaveNets). The training techniques include Conditional Autoencoding, Conditional VAE and GANs. Also we tried multiple hyper paremeter settings. None of them worked on the dataset. This was the point I doubted that  whether the Emotion Transfer is really comparable to Voice Conversion. 

To verify the model capability, we did a **cross-verification**: we tried to train our Emotion Transfer model on the Voice Conversion dataset, and to train a Voice Conversion model on the Emotion Transfer dataset. The result, you guess, is that our emotion models can work on the VC task, but the VC model cannot work on the emotion task. This means that the problem might not be the model capability because if that is the case, the emotion model should not work on VC. 

### Error Analysis 

When things do not work in Deep Learning, there are three things to consider: 1). the data, 2). the model, and 3). the optimization. Of course before the three, there is a number zero: 0). the whole starting point. In our case, the cross-verification experiments show that the problem should not be the model or the optimization. So this leads to the data. Also considering the number zero, the starting point, one may also want to do this task in a ASR-TTS way: first to convert the speech of one emotion to text, then generate speech of another emotion from the text. These might be better ways to tackle this task. 

### Conclusion

So I did not success on this project. But at least, I think the right way might be doing this with larger datasets, or with the ASR-TTS approach (which also requires larger datasets). In terms of modeling, I think we indeed tried the best models at hand (the Transformer model turned out to be the best). So we might not be able to doing things in this direction. This is the project course I took in the 2018 Fall semester at Columbia, and you can read the full report [here](https://francix.github.io/blog/FinalReport.pdf)

