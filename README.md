# Password Generator


This project is a password generator built with JavaScript. It allows users to generate secure random passwords with customizable length and character sets. The generator provides options to include lowercase letters, uppercase letters, numbers, and symbols in the password. It also offers the ability to avoid ambiguous characters (e.g., "l" and "1") and include spaces.

The project uses arrays to store character sets for each enabled character type. It filters out ambiguous characters if the "Avoid ambiguous chars" option is selected. The generator ensures a good distribution by guaranteeing at least one character from each selected set (if possible).

The generated password is displayed in a password box, and the strength of the password is estimated based on its length and character composition. The strength is visually represented by a progress bar and text feedback.

 project includes event listeners for various UI elements, such as the length slider, generate button, shuffle button, copy button, and download button. The copy button uses the Clipboard API to copy the generated password to the clipboard. The download button allows users to download the generated password as a .txt file.

 The project uses a simple modern card style with a dark background color and light text color for readability. It is designed to be responsive and works well on different screen sizes.

Overall, this project provides a convenient and secure way to generate strong passwords for various purposes.
