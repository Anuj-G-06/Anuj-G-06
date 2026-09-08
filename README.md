### Hi, I'm [Anuj Gupta](https://cs.cmu.edu/~anujg2) <img src="https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif" width="30px" alt="wave"/>

<p align="center">
  <img src="https://wsrv.nl/?url=user-images.githubusercontent.com/74038190/235224431-e8c8c12e-6826-47f1-89fb-2ddad83b3abf.gif&w=400&h=400&fit=cover&mask=circle&n=-1&output=gif" width="200" alt="Coding GIF"/>
</p>

**Founder, Researcher & ML Engineer** — MCDS @ Carnegie Mellon University SCS (Aug 2025 – Dec 2026)

I build applied ML systems across LLMs, agentic pipelines, RAG, and computer vision, from research prototyping to production deployments on GCP and AWS. Currently a Senior Data Scientist Intern at Capital One, researching LLM benchmarks at CMU's TEEL Lab, and building an AI-powered video generation startup at the Swartz Center for Entrepreneurship.

---

### What I'm Working On

- **Agentic AML Systems** : LangGraph agents automating suspicious-activity investigations at [Capital One](https://www.capitalone.com/)
- **LLM Benchmarking Research** : Semantic annotation benchmarks across finance, healthcare, news, and law at [TEEL Lab](https://www.cmu.edu/teel/), CMU
- **AI Video Generation Startup** : Building at the [Swartz Center for Entrepreneurship](https://www.cmu.edu/swartz-center-for-entrepreneurship/), CMU

---

### Experience

| Role | Organization | When |
|------|-------------|------|
| Senior Data Scientist Intern | **Capital One** | Jun 2026 – Present |
| Graduate Researcher, TEEL Lab | **Carnegie Mellon University SCS** | Aug 2025 – Present |
| Data Scientist | **Equifax** | Aug 2023 – Jul 2025 |
| Software Developer, Healthcare AI | **Quantiphi** | Aug 2022 – Jul 2023 |
| Founding Software Engineer | **Expify** | Jul 2021 – Jul 2022 |
| AI Research Intern, NLP & FinTech | **Nippon Life India AMC** | Mar 2021 – Jul 2021 |

Selected outcomes: cut AML case resolution time 98% (70 min → 2 min per case); 90% faster reporting across 300+ risk projects with LangGraph agents; credit-loss models at 87.6% accuracy informing over $45.5B in microfinance portfolios; 40% lower operational costs and 27% faster pipelines migrating legacy systems to GCP. Two Spotlight Awards at Equifax.

---

### Research

- **Semantic Span Annotation (SSA)** — accepted to **ACL 2026** (advisor: Dr. Jaromir Savelka). Unified span-annotation benchmark over 7 LLMs across 5 datasets, surfacing two distinct performance regimes: label definitions lifted F1 from 8.8% to 57.5% on ontology-heavy tasks but *hurt* pattern-based tasks like PII detection.
- **RolloutKV** (supervisor: Dr. Lei Li) — profiled KV-cache rollout strategies for veRL GRPO post-training of Qwen2.5-Coder-3B on MBPP; cut training wall-clock from 12k to 9k seconds and raised rollout throughput ~1.56x.
- **RedViz** (advisor: Adam Perer) — unified LLM red-teaming framework combining attention-map interpretability with realtime multilingual harm detection.

---

### Featured Projects

| Project | What It Does | Stack |
|---------|-------------|-------|
| [**EqRAG**](https://github.com/Anuj-G-06/EqRAG) | LLM fine-tuning (LoRA, IA3) for Dow 30 stock prediction. 12% zero-shot to 51.7% accuracy with Qwen-2.5-Math-7B, training 0.19% of parameters | Python, PyTorch, HuggingFace, PEFT |
| [**RedViz**](https://github.com/Anuj-G-06/redviz) | LLM red-teaming dashboard probing safety across 8 languages and 9 harm categories, with live jailbreak testing, token-level entropy, and attention maps on TinyLLaMA & LLaMA | Python, Streamlit, Altair |
| [**Skin-Burn-Detection**](https://github.com/Anuj-G-06/Skin-Burn-Detection) | YOLOv5s classifying burn severity into 3 levels across 14,044 medically validated images, via transfer learning from COCO. **Top 5 Finalist, TiE Global Hackathon** (650+ teams) | Python, PyTorch, YOLOv5 |
| [**Anime-GAN**](https://github.com/Anuj-G-06/Anime-GAN) | Three GAN architectures (DCGAN + Pix2Pix) generating anime faces from video frames. 28.5 dB PSNR, 0.91 SSIM | Python, Keras, PyTorch |

<details>
<summary><b>More Projects</b></summary>

| Project | What It Does |
|---------|-------------|
| [**Credit-Card-Fraud-Detection**](https://github.com/Anuj-G-06/Credit-Card-Fraud-Detection) | Fraud detection across 284,807 transactions at a 0.172% fraud rate; Random Forest reached 99.96% accuracy without resampling |
| [**Telecommunication-Churn-Prediction**](https://github.com/Anuj-G-06/Telecommunication-Churn-Prediction) | Five classifiers compared on 7,043 telecom customers; neural network hit 0.83 AUC, with contract type the strongest churn signal |

</details>

---

### Tech Stack

<p align="center">
  <!-- Languages -->
  <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/c++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/R-%23276DC3.svg?style=for-the-badge&logo=r&logoColor=white" />
</p>
<p align="center">
  <!-- LLM / NLP -->
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white" />
  <img src="https://img.shields.io/badge/HuggingFace-%23FFD21E.svg?style=for-the-badge&logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/LlamaIndex-000?style=for-the-badge&logo=meta&logoColor=white" />
  <img src="https://img.shields.io/badge/vLLM-4B0082?style=for-the-badge&logoColor=white" />
</p>
<p align="center">
  <!-- AI / ML -->
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/OpenCV-%235C3EE8.svg?style=for-the-badge&logo=opencv&logoColor=white" />
</p>
<p align="center">
  <!-- Data Engineering -->
  <img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Spark-FDEE21?style=for-the-badge&logo=apachespark&logoColor=black" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=Apache%20Airflow&logoColor=white" />
  <img src="https://img.shields.io/badge/MLflow-%230194E2.svg?style=for-the-badge&logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Kafka-000?style=for-the-badge&logo=apachekafka" />
  <img src="https://img.shields.io/badge/Apache%20Flink-E6526F?style=for-the-badge&logo=Apache%20Flink&logoColor=white" />
</p>
<p align="center">
  <!-- Cloud & Infra -->
  <img src="https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white" />
  <img src="https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/BigQuery-%23669DF6.svg?style=for-the-badge&logo=googlebigquery&logoColor=white" />
  <img src="https://img.shields.io/badge/Snowflake-%2329B5E8.svg?style=for-the-badge&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white" />
</p>
<p align="center">
  <!-- Databases & Web -->
  <img src="https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
  <img src="https://img.shields.io/badge/Amazon%20DynamoDB-4053D6?style=for-the-badge&logo=Amazon%20DynamoDB&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-%23009688.svg?style=for-the-badge&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white" />
</p>

---

### Certifications

- **Google Cloud Certified** : Associate Cloud Engineer
- **AWS Certified** : Solutions Architect Associate

---

### Connect

<p align="center">
  <a href="https://cs.cmu.edu/~anujg2"><img src="https://img.shields.io/badge/Portfolio-cs.cmu.edu/~anujg2-000?style=for-the-badge&logo=vercel&logoColor=white" /></a>
  <a href="https://www.linkedin.com/in/anuj-gupta-2k/"><img src="https://img.shields.io/badge/LinkedIn-Anuj%20Gupta-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:anujg2@cs.cmu.edu"><img src="https://img.shields.io/badge/Email-anujg2@cs.cmu.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://medium.com/@anuj.1306.gupta"><img src="https://img.shields.io/badge/Medium-@anuj.1306.gupta-12100E?style=for-the-badge&logo=medium&logoColor=white" /></a>
  <a href="https://x.com/Anuj_M_G"><img src="https://img.shields.io/badge/X-@Anuj__M__G-000?style=for-the-badge&logo=x&logoColor=white" /></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=anuj-g-06&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views"/>
</p>
