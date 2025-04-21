# ImageCommentingApp

# Image Commenting App

A simple ReactJS app that allows users to add and view comments under images. Each image has its own independent comment section, with comments saved to and loaded from the browser's localStorage.

## Features

- Displays *2 images* on the page.
- Each image has:
  - A text input for adding comments.
  - An *"Add Comment"* button.
  - A *list of comments* displayed below.
- *Comments are saved to localStorage* to persist across page reloads.
- *Functional components* and *React Hooks (useState, useEffect)* are used.

## Technologies Used

- ReactJS
- JavaScript (ES6+)
- HTML/CSS
- Local Storage API

## Functionality

- Each image maintains a separate comment list.
- On clicking "Add Comment":
  - The comment is saved under the corresponding image.
  - The updated comment list is stored in localStorage.
- On page reload:
  - Comment lists are fetched from localStorage.
