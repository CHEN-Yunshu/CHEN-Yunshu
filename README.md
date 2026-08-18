# Hi, I'm Yunshu 👋

**PhD candidate in Data Science & AI at Monash University.** Multi-modal medical and biological image analysis.

I work on a question that segmentation benchmarks mostly skip: *is the model validated at the level that actually changes a decision?* For coronary intravascular ultrasound, Dice has saturated, so I moved the evaluation to clinical agreement, reaching **84% agreement with expert adjudication** on the plaque-burden treatment threshold and **AUROC 0.97–0.99** on the calcium threshold that determines device selection.

🔗 **[chen-yunshu.github.io](https://chen-yunshu.github.io)** · [Google Scholar](https://scholar.google.com/citations?user=-mTqfsEAAAAJ) · [LinkedIn](https://www.linkedin.com/in/yunshu-chen-22917915a/) · [ORCID](https://orcid.org/0009-0004-4772-4054)

---

### 🔬 What I'm working on

| | |
|---|---|
| **Coronary IVUS** | Geometry-consistent segmentation validated against clinical measurement standards, plus a **49.6M-frame foundation model** across two vendor platforms and 13 years of clinical acquisition |
| **Agentic clinical AI** | LLM-orchestrated reporting where every number comes from a deterministic tool and none from the model, deployed on a local Qwen2.5-7B for patient privacy |
| **Microscopy** | Cell instance segmentation at 8M+ instances, SAM2-memory-based tracking that beats a SOTA tracker with no retraining, and systematic benchmarks of resolution sensitivity |
| **Research infrastructure** | Large-scale data pipelines, versioned lineage, and data audits that catch duplication and leakage before they reach a benchmark |

### 📄 Papers

- *From Pixels to Decisions: Validating Deployable Coronary IVUS Analysis at the Level That Informs Treatment* · first author, under review
- *Clinically Aligned Geometry Constraints for Robust IVUS Vessel Boundary Segmentation* · first author, under review
- *Confidence-Adaptive Trimap for Boundary-Precise Zebrafish Myotome Segmentation* · first author, under review
- **IEEE ISCSLP 2022** · *Efficient Conformer-Based CTC Model for Intelligent Cockpit Speech Recognition* · [doi](https://doi.org/10.1109/ISCSLP57327.2022.10037993)

### 🛠️ Open source

**[Genius Labbook](https://github.com/CHEN-Yunshu/Genius_Labbook)** is a git-backed research logbook CLI. Records experiments, results, figures and decisions as Markdown + YAML with automatic commits. It has driven all of my research since March 2026: **135 experiment entries across 6 projects**.

**[Cell_Collection](https://github.com/CHEN-Yunshu/Cell_Collection)** covers dataset crawling, curation and standardisation for cell-segmentation research: **186 public datasets** across 7 sources, with a duplication and leakage audit run before anything reaches a benchmark.

> Most of my research repositories stay private while the papers are under review.

### 🧰 Tools

`PyTorch` `SAM / SAM2` `DINOv3` `nnU-Net` `MONAI` `vLLM` `Docker` `Kubernetes` `AWS` `Python` `Java` `C++` `R` `SQL`

---

📫 Melbourne, Australia · **[get in touch](https://chen-yunshu.github.io)** (email on the Contact page)
