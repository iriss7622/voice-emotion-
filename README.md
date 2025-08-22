# voice-emotion-
🎤✨ Voice-Driven Emotion Visualization | 基于Whisper与Librosa的语音情绪可视化UI研究。将语音实时转化为动态声波色彩
# 🎤 Voice-Emotion Visualization UI

> **AI赋能的语音情绪可视化交互系统 | 毕业设计/作品集项目**

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue)](https://www.python.org/)
[![Librosa](https://img.shields.io/badge/Librosa-Audio%20Analysis-green)](https://librosa.org/)
[![Whisper](https://img.shields.io/badge/OpenAI-Whisper-9cf)](https://openai.com/index/whisper/)

**🌐 在线体验 **

将语音实时转化为动态的色彩与波形，让情感“看得见”。本项目探索了AI语音识别与UI动效结合的情感化设计新思路。

---

## ✨ 项目亮点

- **🎨 情感可视化**: 将兴奋、平静、悲伤等情绪映射为独特的色彩与动态声波。
- **⚡ 实时交互**: 基于Web Audio API，实现用户语音输入的实时分析与反馈。
- **🤖 多模态分析**: 结合Whisper的文本语义分析与Librosa的声学特征分析，提升准确率。
- **📱 UI/UX驱动**: 设计为先，所有技术为提升用户体验服务。

## 🛠 技术栈

| 领域 | 技术工具 |
|:---|:---|
| **语音转文本** | OpenAI Whisper |
| **音频特征分析** | Librosa |
| **情绪分析** | Transformers (BERT) |
| **前端可视化** | Three.js / Canvas API |
| **后端处理** | Python (Flask) |
| **设计工具** | Figma, ProtoPie, After Effects |

## 📁 项目结构

```bash
voice-emotion-ui/
├── audio_processing/    # 核心音频处理脚本
│   ├── whisper_transcribe.py   # 语音转文本
│   ├── extract_features.py     # 提取声学特征
│   └── emotion_analysis.py     # 情绪分析
├── static/              # 前端静态资源
│   ├── js/              # Canvas/Three.js可视化脚本
│   └── css/             # 样式文件
├── app.py               # Flask主应用
├── requirements.txt     # Python依赖列表
└── README.md           # 项目说明
```

## 🚀 快速开始

1. **克隆项目**
   ```bash
   git clone https://github.com/yourname/voice-emotion-ui.git
   cd voice-emotion-ui
   ```

2. **安装依赖**
   ```bash
   pip install -r requirements.txt
   ```

3. **运行演示**
   ```bash
   python app.py
   ```
   访问 `http://localhost:5000` 体验效果。

## 📊 数据分析

本项目基于对75段语音样本的声学特征分析，关键发现：

| 特征维度 | 激动语音均值 | 平静语音均值 | 差异显著性 |
|:---|:---:|:---:|:---:|
| **音量(dB)** | 78.2 ± 3.5 | 56.7 ± 4.2 | p < 0.001 |
| **基频(Hz)** | 285 ± 35 | 185 ± 28 | p < 0.001 |

*详细研究过程请见我的作品集文档*

## 🎨 设计理念

> "我们不止关注AI*识别了什么*，更关注如何将结果*优雅地呈现*给用户。"
> - 通过**置信度驱动**的视觉映射：高置信度显示鲜明动效，低置信度保持中性。
> - 遵循**情感化设计**三层次理论：本能层（视觉）- 行为层（交互）- 反思层（情感共鸣）。

![情绪映射设计规范](https://example.com/design-spec.png)
## 联系
欢迎交流讨论！如果您有任何问题或建议：
- 📧 Email:2081560346@qq.com
> 此项目为设计作品集项目，重点展示技术理解与设计落地能力。代码仅供参考学习。
