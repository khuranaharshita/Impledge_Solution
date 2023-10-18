# Impledge_Solution

# Compounded Words Finder
The longest and second-longest compound words in a chronologically sorted word list are found using this Python program. Any word from the list that may be created by joining shorter words together is a compound word.

# Steps to follow
1. Place all the input files like Input_01.txt and Input_02.txt in the same directory as the Python script.
2. Run the program with the command: python compounded_words_finder.py.
3. The program reads the input file, processes the words, and displays the results.

# Key Functions in program
1. compounded: Checks whether a word is compounded from shorter words.
2. flcw: Identifies the longest and second longest compounded words.
3. rwf_file: Reads words from the input file.

# Main Program
1. The program measures the time it takes to process the input file using the time module.
2. It specifies the input file using the input_file variable, which can be changed to the desired input file.
3. The program reads the words from the input file using the rwf_file function.
4. It then finds the longest and second longest compounded words using the flcw function.
5. Finally, it displays the results and the time taken for processing the input file.




The program works for any input file. Change the input_file variable to specify the input you want to analyze.
