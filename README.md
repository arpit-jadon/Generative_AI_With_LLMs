## Overview

    .
    ├── Week1                              # Focus on Intro to LLMs, generative AI project lifecycle, and LLM pre-training + scaling laws.
    │   ├── images 		                     # Folder containing images used in the Lab 1 jupyter notebook.
    │   ├── Lab_1_summarize_dialogue.ipynb # Notebook focusing on learning prompt engineering while using pre-trained FLAN-T5 model and the DialogSum dataset from      │   │                                  # hugging face. 	  		  			             
    │   └── W1-2.pdf                       # lecture slides for week 1 from the course.
    │   
    ├── Week2                              # Focus on Fine-Tuning LLMs
    │   └── W2.pdf                         # Lectures slides for week 2 from the course.
    ├── Week3
    │   └── W3.pdf 
    └── README.md            

## Running Prompt Engineering Notebook [Week 1]

- If you are running the prompt engineering lab 1 notebook from week 1 on your own system, follow these steps:
- Create a conda environment
```bash
conda create -n vm_genai python=3.10 anaconda
```
- Install `torch` and `cuda toolkit` [this is for CUDA version 11.3]
```bash
conda install pytorch==1.12.1 torchvision==0.13.1 torchaudio==0.12.1 cudatoolkit=11.3 -c pytorch
```

- Install `transformers` and `datasets` libraries from hugging face
```bash
pip install transformers==4.27.2 datasets 
```

- Now you can peacefully run the notebook on your own system without any errors.
- I will be adding my self-made descriptive notes shortly

