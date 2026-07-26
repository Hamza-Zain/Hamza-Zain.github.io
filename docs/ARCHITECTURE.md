# Scanitta Architecture

## Overview

Scanitta is a client-side web application developed using HTML, CSS, and JavaScript. The application runs entirely in the user's web browser and does not require a backend server or database.

Its primary purpose is to detect barcodes using the device camera, display the decoded information, manage a scan history, and export the collected data.

---

# High-Level Architecture

```text
+------------------------------+
|          Web Browser         |
+------------------------------+
|          index.html          |
|          styles.css          |
|           app.js             |
+--------------+---------------+
               |
               |
               v
+------------------------------+
| Browser Camera API           |
+------------------------------+
               |
               |
               v
+------------------------------+
| Barcode Scanning Library     |
+------------------------------+
               |
               |
               v
+------------------------------+
| Scanitta Application Logic   |
+------------------------------+
               |
               |
     +---------+---------+
     |                   |
     v                   v
User Interface      Scan History
```

---

# Project Structure

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

# Components

## index.html

Defines the application's structure and user interface.

Responsibilities:

* Application layout
* Camera preview container
* Barcode information display
* Scan history table
* User controls

---

## styles.css

Provides the application's visual appearance.

Responsibilities:

* Layout
* Typography
* Responsive design
* Branding
* Table styling
* User interface consistency

---

## app.js

Contains the application's business logic.

Responsibilities:

* Initialize the application
* Access the device camera
* Start barcode detection
* Decode detected barcodes
* Display barcode information
* Maintain the scan history
* Export data to CSV
* Handle user interactions
* Handle application errors

---

# Application Workflow

```text
Application Starts
        │
        ▼
Initialize Application
        │
        ▼
Request Camera Permission
        │
        ▼
Display Live Camera Preview
        │
        ▼
Detect Barcode
        │
        ▼
Decode Barcode
        │
        ▼
Display Barcode Value
        │
        ▼
Identify Barcode Type
        │
        ▼
Update Scan History
        │
        ▼
Wait For Next Scan
```

---

# Data Flow

```text
Camera
   │
   ▼
Video Stream
   │
   ▼
Barcode Scanner
   │
   ▼
Decoded Barcode
   │
   ├──► Latest Barcode
   │
   ├──► Barcode Type
   │
   ├──► Scan History
   │
   └──► CSV Export
```

---

# Technologies

| Technology               | Purpose                          |
| ------------------------ | -------------------------------- |
| HTML5                    | Application structure            |
| CSS3                     | User interface styling           |
| JavaScript (ES6)         | Application logic                |
| Browser Camera API       | Camera access                    |
| Barcode Scanning Library | Barcode detection and decoding   |
| Web Speech API           | Read detected barcodes aloud     |
| Blob API                 | CSV file generation and download |

---

# Design Principles

The application follows several design principles:

* Simple and intuitive user interface
* Client-side processing
* No backend dependencies
* Responsive design
* Modular JavaScript
* Maintainable code structure
* Lightweight architecture

---

# Future Enhancements

Possible future improvements include:

* Enhance user interface
* Support for additional barcode formats
* Import barcode lists from CSV
* Search and filter scan history
* Edit and delete history entries
* Persistent local storage
* Cloud synchronization
* Progressive Web App (PWA) support
* Dark mode
* Multi-language support
* Keyboard shortcuts
