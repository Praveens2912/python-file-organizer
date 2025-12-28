# Python File Organizer Automation

## Description
This project is a Python automation script that organizes files in a given directory
into separate folders based on their file extensions.

## Features
- Automatically creates folders if they do not exist
- Organizes files into Images, Videos, Documents, Music, Excel, and Others
- Case-insensitive file extension matching
- Uses OS-level file handling

## Technologies Used
- Python
- os module
- shutil module

## How to Run
1. Clone the repository
2. Update the folder path in the script
3. Run the Python file

## Example
Before:
Downloads/
- photo.jpg
- report.pdf

After:
Downloads/
- Images/photo.jpg
- Documents/report.pdf
