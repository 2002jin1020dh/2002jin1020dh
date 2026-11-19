## Hi, I'm Jinhwan Jeong

I build robot learning systems that run on real hardware.
Undergraduate at Hansung University (Intelligent Systems Track, Division of IT Convergence Engineering), graduating Feb 2027.

**Interests:** Robotics · Edge AI · Physical AI — VLA models, reward modeling for real-robot RL, on-device inference

📫 2002jin1020dh@gmail.com

---

### Robotics

| Project | What it is | My role | Stack | Period |
|---|---|---|---|---|
| [**PAI**](https://github.com/2002jin1020dh/PAI) | Domain-adaptive VLA system: one natural-language command, and an SO-101 arm sorts recyclables or clears tableware, fully on a Jetson Orin Nano 8GB | Entire pipeline: data collection, training, on-robot deployment | LeRobot (ACT), Gemma 4 E2B, QLoRA, llama.cpp, ROS2 Humble, Isaac Sim | 2026.03–06 · Capstone, team of 3 |
| [**Welding_Robot**with Roboseasy](https://github.com/2002jin1020dh/Welding_Robot) | Teleoperation of a 6-DoF industrial manipulator from a 7-servo leader arm, via end-effector pose mapping and IK | Data collection, Isaac Sim environment setup, architecture design | Python, IK, CI (48 unit tests) | 2026.09–12 · Industry–academia, in progress |
| [**hil_review**](https://github.com/2002jin1020dh/hil_review) | VLM-assisted reward labeling for real-robot RL (HIL-SERL): a local VLM pre-labels the reward classifier, humans check only part of it | Data collection, architecture design | LeRobot, SO-ARM101, HIL-SERL | 2026.10– · Team of 2, in progress |

### Other projects

| Project | What it is | My role | Stack | Period |
|---|---|---|---|---|
| [**SpecPilot**with ThinkTree](https://github.com/2002jin1020dh/Specpilot) | Industry-sponsored tool that checks whether software requirements in planning documents are implemented in source code, and generates test specifications | Team lead (4): system architecture, LLM integration, test-case generation | Python, FastAPI, React, Claude API | 2026 Fall · On-campus internship |
| [**JARVIS**](https://github.com/2002jin1020dh/Jarvis) | Cloud memory server that lets multiple AI clients share one long-term memory over MCP | Memory-capture pipeline, bitemporal data model | FastAPI, PostgreSQL, pgvector, PGroonga, MCP | 2026.03–06 · Capstone, team of 3 |
| [**B_D_P**](https://github.com/2002jin1020dh/B_D_P) | Fake review detection on Yelp: BERT text features fused with reviewer behavior (Macro F1 0.874, AUC-ROC 0.941) | Model integration, MLP behavior encoder | PyTorch, BERT | 2026.03–08 · Course project |
| [**AI Report Generator**](https://github.com/Ctrl-Plus-Zi/capstone-ai-report-generator) | LangGraph multi-agent workflow that turns public cultural data into institution-specific reports in 30–80 s | Data processing and analysis | LangGraph, GPT-4o, FastAPI | 2025 Fall · Pre-capstone, team of 5 |

### Research

Independent research with Prof. Seungho Choi (Hansung University), May 2026 – present.

- Research experience in human-motion measurement, agricultural vision and medical imaging:
  running and verifying experiments, catching evaluation flaws such as data leakage,
  and preparing manuscripts.
- Submission experience: a manuscript on exercise movement analysis submitted to
  Engineering Applications of Artificial Intelligence (2026).

Research code is not public.

### Tech stack

**Robotics** ROS2 Humble · LeRobot · Isaac Sim · SO-101 / SO-ARM101 · Jetson Orin Nano · Intel RealSense
**Learning** PyTorch · imitation learning · RL (HIL-SERL) · LoRA / QLoRA
**VLM / LLM** Gemma · llama.cpp · GGUF · LangGraph · MCP
**Infra** Linux multi-GPU servers · CUDA · Docker · FastAPI · PostgreSQL · AWS · GCP
