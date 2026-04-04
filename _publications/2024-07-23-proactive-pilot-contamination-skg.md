---
title: "Physical Layer Secret Key Generation Leveraging Proactive Pilot Contamination"
collection: publications
category: manuscripts
permalink: /publication/2024-07-23-proactive-pilot-contamination-skg
excerpt: "Proposes a proactive pilot contamination strategy to adaptively shape channel responses, significantly improving quantization consistency in secret key generation."
date: 2024-07-23
venue: "IEEE International Conference on Distributed Computing Systems (IEEE ICDCS)"
paperurl: "https://ieeexplore.ieee.org/document/10631067"
citation: "Limin Liu, Hongbo Liu, Yicong Du, Ziyu Shao, Haomiao Yang, Yanzhi Ren. Physical Layer Secret Key Generation Leveraging Proactive Pilot Contamination. IEEE International Conference on Distributed Computing Systems (ICDCS), 2024: 1272-1282."
---
### Contributions & Highlights
* **Proactive Channel Adaptation:** Shifted from passive channel observation to a **proactive pilot contamination** paradigm. By introducing slight, controlled perturbations to pilot signals, the system adaptively shapes channel responses to align with target quantization strategies, drastically reducing key mismatch probabilities.
* **Adaptive Consistency & Security:** Developed an **adaptive pilot manipulation** mechanism to keep channel measurements away from quantization thresholds. To prevent eavesdroppers from inferring keys via pilot monitoring, a **random cross-threshold mechanism** was integrated to decouple pilot variations from quantization results.
* **Communication-Preserving Design:** Engineered a reliable **Long Training Sequence (LTS) modification** mechanism that adaptively adjusts pilot scales. This ensures high-performance secret key generation without degrading the correct reception or decoding of standard data frames.
