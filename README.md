# Must-Read AI papers
A collections of must-read AI-related papers.

I read a lot of papers that now I think I should keep track of them. In this list, I list papers that I think are important in AI/ML/DL (and even other topics).

Disclaimer: the list is totally opinion-based and does not mean "you should read X and should not read Y". Mostly, the papers are rated based on the idea and impact rather than the SOTA leaderboard and the conference/journal they are published in. Yes, number of citations is not rated.

Note: the year is noted as the lastest version on arXiv/OpenReview.

## AI/ML/DL Topics
- [Deep Reinforcement Learning that Matters](https://arxiv.org/abs/1709.06560) (Henderson et al., 2019): an important paper in RL. It compares algorithms using multiple seeds (I mean, *multiple*), and gives advices how to conduct RL research and experiments.
- [How Many Random Seeds? Statistical Power Analysis in Deep Reinforcement Learning Experiments](https://arxiv.org/abs/1806.08295) (Colas et al., 2018): how many seeds you use to express statistical significance in RL? 5? 10? 20? This paper explains why, from a statistical view.
- [RoFormer: Enhanced Transformer with Rotary Position Embedding](https://arxiv.org/abs/2104.09864) (Su et al., 2021): a rotary positional encoding technique that researchers at EleutherAI found a [significant improvement in performance](https://blog.eleuther.ai/rotary-embeddings/).
- [On the Origin of Deep Learning](https://arxiv.org/abs/1702.07800) (Wang and Raj, 2017): ever wonder when, why and how DL emerges? This one got you covered!
- [Co-Mixup: Saliency Guided Joint Mixup with Supermodular Diversity](https://openreview.net/forum?id=gvxJzw8kW4b) (Kim et al., 2021): a novel mix-up technique that creates new data in batches instead of a pair of images.
- [Combining Ensembles and Data Augmentation Can Harm Your Calibration](https://openreview.net/forum?id=g11CZSghXyY) (Wen et al., 2021): experiments show that combining ensembles and augmentations can decrease your performance.
- [What Matters In On-Policy Reinforcement Learning? A Large-Scale Empirical Study](https://arxiv.org/abs/2006.05990) (Andrychowicz et al., 2020): advices about how to choose hyperparameters for PPO on continuous control task. Although useful, but I think this paper is limited to the tasks it evaluates.
- [Action Space Shaping in Deep Reinforcement Learning](https://arxiv.org/abs/2004.00980) (Kanervisto et al., 2020): how to shape your action space? Should it `(1, 6)` or `(2, 3)` or `(3, 2)`?
- [A Closer Look at Invalid Action Masking in Policy Gradient Algorithms](https://arxiv.org/abs/2006.14171) (Huang and Ontañón, 2020): usually we give a big negative reward if the agent makes an invalid action (for example, a chess piece moves left and gets out of the board), but that is totally a naive workaround: say, doing so may make the agent thinks that action is very bad (moving left) instead of invalid (out of the board).


## Other Topics
- [BOLA: Near-Optimal Bitrate Adaptation for Online Videos](https://arxiv.org/pdf/1601.06748.pdf): determine the near-optimal video quality based on your network speed!
