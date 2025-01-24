# Hello World Application Experiments

This README outlines the steps to create and run "Hello World" applications using Tauri, Flutter, and Electron.js on a Windows machine.

## 1. Tauri

### Steps to Create:
1. Install Rust and Node.js.
   - Install Rust: [https://rustup.rs](https://rustup.rs)
   - Install Node.js: [https://nodejs.org](https://nodejs.org)
2. Create a Tauri project (with Vite React):
   ```bash
   cargo create-tauri-app
   ```
3. Build the app for production:
   ```bash
   npm run tauri build
   ```

### Steps to Run:
- Debug Mode:
  ```bash
  npm run tauri dev
  ```

## 2. Flutter

### Steps to Create:
1. Install Flutter SDK: [https://flutter.dev/docs/get-started/install](https://flutter.dev/docs/get-started/install).
2. Create a new Flutter project:
   ```bash
   flutter create hello_world
   ```
2. Enable Windows desktop support:
   ```bash
   flutter config --enable-windows-desktop
   ```
3. Build the app for production:
   ```bash
   flutter build windows
   ```

### Steps to Run:
- Run on Windows:
  ```bash
  flutter run -d windows
  ```

---

## 3. Electron.js

### Steps to Create (with Vite React):
1. Install Node.js: [https://nodejs.org](https://nodejs.org).
2. Installed required packages:
   ```bash
   npm i electron-vite -D
   ```
3. Create a new Electron app:
    ```bash
    npm create @quick-start/electron@latest
    ```

### Steps to Run:
- Start the app in development mode:
  ```bash
  npm run dev
  ```
- Build the app for production:
  ```bash
  npm run build:win
  ```

---

## Results
### Memory Usage
- Tauri: 73.3 MB
- Flutter: 24.5 MB
- Electron.js: 76.4 MB

### File Size
- Tauri: 8.6 MB
- Flutter: 22.7 MB
- Electron.js: 177.0 MB
