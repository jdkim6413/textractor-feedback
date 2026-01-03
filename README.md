# TeXtractor - Feedback & Support

Welcome to the official feedback repository for **TeXtractor**, a Chrome extension that captures mathematical formulas from your screen and converts them to LaTeX using advanced OCR technology.

> **Note**: This repository is dedicated to bug reports, feature requests, and general feedback. The source code is maintained separately.

---

## What is TeXtractor?

TeXtractor is a powerful Chrome extension that lets you:

- **Capture** any mathematical formula from your screen with a simple drag-to-select interface
- **Convert** captured images to LaTeX code using Pix2Text OCR (powered by ONNX Runtime)
- **Copy** results in multiple formats: LaTeX, Inline (`$...$`), Display (`$$...$$`), or MathML
- **Preview** rendered formulas in real-time with KaTeX
- **Access** your conversion history for quick reference

### Key Features

| Feature | Description |
|---------|-------------|
| One-Click Capture | Click the extension icon or press `Ctrl+Shift+X` to start capturing |
| Offline Support | Models are cached locally after first download (~117 MB) |
| Multiple Formats | Export to LaTeX, Inline, Display, MathML, or AsciiMath |
| History | Keep track of your recent conversions |
| Multilingual UI | Available in English and Korean |

---

## Installation

### From Chrome Web Store (Recommended)

1. Visit the [TeXtractor page on Chrome Web Store](#) *(link coming soon)*
2. Click **"Add to Chrome"**
3. Confirm the installation

### First-Time Setup

On your first capture, TeXtractor will automatically download the required OCR models (~117 MB). This is a one-time process and may take 2-5 minutes depending on your internet connection. After that, the extension works completely offline.

---

## How to Use

1. **Activate Capture Mode**
   - Click the TeXtractor icon in your browser toolbar, OR
   - Press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (Mac)

2. **Select the Formula**
   - Click and drag to draw a rectangle around the formula you want to capture
   - Release the mouse button to capture

3. **Get Your LaTeX**
   - The side panel will open automatically with your converted LaTeX
   - Click the copy button to copy to clipboard
   - Use the format dropdown to switch between output formats

---

## Feedback & Support

Found a bug? Have a suggestion? Just [open an issue](../../issues/new) - no special format required!

Feel free to include:
- What happened (or what you'd like to see)
- Screenshots if helpful
- Your Chrome version and OS (for bugs)

We read every issue and appreciate all feedback.

---

## Frequently Asked Questions

### General

**Q: Is TeXtractor free?**
A: Yes, TeXtractor is completely free to use.

**Q: Does it work offline?**
A: Yes! After the initial model download, TeXtractor works entirely offline.

**Q: What languages are supported?**
A: The UI is available in English and Korean. The OCR recognizes standard mathematical notation.

### Technical

**Q: Why is the first capture slow?**
A: On first use, TeXtractor downloads OCR models (~117 MB). This only happens once.

**Q: Where are the models stored?**
A: Models are cached in your browser's IndexedDB storage.

**Q: How do I clear the cache?**
A: Go to Settings > Data Management > Delete History. Note: This will also clear your conversion history.

**Q: The extension isn't working on certain websites. Why?**
A: Some websites with strict security policies may block extensions. Try using TeXtractor on a different tab or take a screenshot first.

### Troubleshooting

**Q: OCR results are inaccurate. What can I do?**
A: Try these tips:
- Capture a larger area with more padding around the formula
- Ensure the formula is clearly visible (good contrast)
- Avoid capturing at an angle or with shadows

**Q: The side panel doesn't open.**
A: Make sure you're using Chrome 114 or later. The Side Panel API requires this version.

**Q: Keyboard shortcut doesn't work.**
A: The shortcut might conflict with another extension. Go to `chrome://extensions/shortcuts` to customize it.

---

## System Requirements

- **Browser**: Google Chrome 114 or later
- **Storage**: ~150 MB for models and cache
- **Internet**: Required only for initial model download

---

## Privacy

TeXtractor respects your privacy:

- All OCR processing happens **locally** in your browser
- No images or formulas are sent to external servers
- No personal data is collected or transmitted
- Conversion history is stored only in your local browser storage

---

## Contact

For any questions, bugs, or suggestions: [Open an Issue](../../issues/new)

---

*Thank you for using TeXtractor! Your feedback helps make it better.*
