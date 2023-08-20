# PROJECT-S
Q &amp; I of different deverb algos for MESSL source separation

Step 1: 

Separate the mixture of two sounds(Target from Grid corpus) and Masker (from TIMIT dataset) by using one of either six algorithms: 1) MESSLONLY.m, 2)PrePE.m (Mixture dereverberated by Precedence effect and separated by MESSL), 3) PreMINT.m (Mixture dereverberated by MINT and separated by MESSL), 4). PreSMIF (Mixture dereverberated by SMIF and separated by MESSL), 5). PreSS.m (Mixture dereverberated by Spectral Subtraction and separated by MESSL), 6) PreWPE.m (Mixture dereverberated by Weighted Prediction Error and separated by MESSL).

Step 2: 

Apply the evaluation metrics in intelligibility and quality folders for objective evaluation.

Step 3: 

All estimated sources, anchors, and references are sent to listeners via email along with an Excel sheet (given in the repository) for identifying the keywords in each estimated source file along with the set of instructions to perform listening Tests.

Step 4: 

A single mixture in all rooms is loaded into the PEASS toolkit as a single instance for the subjective listening test.

Step 5:

The objective and subjective results are averaged and Pearson's correlation between them is calculated.

Cite As: •	M. S. Fulaly, S. Gul, M. S. Khan, A. Ur-Rehman and S. W. Shah, "On evaluation of dereverberation algorithms for expectation-maximization based binaural source separation in varying echoic conditions," 2022 International Conference on Frontiers of Information Technology (FIT), Islamabad, Pakistan, 2022, pp. 201-206, doi: 10.1109/FIT57066.2022.00045. 
