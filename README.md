# WebToApp

Turn any website into a lightweight Windows app.
Enter a URL -> click **Build** -> get a standalone `.exe` that opens the site in its own window.

## Requirements
- Windows 10/11 with the Edge WebView2 runtime (preinstalled on Win 11 and up-to-date Win 10)
- Python 3.10-3.12 (tick "Add to PATH" when installing)

## Run
Double-click `run.bat`, or:

    pip install -r requirements.txt
    python webtoapp.py

Built apps land in `output\`.

## Options
Window size, resizable, maximized/fullscreen, always on top, frameless, single instance,
open other-domain links in the default browser, forced dark mode, DevTools,
custom user agent, page zoom, injected CSS/JS, one-file vs folder packaging.
Icon is auto-fetched from the site's favicon (or pick your own PNG/ICO).


