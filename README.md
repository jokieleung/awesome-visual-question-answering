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

- Mar.3rd,2019 The First version released.

## Table of Contents
  * [Contributing](#contributing)
  * [Change Log](#change-log)
  * [Table of Contents](#table-of-contents)
  * [Papers](#papers)
     * [Survey](#survey)
     * [2021](#2021)
        - [SIGIR 2021](#SIGIR-2021)
        - [CVPR 2021](#CVPR-2021)
        - [ICLR 2021](#ICLR-2021)
        - [NAACL-HLT 2021](#NAACL-HLT-2021)
        - [AAAI 2021](#AAAI-2021)
     * [2020](#2020)
        - [EMNLP 2020](#EMNLP-2020)
        - [NeurIPS 2020](#NeurIPS-2020)
        - [ECCV 2020](#ECCV-2020)
        - [CVPR 2020](#CVPR-2020)
        - [ACL 2020](#ACL-2020)
        - [WACV 2020](#WACV-2020)
        - [AAAI 2020](#AAAI-2020)
     * [2019](#2019)
        * [ACL 2019](#ACL-2019)
        * [ICCV 2019](#ICCV-2019)
        * [NeurIPS 2019](#NeurIPS-2019)
        * [CVPR 2019](#cvpr-2019)
        * [AAAI 2019](#aaai-2019)
        * [OTHER](#other)
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

### 2021

#### SIGIR 2021

- [LPF: A Language-Prior Feedback Objective Function for De-biased Visual Question Answering](https://arxiv.org/abs/2105.14300) - Zujie Liang et al, **SIGIR 2021**. [[code]](https://github.com/jokieleung/LPF-VQA)
- [Passage Retrieval for Outside-Knowledge Visual Question Answering](https://arxiv.org/abs/2105.03938) - Chen Qu et al, **SIGIR 2021**. [[code]](https://github.com/prdwb/okvqa-release)
- [Select, Substitute, Search: A New Benchmark for Knowledge-Augmented Visual Question Answering](https://arxiv.org/abs/2103.05568) - Aman Jain et al, **SIGIR 2021**. [[code]](https://s3vqa.github.io/)
- [Visual Question Rewriting for Increasing Response Rate](https://arxiv.org/abs/2106.02257) - Jiayi Wei et al, **SIGIR 2021**. 

#### CVPR 2021

- [Separating Skills and Concepts for Novel Visual Question Answering](https://openaccess.thecvf.com/content/CVPR2021/html/Whitehead_Separating_Skills_and_Concepts_for_Novel_Visual_Question_Answering_CVPR_2021_paper.html) - Spencer Whitehead et al, **CVPR 2021**. 
- [Roses Are Red, Violets Are Blue... but Should VQA Expect Them To?](https://openaccess.thecvf.com/content/CVPR2021/html/Kervadec_Roses_Are_Red_Violets_Are_Blue..._but_Should_VQA_Expect_CVPR_2021_paper.html) - Corentin Kervadec et al, **CVPR 2021** [[code]](https://github.com/gqa-ood/GQA-OOD)
- [Predicting Human Scanpaths in Visual Question Answering](https://openaccess.thecvf.com/content/CVPR2021/html/Chen_Predicting_Human_Scanpaths_in_Visual_Question_Answering_CVPR_2021_paper.html) - Xianyu Chen et al, **CVPR 2021**
- [Found a Reason for me? Weakly-supervised Grounded Visual Question Answering using Capsules](https://openaccess.thecvf.com/content/CVPR2021/html/Urooj_Found_a_Reason_for_me_Weakly-supervised_Grounded_Visual_Question_Answering_CVPR_2021_paper.html) - Aisha Urooj et al, **CVPR 2021**
- [TAP: Text-Aware Pre-Training for Text-VQA and Text-Caption](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_TAP_Text-Aware_Pre-Training_for_Text-VQA_and_Text-Caption_CVPR_2021_paper.html) -  Zhengyuan Yang et al, **CVPR 2021**
- [Counterfactual VQA: A Cause-Effect Look at Language Bias](https://openaccess.thecvf.com/content/CVPR2021/html/Niu_Counterfactual_VQA_A_Cause-Effect_Look_at_Language_Bias_CVPR_2021_paper.html) - Yulei Niu et al, **CVPR 2021** [[code]](https://github.com/yuleiniu/cfvqa)
- [KRISP: Integrating Implicit and Symbolic Knowledge for Open-Domain Knowledge-Based VQA](https://openaccess.thecvf.com/content/CVPR2021/html/Marino_KRISP_Integrating_Implicit_and_Symbolic_Knowledge_for_Open-Domain_Knowledge-Based_VQA_CVPR_2021_paper.html) - Kenneth Marino et al, **CVPR 2021**
- [Perception Matters: Detecting Perception Failures of VQA Models Using Metamorphic Testing](https://openaccess.thecvf.com/content/CVPR2021/html/Yuan_Perception_Matters_Detecting_Perception_Failures_of_VQA_Models_Using_Metamorphic_CVPR_2021_paper.html) - Yuanyuan Yuan et al, **CVPR 2021**
- [How Transferable Are Reasoning Patterns in VQA?](https://openaccess.thecvf.com/content/CVPR2021/html/Kervadec_How_Transferable_Are_Reasoning_Patterns_in_VQA_CVPR_2021_paper.html) - Corentin Kervadec et al, **CVPR 2021**
- [Domain-Robust VQA With Diverse Datasets and Methods but No Target Labels](https://openaccess.thecvf.com/content/CVPR2021/html/Zhang_Domain-Robust_VQA_With_Diverse_Datasets_and_Methods_but_No_Target_CVPR_2021_paper.html) - Mingda Zhang et al, **CVPR 2021**
- [Learning Better Visual Dialog Agents With Pretrained Visual-Linguistic Representation](https://openaccess.thecvf.com/content/CVPR2021/html/Tu_Learning_Better_Visual_Dialog_Agents_With_Pretrained_Visual-Linguistic_Representation_CVPR_2021_paper.html) - Tao Tu et al, **CVPR 2021**

#### ICLR 2021

- [MultiModalQA: complex question answering over text, tables and images](https://openreview.net/pdf?id=ee6W5UgQLa) - Alon Talmor et al, **ICLR 2021**. [[page]](https://allenai.github.io/multimodalqa/)

#### NAACL-HLT 2021

- [CLEVR_HYP: A Dataset and Baselines for Visual Question Answering with Hypothetical Actions over Images](https://arxiv.org/abs/2104.05981) - Shailaja Keyur Sampat et al, **NAACL-HLT 2021**. [[code]](https://github.com/shailaja183/clevr_hyp)
- [Video Question Answering with Phrases via Semantic Roles](https://arxiv.org/abs/2104.03762) - Arka Sadhu et al, **NAACL-HLT 2021**.
- [SOrT-ing VQA Models : Contrastive Gradient Learning for Improved Consistency](https://arxiv.org/abs/2010.10038) - Sameer Dharur et al, **NAACL-HLT 2021**.
- [EaSe: A Diagnostic Tool for VQA based on Answer Diversity]() - Shailza Jolly et al, **NAACL-HLT 2021**.
- [Ensemble of MRR and NDCG models for Visual Dialog](https://arxiv.org/abs/2104.07511) - Idan Schwartz, **NAACL-HLT 2021**. [[code]](https://github.com/idansc/mrr-ndcg)

#### AAAI 2021

- [Regularizing Attention Networks for Anomaly Detection in Visual Question Answering](https://arxiv.org/abs/2009.10054) - Doyup Lee et al, **AAAI 2021**. 
- [A Case Study of the Shortcut Effects in Visual Commonsense Reasoning](https://www.aaai.org/AAAI21Papers/AAAI-9821.YeK.pdf) - Keren Ye et al, **AAAI 2021**. [[code]](https://github.com/yekeren/VCR-shortcut-effects-study)
- [VisualMRC: Machine Reading Comprehension on Document Images](https://arxiv.org/abs/2101.11272) - Ryota Tanaka et al, **AAAI 2021**. [[page]](https://github.com/nttmdlab-nlp/VisualMRC)



### 2020

#### EMNLP 2020

- [MUTANT: A Training Paradigm for Out-of-Distribution Generalization in Visual Question Answering](https://www.aclweb.org/anthology/2020.emnlp-main.63/) - Tejas Gokhale et al, **EMNLP 2020**. [[code]](https://github.com/tejas-gokhale/vqa_mutant)
- [Learning to Contrast the Counterfactual Samples for Robust Visual Question Answering](https://www.aclweb.org/anthology/2020.emnlp-main.265/) - Zujie Liang et al, **EMNLP 2020**. [[code]](https://github.com/jokieleung/CL-VQA)
- [VD-BERT: A Unified Vision and Dialog Transformer with BERT](https://www.aclweb.org/anthology/2020.emnlp-main.269/) - Yue Wang et al, **EMNLP 2020**. 

#### NeurIPS 2020

- [Multimodal Graph Networks for Compositional Generalization in Visual Question Answering](https://papers.nips.cc/paper/2020/hash/1fd6c4e41e2c6a6b092eb13ee72bce95-Abstract.html) - Raeid Saqur et al, **NeurIPS 2020**. 
- [Removing Bias in Multi-modal Classifiers: Regularization by Maximizing Functional Entropies](https://papers.nips.cc/paper/2020/hash/20d749bc05f47d2bd3026ce457dcfd8e-Abstract.html) - Itai Gat et al, **NeurIPS 2020**. 
- [Dialog without Dialog Data: Learning Visual Dialog Agents from VQA Data](https://papers.nips.cc/paper/2020/hash/e7023ba77a45f7e84c5ee8a28dd63585-Abstract.html) - Michael Cogswell et al, **NeurIPS 2020**. 
- [On the Value of Out-of-Distribution Testing: An Example of Goodhart's Law](https://arxiv.org/abs/2005.09241) - Damien Teney et al, **NeurIPS 2020**.

#### ECCV 2020

- [Reducing Language Biases in Visual Question Answering with Visually-Grounded Question Encoder](http://www.ecva.net/papers/eccv_2020/papers_ECCV/html/1765_ECCV_2020_paper.php) - Gouthaman KV et al, **ECCV 2020**. 
- [Knowledge-Based Video Question Answering with Unsupervised Scene Descriptions](http://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3056_ECCV_2020_paper.php) - Noa Garcia et al, **ECCV 2020**. 
- [Semantic Equivalent Adversarial Data Augmentation for Visual Question Answering](http://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3245_ECCV_2020_paper.php) - Ruixue Tang et al, **ECCV 2020**. 
- [Visual Question Answering on Image Sets](http://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3640_ECCV_2020_paper.php) - Ankan Bansal et al, **ECCV 2020**. 
- [VQA-LOL: Visual Question Answering under the Lens of Logic](http://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3742_ECCV_2020_paper.php) - Tejas Gokhale et al, **ECCV 2020**. 
- [TRRNet: Tiered Relation Reasoning for Compositional Visual Question Answering](http://www.ecva.net/papers/eccv_2020/papers_ECCV/html/3752_ECCV_2020_paper.php) - Xiaofeng Yang et al, **ECCV 2020**. 
- [Spatially Aware Multimodal Transformers for TextVQA](http://www.ecva.net/papers/eccv_2020/papers_ECCV/html/946_ECCV_2020_paper.php) - Yash Kant et al, **ECCV 2020**. 

#### CVPR 2020

- [Multi-Modal Graph Neural Network for Joint Reasoning on Vision and Scene Text]( http://arxiv.org/abs/2003.13962) - Difei Gao et al, **CVPR 2020**. [[code]]( https://github.com/ricolike/mmgnn_textvqa)
- [On the General Value of Evidence, and Bilingual Scene-Text Visual Question Answering](http://openaccess.thecvf.com/content_CVPR_2020/html/Wang_On_the_General_Value_of_Evidence_and_Bilingual_Scene-Text_Visual_CVPR_2020_paper.html) - Xinyu Wang et al, **CVPR 2020**. 
- [In Defense of Grid Features for Visual Question Answering](http://openaccess.thecvf.com/content_CVPR_2020/html/Jiang_In_Defense_of_Grid_Features_for_Visual_Question_Answering_CVPR_2020_paper.html) - Huaizu Jiang et al, **CVPR 2020**. 
- [Counterfactual Samples Synthesizing for Robust Visual Question Answering](http://openaccess.thecvf.com/content_CVPR_2020/html/Chen_Counterfactual_Samples_Synthesizing_for_Robust_Visual_Question_Answering_CVPR_2020_paper.html) - Long Chen et al, **CVPR 2020**. 
- [Counterfactual Vision and Language Learning](http://openaccess.thecvf.com/content_CVPR_2020/html/Abbasnejad_Counterfactual_Vision_and_Language_Learning_CVPR_2020_paper.html) - Ehsan Abbasnejad et al, **CVPR 2020**. 
- [Iterative Answer Prediction With Pointer-Augmented Multimodal Transformers for TextVQA](http://openaccess.thecvf.com/content_CVPR_2020/html/Hu_Iterative_Answer_Prediction_With_Pointer-Augmented_Multimodal_Transformers_for_TextVQA_CVPR_2020_paper.html) - Ronghang Hu et al, **CVPR 2020**. 
- [Towards Causal VQA: Revealing and Reducing Spurious Correlations by Invariant and Covariant Semantic Editing](http://openaccess.thecvf.com/content_CVPR_2020/html/Agarwal_Towards_Causal_VQA_Revealing_and_Reducing_Spurious_Correlations_by_Invariant_CVPR_2020_paper.html) - Vedika Agarwal et al, **CVPR 2020**. 
- [SQuINTing at VQA Models: Introspecting VQA Models With Sub-Questions](http://openaccess.thecvf.com/content_CVPR_2020/html/Selvaraju_SQuINTing_at_VQA_Models_Introspecting_VQA_Models_With_Sub-Questions_CVPR_2020_paper.html) - Ramprasaath R. Selvaraju et al, **CVPR 2020**. 
- [TA-Student VQA: Multi-Agents Training by Self-Questioning](http://openaccess.thecvf.com/content_CVPR_2020/html/Xiong_TA-Student_VQA_Multi-Agents_Training_by_Self-Questioning_CVPR_2020_paper.html) - Peixi Xiong et al, **CVPR 2020**. 
- [VQA With No Questions-Answers Training](http://openaccess.thecvf.com/content_CVPR_2020/html/Vatashsky_VQA_With_No_Questions-Answers_Training_CVPR_2020_paper.html) - Ben-Zion Vatashsky et al, **CVPR 2020**. 
- [Hierarchical Conditional Relation Networks for Video Question Answering](http://openaccess.thecvf.com/content_CVPR_2020/html/Le_Hierarchical_Conditional_Relation_Networks_for_Video_Question_Answering_CVPR_2020_paper.html) - Thao Minh Le et al, **CVPR 2020**. 
- [Modality Shifting Attention Network for Multi-Modal Video Question Answering](http://openaccess.thecvf.com/content_CVPR_2020/html/Kim_Modality_Shifting_Attention_Network_for_Multi-Modal_Video_Question_Answering_CVPR_2020_paper.html) - Junyeong Kim et al, **CVPR 2020**. 
- [Webly Supervised Knowledge Embedding Model for Visual Reasoning](http://openaccess.thecvf.com/content_CVPR_2020/html/Zheng_Webly_Supervised_Knowledge_Embedding_Model_for_Visual_Reasoning_CVPR_2020_paper.html) - Wenbo Zheng et al, **CVPR 2020**. 
- [Differentiable Adaptive Computation Time for Visual Reasoning](http://openaccess.thecvf.com/content_CVPR_2020/html/Eyzaguirre_Differentiable_Adaptive_Computation_Time_for_Visual_Reasoning_CVPR_2020_paper.html) - Cristobal Eyzaguirre et al, **CVPR 2020**. 

#### ACL 2020

- [A negative case analysis of visual grounding methods for VQA](https://arxiv.org/abs/2004.05704) - Robik Shrestha et al, **ACL 2020**. 
- [Cross-Modality Relevance for Reasoning on Language and Vision](https://arxiv.org/abs/2005.06035) - Chen Zheng et al, **ACL 2020**. 
- [Dense-Caption Matching and Frame-Selection Gating for Temporal Localization in VideoQA](https://arxiv.org/abs/2005.06409) - Hyounghun Kim et al, **ACL 2020**. 
- [TVQA+: Spatio-Temporal Grounding for Video Question Answering](https://arxiv.org/abs/1904.11574) - Jie Lei et al, **ACL 2020**. 

#### WACV 2020

- [BERT representations for Video Question Answering](http://openaccess.thecvf.com/content_WACV_2020/papers/Yang_BERT_representations_for_Video_Question_Answering_WACV_2020_paper.pdf) - Zekun Yang et al, **WACV 2020**. 
- [Deep Bayesian Network for Visual Question Generation](http://openaccess.thecvf.com/content_WACV_2020/html/Patro_Deep_Bayesian_Network_for_Visual_Question_Generation_WACV_2020_paper.html) - Badri Patro et al, **WACV 2020**. 
- [Robust Explanations for Visual Question Answering](http://openaccess.thecvf.com/content_WACV_2020/html/Patro_Robust_Explanations_for_Visual_Question_Answering_WACV_2020_paper.html) - Badri Patro et al, **WACV 2020**. 
- [Visual Question Answering on 360deg Images](http://openaccess.thecvf.com/content_WACV_2020/html/Chou_Visual_Question_Answering_on_360deg_Images_WACV_2020_paper.html) - Shih-Han Chou et al, **WACV 2020**. 
- [LEAF-QA: Locate, Encode & Attend for Figure Question Answering](http://openaccess.thecvf.com/content_WACV_2020/html/Chaudhry_LEAF-QA_Locate_Encode__Attend_for_Figure_Question_Answering_WACV_2020_paper.html) - Ritwick Chaudhry et al, **WACV 2020**. 
- [Answering Questions about Data Visualizations using Efficient Bimodal Fusion](http://openaccess.thecvf.com/content_WACV_2020/html/Kafle_Answering_Questions_about_Data_Visualizations_using_Efficient_Bimodal_Fusion_WACV_2020_paper.html) - Kushal Kafle et al, **WACV 2020**. 

#### AAAI 2020

- [Multi‐Question Learning for Visual Question Answering]() - Chenyi Lei et al, **AAAI 2020**. 
- [Explanation vs Attention: A Two-Player Game to Obtain Attention for VQA]() - Badri N. Patro et al, **AAAI 2020**. 
- [Overcoming Language Priors in VQA via Decomposed Linguistic Representations]() - Chenchen Jing et al, **AAAI 2020**. 
- [Unified Vision-Language Pre-Training for Image Captioning and VQA]() - Luowei Zhou et al, **AAAI 2020**. 
- [Re‐Attention for Visual Question Answering]() - Wenya Guo et al, **AAAI 2020**. 
- [Divide and Conquer: Question­‐Guided Spatio­‐Temporal Contextual Attention for Video Question Answering]() - Jianwen Jiang et al, **AAAI 2020**. 
- [Reasoning with Heterogeneous Graph Alignment for Video Question Answering]() - Pin Jiang et al, **AAAI 2020**. 
- [Location­‐aware Graph Convolutional Networks for Video Question Answering]() - Deng  Huang et al, **AAAI 2020**. 
- [KnowIT VQA: Answering Knowledge­‐Based Questions about Videos]() - Noa  Garcia et al, **AAAI 2020**. 

### 2019

#### ACL 2019

* [Generating Question Relevant Captions to Aid Visual Question Answering]( https://www.aclweb.org/anthology/P19-1348.pdf ) - Jialin Wu et al, **ACL 2019**. 
* [Psycholinguistics Meets Continual Learning: Measuring Catastrophic Forgetting in Visual Question Answering](https://www.aclweb.org/anthology/P19-1350.pdf) - Claudio Greco et al, **ACL 2019**. [[code]]( https://www.aclweb.org/anthology/P19-1350/ )
* [Multi-grained Attention with Object-level Grounding for Visual Question Answering](https://www.aclweb.org/anthology/P19-1349.pdf) - Pingping Huang et al, **ACL 2019**. 
* [Improving Visual Question Answering by Referring to Generated Paragraph Captions]( https://www.aclweb.org/anthology/P19-1351.pdf ) -  Hyounghun Kim et al, **ACL 2019**. 

#### ICCV 2019

*  [Compact Trilinear Interaction for Visual Question Answering](http://openaccess.thecvf.com/content_ICCV_2019/html/Do_Compact_Trilinear_Interaction_for_Visual_Question_Answering_ICCV_2019_paper.html) - Tuong Do Kim et al, **ICCV 2019**. 
*  [Scene Text Visual Question Answering](http://openaccess.thecvf.com/content_ICCV_2019/html/Biten_Scene_Text_Visual_Question_Answering_ICCV_2019_paper.html)  - Ali Furkan Biten et al, **ICCV 2019**. 
* [Multi-Modality Latent Interaction Network for Visual Question Answering](http://openaccess.thecvf.com/content_ICCV_2019/html/Gao_Multi-Modality_Latent_Interaction_Network_for_Visual_Question_Answering_ICCV_2019_paper.html)  - Peng Gao et al, **ICCV 2019**. 
* [Relation-Aware Graph Attention Network for Visual Question Answering](http://openaccess.thecvf.com/content_ICCV_2019/html/Li_Relation-Aware_Graph_Attention_Network_for_Visual_Question_Answering_ICCV_2019_paper.html)  - Linjie Li et al, **ICCV 2019**. 
* [Why Does a Visual Question Have Different Answers?](http://openaccess.thecvf.com/content_ICCV_2019/papers/Bhattacharya_Why_Does_a_Visual_Question_Have_Different_Answers_ICCV_2019_paper.pdf)  - Nilavra Bhattacharya et al, **ICCV 2019**. 

#### NeurIPS 2019

* [RUBi: Reducing Unimodal Biases for Visual Question Answering](https://papers.nips.cc/paper/8371-rubi-reducing-unimodal-biases-for-visual-question-answering) - Remi Cadene et al, **NeurIPS 2019**. 
* [Self-Critical Reasoning for Robust Visual Question Answering](https://papers.nips.cc/paper/9066-self-critical-reasoning-for-robust-visual-question-answering) - Jialin Wu et al, **NeurIPS 2019**. 

#### CVPR 2019 ####
* [Deep Modular Co-Attention Networks for Visual Question Answering](http://openaccess.thecvf.com/content_CVPR_2019/papers/Yu_Deep_Modular_Co-Attention_Networks_for_Visual_Question_Answering_CVPR_2019_paper.pdf) - Zhou Yu et al, **CVPR 2019**. [[code]](https://github.com/MILVLG/mcan-vqa)
* [Information Maximizing Visual Question Generation](https://arxiv.org/abs/1903.11207) - Ranjay Krishna et al, **CVPR 2019**. [code]
* [Social-IQ: A Question Answering Benchmark for Artificial Social Intelligence](http://openaccess.thecvf.com/content_CVPR_2019/papers/Zadeh_Social-IQ_A_Question_Answering_Benchmark_for_Artificial_Social_Intelligence_CVPR_2019_paper.pdf) - Amir Zadeh et al, **CVPR 2019**. [code]
* [Learning to Compose Dynamic Tree Structures for Visual Contexts](https://arxiv.org/abs/1812.01880) - Kaihua Tang et al, **CVPR 2019**. [code]
* [Transfer Learning via Unsupervised Task Discovery for Visual Question Answering](https://arxiv.org/abs/1810.02358) - Hyeonwoo Noh et al, **CVPR 2019**. [code]
* [Video Relationship Reasoning using Gated Spatio-Temporal Energy Graph](https://arxiv.org/abs/1903.10547) - Yao-Hung Hubert Tsai et al, **CVPR 2019**. [[code]](https://github.com/yaohungt/Gated-Spatio-Temporal-Energy-Graph)
* [Explainable and Explicit Visual Reasoning over Scene Graphs](https://arxiv.org/abs/1812.01855) - Jiaxin Shi et al, **CVPR 2019**. [[code]](https://github.com/shijx12/XNM-Net)
* [MUREL: Multimodal Relational Reasoning for Visual Question Answering](https://arxiv.org/abs/1902.09487) - Remi Cadene et al, **CVPR 2019**. [[code]](https://github.com/Cadene/murel.bootstrap.pytorch)
* [Image-Question-Answer Synergistic Network for Visual Dialog](https://arxiv.org/abs/1902.09774) - Dalu Guo et al, **CVPR 2019**. [code]
* [RAVEN: A Dataset for Relational and Analogical Visual rEasoNing](https://arxiv.org/abs/1903.02741) - Chi Zhang et al, **CVPR 2019**. [[project page]](http://wellyzhang.github.io/project/raven.html)
* [Cycle-Consistency for Robust Visual Question Answering](http://openaccess.thecvf.com/content_CVPR_2019/html/Shah_Cycle-Consistency_for_Robust_Visual_Question_Answering_CVPR_2019_paper.html) - Meet Shah et al, **CVPR 2019**.
* [It's Not About the Journey; It's About the Destination: Following Soft Paths Under Question-Guidance for Visual Reasoning](http://openaccess.thecvf.com/content_CVPR_2019/html/Haurilet_Its_Not_About_the_Journey_Its_About_the_Destination_Following_CVPR_2019_paper.html) - Monica Haurilet et al, **CVPR 2019**.
* [OK-VQA: A Visual Question Answering Benchmark Requiring External Knowledge](http://openaccess.thecvf.com/content_CVPR_2019/html/Marino_OK-VQA_A_Visual_Question_Answering_Benchmark_Requiring_External_Knowledge_CVPR_2019_paper.html) - Kenneth Marino et al, **CVPR 2019**.
* [Visual Question Answering as Reading Comprehension](http://openaccess.thecvf.com/content_CVPR_2019/html/Li_Visual_Question_Answering_as_Reading_Comprehension_CVPR_2019_paper.html) - Hui Li et al, **CVPR 2019**.
* [Dynamic Fusion With Intra- and Inter-Modality Attention Flow for Visual Question Answering](http://openaccess.thecvf.com/content_CVPR_2019/html/Gao_Dynamic_Fusion_With_Intra-_and_Inter-Modality_Attention_Flow_for_Visual_CVPR_2019_paper.html) - Peng Gao et al, **CVPR 2019**.
* [Explicit Bias Discovery in Visual Question Answering Models](http://openaccess.thecvf.com/content_CVPR_2019/html/Manjunatha_Explicit_Bias_Discovery_in_Visual_Question_Answering_Models_CVPR_2019_paper.html) - Varun Manjunatha et al, **CVPR 2019**.
* [Answer Them All! Toward Universal Visual Question Answering Models](http://openaccess.thecvf.com/content_CVPR_2019/html/Shrestha_Answer_Them_All_Toward_Universal_Visual_Question_Answering_Models_CVPR_2019_paper.html) - Robik Shrestha et al, **CVPR 2019**.
* [Visual Query Answering by Entity-Attribute Graph Matching and Reasoning](http://openaccess.thecvf.com/content_CVPR_2019/html/Xiong_Visual_Query_Answering_by_Entity-Attribute_Graph_Matching_and_Reasoning_CVPR_2019_paper.html) - Peixi Xiong et al, **CVPR 2019**.

#### AAAI 2019 ####
* [Differential Networks for Visual Question Answering](https://www.aaai.org/Papers/AAAI/2019/AAAI-WuC.76.pdf) - Chenfei Wu et al, **AAAI 2019**. [code]
* [BLOCK: Bilinear Superdiagonal Fusion for Visual Question Answering and Visual Relationship Detection](https://arxiv.org/abs/1902.00038) - Hedi Ben-younes et al, **AAAI 2019**. [[code]](https://github.com/Cadene/block.bootstrap.pytorch)
* [Dynamic Capsule Attention for Visual Question Answering](https://www.aaai.org/Papers/AAAI/2019/AAAI-ZhouYiyi2.3610.pdf) - Yiyi Zhou et al, **AAAI 2019**. [[code]](https://github.com/XMUVQA/CapsAtt)
* Structured Two-stream Attention Network for Video Question Answering - Lianli Gao et al, **AAAI 2019**. [code]
* [Beyond RNNs: Positional Self-Attention with Co-Attention for Video Question Answering](https://www.semanticscholar.org/paper/Beyond-RNNs%3A-Positional-Self-Attention-with-for-Li-Song/565359aac8914505e6b02db05822ee63d3ffd03a) - Xiangpeng Li et al, **AAAI 2019**. [[code]](https://github.com/lixiangpengcs/PSAC)
*  WK-VQA: World Knowledge-enabled Visual Question Answering - Sanket Shah et al, **AAAI 2019**. [[code]](https://github.com/sanket0211/WK-VQA)
*  [Free VQA Models from Knowledge Inertia by Pairwise Inconformity Learning](https://www.aaai.org/Papers/AAAI/2019/AAAI-ZhouYiyi1.1233.pdf) - Yiyi Zhou et al, **AAAI 2019**. [[code]](https://github.com/xiangmingLi/PIL)

#### OTHER ####
* [Focal Visual-Text Attention for Memex Question Answering](https://ieeexplore.ieee.org/abstract/document/8603827/) - Junwei Liang et al, **TPAMI 2019**. [[code]](https://memexqa.cs.cmu.edu/)
* Plenty is Plague: Fine-Grained Learning for Visual Question Answering - Yiyi Zhou et al, **TPAMI 2019**.
* [Combining Multiple Cues for Visual Madlibs Question Answering](https://arxiv.org/abs/1611.00393) - Tatiana Tommasi et al, **IJCV 2019**. [code]
* [Large-Scale Answerer in Questioner's Mind for Visual Dialog Question Generation](https://arxiv.org/abs/1902.08355) - Sang-Woo Lee et al, **ICLR 2019**. [[code]](https://github.com/naver/aqm-plus)


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
* [Visual Question Answering using Explicit Visual Attention](https://ieeexplore.ieee.org/abstract/document/8351158/) - Vasileios Lioutas et al, ***\*ISCAS 2018\****. [code]
* [Explicit ensemble attention learning for improving visual question answering](https://www.sciencedirect.com/science/article/abs/pii/S0167865518301600) - Vasileios Lioutas et al, ***\*Pattern Recognition Letters 2018\****. [code]

### 2017-2015
#### OTHER ####
 Please check the other papers list from VQA area between 2017-2015 in [awesome-vqa](https://github.com/JamesChuanggg/awesome-vqa) from [JamesChuanggg](https://github.com/JamesChuanggg), it seems that he hasn't maintained that project for a long time. Really appreciate for his work. I will merge his work to this list in the future.Stay tuned...

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

### [TextVQA]( https://textvqa.org/ )

* [TextVQA Challenge 2019 Leaderboard in EvalAI]( https://evalai.cloudcv.org/web/challenges/challenge-page/244/overview )

### VQA-CP

- [The VQA-CP leaderboard](https://github.com/cdancette/vqa-cp-leaderboard)

## Licenses

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Jokie Leung](https://github.com/jokieleung) has waived all copyright and related or neighboring rights to this work.

## Reference and Acknowledgement
* [**awesome-image-captioning**](https://github.com/zhjohnchan/awesome-image-captioning) from [Zhihong Chen](https://github.com/zhjohnchan)
* [**awesome-vqa**](https://github.com/JamesChuanggg/awesome-vqa) from [JamesChuanggg](https://github.com/JamesChuanggg)

Really appreciate for their contributions in this area.
