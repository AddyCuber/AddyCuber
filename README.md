# Hi, I'm Aditya Ray.

I am a final year AI engineer. I don't just train models; I build complete systems around them.

My approach is simple: I use competitive environments (hackathons) to stress-test new architectures, and I use micro-SaaS deployments to study how those architectures handle the chaos of the real world.

I am currently moving beyond standard RAG/Chatbot patterns to explore **Compound AI Systems**—specifically, how to make multi-agent pipelines efficient, explainable, and cheap enough to run autonomously.

---

### Rapid Engineering (Hackathons)
*I treat 24-hour builds as feasibility studies for complex system designs.*

**AURA Diagnostics** (Global Digital Health Hackathon)
> **The Stack:** Multi-agent orchestration, Vector Search (biomedical data), Audit Logging.
> **The Challenge:** Building a clinical decision support system that doesn't just "guess" but traces every output back to a source (PubMed/OpenFDA).
> **The Win:** Engineered a traceable reasoning pipeline under extreme time pressure.

**Placement Platform @ Echelon** (NMIMS Flagship Hackathon)
> **Result:** **Winner** (Problem Statement Track) | **3rd Place** (Overall)
> **The Build:** A high-throughput resume parsing and matching engine.
> **Technical Focus:** Designed the backend logic for extracting structured skills from unstructured PDFs and mapping them to job descriptions with high precision.

**Grand India Challenge** (2nd Place Overall)
> **The Build:** Real-time e-commerce price aggregator.
> **The Reality:** The hard part wasn't the AI; it was the data engineering. I built robust pipelines to normalize and rank noisy data from multiple scraping sources in real-time.

---

### Production Systems & Experiments
*Building Startups to learn DevOps.*

**Epochsee** (Live Micro-SaaS)
> **Status:** Running in production.
> **What it is:** An autonomous pipeline that scrapes, filters, and verifies startup hiring signals for students.
> **Why I built it:** I wanted to study **Long-Running Systems**. It allows me to observe concept drift, automation failures, and the cost/latency tradeoffs of LLM pipelines over weeks, not just minutes.

**To Be Deployed (TBD)** (Closed Initiative)
> **Context:** An MSME-registered startup attempt mentored by VCs.
> **Outcome:** I shut it down.
> **Why:** The engineering scope outgrew the value proposition. It taught me the most important lesson in AI: **Constraint**. I now prioritize shipping narrow, reliable tools over broad, undefined platforms.

---

### Research Interest: The "Translation Tax"
Currently, when we chain models together (e.g., GPT-4 → Claude), we force them to communicate in English. This is slow, lossy, and expensive.

I am researching **Latent Space Alignment** (Model Stitching).

**The Hypothesis:** We can train lightweight "bridge" layers to translate the internal vector representations of one model (like Llama 3) directly into the input space of another (like Mistral). This would allow agents to communicate via dense vectors, removing the bottleneck of token generation.

---

[Email](mailto:rayaditya03@gmail.com) | [LinkedIn](https://www.linkedin.com/in/aditya-ray-03ar/) 
