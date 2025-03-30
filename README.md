# SFBU Bayhawk ChatBot

SFBU Bayhawk ChatBot is an AI-powered academic assistant developed for San Francisco Bay University (SFBU). Designed to assist students, faculty, and guests, the chatbot leverages OpenAI's GPT model, LangChain, and other technologies to provide multilingual, context-aware, and dynamic support. Whether you're a student seeking academic resources or a faculty member needing administrative tools, Bayhawk ChatBot delivers efficient, personalized, and responsive solutions.

## Snapshots:


![image](https://github.com/user-attachments/assets/680fe0ee-70dc-4a71-8a09-8ef080db3564)

![image](https://github.com/user-attachments/assets/5b27c0f0-5349-4c06-8790-5857dd2c167e)

![image](https://github.com/user-attachments/assets/7cd6c852-af0d-4552-a9e3-dbb6858ccd2f)


---

## Key Features

### General Features
- **24/7 Accessibility:** AI-driven support across all time zones without manual intervention.
- **Multimodal Inputs:** Accepts queries through text, audio, and documents (PDFs, YouTube transcripts, and web pages).
- **Multilingual Support:** Communicate in your preferred language with seamless translation and response generation.

### Student-Focused Features
- **Smart Q&A System:** Context-aware, history-sensitive responses to academic queries.
- **Escalate Query:** Create tickets for unresolved queries.
- **IT Support:** Help with any IT Related issues.
- **Automated Follow-Ups:** Personalized email updates for unresolved queries.

### Faculty-Focused Features
- **MCQ Generation:** Easily create multiple-choice questions from files, URLs, or typed content.
- **Presentation Creation:** Generate professional PowerPoint presentations from provided content.
- **Syllabus Design:** Streamline course planning with intelligent syllabus generation tools.
- **IT Support Assistant:** Efficiently resolve IT-related issues for seamless operation.

### Advanced Features
- **Audio Chat Support:** Real-time voice interactions using Whisper for transcription and OpenAI TTS for audio responses.
- **Dynamic Prompting:** Ensures responses adhere to SFBU-specific context.
- **Content Moderation:** Automatic moderation to ensure appropriate and reliable responses.
- **Email Integration:** Summarizes chats and notifies admissions or visitors via automated emails.

---

## Architecture Components

- **Backend:** Flask web framework.
- **Frontend:** JavaScript, HTML, and CSS for intuitive UI/UX.
- **Data Processing:** LangChain for conversational chains and document handling.
- **Semantic Search:** OpenAI embeddings with FAISS and AstraDB for fast and scalable data retrieval.
- **Audio Handling:** Whisper for speech-to-text and OpenAI TTS for text-to-speech.
- **Database:** Vector storage and custom memory for maintaining context in conversations.

---


## Execution Flow

1. **User Query:** Input via text, audio, or document.
2. **Processing:** Query processed through LangChain and vector store for semantic understanding.
3. **Response Generation:** Context-aware replies generated using OpenAI's GPT model.
4. **Response Delivery:** Output returned as text, audio, or downloadable resources (e.g., PDFs, presentations).

---

## Contributors

- **Karan Shrestha**
- **Vaishnavi Patil**
- **Rajat Raju Kamble**
- **Yin Yin Phyo**
- **Jubaida Tasnim**

---

## How to Use

1. Access the chatbot via the SFBU web portal or application.
2. Choose your role: Student, Faculty, or Guest.
3. Input your query or upload a document for processing.
4. Receive responses tailored to your needs, including downloadable resources or audio support.

---

## Contact

For queries or assistance, feel free to reach out to the SFBU Bayhawk Bot or the project contributors.

---





**Thank You!**
