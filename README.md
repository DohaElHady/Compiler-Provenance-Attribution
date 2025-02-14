# Compiler Provenance using Machine and Deep Learning
<a href="https://colab.research.google.com/drive/1W0lxYgrZLlm5yIoA5LSMplBQoa4XyqF2"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

**Problem:**
Identifying the compiler family and optimization level is a crucial phase for malware analysis and reverse engineering. Cracking binary files for extracting provenance information supports a faster detection of malware files. <br /><br />
**Methodologies:**
1.  Feature engineering was carried out by Strings and the Ndisasm disassembler through Linex command-line. 
2.  Feature selection through ANOVA and Chi-squared was implemented.
3.  Feature pre-processing including data balancing and standardization were deployed.
4.  Logistic Regression, Support Vector Machines (SVM), Multi-Layer Perceptron (MLP), Decision tree, AdaBoost classifier, Random forest, and ensemble learning were exploited for the two classification tasks. 
5.  Optimization classification problem was tested over deep learning.

**Results:**
The best test accuracy of 100% was achieved by the stacking model for the classification of the compiler family, and 85.9%  for the optimization level by the deep learning model.<br /> 

<p align="left"> 
<img src="https://github.com/MohamedElahl/Compiler-provenance-using-machine-learning/blob/main/assets/compiler%20family%20results.png" alt="Compiler Family Confusion Matrix" width="500" height="500"/> 
<img src="https://github.com/MohamedElahl/Compiler-provenance-using-machine-learning/blob/main/assets/optimization%20level%20results.png" alt="optimization level results" width="500" height="500"/></p>


## Dataset
BinComp compiler fingerprinting dataset. https://github.com/BinSigma/BinComp/tree/master/Dataset.

Disassembled and strings csv files are available upon request.

[Request Compiler Provenance CSV Dataset!](mailto:dohaelhady14@gmail.com,zezo.elahl@gmail.com,hassan.mohamed21997@gmail.com,karimbadreldin98@gmail.com?subject=Request%20Compiler%20Provenance%20CSV%20Dataset) 


## Contributors
[Mohamed Elahl](https://github.com/MohamedElahl) - [Hassan Mohamed](https://github.com/Hsnmhmd) - [Karim Youssef](https://github.com/KarimYoussef98) - [Doha ElHady](https://github.com/DohaElHady)
