AI CAMERA Mobile V10 Tesseract Fast ROI

Upload to GitHub root:
- index.html
- standard_texts.json

V10 notes:
- Shows V10 under the Open Camera button.
- Uses Tesseract Japanese OCR, but only on a strict upper text ROI.
- Downscales ROI to max width 520px for faster recognition.
- This is a fallback path because V9 confirmed PaddleOCR.js CDN loading failed on iPhone Safari/GitHub Pages.
