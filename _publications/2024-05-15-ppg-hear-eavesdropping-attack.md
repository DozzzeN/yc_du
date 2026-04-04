---
title: "PPG-hear: A Practical Eavesdropping Attack with Photoplethysmography Sensors"
collection: publications
category: manuscripts
permalink: /publication/2024-05-15-ppg-hear-eavesdropping-attack
excerpt: "Introduces PPG-Hear, the first side-channel attack exploiting PPG sensors to covertly intercept and reconstruct human speech from nearby audio sources."
date: 2024-05-15
venue: "Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT)"
doi: "10.1145/3659603"
paperurl: "https://dl.acm.org/doi/abs/10.1145/3659603"
citation: "Yuchen Su, Shiyue Huang, Hongbo Liu, Yuefeng Chen, Yicong Du, Yan Wang, Yanzhi Ren, Yingying Chen. PPG-Hear: A Practical Eavesdropping Attack with Photoplethysmography Sensors. Proceedings of the ACM on Interactive, Mobile, Wearable and Ubiquitous Technologies (IMWUT). 2024, 8(2): 1-28."
---
### Contributions & Highlights
* **Novel Side-Channel Discovery:** Uncovered a zero-permission eavesdropping vulnerability where low-frequency **PPG measurements** on commodity wearables can covertly capture acoustic vibrations, enabling the interception of sensitive nearby conversations without being noticed.
* **Robust Signal Processing:** Developed advanced differentiation and filtering techniques to mitigate environmental and biological interference, such as **temperature drift** and **user-specific gestures**, ensuring stable speech pattern identification in the PPG spectrogram.
* **AI-Driven Speech Reconstruction:** Engineered a sophisticated reconstructor integrating a **MiniRocket-based classifier** with a **PixelGAN model**, achieving over **90% accuracy** and significantly surpassing state-of-the-art motion-sensor-based eavesdropping attacks.
