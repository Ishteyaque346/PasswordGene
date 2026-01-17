# Password Generator


This project is a password generator built with JavaScript. It allows users to generate secure random passwords with customizable length and character sets. The generator provides options to include lowercase letters, uppercase letters, numbers, and symbols in the password. It also offers the ability to avoid ambiguous characters (e.g., "l" and "1") and include spaces.

# Project Overview
A compact, beginner-friendly Password Generator built with HTML, CSS and JavaScript.
The app lets users choose which character types to include (lowercase, uppercase, numbers, symbols), set the desired password length, avoid ambiguous characters, and optionally include spaces. It generates a secure, random password, lets users copy it to the clipboard or download it as a .txt file, and provides a simple strength indicator. The project demonstrates arrays, string manipulation, random selection, basic UI state, and the Clipboard API.

Key Features
Adjustable password length (4–64).
Toggle character sets: lowercase, uppercase, numbers, symbols.
Option to avoid ambiguous characters (e.g., l, 1, I, 0, O).
Option to include spaces.
Guarantees at least one char from each selected set (when length permits).
Shuffle to randomize order and improve distribution.
Copy to clipboard (with fallback).
Download password as .txt.
Visual strength meter (crude estimator based on length and variety).
Responsive layout and accessible controls.
