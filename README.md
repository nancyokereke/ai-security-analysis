# Prompt Injection Threat Analysis — Cova Funds

**Analyst:** Nancy Okereke | Cybersecurity Analyst  
**Date:** February 2026  
**Category:** AI Security | Threat Analysis  
**Testing Environment:** Gandalf by Lakera

---

## Project Overview

This project documents a prompt injection threat analysis conducted for Cova Funds, a fictional African fintech company. The assessment identifies how prompt injection attacks could be weaponised against Cova Funds' AI-powered systems, evaluates the risk of each scenario, and recommends controls to mitigate the threat.

---

## AI Systems Assessed

- Customer service chatbot
- Fraud detection system
- Loan decisioning tool

---

## Analyst Observations

Prompt injection techniques were tested hands-on using Gandalf by Lakera, a purpose-built AI security challenge environment. Key findings:

- **Hypothetical framing** successfully bypassed AI instruction filters at lower defence levels
- **Code-based obfuscation** circumvented keyword-based detection mechanisms
- At higher defence levels, semantic filtering replaced keyword blocking — evaluating intent rather than specific words
- Direct instruction override was ineffective against hardened system prompts
- Overall assessment: prompt injection requires low technical skill against inadequately defended systems

---

## Risk Assessment Summary

| Scenario | Likelihood | Impact | Risk Score | Priority |
|----------|-----------|--------|------------|----------|
| Chatbot manipulation | 3 | 3 | 9 | Critical |
| Fraud detection bypass | 2 | 3 | 6 | High |
| Loan decisioning manipulation | 2 | 3 | 6 | High |

---

## Deliverables

- Prompt Injection Threat Analysis Report (docx)

---

## Skills Demonstrated

- AI security threat analysis and attack scenario modelling
- Hands-on prompt injection testing in a controlled environment
- Risk scoring and prioritisation
- Security report writing for executive and technical audiences
- Preventive, detective, and corrective control design

---

## Frameworks and References

- OWASP Top 10 for LLMs (LLM01: Prompt Injection)
- NIST AI Risk Management Framework (AI RMF)
- Nigeria Data Protection Act (NDPA) 2023 / NDPC
- Central Bank of Nigeria (CBN) Guidelines
