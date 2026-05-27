# 📝 Todo App

A clean, minimal, feature-rich todo app built with pure HTML, CSS, and JavaScript. No frameworks, no install needed — just open in any browser.

---

## 🚀 Getting Started

1. Download `todo-app.html`
2. Open it in any browser (Chrome, Firefox, Safari, Edge)
3. That's it — no setup, no install, no internet required after first load

> **Note:** First load requires internet to fetch fonts and icons from CDN. After that it works fully offline.

---

## ✨ Features

### ✅ Task Management
- Add tasks by typing and pressing **Enter** or clicking **+**
- Mark tasks done with the checkbox — shows ✅ when complete
- Delete tasks by hovering and clicking **×**
- Completed tasks automatically move to a **Completed** section at the bottom

### 📌 Pin Tasks
- Hover over any task and click the **pin icon** to pin it
- Pinned tasks always stay at the top in a **Pinned section**
- Click pin again to unpin
- Pinned state is saved and restored on page reload

### 🏷️ Priority, Tags & Due Dates
- Set **priority** when adding a task: High / Medium / Low
- Add a **tag** (e.g. `work`, `personal`) for easy filtering
- Set a **due date** — overdue tasks highlight in red automatically

### 🔍 Search & Filter
- Search bar filters tasks live as you type — matches task text and tags
- Filter buttons: **All / Active / Done / High / Overdue**

### ↕️ Drag to Reorder
- Grab any task card and drag it to reorder your list

### 📊 Progress Bar
- Live progress bar shows percentage of tasks completed
- Animates smoothly as you tick off tasks

### 💾 Auto Save
- All tasks are saved automatically to **localStorage**
- Tasks persist across page refreshes and browser restarts
- Tied to the current browser/device (no account needed)

---

## 📤 Export

| Button | Output |
|--------|--------|
| **TXT** | `tasks.txt` — plain text, one task per line with status, priority, tag, due date |
| **Excel** | `tasks.xlsx` — spreadsheet with columns: Task, Status, Priority, Tag, Due Date |

---

## 📥 Import

Click the **Import** button and select a file:

- `.txt` — must be in the exported TXT format
- `.xlsx` / `.xls` — must match the exported Excel column structure

Imported tasks are **added** to your existing list (nothing is overwritten).

### TXT Format Reference
```
[ ] Buy groceries [low] #personal due:2026-06-01
[x] Submit report [high] #work due:2026-05-25
```

### Excel Column Structure
| A: Task | B: Status | C: Priority | D: Tag | E: Due Date |
|---------|-----------|-------------|--------|-------------|
| Buy groceries | Active | Low | #personal | 2026-06-01 |
| Submit report | Done | High | #work | 2026-05-25 |

---

## 🌗 Dark / Light Mode

The app **automatically follows your device system setting** — no toggle needed.

| Mode | Background | Cards |
|------|-----------|-------|
| Light | Soft grey `#f4f4f5` | White cards |
| Dark | Deep black `#0a0a0a` | Dark grey cards |

To switch: change your OS appearance setting (Windows, macOS, iOS, Android).

---

## ⌨️ Keyboard Shortcut

| Key | Action |
|-----|--------|
| **Enter** | Add task (when typing in the input) |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 | Structure |
| CSS3 | Styling, dark/light mode, animations |
| Vanilla JavaScript | All app logic |
| [DM Sans](https://fonts.google.com/specimen/DM+Sans) | Font (Google Fonts) |
| [Tabler Icons](https://tabler-icons.io/) | UI Icons |
| [SheetJS (xlsx)](https://sheetjs.com/) | Excel export & import |
| localStorage | Data persistence |

---

## 📁 File Structure

```
todo-app.html   ← entire app in one file
README.md       ← this file
```

---

## 🔮 Planned Improvements

- [ ] Edit task inline
- [ ] Undo delete
- [ ] Sort by due date / priority / created date
- [ ] Keyboard shortcuts (N to add, Esc to clear search)
- [ ] Due date time picker
- [ ] Stats & insights panel
- [ ] Supabase login + cloud sync across devices

---

## 📄 License

Free to use for personal and commercial projects. No attribution required.

---

> Built with ❤️ — one HTML file, zero dependencies to install.