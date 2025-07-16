💬 Project Name: Next Level ChatBot (HelpBot)
🧠 Overview:
This is a smart desktop chatbot application built using Python and Tkinter. It uses OpenAI's API via OpenRouter to provide intelligent responses, and integrates rich features like text-to-speech, speech recognition, syntax-highlighted code rendering, LaTeX support, and session-based chat history.

🔑 Key Features:
🎙️ Voice Input & Output:
Users can speak queries and hear responses in multiple languages via speech_recognition, gTTS, and pygame.

📚 Chat History with Search:
Each session is saved and searchable with renaming, deletion, and filtering support.

📌 Persistent Caching:
Frequently asked or long responses are cached to improve performance.

🧾 Code + Table Rendering:
Renders syntax-highlighted code blocks, tables, and even LaTeX math (inline & block).

🎨 Dark Mode Toggle:
Switch between light and dark themes using Ctrl + D.

📎 Right-Click Actions:
Copy or speak selected text with custom right-click context menus.

🔍 Smart Tooltips:
Hover tips help users discover button functionalities easily.

📋 Clipboard-friendly UI:
Copy buttons on code blocks, tables, and chat areas for quick use.

🧰 Tech Stack:
Frontend/UI: Tkinter (ttk), PIL (Pillow)

Voice & TTS: speech_recognition, gTTS, pygame

AI Backend: OpenAI (via OpenRouter API)

Extras: Matplotlib (for LaTeX), threading, JSON storage
