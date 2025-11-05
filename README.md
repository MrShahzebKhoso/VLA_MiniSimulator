# 🧠 Vision‑Language‑Action (VLA) Mini Simulator

A simple, Colab‑ready **Vision‑Language‑Action (VLA)** technical demo showing how vision, language and action can be integrated — suitable for portfolio and developer showcase use.

## 🎯 Objective

> “Keep the pole balanced.”

In this demo you’ll find two notebooks:

- `VLA_Conceptual_Demo.ipynb` — A conceptual demo using an image + instruction → action mapping via CLIP embeddings and a small action head.  
- `VLA_Practical_Demo.ipynb` — A practical demo that uses the CartPole‑v1 environment to show how an agent could interpret visual state + language instruction → control action.

## ⚙️ Setup & Usage

Run easily in Google Colab:

1. Open one of the notebooks in Colab.  
2. Run all cells sequentially.  
3. If using the practical demo, it will log the agent steps and generate a `.mp4` video of the simulation.

## 🧩 Project Structure

```
VLA_MiniSimulator/
│
├── VLA_Conceptual_Demo.ipynb     # Conceptual VLA pipeline
├── VLA_Practical_Demo.ipynb      # Embodied simulation demo
└── README.md                     # This file
```

## 🧪 Example Output

### Logs
```
🎯 Instruction: "Keep the pole balanced"

🌀 Step 0
Observation: [ 0.0208809 -0.1810137 -0.0358661  0.2689328 ]
Action taken: 0
Reward received: 1.000
------------------------------------------------------------
```

### Video
The practical demo produces a movie (`.mp4`) showing the agent balancing the pole, which can be embedded or reviewed as part of the demonstration.

## 📄 Features

- ✅ Vision‑language reasoning with a CLIP‑style image+text embedding.  
- ✅ Structured log output of action decisions and rewards.  
- ✅ Generated video of simulation to visualize results.  
- ✅ Fully runnable in Colab without heavy dependencies.


---
