<div align="center">

```
╔══════════════════════════════════════════════════════════════════════════════╗
║                                                                              ║
║     I don't just move data.  I make it think.                               ║
║                                                                              ║
╚══════════════════════════════════════════════════════════════════════════════╝
```

</div>

# Sai Kiran Reddy Tallapureddy

**Data Engineer · AI Systems Builder · Agentic Automation**  
`Bangalore, India` · Open to Remote Worldwide · Graduating Jun 2026

---

> I build systems where data flows in raw and emerges as decisions.  
> Not dashboards. Not prototypes. **Production pipelines that scale.**

---

## What I've shipped that actually matters

<table>
<tr>
<td align="center" width="25%">
<h3>10,000+</h3>
transactions/min<br/>processed in real-time
</td>
<td align="center" width="25%">
<h3>90.2%</h3>
fraud detection accuracy<br/>on live Kafka streams
</td>
<td align="center" width="25%">
<h3>40%</h3>
deployment cycle cut<br/>at Broadridge Financial
</td>
<td align="center" width="25%">
<h3>$350</h3>
N8N Hackathon prize<br/>autonomous agent, zero human touch
</td>
</tr>
</table>

---

## How I think about systems

Most people pick tools first. I pick the problem first.

```
Raw Events → What's the truth? → How fast do we need it? → What breaks under load?
     ↓               ↓                    ↓                          ↓
  Kafka          Delta Lake            Spark Streaming           Kubernetes + MLflow
  (ingest)       (immutable log)       (sub-second SLA)          (failover + model serving)
```

That mental model built four production-grade systems before I graduate.

---

## Case Studies

### 01 · Real-Time Fraud Detection Engine

**The problem:** Financial fraud doesn't wait. By the time batch pipelines catch it, money is gone.

**What I built:**

```
[Card Swipe] ──→ Kafka ──→ PySpark Streaming ──→ CatBoost (MLflow-versioned)
                                │                        │
                         Delta Live Tables         [FRAUD FLAG]
                      Bronze → Silver → Gold             │
                                │                  Power BI Alert
                         Audit trail preserved     (< 200ms latency)
```

**Result:** 90%+ accuracy. 10,000+ transactions/minute. Full medallion lineage.  
No batch delay. No data loss. Fraud caught in the same second it happens.

→ [`AI-Powered-Real-Time-Fraud-Detection-System`](https://github.com/saikiranreddy18/AI-Powered-Real-Time-Fraud-Detection-System)

---

### 02 · Autonomous Self-Healing Kubernetes Platform

**The problem:** Kubernetes pods die at 3AM. Engineers shouldn't have to.

**What I built:**

```
Prometheus Metrics ──→ Python Anomaly Engine ──→ Predict failure BEFORE SLO breach
        │                  (trend + threshold)            │
   CPU/Mem/Latency                               Auto: restart · scale · rollback
   Errors/Saturation                                       │
                                                  Slack alert (structured, actionable)
                                                  Human involvement: 0
```

**Result:** The system watches itself. Engineers sleep.

→ [`AI-Powered-Autonomous-Self-Healing-Kubernetes`](https://github.com/saikiranreddy18/AI-Powered-Autonomous-Self-Healing-Kubernetes-Reliability-Platform)

---

### 03 · Multilingual Agricultural Price Forecasting

**The problem:** Indian farmers make crop decisions without knowing next week's prices. The data exists — in Hindi, Telugu, and English, scattered across APIs no one connected.

**What I built:**

```
Twitter + Reddit + Google News (3 languages)
             │
      FinBERT Sentiment Analysis
             │
   CatBoost + APMC market data + OpenMeteo climate signals
             │
     82.57% accuracy on 7-day price forecast
             │
       n8n automation → refreshes continuously without me
```

**Result:** A model that reads the news in three languages and predicts commodity markets.  
Runs itself. Beats generic time-series by a significant margin.

→ [`Capstone-Agri_cat`](https://github.com/saikiranreddy18/Capstone-Agri_cat)

---

### 04 · Supply Chain Demand Forecasting Platform

**The problem:** Overstock and stockout cost retail businesses millions. Both are predictable.

**What I built:** Prophet (seasonality) + XGBoost (gradient signals) + Linear Programming optimizer  
**At scale:** 20,000+ order events per day, region-wise demand aggregation  
**Result:** ~20% reduction in both stock-out and overstock scenarios

→ [`AI-Powered-Supply-Chain-Demand-Forecasting`](https://github.com/saikiranreddy18/AI-Powered-Supply-Chain-Demand-Forecasting-Optimization-Platform)

---

## Stack I trust in production

| Layer | Tools |
|---|---|
| **Streaming & Ingestion** | Kafka · PySpark Streaming · Delta Live Tables |
| **Storage & Lakehouse** | Delta Lake · Databricks · Hadoop · dbt |
| **ML & Experimentation** | MLflow · CatBoost · XGBoost · Prophet · PyTorch · TensorFlow |
| **Agentic & LLM** | LangChain · N8N · RAG · HuggingFace · OpenAI API |
| **Infrastructure** | Kubernetes · Docker · Terraform · AWS · Airflow |
| **Observability** | Prometheus · Grafana · Datadog · Power BI |
| **Languages** | Python · SQL · Scala · Bash |

---

## Experience

**DevOps & Data Infrastructure Intern — Broadridge Financial Solutions**  
`Jun 2025 – Aug 2025`

Broadridge processes $10 trillion in securities annually. I helped make their infrastructure faster.

- Cut deployment cycle time **40%** — CI/CD pipeline redesign with Jenkins + GitOps
- Managed 5+ microservices on Kubernetes, **zero-downtime** across deployments  
- Reduced infra provisioning effort **60%** through Terraform IaC  
- Dropped MTTD **35%** by wiring Grafana + Datadog observability across the stack

---

## Recognition

🥈 **IBM Data-thon — 2nd Place** (Mar 2024) — competed against top engineering teams nationwide, built and presented a large-scale ML pipeline live to IBM judges

🏆 **N8N Agentic Arena Hackathon — $350 Winner** (Sep 2025) — deployed a live multi-step reasoning agent that ran end-to-end without human intervention

---

## What I'm building toward

Learning right now: `LLM Fine-tuning` · `LangGraph multi-agent flows` · `Databricks Unity Catalog` · `State Space Models`

If you're working on systems where:
- Data volume makes manual decisions impossible
- Latency requirements make batch pipelines a liability  
- You need AI that actually does things, not just predicts things

...then we should talk.

---

## Education

**B.Tech — Computer Science & Engineering**  
Lovely Professional University · Aug 2022 – Jun 2026 · CGPA: 7.7

**Certifications:** IBM Big Data · UiPath Automation Developer Associate · GFG DSA

---

<div align="center">

**saikiranreddytallapureddy@gmail.com**  
[LinkedIn](https://www.linkedin.com/in/saikiranreddytallapu/) · [GitHub](https://github.com/saikiranreddy18)

---

*Built systems. Shipped results. Looking for the next hard problem.*

</div>
