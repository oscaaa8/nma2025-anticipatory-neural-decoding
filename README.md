# nma2025-anticipatory-neural-decoding

A data-driven analysis of anticipatory state encoding in the mouse visual cortex using in vivo calcium imaging and behavioral alignment. This project was completed during [Neuromatch Academy 2025](https://neuromatch.io), a global computational neuroscience summer school.

---

## 🧠 Project Overview

This project investigates whether the **mouse visual cortex encodes anticipatory cognitive states** during a virtual-reality reward task — even in the absence of explicit external cues.

Using large-scale in vivo calcium imaging data from **Zhong et al. (2025)** (up to ~80,000 neurons per subject), we aligned behaviorally tagged licks with neural activity to extract **anticipatory and non-anticipatory frames**, and quantified neuron selectivity using **Cohen’s d**. We further applied **dimensionality reduction (PCA, t-SNE)** and **logistic regression decoding** to test whether these states were separable at the population level.

---

## 🌍 About Neuromatch Academy

Neuromatch Academy (NMA) is a rigorous, project-based international program focused on computational neuroscience and data science. Over three weeks, participants gain hands-on experience with models, neural data, and team science practices.

🧾 [My Certificate of Completion](https://portal.neuromatchacademy.org/certificate/fc133ae5-c5d8-4aec-9460-0fed90dc0e1c) ← 

---

## 💻 My Role & Contributions

- Selected and **preprocessed** supervised-subject calcium imaging and behavioral data
- Built the complete analysis pipeline from scratch in Python and Jupyter (see notebook)
- Applied **Cohen’s d** to classify neurons as anticipatory, non-anticipatory, or neutral
- Visualized population-wide selectivity distributions and interpretive histograms
- Conducted PCA-based **state decoding** to evaluate whether anticipatory states can be separated at the population level
- Gained practical experience working with multi-animal datasets and over **70,000+ neurons** in a realistic neuroscience research setting

---

## 📊 Key Features

- Behavioral trial cleaning using lick-aligned events
- Frame-matched calcium imaging neural extraction
- Cohen’s d analysis for neuronal selectivity classification
- Cross-animal comparisons of anticipatory activity
- PCA & logistic regression decoding of cognitive states

---

## 📁 Repository Contents

- `Final_Data_Pipeline_Notebook.ipynb`: Full notebook pipeline (data loading, analysis, plots)
- `NMA_Summary.pdf`: Final project summary slide deck
- `figures/`: output plots and visuals

---

## 📚 Dataset

**Zhong et al. (2025)** — Calcium imaging from visual cortex in VR-trained mice  
- Supervised and unsupervised reward paradigms  
- Downloadable via [Figshare (DOI: 10.6084/m9.figshare.28811129)](https://doi.org/10.6084/m9.figshare.28811129)

---

## 🧪 Highlights from Our Findings

- **Anticipatory-selective neurons outnumbered neutral/non-selective neurons** across multiple animals
- **Dimensionality reduction (PCA)** revealed low-dimensional structure separating cognitive states
- **Decoding accuracy** reached up to **98%** in some subjects (logistic regression)
- **Control comparisons** ruled out velocity-based and non-reward-based confounds

> These findings suggest that **sensory cortical areas such as V1 and LM may encode goal-directed internal states**, supporting a broader view of cortical involvement in anticipation.

---

## 👨‍🔬 Author

**Oscar Aguilar**  
Neuroscience Research Technician, University of Illinois at Chicago  
🧠 Interests: computational neuroscience, machine learning, and circuit-level behavior  
📬 [github.com/oscaaa8](https://github.com/oscaaa8)

---

## 🏷 License

MIT License — open for academic use and collaboration.
