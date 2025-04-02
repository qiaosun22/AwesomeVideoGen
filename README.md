# AwesomeVideoGen

# Open-source Video Generation Toolboxes & Foundation Models

**Definition**:  
A collection of open-source frameworks and pre-trained foundation models for video synthesis/editing tasks, covering text-to-video, image-to-video, and video-to-video transformation technologies.

---

## 📦 Toolboxes

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
