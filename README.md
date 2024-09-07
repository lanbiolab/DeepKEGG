# DeepKEGG
W Lan, H Liao, Q Chen, L Zhu, Y Pan, YPP Chen. DeepKEGG: a multi-omics data integration framework with biological insights for cancer recurrence prediction and biomarker discovery. Briefings in Bioinformatics 25 (3), bbae185

DeepKEGG is a multi-omics data integration framework with biological insights for cancer recurrence prediction and biomarker discovery. DeepKEGG can efficiently alleviate the curse of dimensionality in the integration of multi-omics data by using the local connectivity of neuron nodes. In addition, it can enhance the robustness of the model by employing a pathway self-attention module to learn the correlation features of different samples in the pathway feature space. Furthermore,  DeepKEGG can reveal the regulatory relationships between genes, pathways and cancers by calculating the contribution scores of biological nodes.

# File description
KEGG_pathways, Annotation relationships between genes/miRNA and KEGG pathways.  
coef_weight, Feature importance score file.  
BLCA_data,  bladder cancer data.  
LIHC_data,  liver cance data.  
PRAD_data,  prostate cancer data.  
BRCA_data,  breast cancer data.  
kegg-attention_BLCA.ipynb, BLCA_data run code.  
kegg-attention_LIHC.ipynb, LIHC_data run code.  
kegg-attention_PRAD.ipynb, PRAD_data run code.  
kegg-attention_BRCA.ipynb, BRCA_data run code.  


# Running environment

python==3.6.2  
pandas == 1.1.5  
numpy==1.19.5  
networkx==2.5.1  
scikit-learn == 0.24.2  
keras==2.2.4  
tensorflow==1.12.0  
