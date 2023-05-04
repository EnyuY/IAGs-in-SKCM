# IAGs-in-SKCM
Machine learning modeling and prognostic value analysis of invasion-related genes in cutaneous melanoma

available as interactives Google Colab notebooks:

# [Machine learning modeling and prognostic value analysis of invasion-related genes in cutaneous melanoma](https://colab.research.google.com/drive/1PqikmkMxX1vdBiRFSEuL2ALBnTQL4gaF?usp=sharing)

**Authors**: Enyu Yang, Qianyun Ding, Shuo Zhao, Cheng Xuan, Haihan Ye, Xiaowei Fan, Jun Cao+, Meiyu Fang+, Xianfeng Ding+ <a href="https://orcid.org/0000-0003-1119-3816" target="_blank"><img alt="ORCID logo" src="https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png"></a>

<p>
  We used the Python (version 3.10.11) and PyCaret (version 3.0.0) to build the machine learning pipeline. The dataset was preprocessed, and we addressed the class imbalance issue using the Synthetic Minority Over-sampling Technique (SMOTE). We also used the MinMaxScaler from the sklearn (version 1.2.2) to normalize the selected features. The features used for model development included clinical characteristics such as age, gender, T stage, N stage, and M stage, as well as the expression levels of 20 invasion-associated genes. We trained and compared the performance of 15 classification algorithms to select the optimal model for predicting SKCM patient prognosis.
</p>
