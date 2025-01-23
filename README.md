# Airline Flight Reservation System

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Project Structure](#project-structure)
4. [Compilation](#compilation)
5. [Usage](#usage)
6. [Contributors](#contributors)
7. [License](#license)

---

## Introduction
The **Airline Flight Reservation System** is a command-line program written in C that allows users to:
- Reserve seats
- View available seats
- Sort and organize seat arrangements
- Manage reservation data

This project is designed for learning purposes, emphasizing modular design and efficient data management.

---

## Features
- **Seat Reservation**: Users can reserve available seats.
- **Sorting**: Organizes seat arrangements based on user preferences.
- **Data Persistence**: Stores reservations in files for future use.
- **Interactive Interface**: Simple and user-friendly command-line interface.

---

## Project Structure
```plaintext
AirlineReservationSystem/
├── src/
│   ├── main.c
│   ├── sort.c
│   ├── seats.c
│   ├── creators.c
│   ├── data.c
│   ├── interface.c
├── include/
│   ├── sort.h
│   ├── seats.h
│   ├── creators.h
│   ├── data.h
│   ├── interface.h
├── build/
├── docs/
│   ├── design_documentation.md
├── Makefile
└── README.md