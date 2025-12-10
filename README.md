# Zero-shot-Background-Subtraction
Implementation of the Paper ["ZBS: Zero-shot Background Subtraction via Instance-level Background Modeling and Foreground Selection"](https://arxiv.org/abs/2303.14679) by Yongqi An et al., published in the 2023 Computer Vision and Pattern Recognition Conference, as a part of Computer Vision coursework.

Experimental Setup used for the implementation of the project:
- Dataset: CDNet 2014 (53 sequences, 11 categories).
- Input: 50 consecutive frames from the same sequence.
- Labeling protocol: Static and shadow pixels are treated as background (negative), moving pixels as foreground (positive), and non-ROI regions are ignored.
- Universal parameters: τconf = 0.6, τmove = 0.5, τfore = 0.8 in all experiments.
- Evaluation metrics: Precision (P), Recall (R), and F-Measure (F1).
- Comparisons: ZBS results are compared with the well-known SubSENSE BGS results and the consecutive Ground Truths.

Aniket Das (AniketDas13)
