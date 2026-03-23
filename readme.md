# Hi, I'm Naresh 👋
**AI/ML Researcher & Engineer** based in Paris, France.
I specialize in **Deep Reinforcement Learning** and **Applied AI for telecom infrastructure** 
(5G/6G), with hands-on experience in LLM fine-tuning, NLP, and classical ML. I combine research depth with practical engineering — from algorithm design to multi-GPU training pipelines.
---
## 🔬 Research & Work
- **Applied AI Researcher @ CNAM Paris** — Designing AI frameworks for autonomous anomaly 
  detection and recovery in 3D networks (terrestrial + satellite). Building DRL-based agents 
  for intelligent container orchestration and network dimensioning.
- **PhD @ Avignon Université** (ANR MAESTRO5G) — Gametheoretic sollutions for resource allocation in 5G. 
  MDP-based IoT orchestration optimizing Age of Information (AoI).
- **Patent** — Anomaly detection and management in compute environments ([FR3164046](https://data.inpi.fr/brevets/FR3164046?q=FR3164046#FR3164046), 2024)
- **IEEE Publications** — 4 [papers](https://scholar.google.com/citations?user=3RfIKSEAAAAJ&hl=fr) in IEEE TMC, ITC, ICC on next-generation networks
---
## 🚀 Featured Projects
### 📂 [tele-SLMs — Specializing Small Language Models for 3GPP Standards](https://github.com/NareshModina/tele-SLMs)
Research project exploring whether sub-2B parameter SLMs can be specialized for 3GPP 
telecommunications standards — accurately and with low retraining overhead. Two-stage 
pipeline: continual pretraining on ~1.26B tokens (3GPP standards + arXiv), followed by 
instruction fine-tuning. Phase 3 benchmarks SmolLM2 and Qwen2.5 sub-2B variants on 
Tele-Eval (held-out). Multi-GPU training via PyTorch DDP on 3× L40S.  
`PyTorch` `Transformers` `LoRA/PEFT` `SLM` `Qwen2.5` `SmolLM2` `Multi-GPU` `3GPP`

### 🤗 [TeleSpec-Data — Telecommunications Standards Dataset](https://github.com/NareshModina/telespec-data)
Curated NLP dataset combining ~23K ETSI documents and 3GPP standards for continual 
pretraining of language models on telecom domain knowledge. Built a multi-stage PDF 
extraction pipeline handling format variation across 15 ETSI working groups (2000–2024),
with a four-stage clause detection cascade. Compatible with the Tele-Data schema.  
`HuggingFace Datasets` `pymupdf` `NLP` `ETSI` `3GPP` `Continual Pretraining`

### 🔒 ARM — Autonomous Reconfiguration Management *(private — available for technical discussion)*
Applying Deep Reinforcement Learning for automatic reconfiguration of cloud-native 
infrastructure in ICT. DRL agent learns optimal reconfiguration policies for dynamic 
network environments.  
`PyTorch` `Deep Reinforcement Learning` `Cloud-Native` `ICT` `Network Automation`

### 🔒 5G Network Anomaly Detection *(private — available for technical discussion)*
End-to-end anomaly detection pipeline on real Open5GS telemetry data (5G3E_v2.1 dataset).
Timestamp alignment across network functions (AMF, SMF, UPF), multi-NF feature fusion,
and ML-based anomaly classification.  
`Python` `Pandas` `Open5GS` `Time-series` `Anomaly Detection`

### 📂 [Teaching — ML/DL/RL Notebooks](https://github.com/NareshModina/teaching)
Course material and experiments covering classical ML, deep learning, and reinforcement 
learning (DQN, DDQN, D3QN). Developed for the European AI4CI Master's programme.  
`PyTorch` `TensorFlow` `Scikit-learn` `Gymnasium` `Jupyter`
---
## 🛠️ Tech Stack
**Languages:** Python  
**LLMs:** HuggingFace Transformers, PEFT/LoRA  
**ML/DL:** PyTorch, TensorFlow, Scikit-learn  
**RL:** Gymnasium, DQN, DDQN, D3QN, PPO, World Models  
**Data:** Pandas, NumPy, large-scale dataset processing  
**MLOps:** Docker, Git, torchrun (multi-GPU DDP), distributed training  
**Telecom:** 5G/6G, Open5GS, 3GPP/ETSI standards, network slicing
---
## 📡 Open Source
Led the creation of **[5G3E](https://github.com/cedric-cnam/5G3E-dataset)** — an open-source 
end-to-end 5G telemetry dataset for training telecom AI models.
---
## 📫 Contact
[LinkedIn](https://linkedin.com/in/nareshmodina) · [Website](http://nareshmodina.com) · modinanaresh@gmail.com
---
## 📄 CV
- [CV — English](cv/CV_Naresh_Modina_en.pdf)
- [CV — Français](cv/CV_Naresh_Modina_fr.pdf)
