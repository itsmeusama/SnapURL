# Snap URL

A browser extension that helps you manage and organize your URLs efficiently.

## Description

Snap URL is a Chrome extension built with modern web technologies that allows users to quickly save and manage their browser tabs and URLs. The extension provides a clean and intuitive interface for organizing your browsing experience.

## Features

- Quick URL saving
- Clean and modern user interface
- Easy tab management
- Browser extension integration

## Installation

1. Clone the repository:
```bash
git clone https://github.com/itsmeusama/SnapURL.git
cd SnapURL
```

2. Install dependencies:
```bash
npm install
```

3. Build the extension:
```bash
npm run build
```

4. Load the extension in Chrome:
   - Open Chrome and navigate to `chrome://extensions/`
   - Enable "Developer mode" in the top right
   - Click "Load unpacked" and select the `dist` directory from this project

## Development

To start the development server:

```bash
npm run dev
```

To build for production:

```bash
npm run build
```

To preview the production build:

```bash
npm run preview
```

## Project Structure

- `index.html` - Main popup interface
- `index.js` - Main application logic
- `index.css` - Styles for the application
- `manifest.json` - Chrome extension configuration
- `vite.config.js` - Vite build configuration

## Technologies Used

- Vite - Build tool and development server
- Chrome Extension Manifest V3
- Modern JavaScript
- CSS3

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
