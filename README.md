# Seongwoo Lim

Undergraduate in Artificial Intelligence at **Kongju National University**

Undergraduate researcher, **Data Science with Deep Learning Lab**

I study how the structure of data can guide **representations, model architectures, and learning objectives**. My work began with multi-scale spatiotemporal forecasting and has expanded toward efficient video understanding and predictive representation learning. I am preparing to apply for master's programs.

## Research questions

- How should models represent and combine information at different spatial and temporal scales?
- Which information needs to be retained when computation or input length is limited?
- What do learned representations preserve, and how can controlled experiments reveal this?

My longer-term interest is in learning representations of environment states and dynamics that support **prediction and adaptation**. Future-state representation learning is a research direction I am working toward.

## Selected research and projects

### [MSF-ST: Multi-Scale Fusion Spatiotemporal Transformer](https://github.com/seongwo/multiscale-sst-forecasting)

**First-author research · Sea surface temperature forecasting**

SST contains both broad spatial patterns and local frontal structures. I investigated whether representing these structures at multiple scales improves forecasting. The method combines spatial scales **2, 4, 8, and 16**, factorized spatial–temporal Transformers, scale-wise predictions and fusion, and a gradient difference loss. Baseline comparisons and ablations examine the architectural choices.

### [SST representation learning](https://github.com/seongwo/predict-jepa)

**Ongoing research · State-JEPA and controlled reconstruction experiments**

I am investigating what SST representations retain before extending the study to future-state prediction. The current local implementation learns through **same-state spatial latent prediction**. A subsequent experiment freezes the encoder and compares a token-wise MLP decoder with the same decoder plus a zero-initialized residual spatial mixer, including random-encoder controls.

These are **same-state reconstruction experiments**; they do not yet establish future-state prediction or forecasting gains. The public repository currently contains the data and masking foundation; further implementation and experiment documentation are being prepared for release.

### [Video-language safety monitoring — ZroAct](https://github.com/seongwo/zroact-portfolio)

**Team capstone · AI Leader / modeling**

A two-stage system uses YOWOv3 action detection to summarize video as actions, bounding boxes, and temporal information, then passes this context alongside sampled frames to a small VLM. The question is how to retain useful temporal information when the VLM cannot process the full video directly.

My role focused on AI modeling, including prompt/component experiments and LoRA adaptation. The team built an end-to-end monitoring system; this repository presents the AI pipeline, serving components, and experiment records. Results belong to their specific model, prompt, and evaluation settings.

### [Korean AI-generated text detection](https://github.com/seongwo/text-deepfake-detection)

**Team competition project · 2025 SW-Centered University Digital Competition, AI Track**

The team addressed class imbalance, long text, and noisy labels using KoELECTRA-based classification, loss weighting, sampling, sliding-window inference, and score-level ensembles. **7th of 279 teams; Sponsored Company Award.** This repository is a fork of the team's code; the result and combined method are team achievements.

## Other research experience

- **Speech representation pooling:** explored VQ-based pooling of Wav2Vec 2.0 frame representations to reduce redundancy. Pretraining did not converge reliably under the available compute budget; this remains an exploratory study.
- **Emotion-aware dialogue:** used synthetic instruction data and Qwen2.5 with LoRA to jointly produce a response and an emotion state.
- **Infectious disease forecasting:** participated as a coauthor in a spatiotemporal bacterial gastroenteritis forecasting study. Publication details and component-level contributions will be added when confirmed.
- **On-device camera assistance:** an idea-stage competition project proposing language-guided camera parameter recommendations, lightweight visual analysis, and efficient deployment.

## Technical experience

**Python · PyTorch · Transformers · Spatiotemporal modeling · VLMs · LoRA · vLLM · Git / Linux**

Contact: [growingcow01@gmail.com](mailto:growingcow01@gmail.com)
