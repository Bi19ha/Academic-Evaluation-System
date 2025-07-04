
```markdown
# 🎓 Academic Evaluation System

A professional **C++** console program to evaluate a student's academic performance based on three grades and the number of absences.  
It calculates the **average score**, applies **penalty** for absences, and determines the **final result** with a mention.

---

## ✅ Features

- 📥 Input student information (full name, ID, scores, absences).
- 📊 Calculates the average score.
- 🏷️ Assigns a mention based on the average.
- ⚠️ Applies penalties for absences.
- 🎯 Displays final score and pass/fail status.
- 💻 Clean and formatted console output.

---

## 🔍 Sample Output

```

\===============================================
Academic Evaluation System
==========================

Enter full name: Bilal Kalss
Enter student ID: 1258
Enter score 1: 70
Enter score 2: 85
Enter score 3: 90
Enter number of absences: 3
===========================

Student Name      : Bilal Kalss
Student ID        : 1258
Average Score     : 81.67
Mention           : Very Good
Absence Penalty   : 6 points
Final Score       : 75.67
Status            : Passed

\===============================================

```

---

## 🧠 How It Works

- **Average calculation**:
```

average = (score1 + score2 + score3) / 3.0

```

- **Absence penalty**:
```

penalty = absences \* 2

```

- **Final score**:
```

finalScore = average - penalty

```

- **Pass/Fail check**:
```

passed = finalScore >= 50

```

---

## 🛠️ Future Improvements

- Allow evaluating multiple students in a loop.
- Store results in a file.
- Use `struct` or `class` for cleaner organization.
- Build a simple GUI using C++ frameworks.

---

## 💻 Requirements

- C++ compiler (e.g., GCC, Clang, MSVC).
- IDE or editor (e.g., Visual Studio, Code::Blocks, VS Code).

---

## 👨‍💻 Author

Developed by **Bilal Kalss** as part of a self-learning C++ challenge.

---
```


