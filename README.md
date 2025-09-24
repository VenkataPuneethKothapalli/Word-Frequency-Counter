# Word Frequency Counter

## 📌 Project Description
The **Word Frequency Counter** is a Python console application that reads a text file, analyzes its contents, and displays how many times each unique word appears.  

The program:
- Handles file input and output.
- Cleans text by removing punctuation and converting to lowercase.
- Counts and sorts word frequencies.
- Displays summary statistics in a clear format.

---

## 🚀 Features
- **File Handling**
  - Prompts the user to enter a text file path.
  - Shows an error message if the file is missing or cannot be opened.

- **Text Cleaning**
  - Converts all text to lowercase.
  - Removes punctuation and special characters.
  - Splits text into words by whitespace.

- **Word Counting**
  - Counts word frequencies using a dictionary.
  - Treats words differing only by case as the same word.

- **Results Display**
  - Total number of words.
  - Total number of unique words.
  - The top **N** most common words (default = 10).
  - Words are sorted in descending order of frequency.

- **Error Handling**
  - Manages invalid inputs (e.g., empty files, invalid N values).

- **Optional Add-Ons Implemented**
  - Filters out short words (length < 3).
  - Excludes common stop words (e.g., *the, and, is, in*).
  - Lets the user specify how many top words to display.

---

## 🛠 Requirements
- Python 3.x  
- No external libraries required (uses only built-in modules: `os`, `string`).

---

## 📂 Installation & Setup
1. Download or clone this repository.
2. Ensure Python 3 is installed on your system.
3. Open a terminal/command prompt in the project folder.

---

## ▶️ How to Run
Run the script from the terminal:
```bash
python word_counter.py
