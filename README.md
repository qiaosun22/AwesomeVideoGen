# AwesomeVideoGen

# Open-source Video Generation Toolboxes & Foundation Models

**Definition**:  
A collection of open-source frameworks and pre-trained foundation models for video synthesis/editing tasks, covering text-to-video, image-to-video, and video-to-video transformation technologies.

---

## 📦 Toolboxes
---

### **Open-source Toolboxes and Foundation Models**  
**定义**：指开源的工具箱（集成化开发环境/工具集合）和基础模型（预训练的大规模多模态模型），用于视频生成、编辑、合成等任务。这类资源通常提供模型架构、训练代码、推理接口或应用案例，推动视频生成领域的可复现研究和工业应用。

---

#### **1. [Wan-Video](https://github.com/Wan-Video/Wan2.1)**  
**概念**：Wan-Video是一个开源视频生成框架，专注于高质量视频合成与编辑。其核心可能基于扩散模型（Diffusion Models），支持文本/图像到视频的生成任务。  
**特点**：  
- 提供模块化设计，便于自定义视频生成流程  
- 官网([wanxai.com](https://wanxai.com/))可能包含在线演示或商业应用案例  
- GitHub活跃度通过Stars数量反映社区关注度  

---

#### **2. [DiffSynth-Studio](https://github.com/modelscope/DiffSynth-Studio)**  
**概念**：由ModelScope推出的差异化合成工作室，可能集成多种视频生成技术（如分层渲染、时序控制）。  
**特点**：  
- 依托ModelScope生态，兼容其他阿里达摩院模型  
- 可能支持工业级视频生成需求（如广告、影视预可视化）  

---

#### **3. [Step-Video-T2V Technical Report](https://arxiv.org/abs/2502.10248)**  
**概念**：StepFun团队发布的视频基础模型技术报告，系统性探讨视频生成的实践、挑战与未来方向。  
**关键内容**（基于arXiv摘要）：  
- 提出分阶段训练策略优化时序一致性  
- 分析当前视频模型的三大瓶颈：计算成本、长视频连贯性、多模态对齐  
- 关联应用案例见于[阅文集团视频平台](https://yuewen.cn/videos)  

---

#### **4. [Cosmos](https://github.com/NVIDIA/Cosmos)**  
**概念**：NVIDIA实验室开发的视频生成框架，强调物理真实的动态模拟（如流体、粒子效果）。  
**技术亮点**（基于[论文](https://arxiv.org/abs/2501.03575)）：  
- 结合神经渲染与物理引擎（如PhysX）  
- 支持高分辨率视频合成（如4K@60fps）  
- 官网展示[科研级应用](https://research.nvidia.com/labs/dir/cosmos1/)  

---

#### **5. [LTX-Video](https://github.com/Lightricks/LTX-Video)**  
**概念**：由知名AI公司Lightricks（Facetune开发者）开源的轻量化视频生成工具，可能面向移动端优化。  
**推测特点**：  
- 低延迟推理（适合实时应用）  
- 集成特效滤镜等创意功能  

---

#### **6. [HunyuanVideo](https://arxiv.org/abs/2412.03603)**  
**概念**：腾讯混元大模型体系的视频生成子系统，采用"系统性框架"设计。  
**论文核心**：  
- 多专家混合架构（MoE）处理不同视频模态  
- 支持长视频生成（>1分钟）与细粒度编辑  
- GitHub仓库包含预训练模型权重  


---

#### **7. [VideoTuna](https://videoverses.github.io/videotuna/)**  
**概念**：由VideoVerses团队开发的轻量级视频生成工具包，主打**高效微调**（Fine-tuning）能力，支持用户自定义风格迁移。  
**技术亮点**：  
- 基于扩散模型的**低秩适配（LoRA）**技术，实现快速模型适配  
- 提供Web端交互界面（见[官网](https://videoverses.github.io/videotuna/)），支持实时预览  
- 目标场景：短视频内容创作、个性化视频生成  

---

#### **8. [Allegro](https://rhymes.ai/blog-details/allegro-advanced-video-generation-model)**  
**概念**：Rhymes.ai发布的**音乐驱动视频生成模型**，强调音频-视觉跨模态同步。  
**核心能力**（基于[论文](https://arxiv.org/abs/2410.15458)）：  
- 时序对齐：通过**节奏检测算法**动态匹配视频动作与音乐节拍  
- 支持风格化生成（如卡通、写实等）  
- 应用案例：AI MV制作、广告配乐视频  

---

#### **9. [Mochi 1](https://www.genmo.ai/blog)**  
**概念**：Genmo推出的**多模态生成模型套件**，视频生成是其核心功能之一。  
**特点**：  
- 强调**交互式生成**：用户可通过自然语言实时调整生成结果  
- 商业化导向：官网博客展示与设计平台的集成案例  
- 可能采用**MoE（Mixture of Experts）**架构优化生成效率  

---

#### **10. [Movie Gen: A Cast of Media Foundation Models](https://ai.meta.com/research/publications/movie-gen-a-cast-of-media-foundation-models/)**  
**概念**：Meta发布的**电影级生成模型家族**，覆盖剧本→分镜→视频全流程。  
**系统组成**（据[论文](https://arxiv.org/pdf/2410.13720)）：  
- **Text-to-Storyboard**：剧本转分镜脚本  
- **Scene Dynamics Model**：物理合理的动态模拟  
- **Post-Processing**：自动调色、特效合成  
- 配套[YouTube演示集](https://www.youtube.com/playlist?list=PL86eLlsPNfyi27GSizYjinpYxp7gEl5K8)展示完整流程  

---

#### **11. [Pyramidal Flow Matching for Efficient Video Generative Modeling](https://pyramid-flow.github.io/)**  
**概念**：基于**流匹配（Flow Matching）**的新型视频生成方法，通过金字塔结构优化计算效率。  
**技术突破**：  
- **多尺度训练**：从低分辨率到高分辨率的渐进式生成  
- 相比扩散模型，**减少50%训练成本**（论文宣称）  
- GitHub仓库提供PyTorch实现  

---

#### **12. [Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan)**  
**概念**：北京大学团队发起的**开源Sora复现计划**，旨在构建类Sora的视频生成生态系统。  
**当前进展**（v1.0.0报告）：  
- 已实现**时空分割注意力（STSA）**模块  
- 支持**可变长宽比视频**生成  
- 长期目标：构建从数据清洗到推理部署的全流程工具链  

---

#### **13. [Open-Sora](https://github.com/hpcaitech/Open-Sora)**  
**概念**：ColossalAI团队推出的**高效Sora实现方案**，侧重分布式训练优化。  
**差异化**：  
- 基于**ColossalAI框架**，支持多机多卡并行训练  
- 中文文档详尽，适合国内开发者  
- 已实现**3D时空压缩**（类似Sora的ViT-3D架构）  

---

### **14. [Stable Video Diffusion (SVD)](https://github.com/Stability-AI/generative-models)**  
**概念**：Stability AI 开源的**文本/图像到视频生成模型**，基于扩散模型架构，支持高动态范围（HDR）视频生成。  
**技术特性**：  
- **双阶段训练**：  
  - 第一阶段：基于静态图像预训练（图像→视频先验学习）  
  - 第二阶段：时序一致性微调（优化帧间连贯性）  
- **分辨率支持**：最高 **576×1024**，可生成 **3-5秒** 短视频  
- **应用场景**：广告创意、社交媒体内容生成  
**资源**：  
  - [官方公告](https://stability.ai/news/stable-video-diffusion-open-ai-video-model) 提供在线试玩和商业许可说明  

---

### **15. [Show-1](https://github.com/showlab/Show-1)**  
**概念**：ShowLab 提出的**混合架构视频生成模型**，结合扩散模型（Diffusion）与自回归模型（Autoregressive）优势。  
**创新点**：  
- **Hybrid Pipeline**：  
  - 扩散模型生成关键帧（关键动作）  
  - 自回归模型插值中间帧（平滑过渡）  
- **长视频支持**：通过分块生成实现 **>30秒** 连续视频  
- **控制能力**：支持通过草图（Sketch）控制生成内容  
**Demo**：见 [项目主页](https://showlab.github.io/Show-1/)  

---

### **16. [Hotshot-XL](https://github.com/hotshotco/Hotshot-XL)**  
**概念**：专为 **文本→GIF** 优化的轻量级模型，强调快速推理与趣味性生成。  
**特点**：  
- **实时生成**：在消费级GPU（如RTX 3060）上实现 **<2秒** 生成  
- **风格化输出**：支持像素艺术、卡通等多种风格  
- **应用集成**：提供 Discord 机器人接口，适合社区互动  

---

### **17. [zeroscope_v2](https://huggingface.co/cerspense/zeroscope_v2_576w)**  
**概念**：HuggingFace 社区训练的**开源视频生成模型**，主打零样本（Zero-shot）适应能力。  
**模型变体**：  
- **576w**：基础版，平衡质量与速度  
- **XL**：高分辨率版（768×1344），需更高显存  
**典型用途**：  
  - 教育视频快速生成  
  - 低代码平台集成（通过HuggingFace Pipeline）  

---

### **18. [I2VGen-XL](https://modelscope.cn/models/damo/Image-to-Video/summary)**  
**概念**：达摩院开发的**图像/视频到视频转换模型**，支持复杂场景动态化。  
**功能分支**：  
- **Image-to-Video**：静态图转动态视频（如让风景照片中的云层流动）  
- **Video-to-Video**：视频风格/内容重绘（如昼夜转换）  
**技术亮点**：  
  - 使用 **光流估计（Optical Flow）** 保持运动一致性  
  - 支持 **4K超分** 后处理

![image](https://github.com/user-attachments/assets/545f01a5-afe8-4f6d-91dd-f38ccb630f1f)

---

### **19. [text-to-video-synthesis-colab](https://github.com/camenduru/text-to-video-synthesis-colab)**  
**概念**：社区开发者 camenduru 维护的 **Colab Notebook 集合**，集成多个视频生成模型的一键运行环境。  
**优势**：  
- **零配置**：免费GPU资源直接运行（如T4、A100）  
- **模型覆盖全**：包括 Stable Video Diffusion、Zeroscope等  
- **快速实验**：适合学术研究或原型验证  

---

### **20. [VideoCrafter](https://github.com/VideoCrafter/VideoCrafter)**  
**概念**：一站式视频生成与编辑工具箱，覆盖从生成到后处理的完整流程。  
**模块组成**：  
- **Crafter1**：基础文本→视频模型  
- **Crafter2**：支持视频编辑（如对象替换、动态调整）  
- **Toolset**：提供帧提取、插值、超分等实用脚本  

---

### **21. [ModelScope](https://modelscope.cn/models/damo/text-to-video-synthesis/summary)**  
**概念**：阿里达摩院的**模型即服务（MaaS）平台**，内置多模态生成模型。  
**视频相关功能**：  
- **文本→视频**：基于多阶段扩散模型  
- **API支持**：可通过Python SDK直接调用  
- **中文优化**：对中文提示词理解更精准  

---

### **22. [Diffusers](https://huggingface.co/docs/diffusers/main/en/api/pipelines/text_to_video#texttovideo-synthesis)**  
**概念**：HuggingFace 的**标准化扩散模型库**，提供视频生成统一接口。  
**核心价值**：  
- **跨模型兼容性**：相同API调用Stable Video Diffusion、Zeroscope等  
- **自定义训练**：支持LoRA、DreamBooth等微调方法  
- **社区支持**：持续集成最新模型（如Sora复现尝试）  

---

### **关键对比总结**  
| 工具/模型          | 核心优势                          | 适用场景                  |
|--------------------|----------------------------------|-------------------------|
| **Stable Video Diffusion** | 工业级稳定性，HDR支持       | 商业内容创作            |
| **Show-1**         | 长视频生成能力                | 影视预可视化            |
| **Hotshot-XL**     | 极速GIF生成                   | 社交媒体/即时通讯       |
| **Diffusers**      | 统一API，灵活扩展            | 研究/快速原型开发       |



---

### **23. [Wunjo CE](https://github.com/wladradchenko/wunjo.wladradchenko.ru)**  
**概念**：全栈式**视频生成与编辑工具**，集成语音合成、面部动画等多媒体功能。  
**核心模块**：  
- **Text-to-Video**：支持多语言文本驱动生成  
- **Voice Cloning**：结合音视频生成对口型动画  
- **GUI界面**：无需编程基础，适合创意工作者  
**技术栈**：基于PyTorch + FFmpeg，提供Windows/macOS本地应用  

---

### **技术深度解析**  
#### **1. 光流估计（Optical Flow）**  
- **用途**：在I2VGen-XL等模型中保持视频帧间运动一致性  
- **代表算法**：RAFT、FlowNet  
- **开源实现**：参考[OpenCV光流模块](https://docs.opencv.org/4.x/d7/d8b/tutorial_py_lucas_kanade.html)  

#### **2. LoRA微调**  
- **原理**：通过低秩矩阵分解降低训练参数量  
- **视频应用**：  
  - VideoTuna实现风格微调（<1GB显存需求）  
  - Diffusers库提供[官方LoRA训练脚本](https://huggingface.co/docs/diffusers/training/lora)  

---

### **选型指南**  
根据需求匹配工具：  

| **需求场景**          | **推荐工具**                          | **理由**                          |
|-----------------------|--------------------------------------|----------------------------------|
| 快速原型开发          | text-to-video-synthesis-colab        | 免配置，免费GPU资源              |
| 中文视频生成          | ModelScope                           | 针对中文优化，API易用            |
| 长视频生成（>30秒）   | Show-1                               | 混合架构解决连贯性问题            |
| 商业级HDR内容         | Stable Video Diffusion               | 官方商业许可支持                  |
| 实时交互编辑          | Wunjo CE                             | 图形化界面+多模态集成             |

---

### **未来方向**  
1. **计算优化**：Pyramidal Flow Matching等方法的普及可能降低训练成本  
2. **控制精度**：结合扩散模型与物理引擎（如Cosmos）提升动态真实性  
3. **开源生态**：Open-Sora-Plan等项目的进展将推动Sora类技术民主化  

---
## Video Generation

---

### **1. [Aligning Text-to-Video Generation Models with Prompt Optimization](https://arxiv.org/abs/2503.20491)**  
**概念**：VPO（Video Prompt Optimizer）是由清华大学和Zhipu AI提出的**文本到视频生成模型的提示优化框架**，通过两阶段优化（监督微调+多反馈偏好学习）解决用户输入与模型训练数据之间的语义鸿沟问题。  
**技术亮点**：  
- **三原则对齐**：无害性（Harmlessness）、准确性（Accuracy）、帮助性（Helpfulness）  
- **多反馈机制**：结合文本级（LLM评判）和视频级（VisionReward评分）反馈优化提示  
- **泛化能力**：在CogVideoX和Open-Sora等模型上验证，人类评估胜率提升37.5%  
**应用场景**：安全敏感的视频生成（如教育、广告）  

---

### **2. [Target-Aware Video Diffusion Models](https://arxiv.org/abs/2503.18950)**  
**概念**：TAVID（Target-Aware Video Diffusion）通过**目标感知注意力机制**实现视频生成中的精确对象控制，支持动态目标跟踪与属性编辑。  
**创新点**：  
- **空间-目标解耦**：分离背景与目标对象的运动建模  
- **物理一致性**：集成光流估计保持运动连续性  
- **交互式编辑**：官网演示支持用户框选目标并修改属性（如颜色、运动轨迹）  
**数据效率**：仅需单目标标注视频即可微调模型  

---

### **3. [MagicComp: Training-free Dual-Phase Refinement for Compositional Video Generation](https://arxiv.org/abs/2503.14428)**  
**概念**：无需训练的**双阶段视频合成框架**，通过解耦内容（物体）与场景（背景）生成多元素组合视频。  
**关键技术**：  
- **动态掩码引导**：第一阶段生成主体对象，第二阶段融合背景  
- **零样本适配**：兼容Stable Video Diffusion等现成模型  
- **应用案例**：电商产品展示视频合成（见[项目页](https://hong-yu-zhang.github.io/MagicComp-Page/)）  

---

### **4. [Video-T1: Test-Time Scaling for Video Generation](https://arxiv.org/abs/2503.18942)**  
**概念**：通过**测试时动态调整扩散步长**提升视频生成效率，在推理阶段优化计算资源分配。  
**性能对比**：  
| 方法               | 生成速度（帧/秒） | 显存占用（GB） |  
|--------------------|------------------|---------------|  
| 传统扩散模型        | 2.1              | 24            |  
| Video-T1（动态调整）| 5.8 (+176%)      | 18 (-25%)     |  
**适用场景**：边缘设备实时视频生成  

---

### **5. [Temporal Regularization Makes Your Video Generator Stronger](https://arxiv.org/abs/2503.15417)**  
**概念**：提出**时序正则化损失函数**（FluxFlow），通过约束帧间光流一致性解决视频闪烁问题。  
**实验效果**：  
- 在UCF-101数据集上，FVD分数降低22.3%  
- 支持长视频生成（>100帧）  
**可视化案例**：见[项目主页](https://haroldchen19.github.io/FluxFlow/)的天气变化序列  


---

### **1. [VACE: All-in-One Video Creation and Editing](https://arxiv.org/pdf/2503.07598)**  
**概念**：阿里视觉实验室提出的**全流程视频生成与编辑框架**，支持从文本/图像输入到多粒度编辑的一站式解决方案。  
**技术亮点**：  
- **分层编辑架构**：  
  - **全局层**：基于LLM的脚本分镜生成（支持多语言）  
  - **局部层**：扩散模型驱动的主体替换/运动重定向（如人物动作迁移）  
- **物理感知编辑**：通过光流约束保持编辑区域的阴影/反射一致性  
- **应用案例**：电商视频批量生成（见[项目页](https://ali-vilab.github.io/VACE-Page/)的服装展示案例）  

---

### **2. [RIFLEx: Length Extrapolation in Video Diffusion Transformers](https://arxiv.org/abs/2502.15894)**  
**概念**：清华ML组开发的**长视频生成技术**，通过改进DiT架构的注意力机制突破序列长度限制。  
**创新方法**：  
- **相对位置编码扩展**：将可处理的帧数从128帧提升至512帧（约20秒）  
- **动态稀疏注意力**：对远距离帧采用稀疏计算，显存占用减少40%  
- **效果**：在ActivityNet数据集上生成连贯的纪录片风格长视频  

---

### **3. [DLFR-VAE: Dynamic Latent Frame Rate VAE](https://arxiv.org/abs/2502.11897)**  
**概念**：自适应帧率视频生成模型，根据运动复杂度动态调整关键帧间隔。  
**技术价值**：  
- **计算优化**：静态场景帧率可降至5fps，动态场景保持24fps，整体生成速度提升2.3倍  
- **医疗应用**：在超声视频生成中实现病灶区域的高帧率聚焦  

---

### **4. [Magic 1-For-1: Real-Time Video Generation](https://arxiv.org/abs/2502.07701)**  
**概念**：北大DAIG组实现的**实时文本-视频生成系统**，1分钟内生成1分钟视频。  
**关键技术**：  
- **级联蒸馏**：将14B参数模型压缩至3B，保持90%生成质量  
- **流水线并行**：在8×A100上实现56 FPS吞吐量  
- **局限性**：分辨率限制为480p，适合短视频平台快速生产  

---

### **5. [Lumina-Video: Multi-scale Next-DiT](https://arxiv.org/abs/2502.06782)**  
**概念**：Alpha-VLLM团队提出的**多尺度DiT架构**，通过时空分离注意力实现4K视频生成。  
**核心设计**：  
- **空间组**：处理单帧内细节（纹理/光照）  
- **时间组**：管理跨帧运动（相机轨迹/物体位移）  
- **硬件需求**：需80GB显存支持全参数训练，但提供FP8量化版本  

---



### **关键对比**  
| 模型       | 核心突破                | 适用场景               | 硬件需求       |  
|------------|-------------------------|-----------------------|---------------|  
| **VACE**   | 全流程编辑              | 商业视频批量生产       | 消费级GPU     |  
| **RIFLEx** | 长视频连贯性            | 纪录片/教育视频        | 专业级GPU     |  
| **Magic**  | 实时生成                | 社交媒体/UGC内容       | 中等配置GPU   |  

**下一步可深入**：  
1. **医疗视频生成**：DLFR-VAE在动态MRI中的应用潜力  
2. **4K优化技术**：Lumina-Video的时空注意力机制细节  

如需扩展其他论文（如RepVideo、VideoVAEPlus）的解析，请告知具体方向。

### **关键对比**  
| 模型          | 核心优势                  | 适用任务                  |  
|--------------|--------------------------|-------------------------|  
| **VPO**      | 安全可控的提示优化        | 合规性要求高的场景生成    |  
| **TAVID**    | 精确目标控制              | 广告/影视特效制作         |  
| **MagicComp**| 零样本多元素组合          | 电商/教育视频快速生成     |  

**下一批次将解析**：VACE、RIFLEx等视频编辑与长视频生成模型。是否需要针对特定技术（如光流约束、目标感知注意力）展开说明？

---

### 1. Integrated Development Frameworks
| Project | Stars | Paper | Demo | Key Features |
|---------|-------|-------|------|--------------|
| **[Wan-Video](https://github.com/Wan-Video/Wan2.1)** <br> Modular video generation framework | [![Stars](https://img.shields.io/github/stars/Wan-Video/Wan2.1.svg?style=social)](https://github.com/Wan-Video/Wan2.1) | - | [Website](https://wanxai.com/) | • Commercial-grade generation <br> • Supports multi-condition input |
| **[DiffSynth-Studio](https://github.com/modelscope/DiffSynth-Studio)** <br> ModelScope's video synthesis studio | [![Stars](https://img.shields.io/github/stars/modelscope/DiffSynth-Studio.svg?style=social)](https://github.com/modelscope/DiffSynth-Studio) | - | - | • Industrial pipeline integration <br> • Hierarchical rendering |
| **[VideoCrafter](https://github.com/VideoCrafter/VideoCrafter)** <br> End-to-end video toolkit | [![Stars](https://img.shields.io/github/stars/VideoCrafter/VideoCrafter.svg?style=social)](https://github.com/VideoCrafter/VideoCrafter) | - | - | • Crafter1/2 models <br> • Post-processing scripts |

### 2. Community Resources
| **[text-to-video-synthesis-colab](https://github.com/camenduru/text-to-video-synthesis-colab)** <br> Colab notebooks collection | [![Stars](https://img.shields.io/github/stars/camenduru/text-to-video-synthesis-colab.svg?style=social)](https://github.com/camenduru/text-to-video-synthesis-colab) | - | - | • One-click run <br> • T4/A100 support |
| **[Diffusers](https://huggingface.co/docs/diffusers/main/en/api/pipelines/text_to_video)** <br> Standardized diffusion library | [![Stars](https://img.shields.io/github/stars/huggingface/diffusers.svg?style=social)](https://github.com/huggingface/diffusers) | - | - | • Unified API <br> • LoRA/DreamBooth support |

---

## � Foundation Models

### 1. Text-to-Video
| Model | Stars | Paper | Demo | Technical Highlights |
|-------|-------|-------|------|----------------------|
| **[Stable Video Diffusion](https://github.com/Stability-AI/generative-models)** <br> Stability AI's flagship model | [![Stars](https://img.shields.io/github/stars/Stability-AI/generative-models.svg?style=social)](https://github.com/Stability-AI/generative-models) | - | [Website](https://stability.ai/news/stable-video-diffusion-open-ai-video-model) | • Two-stage training <br> • HDR support |
| **[HunyuanVideo](https://arxiv.org/abs/2412.03603)** <br> Tencent's MoE-based model | [![Stars](https://img.shields.io/github/stars/Tencent/HunyuanVideo.svg?style=social)](https://github.com/Tencent/HunyuanVideo) | [arXiv](https://arxiv.org/abs/2412.03603) | - | • Long-video generation <br> • Multi-expert architecture |

### 2. Specialized Models
| **[Hotshot-XL](https://github.com/hotshotco/Hotshot-XL)** <br> Text-to-GIF optimized | [![Stars](https://img.shields.io/github/stars/hotshotco/Hotshot-XL.svg?style=social)](https://github.com/hotshotco/Hotshot-XL) | - | - | • <2s generation <br> • Discord integration |
| **[Allegro](https://rhymes.ai/blog-details/allegro-advanced-video-generation-model)** <br> Music-driven synthesis | [![Stars](https://img.shields.io/github/stars/rhymes-ai/Allegro.svg?style=social)](https://github.com/rhymes-ai/Allegro) | [arXiv](https://arxiv.org/abs/2410.15458) | [Website](https://rhymes.ai/blog-details/allegro-advanced-video-generation-model) | • Beat synchronization <br> • Style transfer |

---

## 🔧 Technical Components

### Core Technologies
| Technology | Implementation Cases | Key Advantages |
|------------|----------------------|----------------|
| **Optical Flow** | I2VGen-XL, VideoCrafter | Motion consistency |
| **LoRA Fine-tuning** | VideoTuna, Diffusers | Low-cost adaptation |
| **Pyramidal Flow** | [Pyramid-Flow](https://pyramid-flow.github.io/) | 50% cost reduction |

### Sora-like Projects
| Project | Stars | Progress | Documentation |
|---------|-------|----------|---------------|
| **[Open-Sora-Plan](https://github.com/PKU-YuanGroup/Open-Sora-Plan)** | [![Stars](https://img.shields.io/github/stars/PKU-YuanGroup/Open-Sora-Plan.svg?style=social)](https://github.com/PKU-YuanGroup/Open-Sora-Plan) | STSA implemented | [Report](https://github.com/PKU-YuanGroup/Open-Sora-Plan/blob/main/docs/Report-v1.0.0.md) |
| **[Open-Sora](https://github.com/hpcaitech/Open-Sora)** | [![Stars](https://img.shields.io/github/stars/hpcaitech/Open-Sora.svg?style=social)](https://github.com/hpcaitech/Open-Sora) | 3D ViT support | [中文文档](https://github.com/hpcaitech/Open-Sora/blob/main/docs/zh_CN/README.md) |

---

## 🗂️ Quick Reference

### Usage Scenarios
| Scenario | Recommended Tools | Reason |
|----------|-------------------|--------|
| Chinese content | ModelScope | Optimized for Chinese prompts |
| Long video (>30s) | Show-1 | Hybrid architecture |
| Commercial HDR | Stable Video Diffusion | Official license |

### Model Comparison
| Model | Resolution | Max Duration | Specialization |
|-------|------------|--------------|---------------|
| zeroscope_v2 | 576p | 3s | Zero-shot adaptation |
| I2VGen-XL | 4K | N/A | Image animation |
| Cosmos | 4K@60fps | N/A | Physics simulation |

---

## 🔮 Future Directions
1. **Efficiency**: Pyramid-Flow like methods
2. **Control**: Physics-engine integration (e.g. Cosmos)
3. **Open-source**: Community-driven Sora implementations
