# To-Do List Application

A simple, functional to-do list application with local storage functionality. All tasks are automatically saved to your browser's local storage and will persist even after closing the browser.

## Features

- ✅ **Add Tasks** - Quickly add new tasks to your list
- ✅ **Mark Complete** - Click to toggle task completion status
- ✅ **Delete Tasks** - Remove individual tasks from your list
- ✅ **Local Storage** - All tasks are saved automatically and persist across sessions
- ✅ **Clear Completed** - Remove all completed tasks at once
- ✅ **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- ✅ **Input Validation** - Prevents empty tasks from being added

## How to Use

1. Open `index.html` in your web browser
2. Type a task in the input field
3. Click "Add Task" or press Enter to add it to your list
4. Click a task to mark it as complete (it will get a strikethrough)
5. Click the trash icon to delete a task
6. Use "Clear Completed" to remove all completed tasks
7. All changes are automatically saved to local storage

## Files

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive design
- `app.js` - JavaScript logic and local storage management
- `README.md` - This file

## Browser Compatibility

Works on all modern browsers that support:
- ES6 JavaScript
- Local Storage API
- CSS Flexbox

## Technical Details

### Local Storage

Tasks are stored as a JSON array in the browser's local storage under the key `todos`. The data structure is:

```javascript
[
  {
    id: unique_timestamp,
    text: "Task description",
    completed: false,
    createdAt: timestamp
  }
]
```

### No Dependencies

This application uses vanilla JavaScript with no external libraries or frameworks, making it lightweight and fast.
