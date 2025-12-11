# Deadlock Prevention & Recovery Toolkit (C++)

This project implements a complete Operating System simulation for **Deadlock Prevention, Detection, and Recovery**.  
It includes **Banker's Algorithm**, **Resource Allocation Graph (RAG) Deadlock Detection**, and **Process Termination Recovery**.

This repository is created as part of the Operating Systems project.

---

## 📘 Features

✔ **Safe State Check** using Banker's Algorithm  
✔ **Need Matrix Calculation**  
✔ **Resource Request Algorithm**  
✔ **Rollback if Unsafe**  
✔ **Deadlock Detection using RAG cycle detection**  
✔ **Deadlock Recovery by terminating a process**  
✔ **Simulation of multiple operations**  
✔ Fully modular C++ implementation  

---

## 📁 Repository Structure

```
deadlock-prevention-toolkit/
│
├── src/
│   └── deadlock.cpp
│
├── docs/
│   ├── Report.md
│   ├── Flowchart.png
│   └── Viva_Questions.md
│
├── README.md
└── .githubignore
```

---

## 🔧 How to Compile

Run this command:

```bash
g++ src/deadlock.cpp -o deadlock
```

---

## ▶️ How to Run

```bash
./deadlock
```

---

## 📥 Input Format

You need to enter:

1️⃣ Number of processes  
2️⃣ Number of resources  
3️⃣ **MAX matrix**  
4️⃣ **ALLOCATION matrix**  
5️⃣ **AVAILABLE vector**

Example:

```
3 3
7 5 3
3 2 2
9 0 2
0 1 0
2 0 0
3 0 2
3 3 2
```

---

## 🖥 Menu Options in Program

The program shows this menu:

```
1. Check Safe State
2. Request Resources
3. Detect Deadlock
4. Exit
```

---

## 🧠 Algorithms Used

### ✔ Banker's Algorithm
Used for:
- Safe state check  
- Granting or denying requests  

### ✔ RAG (Resource Allocation Graph)
Used for:
- Detecting cycles  
- Identifying deadlocked processes  

### ✔ Deadlock Recovery
Method used:
- Terminating a selected process (P0 in this simulation)  
- Releasing its resources  

---

## 📄 Documentation

All project documentation is inside:

```
docs/Report.md
```

---

## 👤 Author

**Vani Bhardwaj**
**Riya Verma**
Roll No: RK24PRA11 
Roll No: RK24PRA10
Operating Systems – Project Submission  

---

## ⭐ Support

Feel free to ⭐ star this repository if it helped you!
