# 🧠 Vision-Language-Action (VLA) Mini Simulation

A simple, Colab-ready **Vision-Language-Action (VLA)** demonstration that connects *vision*, *language*, and *action* — inspired by cutting-edge embodied AI research (e.g., RT-X, OpenVLA, AIRoA).

This project demonstrates how a vision-language model can interpret **visual input** from an environment and decide an **action** based on a natural language instruction.

---

## 🎯 Objective

> “Keep the pole balanced.”

Using the *CartPole-v1* environment, the system:

- Observes the visual state of the environment.  
- Receives a natural language instruction.  
- Uses a simple vision-language reasoning method to select an action.  
- Logs and visualizes its step-by-step behavior.

---

## ⚙️ Setup and Usage

Run this project easily on **Google Colab** — no GPU required.

### Option 1: Open in Colab

| Notebook | Description |
|-----------|--------------|
| [🔗 VLA_Demo_1.ipynb](VLA_Demo_1.ipynb) | Basic reasoning and visualization |
| [🔗 VLA_Demo_2.ipynb](VLA_Demo_2.ipynb) | Enhanced logging and video export |

> Simply open either notebook in Google Colab and run all cells sequentially.

---

## 🧩 Project Structure

```
vla-mini-simulation/
│
├── VLA_Demo_1.ipynb           # Basic simulation and reasoning
├── VLA_Demo_2.ipynb           # With enhanced logging and video output
└── README.md                  # This file
```

---

## 🧪 Example Output

### 🖥️ Logs

```
🎯 Instruction: "Keep the pole balanced"

🌀 Step 5
Observation: [-0.0361, -1.1556, 0.0478, 1.7100]
Action taken: 0
Reward received: 1.000
------------------------------------------------------------
```

### 🎥 Video (auto-generated)

Each run produces a short `.mp4` showing how the agent balances the pole based on the given instruction.

---

## 📄 Features

✅ Vision-language reasoning with CLIP-style embeddings  
✅ Real-time action and reward logging  
✅ JSON-based structured logs for analysis  
✅ Automatic MP4 video generation  
✅ 100% runnable in Google Colab  

---

## 🌍 Research Context

This mini-project reflects the core principles of **embodied AI**, linking perception, reasoning, and motor control.  
It aligns conceptually with projects like:

- AIRoA’s Vision-Language-Action foundation models  
- DeepMind RT-X / RT-2  
- Stanford’s OpenVLA  

---

## 👨‍💻 Author

**Shahzeb Khoso**  
AI Research Engineer | Generative & Embodied Intelligence  
📍 [LinkedIn](https://www.linkedin.com/in/shahzebkhoso) | [GitHub](https://github.com/<yourusername>)

---
