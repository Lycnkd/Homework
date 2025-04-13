# Homework

### Summary

**Title**: Fine-tune Distill-GPT-2 for Data Synthesis

**Objective**: The purpose of this assignment is to explore how language models can be fine-tuned to generate synthetic tabular data. You will use the dataset `adult100.csv`, fine-tune the Distill-GPT-2 model, and evaluate the quality of the generated synthetic data.

### **Guidance**

1. **Setup and Preparation**
    - Use [Google Colab](https://colab.research.google.com/) with GPU acceleration enabled for efficient model training.
2. **Data Transformation**
    - You might need to convert the dataset rows into a textual representation that can be processed by a language model.
3. **Model Fine-Tuning**
    - Fine-tune the Distill-GPT-2 model.
4. **Synthetic Data Generation**
    - Use the fine-tuned model to generate new synthetic data in text format.
    - Convert the generated text back into tabular data by parsing the outputs.
5. **Evaluation of Synthetic Data**
    - Evaluate the quality of the synthetic data by comparing it to the original dataset.
    - Perform:
        - **1-Way Marginal Distributions**: Compare the distributions of individual columns between original and synthetic datasets.
        - **2-Way Marginal Distributions**: Compare joint distributions of feature pairs between original and synthetic datasets.

### **Deliverables**

Provide the complete code implementation in a Colab notebook. There is no need to write a formal report, but your code should be well-organized and easy to follow.