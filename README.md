<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=220&section=header&text=Palli%20Gayathri&fontSize=65&fontColor=fff&animation=twinkling&fontAlignY=38&desc=AI%20%2F%20ML%20Engineer%20%7C%20Deep%20Learning%20%7C%20Autonomous%20Systems&descAlignY=58&descSize=20" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6C63FF&center=true&vCenter=true&width=700&lines=Building+Intelligent+Systems+from+Research+to+Production+%F0%9F%9A%80;Deep+Reinforcement+Learning+%7C+DQN+%7C+Multi-Agent+RL+%F0%9F%A7%A0;Autonomous+Systems+%7C+Self-Driving+Agents+%F0%9F%9A%97;Computer+Vision+%7C+YOLOv8+%7C+Real-Time+Detection+%F0%9F%94%8D;LLM+%26+RAG+Architect+%7C+Document+Intelligence+%F0%9F%93%84)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/palli-gayathri-1a5105384/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PalliGayathri)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/YOUR_LEETCODE)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bapujipalli452@gmail.com)

<img src="https://komarev.com/ghpvc/?username=PalliGayathri&label=Profile+Views&color=6C63FF&style=for-the-badge" alt="profile views"/>

</div>

---

## 🧬 About Me

```python
class PalliGayathri:
    def __init__(self):
        self.name        = "Palli Gayathri"
        self.role        = "AI/ML Engineer | Deep Learning & Autonomous Systems Developer"
        self.education   = "B.Tech in AI & ML @ Sreenidhi Institute of Science & Technology"
        self.experience  = "ML Intern @ Optern EduWorks"
        self.passion     = [
            "Deep Reinforcement Learning (DQN, PPO, Multi-Agent)",
            "Autonomous & Self-Driving Systems",
            "LLMs, RAG Pipelines & Document Intelligence",
            "Real-Time Computer Vision"
        ]
        self.currently   = [
            "Advanced LLM Fine-tuning & PEFT techniques",
            "Production ML Systems & Scalable Architectures",
            "MLOps, CI/CD for ML, and Model Monitoring"
        ]
        self.mission     = "Bridging the gap between cutting-edge AI research and real-world deployment"

    def greet(self):
        return "Let's build something intelligent that actually works in the real world! 🚀"
```

---

## 💼 Professional Experience

<table width="100%">
<tr>
<td width="30%" valign="top">

### 🏢 ML Intern
**Optern EduWorks**
`July 2025 – August 2025`

> Contributed to production-grade ML systems serving real candidates at scale.

</td>
<td width="70%" valign="top">

**🎯 Job Recommendation Engine**
- Designed and deployed an intelligent job-matching system using collaborative filtering and NLP-based semantic similarity
- Achieved **85% accuracy improvement** over the previous rule-based system by leveraging candidate skill embeddings and job description vectorization
- Integrated with a REST API backend for real-time candidate-job matching

**✍️ Automated Cover Letter Generation**
- Built an LLM-powered pipeline that auto-generates personalized cover letters tailored to job descriptions
- Deployed for **500+ active candidates**, reducing manual effort by **60%**
- Used prompt engineering + template chaining to ensure professional tone consistency

**⚡ Inference Optimization**
- Profiled and optimized model inference pipelines, reducing latency by **30%**
- Integrated async REST API endpoints to handle concurrent requests efficiently
- Improved system throughput for real-time candidate processing

</td>
</tr>
</table>

---

## 🏆 Featured Projects

### 🤖 Multi-Environment DQN Agent

<table>
<tr><td width="65%">

**A deep reinforcement learning system that simultaneously trains agents across 3 different environments using a shared encoder architecture.**

- Implemented **DQN variants** (Double DQN, Dueling DQN, Prioritized Experience Replay) from scratch in PyTorch
- Designed a **shared convolutional encoder** that learns generalizable representations across multiple Highway-env scenarios (highway, merge, roundabout)
- Achieved stable convergence with **parallel environment stepping** to maximize sample efficiency
- Benchmarked agent performance across environments, analyzing transfer learning and policy generalization

</td>
<td width="35%" valign="top">

**Tech Stack**
`PyTorch` `Gymnasium` `Highway-env`
`NumPy` `Matplotlib` `Python`

**Key Results**
- 3 environments, 1 shared encoder
- Stable multi-task RL training
- Transfer learning across scenarios

</td>
</tr>
</table>

---

### 🚗 Self-Driving Car — Zero-Knowledge RL Agent

<table>
<tr><td width="65%">

**An autonomous driving agent that learns to navigate complex racing circuits from absolute scratch — no human demonstrations, no pre-training.**

- Built a complete RL pipeline using **PPO / DQN** in a CARLA simulation environment
- The agent starts with **zero knowledge** and learns purely through reward signals (lane keeping, speed control, collision avoidance)
- Designed a custom **reward shaping function** to incentivize smooth steering and penalize unsafe behavior
- Implemented **curriculum learning** — progressively increasing track difficulty as the agent improves
- Achieved consistent lap completion on multiple circuit layouts after training

</td>
<td width="35%" valign="top">

**Tech Stack**
`PyTorch` `CARLA Simulator`
`OpenAI Gym` `OpenCV` `Python`

**Key Results**
- Zero prior knowledge → full lap completion
- Custom reward shaping engine
- Curriculum-based difficulty scaling

</td>
</tr>
</table>

---

### 🚦 Real-Time Traffic Monitoring System

<table>
<tr><td width="65%">

**A production-ready computer vision pipeline for intelligent traffic analysis using live video feeds.**

- Deployed **YOLOv8** for real-time multi-class vehicle detection (cars, trucks, bikes, buses) at high FPS
- Implemented **speed estimation** using frame-to-frame displacement and camera calibration coefficients
- Built a **traffic flow analyzer** that tracks vehicle density, congestion zones, and directional flow
- Added **object tracking** (ByteTrack / DeepSORT) to maintain vehicle identity across frames
- Designed a live dashboard using OpenCV for visualization of detection overlays and traffic metrics

</td>
<td width="35%" valign="top">

**Tech Stack**
`YOLOv8` `OpenCV` `Python`
`ByteTrack` `NumPy` `Matplotlib`

**Key Results**
- Real-time multi-class detection
- Speed & density estimation
- Live visual dashboard

</td>
</tr>
</table>

---

### 📄 Document Intelligence Platform

<table>
<tr><td width="65%">

**An enterprise-grade document Q&A system powered by RAG (Retrieval-Augmented Generation) for context-aware, accurate document analysis.**

- Built an end-to-end **RAG pipeline**: PDF ingestion → chunking → embedding → vector storage → semantic retrieval → LLM response generation
- Integrated with **LangChain** for orchestration and **FAISS / Pinecone** as the vector database backend
- Supports multi-document Q&A with **source citation** — every answer is traceable to the original document section
- Deployed as an interactive **Streamlit** web app with drag-and-drop document upload and real-time Q&A
- Handles complex enterprise use cases: contracts, reports, research papers, HR documents

</td>
<td width="35%" valign="top">

**Tech Stack**
`LangChain` `OpenAI / Mistral LLM`
`FAISS` `Streamlit` `Python`
`HuggingFace Embeddings`

**Key Results**
- Multi-doc Q&A with source citations
- Sub-second retrieval on large corpora
- Drag-and-drop web interface

</td>
</tr>
</table>

---

## 🛠 Tech Stack

<div align="center">

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

### AI / ML & Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)
![Hugging Face](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

### LLMs & Data Tools
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLOv8-00FFFF?style=for-the-badge&logo=yolo&logoColor=black)

### DevOps & Cloud
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=PalliGayathri&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6C63FF&icon_color=6C63FF&text_color=FFFFFF&rank_icon=github" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=PalliGayathri&theme=tokyonight&hide_border=true&background=0D1117&stroke=6C63FF&ring=6C63FF&fire=FF6B6B&currStreakLabel=6C63FF" width="48%" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=PalliGayathri&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6C63FF&text_color=FFFFFF" width="40%" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=PalliGayathri&bg_color=0D1117&color=6C63FF&line=6C63FF&point=FF6B6B&area=true&hide_border=true" width="90%"/>

</div>

---

## 🧩 Competitive Programming

<div align="center">

| Platform | Solved | Focus Areas |
|:--------:|:------:|:-----------:|
| ![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=black) | **500+ Problems** | Arrays, DP, Graphs, Trees |
| ![Coding Ninjas](https://img.shields.io/badge/Coding%20Ninjas-E05D44?style=flat-square&logo=codingninjas&logoColor=white) | **200+ Problems** | DSA, Problem Solving |

</div>

---

## 📚 Currently Exploring

```
🔬  Advanced LLM Fine-tuning — LoRA, QLoRA, PEFT techniques
🏭  Production ML — model serving, monitoring, and scalability engineering
⚙️  MLOps — CI/CD pipelines for ML, experiment tracking, model registries
🤝  Multi-Agent RL systems and cooperative AI architectures
```

---

## 🎓 Education

**B.Tech in Artificial Intelligence & Machine Learning**
Sreenidhi Institute of Science and Technology
`2022 – 2026`

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=130&section=footer&animation=twinkling" width="100%"/>

### 💬 Let's Connect & Build Together!

> *"The best way to predict the future is to invent it."* — Alan Kay

**Open to:** Full-time roles · Internships · Research collaborations · AI/ML discussions

⭐ **Explore my repositories and feel free to reach out — always excited to work on impactful AI projects!**

[![LinkedIn](https://img.shields.io/badge/Let's_Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/palli-gayathri-1a5105384/)
[![Email](https://img.shields.io/badge/Send_Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bapujipalli452@gmail.com)

</div>
