<div align="center">
@ Chandresh Gohel
 
### AI / ML Engineer · Building AI that knows when it doesn't know
 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-chandresh--gohel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/chandresh-gohel/)
[![IEEE paper](https://img.shields.io/badge/IEEE-I3CTCON%202026-00629B?style=flat-square)](https://doi.org/10.1109/I3CTCON68242.2026.11507628)
[![Live demo](https://img.shields.io/badge/Live%20demo-Engine%20Health%20Agent-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://cgcmapsssimgp.streamlit.app/)
![Open to work](https://img.shields.io/badge/Status-Open%20to%20Entry--level%20Roles-brightgreen?style=flat-square)
 
</div>
 
## 👋 About me
 
I recently completed my M.Tech in Computer Science & Engineering (Artificial Intelligence) at the Defence Institute of Advanced Technology (DIAT), Pune. The thread through my work is **reliability**: models that say how uncertain they are, systems that decline instead of guessing, and evaluations that check whether a result actually holds.
 
- 📄 First-author IEEE paper on sonar object detection for autonomous underwater vehicles
- 🔧 ML internship at Rolls-Royce Power Systems, modelling engine fatigue with Gaussian Process Regression
- 🤖 Recent builds: predictive maintenance with calibrated uncertainty and LLM agents, and graph-based memory for chat assistants
Open to **AI/ML engineering, applied AI and research engineering roles**. Open to relocation.
 
---
 
## ⭐ Featured projects
 
### ✈️ Engine Health Agent · Meta Global AI Developer Hackathon 2026
 
**[Live app](https://cgcmapsssimgp.streamlit.app/) · [Demo video](https://youtu.be/3SeoF6LADgI) · [Code](https://github.com/Chandresh-Gohel/NASA_CMAPSS_Meta_Global_AIHT)**
 
Predicts the remaining useful life of turbofan engines (NASA C-MAPSS) with a calibrated 90% band, and turns it into **INSPECT / NO_INSPECTION / ABSTAIN** in plain code. Muse Spark agents explain each decision. They can escalate a decision but never make one, and every number they write is checked against the model's output.
 
- 0 of 106 failures missed, against 42 for fixed-interval maintenance
- Every injected sensor fault led to ABSTAIN instead of a guess
`PyTorch` `GPyTorch` `Conformal prediction` `LLM agents` `Streamlit`
 
### 🧠 Recall · Graph memory for LLM agents · Hack Hydra 2026
 
**[Code](https://github.com/Chandresh-Gohel/hackhydra_t3_recall) · [Demo video](https://www.youtube.com/watch?v=_mHDJMk_SiE)**
 
Stores a chat history as a timestamped knowledge graph in HydraDB and answers by graph traversal, with no embeddings. When no supporting facts exist, it declines instead of guessing.
 
- 0.75 accuracy against 0.58 for a long-context baseline, on a 12-question LongMemEval subset
- All 4 unanswerable questions correctly declined
`HydraDB` `OpenCypher` `Groq` `LLM evaluation`
 
### 🐟 Sonar-AUV Hybrid Pipeline · IEEE I3CTCON 2026
 
**[Code](https://github.com/Chandresh-Gohel/Sonar-AUV-Hybrid-Pipeline) · [Paper](https://doi.org/10.1109/I3CTCON68242.2026.11507628)**
 
Compares raw and preprocessed sonar input for fish detection and counting, across YOLO generations and model sizes, on the Caltech Fish Counting dataset (ARIS sonar).
 
- Preprocessing cut counting error (MAE) by 13.4% on the smallest model but hurt the larger ones: the right pipeline depends on model capacity
`YOLO` `OpenCV` `PyTorch`
 
### 🔎 CodeSage · LLM code review grounded in coding standards
 
**[Code](https://github.com/Chandresh-Gohel/CodeSage)**
 
Reviews code changes from Git diffs. It retrieves the most relevant coding standards from a vector store, using MMR so they don't repeat, and the LLM reviews the code against them.
 
- Recall@3 = 0.78: 7 of 9 expected standards retrieved on a hand-built test set
`LangChain` `ChromaDB` `Sentence Transformers` `Gemini`
 
---
 
## 💼 Experience
 
| Role | Organisation | What I built |
|---|---|---|
| **Engineering Intern (Machine Learning)**<br><sub>Jul – Dec 2025</sub> | Rolls-Royce Power Systems – MTU India | Gaussian Process Regression model predicting engine fatigue cycles, with calibrated uncertainty: 93% coverage on a 95% prediction interval, R² 0.89 |
| **Machine Learning Intern**<br><sub>Dec 2022 – Apr 2023</sub> | BISAG-N | CNN CAPTCHA solver trained on 500,000+ images: 95% test accuracy ([code](https://github.com/Chandresh-Gohel/CAPTCHA-detection-BISAG)) |
| **Artificial Intelligence Intern**<br><sub>Feb – Mar 2020</sub> | Mood Indigo, IIT Bombay | Image classification model with over 95% accuracy |
 
---
 
## 📄 Publication
 
**C. Gohel and S. Dhavale**, "End-to-End vs. Hybrid Pipelines: Quantifying Performance Trade-offs in Sonar Object Detection for Autonomous Underwater Vehicles," *Proc. 2026 IEEE Int. Conf. Convergence in Computing Technology (I3CTCON)*, May 2026. [doi:10.1109/I3CTCON68242.2026.11507628](https://doi.org/10.1109/I3CTCON68242.2026.11507628)
 
---
 
## 🛠️ Skills
 
**ML & AI**
 
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![GPyTorch](https://img.shields.io/badge/GPyTorch-4B4B4B?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat-square)
 
**Data & tools**
 
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
 
**Also worked with**
 
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
 
---
 
## 🧩 Other projects
 
- **[Email System](https://github.com/Chandresh-Gohel/Email-System-ASPNetCORE)** · ASP.NET Core + SQL Server email platform with attachments and role-based access control
- **[Bank Management System](https://github.com/Chandresh-Gohel/Bank-M-Sys-project)** · Django banking portal with OTP two-factor authentication, fund transfers and transaction history
---
 
## 📫 Let's connect
 
The best way to reach me is [LinkedIn](https://www.linkedin.com/in/chandresh-gohel/).
 
<div align="center">
<sub>Always learning · Always building</sub>
</div>
