#Word Frequency Counter

📌 Project Description

The Word Frequency Counter is a Python console application that reads a text file, analyzes its contents, and counts how many times each unique word appears.
The program handles file input/output, cleans text (punctuation and case), sorts results, and displays summary statistics in a user-friendly format.

🚀 Features

Prompts the user to enter the path to a text file.

If the file is not found or cannot be opened, shows an error message and allows retry.

Reads and cleans the text:

Converts all text to lowercase.

Removes punctuation and special characters.

Splits words by whitespace.

Counts word frequencies using a dictionary.

Displays:

Total number of words

Total number of unique words

The top N most frequent words (default: 10)

Sorts words by frequency (highest to lowest).

Handles invalid inputs gracefully (e.g., empty files, negative N).

Optional Add-Ons Implemented:

Filters out short words (length < 3).

Ignores common stop words (e.g., "the", "and", "is", "in").

Lets the user specify how many top words to display.

🛠 Requirements

Python 3.x

No external libraries required (only built-in modules: os, string).

📂 Installation & Setup

Clone or download the project files.

Make sure Python 3 is installed on your system.

Open a terminal or command prompt in the project folder.

▶️ How to Run

Run the script from the terminal:

python word_counter.py


When prompted:

Enter the path to a .txt file.

Example: sample.txt

Enter how many top words you want to display.

Press Enter to use the default (10).

✅ Example Run

Input file (sample.txt):

Python is great. Python is powerful. Python is easy to learn.


Output:

--- WORD FREQUENCY COUNTER ---
Enter the path to a text file (or 'exit' to quit): sample.txt
How many top words to display? (Press Enter for default 10): 5

Total number of words: 6
Total number of unique words: 3

Top 5 most common words:
1. python: 3
2. great: 1
3. powerful: 1
4. easy: 1
5. learn: 1

📦 Deliverables

word_counter.py → Python source code

stop_words (hardcoded in code)

sample.txt → Example input file

README.md (this file)
