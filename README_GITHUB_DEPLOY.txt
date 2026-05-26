AI CAMERA Mobile V9 PaddleOCR Only Diagnostic

Upload to GitHub root:
- index.html
- standard_texts.json

Changes:
- Removed Tesseract fallback because it was slow and generated unstable OCR overlays.
- Uses PaddleOCR.js only. If PaddleOCR.js fails to load, it shows a quick red ROI box instead of waiting 7-10 seconds.
- Crops upper product text ROI before OCR and downscales to max width 760px.
- The middle button shows small version label V9.
