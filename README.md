# Note Taker App

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

## Description

The Note Taker app is a simple web application that allows users to write, save, and delete notes. It uses an Express.js back end and saves and retrieves note data from a JSON file. This application is designed for anyone who needs a quick and easy way to manage their daily tasks or thoughts.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Routes](#routes)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

To run this application locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/note-taker-app.git
    ```

2. Navigate to the project folder:
    ```bash
    cd note-taker-app
    ```

3. Install the necessary dependencies:
    ```bash
    npm install
    ```

4. Start the application:
    ```bash
    npm start
    ```

The app will run on `http://localhost:3001` by default.

## Usage

To use the Note Taker app:

1. Open the app in your browser by visiting the hosted URL or by running the app locally at `http://localhost:3001`.
2. Click on the "Get Started" button.
3. Add a new note by typing in a title and description.
4. Click the save icon to save the note.
5. You can view, delete, or create new notes as needed.

## Routes

### API Routes

- `GET /api/notes`: Retrieves all saved notes as JSON.
- `POST /api/notes`: Saves a new note and returns the note.
- `DELETE /api/notes/:id`: Deletes a note by `id`.

### HTML Routes

- `GET /notes`: Returns the notes.html file.
- `GET *`: Returns the index.html file for all other routes.

## Screenshots

![Screenshot of the Note Taker app]()

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

