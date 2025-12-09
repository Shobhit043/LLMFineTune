# LLMFineTune

A simple project for fine-tuning a Large Language Model (LLM) on a custom instruction-response dataset.

## Contents
LLMFineTune/<br>
├── train.jsonl<br>
├── test.jsonl<br>
├── notebook.ipynb<br>
├── sample_output.txt<br>
└── confusion_matrix.png<br>

## What This Does

- Takes a dataset (train.jsonl) to fine-tune a language model.  
- Runs fine-tuning and evaluates on test.jsonl.  

## Dataset Format
Each line in .jsonl files looks like:

{
  "instruction": "text",
  "response": "text"
}

## How to Use

This project requires a GPU.  
Use **Google Colab** to run the `notebook.ipynb`.

Steps:
1. Open Colab.
2. Upload this repository or mount Google Drive.
3. Open `notebook.ipynb` in Colab.
4. Run all cells to fine-tune and evaluate the model.
