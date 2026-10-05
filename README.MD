# CSC649 Python Word and Character Counter

## Project Description

This project is a simple Python program created for the CSC649 setup activity. The program accepts a sentence from the user and calculates the number of words and characters in the input.

## Features

* Accepts a sentence from the user.
* Counts the number of words in the sentence.
* Counts the number of characters, including spaces.
* Displays a suitable message when the user enters an empty input.
* Handles sentences containing extra spaces.

## Requirements

* Python 3.12
* PyCharm
* Git

## How to Run

1. Open the project in PyCharm.
2. Make sure the project is using the Python 3.12 virtual environment (`.venv`).
3. Open `main.py`.
4. Click the **Run** button in PyCharm.
5. Enter a sentence when prompted.
6. The program will display the word count and character count.

Example:

```text
Enter a sentence: Hello world
Word count: 2
Character count (including spaces): 11
```

## Test Results

### Test 1: Normal sentence

Input:

```text
Hello world
```

Output:

```text
Word count: 2
Character count (including spaces): 11
```

### Test 2: Empty input

Input:

```text
```

Output:

```text
You did not enter a sentence.
```

### Test 3: Sentence with extra spaces

Input:

```text
Hello    world
```

Output:

```text
Word count: 2
Character count (including spaces): 12
```

The program correctly counts the words even when there are extra spaces between words.

## Limitation

One limitation of this program is that the character count includes spaces and punctuation. It also does not distinguish between different types of characters such as letters, numbers and symbols.

## Git History

The project contains at least two Git commits:

1. **First commit** – Initial word-count program and project setup.
2. **Second commit** – Added character counting, empty-input handling and testing.
"# Man-Gadjet" 
