Before running the script on google colab, download these reduced databases created from the public data available on Phagescope (https://phagescope.deepomics.org/download), and keep them in your main My Drive, as they are required for the code tu run:
- https://drive.google.com/file/d/1g3gbYUp_GDmMT587LC0j6Y9qTF2tzv0m/view?usp=sharing (database with infection protein sequences)
- https://drive.google.com/file/d/19FDHLSgKgBYkqxSmAcvqv1MSfMPU6SRm/view?usp=sharing
- https://drive.google.com/file/d/1_mnUoMlvNHkzPRMWISDB_mCEk80XAa4u/view?usp=sharing
- https://drive.google.com/file/d/1-2PQ30-_ssvHJYHPmgqwOOUYz-wReaWX/view?usp=sharing


This project focuses on developing a machine learning model to predict or design bacteriophages (phages) targeting specific bacterial receptors, with an emphasis on phage antireceptors and their corresponding bacterial receptors. The model will blend two approaches: detecting antireceptors in prophages within bacterial genomes and proposing candidate phages from related bacterial species with similar receptors. These two approaches will, when possible, cross-validate each other to enhance prediction accuracy. Data from PhageScope and PHASTEST will be used to train and validate the model. Key machine learning concepts such as feature extraction, classification, and model evaluation will be applied.

Motivation: Phages can be used for precision-targeted gene delivery to bacteria, but accurately identifying or designing phages for specific bacterial receptors remains a challenge. This project aims to improve phage prediction and design by focusing on phage antireceptor-bacterial receptor interactions and leveraging data from closely related bacterial species. By blending and cross-validating two complementary approaches—prophage antireceptor identification and receptor similarity across species—we seek to create more reliable models for phage therapy and gene delivery applications.

Problem Statement: The problem is how to accurately predict or design bacteriophages capable of targeting specific bacterial receptors for use in gene delivery. The challenge includes identifying the antireceptor of prophages within bacterial genomes and recommending phages based on related bacterial species with similar receptors. By blending these two solutions, the model aims to provide robust predictions that can be cross-validated when possible
