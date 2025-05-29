# Minimal V2Ray VLESS WS TLS Docker Project

## Usage

1. Replace `PUT-YOUR-UUID-HERE` in `config.json` with your UUID.  
   You can generate a UUID here: https://www.uuidgenerator.net/

2. Push the project to your GitHub account.

3. Deploy on Railway.app:
   - Login to Railway with GitHub.
   - Create a new project -> Deploy from GitHub repo.
   - Select this repo.
   - Railway will build and deploy.

4. After deployment, get the Railway domain (like yourapp.up.railway.app).

5. Configure your V2Ray client:
   - Address: yourapp.up.railway.app
   - Port: 443
   - UUID: (the UUID you put in config.json)
   - Protocol: VLESS
   - Transport: WebSocket
   - TLS: Enabled
   - WebSocket Path: /vless
