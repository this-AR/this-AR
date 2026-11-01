<img src="assets/header-gold.svg" width="100%" alt="Aditya Rai — AI/ML Researcher, NIT Kurukshetra. Focus: 01 retrieval, 02 RAG and LLMs, 03 edge AI, 04 recsys. 3 papers, 2nd place at IEEE UERC 2026, Amazon ML Summer School 2026"/>

<div align="center">

<a href="https://github.com/this-AR">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=E3B341&center=true&vCenter=true&width=640&lines=Teaching+machines+to+find+the+right+answer+%F0%9F%94%8E;Retrieval+%E2%80%A2+RAG+%E2%80%A2+LLMs+%E2%80%A2+Recommender+Systems;Shrinking+88M+models+to+7M+for+the+edge+%E2%9A%A1;3+papers+%E2%80%A2+FIRE+%E2%80%A2+IJCB+%E2%80%A2+ACM+RecSys;Always+building+something+cool+%F0%9F%9A%80" alt="Typing intro"/>
</a>

<p>
  <a href="https://aditya-rai-portfolio-616843600343.asia-southeast1.run.app/"><img src="https://img.shields.io/badge/Portfolio-6e40c9?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://linkedin.com/in/aditya-rai"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:adityarai735@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=this-AR&style=for-the-badge&color=1f6feb&label=Profile+views" alt="Profile views"/>
</p>

</div>

<p align="center">
  <img src="assets/terminal.svg" width="100%" alt="Terminal: Aditya Rai — B.Tech AI &amp; ML at NIT Kurukshetra; researches information retrieval, RAG and edge-efficient deep learning; papers at FIRE 2025, IJCB 2026 and ACM RecSys 2026; 2nd place at IEEE UERC 2026"/>
</p>

## 🧠 About me

I'm a B.Tech student in **Artificial Intelligence & Machine Learning at NIT Kurukshetra** (CGPA 8.85, 2023–2027). My research is about **finding things**: multilingual information retrieval, retrieval-augmented generation, and recommendation. I also work on **making deep models small enough to run on edge devices**.

- 🔬 Research intern at NIT Kurukshetra, building cross-language math retrieval (Top 6 at FIRE 2025)
- 🥈 2nd place in **both tracks** of the IEEE Unconstrained Ear Recognition Challenge 2026
- ☀️ Selected for **Amazon ML Summer School 2026**
- 💬 Ask me about RAG pipelines, hybrid retrieval, knowledge distillation, or model pruning

## 📄 Publications

| | Paper | Venue |
|:-:|---|---|
| 🎵 | **Dialogue-Aware Conversational Music Recommendation via Multi-Modal Retrieval and Weighted RRF** | ACM RecSys 2026 · Music-CRS |
| 👂 | **System Description: Cascaded Knowledge Distillation and Structured Pruning for Edge Ear Biometrics** | IJCB 2026 · *in press* |
| ➗ | **Enhancing Multilingual Mathematical Document Retrieval: A Hindi-to-English Translation and ColBERT-based Approach** | FIRE 2025 · IIT (BHU) Varanasi |

## 🔬 Research highlights

<table>
<tr>
<td width="50%" valign="top">

### 👂 UERC 2026: Edge Ear Biometrics
Multi-stage **knowledge distillation + Taylor pruning**: SwinV2 88M → TinyViT 21M → **7.2M** parameters, small enough for a Raspberry Pi 4.

`🥈 2nd place, both tracks` · `91% smaller` · `AUC 96.8%`

<sub>PyTorch · TinyViT · SwinV2 · AdaFace · torch-pruning · 📄 IJCB 2026</sub>

</td>
<td width="50%" valign="top">

### ➗ CLMIR: FIRE 2025
Cross-language **math retrieval** (Hindi → English): translation followed by ColBERT late-interaction retrieval.

`Top 6 teams` · `MAP 0.148` · `nDCG 0.220`

<sub>ColBERT · NLP · Multilingual IR · 📄 FIRE 2025</sub>

</td>
</tr>
</table>

## 🚀 Featured repos

<table>
<tr>
<td width="50%" valign="top">

### 🩺 [QAMed](https://github.com/this-AR/QAMED)
A citation-aware **medical RAG** system built on MBBS textbooks.
Hybrid BM25 + dense retrieval, CrossEncoder reranking, multi-hop routing, and two-tier hallucination guardrails.

`86%+ faithfulness` · `~1s generation` · `Redis + semantic cache`

<sub>LLaMA-3.1 · LangChain · Qdrant · PubMedBERT · Langfuse</sub>

</td>
<td width="50%" valign="top">

### 🎶 [Team Sargam: Music-CRS](https://github.com/this-AR/sargam-music-crs)
A conversational music recommender for the ACM RecSys 2026 challenge. Multi-seed FAISS search over CF, audio and visual embeddings, plus BM25, merged with weighted RRF and an LLM exact-match extractor.

`9th academic track` · `47K-track catalog` · `📄 RecSys 2026`

<sub>FAISS · BM25 · Gemini · RRF</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧪 [neetcode-gpt](https://github.com/this-AR/neetcode-gpt)
A **GPT built from scratch**, starting from gradient descent and working up through self-attention, multi-head attention and transformer blocks to a working language model.

`attention from scratch` · `full GPT`

<sub>Python · NumPy</sub>

</td>
<td width="50%" valign="top">

### 🤖 [AI Research Agent](https://github.com/this-AR/AI_RESEARCHAGENT)
A **four-agent CrewAI pipeline**: lead discovery → email generation → workflow review → quality validation. It is being upgraded into an evidence-grounded app.

`multi-agent` · `LLM orchestration`

<sub>CrewAI · Python · LLMs</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [EEG Stress Detection](https://github.com/this-AR/eeg_stress_detection)
Replicates and extends a stress-detection paper on the **SAM40 EEG dataset** (40 subjects, 14 channels). Classifies 4-second windows as rest or stress, using band-pass filtering and per-subject normalisation.

`paper replication` · `biosignals`

<sub>scikit-learn · XGBoost · PyTorch · SciPy</sub>

</td>
<td width="50%" valign="top">

### 🎵 [Music Genre Classification](https://github.com/this-AR/Music_genre_class)
An IEEE paper's **modified CNN on MFCC features**, implemented on GTZAN across 10 genres.

`85.62% test accuracy` · `paper implementation`

<sub>TensorFlow · Keras · Librosa</sub>

</td>
</tr>
</table>

## 🌍 Open-source contributions

<table>
<tr>
<td width="50%" valign="top">

### ⚡ [AlphaGPU/leetgpu-challenges](https://github.com/AlphaGPU/leetgpu-challenges)
<sub>⭐ 1.2k · GPU programming challenges</sub>

- 🟣 [Make Top-p Sampling deterministic and reproducible](https://github.com/AlphaGPU/leetgpu-challenges/pull/374)
- 🟣 [Fix JAX reference crash in Speculative Decoding Verification](https://github.com/AlphaGPU/leetgpu-challenges/pull/368)
- 🟣 [Add challenge structure validator](https://github.com/AlphaGPU/leetgpu-challenges/pull/311)
- 🟣 [Fix stale `run_challenge.py` flag in docs](https://github.com/AlphaGPU/leetgpu-challenges/pull/367)
- 🟢 [Replace the degenerate OLS performance test](https://github.com/AlphaGPU/leetgpu-challenges/pull/377)
- 🟢 [Fix Count Array Element perf test range](https://github.com/AlphaGPU/leetgpu-challenges/pull/378)

</td>
<td width="50%" valign="top">

### 🎯 [sb-ai-lab/RePlay](https://github.com/sb-ai-lab/RePlay)
<sub>⭐ 417 · end-to-end recommender systems framework</sub>

- 🟢 [Preserve tensor feature `padding_value` during serialization](https://github.com/sb-ai-lab/RePlay/pull/92)

### 📘 [The_small_coder](https://github.com/Venkatesh-Shukla/The_small_coder)
<sub>Collaborative ML project</sub>

- 🟣 [Add RAG implementation](https://github.com/Venkatesh-Shukla/The_small_coder/pull/5) + 2 report PRs

</td>
</tr>
</table>

<p align="center"><sub>🟣 merged · 🟢 open</sub></p>

<details>
<summary><b>More things I've built</b></summary>
<br/>

- 🌳 [**Deepphenotree-CVPPA**](https://github.com/this-AR/Deepphenotree-CVPPA): plant phenotyping for the CVPPA workshop
- ☕ [**neetcode-practice**](https://github.com/this-AR/neetcode-practice): my NeetCode problem solutions in Java
- 📊 [**FIFA-Player-Analysis**](https://github.com/this-AR/FIFA-Player-Analysis) · [**Stock_analysis**](https://github.com/this-AR/Stock_analysis): data analysis notebooks

</details>

## 🏆 Achievements

- 🥈 **2nd place, both tracks**: Unconstrained Ear Recognition Challenge (UERC 2026), IEEE Biometrics Council
- 🎵 **9th place (Academic Track), 25th overall**: ACM RecSys 2026 Music-CRS Challenge
- 🏅 **Top 6**: CLMIR track, FIRE 2025
- ☀️ **Selected**: Amazon ML Summer School 2026
- 📈 **AIR 312**: Amazon ML Challenge 2026

## 🛠️ Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,java,pytorch,tensorflow,sklearn,fastapi,redis,sqlite,git,github,linux,vscode&theme=dark&perline=12" alt="Python, Java, PyTorch, TensorFlow, scikit-learn, FastAPI, Redis, SQLite, Git, GitHub, Linux, VS Code"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white" alt="LangChain"/>
  <img src="https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white" alt="Qdrant"/>
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white" alt="FAISS"/>
  <img src="https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Hugging Face"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Langfuse-000000?style=flat-square&logoColor=white" alt="Langfuse"/>
</p>

## ⚡ Under the hood

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=this-AR&theme=github-dark-blue&hide_border=true&background=0D1117&ring=E3B341&fire=E3B341&currStreakLabel=E3B341" alt="GitHub streak"/>
</p>

<p align="center">
  <img src="assets/transformer.svg" width="100%" alt="Animated transformer encoder: a forward pass flows up through embedding, multi-head self-attention, layer norm and feed-forward blocks, beside a live attention heatmap over the tokens query, retrieve, rerank, ground, generate, distill, deploy"/>
</p>

<p align="center"><sub>
The tokens in the heatmap are the stages of my own work: <b>query → retrieve → rerank → ground → generate</b> is the <a href="https://github.com/this-AR/QAMED">QAMed</a> RAG pipeline, and <b>distill → deploy</b> is how the UERC models got from 88M to 7.2M parameters for the edge.<br/>
The attention it draws is the same mechanism I implemented from scratch in <a href="https://github.com/this-AR/neetcode-gpt">neetcode-gpt</a>.
</sub></p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:b8860b,50:e3b341,100:0b0b0f&height=120&section=footer" width="100%" alt=""/>
