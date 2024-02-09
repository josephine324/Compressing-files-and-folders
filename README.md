Compressor

## Overview

This Python program allows users to compress files and folders to various compressed file types, such as `.zip`, `.tar`, `.tgz`, etc. The compressed files or folders are saved with a timestamp in the format "name_of_the_folder_date_month_year."

## Author

Josephine Mutesi <j.mutesi@alusstudent.com>
Benjamin Niyomukiza <b.niyomukiza@alustudent.com>

## How to Run

1. Make sure you have Python installed on your system.

2. Install the required libraries:

    ```bash
    pip install shutil
    ```

3. Download or clone this repository to your local machine.

4. Open a terminal or command prompt and navigate to the project directory.

5. Run the program by executing:

    ```bash
    python folder_compressor.py
    ```

6. Enter the path of the folder you want to compress when prompted.

7. Choose the desired compression type from the available options (zip, tar, tgz).

8. The program will display a message indicating the success or failure of the compression process.

## Example

If you want to compress the folder "MyFolder" as a `.tgz` file, the compressed file will be named "MyFolder_2023_02_27.tgz."

## Notes

- Ensure you have the necessary libraries and tools installed to perform the compression.

- This program uses the `shutil` library for compressing folders and `tarfile` for creating `.tar` and `.tgz` archives.

- Feel free to reach out to the group members if you encounter any issues or have questions.

