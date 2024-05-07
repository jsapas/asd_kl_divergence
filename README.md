
#  anomaly detection
- Each sound is represented by an Gaussian distribution of MFCCs
- The dissimilarity of each sound pair is measured by KL divergence
- Anomaly score is determined by the most similar normal sound of the same category

# Test KL method from:
https://dcase.community/documents/challenge2020/technical_reports/DCASE2020_Zhao_2_t2.pdf
