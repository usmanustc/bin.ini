# Bin.INI
_Welcome to this repository !_ 

This repository contains the code and data used in the paper:

__Bin.INI: An Ensemble Approach for Dynamic Data Streams__, Submitted to Expert Systems with Applications, 2024. 

The main code file is available at the root folder in the form of Jupyter Notebook. The code is written in Python and may require some libraries to be installed prior to running. The data streams used in the experiments are also available in a folder at root. The synthetic data streams could be generated using MOA Framework with the scripts given in the folder.

⚛️ __Paper Abstract__  Class imbalance and concept drifts could deteriorate the performance of classifiers in data stream learning as their co-occurrence presents a complicated learning scenario. This situation becomes more complicated if missing values appear in the data. To tackle this challenge, this paper proposes a novel ensemble method, BINary classification in Incomplete, Non-stationary, and Imbalanced data streams (Bin.INI). As part of Bin.INI, Adapt2Regress builds a linear regression models pool using completely available minority subspaces, monitored under a novel sigmoid-decay function to provide imputation support in a drifting data environment. We use Min++ to balance the data in terms of imbalance complexity, a resampling component proposed earlier. Additionally, the 2-STage Ensemble Pruning technique (2STEP) is proposed which groups the classifiers based upon multiple diversity measures at the first step and selects the best subset using a novel custom metric, Sigmoid-Weighted Imbalance Score, at the second step. By using Adapt2Regress, Min++, and 2STEP, the proposed method can efficiently deal with incomplete, imbalanced, and drifting data in data streams. Experiments are conducted on 350 highly imbalanced data streams containing a variety of concept drifts. 300/350 data streams contain different ratios of missing data (5-30\%) in the minority space. Experiments reveal a noticeable decline in the performance of state-of-the-art approaches when faced with 15\% or more missing data, while Bin.INI maintains its performance.

__Paper Link:__ http://dx.doi.org/10.2139/ssrn.4741249 (PrePrint)

__Authors:__ Muhammad Usman, Huanhuan Chen

🗳️ __For any queries:__ muhammadusman@mail.ustc.edu.cn
