# ⏰ Time Management Optimization for University Students using LPP

## 🔍 Overview
This program helps university students optimize their weekly time allocation using Linear Programming. It provides an optimal distribution of hours across academic, extracurricular, and personal activities while maximizing productivity and well-being.

## ✨ Features
- Optimizes time allocation across 5 key activities: classes, self-study, sports, societies, and leisure
- Accounts for mandatory time commitments and minimum requirements
- Visualizes the optimal time distribution
- Uses mathematical optimization to maximize productivity based on weighted priorities

## 📋 Requirements
- Python 3.x
- PuLP library
- Matplotlib library

## 💻 Installation
```bash
pip install pulp matplotlib
```

## 🚀 Usage
1. Clone this repository or download the Python script
2. Modify the parameters in the script as needed:
   - Number of courses
   - Sports sessions
   - Activity weights
   - Minimum time requirements
3. Run the script:
```bash
python time_management.py
```

## 🧩 How It Works
The program formulates the time management problem as a Linear Programming Problem (LPP) with:

- Decision variables representing hours spent on different activities
- An objective function that maximizes weighted productivity
- Constraints ensuring all requirements are met
- Total available time limit of 119 hours (accounting for 7 hours of sleep per night)

## 📊 Example Output
```
Status: Optimal

--- Optimal Allocation ---
Classes: 20.0 hours
Self-Study: 76.0 hours
Sports: 6.0 hours
Societies: 3.0 hours
Leisure: 14.0 hours
Total Hours Allocated: 119.0
```

The program also generates a bar chart visualization of the time allocation saved as `time_allocation.png`.

## ⚙️ Customization
You can easily customize the model by modifying:
- The weights in the objective function
- The number of courses
- Sports session requirements
- Society participation requirements
- Minimum leisure time

## ⚠️ Limitations
- Assumes linear relationships between time and productivity
- Does not account for variable efficiency during different times of day
- Fixed weights may not reflect changing priorities throughout the semester

## 📝 License
[MIT License](LICENSE)

## 👨‍💻 Author
IT3262 Operations Research - 2020/ICT/07