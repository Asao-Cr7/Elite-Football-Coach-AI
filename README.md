# 🏆 Elite Football Coach AI
## A Modular Prompt Engineering System for Structured Session Generation

---

## 📌 Project Overview

Elite Football Coach AI is a modular prompt-engineering project designed to simulate a professional football coaching mentor.

The system generates structured, human-readable football training sessions tailored to:

- Age group
- Skill focus
- Number of players

This project demonstrates how prompt engineering can be treated as system architecture rather than random text instructions.

---

## 🎯 Purpose of This Project

I built this project to:

- Practice modular prompt design
- Simulate structured reasoning safely (without exposing chain-of-thought)
- Separate AI behavior from business logic
- Apply software engineering principles to prompt engineering
- Build an AI-ready architecture for future OpenAI API integration

---

## 🧠 Prompt Engineering Architecture

This system is designed using modular layers:

### 1️⃣ Persona Layer

Defines tone and coaching personality:

- UEFA-level experience
- Practical and passionate tone
- Never robotic or textbook-like

---

### 2️⃣ Interaction Control Layer

Implements a structured input flow:

- Collects required inputs first
- Prevents premature session generation
- Ensures tailored output

---

### 3️⃣ Structured Reasoning Layer

Simulates professional coaching logic using:

- Safety and age considerations
- Difficulty calibration
- Player organization strategy
- Plain-English explanation filtering

This maintains transparency without exposing raw chain-of-thought reasoning.

---

### 4️⃣ Session Template Engine

Generates structured output sections:

- The Mission
- Warm-Up (with coaching cues)
- Main Drill (Recipe Pattern: Ingredients + Method)
- Visual Aid (YouTube search link)
- Safety Checklist

---

### 5️⃣ Adaptive Extension Layer

Supports dynamic coaching adjustments:

- Option A: Simplify for beginners
- Option B: Gamify the session
- Option C: Knowledge check quiz

---

## 🏗 Project Structure

elite-football-coach-ai/
│
├── prompts.py
├── generator.py
├── streamlit_app.py
├── requirements.txt
├── .env
├── .gitignore
├── LICENSE
└── README.md

### File Responsibilities

- prompts.py → Modular AI behavior configuration
- generator.py → Session generation orchestration logic
- streamlit_app.py → Streamlit user interface layer
- requirements.txt → Project dependencies
- .env → Environment variables (API keys not committed)
- LICENSE → MIT License
- README.md → Project documentation

---

## 💡 Key Technical Concepts Demonstrated

- Modular prompt abstraction
- Persona engineering
- Controlled conversational flow
- Structured reasoning simulation
- Output formatting design
- Separation of concerns
- AI-ready system architecture

---

## 🖥 How to Run Locally

### 1️⃣ Clone the Repository

git clone https://github.com/YOUR-USERNAME/elite-football-coach-ai.git  
cd elite-football-coach-ai

---

### 2️⃣ Create a Virtual Environment (Recommended)

python -m venv venv

Activate it:

Windows  
venv\Scripts\activate  

Mac/Linux  
source venv/bin/activate  

---

### 3️⃣ Install Dependencies

pip install -r requirements.txt

---

### 4️⃣ (Optional) Set Up Environment Variables

Create a `.env` file in the project root:

OPENAI_API_KEY=your_api_key_here

⚠ Never upload your `.env` file to GitHub.

---

### 5️⃣ Run the Application

streamlit run streamlit_app.py

The app will open at:

http://localhost:8501

---

## 🚀 Future Improvements

- OpenAI API integration
- JSON structured output mode
- Player performance tracking
- Session quality evaluation layer
- Multi-language support

---

## 👨‍💻 Development Approach

This project was developed using iterative prompt refinement techniques.

Large language models (ChatGPT and Gemini) were used as collaborative design tools to:

- Prototype prompt structures
- Refine instruction clarity
- Stress-test structured outputs
- Improve modular architecture

All architectural decisions and implementation logic were intentionally structured and organized by me.

---

## 📈 About Me

I am actively building skills in:

- AI engineering
- Prompt system design
- Python backend development
- Applied software architecture
