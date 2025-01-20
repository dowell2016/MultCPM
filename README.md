# MulCMP
MulCMP is a deep learning-based approach to multi-omics integration, and the model utilizes a multi-attention mechanism to dig deeper into key information in biological pathways. Combined with the hierarchical fusion module, the model hierarchically fuses information between histologies to better capture their interdependencies. Interpretability analysis of the model using DeepSHAP reveals key genes that are closely related to cancer recurrence, providing an important reference for biological research and cancer recurrence prediction algorithm

# File description
KEGG_pathways, Annotation relationships between genes/miRNA and KEGG pathways. 
brca_data,  breast cancer data.     
blca_data,  bladder cancer data.  
lihc_data,  liver cance data.   
mulcmp_blca.ipynb, blca_data run code.  
mulcmp_lihc.ipynb, lihc_data run code.   
mulcmp_brca.ipynb, brca_data run code.  

# Running environment
python==3.7.16  
sklearn==0.24.2
pandas == 1.1.5  
numpy==1.21.5  
scikit-learn == 0.24.2  
keras==2.2.4  
tensorflow==2.6.0  
shap==0.42.1
matplotlib==3.5.3

# Acknowledgement
part of the code if borrowed form  https://github.com/lanbiolab/DeepKEGG and https://github.com/jianglindong93/AUTOSurv
