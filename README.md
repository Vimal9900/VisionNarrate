VisionNarrate
VisionNarrate is an AI-powered image understanding system crafted for the visually impaired. It goes beyond simple object recognition by incorporating context, relationships, actions, and emotions to convert images into rich, dynamic narratives.

Table of Contents
Overview

Key Features

Methodology

Datasets & Evaluation

Limitations & Impact

Future Work

References

License

Overview
The system bridges the gap between basic object detection and human-like interpretation by delivering context-aware and emotionally resonant image descriptions. VisionNarrate enhances accessibility, allowing visually impaired users to experience visual content more comprehensively.

Key Features
Dynamic Narratives: Generates detailed and emotionally enriched descriptions.

Advanced Integration: Utilizes large vision-language models based on the BLIP architecture.

User-Centric Design: Tailors descriptions to improve real-world accessibility.

Methodology
VisionNarrate is built on three main approaches using the BLIP architecture:

Custom Transformer Decoder:

Uses a pre-trained BLIP encoder combined with a custom Transformer decoder for fine-grained narrative generation.

Fine-Tuning:

End-to-end fine-tuning of the BLIP model on a custom dataset with standard metrics (BLEU, METEOR, ROUGE, BERTScore) for evaluation.

Caption-Enhanced Fine-Tuning:

Merges detailed descriptions with concise captions using special tokens to improve semantic richness and narrative alignment.

Datasets & Evaluation
Datasets:

IIW Dataset: Real-world images with intrinsic decomposition for varied lighting.

CM-3600 Dataset: High-quality 360-degree images with detailed captions.

Evaluation Metrics:

Metrics include BLEU, METEOR, ROUGE, and BERTScore.

VisionNarrate’s caption-enhanced model (VN-CEST) outperforms the baseline ContextCam model across these metrics.

Limitations & Impact
Limitations:

Challenges remain with abstract scenes and potential biases from pre-trained models.

Real-time performance on resource-limited devices is an ongoing area of research.

Broader Impact:

Enhances accessibility for the visually impaired and democratizes visual content.

Ethical considerations include ensuring privacy, avoiding over-reliance on AI, and mitigating unintended emotional misinterpretations.

Future Work
Enhanced Contextual Understanding: Incorporate multimodal data and external knowledge.

Bias Mitigation: Improve fairness through diverse datasets and debiasing techniques.

Real-time Deployment: Optimize for mobile and edge device performance.

Personalization & Multilingual Support: Enable interactive feedback and support for multiple languages.

References
Baig, M. S. A. et al., 2024. AI-based wearable vision assistance system. arXiv:2412.20059.

Chen, R., Wang, L. & Zhang, H., 2024. Leveraging large vision-language models for image descriptions. arXiv:2407.11300.

Li, X., Zhao, M. & Chen, L., 2024. Contextual emotion detection in images. Front. AI, 7, 1386753.

Smith, A., Johnson, E. & Lee, K., 2024. ContextCam: Bridging context awareness with human-AI collaboration. ACM CHI 2024.

Yang, B. et al., 2024. Viassist: Adapting multi-modal language models for visual impairments. arXiv:2404.02508.

Zhang, W., Liu, Y. & Wang, P., 2024. Emotion contextual fusion network for emotion recognition. Procedia CS, 215, 123–130.

License
Distributed under the MIT License. See the LICENSE file for details.
