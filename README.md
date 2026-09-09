# AI Research & Development

My personal repository focused on rigorous, mathematically grounded implementations of LLMs, VLMs, and World Models — bypassing high-level abstractions in favor of first-principles understanding. This personal learning serves as the foundation for the R&D projects I carry out at NAMETA Labs.

---

## Implementations

### Core Architectures

| Directory                  | Description                         |
| -------------------------- | ----------------------------------- |
| `LLM_GPT_2_from_scratch/`  | GPT-2 from scratch (Raschka-based)  |
| `LLM_gemma_from_scratch/`  | Gemma architecture in native Python |
| `LLM_qwen_3_from_scratch/` | Qwen 3 in PyTorch                   |

### Transformer Primitives

| File                             | Description                               |
| -------------------------------- | ----------------------------------------- |
| `SELF_ATTENTION_FROM_SCRATCH.PY` | Scaled dot-product self-attention         |
| `ROPE.PY`                        | Rotary Positional Embeddings (RoPE)       |
| `ROPE_MLA.ipynb`                 | RoPE + Multi-Latent Attention exploration |

### Vision-Language Models

| Directory                    | Description                      |
| ---------------------------- | -------------------------------- |
| `VLM_clip_style_nanovlm/`    | CLIP-style VLM                   |
| `VLM_paligema_from_scratch/` | PaLiGemma-style VLM from scratch |

---

## Computer Vision Projects

| Project                                                                                                                               | Description                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Football Match Analysis](https://github.com/MuhammadZakiAhmad/FootBallAnalysisCVProject)                                             | Object detection, multi-object tracking, team assignment via K-Means clustering, and real-time ball possession analysis on match video. Uses YOLOv8 for detection and ByteTrack for tracking. |
| [Virtual Try-On (Digital Mannequin)](https://github.com/MuhammadZakiAhmad/DigitalMannequinForOnlineShops)                             | Generates a 3D digital model from user-uploaded photos for virtual clothing try-on, with motion visualization and a customizable catalog. Targets reduction of return rates in e-commerce.    |
| [AI Physiotherapy Trainer](https://github.com/MuhammadZakiAhmad/AITrainer-CV-Application-)                                            | Real-time pose estimation for patient exercise monitoring. Detects and tracks human poses to count repetitions and provide live feedback during physiotherapy sessions.                       |
| [Smart Car Detection & Counting](https://github.com/MuhammadZakiAhmad/cvProject2_carCounterUsingYOLOv8)                               | Defines a Region of Interest for vehicle counting, applies object tracking, and visualizes counts in real time using YOLOv8.                                                                  |
| [Automatic Number Plate Recognition (ANPR)](https://github.com/MuhammadZakiAhmad/ANPRUsingYOLOv8)                                     | Detects vehicles, localizes license plates, reads plate numbers via OCR, and logs the data. Combines detection, tracking, and text recognition in a single pipeline.                          |
| [Human Emotion Detection](https://github.com/MuhammadZakiAhmad/HumanEmotionDetection)                                                 | Image classifier trained from scratch on FER-2013 (48×48 grayscale faces) to recognize seven emotions: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.                               |
| [Chest Cancer Classification (MLflow + DVC)](https://github.com/MuhammadZakiAhmad/EndToEndChestCancerClassificationUsingMlflowAndDVC) | End-to-end ML pipeline for chest cancer classification from images, with a user-facing upload interface. Covers experiment tracking, data versioning, and cloud deployment.                   |

### Computer Vision Stack

`YOLOv8 · ByteTrack · K-Means · OpenCV · Supervision · Pandas · PyTorch3D · PyTorch · Unity · C# · Mediapipe · EasyOCR · SORT · TensorFlow · Keras · NumPy · Matplotlib · MLflow · DVC · DagsHub · AWS · GitHub Actions`

---

**Stack:** Python · PyTorch · TensorFlow
