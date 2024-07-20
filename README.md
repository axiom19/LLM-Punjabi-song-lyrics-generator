# LLM-Punjabi-song-lyrics-generator
GenAI to generate Punjabi song lyrics in the style of a late Punjabi artist using natural language processing and parameter-efficient fine-tuning techniques.

## Project Overview

The project uses natural language processing and machine learning techniques to generate original Punjabi song lyrics. It involves several key steps:

1. Data collection through web scraping
2. Data preprocessing and cleaning
3. Model fine-tuning using PEFT (Parameter-Efficient Fine-Tuning)
4. Lyrics generation using the fine-tuned model

## Key Components

- **Web Scraping**: Utilizes Selenium to collect song lyrics from a public lyrics website.
- **Data Preprocessing**: Cleans and tokenizes the collected lyrics data.
- **Model**: Uses a pre-trained language model (GPT-2) as the base.
- **Fine-tuning**: Employs PEFT techniques, specifically LoRA (Low-Rank Adaptation), for efficient model adaptation.
- **Generation Pipeline**: Creates a text generation pipeline for producing new lyrics.

## Technical Stack

- Python
- PyTorch
- Transformers library
- PEFT library
- Selenium for web scraping
- Pandas for data manipulation

## Setup and Usage

1. Install the required libraries: pip install -r requirements.txt

2. Run the Jupyter notebook `Songs-llm.ipynb` to execute the project steps.

3. The notebook includes sections for:
- Data collection
- Data preprocessing
- Model fine-tuning
- Lyrics generation

## Note on Hardware

This project was developed on an Apple M2 chip MacBook. Some adjustments in the code are made to accommodate this hardware, such as using the MPS (Metal Performance Shaders) device for PyTorch operations.

## Future Improvements

- Expand the dataset with more diverse Punjabi songs
- Experiment with different base models and PEFT techniques
- Implement a user interface for easier interaction with the generation model

## Disclaimer

This project is for educational purposes only. Please respect copyright laws and use generated content responsibly.
