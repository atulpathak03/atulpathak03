# Atul Pathak

### ML Engineer • AI/LLM Systems • Deep Learning • Backend Engineering

<p align="left">
  <a href="https://github.com/atulpathak03">
    <img src="https://komarev.com/ghpvc/?username=atulpathak03&label=Profile%20Views&color=0e75b6&style=flat" />
  </a>
  <a href="https://github.com/atulpathak03?tab=followers">
    <img src="https://img.shields.io/github/followers/atulpathak03?label=Followers&style=flat" />
  </a>
</p>

> I build **machine learning systems, LLM applications, and backend services** — from model development and experimentation to APIs, retrieval pipelines, real-time data processing, and deployment.

I'm a **B.Tech student at MNNIT Allahabad** with a strong focus on **Machine Learning, Deep Learning, Generative AI and Software Engineering**.

My work spans the complete AI stack:

**Data → Features → Models → LLMs → RAG/Agents → APIs → Deployment**

---

## What I Do

```text
┌─────────────────────────────────────────────────────────────┐
│                        AI / ML                              │
│                                                             │
│  Machine Learning   →   Deep Learning   →   GenAI          │
│  Feature Engineering    CNN/RNN/LSTM       RAG              │
│  Model Evaluation       Transformers       Agents           │
│  Experimentation         Transfer Learning  Vector Search   │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│                    ENGINEERING                              │
│                                                             │
│  Python / C++      FastAPI      REST APIs      PostgreSQL   │
│  Redis             MongoDB      WebSockets     Docker       │
│                                                             │
├─────────────────────────────────────────────────────────────┤
│                       SYSTEMS                              │
│                                                             │
│  Real-time Data    TCP/UDP      PMU Streaming   Pipelines  │
│  Signal Processing  Concurrency  Distributed Systems        │
└─────────────────────────────────────────────────────────────┘
```

---

# Featured Work

## Research & Machine Learning

### Power Grid Forecasting & Real-Time PMU Analytics

**Research Intern — MNNIT Allahabad**

Worked on real-time power-system analytics using synchronized **PMU data and deep learning**.

* Simulated IEEE power grids using **MATPOWER**
* Generated synchronized PMU datasets across load and fault scenarios
* Developed a **BiLSTM** model for active/reactive power forecasting
* Built PMU frame decoding and timestamp synchronization
* Implemented **CRC-CCITT** validation and SADF-based parsing
* Implemented **IEEE C37.118.2-2011** over TCP/UDP
* Built an online signal-processing pipeline for voltage, current, frequency, ROCOF and power features

**Focus:** `Time Series` `BiLSTM` `PMU` `Signal Processing` `TCP/UDP` `Real-Time Systems`

---

# Generative AI

## ResearchMind AI

> Autonomous multi-agent AI research and report-generation platform.

**Architecture**

```text
User Query
    │
    ▼
Research Planner
    │
    ├── Web Search
    │
    ├── Web Scraping
    │
    ├── Source Extraction
    │
    ▼
Research Synthesis
    │
    ▼
LLM-as-a-Judge
    │
    ▼
Final Report
```

**Built with**

`Python` `LangChain` `OpenAI API` `Tavily` `BeautifulSoup4` `Streamlit` `REST APIs`

Key engineering work:

* Designed a **4-stage multi-agent architecture**
* Built web ETL pipelines for search, scraping and source extraction
* Implemented an **LLM-as-a-Judge** evaluation chain
* Designed a 10-point report-quality evaluation rubric
* Added real-time execution-state tracking
* Automated Markdown report generation

---

## AI Video & Meeting Assistant

> Multilingual RAG system for transcription, meeting intelligence and contextual Q&A.

```text
Video / Audio
     │
     ▼
 yt-dlp + PyDub
     │
     ▼
 Speech Recognition
 Whisper + Sarvam AI
     │
     ▼
 Chunking + Embeddings
     │
     ▼
 ChromaDB Vector Store
     │
     ▼
 Hybrid Retrieval
     │
     ▼
 Mistral AI
     │
     ▼
 Contextual Q&A
```

**Stack:** `Whisper` `Sarvam AI` `LangChain` `ChromaDB` `HuggingFace` `Mistral AI` `Streamlit`

---

# Machine Learning Engineering

## Mental Health Score Predictor

End-to-end ML application taking a model from **raw data → preprocessing → training → API → deployment**.

* Built an end-to-end **Scikit-Learn pipeline**
* Feature grouping, log transformations and ordinal encoding
* Optimized a **Random Forest Regressor** using 5-fold cross-validation
* Achieved **R² = 0.85**
* Built a production-style **FastAPI** inference service
* Added Pydantic request validation
* Deployed inference service to Render
* Built interactive frontend visualizations

**Stack:** `Python` `Scikit-Learn` `FastAPI` `Pandas` `NumPy` `Pydantic` `Joblib` `JavaScript`

---

# Technical Stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square\&logo=c%2B%2B\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)

### Machine Learning

![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square\&logo=scikit-learn\&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat-square)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square\&logo=tensorflow\&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square\&logo=keras\&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square\&logo=pytorch\&logoColor=white)

`Regression` `Classification` `Decision Trees` `Random Forest` `SVM` `KNN` `Clustering`

### Deep Learning

`ANN` `CNN` `RNN` `LSTM` `GRU` `BiLSTM` `Transformers` `Transfer Learning`

### GenAI / LLM Engineering

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square\&logo=openai\&logoColor=white)

`RAG` `Agentic AI` `CRAG` `LangGraph` `LangChain` `Embeddings`

`Vector Databases` `Hybrid Search` `LLM Evaluation` `LLM-as-a-Judge`

### Backend & APIs

`FastAPI` `REST APIs` `Node.js` `Express.js` `React.js` `Socket.IO`

### Databases

`PostgreSQL` `MongoDB` `Redis` `ChromaDB`

### Data & Analytics

`Pandas` `NumPy` `Statistical Analysis` `Data Visualization` `Power BI` `Excel`

---

# Engineering Interests

I'm particularly interested in the intersection of:

```text
Machine Learning
       +
Generative AI
       +
Backend Engineering
       +
Distributed / Real-Time Systems
```

Areas I'm currently exploring:

* Advanced RAG architectures
* Agentic AI systems
* LLM evaluation
* Multimodal AI
* Time-series forecasting
* Deep learning architectures
* ML model serving
* Scalable AI backends
* Distributed systems
* Real-time data pipelines

---

# Problem Solving

### 550+ LeetCode Problems

I regularly practice **Data Structures & Algorithms** and competitive programming.

```text
Arrays              Graphs
Binary Search       Dynamic Programming
Trees               Greedy
Heaps               Sliding Window
Stacks              Backtracking
DSU                 Shortest Paths
Bit Manipulation    Recursion
```

# Currently Building

```python
class AtulPathak:

    focus = [
        "Machine Learning",
        "Deep Learning",
        "Generative AI",
        "LLM Systems",
        "Backend Engineering",
        "System Design"
    ]

    philosophy = "Build systems, not just demos."

    goal = "Become an exceptional AI / Software Engineer."
```

---

# Let's Connect

<p align="left">
  <a href="https://www.linkedin.com/in/atul-pathak03/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/atulpathak03">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <b>Machine Learning • Generative AI • Systems • Software Engineering</b>
</p>

<p align="center">
  <i>Turning data and ideas into intelligent systems.</i>
</p>
