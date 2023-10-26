![](images/cover_4.jpeg)
*Blue Hours Seattle. 2022*

---


[Google Scholar](https://scholar.google.com/citations?user=liSP4cEAAAAJ&hl=en) / [Github](https://github.com/FranxYao) / [Twitter](https://twitter.com/Francis_YAO_) / [LinkedIn](https://www.linkedin.com/in/yao-fu-281847b5/) / [Blog](https://yaofu.notion.site/Yao-Fu-s-Blog-b536c3d6912149a395931f1e871370db) / [CV](cv.pdf)

Yao Fu 符尧. yao.fu@ed.ac.uk

I am a Ph.D. student at the University of Edinburgh (2020-) with professor [Mirella Lapata](https://homepages.inf.ed.ac.uk/mlap/).
I finished my M.S. at Columbia University (2018-2020) with professor [John Cunningham](https://stat.columbia.edu/~cunningham/) and my B.S. at Peking University (2013-2018) with professor [Yansong Feng](https://sites.google.com/site/ysfeng/home). 
Before Ph.D., I spent great time visiting professor [Alexander Rush](http://rush-nlp.com/) at Cornell Tech (2019-2020). 

I study large-scale generative models for human language.

My research objective is to make large language models the next generation computational platforms and build a language model based application ecosystem together with the community. I am broadly interested in the following topics: 
* Scaling: data composition, long context, efficiency, science of language modeling
* Reasoning: coding, agent, chain-of-thought, learning from feedback

I am expected to graduate in Dec 2023 and will be joining Google DeepMind in Mountain View as a full-time research scientist. 

-----
## Experiences
### Academia
* 2020 - 2023. Ph.D. at University of Edinburgh
* 2018 - 2020. M.S. at Columbia University
* 2013 - 2018. B.S. at Peking University

### Industry
* Jun - Sep 2023. MIT-IBM Waston AI Lab. Research Intern on Training Large Language Models
* Jul - Dec 2022. Allen Institute for AI. Research Intern on Language Model Reasoning
* Jan - Oct 2020. Alibaba DAMO Academy. Research Intern on Latent Variable Models
* May - Sep 2019. Tencent AI Lab. Research Intern on Structured Prediction
* Jan - Aug 2018. Bytedance AI Lab. Research Intern on Language Generation

-----
## Research in Language Models

* [Blog Post 2022] _How does GPT Obtain its Ability? Tracing  Emergent Abilities of Language Models to their Sources_ [[notion](https://yaofu.notion.site/How-does-GPT-Obtain-its-Ability-Tracing-Emergent-Abilities-of-Language-Models-to-their-Sources-b9a57ac0fcf74f30a1ab9e3e36fa1dc1)]
  * __Yao Fu__, Hao Peng and Tushar Khot
  * Analysing sources of emergent abilities of Large Language Models from first principle.
  * [Hacker News](https://news.ycombinator.com/front?day=2022-12-15) top 3 trending.

* [Blog Post 2023]. _Towards Complex Reasoning: the Polaris of Large Language Models_ [[notion](https://yaofu.notion.site/Towards-Complex-Reasoning-the-Polaris-of-Large-Language-Models-c2b4a51355b44764975f88e6a42d4e75)]
  * __Yao Fu__
  * A roadmap towards building language models of strong reasoning capabilties. Covers the full development stages: pretraining, continue training, supervised finetuning, reinforcemeng learning, chain-of-thought prompting, and evaluation.
 
* [Arxiv 2023] _Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback_ [[code](https://github.com/FranxYao/GPT-Bargaining)][[paper](https://arxiv.org/abs/2305.10142)]
  * __Yao Fu__, Hao Peng, Tushar Khot, and Mirella Lapata
  * Two language models negotiate with each other and continuously improve their negotiation strategies by multi-round game playing and iterative in-context learning from AI feedback. 

* [ICML 2023] Oral. _Specializing Smaller Language Models towards Multi-Step Reasoning_. [[paper](https://arxiv.org/abs/2301.12726)][[Code](https://github.com/FranxYao/FlanT5-CoT-Specialization)]
  * __Yao Fu__, Hao Peng, Litu Ou, Ashish Sabharwal, and Tushar Khot 
  * Trading language model's generic ability for specialized math chain-of-thought ability. 

* [ICLR 2023] _Complexity-Based Prompting for Multi-Step Reasoning_. [[paper](https://openreview.net/forum?id=yf1icZHC-l9)][[code](https://github.com/FranxYao/chain-of-thought-hub)]
  * __Yao Fu__, Hao Peng, Ashish Sabharwal, Peter Clark and Tushar Khot 
  * State-of-the-art reasoning performance on math word problems by prompting GPT3 with instances of complex reasoning chains.

* [ICLR 2023] _Decomposed Prompting: A Modular Approach for Solving Complex Tasks_. [[paper](https://arxiv.org/abs/2210.02406)][[code](https://github.com/allenai/DecomP)]
  * Tushar Khot, Harsh Trivedi, Matthew Finlayson, __Yao Fu__, Kyle Richardson, Peter Clark and Ashish Sabharwal
  * Decomposing complex task into simpler sub-tasks then solve each of them by prompting language models. 

* [Opensource] _ChatArena: Multi-Agent Language Game Environments for Large Language Models_ [[GitHub](https://github.com/chatarena/chatarena)]
  * Yuxiang Wu, Zhengyao Jiang, Akbir Khan, __Yao Fu__, Laura Ruis, Edward Grefenstette, and Tim Rocktäschel
  * A library that provides multi-agent language game environments and facilitates research about autonomous LLM agents and their social interactions

* [ICML Deployable GenAI 2023] _Chain-of-thougth Hub: Measuring LLMs' Reasoning Performance_ [[GitHub](https://github.com/FranxYao/chain-of-thought-hub)][[paper](https://arxiv.org/abs/2305.17306)]
  * __Yao Fu__, Litu Ou, Mingyu Chen and Yuhao Wan
  * Benchmarking large language models' complex reasoning performance with chain-of-thought prompting

* [NeurIPS 2023] _C-Eval: A Multi-Level Multi-Discipline Chinese Evaluation Suite for Foundation Models_ [[website](https://cevalbenchmark.com/index.html)] [[GitHub](https://github.com/SJTU-LIT/ceval)] [[paper](http://arxiv.org/abs/2305.08322)]
  * Yuzhen Huang*, Yuzhuo Bai*, Zhihao Zhu, Junlei Zhang, Jinghan Zhang, Tangjun Su, Junteng Liu, Chuancheng Lv, Yikai Zhang, Jiayi Lei, **Yao Fu**, Maosong Sun, Junxian He
  * A evaluation suite consisting of 52 subjects of STEM/ Social science/ Humanity/ Other testing language models' Chinese ability (knowledge and reasoning) 

-----
## Early reseach before large language models

* [ICML 2022] _Scaling Structured Inference with Randomization_. [[paper](https://arxiv.org/abs/2112.03638)][[code](https://github.com/FranxYao/RDP)]
  * __Yao Fu__, John P. Cunningham and Mirella Lapata
  *  A family of randomized dynamic programming algorithms for scaling up classical structured prediction algorithms of different inferences (partition, marginal, entropy, reparameterization) of structures (chains, trees, and general sum-product).

* [EMNLP FigLang 2022] _Just DREAM about it: Figurative Language Understanding with DREAM-FLUTE._ [[paper](https://arxiv.org/abs/2210.16407)][[code](https://github.com/allenai/dream)]
  * The Third Workshop on Figurative Language Processing. In conjunction with EMNLP 2022
  * Yuling Gu, **Yao Fu**, Valentina Pyatkin, Ian Magnusson, Bhavana Dalvi Mishra and Peter Clark
  * **Ranked top 1** in the task leaderboard. A mental model utilizing scene elaboration for understanding figurative language.

* [Arxiv 2022] _Latent Topology Induction for Understanding Contextualized Representations_. [[paper](https://arxiv.org/abs/2206.01512)]
  * __Yao Fu__ and Mirella Lapata
  * Discovering hidden geometric structures of pretrained language models by unsupervised induction of a latent network. 

* [TACL 2022] _Data-to-text Generation with Variational Sequential Planning_.[[paper](https://arxiv.org/abs/2202.13756)][[code](https://github.com/ratishsp/data2text-seq-plan-py)]
  * Ratish Puduppully, __Yao Fu__, Mirella Lapata
  * A latent planning model for generating very long document.

* [NAACL 2021] _Noisy Labeled NER with Confidence Estimation_. [[paper](https://arxiv.org/abs/2104.04318)][[code](https://github.com/liukun95/Noisy-NER-Confidence-Estimation)]
  * Kun Liu\*, __Yao Fu__\*, Chuanqi Tan, Mosha Chen, Ningyu Zhang, Songfang Huang and Sheng Gao. \*Equal contribution.
  * A confidence estimation method for estimating label noise in NER annotations and a training method based on partial marginalization according to estimated noise.

* [ICLR 2021] _Probing BERT in Hyperbolic Spaces_. [[paper](https://openreview.net/forum?id=17VnwXYZyhH)][[code](https://github.com/FranxYao/PoincareProbe)]
  * Boli Chen\*, __Yao Fu__\*, Guangwei Xu, Pengjun Xie, Chuanqi Tan, Mosha Chen, Liping Jing. \*Equal contribution. 
  * A Poincare probe for recovering hierarchical structures from contextualized representations. Applied to probing syntax and sentiment in BERT. 

* [ICLR 2021] _Prototypical Representation Learning for Relation Extraction_. [[paper](https://openreview.net/forum?id=aCgLmfhIy_f)][[code](https://github.com/Alibaba-NLP/ProtoRE)]
  * Ning Ding, Xiaobin Wang, __Yao Fu__, Guangwei Xu, Rui Wang, Pengjun Xie, Ying Shen, Fei Huang, Hai-Tao Zheng, Rui Zhang
  * A representation learning method for embedding relation prototypes on hyperspheres. Applied to supervised, semi-supervised, and few-shot relational learning. 

* [AAAI 2021] _Nested Named Entity Recognition with Partially Observed TreeCRFs_. [[paper](https://arxiv.org/abs/2012.08478)][[code](https://github.com/FranxYao/Partially-Observed-TreeCRFs)]
   *  __Yao Fu__\*, Chuanqi Tan\*, Mosha Chen, Songfang Huang, Fei Huang. \*Equal contribution. 
   * A Masked Inside algorithm for efficient partial marginalization of TreeCRFs. Applied to Nested NER.

* [NeurIPS 2020] _Latent Template Induction with Gumbel-CRFs_. [[paper](https://arxiv.org/abs/2011.14244)][[code](https://github.com/FranxYao/Gumbel-CRF)]
   * __Yao Fu__, Chuanqi Tan, Mosha Chen, Bin Bi, Yansong Feng and Alexander Rush. 
   * A Gumbel-FFBS algorithm for reparameterizing and relaxing CRFs. Applied to controllable text generation with latent templates.

* [NeurIPS 2019] _Paraphrase Generation with Latent Bag of Words_. [[paper](https://arxiv.org/abs/2001.01941)][[code](https://github.com/FranxYao/dgm_latent_bow)]
   * **Yao Fu**, Yansong Feng and John Cunningham. 
   * A differentiable planning and realization model with latent bag of words by Gumbel-topK reparameterization. Applied to paraphrase generation.

* [INLG 2019] _Rethinking Text Attribute Transfer: A Lexical Analysis_. [[paper](https://arxiv.org/abs/1909.12335)][[code](https://github.com/FranxYao/pivot_analysis)]
   * **Yao Fu**, Hao Zhou, Jiaze Chen and Lei Li. 
   * A series of text mining algorithms for discovering words with strong influence on classification. Applied to analysing text attribute transfer models. 

* [NAACL 2018] _Natural Answer Generation with Heterogeneous Memory_. [[paper](https://www.aclweb.org/anthology/N18-1017/)]
   * **Yao Fu** and Yansong Feng. 
   * An attention mechanism fusing information from different source of knowledge. Applied to answer sentence generation.

-----
## Teaching 
* University of Edinburgh. Natural Language Understanding. 2023 Spring. 
  * Teaching Assistant. Tought by Alexandra Birch, Frank Keller, and Mirela Lapata.
* Peking University. Empirical Methods for Natural Language Processing. 2022 Spring. 
  * Guest lecture on Text Generation. Tought by Yansong Feng.
* University of Edinburgh. Natural Language Understanding. 2022 Spring. 
  * Teaching Assistant. Tought by Alexandra Birch, Frank Keller, and Laura Perez.
* University of Edinburgh. [Probabilistic Modeling and Reasoning](http://www.inf.ed.ac.uk/teaching/courses/pmr/21-22/). 2022 Spring. 
  * Teaching Assistant. Tought by Michael Gutmann.
* Peking University. Empirical Methods for Natural Language Processing. 2021 Spring. 
  * Guest lecture on Text Generation. Tought by Yansong Feng.
* Alibaba DAMO Academy. Advanced Probabilistic Machine Learning Seminar. 2020 Spring. 
  * Instructor. 
* Columbia University. [COMS 4995 Applied Machine Learning](http://www.cs.columbia.edu/~amueller/comsw4995s19/), 2019 Spring.
  * Course Assistant. Tought by Andreas Muller. 




