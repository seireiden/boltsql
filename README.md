# 💾 SQL Playground

A lightweight, in-browser SQL interpreter built using [sql.js](https://github.com/sql-js/sql.js), designed for quick practice, learning, and fun — entirely offline and without any backend!

Made by **[rh3xp](https://github.com/rh3xp)** | Powered by WebAssembly and Vanilla JS.

---

## 🚀 Features

- **🔐 User Login**
  Simple username-based login using `localStorage`. Tracks session state per user.

- **🧠 Built-in Demo Database**
  Preloaded tables:
  - `users (id, name, age)`
  - `orders (id, user_id, product)`
  - `products (id, name, price)`

- **📦 SQL Execution Engine**
  Uses `sql.js` (SQLite compiled to WebAssembly) to run raw SQL commands entirely in the browser.

- **🧪 Query Editor**
  - Syntax-agnostic text area
  - Real-time output in an HTML table
  - Instant feedback for syntax errors

- **🔄 Reset DB**
  Reinitialize the demo database in a single click.

- **📚 SQL Tutorial Tabs**
  Interactive tabbed sections to learn:
  - `SELECT`
  - `INSERT`
  - `JOIN`
  With syntax, descriptions, and **mini visual diagrams**.

---

## 🌐 Hosting

This is a single HTML file. Just drag & drop into any browser or upload to:
- GitHub Pages
- Bolt IoT static server
- Netlify / Vercel
- Raspberry Pi kiosk screen

---

## 📷 Screenshots

> _(Optional: Add screenshots of the interface, query output, and tutorial tabs here.)_

---

## 📁 Project Structure

```text
sql-playground/
├── index.html         # Single self-contained SQL editor
├── README.md          # You're reading it
