# CineGen-LLM-Movie-Description-Genre-Prediction-Plot-Twist-Generation-using-LLMs

## Overview
CineGen-LLM is a Large Language Model (LLM)-based system that explores how AI can understand, analyze, and creatively generate movie-related content.  
Developed in Google Colab using the Hugging Face Transformers library, the project performs three core tasks:

1. **Generate creative movie descriptions** based on title and summary  
2. **Predict genres** from descriptions using zero-shot classification  
3. **Generate alternate endings or plot twists** for each movie  

The system demonstrates how LLMs can be used both for creative writing and analytical text classification within limited computational environments

## Implementation Details

- **Environment:** Google Colab  
- **Framework:** Hugging Face Transformers  
- **Programming Language:** Python  
- **Models Used:**
  - `microsoft/phi-2` → for creative description and plot generation  
  - `facebook/bart-large-mnli` → for zero-shot genre prediction 

## Dataset

A custom dataset of 20 movie entries was created with the following fields:
- `movie_title`
- `description`
- `genres`
- `cast`

The dataset combines popular films and fictional entries to evaluate both analytical and generative capabilities of LLMs

## Tasks

Task 1 – Creative Description Generation
LLM-generated enhanced versions of movie descriptions using the `microsoft/phi-2` model.

Task 2 – Genre Prediction
Used facebook/bart-large-mnli for zero-shot classification of genres.
Predicted genres were compared with actual dataset genres to compute accuracy.

Task 3 – Plot Twist / Alternate Ending Generation
Generated alternate endings or creative twists using the same model (microsoft/phi-2).

The google colab code can be accessed [here](https://colab.research.google.com/drive/1G6yJ325yciTm75RFFuqEOH2gayS_ES42?usp=sharing).

