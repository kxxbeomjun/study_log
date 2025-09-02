# Study Log
Personal study log archiving summaries and notes of recent research papers.

## Notice
1. My primary research interest lies in **Autonomous Driving Perception**, particularly focusing on **BEV networks, VLM, LLM, and World Models**.  
2. I am also interested in **auxiliary techniques that can enhance perception models** (e.g., **Knowledge Distillation**, **Diffusion Models**, etc.).    
3. I continuously follow recent research in these areas, summarizing and organizing key insights in this repository.  

## Contents

### 2025
| Accept | Title | Field | Keyword | Paper | Code | My Study |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| ArXiv 2025 (TITS summit) | RESAR-BEV: An Explainable Progressive Residual Autoregressive Approach for Camera-Radar Fusion in BEV Segmentation | BEV Segmentation | Residual, Autoregressive | [ArXiv](https://arxiv.org/pdf/2505.06515) | - | [pdf](2025%20papers/ArXiv_2025_RESAR-BEV.pdf) |
| CVPR 2025 | Toward Real-world BEV Perception: Depth Uncertainty Estimation via Gaussian Splatting | BEV Segmentation | Depth Uncertainty, Gaussian | [ArXiv](https://arxiv.org/abs/2504.01957) | [Git](https://github.com/HCIS-Lab/GaussianLSS) | [pdf](2024%20papers/CVPR_2025_GaussianLSS.pdf) |
| CVPR 2025 | GaussianWorld: Gaussian World Model for Streaming 3D Occupancy Prediction | 3D Occupancy Prediction | World model, Gaussian | [ArXiv](https://arxiv.org/abs/2412.10373) | [Git](https://github.com/zuosc19/GaussianWorld) | [pdf](2024%20papers/CVPR_2025_GaussianWorld.pdf) |


---

### 2024
| Accept | Title | Field | Keyword | Paper | Code | My Study |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| AAAI 2024 | BEV-MAE: Bird's Eye View Masked Autoencoders for Point Cloud Pre-training in Autonomous Driving Scenarios | 3D Object Detection | Masked AutoEncoder | [ArXiv](https://arxiv.org/abs/2212.05758) | [Git](https://github.com/VDIGPKU/BEV-MAE) | [pdf](2024%20papers/AAAI_2024_BEV-MAE.pdf) |
| AAAI 2024 | VLM2Scene: Self-Supervised Image-Text-LiDAR Learning with Foundation Models for Autonomous Driving Scene Understanding | Foundation Model | SAM, CLIP, BLIP-2 | [Paper](https://ojs.aaai.org/index.php/AAAI/article/view/28121) | [Git](https://github.com/gbliao/VLM2Scene) | [pdf](2024%20papers/AAAI_2024_VLM2Scene.pdf) |
| CVPR 2024 | CRKD: Enhanced Camera-Radar Object Detection with Cross-modality Knowledge Distillation | 3D Object Detection | Cross modal KD | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Zhao_CRKD_Enhanced_Camera-Radar_Object_Detection_with_Cross-modality_Knowledge_Distillation_CVPR_2024_paper.html) | [Git](https://song-jingyu.github.io/CRKD/) | [pdf](2024%20papers/CVPR_2024_CRKD.pdf) |
| CVPR 2024 | Lift-Attend-Splat: Bird's-eye-view camera-lidar fusion using transformers | 3D Object Detection | LC Fusion | [ArXiv](https://arxiv.org/abs/2312.14919) | - | [pdf](2024%20papers/CVPR_2024_Lift-Attend-Splat.pdf) |
| CVPR 2024 | CLIP-KD: An Empirical Study of CLIP Model Distillation | Knowledge Distillation | CLIP, KD | [ArXiv](https://arxiv.org/pdf/2307.12732) | [Git](https://github.com/winycg/CLIP-KD) | [pdf](2024%20papers/CVPR_2024_CLIP-KD.pdf) |
| CVPR 2024 (Highlight) | Logit Standardization in Knowledge Distillation | Knowledge Distillation | Standardization | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Sun_Logit_Standardization_in_Knowledge_Distillation_CVPR_2024_paper.pdf) | [Git](https://github.com/sunshangquan/logit-standardization-KD) | [pdf](2024%20papers/CVPR_2024_Logit%20Standardization%20in%20KD.pdf) |
| CVPR 2024 | PromptKD: Unsupervised Prompt Distillation for Vision-Language Model | Knowledge Distillation | CLIP, KD | [ArXiv](https://arxiv.org/pdf/2403.02781) | [Git](https://github.com/zhengli97/PromptKD) | [pdf](2024%20papers/CVPR_2024_PromptKD.pdf) |
| CVPR 2024 | NeuRAD: Neural Rendering for Autonomous Driving | Rendering | Nerual Feature Field, SDF | [ArXiv](https://arxiv.org/pdf/2311.15260) | [Git](https://github.com/georghess/neurad-studio) | [pdf](2024%20papers/CVPR_2024_NeuRAD.pdf) |
| ECCV 2024 | LabelDistill: Label-guided Cross-modal Knowledge Distillation for Camera-based 3D Object Detection | 3D Object Detection | KD, Inverse Function | [ArXiv](https://arxiv.org/pdf/2407.10164) | [Git](https://github.com/sanmin0312/LabelDistill) | [pdf](2024%20papers/ECCV_2024_LabelDistill.pdf) |
| ECCV 2024 | MapDistill: Boosting Efficient Camera-based HD Map Construction via Camera-LiDAR Fusion Model Distillation | HD Map Construction | KD, Sim-LiDAR | [ArXiv](https://arxiv.org/pdf/2407.11682) | [Git](https://github.com/Ricky-Developer/MapDistill) | [pdf](2024%20papers/ECCV_2024_MapDistill.pdf) |
| ECCV 2024 | GaussianFormer: Scene as Gaussians for Vision-Based 3D Semantic Occupancy Prediction | 3D Occupancy Prediction | Gaussian | [ArXiv](https://arxiv.org/pdf/2403.02781) | [Git](https://github.com/huang-yh/GaussianFormer) | [pdf](2024%20papers/ECCV_2024_GaussianFormer.pdf) |
| ECCV 2024 | OccGen: Generative Multi-modal 3D Occupancy Prediction for Autonomous Driving | 3D Occupancy Prediction | Noise to Occupancy Prediction | [ArXiv](https://arxiv.org/pdf/2404.15014) | - | [pdf](2024%20papers/ECCV_2024_OCCGen.pdf) |
| NeurIPS 2024 | VQ-Map: Bird’s-Eye-View Map Layout Estimation in Tokenized Discrete Space via Vector Quantization | BEV Map Segmentation | VQ-VAE | [ArXiv](https://arxiv.org/pdf/2411.01618) | [Git](https://github.com/Z1zyw/VQ-Map) | [pdf](2024%20papers/NeurIPS_2024_VQ-Map.pdf) |
| NeurIPS 2024 | SAM-Guided Masked Token Prediction for 3D Scene Understanding | 3D Scene Understanding | Masked Token Prediction | [ArXiv](https://arxiv.org/pdf/2410.12158) | - | [pdf](2024%20papers/NeurIPS_2024_SAM-Guided%20Mask%20Token%20Prediction.pdf) |



---

### 2023 & earlier
| Accept | Title | Field | Keyword | Paper | Code | My Study |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| ICCV 2023 | UniTR: A Unified and Efficient Multi-Modal Transformer for Bird’s-Eye-View Representation | BEV Representation | Tokenizer, BEV Pooling | [ArXiv](https://arxiv.org/abs/2308.07732) | [Git](https://github.com/Haiyang-W/UniTR) | [pdf](2023%20%26%20ealiear%20papers/ICCV_2023_UniTR.pdf) |

