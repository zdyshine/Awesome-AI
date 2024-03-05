# Awesome-AI
收集有趣的开源算法

## 目录
  - [1. Audio-Face](#1-Audio-Face)
  - [2. I2V](#2-Image-To-Video)
  - [3. CV-base](#3-CV-base)

    
###  1. <a name='Audio-Face'></a>Audio-Face
* Real3DPortrait:
  * 地址：https://github.com/yerfor/Real3DPortrait
  * 简介：在给定的样例中效果很好，需要研究示例样本去适配(正面图片和正面视频，大头照，头部区域基本平齐)，该作者相关工作很多，多关注。
* SyncTalk:
  * 地址：https://github.com/ziqiaopeng/SyncTalk
  * 简介：代码还未开源，示例视频中给的是上半身的视频，非大头照。

* SadTalker：
  * 地址：https://github.com/OpenTalker/SadTalker
  * 简介：语音驱动图片，生成可说话的动态图片。嘴型和微表情生成效果不错，稍有对齐问题，可通过后处理提升效果。
  * 效果测试：在合适的参数和输入图片场景下，可实现特定场景的应用。
  
* SadTalker-Video-Lip-Sync：
  * 地址：https://github.com/Zz-ww/SadTalker-Video-Lip-Sync
  * 简介：基于SadTalker的唇形优化
      
* GeneFace++：
  * 地址：https://github.com/yerfor/GeneFacePlusPlus
  * 简介：实现高嘴形对齐(lip-sync)、高视频真实度(video reality)、高系统效率(system efficiency)的虚拟人视频合成
    
* Wav2Lip:
  * 地址：https://github.com/Rudrabha/Wav2Lip
  * 简介：语音驱动唇部动作的经典之作。

###  2. <a name='I2V'></a>Image-To-Video

#### 2.1 图像生成视频

* AtomoVideo:
  * paper：https://arxiv.org/pdf/2403.01800.pdf
  * github：https://atomo-video.github.io/
  * 简介：基于多粒度图像注入，我们实现了生成的视频对给定图像的更高保真度。此外，得益于高质量的数据集和训练策略，我们在保持卓越的时间一致性和稳定性的同时实现了更大的运动强度。我们的架构灵活地扩展到视频帧预测任务，通过迭代生成实现长序列预测。

* MoVideo：
  * 地址：https://arxiv.org/pdf/2311.11325.pdf
  * 简介：文生图，结合光流和深度估计，在生成视频。
  * 
###  3. <a name='CV-base'></a>CV-base

#### 3.1 图像生成
* DragGAN：
  * 地址：https://github.com/XingangPan/DragGAN
  * 简介：可自由修改，拖拽等形式修改图像。目前支持的类型有限，商用需针对性训练。

* AnimateDiff：
  * 地址：https://github.com/guoyww/AnimateDiff
  * 简介：提出了一种有效的框架，一次性对现有的大多数个性化文本到图像模型进行动画处理，从而节省了在特定模型上进行调优所需的精力。
    
#### 3.2 图像质量评价

* SAM-IQA：
  * 地址：https://github.com/Hedlen/SAM-IQA
  * 简介：结合大模型，图像分割，进行IQA。
  * 
#### 3.3 图像分割

* segment-anything(SAM)：
  * 地址：https://github.com/facebookresearch/segment-anything
  * 简介：大模型，图像分割。可作为CV人物的基座

* Grounded-Segment-Anything(Grounded-SAM)：
  * 地址：https://github.com/IDEA-Research/Grounded-Segment-Anything
  * 简介：大模型，图像分割。可作为CV人物的基座

* HQ-SAM：
  * 地址：https://github.com/SysCV/sam-hq
  * 简介：大模型，图像分割。可作为CV人物的基座，分割质量更高更精准

* SEELE：
  * paper：https://browse.arxiv.org/pdf/2401.16861.pdf | https://yikai-wang.github.io/seele/
  * 简介：修改图像中的物体进行移位操作
  * 
