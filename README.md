📚 Study & Habit Tracker
A command-line productivity tool built with Python to help you track study sessions and daily habits — with full CRUD support, data persistence, search, sort, and timestamps.

🚀 Features
Study Sessions

➕ Add study sessions with subject name and time
👁️ View all sessions with timestamps
✏️ Edit existing sessions
🗑️ Delete sessions
🔍 Search sessions by subject name
📊 Sort sessions by time (highest first)
⏱️ View total study time

Habits

➕ Add habits with name and time commitment
👁️ View all habits with timestamps
✏️ Edit existing habits
🗑️ Delete habits
🔍 Search habits by name
📊 Sort habits by time (highest first)
⏱️ View total habit time

Data & Storage

💾 Auto-saves to session.json and habit.json
📂 Auto-loads your data every time you run the program
🕐 Timestamps on every entry (date + time)
⏳ Time stored in minutes, displayed as X hr Y min


🛠️ Tech Stack
ToolPurposePython 3Core languagejsonData persistencedatetimeTimestamps
No external libraries required — runs on pure Python standard library.

📁 Project Structure
study-habit-tracker/
│
├── Study_and_Habit_tracker.ipynb   # Main Jupyter notebook
├── session.json                    # Auto-generated: saved study sessions
├── habit.json                      # Auto-generated: saved habits
└── README.md

▶️ How to Run
Option 1 — Jupyter Notebook
bashjupyter notebook Study_and_Habit_tracker.ipynb
Option 2 — Convert to Python and run
bashjupyter nbconvert --to script Study_and_Habit_tracker.ipynb
python Study_and_Habit_tracker.py

🖥️ Menu Options
===== Study and Habit Tracker =====
1.  Add Study Sessions
2.  View Study Sessions
3.  Add Habits
4.  View Habits
5.  Total Study Time
6.  Total Habit Time
7.  Delete Study Sessions
8.  Delete Habit Sessions
9.  Edit Study Sessions
10. Edit Habit
11. Search Study Sessions
12. Search Habits
13. Sort Study Sessions
14. Sort Habits
15. Exit

📖 How It Works
When you run the program, it asks for your name and loads any previously saved data automatically. From the menu you can add, view, edit, delete, search, and sort both study sessions and habits. All changes are saved to JSON files instantly — so nothing is lost when you close the program.
Time is stored internally in minutes and displayed in a clean X hr Y min format. When adding time you enter the value and choose h (hours) or m (minutes).

🔄 Project Evolution
This project was built iteratively across multiple versions — each one improving on the last:
VersionWhat was addedv1Basic menu loop — add, view, delete, total timev2Refactored into separate functionsv3JSON save/load for data persistencev4Timestamps, search, sort, auto-save on exitv5Hours/minutes unit input, clean time display

🌐 Web Version
A browser version of this project was also built as a standalone HTML file — no installation needed, just open in any browser. Features a dark UI with a dashboard, progress bars, and localStorage persistence.

🤝 Contributing
This is a learning project, but suggestions and improvements are welcome! Feel free to open an issue or submit a pull request.

👤 Author
Built as a Python learning project — starting from a simple while loop and growing into a structured, feature-rich CLI application.

📄 License
This project is open source and available under the MIT License.
