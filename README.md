# DE Bill Format - Tax Invoice Generator
[Generate Bill](https://hd-mixture.github.io/DE-Bill-Format/)
A professional tax invoice generator with GST calculation, amount in words, and PDF export functionality.

## Features

- Dynamic GST calculation (18%)
- Amount in words with paisa support
- Add/Remove invoice items
- Unit validation with suggestions
- Quantity and Rate field validation
- PDF export with proper formatting
- Optional header visibility
- Responsive design

## Setup

1. Clone the repository:
```bash
git clone [repository-url]
```

2. Open `index.html` in your web browser.

## Usage

1. Fill in the invoice details:
   - Company information
   - Customer details
   - Invoice number and date
   - Item details (description, unit, quantity, rate)

2. The system will automatically:
   - Calculate row totals
   - Compute GST
   - Show amount in words
   - Format numbers with proper decimal places

3. To generate PDF:
   - Click the "Download PDF" button
   - The PDF will be generated with proper formatting
   - All editable fields will be locked in the PDF

## Browser Support

- Chrome (recommended)
- Firefox
- Edge
- Safari

## Dependencies

- html2pdf.js (v0.10.1) - For PDF generation
- No other external dependencies required

## File Structure

```
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # Stylesheet
├── js/
│   └── app.js          # JavaScript code
└── assets/
    └── header.png      # Company header image
```

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
