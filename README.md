# Quick Screenshot → Clipboard

A tiny Chrome extension that copies a screenshot of the **visible area of the current tab** to your clipboard.

## What it does
- Click the extension icon
- The visible part of the active tab is captured as a PNG
- The screenshot is copied to your clipboard (ready to paste into Notes, Slack, Docs, etc.)

## Notes / limitations
- Chrome blocks screenshots on internal pages like `chrome://` and `chrome-extension://` (this is a Chrome security rule).
- The extension does **not** collect, store, or transmit any data. Everything happens locally in your browser.

## Install

### From Chrome Web Store (Recommended)
[Get Quick Screenshot → Clipboard on Chrome Web Store](https://chromewebstore.google.com/detail/quick-screenshot-%E2%86%92-clipbo/pimodklbppjmjnpmhaipihkfnbnldebh)

### Install from source (Developer mode)
1. Download or clone this repository
2. Open Chrome and go to `chrome://extensions`
3. Enable **Developer mode**
4. Click **Load unpacked**
5. Select the folder containing `manifest.json`

## Usage
- Open any normal website (`https://...`)
- Click the extension icon
- Paste anywhere with **Cmd+V** (macOS) or **Ctrl+V** (Windows)

## Permissions
- `activeTab` — needed to capture the visible area of the active tab when you click the icon
- `clipboardWrite` — needed to copy the screenshot image to your clipboard

## Contact
Questions, feedback, or issues? Reach out at [contact@ofcodedev.me](mailto:contact@ofcodedev.me)

## License
MIT - see the LICENSE file.
