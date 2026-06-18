#  History Guesser

A geography-history trivia game where a pin drops on a world map, a year appears, and you guess the historical event.

<img width="654" height="667" alt="image" src="https://github.com/user-attachments/assets/00132171-26d6-45a9-b7a1-505d239c5ac3" />

##  Try it now

**Play the live demo:**  
https://historyguesser.netlify.app/
---

##  Features

- **70+ historical events** spanning categories like War, Science, Politics, Exploration, Culture, and more.
- **Three difficulty levels** (Easy, Medium, Hard) — filter events to match your knowledge.
- **Interactive world map** with a pin that drops precisely at the event's location.
- **Learn as you play** — each round reveals a description and a fun fact after you answer.
- **Score & streak tracking** — keep track of your progress and challenge yourself.
- **Keyboard shortcuts** for quick play: `1-4` or `A-D` to answer, `Enter` for next, `Escape` to quit.
- **Fully responsive** — works on desktop, tablet, and mobile.

---

##  How to run it locally

If you're not using the live demo, here's how to run the project on your own machine:

1. **Clone or download** this repository.
2. Place the `img.jpg` map image in the same directory as `index.html`.  
   (The image must be a world map with country outlines — you can use the one from the link below.)
3. Open `index.html` in your browser.  
   No web server is required — it's a self-contained static page.

**Map image source:**  
The game expects a file named `img.jpg` in the same folder. A high‑resolution blank world map works best — you can download one from sites like Wikimedia Commons or use your own.

---

##  How it works

- The world map is rendered as a background image on a canvas element. The pin is a positioned HTML element that moves based on the event's normalized coordinates.
- All event data (name, year, location, category, difficulty, description, fun fact) is stored in a JavaScript array. The game picks a random event, generates three wrong options from the same filtered pool, and shuffles them.
- The timeline (year) is displayed prominently, and the player chooses from four options. After answering, the correct answer is highlighted, and feedback is shown.
- The game uses no external libraries — it's vanilla HTML/CSS/JS for maximum portability.
<img width="1291" height="679" alt="609546012-6e2b9b48-59ab-48f4-ba14-fb4f4bb52c37" src="https://github.com/user-attachments/assets/bf5834f7-51a5-417a-854b-6ba2e8d0b19a" />
---

##  Credits

This project was built with AI assistance — Claude helped generate boilerplate code, brainstorm event descriptions, and iterate on UI ideas. But every line was reviewed, tested, and refined by me. The event database was manually curated, map coordinates hand-placed, and UX decisions made with real users in mind. AI sketched the scaffolding; I built the house. Transparency matters if you use AI in your projects, be open about it.

---

##  Feedback

If you find a bug, have a suggestion, or want to add more events, open an issue or submit a pull request. Contributions are welcome!

---

Made with and a bit of history nerdery.
