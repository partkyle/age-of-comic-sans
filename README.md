# Age of Comic Sans: Persistent Edition

A tiny, fully local Chrome/Chromium extension that forces Comic Sans fonts on pages under https://gemini.google.com/*. No external resources, tracking, or dependencies — everything runs from your machine.

## Files included
- `manifest.json`
- `style.css`
- `README.md`

## Install as an Unpacked Extension (Chrome, Brave, Vivaldi, or other Chromium-based browsers)
1. Open the browser.
2. Go to the Extensions page:
   - Navigate to `chrome://extensions/` (this also works in Brave, Vivaldi, and other Chromium browsers).
3. Enable Developer mode:
   - Toggle **Developer mode** in the top-right of the page.
4. Click **Load unpacked**.
5. In the folder chooser, select the local folder you created (e.g., `~/Extensions/age-of-comic-sans`).
6. The extension will appear in your list and will immediately inject `style.css` into pages matching `https://gemini.google.com/*`.

## Confirm it's working
- Visit https://gemini.google.com/ and check that text, headings, inputs, and responses use Comic Sans.

## Security & Privacy
- This extension is 100% local: it contains only a JSON manifest and a CSS file.
- There are no remote calls, analytics, or third-party libraries.
- You can inspect the files at any time to confirm what it does.
