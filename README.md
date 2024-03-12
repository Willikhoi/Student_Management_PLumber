## Build/Run

### Requirements
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
python -m http.server
```

You can now access the web vault in your browser at `https://localhost:8000`.

## Special Thanks !

- Chat GPT (open AI)
- Gemini (Google)
- Stackoverflow
- R Document

This project made by Group 1 - DSR301m(Mr.Hung) - FPT University include:
- DINH NGOC KHOI
- BUI THE TUAN
- LE TRAN XUAN DUNG
- NGUYEN GIA HIEN MINH

