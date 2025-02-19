# PDF Handler Console App

## Overview
The PDF Handler Console App is a command-line tool designed to perform various operations on PDF files. It provides a range of features to manipulate and manage PDF documents efficiently.
**The App is in development**

## Features (To-Do)
- **Merge PDFs**: Combine multiple PDF files into a single document.
- **Split PDF**: Split a single PDF file into multiple documents based on page ranges.
- **Extract Text**: Extract text content from PDF files.
- **Encrypt/Decrypt PDF**: Secure your PDF files with password protection and remove encryption.
- **Add Watermark**: Add text or image watermarks to PDF pages.
- **Rotate Pages**: Rotate pages in a PDF document.
- **Convert to Images**: Convert PDF pages to image files (e.g., PNG, JPEG).
- **Metadata Management**: View and edit PDF metadata.


## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/pdf_handler.git
    ```
2. Navigate to the project directory:
    ```sh
    cd pdf_handler
    ```
3. Install the required dependencies:
    ```sh
    cargo install
    ```

## Usage
Run the application using the following command:
```sh
cargo run [options]
```

### Options
- `--merge <files>`: Merge specified PDF files.
- `--split <file> <ranges>`: Split the specified PDF file by page ranges.
- `--extract <file>`: Extract text from the specified PDF file.
- `--encrypt <file> <password>`: Encrypt the specified PDF file with a password.
- `--decrypt <file> <password>`: Decrypt the specified PDF file with a password.
- `--watermark <file> <watermark>`: Add a watermark to the specified PDF file.
- `--rotate <file> <angle>`: Rotate pages in the specified PDF file by the given angle.
- `--convert <file>`: Convert pages of the specified PDF file to images.
- `--metadata <file>`: View and edit metadata of the specified PDF file.

## Examples
- Merge PDFs:
    ```sh
    dh --merge file1.pdf file2.pdf file3.pdf
    ```
- Split PDF:
    ```sh
    dh --split file.pdf 1-3,5-7
    ```
- Extract Text:
    ```sh
    dh --extract file.pdf
    ```
- Encrypt PDF:
    ```sh
    dh --encrypt file.pdf mypassword
    ```
- Decrypt PDF:
    ```sh
    dh --decrypt file.pdf mypassword
    ```
- Add Watermark:
    ```sh
    dh --watermark file.pdf "Confidential"
    ```
- Rotate Pages:
    ```sh
    dh --rotate file.pdf 90
    ```
- Convert to Images:
    ```sh
    dh --convert file.pdf
    ```
- View/Edit Metadata:
    ```sh
    dh --metadata file.pdf
    ```

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss your ideas.

## License
This project is licensed under the MIT License.
