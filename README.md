# Create a corrected, full-length GitHub README (with proper contact details)
# and package it together with the custom banner image into a downloadable zip.

import os, zipfile, shutil, textwrap, json

root = "/mnt/data/ramana_github_profile_readme"
os.makedirs(root, exist_ok=True)

banner_src = "/mnt/data/A_professional_digital_banner_features_Ramana_Redd.png"
banner_dst = os.path.join(root, "A_professional_digital_banner_features_Ramana_Redd.png")
shutil.copyfile(banner_src, banner_dst)

readme = """<!-- Banner -->
<p align="center">
  <img src="A_professional_digital_banner_features_Ramana_Redd.png" alt="Ramana Reddy Banner" width="100%">
</p>

<!-- Greeting -->
<h1 align="center">Hi there, I'm Ramana 👋</h1>
<h3 align="center">Data Scientist 🧠 | AI/ML Engineer 🤖 | Generative AI Specialist 💡</h3>

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="350">
</p>

---

## 🚀 About Me
I’m <b>Venkata Ramana Reddy Karnati</b>, a passionate <b>Data Scientist</b> and <b>AI/ML Engineer</b> with expertise in building scalable machine learning systems, NLP pipelines, and Generative AI applications.
I love solving complex problems using <b>data-driven approaches</b> and turning research into production-ready solutions.

- 🔭 <b>Current focus:</b> AI-powered healthcare analytics & RAG-based assistants for complex domains
- 🌱 <b>Learning:</b> Advanced LLM fine-tuning, vector databases, and robust MLOps
- 💬 <b>Ask me about:</b> Python, Machine Learning, NLP, Generative AI, Data Engineering
- 🌐 <b>Portfolio:</b> <a href="https://venkata-portfolio-chi.vercel.app" target="_blank">venkata-portfolio-chi.vercel.app</a>

---

## 🛠 My AI/ML Toolkit

### Languages & Databases
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-336791?style=flat&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat&logo=r&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Snowflake](https://img.shields.io/badge/-Snowflake-29B5E8?style=flat&logo=snowflake&logoColor=white)
![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Redshift](https://img.shields.io/badge/-Redshift-8C4FFF?style=flat&logo=amazon-aws&logoColor=white)

### Machine Learning / AI
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/-Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Transformers](https://img.shields.io/badge/-Transformers-FFD43B?style=flat&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/-LangChain-12100E?style=flat)
![LlamaIndex](https://img.shields.io/badge/-LlamaIndex-195ef2?style=flat)
![OpenAI](https://img.shields.io/badge/-OpenAI-412991?style=flat&logo=openai&logoColor=white)
![MLflow](https://img.shields.io/badge/-MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

### Data Engineering & MLOps
![Apache Spark](https://img.shields.io/badge/-Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white)
![Databricks](https://img.shields.io/badge/-Databricks-FF3621?style=flat&logo=databricks&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Airflow](https://img.shields.io/badge/-Apache%20Airflow-017CEE?style=flat&logo=apacheairflow&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat&logo=fastapi&logoColor=white)

### Visualization & BI
![Tableau](https://img.shields.io/badge/-Tableau-E97627?style=flat&logo=tableau&logoColor=white)
![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Matplotlib](https://img.shields.io/badge/-Matplotlib-11557c?style=flat)
![Seaborn](https://img.shields.io/badge/-Seaborn-0099CC?style=flat)

---

## 📂 Featured Projects

### <a href="https://github.com/ramanareddy-ai/AI-Powered-Diabetes-Risk-Care-System" target="_blank">AI-Powered Diabetes Risk Care System</a>
ML-powered system predicting diabetes risk and providing preventive recommendations.  
<b>Tech:</b> Python, Pandas, Scikit-learn, Streamlit.

### Legal Case Management AI System
RAG + GenAI-powered platform for legal document processing and automated demand letter generation.  
<b>Tech:</b> Python, LangChain, OpenAI API, PostgreSQL, FastAPI.

### Predictive Analytics for Banking
Credit risk modeling using transactional and behavioral data.  
<b>Tech:</b> Python, XGBoost, SQL, Tableau.

---

## 🏆 Achievements & Certifications
- AWS Certified Developer – Associate
- Google Cloud Professional Data Engineer
- Oracle Certified Associate, Java SE 8 Programmer I
- IBM: Python Project for Data Science
- HackerRank: SQL Advanced

---

## 📊 GitHub Stats & Streak

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ramanareddy-ai&show_icons=true&theme=radical" height="160"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=ramanareddy-ai&theme=radical" height="160"/>
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ramanareddy-ai&layout=compact&theme=radical" height="160"/>
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=ramanareddy-ai&theme=gruvbox&no-frame=false&no-bg=false&margin-w=4"/>
</p>

---

## 🤝 Connect with Me
<a href="mailto:ramanadata568@gmail.com">
  <img src="https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white" />
</a>
<a href="https://www.linkedin.com/in/ramanareddy444" target="_blank">
  <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" />
</a>
<a href="https://github.com/ramanareddy-ai" target="_blank">
  <img src="https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white" />
</a>

---
"""

with open(os.path.join(root, "README.md"), "w", encoding="utf-8") as f:
    f.write(readme)

zip_path = "/mnt/data/ramana_github_profile_readme.zip"
with zipfile.ZipFile(zip_path, "w", zipfile.ZIP_DEFLATED) as z:
    for base, _, files in os.walk(root):
        for nm in files:
            fp = os.path.join(base, nm)
            z.write(fp, arcname=os.path.relpath(fp, root))

zip_path
