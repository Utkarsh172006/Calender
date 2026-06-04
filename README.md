# ***Calendar Reminder***

## Overview

CalendarReminder is a Java console-based application that enables users to create, store, and manage reminders for specific calendar dates. The project demonstrates fundamental Java programming concepts, including arrays, user input handling, conditional statements, loops, and switch-case logic.

The application provides a simple menu-driven interface for managing reminders and is designed as a beginner-friendly project for learning core Java concepts.

---

## Features

### Add Reminders

* Create reminders for specific dates
* Enter day, month, and year information
* Store custom reminder messages

### View Reminders

* Display all saved reminders
* View reminder messages along with their associated dates

### Menu-Driven Interface

* Simple and interactive console-based navigation
* Easy-to-use options for managing reminders

### Fixed-Size Storage

* Supports storage of up to 100 reminders
* Uses arrays for data management

### Exit Application

* Gracefully terminate the program through the menu system

---

## Technology Stack

| Component            | Technology                |
| -------------------- | ------------------------- |
| Programming Language | Java                      |
| Runtime Environment  | Java SE                   |
| Interface            | Console-Based Application |
| Data Storage         | Arrays                    |

---

## How It Works

### Menu Options

#### 1. Add a Reminder

Allows users to create a new reminder by entering:

* Day (1–31)
* Month (1–12)
* Year
* Reminder message

Example:

```text
Enter Day: 15
Enter Month: 7
Enter Year: 2025
Enter Reminder: Doctor appointment at 5 PM
```

#### 2. View Reminders

Displays all stored reminders along with their corresponding dates.

Example:

```text
15/07/2025 - Doctor appointment at 5 PM
20/07/2025 - Project submission
```

#### 3. Exit

Terminates the application safely.

---

## Project Structure

```text
CalendarReminder/
│
├── CalendarReminder.java
├── README.md
│
└── Compiled Class Files
```

---

## Getting Started

### Prerequisites

* Java JDK 8 or higher

### Compile the Program

```bash
javac CalendarReminder.java
```

### Run the Program

```bash
java CalendarReminder
```

---

## Sample Workflow

1. Launch the application.
2. Select the "Add Reminder" option.
3. Enter the date and reminder message.
4. Save multiple reminders as needed.
5. Use the "View Reminders" option to display all stored reminders.
6. Select "Exit" to close the application.

---

## Learning Outcomes

This project demonstrates:

* Java Fundamentals
* Arrays and Data Storage
* User Input Handling
* Conditional Statements
* Loops
* Switch-Case Implementation
* Console-Based Application Development

---

## Limitations

* Reminders are stored only during program execution.
* Data is not persisted after the application closes.
* Maximum storage capacity is limited to 100 reminders.
* No reminder editing or deletion functionality.

---

## Author

Utkarsh Kumar Srivastava
