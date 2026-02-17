<!-- ============================================================ -->
<!--  Krish Nagaral · v3 · Zero broken images                    -->
<!--  Only external APIs + pure markdown. Everything renders.     -->
<!-- ============================================================ -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=180&section=header&text=Krish%20Nagaral&fontColor=e6edf3&fontSize=44&fontAlignY=32&desc=AI%20Systems%20Engineer&descColor=58A6FF&descSize=16&descAlignY=52&animation=fadeIn" width="100%"/>
</p>

<p align="center">
  <a href="https://github.com/Blanq-one">
    <img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&size=15&duration=3000&pause=1500&color=58A6FF&center=true&vCenter=true&width=700&height=25&lines=Computer+Vision+%C2%B7+RAG+Architectures+%C2%B7+LLM+Systems+%C2%B7+Predictive+Intelligence;MS+CS+%40+Northeastern+%C2%B7+3%C3%97+AWS+Certified+%C2%B7+Published+ML+Researcher;Building+intelligent+systems+that+reason%2C+retrieve%2C+and+respond" />
  </a>
</p>

<br/>

---

<br/>

## ◈ Systems I've Built

<br/>

<table>
<tr>
<td width="50%" valign="top">

### LegalLens AI
Retrieval-augmented legal reasoning platform. Semantic chunking over case law corpora with hybrid vector search, re-ranking pipelines, and structured inference via LLM orchestration.

`Python` `LangChain` `FAISS` `FastAPI` `Transformers`

</td>
<td width="50%" valign="top">

### [Pneumonia Detection System](https://github.com/Blanq-one/Pneumonia_Detection_AI)
Medical imaging pipeline achieving **91.5% accuracy** on chest X-ray classification. ResNet-50 backbone with Grad-CAM explainability for clinical interpretability.

`PyTorch` `ResNet-50` `Grad-CAM` `Medical Imaging`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Facial Emotion Recognition](https://github.com/Blanq-one/Facial-emotion-recognition)
Multimodal emotion classification fusing facial, speech, and text inputs to capture verbal and non-verbal cues. Applications in HCI, healthcare, and education.

`Computer Vision` `NLP` `Multimodal Fusion` `Deep Learning`

</td>
<td width="50%" valign="top">

### [Blind Vision AI](https://github.com/Blanq-one/Blind-Vision-AI-Powered-Object-Face-Detection)
Accessibility-first object detection for visually impaired users. Real-time scene understanding with speech feedback — converting visual input into navigable audio cues.

`Object Detection` `Speech Synthesis` `Computer Vision` `Accessibility`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Fake News Detection](https://github.com/Blanq-one/Fake-News-Detection-Analysis)
NLP framework for digital misinformation identification. Multi-layer LSTM with Word Embeddings and NLTK-driven preprocessing over 50+ training epochs.

`LSTM` `Word Embeddings` `NLTK` `NLP`

</td>
<td width="50%" valign="top">

### [CaptionCraft AI](https://github.com/Blanq-one/CaptionCraft-AI-Image-Caption-Generator)
Image-to-text generation using CNN + LSTM on Flickr8k. VGG16 encoder with sequential LSTM decoder, evaluated via BLEU scoring.

`VGG16` `LSTM` `Image Captioning` `Seq2Seq`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Credit Risk Scoring Engine](https://github.com/Blanq-one/Credit-Risk-Scoring-System)
ML system predicting loan default risk using XGBoost with SHAP explainability and fairness auditing. Flask API for real-time scoring.

`XGBoost` `SHAP` `Flask` `Fairness Auditing`

</td>
<td width="50%" valign="top">

### JARVIS Voice Assistant
Multimodal AI assistant integrating speech recognition, LLM reasoning, and tool-use. Real-time voice interaction with contextual memory and task execution.

`Python` `LLMs` `Speech Recognition` `Tool Use`

</td>
</tr>
</table>

<br/>

---

<br/>

## ◈ Architecture Thinking

<br/>

```
                    ┌─────────────────────────────────────────────────────────────────┐
                    │              RETRIEVAL-AUGMENTED GENERATION PIPELINE             │
                    └─────────────────────────────────────────────────────────────────┘

    ┌──────────────┐       ┌──────────────┐       ┌──────────────┐       ┌──────────────┐
    │              │       │              │       │              │       │              │
    │  User Query  │──────▶│  Embedding   │──────▶│ Vector Store │──────▶│  Retriever   │
    │              │       │    Model     │       │ FAISS/Pinecone│      │  Top-K Sim   │
    └──────────────┘       └──────────────┘       └──────────────┘       └──────┬───────┘
                                                                                │
    ┌──────────────┐       ┌──────────────┐                                     │
    │              │       │     LLM      │◀────────────────────────────────────┘
    │  Structured  │◀──────│  Reasoning   │       context injection
    │   Response   │       │   Layer      │       + re-ranking
    └──────────────┘       └──────────────┘

    ┌──────────────┐
    │  Doc Corpus  │─ ─ ─ ─ ─ ─ ─ ─ ▶  chunking + embedding at ingest time
    │ Legal/Medical│
    └──────────────┘
```

<br/>

---

<br/>

## ◈ Domain Focus

<br/>

<table>
<tr>
<td>

```
 Computer Vision & Medical Imaging    ████████████████████████████████████░░░  92%
 Retrieval-Augmented Generation       ██████████████████████████████░░░░░░░░░  78%
 NLP & Language Models                ████████████████████████████░░░░░░░░░░░  72%
 Predictive Modeling & Risk           ██████████████████████████░░░░░░░░░░░░░  68%
 Cloud & MLOps (3× AWS Certified)     ████████████████████████░░░░░░░░░░░░░░░  62%
```

</td>
</tr>
</table>

<br/>

---

<br/>

## ◈ Technical Stack

<br/>

<p align="center">
  <img src="https://img.shields.io/badge/Python-0d1117?style=for-the-badge&logo=python&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/TypeScript-0d1117?style=for-the-badge&logo=typescript&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/SQL-0d1117?style=for-the-badge&logo=postgresql&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/C++-0d1117?style=for-the-badge&logo=cplusplus&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/Java-0d1117?style=for-the-badge&logo=openjdk&logoColor=58A6FF" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyTorch-0d1117?style=for-the-badge&logo=pytorch&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/TensorFlow-0d1117?style=for-the-badge&logo=tensorflow&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/HuggingFace-0d1117?style=for-the-badge&logo=huggingface&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/LangChain-0d1117?style=for-the-badge&logo=chainlink&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/Scikit--learn-0d1117?style=for-the-badge&logo=scikitlearn&logoColor=58A6FF" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/AWS-0d1117?style=for-the-badge&logo=amazonaws&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/Docker-0d1117?style=for-the-badge&logo=docker&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/FastAPI-0d1117?style=for-the-badge&logo=fastapi&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/MySQL-0d1117?style=for-the-badge&logo=mysql&logoColor=58A6FF" />
  <img src="https://img.shields.io/badge/Git-0d1117?style=for-the-badge&logo=git&logoColor=58A6FF" />
</p>

<br/>

---

<br/>

## ◈ Currently

```
→  Building LegalLens AI — semantic case analysis at scale
→  Exploring multimodal emotion recognition architectures
→  Studying mechanistic interpretability & sparse autoencoders
→  Open to Summer 2026 AI/ML engineering opportunities
```

<br/>

---

<br/>

## ◈ Research

> 📄 Published work in **machine learning algorithms**, **quantum cryptography**, and **heart attack prediction modeling**. Focused on applied ML for healthcare and security domains.

<br/>

---

<br/>

<p align="center">
  <a href="https://github.com/Blanq-one">
    <img src="https://img.shields.io/badge/GitHub-0d1117?style=for-the-badge&logo=github&logoColor=e6edf3" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/krish-nagaral-7b9188238/">
    <img src="https://img.shields.io/badge/LinkedIn-0d1117?style=for-the-badge&logo=linkedin&logoColor=58A6FF" />
  </a>
  &nbsp;
  <a href="mailto:nagaralkrish@gmail.com">
    <img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=58A6FF" />
  </a>
</p>

<br/>

<p align="center">
  <sub>designed to reason · built to deploy</sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=100&section=footer" width="100%"/>
</p>
