---
title: "ArmSpy: Video-assisted PIN Inference Leveraging Keystroke-induced Arm Posture Changes"
collection: publications
category: manuscripts
permalink: /publication/2022-infocom-armspy
excerpt: "Uncovers a stealthy side-channel threat where PINs are inferred from arm posture changes captured via video, even under hand occlusion."
date: 2022-06-01
venue: "IEEE Conference on Computer Communications (IEEE INFOCOM)"
paperurl: "https://ieeexplore.ieee.org/document/9796930"
citation: "Yuefeng Chen, Yicong Du, Chunlong Xu, Yanghai Yu, Hongbo Liu, Huan Dai, Yanzhi Ren, Jiadi Yu. (2022). ArmSpy: Video-assisted PIN Inference Leveraging Keystroke-induced Arm Posture Changes. In Proceedings of the IEEE INFOCOM, 1878-1887."
---

### Contributions & Highlights
* **Novel Stealthy Side-Channel:** Uncovered a severe security vulnerability where sensitive PINs can be inferred by covertly observing a victim's back. Unlike traditional shoulder-surfing, **ArmSpy** leverages arm and elbow posture dynamics, making it effective even when the keypad is completely obstructed from view.
* **Fine-grained Posture Analysis:** Developed a sophisticated vision-based pipeline to track upper-limb trajectories. By analyzing **elbow angle variations**, the system can precisely timestamp keystroke events and localize fingertip positions relative to the keypad.
* **Spatial Correlation Modeling:** Engineered a coordinate transformation mechanism based on the constant spatial relationship between the elbow, wrist, and fingertips, enabling high-accuracy PIN reconstruction through Euclidean distance-based keystroke inference.
