# Pandabuy to Weidian URL Converter

This project is a simple yet effective tool designed to unmask Weidian links hidden by Pandabuy, allowing users to access original product pages directly. By bypassing Pandabuy's link masking, users can explore Weidian's offerings without restrictions, gaining more purchasing freedom.

## Features

- **Weidian Link Conversion**: Extracts and decodes Weidian URLs from Pandabuy links.
- **Copy to Clipboard**: Conveniently copy the converted link with a single click.
- **Responsive Design**: Optimized for various screen sizes and devices.
- **Error Handling**:
  - Displays an error message if the required assets (logo or font) are not found.
  - Provides user-friendly feedback when input URLs are invalid.
- **Professional Styling**: Styled with Ferrari Sans font, green theme accents, and branding elements.
- **Custom Branding**: Features a Pandabuy logo and a personalized watermark.

## Usage

1. Paste a Pandabuy URL into the input box.
2. Click the **Convert** button to retrieve the original Weidian link.
3. Copy the link using the **Copy** button for easy sharing.

## Installation

1. Clone or download the repository.
2. Ensure the following assets are included in the project directory:
   - `Ferrari-SansRegular.woff2`
   - `pandabuy.png`
3. Open `index.html` in your browser to use the tool.

## Technical Overview

- **HTML/CSS/JavaScript**: Provides a lightweight and interactive user interface.
- **Custom Fonts and Assets**: Includes Ferrari Sans for a professional look.
- **Dynamic Error Handling**: Alerts users to missing assets or invalid URLs.

## Example Workflow

1. Input: `https://www.pandabuy.com/product?url=encodedWeidianLink`
2. Output: `https://weidian.com/item.html?itemID=12345&spider_token=abcde`

The output link is clickable and can also be copied to the clipboard for immediate use.

## License
This project is open source and available for personal and non-commercial use.
