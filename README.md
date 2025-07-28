# NotesTaking

A simple note-taking web app built with Node.js, Express, and EJS.

## Features

- Create new notes with a title and content
- View a list of all notes
- View the content of each note

## Project Structure

```
NotesTaking/
├── files/           # Stores all note files
├── public/          # Static assets (CSS, JS, etc.)
├── views/           # EJS templates
│   ├── index.ejs
│   └── show.ejs
├── index.js         # Main server file
└── README.md
```

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/NotesTaking.git
   cd NotesTaking
   ```

2. **Install dependencies:**
   ```sh
   npm install
   ```

3. **Create a `files` directory if it doesn't exist:**
   ```sh
   mkdir files
   ```

4. **Start the server:**
   ```sh
   node index.js
   ```

5. **Open your browser and visit:**
   ```
   http://localhost:3000
   ```

## Usage

- Click "Go Back To Home" to see all notes.
- Click on a note to view its content.
- Use the form on the home page to create a new note.

## License

MIT
