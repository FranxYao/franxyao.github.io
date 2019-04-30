## On text generation and evaluation 

Yao Fu, Columbia University 

yao.fu@columbia.edu

Apr 29th 2019

---- 

Talking about today's neural text generation: previously, the most challenging generation task is machine translation. But today, with deep learning, machine translation becomes a baseline task. The challenges in generation, now transfer to more open ended tasks. 

For close ended generation tasks like translation and summarization, the search space of the decoder is restricted: although we may have different references, generally, the way we can translate the sentences are limited by the source sentences. In this case, with good enough references, we have meaningful evaluation. 

But for open ended tasks like dialog (especially chit chat), data to text, visual story telling, the search space is exponential: we have nearly arbitrary choices of generation, they are all different from each other, yet all acceptable. With the exponentially growth of search space, it the nearly impossible to enumerate all meaningful references, making the reference-based evaluation struggling for this task. 

In the talk I gave at Interactions, I discussed how the challenges transfer from close ended generation to open ended generation, why the decoder is playing central role in this task, and what are the evaluation considerations when matching based evaluation is no longer reliable. 

Here is a [link](https://francix.github.io/blog/yaofu_NLG.pdf) to the slides. 
