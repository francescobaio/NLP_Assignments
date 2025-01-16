# NLP_Assignments

## Overview of the Tasks

This repository addresses two key challenges in sexism detection using Natural Language Processing (NLP):

**[EXIST 2023 Task 1](https://nlp.uned.es/exist2023/)** 

🌟 *Objective*: Detecting and classifying sexism in textual data extracted from **tweets**.  
  
🔍 *Overview*:
      
Our analysis compared the performance of **LSTM** and **Transformer models**, with **RoBERTa** significantly outperforming the Custom Model. This success is attributed to RoBERTa’s **larger number of parameters**, **Pretraining** on a more extensive corpus and **Fine-tuning** on the specific task.
  
  ✅ *Key Takeaways*:  
  - Pre-trained transformer architectures like RoBERTa are highly effective for complex tasks such as **sexism detection**.  
  - Overassociation of the term **‘woman’** with sexism, leading to systematic misclassifications.  


**[EDOS Task A](https://github.com/rewire-online/edos)** 

   🌟 *Objective*: Classifying sexist content in textual data extracted from **tweets**.  

   🔍 *Overview*:  
   
   This task focuses on the exploration of **Prompting techniques** using **Large Language Models (LLMs)**: the goal is to assess their capability to **understand nuanced contexts** in sexist content and **classify complex and ambiguous cases** effectively.  

✅ *Key Takeaways*:  

- **Few-shot prompting** proves to be the most effective technique for this type of task.    
- The **Chain of Thought (CoT) technique** positively impacts model performance by enhancing reasoning capabilities.  
- Experiments on a smaller dataset (CLEF EXIST Task 1, 2023) highlight the **importance of fine-tuning**, which:  
  - Enables the use of **lightweight models** that outperform larger LLMs.  
  - Aligns with recent research findings (Bucher and Martini, 2024).  


## 📂 Project Structure

Here’s an overview of the repository structure:

```plaintext
.
├── assignment_1/           # Files related to Assignment 1
│   ├── html/  # HTML report for Assignment 1
│   ├── assignment_1.ipynb                          # Jupyter notebook
│   └── assignment_1.pdf                            # PDF report for Assignment 1
│
├── assignment_2/           # Files related to Assignment 2
│   ├── html/  # HTML report for Assignment 2
│   ├── assignment_2.ipynb                          # Jupyter notebook
│   └── assignment_2.pdf                            # PDF report for Assignment 2
│
├── docs/                   # Documentation files
│   └── index.html          # Main entry for online documentation
│
├── LICENSE                 # Project license
├── README.md               # This file
├── _quarto.yml             # Quarto configuration file
└── index.qmd               # Source file for the homepage
```

## 📩 Contacts

- Francesco Baiocchi ([francesco.baiocchi2@studio.unibo.it](mailto:francesco.baiocchi2@studio.unibo.it))
- Christian Di Buò ([christian.dibuo@studio.unibo.it](mailto:christian.dibuo@studio.unibo.it))
- Leonardo Petrilli ([leonardo.petrilli@studio.unibo.it](mailto:leonardo.petrilli@studio.unibo.it))

## 📖 Documentation

Access the full documentation and assignment reports directly from this page: [Online Documentation](https://francescobaio.github.io/NLP_Assignments/)

