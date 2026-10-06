# Case Study 01 — Reducing UPI Payment Failures

### Product Management Case Study

🔗 **Live Case Study:**  
https://praah18.github.io/case01_paymentFailures/
---

## 📌 Overview

A Product Management case study focused on reducing the negative impact of UPI payment failures and improving customer trust during failed, pending, or uncertain transactions.

The case explores how a payment product can move beyond a simple **"Payment Failed"** message and provide customers with clear information, safe recovery options, while giving internal teams visibility into larger payment incidents.

---

## 💡 Proposed Solution

### Payment Health & Recovery Engine

A system designed to:

**Detect → Classify → Inform → Monitor → Recover → Alert → Learn**

The solution:

- Detects and classifies payment failures
- Provides contextual notifications to customers
- Prevents unsafe retries and duplicate payments
- Checks the status of uncertain transactions
- Alerts internal teams when failure rates spike
- Tracks affected customers and transactions
- Creates a feedback loop for engineering teams

The central product principle is:

> **"Don't just fix the failure. Fix the customer's experience of the failure."**

---

## 🎯 Key Product Decisions

- Focus on **recovery and customer experience**, not only reducing technical failures
- Never allow an **UNKNOWN** transaction to be blindly retried
- Use **First-Attempt Payment Success Rate** as the North Star Metric
- Monitor fraud, duplicate payments and latency as guardrails
- Start with a focused MVP before expanding into advanced routing and preventive features

---

## 📊 Case Study Covers

- Problem Definition
- Customer & Business Impact
- Root Cause Analysis
- Customer Journey
- Solutions Considered
- Product Strategy
- Payment Health & Recovery Engine
- Internal Incident Alerting
- Transaction Recovery
- PRD
- Metrics & Guardrails
- Experiment Design
- 12-Week Execution Roadmap
- Product Trade-offs
- Interview Q&A

---

## 📄 Case Study

**[View the full interactive case study →](https://silver-capybara-699rqrw4qxpp3rgxw-8000.app.github.dev/)**

---

## ⚠️ Data Disclaimer

UPI transaction-volume figures used in the case study are based on published NPCI data.

Failure rates, incident numbers, dashboards and improvement targets are **hypothetical illustrations** and are not Google internal data. :contentReference[oaicite:1]{index=1}

---

## 🛠️ Created As

A Product Management portfolio project demonstrating:

- Product thinking
- Problem decomposition
- User-centric design
- Product strategy
- PRD writing
- Metrics & experimentation
- Prioritization
- Execution planning
