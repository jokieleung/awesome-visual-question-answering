# Awesome Visual Question Answering:[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

A curated list of **Visual Question Answering(VQA)**(Image/Video Question Answering),**Visual Question Generation** ,**Visual Dialog** ,**Visual Commonsense Reasoning** and related area. 

## Contributing
Please feel free to send me [pull requests](https://github.com/jokieleung/awesome-visual-question-answering/pulls) or email (leungjokie@gmail.com) to add links.
Markdown format:
```markdown
- [Paper Name](link) - Author 1 et al, **Conference Year**. [[code]](link)
```

## Change Log

- Mar.3rd,2019 The Fist version released.

## Table of Contents
  * [Contributing](#contributing)
  * [Change Log](#change-log)
  * [Table of Contents](#table-of-contents)
  * [Papers](#papers)
     * [Survey](#survey)
     * [2019](#2019)
     * [2018](#2018)
        * [NIPS 2018](#nips-2018)
        * [AAAI 2018](#aaai-2018)
        * [IJCAI 2018](#ijcai-2018)
        * [CVPR 2018](#cvpr-2018)
        * [ACM MM 2018](#acm-mm-2018)
        * [ECCV 2018](#eccv-2018)
        * [OTHER](#other)
     * [2017-2015](#2017-2015)
        * [OTHER](#other-1)
        * [ICCV 2017](#iccv-2017)
  * [VQA Challenge Leaderboard](#vqa-challenge-leaderboard)
     * [test-std 2018](#test-std-2018)
     * [test-std 2017](#test-std-2017)
  * [Licenses](#licenses)
  * [Reference and Acknowledgement](#reference-and-acknowledgement)

## Papers
### Survey
* [Visual question answering: Datasets, algorithms, and future challenges](https://arxiv.org/abs/1610.01465) - Kushal Kafle et al, **CVIU 2017**.
* [Visual question answering: A survey of methods and datasets](https://arxiv.org/abs/1607.05910) - Qi Wu et al, **CVIU 2017**.

### 2019
* [Combining Multiple Cues for Visual Madlibs Question Answering](https://arxiv.org/abs/1611.00393) - Tatiana Tommasi et al, **IJCV 2019**. [code]
* Differential Networks for Visual Question Answering - Chenfei Wu et al, **AAAI 2019**. [code]
* BLOCK: Bilinear Superdiagonal Fusion for Visual Question Answering and Visual
Relationship Detection - Hedi Ben-younes et al, **AAAI 2019**. [code]
* Dynamic Capsule Attention for Visual Question Answering - Yiyi Zhou et al, **AAAI 2019**. [code]
* Structured Two-stream Attention Network for Video Question Answering - Lianli Gao et al, **AAAI 2019**. [code]
* Beyond RNNs: Positional Self-Attention with Co-Attention for Video Question Answering - Xiangpeng Li et al, **AAAI 2019**. [code]
*  WK-VQA: World Knowledge-enabled Visual Question Answering - Sanket Shah et al, **AAAI 2019**. [code]

### 2018
#### NIPS 2018 ####
* [Bilinear Attention Networks](https://papers.nips.cc/paper/7429-bilinear-attention-networks) - Jin-Hwa Kim et al, **NIPS 2018**. [code]
* [Chain of Reasoning for Visual Question Answering](https://papers.nips.cc/paper/7311-chain-of-reasoning-for-visual-question-answering) - Chenfei Wu et al, **NIPS 2018**. [code]
* [Learning Conditioned Graph Structures for Interpretable Visual Question Answering](https://papers.nips.cc/paper/8054-learning-conditioned-graph-structures-for-interpretable-visual-question-answering) - Will Norcliffe-Brown et al, **NIPS 2018**. [[code]](https://github.com/aimbrain/vqa-project)
* [Learning to Specialize with Knowledge Distillation for Visual Question Answering](https://papers.nips.cc/paper/8031-learning-to-specialize-with-knowledge-distillation-for-visual-question-answering) - Jonghwan Mun et al, **NIPS 2018**. [code]
* [Out of the Box: Reasoning with Graph Convolution Nets for Factual Visual Question Answering](https://papers.nips.cc/paper/7531-out-of-the-box-reasoning-with-graph-convolution-nets-for-factual-visual-question-answering) - Medhini Narasimhan et al, **NIPS 2018**. [code]
* [Overcoming Language Priors in Visual Question Answering with Adversarial Regularization](https://papers.nips.cc/paper/7427-overcoming-language-priors-in-visual-question-answering-with-adversarial-regularization) - Sainandan Ramakrishnan et al, **NIPS 2018**. [code]

#### AAAI 2018 ####
* [Explicit Reasoning over End-to-End Neural Architectures for Visual Question Answering](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16446) - Somak Aditya et al, **AAAI 2018**. [code]
* [Co-Attending Free-Form Regions and Detections with Multi-Modal Multiplicative Feature Embedding for Visual Question Answering](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16249) - Pan Lu et al, **AAAI 2018**. [[code]](https://github.com/lupantech/dual-mfa-vqa)
* [Exploring Human-Like Attention Supervision in Visual Question Answering](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16485) - Somak Aditya et al, **AAAI 2018**. [code]
* [Movie Question Answering: Remembering the Textual Cues for Layered Visual Contents](https://aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16359) - Bo Wang et al, **AAAI 2018**. [code]

#### IJCAI 2018 ####
* [Feature Enhancement in Attention for Visual Question Answering](https://www.ijcai.org/proceedings/2018/586) - Yuetan Lin et al, **IJCAI 2018**. [code]
* [A Question Type Driven Framework to Diversify Visual Question Generation](https://www.ijcai.org/proceedings/2018/563) - Zhihao Fan et al, **IJCAI 2018**. [code]
* [Multi-Turn Video Question Answering via Multi-Stream Hierarchical Attention Context Network](https://www.ijcai.org/proceedings/2018/513) - Zhou Zhao et al, **IJCAI 2018**. [code]
* [Open-Ended Long-form Video Question Answering via Adaptive Hierarchical Reinforced Networks](https://www.ijcai.org/proceedings/2018/512) - Zhou Zhao et al, **IJCAI 2018**. [code]

#### CVPR 2018 ####
* [Bottom-Up and Top-Down Attention for Image Captioning and Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Anderson_Bottom-Up_and_Top-Down_CVPR_2018_paper.html) - 	Peter Anderson et al, **CVPR 2018**. [[code(author)]](https://github.com/peteanderson80/bottom-up-attention) [[code(pythiaV0.1)]](https://github.com/facebookresearch/pythia) [[code(Pytorch Reimplementation)]](https://github.com/hengyuan-hu/bottom-up-attention-vqa)
* [Tips and Tricks for Visual Question Answering: Learnings From the 2017 Challenge](http://openaccess.thecvf.com/content_cvpr_2018/html/Teney_Tips_and_Tricks_CVPR_2018_paper.html) - Damien Teney et al, **CVPR 2018**. [code]
* [Learning by Asking Questions](http://openaccess.thecvf.com/content_cvpr_2018/html/Misra_Learning_by_Asking_CVPR_2018_paper.html) - Ishan Misra et al, **CVPR 2018**. [code]
* [Embodied Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Das_Embodied_Question_Answering_CVPR_2018_paper.html) - Abhishek Das et al, **CVPR 2018**. [code]
* [VizWiz Grand Challenge: Answering Visual Questions From Blind People](http://openaccess.thecvf.com/content_cvpr_2018/html/Gurari_VizWiz_Grand_Challenge_CVPR_2018_paper.html) - Danna Gurari et al, **CVPR 2018**. [code]
* [Textbook Question Answering Under Instructor Guidance With Memory Networks](http://openaccess.thecvf.com/content_cvpr_2018/html/Li_Textbook_Question_Answering_CVPR_2018_paper.html) - Juzheng Li et al, **CVPR 2018**. [[code]](https://github.com/freerailway/igmn)
* [IQA: Visual Question Answering in Interactive Environments](http://openaccess.thecvf.com/content_cvpr_2018/html/Gordon_IQA_Visual_Question_CVPR_2018_paper.html) - Daniel Gordon et al, **CVPR 2018**. [[sample video]](https://youtu.be/pXd3C-1jr98)
* [Don't Just Assume; Look and Answer: Overcoming Priors for Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Agrawal_Dont_Just_Assume_CVPR_2018_paper.html) - Aishwarya Agrawal et al, **CVPR 2018**. [code]
* [Learning Answer Embeddings for Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Hu_Learning_Answer_Embeddings_CVPR_2018_paper.html) - Hexiang Hu et al, **CVPR 2018**. [code]
* [DVQA: Understanding Data Visualizations via Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Kafle_DVQA_Understanding_Data_CVPR_2018_paper.html) - Kushal Kafle et al, **CVPR 2018**. [code]
* [Cross-Dataset Adaptation for Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Chao_Cross-Dataset_Adaptation_for_CVPR_2018_paper.html) - Wei-Lun Chao et al, **CVPR 2018**. [code]
* [Two Can Play This Game: Visual Dialog With Discriminative Question Generation and Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Jain_Two_Can_Play_CVPR_2018_paper.html) - Unnat Jain et al, **CVPR 2018**. [code]
* [Improved Fusion of Visual and Language Representations by Dense Symmetric Co-Attention for Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Nguyen_Improved_Fusion_of_CVPR_2018_paper.html) - Duy-Kien Nguyen et al, **CVPR 2018**. [code]
* [Visual Question Generation as Dual Task of Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Li_Visual_Question_Generation_CVPR_2018_paper.html) - Yikang Li et al, **CVPR 2018**. [code]
* [Focal Visual-Text Attention for Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Liang_Focal_Visual-Text_Attention_CVPR_2018_paper.html) - Junwei Liang et al, **CVPR 2018**. [code]
* [Motion-Appearance Co-Memory Networks for Video Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Gao_Motion-Appearance_Co-Memory_Networks_CVPR_2018_paper.html) - Jiyang Gao et al, **CVPR 2018**. [code]
* [Visual Question Answering With Memory-Augmented Networks](http://openaccess.thecvf.com/content_cvpr_2018/html/Ma_Visual_Question_Answering_CVPR_2018_paper.html) - Chao Ma et al, **CVPR 2018**. [code]
* [Visual Question Reasoning on General Dependency Tree](http://openaccess.thecvf.com/content_cvpr_2018/html/Cao_Visual_Question_Reasoning_CVPR_2018_paper.html) - Qingxing Cao et al, **CVPR 2018**. [code]
* [Differential Attention for Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Patro_Differential_Attention_for_CVPR_2018_paper.html) - Badri Patro et al, **CVPR 2018**. [code]
* [Learning Visual Knowledge Memory Networks for Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Su_Learning_Visual_Knowledge_CVPR_2018_paper.html) - Zhou Su et al, **CVPR 2018**. [code]
* [IVQA: Inverse Visual Question Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Liu_IVQA_Inverse_Visual_CVPR_2018_paper.html) - Feng Liu et al, **CVPR 2018**. [code]
* [Customized Image Narrative Generation via Interactive Visual Question Generation and Answering](http://openaccess.thecvf.com/content_cvpr_2018/html/Shin_Customized_Image_Narrative_CVPR_2018_paper.html) - Andrew Shin et al, **CVPR 2018**. [code]

#### ACM MM 2018 ####
* [Object-Difference Attention: A simple relational attention for Visual Question Answering](https://dl.acm.org/citation.cfm?doid=3240508.3240513) - 	Chenfei Wu et al, **ACM MM 2018**. [code]
* [Enhancing Visual Question Answering Using Dropout](https://doi.org/10.1145/3240508.3240662) - 	Zhiwei Fang et al, **ACM MM 2018**. [code]
* [Fast Parameter Adaptation for Few-shot Image Captioning and Visual Question Answering](https://doi.org/10.1145/3240508.3240527) - Xuanyi Dong et al, **ACM MM 2018**. [[code]](https://github.com/D-X-Y/FPAIT)
* [Explore Multi-Step Reasoning in Video Question Answering](https://doi.org/10.1145/3240508.3240563) - Xiaomeng Song et al, **ACM MM 2018**. [[code]](https://github.com/SVQA-founder/SVQA/tree/master/code) [[SVQA dataset]](https://svqa-founder.github.io/SVQA/)

#### ECCV 2018 ####
* [Visual Question Answering as a Meta Learning Task](http://openaccess.thecvf.com/content_ECCV_2018/html/Damien_Teney_Visual_Question_Answering_ECCV_2018_paper.html) - 	Damien Teney et al, **ECCV 2018**. [code]
* [Question-Guided Hybrid Convolution for Visual Question Answering](http://openaccess.thecvf.com/content_ECCV_2018/html/gao_peng_Question-Guided_Hybrid_Convolution_ECCV_2018_paper.html) - Peng Gao et al, **ECCV 2018**. [code]
* [Goal-Oriented Visual Question Generation via Intermediate Rewards](http://openaccess.thecvf.com/content_ECCV_2018/html/Junjie_Zhang_Goal-Oriented_Visual_Question_ECCV_2018_paper.html) - Junjie Zhang et al, **ECCV 2018**. [code]
* [Multimodal Dual Attention Memory for Video Story Question Answering](http://openaccess.thecvf.com/content_ECCV_2018/html/Kyungmin_Kim_Multimodal_Dual_Attention_ECCV_2018_paper.html) - Kyung-Min Kim et al, **ECCV 2018**. [code]
* [A Joint Sequence Fusion Model for Video Question Answering and Retrieval](http://openaccess.thecvf.com/content_ECCV_2018/html/Youngjae_Yu_A_Joint_Sequence_ECCV_2018_paper.html) - Youngjae Yu et al, **ECCV 2018**. [code]
* [Deep Attention Neural Tensor Network for Visual Question Answering](http://openaccess.thecvf.com/content_ECCV_2018/html/Yalong_Bai_Deep_Attention_Neural_ECCV_2018_paper.html) - Yalong Bai et al, **ECCV 2018**. [code]
* [Question Type Guided Attention in Visual Question Answering](http://openaccess.thecvf.com/content_ECCV_2018/html/Yang_Shi_Question_Type_Guided_ECCV_2018_paper.html) - Yang Shi et al, **ECCV 2018**. [code]
* [Learning Visual Question Answering by Bootstrapping Hard Attention](http://openaccess.thecvf.com/content_ECCV_2018/html/Mateusz_Malinowski_Learning_Visual_Question_ECCV_2018_paper.html) - Mateusz Malinowski et al, **ECCV 2018**. [code]
* [Straight to the Facts: Learning Knowledge Base Retrieval for Factual Visual Question Answering](http://openaccess.thecvf.com/content_ECCV_2018/html/Medhini_Gulganjalli_Narasimhan_Straight_to_the_ECCV_2018_paper.html) - Medhini Narasimhan et al, **ECCV 2018**. [code]
* [Visual Question Generation for Class Acquisition of Unknown Objects](http://openaccess.thecvf.com/content_ECCV_2018/html/Kohei_Uehara_Visual_Question_Generation_ECCV_2018_paper.html) - Kohei Uehara et al, **ECCV 2018**. [[code]](https://github.com/mil-tokyo/vqg-unknown)

#### OTHER ####
* [Image Captioning and Visual Question Answering Based on Attributes and External Knowledge](https://arxiv.org/abs/1603.02814) - Qi Wu et al, **TPAMI 2018**. [code]
* [FVQA: Fact-Based Visual Question Answering](https://arxiv.org/abs/1606.05433) - Peng Wang et al, **TPAMI 2018**. [code]
* [R-VQA: Learning Visual Relation Facts with Semantic Attention for Visual Question Answering](https://dl.acm.org/citation.cfm?doid=3219819.3220036) - 	Pan Lu et al, **SIGKDD 2018**. [[code(Dataset)]](https://github.com/lupantech/rvqa)
* [Interpretable Counting for Visual Question Answering](https://arxiv.org/abs/1712.08697) - Alexander Trott et al, **ICLR 2018**. [code]
* [Learning to Count Objects in Natural Images for Visual Question Answering](https://openreview.net/forum?id=B12Js_yRb) - Yan Zhang et al, **ICLR 2018**. [code]
* [A Better Way to Attend: Attention With Trees for Video Question Answering](https://ieeexplore.ieee.org/document/8419716) - Hongyang Xue et al, **TIP 2018**. [[code]](https://github.com/xuehy/TreeAttention)
* [Zero-Shot Transfer VQA Dataset](https://arxiv.org/abs/1811.00692) - 	Pan Lu et al, **arxiv preprint**. [code]

### 2017-2015
#### OTHER ####
 Please check the other papers list from VQA area between 2017-2015 in [awesome-vqa](https://github.com/JamesChuanggg/awesome-vqa) from [JamesChuanggg](https://github.com/JamesChuanggg),it seems that he hasn't maintained that project for a long time.Really appreciate for his work.I will merge his work to this list in the future.Stay tuned...

#### ICCV 2017 ####
* [Learning to Reason: End-to-End Module Networks for Visual Question Answering](https://ieeexplore.ieee.org/document/8237355) - Ronghang Hu et al, **ICCV 2017**. [code]
* [Structured Attentions for Visual Question Answering](https://ieeexplore.ieee.org/document/8237407) - Chen Zhu et al, **ICCV 2017**. [[code]](https://github.com/shtechair/vqa-sva)
* [VQS: Linking Segmentations to Questions and Answers for Supervised Attention in VQA and Question-Focused Semantic Segmentation](https://ieeexplore.ieee.org/document/8237463) - Chuang Gan et al, **ICCV 2017**. [[code]](https://github.com/Cold-Winter/vqs)
* [**Multi-modal Factorized Bilinear Pooling with Co-attention Learning for Visual Question Answering**](https://ieeexplore.ieee.org/document/8237464) - Zhou Yu et al, **ICCV 2017**. [[code]](https://github.com/yuzcccc/vqa-mfb)
* [An Analysis of Visual Question Answering Algorithms](https://ieeexplore.ieee.org/document/8237479) - Kushal Kafle et al, **ICCV 2017**. [code]
* [MUTAN: Multimodal Tucker Fusion for Visual Question Answering](https://ieeexplore.ieee.org/document/8237547) - Hedi Ben-younes et al, **ICCV 2017**. [[code]](https://github.com/cadene/vqa.pytorch)
* [MarioQA: Answering Questions by Watching Gameplay Videos](https://ieeexplore.ieee.org/document/8237574) - Jonghwan Mun et al, **ICCV 2017**. [code]
* [Learning to Disambiguate by Asking Discriminative Questions](https://ieeexplore.ieee.org/document/8237632) - Yining Li et al, **ICCV 2017**. [code]


## VQA Challenge Leaderboard
I will collect the leaderboard's implementations in the future.Stay tuned...
### test-std 2018
* [VQA Challenge 2018 Leaderboard in EvalAI](https://evalai.cloudcv.org/featured-challenges/80/leaderboard/124)
### test-std 2017
* [VQA Challenge 2017(Open-Ended) Leaderboard in EvalAI](https://evalai.cloudcv.org/featured-challenges/1/leaderboard/3)

## Licenses

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jokie Leung](https://github.com/jokieleung) has waived all copyright and related or neighboring rights to this work.

## Reference and Acknowledgement
* [**awesome-image-captioning**](https://github.com/zhjohnchan/awesome-image-captioning) from [Zhihong Chen](https://github.com/zhjohnchan)
* [**awesome-vqa**](https://github.com/JamesChuanggg/awesome-vqa) from [JamesChuanggg](https://github.com/JamesChuanggg)

Really appreciate for there contributions in this area.