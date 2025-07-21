# 🚗 Smart Car Parking System using Arrays

A smart car parking lot management application built using **C**, focusing on **array-based structures**. This project simulates real-world parking operations including vehicle registration, space allocation, membership tracking, revenue generation, and slot management.

---

## 🔧 Features

- Register new or returning vehicles with full owner details
- Allocate parking space based on membership level
- Calculate total parking hours and charges
- Manage Gold, Premium, and Non-member benefits
- Update and upgrade membership levels based on parking hours
- Maintain and update parking space status (Free/Occupied)
- Sort and view:
  - Vehicles by number of parkings
  - Vehicles by total revenue generated
  - Parking spaces by frequency of use
  - Parking spaces by revenue generated
- File handling (`data.txt`) for persistent data storage
- Implemented using **arrays of structures** for both vehicles and parking slots

---

## 🧠 Project Summary

This C project models a real-world smart parking system using **arrays** to store and manage vehicle and parking slot data. Vehicles are tracked by their number, entry/exit times, parking history, and revenue. The parking lot intelligently assigns slots based on membership and updates all data dynamically.

---

## 📌 Allocation Policy

| Membership | Slot Range | Description             |
|------------|------------|-------------------------|
| Golden     | 1–10       | Highest priority        |
| Premium    | 11–20      | Next best slots         |
| None       | 21–50      | Allocated first available |

---

## 🎖 Membership Policy

| Membership | Total Parking Hours |
|------------|---------------------|
| None       | < 100 hours         |
| Premium    | ≥ 100 hours         |
| Golden     | ≥ 200 hours         |

---

## 💰 Payment Policy

| Duration           | Charges             |
|--------------------|---------------------|
| First 3 hours      | ₹100                |
| After 3 hours      | ₹50 per extra hour  |
| Membership Discount| 10% on total charge |

---

## 🧪 Technologies Used

- C Programming Language (GCC)
- Arrays of Structures
- File Handling
- Time Handling (`<time.h>`)
- Quicksort (for sorting vehicles and slots)
- Command-Line Interface (CLI)

---



