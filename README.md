# Node Farm 🌱

A beginner-friendly Node.js project that dynamically serves product data using templates and raw Node.js modules (no frameworks like Express). This project is part of a learning journey to understand how web servers work at a lower level in Node.js.

## 📁 Project Structure

```
starter/
├── dev-data/
│   └── data.json              # Raw product data in JSON format
├── module/
│   └── replaceTemplate.js     # Custom module to replace placeholders in templates
├── templates/
│   ├── template-card.html     # Template for a single product card
│   ├── template-overview.html# Template for the main overview page
│   └── template-product.html  # Template for the individual product page
├── txt/
│   └── *.txt                  # Assorted text files used for filesystem practice
├── index.js                   # Main entry point of the server
└── package.json               # Project metadata and dependencies
```

## 🚀 Features

- Serves three types of routes:
  - `/` or `/overview`: Displays all product cards using dynamic templating.
  - `/product?id=x`: Displays individual product detail page.
  - `/api`: Returns raw JSON data via a RESTful API endpoint.
- Uses custom HTML templates and replaces placeholders manually.
- No external libraries/frameworks – built entirely with core Node.js modules.

## 📦 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Simnsh/node_farm.git
   cd node_farm
   ```

2. **Install dependencies**
   *(This project currently uses only core Node.js modules, so no npm install is needed unless you add packages.)*

3. **Run the server**
   ```bash
   node index.js
   ```

4. **Open your browser**
   ```
   http://localhost:8000
   ```

## 🛠 Technologies Used

- Node.js
  - `fs` for file reading
  - `http` for creating the server
  - `url` for parsing URLs
- HTML (templating with custom placeholder replacement)

## 📚 Learning Objectives

- Understand how to manually build an HTTP server in Node.js
- Learn about routing and URL parsing
- Implement a basic templating system
- Work with synchronous file I/O

## 📄 License

This project is for educational purposes and does not use a specific license.

---

👨‍💻 Made with love while learning Node.js!
