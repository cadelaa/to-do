Web Development Template

This repository is a customizable and efficient starter template for simple web development projects. It includes SCSS support, live reloading, and a structured workflow to speed up development.

---

my-project/
│── src/
│   ├── index.html        # Main HTML file
│   ├── styles/
│   │   ├── main.scss     # Main SCSS file
│── dist/
│   ├── styles/
│   │   ├── main.css      # Compiled CSS file (auto-generated)
│── node_modules/         # Dependencies (auto-generated)
│── package.json          # Project scripts and dependencies
│── package-lock.json     # Dependency lock file

---

🚀 Features
SCSS Compilation: Write modular and maintainable stylesheets in SCSS, compiled to CSS.

Live Server: Automatically reloads your browser on file changes.

File Watching: Watches SCSS files for changes and rebuilds CSS in real-time.

Flexible Workflow: Easily extendable for more complex setups in the future.

---

1. Clone the Repository
   
   git clone https://github.com/cadelaa/web-dev-template.git my-new-project
   cd my-new-project

3. Install Dependencies
   
   npm install

5. Build SCSS
   To compile SCSS manually:
   
   npm run build:scss

4. Watch SCSS
   To automatically recompile SCSS on changes:
   
   npm run watch:css

6. Start the Live Server
   To preview your project and enable live reloading:
   
   npm start

---

🌟 Workflow
Write Your HTML: Modify src/index.html.

Style with SCSS: Add styles to src/styles/main.scss.

Preview Changes: Use npm start to see updates live in your browser.

⚙️ Dependencies
sass: Compiles SCSS to CSS.

lite-server (or alternative): Serves your project with live reloading.

concurrently (optional): Runs multiple scripts in parallel.

📝 Customization
Feel free to modify the following as needed:

SCSS File Structure: Add more SCSS files and import them into main.scss.

Scripts in package.json: Adjust or add new scripts for other tools or workflows.

---

🖥️ Example Commands
Start live server and watch SCSS:

npm start
Build SCSS only:

npm run build:scss

---

📖 Future Enhancements
Consider adding:

Linters like ESLint or Stylelint for code quality.

Prettier for consistent formatting.

Build Tools like Webpack or Vite for advanced workflows.
