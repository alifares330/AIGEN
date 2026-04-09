# Pavement AI Generator (AIGEN)

This repository contains the **AIGEN** research tool, designed to generate high-fidelity synthetic datasets for pavement crack segmentation. By leveraging Google’s advanced Generative AI (Imagen 4 and Gemini), the tool creates perfectly paired RGB pavement images and binary masks to address the scarcity of annotated real-world data.

### Key Features
* **Dual-Modality Output:** Generates photorealistic RGB images paired with pixel-perfect binary masks (704 × 768 pixels).
* **Controllable Pipeline:** Users can define crack morphology, surface textures (e.g., oil, leaves), and lighting conditions.
* **Human-in-the-Loop Quality Control:** Employs post-processing algorithms for mask alignment alongside automated flagging of inverted or null samples for manual verification.
* **Nadir Viewpoint:** Synthesizes consistent top-down perspectives for direct integration into segmentation model training.

---

### Available Datasets & Tools
All research data and the generation application can be accessed via the primary project directory:

**[Access Full Project Directory (Google Drive)](https://drive.google.com/drive/u/2/folders/176BIgEpKPsLGexGOODWxvWkn4ibsg-6u)**

**Directory Contents:**
* **AI500 Dataset:** 500 synthetic pavement crack images and masks generated using the Imagen 4 model. [Direct Link](https://drive.google.com/drive/folders/1M7GQ0Kwxnfqnt_48S6ybaQEkTCuVNMn0?usp=drive_link)
* **G3P-500 Dataset:** Specialized dataset generated via the Gemini 3 Pro pipeline, focusing on diverse morphologies. [Direct Link](https://drive.google.com/drive/folders/1us2FzPxwHCS_3jJzGA9dhgbvwD7bjliP?usp=drive_link)
* **AI Generation Tool:** The standalone application used to automate synthesis and quality control. [Download .zip](https://drive.google.com/file/d/18vn2Kvhqlrn2aKr0mZUbHyiNduxo8nzJ/view?usp=drive_link)

---

### Research Context
Developed as part of doctoral research on multi-sensing pavement performance assessment at **The Hong Kong Polytechnic University (PolyU)** in collaboration with **McGill University**.

* **Researcher:** Ali Fares (PolyU / McGill)
* **Supervisor:** Prof. Tarek Zayed (PolyU) & Prof. Luis Miranda-Moreno (McGill)

---

### Citations
If you use this tool or the associated datasets in your research, please cite the following works:

**Conference Paper:**
> Fares, A., Yu, J., Zayed, T., Faris, N.*, Romero, J.-P., Wu, M., Jiao, Y., & Miranda-Moreno, L. (2026). **AI500: A Synthetic Dataset for Data-Efficient Deep Learning in Asphalt Crack Segmentation.** *Transportation Research Board 105th Annual Meeting*, Washington, D.C.

**Journal Paper (Under Review):**
> Fares, A., Yu, J., Zayed, T., Faris, N.*, Romero, J.-P., Wu, M., Jiao, Y., & Miranda-Moreno, L. (2026). **A Data-Efficient Deep Learning Paradigm for Crack Segmentation Using Generative AI.** *Transportation Research Records*.

**Contact:** ali.i.fares@connect.polyu.hk
