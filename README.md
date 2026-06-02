#  Email Writer App (Spring Boot + Gemini API)

An AI-powered email reply generator that helps users create context-aware email responses in different tones using Google's Gemini API. The application provides a simple interface for generating professional, friendly, or casual email replies instantly.

##  Features

* Generate AI-powered email replies from email content
* Support for multiple response tones:

  * Professional
  * Friendly
  * Casual
* Fast and responsive user interface
* Real-time integration with Google Gemini API
* Full-stack architecture with React and Spring Boot

##  Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* CSS

### Backend

* Spring Boot
* Java 21
* Maven
* Spring WebFlux

### AI Integration

* Google Gemini API

##  Project Structure

```text
Email-Writer
├── email_writer_react   # Frontend
├── email-writer-sb      # Backend
└── email-writer-ext     # Chrome Extension
```

##  Setup & Run

### Backend

```bash
cd email-writer-sb
mvn spring-boot:run
```

### Frontend

```bash
cd email_writer_react
npm install
npm run dev
```

##  Environment Variable

```env
GEMINI_API_KEY=your_api_key
```

