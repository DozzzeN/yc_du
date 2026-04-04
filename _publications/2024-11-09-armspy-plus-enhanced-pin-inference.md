---
title: "ArmSpy++: Enhanced PIN Inference through Video-based Fine-grained Arm Posture Analysis"
collection: publications
category: manuscripts
permalink: /publication/2024-11-09-armspy-plus-enhanced-pin-inference
excerpt: "An enhanced video-assisted PIN inference attack that leverages fine-grained arm joint dynamics and typing habits to overcome hand-occlusion limitations."
date: 2024-11-09
venue: "ACM Transactions on Privacy and Security (TOPS)"
paperurl: "https://dl.acm.org/doi/10.1145/3696418"
citation: "Huan Dai, Yuefeng Chen, Yicong Du, Luping Wang, Ziyu Shao, Hongbo Liu, Yanzhi Ren, Jiadi Yu, Bo Liu. ArmSpy++: Enhanced PIN Inference through Video-based Fine-grained Arm Posture Analysis. ACM Transactions on Privacy and Security. 2024, 28(1): 1-26."
---
### Contributions & Highlights
* **Fine-grained Feature Fusion:** Developed **ArmSpy++**, an advanced inference attack that significantly improves keystroke detection by fusing multi-dimensional features, including **keystroke-induced elbow bending**, **wrist speed variations**, and complex spatial relationships between arm joints.
* **Typing Habit & Perspective Modeling:** Engineered a robust PIN reconstruction mechanism that incorporates natural typing habits and perspective geometry. By utilizing a pre-trained **HigherHRNet** model for posture estimation, the system achieves high-fidelity inference without the need for victim-specific training.
* **High-Accuracy under Occlusion:** Demonstrated through extensive experiments that the system can achieve an average accuracy of **over 83.1% within 3 attempts**, proving that PIN security remains highly vulnerable even when the user's hand gestures are completely occluded from the attacker's line of sight.
