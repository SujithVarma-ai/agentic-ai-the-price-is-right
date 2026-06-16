# 🚀 Agentic AI: The Price Is Right

An intelligent multi-agent AI system that automatically discovers online deals, estimates product value using multiple AI models, identifies high-discount opportunities, and sends notifications to users.

Built using Agentic AI principles, Retrieval-Augmented Generation (RAG), ChromaDB, OpenAI models, and a Gradio dashboard for real-time monitoring.

---

## 📌 Overview

The Price Is Right is an Agentic AI application that continuously scans online deal sources, evaluates products using a collaborative agent framework, and surfaces the most promising opportunities.

The system combines multiple specialized agents that work together autonomously to discover, analyze, and recommend deals.

---

## Model Files

The trained model file (`deep_neural_network.pth`) is not included in this repository due to its large size.

To run the complete system:

1. Train the neural network model using the provided training scripts.
2. Place the generated `deep_neural_network.pth` file in the appropriate project directory.
3. Run the application normally.

The repository includes all source code, training pipelines, and configuration required to reproduce the model.

---

## ✨ Features

* 🤖 Multi-Agent Architecture
* 🔍 Automated Deal Discovery
* 🧠 AI-Powered Product Valuation
* 📊 ChromaDB Vector Database
* 🔔 Real-Time Notifications
* 🌐 RSS Feed Integration
* 🎯 Opportunity Scoring
* 🖥️ Interactive Gradio Dashboard
* 📈 Embedding Visualization

---

## 🏗️ Agent Workflow

```text
User / Scheduler
        ↓
Planning Agent
        ↓
Scanner Agent
        ↓
Ensemble Agent
   ├── Frontier Agent
   ├── Specialist Agent
   └── Neural Network Agent
        ↓
Planning Agent
        ↓
Messaging Agent
        ↓
Notification + Dashboard Update
```

### Planning Agent

Coordinates the entire workflow and decides which agent should perform each task.

### Scanner Agent

Retrieves new deals from RSS feeds and prepares candidate opportunities.

### Ensemble Agent

Combines predictions from multiple valuation models to estimate the true market value of products.

### Messaging Agent

Sends notifications when high-value opportunities are discovered.

---

# 📸 Application Screenshot

![App Screenshot](https://github.com/SujithVarma-ai/agentic-ai-the-price-is-right/blob/main/Screenshot%202026-06-13%20222823.png)

---

## 🔄 How It Works

### Step 1: Deal Collection

The Scanner Agent retrieves the latest deals from online RSS feeds.

### Step 2: Deal Selection

OpenAI Structured Outputs are used to select the most detailed and relevant deals.

### Step 3: Product Valuation

The Ensemble Agent estimates product value using:

* Frontier LLM
* Specialist Model
* Neural Network Model

### Step 4: Opportunity Detection

The system calculates:

```text
Discount = Estimated Value - Deal Price
```

### Step 5: Notification

High-value opportunities are sent to the user through the Messaging Agent.

---

## 🧠 Technologies Used

### AI & LLMs

* OpenAI GPT Models
* Agentic AI
* Structured Outputs

### Retrieval & Search

* ChromaDB
* Vector Embeddings
* RAG Pipeline

### Machine Learning

* Neural Networks
* Ensemble Modeling
* Scikit-Learn

### Backend

* Python
* RSS Feed Processing
* JSON Data Pipelines

### Frontend

* Gradio

---

## 📊 Example Output

| Product                    | Price | Estimated Value | Discount |
| -------------------------- | ----- | --------------- | -------- |
| Samsung Galaxy Watch Ultra | $350  | $773.81         | $423.81  |
| Apple iPhone 14 Pro Max    | $705  | $930.88         | $225.88  |

---

## 🚀 Installation

```bash
git clone https://github.com/SujithVarma-ai/agentic-ai-the-price-is-right.git

cd agentic-ai-the-price-is-right

pip install -r requirements.txt
```

---

## ▶️ Run

```bash
python price_is_right.py
```

---

## 🎯 Skills Demonstrated

* Agentic AI Systems
* Multi-Agent Workflows
* Retrieval-Augmented Generation (RAG)
* ChromaDB Vector Databases
* OpenAI API Integration
* Structured Outputs
* Gradio Application Development
* Neural Network Price Prediction
* RSS Feed Processing
* End-to-End AI Application Engineering

---

## 📜 License

This project is intended for educational and research purposes.
