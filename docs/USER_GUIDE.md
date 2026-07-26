# Scanitta User Guide

## Introduction

Welcome to **Scanitta**.

Scanitta is a lightweight web application developed by **Bricks Technologies** for scanning barcodes using a device's camera. The application runs entirely in the browser and requires no installation.

This guide explains how to use Scanitta's features.

---

# System Requirements

* A modern web browser (Google Chrome, Microsoft Edge, Firefox, or Safari)
* A device with a good camera
* Camera permission enabled
* Internet connection (only if required by the barcode scanning library)

---

# Starting the Application

1. Open the Scanitta application in your web browser.
2. Allow camera access when prompted.
3. Wait for the live camera preview to appear.
4. The application is now ready to scan barcodes.

---

# Scanning a Barcode

1. Position the barcode inside the camera preview.
2. Hold the barcode steady.
3. Wait for Scanitta to detect and decode the barcode.
4. The app beeps when a barcode is detected.
5. Review the detected barcode information.

After a successful scan, the application displays:

* Barcode value
* Barcode type
* Latest scanned barcode
* Updated scan history

---

# Reading the Detected Barcode

After a barcode is detected:

1. Click on the **Read** button.
2. Scanitta reads the barcode aloud using your device's text-to-speech engine.

---

# Adding a Barcode Manually

If a barcode cannot be scanned:

1. Locate the manual entry field.
2. Enter the barcode value.
3. Select **Add**.
4. The barcode is added to the scan history.

---

# Adding an Empty Barcode Entry

If you need to record an item without a barcode:

1. Select **Add Empty Barcode**.
2. An empty barcode entry is added to the scan history.

This feature can be useful when documenting items that do not have readable barcodes.

---

# Viewing Scan History

The scan history records every barcode added to the application.

Each entry includes:

* Barcode value
* Barcode type
* Timestamp

The latest scan is automatically added to the list.

---

# Exporting the Barcode List

To export the collected data:

1. Select **Export CSV**.
2. Choose the destination folder.
3. Save the generated CSV file.

The exported file can be opened in spreadsheet applications such as Microsoft Excel, LibreOffice Calc, or Google Sheets.

---

# Troubleshooting

## Camera does not start

Possible causes:

* Camera permission was denied.
* Another application is using the camera.
* The browser does not support camera access.

Recommended actions:

* Refresh the page.
* Allow camera permission.
* Close other applications using the camera.

---

## Barcode is not detected

Possible causes:

* Poor lighting.
* Barcode is damaged.
* Camera is too close or too far.

Recommended actions:

* Improve lighting.
* Hold the barcode steady.
* Adjust the distance from the camera.
* Ensure the barcode is fully visible.

---

## CSV export does not work

Possible causes:

* Browser download was blocked.
* Downloads are disabled.

Recommended actions:

* Allow downloads for the website.
* Try another supported browser.

---

# Best Practices

For the best scanning experience:

* Use adequate lighting.
* Hold the camera steady.
* Keep the barcode clean and unobstructed.
* Scan one barcode at a time.
* Review the scan history before exporting.
* Export the barcode list before closing the application if you need to keep a record.

---

# Keyboard and Browser Permissions

Scanitta requires permission to access your device camera.

No images or barcode data are uploaded to a server. All barcode processing is performed locally within your web browser.

---

# Support

For questions, bug reports, or feature requests, please use the GitHub repository's **Issues** section.

Repository:

`https://github.com/hamza-zain/scanitta`

---

# Version

Document Version: **1.0.0**

Applies to: **Scanitta v1.0.0**
