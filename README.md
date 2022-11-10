# mBERT and Simple Post-Processing: A Baseline for Disease Mention Detection in Spanish

Authors:

Antonio Tamayo (ajtamayo2019@ipn.cic.mx, ajtamayoh@gmail.com)

Diego A. Burgos (burgosda@wfu.edu)

Alexander Gelbulkh (gelbukh@gelbukh.com)

For bugs or questions related to the code, do not hesitate to contact us (Antonio Tamayo: ajtamayoh@gmail.com)

If you use this code please cite our work:

Tamayo, A., Burgos, D. A., & Gelbukh, A. (2022). mbert and simple post-processing: A baseline for disease mention detection in spanish. In Working Notes of Conference and Labs of the Evaluation (CLEF) Forum. CEUR Workshop Proceedings.

## Abstract

Automatic disease mention extraction is a relevant task due to its various applications in the medical field. During the last decade, many related works have been published, which have accelerated the progress of this research area, but most of them have been carried out in English. In this work, we propose a deep-learning baseline for this task in Spanish. We report an approach based on transfer learning using multilingual BERT and a straightforward post-processing to tackle the problem. Our system does not use any external resources and rely only on efficient fine tuning, which makes it a fair baseline (Micro F1 = 0.5456) for disease mention identification in Spanish using transformer-based models. 

### How to use our model

Option 1: [Hugging Face Space](https://huggingface.co/spaces/ajtamayoh/NLP-CIC-WFU-DisTEMIST)

Option 2: [Hugging Face Model](https://huggingface.co/ajtamayoh/NER_EHR_Spanish_model_Mulitlingual_BERT)

### How to replicate our experiments

[source code](https://github.com/ajtamayoh/NLP-CIC-WFU-Contribution-to-DisTEMIST-shared-task-2022/blob/main/Code.ipynb)
