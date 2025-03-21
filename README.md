Web Development Template

This repository is a customizable and efficient starter template for simple web development projects. It includes SCSS support, live reloading, and a structured workflow to speed up development.


---


my-project/
│── src/
│   ├── index.html        # Main HTML file
│   ├── styles/
│   │   ├── main.scss     # Main SCSS file
|   |   ├── colors.scss   # Colors SCSS file
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
   
   git clone https://github.com/cadelaa/web-dev-template.git


2. Install Dependencies
   
   npm install


3. Build SCSS
   To compile SCSS manually:
   
   npm run build:scss


4. Watch SCSS
   To automatically recompile SCSS on changes:
   
   npm run watch:css


5. Start the Live Server
   To preview your project and enable live reloading:
   
   npm start

   or

6. Start both Autocompile SCSS & live server

   npm run dev 


---


Checking where the project is pushed to / pulling from

1. Check current remote URL

   git remote -v


2. Update the git remote to new URL

   git remote set-url origin <NEW_GIT_URL>


3. Verify the remote is set to the new one by rerunning

   git remote -v


4. Push to current branch in repo

   git push origin <BRANCH_NAME>


---


Pushing changes

1. Checking changes made
   
   git status


2. Adding files to the commit

   git add .

   or 

   git add file_name.ext


3. Adding a message to your commit

   git commit -m "Your commit message here"


4. Pushing the committed changes

   git push origin main
   

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
