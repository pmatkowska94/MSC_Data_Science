# MSC_Data_Science
Repository containing Code used for my Capstone Project: Transfer Learning in Bioprocessing. 

## Pilot study:

(1) **Pilot_EDA.ipynb** – code for EDA on the source (CHO) domain.  
(2) **Pilot_Normalize+RNN.ipynb** – code for preprocessing and the first baseline RNN model on the CHO dataset (1st stage).  
(3) **Pilot_Normalize+RNN_improved.ipynb** – code for preprocessing and improved model refinement (2nd stage).  
(4) **Pilot_knowledge_transfer.ipynb** – code for the pilot study implementing transfer learning from CHO to iPSC (3rd stage).  
(5) **Pilot_EDA_iPSC.ipynb** – code for EDA on the target (iPSC) domain.

---

## The main study expands this workflow to the full dataset and formal transfer learning framework:

(6) **CHO_EDA.ipynb** – main study EDA on the CHO dataset.  
(7) **CHO_preprocessing.ipynb** – preprocessing pipeline for CHO data.  
(8) **CHO_Augmentation+Scaling.ipynb** – data augmentation and feature scaling applied to the CHO dataset.  
(9) **CHO_seq+RNN.ipynb** – sequence generation and RNN model development on the source domain.  
(10) **iPSC_EDA+preprocessing.ipynb** – EDA and preprocessing for the target (iPSC) dataset.  
(11) **iPSC_transfer_knowledge_zero_shot.ipynb** – zero-shot model evaluation on the iPSC dataset.  
(12) **iPSC_transfer_knowledge_tl1.ipynb** – first transfer learning attempt on the iPSC dataset.  
(13) **Copy_of_iPSC_transfer_knowledge_tl1.ipynb** – second transfer learning attempt with reduced LR.  
(14) **CHO_seq+RNN_model_cross_validation.ipynb** – cross-validation of transfer learning models.  
(15) **RMSE,_MAE_Comparison_TL.ipynb** – visuals.








