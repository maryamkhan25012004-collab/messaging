# Messaging Login Training Demo

A clearly labeled, fictional training simulation. It is not WhatsApp and does not access WhatsApp accounts.

## Run on Windows
1. Install Python.
2. Open CMD in this folder.
3. Run: `python -m pip install -r requirements.txt`
4. Run: `python app.py`
5. Visit: `http://127.0.0.1:5000`

## Public hosting with Render
1. Upload these files to a GitHub repository.
2. In Render, create a new **Web Service** and connect that repository.
3. Build command: `pip install -r requirements.txt`
4. Start command: `gunicorn app:app`
5. Deploy. Render will provide a public URL you can share.

The only accepted demo code is `123456`. The app deliberately does not save, log, or transmit submitted phone numbers or codes. Use fictional test data only.
