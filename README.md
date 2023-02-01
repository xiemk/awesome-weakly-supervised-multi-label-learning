# Awesome Weakly-Supervised Multi-Label Learning List 

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of papers & ressources related to weakly supervised multi-label learning, including multi-label learning with missing labels, single positive multi-label learning, partial multi-label learning, multi-label learning with noisy labels, and multi-label zero/few-shot learning.

**Note that:**
- **This list only contains deep methods.**
- **This list is not exhaustive.**
- **Papers use alphabetical order for fairness.**

## Contents

- [Multi-Label Learning with Missing (Partial) Labels](#papers-mlml)
- [Single Positive Multi-Label Learning](#papers-spml)
- [Partial Multi-Label Learning](#papers-pml)
- [Multi-Label Learning with Noisy Labels](#papers-mllnl)
- [Other Settings](#paper-other)
<!-- - [Multi-Label Zero/Few-Shot Learning](#papers-mlzsl) -->
	

<a name="papers-mlml"></a>
## Multi-Label Learning with Missing (Partial) Labels

#### 2022
  
- [DualCoOp: Fast Adaptation to Multi-Label Recognition with Limited Annotations](https://openreview.net/pdf?id=QnajmHkhegH). Ximeng Sun, Ping Hu, Kate Saenko. (**NeurIPS 2022**). [[Code]](https://github.com/sunxm2357/DualCoOp).

- [Multi-label Classification with Partial Annotations using Class-aware Selective Loss](https://openaccess.thecvf.com/content/CVPR2022/papers/Ben-Baruch_Multi-Label_Classification_With_Partial_Annotations_Using_Class-Aware_Selective_Loss_CVPR_2022_paper.pdf). Emanuel Ben-Baruch, Tal Ridnik. (**CVPR 2022**). [[Code]](https://github.com/Alibaba-MIIL/PartialLabelingCSL).

- [Revisiting Vicinal Risk Minimization for Partially Supervised Multi-Label Classification Under Data Scarcity](https://openaccess.thecvf.com/content/CVPR2022W/L3D-IVU/papers/Dong_Revisiting_Vicinal_Risk_Minimization_for_Partially_Supervised_Multi-Label_Classification_Under_CVPRW_2022_paper.pdf). Nanqing Dong, Jiayi Wang, Irina Voiculescu. (**CVPR 2022**). [[Code]](https://github.com/palm-ml/smile).
  
- [Robust Recurrent Classifier Chains for Multi-Label Learning with Missing Labels](https://dspace.mit.edu/bitstream/handle/1721.1/146499/3511808.3557438.pdf?sequence=1&isAllowed=y). Walter Gerych, Thomas Hartvigsen, Luke Buquicchio, Emmanuel Agu, Elke Rundensteiner. (**CIKM 2022**).

- [Semantic-Aware Representation Blending for Multi-Label Image Recognition with Partial Labels](https://ojs.aaai.org/index.php/AAAI/article/view/20105). Tao Pu, Tianshui Chen, Hefeng Wu, Liang Lin. (**AAAI 2022**). [[Code]](https://github.com/HCPLab-SYSU/HCP-MLR-PL).

- [Structured Semantic Transfer for Multi-Label Recognition with Partial Labels](https://ojs.aaai.org/index.php/AAAI/article/view/19910). Tianshui Chen, Tao Pu, Hefeng Wu, Yuan Xie, Liang Lin. (**AAAI 2022**). [[Code]](https://github.com/HCPLab-SYSU/HCP-MLR-PL).


- [Heterogeneous Semantic Transfer for Multi-label Recognition with Partial Labels](https://openreview.net/pdf?id=QnajmHkhegH). Tianshui Chen, Tao Pu, Lingbo Liu, Yukai Shi, Zhijing Yang, Liang Lin. (**arXiv 2022**).
  
#### 2021

- [General multi-label image classification with transformers](https://openaccess.thecvf.com/content/CVPR2021/papers/Lanchantin_General_Multi-Label_Image_Classification_With_Transformers_CVPR_2021_paper.pdf). Jack Lanchantin, Tianlu Wang, Vicente Ordonez, Yanjun Qi. (**CVPR 2021**). [[Code]](https://github.com/QData/C-Tran).

- [Simple and Robust Loss Design for Multi-Label Learning with Missing Labels](https://arxiv.org/pdf/2112.07368.pdf). Youcai Zhang, Yuhao Cheng, Xinyu Huang, Fei Wen, Rui Feng, Yaqian Li, and Yandong Guo. (**arXiv 2021**). [[Code]](https://github.com/xinyu1205/robust-loss-mlml).



#### 2020
- [Interactive Multi-Label CNN Learning With Partial Labels](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huynh_Interactive_Multi-Label_CNN_Learning_With_Partial_Labels_CVPR_2020_paper.pdf). Dat Huynh, Ehsan Elhamifar. (**CVPR 2020**). [[Code]](https://github.com/hbdat/cvpr20_IMCL).

#### 2019

- [Learning a Deep ConvNet for Multi-label Classification with Partial Labels](https://openaccess.thecvf.com/content_CVPR_2019/papers/Durand_Learning_a_Deep_ConvNet_for_Multi-Label_Classification_With_Partial_Labels_CVPR_2019_paper.pdf). Thibaut Durand, Nazanin Mehrasa, Greg Mori. (**CVPR 2019**).

- [A Pseudo-Label Method for Coarse-to-Fine Multi-Label Learning with Limited Supervision ](https://openreview.net/pdf?id=rylVYjqHdN). Cheng-Yu Hsieh, Miao Xu, Gang Niu, Hsuan-Tien Lin, Masashi Sugiyama. (**ICLRW 2019**).

#### 2018
- [Deep Generative Models for Weakly-Supervised Multi-Label Classification](https://openaccess.thecvf.com/content_ECCV_2018/papers/Hong-Min_Chu_Deep_Generative_Models_ECCV_2018_paper.pdf). Hong-Min Chu, Chih-Kuan Yeh, and Yu-Chiang Frank Wang. (**ECCV 2018**).

#### 2016
- [Multi-label Ranking from Positive and Unlabeled Data](https://openaccess.thecvf.com/content_cvpr_2016/papers/Kanehira_Multi-Label_Ranking_From_CVPR_2016_paper.pdf). Atsushi Kanehira, and Tatsuya Harada. (**CVPR 2016**).

<a name="papers-spml"></a>
## Single Positive Multi-Label Learning

- [Acknowledging the Unknown for Multi-label Learning with Single Positive Labels](https://arxiv.org/pdf/2203.16219.pdf). Donghao Zhou, Pengfei Chen, Qiong Wang, Guangyong Chen, Pheng-Ann Heng. (**ECCV 2022**). [[Code]](https://github.com/Correr-Zhou/SPML-AckTheUnknown).

- [Label-Aware Global Consistency for Multi-Label Learning with Single Positive Labels](http://www.xiemk.pro/publication/neurips22-lac.pdf). Ming-Kun Xie, Jia-Hao Xiao, Sheng-Jun Huang. (**NeurIPS 2022**). [[Code]](https://github.com/milkxie/SPML-LAC).
  
- [Large Loss Matters in Weakly Supervised Multi-Label Classification](https://openaccess.thecvf.com/content/CVPR2022/papers/Kim_Large_Loss_Matters_in_Weakly_Supervised_Multi-Label_Classification_CVPR_2022_paper.pdf). Youngwook Kim, Jae Myung Kim, Zeynep Akata, Jungwoo Lee. (**CVPR 2022**). [[Code]](https://github.com/snucml/LargeLossMatters).

- [Multi-Label Learning from Single Positive Labels](https://openaccess.thecvf.com/content/CVPR2021/papers/Cole_Multi-Label_Learning_From_Single_Positive_Labels_CVPR_2021_paper.pdf). Elijah Cole, Oisin Mac Aodha, Titouan Lorieul, Pietro Perona, Dan Morris, Nebojsa Jojic. (**CVPR 2021**). [[Code]](https://github.com/elijahcole/single-positive-multi-label).
  
- [One Positive Label is Sufficient: Single-Positive Multi-Label Learning with Label Enhancement](https://arxiv.org/pdf/2206.00517.pdf). Ning Xu, Congyu Qiao, Jiaqi Lv, Xin Geng, Min-Ling Zhang. (**NeurIPS 2022**). [[Code]](https://github.com/palm-ml/smile).

- [Spatial Consistency Loss for Training Multi-Label Classifiers from Single-Label Annotations](https://openaccess.thecvf.com/content/WACV2023/papers/Verelst_Spatial_Consistency_Loss_for_Training_Multi-Label_Classifiers_From_Single-Label_Annotations_WACV_2023_paper.pdf). Thomas Verelst, Paul K. Rubenstein, Marcin Eichner, Tinne Tuytelaars, Maxim Berman. (**WACV 2023**). [[Code]](https://github.com/CASIA-IVA-Lab/Obj2Seq).

- [A Patch-Based Architecture for Multi-Label Classification from Single Label Annotations](https://arxiv.org/pdf/2209.06530.pdf). Warren Jouanneau, Aurélie Bugeau, Marc Palyart, Nicolas Papadakis, Laurent Vézard. (**arXiv 2022**).

<a name="papers-pml"></a>
## Partial Multi-Label Learning

- [A Deep Model for Partial Multi-Label Image Classification with Curriculum Based Disambiguation.](http://www.xiemk.pro/publication/arxiv-cdcr-preprint.pdf). Feng Sun, Ming-Kun Xie, and Sheng-Jun Huang. (**arXiv 2022**).
  
- [Partial Multi-Label Learning with Meta Disambiguation](http://www.xiemk.pro/publication/kdd21-pmlmd.pdf). Ming-Kun Xie, Feng Sun, and Sheng-Jun Huang. (**KDD 2021**).

<a name="papers-mllnl"></a>
## Multi-Label Learning with Noisy Labels

- [CCMN: A General Framework for Learning with Class-Conditional Multi-Label Noise](http://www.xiemk.pro/publication/tpami-ccmn-preprint.pdf). Ming-Kun Xie, Sheng-Jun Huang. (**TPAMI 2022**). [[Code]](http://www.xiemk.pro).

- [Estimating Noise Transition Matrix with Label Correlations for Noisy Multi-Label Learning](https://openreview.net/pdf?id=GwXrGy_vc8m). Shikun Li, Xiaobo Xia, Hansong Zhang, Yibing Zhan, Shiming Ge, Tongliang Liu. (**NeurIPS 2022**). [[Code]](https://github.com/ShikunLi/Estimating_T_For_Noisy_Mutli-Labels).

- [Weakly Supervised Image Classification through Noise Regularization](https://openaccess.thecvf.com/content_CVPR_2019/papers/Hu_Weakly_Supervised_Image_Classification_Through_Noise_Regularization_CVPR_2019_paper.pdf). Mengying Hu, Hu Han, Shiguang Shan, Xilin Chen. (**CVPR 2019**).
  
- [Evaluating Multi-label Classifiers with Noisy Labels](https://arxiv.org/pdf/2102.08427.pdf). Wenting Zhao, Carla Gomes. (**arXiv 2021**).

- [Learning from Noisy Labels with Noise Modeling Network](https://arxiv.org/pdf/2005.00596.pdf). Zhuolin Jiang, Jan Silovsky, Man-Hung Siu, William Hartmann, Herbert Gish, Sancar Adali. (**arXiv 2020**).
  
<a name="papers-other"></a>
## Other Settings

- [Multi-label Iterated Learning for Image Classification with Label Ambiguity](https://openaccess.thecvf.com/content/CVPR2022/papers/Rajeswar_Multi-Label_Iterated_Learning_for_Image_Classification_With_Label_Ambiguity_CVPR_2022_paper.pdf). Sai Rajeswar, Pau Rodríguez, Soumye Singhal, David Vazquez, Aaron Courville. (**CVPR 2022**).

<!-- <a name="papers-mlzsl"></a>
## Multi-Label Zero/Few-Shot Learning

#### 2023
- [Open-Vocabulary Multi-Label Classification via Multi-modal Knowledge Transfer](https://arxiv.org/pdf/2207.01887.pdf). Sunan He, Taian Guo, Tao Dai3, Ruizhi Qiao, Bo Ren, Shu-Tao Xia. (**AAAI 2023**). [[Code]](https://github.com/sunanhe/MKT).

#### 2021
- [Discriminative Region-based Multi-Label Zero-Shot Learning](https://openaccess.thecvf.com/content/ICCV2021/papers/Narayan_Discriminative_Region-Based_Multi-Label_Zero-Shot_Learning_ICCV_2021_paper.pdf). Sanath Narayan, Akshita Gupta, Salman Khan, Fahad Shahbaz Khan, Ling Shao, Mubarak Shah. (**ICCV 2021**). [[Code]](https://github.com/akshitac8/BiAM).

- [Semantic Diversity Learning for Zero-Shot Multi-label Classification](https://openaccess.thecvf.com/content/ICCV2021/papers/Ben-Cohen_Semantic_Diversity_Learning_for_Zero-Shot_Multi-Label_Classification_ICCV_2021_paper.pdf). Avi Ben-Cohen, Nadav Zamir, Emanuel Ben Baruch, Itamar Friedman, Lihi Zelnik-Manor. (**ICCV 2021**). [[Code]](https://github.com/Alibaba-MIIL/ZS_SDL).

#### 2020

- [A Shared Multi-Attention Framework for Multi-Label Zero-Shot Learning](https://openaccess.thecvf.com/content_CVPR_2020/papers/Huynh_A_Shared_Multi-Attention_Framework_for_Multi-Label_Zero-Shot_Learning_CVPR_2020_paper.pdf). Dat Huynh, Ehsan Elhamifar. (**CVPR 2020**). [[Code]](https://github.com/hbdat/cvpr20_LESA).
  
- [Knowledge-Guided Multi-Label Few-Shot Learning for General Image Recognition](https://arxiv.org/pdf/2009.09450.pdf). Tianshui Chen, Liang Lin, Riquan Chen, Xiaolu Hui, Hefeng Wu. (**TPAMI 2020**). [[Code]](https://github.com/Alibaba-MIIL/ZS_SDL).

- [Multi-label Zero-shot Classification by Learning to Transfer from External Knowledge](https://www.bmvc2020-conference.com/assets/papers/0249.pdf). He Huang, Yuanwei Chen, Wei Tang, Wenhao Zheng, Qing-Guo Chen, Philip Yu. (**BMCV 2020**). [[Code]](https://github.com/stevehuanghe/multi_label_zsl). -->













