# 📂 Dataset Overview

This folder contains **data files** used for siRNA analysis and machine learning workflows.  
Below is a description of the files and their usage.

---

## 📑 File Descriptions

### 1. **`smdb_data.csv`**
- Contains the **complete database information**:  
  - PMIDs  
  - siRNAs  
  - Sequences  
  - Efficacy modifications  
  - And more...  
- This is the **basic raw data** source.

---

### 2. **`siRNAs_cleaned_input.txt`**
- A **pre-cleaned dataset**, useful as an **example for exploration and data cleaning**.  
- Helps in **selecting the final input** for ML/AI models.  
- This file has already been **cleaned and processed** (as demonstrated in the workflow).

---

### 3. **`sirna_final_sequences_24length_for_input.tsv`**
- The **final input file** for AI/ML models.  
- Contains:  
  - **24-nucleotide sequences** (sense & antisense)  
  - **Efficacy values** in numerical format  
- Ready to be used directly in model training/testing.

---

## Usage Notes
- Start with `smdb_data.csv` if you need **raw unprocessed data**.  
- Use `siRNAs_cleaned_input.txt` as a **reference for cleaning steps**.  
- For AI/ML experiments, **always use** `sirna_final_sequences_24length_for_input.tsv`.

---
