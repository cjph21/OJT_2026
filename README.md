# React Native with Expo - Setup Guide

## Prerequisites

- **Node.js** (LTS version recommended)
- **Git** (for version control)
- A code editor (e.g., VS Code)
- A physical device or emulator/simulator for testing

---

## Step 1: Install Node.js and npm

1. Download the **LTS** version of Node.js from [https://nodejs.org](https://nodejs.org).
2. Run the installer and follow the prompts (npm is included with Node.js).
3. Verify the installation by opening a terminal and running:

```bash
node -v
npm -v
```

Both commands should print version numbers.

---

## Step 2: Install Expo CLI

Expo now recommends using `npx` instead of installing the CLI globally. This ensures you always use the latest version without relying on old dependencies.

```bash
npx create-expo-app@latest my-app
```

Verify it was installed:

```bash
expo --version
```

## Step 3: Navigate into the Project

```bash
cd my-app
```

---

## Step 4: Install Dependencies

Dependencies are installed automatically when you create the project. If needed, you can reinstall them with:

```bash
npm install
```

---

## Step 5: Start the Development Server

```bash
npx expo start
```

This will open the Expo Dev Tools in your terminal showing a QR code and several options:
- Press `a` to open on an Android emulator
- Press `i` to open on an iOS simulator (macOS only)
- Press `w` to open in a web browser
- Scan the QR code with the **Expo Go** app on your physical device

---

## Step 6: Run on a Physical Device

1. Install the **Expo Go** app on your phone:
   - [Android - Google Play Store](https://play.google.com/store/apps/details?id=host.exp.exponent)
   - [iOS - Apple App Store](https://apps.apple.com/app/expo-go/id982107779)
2. Make sure your phone and computer are on the **same Wi-Fi network**.
3. Scan the QR code shown in the terminal using:
   - **Android**: Expo Go app's built-in scanner
   - **iOS**: The default Camera app

---

## Quick Reference

```bash
# Full setup from scratch
node -v                                  # Verify Node.js
npm -v                                   # Verify npm
npx create-expo-app@latest my-app       # Create project
cd my-app                                # Enter project folder
npx expo start                           # Start dev server
```
