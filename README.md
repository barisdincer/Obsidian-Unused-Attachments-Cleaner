# Obsidian-Unused-Attachments-Cleaner

### Deleting Unused Attachments Script

This script is designed to help users delete unused attachments in their Obsidian vault. When working with markdown files, users often include attachments such as images or files. However, over time, these attachments can accumulate and take up unnecessary space if they are no longer referenced in any of the markdown files.

How the Script Works:
The script scans through the specified directory containing attachments (referred to as z_ekler folder in this example) and checks if each attachment is referenced in any markdown file within the main folder and its subfolders. If an attachment is not referenced, the script deletes it.

Usage:
Clone the Repository: Clone or download this repository to your local machine.

Customize Paths: Open the Python script (delete_unused_attachments.py) in a text editor. Modify the attachment_path and main_folder_path variables according to your directory structure.

attachment_path = r'YOUR_attachment_path_HERE'
main_folder_path = r'YOUR_MAIN_FOLDER_PATH_HERE'
Run the Script: Execute the script using Python. It will scan for unused attachments and delete them if found.

Note:
Make sure to review and understand the script before running it, especially if you're dealing with sensitive data. While the script aims to delete unused attachments, always ensure you have backups of your data.
Ensure Python is installed on your system to run the script (python delete_unused_attachments.py)