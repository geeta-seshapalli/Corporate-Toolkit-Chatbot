# Corporate-Toolkit-Chatbot
Corporate Toolkit Chatbot: An LLM-powered web application with multiple tools for business use. Features include a meeting agenda generator, text summarizer, email drafter, and a grammar/tone fixer. Built with HTML, Tailwind CSS, JavaScript using the Gemini API.

# 🤖 Corporate Toolkit Chatbot

The **Corporate Toolkit Chatbot** is an interactive web-based assistant designed to support corporate workflows.  
It provides **meeting agenda generation, text summarization, professional email drafting, and grammar/tone correction** — all inside a clean, responsive chat UI built with **HTML, Tailwind CSS, and JavaScript**.  

---

## 🚀 Features

### 📝 1. Meeting Agenda Generator
- Generates professional, **time-boxed agendas** for any meeting type (kick-off, review, planning, etc.).
- Takes **topic** and **duration (minutes)** as inputs.
- Outputs a **structured agenda with descriptions** for each agenda item.

### 📄 2. Text Summarizer
- Summarizes **long text blocks** into concise points.
- Ideal for reducing emails, documents, or notes into a **digestible summary**.

### 📧 3. Email Drafting Tool
- Drafts **professional emails** based on:
  - **Topic/subject**
  - **Recipient**
  - **Key points**
  - **Desired tone** (formal, casual, urgent, etc.)
- Produces clean, professional messages ready to send.

### ✍️ 4. Grammar & Tone Fixer
- Rewrites any text into **grammatically correct, professional language**.
- Supports custom tone preferences like *formal*, *casual*, or *professional*.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, Tailwind CSS  
- **Styling:** Google Fonts (Inter), custom CSS with **glassmorphism effect**  
- **Logic:** Vanilla JavaScript  
- **LLM API:** Google Generative Language API (Gemini 2.5 Flash Preview)  
- **UI Enhancements:**
  - Animated loading dots
  - Different **chat bubble styles** for user and bot
  - Mobile-friendly responsive layout

---

---

## ⚡ How It Works

1. **User Input**  
   - Enter a request in the chat box (e.g., *“Generate a 45-minute agenda for a project kickoff meeting”*).  

2. **Processing**  
   - The chatbot parses the request.
   - If a **tool function** (agenda, summary, email, fixer) is detected, it prepares a custom API call.  

3. **API Call**  
   - Sends the prompt to **Google Generative Language API (Gemini)**.  
   - Different payloads are used for each tool (agenda JSON, summary text, email draft, etc.).  

4. **Bot Response**  
   - Displays structured output in a styled **chat bubble**.
   - Special layouts are used for agendas, summaries, and corrected text.

---

## 🖥️ Setup & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/Corporate-Toolkit-Chatbot.git
cd Corporate-Toolkit-Chatbot
```
### 2. Open Locally

Simply open index.html in a browser (no build step required).

Works with any modern browser.

### 3. Replace API Key

Inside index.html, locate this line: const apiKey = typeof window.__GAPI_KEY__ !== 'undefined' ? window.__GAPI_KEY__ : "API KEY";
Replace with your own Google Generative Language API Key:
const apiKey = "YOUR_GOOGLE_API_KEY";

---
## 🧑‍💻 Developer

**Geeta Seshapalli**  
🔗 [LinkedIn](https://www.linkedin.com/in/geetaseshapalli)  
🐱 [GitHub](https://github.com/geeta-seshapalli)

## 📝 Contribution

Feel free to fork this repository and submit pull requests. If you encounter any issues or have suggestions for improvements, please open an issue. 🙌
> _If you find this repository helpful, please give it a ⭐️!_

## Check this
 [Website](https://geeta-seshapalli.github.io/Corporate-Toolkit-Chatbot) 

