# Landing Page — LDKM 2024

A very simple static site (HTML, CSS, JS) for LDKM 2024. Contains example pages, materials, and small demos for practice.

## Quick start

1. Clone the repository
   - HTTPS:
     git clone https://github.com/bacca/landingpage-ldkm24.git
   - SSH:
     git clone git@github.com:bacca/landingpage-ldkm24.git

2. Enter the project
   cd landingpage-ldkm24

3. Run locally (no Node required)
   - Recommended — VS Code Live Server:
     1. Open the project in VS Code:
        code .
     2. Install the "Live Server" extension (Ritwick Dey) if needed.
     3. Open `index.html` in the editor.
     4. Right-click → "Open with Live Server" or click "Go Live" in the status bar.
     5. The site opens in your browser (commonly http://127.0.0.1:5500).
   - Alternative — simple HTTP server:
     - Python 3:
       python -m http.server 8000
       then open http://localhost:8000
     - Or:
       npx serve .
