# things-i-automated ⚙️
> Small tools for boring problems.

This repository hosts the automation scripts, webhooks, and backend data checks I built to cut down manual overhead. No bloated frameworks—just functional Python code designed to handle heavy lifting, clean up noisy data, and keep external systems perfectly synced.

---

## 🛠️ The Automation Matrix

### 01 | B2B Lead Research & Sync Engine
* **The Problem:** Raw lead data is universally messy, full of duplicates, and takes hours to manually scrub before it's ready for sales outreach.
* **The Fix:** A Python utility that ingests dirty lead lists, runs structured data validation checks, strips out duplicates based on flexible matching logic, and passes the clean data directly to the CRM via REST APIs.
* **Tech Stack:** `Python`, `REST APIs`, `JSON`, `CRM Webhooks`

### 02 | Meeting Intelligence Parser
* **The Problem:** Transcripts are long, chaotic, and require manual reading to pull out actual action items and client pain points.
* **The Fix:** A lightweight text processor that extracts structured data directly from raw transcripts, outputting 6 specific categories (from instant action points to clean, CRM-ready stakeholder briefs).
* **Tech Stack:** `Python`, `Structured Data Parsing`, `JSON`

### 03 | AI Output Evaluation Sandbox
* **The Problem:** Measuring LLM performance across hundreds of prompts is impossible to track manually without a systematic setup.
* **The Fix:** A programmatic testing harness built to batch-evaluate outputs against 4 core product guardrails: Accuracy, Relevance, Consistency, and Usability. It flags edge-case failures automatically so they can be fixed before shipment.
* **Tech Stack:** `Python`, `LLM Apps Frameworks`, `Data Validation`

---

## 🚀 Quick Setup & Local Execution

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd things-i-automated
   ```

2. **Set up your environment:**
   Create a `.env` file in the root directory to store your local configuration and system webhooks safely:
   ```env
   CRM_API_KEY=your_secure_api_key_here
   WEBHOOK_URL=your_webhook_endpoint_here
   ```

3. **Install basic dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

---

## 📈 Impact Blueprint
These tools were built to eliminate the bottleneck between raw workflows and clean product execution. By shifting repetitive operational tasks over to code, they cut manual effort down by **~75-80%** on core processes.
