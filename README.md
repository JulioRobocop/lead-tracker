# 🚀 Lead Tracker Extension

**Lead Tracker** is a lightweight, efficient Browser Extension designed to help users quickly save and manage potential leads (URLs) directly from their browser popup.

![Lead Tracker Icon](icon.png)

## 📖 Overview

This project is a Chrome/Browser extension built with vanilla JavaScript, HTML, and CSS. It allows sales representatives, marketers, or general users to input URLs or text identifiers for leads and save them into a persistent list for easy access.

## ✨ Features

- **Quick Save:** Instantly save input text (URLs or names) to a list.
- **Live Rendering:** Leads appear immediately in the extension popup without refreshing.
- **Direct Access:** Saved leads are rendered as clickable hyperlinks (`target="_blank"`), allowing you to revisit them instantly.
- **Clean UI:** A minimalist, user-friendly interface styled with a professional green color palette (`#5f9341`).

## 📂 Project Structure

```text
lead_tracker/
│
├── index.html      # The HTML structure of the extension popup
├── index.css       # Styling for the popup (Green theme)
├── index.js        # Logic for saving leads and DOM manipulation
├── manifest.json   # Configuration file for the Chrome Extension (Manifest V3)
└── icon.png        # Extension toolbar icon
🛠️ Technologies Used
HTML5 - Markup

CSS3 - Styling (Responsive width, custom buttons)

JavaScript (ES6) - Logic, Event Listeners, and Template Literals

JSON - Manifest configuration

📥 Installation (Developer Mode)
Since this is a custom extension, you can install it manually in Chrome (or Chromium-based browsers) using Developer Mode:

Download or move the lead_tracker folder to a location on your computer.

Open your browser and navigate to the Extensions page:

Chrome: type chrome://extensions in the address bar.

Edge: type edge://extensions in the address bar.

Toggle Developer mode on (usually a switch in the top right corner).

Click the Load unpacked button (top left).

Select the lead_tracker folder.

The Lead Tracker icon should now appear in your browser toolbar!

🖱️ Usage
Click the Lead Tracker icon in your browser toolbar to open the popup.

Type a URL or lead name into the text input box.

Click the SAVE INPUT button.

The lead will appear in the list below. You can click the link to open it in a new tab.

📝 Notes on Code
Manifest V3: This project uses the latest Manifest version 3 standard for Chrome Extensions.

DOM Manipulation: The index.js file handles user input via addEventListener and updates the innerHTML of the unordered list (ul) dynamically.
```
