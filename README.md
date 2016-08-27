# Deep Reinforcement Learning survey
This paper list is a bit different from others. I'll put some opinion and summary on it. However, to understand the whole paper, you still have to read it by yourself!   
Surely, any pull request or discussion are welcomed!

## Outline
- [Papers](https://github.com/andrewliao11/Deep-Reinforcement-Learning-Survey#papers)
- [Generative Model](https://github.com/andrewliao11/Deep-Reinforcement-Learning-Survey#generative-model)
- [Open Source](https://github.com/andrewliao11/Deep-Reinforcement-Learning-Survey#open-source)
- [Courses](https://github.com/andrewliao11/Deep-Reinforcement-Learning-Survey#course)
  - Python users
  - Lua users
- [Textbook](https://github.com/andrewliao11/Deep-Reinforcement-Learning-Survey#textbook)
- [Misc](https://github.com/andrewliao11/Deep-Reinforcement-Learning-Survey#misc)

## Open Source
### Python users[Tensorflow, Theano]
  - [OpenAI gym](https://gym.openai.com/)
    - RL **benchmarking** toolkit
    - Provide environment and evaluation metrics
  - [Keras](https://github.com/matthiasplappert/keras-rl)
    - Fully compatible with OpenAI
    - Some algorithms have been implement(e.g DQN, DDQN, DDPG, CDQN)
  - [TensorLayer](https://github.com/zsdonghao/tensorlayer)
    - Built on the top of Google TensorFlow
  - [rllab](https://github.com/rllab/rllab)
    - Fully compatible with OpenAI 
    - Continuous control tasks 
    - Nice to implement new algorothms
    - [Benchmarking Deep Reinforcement Learning for Continuous Control](https://arxiv.org/abs/1604.06778)
  - [KEras](https://github.com/osh/kerlym)
    - Built on keras
    - Fully compatible with OpenAI
    - Host a handful of agent of reinforcement learning agents
    - [Deep Reinforcement Learning Radio Control and Signal Detection with KeRLym, a Gym RL Agent](http://arxiv.org/abs/1605.09221)
  - [Deep Reinforcement Learning in TensorFlow](https://github.com/carpedm20/deep-rl-tensorflow)
    - Implemented by @carpedm20
    - Having some basic reinforcement algorothms

### Lua users[Torch]
  - [rltorch](https://github.com/ludc/rltorch), basic reinforcement learning package
  - [awesome-torch for reinforcement learning](https://github.com/carpedm20/awesome-torch#reinforcement-learning)
    - List of open sources for rerinforcement learning 

## Course
  - [CS 294: Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/#related-materials)
      - Instructors: John Schulman, Pieter Abbeel
  - [UC Berkeley CS188 Intro to AI](http://ai.berkeley.edu/home.html)
      - [2013 Spring video](https://www.youtube.com/user/CS188Spring2013) on youtube   
  - [Advanced Topics: RL](http://www0.cs.ucl.ac.uk/staff/d.silver/web/Teaching.html)
      - Instructors: David Silver
  - [Deep learning videoes at Oxford 2015](https://www.youtube.com/playlist?list=PLE6Wd9FR--EfW8dtjAuPoTuPcqmOV53Fu)
      - Instructors: Nando de Freitas
      - lecture 15, 16 are strongly related to reinforcement learning
  
## Textbook
  - [Foundations_of_Machine_Learning](http://www.cs.nyu.edu/~mohri/mlbook/)
      - chapter 14: Reinforcement learning  
   
  
## Misc
  - [A collection of Deep Learning resources](http://www.jeremydjacksonphd.com/category/deep-learning/)
  - [Deep Reinforcement Learning: Pong from Pixels](http://karpathy.github.io/2016/05/31/rl/), from Andrej Karpathy' blog
      - policy gradient (very clear!)
  - [Guest Post (Part I): Demystifying Deep Reinforcement Learning](https://www.nervanasys.com/demystifying-deep-reinforcement-learning/)
  - [Reinforcement Learning and Control](http://cs229.stanford.edu/notes/cs229-notes12.pdf), lecture from Andrew Ng
      - basic reinforcement learning 
      - continuous state MDPs
  - [DEEP REINFORCEMENT LEARNING](https://deepmind.com/blog), from David Silver, Google DeepMind
      - briefly discuss some work done by deepmind
  - [What are the benefits of actor/critic framework in reinforcement learning?](https://www.quora.com/What-are-the-benefits-of-actor-critic-framework-in-reinforcement-learning)
      - Clearly expain the advantages of actor/critic 


