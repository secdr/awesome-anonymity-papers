<h1 align="center">
  Awesome Anonymity Papers
</h1>

<p align="center">
  <a href="https://github.com/secdr/awesome-anonymity-papers/blob/c3ef16841398c86a56259765c5106a82e2f43ead/LICENSE" target="_blank">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg">
  </a>
  <a href="https://github.com/GSTovey/awesome-anonymity-papers/pulls">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg">
  </a>
</p>

This repository maintains a curated index of papers on anonymity and anonymous communications, with particular attention to website fingerprinting, Tor and onion services, proxy and VPN fingerprinting, censorship measurement and circumvention, anonymous traffic classification, traffic-analysis side channels, and covert channels. It records publication entries and links only; it does not host paper content. Papers can be browsed by publication venue, year, or research topic, and links preferentially point to DOI, publisher, conference, or arXiv pages.

<div style="text-align: center">
 <img src="assets/cyber_security.jpg" alt="banner"/>
</div>

## Table of Contents

- [Awesome Anonymity Papers](#awesome-anonymity-papers)
  - [Table of Contents](#table-of-contents)
  - [Awesome list criteria](#awesome-list-criteria)
  - [Papers](#papers)
    - [By Journals \& Conferences](#by-journals--conferences)
    - [By Time](#by-time)
      - [2026](#2026)
      - [2025](#2025)
      - [2024](#2024)
      - [2023](#2023)
      - [2022](#2022)
      - [2021](#2021)
      - [2020](#2020)
      - [2019](#2019)
      - [2018](#2018)
      - [2017](#2017)
      - [2016](#2016)
      - [2015](#2015)
      - [2014](#2014)
      - [2013](#2013)
      - [2012](#2012)
    - [By Topic](#by-topic)
      - [Website Fingerprinting Attacks](#website-fingerprinting-attacks)
      - [Website Fingerprinting Defenses](#website-fingerprinting-defenses)
      - [Multi-Tab and Real-World Website Fingerprinting](#multi-tab-and-real-world-website-fingerprinting)
      - [Tor and Onion-Service Analysis](#tor-and-onion-service-analysis)
      - [Proxy, VPN, and Obfuscated-Traffic Fingerprinting](#proxy-vpn-and-obfuscated-traffic-fingerprinting)
      - [Censorship Measurement and Circumvention](#censorship-measurement-and-circumvention)
      - [Anonymous and Encrypted Traffic Classification](#anonymous-and-encrypted-traffic-classification)
      - [Traffic-Analysis Attacks and Side Channels](#traffic-analysis-attacks-and-side-channels)
      - [Covert Channels and Pluggable Transports](#covert-channels-and-pluggable-transports)
  - [Research Groups](#research-groups)
  - [Acknowledgement](#acknowledgement)
  - [Contact \& Feedback](#contact--feedback)
  - [License](#license)

## Awesome list criteria

> A curated list of **anonymity and anonymous-communication papers** published through 2026. Entries are selected for direct relevance to anonymity systems, traffic analysis, censorship, or closely related privacy threats and defenses.

## Papers

### By Journals & Conferences

#### USENIX Security

  - 2025 | *Censorship Evasion with Unidentified Protocol Generation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/wails)
  - 2024 | *Fingerprinting Obfuscated Proxy Traffic with Encapsulated TLS Handshakes*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/xue-fingerprinting)
  - 2024 | *GFWeb: Measuring the Great Firewall’s Web Censorship at Scale*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/hoang)
  - 2024 | *Stop! Don't Click Here Anymore: Boosting Website Fingerprinting By Considering Sets of Subpages*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/mitseva)
  - 2023 | *Subverting Website Fingerprinting Defenses with Robust Traffic Representation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/shen-meng)
  - 2022 | *Online Website Fingerprinting: Evaluating Website Fingerprinting Attacks on Tor in the Real World*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/cherubin)
  - 2021 | *Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations*, [`PDF`](https://www.usenix.org/system/files/sec21-nasr.pdf)
  - 2020 | *Zero-delay Lightweight Defenses against Website Fingerprinting*, [`PDF`](https://www.usenix.org/conference/usenixsecurity20/presentation/gong)

#### IEEE S&P

  - 2025 | *COUNTMAMBA: A Generalized Website Fingerprinting Attack via Coarse-Grained Representation and Fine-Grained Prediction*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00154)
  - 2024 | *Real-Time Website Fingerprinting Defense via Traffic Cluster Anonymization*, [`PDF`](https://doi.org/10.1109/sp54263.2024.00247)
  - 2023 | *Robust Multi-tab Website Fingerprinting Attacks in the Wild*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179464)
  - 2023 | *SoK: A Critical Evaluation of Efficient Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179289)
  - 2022 | *Surakav: Generating Realistic Traces for a Strong Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1109/sp46214.2022.9833722)

#### ACM CCS

  - 2025 | *GAPDiS: Gradient-Assisted Perturbation Design via Sequence Editing for Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1145/3719027.3765084)
  - 2025 | *Swallow: A Transfer-Robust Website Fingerprinting Attack via Consistent Feature Learning*, [`PDF`](https://doi.org/10.1145/3719027.3744795)
  - 2024 | *Robust and Reliable Early-Stage Website Fingerprinting Attacks via Spatial-Temporal Distribution Analysis*, [`PDF`](https://doi.org/10.1145/3658644.3670272)
  - 2023 | *Realistic Website Fingerprinting by Augmenting Network Traces*, [`PDF`](https://doi.org/10.1145/3576915.3616639)
  - 2023 | *Transformer-based Model for Multi-tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1145/3576915.3623107)
  - 2020 | *Censored Planet: An Internet-wide, Longitudinal Censorship Observatory*, [`PDF`](https://doi.org/10.1145/3372297.3417883)
  - 2020 | *TrafficSliver: Fighting Website Fingerprinting Attacks with Traffic Splitting*, [`PDF`](https://doi.org/10.1145/3372297.3423351)
  - 2018 | *Deep Fingerprinting: Undermining Website Fingerprinting Defenses with Deep Learning*, [`PDF`](https://doi.org/10.1145/3243734.3243768)

#### NDSS

  - 2026 | *Cease at the Ultimate Goodness: Towards Efficient Website Fingerprinting Defense via Iterative Mutual Information Minimization*, [`PDF`](https://doi.org/10.14722/ndss.2026.240786)
  - 2026 | *CELLSHIFT: RTT-Aware Trace Transduction for Real-World Website Fingerprinting*, [`PDF`](https://doi.org/10.14722/ndss.2026.231004)
  - 2026 | *Enhancing Website Fingerprinting Attacks against Traffic Drift*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/enhancing-website-fingerprinting-attacks-against-traffic-drift/)
  - 2026 | *Huma: Censorship Circumvention via Web Protocol Tunneling with Deferred Traffic Replacement*, [`PDF`](https://doi.org/10.14722/ndss.2026.240328)
  - 2026 | *Lightening the Load: A Cluster-Based Framework for A Lower-Overhead, Provable Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.14722/ndss.2026.241760)
  - 2025 | *The Discriminative Power of Cross-layer RTTs in Fingerprinting Proxy Traffic*, [`PDF`](https://doi.org/10.14722/ndss.2025.240966)
  - 2024 | *Flow Correlation Attacks on Tor Onion Service Sessions with Sliding Subset Sum*, [`PDF`](https://doi.org/10.14722/ndss.2024.24337)
  - 2024 | *MirageFlow: A New Bandwidth Inflation Attack on Tor*, [`PDF`](https://doi.org/10.14722/ndss.2024.241133)
  - 2024 | *On Precisely Detecting Censorship Circumvention in Real-World Networks*, [`PDF`](https://doi.org/10.14722/ndss.2024.23394)
  - 2021 | *Detecting Tor Bridge from Sampled Traffic in Backbone Networks*, [`PDF`](https://doi.org/10.14722/madweb.2021.23011)
  - 2020 | *Detecting Probe-resistant Proxies*, [`PDF`](https://doi.org/10.14722/ndss.2020.23087)

#### IEEE TIFS

  - 2025 | *WF-TFC: An Open-World Few-Shot Anonymous Website Fingerprinting via Time-Frequency Consistency*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3581092)
  - 2024 | *Inter-Flow Spatio-Temporal Correlation Analysis Based Website Fingerprinting Using Graph Neural Network*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3441935)
  - 2024 | *Multi-Level Resource-Coherented Graph Learning for Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3520014)
  - 2024 | *WFDefProxy: Real World Implementation and Evaluation of Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3327662)
  - 2023 | *Exploring Uncharted Waters of Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3342607)
  - 2022 | *Minipatch: Undermining DNN-Based Website Fingerprinting With Adversarial Patches*, [`PDF`](https://doi.org/10.1109/TIFS.2022.3186743)

#### IEEE TDSC

  - 2026 | *WFCAT: Augmenting Website Fingerprinting With Channel-Wise Attention on Timing Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3605197)
  - 2025 | *Few-Shot Website Fingerprinting With Distribution Calibration*, [`PDF`](https://doi.org/10.1109/TDSC.2024.3411014)
  - 2025 | *Toward an Effective Few-Shot Website Fingerprinting Attack With Quadruplet Networks and Deep Local Fingerprinting Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3563389)
  - 2022 | *An Automated Multi-Tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1109/TDSC.2021.3104869)
  - 2021 | *BiMorphing: A Bi-Directional Bursting Defense against Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/tdsc.2019.2907240)

#### IEEE/ACM ToN

  - 2026 | *Toward Robust Multi-Tab Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TON.2026.3666721)
  - 2025 | *High Precision and Efficient Anonymous Traffic Classification in the Real-World*, [`PDF`](https://doi.org/10.1109/TON.2024.3518976)
  - 2024 | *Website Fingerprinting on Encrypted Proxies: A Flow-Context-Aware Approach and Countermeasures*, [`PDF`](https://doi.org/10.1109/TNET.2023.3337270)

#### IEEE INFOCOM

  - 2025 | *Cross-Environmental Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/INFOCOM55648.2025.11044569)
  - 2024 | *Causality Correlation and Context Learning Aided Robust Lightweight Multi-Tab Website Fingerprinting Over Encrypted Tunnel*, [`PDF`](https://doi.org/10.1109/infocom52122.2024.10621235)

#### ACM IMC

  - 2020 | *How China Detects and Blocks Shadowsocks*, [`PDF`](https://doi.org/10.1145/3419394.3423644)

#### The Web Conference

  - 2024 | *AN-Net: an Anti-Noise Network for Anonymous Traffic Classification*, [`PDF`](https://doi.org/10.1145/3589334.3645691)

#### Other Journals, Conferences, and Preprints

  - 2026 | arXiv, *DEMUX: Boundary-Aware Multi-Scale Traffic Demixing for Multi-Tab Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2604.15677)
  - 2026 | Computers & Security, *Hiding the Trees in the Forest: Building Network Covert Channels with Hash-Based Covert Carrier Filtering*, [`PDF`](https://doi.org/10.1016/j.cose.2026.104981)
  - 2026 | arXiv, *More Than Meets the Eye: A Semantics-Aware Traffic Augmentation Framework for Generalizable Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2605.11402)
  - 2026 | arXiv, *PrismWF: A Multi-Granularity Patch-Based Transformer for Robust Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.48550/arxiv.2603.21117)
  - 2026 | arXiv, *Reality Check for Tor Website Fingerprinting in the Open World*, [`PDF`](https://arxiv.org/abs/2603.07412)
  - 2026 | arXiv, *ResAware: Cross-Environment Website Fingerprinting via Resource-Privileged Distillation*, [`PDF`](https://arxiv.org/abs/2606.17462)
  - 2026 | arXiv, *The Inevitability of Side-Channel Leakage in Encrypted Traffic*, [`PDF`](https://arxiv.org/abs/2602.14055)
  - 2025 | AAAI, *MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2412.15306)
  - 2025 | arXiv, *STAR: Semantic-Traffic Alignment and Retrieval for Zero-Shot HTTPS Website Fingerprinting*, [`PDF`](https://doi.org/10.48550/arxiv.2512.17667)
  - 2024 | arXiv, *Discovering Command and Control (C2) Channels on Tor and Public Networks Using Reinforcement Learning*, [`PDF`](https://arxiv.org/abs/2402.09200)
  - 2024 | FOCI, *Extended Abstract: Traffic Splitting for Pluggable Transports*, [`PDF`](https://petsymposium.org/foci/2024/foci-2024-0004.pdf)
  - 2024 | ICNP, *NetMamba: Efficient Network Traffic Classification via Pre-training Unidirectional Mamba*, [`PDF`](https://arxiv.org/abs/2405.11449)
  - 2024 | Communications of the ACM, *OpenVPN is Open to VPN Fingerprinting*, [`PDF`](https://doi.org/10.1145/3618117)
  - 2024 | ICICS, *TorHunter: A Lightweight Method for Efficient Identification of Obfuscated Tor Traffic Through Unsupervised Pre-training*, [`PDF`](https://link.springer.com/chapter/10.1007/978-981-97-8801-9_1)
  - 2024 | arXiv, *TrafficGPT: Breaking the Token Barrier for Efficient Long Traffic Analysis and Generation*, [`PDF`](https://arxiv.org/abs/2403.05822)
  - 2024 | Wireless Networks, *Updated Exploration of the Tor Network: Advertising, Availability and Protocols of Onion Services*, [`PDF`](https://link.springer.com/article/10.1007/s11276-024-03679-4)
  - 2023 | Computers & Security, *Detection of Obfuscated Tor Traffic Based on Bidirectional Generative Adversarial Networks and Vision Transform*, [`PDF`](https://doi.org/10.1016/j.cose.2023.103512)
  - 2021 | ICEA, *Towards Comprehensive Analysis of Tor Hidden Service Access Behavior Identification Under Obfs4 Scenario*, [`PDF`](https://doi.org/10.1145/3491396.3506532)
  - 2019 | ICDIS, *Detection of Tor Traffic Hiding Under Obfs4 Protocol Based on Two-Level Filtering*, [`PDF`](https://ieeexplore.ieee.org/document/8855280)
  - 2019 | IEEE INFOCOM Workshops, *FlowPic: Encrypted Internet Traffic Classification is as Easy as Image Recognition*, [`PDF`](https://ieeexplore.ieee.org/document/8845315)
  - 2018 | ICKII, *Tor Traffic Classification from Raw Packet Header using Convolutional Neural Network*, [`PDF`](https://ieeexplore.ieee.org/document/8569113)
  - 2017 | IEEE Big Data, *Tor Traffic Analysis and Detection via Machine Learning Techniques*, [`PDF`](https://ieeexplore.ieee.org/document/8258487)

***

### By Time

#### 2026

- arXiv, *DEMUX: Boundary-Aware Multi-Scale Traffic Demixing for Multi-Tab Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2604.15677)
- arXiv, *More Than Meets the Eye: A Semantics-Aware Traffic Augmentation Framework for Generalizable Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2605.11402)
- arXiv, *PrismWF: A Multi-Granularity Patch-Based Transformer for Robust Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.48550/arxiv.2603.21117)
- arXiv, *Reality Check for Tor Website Fingerprinting in the Open World*, [`PDF`](https://arxiv.org/abs/2603.07412)
- arXiv, *ResAware: Cross-Environment Website Fingerprinting via Resource-Privileged Distillation*, [`PDF`](https://arxiv.org/abs/2606.17462)
- arXiv, *The Inevitability of Side-Channel Leakage in Encrypted Traffic*, [`PDF`](https://arxiv.org/abs/2602.14055)
- Computers & Security, *Hiding the Trees in the Forest: Building Network Covert Channels with Hash-Based Covert Carrier Filtering*, [`PDF`](https://doi.org/10.1016/j.cose.2026.104981)
- IEEE TDSC, *WFCAT: Augmenting Website Fingerprinting With Channel-Wise Attention on Timing Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3605197)
- IEEE/ACM ToN, *Toward Robust Multi-Tab Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TON.2026.3666721)
- NDSS, *Cease at the Ultimate Goodness: Towards Efficient Website Fingerprinting Defense via Iterative Mutual Information Minimization*, [`PDF`](https://doi.org/10.14722/ndss.2026.240786)
- NDSS, *CELLSHIFT: RTT-Aware Trace Transduction for Real-World Website Fingerprinting*, [`PDF`](https://doi.org/10.14722/ndss.2026.231004)
- NDSS, *Enhancing Website Fingerprinting Attacks against Traffic Drift*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/enhancing-website-fingerprinting-attacks-against-traffic-drift/)
- NDSS, *Huma: Censorship Circumvention via Web Protocol Tunneling with Deferred Traffic Replacement*, [`PDF`](https://doi.org/10.14722/ndss.2026.240328)
- NDSS, *Lightening the Load: A Cluster-Based Framework for A Lower-Overhead, Provable Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.14722/ndss.2026.241760)

#### 2025

- AAAI, *MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2412.15306)
- ACM CCS, *GAPDiS: Gradient-Assisted Perturbation Design via Sequence Editing for Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1145/3719027.3765084)
- ACM CCS, *Swallow: A Transfer-Robust Website Fingerprinting Attack via Consistent Feature Learning*, [`PDF`](https://doi.org/10.1145/3719027.3744795)
- arXiv, *STAR: Semantic-Traffic Alignment and Retrieval for Zero-Shot HTTPS Website Fingerprinting*, [`PDF`](https://doi.org/10.48550/arxiv.2512.17667)
- IEEE INFOCOM, *Cross-Environmental Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/INFOCOM55648.2025.11044569)
- IEEE S&P, *COUNTMAMBA: A Generalized Website Fingerprinting Attack via Coarse-Grained Representation and Fine-Grained Prediction*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00154)
- IEEE TDSC, *Few-Shot Website Fingerprinting With Distribution Calibration*, [`PDF`](https://doi.org/10.1109/TDSC.2024.3411014)
- IEEE TDSC, *Toward an Effective Few-Shot Website Fingerprinting Attack With Quadruplet Networks and Deep Local Fingerprinting Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3563389)
- IEEE TIFS, *WF-TFC: An Open-World Few-Shot Anonymous Website Fingerprinting via Time-Frequency Consistency*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3581092)
- IEEE/ACM ToN, *High Precision and Efficient Anonymous Traffic Classification in the Real-World*, [`PDF`](https://doi.org/10.1109/TON.2024.3518976)
- NDSS, *The Discriminative Power of Cross-layer RTTs in Fingerprinting Proxy Traffic*, [`PDF`](https://doi.org/10.14722/ndss.2025.240966)
- USENIX Security, *Censorship Evasion with Unidentified Protocol Generation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/wails)

#### 2024

- ACM CCS, *Robust and Reliable Early-Stage Website Fingerprinting Attacks via Spatial-Temporal Distribution Analysis*, [`PDF`](https://doi.org/10.1145/3658644.3670272)
- arXiv, *Discovering Command and Control (C2) Channels on Tor and Public Networks Using Reinforcement Learning*, [`PDF`](https://arxiv.org/abs/2402.09200)
- arXiv, *TrafficGPT: Breaking the Token Barrier for Efficient Long Traffic Analysis and Generation*, [`PDF`](https://arxiv.org/abs/2403.05822)
- Communications of the ACM, *OpenVPN is Open to VPN Fingerprinting*, [`PDF`](https://doi.org/10.1145/3618117)
- FOCI, *Extended Abstract: Traffic Splitting for Pluggable Transports*, [`PDF`](https://petsymposium.org/foci/2024/foci-2024-0004.pdf)
- ICICS, *TorHunter: A Lightweight Method for Efficient Identification of Obfuscated Tor Traffic Through Unsupervised Pre-training*, [`PDF`](https://link.springer.com/chapter/10.1007/978-981-97-8801-9_1)
- ICNP, *NetMamba: Efficient Network Traffic Classification via Pre-training Unidirectional Mamba*, [`PDF`](https://arxiv.org/abs/2405.11449)
- IEEE INFOCOM, *Causality Correlation and Context Learning Aided Robust Lightweight Multi-Tab Website Fingerprinting Over Encrypted Tunnel*, [`PDF`](https://doi.org/10.1109/infocom52122.2024.10621235)
- IEEE S&P, *Real-Time Website Fingerprinting Defense via Traffic Cluster Anonymization*, [`PDF`](https://doi.org/10.1109/sp54263.2024.00247)
- IEEE TIFS, *Inter-Flow Spatio-Temporal Correlation Analysis Based Website Fingerprinting Using Graph Neural Network*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3441935)
- IEEE TIFS, *Multi-Level Resource-Coherented Graph Learning for Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3520014)
- IEEE TIFS, *WFDefProxy: Real World Implementation and Evaluation of Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3327662)
- IEEE/ACM ToN, *Website Fingerprinting on Encrypted Proxies: A Flow-Context-Aware Approach and Countermeasures*, [`PDF`](https://doi.org/10.1109/TNET.2023.3337270)
- NDSS, *Flow Correlation Attacks on Tor Onion Service Sessions with Sliding Subset Sum*, [`PDF`](https://doi.org/10.14722/ndss.2024.24337)
- NDSS, *MirageFlow: A New Bandwidth Inflation Attack on Tor*, [`PDF`](https://doi.org/10.14722/ndss.2024.241133)
- NDSS, *On Precisely Detecting Censorship Circumvention in Real-World Networks*, [`PDF`](https://doi.org/10.14722/ndss.2024.23394)
- The Web Conference, *AN-Net: an Anti-Noise Network for Anonymous Traffic Classification*, [`PDF`](https://doi.org/10.1145/3589334.3645691)
- USENIX Security, *Fingerprinting Obfuscated Proxy Traffic with Encapsulated TLS Handshakes*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/xue-fingerprinting)
- USENIX Security, *GFWeb: Measuring the Great Firewall’s Web Censorship at Scale*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/hoang)
- USENIX Security, *Stop! Don't Click Here Anymore: Boosting Website Fingerprinting By Considering Sets of Subpages*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/mitseva)
- Wireless Networks, *Updated Exploration of the Tor Network: Advertising, Availability and Protocols of Onion Services*, [`PDF`](https://link.springer.com/article/10.1007/s11276-024-03679-4)

#### 2023

- ACM CCS, *Realistic Website Fingerprinting by Augmenting Network Traces*, [`PDF`](https://doi.org/10.1145/3576915.3616639)
- ACM CCS, *Transformer-based Model for Multi-tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1145/3576915.3623107)
- Computers & Security, *Detection of Obfuscated Tor Traffic Based on Bidirectional Generative Adversarial Networks and Vision Transform*, [`PDF`](https://doi.org/10.1016/j.cose.2023.103512)
- IEEE S&P, *Robust Multi-tab Website Fingerprinting Attacks in the Wild*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179464)
- IEEE S&P, *SoK: A Critical Evaluation of Efficient Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179289)
- IEEE TIFS, *Exploring Uncharted Waters of Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3342607)
- USENIX Security, *Subverting Website Fingerprinting Defenses with Robust Traffic Representation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/shen-meng)

#### 2022

- IEEE S&P, *Surakav: Generating Realistic Traces for a Strong Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1109/sp46214.2022.9833722)
- IEEE TDSC, *An Automated Multi-Tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1109/TDSC.2021.3104869)
- IEEE TIFS, *Minipatch: Undermining DNN-Based Website Fingerprinting With Adversarial Patches*, [`PDF`](https://doi.org/10.1109/TIFS.2022.3186743)
- USENIX Security, *Online Website Fingerprinting: Evaluating Website Fingerprinting Attacks on Tor in the Real World*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/cherubin)

#### 2021

- ICEA, *Towards Comprehensive Analysis of Tor Hidden Service Access Behavior Identification Under Obfs4 Scenario*, [`PDF`](https://doi.org/10.1145/3491396.3506532)
- IEEE TDSC, *BiMorphing: A Bi-Directional Bursting Defense against Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/tdsc.2019.2907240)
- NDSS, *Detecting Tor Bridge from Sampled Traffic in Backbone Networks*, [`PDF`](https://doi.org/10.14722/madweb.2021.23011)
- USENIX Security, *Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations*, [`PDF`](https://www.usenix.org/system/files/sec21-nasr.pdf)

#### 2020

- ACM CCS, *Censored Planet: An Internet-wide, Longitudinal Censorship Observatory*, [`PDF`](https://doi.org/10.1145/3372297.3417883)
- ACM CCS, *TrafficSliver: Fighting Website Fingerprinting Attacks with Traffic Splitting*, [`PDF`](https://doi.org/10.1145/3372297.3423351)
- ACM IMC, *How China Detects and Blocks Shadowsocks*, [`PDF`](https://doi.org/10.1145/3419394.3423644)
- NDSS, *Detecting Probe-resistant Proxies*, [`PDF`](https://doi.org/10.14722/ndss.2020.23087)
- USENIX Security, *Zero-delay Lightweight Defenses against Website Fingerprinting*, [`PDF`](https://www.usenix.org/conference/usenixsecurity20/presentation/gong)

#### 2019

- ICDIS, *Detection of Tor Traffic Hiding Under Obfs4 Protocol Based on Two-Level Filtering*, [`PDF`](https://ieeexplore.ieee.org/document/8855280)
- IEEE INFOCOM Workshops, *FlowPic: Encrypted Internet Traffic Classification is as Easy as Image Recognition*, [`PDF`](https://ieeexplore.ieee.org/document/8845315)

#### 2018

- ACM CCS, *Deep Fingerprinting: Undermining Website Fingerprinting Defenses with Deep Learning*, [`PDF`](https://doi.org/10.1145/3243734.3243768)
- ICKII, *Tor Traffic Classification from Raw Packet Header using Convolutional Neural Network*, [`PDF`](https://ieeexplore.ieee.org/document/8569113)

#### 2017

- IEEE Big Data, *Tor Traffic Analysis and Detection via Machine Learning Techniques*, [`PDF`](https://ieeexplore.ieee.org/document/8258487)

#### 2016

_No curated entries yet._

#### 2015

_No curated entries yet._

#### 2014

_No curated entries yet._

#### 2013

_No curated entries yet._

#### 2012

_No curated entries yet._

***

### By Topic

Each paper is assigned to one primary topic to keep this view concise.

#### Website Fingerprinting Attacks

- 2026 | NDSS, *CELLSHIFT: RTT-Aware Trace Transduction for Real-World Website Fingerprinting*, [`PDF`](https://doi.org/10.14722/ndss.2026.231004)
- 2026 | arXiv, *PrismWF: A Multi-Granularity Patch-Based Transformer for Robust Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.48550/arxiv.2603.21117)
- 2025 | IEEE S&P, *COUNTMAMBA: A Generalized Website Fingerprinting Attack via Coarse-Grained Representation and Fine-Grained Prediction*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00154)
- 2025 | arXiv, *STAR: Semantic-Traffic Alignment and Retrieval for Zero-Shot HTTPS Website Fingerprinting*, [`PDF`](https://doi.org/10.48550/arxiv.2512.17667)
- 2025 | ACM CCS, *Swallow: A Transfer-Robust Website Fingerprinting Attack via Consistent Feature Learning*, [`PDF`](https://doi.org/10.1145/3719027.3744795)
- 2024 | IEEE TIFS, *Inter-Flow Spatio-Temporal Correlation Analysis Based Website Fingerprinting Using Graph Neural Network*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3441935)
- 2024 | IEEE TIFS, *Multi-Level Resource-Coherented Graph Learning for Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3520014)
- 2023 | IEEE TIFS, *Exploring Uncharted Waters of Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3342607)
- 2023 | ACM CCS, *Realistic Website Fingerprinting by Augmenting Network Traces*, [`PDF`](https://doi.org/10.1145/3576915.3616639)
- 2023 | USENIX Security, *Subverting Website Fingerprinting Defenses with Robust Traffic Representation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/shen-meng)
- 2018 | ACM CCS, *Deep Fingerprinting: Undermining Website Fingerprinting Defenses with Deep Learning*, [`PDF`](https://doi.org/10.1145/3243734.3243768)

#### Website Fingerprinting Defenses

- 2026 | NDSS, *Cease at the Ultimate Goodness: Towards Efficient Website Fingerprinting Defense via Iterative Mutual Information Minimization*, [`PDF`](https://doi.org/10.14722/ndss.2026.240786)
- 2026 | NDSS, *Lightening the Load: A Cluster-Based Framework for A Lower-Overhead, Provable Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.14722/ndss.2026.241760)
- 2025 | ACM CCS, *GAPDiS: Gradient-Assisted Perturbation Design via Sequence Editing for Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1145/3719027.3765084)
- 2024 | IEEE S&P, *Real-Time Website Fingerprinting Defense via Traffic Cluster Anonymization*, [`PDF`](https://doi.org/10.1109/sp54263.2024.00247)
- 2024 | IEEE TIFS, *WFDefProxy: Real World Implementation and Evaluation of Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3327662)
- 2023 | IEEE S&P, *SoK: A Critical Evaluation of Efficient Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179289)
- 2022 | IEEE TIFS, *Minipatch: Undermining DNN-Based Website Fingerprinting With Adversarial Patches*, [`PDF`](https://doi.org/10.1109/TIFS.2022.3186743)
- 2022 | IEEE S&P, *Surakav: Generating Realistic Traces for a Strong Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1109/sp46214.2022.9833722)
- 2021 | IEEE TDSC, *BiMorphing: A Bi-Directional Bursting Defense against Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/tdsc.2019.2907240)
- 2020 | ACM CCS, *TrafficSliver: Fighting Website Fingerprinting Attacks with Traffic Splitting*, [`PDF`](https://doi.org/10.1145/3372297.3423351)
- 2020 | USENIX Security, *Zero-delay Lightweight Defenses against Website Fingerprinting*, [`PDF`](https://www.usenix.org/conference/usenixsecurity20/presentation/gong)

#### Multi-Tab and Real-World Website Fingerprinting

- 2026 | arXiv, *DEMUX: Boundary-Aware Multi-Scale Traffic Demixing for Multi-Tab Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2604.15677)
- 2026 | NDSS, *Enhancing Website Fingerprinting Attacks against Traffic Drift*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/enhancing-website-fingerprinting-attacks-against-traffic-drift/)
- 2026 | arXiv, *More Than Meets the Eye: A Semantics-Aware Traffic Augmentation Framework for Generalizable Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2605.11402)
- 2026 | arXiv, *Reality Check for Tor Website Fingerprinting in the Open World*, [`PDF`](https://arxiv.org/abs/2603.07412)
- 2026 | arXiv, *ResAware: Cross-Environment Website Fingerprinting via Resource-Privileged Distillation*, [`PDF`](https://arxiv.org/abs/2606.17462)
- 2026 | IEEE/ACM ToN, *Toward Robust Multi-Tab Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TON.2026.3666721)
- 2026 | IEEE TDSC, *WFCAT: Augmenting Website Fingerprinting With Channel-Wise Attention on Timing Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3605197)
- 2025 | IEEE INFOCOM, *Cross-Environmental Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/INFOCOM55648.2025.11044569)
- 2025 | IEEE TDSC, *Few-Shot Website Fingerprinting With Distribution Calibration*, [`PDF`](https://doi.org/10.1109/TDSC.2024.3411014)
- 2025 | IEEE TDSC, *Toward an Effective Few-Shot Website Fingerprinting Attack With Quadruplet Networks and Deep Local Fingerprinting Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3563389)
- 2025 | IEEE TIFS, *WF-TFC: An Open-World Few-Shot Anonymous Website Fingerprinting via Time-Frequency Consistency*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3581092)
- 2024 | IEEE INFOCOM, *Causality Correlation and Context Learning Aided Robust Lightweight Multi-Tab Website Fingerprinting Over Encrypted Tunnel*, [`PDF`](https://doi.org/10.1109/infocom52122.2024.10621235)
- 2024 | ACM CCS, *Robust and Reliable Early-Stage Website Fingerprinting Attacks via Spatial-Temporal Distribution Analysis*, [`PDF`](https://doi.org/10.1145/3658644.3670272)
- 2024 | USENIX Security, *Stop! Don't Click Here Anymore: Boosting Website Fingerprinting By Considering Sets of Subpages*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/mitseva)
- 2023 | IEEE S&P, *Robust Multi-tab Website Fingerprinting Attacks in the Wild*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179464)
- 2023 | ACM CCS, *Transformer-based Model for Multi-tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1145/3576915.3623107)
- 2022 | IEEE TDSC, *An Automated Multi-Tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1109/TDSC.2021.3104869)
- 2022 | USENIX Security, *Online Website Fingerprinting: Evaluating Website Fingerprinting Attacks on Tor in the Real World*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/cherubin)

#### Tor and Onion-Service Analysis

- 2024 | arXiv, *Discovering Command and Control (C2) Channels on Tor and Public Networks Using Reinforcement Learning*, [`PDF`](https://arxiv.org/abs/2402.09200)
- 2024 | NDSS, *MirageFlow: A New Bandwidth Inflation Attack on Tor*, [`PDF`](https://doi.org/10.14722/ndss.2024.241133)
- 2024 | Wireless Networks, *Updated Exploration of the Tor Network: Advertising, Availability and Protocols of Onion Services*, [`PDF`](https://link.springer.com/article/10.1007/s11276-024-03679-4)
- 2021 | NDSS, *Detecting Tor Bridge from Sampled Traffic in Backbone Networks*, [`PDF`](https://doi.org/10.14722/madweb.2021.23011)

#### Proxy, VPN, and Obfuscated-Traffic Fingerprinting

- 2025 | NDSS, *The Discriminative Power of Cross-layer RTTs in Fingerprinting Proxy Traffic*, [`PDF`](https://doi.org/10.14722/ndss.2025.240966)
- 2024 | USENIX Security, *Fingerprinting Obfuscated Proxy Traffic with Encapsulated TLS Handshakes*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/xue-fingerprinting)
- 2024 | Communications of the ACM, *OpenVPN is Open to VPN Fingerprinting*, [`PDF`](https://doi.org/10.1145/3618117)
- 2024 | ICICS, *TorHunter: A Lightweight Method for Efficient Identification of Obfuscated Tor Traffic Through Unsupervised Pre-training*, [`PDF`](https://link.springer.com/chapter/10.1007/978-981-97-8801-9_1)
- 2024 | IEEE/ACM ToN, *Website Fingerprinting on Encrypted Proxies: A Flow-Context-Aware Approach and Countermeasures*, [`PDF`](https://doi.org/10.1109/TNET.2023.3337270)
- 2023 | Computers & Security, *Detection of Obfuscated Tor Traffic Based on Bidirectional Generative Adversarial Networks and Vision Transform*, [`PDF`](https://doi.org/10.1016/j.cose.2023.103512)
- 2021 | ICEA, *Towards Comprehensive Analysis of Tor Hidden Service Access Behavior Identification Under Obfs4 Scenario*, [`PDF`](https://doi.org/10.1145/3491396.3506532)
- 2020 | NDSS, *Detecting Probe-resistant Proxies*, [`PDF`](https://doi.org/10.14722/ndss.2020.23087)
- 2019 | ICDIS, *Detection of Tor Traffic Hiding Under Obfs4 Protocol Based on Two-Level Filtering*, [`PDF`](https://ieeexplore.ieee.org/document/8855280)

#### Censorship Measurement and Circumvention

- 2026 | NDSS, *Huma: Censorship Circumvention via Web Protocol Tunneling with Deferred Traffic Replacement*, [`PDF`](https://doi.org/10.14722/ndss.2026.240328)
- 2025 | USENIX Security, *Censorship Evasion with Unidentified Protocol Generation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/wails)
- 2024 | USENIX Security, *GFWeb: Measuring the Great Firewall’s Web Censorship at Scale*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/hoang)
- 2024 | NDSS, *On Precisely Detecting Censorship Circumvention in Real-World Networks*, [`PDF`](https://doi.org/10.14722/ndss.2024.23394)
- 2020 | ACM CCS, *Censored Planet: An Internet-wide, Longitudinal Censorship Observatory*, [`PDF`](https://doi.org/10.1145/3372297.3417883)
- 2020 | ACM IMC, *How China Detects and Blocks Shadowsocks*, [`PDF`](https://doi.org/10.1145/3419394.3423644)

#### Anonymous and Encrypted Traffic Classification

- 2025 | IEEE/ACM ToN, *High Precision and Efficient Anonymous Traffic Classification in the Real-World*, [`PDF`](https://doi.org/10.1109/TON.2024.3518976)
- 2025 | AAAI, *MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2412.15306)
- 2024 | The Web Conference, *AN-Net: an Anti-Noise Network for Anonymous Traffic Classification*, [`PDF`](https://doi.org/10.1145/3589334.3645691)
- 2024 | ICNP, *NetMamba: Efficient Network Traffic Classification via Pre-training Unidirectional Mamba*, [`PDF`](https://arxiv.org/abs/2405.11449)
- 2024 | arXiv, *TrafficGPT: Breaking the Token Barrier for Efficient Long Traffic Analysis and Generation*, [`PDF`](https://arxiv.org/abs/2403.05822)
- 2019 | IEEE INFOCOM Workshops, *FlowPic: Encrypted Internet Traffic Classification is as Easy as Image Recognition*, [`PDF`](https://ieeexplore.ieee.org/document/8845315)
- 2018 | ICKII, *Tor Traffic Classification from Raw Packet Header using Convolutional Neural Network*, [`PDF`](https://ieeexplore.ieee.org/document/8569113)
- 2017 | IEEE Big Data, *Tor Traffic Analysis and Detection via Machine Learning Techniques*, [`PDF`](https://ieeexplore.ieee.org/document/8258487)

#### Traffic-Analysis Attacks and Side Channels

- 2026 | arXiv, *The Inevitability of Side-Channel Leakage in Encrypted Traffic*, [`PDF`](https://arxiv.org/abs/2602.14055)
- 2024 | NDSS, *Flow Correlation Attacks on Tor Onion Service Sessions with Sliding Subset Sum*, [`PDF`](https://doi.org/10.14722/ndss.2024.24337)
- 2021 | USENIX Security, *Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations*, [`PDF`](https://www.usenix.org/system/files/sec21-nasr.pdf)

#### Covert Channels and Pluggable Transports

- 2026 | Computers & Security, *Hiding the Trees in the Forest: Building Network Covert Channels with Hash-Based Covert Carrier Filtering*, [`PDF`](https://doi.org/10.1016/j.cose.2026.104981)
- 2024 | FOCI, *Extended Abstract: Traffic Splitting for Pluggable Transports*, [`PDF`](https://petsymposium.org/foci/2024/foci-2024-0004.pdf)

***

## Research Groups

(Thanks to [@linwhitehat](https://github.com/linwhitehat))

<details>
<summary>
Chinese Academy of Sciences, University of Chinese Academy of Sciences/China
</summary>

- [Gang Xiong](https://people.ucas.ac.cn/~xionggang) (Institute of Information Engineering)
- [Kai Chen](https://people.ucas.ac.cn/~kaichen) (Institute of Information Engineering)
- [Qixu Liu](https://people.ucas.ac.cn/~liuqixu) (Institute of Information Engineering)
- [Guozhu Meng](https://people.ucas.ac.cn/~gzmeng) (Institute of Information Engineering)
- [Qingyun Liu](https://people.ucas.ac.cn/~0027674) (Institute of Information Engineering)
- [Zhigang Lu](https://people.ucas.ac.cn/~luzhigang) (Institute of Information Engineering)
- [Xiaodong Li](https://people.ucas.edu.cn/~LEE) (Institute of Computing Technology)
- [Zhenyu Li](http://www.ict.ac.cn/sourcedb_2018_ict_cas/cn/jssrck/201111/t20111114_3395505.html) (Institute of Computing Technology)
- [Yujun Zhang](https://people.ucas.ac.cn/~yujun) (Institute of Computing Technology)
- [Yuqing Zhang](https://people.ucas.ac.cn/~zhangyuqing) (School of Computer Science and Technology)
</details>

<details>
<summary>
Tsinghua University/China
</summary>

- [Ke Xu](http://www.thucsnet.org/xuke.html)
- [Jiahai Yang](https://nmgroup.tsinghua.edu.cn/yjh/)
- [Haixin Duan](http://netsec.ccert.edu.cn/people/duanhx/)
- [Jianjun Chen](https://www.jianjunchen.com/)
- [Dan Li](https://www.cs.tsinghua.edu.cn/info/1126/3948.htm)
- [Yong Cui](https://www.cs.tsinghua.edu.cn/info/1126/3589.htm)
- [Mingwei Xu](https://www.cs.tsinghua.edu.cn/info/1126/3580.htm)
- [Xia Yin](https://www.cs.tsinghua.edu.cn/info/1126/3578.htm)
- [Qi Li](https://www.insc.tsinghua.edu.cn/info/1157/2851.htm)
- [Dan Pei](https://www.cs.tsinghua.edu.cn/info/1127/3597.htm)
- [Zhiliang Wang](https://www.cs.tsinghua.edu.cn/info/1127/3593.htm)
- [Chao Zhang](https://netsec.ccert.edu.cn/chs/people/chaoz/)
</details>

<details>
<summary>
Zhejiang University/China
</summary>

- [Shouling Ji](https://person.zju.edu.cn/sji#0)
- [Wenyuan Xu](https://person.zju.edu.cn/wyxu#0)
- [Meng Luo](https://person.zju.edu.cn/mengluo#0)
- [Kui Ren](https://person.zju.edu.cn/kuiren)
- [Fan Zhang](https://person.zju.edu.cn/fanzhang)
</details>

<details>
<summary>
Harbin Institute of Technology/China
</summary>

- [Weizhe (James) Zhang](https://homepage.hit.edu.cn/wzzhang)
- [Xiangzhan Yu](https://homepage.hit.edu.cn/yuxiangzhan)
- [Hui (Sophia) He](https://homepage.hit.edu.cn/huihe)
- [Junbao Li](https://homepage.hit.edu.cn/lijunbao)
- [Zhaoxin Zhang](https://homepage.hit.edu.cn/zhangzhaoxin)
</details>

<details>
<summary>
Beijing University of Posts and Telecommunications/China
</summary>

- [Shize Guo](https://scss.bupt.edu.cn/info/1063/5386.htm)
- [Dongbin Wang](https://scss.bupt.edu.cn/info/1249/5098.htm)
- [Zhongliang Yang](https://scss.bupt.edu.cn/info/1247/5070.htm)
</details>

<details>
<summary>
Beijing Institute of Technology/China
</summary>

- [Changzhen Hu](https://cst.bit.edu.cn/szdw/jsml/bssds/ca94335a79114dbe9ae967e53ca86bec.htm)
- [Liehuang Zhu](https://cs.bit.edu.cn/szdw/jsml/wlkjaqxy/zlh/index.htm)
- [Meng Shen](https://cst.bit.edu.cn/szdw/jsml/bssds/86728e84066248b0b13bdf04f685817f.htm)
- [Xuhui Ding](https://cst.bit.edu.cn/szdw/jsml/bssds/711aba6ea79b41618a2f2fac616652a9.htm)
</details>

<details>
<summary>
Beihang University/China
</summary>

- [Jian Mao](https://shi.buaa.edu.cn/maojian/zh_CN/index.htm)
- [Sheng Hong](http://shi.buaa.edu.cn/hongsheng/zh_CN/index.htm)
- [Ying Gao](https://shi.buaa.edu.cn/gaoying/zh_CN/index.htm)
</details>

<details>
<summary>
Xi'an Jiaotong University/China
</summary>

- [Xiaohong Guan](https://www.xjtu.edu.cn/jsnr.jsp?wbtreeid=1632&wbwbxjtuteacherid=502)
- [Chao Shen](https://gr.xjtu.edu.cn/web/cshen)
</details>

<details>
<summary>
Shanghai Jiao Tong University/China
</summary>

- [Guoxing Chen](https://donnod.github.io/)
- [Haojin Zhu](https://nsec.sjtu.edu.cn/~hjzhu/)
</details>

<details>
<summary>
Others
</summary>

- [Guang Cheng](https://cyber.seu.edu.cn/cg1/list.htm) (Southeast University/China)
- [Fengwei Zhang](https://fengweiz.github.io/) (Southern University of Science and Technology/China)
- [Qian Wang](http://nisplab.whu.edu.cn/people.html) (Wuhan University/China)
- [Min Yang](https://cs.fudan.edu.cn/3e/d7/c25921a278231/page.htm) (Fudan University/China)
- [Shuguang Cui](https://sse.cuhk.edu.cn/en/faculty/cuishuguang) (The Chinese University of Hong Kong/China)
</details>
  
<details>
<summary>
Overseas
</summary>

- [Xuemin (Sherman) Shen](https://uwaterloo.ca/scholar/sshen) (University of Waterloo/Canada)
- [Xiaofeng Wang](https://homes.luddy.indiana.edu/xw7/) (Indiana University Bloomington/United States)
- [Tao Wang](https://www.cs.sfu.ca/~taowang/) (Simon Fraser University/Canada)
- [Ivan Martinovic](https://www.cs.ox.ac.uk/people/ivan.martinovic/) (University of Oxford/United Kingdom)
- [Amir Houmansadr](https://people.cs.umass.edu/~amir/) (University of Massachusetts Amherst/United States)
- [Giuseppe Aceto](http://wpage.unina.it/giuseppe.aceto/) (Università di Napoli Federico II/Italy)
- [Antonio Pescapè](http://wpage.unina.it/pescape/) (Università di Napoli Federico II/Italy)
- [Thorsten Holz](https://cispa.de/en/research/groups/holz) (CISPA Helmholtz Center for Information Security/Germany)
- [Mohammad Saidur Rahman](https://www.rahmanmsaidur.com/) (University of Texas at El Paso/United States)
- [Yue Zhang](https://yue.zyueinfosec.com/) (Drexel University/United States)
- [Xinyu Xing](http://xinyuxing.org/) (Northwestern University/United States)
- [Yang Liu](https://personal.ntu.edu.sg/yangliu/) (Nanyang Technological University/Singapore)
- [Alessandro Finamore](https://afinamore.io/) (Huawei Technologies/France)
- [Thijs van Ede](https://thijsvane.de/) (University of Twente/Netherlands)
</details>

***

## Acknowledgement

Special thanks to everyone who contributed to this project.

| Name       | Bio        |
| :--------: | :--------: |
| [Qiang Zhang](mailto:qzhang@stu.scu.edu.cn) | PhD Student @SCU |
| [Chenxin Zhou](mailto:tovey_zhou@foxmail.com) | PhD Student @ Das-Lab, SCU |

## Contact & Feedback

If you have any suggestions (missing papers, new papers, key researchers or typos), feel free to pull a request. Also you can mail to:

- [Qiang Zhang](mailto:qzhang@stu.scu.edu.cn?subject=Feedback)
- [Chenxin Zhou](mailto:tovey_zhou@foxmail.com?subject=Feedback)

## License

The source-code is licensed under the MIT license. See [LICENSE](LICENSE).
