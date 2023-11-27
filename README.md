### A summarization of lung nodule prediction in spatio-Temporal network

![](https://img.shields.io/badge/-Github-181717?style=flat-square&logo=Github&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=Python&logoColor=FFFFFF)
![](https://img.shields.io/badge/-Pytorch-EE4C2C?style=flat-square&logo=Pytorch&logoColor=FFFFFF)





## Summarize
+ **On the performance of lung nodule detection, segmentation and classification**
  
  *Dongdong Gu, Guocai Liu, Zhong Xue*

  Computerized Medical Imaging and Graphics 2021 .[[PDF]](https://www.sciencedirect.com/science/article/pii/S0895611121000343)

+ **Deep learning for time series classification: a review**

  *Hassan Ismail Fawaz, Germain Forestier,Jonathan Weber,Lhassane Idoumghar,Pierre-Alain Muller*

  Data Mining and Knowledge Discovery 2019 .[[PDF]](https://link.springer.com/article/10.1007/s10618-019-00619-1)
  
## Prediction of pulmonary nodules combined with spatiotemporal networks
+ **⭐MSTS-Net: malignancy evolution prediction of pulmonary nodules from longitudinal CT images via multi-task spatial-temporal self-attention network**

  *Ping Song, Jiaxin Hou, Ning Xiao, Jun Zhao, Juanjuan Zhao, Yan Qiang & Qianqian Yang*

  International Journal of Computer Assisted Radiology and Surgery 2022 .[[PDF]](https://link.springer.com/article/10.1007/s11548-022-02744-7#article-info)

+ **⭐Lung Nodule Malignancy Prediction From Longitudinal CT Scans With Siamese Convolutional Attention Networks**

  *Benjamin P. Veasey,Justin Broadhead,Michael Dahle,Albert Seow,Amir A. Amini*

  IEEE Open Journal of Engineering in Medicine and Biology 2020 .[[PDF]](https://ieeexplore.ieee.org/document/9195164)

+ **⭐Siamese Encoder-based Spatial-Temporal Mixer for Growth Trend Prediction of Lung Nodules on CT Scans**

  *Jiansheng Fang, Jingwen Wang, Anwei Li, Yuguang Yan, Yonghe Hou, Chao Song, Hongbo Liu, Jiang Liu*

  Medical Image Computing and Computer Assisted Intervention 2022 .[[PDF]](https://link.springer.com/chapter/10.1007/978-3-031-16431-6_46) [[Github]](https://github.com/liaw05/STMixer)

+ **Deep learning-based growth prediction for sub-solid pulmonary nodules on CT images**

  *Ri-qiang Liao,An-wei Li,Hong-hong Yan, Jun-tao Lin, Si-yang Liu, Jing-wen Wang, Jian-sheng Fang, Hong-bo Liu, Yong-he Hou, Chao Song, Hui-fang Yang, Bin Li, Ben-yuan Jiang, Song Dong, Qiang Nie, Wen-zhao Zhong, Yi-long Wu, Xue-ning Yang*

  Frontiers in Oncology 2022 .[[PDF]](https://www.frontiersin.org/journals/oncology/articles/10.3389/fonc.2022.1002953/full)




## spatiotemporal networks
+ **PredRNN: A Recurrent Neural Network for Spatiotemporal Predictive Learning**

  *Y Wang, H Wu, J Zhang, Z Gao, J Wang, SY Philip, M Long*

  IEEE Transactions on Pattern Analysis and Machine Intelligence 2022 .[[PDF]](https://ieeexplore.ieee.org/abstract/document/9749915/)[[Github]](https://github.com/thuml/predrnn-pytorch)

+ **Video Summarization With Spatiotemporal Vision Transformer**

  *TC Hsu, YS Liao, CR Huang*

  IEEE Transactions on Image Processing 2023 .[[PDF]](https://ieeexplore.ieee.org/abstract/document/10124837/)[[Github]](https://github.com/nchucvml/STVT)



## Encoder-Decoder
+ **Parameterized Gompertz-guided Morphological AutoEncoder for Predicting Pulmonary Nodule Growth**

  *Jiansheng Fang, Jingwen Wang, Anwei Li, Yuguang Yan, Hongbo Liu, Jiajian Li, Huifang Yang, Yonghe Hou, Xuening Yang, Ming Yang ,Jiang Liu*

  IEEE Transactions on Medical Imaging 2023 .[[PDF]](https://ieeexplore.ieee.org/abstract/document/10189348/authors#authors)

## 3D Convolutional Neural Network
+ **Pulmonary Nodule Detection Based on RPN with Squeeze-and-Excitation Block**

  *Xiaoxi Lu, Xingyue Wang, Jiansheng Fang, Na Zeng, Yao Xiang, Jingfeng Zhang, Jianjun Zheng, Jiang Liu*

  ICCCV '22: Proceedings of the 5th International Conference on Control and Computer Vision 2022 .[[PDF]](https://dl.acm.org/doi/abs/10.1145/3561613.3561627)

+ **Dual Convolutional Neural Network for Lung Nodule Classification**

  *Pengxiang Shi, Wenhui Yu, Yang Liu, Zheng Qin*

  International Joint Conference on Neural Networks 2021 .[[PDF]](https://ieeexplore.ieee.org/abstract/document/9533336)

## LSTM
+ **Ensemble framework based on attributes and deep features for benign-malignant classification of lung nodule**

  *Jianping Qiao,Yanling Fan, Mowen Zhang, Kunlun Fang, Dengwang Li,Zhishun Wang*

  Biomedical Signal Processing and Control 2022 .[[PDF]](https://www.sciencedirect.com/science/article/pii/S1746809422006711)

+ **⭐Study on the Prediction Method of Long-term Benign and Malignant Pulmonary Lesions Based on LSTM**

  *Xindong Liu,Mengnan Wang,Rukhma Aftab*
  
  Frontiers in Bioengineering and Biotechnology 2022 .[[PDF]](https://www.frontiersin.org/articles/10.3389/fbioe.2022.791424/full)


## Graph Convolutional Network


## Datasets

### CT
|                    Dataset                 |                  Source                             | Private or Oublic |  Number of Studies/Patients  |                                      Link                                              |
|:------------------------------------------:|:---------------------------------------------------:|:-----------------:|:----------------------------:|:--------------------------------------------------------------------------------------:|
|                   LIDC-IDRI                |              National Cancer Institute              |       Public      |           1318/1010          |               https://wiki.cancerimagingarchive.net/display/Public/LIDC-IDRI           |
|                    LUNA16                  |A subset of LIDC-IDRI containing thin-slice CT images|       Public      |            888/-             |                            https://luna16.grand-challenge.org/                         |
|    National Lung Screening Trial (NLST)    |              National Cancer Institute              |       Public      |         75,000/25,000        |                               https://cdas.cancer.gov/nlst/                            |
|Non-Small Cell Lung Cancer(NSCLC) Radiomics |                          TCIA                       |       Public      |            422/422           |           https://wiki.cancerimagingarchive.net/display/Public/NSCLC-Radiomics         |
|               Lung CT-Diagnosis            |              Moffitt Cancer Center, TCIA            |       Public      |             61/61            |           https://wiki.cancerimagingarchive.net/display/Public/LungCT-Diagnosis        |
|                Lung-PET-CT-DX              |                          TCIA                       |       Public      |            449/363           |       https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=70224216      |
|              TCGA-LUSC & LUAD              |                       ISS groups                    |       Public      |         74/37; 152/69        |          https://wiki.cancerimagingarchive.net/display/Public/TCGA-LUSC(LUAD)          |
|          SPIE-AAPM Lung CT Challeng        |                          AAPM                       |       Public      |             70/70            |     https://wiki.cancerimagingarchive.net/display/Public/SPIE-AAPM+Lung+CT+Challenge   |
|             Lung CT Segmentation           |                 AAPM/LCTSC, MD Anderson             |       Public      |             60/60            |https://wiki.cancerimagingarchive.net/display/Public/Lung+CT+Segmentation+Challenge+2017|
