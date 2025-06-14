# 🧮 SQL Playground by rh3xp

A fun, interactive, browser-based SQL editor built with `sql.js`, `CodeMirror`, and HTML5. This tool lets you write, run, and experiment with SQL in a local sandboxed environment — no backend required!

---

## 🚀 Features

- 🔐 **Login System**
  Enter a name to start using your personal SQL playground. Your session, including query history, is stored using `localStorage`.

- 🧠 **Syntax Highlighting**
  Powered by [CodeMirror](https://codemirror.net/) for rich, SQL-aware editing experience.

- 🧾 **Live Query Execution**
  Type SQL and run it instantly on the in-browser SQLite engine.

- 📜 **Query History**
  Automatically stores your last 10 queries for each user session.

- 🛠️ **Demo Database**
  Pre-loaded tables:
  - `users` (id, name, age)
  - `orders` (id, user_id, product)
  - `products` (id, name, price)

- 🎓 **Built-in Tutorials**
  Tabs showing SQL syntax for `SELECT`, `INSERT`, and `JOIN` with examples and diagrams.

- 🧬 **Schema Visualizer**
  View current schema and table definitions at any time.

- 🏗️ **Custom Table Builder**
  Create your own tables using simple input fields (name and columns).

- 🔄 **Reset DB**
  Wipe and restore the demo database with one click.

---

## 🧪 Technologies Used

- [`sql.js`](https://github.com/sql-js/sql.js) – SQLite compiled to WebAssembly
- [`CodeMirror`](https://codemirror.net/) – Code editor in the browser
- Vanilla JS, HTML5, and CSS (no frameworks)

---

## 📂 Project Structure

- `index.html` – All-in-one HTML app
- Self-contained frontend, can be hosted on:
  - GitHub Pages
  - Bolt IoT WiFi chip
  - Any static file server

---

## 🔐 Data & Privacy

This project uses only `localStorage`. No data is sent to a server. All changes and history are stored on your own device.

---

## 📸 Screenshots (Optional)

> Add screenshots of the SQL editor, schema viewer, and query history section here.

---

## 👨‍💻 Made By

**rh3xp** – I explore rabbit holes 🕳️, love automation, local tools, and building cool web-native projects.
_“Made with ❤️ and local SQLite magic”_

---
