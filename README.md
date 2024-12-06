[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

# Video-Restoration Research Papers (With GPT Analysis)
### Automatically Updated on 2024.12.06
Current Search Keywords: `Video Restoration`, `Video Enhancement`, `Video Face Super Resolution`, `Video Super Resolution`, `Face Restoration`, `Video Deblurring`, `Video Denoising`, `Video Deflickering`

> If you have any other keywords, please feel free to let us know :) 

> We now offer support for article analysis through large language models. You can view this feature by clicking the `Paper Analysis` link below. Currently, we are experimenting with `Claude.ai` or `Moonshot AI`. This is to help everyone **quickly skim** through the latest research papers. 

 

<details>
  <summary>Recent Trends (by AI)</summary>
  <ol>
    <li>Based on the provided snippets, I have identified the top five prominent keywords and synthesized the key themes, methodologies, findings, and shifts in perspective from the papers:

<b>1. One-shot Talking Face Generation</b>: 
The concept of generating realistic talking faces from a single image is a recurring theme across multiple papers. Techniques like NeRFFaceSpeech and AniTalker emphasize creating lifelike animations using minimal input data. These methods leverage generative models and audio-driven dynamics to produce natural-looking facial movements. The key challenge addressed is achieving high-quality synthesis while preserving identity and visual details.

<b>2. Lip Synchronization and Audio-Visual Correlation</b>: 
Ensuring accurate lip synchronization with corresponding audio is critical in talking face generation. Papers like "Audio-Visual Speech Representation Expert" and SwapTalk focus on synchronizing lip movements with audio while maintaining the visual quality of the generated faces. The methodologies involve advanced neural networks and latent space manipulation to enhance synchronization and minimize artifacts.

<b>3. Real-time Rendering and Efficiency</b>: 
The need for fast and efficient rendering is highlighted in works such as GSTalker. This model utilizes deformable Gaussian splatting to enable real-time audio-driven face generation. The emphasis is on reducing training time and improving rendering speeds without compromising the quality of the generated faces. This shift towards real-time applications reflects the growing demand for practical and scalable solutions in various domains.

<b>4. Multimodal Emotion Representation</b>: 
EMOPortraits introduces the integration of emotional expressions into talking face avatars. This approach enhances the realism and expressiveness of generated faces by incorporating emotion-driven dynamics. The methodology involves multimodal inputs and cross-driving synthesis, where avatars are animated with different emotional states, addressing the challenge of creating more engaging and lifelike digital avatars.

<b>5. Identity Preservation and Customization</b>: 
Maintaining the unique identity of the subject while generating talking faces is a crucial aspect explored in SwapTalk and AniTalker. These papers propose innovative solutions for identity-decoupled motion encoding and one-shot customization. The goal is to create personalized talking faces that retain the distinct features of the original subject, enabling applications in personalized media and communication.

Overall, the interconnectedness among these papers highlights a trend towards achieving higher realism, efficiency, and customization in talking face generation. The field is moving towards developing more practical and scalable solutions that can be applied in real-time scenarios, with an increasing focus on emotional expressiveness and identity preservation. Researchers are exploring advanced neural network architectures, generative models, and multimodal approaches to push the boundaries of what's possible in this rapidly evolving domain.</li>
  </ol>
</details>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href=#video-restoration>Video Restoration</a></li>
  </ol>
</details>

## Video Restoration

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-12-02**|**Adaptive High-Pass Kernel Prediction for Efficient Video Deblurring**|Bo Ji et.al.|[2412.01559](http://arxiv.org/abs/2412.01559)|**[link](https://github.com/jibo27/ahfnet)**|
|**2024-12-01**|**DIVD: Deblurring with Improved Video Diffusion Model**|Haoyang Long et.al.|[2412.00773](http://arxiv.org/abs/2412.00773)|null|
|**2024-11-27**|**DiffMVR: Diffusion-based Automated Multi-Guidance Video Restoration**|Zheyan Zhang et.al.|[2411.18745](http://arxiv.org/abs/2411.18745)|null|
|**2024-11-26**|**OSDFace: One-Step Diffusion Model for Face Restoration**|Jingkai Wang et.al.|[2411.17163](http://arxiv.org/abs/2411.17163)|**[link](https://github.com/jkwang28/osdface)**|
|**2024-11-25**|**Efficient Video Face Enhancement with Enhanced Spatial-Temporal Consistency**|Yutong Wang et.al.|[2411.16468](http://arxiv.org/abs/2411.16468)|**[link](https://github.com/dixin-lab/bfvr-stc)**|
|**2024-11-24**|**Towards Unsupervised Blind Face Restoration using Diffusion Prior**|Tianshu Kuai et.al.|[2410.04618](http://arxiv.org/abs/2410.04618)|null|
|**2024-11-23**|**Efficient Diffusion Model for Image Restoration by Residual Shifting**|Zongsheng Yue et.al.|[2403.07319](http://arxiv.org/abs/2403.07319)|**[link](https://github.com/zsyoaoa/resshift)**|
|**2024-11-21**|**RestorerID: Towards Tuning-Free Face Restoration with ID Preservation**|Jiacheng Ying et.al.|[2411.14125](http://arxiv.org/abs/2411.14125)|**[link](https://github.com/yingjiacheng/restorerid)**|
|**2024-11-20**|**RTSR: A Real-Time Super-Resolution Model for AV1 Compressed Content**|Yuxuan Jiang et.al.|[2411.13362](http://arxiv.org/abs/2411.13362)|null|
|**2024-11-15**|**DR-BFR: Degradation Representation with Diffusion Models for Blind Face Restoration**|Xinmin Qiu et.al.|[2411.10508](http://arxiv.org/abs/2411.10508)|null|
|**2024-11-15**|**Quanta Video Restoration**|Prateek Chennuri et.al.|[2410.14994](http://arxiv.org/abs/2410.14994)|**[link](https://github.com/chennuriprateek/Quanta_Video_Restoration-QUIVER-)**|
|**2024-11-11**|**360-Degree Video Super Resolution and Quality Enhancement Challenge: Methods and Results**|Ahmed Telili et.al.|[2411.06738](http://arxiv.org/abs/2411.06738)|null|
|**2024-11-08**|**UnDIVE: Generalized Underwater Video Enhancement Using Generative Priors**|Suhas Srinath et.al.|[2411.05886](http://arxiv.org/abs/2411.05886)|**[link](https://github.com/suhas-srinath/undive)**|
|**2024-10-26**|**SeeClear: Semantic Distillation Enhances Pixel Condensation for Video Super-Resolution**|Qi Tang et.al.|[2410.05799](http://arxiv.org/abs/2410.05799)|**[link](https://github.com/tang1705/seeclear-neurips24)**|
|**2024-10-22**|**Warped Diffusion: Solving Video Inverse Problems with Image Diffusion Models**|Giannis Daras et.al.|[2410.16152](http://arxiv.org/abs/2410.16152)|null|
|**2024-10-20**|**Quality Prediction of AI Generated Images and Videos: Emerging Trends and Opportunities**|Abhijay Ghildyal et.al.|[2410.08534](http://arxiv.org/abs/2410.08534)|null|
|**2024-10-15**|**Analysis and Benchmarking of Extending Blind Face Image Restoration to Videos**|Zhouxia Wang et.al.|[2410.11828](http://arxiv.org/abs/2410.11828)|null|
|**2024-10-15**|**Spatio-Temporal Distortion Aware Omnidirectional Video Super-Resolution**|Hongyu An et.al.|[2410.11506](http://arxiv.org/abs/2410.11506)|**[link](https://github.com/nichenxingmeng/STDAN)**|
|**2024-10-15**|**Learning Truncated Causal History Model for Video Restoration**|Amirhosein Ghasemabadi et.al.|[2410.03936](http://arxiv.org/abs/2410.03936)|**[link](https://github.com/Ascend-Research/Turtle)**|
|**2024-10-13**|**AuthFace: Towards Authentic Blind Face Restoration with Face-oriented Generative Diffusion Prior**|Guoqiang Liang et.al.|[2410.09864](http://arxiv.org/abs/2410.09864)|**[link](https://github.com/ethanliang99/authface)**|
|**2024-10-10**|**RMT-BVQA: Recurrent Memory Transformer-based Blind Video Quality Assessment for Enhanced Video Content**|Tianhao Peng et.al.|[2405.08621](http://arxiv.org/abs/2405.08621)|null|
|**2024-10-05**|**AIM 2024 Challenge on Video Super-Resolution Quality Assessment: Methods and Results**|Ivan Molodetskikh et.al.|[2410.04225](http://arxiv.org/abs/2410.04225)|null|
|**2024-10-05**|**Overcoming False Illusions in Real-World Face Restoration with Multi-Modal Guided Diffusion Model**|Keda Tao et.al.|[2410.04161](http://arxiv.org/abs/2410.04161)|null|
|**2024-10-04**|**DiffIR2VR-Zero: Zero-Shot Video Restoration with Diffusion-based Image Restoration Models**|Chang-Han Yeh et.al.|[2407.01519](http://arxiv.org/abs/2407.01519)|**[link](https://github.com/jimmycv07/DiffIR2VR-Zero)**|
|**2024-10-03**|**Qwen2-VL: Enhancing Vision-Language Model's Perception of the World at Any Resolution**|Peng Wang et.al.|[2409.12191](http://arxiv.org/abs/2409.12191)|**[link](https://github.com/qwenlm/qwen2-vl)**|
|**2024-09-30**|**DeTurb: Atmospheric Turbulence Mitigation with Deformable 3D Convolutions and 3D Swin Transformers**|Zhicheng Zou et.al.|[2407.20855](http://arxiv.org/abs/2407.20855)|null|
|**2024-09-25**|**AIM 2024 Challenge on Efficient Video Super-Resolution for AV1 Compressed Content**|Marcos V Conde et.al.|[2409.17256](http://arxiv.org/abs/2409.17256)|null|
|**2024-09-13**|**Optimizing 4D Lookup Table for Low-light Video Enhancement via Wavelet Priori**|Jinhong He et.al.|[2409.08585](http://arxiv.org/abs/2409.08585)|null|
|**2024-09-12**|**3D Priors-Guided Diffusion for Blind Face Restoration**|Xiaobin Lu et.al.|[2409.00991](http://arxiv.org/abs/2409.00991)|**[link](https://github.com/838143396/3Diffusion)**|
|**2024-09-12**|**From Sim-to-Real: Toward General Event-based Low-light Frame Interpolation with Per-scene Optimization**|Ziran Zhang et.al.|[2406.08090](http://arxiv.org/abs/2406.08090)|null|
|**2024-09-02**|**DAVIDE: Depth-Aware Video Deblurring**|German F. Torres et.al.|[2409.01274](http://arxiv.org/abs/2409.01274)|null|
|**2024-09-01**|**VDPI: Video Deblurring with Pseudo-inverse Modeling**|Zhihao Huang et.al.|[2409.00777](http://arxiv.org/abs/2409.00777)|null|
|**2024-08-29**|**EvLight++: Low-Light Video Enhancement with an Event Camera: A Large-Scale Real-World Dataset, Novel Method, and More**|Kanghao Chen et.al.|[2408.16254](http://arxiv.org/abs/2408.16254)|null|
|**2024-08-28**|**CMTA: Cross-Modal Temporal Alignment for Event-guided Video Deblurring**|Taewoo Kim et.al.|[2408.14930](http://arxiv.org/abs/2408.14930)|**[link](https://github.com/intelpro/cmta)**|
|**2024-08-27**|**Towards Real-world Event-guided Low-light Video Enhancement and Deblurring**|Taewoo Kim et.al.|[2408.14916](http://arxiv.org/abs/2408.14916)|**[link](https://github.com/intelpro/elednet)**|
|**2024-08-26**|**Cascaded Temporal Updating Network for Efficient Video Super-Resolution**|Hao Li et.al.|[2408.14244](http://arxiv.org/abs/2408.14244)|null|
|**2024-08-24**|**Frontal Slice Approaches for Tensor Linear Systems**|Hengrui Luo et.al.|[2408.13547](http://arxiv.org/abs/2408.13547)|null|
|**2024-08-24**|**Rethinking Video Deblurring with Wavelet-Aware Dynamic Transformer and Diffusion Model**|Chen Rao et.al.|[2408.13459](http://arxiv.org/abs/2408.13459)|**[link](https://github.com/chen-rao/vd-diff)**|
|**2024-08-22**|**Adapting MIMO video restoration networks to low latency constraints**|Valéry Dewil et.al.|[2408.12439](http://arxiv.org/abs/2408.12439)|null|
|**2024-08-22**|**Unrolled Decomposed Unpaired Learning for Controllable Low-Light Video Enhancement**|Lingyu Zhu et.al.|[2408.12316](http://arxiv.org/abs/2408.12316)|**[link](https://github.com/lingyzhu0101/udu)**|
|**2024-08-20**|**MagicID: Flexible ID Fidelity Generation System**|Zhaoli Deng et.al.|[2408.09248](http://arxiv.org/abs/2408.09248)|null|
|**2024-08-20**|**Compression-Realized Deep Structural Network for Video Quality Enhancement**|Hanchi Sun et.al.|[2405.06342](http://arxiv.org/abs/2405.06342)|null|
|**2024-08-14**|**GQE: Generalized Query Expansion for Enhanced Text-Video Retrieval**|Zechen Bai et.al.|[2408.07249](http://arxiv.org/abs/2408.07249)|null|
|**2024-08-09**|**Kalman-Inspired Feature Propagation for Video Face Super-Resolution**|Ruicheng Feng et.al.|[2408.05205](http://arxiv.org/abs/2408.05205)|null|
|**2024-08-08**|**Physical prior guided cooperative learning framework for joint turbulence degradation estimation and infrared video restoration**|Ziran Zhang et.al.|[2408.04227](http://arxiv.org/abs/2408.04227)|null|
|**2024-07-29**|**FreeLong: Training-Free Long Video Generation with SpectralBlend Temporal Attention**|Yu Lu et.al.|[2407.19918](http://arxiv.org/abs/2407.19918)|null|
|**2024-07-28**|**BVI-RLV: A Fully Registered Dataset and Benchmarks for Low-Light Video Enhancement**|Ruirui Lin et.al.|[2407.03535](http://arxiv.org/abs/2407.03535)|null|
|**2024-07-26**|**PIV3CAMS: a multi-camera dataset for multiple computer vision problems and its application to novel view-point synthesis**|Sohyeong Kim et.al.|[2407.18695](http://arxiv.org/abs/2407.18695)|null|
|**2024-07-24**|**Cuboid-Net: A Multi-Branch Convolutional Neural Network for Joint Space-Time Video Super Resolution**|Congrui Fu et.al.|[2407.16986](http://arxiv.org/abs/2407.16986)|null|
|**2024-07-24**|**3DAttGAN: A 3D Attention-based Generative Adversarial Network for Joint Space-Time Video Super-Resolution**|Congrui Fu et.al.|[2407.16965](http://arxiv.org/abs/2407.16965)|**[link](https://github.com/fcongrui/3dattgan)**|
|**2024-07-19**|**RealViformer: Investigating Attention for Real-World Video Super-Resolution**|Yuehan Zhang et.al.|[2407.13987](http://arxiv.org/abs/2407.13987)|**[link](https://github.com/yuehan717/realviformer)**|
|**2024-07-17**|**Sphere Window: Challenges and Opportunities of 360° Video in Collaborative Design Workshops**|Wo Meijer et.al.|[2407.12407](http://arxiv.org/abs/2407.12407)|null|
|**2024-07-16**|**Enhancing Perceptual Quality in Video Super-Resolution through Temporally-Consistent Detail Synthesis using Diffusion Models**|Claudio Rota et.al.|[2311.15908](http://arxiv.org/abs/2311.15908)|**[link](https://github.com/claudiom4sir/stablevsr)**|
|**2024-07-14**|**Noise Calibration: Plug-and-play Content-Preserving Video Enhancement using Pre-trained Video Diffusion Models**|Qinyu Yang et.al.|[2407.10285](http://arxiv.org/abs/2407.10285)|**[link](https://github.com/yangqy1110/nc-sdedit)**|
|**2024-07-13**|**Arbitrary-Scale Video Super-Resolution with Structural and Textural Priors**|Wei Shang et.al.|[2407.09919](http://arxiv.org/abs/2407.09919)|**[link](https://github.com/shangwei5/st-avsr)**|
|**2024-07-12**|**Domain-adaptive Video Deblurring via Test-time Blurring**|Jin-Ting He et.al.|[2407.09059](http://arxiv.org/abs/2407.09059)|**[link](https://github.com/jin-ting-he/dadeblur)**|
|**2024-07-12**|**A Spatio-temporal Aligned SUNet Model for Low-light Video Enhancement**|Ruirui Lin et.al.|[2403.02408](http://arxiv.org/abs/2403.02408)|null|
|**2024-07-12**|**Motion-Guided Latent Diffusion for Temporally Consistent Real-world Video Super-resolution**|Xi Yang et.al.|[2312.00853](http://arxiv.org/abs/2312.00853)|**[link](https://github.com/ianyeung/mgld-vsr)**|
|**2024-07-11**|**Global Spatial-Temporal Information-based Residual ConvLSTM for Video Space-Time Super-Resolution**|Congrui Fu et.al.|[2407.08466](http://arxiv.org/abs/2407.08466)|null|
|**2024-07-10**|**VEnhancer: Generative Space-Time Enhancement for Video Generation**|Jingwen He et.al.|[2407.07667](http://arxiv.org/abs/2407.07667)|null|
|**2024-07-10**|**MNeRV: A Multilayer Neural Representation for Videos**|Qingling Chang et.al.|[2407.07347](http://arxiv.org/abs/2407.07347)|**[link](https://github.com/aaronbtb/mnerv)**|
|**2024-07-10**|**DaBiT: Depth and Blur informed Transformer for Joint Refocusing and Super-Resolution**|Crispian Morris et.al.|[2407.01230](http://arxiv.org/abs/2407.01230)|null|
|**2024-07-02**|**Zero-shot Video Restoration and Enhancement Using Pre-Trained Image Diffusion Model**|Cong Cao et.al.|[2407.01960](http://arxiv.org/abs/2407.01960)|null|
|**2024-06-24**|**Improving Generative Adversarial Networks for Video Super-Resolution**|Daniel Wen et.al.|[2406.16359](http://arxiv.org/abs/2406.16359)|null|
|**2024-06-21**|**LU2Net: A Lightweight Network for Real-time Underwater Image Enhancement**|Haodong Yang et.al.|[2406.14973](http://arxiv.org/abs/2406.14973)|null|
|**2024-06-19**|**EvTexture: Event-driven Texture Enhancement for Video Super-Resolution**|Dachun Kai et.al.|[2406.13457](http://arxiv.org/abs/2406.13457)|**[link](https://github.com/dachunkai/evtexture)**|
|**2024-06-15**|**Fast Unsupervised Tensor Restoration via Low-rank Deconvolution**|David Reixach et.al.|[2406.10679](http://arxiv.org/abs/2406.10679)|null|
|**2024-06-11**|**Blur-aware Spatio-temporal Sparse Transformer for Video Deblurring**|Huicong Zhang et.al.|[2406.07551](http://arxiv.org/abs/2406.07551)|**[link](https://github.com/huicongzhang/bsstnet)**|
|**2024-06-11**|**Missingness-resilient Video-enhanced Multimodal Disfluency Detection**|Payal Mohapatra et.al.|[2406.06964](http://arxiv.org/abs/2406.06964)|**[link](https://github.com/payalmohapatra/Multimodal-Speech-Disfluency)**|
|**2024-05-28**|**Disentangling Foreground and Background Motion for Enhanced Realism in Human Video Generation**|Jinlin Liu et.al.|[2405.16393](http://arxiv.org/abs/2405.16393)|null|
|**2024-05-25**|**BVI-Lowlight: Fully Registered Benchmark Dataset for Low-Light Video Enhancement**|Nantheera Anantrasirichai et.al.|[2402.01970](http://arxiv.org/abs/2402.01970)|**[link](https://github.com/lrr-rachel/PCDUNet)**|
|**2024-05-24**|**Low-Light Video Enhancement via Spatial-Temporal Consistent Illumination and Reflection Decomposition**|Xiaogang Xu et.al.|[2405.15660](http://arxiv.org/abs/2405.15660)|null|
|**2024-05-24**|**Distinguish Any Fake Videos: Unleashing the Power of Large-scale Data and Motion Features**|Lichuan Ji et.al.|[2405.15343](http://arxiv.org/abs/2405.15343)|null|
|**2024-05-22**|**HR-INR: Continuous Space-Time Video Super-Resolution via Event Camera**|Yunfan Lu et.al.|[2405.13389](http://arxiv.org/abs/2405.13389)|null|
|**2024-05-22**|**Uncovering Hidden Connections: Iterative Search and Reasoning for Video-grounded Dialog**|Haoyu Zhang et.al.|[2310.07259](http://arxiv.org/abs/2310.07259)|**[link](https://github.com/hyu-zhang/itr)**|
|**2024-05-15**|**Illumination Histogram Consistency Metric for Quantitative Assessment of Video Sequences**|Long Chen et.al.|[2405.09716](http://arxiv.org/abs/2405.09716)|**[link](https://github.com/longchencv/ihc-metric)**|
|**2024-05-14**|**Light-VQA+: A Video Quality Assessment Model for Exposure Correction with Vision-Language Guidance**|Xunchu Zhou et.al.|[2405.03333](http://arxiv.org/abs/2405.03333)|**[link](https://github.com/SaMMyCHoo/Light-VQA-plus)**|
|**2024-05-04**|**Towards Real-world Video Face Restoration: A New Benchmark**|Ziyan Chen et.al.|[2404.19500](http://arxiv.org/abs/2404.19500)|null|
|**2024-05-01**|**VideoGigaGAN: Towards Detail-rich Video Super-Resolution**|Yiran Xu et.al.|[2404.12388](http://arxiv.org/abs/2404.12388)|null|
|**2024-04-27**|**UVEB: A Large-scale Benchmark and Baseline Towards Real-World Underwater Video Enhancement**|Yaofeng Xie et.al.|[2404.14542](http://arxiv.org/abs/2404.14542)|**[link](https://github.com/yzbouc/uveb)**|
|**2024-04-23**|**SC-HVPPNet: Spatial and Channel Hybrid-Attention Video Post-Processing Network with CNN and Transformer**|Tong Zhang et.al.|[2404.14709](http://arxiv.org/abs/2404.14709)|null|
|**2024-04-21**|**Beyond Alignment: Blind Video Face Restoration via Parsing-Guided Temporal-Coherent Transformer**|Kepeng Xu et.al.|[2404.13640](http://arxiv.org/abs/2404.13640)|**[link](https://github.com/kepengxu/pgtformer)**|
|**2024-04-21**|**Turb-Seg-Res: A Segment-then-Restore Pipeline for Dynamic Videos with Atmospheric Turbulence**|Ripon Kumar Saha et.al.|[2404.13605](http://arxiv.org/abs/2404.13605)|null|
|**2024-04-12**|**DiffBIR: Towards Blind Image Restoration with Generative Diffusion Prior**|Xinqi Lin et.al.|[2308.15070](http://arxiv.org/abs/2308.15070)|**[link](https://github.com/xpixelgroup/diffbir)**|
|**2024-04-11**|**DriveDreamer-2: LLM-Enhanced World Models for Diverse Driving Video Generation**|Guosheng Zhao et.al.|[2403.06845](http://arxiv.org/abs/2403.06845)|null|
|**2024-04-09**|**Space-Time Video Super-resolution with Neural Operator**|Yuantong Zhang et.al.|[2404.06036](http://arxiv.org/abs/2404.06036)|null|
|**2024-04-06**|**Collaborative Feedback Discriminative Propagation for Video Super-Resolution**|Hao Li et.al.|[2404.04745](http://arxiv.org/abs/2404.04745)|**[link](https://github.com/house-leo/cfdvsr)**|
|**2024-04-03**|**Translation-based Video-to-Video Synthesis**|Pratim Saha et.al.|[2404.04283](http://arxiv.org/abs/2404.04283)|null|
|**2024-04-03**|**Effective Adapter for Face Recognition in the Wild**|Yunhao Liu et.al.|[2312.01734](http://arxiv.org/abs/2312.01734)|null|
|**2024-03-29**|**Binarized Low-light Raw Video Enhancement**|Gengchen Zhang et.al.|[2403.19944](http://arxiv.org/abs/2403.19944)|**[link](https://github.com/ying-fu/brve)**|
|**2024-03-29**|**Video Super-Resolution Transformer with Masked Inter&Intra-Frame Attention**|Xingyu Zhou et.al.|[2401.06312](http://arxiv.org/abs/2401.06312)|**[link](https://github.com/labshuhanggu/mia-vsr)**|
|**2024-03-28**|**FMA-Net: Flow-Guided Dynamic Filtering and Iterative Feature Refinement with Multi-Attention for Joint Video Super-Resolution and Deblurring**|Geunhyuk Youk et.al.|[2401.03707](http://arxiv.org/abs/2401.03707)|null|
|**2024-03-25**|**Learning Spatial Adaptation and Temporal Coherence in Diffusion Models for Video Super-Resolution**|Zhikai Chen et.al.|[2403.17000](http://arxiv.org/abs/2403.17000)|null|
|**2024-03-23**|**Time-series Initialization and Conditioning for Video-agnostic Stabilization of Video Super-Resolution using Recurrent Networks**|Hiroshi Mori et.al.|[2403.15832](http://arxiv.org/abs/2403.15832)|null|
|**2024-03-21**|**StreamingT2V: Consistent, Dynamic, and Extendable Long Video Generation from Text**|Roberto Henschel et.al.|[2403.14773](http://arxiv.org/abs/2403.14773)|**[link](https://github.com/picsart-ai-research/streamingt2v)**|
|**2024-03-19**|**WaveFace: Authentic Face Restoration with Efficient Frequency Recovery**|Yunqi Miao et.al.|[2403.12760](http://arxiv.org/abs/2403.12760)|null|
|**2024-03-19**|**Improving Visual Quality and Transferability of Adversarial Attacks on Face Recognition Simultaneously with Adversarial Restoration**|Fengfan Zhou et.al.|[2309.01582](http://arxiv.org/abs/2309.01582)|null|
|**2024-03-18**|**End-To-End Underwater Video Enhancement: Dataset and Model**|Dazhao Du et.al.|[2403.11506](http://arxiv.org/abs/2403.11506)|**[link](https://github.com/ddz16/UVENet)**|
|**2024-03-18**|**Towards Real-World Blind Face Restoration with Generative Diffusion Prior**|Xiaoxu Chen et.al.|[2312.15736](http://arxiv.org/abs/2312.15736)|**[link](https://github.com/chenxx89/bfrffusion)**|
|**2024-03-15**|**DiffMAC: Diffusion Manifold Hallucination Correction for High Generalization Blind Face Restoration**|Nan Gao et.al.|[2403.10098](http://arxiv.org/abs/2403.10098)|null|
|**2024-03-13**|**PFStorer: Personalized Face Restoration and Super-Resolution**|Tuomas Varanka et.al.|[2403.08436](http://arxiv.org/abs/2403.08436)|null|
|**2024-03-11**|**AS-FIBA: Adaptive Selective Frequency-Injection for Backdoor Attack on Deep Face Restoration**|Zhenbo Song et.al.|[2403.06430](http://arxiv.org/abs/2403.06430)|null|
|**2024-03-10**|**BlazeBVD: Make Scale-Time Equalization Great Again for Blind Video Deflickering**|Xinmin Qiu et.al.|[2403.06243](http://arxiv.org/abs/2403.06243)|null|
|**2024-03-10**|**Learning Exposure Correction in Dynamic Scenes**|Jin Liu et.al.|[2402.17296](http://arxiv.org/abs/2402.17296)|**[link](https://github.com/kravrolens/vecnet)**|
|**2024-03-08**|**Decoupling Degradations with Recurrent Network for Video Restoration in Under-Display Camera**|Chengxu Liu et.al.|[2403.05660](http://arxiv.org/abs/2403.05660)|**[link](https://github.com/chengxuliu/ddrnet)**|
|**2024-02-29**|**BFRFormer: Transformer-based generator for Real-World Blind Face Restoration**|Guojing Ge et.al.|[2402.18811](http://arxiv.org/abs/2402.18811)|null|
|**2024-02-08**|**CLR-Face: Conditional Latent Refinement for Blind Face Restoration Using Score-Based Diffusion Models**|Maitreya Suin et.al.|[2402.06106](http://arxiv.org/abs/2402.06106)|null|
|**2024-02-05**|**Video Super-Resolution for Optimized Bitrate and Green Online Streaming**|Vignesh V Menon et.al.|[2402.03513](http://arxiv.org/abs/2402.03513)|null|
|**2024-01-26**|**VJT: A Video Transformer on Joint Tasks of Deblurring, Low-light Enhancement and Denoising**|Yuxiang Hui et.al.|[2401.14754](http://arxiv.org/abs/2401.14754)|null|
|**2024-01-21**|**Dual Associated Encoder for Face Restoration**|Yu-Ju Tsai et.al.|[2308.07314](http://arxiv.org/abs/2308.07314)|**[link](https://github.com/LIAGM/DAEFR)**|
|**2024-01-19**|**Semantic Lens: Instance-Centric Semantic Alignment for Video Super-Resolution**|Qi Tang et.al.|[2312.07823](http://arxiv.org/abs/2312.07823)|**[link](https://github.com/Tang1705/Semantic-Lens-AAAI24)**|
|**2024-01-18**|**Inflation with Diffusion: Efficient Temporal Adaptation for Text-to-Video Super-Resolution**|Xin Yuan et.al.|[2401.10404](http://arxiv.org/abs/2401.10404)|null|
|**2024-01-13**|**Deep Blind Super-Resolution for Satellite Video**|Yi Xiao et.al.|[2401.07139](http://arxiv.org/abs/2401.07139)|**[link](https://github.com/xy-boy/blind-satellite-vsr)**|
|**2024-01-13**|**ENTED: Enhanced Neural Texture Extraction and Distribution for Reference-based Blind Face Restoration**|Yuen-Fui Lau et.al.|[2401.06978](http://arxiv.org/abs/2401.06978)|null|
|**2023-12-30**|**A Survey on Super Resolution for video Enhancement Using GAN**|Ankush Maity et.al.|[2312.16471](http://arxiv.org/abs/2312.16471)|null|
|**2023-12-26**|**Geometric-Aware Low-Light Image and Video Enhancement via Depth Guidance**|Yingqi Lin et.al.|[2312.15855](http://arxiv.org/abs/2312.15855)|null|
|**2023-12-25**|**Toward Accurate and Temporally Consistent Video Restoration from Raw Data**|Shi Guo et.al.|[2312.16247](http://arxiv.org/abs/2312.16247)|**[link](https://github.com/guoshi28/vjdd)**|
|**2023-12-22**|**ViStripformer: A Token-Efficient Transformer for Versatile Video Restoration**|Fu-Jen Tsai et.al.|[2312.14502](http://arxiv.org/abs/2312.14502)|null|
|**2023-12-18**|**TMP: Temporal Motion Propagation for Online Video Super-Resolution**|Zhengqiang Zhang et.al.|[2312.09909](http://arxiv.org/abs/2312.09909)|**[link](https://github.com/xtudbxk/tmp)**|
|**2023-12-13**|**EventAid: Benchmarking Event-aided Image/Video Enhancement Algorithms with Real-captured Hybrid Dataset**|Peiqi Duan et.al.|[2312.08220](http://arxiv.org/abs/2312.08220)|null|
|**2023-12-13**|**Video Dynamics Prior: An Internal Learning Approach for Robust Video Enhancements**|Gaurav Shrivastava et.al.|[2312.07835](http://arxiv.org/abs/2312.07835)|null|
|**2023-12-11**|**Photorealistic Video Generation with Diffusion Models**|Agrim Gupta et.al.|[2312.06662](http://arxiv.org/abs/2312.06662)|null|
|**2023-12-11**|**Upscale-A-Video: Temporal-Consistent Diffusion Model for Real-World Video Super-Resolution**|Shangchen Zhou et.al.|[2312.06640](http://arxiv.org/abs/2312.06640)|null|
|**2023-12-11**|**Cross-Consistent Deep Unfolding Network for Adaptive All-In-One Video Restoration**|Yuanshuo Cheng et.al.|[2309.01627](http://arxiv.org/abs/2309.01627)|null|
|**2023-12-10**|**RBPGAN: Recurrent Back-Projection GAN for Video Super Resolution**|Marwah Sulaiman et.al.|[2311.09178](http://arxiv.org/abs/2311.09178)|null|
|**2023-12-07**|**ConVRT: Consistent Video Restoration Through Turbulence with Test-time Optimization of Neural Video Representations**|Haoming Cai et.al.|[2312.04679](http://arxiv.org/abs/2312.04679)|null|
|**2023-12-04**|**Peer attention enhances student learning**|Songlin Xu et.al.|[2312.02358](http://arxiv.org/abs/2312.02358)|**[link](https://github.com/songlinxu/peeredu)**|
|**2023-12-01**|**Blind Face Restoration for Under-Display Camera via Dictionary Guided Transformer**|Jingfan Tan et.al.|[2308.10196](http://arxiv.org/abs/2308.10196)|null|
|**2023-11-27**|**Scale-Adaptive Feature Aggregation for Efficient Space-Time Video Super-Resolution**|Zhewei Huang et.al.|[2310.17294](http://arxiv.org/abs/2310.17294)|**[link](https://github.com/megvii-research/wacv2024-safa)**|
|**2023-11-26**|**FLAIR: A Conditional Diffusion Framework with Applications to Face Video Restoration**|Zihao Zou et.al.|[2311.15445](http://arxiv.org/abs/2311.15445)|null|
|**2023-11-23**|**VCISR: Blind Single Image Super-Resolution with Video Compression Synthetic Data**|Boyang Wang et.al.|[2311.00996](http://arxiv.org/abs/2311.00996)|**[link](https://github.com/kiteretsu77/vcisr-official)**|
|**2023-11-15**|**FastBlend: a Powerful Model-Free Toolkit Making Video Stylization Easier**|Zhongjie Duan et.al.|[2311.09265](http://arxiv.org/abs/2311.09265)|**[link](https://github.com/artiprocher/sd-webui-fastblend)**|
|**2023-11-08**|**An End-Cloud Computing Enabled Surveillance Video Transmission System**|Dingxi Yang et.al.|[2311.04685](http://arxiv.org/abs/2311.04685)|null|
|**2023-11-07**|**Restoration of Analog Videos Using Swin-UNet**|Lorenzo Agnolucci et.al.|[2311.04261](http://arxiv.org/abs/2311.04261)|**[link](https://github.com/miccunifi/analog-video-restoration)**|
|**2023-11-03**|**Reference-based Restoration of Digitized Analog Videotapes**|Lorenzo Agnolucci et.al.|[2310.14926](http://arxiv.org/abs/2310.14926)|**[link](https://github.com/miccunifi/tape)**|
|**2023-10-18**|**HSTR-Net: Reference Based Video Super-resolution for Aerial Surveillance with Dual Cameras**|H. Umut Suluhan et.al.|[2310.12092](http://arxiv.org/abs/2310.12092)|null|
|**2023-10-17**|**Video Super-Resolution Using a Grouped Residual in Residual Network**|MohammadHossein Ashoori et.al.|[2310.11276](http://arxiv.org/abs/2310.11276)|null|
|**2023-10-09**|**Survey on Deep Face Restoration: From Non-blind to Blind and Beyond**|Wenjie Li et.al.|[2309.15490](http://arxiv.org/abs/2309.15490)|**[link](https://github.com/24wenjie-li/awesome-face-restoration)**|
|**2023-10-02**|**A New Real-World Video Dataset for the Comparison of Defogging Algorithms**|Alexandra Duminil et.al.|[2310.01020](http://arxiv.org/abs/2310.01020)|null|
|**2023-09-27**|**VideoAdviser: Video Knowledge Distillation for Multimodal Transfer Learning**|Yanan Wang et.al.|[2309.15494](http://arxiv.org/abs/2309.15494)|null|
|**2023-09-27**|**LAVIE: High-Quality Video Generation with Cascaded Latent Diffusion Models**|Yaohui Wang et.al.|[2309.15103](http://arxiv.org/abs/2309.15103)|**[link](https://github.com/Vchitect/LaVie)**|
|**2023-09-25**|**A Lightweight Recurrent Grouping Attention Network for Video Super-Resolution**|Yonggui Zhu et.al.|[2309.13940](http://arxiv.org/abs/2309.13940)|**[link](https://github.com/karlygzhu/rgan)**|
|**2023-09-25**|**Fill the K-Space and Refine the Image: Prompting for Dynamic and Multi-Contrast MRI Reconstruction**|Bingyu Xin et.al.|[2309.13839](http://arxiv.org/abs/2309.13839)|**[link](https://github.com/hellopipu/promptmr)**|
|**2023-09-19**|**PGDiff: Guiding Diffusion Models for Versatile Face Restoration via Partial Guidance**|Peiqing Yang et.al.|[2309.10810](http://arxiv.org/abs/2309.10810)|**[link](https://github.com/pq-yang/pgdiff)**|
|**2023-09-14**|**HDTR-Net: A Real-Time High-Definition Teeth Restoration Network for Arbitrary Talking Face Generation Methods**|Yongyuan Li et.al.|[2309.07495](http://arxiv.org/abs/2309.07495)|**[link](https://github.com/yylgoodlucky/hdtr)**|
|**2023-09-13**|**Aggregating Long-term Sharp Features via Hybrid Transformers for Video Deblurring**|Dongwei Ren et.al.|[2309.07054](http://arxiv.org/abs/2309.07054)|**[link](https://github.com/shangwei5/stgtn)**|
|**2023-09-09**|**Deep Video Restoration for Under-Display Camera**|Xuanxi Chen et.al.|[2309.04752](http://arxiv.org/abs/2309.04752)|null|
|**2023-08-18**|**SimDA: Simple Diffusion Adapter for Efficient Video Generation**|Zhen Xing et.al.|[2308.09710](http://arxiv.org/abs/2308.09710)|null|
|**2023-08-15**|**Boosting Cross-Quality Face Verification using Blind Face Restoration**|Messaoud Bengherabi et.al.|[2308.07967](http://arxiv.org/abs/2308.07967)|null|
|**2023-08-14**|**RestoreFormer++: Towards Real-World Blind Face Restoration from Undegraded Key-Value Pairs**|Zhouxia Wang et.al.|[2308.07228](http://arxiv.org/abs/2308.07228)|**[link](https://github.com/wzhouxiff/restoreformerplusplus)**|
|**2023-08-13**|**FastLLVE: Real-Time Low-Light Video Enhancement with Intensity-Aware Lookup Table**|Wenhao Li et.al.|[2308.06749](http://arxiv.org/abs/2308.06749)|**[link](https://github.com/wenhao-li-777/fastllve)**|
|**2023-08-10**|**DiffSynth: Latent In-Iteration Deflickering for Realistic Video Synthesis**|Zhongjie Duan et.al.|[2308.03463](http://arxiv.org/abs/2308.03463)|null|

<p align=right>(<a href=#updated-on-20241206>back to top</a>)</p>

Notes: 

* We have modified the `sorting rule` of the above table to prioritize papers based on the time of their latest update rather than their initial publication date. If an article has been recently modified, it will appear earlier in the list. 

* However, recent trends are still based on `ten` papers sorted by the initial publication date. 

Function added: 

* Support more reliable text parser. [Link](https://github.com/pdfminer/pdfminer.six) 

* Support rich markdown format (better at parsing experimental tables). [Link](https://github.com/davendw49/sciparser) 

* Supports the analysis of more than 10 papers in a single conversation, which exceeds the attachment size limit. 

[contributors-shield]: https://img.shields.io/github/contributors/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[contributors-url]: https://github.com/hhhh1138/video-restoration-arxiv-daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[forks-url]: https://github.com/hhhh1138/video-restoration-arxiv-daily/network/members
[stars-shield]: https://img.shields.io/github/stars/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[stars-url]: https://github.com/hhhh1138/video-restoration-arxiv-daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[issues-url]: https://github.com/hhhh1138/video-restoration-arxiv-daily/issues

