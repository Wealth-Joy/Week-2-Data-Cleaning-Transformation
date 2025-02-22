Week 2: Data Cleaning & Transformation

Introduction

I focused on cleaning up messy data in Microsoft Excel. The goal was to remove unnecessary things, fix text formatting, and organize the data so it looks neat and is easy to use.

What I Did in This Project

1. Removing Unwanted Blank Rows

The dataset came with empty rows that can make the data look messy. I deleted all blank rows to keep the table clean and easy to read.

2. Clearing Unwanted Formatting

Sometimes, a file comes with bold text, different colors, or fonts that we don’t need, just like this dataset i worked with. I used Excel’s "Clear Formatting" option to remove all unwanted styles and make the data uniform.

3. Fixing Text Formatting

Data often comes in different text styles (some words in uppercase, lowercase, or mixed case). I used the following Excel functions to fix this:

PROPER – Changes text to Title Case (e.g., "juarez, jose" → "Juarez, Jose").

UPPER – Converts all text to UPPERCASE (e.g., "juarez, jose" → "JUAREZ, JOSE").

LOWER – Converts all text to lowercase (e.g., "juarez, jose" → "juarez, jose").

4. Replacing Words Automatically

Instead of using "Find and Replace" manually, I learned to use the SUBSTITUTE function to replace words inside cells.

Example: A cell in the department column had "Mktg" but I wanted it as "Marketing", so I used the excel function named: SUBSTITUTE

=SUBSTITUTE(cell name(e.g A2), "Mktg", "Marketing")

This automatically changed "Mktg" to "Marketing" in the entire column.

5. Importing a Text File into Excel

Instead of typing everything manually, I imported a .txt file into Excel and converted the raw text into a structured table.

I learned how to split text into columns, using the delimiters present in the file, so that it fits neatly into Excel.

What I Learned from This Exercise

This practice helped me understand how to clean, fix, and organize messy data. Now, I can quickly remove unwanted spaces, fix text formatting, and import files into Excel without errors. Next, I’ll focus on more advanced data analysis techniques.
