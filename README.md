# Inventory Capture

A premium, high-performance web application for inventory management featuring live photo capture, barcode scanning, and real-time image optimization.

## Features

- **Live Viewfinder**: Real-time camera stream with glassmorphism UI.
- **Barcode/QR Scanner**: Instantly decode inventory names using the integrated `jsQR` library.
- **Settings Modal**:
  - **File Formats**: WebP, JPEG, PNG.
  - **Compression**: Auto-optimization or Manual High Quality.
  - **Aspect Ratios**: Original, 1:1, 4:3, 16:9.
- **Live Size Badge**: Real-time KB feedback of the optimized image.
- **Save/Reject Flow**: Review images before saving them to local storage.
- **SEO Optimized**: Semantic HTML and meta-tags for better discovery.

## Usage

1. Open `index.html` in any modern web browser.
2. Grant camera permissions.
3. Enter a name or scan a barcode to set the filename.
4. Capture, optimize, and save!

## Technology

- Vanilla JavaScript
- CSS3 (Glassmorphism, Dark Mode)
- HTML5 (Canvas, MediaDevices API)
- [jsQR](https://github.com/cozmo/jsQR) for barcode decoding.
