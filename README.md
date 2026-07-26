<p align="center">
  <img src="assets/docs/logo-for-readme-file.png" alt="Scanitta Logo" width="6270">
</p>

<h1 align="center">Scanitta</h1>

<p align="center">
  <strong>Simple. Reliable. Customizable.</strong>
</p>

<p align="center">
  A lightweight barcode scanner web application developed by <strong>Bricks Technologies</strong>.
</p>

---

## Overview

Scanitta is a lightweight, browser-based barcode scanner that uses a device's camera to detect and decode barcodes in real time. It identifies the barcode type, displays the decoded value, maintains a scan history, supports manual barcode entry, allows empty entries when required, and exports the collected data as a CSV file.

The application runs entirely in the browser and requires no installation or backend server.

---

## Screenshots (To Be Shared In Future Release)

### Home

![Home](assets/docs/screenshots/home.png)

### Barcode Detected

![Barcode Detected](assets/docs/screenshots/barcode-detected.png)

### Scan History

![Scan History](assets/docs/screenshots/scan-history.png)

---

## Features

### Barcode Scanning

* 📷 Live camera preview
* 🔍 Real-time barcode detection
* 🏷️ Automatic barcode type identification
* 🔢 Display the detected barcode value
* 🔊 Read the detected barcode using text-to-speech

### Barcode Management

* 📋 Display the latest scanned barcode
* 📚 Maintain a scan history with timestamps
* ➕ Add barcodes manually
* ⬜ Add empty barcode entries when needed
* 💾 Export the barcode list as a CSV file

### User Experience

* 📱 Responsive user interface
* 🌐 Runs entirely in the browser
* ⚡ Lightweight and easy to use

---

## Technology Stack

* HTML5
* CSS3
* JavaScript (ES6)
* Browser Camera API
* Barcode Scanning Library
* Web Speech API

---

## Project Structure

```text
scanitta/
├── assets/
│   ├── docs/
│   │   ├── logo-for-readme-file.png
│   │   └── screenshots/
│   │       ├── home.png
│   │       ├── barcode-detected.png
│   │       └── scan-history.png
│   └── images/
│       ├── logo.png
│       └── logo2.png
├── css/
│   └── styles.css
├── docs/
│   ├── USER_GUIDE.md
│   ├── ARCHITECTURE.md
│   └── CHANGELOG.md
├── js/
│   └── app.js
├── index.html
├── LICENSE
├── README.md
└── .gitignore
```

---

## Getting Started

### Prerequisites

* A modern web browser
* A device with a camera
* Camera permission enabled

### Clone the Repository

```bash
git clone https://github.com/hamza-zain/scanitta.git
```

### Run the Application

1. Navigate to the project directory.

   ```bash
   cd scanitta
   ```

2. Open `index.html` in your web browser.

3. Allow camera access when prompted.

4. Start scanning barcodes.

---

## How to Use

1. Allow the application to access your device camera.
2. Position a barcode within the camera preview.
3. Wait for the barcode to be detected automatically.
4. Review the detected barcode value and barcode type.
5. Listen to the detected barcode using the built-in read feature (optional).
6. Add additional barcodes manually or create an empty entry if required.
7. Continue scanning as needed.
8. Export the barcode list as a CSV file whenever required.

---

## Documentation

Additional documentation is available in the `docs` directory.

* [User Guide](docs/USER_GUIDE.md)
* [Architecture](docs/ARCHITECTURE.md)
* [Changelog](docs/CHANGELOG.md)

---

## Roadmap

Completed releases:

* **v0.1.0** — Initial Application Skeleton
* **v0.2.0** — Application Layout
* **v0.3.0** — User Interface Refinement
* **v0.4.0** — Functionality Implementation
* **v1.0.0** — Stable Release

Future enhancements will be tracked through GitHub Issues, Milestones, and Releases.

---

## License

Copyright © 2026 Bricks Technologies. All rights reserved.

This project is proprietary software. No part of this software or its source code may be copied, modified, distributed, published, sublicensed, sold, licensed, reverse engineered, or used for commercial purposes without the prior written permission of Bricks Technologies.

See the [LICENSE](LICENSE) file for the complete license terms.

---

## Company

**Bricks Technologies**

**Product:** Scanitta

**Tagline:** *Simple. Reliable. Customizable.*
