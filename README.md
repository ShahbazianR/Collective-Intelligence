# Collective-Intelligence

  
*A lightweight ensemble of GPT-based models for automated CVSS 3.1 scoring*


## Why this repo?

The number of published vulnerabilities rises every week, but the CVSS
base score—essential for triage—can arrive **months** later.  
This project releases **CIVS** (Collective Intelligence for Vulnerability Scoring), a
parameter-free ensemble that fuses GPT-4 with a fine-tuned GPT-3.5-Turbo
to predict the eight CVSS 3.1 metrics directly from a CVE description.



## Features
* **Zero extra parameters** – simple weighted aggregation, no new training.
* **Plug-and-play** – drop in your own OpenAI (or Azure) keys.
* **Robust** – remains stable on GPT-rewritten “what-if” descriptions.
* **Reproducible** – full dataset splits and evaluation scripts included.

---

