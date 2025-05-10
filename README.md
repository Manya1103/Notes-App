# Notes App

A simple web-based notes application that allows users to create, edit, and delete notes. The app uses `localStorage` to save notes, ensuring they persist even after the browser is closed.

## Features

- **Create Notes**: Add new notes by clicking the "Create Notes" button.
- **Edit Notes**: Click on a note to edit its content directly.
- **Delete Notes**: Remove notes by clicking the delete icon.
- **Persistent Storage**: Notes are saved in the browser's `localStorage` and automatically loaded when the app is reopened.

## Technologies Used

- **HTML**: Structure of the application.
- **CSS**: Styling and layout of the app.
- **JavaScript**: Functionality for creating, editing, deleting, and saving notes.

## Project Structure
Notes-App/
├── README.md         # Project documentation
├── index.html        # Main HTML file
├── styles.css        # CSS file for styling
├── script.js         # JavaScript file for app functionality
├── images/           # Folder containing icons
│   ├── delete.png    # Icon for deleting notes
│   ├── edit.png      # Icon for the "Create Notes" button
│   └── notes.png     # Icon for the app title
## How to Use
1. Open `index.html` in a web browser.
2. Click the "Create Notes" button to add a new note.
3. Edit the note by clicking on it and typing.
4. Delete a note by clicking the trash icon.
5. Notes are automatically saved and will reappear when you reopen the app.

## Live Demo

Try the application live [here](https://manya1103.github.io/Notes-App/).

## Future Enhancements

- Add support for categorizing notes.
- Implement a search feature to find notes quickly.
- Allow users to sort notes by creation date or title.
- Add the ability to password-protect notes for enhanced privacy.

## License

This project is open-source and available under the [MIT License](LICENSE).