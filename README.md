<h1 align="center">Hi, I'm Mohamed Sahbi Ben Kalaia 👋</h1>
<p align="center"><b>Software Engineering student · Applied AI & data-intensive systems</b><br/>Tunis, Tunisia</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohamed-sahbi-ben-kalaia-52870a360/">LinkedIn</a> ·
  <a href="mailto:mohamedsahbi.benkalia@insat.ucar.tn">Email</a>
</p>

---

## About me

Final-year Software Engineering student at **INSAT** (University of Carthage), focused on applied AI and data-intensive systems. Through internships in medical imaging, regulatory document analysis and big-data pipelines, I've learned that I enjoy the research side of engineering most: designing architectures, testing hypotheses, and iterating when the results fall short.

- 🎓 **Studying:** National Engineering Degree in Software Engineering, INSAT (2022–2027)
- 🧠 **Interests:** NLP and LLMs, medical imaging, graph-based reasoning, big data and streaming
- 🏁 **Outside class:** CTF competitions (web exploitation) and competitive programming
- 🗣️ **Languages:** Arabic (native), English (advanced), French (intermediate), German (beginner)

---

## Featured projects

| Project | What it does | Highlight |
|---|---|---|
| [**document-incoherence-detection**](https://github.com/MedSahbiBenKalia/document-incoherence-detection) | Finds contradictions between QHSE documents. A Neo4j dependency graph selects which clauses to compare, then rules → NLI → LLM judge verify them with verbatim evidence | **95 %** of pairs pruned, **19/19** inconsistencies kept, **16/19** found (F1 0.80) on a small synthetic corpus |
| [**dental-xray-anomaly-detection**](https://github.com/MedSahbiBenKalia/dental-xray-anomaly-detection) | Two-stage pipeline on panoramic X-rays: U-Net + ResNet-34 tooth segmentation, then EfficientNet-B3 per-tooth diagnosis | Dice **0.84**, handles a ~128:1 class imbalance; evaluated on 50 unseen X-rays |
| [**fer2013-emotion-recognition-benchmark**](https://github.com/MedSahbiBenKalia/fer2013-emotion-recognition-benchmark) | Six models compared on FER2013, plus a Streamlit app to test them | A 5.87M-parameter custom CNN reaches **66.9 %** accuracy (0.651 macro-F1), beating VGG16 and ResNet50 |
| [**qhse-document-rag**](https://github.com/MedSahbiBenKalia/qhse-document-rag) | French question answering over QHSE documents: FAISS retrieval + Google Gemini, answers grounded in and cited from the sources | Strict prompt: context-only answers, mandatory citations, explicit "I don't know" |
| [**music-analytics-lambda-pipeline**](https://github.com/MedSahbiBenKalia/music-analytics-lambda-pipeline) | Lambda-architecture pipeline on 550K Spotify tracks: Kafka, HDFS, Spark batch + streaming, Cassandra / PostgreSQL / Elasticsearch, Grafana | Real-time mood tracking, trend and anomaly detection, K-Means genre clustering |
| [**film-revenue-prediction**](https://github.com/MedSahbiBenKalia/film-revenue-prediction) | Six regressors benchmarked to predict box-office revenue from pre-release data, with a Flask app | Random Forest **R² 0.751**; engineered a Bayesian cast star-power feature; Gaussian Process uncertainty |

Also built: **DoussiyaFidaya**, a full-stack medical platform (NestJS, Next.js, PostgreSQL) with role-based spaces, 2FA and an AI layer (OCR + RAG chatbot), and a **package delivery optimiser** implementing six search algorithms from scratch in Java.

---

## Experience

**R&D Software Engineering Intern, Saphir Consult (Qualipro)**, Tunis
- *Jul–Aug 2026:* architected a cross-document contradiction detector for QHSE normative documents (Neo4j dependency graph, spaCy → NLI → LLM cascade).
- *Jul 2025:* built a RAG question-answering system (Sentence Transformers, FAISS, Gemini API) with a Flask web app.

---

## Tech stack

**Languages:** Python · JavaScript · TypeScript · Java · C++ · C# · C · PHP · SQL

<p>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/spaCy-09A3D5?logo=spacy&logoColor=white" />
  <img src="https://img.shields.io/badge/FAISS-RAG-0467DF" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?logo=apachekafka&logoColor=white" />
  <img src="https://img.shields.io/badge/Elasticsearch-005571?logo=elasticsearch&logoColor=white" />
  <img src="https://img.shields.io/badge/Cassandra-1287B1?logo=apachecassandra&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1?logo=neo4j&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/NestJS-E0234E?logo=nestjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white" />
  <img src="https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET-512BD4?logo=dotnet&logoColor=white" />
  <img src="https://img.shields.io/badge/Symfony-000000?logo=symfony&logoColor=white" />
</p>
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?logo=terraform&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
</p>

**Also:** Sentence Transformers · RAG · LLaMA 4 · Mistral 7B · Gemini API · LM Studio · OCR · MLlib · HDFS · MySQL · SQL Server · Metabase · pytest / TDD

---

## Certifications

- HackerRank: Software Engineer Intern (Java, Python, REST API)
- Google: Cloud Computing Foundations (Cloud Computing Fundamentals, Infrastructure in Google Cloud)

---

<p align="center">
  <i>Let's connect: I'm happy to talk about NLP, applied AI and data systems.</i><br/>
  <a href="https://www.linkedin.com/in/mohamed-sahbi-ben-kalia-52870a360/">LinkedIn</a> ·
  <a href="mailto:mohamedsahbi.benkalia@insat.ucar.tn">Email</a>
</p>
