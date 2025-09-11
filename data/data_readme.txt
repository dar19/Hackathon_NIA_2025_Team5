# 📂 Dataset Overview

This folder contains **data files** for siRNA analysis and machine learning workflows.  
Each file is described below with its purpose and usage.

---

## 📑 File Descriptions

### 1. **`A_smdb_data.csv`**
- Contains the **core database information**:  
  - PMIDs  
  - siRNAs  
  - Sequences  
  - Efficacy modifications  
  - And more...  
- Serves as the **primary raw dataset**.

---

### 2. **`B_siRNAs_raw_input.txt`**
- The **raw siRNA dataset** for initial exploration.  
- Useful for understanding **data cleaning and preprocessing steps**.  
- Acts as a **starting point** before generating ML-ready inputs.

---

### 3. **`C_sirna_final_sequences_24length_4_input.txt`**
- The **final prepared dataset** for AI/ML model training.  
- Includes:  
  - **24-nucleotide sequences** (sense & antisense)  
  - **Efficacy values** in numerical format  
- Ready to be used directly in experiments.

---

### 4. **`D_sirnas_90percent_input.txt`**
- A **subset of siRNA data** containing **90% of the dataset**.  
- Can be used for **training ML models**, while holding back the remaining 10% for testing/validation.  
- Useful for controlled experiments and benchmarking.

---

### 5. **`E_sirnas_ind_validation.txt`**
- An **independent validation dataset**.  
- Contains siRNAs not included in the training set.  
- Essential for **evaluating model generalizability** and preventing overfitting.

---

## Usage Notes
- Start with **`A_smdb_data.csv`** if you need **raw unprocessed data**.  
- Use **`B_siRNAs_raw_input.txt`** as a **reference for preprocessing**.  
- For model training, use **`C_sirna_final_sequences_24length_4_input.txt`**.  
- For train/test splits, leverage **`D_sirnas_90percent_input.txt`**.  
- Always validate performance on **`E_sirnas_ind_validation.txt`**.  

---
