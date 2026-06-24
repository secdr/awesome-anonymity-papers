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

This repository maintains a curated index of network-traffic security research, spanning anonymity and anonymous communications, website fingerprinting, encrypted traffic classification, malicious traffic detection, traffic representation learning and foundation models, tunnel and protocol analysis, censorship measurement and circumvention, and related evaluation methods. It records publication entries and links only; it does not host paper content. The complete catalog can be browsed by publication venue, year, or primary research topic, with links preferentially pointing to DOI, publisher, conference, or arXiv pages.

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
      - [2008](#2008)
    - [By Topic](#by-topic)
      - [Website Fingerprinting Attacks](#website-fingerprinting-attacks)
      - [Website Fingerprinting Defenses](#website-fingerprinting-defenses)
      - [Multi-Tab, Open-World, and Real-World Website Fingerprinting](#multi-tab-open-world-and-real-world-website-fingerprinting)
      - [Tor, Onion Services, Proxy, VPN, and Anonymous Traffic Analysis](#tor-onion-services-proxy-vpn-and-anonymous-traffic-analysis)
      - [Censorship Measurement, Circumvention, and Covert Channels](#censorship-measurement-circumvention-and-covert-channels)
      - [Malicious Traffic, C2, Anomaly, and Attack Detection](#malicious-traffic-c2-anomaly-and-attack-detection)
      - [Encrypted Traffic Classification and Application Identification](#encrypted-traffic-classification-and-application-identification)
      - [Traffic Representation, Pretraining, and Foundation Models](#traffic-representation-pretraining-and-foundation-models)
      - [Robust, Adaptive, Few-Shot, Open-Set, and Federated Learning](#robust-adaptive-few-shot-open-set-and-federated-learning)
      - [Tunnel, QUIC, DoH, and Protocol Analysis](#tunnel-quic-doh-and-protocol-analysis)
      - [Surveys, Benchmarks, Explainability, and Evaluation](#surveys-benchmarks-explainability-and-evaluation)
      - [Other Network Security and Supporting Methods](#other-network-security-and-supporting-methods)
  - [Research Groups](#research-groups)
  - [Acknowledgement](#acknowledgement)
  - [Contact \& Feedback](#contact--feedback)
  - [License](#license)

## Awesome list criteria

> A curated catalog of **network-traffic security papers** published through 2026. The list includes all papers tracked by the companion Traffic Papers knowledge base, while the topic view separates anonymity research from general encrypted-traffic, malicious-traffic, representation-learning, and supporting work.

## Papers

### By Journals & Conferences

#### USENIX Security

  - 2025 | *Censorship Evasion with Unidentified Protocol Generation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/wails)
  - 2025 | *CertTA: Certified Robustness Made Practical for Learning-Based Traffic Analysis*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/yan-jinzhu)
  - 2024 | *Fingerprinting Obfuscated Proxy Traffic with Encapsulated TLS Handshakes*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/xue-fingerprinting)
  - 2024 | *GFWeb: Measuring the Great Firewall’s Web Censorship at Scale*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/hoang)
  - 2024 | *OpenVPN is Open to VPN Fingerprinting*, [`PDF`](https://doi.org/10.1145/3618117)
  - 2024 | *Stop! Don't Click Here Anymore: Boosting Website Fingerprinting By Considering Sets of Subpages*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/mitseva)
  - 2023 | *How the Great Firewall of China Detects and Blocks Fully Encrypted Traffic*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/wu-mingshi)
  - 2023 | *Subverting Website Fingerprinting Defenses with Robust Traffic Representation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/shen-meng)
  - 2022 | *Off-Path Network Traffic Manipulation via Revitalized ICMP Redirect Attacks*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/feng)
  - 2022 | *Online Website Fingerprinting: Evaluating Website Fingerprinting Attacks on Tor in the Real World*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/cherubin)
  - 2021 | *Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations*, [`PDF`](https://www.usenix.org/system/files/sec21-nasr.pdf)
  - 2021 | *LZR: Identifying Unexpected Internet Services*, [`PDF`](https://www.usenix.org/conference/usenixsecurity21/presentation/izhikevich)
  - 2020 | *Zero-delay Lightweight Defenses against Website Fingerprinting*, [`PDF`](https://www.usenix.org/conference/usenixsecurity20/presentation/gong)

#### IEEE S&P

  - 2025 | *COUNTMAMBA: A Generalized Website Fingerprinting Attack via Coarse-Grained Representation and Fine-Grained Prediction*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00154)
  - 2025 | *SoK: Decoding the Enigma of Encrypted Network Traffic Classifiers*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00165)
  - 2025 | *TrafficFormer: An Efficient Pre-trained Model for Traffic Data*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00102)
  - 2024 | *Real-Time Website Fingerprinting Defense via Traffic Cluster Anonymization*, [`PDF`](https://doi.org/10.1109/sp54263.2024.00247)
  - 2023 | *Robust Multi-tab Website Fingerprinting Attacks in the Wild*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179464)
  - 2023 | *SoK: A Critical Evaluation of Efficient Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179289)
  - 2022 | *Surakav: Generating Realistic Traces for a Strong Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1109/sp46214.2022.9833722)

#### ACM CCS

  - 2025 | *Fingerprinting Deep Packet Inspection Devices by Their Ambiguities*, [`PDF`](https://doi.org/10.1145/3719027.3765145)
  - 2025 | *GAPDiS: Gradient-Assisted Perturbation Design via Sequence Editing for Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1145/3719027.3765084)
  - 2025 | *MM4flow: A Pre-trained Multi-modal Model for Versatile Network Traffic Analysis*, [`PDF`](https://doi.org/10.1145/3719027.3744804)
  - 2025 | *Swallow: A Transfer-Robust Website Fingerprinting Attack via Consistent Feature Learning*, [`PDF`](https://doi.org/10.1145/3719027.3744795)
  - 2025 | *Training Robust Classifiers for Classifying Encrypted Traffic under Dynamic Network Conditions*, [`PDF`](https://doi.org/10.1145/3719027.3765073)
  - 2025 | *Training with Only 1.0 ‰ Samples: Malicious Traffic Detection via Cross-Modality Feature Fusion*, [`PDF`](https://doi.org/10.1145/3719027.3765143)
  - 2024 | *Detecting Tunneled Flooding Traffic via Deep Semantic Analysis of Packet Length Patterns*, [`PDF`](https://doi.org/10.1145/3658644.3670353)
  - 2024 | *Robust and Reliable Early-Stage Website Fingerprinting Attacks via Spatial-Temporal Distribution Analysis*, [`PDF`](https://doi.org/10.1145/3658644.3670272)
  - 2024 | *Towards Fine-Grained Webpage Fingerprinting at Scale*, [`PDF`](https://doi.org/10.1145/3658644.3690211)
  - 2023 | *Point Cloud Analysis for ML-Based Malicious Traffic Detection: Reducing Majorities of False Positive Alarms*, [`PDF`](https://doi.org/10.1145/3576915.3616631)
  - 2023 | *Realistic Website Fingerprinting by Augmenting Network Traces*, [`PDF`](https://doi.org/10.1145/3576915.3616639)
  - 2023 | *Transformer-based Model for Multi-tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1145/3576915.3623107)
  - 2021 | *Realtime Robust Malicious Traffic Detection via Frequency Domain Analysis*, [`PDF`](https://doi.org/10.1145/3460120.3484585)
  - 2020 | *Censored Planet: An Internet-wide, Longitudinal Censorship Observatory*, [`PDF`](https://doi.org/10.1145/3372297.3417883)
  - 2020 | *TrafficSliver: Fighting Website Fingerprinting Attacks with Traffic Splitting*, [`PDF`](https://doi.org/10.1145/3372297.3423351)
  - 2018 | *Deep Fingerprinting: Undermining Website Fingerprinting Defenses with Deep Learning*, [`PDF`](https://doi.org/10.1145/3243734.3243768)

#### NDSS

  - 2026 | *A Hard-Label Black-Box Evasion Attack against ML-based Malicious Traffic Detection Systems*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/a-hard-label-black-box-evasion-attack-against-ml-based-malicious-traffic-detection-systems/)
  - 2026 | *Cease at the Ultimate Goodness: Towards Efficient Website Fingerprinting Defense via Iterative Mutual Information Minimization*, [`PDF`](https://doi.org/10.14722/ndss.2026.240786)
  - 2026 | *CELLSHIFT: RTT-Aware Trace Transduction for Real-World Website Fingerprinting*, [`PDF`](https://doi.org/10.14722/ndss.2026.231004)
  - 2026 | *Enhancing Website Fingerprinting Attacks against Traffic Drift*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/enhancing-website-fingerprinting-attacks-against-traffic-drift/)
  - 2026 | *Huma: Censorship Circumvention via Web Protocol Tunneling with Deferred Traffic Replacement*, [`PDF`](https://doi.org/10.14722/ndss.2026.240328)
  - 2026 | *Lightening the Load: A Cluster-Based Framework for A Lower-Overhead, Provable Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.14722/ndss.2026.241760)
  - 2025 | *The Discriminative Power of Cross-layer RTTs in Fingerprinting Proxy Traffic*, [`PDF`](https://doi.org/10.14722/ndss.2025.240966)
  - 2024 | *Flow Correlation Attacks on Tor Onion Service Sessions with Sliding Subset Sum*, [`PDF`](https://doi.org/10.14722/ndss.2024.24337)
  - 2024 | *Low-Quality Training Data Only? A Robust Framework for Detecting Encrypted Malicious Network Traffic*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/low-quality-training-data-only-a-robust-framework-for-detecting-encrypted-malicious-network-traffic/)
  - 2024 | *MirageFlow: A New Bandwidth Inflation Attack on Tor*, [`PDF`](https://doi.org/10.14722/ndss.2024.241133)
  - 2024 | *On Precisely Detecting Censorship Circumvention in Real-World Networks*, [`PDF`](https://doi.org/10.14722/ndss.2024.23394)
  - 2023 | *Detecting Unknown Encrypted Malicious Traffic in Real Time via Flow Interaction Graph Analysis*, [`PDF`](https://doi.org/10.14722/ndss.2023.23080)
  - 2021 | *Detecting Tor Bridge from Sampled Traffic in Backbone Networks*, [`PDF`](https://doi.org/10.14722/madweb.2021.23011)
  - 2020 | *Detecting Probe-resistant Proxies*, [`PDF`](https://doi.org/10.14722/ndss.2020.23087)
  - 2020 | *FLOWPRINT: Semi-Supervised Mobile-App Fingerprinting on Encrypted Network Traffic*, [`PDF`](https://github.com/Thijsvanede/Flowprint)

#### IEEE TIFS

  - 2026 | *End-to-End Open-Set Semi-Supervised Learning for Fine-Grained Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/TIFS.2026.3653575)
  - 2026 | *MT-DEGCL: Multi-Task Encrypted Traffic Classification With Dual Embedding and Graph Contrastive Learning*, [`PDF`](https://doi.org/10.1109/TIFS.2026.3664007)
  - 2025 | *Bottom Aggregating, Top Separating: An Aggregator and Separator Network for Encrypted Traffic Understanding*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3529316)
  - 2025 | *FG-SAT: Efficient Flow Graph for Encrypted Traffic Classification Under Environment Shifts*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3571663)
  - 2025 | *Proxied Traffic Fingerprinting for Hidden Service De-Anonymization With Burst Reshaping*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3588248)
  - 2025 | *Robust Detection of Malicious Encrypted Traffic via Contrastive Learning*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3560560)
  - 2025 | *WF-TFC: An Open-World Few-Shot Anonymous Website Fingerprinting via Time-Frequency Consistency*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3581092)
  - 2024 | *Inter-Flow Spatio-Temporal Correlation Analysis Based Website Fingerprinting Using Graph Neural Network*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3441935)
  - 2024 | *MPAF: Encrypted Traffic Classification With Multi-Phase Attribute Fingerprint*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3428839)
  - 2024 | *Multi-Level Resource-Coherented Graph Learning for Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3520014)
  - 2024 | *WFDefProxy: Real World Implementation and Evaluation of Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3327662)
  - 2023 | *Exploring Uncharted Waters of Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3342607)
  - 2022 | *Minipatch: Undermining DNN-Based Website Fingerprinting With Adversarial Patches*, [`PDF`](https://doi.org/10.1109/TIFS.2022.3186743)
  - 2021 | *Accurate Decentralized Application Identification via Encrypted Traffic Analysis Using Graph Neural Networks*, [`PDF`](https://doi.org/10.1109/TIFS.2021.3050608)
  - 2020 | *Fine-Grained Webpage Fingerprinting Using Only Packet Length Information of Encrypted Traffic*, [`PDF`](https://doi.org/10.1109/TIFS.2020.3046876)
  - 2018 | *Robust Smartphone App Identification via Encrypted Network Traffic Analysis*, [`PDF`](https://doi.org/10.1109/TIFS.2017.2737970)
  - 2017 | *Classification of Encrypted Traffic With Second-Order Markov Chains and Application Attribute Bigrams*, [`PDF`](https://doi.org/10.1109/TIFS.2017.2692682)

#### IEEE TDSC

  - 2026 | *Learning Flow Semantics via Contrastive Pre-training for Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/TDSC.2026.3677663)
  - 2026 | *WFCAT: Augmenting Website Fingerprinting With Channel-Wise Attention on Timing Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3605197)
  - 2025 | *DAIR-FedMoE: Hierarchical MoE for Federated Encrypted Traffic Classification under Compound Drift*, [`PDF`](https://doi.org/10.1109/tdsc.2026.3676447)
  - 2025 | *Few-Shot Website Fingerprinting With Distribution Calibration*, [`PDF`](https://doi.org/10.1109/TDSC.2024.3411014)
  - 2025 | *Toward an Effective Few-Shot Website Fingerprinting Attack With Quadruplet Networks and Deep Local Fingerprinting Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3563389)
  - 2022 | *An Automated Multi-Tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1109/TDSC.2021.3104869)
  - 2021 | *BiMorphing: A Bi-Directional Bursting Defense against Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/tdsc.2019.2907240)

#### IEEE/ACM ToN

  - 2026 | *Toward Robust Multi-Tab Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TON.2026.3666721)
  - 2025 | *High Precision and Efficient Anonymous Traffic Classification in the Real-World*, [`PDF`](https://doi.org/10.1109/TON.2024.3518976)
  - 2025 | *One Model Fits All Nodes: Neuron Activation Pattern Analysis-Based Attack Traffic Detection Framework for P2P Networks*, [`PDF`](https://doi.org/10.1109/TON.2025.3546735)
  - 2024 | *Flow Interaction Graph Analysis: Unknown Encrypted Malicious Traffic Detection*, [`PDF`](https://doi.org/10.1109/TNET.2024.3370851)
  - 2024 | *Website Fingerprinting on Encrypted Proxies: A Flow-Context-Aware Approach and Countermeasures*, [`PDF`](https://doi.org/10.1109/TNET.2023.3337270)
  - 2023 | *A Novel Multimodal Deep Learning Framework for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/TNET.2022.3215507)
  - 2023 | *A Two-Phase Approach to Fast and Accurate Classification of Encrypted Traffic*, [`PDF`](https://doi.org/10.1109/TNET.2022.3209979)
  - 2023 | *Frequency Domain Feature Based Robust Malicious Traffic Detection*, [`PDF`](https://doi.org/10.1109/TNET.2022.3195871)

#### IEEE INFOCOM

  - 2025 | *Cross-Environmental Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/INFOCOM55648.2025.11044569)
  - 2024 | *Causality Correlation and Context Learning Aided Robust Lightweight Multi-Tab Website Fingerprinting Over Encrypted Tunnel*, [`PDF`](https://doi.org/10.1109/infocom52122.2024.10621235)
  - 2019 | *FlowPic: Encrypted Internet Traffic Classification is as Easy as Image Recognition*, [`PDF`](https://ieeexplore.ieee.org/document/8845315)
  - 2019 | *FS-Net: A Flow Sequence Network For Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/infocom.2019.8737507)

#### ACM IMC

  - 2020 | *How China Detects and Blocks Shadowsocks*, [`PDF`](https://doi.org/10.1145/3419394.3423644)

#### ACM KDD

  - 2026 | *Building Transparency in Deep Learning-Powered Network Traffic Classification: A Traffic-Explainer Framework*, [`PDF`](https://arxiv.org/abs/2509.18007)
  - 2025 | *Wedjat: Detecting Sophisticated Evasion Attacks via Real-time Causal Analysis*, [`PDF`](https://doi.org/10.1145/3690624.3709218)
  - 2023 | *A Lightweight, Efficient and Explainable-by-Design Convolutional Neural Network for Internet Traffic Classification*, [`PDF`](https://doi.org/10.1145/3580305.3599762)

#### SIGCOMM

  - 2025 | *The Sweet Danger of Sugar: Debunking Representation Learning for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1145/3718958.3750498)
  - 2023 | *GGFAST: Automating Generation of Flexible Network Traffic Classifiers*, [`PDF`](https://doi.org/10.1145/3603269.3604840)

#### The Web Conference

  - 2025 | *DecETT: Accurate App Fingerprinting Under Encrypted Tunnels via Dual Decouple-based Semantic Enhancement*, [`PDF`](https://doi.org/10.1145/3696410.3714643)
  - 2024 | *AN-Net: an Anti-Noise Network for Anonymous Traffic Classification*, [`PDF`](https://doi.org/10.1145/3589334.3645691)
  - 2022 | *ET-BERT: A Contextualized Datagram Representation with Pre-training Transformers for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1145/3485447.3512217)

#### AAAI

  - 2025 | *MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2412.15306)
  - 2023 | *Yet Another Traffic Classifier: A Masked Autoencoder Based Traffic Transformer with Multi-Level Flow Representation*, [`PDF`](https://doi.org/10.1609/aaai.v37i4.25674)

#### NeurIPS

  - 2025 | *FlowRefiner: A Robust Traffic Classification Framework against Label Noise*, [`PDF`](https://papers.nips.cc/paper_files/paper/2025/hash/ba1d33849b963efc6b5d3082ad68f480-Abstract-Conference.html)
  - 2025 | *Gated Attention for Large Language Models: Non-linearity, Sparsity, and Attention-Sink-Free*, [`PDF`](https://arxiv.org/abs/2505.06708)

#### Computer Networks

  - 2026 | *A prototypical alignment approach to unknown traffic classification using BERT*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112062)
  - 2026 | *ByteDance: Let bytes perform brilliantly in multi-view encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2025.111843)
  - 2026 | *DenTC: An expandable framework for dynamic malicious traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112078)
  - 2026 | *GMM-cGAN: Mitigating data scarcity and label noise for robust encrypted malicious traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2025.111823)
  - 2026 | *Plug-in enhancement framework: Breaking through performance bottleneck of pre-trained models for encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112122)
  - 2026 | *Traffic burst relational graph attention network combined position encoding for traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112072)
  - 2023 | *Few-shot encrypted traffic classification via multi-task representation enhanced meta-learning*, [`PDF`](https://doi.org/10.1016/j.comnet.2023.109731)
  - 2018 | *An Efficient Feature Generation Approach Based on Deep Learning and Feature Selection Techniques for Traffic Classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2018.01.007)

#### Computers & Security

  - 2026 | *Hiding the Trees in the Forest: Building Network Covert Channels with Hash-Based Covert Carrier Filtering*, [`PDF`](https://doi.org/10.1016/j.cose.2026.104981)
  - 2023 | *Detection of Obfuscated Tor Traffic Based on Bidirectional Generative Adversarial Networks and Vision Transform*, [`PDF`](https://doi.org/10.1016/j.cose.2023.103512)

#### IEEE IoT Journal

  - 2026 | *NetTTT: Online Self-Adaptation Inference via Test-Time Training for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/jiot.2026.3652996)
  - 2025 | *A Detection Method for Malware Communication Traffic via Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/JIOT.2025.3577245)

#### IWQoS

  - 2025 | *MOTA: Mixture Of Traffic Agents for robust network traffic classification*, [`PDF`](https://doi.org/10.1109/iwqos65803.2025.11143417)
  - 2025 | *TraGe: A Generic Packet Representation for Traffic Classification Based on Header-Payload Differences*, [`PDF`](https://doi.org/10.1109/iwqos65803.2025.11143462)

#### arXiv

  - 2026 | *Bias in the Shadows: Explore Shortcuts in Encrypted Network Traffic Classification*, [`PDF`](https://doi.org/10.48550/arxiv.2601.10180)
  - 2026 | *DEMUX: Boundary-Aware Multi-Scale Traffic Demixing for Multi-Tab Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2604.15677)
  - 2026 | *More Than Meets the Eye: A Semantics-Aware Traffic Augmentation Framework for Generalizable Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2605.11402)
  - 2026 | *Multimodal Reasoning with LLM for Encrypted Traffic Interpretation: A Benchmark*, [`PDF`](https://arxiv.org/abs/2604.08140)
  - 2026 | *Nethira: A Heterogeneity-aware Hierarchical Pre-trained Model for Network Traffic Classification*, [`PDF`](https://doi.org/10.48550/arxiv.2601.22494)
  - 2026 | *NetMamba+: A Framework of Pre-trained Models for Efficient and Accurate Network Traffic Classification*, [`PDF`](https://arxiv.org/abs/2405.11449v3)
  - 2026 | *PrismWF: A Multi-Granularity Patch-Based Transformer for Robust Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.48550/arxiv.2603.21117)
  - 2026 | *Reality Check for Tor Website Fingerprinting in the Open World*, [`PDF`](https://arxiv.org/abs/2603.07412)
  - 2026 | *ResAware: Cross-Environment Website Fingerprinting via Resource-Privileged Distillation*, [`PDF`](https://arxiv.org/abs/2606.17462)
  - 2026 | *Talk Like a Packet: Rethinking Network Traffic Analysis with Transformer Foundation Models*, [`PDF`](https://doi.org/10.48550/arxiv.2602.06636)
  - 2026 | *The Inevitability of Side-Channel Leakage in Encrypted Traffic*, [`PDF`](https://arxiv.org/abs/2602.14055)
  - 2026 | *TrafficMoE: Heterogeneity-aware Mixture of Experts for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2603.29520)
  - 2026 | *Treat Traffic Like Trees: A Semantic-Preserving Hierarchical Graph-Based Expert Framework for Encrypted Traffic Analysis*, [`PDF`](https://arxiv.org/abs/2606.04517)
  - 2026 | *Where Do Flow Semantics Reside? A Protocol-Native Tabular Pretraining Paradigm for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2603.10051)
  - 2025 | *STAR: Semantic-Traffic Alignment and Retrieval for Zero-Shot HTTPS Website Fingerprinting*, [`PDF`](https://doi.org/10.48550/arxiv.2512.17667)
  - 2024 | *Discovering Command and Control (C2) Channels on Tor and Public Networks Using Reinforcement Learning*, [`PDF`](https://arxiv.org/abs/2402.09200)
  - 2024 | *NetMamba: Efficient Network Traffic Classification via Pre-training Unidirectional Mamba*, [`PDF`](https://arxiv.org/abs/2405.11449)
  - 2024 | *TrafficGPT: Breaking the Token Barrier for Efficient Long Traffic Analysis and Generation*, [`PDF`](https://arxiv.org/abs/2403.05822)

#### Other Journals and Conferences

  - 2026 | CCPE, *A Lightweight Deep Learning Framework for Encrypted Traffic Classification via Visual Flow Representation*, [`PDF`](https://doi.org/10.1002/cpe.70679)
  - 2026 | JKSU, *Bridging Packet and Session: Cross-Level Dual-Attention Networks for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1007/s44443-026-00470-7)
  - 2026 | Journal of Network and Systems Management, *FGFR-Net: An Improved Residual Network Encrypted Traffic Classification Model Based on Byte-Level Traffic Graphs*, [`PDF`](https://doi.org/10.1007/s10922-025-10011-8)
  - 2026 | IEEE TSC, *Time Will Tell: Criss-cross Transformer for Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/tsc.2026.3664705)
  - 2026 | IEEE TNSM, *TrafficAudio: Audio Representation for Lightweight Encrypted Traffic Classification in IoT*, [`PDF`](https://doi.org/10.1109/TNSM.2026.3651599)
  - 2026 | ICASSP, *TriFusion: A Self-Supervised Learning Enhanced Dual-Level Multimodal Framework for Traffic Classification*, [`PDF`](https://doi.org/10.1109/icassp55912.2026.11460777)
  - 2025 | ICAACE, *A Semi-Supervised Learning Framework for Encrypted Traffic Classification Based on Supervised Contrastive Learning and Masked Sequence Prediction Tasks*, [`PDF`](https://doi.org/10.1109/icaace65325.2025.11020246)
  - 2025 | AIA, *Enhancing DNS-over-HTTPS Traffic Classification in Heterogeneous Networks Through Latent Space Analysis with a Tabular-Variational Autoencoder and Self-Attention Classifier Model*, [`PDF`](https://doi.org/10.47852/bonviewAIA52025552)
  - 2025 | INCAS, *Malicious QUIC C2 Traffic Detection based on Random Forest in Programmable Data Plane*, [`PDF`](https://doi.org/10.1145/3769699.3771588)
  - 2025 | ESWA, *MET-LLM: Enhancing Large Language Models for Malicious Encrypted Traffic Detection*, [`PDF`](https://doi.org/10.1016/j.eswa.2025.130621)
  - 2025 | JPDC, *Multi-ARCL: Multimodal adaptive relay-based distributed continual learning for encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.jpdc.2025.105083)
  - 2024 | CNSM, *Experience Report: Using JA4+ Fingerprints for Malware Detection in Encrypted Traffic*, [`PDF`](https://doi.org/10.23919/cnsm62983.2024.10814358)
  - 2024 | FOCI, *Extended Abstract: Traffic Splitting for Pluggable Transports*, [`PDF`](https://petsymposium.org/foci/2024/foci-2024-0004.pdf)
  - 2024 | ICICS, *TorHunter: A Lightweight Method for Efficient Identification of Obfuscated Tor Traffic Through Unsupervised Pre-training*, [`PDF`](https://link.springer.com/chapter/10.1007/978-981-97-8801-9_1)
  - 2024 | Wireless Networks, *Updated Exploration of the Tor Network: Advertising, Availability and Protocols of Onion Services*, [`PDF`](https://link.springer.com/article/10.1007/s11276-024-03679-4)
  - 2022 | EITCE, *An Encrypted Traffic Classification Model Based on the Raw Traffic and Spatiotemporal Characteristics*, [`PDF`](https://doi.org/10.1145/3573428.3573644)
  - 2022 | IEEE TBD, *Identification of Encrypted Traffic Through Attention Mechanism Based Long Short Term Memory*, [`PDF`](https://doi.org/10.1109/TBDATA.2019.2940675)
  - 2022 | IEEE Communications Surveys & Tutorials, *Machine Learning-Powered Encrypted Network Traffic Analysis: A Comprehensive Survey*, [`PDF`](https://doi.org/10.1109/COMST.2022.3208196)
  - 2022 | HPCC, *MTBD: HTTPS Tunnel Detection Based on Multi-dimension Traffic Behaviors Decision*, [`PDF`](https://doi.org/10.1109/hpcc-dss-smartcity-dependsys57074.2022.00091)
  - 2022 | ICMLA, *Separating Flows in Encrypted Tunnel Traffic*, [`PDF`](https://doi.org/10.1109/ICMLA55696.2022.00094)
  - 2021 | ICEA, *Towards Comprehensive Analysis of Tor Hidden Service Access Behavior Identification Under Obfs4 Scenario*, [`PDF`](https://doi.org/10.1145/3491396.3506532)
  - 2019 | ICDIS, *Detection of Tor Traffic Hiding Under Obfs4 Protocol Based on Two-Level Filtering*, [`PDF`](https://ieeexplore.ieee.org/document/8855280)
  - 2018 | ICKII, *Tor Traffic Classification from Raw Packet Header using Convolutional Neural Network*, [`PDF`](https://ieeexplore.ieee.org/document/8569113)
  - 2017 | IEEE Big Data, *Tor Traffic Analysis and Detection via Machine Learning Techniques*, [`PDF`](https://ieeexplore.ieee.org/document/8258487)
  - 2008 | ICC, *Detection of Encrypted Tunnels across Network Boundaries*, [`PDF`](https://doi.org/10.1109/icc.2008.334)

***

### By Time

#### 2026

- ACM KDD, *Building Transparency in Deep Learning-Powered Network Traffic Classification: A Traffic-Explainer Framework*, [`PDF`](https://arxiv.org/abs/2509.18007)
- arXiv, *Bias in the Shadows: Explore Shortcuts in Encrypted Network Traffic Classification*, [`PDF`](https://doi.org/10.48550/arxiv.2601.10180)
- arXiv, *DEMUX: Boundary-Aware Multi-Scale Traffic Demixing for Multi-Tab Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2604.15677)
- arXiv, *More Than Meets the Eye: A Semantics-Aware Traffic Augmentation Framework for Generalizable Website Fingerprinting*, [`PDF`](https://arxiv.org/abs/2605.11402)
- arXiv, *Multimodal Reasoning with LLM for Encrypted Traffic Interpretation: A Benchmark*, [`PDF`](https://arxiv.org/abs/2604.08140)
- arXiv, *Nethira: A Heterogeneity-aware Hierarchical Pre-trained Model for Network Traffic Classification*, [`PDF`](https://doi.org/10.48550/arxiv.2601.22494)
- arXiv, *NetMamba+: A Framework of Pre-trained Models for Efficient and Accurate Network Traffic Classification*, [`PDF`](https://arxiv.org/abs/2405.11449v3)
- arXiv, *PrismWF: A Multi-Granularity Patch-Based Transformer for Robust Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.48550/arxiv.2603.21117)
- arXiv, *Reality Check for Tor Website Fingerprinting in the Open World*, [`PDF`](https://arxiv.org/abs/2603.07412)
- arXiv, *ResAware: Cross-Environment Website Fingerprinting via Resource-Privileged Distillation*, [`PDF`](https://arxiv.org/abs/2606.17462)
- arXiv, *Talk Like a Packet: Rethinking Network Traffic Analysis with Transformer Foundation Models*, [`PDF`](https://doi.org/10.48550/arxiv.2602.06636)
- arXiv, *The Inevitability of Side-Channel Leakage in Encrypted Traffic*, [`PDF`](https://arxiv.org/abs/2602.14055)
- arXiv, *TrafficMoE: Heterogeneity-aware Mixture of Experts for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2603.29520)
- arXiv, *Treat Traffic Like Trees: A Semantic-Preserving Hierarchical Graph-Based Expert Framework for Encrypted Traffic Analysis*, [`PDF`](https://arxiv.org/abs/2606.04517)
- arXiv, *Where Do Flow Semantics Reside? A Protocol-Native Tabular Pretraining Paradigm for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2603.10051)
- CCPE, *A Lightweight Deep Learning Framework for Encrypted Traffic Classification via Visual Flow Representation*, [`PDF`](https://doi.org/10.1002/cpe.70679)
- Computer Networks, *A prototypical alignment approach to unknown traffic classification using BERT*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112062)
- Computer Networks, *ByteDance: Let bytes perform brilliantly in multi-view encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2025.111843)
- Computer Networks, *DenTC: An expandable framework for dynamic malicious traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112078)
- Computer Networks, *GMM-cGAN: Mitigating data scarcity and label noise for robust encrypted malicious traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2025.111823)
- Computer Networks, *Plug-in enhancement framework: Breaking through performance bottleneck of pre-trained models for encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112122)
- Computer Networks, *Traffic burst relational graph attention network combined position encoding for traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112072)
- Computers & Security, *Hiding the Trees in the Forest: Building Network Covert Channels with Hash-Based Covert Carrier Filtering*, [`PDF`](https://doi.org/10.1016/j.cose.2026.104981)
- ICASSP, *TriFusion: A Self-Supervised Learning Enhanced Dual-Level Multimodal Framework for Traffic Classification*, [`PDF`](https://doi.org/10.1109/icassp55912.2026.11460777)
- IEEE IoT Journal, *NetTTT: Online Self-Adaptation Inference via Test-Time Training for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/jiot.2026.3652996)
- IEEE TDSC, *Learning Flow Semantics via Contrastive Pre-training for Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/TDSC.2026.3677663)
- IEEE TDSC, *WFCAT: Augmenting Website Fingerprinting With Channel-Wise Attention on Timing Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3605197)
- IEEE TIFS, *End-to-End Open-Set Semi-Supervised Learning for Fine-Grained Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/TIFS.2026.3653575)
- IEEE TIFS, *MT-DEGCL: Multi-Task Encrypted Traffic Classification With Dual Embedding and Graph Contrastive Learning*, [`PDF`](https://doi.org/10.1109/TIFS.2026.3664007)
- IEEE TNSM, *TrafficAudio: Audio Representation for Lightweight Encrypted Traffic Classification in IoT*, [`PDF`](https://doi.org/10.1109/TNSM.2026.3651599)
- IEEE TSC, *Time Will Tell: Criss-cross Transformer for Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/tsc.2026.3664705)
- IEEE/ACM ToN, *Toward Robust Multi-Tab Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TON.2026.3666721)
- JKSU, *Bridging Packet and Session: Cross-Level Dual-Attention Networks for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1007/s44443-026-00470-7)
- Journal of Network and Systems Management, *FGFR-Net: An Improved Residual Network Encrypted Traffic Classification Model Based on Byte-Level Traffic Graphs*, [`PDF`](https://doi.org/10.1007/s10922-025-10011-8)
- NDSS, *A Hard-Label Black-Box Evasion Attack against ML-based Malicious Traffic Detection Systems*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/a-hard-label-black-box-evasion-attack-against-ml-based-malicious-traffic-detection-systems/)
- NDSS, *Cease at the Ultimate Goodness: Towards Efficient Website Fingerprinting Defense via Iterative Mutual Information Minimization*, [`PDF`](https://doi.org/10.14722/ndss.2026.240786)
- NDSS, *CELLSHIFT: RTT-Aware Trace Transduction for Real-World Website Fingerprinting*, [`PDF`](https://doi.org/10.14722/ndss.2026.231004)
- NDSS, *Enhancing Website Fingerprinting Attacks against Traffic Drift*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/enhancing-website-fingerprinting-attacks-against-traffic-drift/)
- NDSS, *Huma: Censorship Circumvention via Web Protocol Tunneling with Deferred Traffic Replacement*, [`PDF`](https://doi.org/10.14722/ndss.2026.240328)
- NDSS, *Lightening the Load: A Cluster-Based Framework for A Lower-Overhead, Provable Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.14722/ndss.2026.241760)

#### 2025

- AAAI, *MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2412.15306)
- ACM CCS, *Fingerprinting Deep Packet Inspection Devices by Their Ambiguities*, [`PDF`](https://doi.org/10.1145/3719027.3765145)
- ACM CCS, *GAPDiS: Gradient-Assisted Perturbation Design via Sequence Editing for Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1145/3719027.3765084)
- ACM CCS, *MM4flow: A Pre-trained Multi-modal Model for Versatile Network Traffic Analysis*, [`PDF`](https://doi.org/10.1145/3719027.3744804)
- ACM CCS, *Swallow: A Transfer-Robust Website Fingerprinting Attack via Consistent Feature Learning*, [`PDF`](https://doi.org/10.1145/3719027.3744795)
- ACM CCS, *Training Robust Classifiers for Classifying Encrypted Traffic under Dynamic Network Conditions*, [`PDF`](https://doi.org/10.1145/3719027.3765073)
- ACM CCS, *Training with Only 1.0 ‰ Samples: Malicious Traffic Detection via Cross-Modality Feature Fusion*, [`PDF`](https://doi.org/10.1145/3719027.3765143)
- ACM KDD, *Wedjat: Detecting Sophisticated Evasion Attacks via Real-time Causal Analysis*, [`PDF`](https://doi.org/10.1145/3690624.3709218)
- AIA, *Enhancing DNS-over-HTTPS Traffic Classification in Heterogeneous Networks Through Latent Space Analysis with a Tabular-Variational Autoencoder and Self-Attention Classifier Model*, [`PDF`](https://doi.org/10.47852/bonviewAIA52025552)
- arXiv, *STAR: Semantic-Traffic Alignment and Retrieval for Zero-Shot HTTPS Website Fingerprinting*, [`PDF`](https://doi.org/10.48550/arxiv.2512.17667)
- ESWA, *MET-LLM: Enhancing Large Language Models for Malicious Encrypted Traffic Detection*, [`PDF`](https://doi.org/10.1016/j.eswa.2025.130621)
- ICAACE, *A Semi-Supervised Learning Framework for Encrypted Traffic Classification Based on Supervised Contrastive Learning and Masked Sequence Prediction Tasks*, [`PDF`](https://doi.org/10.1109/icaace65325.2025.11020246)
- IEEE INFOCOM, *Cross-Environmental Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/INFOCOM55648.2025.11044569)
- IEEE IoT Journal, *A Detection Method for Malware Communication Traffic via Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/JIOT.2025.3577245)
- IEEE S&P, *COUNTMAMBA: A Generalized Website Fingerprinting Attack via Coarse-Grained Representation and Fine-Grained Prediction*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00154)
- IEEE S&P, *SoK: Decoding the Enigma of Encrypted Network Traffic Classifiers*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00165)
- IEEE S&P, *TrafficFormer: An Efficient Pre-trained Model for Traffic Data*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00102)
- IEEE TDSC, *DAIR-FedMoE: Hierarchical MoE for Federated Encrypted Traffic Classification under Compound Drift*, [`PDF`](https://doi.org/10.1109/tdsc.2026.3676447)
- IEEE TDSC, *Few-Shot Website Fingerprinting With Distribution Calibration*, [`PDF`](https://doi.org/10.1109/TDSC.2024.3411014)
- IEEE TDSC, *Toward an Effective Few-Shot Website Fingerprinting Attack With Quadruplet Networks and Deep Local Fingerprinting Features*, [`PDF`](https://doi.org/10.1109/TDSC.2025.3563389)
- IEEE TIFS, *Bottom Aggregating, Top Separating: An Aggregator and Separator Network for Encrypted Traffic Understanding*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3529316)
- IEEE TIFS, *FG-SAT: Efficient Flow Graph for Encrypted Traffic Classification Under Environment Shifts*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3571663)
- IEEE TIFS, *Proxied Traffic Fingerprinting for Hidden Service De-Anonymization With Burst Reshaping*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3588248)
- IEEE TIFS, *Robust Detection of Malicious Encrypted Traffic via Contrastive Learning*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3560560)
- IEEE TIFS, *WF-TFC: An Open-World Few-Shot Anonymous Website Fingerprinting via Time-Frequency Consistency*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3581092)
- IEEE/ACM ToN, *High Precision and Efficient Anonymous Traffic Classification in the Real-World*, [`PDF`](https://doi.org/10.1109/TON.2024.3518976)
- IEEE/ACM ToN, *One Model Fits All Nodes: Neuron Activation Pattern Analysis-Based Attack Traffic Detection Framework for P2P Networks*, [`PDF`](https://doi.org/10.1109/TON.2025.3546735)
- INCAS, *Malicious QUIC C2 Traffic Detection based on Random Forest in Programmable Data Plane*, [`PDF`](https://doi.org/10.1145/3769699.3771588)
- IWQoS, *MOTA: Mixture Of Traffic Agents for robust network traffic classification*, [`PDF`](https://doi.org/10.1109/iwqos65803.2025.11143417)
- IWQoS, *TraGe: A Generic Packet Representation for Traffic Classification Based on Header-Payload Differences*, [`PDF`](https://doi.org/10.1109/iwqos65803.2025.11143462)
- JPDC, *Multi-ARCL: Multimodal adaptive relay-based distributed continual learning for encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.jpdc.2025.105083)
- NDSS, *The Discriminative Power of Cross-layer RTTs in Fingerprinting Proxy Traffic*, [`PDF`](https://doi.org/10.14722/ndss.2025.240966)
- NeurIPS, *FlowRefiner: A Robust Traffic Classification Framework against Label Noise*, [`PDF`](https://papers.nips.cc/paper_files/paper/2025/hash/ba1d33849b963efc6b5d3082ad68f480-Abstract-Conference.html)
- NeurIPS, *Gated Attention for Large Language Models: Non-linearity, Sparsity, and Attention-Sink-Free*, [`PDF`](https://arxiv.org/abs/2505.06708)
- SIGCOMM, *The Sweet Danger of Sugar: Debunking Representation Learning for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1145/3718958.3750498)
- The Web Conference, *DecETT: Accurate App Fingerprinting Under Encrypted Tunnels via Dual Decouple-based Semantic Enhancement*, [`PDF`](https://doi.org/10.1145/3696410.3714643)
- USENIX Security, *Censorship Evasion with Unidentified Protocol Generation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/wails)
- USENIX Security, *CertTA: Certified Robustness Made Practical for Learning-Based Traffic Analysis*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/yan-jinzhu)

#### 2024

- ACM CCS, *Detecting Tunneled Flooding Traffic via Deep Semantic Analysis of Packet Length Patterns*, [`PDF`](https://doi.org/10.1145/3658644.3670353)
- ACM CCS, *Robust and Reliable Early-Stage Website Fingerprinting Attacks via Spatial-Temporal Distribution Analysis*, [`PDF`](https://doi.org/10.1145/3658644.3670272)
- ACM CCS, *Towards Fine-Grained Webpage Fingerprinting at Scale*, [`PDF`](https://doi.org/10.1145/3658644.3690211)
- arXiv, *Discovering Command and Control (C2) Channels on Tor and Public Networks Using Reinforcement Learning*, [`PDF`](https://arxiv.org/abs/2402.09200)
- arXiv, *NetMamba: Efficient Network Traffic Classification via Pre-training Unidirectional Mamba*, [`PDF`](https://arxiv.org/abs/2405.11449)
- arXiv, *TrafficGPT: Breaking the Token Barrier for Efficient Long Traffic Analysis and Generation*, [`PDF`](https://arxiv.org/abs/2403.05822)
- CNSM, *Experience Report: Using JA4+ Fingerprints for Malware Detection in Encrypted Traffic*, [`PDF`](https://doi.org/10.23919/cnsm62983.2024.10814358)
- FOCI, *Extended Abstract: Traffic Splitting for Pluggable Transports*, [`PDF`](https://petsymposium.org/foci/2024/foci-2024-0004.pdf)
- ICICS, *TorHunter: A Lightweight Method for Efficient Identification of Obfuscated Tor Traffic Through Unsupervised Pre-training*, [`PDF`](https://link.springer.com/chapter/10.1007/978-981-97-8801-9_1)
- IEEE INFOCOM, *Causality Correlation and Context Learning Aided Robust Lightweight Multi-Tab Website Fingerprinting Over Encrypted Tunnel*, [`PDF`](https://doi.org/10.1109/infocom52122.2024.10621235)
- IEEE S&P, *Real-Time Website Fingerprinting Defense via Traffic Cluster Anonymization*, [`PDF`](https://doi.org/10.1109/sp54263.2024.00247)
- IEEE TIFS, *Inter-Flow Spatio-Temporal Correlation Analysis Based Website Fingerprinting Using Graph Neural Network*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3441935)
- IEEE TIFS, *MPAF: Encrypted Traffic Classification With Multi-Phase Attribute Fingerprint*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3428839)
- IEEE TIFS, *Multi-Level Resource-Coherented Graph Learning for Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3520014)
- IEEE TIFS, *WFDefProxy: Real World Implementation and Evaluation of Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3327662)
- IEEE/ACM ToN, *Flow Interaction Graph Analysis: Unknown Encrypted Malicious Traffic Detection*, [`PDF`](https://doi.org/10.1109/TNET.2024.3370851)
- IEEE/ACM ToN, *Website Fingerprinting on Encrypted Proxies: A Flow-Context-Aware Approach and Countermeasures*, [`PDF`](https://doi.org/10.1109/TNET.2023.3337270)
- NDSS, *Flow Correlation Attacks on Tor Onion Service Sessions with Sliding Subset Sum*, [`PDF`](https://doi.org/10.14722/ndss.2024.24337)
- NDSS, *Low-Quality Training Data Only? A Robust Framework for Detecting Encrypted Malicious Network Traffic*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/low-quality-training-data-only-a-robust-framework-for-detecting-encrypted-malicious-network-traffic/)
- NDSS, *MirageFlow: A New Bandwidth Inflation Attack on Tor*, [`PDF`](https://doi.org/10.14722/ndss.2024.241133)
- NDSS, *On Precisely Detecting Censorship Circumvention in Real-World Networks*, [`PDF`](https://doi.org/10.14722/ndss.2024.23394)
- The Web Conference, *AN-Net: an Anti-Noise Network for Anonymous Traffic Classification*, [`PDF`](https://doi.org/10.1145/3589334.3645691)
- USENIX Security, *Fingerprinting Obfuscated Proxy Traffic with Encapsulated TLS Handshakes*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/xue-fingerprinting)
- USENIX Security, *GFWeb: Measuring the Great Firewall’s Web Censorship at Scale*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/hoang)
- USENIX Security, *OpenVPN is Open to VPN Fingerprinting*, [`PDF`](https://doi.org/10.1145/3618117)
- USENIX Security, *Stop! Don't Click Here Anymore: Boosting Website Fingerprinting By Considering Sets of Subpages*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/mitseva)
- Wireless Networks, *Updated Exploration of the Tor Network: Advertising, Availability and Protocols of Onion Services*, [`PDF`](https://link.springer.com/article/10.1007/s11276-024-03679-4)

#### 2023

- AAAI, *Yet Another Traffic Classifier: A Masked Autoencoder Based Traffic Transformer with Multi-Level Flow Representation*, [`PDF`](https://doi.org/10.1609/aaai.v37i4.25674)
- ACM CCS, *Point Cloud Analysis for ML-Based Malicious Traffic Detection: Reducing Majorities of False Positive Alarms*, [`PDF`](https://doi.org/10.1145/3576915.3616631)
- ACM CCS, *Realistic Website Fingerprinting by Augmenting Network Traces*, [`PDF`](https://doi.org/10.1145/3576915.3616639)
- ACM CCS, *Transformer-based Model for Multi-tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1145/3576915.3623107)
- ACM KDD, *A Lightweight, Efficient and Explainable-by-Design Convolutional Neural Network for Internet Traffic Classification*, [`PDF`](https://doi.org/10.1145/3580305.3599762)
- Computer Networks, *Few-shot encrypted traffic classification via multi-task representation enhanced meta-learning*, [`PDF`](https://doi.org/10.1016/j.comnet.2023.109731)
- Computers & Security, *Detection of Obfuscated Tor Traffic Based on Bidirectional Generative Adversarial Networks and Vision Transform*, [`PDF`](https://doi.org/10.1016/j.cose.2023.103512)
- IEEE S&P, *Robust Multi-tab Website Fingerprinting Attacks in the Wild*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179464)
- IEEE S&P, *SoK: A Critical Evaluation of Efficient Website Fingerprinting Defenses*, [`PDF`](https://doi.org/10.1109/sp46215.2023.10179289)
- IEEE TIFS, *Exploring Uncharted Waters of Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3342607)
- IEEE/ACM ToN, *A Novel Multimodal Deep Learning Framework for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/TNET.2022.3215507)
- IEEE/ACM ToN, *A Two-Phase Approach to Fast and Accurate Classification of Encrypted Traffic*, [`PDF`](https://doi.org/10.1109/TNET.2022.3209979)
- IEEE/ACM ToN, *Frequency Domain Feature Based Robust Malicious Traffic Detection*, [`PDF`](https://doi.org/10.1109/TNET.2022.3195871)
- NDSS, *Detecting Unknown Encrypted Malicious Traffic in Real Time via Flow Interaction Graph Analysis*, [`PDF`](https://doi.org/10.14722/ndss.2023.23080)
- SIGCOMM, *GGFAST: Automating Generation of Flexible Network Traffic Classifiers*, [`PDF`](https://doi.org/10.1145/3603269.3604840)
- USENIX Security, *How the Great Firewall of China Detects and Blocks Fully Encrypted Traffic*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/wu-mingshi)
- USENIX Security, *Subverting Website Fingerprinting Defenses with Robust Traffic Representation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/shen-meng)

#### 2022

- EITCE, *An Encrypted Traffic Classification Model Based on the Raw Traffic and Spatiotemporal Characteristics*, [`PDF`](https://doi.org/10.1145/3573428.3573644)
- HPCC, *MTBD: HTTPS Tunnel Detection Based on Multi-dimension Traffic Behaviors Decision*, [`PDF`](https://doi.org/10.1109/hpcc-dss-smartcity-dependsys57074.2022.00091)
- ICMLA, *Separating Flows in Encrypted Tunnel Traffic*, [`PDF`](https://doi.org/10.1109/ICMLA55696.2022.00094)
- IEEE Communications Surveys & Tutorials, *Machine Learning-Powered Encrypted Network Traffic Analysis: A Comprehensive Survey*, [`PDF`](https://doi.org/10.1109/COMST.2022.3208196)
- IEEE S&P, *Surakav: Generating Realistic Traces for a Strong Website Fingerprinting Defense*, [`PDF`](https://doi.org/10.1109/sp46214.2022.9833722)
- IEEE TBD, *Identification of Encrypted Traffic Through Attention Mechanism Based Long Short Term Memory*, [`PDF`](https://doi.org/10.1109/TBDATA.2019.2940675)
- IEEE TDSC, *An Automated Multi-Tab Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.1109/TDSC.2021.3104869)
- IEEE TIFS, *Minipatch: Undermining DNN-Based Website Fingerprinting With Adversarial Patches*, [`PDF`](https://doi.org/10.1109/TIFS.2022.3186743)
- The Web Conference, *ET-BERT: A Contextualized Datagram Representation with Pre-training Transformers for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1145/3485447.3512217)
- USENIX Security, *Off-Path Network Traffic Manipulation via Revitalized ICMP Redirect Attacks*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/feng)
- USENIX Security, *Online Website Fingerprinting: Evaluating Website Fingerprinting Attacks on Tor in the Real World*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/cherubin)

#### 2021

- ACM CCS, *Realtime Robust Malicious Traffic Detection via Frequency Domain Analysis*, [`PDF`](https://doi.org/10.1145/3460120.3484585)
- ICEA, *Towards Comprehensive Analysis of Tor Hidden Service Access Behavior Identification Under Obfs4 Scenario*, [`PDF`](https://doi.org/10.1145/3491396.3506532)
- IEEE TDSC, *BiMorphing: A Bi-Directional Bursting Defense against Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/tdsc.2019.2907240)
- IEEE TIFS, *Accurate Decentralized Application Identification via Encrypted Traffic Analysis Using Graph Neural Networks*, [`PDF`](https://doi.org/10.1109/TIFS.2021.3050608)
- NDSS, *Detecting Tor Bridge from Sampled Traffic in Backbone Networks*, [`PDF`](https://doi.org/10.14722/madweb.2021.23011)
- USENIX Security, *Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations*, [`PDF`](https://www.usenix.org/system/files/sec21-nasr.pdf)
- USENIX Security, *LZR: Identifying Unexpected Internet Services*, [`PDF`](https://www.usenix.org/conference/usenixsecurity21/presentation/izhikevich)

#### 2020

- ACM CCS, *Censored Planet: An Internet-wide, Longitudinal Censorship Observatory*, [`PDF`](https://doi.org/10.1145/3372297.3417883)
- ACM CCS, *TrafficSliver: Fighting Website Fingerprinting Attacks with Traffic Splitting*, [`PDF`](https://doi.org/10.1145/3372297.3423351)
- ACM IMC, *How China Detects and Blocks Shadowsocks*, [`PDF`](https://doi.org/10.1145/3419394.3423644)
- IEEE TIFS, *Fine-Grained Webpage Fingerprinting Using Only Packet Length Information of Encrypted Traffic*, [`PDF`](https://doi.org/10.1109/TIFS.2020.3046876)
- NDSS, *Detecting Probe-resistant Proxies*, [`PDF`](https://doi.org/10.14722/ndss.2020.23087)
- NDSS, *FLOWPRINT: Semi-Supervised Mobile-App Fingerprinting on Encrypted Network Traffic*, [`PDF`](https://github.com/Thijsvanede/Flowprint)
- USENIX Security, *Zero-delay Lightweight Defenses against Website Fingerprinting*, [`PDF`](https://www.usenix.org/conference/usenixsecurity20/presentation/gong)

#### 2019

- ICDIS, *Detection of Tor Traffic Hiding Under Obfs4 Protocol Based on Two-Level Filtering*, [`PDF`](https://ieeexplore.ieee.org/document/8855280)
- IEEE INFOCOM, *FlowPic: Encrypted Internet Traffic Classification is as Easy as Image Recognition*, [`PDF`](https://ieeexplore.ieee.org/document/8845315)
- IEEE INFOCOM, *FS-Net: A Flow Sequence Network For Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/infocom.2019.8737507)

#### 2018

- ACM CCS, *Deep Fingerprinting: Undermining Website Fingerprinting Defenses with Deep Learning*, [`PDF`](https://doi.org/10.1145/3243734.3243768)
- Computer Networks, *An Efficient Feature Generation Approach Based on Deep Learning and Feature Selection Techniques for Traffic Classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2018.01.007)
- ICKII, *Tor Traffic Classification from Raw Packet Header using Convolutional Neural Network*, [`PDF`](https://ieeexplore.ieee.org/document/8569113)
- IEEE TIFS, *Robust Smartphone App Identification via Encrypted Network Traffic Analysis*, [`PDF`](https://doi.org/10.1109/TIFS.2017.2737970)

#### 2017

- IEEE Big Data, *Tor Traffic Analysis and Detection via Machine Learning Techniques*, [`PDF`](https://ieeexplore.ieee.org/document/8258487)
- IEEE TIFS, *Classification of Encrypted Traffic With Second-Order Markov Chains and Application Attribute Bigrams*, [`PDF`](https://doi.org/10.1109/TIFS.2017.2692682)

#### 2008

- ICC, *Detection of Encrypted Tunnels across Network Boundaries*, [`PDF`](https://doi.org/10.1109/icc.2008.334)

***

### By Topic

Each paper is assigned to one primary topic to keep this view concise.

#### Website Fingerprinting Attacks

- 2026 | arXiv, *PrismWF: A Multi-Granularity Patch-Based Transformer for Robust Website Fingerprinting Attack*, [`PDF`](https://doi.org/10.48550/arxiv.2603.21117)
- 2025 | IEEE S&P, *COUNTMAMBA: A Generalized Website Fingerprinting Attack via Coarse-Grained Representation and Fine-Grained Prediction*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00154)
- 2025 | IEEE TIFS, *Proxied Traffic Fingerprinting for Hidden Service De-Anonymization With Burst Reshaping*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3588248)
- 2025 | arXiv, *STAR: Semantic-Traffic Alignment and Retrieval for Zero-Shot HTTPS Website Fingerprinting*, [`PDF`](https://doi.org/10.48550/arxiv.2512.17667)
- 2025 | ACM CCS, *Swallow: A Transfer-Robust Website Fingerprinting Attack via Consistent Feature Learning*, [`PDF`](https://doi.org/10.1145/3719027.3744795)
- 2024 | IEEE TIFS, *Inter-Flow Spatio-Temporal Correlation Analysis Based Website Fingerprinting Using Graph Neural Network*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3441935)
- 2024 | IEEE TIFS, *Multi-Level Resource-Coherented Graph Learning for Website Fingerprinting Attacks*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3520014)
- 2024 | ACM CCS, *Towards Fine-Grained Webpage Fingerprinting at Scale*, [`PDF`](https://doi.org/10.1145/3658644.3690211)
- 2024 | IEEE/ACM ToN, *Website Fingerprinting on Encrypted Proxies: A Flow-Context-Aware Approach and Countermeasures*, [`PDF`](https://doi.org/10.1109/TNET.2023.3337270)
- 2023 | IEEE TIFS, *Exploring Uncharted Waters of Website Fingerprinting*, [`PDF`](https://doi.org/10.1109/TIFS.2023.3342607)
- 2023 | ACM CCS, *Realistic Website Fingerprinting by Augmenting Network Traces*, [`PDF`](https://doi.org/10.1145/3576915.3616639)
- 2023 | USENIX Security, *Subverting Website Fingerprinting Defenses with Robust Traffic Representation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/shen-meng)
- 2020 | IEEE TIFS, *Fine-Grained Webpage Fingerprinting Using Only Packet Length Information of Encrypted Traffic*, [`PDF`](https://doi.org/10.1109/TIFS.2020.3046876)
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

#### Multi-Tab, Open-World, and Real-World Website Fingerprinting

- 2026 | NDSS, *CELLSHIFT: RTT-Aware Trace Transduction for Real-World Website Fingerprinting*, [`PDF`](https://doi.org/10.14722/ndss.2026.231004)
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

#### Tor, Onion Services, Proxy, VPN, and Anonymous Traffic Analysis

- 2025 | IEEE/ACM ToN, *High Precision and Efficient Anonymous Traffic Classification in the Real-World*, [`PDF`](https://doi.org/10.1109/TON.2024.3518976)
- 2025 | NDSS, *The Discriminative Power of Cross-layer RTTs in Fingerprinting Proxy Traffic*, [`PDF`](https://doi.org/10.14722/ndss.2025.240966)
- 2024 | The Web Conference, *AN-Net: an Anti-Noise Network for Anonymous Traffic Classification*, [`PDF`](https://doi.org/10.1145/3589334.3645691)
- 2024 | arXiv, *Discovering Command and Control (C2) Channels on Tor and Public Networks Using Reinforcement Learning*, [`PDF`](https://arxiv.org/abs/2402.09200)
- 2024 | USENIX Security, *Fingerprinting Obfuscated Proxy Traffic with Encapsulated TLS Handshakes*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/xue-fingerprinting)
- 2024 | NDSS, *Flow Correlation Attacks on Tor Onion Service Sessions with Sliding Subset Sum*, [`PDF`](https://doi.org/10.14722/ndss.2024.24337)
- 2024 | NDSS, *MirageFlow: A New Bandwidth Inflation Attack on Tor*, [`PDF`](https://doi.org/10.14722/ndss.2024.241133)
- 2024 | USENIX Security, *OpenVPN is Open to VPN Fingerprinting*, [`PDF`](https://doi.org/10.1145/3618117)
- 2024 | ICICS, *TorHunter: A Lightweight Method for Efficient Identification of Obfuscated Tor Traffic Through Unsupervised Pre-training*, [`PDF`](https://link.springer.com/chapter/10.1007/978-981-97-8801-9_1)
- 2024 | Wireless Networks, *Updated Exploration of the Tor Network: Advertising, Availability and Protocols of Onion Services*, [`PDF`](https://link.springer.com/article/10.1007/s11276-024-03679-4)
- 2023 | Computers & Security, *Detection of Obfuscated Tor Traffic Based on Bidirectional Generative Adversarial Networks and Vision Transform*, [`PDF`](https://doi.org/10.1016/j.cose.2023.103512)
- 2021 | NDSS, *Detecting Tor Bridge from Sampled Traffic in Backbone Networks*, [`PDF`](https://doi.org/10.14722/madweb.2021.23011)
- 2021 | ICEA, *Towards Comprehensive Analysis of Tor Hidden Service Access Behavior Identification Under Obfs4 Scenario*, [`PDF`](https://doi.org/10.1145/3491396.3506532)
- 2020 | NDSS, *Detecting Probe-resistant Proxies*, [`PDF`](https://doi.org/10.14722/ndss.2020.23087)
- 2020 | ACM IMC, *How China Detects and Blocks Shadowsocks*, [`PDF`](https://doi.org/10.1145/3419394.3423644)
- 2019 | ICDIS, *Detection of Tor Traffic Hiding Under Obfs4 Protocol Based on Two-Level Filtering*, [`PDF`](https://ieeexplore.ieee.org/document/8855280)
- 2018 | ICKII, *Tor Traffic Classification from Raw Packet Header using Convolutional Neural Network*, [`PDF`](https://ieeexplore.ieee.org/document/8569113)
- 2017 | IEEE Big Data, *Tor Traffic Analysis and Detection via Machine Learning Techniques*, [`PDF`](https://ieeexplore.ieee.org/document/8258487)

#### Censorship Measurement, Circumvention, and Covert Channels

- 2026 | Computers & Security, *Hiding the Trees in the Forest: Building Network Covert Channels with Hash-Based Covert Carrier Filtering*, [`PDF`](https://doi.org/10.1016/j.cose.2026.104981)
- 2026 | NDSS, *Huma: Censorship Circumvention via Web Protocol Tunneling with Deferred Traffic Replacement*, [`PDF`](https://doi.org/10.14722/ndss.2026.240328)
- 2025 | USENIX Security, *Censorship Evasion with Unidentified Protocol Generation*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/wails)
- 2024 | FOCI, *Extended Abstract: Traffic Splitting for Pluggable Transports*, [`PDF`](https://petsymposium.org/foci/2024/foci-2024-0004.pdf)
- 2024 | USENIX Security, *GFWeb: Measuring the Great Firewall’s Web Censorship at Scale*, [`PDF`](https://www.usenix.org/conference/usenixsecurity24/presentation/hoang)
- 2024 | NDSS, *On Precisely Detecting Censorship Circumvention in Real-World Networks*, [`PDF`](https://doi.org/10.14722/ndss.2024.23394)
- 2023 | USENIX Security, *How the Great Firewall of China Detects and Blocks Fully Encrypted Traffic*, [`PDF`](https://www.usenix.org/conference/usenixsecurity23/presentation/wu-mingshi)
- 2020 | ACM CCS, *Censored Planet: An Internet-wide, Longitudinal Censorship Observatory*, [`PDF`](https://doi.org/10.1145/3372297.3417883)

#### Malicious Traffic, C2, Anomaly, and Attack Detection

- 2026 | NDSS, *A Hard-Label Black-Box Evasion Attack against ML-based Malicious Traffic Detection Systems*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/a-hard-label-black-box-evasion-attack-against-ml-based-malicious-traffic-detection-systems/)
- 2026 | Computer Networks, *DenTC: An expandable framework for dynamic malicious traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112078)
- 2026 | Computer Networks, *GMM-cGAN: Mitigating data scarcity and label noise for robust encrypted malicious traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2025.111823)
- 2025 | IEEE IoT Journal, *A Detection Method for Malware Communication Traffic via Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/JIOT.2025.3577245)
- 2025 | INCAS, *Malicious QUIC C2 Traffic Detection based on Random Forest in Programmable Data Plane*, [`PDF`](https://doi.org/10.1145/3769699.3771588)
- 2025 | ESWA, *MET-LLM: Enhancing Large Language Models for Malicious Encrypted Traffic Detection*, [`PDF`](https://doi.org/10.1016/j.eswa.2025.130621)
- 2025 | IEEE/ACM ToN, *One Model Fits All Nodes: Neuron Activation Pattern Analysis-Based Attack Traffic Detection Framework for P2P Networks*, [`PDF`](https://doi.org/10.1109/TON.2025.3546735)
- 2025 | IEEE TIFS, *Robust Detection of Malicious Encrypted Traffic via Contrastive Learning*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3560560)
- 2025 | ACM CCS, *Training with Only 1.0 ‰ Samples: Malicious Traffic Detection via Cross-Modality Feature Fusion*, [`PDF`](https://doi.org/10.1145/3719027.3765143)
- 2025 | ACM KDD, *Wedjat: Detecting Sophisticated Evasion Attacks via Real-time Causal Analysis*, [`PDF`](https://doi.org/10.1145/3690624.3709218)
- 2024 | ACM CCS, *Detecting Tunneled Flooding Traffic via Deep Semantic Analysis of Packet Length Patterns*, [`PDF`](https://doi.org/10.1145/3658644.3670353)
- 2024 | CNSM, *Experience Report: Using JA4+ Fingerprints for Malware Detection in Encrypted Traffic*, [`PDF`](https://doi.org/10.23919/cnsm62983.2024.10814358)
- 2024 | IEEE/ACM ToN, *Flow Interaction Graph Analysis: Unknown Encrypted Malicious Traffic Detection*, [`PDF`](https://doi.org/10.1109/TNET.2024.3370851)
- 2024 | NDSS, *Low-Quality Training Data Only? A Robust Framework for Detecting Encrypted Malicious Network Traffic*, [`PDF`](https://www.ndss-symposium.org/ndss-paper/low-quality-training-data-only-a-robust-framework-for-detecting-encrypted-malicious-network-traffic/)
- 2023 | NDSS, *Detecting Unknown Encrypted Malicious Traffic in Real Time via Flow Interaction Graph Analysis*, [`PDF`](https://doi.org/10.14722/ndss.2023.23080)
- 2023 | IEEE/ACM ToN, *Frequency Domain Feature Based Robust Malicious Traffic Detection*, [`PDF`](https://doi.org/10.1109/TNET.2022.3195871)
- 2023 | ACM CCS, *Point Cloud Analysis for ML-Based Malicious Traffic Detection: Reducing Majorities of False Positive Alarms*, [`PDF`](https://doi.org/10.1145/3576915.3616631)
- 2021 | ACM CCS, *Realtime Robust Malicious Traffic Detection via Frequency Domain Analysis*, [`PDF`](https://doi.org/10.1145/3460120.3484585)

#### Encrypted Traffic Classification and Application Identification

- 2026 | JKSU, *Bridging Packet and Session: Cross-Level Dual-Attention Networks for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1007/s44443-026-00470-7)
- 2025 | IEEE TIFS, *Bottom Aggregating, Top Separating: An Aggregator and Separator Network for Encrypted Traffic Understanding*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3529316)
- 2024 | IEEE TIFS, *MPAF: Encrypted Traffic Classification With Multi-Phase Attribute Fingerprint*, [`PDF`](https://doi.org/10.1109/TIFS.2024.3428839)
- 2023 | IEEE/ACM ToN, *A Two-Phase Approach to Fast and Accurate Classification of Encrypted Traffic*, [`PDF`](https://doi.org/10.1109/TNET.2022.3209979)
- 2023 | SIGCOMM, *GGFAST: Automating Generation of Flexible Network Traffic Classifiers*, [`PDF`](https://doi.org/10.1145/3603269.3604840)
- 2022 | EITCE, *An Encrypted Traffic Classification Model Based on the Raw Traffic and Spatiotemporal Characteristics*, [`PDF`](https://doi.org/10.1145/3573428.3573644)
- 2022 | IEEE TBD, *Identification of Encrypted Traffic Through Attention Mechanism Based Long Short Term Memory*, [`PDF`](https://doi.org/10.1109/TBDATA.2019.2940675)
- 2019 | IEEE INFOCOM, *FlowPic: Encrypted Internet Traffic Classification is as Easy as Image Recognition*, [`PDF`](https://ieeexplore.ieee.org/document/8845315)
- 2019 | IEEE INFOCOM, *FS-Net: A Flow Sequence Network For Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/infocom.2019.8737507)
- 2018 | Computer Networks, *An Efficient Feature Generation Approach Based on Deep Learning and Feature Selection Techniques for Traffic Classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2018.01.007)
- 2018 | IEEE TIFS, *Robust Smartphone App Identification via Encrypted Network Traffic Analysis*, [`PDF`](https://doi.org/10.1109/TIFS.2017.2737970)
- 2017 | IEEE TIFS, *Classification of Encrypted Traffic With Second-Order Markov Chains and Application Attribute Bigrams*, [`PDF`](https://doi.org/10.1109/TIFS.2017.2692682)

#### Traffic Representation, Pretraining, and Foundation Models

- 2026 | CCPE, *A Lightweight Deep Learning Framework for Encrypted Traffic Classification via Visual Flow Representation*, [`PDF`](https://doi.org/10.1002/cpe.70679)
- 2026 | Computer Networks, *ByteDance: Let bytes perform brilliantly in multi-view encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2025.111843)
- 2026 | Journal of Network and Systems Management, *FGFR-Net: An Improved Residual Network Encrypted Traffic Classification Model Based on Byte-Level Traffic Graphs*, [`PDF`](https://doi.org/10.1007/s10922-025-10011-8)
- 2026 | IEEE TDSC, *Learning Flow Semantics via Contrastive Pre-training for Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/TDSC.2026.3677663)
- 2026 | IEEE TIFS, *MT-DEGCL: Multi-Task Encrypted Traffic Classification With Dual Embedding and Graph Contrastive Learning*, [`PDF`](https://doi.org/10.1109/TIFS.2026.3664007)
- 2026 | arXiv, *Nethira: A Heterogeneity-aware Hierarchical Pre-trained Model for Network Traffic Classification*, [`PDF`](https://doi.org/10.48550/arxiv.2601.22494)
- 2026 | arXiv, *NetMamba+: A Framework of Pre-trained Models for Efficient and Accurate Network Traffic Classification*, [`PDF`](https://arxiv.org/abs/2405.11449v3)
- 2026 | Computer Networks, *Plug-in enhancement framework: Breaking through performance bottleneck of pre-trained models for encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112122)
- 2026 | arXiv, *Talk Like a Packet: Rethinking Network Traffic Analysis with Transformer Foundation Models*, [`PDF`](https://doi.org/10.48550/arxiv.2602.06636)
- 2026 | IEEE TSC, *Time Will Tell: Criss-cross Transformer for Encrypted Traffic Analysis*, [`PDF`](https://doi.org/10.1109/tsc.2026.3664705)
- 2026 | Computer Networks, *Traffic burst relational graph attention network combined position encoding for traffic classification*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112072)
- 2026 | IEEE TNSM, *TrafficAudio: Audio Representation for Lightweight Encrypted Traffic Classification in IoT*, [`PDF`](https://doi.org/10.1109/TNSM.2026.3651599)
- 2026 | arXiv, *TrafficMoE: Heterogeneity-aware Mixture of Experts for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2603.29520)
- 2026 | arXiv, *Treat Traffic Like Trees: A Semantic-Preserving Hierarchical Graph-Based Expert Framework for Encrypted Traffic Analysis*, [`PDF`](https://arxiv.org/abs/2606.04517)
- 2026 | ICASSP, *TriFusion: A Self-Supervised Learning Enhanced Dual-Level Multimodal Framework for Traffic Classification*, [`PDF`](https://doi.org/10.1109/icassp55912.2026.11460777)
- 2026 | arXiv, *Where Do Flow Semantics Reside? A Protocol-Native Tabular Pretraining Paradigm for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2603.10051)
- 2025 | AAAI, *MIETT: Multi-Instance Encrypted Traffic Transformer for Encrypted Traffic Classification*, [`PDF`](https://arxiv.org/abs/2412.15306)
- 2025 | ACM CCS, *MM4flow: A Pre-trained Multi-modal Model for Versatile Network Traffic Analysis*, [`PDF`](https://doi.org/10.1145/3719027.3744804)
- 2025 | IWQoS, *MOTA: Mixture Of Traffic Agents for robust network traffic classification*, [`PDF`](https://doi.org/10.1109/iwqos65803.2025.11143417)
- 2025 | IEEE S&P, *TrafficFormer: An Efficient Pre-trained Model for Traffic Data*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00102)
- 2025 | IWQoS, *TraGe: A Generic Packet Representation for Traffic Classification Based on Header-Payload Differences*, [`PDF`](https://doi.org/10.1109/iwqos65803.2025.11143462)
- 2024 | arXiv, *NetMamba: Efficient Network Traffic Classification via Pre-training Unidirectional Mamba*, [`PDF`](https://arxiv.org/abs/2405.11449)
- 2024 | arXiv, *TrafficGPT: Breaking the Token Barrier for Efficient Long Traffic Analysis and Generation*, [`PDF`](https://arxiv.org/abs/2403.05822)
- 2023 | IEEE/ACM ToN, *A Novel Multimodal Deep Learning Framework for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/TNET.2022.3215507)
- 2023 | AAAI, *Yet Another Traffic Classifier: A Masked Autoencoder Based Traffic Transformer with Multi-Level Flow Representation*, [`PDF`](https://doi.org/10.1609/aaai.v37i4.25674)
- 2022 | The Web Conference, *ET-BERT: A Contextualized Datagram Representation with Pre-training Transformers for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1145/3485447.3512217)
- 2021 | IEEE TIFS, *Accurate Decentralized Application Identification via Encrypted Traffic Analysis Using Graph Neural Networks*, [`PDF`](https://doi.org/10.1109/TIFS.2021.3050608)

#### Robust, Adaptive, Few-Shot, Open-Set, and Federated Learning

- 2026 | Computer Networks, *A prototypical alignment approach to unknown traffic classification using BERT*, [`PDF`](https://doi.org/10.1016/j.comnet.2026.112062)
- 2026 | IEEE TIFS, *End-to-End Open-Set Semi-Supervised Learning for Fine-Grained Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/TIFS.2026.3653575)
- 2026 | IEEE IoT Journal, *NetTTT: Online Self-Adaptation Inference via Test-Time Training for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1109/jiot.2026.3652996)
- 2025 | ICAACE, *A Semi-Supervised Learning Framework for Encrypted Traffic Classification Based on Supervised Contrastive Learning and Masked Sequence Prediction Tasks*, [`PDF`](https://doi.org/10.1109/icaace65325.2025.11020246)
- 2025 | IEEE TDSC, *DAIR-FedMoE: Hierarchical MoE for Federated Encrypted Traffic Classification under Compound Drift*, [`PDF`](https://doi.org/10.1109/tdsc.2026.3676447)
- 2025 | IEEE TIFS, *FG-SAT: Efficient Flow Graph for Encrypted Traffic Classification Under Environment Shifts*, [`PDF`](https://doi.org/10.1109/TIFS.2025.3571663)
- 2025 | NeurIPS, *FlowRefiner: A Robust Traffic Classification Framework against Label Noise*, [`PDF`](https://papers.nips.cc/paper_files/paper/2025/hash/ba1d33849b963efc6b5d3082ad68f480-Abstract-Conference.html)
- 2025 | JPDC, *Multi-ARCL: Multimodal adaptive relay-based distributed continual learning for encrypted traffic classification*, [`PDF`](https://doi.org/10.1016/j.jpdc.2025.105083)
- 2025 | ACM CCS, *Training Robust Classifiers for Classifying Encrypted Traffic under Dynamic Network Conditions*, [`PDF`](https://doi.org/10.1145/3719027.3765073)
- 2023 | Computer Networks, *Few-shot encrypted traffic classification via multi-task representation enhanced meta-learning*, [`PDF`](https://doi.org/10.1016/j.comnet.2023.109731)
- 2020 | NDSS, *FLOWPRINT: Semi-Supervised Mobile-App Fingerprinting on Encrypted Network Traffic*, [`PDF`](https://github.com/Thijsvanede/Flowprint)

#### Tunnel, QUIC, DoH, and Protocol Analysis

- 2025 | The Web Conference, *DecETT: Accurate App Fingerprinting Under Encrypted Tunnels via Dual Decouple-based Semantic Enhancement*, [`PDF`](https://doi.org/10.1145/3696410.3714643)
- 2025 | AIA, *Enhancing DNS-over-HTTPS Traffic Classification in Heterogeneous Networks Through Latent Space Analysis with a Tabular-Variational Autoencoder and Self-Attention Classifier Model*, [`PDF`](https://doi.org/10.47852/bonviewAIA52025552)
- 2022 | HPCC, *MTBD: HTTPS Tunnel Detection Based on Multi-dimension Traffic Behaviors Decision*, [`PDF`](https://doi.org/10.1109/hpcc-dss-smartcity-dependsys57074.2022.00091)
- 2022 | ICMLA, *Separating Flows in Encrypted Tunnel Traffic*, [`PDF`](https://doi.org/10.1109/ICMLA55696.2022.00094)
- 2008 | ICC, *Detection of Encrypted Tunnels across Network Boundaries*, [`PDF`](https://doi.org/10.1109/icc.2008.334)

#### Surveys, Benchmarks, Explainability, and Evaluation

- 2026 | arXiv, *Bias in the Shadows: Explore Shortcuts in Encrypted Network Traffic Classification*, [`PDF`](https://doi.org/10.48550/arxiv.2601.10180)
- 2026 | ACM KDD, *Building Transparency in Deep Learning-Powered Network Traffic Classification: A Traffic-Explainer Framework*, [`PDF`](https://arxiv.org/abs/2509.18007)
- 2026 | arXiv, *Multimodal Reasoning with LLM for Encrypted Traffic Interpretation: A Benchmark*, [`PDF`](https://arxiv.org/abs/2604.08140)
- 2026 | arXiv, *The Inevitability of Side-Channel Leakage in Encrypted Traffic*, [`PDF`](https://arxiv.org/abs/2602.14055)
- 2025 | NeurIPS, *Gated Attention for Large Language Models: Non-linearity, Sparsity, and Attention-Sink-Free*, [`PDF`](https://arxiv.org/abs/2505.06708)
- 2025 | IEEE S&P, *SoK: Decoding the Enigma of Encrypted Network Traffic Classifiers*, [`PDF`](https://doi.org/10.1109/sp61157.2025.00165)
- 2025 | SIGCOMM, *The Sweet Danger of Sugar: Debunking Representation Learning for Encrypted Traffic Classification*, [`PDF`](https://doi.org/10.1145/3718958.3750498)
- 2023 | ACM KDD, *A Lightweight, Efficient and Explainable-by-Design Convolutional Neural Network for Internet Traffic Classification*, [`PDF`](https://doi.org/10.1145/3580305.3599762)
- 2022 | IEEE Communications Surveys & Tutorials, *Machine Learning-Powered Encrypted Network Traffic Analysis: A Comprehensive Survey*, [`PDF`](https://doi.org/10.1109/COMST.2022.3208196)

#### Other Network Security and Supporting Methods

- 2025 | USENIX Security, *CertTA: Certified Robustness Made Practical for Learning-Based Traffic Analysis*, [`PDF`](https://www.usenix.org/conference/usenixsecurity25/presentation/yan-jinzhu)
- 2025 | ACM CCS, *Fingerprinting Deep Packet Inspection Devices by Their Ambiguities*, [`PDF`](https://doi.org/10.1145/3719027.3765145)
- 2022 | USENIX Security, *Off-Path Network Traffic Manipulation via Revitalized ICMP Redirect Attacks*, [`PDF`](https://www.usenix.org/conference/usenixsecurity22/presentation/feng)
- 2021 | USENIX Security, *Defeating DNN-Based Traffic Analysis Systems in Real-Time With Blind Adversarial Perturbations*, [`PDF`](https://www.usenix.org/system/files/sec21-nasr.pdf)
- 2021 | USENIX Security, *LZR: Identifying Unexpected Internet Services*, [`PDF`](https://www.usenix.org/conference/usenixsecurity21/presentation/izhikevich)

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
| [Chenxin Zhou](mailto:tovey_zhou@foxmail.com) | PhD Student @ DAS-Lab, SCU |

## Contact & Feedback

If you have any suggestions (missing papers, new papers, key researchers or typos), feel free to pull a request. Also you can mail to:

- [Qiang Zhang](mailto:qzhang@stu.scu.edu.cn?subject=Feedback)
- [Chenxin Zhou](mailto:tovey_zhou@foxmail.com?subject=Feedback)

## License

The source-code is licensed under the MIT license. See [LICENSE](LICENSE).
