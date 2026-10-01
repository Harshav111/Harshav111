<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0d1117,100:0b3d5c&height=170&text=Harshavarthan%20S&fontSize=48&fontColor=e6edf3&fontAlignY=42&desc=clinical%20NLP%20%C2%B7%20multimodal%20AI%20%C2%B7%20robot%20perception&descSize=16&descAlignY=68&descColor=7dd3fc" width="100%"/>

<sub><code>README.md</code> &nbsp;·&nbsp; <code>cs.CL</code> <code>cs.CV</code> <code>cs.RO</code> &nbsp;·&nbsp; rev. October 2026</sub>

**Harshavarthan S**<sup>1</sup><br/>
<sub><sup>1</sup> Department of Computer Science & Engineering, SSN College of Engineering, Chennai, India</sub>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3200&pause=900&color=7DD3FC&center=true&vCenter=true&width=620&lines=Reading+clinical+notes+in+more+than+one+language.;Teaching+a+Jetson+to+know+where+it+is.;4+published+works+%C2%B7+1+in+press+%C2%B7+1+Best+Paper." alt="typing"/></a>

<a href="https://in.linkedin.com/in/harshavarthan-s"><img src="https://img.shields.io/badge/LinkedIn-harshavarthan--s-0A66C2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<a href="mailto:harshavarthansami@gmail.com"><img src="https://img.shields.io/badge/Email-harshavarthansami%40gmail.com-c2410c?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://doi.org/10.1201/9781003777458-12"><img src="https://img.shields.io/badge/Latest-CRC%20Press%20Chapter%2012-0b3d5c?style=flat-square&logo=bookstack&logoColor=white"/></a>
<!-- Add your Scholar profile: replace YOUR_ID and uncomment
<a href="https://scholar.google.com/citations?user=YOUR_ID"><img src="https://img.shields.io/badge/Google%20Scholar-profile-4285F4?style=flat-square&logo=googlescholar&logoColor=white"/></a>
-->

</div>

---

> **Abstract.** I work on two problems that look unrelated and aren't. The first is clinical: rural hospitals in Tamil Nadu often have a general practitioner and no specialist, so I build decision-support models (BioBERT + Bi-LSTM, multilingual) that read physician notes and flag conditions like neonatal sepsis, marasmus and tuberculosis before they are missed. The second is robotic: keeping a SLAM system on a Jetson Orin Nano on track when the world gets messy, by bringing self-supervised features (DINOv2) and graph/transformer matching into ORB-SLAM3. Both reduce to one question — *how do you make a model trustworthy on cheap hardware, in places where nobody is around to fix it?*
>
> **Keywords —** clinical NLP · decision support · multimodal retrieval · visual SLAM · edge AI

<br/>

```mermaid
flowchart LR
    subgraph A["Track A · Clinical NLP"]
        direction LR
        A1["Physician notes<br/>multilingual, noisy"] --> A2["BioBERT + Bi-LSTM"] --> A3["Diagnostic support<br/>for rural clinics"]
    end
    subgraph B["Track B · Robot perception"]
        direction LR
        B1["Camera stream<br/>Jetson Orin Nano"] --> B2["ORB-SLAM3 + DINOv2<br/>+ GNN / Transformer"] --> B3["Robust trajectory<br/>under 15 ms / frame"]
    end
    A2 -.-|"shared idea: learned representations on constrained hardware"| B2
```

<p align="center"><sub><b>Fig. 1.</b> Two research tracks, one underlying question.</sub></p>

---

### § 1 &nbsp; Ongoing work

<table>
<tr>
<td width="50%" valign="top">

**Neural-SLAM-Zero** &nbsp;<sub>`Jan 2026 – present`</sub>

Self-supervised visual SLAM for edge robots, funded by an **IFPS Institutional Research Grant** at SSN.

```yaml
goal:     ">40% lower ATE vs. ORB-SLAM3 baseline"
budget:   "<15 ms per frame"
hardware: Jetson Orin Nano
stack:    [ORB-SLAM3, DINOv2, GNN, Transformers, PyTorch, OpenCV]
```

</td>
<td width="50%" valign="top">

**Centre for Digital Infrastructure, NIT Trichy** &nbsp;<sub>`Summer 2026`</sub>

Building internal software for the institute's digital infrastructure, end to end: requirements, implementation, testing and production deployment of institution-specific web applications.

```yaml
role:  Summer Intern
scope: full development lifecycle
```

</td>
</tr>
</table>

---

### § 2 &nbsp; Publications

**[1]** &nbsp;**Harshavarthan S.**, Ahmed Hafeel, Sabareeswaran, Kavitha T. &nbsp;*An AI-Driven Approach for Enhancing Patient Healthcare in Resource-Constrained Rural Areas.* &nbsp;In A. K. Tyagi (Ed.), **Role of Machine Learning in IoT-Cloud Enabled Healthcare: Prospects, Challenges and Opportunities**, Chapter 12, pp. 222–241. CRC Press (Taylor & Francis Group). &nbsp;<sub>An AI clinical decision support system combining BERT, Random Forest and LSTM classifiers, evaluated on real patient interactions from rural hospitals in Tamil Nadu.</sub><br/>
[![DOI](https://img.shields.io/badge/DOI-10.1201%2F9781003777458--12-0b3d5c?style=flat-square)](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003777458-12/ai-driven-approach-enhancing-patient-healthcare-resource-constrained-rural-areas-harshavarthan-ahmed-hafeel-sabareeswaran-kavitha)
![CRC Press](https://img.shields.io/badge/CRC%20Press-Book%20Chapter-c2410c?style=flat-square)

**[2]** &nbsp;*Multilingual AI-Driven Clinical Decision Support System: Hybrid BioBERT & Bi-LSTM.* &nbsp;**IEEE ISCS 2025**, Delhi (IEEE Xplore). &nbsp;<sub>Diagnosis support for neonatal sepsis, marasmus and tuberculosis; containerised with Docker and Kubernetes.</sub><br/>
[![DOI](https://img.shields.io/badge/DOI-10.1109%2FISCS69371.2025.11385867-00629B?style=flat-square&logo=ieee&logoColor=white)](https://doi.org/10.1109/ISCS69371.2025.11385867)

**[3]** &nbsp;*NewsImages: CLIP–FAISS Retrieval and Diffusion-Based Thumbnail Generation.* &nbsp;**MediaEval 2025**, CEUR Workshop Proceedings.<br/>
[![Paper](https://img.shields.io/badge/PDF-MediaEval%202025-6d28d9?style=flat-square)](https://2025.multimediaeval.com/paper46.pdf)

**[4]** &nbsp;*AI-Driven Patient Outcome Enhancement.* &nbsp;**Taylor & Francis** (in press). &nbsp;<sub>Severity prediction for status asthmaticus and diabetic ketoacidosis, 90% accuracy.</sub><br/>
![Best Paper](https://img.shields.io/badge/%F0%9F%8F%86%20Best%20Paper-Next%20Gen%20Intl.%20Conf.%2C%20SRM%202025-b45309?style=flat-square)
![In press](https://img.shields.io/badge/status-in%20press-6b7280?style=flat-square)

**[5]** &nbsp;*User-to-Root Attack Detection: CNN AlexNet vs. SVM.* &nbsp;**IEEE ACROSET 2024** (Scopus-indexed).<br/>
[![DOI](https://img.shields.io/badge/DOI-10.1109%2FACROSET62108.2024.10743609-00629B?style=flat-square&logo=ieee&logoColor=white)](https://doi.org/10.1109/ACROSET62108.2024.10743609)

<details>
<summary><sub><b>Cite [1] — BibTeX</b></sub></summary>

```bibtex
@incollection{harshavarthan2027rural,
  author    = {Harshavarthan, S. and Hafeel, Ahmed and {Sabareeswaran} and Kavitha, T.},
  title     = {An AI-Driven Approach for Enhancing Patient Healthcare in Resource-Constrained Rural Areas},
  booktitle = {Role of Machine Learning in IoT-Cloud Enabled Healthcare: Prospects, Challenges and Opportunities},
  editor    = {Tyagi, Amit Kumar},
  publisher = {CRC Press},
  chapter   = {12},
  pages     = {222--241},
  year      = {2027},
  doi       = {10.1201/9781003777458-12}
}
```

</details>

---

### § 3 &nbsp; Experience

| When | Where | What |
|:--|:--|:--|
| `2026` | **NIT Trichy** — Centre for Digital Infrastructure | Summer intern · internal web systems, full lifecycle |
| `2024` | **Avivo AI LLC** | Junior software developer · LLM + RAG pipelines, vector search, React front ends for real-time AI |
| `2023–24` | **SUNFLEX Global Energy** | System administrator · uptime, DNS, domains, task automation |
| `2023` | **Hyundai Motor India** | Summer intern · automatic ticket management (Ignition, MS SQL, Python), Qlik Sense plant analytics |

<sub>**Education —** M.E. CSE, SSN College of Engineering (2025–27, CGPA 8.4) &nbsp;·&nbsp; B.Tech CSE (Data Science), Periyar Maniammai Institute of Science & Technology (2021–25, CGPA 7.9)</sub>

---

### § 4 &nbsp; Methods

| | |
|:--|:--|
| **Languages** | <img src="https://skillicons.dev/icons?i=python,cpp,c,js,r,bash&theme=dark" height="36"/> |
| **Learning** | <img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" height="36"/> &nbsp; ![HF](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black) ![BioBERT](https://img.shields.io/badge/BioBERT-1e3a8a?style=flat-square) ![CLIP](https://img.shields.io/badge/CLIP%20%2B%20FAISS-412991?style=flat-square) ![Diffusion](https://img.shields.io/badge/Diffusion-0f766e?style=flat-square) |
| **Robotics** | ![ORB-SLAM3](https://img.shields.io/badge/ORB--SLAM3-222222?style=flat-square) ![DINOv2](https://img.shields.io/badge/DINOv2-0b3d5c?style=flat-square) ![GNN](https://img.shields.io/badge/GNN%20%2F%20Transformers-7c3aed?style=flat-square) ![Jetson](https://img.shields.io/badge/Jetson%20Orin%20Nano-76B900?style=flat-square&logo=nvidia&logoColor=white) |
| **Systems** | <img src="https://skillicons.dev/icons?i=fastapi,django,react,nodejs,docker,kubernetes,aws,linux,git&theme=dark" height="36"/> |
| **Data** | <img src="https://skillicons.dev/icons?i=postgres,mongodb,redis,kafka&theme=dark" height="36"/> &nbsp; ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Cassandra](https://img.shields.io/badge/Cassandra-1287B1?style=flat-square&logo=apachecassandra&logoColor=white) |

---

### § 5 &nbsp; Results

| | |
|:--|:--|
| 🏆 | **Best Paper Award** — Next Gen International Conference, SRM University (2025) |
| 🔬 | **IFPS Institutional Research Grant** — SSN College of Engineering, for Neural-SLAM-Zero |
| 🥇 | **First Prize** — CODEX Hackathon (2024) |
| ☁️ | **AWS Certified Cloud Practitioner** · Data Analytics, Honeywell & ICT Academy |

---

### § 6 &nbsp; Experimental log

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=harshav111&theme=dark&hide_border=true&background=0D1117&ring=7DD3FC&fire=7DD3FC&currStreakLabel=7DD3FC"/>
  <img src="https://streak-stats.demolab.com?user=harshav111&theme=default&hide_border=true&ring=0B3D5C&fire=0B3D5C&currStreakLabel=0B3D5C" alt="GitHub streak"/>
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-activity-graph.vercel.app/graph?username=harshav111&bg_color=0d1117&color=7dd3fc&line=0b84b8&point=e6edf3&area=true&area_color=0b3d5c&hide_border=true"/>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=harshav111&bg_color=ffffff&color=0b3d5c&line=0b84b8&point=0b3d5c&area=true&area_color=7dd3fc&hide_border=true" alt="Contribution graph" width="100%"/>
</picture>

</div>

---

<details>
<summary><b>Appendix A</b> — away from the keyboard</summary>
<br/>

110 m hurdles · State and South Zone medalist (2022). It turns out clearing obstacles at speed is decent training for debugging SLAM.

</details>

<br/>

<div align="center">
<sub><b>Correspondence:</b> <a href="mailto:harshavarthansami@gmail.com">harshavarthansami@gmail.com</a> &nbsp;·&nbsp; <a href="https://in.linkedin.com/in/harshavarthan-s">LinkedIn</a> &nbsp;·&nbsp; Chennai, India</sub>
</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0b3d5c,100:0d1117&height=6" width="100%"/>
