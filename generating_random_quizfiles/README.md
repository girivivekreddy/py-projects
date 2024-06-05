# Randomized Quiz Generator

## Project Overview

This project aims to create a set of 35 unique quizzes for a class of 35 students. Each quiz contains 50 multiple-choice questions (MCQs) about US states and their capitals. To prevent cheating, each quiz will have the questions and answer options randomized. The project also generates corresponding answer keys for each quiz.

## Table of Contents

1. [Project Description](#project-description)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Usage](#usage)
5. [File Structure](#file-structure)


## Project Description

This project involves:
- Creating 35 different quizzes, each containing 50 MCQs.
- Randomizing the order of questions and the answer choices for each quiz.
- Storing the states and their capitals in a dictionary.
- Writing the quizzes and the corresponding answer keys to separate text files using Python's `open()`, `write()`, and `close()` functions.
- Using the `random` module to shuffle the order of questions and answers.

## Features

- **Unique Quizzes**: Generates 35 unique quizzes with 50 questions each.
- **Randomized Questions and Answers**: Ensures that both the order of the questions and the answer choices are randomized for each quiz.
- **Separate Answer Keys**: Provides corresponding answer keys for each quiz.
- **Easy to Extend**: The code can be extended to include more states or questions if needed.

## Requirements

- Python 3.x

## Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/girivivekreddy/py-project.git
   cd generating_random_quizfiles


## file-structure

generating_random_quizfiles/
│
├── outfiles/
|   ├── agenda.txt
│   ├── apaper1.txt
│   ├── apaper2.txt
│   ├── ...
│   ├── apaper35.txt
│   ├── qpaper1.txt
│   ├── qpaper2.txt
│   ├── ...
│   └── qpaper35.txt
│
├── aim.txt
├── code.ipynb
├── solution_thought_process.docx
└── README.md
