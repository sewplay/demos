
### Title
- Neural text-to-speech with a modeling-by-generation excitation vocoder
### Authors
- Eunwoo Song, Min-Jae Hwang, Ryuichi Yamamoto, Jin-Seob Kim, Ohsung Kwon, Jae-Min Kim
### Abstract
- This paper proposes a modeling-by-generation (MbG) excitation vocoder for a neural text-to-speech (TTS) system. Recently proposed neural excitation vocoders can realize qualified waveform generation by combining a vocal tract filter with a WaveNet-based glottal excitation generator. However, when these vocoders are used in a TTS system, the quality of synthesized speech is often degraded owing to a mismatch between training and synthesis steps. Specifically, the vocoder is separately trained from an acoustic model front-end. Therefore, estimation errors of the acoustic model are inevitably boosted throughout the synthesis process of the vocoder back-end. To address this problem, we propose to incorporate an MbG structure into the vocoder's training process. In the proposed method, the excitation signal is extracted by the acoustic model's generated spectral parameters, and the neural vocoder is then optimized not only to learn the target excitation's distribution but also to compensate for the estimation errors occurring from the acoustic model. Furthermore, as the generated spectral parameters are shared in the training and synthesis steps, their mismatch conditions can be reduced effectively. The experimental results verify that the proposed system provides high-quality synthetic speech by achieving a mean opinion score of 4.57 within the TTS framework.
---

![fig](img/fig1.png)

---

- Demo page: [https://sewplay.github.io/demos/mbg_excitnet](https://sewplay.github.io/demos/mbg_excitnet/)
- Published in: [INTERSPEECH 2020](http://www.interspeech2020.org/)
- Preprinted version:  [arXiv 2008.00132](https://arxiv.org/abs/2008.00132)
