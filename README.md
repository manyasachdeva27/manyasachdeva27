<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,40:302b63,100:24243e&height=220&section=header&text=Manya%20Sachdeva&fontSize=58&fontColor=ffffff&fontAlignY=40&desc=I%20build%20AI%20that%20actually%20works.&descAlignY=62&descSize=20&animation=fadeIn" width="100%"/>
</div>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=A78BFA&center=true&vCenter=true&width=750&lines=RAG+Pipelines+that+score+0.91+Faithfulness+%F0%9F%A7%A0;ML+models+with+%7E7.8%25+MAPE+on+real+financial+data+%F0%9F%92%B9;NLP+research+on+Hinglish+profanity+%26+code-switching+%F0%9F%94%AC;Ranked+33+out+of+600%2B+teams+at+a+national+hackathon+%E2%9A%A1;Always+building%2C+always+shipping+%F0%9F%9A%80)](https://git.io/typing-svg)

<br/>

[![Gmail](https://img.shields.io/badge/Gmail-sachdevamanya92%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sachdevamanya92@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Manya_Sachdeva-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/manyasachdeva27)
[![GitHub](https://img.shields.io/badge/GitHub-manyasachdeva27-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/manyasachdeva27)
![Profile Views](https://komarev.com/ghpvc/?username=manyasachdeva27&color=a78bfa&style=for-the-badge&label=Profile+Views)

</div>

---

## 🧬 Who am I?

```python
class Manya(AIEngineer):

    def __init__(self):
        self.name        = "Manya Sachdeva"
        self.university  = "Bennett University, Greater Noida"
        self.degree      = "B.Tech Computer Science & Engineering"
    

    @property
    def superpower(self):
        return "Turning messy real-world data into AI that actually ships"

    def tech_i_love(self):
        return {
            "AI/ML"   : ["RAG Pipelines", "NLP", "LLMs", "Prompt Engineering"],
            "ML Eng"  : ["XGBoost", "Prophet", "Isolation Forest", "BERT"],
            "Backend" : ["FastAPI", "LangChain", "FAISS", "Docker"],
            "UI"      : ["Streamlit"],
            "Research": ["Supply Chain AI", "Hinglish NLP", "Code-Mixed Text"]
        }

    def currently(self):
        return [
            "🔬 Wrapping up 2 research papers",
            "🤖 Expanding Nova with multi-agent capabilities",
            "📚 Deep-diving into Agentic AI & LLM fine-tuning",
            "🎯 Hunting for summer internships & research collabs"
        ]
```

---

## 🚀 Projects That Actually Ship

<table>
<tr>
<td width="50%" valign="top">

### 🔬 Nova — AI Research Assistant
> *"What if you had a PhD-level research buddy available 24/7?"*

Nova ingests PDFs & URLs, semantically chunks them, retrieves the most relevant context using FAISS, and generates **cited answers** powered by **Llama-3.3-70b via Groq** — blazing fast.

**What makes it special:**
- 🧠 ArXiv integration for live academic paper discovery
- 📊 RAGAS-evaluated with LangSmith tracing
- 🔗 Multi-source retrieval — not just one doc at a time

**Stack:** `LangChain` `FAISS` `Cohere` `Groq` `Ragas` `LangSmith`

```
Faithfulness     ████████████████████ 0.91
Answer Relevancy █████████████████████ 0.94
```

[![Repo](https://img.shields.io/badge/View_Repo-Nova-a78bfa?style=flat-square&logo=github)](https://github.com/manyasachdeva27/Nova-AI-Research-Assistant)

</td>
<td width="50%" valign="top">

### 💰 Finsage — AI Financial Assistant
> *"Your bank statement has stories. Finsage reads them."*

Built on **4,000+ real transactions**, Finsage forecasts your income and expenses, spots anomalies before they hurt you, and lets you chat with your own financial data in real time.

**What makes it special:**
- 📈 XGBoost + Prophet ensemble with walk-forward CV
- 🚨 Isolation Forest for anomaly detection
- 💬 Gemini-powered chatbot for natural language finance queries

**Stack:** `XGBoost` `Prophet` `Gemini API` `Streamlit` `Isolation Forest`

```
MAPE (walk-forward CV)  ████████████████ ~7.8%
Transactions analyzed   ████████████████ 4,000+
```

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🛡️ Insurance Risk Predictor
> *"Risk assessment in milliseconds, not weeks."*

A production-ready **Random Forest** model wrapped in a FastAPI REST endpoint that returns risk category (high/medium/low) **with confidence scores** — deployed and callable in real time.

**What makes it special:**
- ⚡ Sub-second API response time
- 🎯 Class probability scores, not just labels
- 🖥️ Streamlit UI for non-technical users

**Stack:** `FastAPI` `Scikit-learn` `Random Forest` `Streamlit`

[![Repo](https://img.shields.io/badge/View_Repo-Insurance_Predictor-a78bfa?style=flat-square&logo=github)](https://github.com/manyasachdeva27/Insurance-Premium-Prediction)

</td>
<td width="50%" valign="top">

### 📺 YouTube RAG Chatbot
> *"Watch less. Know more."*

A RAG pipeline that ingests YouTube video transcripts and lets you have a **full conversation** about the video content — no scrubbing through hours of footage.

**What makes it special:**
- 🎬 Transcript-to-knowledge pipeline
- 🔍 Semantic search over video content
- 💬 Conversational memory across turns

**Stack:** `LangChain` `FAISS` `Python`

[![Repo](https://img.shields.io/badge/View_Repo-YouTube_Chatbot-a78bfa?style=flat-square&logo=github)](https://github.com/manyasachdeva27/Youtube-chatbot-using-rag-pipeline-in-langchain)

</td>
</tr>
</table>

---

## 🔬 Research in Progress

### 📦 Demand Forecasting in Supply Chain AI
> Sustainable inventory management meets machine learning

Developing an **ML-integrated cross-docking model** that forecasts 12-week retail demand across multiple products and retailers — then embeds those forecasts into an **EOQ optimization framework** with real-world constraints:
- ♻️ **Carbon cap-and-trade** penalties
- 🏭 Imperfect quality handling
- 📉 ~14% MAPE with time-series cross-validation

`XGBoost` `Gradient Boosting` `EOQ` `Carbon Modeling` `Python`

---

### 🗣️ Hinglish Profanity Detection
> NLP in the wild — where language gets messy

Analyzed linguistic patterns of profanity in **Hindi-English code-mixed** social media text — one of the hardest NLP problems because the language itself is constantly shape-shifting.

Challenges tackled:
- 🔀 **Code-switching** — mid-sentence language flips
- 🔡 **Transliteration noise** — same word, infinite spellings
- 🙈 **Obfuscation** — intentional masking to evade detection

Proposed pipeline: Text Normalization → Fuzzy Matching → **BERT contextual embeddings**

`BERT` `NLP` `Fuzzy Matching` `TRAC` `HASOC` `HOT datasets`

---

## 💼 Experience

### Centilytics — Business Analyst Intern *(Jun 2025 – Mar 2026)*

- 📋 Led **end-to-end PRD development** for *Travel Dil Se* — from client requirement gathering all the way to roadmap recommendations
- 🔍 Benchmarked **9+ CRM and cloud platforms** — documented comparative insights in Zoho to streamline vendor selection
- 🗺️ Drove feature gap analysis and feature prioritization for a live product

---

## 🛠️ Full Tech Arsenal

<div align="center">

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML/CSS](https://img.shields.io/badge/HTML%2FCSS-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**AI / ML**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-AA4A44?style=for-the-badge&logoColor=white)

**Frameworks & Tools**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

</div>

---

## 📊 GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=manyasachdeva27&show_icons=true&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=a78bfa&text_color=c9d1d9&include_all_commits=true&count_private=true" height="170"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=manyasachdeva27&layout=compact&theme=midnight-purple&hide_border=true&bg_color=0d1117&title_color=a78bfa&text_color=c9d1d9&langs_count=6" height="170"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=manyasachdeva27&theme=midnight-purple&hide_border=true&background=0d1117&stroke=a78bfa&ring=a78bfa&fire=ff6b6b&currStreakLabel=a78bfa" width="65%"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=manyasachdeva27&bg_color=0d1117&color=a78bfa&line=a78bfa&point=ffffff&area=true&hide_border=true" width="95%"/>
</div>

---

## 🏆 Achievements & Certifications

<div align="center">

| 🏅 | Achievement |
|---|---|
| ⚡ | **Rank 33 / 600+ teams** — Smart BU Hackathon, Bennett University |
| 🌟 | **Dean's List** — 10/10 SGPA, Bennett University |
| 🤖 | **IBM Certified** — RAG and Agentic AI |
| 🗄️ | **IBM Certified** — Databases & SQL for Data Science with Python |
| 📊 | **Certified** — Text Mining & Analytics |

</div>

---

## 🎭 Positions of Responsibility

> Because building AI isn't the only thing I do

- 🏛️ **Deputy Minister of Alumni Relations** — SCSET Student Cabinet
- 📣 **Sub-Head, PR & Outreach** — CodeChef BU Chapter  
- 🎯 **Member** — Career Advancement Committee, SCSET
- 📢 **Core Member, Internal Communications** — SCSET Student Cabinet

---

## 💬 Let's Talk

<div align="center">

I'm always open to:
**Internship opportunities** · **Research collaborations** · **AI project discussions** · **Just geeking out about LLMs**

[![Email Me](https://img.shields.io/badge/📧_Email_Me-sachdevamanya92%40gmail.com-D14836?style=for-the-badge)](mailto:sachdevamanya92@gmail.com)
[![Connect on LinkedIn](https://img.shields.io/badge/🤝_Connect_on_LinkedIn-Manya_Sachdeva-0077B5?style=for-the-badge)](https://linkedin.com/in/manyasachdeva27)

*"The best AI is the one that ships."*

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=130&section=footer" width="100%"/>
</div>
