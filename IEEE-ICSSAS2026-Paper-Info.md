# 🐍 SphinxATS: <br>A Multi-Attribute AI-based Decision Support System for Automated Resume Screening and Candidate Ranking

* **Conference:** 4th International Conference on Self Sustainable Artificial Intelligence Systems (ICSSAS-2026)
* **Publisher:** IEEE
* **Publication Year:** 2026
* **Direct Access Link:** [IEEE Xplore](https://ieeexplore.ieee.org/document/11559449/)

This research paper introduces **SphinxATS**, an AI-driven automated resume screening and decision-support framework that transitions recruitment workflows from traditional keyword filtering to structured multi-attribute optimization. By formalizing the shortlisting pipeline as a Multi-Criteria Decision Making (MCDM) process, the system accurately analyzes unstructured resume data while ensuring complete architectural transparency for hiring teams.

---

## 📘 Publication Details

### Abstract Summary
Modern enterprise hiring workflows suffer from severe administrative overhead and inconsistent evaluation criteria due to manual screening. Traditional Applicant Tracking Systems (ATS) miss contextual semantic connections by relying entirely on surface-level keyword matching. Concurrently, advanced deep learning models operate as opaque "black-boxes," offering little accountability or visibility into why a candidate is selected or rejected.

SphinxATS resolves these issues by representing each candidate as a multidimensional feature vector evaluated across a configurable Simple Additive Weighting (SAW) aggregation framework. The framework calculates a composite ranking score based on three independent, measurable dimensions:
1. **Semantic Alignment (S1):** Measures contextual profile fit against the job description using TF-IDF vectorization and Cosine Similarity calculations.
2. **Technical Skill Overlap (S2):** Quantifies technical tool alignment using regex-based whole-word matching over a predefined skillset taxonomy.
3. **Experience Relevance (S3):** Measures and normalizes the candidate's professional duration against specific target role requirements.

A dedicated **Explainability Layer** breaks down automated decisions into human-interpretable outputs by providing raw attribute score profiles, custom weight contributions, exact technical skill gaps, and unsupervised K-Means clustering signals (k=2) for high-velocity candidate sorting.

### Performance Evaluation
Evaluated across a benchmark dataset of 150 anonymized candidate profiles spanning multiple engineering roles, SphinxATS yields high-tier matching consistency without requiring heavy GPU infrastructure, labeled training data, or large pre-trained transformer weights:
* **Matching Accuracy:** **96.0%** (Outperforming keyword ATS baselines at 93.3% and standalone TF-IDF matching at 89.3%).
* **Balanced F1-Score:** **0.960** balance across precision and recall bounds.
* **Ranking Stability Index (RSI):** **0.741**, ensuring reliable candidate ordering under dynamic attribute adjustments.
* Paired t-test validations confirm performance gains are highly statistically significant (t = 22.21 / t = -22.25, p < 0.0001) and not the result of random variation.

---

## 🛠️ Repository Mapping
* 👉 **Publication Copy:** Stored in the root directory under [IEEE-ICSSAS2026-Publication.pdf](https://github.com/MANISH-K-07/Research/blob/main/IEEE-ICSSAS2026-Publication.pdf).
* 👉 **Core Implementation:** Modular Python and Flask processing engine, NLP text pipelines, and responsive frontend visualization modules located within the project repository.

---
*If you find this research framework helpful or intend to build upon this multi-attribute optimization model for transparent recruitment systems, consider starring the repository!*
