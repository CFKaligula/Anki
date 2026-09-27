# Anki Card Preview

The preview loads each deck's HTML templates from its folder, so serve the project over localhost instead of opening `index.html` directly.

In PowerShell, run the server from the Anki project root:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

If `python` is not recognized, try the Windows Python launcher:

```powershell
py -m http.server 8000 --bind 127.0.0.1
```

Open the preview at <http://127.0.0.1:8000/>. Keep the terminal running while using the page. Press `Ctrl+C` in that terminal to stop the server.
