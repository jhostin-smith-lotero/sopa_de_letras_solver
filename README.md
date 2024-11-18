
# Word Search Solver

## Description
This project allows you to search for words in a word search puzzle and generate a JSON report. 
It is ideal for solving word search puzzles automatically.

## How to Run
To execute this project, simply use Python (no external dependencies are required).

### Steps:
1. Prepare an input file named `input.txt` with the following structure:
    ```
    amars
    steri
    omazc
    alcrh
    polos
    ---
    amar
    osa
    atar
    solo
    polos
    mezclar
    palo
    ```
    - The word search grid and the words must be separated by a line containing `---`.
    - Ensure that both the grid and the words are entirely in **uppercase** or **lowercase**.

2. Run the main script:
    ```bash
    python sopa
    ```

3. The report will be generated in a file named `report.json` with the results of the words found.

## Input and Output
### Input File
The file must contain the word search grid and the words to search for, separated by `---`. Both the grid and the words must be entirely in **uppercase** or **lowercase**.

### Output File
The program will generate a `report.json` file containing the results of the words found.

## Requirements
No external dependencies. This project uses only Python's standard library.
