[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

# Video-Restoration Research Papers (With GPT Analysis)
### Automatically Updated on 2024.07.11
Current Search Keywords: `Video Restoration`, `Video Enhancement`, `Video Super Resolution`, `Face Restoration`, `Video Deblurring`

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

[>>>> Each Paper Analysis (by AI) <<<<](https://github.com/hhhh1138/video-restoration-arxiv-daily/blob/main/analysis_by_ai.md) 

[Web Page](https://liutaocode.github.io/talking-face-arxiv-daily/) ([Scrape Code](https://github.com/liutaocode/talking-face-arxiv-daily)) 

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href=#video-restoration>Video Restoration</a></li>
  </ol>
</details>

## Video Restoration

|Publish Date|Title|Authors|PDF|Code|
|---|---|---|---|---|
|**2024-07-10**|**VEnhancer: Generative Space-Time Enhancement for Video Generation**|Jingwen He et.al.|[2407.07667](http://arxiv.org/abs/2407.07667)|null|
|**2024-07-10**|**MNeRV: A Multilayer Neural Representation for Videos**|Qingling Chang et.al.|[2407.07347](http://arxiv.org/abs/2407.07347)|**[link](https://github.com/aaronbtb/mnerv)**|
|**2024-07-10**|**DaBiT: Depth and Blur informed Transformer for Joint Refocusing and Super-Resolution**|Crispian Morris et.al.|[2407.01230](http://arxiv.org/abs/2407.01230)|null|
|**2024-07-03**|**BVI-RLV: A Fully Registered Dataset and Benchmarks for Low-Light Video Enhancement**|Ruirui Lin et.al.|[2407.03535](http://arxiv.org/abs/2407.03535)|null|
|**2024-07-02**|**Zero-shot Video Restoration and Enhancement Using Pre-Trained Image Diffusion Model**|Cong Cao et.al.|[2407.01960](http://arxiv.org/abs/2407.01960)|null|
|**2024-07-01**|**DiffIR2VR-Zero: Zero-Shot Video Restoration with Diffusion-based Image Restoration Models**|Chang-Han Yeh et.al.|[2407.01519](http://arxiv.org/abs/2407.01519)|null|
|**2024-06-24**|**Improving Generative Adversarial Networks for Video Super-Resolution**|Daniel Wen et.al.|[2406.16359](http://arxiv.org/abs/2406.16359)|null|
|**2024-06-21**|**LU2Net: A Lightweight Network for Real-time Underwater Image Enhancement**|Haodong Yang et.al.|[2406.14973](http://arxiv.org/abs/2406.14973)|null|
|**2024-06-19**|**EvTexture: Event-driven Texture Enhancement for Video Super-Resolution**|Dachun Kai et.al.|[2406.13457](http://arxiv.org/abs/2406.13457)|**[link](https://github.com/dachunkai/evtexture)**|
|**2024-06-15**|**Fast Unsupervised Tensor Restoration via Low-rank Deconvolution**|David Reixach et.al.|[2406.10679](http://arxiv.org/abs/2406.10679)|null|

<p align=right>(<a href=#updated-on-20240711>back to top</a>)</p>

Notes: 

* We have modified the `sorting rule` of the above table to prioritize papers based on the time of their latest update rather than their initial publication date. If an article has been recently modified, it will appear earlier in the list. 

* However, recent trends are still based on `ten` papers sorted by the initial publication date. 

Function added: 

* Support more reliable text parser. [Link](https://github.com/pdfminer/pdfminer.six) 

* Support rich markdown format (better at parsing experimental tables). [Link](https://github.com/davendw49/sciparser) 

* Supports the analysis of more than 10 papers in a single conversation, which exceeds the attachment size limit. 

[contributors-shield]: https://img.shields.io/github/contributors/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[contributors-url]: https://github.com/liutaocode/talking-face-arxiv-daily/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[forks-url]: https://github.com/liutaocode/talking-face-arxiv-daily/network/members
[stars-shield]: https://img.shields.io/github/stars/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[stars-url]: https://github.com/liutaocode/talking-face-arxiv-daily/stargazers
[issues-shield]: https://img.shields.io/github/issues/liutaocode/talking-face-arxiv-daily.svg?style=for-the-badge
[issues-url]: https://github.com/liutaocode/talking-face-arxiv-daily/issues

