# training-free-methods
This repository collects recent training-free algorithms relevant to visual generation and manipulation, with a focus on methods that can be run on a single GPU (ideally with ≤24GB memory). Hope it could be beneficial for students and researchers with limited computational resources.

If you find any missed resources or errors, feel free to open an issue or make a pull request.

<a name="top"></a>
## 📚 Table of Contents
- [Image Generation](#image-generation)
- [Image Manipulation](#image-manipulation)
- [Style Transfer](#style-transfer)
- [Material Transfer](#material-transfer)
- [Video Generation](#video-generation)
- [Video Manipulation](#video-manipulation)
- [3D Generation](#3d-generation)
- [3D Manipulation](#3d-manipulation)

## Image Generation

**Training-Free Generation of Diverse and High-Fidelity Images via Prompt Semantic Space Optimization.**<br>
*Debin Meng, Chen Jin, Zheng Gao, Yanran Li, Ioannis Patras, Georgios Tzimiropoulos.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2511.19811)]<br>

**A Training-Free Approach for Multi-ID Customization via Attention Adjustment and Spatial Control.**<br>
*Jiawei Lin, Guanlong Jiao, Jianjin Xu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2511.20401)]<br>

**Infinite-Story: A Training-Free Consistent Text-to-Image Generation.**<br>
*Jihun Park, Kyoungmin Lee, Jongmin Gim, Hyeonseo Jo, Minseok Oh, Wonhyeok Choi, Kyumin Hwang, Jaeyeul Kim, Minwoo Choi, Sunghoon Im.*<br>
AAAI 2026. [[PDF](https://arxiv.org/abs/2511.13002)]<br>

**TAUE: Training-free Noise Transplant and Cultivation Diffusion Model.**<br>
*Daichi Nagai, Ryugo Morita, Shunsuke Kitada, Hitoshi Iyatomi.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2511.02580)]  [[Project]](https://iyatomilab.github.io/TAUE/) [[Code]](https://github.com/IyatomiLab/TAUE)<br>

**ETC: training-free diffusion models acceleration with Error-aware Trend Consistency.**<br>
*Jiajian Xie, Hubery Yin, Chen Li, Zhou Zhao, Shengyu Zhang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.24129)]<br>

**GeoDiffusion: A Training-Free Framework for Accurate 3D Geometric Conditioning in Image Generation.**<br>
*Phillip Mueller, Talip Uenlue, Sebastian Schmidt, Marcel Kollovieh, Jiajie Fan, Stephan Guennemann, Lars Mikelsons.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2510.22337)] [[Code]](https://github.com/Phillip-M97/ICCV_GeoDiff)<br>

**Stroke2Sketch: Harnessing Stroke Attributes for Training-Free Sketch Generation.**<br>
*Rui Yang, Huining Li, Yiyi Long, Xiaojun Wu, Shengfeng He.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2510.16319)] [[Code]](https://github.com/rane7/Stroke2Sketch)<br>

**MosaicDiff: Training-free Structural Pruning for Diffusion Model Acceleration Reflecting Pretraining Dynamics.**<br>
*Bowei Guo, Shengkun Tang, Cong Zeng, Zhiqiang Shen.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2510.11962)] [[Code]](https://github.com/bwguo105/MosaicDiff)<br>

**PEO: Training-Free Aesthetic Quality Enhancement in Pre-Trained Text-to-Image Diffusion Models with Prompt Embedding Optimization.**<br>
*Hovhannes Margaryan, Bo Wan, Tinne Tuytelaars.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.02599)] [[Code]](https://github.com/marghovo/PEO)<br>

**Stitch: Training-Free Position Control in Multimodal Diffusion Transformers.**<br>
*Jessica Bader, Mateusz Pach, Maria A. Bravo, Serge Belongie, Zeynep Akata.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2509.26644)] [[Code]](https://github.com/ExplainableML/Stitch)<br>

**SemanticControl: A Training-Free Approach for Handling Loosely Aligned Visual Conditions in ControlNet.**<br>
*Woosung Joung, Daewon Chae, Jinkyu Kim.*<br>
BMVC 2025. [[PDF](https://arxiv.org/abs/2509.21938)]  [[Project]](https://mung3477.github.io/semantic-control/) [[Code]](https://github.com/mung3477/SemanticControl)<br>

**Training-Free Synthetic Data Generation with Dual IP-Adapter Guidance.**<br>
*Luc Boudier, Loris Manganelli, Eleftherios Tsonis, Nicolas Dufour, Vicky Kalogeiton.*<br>
BMVC 2025. [[PDF](https://arxiv.org/abs/2509.22635)]  [[Project]](https://www.lix.polytechnique.fr/vista/projects/2025_bmvc_dipsy/) <br>

**InfoScale: Unleashing Training-free Variable-scaled Image Generation via Effective Utilization of Information.**<br>
*Guohui Zhang, Jiangtong Tan, Linjiang Huang, Zhonghang Yuan, Naishan Zheng, Jie Huang, Feng Zhao.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2509.01421)] [[Code]](https://github.com/zghhui/InfoScale)<br>

**CountLoop: Training-Free High-Instance Image Generation via Iterative Agent Guidance.**<br>
*Anindya Mondal, Ayan Banerjee, Sauradip Nag, Josep Lladós, Xiatian Zhu, Anjan Dutta.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.16644)]  [[Project]](https://mondalanindya.github.io/CountLoop/) [[Code]](https://github.com/mondalanindya/CountLoop/)<br>

**HiCache: Training-free Acceleration of Diffusion Models via Hermite Polynomial-based Feature Caching.**<br>
*Liang Feng, Shikang Zheng, Jiacheng Liu, Yuqi Lin, Qinming Zhou, Peiliang Cai, Xinyu Wang, Junjie Chen, Chang Zou, Yue Ma, Linfeng Zhang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.16984)]<br>

**S^2-Guidance: Stochastic Self Guidance for Training-Free Enhancement of Diffusion Models.**<br>
*Chubin Chen, Jiashu Zhu, Xiaokun Feng, Nisha Huang, Meiqi Wu, Fangyuan Mao, Jiahong Wu, Xiangxiang Chu, Xiu Li.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.12880)]  [[Project]](https://s2guidance.github.io/) [[Code]](https://github.com/AMAP-ML/S2-Guidance)<br>

**CountCluster: Training-Free Object Quantity Guidance with Cross-Attention Map Clustering for Text-to-Image Generation.**<br>
*Joohyeon Lee, Jin-Seop Lee, Jee-Hyong Lee.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.10710)] [[Code]](https://github.com/JoohyeonL22/CountCluster)<br>

**Subject or Style: Adaptive and Training-Free Mixture of LoRAs.**<br>
*Jia-Chen Zhang, Yu-Jie Xiong.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.02165)] [[Code]](https://anonymous.4open.science/r/EST-LoRA-F318)<br>

**FreeLoRA: Enabling Training-Free LoRA Fusion for Autoregressive Multi-Subject Personalization.**<br>
*Peng Zheng, Ye Wang, Rui Ma, Zuxuan Wu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2507.01792)]<br>

**Story2Board: A Training-Free Approach for Expressive Storyboard Generation.**<br>
*David Dinkevich, Matan Levy, Omri Avrahami, Dvir Samuel, Dani Lischinski.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.09983)]  [[Project]](https://daviddinkevich.github.io/Story2Board/) [[Code]](https://github.com/daviddinkevich/Story2Board)<br>

**LaRender: Training-Free Occlusion Control in Image Generation via Latent Rendering.**<br>
*Xiaohang Zhan, Dingming Liu.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2508.07647)]  [[Project]](https://xiaohangzhan.github.io/projects/larender/)<br>

**T2I-Copilot: A Training-Free Multi-Agent Text-to-Image System for Enhanced Prompt Interpretation and Interactive Generation.**<br>
*Chieh-Yun Chen, Min Shi, Gong Zhang, Humphrey Shi.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2507.20536)] [[Code]](https://github.com/SHI-Labs/T2I-Copilot)<br>

**FreeCus: Free Lunch Subject-driven Customization in Diffusion Transformers.**<br>
*Yanbing Zhang, Zhe Wang, Qin Zhou, Mengping Yang.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2507.15249)] [[Code]](https://github.com/Monalissaa/FreeCus)<br>

**Normalized Attention Guidance: Universal Negative Guidance for Diffusion Models.**<br>
*Dar-Yen Chen, Hmrishav Bandyopadhyay, Kai Zou, Yi-Zhe Song.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.21179)]  [[Project]](https://chendaryen.github.io/NAG.github.io/) [[Code]](https://github.com/ChenDarYen/Normalized-Attention-Guidance)<br>

**A Training-Free Style-Personalization via Scale-wise Autoregressive Model.**<br>
*Kyoungmin Lee, Jihun Park, Jongmin Gim, Wonhyeok Choi, Kyumin Hwang, Jaeyeul Kim, Sunghoon Im.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2507.04482)]<br>

**RichControl: Structure- and Appearance-Rich Training-Free Spatial Control for Text-to-Image Generation.**<br>
*Liheng Zhang, Lexi Pang, Hang Ye, Xiaoxuan Ma, Yizhou Wang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2507.02792)]  [[Project]](https://zhang-liheng.github.io/rich-control/) [[Code]](https://github.com/zhang-liheng/RichControl)<br>

**FreeMorph: Tuning-Free Generalized Image Morphing with Diffusion Model.**<br>
*Yukang Cao, Chenyang Si, Jinghao Wang, Ziwei Liu.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2507.01953)]  [[Project]](https://yukangcao.github.io/FreeMorph/) [[Code]](https://github.com/yukangcao/FreeMorph)<br>

**HiWave: Training-Free High-Resolution Image Generation via Wavelet-Based Diffusion Sampling.**<br>
*Tobias Vontobel, Seyedmorteza Sadat, Farnood Salehi, Romann M. Weber.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.20452)]<br>

**Control and Realism: Best of Both Worlds in Layout-to-Image without Training.**<br>
*Bonan Li, Yinhan Hu, Songhua Liu, Xinchao Wang.*<br>
ICML 2025. [[PDF](https://arxiv.org/abs/2506.15563)]<br>

**LoRAShop: Training-Free Multi-Concept Image Generation and Editing with Rectified Flow Transformers.**<br>
*Yusuf Dalva, Hidir Yesiltepe, Pinar Yanardag.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.23758)] [[Project]](https://lorashop.github.io/)<br>

**MultLFG: Training-free Multi-LoRA composition using Frequency-domain Guidance.**<br>
*Aniket Roy, Maitreya Suin, Ketul Shah, Rama Chellappa.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.20525)]<br>

**ConsiStyle: Style Diversity in Training-Free Consistent T2I Generation.**<br>
*Yohai Mazuz, Janna Bruner, Lior Wolf.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.20626)] [[Project]](https://jbruner23.github.io/consistyle/)<br>

**ISAC: Training-Free Instance-to-Semantic Attention Control for Improving Multi-Instance Generation.**<br>
*Sanghyun Jo, Wooyeol Lee, Ziseok Lee, Kyungsu Kim.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.20935)]<br>

**ExpertGen: Training-Free Expert Guidance for Controllable Text-to-Face Generation.**<br>
*Liang Shi, Yun Fu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.17256)]<br>

**Training-Free Watermarking for Autoregressive Image Generation.**<br>
*Yu Tong, Zihao Pan, Shuai Yang, Kaiyang Zhou.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.14673)] [[Code]](https://github.com/maifoundations/IndexMark)<br>

**Grouping First, Attending Smartly: Training-Free Acceleration for Diffusion Transformers.**<br>
*Sucheng Ren, Qihang Yu, Ju He, Alan Yuille, Liang-Chieh Chen.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.14687)]  [[Project]](https://oliverrensu.github.io/project/GRAT/) [[Code]](https://github.com/OliverRensu/GRAT)<br>

**CountDiffusion: Text-to-Image Synthesis with Training-Free Counting-Guidance Diffusion.**<br>
*Yanyu Li, Pencheng Wan, Liang Han, Yaowei Wang, Liqiang Nie, Min Zhang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.04347)]<br>

**SphereDiff: Tuning-free Omnidirectional Panoramic Image and Video Generation via Spherical Latent Representation.**<br>
*Minho Park, Taewoong Kang, Jooyeol Yun, Sungwon Hwang, Jaegul Choo.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.14396)]  [[Project]](https://pmh9960.github.io/research/SphereDiff/) [[Code]](https://github.com/pmh9960/SphereDiff)<br>

**FreeGraftor: Training-Free Cross-Image Feature Grafting for Subject-Driven Text-to-Image Generation.**<br>
*Zebin Yao, Lei Ren, Huixing Jiang, Chen Wei, Xiaojie Wang, Ruifan Li, Fangxiang Feng.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.15958)] [[Code]](https://github.com/Nihukat/FreeGraftor)<br>

**Storybooth: Training-free Multi-Subject Consistency for Improved Visual Storytelling.**<br>
*Jaskirat Singh, Junshen Kevin Chen, Jonas Kohler, Michael Cohen.*<br>
ICLR 2025. [[PDF](https://arxiv.org/abs/2504.05800)]<br>

**A Training-Free Style-aligned Image Generation with Scale-wise Autoregressive Model.**<br>
*Jihun Park, Jongmin Gim, Kyoungmin Lee, Minseok Oh, Minwoo Choi, Jaeyeul Kim, Woo Chool Park, Sunghoon Im.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.06144)]<br>

**HiFlow: Training-free High-Resolution Image Generation with Flow-Aligned Guidance.**<br>
*Jiazi Bu, Pengyang Ling, Yujie Zhou, Pan Zhang, Tong Wu, Xiaoyi Dong, Yuhang Zang, Yuhang Cao, Dahua Lin, Jiaqi Wang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.06232)] [[Code]](https://github.com/Bujiazi/HiFlow)<br>

**Training-free Dense-Aligned Diffusion Guidance for Modular Conditional Image Synthesis.**<br>
*Zixuan Wang, Duo Peng, Feng Chen, Yuwei Yang, Yinjie Lei.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.01515)] [[Code]](https://github.com/ZixuanWang0525/DADG)<br>

**Spatial Transport Optimization by Repositioning Attention Map for Training-Free Text-to-Image Synthesis.**<br>
*Woojung Han, Yeonkyung Lee, Chanyoung Kim, Kwanghyun Park, Seong Jae Hwang.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2503.22168)] [[Project]](https://micv-yonsei.github.io/storm2025/) [[Code]](https://github.com/MICV-yonsei/STORM)<br>

**TF-TI2I: Training-Free Text-and-Image-to-Image Generation via Multi-Modal Implicit-Context Learning in Text-to-Image Models.**<br>
*Teng-Fang Hsiao, Bo-Kai Ruan, Yi-Lun Wu, Tzu-Ling Lin, Hong-Han Shuai.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.15283)] [[Project]](https://bluedyee.github.io/TF-TI2I_page/) [[Code]](https://github.com/BlueDyee/TF-TI2I)<br>

**Personalize Anything for Free with Diffusion Transformer.**<br>
*Haoran Feng, Zehuan Huang, Lin Li, Hairong Lv, Lu Sheng.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.12590)] [[Project]](https://fenghora.github.io/Personalize-Anything-Page/) [[Code]](https://github.com/fenghora/personalize-anything)<br>

**Localized Concept Erasure for Text-to-Image Diffusion Models Using Training-Free Gated Low-Rank Adaptation.**<br>
*Byung Hyun Lee, Sungjin Lim, Se Young Chun.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2503.12356)]<br>

**EditID: Training-Free Editable ID Customization for Text-to-Image Generation.**<br>
*Guandong Li, Zhaobin Chu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.12526)]<br>

**ToLo: A Two-Stage, Training-Free Layout-To-Image Generation Framework For High-Overlap Layouts.**<br>
*Linhao Huang, Jing Yu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.01667)] [[Code]](https://github.com/misaka12435/ToLo)<br>

**FlipConcept: Tuning-Free Multi-Concept Personalization for Text-to-Image Generation.**<br>
*Young Beom Woo, Sun Eung Kim.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2502.15203)]<br>

**MagicGeo: Training-Free Text-Guided Geometric Diagram Generation.**<br>
*Junxiao Wang, Ting Zhang, Heng Yu, Jingdong Wang, Hua Huang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2502.13855)]<br>

**LoRA-X: Bridging Foundation Models with Training-Free Cross-Model Adaptation.**<br>
*Farzad Farhadzadeh, Debasmit Das, Shubhankar Borse, Fatih Porikli.*<br>
ICLR 2025. [[PDF](https://arxiv.org/abs/2501.16559)]<br>

**Event-Customized Image Generation.**<br>
*Zhen Wang, Yilei Jiang, Dong Zheng, Jun Xiao, Long Chen.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2410.02483)]<br>

**AP-LDM: Attentive and Progressive Latent Diffusion Model for Training-Free High-Resolution Image Generation.**<br>
*Boyuan Cao, Jiaxin Ye, Yujie Wei, Hongming Shan.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2410.06055)] [[Code]](https://github.com/kmittle/AP-LDM)<br>

**Training-free Color-Style Disentanglement for Constrained Text-to-Image Synthesis.**<br>
*Aishwarya Agarwal, Srikrishna Karanam, Balaji Vasan Srinivasan.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2409.02429)]<br>

**Smoothed Energy Guidance: Guiding Diffusion Models with Reduced Energy Curvature of Attention.**<br>
*Susung Hong.*<br>
NeurIPS 2024. [[PDF](https://arxiv.org/abs/2408.00760)] [[Code]](https://github.com/SusungHong/SEG-SDXL)<br>

**MegaFusion: Extend Diffusion Models towards Higher-resolution Image Generation without Further Tuning.**<br>
*Haoning Wu, Shaocheng Shen, Qiang Hu, Xiaoyun Zhang, Ya Zhang, Yanfeng Wang.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2408.11001)] [[Project](https://haoningwu3639.github.io/MegaFusion/)] [[Code]](https://github.com/ShaochengShen/MegaFusion/)<br>

**DiffuseHigh: Training-free Progressive High-Resolution Image Synthesis through Structure Guidance.**<br>
*Younghyun Kim, Geunmin Hwang, Junyu Zhang, Eunbyung Park.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2406.18459)] [[Project](https://yhyun225.github.io/DiffuseHigh/)] [[Code]](https://github.com/yhyun225/DiffuseHigh)<br>

**TraDiffusion: Trajectory-Based Training-Free Image Generation.**<br>
*Mingrui Wu, Oucheng Huang, Jiayi Ji, Jiale Li, Xinyue Cai, Huafeng Kuang, Jianzhuang Liu, Xiaoshuai Sun, Rongrong Ji.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2408.09739)] [[Code]](https://github.com/och-mac/TraDiffusion)<br>

**MagicFace: Training-free Universal-Style Human Image Customized Synthesis.**<br>
*Yibin Wang, Weizhong Zhang, Cheng Jin.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2408.07433)] [[Project](https://codegoat24.github.io/MagicFace/)] [[Code]](https://github.com/CodeGoat24/MagicFace)<br>

**AccDiffusion: An Accurate Method for Higher-Resolution Image Generation.**<br>
*Zhihang Lin, Mingbao Lin, Meng Zhao, Rongrong Ji.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2407.10738v2)] [[Project](https://lzhxmu.github.io/accdiffusion/accdiffusion.html)] [[Code]](https://github.com/lzhxmu/AccDiffusion)<br>

**ResMaster: Mastering High-Resolution Image Generation via Structural and Fine-Grained Guidance.**<br>
*Shuwei Shi, Wenbo Li, Yuechen Zhang, Jingwen He, Biao Gong, Yinqiang Zheng.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2406.16476)] [[Project](https://shuweis.github.io/ResMaster/)] [[Code]](https://github.com/Shuweis/ResMaster)<br>

**Coherent Zero-Shot Visual Instruction Generation.**<br>
*Quynh Phung, Songwei Ge, Jia-Bin Huang.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2406.04337)] [[Project](https://instruct-vis-zero.github.io/)]<br>

**FreeCustom: Tuning-Free Customized Image Generation for Multi-Concept Composition.**<br>
*Ganggui Ding, Canyu Zhao, Wen Wang, Zhen Yang, Zide Liu, Hao Chen, Chunhua Shen.*<br>
CVPR 2024. [[PDF](https://arxiv.org/pdf/2405.13870)] [[Code]](https://github.com/aim-uofa/FreeCustom)<br>

**Training-free Subject-Enhanced Attention Guidance for Compositional Text-to-image Generation.**<br>
*Shengyuan Liu, Bo Wang, Ye Ma, Te Yang, Xipeng Cao, Quan Chen, Han Li, Di Dong, Peng Jiang.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2405.06948)]<br>

**DemoFusion: Democratising High-Resolution Image Generation With No $$$.**<br>
*Ruoyi Du, Dongliang Chang, Timothy Hospedales, Yi-Zhe Song, Zhanyu Ma.*<br>
CVPR 2024. [[PDF](https://arxiv.org/pdf/2311.16973.pdf)] [[Project]](https://ruoyidu.github.io/demofusion/demofusion.html) [[Code]](https://github.com/PRIS-CV/DemoFusion)<br>

**HiDiffusion: Unlocking High-Resolution Creativity and Efficiency in Low-Resolution Trained Diffusion Models.**<br>
*Shen Zhang, Zhaowei Chen, Zhenyu Zhao, Zhenyuan Chen, Yao Tang, Yuhao Chen, Wengang Cao, Jiajun Liang.*<br>
ECCV 2024. [[PDF](https://arxiv.org/pdf/2311.17528.pdf)] [[Project]](https://hidiffusion.github.io/) [[Code]](https://github.com/megvii-research/HiDiffusion)<br>

**Training-Free Consistent Text-to-Image Generation.**<br>
*Yoad Tewel, Omri Kaduri, Rinon Gal, Yoni Kasten, Lior Wolf, Gal Chechik, Yuval Atzmon.*<br>
SIGGRAPH 2024. [[PDF](https://arxiv.org/pdf/2402.03286.pdf)] [[Project]](https://research.nvidia.com/labs/par/consistory/)<br>

**FouriScale: A Frequency Perspective on Training-Free High-Resolution Image Synthesis.**<br>
*Linjiang Huang, Rongyao Fang, Aiping Zhang, Guanglu Song, Si Liu, Yu Liu, Hongsheng Li.*<br>
ECCV 2024. [[PDF](https://arxiv.org/pdf/2403.12963.pdf)] [[Code]](https://github.com/LeonHLJ/FouriScale)<br>

**Training-Free Layout Control with Cross-Attention Guidance.**<br>
*Minghao Chen, Iro Laina, Andrea Vedaldi.*<br>
WACV 2024. [[PDF](https://arxiv.org/abs/2304.03373)]  [[Project]](https://silent-chen.github.io/layout-guidance/) [[Code]](https://github.com/silent-chen/layout-guidance)<br>

**BoxDiff: Text-to-Image Synthesis with Training-Free Box-Constrained Diffusion.**<br>
*Jinheng Xie, Yuexiang Li, Yawen Huang, Haozhe Liu, Wentian Zhang, Yefeng Zheng, Mike Zheng Shou.*<br>
ICCV 2023. [[PDF](https://arxiv.org/abs/2307.10816)] [[Code]](https://github.com/showlab/BoxDiff)<br>

[🔝 Return to Top](#top)

## Image Manipulation

**FreeControl: Efficient, Training-Free Structural Control via One-Step Attention Extraction.**<br>
*Jiang Lin, Xinyu Chen, Song Wu, Zhiqiu Zhang, Jizhi Zhang, Ye Wang, Qiang Tang, Qian Wang, Jian Yang, Zili Yi.*<br>
NeurIPS 2025. [[PDF](https://arxiv.org/abs/2511.05219)]<br>

**SplitFlow: Flow Decomposition for Inversion-Free Text-to-Image Editing.**<br>
*Sung-Hoon Yoon, Minghan Li, Gaspard Beaudouin, Congcong Wen, Muhammad Rafay Azhar, Mengyu Wang.*<br>
NeurIPS 2025. [[PDF](https://arxiv.org/abs/2510.25970)] [[Code]](https://github.com/Harvard-AI-and-Robotics-Lab/SplitFlow)<br>

**RegionE: Adaptive Region-Aware Generation for Efficient Image Editing.**<br>
*Pengtao Chen, Xianfang Zeng, Maosen Zhao, Mingzhu Shen, Peng Ye, Bangyin Xiang, Zhibo Wang, Wei Cheng, Gang Yu, Tao Chen.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.25590)] [[Code]](https://github.com/Peyton-Chen/RegionE)<br>

**OmniText: A Training-Free Generalist for Controllable Text-Image Manipulation.**<br>
*Agus Gunawan, Samuel Teodoro, Yun Chen, Soo Ye Kim, Jihyong Oh, Munchurl Kim.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.24093)] [[Project](https://kaist-viclab.github.io/omnitext-site)]<br>

**ConsistEdit: Highly Consistent and Precise Training-free Visual Editing.**<br>
*Zixin Yin, Ling-Hao Chen, Lionel Ni, Xili Dai.*<br>
SIGGRAPH Asia 2025. [[PDF](https://arxiv.org/abs/2510.17803)] [[Project](https://zxyin.github.io/ConsistEdit/)] [[Code]](https://github.com/zxYin/ConsistEdit_Code)<br>

**Coupled Diffusion Sampling for Training-Free Multi-View Image Editing.**<br>
*Hadi Alzayer, Yunzhi Zhang, Chen Geng, Jia-Bin Huang, Jiajun Wu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.14981)] [[Project](https://coupled-diffusion.github.io/)] [[Code]](https://github.com/HadiZayer/coupled-diffusion)<br>

**RetouchLLM: Training-free White-box Image Retouching.**<br>
*Moon Ye-Bin, Roy Miles, Tae-Hyun Oh, Ismail Elezi, Jiankang Deng.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.08054)]<br>

**Teleportraits: Training-Free People Insertion into Any Scene.**<br>
*Jialu Gao, K J Joseph, Fernando De La Torre.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.05660)]<br>

**Token Painter: Training-Free Text-Guided Image Inpainting via Mask Autoregressive Models.**<br>
*Longtao Jiang, Mingfei Han, Lei Chen, Yongqiang Yu, Feng Zhao, Xiaojun Chang, Zhihui Li.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2509.23919)]<br>

**FreeInsert: Personalized Object Insertion with Geometric and Style Control.**<br>
*Yuhong Zhang, Han Wang, Yiwen Wang, Rong Xie, Li Song.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2509.20756)]<br>

**Training-Free Text-Guided Color Editing with Multi-Modal Diffusion Transformer.**<br>
*Zixin Yin, Xili Dai, Ling-Hao Chen, Deyu Zhou, Jianan Wang, Duomin Wang, Gang Yu, Lionel M. Ni, Heung-Yeung Shum.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.09131)]  [[Project](https://zxyin.github.io/ColorCtrl/)]<br>

**CannyEdit: Selective Canny Control and Dual-Prompt Guidance for Training-Free Image Editing.**<br>
*Weiyan Xie, Han Gao, Didan Deng, Kaican Li, April Hua Liu, Yongxiang Huang, Nevin L. Zhang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.06937)]  [[Project](https://vaynexie.github.io/CannyEdit/)]<br>

**UniEdit-I: Training-free Image Editing for Unified VLM via Iterative Understanding, Editing and Verifying.**<br>
*Chengyu Bai, Jintao Chen, Xiang Bai, Yilong Chen, Qi She, Ming Lu, Shanghang Zhang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2508.03142)]<br>

**Training-free Geometric Image Editing on Diffusion Models.**<br>
*Hanshen Zhu, Zhen Zhu, Kaile Zhang, Yiming Gong, Yuliang Liu, Xiang Bai.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2507.23300)] [[Code]](https://github.com/CIawevy/FreeFine)<br>

**OmniVTON: Training-Free Universal Virtual Try-On.**<br>
*Zhaotong Yang, Yuhui Li, Shengfeng He, Xinzhe Li, Yangyang Xu, Junyu Dong, Yong Du.*<br>
ICCV 2025. [[PDF](https://arxiv.org/abs/2507.15037)] [[Code]](https://github.com/Jerome-Young/OmniVTON)<br>

**Towards Generalized and Training-Free Text-Guided Semantic Manipulation.**<br>
*Yu Hong, Xiao Cai, Pengpeng Zeng, Shuai Zhang, Jingkuan Song, Lianli Gao, Heng Tao Shen.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.17269)]<br>

**Anchor Token Matching: Implicit Structure Locking for Training-free AR Image Editing.**<br>
*Taihang Hu, Linxuan Li, Kai Wang, Yaxing Wang, Jian Yang, Ming-Ming Cheng.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.10434)] [[Code]](https://github.com/hutaiHang/ATM)<br>

**Tuning-Free Image Editing with Fidelity and Editability via Unified Latent Diffusion Model.**<br>
*Qi Mao, Lan Chen, Yuchao Gu, Mike Zheng Shou, Ming-Hsuan Yang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.05594)] [[Code]](https://github.com/CUC-MIPG/UnifyEdit)<br>

**Training-Free Text-Guided Image Editing with Visual Autoregressive Model.**<br>
*Yufei Wang, Lanqing Guo, Zhihao Li, Jiaxing Huang, Pichao Wang, Bihan Wen, Jian Wang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.23897)] [[Code]](https://github.com/wyf0912/AREdit)<br>

**OmnimatteZero: Training-free Real-time Omnimatte with Pre-trained Video Diffusion Models.**<br>
*Dvir Samuel, Matan Levy, Nir Darshan, Gal Chechik, Rami Ben-Ari.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.18033)]<br>

**FreeFlux: Understanding and Exploiting Layer-Specific Roles in RoPE-Based MMDiT for Versatile Image Editing.**<br>
*Tianyi Wei, Yifan Zhou, Dongdong Chen, Xingang Pan.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.16153)] [[Project](https://wtybest.github.io/projects/FreeFlux/)] [[Code]](https://github.com/wtybest/FreeFlux)<br>

**NullFace: Training-Free Localized Face Anonymization.**<br>
*Han-Wei Kung, Tuomas Varanka, Terence Sim, Nicu Sebe.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.08478)] [[Code](https://github.com/hanweikung/nullface)]<br>

**PTDiffusion: Free Lunch for Generating Optical Illusion Hidden Pictures with Phase-Transferred Diffusion Model.**<br>
*Xiang Gao, Shuai Yang, Jiaying Liu.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2503.06186)]<br>

**KV-Edit: Training-Free Image Editing for Precise Background Preservation.**<br>
*Tianrui Zhu, Shiyi Zhang, Jiawei Shao, Yansong Tang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2409.08397)] [[Project](https://xilluill.github.io/projectpages/KV-Edit/)] [[Code]](https://github.com/Xilluill/KV-Edit)<br>

**360PanT: Training-Free Text-Driven 360-Degree Panorama-to-Panorama Translation.**<br>
*Hai Wang, Jing-Hao Xue.*<br>
WACV 2025. [[PDF](https://arxiv.org/abs/2502.17363)] [[Project](https://littlewhitesea.github.io/360PanT.github.io/)] [[Code]](https://github.com/littlewhitesea/360PanT)<br>

**OmniSSR: Zero-shot Omnidirectional Image Super-Resolution using Stable Diffusion Model.**<br>
*Runyi Li, Xuhan Sheng, Weiqi Li, Jian Zhang.*<br>
ECCV 2024. [[PDF](https://arxiv.org/abs/2404.10312)] [[Project](https://lirunyi2001.github.io/projects/omnissr/)] [[Code]](https://github.com/LiRunyi2001/OmniSSR)<br>

**Guide-and-Rescale: Self-Guidance Mechanism for Effective Tuning-Free Real Image Editing.**<br>
*Vadim Titov, Madina Khalmatova, Alexandra Ivanova, Dmitry Vetrov, Aibek Alanov.*<br>
arxiv 2024. [[PDF](https://arxiv.org/abs/2409.01322)] [[Code]](https://github.com/FusionBrainLab/Guide-and-Rescale)<br>

**TALE: Training-free Cross-domain Image Composition via Adaptive Latent Manipulation and Energy-guided Optimization.**<br>
*Kien T. Pham, Jingye Chen, Qifeng Chen.*<br>
ACM MM 2024. [[PDF](https://arxiv.org/abs/2408.03637)] [[Project](https://tkpham3105.github.io/tale/)] [[Code]](https://github.com/tkpham3105/TALE)<br>

**Faster Diffusion via Temporal Attention Decomposition.**<br>
*Haozhe Liu, Wentian Zhang, Jinheng Xie, Francesco Faccio, Mengmeng Xu, Tao Xiang, Mike Zheng Shou, Juan-Manuel Perez-Rua, Jürgen Schmidhuber.*<br>
arXiv 2024. [[PDF](https://arxiv.org/abs/2404.02747v2)] [[Code](https://github.com/HaozheLiu-ST/T-GATE)]<br>

**DiffUHaul: A Training-Free Method for Object Dragging in Images.**<br>
*Omri Avrahami, Rinon Gal, Gal Chechik, Ohad Fried, Dani Lischinski, Arash Vahdat, Weili Nie.*<br>
Siggraph Asia 2024. [[PDF](https://arxiv.org/pdf/2406.01594)] [[Project](https://omriavrahami.com/diffuhaul/)]<br>

**Analogist: Out-of-the-box Visual In-Context Learning with Image Diffusion Model.**<br>
*Zheng Gu, Shiyuan Yang, Jing Liao, Jing Huo, Yang Gao.*<br>
Siggraph 2024. [[PDF](https://arxiv.org/pdf/2405.10316)] [[Project](https://analogist2d.github.io/)] [[Code]](https://github.com/edward3862/Analogist)<br>

**ObjectAdd: Adding Objects into Image via a Training-Free Diffusion Modification Fashion.**<br>
*Ziyue Zhang, Mingbao Lin, Rongrong Ji.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2404.17230)]<br>

**CutDiffusion: A Simple, Fast, Cheap, and Strong Diffusion Extrapolation Method.**<br>
*Mingbao Lin, Zhihang Lin, Wengyi Zhan, Liujuan Cao, Rongrong Ji.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2404.15141.pdf)] [[Project]](https://github.com/lmbxmu/CutDiffusion)<br>

**FreeDiff: Progressive Frequency Truncation for Image Editing with Diffusion Models.**<br>
*Wei Wu, Qingnan Fan, Shuai Qin, Hong Gu, Ruoyu Zhao, Antoni B. Chan.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2404.11895.pdf)] <br>

**FreeControl: Training-Free Spatial Control of Any Text-to-Image Diffusion Model with Any Condition.**<br>
*Sicheng Mo, Fangzhou Mu, Kuan Heng Lin, Yanli Liu, Bochen Guan, Yin Li, Bolei Zhou.*<br>
CVPR 2024. [[PDF](https://arxiv.org/pdf/2312.07536.pdf)] [[Project](https://genforce.github.io/freecontrol/)] [[Code]](https://github.com/genforce/freecontrol)<br>

**Plug-and-Play Diffusion Features for Text-Driven Image-to-Image Translation.**<br>
*Narek Tumanyan, Michal Geyer, Shai Bagon, Tali Dekel.*<br>
CVPR 2023. [[PDF](https://arxiv.org/pdf/2211.12572.pdf)] [[Project](https://pnp-diffusion.github.io/)] [[Code]](https://github.com/MichalGeyer/plug-and-play)<br>

[🔝 Return to Top](#top)

## Style Transfer

**SceneTextStylizer: A Training-Free Scene Text Style Transfer Framework with Diffusion Model.**<br>
*Honghui Yuan, Keiji Yanai.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.10910)]<br>

**Training-Free Multi-Style Fusion Through Reference-Based Adaptive Modulation.**<br>
*Xu Liu, Yibo Lu, Xinxian Wang, Xinyu Wu.*<br>
ACPR 2025. [[PDF](https://arxiv.org/abs/2509.18602)]<br>

**Training-Free Identity Preservation in Stylized Image Generation Using Diffusion Models.**<br>
*Mohammad Ali Rezaei, Helia Hajikazem, Saeed Khanehgir, Mahdi Javanmardi.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.06802)]<br>

**Training Free Stylized Abstraction.**<br>
*Aimon Rahman, Kartik Narayan, Vishal M. Patel.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.22663)] [[Project](https://kartik-3004.github.io/TF-SA/)] [[Code]](https://github.com/Kartik-3004/TF-SA)<br>

**Training-free Stylized Text-to-Image Generation with Fast Inference.**<br>
*Xin Ma, Yaohui Wang, Xinyuan Chen, Tien-Tsin Wong, Cunjian Chen.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.19063)] [[Project](https://maxin-cn.github.io/omnipainter_project/)] [[Code]](https://github.com/maxin-cn/OmniPainter)<br>

**DriveGEN: Generalized and Robust 3D Detection in Driving via Controllable Text-to-Image Diffusion Generation.**<br>
*Hongbin Lin, Zilu Guo, Yifan Zhang, Shuaicheng Niu, Yafeng Li, Ruimao Zhang, Shuguang Cui, Zhen Li.*<br>
CVPR 2025. [[PDF](https://www.arxiv.org/abs/2503.11122)] [[Code]](https://github.com/Hongbin98/DriveGEN)<br>

**Free-Lunch Color-Texture Disentanglement for Stylized Image Generation.**<br>
*Jiang Qin, Senmao Li, Alexandra Gomez-Villa, Shiqi Yang, Yaxing Wang, Kai Wang, Joost van de Weijer.*<br>
arXiv 2025. [[PDF](https://arxiv.org/abs/2503.14275)]<br>

**AttenST: A Training-Free Attention-Driven Style Transfer Framework with Pre-Trained Diffusion Models.**<br>
*Bo Huang, Wenlun Xu, Qizhuo Han, Haodong Jing, Ying Li.*<br>
arXiv 2025. [[PDF](https://arxiv.org/abs/2503.07307)]<br>

**K-LoRA: Unlocking Training-Free Fusion of Any Subject and Style LoRAs.**<br>
*Ziheng Ouyang, Zhen Li, Qibin Hou.*<br>
arXiv 2025. [[PDF](https://arxiv.org/abs/2502.18461)]<br>

**Artist: Aesthetically Controllable Text-Driven Stylization without Training.**<br>
*Ruixiang Jiang, Changwen Chen.*<br>
arXiv 2024. [[PDF](https://arxiv.org/abs/2407.15842)] [[Project](https://diffusionartist.github.io/)] [[Code]](https://github.com/songrise/artist)<br>

**Visual Style Prompting with Swapping Self-Attention.**<br>
*Jaeseok Jeong, Junho Kim, Yunjey Choi, Gayoung Lee, Youngjung Uh.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2402.12974)] [[Project](https://curryjung.github.io/VisualStylePrompt/)] [[Code]](https://github.com/naver-ai/Visual-Style-Prompting)<br>

**FreeStyle: Free Lunch for Text-guided Style Transfer using Diffusion Models.**<br>
*Feihong He, Gang Li, Mengyuan Zhang, Leilei Yan, Lingyu Si, Fanzhang Li.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2401.15636)] [[Project](https://freestylefreelunch.github.io/)] [[Code]](https://github.com/FreeStyleFreeLunch/FreeStyle)<br>

**Eye-for-an-eye: Appearance Transfer with Semantic Correspondence in Diffusion Models.**<br>
*Sooyeon Go, Kyungmook Choi, Minjung Shin, Youngjung Uh.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2406.07008)] [[Project](https://sooyeon-go.github.io/eye_for_an_eye/)] [[Code]](https://github.com/sooyeon-go/eye_for_an_eye)<br>

**Ctrl-X: Controlling Structure and Appearance for Text-To-Image Generation Without Guidance.**<br>
*Kuan Heng Lin, Sicheng Mo, Ben Klingher, Fangzhou Mu, Bolei Zhou.*<br>
NeurIPS 2024. [[PDF](https://arxiv.org/pdf/2406.07540)] [[Project](https://genforce.github.io/ctrl-x/)] [[Code]](https://github.com/genforce/ctrl-x)<br>

**RB-Modulation: Training-Free Personalization of Diffusion Models using Stochastic Optimal Control.**<br>
*Litu Rout, Yujia Chen, Nataniel Ruiz, Abhishek Kumar, Constantine Caramanis, Sanjay Shakkottai, Wen-Sheng Chu.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2405.17401)] [[Project](https://rb-modulation.github.io/)] [[Code]](https://github.com/LituRout/RB-Modulation)<br>

**Tuning-Free Adaptive Style Incorporation for Structure-Consistent Text-Driven Style Transfer.**<br>
*Yanqi Ge, Jiaqi Liu, Qingnan Fan, Xi Jiang, Ye Huang, Shuai Qin, Hong Gu, Wen Li, Lixin Duan.*<br>
arXiv 2024. [[PDF](https://arxiv.org/pdf/2404.06835.pdf)]<br>

**Cross-Image Attention for Zero-Shot Appearance Transfer.**<br>
*Yuval Alaluf, Daniel Garibi, Or Patashnik, Hadar Averbuch-Elor, Daniel Cohen-Or.*<br>
SIGGRAPH 2024. [[PDF](https://arxiv.org/abs/2311.03335)] [[Project](https://garibida.github.io/cross-image-attention/)] [[Code]](https://github.com/garibida/cross-image-attention)<br>

**Style Injection in Diffusion: A Training-free Approach for Adapting Large-scale Diffusion Models for Style Transfer.**<br>
*Jiwoo Chung, Sangeek Hyun, Jae-Pil Heo.*<br>
CVPR 2024. [[PDF](https://arxiv.org/pdf/2312.09008.pdf)] [[Project](https://jiwoogit.github.io/StyleID_site/)] [[Code]](https://github.com/jiwoogit/StyleID)<br>

[🔝 Return to Top](#top)

## Material Transfer

**ZeST: Zero-Shot Material Transfer from a Single Image.**<br>
*Ta-Ying Cheng, Prafull Sharma, Andrew Markham, Niki Trigoni, Varun Jampani.*<br>
ECCV 2024. [[PDF](https://arxiv.org/pdf/2404.06425)] [[Project](https://ttchengab.github.io/zest/)] [[Code]](https://github.com/ttchengab/zest_code)<br>

[🔝 Return to Top](#top)

## Video Generation

**Block Cascading: Training Free Acceleration of Block-Causal Video Models.**<br>
*Hmrishav Bandyopadhyay, Nikhil Pinnaparaju, Rahim Entezari, Jim Scott, Yi-Zhe Song, Varun Jampani.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2511.20426)] [[Project](https://hmrishavbandy.github.io/block_cascading_page/index.html)]<br>

**FreeSwim: Revisiting Sliding-Window Attention Mechanisms for Training-Free Ultra-High-Resolution Video Generation.**<br>
*Yunfeng Wu, Jiayi Song, Zhenxiong Tan, Zihao He, Songhua Liu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2511.14712)] [[Code](https://github.com/WillWu111/FreeSwim)]<br>

**BachVid: Training-Free Video Generation with Consistent Background and Character.**<br>
*Han Yan, Xibin Song, Yifu Wang, Hongdong Li, Pan Ji, Chao Ma.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.21696)] [[Project](https://wolfball.github.io/bachvid/)] [[Code](https://github.com/wolfball/BachVid)]<br>

**Playmate2: Training-Free Multi-Character Audio-Driven Animation via Diffusion Transformer with Reward Feedback.**<br>
*Xingpei Ma, Shenneng Huang, Jiaran Cai, Yuansheng Guan, Shen Zheng, Hanfeng Zhao, Qiang Zhang, Shunsi Zhang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.12089)] [[Project](https://playmate111.github.io/Playmate2/)] [[Code](https://github.com/Playmate111/Playmate2)]<br>

**LightCache: Memory-Efficient, Training-Free Acceleration for Video Generation.**<br>
*Yang Xiao, Gen Li, Kaiyuan Deng, Yushu Wu, Zheng Zhan, Yanzhi Wang, Xiaolong Ma, Bo Hui.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.05367)] [[Code](https://github.com/NKUShaw/LightCache)]<br>

**DiTraj: training-free trajectory control for video diffusion transformer.**<br>
*Cheng Lei, Jiayu Zhang, Yue Ma, Xinyu Wang, Long Chen, Liang Tang, Yiqiang Yan, Fei Su, Zhicheng Zhao.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2509.21839)] <br>

**Identity-Preserving Text-to-Video Generation via Training-Free Prompt, Image, and Guidance Enhancement.**<br>
*Jiayi Gao, Changcheng Hua, Qingchao Chen, Yuxin Peng, Yang Liu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2509.01362)] [[Code](https://github.com/Andyplus1/IPT2V)]<br>

**Less is Enough: Training-Free Video Diffusion Acceleration via Runtime-Adaptive Caching.**<br>
*Xin Zhou, Dingkang Liang, Kaijin Chen, Tianrui Feng, Xiwu Chen, Hongkai Lin, Yikang Ding, Feiyang Tan, Hengshuang Zhao, Xiang Bai.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2507.02860)] [[Project](https://h-embodvis.github.io/EasyCache/)] [[Code](https://github.com/H-EmbodVis/EasyCache)]<br>

**FreeLong++: Training-Free Long Video Generation via Multi-band SpectralFusion.**<br>
*Yu Lu, Yi Yang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2507.00162)] [[Project](https://freelongvideo.github.io/)] [[Code](https://github.com/aniki-ly/FreeLong)]<br>

**Training-Free Motion Customization for Distilled Video Generators with Adaptive Test-Time Distillation.**<br>
*Jintao Rong, Xin Xie, Xinyi Yu, Linlin Ou, Xinyu Zhang, Chunhua Shen, Dong Gong.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.19348)] [[Project](https://euminds.github.io/motionecho/)]<br>

**Frame Guidance: Training-Free Guidance for Frame-Level Control in Video Diffusion Models.**<br>
*Sangwon Jang, Taekyung Ki, Jaehyeong Jo, Jaehong Yoon, Soo Ye Kim, Zhe Lin, Sung Ju Hwang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.07177)] [[Project](https://frame-guidance-video.github.io/)] [[Code](https://github.com/agwmon/frame-guidance)]<br>

**DiffuseSlide: Training-Free High Frame Rate Video Generation Diffusion.**<br>
*Geunmin Hwang, Hyun-kyu Ko, Younghyun Kim, Seungryong Lee, Eunbyung Park.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.01454)] [[Project](https://geunminhwang.github.io/DiffuseSlide/)] [[Code](https://github.com/GeunminHwang/DiffuseSlide)]<br>

**MOVi: Training-free Text-conditioned Multi-Object Video Generation.**<br>
*Aimon Rahman, Jiang Liu, Ze Wang, Ximeng Sun, Jialian Wu, Xiaodong Yu, Yusheng Su, Vishal M. Patel, Zicheng Liu, Emad Barsoum.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.22980)] [[Code](https://github.com/aimansnigdha/MOVi)]<br>

**Training-Free Efficient Video Generation via Dynamic Token Carving.**<br>
*Yuechen Zhang, Jinbo Xing, Bin Xia, Shaoteng Liu, Bohao Peng, Xin Tao, Pengfei Wan, Eric Lo, Jiaya Jia.*<br>
arxiv 2025. [[PDF](http://arxiv.org/abs/2505.16864)] [[Project](https://julianjuaner.github.io/projects/jenga/)]  [[Code](https://github.com/dvlab-research/Jenga/)]<br>

**DynamicScaler: Seamless and Scalable Video Generation for Panoramic Scenes.**<br>
*Jinxiu Liu, Shaoheng Lin, Yinxiao Li, Ming-Hsuan Yang.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2412.11100)] [[Project](https://dynamic-scaler.pages.dev/)]  [[Code](https://github.com/sh-Lin/DynamicScaler)]<br>

**FreePCA: Integrating Consistency Information across Long-short Frames in Training-free Long Video Generation via Principal Component Analysis.**<br>
*Jiangtong Tan, Hu Yu, Jie Huang, Jie Xiao, Feng Zhao.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2505.01172)] [[Code](https://github.com/JosephTiTan/FreePCA)]<br>

**Training-free Guidance in Text-to-Video Generation via Multimodal Planning and Structured Noise Initialization.**<br>
*Jialu Li, Shoubin Yu, Han Lin, Jaemin Cho, Jaehong Yoon, Mohit Bansal.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2504.08641)] [[Project](https://video-msg.github.io/)]  [[Code](https://github.com/jialuli-luka/Video-MSG)]<br>

**EIDT-V: Exploiting Intersections in Diffusion Trajectories for Model-Agnostic, Zero-Shot, Training-Free Text-to-Video Generation.**<br>
*Diljeet Jagpal, Xi Chen, Vinay P. Namboodiri.*<br>
CVPR 2025. [[PDF](https://arxiv.org/abs/2504.06861)] [[Project](https://djagpal02.github.io/EIDT-V/)]  [[Code](https://github.com/djagpal02/EIDT-V)]<br>

**Every Painting Awakened: A Training-free Framework for Painting-to-Animation Generation.**<br>
*Lingyu Liu, Yaxiong Wang, Li Zhu, Zhedong Zheng.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.23736)] [[Project](https://painting-animation.github.io/animation/)]<br>

**On-device Sora: Enabling Training-Free Diffusion-based Text-to-Video Generation for Mobile Devices.**<br>
*Bosung Kim, Kyuhwan Lee, Isu Jeong, Jungmin Cheon, Yeojin Lee, Seulki Lee.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.23796)] [[Code](https://github.com/eai-lab/On-device-Sora)]<br>

**Zero4D: Training-Free 4D Video Generation From Single Video Using Off-the-Shelf Video Diffusion Model.**<br>
*Jangho Park, Taesung Kwon, Jong Chul Ye.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.22622)] [[Project](https://zero4dvid.github.io/)]<br>

**MagicComp: Training-free Dual-Phase Refinement for Compositional Video Generation.**<br>
*Hongyu Zhang, Yufan Deng, Shenghai Yuan, Peng Jin, Zesen Cheng, Yian Zhao, Chang Liu, Jie Chen.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.14428)] [[Project](https://hong-yu-zhang.github.io/MagicComp-Page/)] [[Code]](https://github.com/Hong-yu-Zhang/MagicComp)<br>

**MotionMaster: Training-free Camera Motion Transfer For Video Generation.**<br>
*Teng Hu, Jiangning Zhang, Ran Yi, Yating Wang, Hongrui Huang, Jieyu Weng, Yabiao Wang, Lizhuang Ma.*<br>
ACM MM 2024. [[PDF](https://arxiv.org/abs/2404.15789)] [[Code]](https://github.com/sjtuplayer/MotionMaster)<br>

[🔝 Return to Top](#top)

## Video Manipulation

**FAME: Fairness-aware Attention-modulated Video Editing.**<br>
*Zhangkai Wu, Xuhui Fan, Zhongyuan Xie, Kaize Shi, Zhidong Li, Longbing Cao.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.22960)]<br>

**VALA: Learning Latent Anchors for Training-Free and Temporally Consistent Video Editing.**<br>
*Zhangkai Wu, Xuhui Fan, Zhongyuan Xie, Kaize Shi, Longbing Cao.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.22970)]<br>

**ConsistEdit: Highly Consistent and Precise Training-free Visual Editing.**<br>
*Zixin Yin, Ling-Hao Chen, Lionel Ni, Xili Dai.*<br>
SIGGRAPH Asia 2025. [[PDF](https://arxiv.org/abs/2510.17803)] [[Project](https://zxyin.github.io/ConsistEdit/)] [[Code]](https://github.com/zxYin/ConsistEdit_Code)<br>

**FreeViS: Training-free Video Stylization with Inconsistent References.**<br>
*Jiacong Xu, Yiqun Mei, Ke Zhang, Vishal M. Patel.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.01686)] [[Project](https://xujiacong.github.io/FreeViS/)] [[Code]](https://xujiacong.github.io/FreeViS/)<br>

**ContextFlow: Training-Free Video Object Editing via Adaptive Context Enrichment.**<br>
*Yiyang Chen, Xuanhua He, Xiujun Ma, Yue Ma.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2509.17818)] [[Project](https://yychen233.github.io/ContextFlow-page/)] [[Code]](https://github.com/yyChen233/ContextFlow)<br>

**STR-Match: Matching SpatioTemporal Relevance Score for Training-Free Video Editing.**<br>
*Junsung Lee, Junoh Kang, Bohyung Han.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.22868)] [[Project](https://jslee525.github.io/str-match/)] [[Code]](https://github.com/jslee525/STR-Match_official)<br>

**Good Noise Makes Good Edits: A Training-Free Diffusion-Based Video Editing with Image and Text Prompts.**<br>
*Saemee Choi, Sohyun Jeong, Jaegul Choo, Jinhee Kim.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.12520)]<br>

**TV-LiVE: Training-Free, Text-Guided Video Editing via Layer Informed Vitality Exploitation.**<br>
*Min-Jung Kim, Dongjin Kim, Seokju Yun, Jaegul Choo.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.07205)] [[Project](https://emjay73.github.io/TV_LiVE/)]<br>

**FlowDirector: Training-Free Flow Steering for Precise Text-to-Video Editing.**<br>
*Guangzhao Li, Yanming Yang, Chenxi Song, Chi Zhang.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2506.05046)] [[Project](https://flowdirector-edit.github.io/)] [[Code]](https://github.com/guangzhaoli/FlowDirector)<br>

**RoPECraft: Training-Free Motion Transfer with Trajectory-Guided RoPE Optimization on Diffusion Transformers.**<br>
*Ahmet Berke Gokmen, Yigit Ekin, Bahri Batuhan Bilecen, Aysegul Dundar.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2505.13344)] [[Project](https://berkegokmen1.github.io/RoPECraft/)] [[Code]](https://github.com/berkegokmen1/RoPECraft)<br>

**RASA: Replace Anyone, Say Anything -- A Training-Free Framework for Audio-Driven and Universal Portrait Video Editing.**<br>
*Tianrui Pan, Lin Liu, Jie Liu, Xiaopeng Zhang, Jie Tang, Gangshan Wu, Qi Tian.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2503.11571)] [[Project](https://alice01010101.github.io/RASA/)]<br>

**Light-A-Video: Training-free Video Relighting via Progressive Light Fusion.**<br>
*Yujie Zhou, Jiazi Bu, Pengyang Ling, Pan Zhang, Tong Wu, Qidong Huang, Jinsong Li, Xiaoyi Dong, Yuhang Zang, Yuhang Cao, Anyi Rao, Jiaqi Wang, Li Niu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2502.08590)] [[Project](https://bujiazi.github.io/light-a-video.github.io/)] [[Code]](https://github.com/bcmi/Light-A-Video/)<br>

**Slicedit: Zero-Shot Video Editing With Text-to-Image Diffusion Models Using Spatio-Temporal Slices.**<br>
*Nathaniel Cohen, Vladimir Kulikov, Matan Kleiner, Inbar Huberman-Spiegelglas, Tomer Michaeli.*<br>
ICML 2024. [[PDF](https://arxiv.org/pdf/2405.12211)] [[Project](https://matankleiner.github.io/slicedit/)] [[Code]](https://github.com/fallenshock/Slicedit)<br>

**FLATTEN: optical FLow-guided ATTENtion for consistent text-to-video editing.**<br>
*Yuren Cong, Mengmeng Xu, Christian Simon, Shoufa Chen, Jiawei Ren, Yanping Xie, Juan-Manuel Perez-Rua, Bodo Rosenhahn, Tao Xiang, Sen He.*<br>
ICLR 2024. [[PDF](https://arxiv.org/pdf/2310.05922.pdf)] [[Project](https://flatten-video-editing.github.io/)] [[Code]](https://github.com/yrcong/flatten)<br>

**TokenFlow: Consistent Diffusion Features for Consistent Video Editing.**<br>
*Michal Geyer, Omer Bar-Tal, Shai Bagon, Tali Dekel.*<br>
ICLR 2024. [[PDF](https://arxiv.org/pdf/2307.10373.pdf)] [[Project](https://diffusion-tokenflow.github.io/)] [[Code]](https://github.com/omerbt/TokenFlow)<br>

[🔝 Return to Top](#top)

## 3D Generation

**FreeArt3D: Training-Free Articulated Object Generation using 3D Diffusion.**<br>
*Chuhao Chen, Isabella Liu, Xinyue Wei, Hao Su, Minghua Liu.*<br>
SIGGRAPH Asia 2025. [[PDF](https://arxiv.org/abs/2510.25765)] [[Project](https://czzzzh.github.io/FreeArt3D/)] [[Code]](https://github.com/CzzzzH/FreeArt3D)<br>

**TRELLISWorld: Training-Free World Generation from Object Generators.**<br>
*Hanke Chen, Yuan Liu, Minchen Li.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.23880)]<br>

[🔝 Return to Top](#top)

## 3D Manipulation

**NANO3D: A Training-Free Approach for Efficient 3D Editing Without Masks.**<br>
*Junliang Ye, Shenghao Xie, Ruowen Zhao, Zhengyi Wang, Hongyu Yan, Wenqiang Zu, Lei Ma, Jun Zhu.*<br>
arxiv 2025. [[PDF](https://arxiv.org/abs/2510.15019)] [[Project](https://jamesyjl.github.io/Nano3D/)] [[Code]](https://github.com/JAMESYJL/Nano3D)<br>

[🔝 Return to Top](#top)
