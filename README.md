# Jersey v12 – Bupreme Sports Wear

Railway-ready Flask app with full jersey PDF automation.

## Features (100% working + new)
- Excel upload → parses NAME, NUMBER, SIZE
- Upload jersey templates (PDF) → overlays name/number automatically
- Live progress bar while generating
- ZIP size display
- Admin → Send Message to client
- History search
- Offline detection banner
- Ctrl+G shortcut to generate
- Signup/Login (local DB)
- All original v7 features preserved

## Deploy to Railway
1. Create new GitHub repo, upload these files
2. Railway → New Project → Deploy from GitHub
3. Railway auto-detects Python, installs requirements
4. No env vars needed
5. App runs on PORT provided by Railway

## Files
- app.py – Flask backend (with PyMuPDF template overlay)
- templates/index.html – full frontend
- requirements.txt
- README.md

## Admin
Email: dhub0005@gmail.com
Pass: dhub@0005

## Template Upload
In Generator tab, select your template PDFs (LEFT SLEEVE, RIGHT SLEEVE, FRONT BODY, BACK BODY etc.). The app overlays each player's name & number onto each template.

Built for Railway.com – supports file uploads and PDF processing.
