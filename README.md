
# WESAD
Analysis of Heart Rate Variability (HRV) and Electrodermal Acitivity (EDA) from [WESAD](https://www.eti.uni-siegen.de/ubicomp/papers/ubi_icmi2018.pdf)

Google Colab - [Link](https://colab.research.google.com/drive/10RiRR5a0X7DUewiXbAfUVMeg36Qi9cyv?usp=sharing)

### Understanding the Data

In this analysis, I will be using the [WESAD dataset](https://ubicomp.eti.uni-siegen.de/home/datasets/icmi18/), a comprehensive dataset that includes heart rate, electrodermal activity (EDA), and movement data collected from wrist-worn (Empatica E4) and chest-worn sensors. The primary purpose of this dataset is to facilitate the identification of stress and affective states from these physiological signals. The data was collected from 15 participants who underwent various conditions: baseline, stress, amusement, and meditation.

The objective of this analysis is to determine whether heart rate and EDA data can reveal physiological distinctions between the baseline, stress, and meditation conditions.

Specifically, we will:

1.  **Measure Time and Frequency Domain Features of Heart Rate (HR)**: By analyzing the HR data, we aim to extract meaningful features that can indicate different physiological states.
    
2.  **Analyze SCR and SCL of EDA**: SCR (Skin Conductance Response) reflects immediate reactions to stimuli, while SCL (Skin Conductance Level) indicates overall arousal levels. Both metrics are crucial for understanding stress responses.
    
3.  **Apply Dimensionality Reduction Techniques**: Using t-SNE, UMAP, and Autoencoders, we will reduce the dimensionality of the data to visualize and identify potential physiological distinctions between the baseline, stress, and meditation conditions.
    

The findings from this analysis will help in understanding how different physiological signals can be used to distinguish between various emotional and stress-related states.
