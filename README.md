# note_saver
Note_saver

Notes to Excel Automation

Introduction

We all have those repetitive tasks that consume our time—tasks we know could be automated but haven't gotten around to. For me, it was transferring notes from my phone’s notepad to an Excel spreadsheet. Every day, I would spend countless minutes copying and pasting, a tedious and outdated process. That is, until I discovered the power of coding.

My Story

I’ve always preferred keeping notes on my phone—it’s convenient and perfect for capturing fleeting thoughts. My note-taking app allowed me to save notes as .txt files, following a simple format: Title — Content. However, I needed these notes organized in Excel, with the title in one column and the content in another.

Manually copying and pasting took over an hour daily. So, I decided to take matters into my own hands and learn some basic Python. With the help of online tutorials and a bit of trial and error, I wrote a simple script to automate the process. Now, with just a few clicks, my notes are neatly organized in an Excel file, saving me valuable time!

Features

Reads a .txt file containing notes.

Splits notes based on a Title — Content format.

Saves the notes into an Excel file with titles in Column B and content in Column C.

Handles errors where the expected format is missing.

Installation

To use this script, ensure you have Python installed along with the openpyxl library

Usage

Place your .txt note file in the same directory as the script.

Update the txt_file_path and excel_file_path variables in the script with the correct filenames.

Run the script

Your notes will be saved in an Excel file with proper formatting.

License

This project is open-source and available under the MIT License

