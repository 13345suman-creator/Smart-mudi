Smart Mudi Khana - POS System
================================

Features:
- Inventory Management
- Billing with Barcode Scanner
- UPI QR Code Payment
- Voice Input
- Multi-language (Bengali, Hindi, English)
- Offline-first (works without internet)

Setup Instructions:
1. Extract all files maintaining folder structure
2. Open index.html in Chrome/Edge browser
3. Allow camera permission for barcode scanning
4. Go to Settings (Dashboard → Settings) and enter your UPI ID
5. Start using!

File Structure:
smart-mudi-khana/
├── index.html          (Main HTML file)
├── css/
│   └── style.css       (All styles)
├── js/
│   └── app.js          (Application logic)
├── lib/
│   ├── qrcode.min.js   (QR Code library)
│   └── html5-qrcode.min.js (Barcode scanner library)
└── README.txt          (This file)

Note: For barcode scanner to work, you must use HTTPS or localhost.