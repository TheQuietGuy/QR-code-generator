# QRGen — Modern QR Code Generator

A modern, responsive QR code generator built with **HTML, CSS and JavaScript**.

## Features

- Generate QR codes from website URLs
- Custom foreground and background colours
- Multiple QR corner styles
- Adjustable QR size from **160px to 1000px**
- PNG, JPG and SVG logo upload
- 2MB logo upload limit
- Error correction levels: L, M, Q and H
- Live QR code preview
- Download as PNG or SVG
- Responsive desktop/mobile layout
- Dark UI with optional light mode
- QR generation happens locally in the browser

## Project Structure

```text
qr-generator/
├── index.html
├── style.css
├── app.js
└── README.md
```

## Technologies

- HTML5
- CSS3
- JavaScript
- QR Code Styling
- Google Fonts — Inter

## How to Run

No build tools or backend are required.

Simply open `index.html` in a modern browser.

Alternatively, run a local server:

```bash
cd qr-generator
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## How to Use

1. Enter a complete website URL, such as `https://example.com`.
2. Choose the foreground and background colours.
3. Select a corner style.
4. Adjust the QR code size.
5. Optionally upload a logo.
6. Select the desired error correction level.
7. Click **Generate QR Code**.
8. Download the result as PNG or SVG.

## Logo Recommendations

For reliable scanning:

- Keep the logo relatively small.
- Use a simple logo with good contrast.
- Use High (`H`) error correction when using a logo.
- Test the final QR code with a phone before printing or distributing it.

## Download Formats

### PNG

Best for:

- Social media
- Websites
- Presentations
- General image use

### SVG

Best for:

- Printing
- Posters
- Large displays
- Designs where the QR code needs to scale without losing quality

## Privacy

QR codes are generated directly in the browser. The project does not require a backend or database, and entered URLs are not intentionally sent to a QR-generation server.

Logo images are processed locally by the browser.

The QR Code Styling library and Google Fonts are loaded from external CDNs, so an internet connection may be required when opening the page.

## Browser Support

Designed for modern versions of:

- Google Chrome
- Safari
- Firefox
- Microsoft Edge

## Customization

The project can be extended with features such as:

- Gradient QR colours
- Custom finder/eye patterns
- Drag-and-drop logo uploads
- Preset colour themes
- Copy-to-clipboard
- QR code history
- Batch QR generation
- Wi-Fi QR codes
- Contact/vCard QR codes
- Social media QR codes

## Scanning Considerations

Highly customized QR codes can become harder for phones to scan.

For the best results:

1. Maintain strong contrast between the QR code and its background.
2. Avoid making the logo too large.
3. Use an appropriate error correction level.
4. Test the final downloaded QR code before publishing or printing it.

## License

This project is provided for personal and educational use. Check the licenses and terms of any third-party libraries used by the project before redistributing it commercially.
