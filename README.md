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
- **PDF Password Protection:** Encrypt PDF files with passwords for added security.
- **PDF Decryption:** Decrypt password-protected PDF files.
- **More Tools:** Explore additional functionalities and tools for PDF manipulation.

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

- `-s` or `--s`: Use for silent use.
- `-opt` or `--opt`: Use for option switch for the task.
- `-o` or `--o`: Use for the output folder where your output file will save.
- `-temp` or `-temp`: Use for the temp folder where your source file exists.
- `-ct` or `--ct`: Use `-ct True` for clearing the temp folder after the process is completed.

#### Examples:

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

10. **PDF Password Protection:**

   ```bash
   pdftoolkit.exe -s --opt 10 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct -p "your_password"
   ```

11. **PDF Decryption:**

   ```bash
   pdftoolkit.exe -s --opt 11 -temp /path/to/temp_folder -o /path/to/output_folder -oo -ct -p "your_password"
   ```

Replace `/path/to/temp_folder` and `/path/to/output_folder` with the actual paths where you want to store temporary files and output files, respectively. Adjust other options as needed.

## More Tools

PDF Tool Kit offers additional tools for advanced PDF manipulation. These tools include:

- **PDF Metadata Editor:** Modify metadata (such as author, title, subject, keywords) of PDF files.
- **PDF Page Rotation:** Rotate pages of PDF documents to desired orientations.
- **PDF Page Extraction:** Extract specific pages or ranges of pages from PDF files.
- **PDF Text Extraction:** Extract text content from PDF files for further processing.
- **PDF Watermarking:** Add watermarks (text or image) to PDF pages for branding or security purposes.

Explore these tools further by using the corresponding options in silent mode or interactive mode.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to customize this README according to your specific project details and preferences!