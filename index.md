![](images/cover_4.jpeg)
*Blue Hours Seattle. 2022*

---


[Google Scholar](https://scholar.google.com/citations?user=liSP4cEAAAAJ&hl=en) / [Github](https://github.com/FranxYao) / [Twitter](https://twitter.com/Francis_YAO_) / [LinkedIn](https://www.linkedin.com/in/yao-fu-281847b5/) / [Blog](https://yaofu.notion.site/Yao-Fu-s-Blog-b536c3d6912149a395931f1e871370db)

Yao Fu 符尧. yao.fu@ed.ac.uk

I am a Ph.D. student at the University of Edinburgh (2020-) with professor [Mirella Lapata](https://homepages.inf.ed.ac.uk/mlap/).
I finished my M.S. at Columbia University (2018-2020) with professor [John Cunningham](https://stat.columbia.edu/~cunningham/) and my B.S. at Peking University (2013-2018) with professor [Yansong Feng](https://sites.google.com/site/ysfeng/home). 
Before Ph.D., I spent great time visiting professor [Alexander Rush](http://rush-nlp.com/) at Cornell Tech (2019-2020). 

I study large-scale generative models for human language.

My research objective is to make large language models the next generation computational platforms and build a language model based application ecosystem together with the community. I am broadly interested in the following topics: 
* **Science driven scaling**: to pursue scientific principles bebind scaling and use them to guide next-generation model development, where the subareas include data engineering, long context, efficiency, and science of language models
* **Reasoning as agents**: to study how deployed language models reason over complex problems and environment, where the subareas include coding, multi-agent games, chain-of-thought, and learning from X feedback

-----
## Featured Research

* [Arxiv 2024] _Challenges in Deploying Long-Context Transformers: A Theoretical Peak Performance Analysis_ [[paper](https://arxiv.org/abs/2405.08944)][[Twitter/X](https://twitter.com/Francis_YAO_/status/1791013218707439664)]
  * __Yao Fu__
  * A concurrent programming framework for analyzing understanding the serving cost of long-context transformers: concurrency, prefilling, decoding and context switching.
  * Identifying lossless compression of KV cache is the number one challenge for reducing the cost of 1M to be as cheap as 4K.

* [Arxiv 2024] _Retrieval Head Mechanistically Explains Long-Context Factuality_ [[code](https://github.com/nightdessert/Retrieval_Head)][[paper](https://arxiv.org/pdf/2404.15574)][[Twitter/X](https://twitter.com/Francis_YAO_/status/1783446286479286700)]
  * Wenhao Wu, Yizhong Wang, Guangxuan Xiao, Hao Peng and __Yao Fu__
  * A systematic investigation upon a wide range of models reveals the existance retrieval heads, a special type of attention heads accounting for long-context factuality.

* [ICML 2024] _Data Engineering for Scaling Language Models to 128K Context_  [[code](https://github.com/FranxYao/Long-Context-Data-Engineering)][[Paper](https://arxiv.org/abs/2402.10171)][[Twitter/X](https://twitter.com/Francis_YAO_/status/1759986097365627054)]
  * __Yao Fu__, Rameswar Panda, Xinyao Niu, Xiang Yue, Hannaneh Hajishirzi, Yoon Kim and Hao Peng
  * An effective and affordable recipe for training language models to 128K context, the key is to continue pretrain the full-attention model on 5B per-source length-upsampled data.
  * The first open-sourced model matching GPT-4 128K performance on Needle-in-a-Haystack.
 
* [Arxiv 2023] _Improving Language Model Negotiation with Self-Play and In-Context Learning from AI Feedback_ [[code](https://github.com/FranxYao/GPT-Bargaining)][[paper](https://arxiv.org/abs/2305.10142)]
  * __Yao Fu__, Hao Peng, Tushar Khot, and Mirella Lapata
  * Two language models negotiate with each other and continuously improve their negotiation strategies by multi-round game playing and iterative in-context learning from AI feedback. 

* [ICML 2023] Oral. _Specializing Smaller Language Models towards Multi-Step Reasoning_. [[paper](https://arxiv.org/abs/2301.12726)][[Code](https://github.com/FranxYao/FlanT5-CoT-Specialization)]
  * __Yao Fu__, Hao Peng, Litu Ou, Ashish Sabharwal, and Tushar Khot 
  * Trading language model's generic ability for specialized math chain-of-thought ability. 

* [ICLR 2023] _Complexity-Based Prompting for Multi-Step Reasoning_. [[paper](https://openreview.net/forum?id=yf1icZHC-l9)][[code](https://github.com/FranxYao/chain-of-thought-hub)]
  * __Yao Fu__, Hao Peng, Ashish Sabharwal, Peter Clark and Tushar Khot 
  * State-of-the-art reasoning performance on math word problems by prompting GPT3 with instances of complex reasoning chains.

-----
## Featured Blog Posts
* [Apr 2024]. _Llama 3 Opens the Second Chapter of the Game of Scale_ [[notion](https://yaofu.notion.site/Apr-2024-Llama-3-Opens-the-Second-Chapter-of-the-Game-of-Scale-efff1c0c185f4008af673b78faf83b61)]
  * __Yao Fu__
  * Llama 3 marks open-source models reaching GPT-4 performance. Further text scaling is likely to be saturated. Future directions of scaling may focus on video-language models and reinforcement learning from X feedback.
 
* [Dec 2023]. _Towards 100x Speedup: Full Stack Transformer Inference Optimization_ [[notion](https://yaofu.notion.site/Towards-100x-Speedup-Full-Stack-Transformer-Inference-Optimization-43124c3688e14cffaf2f1d6cbdf26c6c)]
  * __Yao Fu__
  * From hardware specs like A100 memory hierarchy, to MLSys methods like FlashAttention and vLLM, to model architectures like Mixture of Experts, to decoding algorithms like Speculative Decoding and its variants, we discuss full-stack transformer inference optimization.

* [Jun 2023]. _A Stage Review of Instruction Tuning_ [[notion](https://yaofu.notion.site/June-2023-A-Stage-Review-of-Instruction-Tuning-f59dbfc36e2d4e12a33443bd6b2012c2)]
  * __Yao Fu__
  * A review of the development of LLaMA-based models after the release of ChatGPT and discusses the next challenges of Instruction Tuning.

* [May 2023]. _Towards Complex Reasoning: the Polaris of Large Language Models_ [[notion](https://yaofu.notion.site/Towards-Complex-Reasoning-the-Polaris-of-Large-Language-Models-c2b4a51355b44764975f88e6a42d4e75)]
  * __Yao Fu__
  * A roadmap towards building language models of strong reasoning capabilties. Covers the full development stages: pretraining, continue training, supervised finetuning, reinforcemeng learning, chain-of-thought prompting, and evaluation.

* [Dec 2022] _How does GPT Obtain its Ability? Tracing  Emergent Abilities of Language Models to their Sources_ [[notion](https://yaofu.notion.site/How-does-GPT-Obtain-its-Ability-Tracing-Emergent-Abilities-of-Language-Models-to-their-Sources-b9a57ac0fcf74f30a1ab9e3e36fa1dc1)]
  * __Yao Fu__, Hao Peng and Tushar Khot
  * Analysing sources of emergent abilities of Large Language Models from first principle.
  * [Hacker News](https://news.ycombinator.com/front?day=2022-12-15) top 3 trending.


 



