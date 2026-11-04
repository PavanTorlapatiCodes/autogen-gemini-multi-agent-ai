# AutoGen + Gemini: Multi-Agent AI Applications

A collection of AI-powered applications built using **Python, Microsoft AutoGen, Google Gemini, and Streamlit**.

This repository demonstrates multimodal AI image understanding and collaborative multi-agent workflows using modern Generative AI technologies.

## 🚀 Projects Included

### 1. Multimodal AI Image Analyzer

An interactive AI-powered image analysis application using Google Gemini Vision and Microsoft AutoGen.

**Features:**
- Upload images in JPG, JPEG, PNG, and WEBP formats.
- Fetch random sample images for testing.
- Enter custom prompts to analyze images.
- Perform multimodal AI analysis using text and image inputs.
- Generate detailed image descriptions and identify key visual elements.
- Display AI-generated responses through Streamlit.

**Technologies:**
- Python
- Microsoft AutoGen 0.4+
- Google Gemini 3 Flash Preview
- Streamlit
- Pillow
- Requests
- Python-dotenv

### 2. Multi-Agent Morning Coordinator

An AI-powered task coordination application using Microsoft AutoGen and Google Gemini.

The application uses three specialized AI agents to coordinate a morning schedule involving school drop-offs and office responsibilities.

**AI Agents:**

1. **School Agent 1**
   - Responsible for taking Kid 1 to School A.
   - Ensures arrival before 8:00 AM.

2. **School Agent 2**
   - Responsible for taking Kid 2 to School B.
   - Ensures arrival before 8:15 AM.

3. **Office Agent**
   - Responsible for coordinating Father's office schedule.
   - Ensures arrival before 9:00 AM.
   - Reviews and coordinates the other agents' plans.

**Features:**
- Multi-agent collaboration.
- Specialized agent responsibilities.
- Round-robin group chat execution.
- Task coordination and deadline-based planning.
- Streamlit chat interface.
- Persistent conversation history during the session.
- Automatic workflow termination using TextMentionTermination.

**Technologies:**
- Python
- Microsoft AutoGen AgentChat
- AutoGen Core
- AutoGen Extensions
- Google Gemini
- Streamlit
- Asyncio
- Python-dotenv

## 🏗️ Project Structure

```text
autogen-gemini-multi-agent-ai/
│
├── AGmultiagent.py       # Multimodal Gemini Image Analyzer
├── father.py             # Multi-Agent Morning Coordinator
├── requirements.txt      # Project dependencies
├── .env.example          # Environment variable template
├── .gitignore            # Git ignored files
└── README.md             # Project documentation
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/PavanTorlapatiCodes/autogen-gemini-multi-agent-ai.git
cd autogen-gemini-multi-agent-ai
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it on Windows:

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Gemini API Key

Get a Gemini API key from Google AI Studio:

https://aistudio.google.com/

Create a `.env` file in the project directory:

```env
GEMINI_API_KEY=your_gemini_api_key_here
```

Never upload your actual API key to GitHub.

### 5. Run the Multimodal Image Analyzer

```bash
streamlit run AGmultiagent.py
```

### 6. Run the Multi-Agent Morning Coordinator

```bash
streamlit run father.py
```

Open the local Streamlit URL displayed in your terminal.

## 🧠 Concepts Demonstrated

- Generative AI and Large Language Models
- Multimodal AI and Vision Models
- AI Agent Architecture
- Multi-Agent Collaboration
- Role-Based Agent Design
- Asynchronous Programming
- Group Chat Workflows
- Prompt Engineering
- LLM Integration
- Interactive AI Applications

## 🎯 Learning Outcomes

- Building AI applications with Microsoft AutoGen.
- Integrating Google Gemini models using an OpenAI-compatible API interface.
- Working with multimodal image and text inputs.
- Designing specialized AI agents.
- Implementing collaborative multi-agent workflows.
- Developing interactive applications using Streamlit.

## 👨‍💻 Author

**Pavan Kumar Torlapati**

GitHub: https://github.com/PavanTorlapatiCodes

LinkedIn: https://linkedin.com/in/pavan-torlapati-7543732ba

## 🙏 Acknowledgement

Special thanks to **Mr. Kodi Prakash Senapati** for guidance and support throughout my Generative AI and Agentic AI learning journey.

---

⭐ If you find this project useful, consider giving the repository a star!
