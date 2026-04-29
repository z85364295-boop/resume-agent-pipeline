# 🚀 Resume-Agent-Pipeline

A Multi-Agent System focused on "Cross-Industry Career Transition" resume reconstruction and alignment.

## 💡 Core Pain Point Resolved
Solves the low conversion rate for zero-experience candidates transitioning to new industries (e.g., traditional roles to livestream e-commerce). Eliminates the bottleneck of high-cost, inefficient manual resume rewriting by enforcing strict industry-specific logic mapping.

## ⚙️ Architecture (Multi-Agent Workflow)
The system employs a 3-layer asynchronous Agent pipeline:

1. **Extraction & Denoising Agent**: Strips redundant personal info, extracting underlying transferable skills.
2. **Industry Logic Mapping Agent**: The core reasoning engine. Maps general skills to specific industry competencies and jargon (e.g., Livestreaming conversion metrics).
3. **QA & Formatting Agent**: Validates sensitive information (age, tenure) and renders the final standardized output.

## 🛠 Quick Start
*(Note: Core prompt templates and fine-tuned models are currently kept private for MVP testing).*
```bash
git clone [https://github.com/your-username/resume-agent-pipeline.git](https://github.com/your-username/resume-agent-pipeline.git)
cd resume-agent-pipeline
pip install -r requirements.txt
python main.py
