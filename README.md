# Must-Read AI papers
A collections of must-read AI-related papers.

I read a lot of papers that now I think I should keep track of them. In this list, I list papers that I think are important in AI/ML/DL (and even other topics).

Disclaimer: the list is totally opinion-based and does not mean "you should read X and should not read Y". Mostly, the papers are rated based on the idea and impact rather than the SOTA leaderboard and the conference/journal they are published in. Yes, number of citations is not rated.

Note: the year is noted as the lastest version on arXiv/OpenReview.

**SUGGESTIONS ARE WELCOME**. Create a pull request, issue, or drop me a message on LinkedIn or email (link on my main profile). Note that I do not promote papers, so I will not response to messages like "Hey my method is novel, can you add it?". I am open to discussions and collaborations.

## AI/ML/DL Topics
- [Deep Reinforcement Learning that Matters](https://arxiv.org/abs/1709.06560) (Henderson et al., 2019): an important paper in RL. It compares algorithms using multiple seeds (I mean, *multiple*), and gives advices how to conduct RL research and experiments.
- [Implementation Matters in Deep RL: A Case Study on PPO and TRPO](https://openreview.net/forum?id=r1etN1rtPB) (Engstorm et al., 2020): a study how code-level optimization in deep RL can significantly change results.
- [How Many Random Seeds? Statistical Power Analysis in Deep Reinforcement Learning Experiments](https://arxiv.org/abs/1806.08295) (Colas et al., 2018): how many seeds you use to express statistical significance in RL? 5? 10? 20? This paper explains why, from a statistical view.
- [RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864) (Su et al., 2021): a rotary positional encoding technique that researchers at EleutherAI found a [significant improvement in performance](https://blog.eleuther.ai/rotary-embeddings/).
- [On the Origin of Deep Learning](https://arxiv.org/abs/1702.07800) (Wang and Raj, 2017): ever wonder when, why and how DL emerges? This one got you covered!
- [Co-Mixup: Saliency Guided Joint Mixup with Supermodular Diversity](https://openreview.net/forum?id=gvxJzw8kW4b) (Kim et al., 2021): a novel mix-up technique that creates new data in batches instead of a pair of images.
- [Combining Ensembles and Data Augmentation Can Harm Your Calibration](https://openreview.net/forum?id=g11CZSghXyY) (Wen et al., 2021): experiments show that combining ensembles and augmentations can decrease your performance.
- [What Matters In On-Policy Reinforcement Learning? A Large-Scale Empirical Study](https://arxiv.org/abs/2006.05990) (Andrychowicz et al., 2020): advices about how to choose hyperparameters for PPO on continuous control task. Although useful, but I think this paper is limited to the tasks it evaluates.
- [Action Space Shaping in Deep Reinforcement Learning](https://arxiv.org/abs/2004.00980) (Kanervisto et al., 2020): how to shape your action space? Should it `(1, 6)` or `(2, 3)` or `(3, 2)`?
- [A Closer Look at Invalid Action Masking in Policy Gradient Algorithms](https://arxiv.org/abs/2006.14171) (Huang and Ontañón, 2020): usually we give a big negative reward if the agent makes an invalid action (for example, a chess piece moves left and gets out of the board), but that is totally a naive workaround: say, doing so may make the agent thinks that action is very bad (moving left) instead of invalid (out of the board).
- [An Empirical Model of Large-Batch Training](https://arxiv.org/pdf/1812.06162.pdf) (also [blog](https://openai.com/blog/science-of-ai/)) (McCandlish et al., 2018): a paper that surveys and explains large batch size training in AI. Batch size speeds up training and reduces variance, so this is a must-read one!
- [Writing Great Reward Functions - Bonsai](https://www.youtube.com/watch?v=0R3PnJEisqk) (Bonsai, 2017): reward function plays an imporant role on how the agent learns. Be careful what you give them!
- Critizing Neural Architecture Search (NAS) and explaining why Randomness just performs equally good.
  - [Random Search and Reproducibility for Neural Architecture Search](https://arxiv.org/abs/1902.07638) (Li and Talwalkar, 2019), 
  - [Pitfalls in Machine Learning Research: Reexamining the Development Cycle](http://proceedings.mlr.press/v137/biderman20a/biderman20a.pdf) (Biderman and Scheirer, 2020), 
  - [Local Search is a Remarkably Strong Baseline for Neural Architecture Search](https://arxiv.org/abs/2004.08996) (Ottelander et al., 2020)
  

## Blog posts and others
- [Competing in the Obstacle Tower Challenge](https://blog.aqnichol.com/2019/07/24/competing-in-the-obstacle-tower-challenge/): A very interesting blog that tells why entropy should not be included in the loss calculation, why RNN-based network fails in RL, and more!
- [Deep Reinforcement Learning Doesn't Work Yet](https://www.alexirpan.com/2018/02/14/rl-hard.html): why RL is so *damn* hard? This blog explains possible reasons why RL does not work yet, despite breaking news about RL in recent years.
- [Approximating KL Divergence](http://joschu.net/blog/kl-approx.html): a short blog explains why in RL, approx KL divergence is enough, instead of calculating true KL.
- [Machine Learning in Physics resources](https://www.reddit.com/r/MachineLearning/comments/nbdoc6/p_machine_learning_in_physics/gxytad4?utm_source=share&utm_medium=web2x&context=3) (ChrisRackauckas): an extremely detailed collection of resources about ML in Physics. I am overwhelmed by his effort typing this answer!
- [A collection of failed RL algorithms](https://docs.google.com/spreadsheets/d/e/2PACX-1vRPiprOaC3HsCf5Tuum8bRfzYUiKLRqJmbOoC-32JorNdfyTiRRsR7Ea5eWtvsWzuxo8bjOxCG84dAg/pubhtml)

## Other Topics
- [BOLA: Near-Optimal Bitrate Adaptation for Online Videos](https://arxiv.org/pdf/1601.06748.pdf): determine the near-optimal video quality based on your network speed!
- [How to Design for Color Blindness](https://www.getfeedback.com/resources/ux/how-to-design-for-color-blindness/)
