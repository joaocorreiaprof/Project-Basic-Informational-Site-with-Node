# Node.js Informational Website

This project is a basic informational website built using Node.js. It demonstrates how to serve static HTML pages and handle different routes, including a custom 404 error page.

## Features

- Serve static HTML files.
- Handle routes for:
  - `/` → Home page.
  - `/about` → About page.
  - `/contact-me` → Contact page.
  - Unmatched routes → Custom 404 error page.
- Proper `Content-Type` handling for different file types (e.g., `.html`, `.css`, `.js`).

## Requirements

- [Node.js](https://nodejs.org/) (v14 or later)

## Installation

1. Clone this repository or download the source files.
   ```bash
   git clone <repository-url>
   cd project-folder
   npm install
   ```

## Usage

1. Start de Server

   ```bash
   node index.js

   ```

2. Open your browser and visit:
   - http://localhost:5000/ for the home page.
   - http://localhost:5000/about for the about page.
   - http://localhost:5000/contact-me for the contact page.
   - Any other route to see the custom 404 error page.

## Contributing

Feel free to fork the repository and submit pull requests to improve functionality or add features!

## License

This project is licensed under the MIT License. See the LICENSE file for details.
