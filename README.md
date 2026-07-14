<div align="center">

# 🛰️ Splunk SIEM Log Analysis
### DNS & HTTP Triage Guides

*Hands-on Splunk workflows built around free sample datasets — practice real SOC triage, not just theory.*

![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![SIEM](https://img.shields.io/badge/SIEM-Blue%20Team-blue?style=for-the-badge)
![Level](https://img.shields.io/badge/Level-Beginner--Friendly-brightgreen?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

</div>

---

## 🧭 Overview

A pair of hands-on guides for practicing log analysis triage in Splunk, built around freely available sample datasets. Each guide walks through getting sample data into Splunk, then working it with a repeatable triage approach:

<div align="center">

**`Baseline`** → **`Narrow`** → **`Attribute`** → **`Validate`**

</div>

Start broad, zero in on what's high-volume or unusual, trace it back to a source, then confirm against raw events before drawing conclusions.

---

## 📂 Contents

| # | Guide | Focus |
|---|-------|-------|
| 🌐 01 | [**DNS Log Analysis**](./Project1-DNS-Log-Analysis-Splunk.md) | Triaging DNS query logs to spot DNS tunneling, DGA activity, and abuse of legacy protocols (WPAD / ISATAP) |
| 🖥️ 02 | [**HTTP Log Analysis**](./Project3-HTTP-Log-Analysis-Splunk.md) | Triaging web server access logs to identify scanning behavior, brute-force attempts, and abnormal endpoint targeting |

---

## 🎯 What You'll Practice

- 📥 Ingesting sample log data into Splunk
- 🔎 Writing SPL queries for baselining and anomaly detection
- 📊 Pivoting from summary stats to source attribution
- ✅ Validating findings against raw events before calling anything malicious

---

## 👤 Who This Is For

Anyone building practical SIEM skills for a **SOC Analyst** path. These guides are designed as a **repeatable workflow** — swap in different sample datasets and run the same triage funnel again to build muscle memory, not just a one-time walkthrough.

---

<div align="center">

*Happy hunting 🕵️*

</div>
