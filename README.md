# File Finder

This project helps you find files on your system when you can't remember the exact location but still remember some portion of the file name or its extension.

## Features

- Search for files by partial name or extension.
- Optionally search for both partial file names and extensions simultaneously.
- Scalable search for large directories and multiple locations.

## Requirements

- Python 3.x
- Required libraries (listed below)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/file-finder.git
    ```

2. Navigate into the project directory:
    ```bash
    cd file-finder
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

To find files, you can run the script and pass in a portion of the filename or file extension.

### Example:

1. **Find files by partial name**:
    ```bash
    python file_finder.py --name "example"
    ```
    This will search for files that contain the word "example" in their filename.

2. **Find files by extension**:
    ```bash
    python file_finder.py --extension ".txt"
    ```
    This will search for all `.txt` files on your system.

3. **Find files by both partial name and extension**:
    ```bash
    python file_finder.py --name "report" --extension ".pdf"
    ```
    This will search for files that contain "report" in their filename and have a `.pdf` extension.

### Command-Line Arguments:
- `--name <name>`: (optional) Partial or full f
