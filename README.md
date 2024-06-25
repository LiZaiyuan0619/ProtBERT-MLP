# ProtBERT-MLP4TFPM
**Accurate Identification of Transcription Factors’ DNA Methylation Preference via Simplified K-mer and SVM**


  Transcription factors (TFs) are essential proteins that regulate gene expression by binding to specific DNA sequences and are instrumental in maintaining the three-dimensional architecture of the genome. DNA methylation can modify the binding affinities of TFs, influencing gene regulatory mechanisms and contributing to the onset of various diseases, including cancer.Within the TFs, there is a subgroup known as transcription factors that preferentially bind to methylated DNA (TFPMs). 
  
  Identifying TFPMs is crucial for understanding how DNA methylation affects gene regulation and how these interactions may lead to pathological conditions.
  
  However, the identification of TFPMs is challenging due to the time-consuming and labor-intensive nature of experimental methods.
  
  In this study, we propose a novel two-step computational approach to classify TFs and TFPMs. In the first step, our model distinguishes between transcription factors and non-transcription factors (Non-TFs). For proteins identified as TFs, the second step predicts their ability to bind methylated DNA.
  
  For TF classification, we utilized a fine-tuned ProtBERT model, which demonstrated superior performance on an independent dataset with a sensitivity of 91.51\%, specificity of 94.34\%, accuracy of 92.92\%,Matthews Correlation Coefficient (MCC) of 0.8588, and an Area Under the Receiver Operating Characteristic Curve (AUC) of 0.9721. For TFPM classification, we employed a combination of reduced amino acid category (RAAC) and K-mer encoding with a Support Vector Machine (SVM), achieving a sensitivity of 86.96\%, specificity of 67.57\%, accuracy of 80.19\%, MCC of 0.5568, and AUC of 0.8351 on an independent dataset.Our comparative experiments indicate that the proposed methods are effective, outperforming existing approaches.
  
---
![6 5 0 2](https://github.com/LiZaiyuan0619/RKmer-SVM4TFPM/assets/121675297/c8f083bf-a9e2-4e24-98e9-c8bc295b88c7)

---

![6 5 2 3](https://github.com/LiZaiyuan0619/RKmer-SVM4TFPM/assets/121675297/afaf3d76-64a3-47ef-80d5-456d831c5330)

---

![6 5 3 2](https://github.com/LiZaiyuan0619/RKmer-SVM4TFPM/assets/121675297/66d0cf9f-11ea-4939-a319-855f710ed84b)

---

![image](https://github.com/LiZaiyuan0619/RKmer-SVM4TFPM/assets/121675297/d78f3934-362c-4f39-8b46-bedea69602f7)
