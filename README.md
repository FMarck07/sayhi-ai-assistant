# SayHi! Chatbot 🤖

**SayHi!** is an interactive web-based chatbot developed in vanilla JavaScript, designed to answer questions about programming, Artificial Intelligence, and web development[cite: 1]. The bot implements a hybrid mechanism combining **Pattern Matching** with a structured **Knowledge Base**, evaluating and displaying a relevance confidence score for every answer[cite: 1].

---

## 👥 Authors
- **Francesco Marchetto**
- **Nicolò Visentini**
- **Riccardo Gianesella**

*Class: 5F (School Year 2025/2026)

---

## ✨ Features

- **Responsive Web Interface:** Modern UI built around a purple, white, and gray palette, fully optimized for desktops, tablets, and smartphones[cite: 1, 3, 7].
- **Relevance Scoring:** Color-coded badges indicating match confidence[cite: 1]:
  - 🟢 **Green (70–98%):** Highly relevant answer.
  - 🟠 **Orange (40–69%):** Partially relevant answer.
  - 🔴 **Red (0–39%):** Out-of-context query / fallback response[cite: 1, 5, 6].
- **Categories & Dynamic Prompts:** 5 quick-access categories (*Programming*, *AI*, *Web*, *Career*, *Random*) with interactive buttons to test predefined queries[cite: 1, 4, 5, 6].
- **Question Counter & Timestamps:** Tracks total queries sent and tags every message with the exact delivery time[cite: 1, 4, 5, 6].
- **Zero Heavy Dependencies:** Lightweight implementation using pure HTML, CSS, and Vanilla JavaScript[cite: 1].

---

## 📁 Repository Structure

```text
├── index.html          # Chat interface and primary entry point
├── index.js            # Core logic, pattern matching, and knowledge base
├── css/
│   └── style.css       # Layout styles, responsive media queries, and animations
├── analisi.pdf         # Project analysis and specification document
└── manuale_utente.pdf   # End-user guide
