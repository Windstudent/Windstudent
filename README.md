# Lu Zhang

Audio Algorithm Expert at [XG Tech](https://www.xg.auto/).

I work on speech enhancement, audio source separation, and in-vehicle spatial audio.

Ph.D. in Electronic Science and Technology from Harbin Institute of Technology. I take audio algorithms from research to mass production across ai speech front-ends, music source separation, immersive cabin sound, and on-device deployment on HiFi DSP, ARM, NPU, and Vision DSP. 

- Google Scholar: [Profile](https://scholar.google.com/citations?user=IUB7vgYAAAAJ&hl=en)
- Email: [zhanglu_wind@163.com](mailto:zhanglu_wind@163.com)
- GitHub: [@Windstudent](https://github.com/Windstudent)

## Current Focus

- Speech enhancement and audio source separation
- In-vehicle 3D spatial audio and surround upmixing
- On-device model design, quantization, and heterogeneous deployment
- Cabin sound systems from algorithm research to vehicle delivery

## Experience

- `2025.07 - present`: Audio Algorithm Expert, XG Tech
- `2025.03 - 2025.07`: Senior Engineer, Advanced Acoustics, Geely Automobile Research Institute
- `2022.06 - 2025.03`: Senior Algorithm Engineer, NIO
- `2021.02 - 2021.08`: Audio Algorithm Researcher (Intern), Kuaishou

## Education

- `2018.09 - 2022.03`: Ph.D., Electronic Science and Technology, Harbin Institute of Technology
- `2016.09 - 2018.07`: M.Eng., Integrated Circuit Engineering, Harbin Institute of Technology
- `2012.09 - 2016.07`: B.Eng., Electronic Science and Technology, Harbin Institute of Technology

## Selected Work

- **Streaming music stem separation.** Designed streaming Transformer and U-Net separators for real-time playback, trained on about 50,000 songs (~3,000 hours). Under a streaming constraint, quality approaches offline models such as BS-RoFormer, with a latency of 150–300 ms. Deployed on a heterogeneous cockpit SoC: ARM Core for front- and back-end processing, NPU Core for the Transformer inference, and DSP Core for the U-Net inference.
- **Immersive 3D upmixing.** Built a cabin upmixer from direct/ambient separation, VBAP imaging, and AI-assisted FDN reverberation, lifting stereo to 5.1, 5.1.4, 7.1, and 7.1.4. Engineered on a HiFi-5 DSP at 48 kHz, with 10 ms frames and 30 ms algorithmic latency.
- **Automotive Audio Effects System Delivery at NIO.** Built the in-house cabin audio algorithm team from scratch and delivered the Firefly sound system, including the Dolby 7.1 / 7.1.4 tuning architecture and Qualcomm ADSP deployment.
- **In-cabin speech front-end.** Developed In-Car Communication and microphone-free karaoke pickup, using a lightweight denoiser, deployed on the Qualcomm 8295 ARM core.
- **Multi-task source separation.** At Kuaishou, proposed Complex-MTASSNet, a two-stage multi-task source separation model for speech, music, and background, and released the [code](https://github.com/Windstudent/Complex-MTASSNet).

## Selected Publications

- [PhaseDCN: A Phase-Enhanced Dual-Path Dilated Convolutional Network for Single-Channel Speech Enhancement](https://ieeexplore.ieee.org/document/9465679) (IEEE/ACM TASLP, 2021)
- [Multi-Scale TCN: Exploring Better Temporal DNN Model for Causal Speech Enhancement](https://www.isca-archive.org/interspeech_2020/zhang20x_interspeech.html) (INTERSPEECH, 2020)
- [Multi-Task Audio Source Separation](https://arxiv.org/abs/2107.06467) (ASRU, 2021) · [Code](https://github.com/Windstudent/Complex-MTASSNet)
- [FB-MSTCN: A Full-Band Single-Channel Speech Enhancement Method Based on Multi-Scale Temporal Convolutional Network](https://arxiv.org/html/2203.07684v1) (ICASSP, 2022)
- [Lite-RTSE: Exploring a Cost-Effective Lite DNN Model for Real-Time Speech Enhancement in RTC Scenarios](https://ieeexplore.ieee.org/document/10308952) (IEEE Signal Processing Letters, 2023) · [Demo](https://xingweiliang.github.io/Lite-RTSE.html)

## Awards

- 3rd place, Microsoft Deep Noise Suppression Challenge 4 (DNS-4, 2022), with FB-MSTCN
