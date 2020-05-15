
### Title
- Improved Parallel WaveGAN with perceptually weighted spectrogram loss
### Authors
- Eunwoo Song, Ryuichi Yamamoto, Min-Jae Hwang, Jin-Seob Kim, Ohsung Kwon, Jae-Min Kim
### Abstract
- We propose a spectral-domain perceptual weighting technique for Parallel WaveGAN-based text-to-speech (TTS) systems. The recently proposed Parallel WaveGAN vocoder successfully generates waveform sequences using a fast non-autoregressive WaveNet model. By employing a generative adversarial network framework with multi-resolution short-time Fourier transform (MR-STFT) criteria, the light-weight convolutional networks can be effectively trained without any distillation process. To further improve the vocoding performance, we propose the application of frequency-dependent weighting to the MR-STFT loss function. The weighting method penalizes perceptually sensitive errors in the frequency domain which enables significant reduction of auditory noise in the synthesized speech while model complexity and inference speed remain light and fast. Perceptual listening test results demonstrate that our proposed method achieves 4.16 and 4.21 mean opinion scores for female and male Korean speakers, respectively.
---


- Demo page: [https://sewplay.github.io/demos/pwsl_wavegan](https://sewplay.github.io/demos/pwsl_wavegan/)
