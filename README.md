# 🤖 AutoTaskerAI – Multi-Agent AI System

## 📌 Overview

AutoTaskerAI is an AutoGPT-style Multi-Agent AI system built using Python and powered by Gemini.
Instead of generating a single generic response, this system simulates a real software team where multiple AI agents collaborate to solve a given task.

From a single user prompt like:
👉 "Build a chatbot"
👉 "Create a sentiment analysis system"

The system intelligently breaks down, analyzes, implements, and evaluates the solution using specialized agents.

---

## 🎥 Demo Video

👉 [Watch Demo](https://1drv.ms/v/c/f27581e6ec46dbc4/IQDeW-NwW_3jTr5TWUv-MXQdAUB18yfGdIRCLVHolvj2Uz8?e=eSlCUw)

---

## 🚀 Features

* Multi-agent collaboration system
* AutoGPT-style task execution
* Modular and scalable architecture
* Intelligent task decomposition
* Real-time research and code generation
* Evaluation with quality and confidence scores
* Docker support for easy deployment

---

## 🧠 System Architecture (Agents)

### 🧠 Planner Agent

Understands the user input and breaks it into structured, actionable steps.

### 🔍 Researcher Agent

Analyzes each step and selects the best algorithms, tools, and approaches.

### 💻 Coder Agent

Generates clean, readable, and implementation-ready code based on research.

### 🧪 Reviewer Agent

Evaluates the output and provides:

* ✅ Confidence Score
* ✅ Quality Score
* ✅ Readiness Assessment

---

## 🛠️ Technologies Used

* Python
* Gemini API
* Docker
* Git & GitHub

---

## ▶️ How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Run the application:

   ```bash
   python app.py
   ```

---

## 📂 Project Structure

* agents/ → Individual AI agents (Planner, Researcher, Coder, Reviewer)
* core/ → Main orchestration logic
* app.py → Entry point

---

## 🌐 Future Improvements

* Integrate advanced ML models for improved decision-making
* Connect with real-world organizational datasets
* Enhance agent collaboration with memory and context awareness
* Deploy as a scalable web-based application

---

## 👩‍💻 Author

Ishwari Mhaske
