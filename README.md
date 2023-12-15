# Assess-Compressor
This repository contains the code and data for the paper "What is Lost in Knowledge Distillation for Pre-trained Code Models"


## Clone Detection and Defect Detection
We directly use the official implementation of [Compressor](https://github.com/soarsmu/Compressor) to compress the CodeBERT and GraphCodeBERT model into smaller sizes such as 3MB and 50MB.

## Exception Type
Following the work of [Niu et al.](https://arxiv.org/abs/2302.04026), we also conduct experiements on the exception type prediciton task.

## Code Classification
We use three different datasets in our code classification experiments, namely POJ104, Java250 and Python800. The datasets can be downloaded from the following sources:

* POJ104: https://github.com/microsoft/CodeXGLUE/tree/main/Code-Code/Clone-detection-POJ-104
* Java250 and Python800: https://github.com/IBM/Project_CodeNet


## Natural Attack (ALERT)
We employ a state-of-the-art natural attack method for pre-trained code models, [ALERT](https://github.com/soarsmu/attack-pretrain-models-of-code), to evaluate the robustness of the compressed models.





## Acknowledgement
We appreciate the authors, Shi et al., of the [_Compressing Pre-trained Models of Code into 3 MB_](https://arxiv.org/abs/2208.07120) for making their datasets and code publicly available. Our code repository is based on the code in the project of [Compressor](https://github.com/soarsmu/Compressor)

We also appreciate the authors, Yang et al., of the [_Natural Attack for Pre-trained Models of Code_](https://arxiv.org/abs/2208.07120) for making their datasets and code publicly available. 
