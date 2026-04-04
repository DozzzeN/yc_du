---
title: "Backdoor-Resistant Public Data Integrity Verification Scheme Based on Smart Contracts"
collection: publications
category: manuscripts
permalink: /publication/2023-06-14-backdoor-resistant-data-integrity
excerpt: "Proposes ASSIST, a smart contract-based integrity verification scheme that resists hardware backdoors and optimizes storage via encrypted deduplication."
date: 2023-06-14
venue: "IEEE Internet of Things Journal"
doi: "10.1109/JIOT.2023.3285939"
paperurl: "https://ieeexplore.ieee.org/document/10153425"
citation: "Shanshan Li, Chunxiang Xu, Yuan Zhang, Yicong Du, Anjia Yang, Xinsheng Wen, Kefei Chen. Backdoor-Resistant Public Data Integrity Verification Scheme Based on Smart Contracts. IEEE Internet of Things Journal. 2023: 10(16), 14269-14284."
---
### Contributions & Highlights
* **Timely Integrity Monitoring:** Introduced a novel "whistleblower" entity to periodically monitor blockchain-recorded verification results. This ensures that users are promptly notified of any data corruption or loss, overcoming the notification delays inherent in traditional arbitration mechanisms.
* **Storage-Efficient Confidentiality:** Leveraged **Message-Locked Encryption (MLE)** to enable secure data deduplication. This allows different users to generate identical ciphertexts for the same underlying data, significantly reducing redundant storage costs for cloud servers without compromising data privacy.
* **Hardware Backdoor Defense:** Deployed a **Cryptographic Reverse Firewall (CRF)** to re-randomize interactive messages between user devices and the external network. This mechanism effectively prevents secret exfiltration and ensures scheme security even when user hardware is poorly designed or intentionally compromised with backdoors.
