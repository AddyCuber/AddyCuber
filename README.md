# Hi, I'm Aditya Ray.

AI engineer, recent graduate (B.Tech in AI & Data Science). I don't just train models; I build complete systems around them.

My approach is simple: I use competitive environments (hackathons) to stress-test new architectures, and I use micro-SaaS deployments to study how those architectures handle the chaos of the real world.

I am currently moving beyond standard RAG/Chatbot patterns to explore **Compound AI Systems**: how to make multi-agent pipelines efficient, explainable, and cheap enough to run autonomously. Right now I'm also learning **evals and inference**.

---

### Rapid Engineering (Hackathons)
*I treat 24-hour builds as feasibility studies for complex system designs.*

**AURA Diagnostics** (Global Digital Health Hackathon)
> **The Stack:** Multi-agent orchestration, Vector Search (biomedical data), Audit Logging.
> **The Challenge:** Building a clinical decision support system that doesn't just "guess" but traces every output back to a source (PubMed/OpenFDA).
> **The Build:** A traceable reasoning pipeline, built under extreme time pressure.

**Placement Platform @ Echelon** (NMIMS Flagship Hackathon)
> **Result:** **Winner** (Problem Statement Track) | **3rd Place** (Overall)
> **The Build:** A high-throughput resume parsing and matching engine.
> **Technical Focus:** Designed the backend logic for extracting structured skills from unstructured PDFs and mapping them to job descriptions with high precision.

**Grand India Challenge** (2nd Place Overall)
> **The Build:** Real-time e-commerce price aggregator.
> **The Reality:** The hard part wasn't the AI; it was the data engineering. I built robust pipelines to normalize and rank noisy data from multiple scraping sources in real-time.

---

### Production Systems & Experiments
*Building startups to learn DevOps.*

**Epochsee** (Live Micro-SaaS)
> **Status:** Running in production.
> **What it is:** An autonomous pipeline that scrapes, filters, and verifies startup hiring signals for students.
> **Why I built it:** I wanted to study **Long-Running Systems**. It allows me to observe concept drift, automation failures, and the cost/latency tradeoffs of LLM pipelines over weeks, not just minutes.

**Faceless Shorts Pipeline** (Automation Experiment)
> **What it is:** An attempt to automate YouTube Shorts end to end. Pre-written stories go in; voiceover (Edge TTS), B-roll (Pexels), editing (FFmpeg) and upload run automatically on a GitHub Actions schedule.
> **Stack:** Python, Edge TTS, Pexels API, FFmpeg, YouTube Data API, Instagram Graph API, GitHub Actions.
> **What I learned:** The hard parts were OAuth token refresh for unattended runs and keeping the pipeline from republishing stories, not the video editing.

**RailCompute** (Stopped)
> **What it was:** A platform that automated fine-tuning end to end: describe what the model should learn, approve a plan, and the system handles data prep, training, evals, and packaging the model with a usage guide. 
> **My role:** I owned the backend. Agent workflows and infrastructure architecture.

**To Be Deployed (TBD)** (Closed Initiative)
> **Context:** An MSME-registered startup attempt mentored by VCs.
> **Outcome:** We shut it down.
> **Why:** The engineering scope outgrew the value proposition. It taught me the most important lesson in AI: **Constraint**. I now prioritize shipping narrow, reliable tools over broad, undefined platforms.

---

### Past Research Interest: The "Translation Tax"
*Paused. I explored this earlier and am not actively working on it.*

When we chain models together (e.g., GPT-4 to Claude), we force them to communicate in English. This is slow, lossy, and expensive.

The idea I looked at was **Latent Space Alignment** (Model Stitching): training lightweight "bridge" layers to translate one model's internal vector representations (like Llama 3) into the input space of another (like Mistral), so agents could communicate via dense vectors instead of tokens.

---

[Email](mailto:rayaditya03@gmail.com) | [LinkedIn](https://www.linkedin.com/in/aditya-ray-03ar/) | [X](https://x.com/Aditya_Ray_03)
