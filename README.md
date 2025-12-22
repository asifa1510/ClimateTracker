**Climate Impact Tracker** 🌱

An open-source AI agent that estimates the carbon impact of digital activity and suggests practical ways to reduce it.

**Overview**
Climate Impact Tracker makes *invisible digital emissions visible**.  
Instead of tracking people or offsets, it focuses on **technical decisions** — code, cloud usage, and infrastructure choices.

At its core is an AI agent that doesn’t just report numbers, but **reasons about where change actually matters**.

**What makes it different**
- Focuses on *decisions*, not guilt or offsets  
- Uses an AI agent to prioritize actions, not just summarize data  
- Explicitly models uncertainty and confidence  
- Designed to be composable with existing developer workflows

**What it does**
- Estimates carbon impact from cloud and web activity  
- Identifies the largest emission drivers  
- Suggests low-effort, high-impact optimizations  
- Tracks changes over time

**How it works**
Usage data → CO₂e estimation → agent analysis → recommendations

All outputs are *directional estimates**, with documented assumptions and limitations.

**Tech stack**
- n8n (workflow orchestration)
- PostgreSQL (data storage)
- CrewAI (agent reasoning)
- Open-source carbon estimation models
- Local or hosted LLM (optional)
