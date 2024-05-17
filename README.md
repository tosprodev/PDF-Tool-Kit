# PDF Tool Kit

PDF Tool Kit is a versatile Python-based command-line application that provides various functionalities for working with PDF files. With PDF Tool Kit, you can easily perform tasks such as converting images to PDFs, merging multiple PDFs, compressing PDFs, converting PDFs to images or Word documents, and converting Word documents to PDFs.

## Features

- **Image to PDF Conversion:** Convert images (e.g., JPEG, PNG) into PDF documents.
- **PDF Merge:** Merge multiple PDF files into a single PDF document.
- **PDF Compression:** Reduce the file size of PDF documents while preserving quality.
- **PDF to JPG Conversion:** Extract pages from a PDF file and save them as separate JPG images.
- **PDF to Word Conversion:** Convert PDF documents into editable Word documents.
- **Word to PDF Conversion:** Convert Word documents into PDF format.
- **Update Checker:** Check for updates to the application.
- **Settings Menu:** Configure application settings.
- **Help Menu:** Display usage guidance and instructions.

## Installation

1. **Download the compiled executable (`pdftoolkit.exe`):**

   You can download the compiled executable from the [Releases](https://github.com/tosprodev/pdf-tool-kit/releases) section of the GitHub repository.

2. **Usage**

   Simply double-click on the `pdftoolkit.exe` file to launch the application.

## Usage

### Normal Mode

To use PDF Tool Kit in normal mode, simply double-click on the `pdftoolkit.exe` file. Follow the prompts to select the desired operation and provide input/output paths when prompted.

### Silent Mode

PDF Tool Kit also supports silent mode for automated operations. Below are examples of using different operations in silent mode:

1. **Image to PDF Conversion:**

   ```bash
   pdftoolkit.exe -s --opt 1 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct
   ```

2. **PDF Merge:**

   ```bash
   pdftoolkit.exe -s --opt 2 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct
   ```

3. **PDF Compression:**

   ```bash
   pdftoolkit.exe -s --opt 3 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct
   ```

4. **PDF to JPG Conversion:**

   ```bash
   pdftoolkit.exe -s --opt 4 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct
   ```

5. **PDF to Word Conversion:**

   ```bash
   pdftoolkit.exe -s --opt 5 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct
   ```

6. **Word to PDF Conversion:**

   ```bash
   pdftoolkit.exe -s --opt 6 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct
   ```

7. **Update Checker:**

   ```bash
   pdftoolkit.exe -s --opt 7
   ```

8. **Settings Menu:**

   ```bash
   pdftoolkit.exe -s --opt 8
   ```

9. **Help Menu:**

   ```bash
   pdftoolkit.exe -s --opt 9
   ```

Replace `/path/to/temp_folder` and `/path/to/output_folder` with the actual paths where you want to store temporary files and output files, respectively. Adjust other options as needed.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your specific project details and preferences!
