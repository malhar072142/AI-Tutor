# EducationAI - Personalized AI Learning Assistant

## 📌 Overview
EducationAI is an AI-driven educational platform designed to personalize learning experiences for students. By leveraging advanced Natural Language Processing (NLP) techniques, this project demonstrates the application of:
- **Multi-Stage Prompting**  
- **Few-Shot Learning**  
- **Chain-of-Thought Reasoning**  
- **Iterative Chatbot Development**  

The system dynamically adapts to a student’s needs, generates personalized learning plans, creates tailored quizzes, and provides interactive step-by-step explanations.

## 🎯 Project Goals
- Develop an **AI-powered tutoring system** for a 10th-grade student, Alex, focusing on Algebra and Physics.
- Create a **personalized learning experience** by analyzing user profiles and learning preferences.
- Implement an **iterative chatbot** that assists students in real-time.
- Use **generative AI models** (OpenAI GPT-4o) to provide structured educational content.

---

## 🛠️ Installation & Setup

### 📌 Prerequisites
- Python 3.x
- OpenAI API Key
- Dependencies: `openai`, `requests`, `aiohttp`, `tqdm`

### 📥 Install Dependencies
Run the following command to install required packages:

```bash
pip install openai requests aiohttp tqdm
```

### 🔑 Set Up OpenAI API Key

Replace 'YOUR_API_KEY_HERE' with your actual OpenAI API Key:

```python
import openai
openai.api_key = "YOUR_API_KEY_HERE"
```

### 📌 Features & Implementation

1️⃣ Student Profile Initialization

Collects student data (name, grade, preferred subjects, learning goals).
Configures AI model (gpt-4o) for generating personalized learning content.

2️⃣ Multi-Stage Prompting

🔹 Generate Personalized Learning Plan
AI analyzes the student’s profile and creates a customized study plan.
Breaks down weekly goals and activities for structured learning.

🔹 Design a 4-Week Study Plan
The system generates a structured 4-week schedule.
Each week has defined goals, activities, and progress tracking.

🔹 Summarize Educational Resources
AI curates a list of books, online courses, and practice tests.
Focuses on high-quality, accessible, and interactive learning materials.

3️⃣ Quiz Generation (Few-Shot Prompting)
Generates custom quizzes for algebra and physics.
Ensures question variety and increasing difficulty levels.

4️⃣ Step-by-Step Problem Solving (Chain-of-Thought)
Uses reasoning techniques to break down complex physics problems.
Provides structured, logical steps for better understanding.

5️⃣ Interactive & Iterative Chatbot
- Iteration 1: Basic tutoring assistance.
- Iteration 2: Personalized responses with encouragement.
- Iteration 3: Adjusts responses based on feedback (concise or detailed explanations).
  
### 📊 Observations & Insights

✔️ AI successfully created structured learning profiles and study plans.

✔️ The chatbot was adaptive and responsive to user input.

✔️ Step-by-step problem-solving improved conceptual understanding.

⚡ Improvements Suggested:

- Increase contextual adaptability in chatbot responses.
- Provide specific resource recommendations (book titles, course links).
- Implement semantic understanding to refine chatbot behavior.


Develop a user-friendly UI for better accessibility.

📜 References & Acknowledgments
- Developed as part of IE7374 GenAI
- Author: Malhar Sham Ghogare