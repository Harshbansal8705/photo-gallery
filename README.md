# Photo Gallery Web App Frontend [🌐](https://photo-gallery-6hjw.onrender.com)

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This repository contains the frontend for the Photo Gallery Web App, a React application that allows users to upload, view, delete, and download multiple photos at once. The application features multiselect functionality for ease of use. The application is hosted live at [photo-gallery-6hjw.onrender.com](https://photo-gallery-6hjw.onrender.com).

## Features
- Upload multiple photos simultaneously
- View photos in a gallery
- Download and Delete multiple photos with multiselect
- Responsive design

## Technologies
- React

## Installation
To set up this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/harshbansal8705/photo-gallery.git
    cd photo-gallery
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file and add the necessary environment variables:
    ```plaintext
    REACT_APP_BACKEND_URL = <your-backend-api-url>
    ```

4. Start the development server:
    ```bash
    npm start
    ```

## Usage
1. Ensure your backend server is running and accessible. Head over to the [backend repository](https://github.com/Harshbansal8705/photo-gallery-api) for instructions on setting up the backend.
2. Start the frontend development server:
    ```bash
    npm start
    ```
3. Open [http://localhost:3000](http://localhost:3000) in your browser to use the application locally.

## Project Structure
```plaintext
photo-gallery/
├── public/
│   └── ...
├── src/
│   ├── MyComponents/
│   ├── App.js
│   └── ...
├── .gitignore
├── README.md
├── package-lock.json
└── package.json
```

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
