# Moment 1 – CV Server

### Av Maamoun Okla

En enkel Node.js-applikation som hanterar kurser i ett CV med **Express**, **EJS** och **SQLite3**.

---

## 🧩 Funktioner

* Visa alla kurser (`/`)
* Lägg till ny kurs (`/addCourse`)
* Radera kurs (`/delete/:id`)
* Om-sida (`/about`)

---

## ⚙️ Installation

1. Klona projektet
2. Kör

   ```bash
   npm install
   npm run install   # Skapar databasen
   npm start         # Startar servern
   ```
3. Öppna: [http://localhost:3001](http://localhost:3001)

---

## 💾 Databas

Tabell: `courses`

| Fält        | Typ                 |
| ----------- | ------------------- |
| id          | INTEGER PRIMARY KEY |
| coursecode  | TEXT                |
| coursename  | TEXT                |
| syllabus    | TEXT                |
| progression | TEXT                |
| posted      | TIMESTAMP           |

---

## 📁 Struktur

```
server.js
install.js
views/
public/
db/cv.db
```

---

## 🧠 Kort info

* View engine: **EJS**
* Statiska filer i `/public`
* Data lagras lokalt i `SQLite`
* Startport: **3001**

---

📅 Senast uppdaterad: 2025-10-23
