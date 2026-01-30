# Guardian - Women Safety Application

Guardian is a Progressive Web Application (PWA) designed to provide immediate assistance and location tracking for women's safety. It features real-time GPS tracking and one-tap emergency alerts.

## Features

- **Real-time Geolocation**: Automatically tracks and displays current user location on an interactive map.
- **Panic Button (SOS)**: A large, accessible button to simulate sending an immediate distress signal to the nearest police station.
- **Alert Variations**: 
    - **Danger (SOS)**: High priority alert.
    - **Warning**: For potential threats.
    - **Medical**: For health emergencies.
- **Installable (PWA)**: Can be installed on Android and iOS devices directly from the browser, functioning like a native app.
- **Responsive Design**: Optimized for mobile devices.

## How to Run

1.  Ensure you have Node.js installed.
2.  Install dependencies:
    ```bash
    npm install
    ```
3.  Start the development server:
    ```bash
    npm run dev
    ```

## How to Install on Android (PWA)

1.  Open the application in Chrome on your Android device (ensure your phone is on the same network and use the Network IP shown in the terminal, usually `http://192.168.x.x:5173`).
2.  Tap the "Share" or "Menu" button.
3.  Select "Add to Home Screen" or "Install App".
4.  The app will appear in your app drawer and launch in fullscreen mode.

## Technologies Used

- **React**: Frontend framework.
- **Vite**: Build tool and dev server.
- **Leaflet / React-Leaflet**: Open-source maps.
- **Vite PWA**: For offline and installable capabilities.
- **Lucide React**: Iconography.
