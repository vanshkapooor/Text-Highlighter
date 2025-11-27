# Text-Highlighter
The goal of this assignment is to create a Python program that takes a file and a text string as input, searches for the text within the file, and then generates an output file/view where the found text is highlighted with a red, unfilled bounding box overlay, without altering the original file content.

This solution relates to how bounding boxes are used in auditing to highlight specific, auditable evidence.

With the help of this code, the User can able to upload PDF, Excel, Word, and Image files. The text from these files will be extracted, and based on the text, the user can enter a string as a second input, which will be searched within the converted document, and in the output, the string will be highlighted in a RED overlay.

At the beginning of the code, I imported all the required libraries, like Pandas, which is a very popular library written for the Python programming language for data manipulation and analysis, OS library, which provides tools for using operating system-dependent functionality, like reading or writing to the file system, tkinter library which is Python’s built-in library for creating graphical user interfaces (GUIs), PyPDF2 which is a pure-python PDF library capable of splitting, merging, cropping, and transforming PDF files, docx, pytesseract, and Image libraries taht are used for Word, image manipulation.

My approach to this problem is that the user first selects the file (PDF, Excel, Word, or Image) from their system. Then the text will be extracted from the file in the GUI itself, and based on the string that the user will enter in the second input, the programme will search the string irrespective of the case the user has input it, and it will highlight all the matches of the string in a RED overlay over it. For Example, if the user enters "STATION" in the second input field, the code will search all the matches like "station", "Station", and highlight all those.

We can also save the output into a text file in the system for future reference.

Below are the instructions through which we can run the programme:-

-> After execution of the code, A GUI will open like below

<img width="380" height="380" alt="image" src="https://github.com/user-attachments/assets/fb65403c-250a-466b-be19-23c0bab98f46" />

Now, in the GUI, there is a button named "Browse", with the help of this button, the user can select any file out of the 4 above formats from their system, and the button next to "Browse" is the "Extract" button that will extract the document and convert it into a basic text document.

-> Then in the next field, the user will enter the string he/she want to get highlighted from the document. Just next to the input field is a check box to allow case-insensitivity.

-> After filling the second input field, the user will find the string and highlight it using the "Find & Highlight" button. Right next to it is the "Clear Highlight" button that basically removes the highlights from the output text field.

-> Beneath the text field is the button called "Save highlighted copy (output_highlighted.txt)", which will save the output with highlighted text into another text document in your system.

-> In the bottom is the output area where the document that the user will upload will get converted into raw text form, and we can see the string being highlighted at the run time itself.

<img width="380" height="380" alt="image" src="https://github.com/user-attachments/assets/2bf8bd79-5c62-479c-aace-00d70fda6073" />

The above image shows the execution of the code and how it has taken "mongodb" as a string from the user and from the Word document, and it has highlighted the word "MongoDB."
