# To-Do List App

A modern, lightweight To-Do application built with HTML, CSS, and JavaScript. Features task management with local storage persistence, progress tracking, and a celebratory confetti effect when all tasks are completed.

## Features

- **Add Tasks** - Quickly add new tasks to your list
- **Mark as Complete** - Check off tasks as you finish them
- **Edit Tasks** - Modify existing tasks
- **Delete Tasks** - Remove tasks from your list
- **Progress Tracking** - Visual progress bar showing completion percentage
- **Task Counter** - Live count of completed vs total tasks
- **Local Storage** - Your tasks persist even after closing the browser
- **Confetti Celebration** - Auto celebratory animation when all tasks are completed

## Screenshots

![To-Do App Interface](screenshots/app.png)

## How to Use

1. Open `index.html` in your web browser
2. Type your task in the input field
3. Click the "+" button or press Enter to add it
4. Check the box to mark a task as complete
5. Click the edit icon to modify a task
6. Click the delete icon to remove a task

## Tech Stack

- **HTML5** - Structure
- **CSS3** - Styling with custom properties for theming
- **JavaScript (ES6+)** - Application logic
- **Local Storage API** - Data persistence
- **@tsparticles/confetti** - Celebration effect

## Customization

The app uses CSS custom properties for easy theme customization:

```css
:root {
    --background: #000430;
    --secondaryBackground: #171c48;
    --text: #fff;
    --purple: #828dff;
    --teal: #24feee;
}
```

## License

This project is open source and available under the MIT License.
