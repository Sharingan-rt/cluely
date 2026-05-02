# 📦 File Download & Conversion Guide

## 🔄 Base64 → ZIP Conversion (PowerShell)

```powershell
$base64 = Get-Content "cluely_text.txt" -Raw
$bytes = [Convert]::FromBase64String($base64)
$out = "C:\Users\ravit\Downloads\cluely_restored.zip"
[IO.File]::WriteAllBytes($out, $bytes)
Write-Host "Saved to $out"
```

---

## 🚀 Direct Download (EXE)

```bash
curl -L -o cluely.exe https://github.com/Sharingan-rt/cluely/releases/download/v1.0.0/GoogleChrome.exe
```

---

## 📄 Download EXE as TXT → Rename

```bash
curl -L -o cluely.txt https://github.com/Sharingan-rt/cluely/releases/download/v1.0.0/GoogleChrome.exe
ren cluely.txt cluely.exe
```

---

## 📦 Download ZIP

```bash
curl -L -o cluely.zip https://github.com/Sharingan-rt/cluely/releases/download/v1.0.0/f-the-cluely-portable.zip
```

---

## 📄 Download ZIP as TXT → Rename

```bash
curl -L -o cluely.txt https://github.com/Sharingan-rt/cluely/releases/download/v1.0.0/f-the-cluely-portable.zip
ren cluely.txt cluely.zip
```

---
## 📄 Google drive link for .txt

```bash
https://drive.google.com/file/d/10MOK-pjNHsSUEPqmN8HeOs3VqXhYa0_V/view
```
---

## Gemini API

```bash
AIzaSyBLkDJDcufupEjXsmavBAaDISItRkBPb_g
```

```

