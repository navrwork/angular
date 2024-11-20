# How to Setup and Run a Angular Project

Running an Angular project locally involves setting up the development environment, installing dependencies, and starting the Angular development server. Here’s a step-by-step guide:

---

### **1. Install Node.js**
Angular requires Node.js and npm (Node Package Manager) to manage dependencies.

- **Download and install Node.js**:
  - [Node.js official site](https://nodejs.org)
  - Install the **LTS** version for better stability.
- After installation, verify Node.js and npm by running:
  ```bash
  node -v
  npm -v
  ```

---

### **2. Install Angular CLI**
The Angular CLI is a command-line tool that helps you manage and run Angular projects.

- Install globally using npm:
  ```bash
  npm install -g @angular/cli
  ```
- Verify the installation:
  ```bash
  ng version
  ```

---

### **3. Clone or Create an Angular Project**
- **Clone an existing project**:
  ```bash
  git clone <repository-url>
  cd <project-folder>
  ```
- **Create a new project**:
  ```bash
  ng new my-angular-app
  cd my-angular-app
  ```

---

### **4. Install Project Dependencies**
Run the following command in the project directory to install dependencies specified in `package.json`:
```bash
npm install
```

---

### **5. Run the Development Server**
Start the Angular development server:
```bash
ng serve
```
- By default, the server runs on [http://localhost:4200](http://localhost:4200).
- If you want to use a different port:
  ```bash
  ng serve --port 4201
  ```

---

### **6. Troubleshooting Tips**
- **Check for missing dependencies**:
  If you encounter errors during `ng serve`, try cleaning and reinstalling dependencies:
  ```bash
  rm -rf node_modules package-lock.json
  npm install
  ```
- **Clear Angular CLI cache**:
  ```bash
  npm cache clean --force
  ```

---

### **7. Stop the Server**
To stop the development server, press `Ctrl + C` in the terminal.

---

### **8. Additional Notes**
- **Hot Reloading**: Angular's development server automatically reloads the app when you make changes to the code.
- **Build the Project for Production**: When you're ready to deploy, use:
  ```bash
  ng build --prod
  ```

This will generate the optimized output in the `dist` directory.

