# 🌌 NEON DYSTOPIA - Installation Guide 🔧

This guide provides detailed instructions for installing and running NEON DYSTOPIA on various platforms and environments.

## System Requirements

### Minimum Requirements
- **Operating System**: Any OS with a modern web browser
- **Processor**: Dual-core 1.5 GHz or better
- **Memory**: 2 GB RAM
- **Graphics**: Any graphics card supporting WebGL
- **Storage**: 10 MB available space
- **Internet**: Only required for initial download

### Recommended Requirements
- **Operating System**: Windows 10/11, macOS 10.15+, or Linux
- **Processor**: Quad-core 2.0 GHz or better
- **Memory**: 4 GB RAM
- **Graphics**: Dedicated graphics card with WebGL 2.0 support
- **Storage**: 20 MB available space
- **Internet**: Broadband connection for optimal experience

### Supported Browsers
- Google Chrome 80+ (recommended)
- Mozilla Firefox 75+
- Microsoft Edge 80+
- Safari 13+
- Opera 67+

## Desktop Installation

### Windows

#### Method 1: Using Git
1. Install Git from [git-scm.com](https://git-scm.com/download/win) if not already installed
2. Open Command Prompt or PowerShell
3. Navigate to your desired installation directory:
   ```
   cd C:\Users\YourUsername\Documents
   ```
4. Clone the repository:
   ```
   git clone https://github.com/Antot-12/NEON-DYSTOPIA.git
   ```
5. Navigate to the game directory:
   ```
   cd NEON-DYSTOPIA
   ```
6. Double-click on `index.html` to launch the game in your default browser

#### Method 2: Manual Download
1. Visit [https://github.com/Antot-12/NEON-DYSTOPIA](https://github.com/Antot-12/NEON-DYSTOPIA)
2. Click the green "Code" button
3. Select "Download ZIP"
4. Extract the ZIP file to your desired location using Windows Explorer or a tool like 7-Zip
5. Open the extracted folder
6. Double-click on `index.html` to launch the game

### macOS

#### Method 1: Using Git
1. Open Terminal
2. Install Git using Homebrew if not already installed:
   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   brew install git
   ```
3. Navigate to your desired installation directory:
   ```
   cd ~/Documents
   ```
4. Clone the repository:
   ```
   git clone https://github.com/Antot-12/NEON-DYSTOPIA.git
   ```
5. Navigate to the game directory:
   ```
   cd NEON-DYSTOPIA
   ```
6. Open `index.html` with your preferred browser:
   ```
   open -a "Google Chrome" index.html
   ```

#### Method 2: Manual Download
1. Visit [https://github.com/Antot-12/NEON-DYSTOPIA](https://github.com/Antot-12/NEON-DYSTOPIA)
2. Click the green "Code" button
3. Select "Download ZIP"
4. Extract the ZIP file to your desired location
5. Open the extracted folder
6. Right-click on `index.html` and select "Open with" followed by your preferred browser

### Linux

#### Method 1: Using Git
1. Open Terminal
2. Install Git if not already installed:
   ```
   # For Debian/Ubuntu
   sudo apt-get update
   sudo apt-get install git
   
   # For Fedora
   sudo dnf install git
   
   # For Arch Linux
   sudo pacman -S git
   ```
3. Navigate to your desired installation directory:
   ```
   cd ~/Documents
   ```
4. Clone the repository:
   ```
   git clone https://github.com/Antot-12/NEON-DYSTOPIA.git
   ```
5. Navigate to the game directory:
   ```
   cd NEON-DYSTOPIA
   ```
6. Open `index.html` with your preferred browser:
   ```
   xdg-open index.html
   ```

#### Method 2: Manual Download
1. Visit [https://github.com/Antot-12/NEON-DYSTOPIA](https://github.com/Antot-12/NEON-DYSTOPIA)
2. Click the green "Code" button
3. Select "Download ZIP"
4. Extract the ZIP file to your desired location
5. Open the extracted folder
6. Right-click on `index.html` and select "Open with" followed by your preferred browser

## Mobile Installation

### Android

1. Install a modern browser like Google Chrome or Firefox from the Google Play Store
2. Visit [https://github.com/Antot-12/NEON-DYSTOPIA](https://github.com/Antot-12/NEON-DYSTOPIA) in your browser
3. Download the ZIP file
4. Use a file manager app to extract the ZIP file
5. Navigate to the extracted folder
6. Tap on `index.html` to open it in your browser
7. For easier access, create a bookmark or add a shortcut to your home screen:
   - In Chrome, tap the menu (⋮) and select "Add to Home screen"
   - In Firefox, tap the menu (⋮) and select "Page" > "Add to Home screen"

### iOS

1. Ensure you have a modern browser like Safari or Chrome
2. Visit [https://github.com/Antot-12/NEON-DYSTOPIA](https://github.com/Antot-12/NEON-DYSTOPIA) in your browser
3. Download the ZIP file
4. Use the Files app to extract the ZIP file
5. Navigate to the extracted folder
6. Tap on `index.html` to open it in your browser
7. For easier access, add to your home screen:
   - In Safari, tap the share button and select "Add to Home Screen"
   - In Chrome, tap the menu (⋮) and select "Add to Home screen"

## Running on a Local Web Server

For advanced users or developers, running the game on a local web server can provide a more stable experience:

### Using Python's Built-in HTTP Server

1. Install Python if not already installed
2. Open a terminal or command prompt
3. Navigate to the game directory
4. Run one of the following commands:
   ```
   # For Python 3.x
   python -m http.server 8000
   
   # For Python 2.x
   python -m SimpleHTTPServer 8000
   ```
5. Open your browser and navigate to `http://localhost:8000`

### Using Node.js and http-server

1. Install Node.js if not already installed
2. Open a terminal or command prompt
3. Install http-server globally:
   ```
   npm install -g http-server
   ```
4. Navigate to the game directory
5. Run the server:
   ```
   http-server -p 8000
   ```
6. Open your browser and navigate to `http://localhost:8000`

## Troubleshooting

### Common Installation Issues

#### "Cannot open index.html" or Blank Screen
- Ensure all files were extracted properly
- Try using a different browser
- Check if JavaScript is enabled in your browser settings

#### Graphics or Display Issues
- Update your browser to the latest version
- Enable hardware acceleration in browser settings
- Update your graphics drivers

#### Game Doesn't Load on Mobile
- Ensure your mobile browser supports modern web standards
- Clear browser cache and cookies
- Try using Chrome or Safari for best compatibility

#### Permission Denied Errors (Linux/macOS)
- Ensure you have read permissions for the game files:
  ```
  chmod -R 755 /path/to/NEON-DYSTOPIA
  ```

### Getting Help

If you encounter issues not covered in this guide:
- Check the GitHub repository for known issues
- Open a new issue on the GitHub repository with details about your problem
- Contact the developer through GitHub

---

*This installation guide was last updated on July 19, 2025.*

*© 2025 NEON DYSTOPIA*