# 🚆 Railway Reservation System

## 📌 Project - 2

A **Railway Reservation System** developed in **C++** using Object-Oriented Programming concepts.

The system allows users to add train records, display all train records, and search for a train using its train number.

---

## 🎯 Project Objective

The project demonstrates the use of:

* Classes and Objects
* Constructors
* Destructors
* Static Members
* Arrays of Objects
* Getters and Setters
* Encapsulation
* Menu-driven programming

---

## ✨ Features

1. Add New Train Record
2. Display All Train Records
3. Search Train by Number
4. Exit the System

Each train record contains:

* Train Number
* Train Name
* Source
* Destination
* Train Time

---

## 🏗️ Classes Used

### Train Class

The `Train` class contains the details of each train.

**Data Members:**

```text
trainNumber
trainName
source
destination
trainTime
```

**Static Member:**

```text
trainCount
```

**Constructors:**

* Default Constructor
* Parameterized Constructor

**Other Functions:**

* `inputTrainDetails()`
* `displayTrainDetails()`
* `getTrainCount()`
* Getters and Setters

---

### RailwaySystem Class

The `RailwaySystem` class manages multiple train records using an array of objects.

```cpp
Train trains[100];
```

It provides:

* `addTrain()`
* `displayAllTrains()`
* `searchTrainByNumber()`

These class requirements are specified in the project instructions.

---

# 🖥️ Program Output Screenshots

## 1️⃣ Main Menu

![Main Menu](screenshots/menu.png)

---

## 2️⃣ Adding Train Record

![Adding Train](screenshots/add-train.png)

Example:

```text
Enter Train Number: 101
Enter Train Name: Okha Express
Enter Source: Surat
Enter Destination: Mumbai
Enter Train Time: 10 AM

Train record added successfully!
```

---

## 3️⃣ Displaying Train Records

![Display Train Records](screenshots/display-trains.png)

Example:

```text
Train 1 details:
Train Number: 101
Train Name: Okha Express
Source: Surat
Destination: Mumbai
Train Time: 10 AM
```

---

## 4️⃣ Searching for a Train

![Search Train](screenshots/search-train.png)

Example:

```text
Enter Train Number to search: 101

Train found!

Train Number: 101
Train Name: Okha Express
Source: Surat
Destination: Mumbai
Train Time: 10 AM
```

---

## 5️⃣ Train Not Found

![Train Not Found](screenshots/train-not-found.png)

Example:

```text
Enter Train Number to search: 104

Train with number 104 not found!
```

---

## 6️⃣ Exit

![Exit](screenshots/exit.png)

Example:

```text
Exiting the system. Goodbye!
```

The required menu and example outputs are given in the project document.

---

# 🎥 Explanation Video

Click the link below to watch the explanation video of the project:

👉 **[🎬 Watch Project Explanation Video on Google Drive](PASTE-YOUR-GOOGLE-DRIVE-LINK-HERE)**

### Video Contents

The explanation video covers:

1. Project introduction
2. `Train` class
3. Data members
4. Constructors
5. Destructor
6. Static member
7. Getters and Setters
8. `RailwaySystem` class
9. Array of objects
10. Menu-driven system
11. Adding train records
12. Displaying train records
13. Searching for a train
14. Program output

---

# 📁 Project Structure

```text
Railway-Reservation-System/
│
├── RailwayReservation.cpp
├── README.md
│
└── screenshots/
    ├── menu.png
    ├── add-train.png
    ├── display-trains.png
    ├── search-train.png
    ├── train-not-found.png
    └── exit.png
```

---

# 💻 Technologies Used

* **Language:** C++
* **Concept:** Object-Oriented Programming
* **IDE/Compiler:** C++ Compiler
* **Repository:** GitHub
* **Video:** Google Drive

---

# 👨‍💻 Project Information

**Project:** Railway Reservation System
**Project Number:** 2
**Programming Language:** C++
**Project Type:** Individual Project

---

# ✅ Conclusion

This project implements a basic Railway Reservation System using C++ and demonstrates important Object-Oriented Programming concepts such as classes, objects, constructors, destructors, static members, encapsulation, getters, setters, and arrays of objects.

The project follows the required menu-driven approach for adding, displaying, and searching train records.

```

### One important thing

When you upload your video to Google Drive:

**Share → General access → Anyone with the link → Viewer → Copy link**

Then replace:

`PASTE-YOUR-GOOGLE-DRIVE-LINK-HERE`

with your actual link.

And bro, **if you send me your screenshots + Google Drive link**, I can make the README look much more professional and arrange exactly where each screenshot/video link should go. 🚆💻
```
