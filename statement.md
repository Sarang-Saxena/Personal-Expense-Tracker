# Project Statement: Personal Expense Tracker

##  Problem Statement
Managing daily personal finances is challenging without a dedicated routine. Most people incur multiple small daily expenses that go unrecorded, leading to poor financial awareness and budgeting issues. Existing solutions are often over-engineered, requiring cloud accounts, complex interfaces, and persistent internet access. This project provides a lightweight, offline, and distraction-free Java console tool to log, track, and aggregate daily spending efficiently.

---

##  Scope of the Project

### In-Scope
* Adding expenses with amount, category, date, and description.
* Displaying all stored expenses in an aligned tabular console format.
* Deleting specific entries by record number with validation checks.
* Calculating total cumulative expenditure automatically.
* Local persistent storage using flat-file I/O (`data.txt`).

### Out-of-Scope
* Graphical User Interface (GUI).
* Multi-currency conversion or live exchange rates.
* Multi-user profiles and cloud synchronization.
* Advanced visual charts and predictive analytics.

---

##  Target Users
* **Students & Young Adults:** Tracking daily pocket money, meals, and travel expenses.
* **Minimalist Users:** Anyone preferring fast CLI utilities over heavy mobile/web apps.
* **Privacy-Conscious Individuals:** Users who want their financial logs stored entirely offline on local disk.
* **Beginner Developers:** Learners exploring core Java OOP, Collections, and File I/O workflows.

---

##  High-Level Features

| Feature | Description |
| :--- | :--- |
| **Interactive Menu** | Simple numeric menu loop for quick navigation. |
| **Expense Logging** | Step-by-step console prompts for transaction details. |
| **Tabular Output** | Clean ASCII table layout using `System.out.printf`. |
| **Safe Deletion** | Bounds-checked record removal using list indices. |
| **Auto Total** | Instant summation of all active expenditures. |
| **Data Persistence** | Automatic read on startup and save on exit using `data.txt`. |
