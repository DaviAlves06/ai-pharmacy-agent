# 💊 AI Pharmacy Agent

An intelligent pharmaceutical assistant developed with **Python** and **Google Generative AI (Gemini API)**. This agent is designed to assist users with medication queries, health recommendations, and general pharmaceutical guidance in a professional and safe manner.

---

## 🚀 Key Features

* **Context-Aware Interactions:** Built using chat history to maintain the flow of conversation.  
* **System Instructions:** The agent is hard-coded to act as "Dr. Davi," a professional pharmacy attendant, ensuring a consistent and helpful persona.  
* **Safety First:** Implements rigorous safety filters for categories like Hate Speech, Harassment, and Dangerous Content to ensure reliable interactions.  
* **Real-time Guidance:** Capable of suggesting medication dosages, explaining side effects, and recommending medical consultations when necessary.  

---

## 🛠 Tech Stack

* **Language:** Python  
* **Model:** Google Gemini 1.5 Flash  
* **Library:** `google-generativeai`  

---

## ⚙️ Setup & Installation

1. **Clone the repository:**  
   ```bash
   git clone [https://github.com/DaviAlves06/ai-pharmacy-agent.git](https://github.com/DaviAlves06/ai-pharmacy-agent.git)
   ```

2. **Install dependencies:**  
   ```bash
   pip install -qU "langchain>=0.2.0,<0.4.0" langchain-community langchain-google-genai
   ```

3. **Configure your API Key:**  
   Get your API key from Google AI Studio and set it up as an environment variable.

---

## 🛡️ Safety & Ethics

This project prioritizes user safety by configuring the `safety_settings` of the Gemini model.  
It actively blocks:  
- Harassment  
- Hate Speech  
- Sexually Explicit Content  
- Dangerous Content  

---

## ⚠️ Disclaimer

This AI Agent is for educational and informational purposes only.  
It does not replace professional medical advice, diagnosis, or treatment.  
Always seek the advice of a physician or other qualified health provider with any questions regarding a medical condition.  

---

## 👤 Author

**Davi Alves**  
- Software Engineering Student @ FIAP 
- LinkedIn  
```
