## Hi, I'm Vishal Kumar Reddy Gudla

**AI / ML Engineer · London, UK** · I build ML systems that are evaluated honestly, deployed, and kept running.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-vishalkumar--gudla-0077B5?logo=linkedin&logoColor=white)](https://linkedin.com/in/vishalkumar-gudla)
[![Email](https://img.shields.io/badge/Email-reddyvishal0311%40gmail.com-D14836?logo=gmail&logoColor=white)](mailto:reddyvishal0311@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-bit.ly%2FVishalgudla-555?logo=google-chrome&logoColor=white)](https://bit.ly/Vishalgudla)

- **4+ years** of production software engineering, **2+ years** building end-to-end ML pipelines
- Focus: semantic search and RAG, computer vision, MLOps (CI, monitoring, reproducible training)
- Open to **AI/ML, ML platform, backend and data engineering** roles in the UK

---

### Featured projects

#### [HireSense AI](https://github.com/lonewolf1621/hiresense-ai): semantic CV ↔ job matching · [live demo](https://hiresense-ai-vishal.streamlit.app) · [API](https://hiresense-ai-3k4d.onrender.com/docs)

[![tests](https://github.com/lonewolf1621/hiresense-ai/actions/workflows/tests.yml/badge.svg)](https://github.com/lonewolf1621/hiresense-ai/actions/workflows/tests.yml) [![uptime](https://github.com/lonewolf1621/hiresense-ai/actions/workflows/uptime.yml/badge.svg)](https://github.com/lonewolf1621/hiresense-ai/actions/workflows/uptime.yml)

`Python` `FastAPI` `Sentence Transformers (ONNX)` `FAISS` `Streamlit` `GitHub Actions`

- Scores a CV against a job advert: matched and missing skills, plus the CV line that best supports each requirement (MiniLM embeddings + FAISS retrieval, with job-advert boilerplate filtered out)
- **Ranks up to 10 CVs** against one job, with CSV and report downloads
- Benchmarked on **1,759 human-labelled CV/job pairs** with results published, including what didn't work; ~16,700 pairs/hour on one CPU
- Runs on its own: uptime checks every 6 hours with alert issues, a weekly benchmark regression guard, Dependabot

#### [Thyroid ML System](https://github.com/lonewolf1621/thyroid-ml-system): clinical risk + ultrasound classification · [live demo](https://thyroid-ml-system.onrender.com)

[![tests](https://github.com/lonewolf1621/thyroid-ml-system/actions/workflows/ml_pipeline.yml/badge.svg)](https://github.com/lonewolf1621/thyroid-ml-system/actions/workflows/ml_pipeline.yml) [![uptime](https://github.com/lonewolf1621/thyroid-ml-system/actions/workflows/uptime.yml/badge.svg)](https://github.com/lonewolf1621/thyroid-ml-system/actions/workflows/uptime.yml)

`PyTorch` `EfficientNet-B0` `scikit-learn` `XGBoost` `MLflow` `FastAPI` `Docker`

- Benign vs malignant ultrasound classifier: **ROC-AUC 0.93** on the TN5000 test set and **0.80 on TN3K**, an independent hospital's data
- **Grad-CAM heatmaps** show which image regions drove each prediction
- Hypothyroidism risk from lab values with three tracked models; **batch CSV scoring** for up to 1,000 patients
- Model card, input validation, tests in CI, Docker deployment and automated live checks

---

### Tech stack

**ML / AI:** Python · PyTorch · scikit-learn · XGBoost · Hugging Face · Sentence Transformers · FAISS · spaCy
**Backend:** FastAPI · REST APIs · PostgreSQL · Streamlit
**MLOps / data:** MLflow · Docker · GitHub Actions · GCP · BigQuery · Apache Spark · Linux
