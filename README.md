Project Name: QR Code Generator

Description:
A simple web app that generates a QR code from a user-provided URL using the free QRServer API. Built with HTML, CSS, and JavaScript.

Features:

User inputs any URL.

Instantly generates a QR code image.

Error animation if input is empty.

Responsive and minimal UI.

Files:

index.html — main webpage structure.

styles.css — handles styling and layout.

script.js — contains QR generation logic.

How It Works:

User types a URL into the input box.

Clicks “Generate QR Code.”

JavaScript calls the API:
https://api.qrserver.com/v1/create-qr-code/?size=150x150&data=YOUR_URL

QR code image appears below the button.

Setup Instructions:

Download or clone the repository.

Keep all files (index.html, styles.css, script.js) in the same folder.

Open index.html in a web browser.

Enter any URL and click Generate QR Code.

Dependencies:
No external dependencies.
