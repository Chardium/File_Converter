# File Converter Project

## Description

A web-based file conversion tool that allows users to convert between different document and image formats with ease.

**Live Demo:** [File Converter](https://file-converter-h1dj.onrender.com)

## Features

- Convert images between multiple formats (PNG, JPG, WEBP, etc.)
- Convert documents between various formats:
  - DOCX to PDF
  - HTML to PDF
  - Excel to PDF
  - PDF to DOCX
  - Excel to CSV
  - Text to HTML
  - Image to Text (OCR)
- Simple and intuitive web interface
- Fast and efficient conversion process
- No need for installation—accessible from the web

## Installation

### Prerequisites

- Python 3.8+
- pip (Python package manager)

### Setup

1. **Clone the repository**

   ```sh
   git clone https://github.com/YOUR-USERNAME/File_Converter.git
   cd File_Converter
   ```

2. **Create a virtual environment**

   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install dependencies**

   ```sh
   pip install -r requirements.txt
   ```

4. **Run the application**

   ```sh
   python app.py
   ```

5. **Access the application**
   Open your web browser and go to `http://127.0.0.1:5000/`

## Technologies Used

- **Flask** - Web framework for Python
- **Pillow** - Image processing library
- **pdf2docx** - PDF to DOCX conversion
- **pandas** - Excel and CSV processing
- **Tesseract OCR** - Image to text extraction
- **HTML/CSS** - Frontend design

## Future Improvements

- Batch file conversion
- Cloud storage integration (Google Drive, Dropbox, etc.)
- Fix Excel glitching when converting to PDF and CSV


## Contributions

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

For major changes, please open an issue first to discuss what you'd like to change.

## Current Direction
- Devlopment is on hold (Working on other projects)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

**Developed with ❤️ by Chardium**

