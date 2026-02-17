# Photo Grid Overlay

A simple, mobile-friendly web app for overlaying a grid on photos. Perfect for checking composition, alignment, and the rule of thirds in photography.

## Features

- 📷 **Photo Loading**: Load photos from your camera or local files
- 📐 **Grid Overlay**: Adjustable 3x3 grid overlay for composition
- 🔄 **Dual Mode Control**: Toggle between manipulating the grid or the photo
- 👆 **Touch Gestures**: 
  - Pinch to zoom in/out
  - Drag to reposition
- 📱 **Mobile Optimized**: Designed for phone screens with full-screen view
- 🎨 **Aspect Ratio Maintained**: Photos fill the screen while keeping their original proportions
- 📲 **Installable**: Can be installed as a Progressive Web App (PWA) on your device
- 🔌 **Offline Support**: Works completely offline once installed

## Usage

1. Open the app on your phone or desktop browser
2. **Install the app** (optional): 
   - On mobile: Look for the "Add to Home Screen" or "Install" prompt in your browser
   - On desktop: Look for the install icon in the address bar
3. Choose "Open Camera" to take a new photo or "Choose Photo" to select an existing one
4. The photo will appear with a grid overlay
5. Use the toggle switch to choose what to manipulate:
   - **Grid Mode** (default): Pinch and drag to adjust the grid
   - **Photo Mode**: Pinch and drag to adjust the photo
6. Tap the screen to show/hide controls
7. Use pinch gestures or scroll wheel (desktop) to zoom
8. Drag with one finger to reposition

## Installation

The app can be installed as a Progressive Web App (PWA):

- **On iOS**: Open in Safari, tap the Share button, then "Add to Home Screen"
- **On Android**: Open in Chrome, tap the menu, then "Install app" or "Add to Home Screen"
- **On Desktop**: Look for the install icon in the browser address bar (Chrome, Edge, etc.)

Once installed, the app works completely offline and can be launched from your home screen or app drawer like a native app.

## GitHub Pages

This app is designed to be hosted on GitHub Pages. Simply enable GitHub Pages in your repository settings and point it to the main branch.

## Technology

Built with vanilla HTML, CSS, and JavaScript - no dependencies required. Uses the HTML5 Canvas API for rendering and touch events for gesture handling.

### PWA Features

- **Web App Manifest**: Defines app metadata for installation
- **Service Worker**: Enables offline functionality and caching
- **Responsive Icons**: Multiple icon sizes for different devices
- **Theme Integration**: Matches device theme colors