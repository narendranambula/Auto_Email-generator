# 📧 Email Writer – Spring Boot + Gemini API

A Spring Boot-based web application that uses Google's **Gemini 2.0 Flash** model to generate **professional email replies** based on given input content and tone.

---

## 🚀 Features

- 🌐 RESTful API using Spring Boot
- ⚡ Reactive `WebClient` integration
- 🤖 AI-generated email replies using Google Gemini API
- 🎯 Tone customization (e.g., formal, friendly, persuasive)
- 🛡️ CORS enabled for frontend integration

---

## 🏗️ Tech Stack

- Java 17+
- Spring Boot 3+
- WebFlux (for non-blocking HTTP calls)
- Lombok
- Google Generative Language API (Gemini 2.0 Flash)

## 📸 Screenshots & Workflow

This section explains the functionality of the Email Generator app using actual screenshots from development and testing.

---

### ✅ 1. Server Status

The Spring Boot application is successfully running, confirming that the backend is properly initialized and ready to handle API requests.

![Server Running](./server_running.png)

---

### 🌐 2. Chrome Extension Integration (Optional)

The application is planned to be integrated into a Chrome extension to allow users to generate email replies directly from their browser-based email client (like Gmail).

![Chrome Extension](./chrome_ext.png)

### 📥 3. Input Phase – Providing Email

The user submits an original email message that needs a professional reply. This input is provided either through a frontend UI or an API tool like Postman.

![Email Input](./email_1.png)

---

### ✨ 4. Output Phase – AI-Generated Reply

**Alternate/Improved AI Response:**

![AI Reply](./AI_replay.png)


The Gemini model takes the prompt and tone as input and returns a human-like, professional email response.

**First Generated Output:**

![Generated Reply](./Replay_generated.png)

---




