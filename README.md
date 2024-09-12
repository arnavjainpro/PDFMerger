# PDF Merger Script

Welcome to the **PDF Merger Script**, a simple yet efficient Python program designed to combine multiple PDF files in the current directory into a single output file. This script automatically detects all PDF files and merges them, streamlining your workflow.

## Key Features

- **PyPDF2**
    - A robust PDF library in Python that provides functionalities to manipulate PDF files, including merging, splitting, and extracting content. It is easy to integrate and highly efficient for PDF-related tasks.
- **Automated PDF Detection**
    - This script scans the current working directory and detects all PDF files automatically, eliminating the need for manual file input.
- **Single Output**
    - After merging, the script generates a single output PDF (`combined.pdf`), keeping your workspace clean and organized.

## Installation Process

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/pdf-merger-script.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd pdf-merger-script
    ```

3. **Install dependencies:**
    ```bash
    pip install PyPDF2
    ```

4. **Run the script:**
    ```bash
    python3 pdfmerger.py
    ```

## Usage

1. **Place the PDFs:**
    - Move all the PDF files you wish to merge into the same folder where the script is located.

2. **Run the Script:**
    - Simply execute the script using the provided command. The script will automatically merge all PDFs in the current folder into a single file named `combined.pdf`.

3. **Check Output:**
    - The merged PDF, `combined.pdf`, will be saved in the same folder where the script was executed.

## Example Output

The final output will be a single PDF file, combining all the detected PDF files in the folder.

```bash
combined.pdf
