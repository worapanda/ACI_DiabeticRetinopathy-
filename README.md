# ACI_DiabeticRetinopathy
This contains supplementary materials for the paper ACI-06-2022-0150 (Applied Computing and Informatics), entitled "Detecting and Staging Diabetic Retinopathy in Retinal Images using Multi-Branch CNN". Diabetic retinopathy contains a scale of 0 to 4, as below [1-2].

0: No DR

1: Mild non-proliferative

2: Moderate non-proliferative

3: Severe non-proliferative

4: Proliferative. 

This paper thus considers a classification domain with 5 classes of these 5 stages.

![figure1](https://user-images.githubusercontent.com/109519153/180480024-02e51f51-fb5c-4b79-bfc0-dcfc01e0a507.jpg)

Figure 1. An example of a CNN architecture of a single straight branch structure.

![figure2](https://user-images.githubusercontent.com/109519153/180488300-47965866-0ebc-4f24-86b5-cb72c32a22d6.jpg)

Figure 2. An example of a CNN architecture of a multi-branch structure (e.g, Siamese network).

![figure6](https://user-images.githubusercontent.com/109519153/180490026-26290062-2a49-462b-8f9a-1c4d49966b20.jpg)

Figure 3. The structure of attention layer.

References:
[1] https://www.kaggle.com/competitions/diabetic-retinopathy-detection/data

[2] Gangaputra S, Lovato JF, Hubbard L, Davis MD, Esser BA, Ambrosius WT, Chew EY, Greven C, Perdue LH, Wong WT, Condren A. Comparison of standardized clinical classification with fundus photograph grading for the assessment of diabetic retinopathy and diabetic macular edema severity. Retina (Philadelphia, Pa.). 2013 Jul;33(7).
