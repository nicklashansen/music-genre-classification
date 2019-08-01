# Audio Features for Music Genre Classification

This repository contains code and results for the exam project on Music Genre Classification for the 02452 graduate course offered at the Technical University of Denmark (DTU). Unless authorship of code and documentation is stated explicitly (e.g. in the function description), it can be assumed implemented by Nicklas Hansen.

The work presented in this repository is to be considered open source under the MIT License. If you found this code useful in your research, then please cite


```
@misc{mgc-hansen-marinosson,
  title={Audio Features for Music Genre Classification},
  author={Hansen, Nicklas and Marinosson, Bragi},
  year={2019}
}
```


### Abstract
Music genre classification is an inherently difficult task for machines as categorization is subjective and based on human perception. Typically, hand-engineered audio features are used in models that aim to automate genre annotation, but it is unclear which features best describe a genre and to which extent.

In this study, we provide a holistic view on common audio features and apply a backward feature selection using a k-nearest neighbors (KNN) classifier and features extracted from a slightly imbalanced 7-genre subset (6573 audio files) of the Free Music Archive (FMA) dataset. We then train a 20-layer DenseNet on the best-performing feature subset -- 32 Mel Frequency Cepstral Coefficents (MFCCs) -- and achieve a F1-score of 0.60, which is comparable to other studies but below human-level performance measured under similar conditions. It is observed that classification performance is highly genre-dependent, which suggests that certain genres may have similar profiles in the frequency domain.
