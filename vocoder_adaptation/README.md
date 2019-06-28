
### Title
- Speaker-adaptive neural vocoders for parametric speech synthesis systems
### Authors
- Eunwoo Song, Jinseob Kim, Kyungguen Byun, Hong-Goo Kang
### Abstract
- This paper proposes speaker-adaptive neural vocoders for statistical parametric speech synthesis (SPSS) systems. Recently proposed WaveNet-based neural vocoding systems successfully generate a time sequence of speech signal with an autoregressive framework. However, it remains a challenge to build high-quality speech synthesis systems when the amount of a target speaker's training data is insufficient. To generate more natural speech signals with the constraint of limited training data, we propose a speaker adaptation task with an effective variation of neural vocoding models. In the proposed method, a speaker-independent training method is applied to capture universal attributes embedded in multiple speakers, and the trained model is then optimized to represent the specific characteristics of the target speaker. Experimental results verify that the proposed SPSS systems with speaker-adaptive neural vocoders outperform those with traditional source-filter model-based vocoders and those with WaveNet vocoders, trained either speaker-dependently or speaker-independently.

---

![fig](img/fig1.png)

---

- Demo page: [https://sewplay.github.io/demos/vocoder_adaptation](https://sewplay.github.io/demos/vocoder_adaptation/)
- Preprinted version:  [arXiv 1811.03311](https://arxiv.org/abs/1811.03311/)
