## Build/Run

### Requirements

- [Node.js](https://nodejs.org) you have to install this pakage
- [RPlumber](https://www.rplumber.io/) 
- SQLite

### Run the app
For local development
1. RUN student_api.R by R studio with port = 4046
```
plumb(file='student_api.R')$run(port = 4046)
```

2. Open CMD:

```
cd C:\path\to\project
node server.js
```

You can now access the web vault in your browser at `https://localhost:4046`.


You can also manually adjusting your API endpoint settings by adding `config/local.json` overriding any of the following values:

```json
{
  "dev": {
    "proxyApi": "http://your-api-url",
    "proxyIdentity": "http://your-identity-url",
    "proxyEvents": "http://your-events-url",
    "proxyNotifications": "http://your-notifications-url",
    "allowedHosts": ["hostnames-to-allow-in-webpack"]
  },
  "urls": {}
}
```

Where the `urls` object is defined by the [Urls type in jslib](https://github.com/bitwarden/jslib/blob/master/common/src/abstractions/environment.service.ts).

## Special Thanks !

Chat GPT (open AI)
Gemini (Google)
Stackoverflow
R Document

This project made by Group 1 - DSR301m(Mr.Hung) - FPT University include:
DINH NGOC KHOI
BUI THE TUAN
LE TRAN XUAN DUNG
NGUYEN GIA HIEN MINH

