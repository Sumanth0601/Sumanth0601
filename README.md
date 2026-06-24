<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1a2e,100:16213e&height=200&section=header&text=T%20Sumanth&fontSize=60&fontColor=58a6ff&fontAlignY=38&desc=Backend%20Engineer%20%7C%20Systems%20%7C%20AI-Native%20Infrastructure&descAlignY=58&descColor=8b949e&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&multiline=false&width=700&lines=Building+systems+that+process+130M%2B+records%2Fday;Distributed+systems+%7C+AI+pipelines+%7C+LLM+infra;FastAPI+%7C+Go+%7C+PostgreSQL+%7C+Snowflake;Turning+data+chaos+into+sub-second+SLAs)](https://git.io/typing-svg)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tsumanth0601)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/SUMANTH0601)
[![AWS Certified](https://img.shields.io/badge/AWS_Certified-Developer_Associate-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)](https://www.credly.com/badges/a9d2704a-526f-4512-ae85-d572a20d9413/public_url)
![Profile Views](https://komarev.com/ghpvc/?username=Sumanth0601&style=for-the-badge&color=58a6ff&label=PROFILE+VIEWS)

</div>

---

## `$ whoami`

```python
class Engineer:
    name        = "T Sumanth"
    location    = "Bangalore, India 🇮🇳"
    role        = "Software Engineer @ Cimpress"
    focus       = ["Distributed Systems", "AI-Native Pipelines", "High-Throughput APIs"]
    daily_load  = "130M+ records processed with 99.9% SLA"
    eliminated  = "$30K/yr SaaS spend by owning pipelines end-to-end"
    certifications = ["AWS Certified Developer – Associate"]

    def current_interests(self):
        return [
            "LLM agent memory architectures",
            "AI fairness & bias evaluation",
            "Adversarial robustness in AI systems",
            "Distributed task orchestration",
        ]
```

---

## `$ cat tech_stack.json`

<div align="center">

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

### Backend & APIs

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6B35?style=for-the-badge&logo=postman&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![Microservices](https://img.shields.io/badge/Microservices-1572B6?style=for-the-badge&logo=kubernetes&logoColor=white)

### Data & AI Infrastructure

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Airflow](https://img.shields.io/badge/Apache_Airflow-017CEE?style=for-the-badge&logo=apache-airflow&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

### AI / ML

![LLM](https://img.shields.io/badge/LLM_Integration-412991?style=for-the-badge&logo=openai&logoColor=white)
![Mem0](https://img.shields.io/badge/Mem0_Agent_Memory-6B2FBF?style=for-the-badge&logoColor=white)
![AI Fairness](https://img.shields.io/badge/AI_Fairness_Metrics-00B4D8?style=for-the-badge&logoColor=white)
![Great Expectations](https://img.shields.io/badge/Great_Expectations-FF6B35?style=for-the-badge&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)

### Cloud & DevOps

![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

</div>

---

## `$ ls -la projects/`

<table>
<tr>
<td width="50%">

### 🔴 GoQueue — Distributed Task Queue

**`Go · PostgreSQL · Docker · Prometheus`**

High-throughput distributed task queue engine built from first principles. Uses PostgreSQL `SKIP LOCKED` for zero double-processing across concurrent workers.

- Goroutine-based worker pool with graceful shutdown
- Priority scheduling + exponential backoff retries
- Dead-letter handling & heartbeat-driven stale job recovery
- Prometheus metrics + REST API for job lifecycle
- **Zero message loss under crash scenarios**

[![Repo](https://img.shields.io/badge/View_Repo-0d1117?style=for-the-badge&logo=github)](https://github.com/Sumanth0601/GoQueue)

</td>
<td width="50%">

### 🔵 mem0-shield — AI Agent Memory Defense

**`Python · Mem0 · LLM Security · Adversarial ML`**

Defense layer for AI agents using long-term memory. Detects and neutralizes adversarial prompt injection attempts that try to **corrupt or hijack agent memory**.

- Adversarial input classification pipeline
- Memory poisoning pattern detection
- Sanitization layer before Mem0 writes
- Plug-and-play wrapper around Mem0 SDK

[![Repo](https://img.shields.io/badge/View_Repo-0d1117?style=for-the-badge&logo=github)](https://github.com/Sumanth0601/mem0-shield)

</td>
</tr>
<tr>
<td width="50%">

### 🟢 AI Bias Report Card

**`Python · Fairness Metrics · ML · Web`**

End-to-end AI fairness auditing tool. Computes demographic parity, equalized odds, and disparate impact across protected groups — outputs a shareable, human-readable Report Card.

- Multi-metric fairness evaluation engine
- Demographic slicing & intersectional analysis
- Exportable HTML/PDF report generation
- Built for responsible AI deployment workflows

[![Repo](https://img.shields.io/badge/View_Repo-0d1117?style=for-the-badge&logo=github)](https://github.com/Sumanth0601/AI-bias-reportcard)

</td>
<td width="50%">

### 🟡 Don't Wait — Async Intelligence Layer

**`Python · Async Processing · Distributed Queues`**

Intelligent async task orchestration system. Eliminates blocking waits in data-intensive workflows through smart queuing and parallel execution strategies.

- Event-driven architecture with backpressure handling
- Configurable concurrency limits per task type
- Dead-zone detection & automatic retry logic
- Production-grade observability hooks

[![Repo](https://img.shields.io/badge/View_Repo-0d1117?style=for-the-badge&logo=github)](https://github.com/Sumanth0601/Don-t-Wait)

</td>
</tr>
</table>

---

## `$ git stats --global`

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Sumanth0601&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sumanth0601&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&langs_count=8"/>

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=Sumanth0601&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=58a6ff&ring=58a6ff&fire=ff6b35&currStreakLabel=58a6ff&sideNums=8b949e&currStreakNum=ffffff&dates=8b949e&sideLabels=8b949e)](https://git.io/streak-stats)

</div>

---

## `$ leetcode --stats Sumanth0601`

<div align="center">

[![LeetCode Stats](https://leetcard.jacoblin.cool/Sumanth0601?theme=dark&font=JetBrains%20Mono&ext=heatmap&hide_border=true&border=0d1117&background=0d1117)](https://leetcode.com/u/Sumanth0601/)

[![LeetCode](https://img.shields.io/badge/LeetCode-Sumanth0601-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Sumanth0601/)
![Rank](https://img.shields.io/badge/Global_Rank-Top_26%25-brightgreen?style=for-the-badge&logo=leetcode&logoColor=white)
![Rating](https://img.shields.io/badge/Contest_Rating-1584-orange?style=for-the-badge&logo=leetcode&logoColor=white)

</div>

---

## `$ grep -r "currently_building" .`

```yaml
active_projects:
  - name: "AI-native data pipelines at scale"
    status: "production"
    throughput: "130M+ records/day"

  - name: "LLM agent memory safety research"
    status: "active"
    focus: "adversarial robustness for persistent AI agents"

  - name: "AI fairness tooling for production ML"
    status: "active"
    goal: "democratize bias audits for deployed models"

open_to:
  - "Distributed systems deep dives"
  - "LLM infrastructure & agent orchestration"
  - "High-throughput data engineering challenges"
  - "AI safety & alignment engineering"
```

---

<div align="center">

### `> Let's build something that scales.`

[![Email](https://img.shields.io/badge/sumanth2031@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sumanth2031@gmail.com)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/tsumanth0601)
[![Twitter](https://img.shields.io/badge/Follow_on_Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/SUMANTH0601)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:16213e,50:1a1a2e,100:0d1117&height=100&section=footer" width="100%"/>

</div>
