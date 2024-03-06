## Conditional Probabilistic Diffusion Model Driven Synthetic Radiogenomics for Predicting Breast Cancer Outcomes

#### **The codes will be available after the paper is published.

**L. Chen**, Z. Huang, Y. Sun, M. Domaratzki, Q. Liu, P. Hu.

**ABSTRACT**

**Introduction:** The integration of medical images (e.g. magnetic resonance imaging (MRI)) and genomics offers a novel perspective on the study of breast cancer (BC) heterogeneity. However, the absence of paired medical images and genomics data could pose a significant challenge. We hypothesize a well-trained conditional probabilistic diffusion model (CPDM) can address this unpaired data problem by generating BC MRIs conditionally on genomic information. These generated MRIs can be used to predict BC clinical attributes such as disease subtypes and prognosis.

**Methods:**  A CPDM was trained on sagittal MRI projections, conditioned on multi-omic features from TCGA-BRCA patients. Frechet's Inception Distance (FID) was used to evaluate the CPDM performance. The well-trained CPDM was utilized to generate MRIs for 726 TCGA-BRCA patients who lacked actual MRIs, using their multi-omic profiles. The generated MRIs were further used to train XGBoost models and survival models to predict BC clinical outcomes. The efficacy of the models was assessed through the application of established standard evaluation methodologies. We repeated experiments using the gene expression data to evaluate the CPDM’s generalizability in single genomics. An overall project design is shown in Figure 1.

**Results:** The FID scores of the CPDMs were 1.33. The generated MRIs achieved an Area Under the Receiver-Operating-Characteristic curve (AUROC) of 0.85 and an Area Under the Precision-Recall Curve (AUPRC) of 0.89 in predicting the patients’ ER+/HER2+ subtypes. Furthermore, we demonstrated that the MRIs can predict BC patient survival with a Concordance-index score of 0.92. We also showed that the performance of the proposed model has better performance than other baselines.

**Conclusion:** We explored the potential of CPDMs in generating MRIs using BC patients’ genomic profiles. The synthesized MRIs were well-performed in predicting BC clinical outcomes. This study offers valuable references for further radiogenomic research and precision medicine advancements.

**Key words:** Breast Cancer, Conditional Probabilistic Diffusion Model, Radiogenomics, Magnetic Resonance Images, Image synthesis
