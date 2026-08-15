<div align="center">

<img src="https://raw.githubusercontent.com/Zeesejo/Zeesejo/main/assets/header.svg" width="100%" alt="Zeeshan Modi" />

# Zeeshan Modi

### AI/ML · Robotics · Computer Vision · Medical AI

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1200&color=A855F7&center=true&vCenter=true&width=820&lines=M.Sc.+Artificial+Intelligence+%26+Intelligent+Systems;Building+ML+systems+that+move+from+experiments+to+engineering;Medical+Imaging+%7C+Robotics+%7C+Multimodal+Learning;Research-minded.+Engineering-driven.)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Zeeshan_Modi-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/zeesejo)
[![Portfolio](https://img.shields.io/badge/Portfolio-litends.com-A855F7?style=for-the-badge&logo=firefox&logoColor=white)](https://litends.com)
[![GitHub](https://img.shields.io/badge/GitHub-Zeesejo-181717?style=for-the-badge&logo=github)](https://github.com/Zeesejo)

</div>

---

## 👋 About me

I am an AI/ML engineer and M.Sc. student in **Artificial Intelligence & Intelligent Systems at the University of Bremen**. I like projects where machine learning is not just trained, but **measured, questioned, reproduced and integrated into a real system**.

My strongest interests sit at the intersection of:

- 🩻 **Medical AI** — chest X-ray classification, robustness, explainability, fairness and calibration
- 🤖 **Robotics** — ROS 2, navigation, planning, perception and autonomous systems
- 🧠 **Multimodal & biosignal ML** — EEG, temporal signals and representation learning
- 🔎 **Applied AI systems** — semantic search, retrieval, automation and research tooling
- 🧪 **Reproducible research** — controlled experiments, provenance, raw predictions and honest evaluation

---

## 🚀 Featured research & engineering

| Project | What I built / investigated | Highlight | Stack |
|---|---|---|---|
| 🩻 **[MedVision-AI](https://github.com/Zeesejo/medvision-ai)** | Multi-label chest X-ray classification on NIH ChestX-ray14 with CNN backbones, asymmetric loss, XAI and planned SSL/fairness experiments | **DenseNet-121: 0.7978 mean AUROC** vs **ResNet-50: 0.7067** across 14 pathologies in committed historical runs | PyTorch · timm · W&B · Grad-CAM |
| 🛰️ **[Gravloc](https://github.com/Zeesejo/gravloc)** | Spacecraft-hardware discovery and comparison prototype with datasheet extraction, semantic retrieval and grounded RFQ generation | Engineering-focused AI search with provenance and verification guardrails | Python · FAISS · Sentence Transformers · Streamlit |
| 🤖 **[Intelligent Interactive Systems Robot Project](https://github.com/Zeesejo/iis-robot-project-win2025-2026)** | Mapping, localization, global planning and motion control for a mobile robot | End-to-end autonomous navigation stack | ROS 2 · A* · LiDAR · RViz · Python |
| 🧠 **[EEG Motor Imagery Classification](https://github.com/Zeesejo/eeg-motor-imagery-classification)** | EEG preprocessing and machine-learning classification experiments | Biosignal ML pipeline and comparative modelling | Python · EEG · Signal Processing · ML |
| 🫁 **[Pneumothorax Shortcut Learning](https://github.com/Zeesejo/pneumothorax-shortcut-learning)** | Medical-imaging robustness experiments around shortcut learning in pneumothorax detection | Focus on whether models learn pathology or spurious cues | PyTorch · Medical Imaging · XAI · Robustness |

> **Research note:** repository metrics are described as experimental results unless a linked paper explicitly states that the work has been peer reviewed or published.

---

## 🔬 Current research focus — MedVision-AI

MedVision-AI is being rebuilt as a **publication-grade reproducible research project** rather than just a collection of training scripts.

The current direction is to establish a clean baseline and then test:

```text
Backbones      → ResNet-50 · DenseNet-121 · transformer baseline
Losses         → BCE · Focal · Asymmetric Loss
Label budgets  → 1% · 5% · 10% · 25% · 50% · 100%
Representation → ImageNet supervised vs medical self-supervised pretraining
Trustworthiness→ AUROC · AUPRC · calibration · subgroup analysis · XAI localization
Statistics     → multiple seeds · bootstrap confidence intervals · saved raw predictions
```

The goal is not to chase one headline metric. It is to understand **when a model improves, why it improves, and whether that improvement survives stronger evaluation**.

---

## 🧩 Open-source contribution

I also contribute fixes upstream instead of only working in my own repositories.

### Project MONAI

✅ **[MONAI #8818](https://github.com/Project-MONAI/MONAI/pull/8818)** — merged fix using `register_buffer` for constant tensors in `LocalNormalizedCrossCorrelationLoss`, improving correct device/state handling in the PyTorch module.

I am particularly interested in contributing to open-source tooling around **medical imaging, robotics and ML infrastructure**.

---

## 🛠️ Technology stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

### ML / Vision
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### Robotics / Engineering
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

---

## 📊 GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Zeesejo&show_icons=true&hide_border=true&theme=tokyonight" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Zeesejo&layout=compact&hide_border=true&theme=tokyonight" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=Zeesejo&theme=tokyonight&hide_border=true" />

</div>

---

## 🧭 How I like to work

```python
research = {
    "question": "clear and falsifiable",
    "baseline": "reproducible",
    "results": "saved with provenance",
    "claims": "no stronger than the evidence",
    "engineering": "clean enough to run again later",
}
```

I enjoy turning rough experiments into systems that another person can actually understand, run and critique.

<div align="center">

### Build. Measure. Question. Improve.

</div>
