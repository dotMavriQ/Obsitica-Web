# Obsitica-Web

Obsitica-Web is a web service that allows you to export your Habits, ToDo's, and Dailies from Habitica into a format suitable for journaling in Obsidian. This tool helps streamline your habit tracking and journaling process, making it easier to keep track of your progress and stay organized.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)

## Features
- Export Habits, ToDo's, and Dailies from Habitica.
- Generate a formatted output compatible with Obsidian.
- Simple and user-friendly interface.

## Installation
To get started with Obsitica-Web, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/dotmavriq/obsitica-web.git
    ```
2. Navigate to the project directory:
    ```bash
    cd obsitica-web
    ```
3. Install the required dependencies:
    ```bash
    npm install
    ```

## Usage
To use Obsitica-Web, follow these steps:

1. Start the web server:
    ```bash
    npm start
    ```
2. Open your browser and navigate to:
    ```
    http://localhost:3000
    ```
3. Follow the instructions on the web interface to connect your Habitica account and export your data.

4. Copy the formatted output and paste it into your Obsidian journal.

## Configuration
To configure Obsitica-Web, you can modify the following settings in the `config.json` file:

- `habitica_api_url`: The API endpoint for Habitica.
- `output_format`: Customize the format of the exported data to suit your journaling style.

## Contributing
We welcome contributions to Obsitica-Web! If you would like to contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix:
    ```bash
    git checkout -b feature-name
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add feature-name"
    ```
4. Push your changes to your fork:
    ```bash
    git push origin feature-name
    ```
5. Create a pull request and describe your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
