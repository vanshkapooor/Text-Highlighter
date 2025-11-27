# Text-Highlighter
The goal of this assignment is to create a Python program that takes a file and a text string as input, searches for the text within the file, and then generates an output file/view where the found text is highlighted with a red, unfilled bounding box overlay, without altering the original file content.

This solution relates to how bounding boxes are used in auditing to highlight specific, auditable evidence.

With the help of this code, the User can able to upload PDF, Excel, Word, and Image files, then the text out of these files will be extracted and based on the text, the user can enter a string as a second input, which will be searched within the converted document, and in the output, the string will be highlighted in a RED overlay.

At the beginning of the code, I imported all the required libraries, like Pandas, which is a very popular library written for the Python programming language for data manipulation and analysis, OS library, which provides tools for using operating system-dependent functionality, like reading or writing to the file system, tkinter library which is Python’s built-in library for creating graphical user interfaces (GUIs), PyPDF2 which is a pure-python PDF library capable of splitting, merging, cropping, and transforming PDF files, docx, pytesseract, and Image libraries taht are used for Word, image manipulation.

My Approach for this problem is that first, the user will select the file(PDF, Excel, Word, and Image) from their system and then the text will be extracted from the file in the GUI itself and based on the string that the user will enter in the second input, the programme will search the string irrespective of the case it has been inputed by the user, it will highlight all the matches of the string into a RED overlay over it. For Example, if the user enters "STATION" in the second input field, the code will search all the matches like "station", "Station", and highlight all those.

We can also save the output into a text file in the system as well for future reference.
