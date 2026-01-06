# 📖 Dictionary App

A clean, responsive **Dictionary Web App** built with **HTML, CSS, and JavaScript** that allows users to search for English words, view their meanings, phonetics, synonyms, antonyms, and listen to pronunciation audio — all powered by a free public dictionary API.

---

## 📑 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [How It Works](#how-it-works)
- [Installation & Usage](#installation-usage)
- [API Used](#api-used)
- [Dark Mode Support](#dark-mode-support)
- [Error Handling](#error-handling)
- [Future Improvements](#future-improvements)
- [Credits](#credits)

---

<h2 id="overview">📌 Overview</h2> 

The **Dictionary App** lets users quickly search for English words and displays:

- Word definition
- Part of speech
- Phonetic pronunciation
- Audio pronunciation
- Synonyms and antonyms

The UI is designed to look like a **classic dictionary**, with automatic **dark mode support** based on the user's system settings.

---

<h2 id="features">✨ Features</h2> 

- 🔍 Search for any English word
- 🔊 Audio pronunciation (when available)
- 📝 Phonetic transcription
- 📚 Definitions with part of speech
- 🔁 Synonyms and antonyms
- 🌙 Automatic light & dark mode
- 📱 Fully responsive design
- ⚡ Fast API-based results

---

<h2 id="demo">🚀 Demo</h2>

You can run the project locally or deploy it using **GitHub Pages**.

```bash
https://sohan123-45.github.io/Dictionary_App/
```

---

<h2 id="technologies-used">🛠 Technologies Used</h2> 

- **HTML5** – Structure
- **CSS3** – Styling & dark mode
- **JavaScript** – Logic & API handling
- **Font Awesome** – Icons
- **Dictionary API** – Word data

---

<h2 id="project-structure">📁 Project Structure</h2> 

```text
dictionary-app/
│
├── index.html       # Main HTML file
├── style.css        # Styling and dark mode
├── script.js        # JavaScript logic
└── README.md        # Project documentation
```

---

<h2 id="how-it-works">⚙️ How It Works</h2> 

1. User enters a word in the search box
2. JavaScript fetches data from the Dictionary API
3. The app displays:
   
   Word title
   
   Phonetic text
   
   Pronunciation button
   
   Meanings with part of speech
   
   Synonyms and antonyms
5. If pronunciation audio exists, it can be played using the play button

---

<h2 id=""installation-usage>▶️ Installation & Usage</h2> 
Option 1: Run Locally
1. Clone the repository:
   ```bash
   https://github.com/Sohan123-45/Dictionary_App.git
  
2. Open project folder
3. Open index.html in your browser

---

<h2 id="api-used">🌐 API Used</h2> 
This project uses the Free Dictionary API:
```bash
https://api.dictionaryapi.dev/
```
Example API endpoint:
```bash
https://api.dictionaryapi.dev/api/v2/entries/en/example
```

---

<h2 id="dark-mode-support">🌙 Dark Mode Support</h2>

The app automatically switches between light and dark themes based on the user's system preferences using:
```bash
@media (prefers-color-scheme: dark)
```
No manual toggle required.

---

<h2 id="error-handling">❗ Error Handling</h2> 

Alerts the user if:
  The word does not exist
  Pronunciation audio is unavailable
Prevents crashes with try...catch handling

---

<h2 id="future-impovements">🔮 Future Improvements</h2>

⌨️ Search on Enter key press

⭐ Save favorite words

📜 Search history

🌍 Multiple language support

🧠 Multiple definitions per word

🎨 Theme toggle button

---

<h2 id="credits">🙌 Credits</h2> 

Font Awesome for icons
DictionaryAPI.dev for word data

---

<h2 id="credits">⭐ If you like this project, give it a star on GitHub!</h2> 
