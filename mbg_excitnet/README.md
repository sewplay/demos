
### Title
- Neural text-to-speech with a modeling-by-generation excitation model
### Authors
- Eunwoo Song, Min-Jae Hwang, Ryuichi Yamamoto, Jin-Seob Kim, Ohsung Kwon, Jae-Min Kim
### Abstract
- In this paper, we propose a modeling-by-generation (MbG)-structured excitation model for a parametric text-to-speech (TTS) system. The recently proposed neural excitation vocoders successfully generates a time-sequence of speech signal by combining a vocal tract spectral filter with a WaveNet-based glottal excitation generator. However, the quality of synthesized speech is often degraded owing to the mismatch problem between the training and synthesis phases. As the vocoding model is trained without considering the effect of acoustic model front-end, the errors in estimating conditional inputs are inevitably boosted throughout the synthesis process of the vocoder back-end. To address this problem, we propose to incorporate the MbG structure into the neural excitation model as a closed-loop solution. In the proposed method, the excitation signal is extracted by the generated spectral parameters, and the WaveNet is then optimized not only to learn the target excitation's distribution, but also to compensate for the errors occurred from the acoustic model. Furthermore, as the same spectral parameters are shared in the training and synthesis steps, their mismatch condition can be significantly reduced. The experimental results verify that the proposed system provides high quality synthetic speech by achieving a mean opinion score of 4.51 within a neural TTS framework.

---

![fig](img/fig1.png)

---

- Demo page: [https://sewplay.github.io/demos/mbg_excitnet](https://sewplay.github.io/demos/mbg_excitnet/)
