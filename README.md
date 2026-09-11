# Password Security Analyzer — Web Edition

## Local run

```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
pip install -r requirements.txt
python app.py
```
Open http://127.0.0.1:5000

## Render
Build command: `pip install -r requirements.txt`
Start command: `gunicorn app:app`

## Security
Password analysis and generation happen in the browser. The Flask server does not receive or store the entered password.
