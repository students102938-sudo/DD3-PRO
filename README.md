# BOSS DD-3 Pro Digital Delay (Auto-Tempo Edition)

Clean, zero-crackling Python + Flask web application emulating the BOSS DD-3 Digital Delay with kick-locked Auto-Tempo BPM detection.

## Run Locally
```bash
pip install -r requirements.txt
python app.py
```
Open `http://localhost:5000` in your browser.

## Deploy on Render / Railway via GitHub
- **Build Command:** `pip install -r requirements.txt`
- **Start Command:** `gunicorn app:app`
