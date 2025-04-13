# VisionNarrate

VisionNarrate is an AI-powered image understanding system crafted for the visually impaired. It goes beyond basic object detection by incorporating context, relationships, actions, and emotions to convert images into rich, dynamic narratives.

## Table of Contents

- [Overview](#overview)
- [Key Features](#key-features)
- [Methodology](#methodology)
- [Datasets & Evaluation](#datasets--evaluation)
- [Limitations & Impact](#limitations--impact)
- [Future Work](#future-work)
- [References](#references)
- [License](#license)

## Overview

VisionNarrate bridges the gap between simple object recognition and human-like interpretation by delivering context-aware, emotionally resonant image descriptions. This project enhances accessibility, enabling visually impaired users to experience visual content more comprehensively.

## Key Features

- **Dynamic Narratives:** Generates detailed, emotionally enriched descriptions.
- **Advanced Integration:** Leverages large vision-language models based on the BLIP architecture.
- **User-Centric Design:** Tailored to improve accessibility for the visually impaired.

## Methodology

VisionNarrate employs three main approaches built upon the BLIP architecture:

1. **Custom Transformer Decoder:**  
   - Utilizes a pre-trained BLIP encoder paired with a custom Transformer decoder for precise narrative generation.

2. **Fine-Tuning:**  
   - Fine-tunes the BLIP model end-to-end on a custom dataset, evaluating performance using metrics such as BLEU, METEOR, ROUGE, and BERTScore.

3. **Caption-Enhanced Fine-Tuning:**  
   - Merges detailed descriptions with concise captions (using special tokens) to improve semantic richness and narrative alignment.

## Datasets & Evaluation

- **Datasets:**
  - *IIW Dataset:* Offers real-world images with intrinsic decomposition for varied lighting conditions.
  - *CM-3600 Dataset:* Contains high-quality 360-degree images along with detailed captions.

- **Evaluation Metrics:**
  - Metrics include BLEU, METEOR, ROUGE, and BERTScore.
  - VisionNarrate’s caption-enhanced model outperforms the baseline ContextCam model across these metrics.

## Limitations & Impact

- **Limitations:**
  - Challenges remain with abstract or highly symbolic scenes.
  - Inherited biases from pre-trained models and real-time performance on low-resource devices require further research.

- **Broader Impact:**
  - Enhances visual content accessibility for the visually impaired.
  - Addresses ethical considerations such as privacy, over-reliance on AI, and potential misinterpretations of emotion.

## Future Work

- **Enhanced Contextual Understanding:** Integrate multimodal data and external knowledge sources.
- **Bias Mitigation:** Employ debiasing strategies and incorporate diverse datasets.
- **Real-time Deployment:** Optimize for efficiency on mobile and edge devices.
- **Personalization & Multilingual Support:** Implement interactive feedback loops and support multiple languages.

## References

- **Baig, M. S. A. et al. (2024):** *AI-based wearable vision assistance system* [arXiv:2412.20059](https://arxiv.org/abs/2412.20059)
- **Chen, R., Wang, L. & Zhang, H. (2024):** *Leveraging large vision-language models for image descriptions* [arXiv:2407.11300](https://arxiv.org/abs/2407.11300)
- **Li, X., Zhao, M. & Chen, L. (2024):** *Contextual emotion detection in images* - Frontiers in Artificial Intelligence, 7, 1386753.
- **Smith, A., Johnson, E. & Lee, K. (2024):** *ContextCam: Bridging context awareness with human-AI collaboration* - ACM CHI 2024.
- **Yang, B. et al. (2024):** *Viassist: Adapting multi-modal language models for visual impairments* [arXiv:2404.02508](https://arxiv.org/abs/2404.02508)
- **Zhang, W., Liu, Y. & Wang, P. (2024):** *Emotion contextual fusion network for emotion recognition* - Procedia Computer Science, 215, 123–130.

## License

Distributed under the MIT License. See the [LICENSE](LICENSE) file for more details.
