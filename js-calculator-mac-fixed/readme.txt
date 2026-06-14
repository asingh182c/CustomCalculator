## 🚀 Getting Started

Follow these steps to set up the project locally:

1. **Unzip or Clone the repository** into your desired directory.
2. **Open your Terminal** and navigate to the project folder:
   ```bash
   cd path/to/js-calculator-mac
   ```
3. **Install the dependencies:**
   ```bash
   npm install
   ```

## 🛠 Development Commands

You can run the application in two ways during development:

### 1. Web Preview (Vite Server)
To run the calculator in your web browser with hot-reloading:
```bash
npm run dev
```

### 2. Desktop Preview (Electron)
To instantly preview how the app will look and behave inside the macOS desktop window:
```bash
npm run build && npm run start-desktop
```

## 📦 Building the macOS Installer (.dmg)

When you are ready to distribute or install the application, you can generate a `.dmg` file.

1. In your terminal, ensure you are in the project root directory.
2. Run the build script:
   ```bash
   npm run build-mac
   ```
3. Wait for the process to finish. Vite will compile the web assets, and `electron-builder` will package the macOS application.

### Output
Once the build is complete, navigate to the newly created `mac-release` folder in your project directory. Inside, you will find:
* `JS Calculator.dmg`

Simply double-click the `.dmg` file and drag the app into your Applications folder to install it!