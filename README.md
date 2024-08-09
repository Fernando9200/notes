# Notes

This project was built with React and Appwrite. The app allows users to create, update, delete, and manage sticky notes with customizable colors and positions on a web page.

## Features

- Create new sticky notes with default colors and position.
- Drag and drop notes to reposition them.
- Change the color of the notes.
- Automatically save notes' content, position, and colors to the database.
- Delete notes.

## Technologies Used

- **React**: JavaScript library for building user interfaces.
- **Appwrite**: Backend-as-a-Service (BaaS) platform for managing databases, authentication, and more.
- **JavaScript**: Programming language used for app logic.
- **CSS**: Styling the user interface.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Fernando9200/notes.git
   cd notes
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up environment variables:**
   Create a `.env` file in the root of your project and add the following environment variables. Replace the placeholders with your actual Appwrite endpoint, project ID, and collection IDs:
  ```bash
  VITE_ENDPOINT=https://appwrite.io/v1
  VITE_PROJECT_ID=your_project_id
  VITE_DATABASE_ID=your_database_id
  VITE_COLLECTION_NOTES_ID=your_notes_collection_id
   ```
