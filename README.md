## Basel Computational Biology Conference 2025 - Tutorial T8 on "LLMs in genomics: decoding genomic sequences with advanced representations"

This tutorial focuses on learning various ways to represent sequences for machine learning applications. Practical 1 focuses on ... while Practical 2 focuses on ... .

#### Schedule
Official schedule for this tutorial can be found [here](https://www.bc2.ch/tutorials-workshops).

#### Speakers
- Fabiana Goes, The Rosalind Franklin Institute
- Aparajita Karmakar, The University of Edinburgh and The Rosalind Franklin Institute

#### Slides
- Lecture: Introduction to NLP concepts (Tokens & Embeddings) [📁 slides](/slides/Part1_Representation_Learning_for_Nucleic_Acid_Sequences.pdf)
- Lecture: Fine-tuning LLMs for genomic downstream tasks [📁 slides](/slides/Part2_Representation_Learning_Embeddings.pdf)
  
## Getting ready for T8
### What would you need?

- Gmail account (to access google colaboratory). Google colaboratory lets you write and execute Python code in your browser, with access to GPUs and TPUs.
- Github account  and [git bash](https://git-scm.com/downloads) (to save the codebase locally).

### Running on Google Colab

To use Google Colab simply click on the links below and run the cells. Each cell has related instructions. To run the tutorials on Google Colab:

1. Click on the notebook links provided below to open them directly in Colab.
2. Follow the step-by-step instructions included in each notebook cell.
3. Run each cell by clicking the ▶️ button on the left side of the code block.

> **Tip:** Google Colab lets you write and execute Python code for free in your browser, with access to GPUs and TPUs.

### Cloning the git repository locally (not compulsory)

If you wish to keep a copy of the repo locally

1. Open the terminal
2. Clone the repository:
   ```bash
   git clone https://github.com/fabianagoes/bc2_tutorial8.git
   ```

## Practical 1

Practical 1 focuses on understanding basics of Natural Language processing --> Tokens and Embeddings.

[Open Practical 1 in Colab](https://colab.research.google.com/github/fabianagoes/bc2_tutorial8/blob/main/BC2_Tutorial_Part1.ipynb)

## Practical 2

Practical 2 focuses on understanding how to fine-tuning LLMs for genomic downstream tasks

[Open Practical 2.1 in Colab](https://colab.research.google.com/github/fabianagoes/bc2_tutorial8/blob/main/BC2_Tutorial_Part2.ipynb)

## Resources

### Hugging Face
- A collaborative platform that enables users to build, train, and deploy NLP and ML models with open-source code: https://huggingface.co/

### LLMs
- DNABERT2: https://github.com/MAGICS-LAB/DNABERT_2
- Nucleotide Tranformer: https://github.com/instadeepai/nucleotide-transformer
- RNA-FM: https://github.com/ml4bio/RNA-FM

### Datasets

The datasets used in this tutorial are based on the Genome Understanding Evaluation (GUE) benchmark proposed by DNABERT2 authors. GUE is a broad and well-structured benchmark designed to evaluate models across multiple genome analysis tasks. It includes a diverse collection of datasets covering various tasks and species, making it a valuable resource for assessing model performance in genomic sequence understanding. More details available at: https://arxiv.org/abs/2306.15006.