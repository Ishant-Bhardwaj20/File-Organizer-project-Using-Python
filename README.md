# Python File Organizer :-
This project is a simple and efficient **File Organizer application built using Python**. It automatically organizes files in a directory by identifying their file extensions and moving them into appropriate folders. The project helps keep directories clean and structured without requiring users to manually sort their files.

The program uses Python's built-in **`os`** and **`shutil`** libraries to perform file and folder operations. It first identifies the current working directory and defines different file categories based on their extensions. The program then creates folders for each category if they do not already exist.

Currently, the File Organizer supports the following file types:

 **PDFs** – `.pdf`
 **Word Files** – `.docx`, `.doc`
 **Images** – `.jpg`, `.jpeg`, `.png`
 **Videos** – `.mp4`, `.mkv`
 **Text Files** – `.txt`

The application scans all files available in the selected working directory, checks their extensions, and automatically moves each file to its corresponding folder. Existing directories are ignored during the scanning process to prevent unnecessary errors.

## Features :-
* Automatically organizes files based on their extensions
* Creates category folders automatically if they do not exist
* Supports multiple common file formats
* Uses Python's built-in `os` and `shutil` libraries
* Simple, lightweight, and easy to understand
* Helps maintain a clean and organized directory

## Technologies Used :-
 **Python**
 **OS Library** – For working with files, directories, and file paths
 **Shutil Library** – For moving files between folders

This project was created to practice **Python file handling, directory management, loops, dictionaries, conditional statements, and automation**. It is a beginner-friendly project that demonstrates how Python can be used to automate everyday tasks and improve productivity.

This File Organizer can also be expanded in the future by adding support for more file types, a graphical user interface (GUI), custom folder selection, duplicate file detection, and automatic organization of downloads or other directories.
