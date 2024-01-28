# Read Me File

---

## Supplementary Data

### Title: 
Large Language Model Based Framework for Automated Extraction of Genetic Interactions from Unstructured Data

### Authors:
- Jaskaran Gill<sup>1</sup>
- Madhu Chetty<sup>1</sup>
- Suryani Lim<sup>1</sup>
- Jennifer Hallinan<sup>1,2</sup>

**Affiliations:**
1. Health Innovation and Transformation Centre, Federation University, Victoria, Australia
2. BioThink, Queensland, Australia

---

## Abstract:

This supplementary data accompanies the paper titled "Large Language Model Based Framework for Automated Extraction of Genetic Interactions from Unstructured Data" submitted to PLOS ONE. The paper proposes a novel framework utilising large language models for the automated extraction of genetic interactions from unstructured data. The authors present findings from experiments conducted at the Health Innovation and Transformation Centre, Federation University, Victoria, Australia, and BioThink, Queensland, Australia.

---

# Supplementary Materials

## Contents:

1. **Pseudocode.docx:**
   - This Word document includes three Pseudocode for our GIX framework: pre-processing, relation extraction, and post-processing.

2. **Extracted Regulations - Experiment Exp2 - Comparison of GIX with manual curation of a benchmark dataset.xlsx:**
   - Excel file with results from the experiment comparing GIX with manual curation of a benchmark dataset, including extracted regulations and augmented sentences.

3. **Extracted Regulations - Experiment Exp3 - Comparison of GIX with manual curation of a real-world database.xlsx:**
   - Excel file with results from the experiment comparing GIX with manual curation of a real-world database, including extracted regulations.

4. **Training_Data_Relation_Classification.xlsx:**
   - Excel file containing data used to train the relation classification model in our framework. Includes labeled sentences for relation extraction from BioInfer, HPRD50, IEPA, and LLL datasets.

5. **Training_Data_Sentence_Eliminator_1.xlsx:**
   - Excel file containing data used to train "Sentence Eliminator 1" in the pre-processing stage of our framework.

6. **Unwanted Words - Excel:**
   - Excel file with a list of the most repetitive non-entity words.

7. **Gene Interaction Extraction Framework (Code):**
   - Python code file containing the implementation of GIX relation extraction. The code execution instructions are provided within the file.

8. **E_Coli_RegulonDB_regs.xlsx**
  - This file contains Transcriptional regulations in Escherichia coli (E. Coli) obtained from RegulonDB.
  
9. **relation_extraction_f.pth**
  - This file contains the pre-trained model for fine-tunned for gene relation extraction (Stage-2 of GIX: Relation Extraction). 
  
10. **sentence_classification_f.pth**
  - This file contains the pre-trained model fine tuned to eliminate sentences that do not dictate a regulatory interaction (Stage-1 of GIX: Pre-processing).
  

Please refer to the main paper for a comprehensive understanding of the framework, methodologies, and results. If you have any inquiries or require clarification. 


