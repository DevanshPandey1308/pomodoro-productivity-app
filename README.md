# Pomodoro Productivity App ⏱️🍅

A simple and effective **Pomodoro timer** built with **Python** and **Tkinter**.  
Stay focused and productive by cycling through structured work sessions and timed breaks using the classic Pomodoro technique.

---

## 📌 Features

- 25‑minute focused **work sessions**  
- 5‑minute **short breaks**  
- 20‑minute **long break** after every 4 work sessions  
- **Automatic** switching between work and break cycles  
- Clean and minimal **Tkinter GUI**  
- Visual **checkmarks** for completed work sessions  


---


## 📁 Project Structure

pomodoro-productivity-app/
│
├── main.py # Main Pomodoro logic + Tkinter UI
│
├── tomato.png # Tomato image used in the UI
│
├── Output Screenshot/ # UI screenshots
│ └── output.png
│
├── .idea/ # Auto-generated IDE metadata
├── .gitignore
├── desktop.ini
└── README.md

---

## ▶️ How to Run

1. **Clone the repository**

git clone https://github.com/DevanshPandey1308/pomodoro-productivity-app.git
cd pomodoro-productivity-app

text

2. **Run the application**

python main.py

text

No external libraries are required — the app uses Python's built‑in **Tkinter** module.

---

## ⚙️ Customization

You can tweak the Pomodoro cycle durations by editing the constants at the top of `main.py`:

WORK_MIN = 25
SHORT_BREAK_MIN = 5
LONG_BREAK_MIN = 20


You can also customize:

- **Colors** (theme and highlights)  
- **Fonts**  
- **UI layout** (window size, labels, buttons, etc.)

All of these are configurable inside `main.py`.

---

## 🚀 Future Enhancements

Planned improvements:

- Sound notifications for session start/end  
- Session statistics (CSV/Excel logging)  
- Customizable timer settings from the UI  
- Dark/Light theme toggle  
- Packaging as a standalone `.exe` using PyInstaller  

---

🙌 Acknowledgments

This project is part of my Python development journey — focusing on GUI design, event-driven programming, and clean project structure.
The Pomodoro method has personally helped improve focus, so building a tool around it was both practical and educational.
