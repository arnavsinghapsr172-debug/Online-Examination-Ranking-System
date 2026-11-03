# 🎓 Online Examination Ranking System

### 💻 Data Structures Project | C++

<p align="center">
  <img src="https://img.shields.io/badge/Language-C++-blue?style=for-the-badge&logo=cplusplus" />
  <img src="https://img.shields.io/badge/Data%20Structure-Max%20Heap-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Data%20Structure-Hash%20Table-green?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Project-Academic-purple?style=for-the-badge" />
</p>

---

## 📌 About The Project

The **Online Examination Ranking System** is a menu-driven, console-based application developed in **C++**.

The system manages student examination records and generates a **merit list based on marks**. It combines two important data structures:

- 🏆 **Max Heap** – maintains priority based on student marks.
- 🔍 **Hash Table** – provides efficient student record lookup using Student ID.

The project demonstrates how multiple data structures can work together to solve a practical examination result-management problem.

---

## ✨ Features

| Feature | Description |
|---|---|
| ➕ Add Student | Add student ID, name and examination marks |
| 🔍 Search Student | Search records using Student ID |
| 📋 Display Students | Display all stored student records |
| 🏆 Merit List | Generate ranking in descending order of marks |
| 🥇 Top 3 Scorers | Display the three highest-scoring students |
| 🚫 Duplicate Validation | Prevent duplicate Student IDs |
| ✅ Marks Validation | Accept marks only between 0–100 |

---

## 🧠 Data Structures Used

### 🏆 Max Heap

A **Max Heap** is used to maintain students according to their examination marks.

The student with the highest marks is maintained at the root of the heap.

```text
             98
            /  \
          95    91
         /  \
       85    78
