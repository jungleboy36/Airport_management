# 🛫 Airport Management System

A full-featured **JavaFX desktop application** for managing airports, flights, reservations, and clients.  
Built with Java and FXML, this project demonstrates desktop GUI design, modular code structure, and data management for a small-scale airport management system.

---

## 🧩 Architecture & Structure

This project is structured around JavaFX and Maven:

### 🖥 Frontend / GUI
- Built entirely with **JavaFX** using `.fxml` layout files
- Styled with `.css` files for a clean, modern interface
- Screens include:
  - Login (`FXMLDocument1.fxml`)  
  - Dashboard (`dashboard.fxml`)  
  - Flight management  
  - Reservation management  
  - Client & Employee management  

### 🔧 Backend / Logic
- Written in **Java**
- Modularized by entity:
  - `Vol` / `VolData` → Flight data  
  - `Reservation` / `ReservationData` → Reservations  
  - `Client` → Clients  
  - `EmployeeData` → Employees  
  - `Escale` / `EscaleData` → Stopovers  
- `database.java` & `getData.java` handle data persistence  
- `EnvoyerEmail.java` handles sending emails from the app  

### ⚙️ Build System
- **Maven** for dependencies, compilation, and project management
- Standard Maven structure (`src/main/java`, `src/main/resources`)

---

## 🚀 Key Features

- 🔐 Login and authentication  
- 📋 Dashboard overview for flights, reservations, and clients  
- ✏️ Add / edit / delete flights, reservations, and clients  
- 🗂 Employee management  
- 🛬 Manage stopovers (`Escale`)  
- 📧 Email notifications for reservations  
- 🎨 Styled GUI using FXML + CSS for an intuitive interface  

---

## 📌 Status

- **Archived learning project**
- Fully functional as a **desktop JavaFX app**
- Environment may need local setup to run (JDK + Maven required)
- Kept as a reference for **code quality, modular design, and GUI development**

---

## 🛠 Tech Stack

| Layer      | Technology |
|------------|------------|
| Frontend   | JavaFX (FXML + CSS) |
| Backend    | Java (object-oriented, modular) |
| Build      | Maven |
| Additional | Email notifications, local database integration |

---

## 📚 What this demonstrates

This project highlights:

- Designing a modular JavaFX desktop application  
- Building CRUD functionality for multiple entities  
- Integrating GUI with backend logic  
- Using Maven for structured project management  
- Implementing email notifications and basic persistence  

---

## 📌 Notes for Recruiters

> ⚠️ This is a desktop application intended for learning and demonstration.  
> Dependencies may need updating to run in current environments.  
> The repo demonstrates **JavaFX GUI design, modular code, and full desktop app architecture**.
