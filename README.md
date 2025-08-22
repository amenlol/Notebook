# Notebook

A lightweight, browser-based note-taking app built with HTML, CSS, and vanilla JavaScript. Notes are stored locally in your browser using `localStorage`, so they persist across sessions without any backend.

### Features
- **Quick note creation**: Add new notes with a single click
- **Auto-save**: Changes persist as you type
- **Easy deletion**: Double-click a note to delete it (with confirmation)
- **Responsive layout**: Clean grid-based UI

### Quick Start
1. Clone the repository:
```bash
git clone https://github.com/amenlol/Notebook-main.git
```
2. Open `note.html` in your web browser.

No build step or dependencies required.

### Usage
- Click the `+` button to create a note.
- Type in the note; it saves automatically.
- Double-click a note to remove it (you'll be asked to confirm).

### Project Structure
```
Notebook-main/
├── assets/
│   ├── csss/
│   │   └── note.css       # Styles for the app
│   └── note.js            # App logic (create, update, delete, persist)
├── note.html              # Entry file
└── README.md
```

### How It Works
- Notes are stored in `localStorage` under the key `note-app`.
- Each note has an auto-generated numeric `id` and a `content` string.
- Notes render dynamically and are inserted before the `+` button.

### Browser Support
Modern browsers supporting `localStorage` and standard DOM APIs.

### Author
- GitHub: [`@amenlol`](https://github.com/amenlol)

### License
Provided as-is. If you need a specific open-source license, add a `LICENSE` file (e.g., MIT). 
