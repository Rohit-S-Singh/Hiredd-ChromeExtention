# Hiredd-ChromeExtention

File Structure

/email-extension
├── /assets
│   ├── icon.png              # Extension icon (16x16, 48x48, 128x128)
├── /background
│   ├── background.js         # Handles background tasks (e.g., event listeners)
├── /content
│   ├── content.js            # Extracts email data from the page
│   ├── styles.css            # CSS for styling content if needed
├── /popup
│   ├── popup.html            # The HTML for the popup interface
│   ├── popup.js              # Logic for the popup (optional)
├── /utils
│   ├── api.js                # Functions for sending data to the API
│   ├── dataProcessing.js     # Utility functions for data processing (optional)
├── manifest.json             # The extension's metadata and permissions
└── README.md                 # Project documentation
