This repo is forked by [delight.im](https://github.com/delight-im/HTML-Sheets-of-Paper). I created the style.css (created by style.scss) and did some modifications to build my CV.

# Sheets of Paper

Word processor in your browser using HTML and CSS (e.g. for invoices, legal notices, etc.)

 * Poor man's Google Docs
 * Like the foundation of Microsoft Word or LibreOffice — but in your web browser
 * Emulates sheets of paper in web documents (but without skeuomorphic paper textures)

## Usage

 1. Copy all files to any desired directory
 2. Modify the HTML source in [`index.html`](index.html) to your liking

## Paper sizes

 * `A4` (21cm × 29.7cm) — `sheets-of-paper-a4.css`
 * `A3` (29.7cm × 42cm) — `sheets-of-paper-a3.css`
 * `US Letter` (21.6cm × 27.9cm) — `sheets-of-paper-usletter.css`
 * `US Legal` (21.6cm × 35.6cm) — `sheets-of-paper-uslegal.css`
 * `US Tabloid` (27.9cm × 43.2cm) — `sheets-of-paper-ustabloid.css`

### Landscape orientation

 1. In the `css/sheets-of-paper-*.css` variant that you’re using:
    1. Swap the values of `width` and `min-height`
    1. Set the second value of the `size` attribute to `landscape`
 1. In `index.html`, set `Config.pageHeightInCentimeter` to your new `min-height` value from above

## Printing

### Chrome

 * Change the `Destination` to `Save as PDF`.
 * Make sure the `Paper size` is set to the one defined in your CSS.
 * From the `Margins` list, choose `None` to prevent the browser from overriding our CSS.
 * In the `Options` section, uncheck `Headers and footers` and check `Background colors and images`.

## License

This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).
