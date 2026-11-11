# QR Studio | QR Code Generator

A free, modern, and responsive QR Code Generator built with **HTML, CSS, and JavaScript**.

Generate customizable QR codes for websites, text, Wi-Fi networks, email addresses, and phone numbers. Download your QR codes in PNG or SVG format.

The application runs entirely in your browser, with no backend, database, or API key required.

## Features

- Generate QR codes for websites, text, Wi-Fi, emails, and phone numbers
- Customize foreground and background colors
- Download QR codes as PNG or SVG
- Choose image sizes of 256, 512, or 1024 pixels
- Adjustable error correction levels
- Instant QR code generation
- Responsive design for desktop, tablet, and mobile
- Works offline
- No registration or API keys required

## Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Application structure |
| CSS3 | Styling and responsive design |
| JavaScript | QR code generation and interaction |
| Canvas API | Image rendering and PNG export |
| SVG | Scalable QR code exports |

## Installation and Setup

### Step 1: Download the Project

Click the green **Code** button at the top of this GitHub repository.

Select **Download ZIP** and extract the downloaded folder.

### Step 2: Open in Visual Studio Code

1. Open Visual Studio Code.
2. Click **File > Open Folder**.
3. Select the extracted `qr-code-generator` folder.
4. Open the `index.html` file.

### Step 3: Run the Application

**Option 1: Run directly in your browser**

Double-click `index.html` to launch the application.

**Option 2: Use Live Server in VS Code**

1. Open the Extensions panel in VS Code.
2. Search for **Live Server** by Ritwick Dey.
3. Install the extension.
4. Right-click `index.html`.
5. Select **Open with Live Server**.

The application will open in your browser, typically at:

`http://127.0.0.1:5500`

No additional installation is required.

## How to Use

1. Open the QR Code Generator.
2. Choose the QR code type: Website, Text, Wi-Fi, Email, or Phone.
3. Enter the required information.
4. Customize the QR code colors and size.
5. Select the preferred error correction level.
6. Click **Generate QR Code**.
7. Download the generated QR code as PNG or SVG.

## Project Structure

```text
qr-code-generator/
├── index.html
├── assets/
│   ├── app.js
│   └── styles.css
├── vendor/
│   ├── qr-engine.js
│   └── LICENSE.txt
├── tests/
│   └── qr.test.cjs
├── .gitignore
├── LICENSE
└── README.md
```

## Running Automated Tests

Node.js 18 or later is required to run the automated tests.

Open the VS Code terminal and execute:

```bash
node --test tests/qr.test.cjs
```

The tests verify QR code matrix generation, payload creation, and validation.

Node.js is not required to use the web application.

## Deploying on GitHub Pages

You can host this project for free using GitHub Pages.

1. Create a public GitHub repository named `qr-code-generator`.
2. Upload the project files to the repository.
3. Ensure `index.html` is in the root directory.
4. Open your repository's **Settings**.
5. Select **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select the `main` branch and `/(root)` folder.
8. Click **Save**.

Once deployment finishes, GitHub will provide your live website URL.

## Important Notes

- QR codes are generated directly in the browser.
- No user information is uploaded to an external server.
- Generated QR codes are static.
- Use high-contrast colors for reliable QR code scanning.
- Avoid sharing QR codes containing sensitive information.
- Very long content may exceed QR code capacity.

## Third-Party Attribution

This project includes a locally bundled QR encoding implementation based on **QRCode for JavaScript**, copyright (c) 2009 Kazuhiko Arase.

The library is distributed under the MIT License. See `vendor/LICENSE.txt` for details.

## Contributing

Contributions and suggestions are welcome.

1. Fork this repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes.
5. Submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more information.
