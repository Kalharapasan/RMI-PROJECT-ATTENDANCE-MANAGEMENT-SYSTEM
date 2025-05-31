
# 📡 Attendance Management System (Java RMI)

A network-based **Attendance Management System** developed using **Java RMI (Remote Method Invocation)**. This system demonstrates distributed communication between client and server to manage student attendance in real-time.

---

## ✨ Features

- 📶 Client-server architecture using Java RMI
- 🧑‍🎓 Mark and view student attendance
- 📅 Track date-wise attendance
- 🧾 Simple authentication and role-based UI
- 💾 Data persistence using local files or database (optional)

---

## 🛠️ Tech Stack

- **Language**: Java
- **Architecture**: Java RMI (Remote Method Invocation)
- **UI**: Swing / AWT (based on implementation)
- **Storage**: In-memory / file-based / DB (depending on version)
- **IDE**: NetBeans / IntelliJ / Eclipse

---

## 📦 Setup Instructions

### 📁 1. Compile RMI Classes

```bash
# Navigate to your source folder
javac *.java
rmic ServerImplementation
```

### 🚀 2. Start the RMI Registry

```bash
start rmiregistry
```

> ⚠️ Keep this terminal open!

### 🖥️ 3. Run the Server

```bash
java ServerMain
```

### 🧑‍💻 4. Run the Client

```bash
java ClientMain
```

---

## 📁 Project Structure

```
RMI-Attendance-System/
├── ServerMain.java
├── ServerInterface.java
├── ServerImplementation.java
├── ClientMain.java
├── Student.java
├── AttendanceRecord.java
├── utils/                        # (if applicable)
└── README.md
```

---

## ✅ TODO

- [ ] Add GUI for admin & teacher roles
- [ ] Store attendance in a persistent database (e.g., MySQL)
- [ ] Add attendance summary reports
- [ ] Role-based authentication for teachers/students

---

## 🧪 Requirements

- Java 8 or higher
- RMI support enabled (usually default in JDK)
- IDE like NetBeans or IntelliJ recommended for development

---

## 📃 License

This project is licensed under the **MIT License**.

---

> Built with 🛰️ and ❤️ using Java RMI
