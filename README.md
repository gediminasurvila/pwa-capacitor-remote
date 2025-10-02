# PushApp – Capacitor PWA

> This app is built using [Capacitor](https://capacitorjs.com/) and is configured to run as a PWA with iOS support.

## Project Structure

- `capacitor.config.json`: Capacitor configuration (App ID, name, server URL, plugins)
- `package.json`: Project metadata and dependencies
- `package-lock.json`: Dependency lock file
- `.gitignore`: Files and folders to ignore in git
- `README.md`: Project documentation

## Main Features

- Uses Capacitor core and plugins:
  - Camera
  - Splash Screen
  - iOS platform support
- Configured to load from: `https://pwa-tester.netlify.app`
- Splash screen auto-hide enabled

## Getting Started

1. **Install dependencies:**

   ```bash
   npm install
   ```

2. **Capacitor CLI commands:**
   - Add iOS platform:
     ```bash
     npx cap add ios
     ```
   - Open iOS project:
     ```bash
     npx cap open ios
     ```

## Development Notes

- No npm scripts are defined in `package.json` by default.
- Use Capacitor CLI (`npx cap <command>`) for platform management and plugin usage.
- Edit your PWA at the configured server URL.
- Use Capacitor plugins for native features.
