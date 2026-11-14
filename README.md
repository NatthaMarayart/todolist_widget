[README.md](https://github.com/user-attachments/files/34726813/README.md)
# 🌸 — To-do widget for Übersicht

A cute pink to-do list that lives on your Mac desktop and a flower blooms when you finish a task.

## ⬇️ Download

**[Download todo-widget.zip](https://github.com/NatthaMarayart/todolist_widget/raw/main/todo-widget.zip)**

## Install

1. Install **Übersicht** (free): https://tracesof.net/uebersicht/
   If macOS blocks it, right-click the app > **Open**.
2. Click the Übersicht icon in the menu bar > **Open Widgets Folder**.
3. Unzip, then drag the whole **`todo.widget`** folder into that folder.
4. The widget appears in the top-right corner of your screen.

## How to use

| Action | How |
|---|---|
| Add a task | Type and press **Enter** |
| Mark as done | Click the task 🌼 |
| Delete | Hover, then click **✕** |

Your tasks are saved on your own Mac in `~/.todo-widget.json`.

## Customize

Open `todo.widget/index.jsx` in any text editor:

- **Position:** change `top` / `right` near the top of the file
- **Colors:** change the `linear-gradient(...)` line in `box`
- **Flower:** replace `todo.widget/todo-assets/flower-sprite.png`

Requires macOS.
