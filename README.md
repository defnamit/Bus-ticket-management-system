# 🚌 Bus Ticket Management System

A Python-based Bus Ticket Management System integrated with MySQL for managing passenger ticket records efficiently.

This project allows users to add, modify, search, display, and delete passenger records through a menu-driven command-line interface.

---

## ✨ Features

✅ Add Passenger Records  
✅ Delete Existing Records  
✅ Search Passenger Details  
✅ Modify Passenger Information  
✅ Display All Records  
✅ MySQL Database Integration  
✅ Menu-Driven CLI Interface

---

## 🛠️ Tech Stack

- Python
- MySQL
- MySQL Connector for Python

---

## 📂 Project Structure

```txt
Bus-Ticket-Management-System/
│── main.py
│── README.md
│── requirements.txt
│── database.sql
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/bus-ticket-management-system.git
cd bus-ticket-management-system
```

### 2. Install Dependencies

```bash
pip install mysql-connector-python
```

Or install from requirements file:

```bash
pip install -r requirements.txt
```

---

## 🗄️ Database Setup

Create a MySQL database:

```sql
CREATE DATABASE busfaremgmt_sys;
```

Use the database:

```sql
USE busfaremgmt_sys;
```

Create the required table:

```sql
CREATE TABLE BUS_LOGS(
    pname VARCHAR(50),
    pid VARCHAR(20),
    start VARCHAR(50),
    stop VARCHAR(50),
    b_date DATE,
    fare INT
);
```

---

## ▶️ How to Run

Run the Python file:

```bash
python main.py
```

---

## 📌 Functionalities

### Add Record
Add passenger details including:
- Passenger Name
- Passenger ID
- Boarding Station
- Destination Station
- Travel Date
- Ticket Fare

### Search Record
Search passengers using:
- Name
- Passenger ID
- Boarding Station
- Destination Station
- Date of Trip
- Fare

### Modify Record
Update:
- Passenger Name
- Boarding Station
- Destination Station
- Date of Travel
- Fare

### Delete Record
Delete records by:
- Passenger Name
- Passenger ID
- Boarding Date

### Display Records
View all passenger ticket records stored in the database.

---

## 📸 Sample Menu

```txt
MENU ===>

1. ADD A RECORD
2. DELETE A RECORD
3. DISPLAY ALL RECORDS
4. SEARCH A SPECIFIC RECORD
5. MODIFY A RECORD
6. QUIT
```

---

## 🚀 Future Improvements

- GUI Interface using Tkinter
- Login Authentication
- Bus Seat Booking System
- Fare Calculation Automation
- Better Error Handling
- Report Generation

---

## ⚠️ Note

Update the MySQL credentials inside the code before running:

```python
mysql = myc.connect(
    host="localhost",
    user="root",
    password="your_password",
    database="busfaremgmt_sys"
)
```

---

## 👨‍💻 Author

**Namit**  
Python & Machine Learning Enthusiast
