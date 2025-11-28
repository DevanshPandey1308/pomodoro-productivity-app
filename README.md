# Pomodoro Productivity App (PMD)

A clean and simple Pomodoro Timer built using **Python** and **Tkinter**, designed to help maintain focus using the classic 25–5 work/break cycle.  
The app automatically switches between work sessions, short breaks, and long breaks while visually tracking completed sessions.

---

## 📌 Features
- 25-minute work sessions  
- 5-minute short breaks  
- 20-minute long break after 4 work cycles  
- Automatic session transitions  
- Visual checkmarks for completed sessions  
- Minimal and distraction-free UI  

---

## 📁 Project Structure
pomodoro-productivity-app/
│
├── Output Screenshot/ # App screenshots
├── .idea/ # Auto-generated IDE config
├── .gitignore
├── desktop.ini
├── main.py # Main Pomodoro application
└── tomato.png # Tomato image used in UI


---

## ▶️ How to Run

### 1. Clone the repository
git clone https://github.com/DevanshPandey1308/pomodoro-productivity-app.git
cd pomodoro-productivity-app
2. Run the application
bash
Copy code
python main.py
No external dependencies are required. Tkinter comes built-in with most Python installations.

⚙️ Customization
You can modify session durations directly inside main.py:
WORK_MIN = 25
SHORT_BREAK_MIN = 5
LONG_BREAK_MIN = 20
You can also change theme colors, fonts, and UI layout within the same file.

🚀 Future Improvements
- Add sound alerts
- Add session logging (CSV/Excel)
- Add customizable settings through UI
- Add light/dark mode


🙌 Acknowledgment
This project was built as part of my Python learning journey, focusing on improving UI development and timer-based logic using Tkinter.
If you find this useful or want to contribute improvements, feel free to open an issue or submit a pull request.
