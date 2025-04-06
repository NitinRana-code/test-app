# Node Webpage Project

This project is a simple Node.js application that serves a basic webpage. It utilizes Express to serve static files and includes a CSS file for styling and a JavaScript file for client-side functionality.

## Project Structure

```
node-webpage-project
├── public
│   ├── css
│   │   └── styles.css
│   ├── js
│   │   └── script.js
│   └── index.html
├── src
│   └── server.js
├── package.json
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd node-webpage-project
   ```

2. **Install dependencies:**
   ```
   npm install
   ```

3. **Run the server:**
   ```
   npm start
   ```

4. **Access the webpage:**
   Open your browser and navigate to `http://localhost:3000`.

## Usage

- The `public/index.html` file is the main entry point for the webpage.
- The `public/css/styles.css` file contains styles for the webpage.
- The `public/js/script.js` file contains JavaScript for client-side interactions.
- The `src/server.js` file sets up the Express server to serve the static files.

## License

This project is licensed under the MIT License.