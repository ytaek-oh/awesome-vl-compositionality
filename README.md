# <div align="center">Awesome Vision-Language Compositionality</div>

<div align="center">
  
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href=""> <img src="https://img.shields.io/github/stars/ytaek-oh/awesome-vl-compositionality?style=flat-square&logo=github" alt="GitHub stars"></a>
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/ytaek-oh/awesome-vl-compositionality/graphs/commit-activity)

</div>

Welcome to **Awesome Vision-Language Compositionality**, an extensively curated collection of research papers and resources on compositional understanding in vision-language models (VLMs). 
This repository will serve as a comprehensive resource to keep up to date with the latest advancements and to provide an overarching view of the vision-language compositionality landscape. 

We'd welcome contributions and feedback to continuously improve and expand this collection. 😊 <br />
[How to contribute?](#contributing)

<br />

## Our Works

🌟 **Preserving Multi-Modal Capabilities of Pre-trained VLMs for Improving Vision-Linguistic Compositionality**, EMNLP 2024. 🌟<br />
[[Paper](https://arxiv.org/abs/2410.05210)]  [[Project Page](https://ytaek-oh.github.io/fsc-clip)]  [[Code](https://github.com/ytaek-oh/fsc-clip)]  

**TL;DR;** We present a new fine-tuning framework to increase compositional reasoning of CLIP without sacrificing the multi-modal capabilities.

🌟 **Exploring the Spectrum of Visio-Linguistic Compositionality and Recognition**, CVPRW 2024. 🌟<br />
[[Paper](https://arxiv.org/abs/2406.09388)]  [[Code](https://github.com/ytaek-oh/vl_compo)]  

**TL;DR;** We comprehensively curate VLMs and benchmarks for compositionality and recognition evaluation!

<br />

## Repository Structure
- [Compositionality in Image-Text Understanding](#compositionality-in-image-text-understanding) <br />
- [Compositionality in Video-Text Understanding](#compositionality-in-video-text-understanding) <br />
- [Compositionality in Text to Image Generation](#compositionality-in-text-to-image-generation)

### Icon Glossary
- 🗂️ **Dataset:** New benchmarks or datasets for evaluating compositionality.
- 🤖 **Model:** New architectures or training methodologies for enhanced compositional understanding.
- ⚖️ **Evaluation:** Assessment metrics and benchmarks for compositional reasoning.

<br />

## Compositionality in Image-Text Understanding

🗂️🤖 **Cambrian-1: A Fully Open, Vision-Centric Exploration of Multimodal LLMs.** *(CV-Bench).* [NeurIPS, 2024]. <br />
*Shengbang Tong, Ellis Brown, Penghao Wu, Sanghyun Woo, Manoj Middepogu, Sai Charitha Akula, Jihan Yang, Shusheng Yang, Adithya Iyer, Xichen Pan, Austin Wang, Rob Fergus, Yann LeCun, Saining Xie.* <br />
[[Paper](https://arxiv.org/abs/2406.16860)] [[Code](https://github.com/cambrian-mllm/cambrian)] [[HF Dataset](https://huggingface.co/datasets/nyu-visionx/CV-Bench)]

🗂️ **NaturalBench: Evaluating Vision-Language Models on Natural Adversarial Samples.** *(NaturalBench).* [NeurIPS, 2024]. <br />
*Baiqi Li, Zhiqiu Lin, Wenxuan Peng, Jean de Dieu Nyandwi, Daniel Jiang, Zixian Ma, Simran Khanuja, Ranjay Krishna, Graham Neubig, Deva Ramanan.* <br />
[[Paper](https://arxiv.org/abs/2410.14669)]  [[Code](https://github.com/Baiqi-Li/NaturalBench)]  [[HF Dataset](https://huggingface.co/datasets/BaiqiL/NaturalBench)]

🗂️🤖 **TripletCLIP: Improving Compositional Reasoning of CLIP via Synthetic Vision-Language Negatives.** *(TripletCLIP).* [NeurIPS, 2024]. <br />
*Maitreya Patel, Abhiram Kusumba, Sheng Cheng, Changhoon Kim, Tejas Gokhale, Chitta Baral, Yezhou Yang.* <br />
[[Paper](https://arxiv.org/abs/2411.02545)]  [[Code](https://github.com/tripletclip/TripletCLIP)]  [[HF Dataset](https://huggingface.co/TripletCLIP)]

🗂️ **ConMe: Rethinking Evaluation of Compositional Reasoning for Modern VLMs.** *(ConMe)*. [NeurIPS, 2024]. <br />
*Irene Huang, Wei Lin, M. Jehanzeb Mirza, Jacob A. Hansen, Sivan Doveh, Victor Ion Butoi, Roei Herzig, Assaf Arbelle, Hilde Kuhene, Trevor Darrel, Chuang Gan, Aude Oliva, Rogerio Feris, Leonid Karlinsky.* <br />
[[Paper](https://arxiv.org/abs/2406.08164)] [[Code](https://github.com/jmiemirza/ConMe)] [[HF Dataset](https://huggingface.co/conme/ConMe)]

🗂️🤖 **VisMin: Visual Minimal-Change Understanding.** *(VisMin)*. [NeurIPS, 2024]. <br />
*Rabiul Awal, Saba Ahmadi, Le Zhang, Aishwarya Agrawal.* <br />
[[Paper](https://arxiv.org/abs/2407.16772)] [[HF Dataset](https://huggingface.co/datasets/mair-lab/vismin)]

🗂️ **BiVLC: Extending Vision-Language Compositionality Evaluation with Text-to-Image Retrieval.** *(BiVLC).* [NeurIPS, 2024]. <br />
*Imanol Miranda, Ander Salaberria, Eneko Agirre, Gorka Azkune.* <br />
[[Paper](https://arxiv.org/abs/2406.09952)] [[Code](https://github.com/IMirandaM/BiVLC)] [[HF Dataset](https://huggingface.co/datasets/imirandam/BiVLC)]

🤖 **Preserving Multi-Modal Capabilities of Pre-trained VLMs for Improving Vision-Linguistic Compositionality.** *(FSC-CLIP).* [EMNLP, 2024]. <br />
*Youngtaek Oh, Jae Won Cho, Dong-Jin Kim, In So Kweon, Junmo Kim.* <br />
[[Paper](https://arxiv.org/abs/2410.05210)]  [[Code](https://github.com/ytaek-oh/fsc-clip)]

🤖 **Distilling Knowledge from Text-to-Image Generative Models Improves Visio-Linguistic Reasoning in CLIP.** *(SDS-CLIP).* [EMNLP, 2024]. <br />
*Samyadeep Basu, Shell Xu Hu, Maziar Sanjabi, Daniela Massiceti, Soheil Feizi.* <br />
[[Paper](https://arxiv.org/abs/2307.09233)]

🤖 **Natural Language Inference Improves Compositionality in Vision-Language Models.** *(CECE).* [arXiv, 2024]. <br />
*Paola Cascante-Bonilla, Yu Hou, Yang Trista Cao, Hal Daumé III, Rachel Rudinger.* <br />
[[Paper](https://arxiv.org/abs/2410.22315)]  [[Code](https://github.com/pcascanteb/cece-vlm)]

🤖 **Locality Alignment Improves Vision-Language Models.** [arXiv, 2024]. <br />
*Ian Covert, Tony Sun, James Zou, Tatsunori Hashimoto.* <br />
[[Paper](https://arxiv.org/abs/2410.11087)]  [[Code](https://github.com/iancovert/locality-alignment)]

🗂️ **VL-GLUE: A Suite of Fundamental yet Challenging Visuo-Linguistic Reasoning Tasks.** *(VL-GLUE).* [arXiv, 2024]. <br />
*Shailaja Keyur Sampat, Mutsumi Nakamura, Shankar Kailas, Kartik Aggarwal, Mandy Zhou, Yezhou Yang, Chitta Baral.* <br />
[[Paper](https://arxiv.org/abs/2410.13666)]  [[Code](https://github.com/shailaja183/VL-GLUE)]

🗂️ **MMCOMPOSITION: Revisiting the Compositionality of Pre-trained Vision-Language Models.** *(MMComposition).* [arXiv, 2024]. <br />
*Hang Hua, Yunlong Tang, Ziyun Zeng, Liangliang Cao, Zhengyuan Yang, Hangfeng He, Chenliang Xu, Jiebo Luo.* <br />
[[Paper](https://arxiv.org/abs/2410.09733v1)]  [[Code](https://github.com/hanghuacs/MMComposition)]  

🗂️🤖 **The Hard Positive Truth about Vision-Language Compositionality.** *(HP+HN).* [ECCV, 2024]. <br />
*Amita Kamath, Cheng-Yu Hsieh, Kai-Wei Chang, Ranjay Krishna.* <br />
[[Paper](https://amitakamath.github.io/oversensitivity.pdf)]  [[Code](https://github.com/amitakamath/hard_positives)]

🗂️ **Mismatch Quest: Visual and Textual Feedback for Image-Text Misalignment.** *(MismatchQuest).* [ECCV, 2024]. <br />
*Brian Gordon, Yonatan Bitton, Yonatan Shafir, Roopal Garg, Xi Chen, Dani Lischinski, Daniel Cohen-Or, Idan Szpektor.* <br />
[[Paper](https://arxiv.org/abs/2312.03766)]  [[Code](https://github.com/BrianG13/MismatchQuest)]  [[HF Dataset](https://huggingface.co/datasets/mismatch-quest/SeeTRUE-Feedback)]

⚖️ **Removing Distributional Discrepancies in Captions Improves Image-Text Alignment.** *(LLaVA-score).* [ECCV, 2024]. <br />
*Yuheng Li, Haotian Liu, Mu Cai, Yijun Li, Eli Shechtman, Zhe Lin, Yong Jae Lee, Krishna Kumar Singh.* <br />
[[Paper](https://arxiv.org/abs/2410.00905)] [[Code](https://github.com/adobe-research/llava-score)]

🗂️🤖 **Evaluating Text-to-Visual Generation with Image-to-Text Generation.** *(VQAScore).* [ECCV, 2024]. <br />
*Zhiqiu Lin, Deepak Pathak, Baiqi Li, Jiayao Li, Xide Xia, Graham Neubig, Pengchuan Zhang, Deva Ramanan.* <br />
[[Code](https://github.com/linzhiqiu/t2v_metrics)]  [[Model](https://github.com/linzhiqiu/CLIP-FlanT5)]  [[HF Dataset](https://huggingface.co/datasets/BaiqiL/GenAI-Bench)]

🗂️ **Detect, Describe, Discriminate: Moving Beyond VQA for MLLM Evaluation.** *(D3).*  [ECCVW, 2024]. <br />
*Manu Gaur, Darshan Singh S, Makarand Tapaswi.* <br />
[[Paper](https://arxiv.org/abs/2409.15125)]  [[Code](https://github.com/manugaurdl/detect-describe-discriminate/)]

🗂️ **ColorSwap: A Color and Word Order Dataset for Multimodal Evaluation.** *(ColorSwap).* [ACL Findings, 2024]. <br />
*Jirayu Burapacheep, Ishan Gaur, Agam Bhatia, Tristan Thrush.* <br />
[[Paper](https://arxiv.org/abs/2402.04492)] [[Code](https://github.com/Top34051/colorswap)] [[HF Dataset](https://huggingface.co/datasets/stanfordnlp/colorswap)]

⚖️ **An Examination of the Compositionality of Large Generative Vision-Language Models.** *(SADE).* [NAACL, 2024]. <br />
*Teli Ma, Rong Li, Junwei Liang.* <br />
[[Paper](https://arxiv.org/abs/2308.10509)] [[Code](https://github.com/TeleeMa/SADE)]

⚖️ **Diagnosing the Compositional Knowledge of Vision Language Models from a Game-Theoretic View.** [ICML, 2024]. <br />
*Jin Wang, Shichao Dong, Yapeng Zhu, Kelu Yao, Weidong Zhao, Chao Li, Ping Luo.* <br />
[[Paper](https://arxiv.org/abs/2405.17201)] [[Code](https://github.com/jinjinw/VLMs-Compositionality-Game-Theory)]

🤖 **Revisiting the Role of Language Priors in Vision-Language Models.** *(VisualGPTScore).* [ICML, 2024]. <br />
*Zhiqiu Lin, Xinyue Chen, Deepak Pathak, Pengchuan Zhang, Deva Ramanan.* <br />
[[Paper](https://arxiv.org/abs/2306.01879)] [[Code](https://github.com/linzhiqiu/visual_gpt_score)]

⚖️ **Exploring the Spectrum of Visio-Linguistic Compositionality and Recognition.** [CVPRW, 2024]. <br />
*Youngtaek Oh, Pyunghwan Ahn, Jinhyung Kim, Gwangmo Song, Soonyoung Lee, In So Kweon, Junmo Kim.* <br />
[[Paper](https://arxiv.org/abs/2406.09388)]  [[Code](https://github.com/ytaek-oh/vl_compo)]

🗂️🤖 **Eyes Wide Shut? Exploring the Visual Shortcomings of Multimodal LLMs.** *(MMVP).* [CVPR, 2024]. <br />
*Shengbang Tong, Zhuang Liu, Yuexiang Zhai, Yi Ma, Yann LeCun, Saining Xie.* <br />
[[Paper](https://arxiv.org/abs/2401.06209)] [[Code](https://github.com/tsb0601/MMVP)] [[HF Dataset](https://huggingface.co/MMVP)]

🗂️ **A Picture is Worth More Than 77 Text Tokens: Evaluating CLIP-Style Models on Dense Captions.** *(DCI).* [CVPR, 2024]. <br />
*Jack Urbanek, Florian Bordes, Pietro Astolfi, Mary Williamson, Vasu Sharma, Adriana Romero-Soriano.* <br />
[[Paper](https://arxiv.org/abs/2404.00419)] [[Code](https://github.com/facebookresearch/DCI)]

🗂️🤖 **Synthesize, Diagnose, and Optimize: Towards Fine-Grained Vision-Language Understanding.** *(SPEC).* [CVPR, 2024]. <br />
*Wujian Peng, Sicheng Xie, Zuyao You, Shiyi Lan, Zuxuan Wu.* <br />
[[Paper](https://arxiv.org/abs/2312.00081)] [[Code](https://github.com/wjpoom/SPEC)] [[HF Dataset](https://huggingface.co/datasets/wjpoom/SPEC)]

🤖 **Iterated Learning Improves Compositionality in Large Vision-Language Models.** *(IL-CLIP).* [CVPR, 2024]. <br />
*Chenhao Zheng, Jieyu Zhang, Aniruddha Kembhavi, Ranjay Krishna.* <br />
[[Paper](https://arxiv.org/abs/2404.02145)]

🤖 **Contrasting Intra-Modal and Ranking Cross-Modal Hard Negatives to Enhance Visio-Linguistic Compositional Understanding.** *(CE-CLIP).* [CVPR, 2024]. <br />
*Le Zhang, Rabiul Awal, Aishwarya Agrawal.* <br />
[[Paper](https://arxiv.org/abs/2306.08832)] [[Code](https://github.com/lezhang7/Enhance-FineGrained)]

🤖 **MobileCLIP: Fast Image-Text Models through Multi-Modal Reinforced Training.** *(MobileCLIP).* [CVPR, 2024]. <br />
*Pavan Kumar Anasosalu Vasu, Hadi Pouransari, Fartash Faghri, Raviteja Vemulapalli, Oncel Tuzel.* <br />
[[Paper](https://arxiv.org/abs/2311.17049)] [[Code](https://github.com/apple/ml-mobileclip)] [[HF Dataset](https://huggingface.co/datasets/apple/DataCompDR-1B)]

🤖 **Efficient Vision-Language Pre-training by Cluster Masking.** [CVPR, 2024]. <br />
*Zihao Wei, Zixuan Pan, Andrew Owens.* <br />
[[Paper](https://arxiv.org/abs/2405.08815)] [[Code](https://github.com/Zi-hao-Wei/Efficient-Vision-Language-Pre-training-by-Cluster-Masking)]

🤖 **Building Vision-Language Models on Solid Foundations with Masked Distillation.** *(SF-CLIP).* [CVPR, 2024]. <br />
*Sepehr Sameni, Kushal Kafle, Hao Tan, Simon Jenni.* <br />
[[Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Sameni_Building_Vision-Language_Models_on_Solid_Foundations_with_Masked_Distillation_CVPR_2024_paper.html)]

⚖️ **Probing Conceptual Understanding of Large Visual-Language Models.** *(UnderstandingVisualTextModels).* [CVPRW, 2024]. <br />
*Madeline Schiappa, Raiyaan Abdullah, Shehreen Azad, Jared Claypoole, Michael Cogswell, Ajay Divakaran, Yogesh Rawat.* <br />
[[Paper](https://arxiv.org/abs/2304.03659)] [[Code](https://github.com/DeepLearningRobustnessStudies/UnderstandingVisualTextModels)]

🗂️ **EVil-Probe - a Composite Benchmark for Extensive Visio-Linguistic Probing** *(Evil-Probe).* [LREC, 2024]. <br />
*Marie Bexte, Andrea Horbach, Torsten Zesch.* <br />
[[Paper](https://aclanthology.org/2024.lrec-main.591/)] [[Code](https://github.com/mariebexte/vl-probing)]

🗂️🤖 **CounterCurate: Enhancing Physical and Semantic Visio-Linguistic Compositional Reasoning via Counterfactual Examples.** *(CounterCurate).* [ACL Findings, 2024]. <br />
*Jianrui Zhang, Mu Cai, Tengyang Xie, Yong Jae Lee.* <br />
[[Paper](https://arxiv.org/abs/2402.13254)] [[Code](https://github.com/HanSolo9682/CounterCurate)]

🤖 **ContextBLIP: Doubly Contextual Alignment for Contrastive Image Retrieval from Linguistically Complex Descriptions.** *(ContextBLIP)*. [ACL Findings, 2024]. <br />
*Honglin Lin, Siyu Li, Guoshun Nan, Chaoyue Tang, Xueting Wang, Jingxin Xu, Rong Yankai, Zhili Zhou, Yutong Gao, Qimei Cui, Xiaofeng Tao.* <br />
[[Paper](https://arxiv.org/abs/2405.19226)] [[Code](https://github.com/LHL3341/ContextBLIP)]

🗂️ **Do Vision-Language Models Understand Compound Nouns?** *(Compun).* [NAACL, 2024]. <br />
*Sonal Kumar, Sreyan Ghosh, S Sakshi, Utkarsh Tyagi, Dinesh Manocha.* <br />
[[Paper](https://arxiv.org/abs/2404.00419)] [[Code](https://github.com/sonalkum/Compun)]

🤖 **ComCLIP: Training-Free Compositional Image and Text Matching.** *(ComCLIP).* [NAACL, 2024]. <br />
*Kenan Jiang, Xuehai He, Ruize Xu, Xin Eric Wang.* <br />
[[Paper](https://arxiv.org/abs/2211.13854)] [[Code](https://github.com/eric-ai-lab/ComCLIP)]

⚖️ **Lost in Space: Probing Fine-grained Spatial Understanding in Vision and Language Resamplers.** *(probing-resamplers).* [NAACL, 2024]. <br />
*Georgios Pantazopoulos, Alessandro Suglia, Oliver Lemon, Arash Eshghi.* <br />
[[Paper](https://arxiv.org/abs/2404.13594)] [[Code](https://github.com/gpantaz/probing-resamplers)]

⚖️ **How and where does CLIP process negation?**, [ALVR, 2024]. <br />
*Vincent Quantmeyer, Pablo Mosteiro, Albert Gatt.* <br />
[[Paper](https://arxiv.org/abs/2407.10488)]

🗂️**Rainbow - A Benchmark for Systematic Testing of How Sensitive Visio-Linguistic Models are to Color Naming.** *(Rainbow).* [EACL, 2024]. <br />
*Marie Bexte, Andrea Horbach, Torsten Zesch.* <br />
[[Paper](https://aclanthology.org/2024.eacl-long.112/)] [[Code](https://github.com/mariebexte/vl-probing)]

🤖 **Fine-tuning CLIP Text Encoders with Two-step Paraphrasing.** *(ParaCLIP)*. [EACL Findings, 2024]. <br />
*Hyunjae Kim, Seunghyun Yoon, Trung Bui, Handong Zhao, Quan Tran, Franck Dernoncourt, Jaewoo Kang.* <br />
[[Paper](https://arxiv.org/abs/2402.15120)] [[Code](https://github.com/dmis-lab/ParaCLIP)]

🤖 **Diffusion Feedback Helps CLIP See Better.** (*DIVA*). [arXiv, 2024]. <br />
*Wenxuan Wang, Quan Sun, Fan Zhang, Yepeng Tang, Jing Liu, Xinlong Wang.* <br />
[[Paper](https://arxiv.org/abs/2407.20171)] [[Code](https://github.com/baaivision/DIVA)]

🗂️ **SUGARCREPE++ Dataset: Vision-Language Model Sensitivity to Semantic and Lexical Alterations.** *(SUGARCREPE++)*. [arXiv, 2024]. <br />
*Sri Harsha Dumpala, Aman Jaiswal, Chandramouli Sastry, Evangelos Milios, Sageev Oore, Hassan Sajjad*. <br />
[[Paper](https://arxiv.org/abs/2406.11171)] [[Code](https://github.com/Sri-Harsha/scpp)]

🗂️ **ColorFoil: Investigating Color Blindness in Large Vision and Language Models.** *(ColorFoil).* [arXiv, 2024]. <br />
*Ahnaf Mozib Samin, M. Firoz Ahmed, Md. Mushtaq Shahriyar Rafee.* <br />
[[Paper](https://arxiv.org/abs/2405.11685)] [[Code](https://github.com/samin9796/ColorFoil)]

🗂️ **VISLA Benchmark: Evaluating Embedding Sensitivity to Semantic and Lexical Alterations.** *(VISLA).* [arXiv, 2024]. <br />
*Sri Harsha Dumpala, Aman Jaiswal, Chandramouli Sastry, Evangelos Milios, Sageev Oore, Hassan Sajjad.* <br />
[[Paper](https://arxiv.org/abs/2404.16365)] [[Code](https://github.com/Sri-Harsha/visla_benchmark)]

🗂️🤖 **Learn "No" to Say "Yes" Better: Improving Vision-Language Models via Negations.** *(CoN-CLIP).* [arXiv, 2024]. <br />
*Jaisidh Singh, Ishaan Shrivastava, Mayank Vatsa, Richa Singh, Aparna Bharati.* <br />
[[Paper](https://arxiv.org/abs/2403.20312)] [[Code](https://github.com/jaisidhsingh/CoN-CLIP)]

🤖 **Enhancing Conceptual Understanding in Multimodal Contrastive Learning through Hard Negative Samples.** [arXiv, 2024]. <br />
*Philipp J. Rösch, Norbert Oswald, Michaela Geierhos, Jindřich Libovický.* <br />
[[Paper](https://arxiv.org/abs/2403.02875)]

🤖 **CLoVe: Encoding Compositional Language in Contrastive Vision-Language Models.** *(CLoVe).* [arXiv, 2024]. <br />
*Santiago Castro, Amir Ziai, Avneesh Saluja, Zhuoning Yuan, Rada Mihalcea.* <br />
[[Paper](https://arxiv.org/abs/2402.15021)] [[Code](https://github.com/netflix/clove)]

🤖 **Prompting Large Vision-Language Models for Compositional Reasoning.** *(KeyComp).* [arXiv, 2024]. <br />
*Timothy Ossowski, Ming Jiang, Junjie Hu.* <br />
[[Paper](https://arxiv.org/abs/2401.11337)]  [[Code](https://github.com/tossowski/KeyComp)]

🤖 **FiGCLIP: Fine-Grained CLIP Adaptation via Densely Annotated Videos.** *(FiG-CLIP).* [arXiv, 2024]. <br />
*Darshan Singh S, Zeeshan Khan, Makarand Tapaswi.* <br />
[[Paper](https://arxiv.org/abs/2401.07669)] [[Code](https://github.com/Darshansingh11/FiGCLIP)]

🤖 **Structure-CLIP: Towards Scene Graph Knowledge to Enhance Multi-modal Structured Representations.** *(Structure-CLIP)*. [AAAI, 2024]. <br />
*Yufeng Huang, Jiji Tang, Zhuo Chen, Rongsheng Zhang, Xinfeng Zhang, Weijie Chen, Zeng Zhao, Zhou Zhao, Tangjie Lv, Zhipeng Hu, Wen Zhang.* <br />
[[Paper](https://arxiv.org/abs/2305.06152)] [[Code](https://github.com/zjukg/Structure-CLIP)]

🤖 **Enhancing Multimodal Compositional Reasoning of Visual Language Models with Generative Negative Mining.** *(GNM-CLIP).* [WACV, 2024]. <br />
*Ugur Sahin, Hang Li, Qadeer Khan, Daniel Cremers, Volker Tresp.* <br />
[[Paper](https://arxiv.org/abs/2311.03964)] [[Code](https://github.com/ugorsahin/Generative-Negative-Mining)]

🗂️ **COCO-Counterfactuals: Automatically Constructed Counterfactual Examples for Image-Text Pairs.** *(COCO-Counterfactuals).* [NeurIPS D&B, 2023]. <br />
*Tiep Le, Vasudev Lal, Phillip Howard.* <br />
[[Paper](https://arxiv.org/abs/2309.14356)] [[Code](https://github.com/IntelLabs/multimodal_cognitive_ai/tree/main/COCO-Counterfactuals)] [[HF Dataset](https://huggingface.co/datasets/Intel/COCO-Counterfactuals)]

🗂️ **SugarCrepe: Fixing Hackable Benchmarks for Vision-Language Compositionality.** *(SugarCrepe).* [NeurIPS D&B, 2023]. <br />
*Cheng-Yu Hsieh, Jieyu Zhang, Zixian Ma, Aniruddha Kembhavi, Ranjay Krishna.* <br />
[[Paper](https://arxiv.org/abs/2306.14610)] [[Code](https://github.com/RAIVNLab/sugar-crepe)]

🗂️ **PUG: Photorealistic and Semantically Controllable Synthetic Data for Representation Learning.** *(PUG).* [NeurIPS, 2023]. <br />
*Florian Bordes, Shashank Shekhar, Mark Ibrahim, Diane Bouchacourt, Pascal Vincent, Ari S. Morcos.* <br />
[[Paper](https://arxiv.org/abs/2308.03977)] [[Code](https://github.com/facebookresearch/PUG)]

🗂️ **COLA: A Benchmark for Compositional Text-to-image Retrieval.**  *(COLA).* [NeurIPS, 2023]. <br />
*Arijit Ray, Filip Radenovic, Abhimanyu Dubey, Bryan A. Plummer, Ranjay Krishna, Kate Saenko.* <br />
[[Paper](https://arxiv.org/abs/2305.03689)] [[Code](https://github.com/arijitray1993/COLA)]

🤖 **Dense and Aligned Captions (DAC) Promote Compositional Reasoning in VL Models.** *(DAC).* [NeurIPS, 2023]. <br />
*Sivan Doveh, Assaf Arbelle, Sivan Harary, Roei Herzig, Donghyun Kim, Paola Cascante-bonilla, Amit Alfassy, Rameswar Panda, Raja Giryes, Rogerio Feris, Shimon Ullman, Leonid Karlinsky.* <br />
[[Paper](https://arxiv.org/abs/2305.19595)] [[Code](https://github.com/SivanDoveh/DAC)]

🤖 **Image Captioners Are Scalable Vision Learners Too.** *(CapPa).* [NeurIPS, 2023]. <br />
*Michael Tschannen, Manoj Kumar, Andreas Steiner, Xiaohua Zhai, Neil Houlsby, Lucas Beyer.* <br />
[[Paper](https://arxiv.org/abs/2306.07915)]

🗂️🤖 **When and why vision-language models behave like bags-of-words, and what to do about it?.** *(ARO, NegCLIP).* [ICLR, 2023]. <br />
*Mert Yuksekgonul, Federico Bianchi, Pratyusha Kalluri, Dan Jurafsky, James Zou.* <br />
[[Paper](https://arxiv.org/abs/2210.01936)] [[Code](https://github.com/mertyg/vision-language-models-are-bows)]

🗂️ **What's "up" with vision-language models? Investigating their struggle with spatial reasoning.** *(WhatsUp).* [EMNLP, 2023]. <br />
*Amita Kamath, Jack Hessel, Kai-Wei Chang.* <br />
[[Paper](https://arxiv.org/abs/2310.19785)] [[Code](https://github.com/amitakamath/whatsup_vlms)]

🗂️⚖️ **Text encoders bottleneck compositionality in contrastive vision-language models.** *(ControlledLMCaps).* [EMNLP, 2023]. <br />
*Amita Kamath, Jack Hessel, Kai-Wei Chang.* <br />
[[Paper](https://arxiv.org/abs/2305.14897)] [[Code](https://github.com/amitakamath/vl_text_encoders_are_bottlenecks)]

🗂️ **The BLA Benchmark: Investigating Basic Language Abilities of Pre-Trained Multimodal Models.** *(BLA).* [EMNLP, 2023]. <br />
*Xinyi Chen, Raquel Fernández, Sandro Pezzelle.* <br />
[[Paper](https://arxiv.org/abs/2310.15061)] [[Code](https://github.com/shin-ee-chen/BLA)]

🗂️ **When are Lemons Purple? The Concept Association Bias of Vision-Language Models.** *(CAB).* [EMNLP, 2023]. <br />
*Yutaro Yamada, Yingtian Tang, Yoyo Zhang, Ilker Yildirim.* <br />
[[Paper](https://arxiv.org/abs/2212.12043)] 

🤖 **Coarse-to-Fine Contrastive Learning in Image-Text-Graph Space for Improved Vision-Language Compositionality.** *(MosaiCLIP).* [EMNLP, 2023]. <br />
*Harman Singh, Pengchuan Zhang, Qifan Wang, Mengjiao Wang, Wenhan Xiong, Jingfei Du, Yu Chen.* <br />
[[Paper](https://arxiv.org/abs/2305.13812)]

🤖 **Incorporating Structured Representations into Pretrained Vision & Language Models Using Scene Graphs.** *(SGVL).* [EMNLP, 2023]. <br />
*Roei Herzig, Alon Mendelson, Leonid Karlinsky, Assaf Arbelle, Rogerio Feris, Trevor Darrell, Amir Globerson.* <br />
[[Paper](https://arxiv.org/abs/2305.06343)] [[Code](https://github.com/AlonMendelson/SGVL)]

🗂️ **Visual Spatial Reasoning.** *(VSR).* [TACL, 2023]. <br />
*Fangyu Liu, Guy Emerson, Nigel Collier.* <br />
[[Paper](https://arxiv.org/abs/2205.00363)] [[Code](https://github.com/cambridgeltl/visual-spatial-reasoning)]

🗂️🤖 **Equivariant Similarity for Vision-Language Foundation Models.** *(EqBen).* [ICCV, 2023]. <br />
*Tan Wang, Kevin Lin, Linjie Li, Chung-Ching Lin, Zhengyuan Yang, Hanwang Zhang, Zicheng Liu, Lijuan Wang.* <br />
[[Paper](https://arxiv.org/abs/2303.14465)] [[Code](https://github.com/Wangt-CN/EqBen)]

🗂️ **Teaching CLIP to Count to Ten.** *(CountBench).* [ICCV, 2023]. <br />
*Roni Paiss, Ariel Ephrat, Omer Tov, Shiran Zada, Inbar Mosseri, Michal Irani, Tali Dekel.* <br />
[[Paper](https://arxiv.org/abs/2302.12066)] [[Code](https://github.com/teaching-clip-to-count/teaching-clip-to-count.github.io)] 

🤖 **Going Beyond Nouns With Vision & Language Models Using Synthetic Data.** *(SyViC).* [ICCV, 2023]. <br />
*Paola Cascante-Bonilla, Khaled Shehada, James Seale Smith, Sivan Doveh, Donghyun Kim, Rameswar Panda, Gül Varol, Aude Oliva, Vicente Ordonez, Rogerio Feris, Leonid Karlinsky.* <br />
[[Paper](https://arxiv.org/abs/2303.17590)] [[Code](https://github.com/uvavision/SyViC)]

⚖️ **Measuring Progress in Fine-grained Vision-and-Language Understanding.** [ACL, 2023]. <br />
*Emanuele Bugliarello, Laurent Sartran, Aishwarya Agrawal, Lisa Anne Hendricks, Aida Nematzadeh.* <br />
[[Paper](https://arxiv.org/abs/2305.07558)] [[Code](https://github.com/e-bug/fine-grained-evals)]

🗂️ **CREPE: Can Vision-Language Foundation Models Reason Compositionally?** *(CREPE).* [CVPR, 2023]. <br />
*Zixian Ma, Jerry Hong, Mustafa Omer Gul, Mona Gandhi, Irena Gao, Ranjay Krishna.* <br />
[[Paper](https://arxiv.org/abs/2212.07796)] [[Code](https://github.com/RAIVNLab/CREPE)]

🤖 **Teaching Structured Vision&Language Concepts to Vision&Language Models.** *(TSVLC).* [CVPR, 2023]. <br />
*Sivan Doveh, Assaf Arbelle, Sivan Harary, Rameswar Panda, Roei Herzig, Eli Schwartz, Donghyun Kim, Raja Giryes, Rogerio Feris, Shimon Ullman, Leonid Karlinsky.* <br />
[[Paper](https://arxiv.org/abs/2211.11733)] [[Code](https://github.com/SivanDoveh/TSVLC)]

🗂️ **HL Dataset: Visually-grounded Description of Scenes, Actions and Rationales.** *(HL Dataset).* [INLG, 2023]. <br />
*Michele Cafagna, Kees van Deemter, Albert Gatt.* <br />
[[Paper](https://arxiv.org/abs/2302.12189)] [[Code](https://github.com/michelecafagna26/HL-dataset)]

🗂️ **Can Linguistic Knowledge Improve Multimodal Alignment in Vision-Language Pretraining?** *(SNARE).* [arXiv, 2023]. <br />
*Fei Wang, Liang Ding, Jun Rao, Ye Liu, Li Shen, Changxing Ding.* <br />
[[Paper](https://arxiv.org/abs/2308.12898)] [[Code](https://github.com/WangFei-2019/SNARE/)]

🗂️ **Do Vision-and-Language Transformers Learn Grounded Predicate-Noun Dependencies?.** *(Predicate-Noun-Dependencies).* [EMNLP, 2022]. <br />
*Mitja Nikolaus, Emmanuelle Salin, Stephane Ayache, Abdellah Fourtassi, Benoit Favre.* <br />
[[Paper](https://arxiv.org/abs/2210.12079)] [[Code](https://github.com/mitjanikolaus/multimodal-predicate-noun-dependencies)]

🗂️⚖️ **Why is Winoground Hard? Investigating Failures in Visuolinguistic Compositionality.** [EMNLP, 2022]. <br />
*Anuj Diwan, Layne Berry, Eunsol Choi, David Harwath, Kyle Mahowald.* <br />
[[Paper](https://arxiv.org/abs/2211.00768)] [[Code](https://github.com/ajd12342/why-winoground-hard)]

🗂️ **VIPHY: Probing "Visible" Physical Commonsense Knowledge.** *(ViPhy).* [EMNLP Findings, 2022]. <br />
*Shikhar Singh, Ehsan Qasemi, Muhao Chen.* <br />
[[Paper](https://arxiv.org/abs/2209.07000)] [[Code](https://github.com/Axe--/ViPhy)]

🗂️ **VL-CheckList: Evaluating Pre-trained Vision-Language Models with Objects, Attributes and Relations.** *(VL-Checklist).* [EMNLP Demo, 2022]. <br />
*Tiancheng Zhao, Tianqi Zhang, Mingwei Zhu, Haozhan Shen, Kyusong Lee, Xiaopeng Lu, Jianwei Yin.* <br />
[[Paper](https://arxiv.org/abs/2207.00221)] [[Code](https://github.com/om-ai-lab/VL-CheckList)]

🗂️ **Winoground: Probing Vision and Language Models for Visio-Linguistic Compositionality.** *(Winoground).* [CVPR, 2022]. <br />
*Tristan Thrush, Ryan Jiang, Max Bartolo, Amanpreet Singh, Adina Williams, Douwe Kiela, Candace Ross.* <br />
[[Paper](https://arxiv.org/abs/2204.03162)] [[HF Dataset](https://huggingface.co/datasets/facebook/winoground)]

🗂️ **VALSE: A Task-Independent Benchmark for Vision and Language Models Centered on Linguistic Phenomena.** *(VALSE).* [ACL, 2022]. <br />
*Letitia Parcalabescu, Michele Cafagna, Lilitta Muradjan, Anette Frank, Iacer Calixto, Albert Gatt.* <br />
[[Paper](https://arxiv.org/abs/2112.07566)] [[Code](https://github.com/Heidelberg-NLP/VALSE)]

🗂️ **Image Retrieval from Contextual Descriptions.** *(ImageCoDe).* [ACL, 2022]. <br />
*Benno Krojer, Vaibhav Adlakha, Vibhav Vineet, Yash Goyal, Edoardo Ponti, Siva Reddy.* <br />
[[Paper](https://arxiv.org/abs/2203.15867)] [[Code](https://github.com/McGill-NLP/imagecode)]

🗂️ **Probing Image-Language Transformers for Verb Understanding.** *(SVO Probes).* [ACL Findings, 2021]. <br />
*Lisa Anne Hendricks, Aida Nematzadeh.* <br />
[[Paper](https://arxiv.org/abs/2106.09141)] [[Code](https://github.com/google-deepmind/svo_probes)] [[HF Dataset](https://huggingface.co/datasets/MichiganNLP/svo_probes)]

🗂️ **Seeing past words: Testing the cross-modal capabilities of pretrained V&L models on counting tasks.** *(Counting-Probe).* [MMSR, 2021]. <br />
*Letitia Parcalabescu, Albert Gatt, Anette Frank, Iacer Calixto.* <br />
[[Paper](https://arxiv.org/abs/2012.12352)] [[Code](https://github.com/Heidelberg-NLP/counting-probe)]

🗂️ **FOIL it! Find One mismatch between Image and Language caption.** *(FOIL).* [ACL, 2017]. <br />
*Ravi Shekhar, Sandro Pezzelle, Yauhen Klimovich, Aurelie Herbelot, Moin Nabi, Enver Sangineto, Raffaella Bernardi.* <br />
[[Paper](https://arxiv.org/abs/1705.01359)] [[Dataset](https://foilunitn.github.io/)]

<br />

## Compositionality in Video-Text Understanding

🗂️ **TemporalBench: Benchmarking Fine-grained Temporal Understanding for Multimodal Video Models.** *(TemporalBench).* [arXiv, 2024]. <br />
*Mu Cai, Reuben Tan, Jianrui Zhang, Bocheng Zou, Kai Zhang, Feng Yao, Fangrui Zhu, Jing Gu, Yiwu Zhong, Yuzhang Shang, Yao Dou, Jaden Park, Jianfeng Gao, Yong Jae Lee, Jianwei Yang.* <br />
[[Paper](https://arxiv.org/abs/2410.10818)]  [[Code](https://github.com/mu-cai/TemporalBench)]  [[HF Dataset](https://huggingface.co/datasets/microsoft/TemporalBench)]

🗂️ **Vinoground: Scrutinizing LMMs over Dense Temporal Reasoning with Short Videos.** *(Vinoground).* [arXiv, 2024]. <br />
*Jianrui Zhang, Mu Cai, Yong Jae Lee.* <br />
[[Paper](https://arxiv.org/abs/2410.02763)]  [[Code](https://github.com/Vinoground/Vinoground)]  [[HF Dataset](https://huggingface.co/datasets/HanSolo9682/Vinoground)]

🗂️🤖 **VideoCon: Robust Video-Language Alignment via Contrast Captions.** *(VideoCon).* [CVPR, 2024]. <br />
*Hritik Bansal, Yonatan Bitton, Idan Szpektor, Kai-Wei Chang, Aditya Grover.* <br />
[[Paper](https://arxiv.org/abs/2311.10111)] [[Code](https://github.com/Hritikbansal/videocon)] [[Project](https://video-con.github.io/)] [[HF Dataset](https://huggingface.co/datasets/videocon/videocon)] [[HF Model](https://huggingface.co/videocon/owl-con/tree/main)]

🗂️ **NAVERO: Unlocking Fine-Grained Semantics for Video-Language Compositionality.** (*NAVERO*). [arXiv, 2024]. <br />
*Chaofan Tao, Gukyeong Kwon, Varad Gunjal, Hao Yang, Zhaowei Cai, Yonatan Dukler, Ashwin Swaminathan, R. Manmatha, Colin Jon Taylor, Stefano Soatto.* <br />
[[Paper](https://arxiv.org/abs/2408.09511)]

<br />

## Compositionality in Text to Image Generation

🗂️ **ConceptMix: A Compositional Image Generation Benchmark with Controllable Difficulty.** *(ConceptMix).* [NeurIPS, 2024]. <br />
*Xindi Wu, Dingli Yu, Yangsibo Huang, Olga Russakovsky, Sanjeev Arora.* <br />
[[Paper](https://arxiv.org/abs/2408.14339)]  [[Code](https://github.com/princetonvisualai/ConceptMix)]


<br />

## Contributing

If you find any errors or would like to add papers, please feel free to contribute by contacting [me](https://ytaek-oh.github.io), posting an issue, or submitting a pull request. Please use the following Markdown format for the pull requests, including `<br />` tag:

```markdown
**Paper Title.** *(Optional Method/Benchmark name or abbreviation).* [Conference/Journal, Year]. <br />
*Authors.*  <br />
[[Paper](link)] [[Code](link)] [[HF Dataset](link)]
```

