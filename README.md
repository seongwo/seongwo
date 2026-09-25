# Seong-U IM

I'm an undergraduate in Artificial Intelligence at **Kongju National University** and a student researcher in the **Data Science with Deep Learning Lab**.

My research focuses on spatiotemporal modeling and representation learning. I am interested in how a model should represent information at different scales, and what it can retain when input length or computation is limited.

## Research

### [MSF-ST · Multi-Scale SST Forecasting](https://github.com/seongwo/multiscale-sst-forecasting)

*First-author research*

Sea surface temperature contains both broad regional changes and local temperature fronts. I studied a multi-scale Transformer that represents these structures at different resolutions and combines their forecasts. The work includes scale and component ablations, baseline comparisons, and a gradient difference loss for preserving spatial structure.

[Method](https://github.com/seongwo/multiscale-sst-forecasting/blob/public-release/docs/method.md) · [Experiments](https://github.com/seongwo/multiscale-sst-forecasting/blob/public-release/docs/experiment_record.md)

### [SST Representation Learning · State-JEPA](https://github.com/seongwo/predict-jepa)

*Ongoing research*

I am now studying what an SST encoder retains in its representations. In a recent experiment, I froze the encoder and compared the same MLP decoder with and without a small spatial mixer, keeping the initial outputs and evaluation data matched.

The mixer improved reconstruction from pretrained features, but random encoders still reconstructed pixels more accurately. This has led me to examine the difference between recovering an input and learning features useful for prediction. Future-state prediction is the next research direction.

[Experiment and controls](https://github.com/seongwo/predict-jepa/blob/experiment/state-jepa/docs/experiments/frozen_decoder_spatial_mixer.md) · [Available code](https://github.com/seongwo/predict-jepa#current-release-and-research-status)

## Projects

### [ZroAct · Video-Language Safety Monitoring](https://github.com/seongwo/zroact-portfolio)

*Team capstone · AI Leader / modeling*

We combined action detection with a small vision-language model for CCTV safety monitoring. Action and temporal context accompany sampled frames, giving the VLM information beyond the images alone. My work focused on AI modeling, prompt/component experiments, and LoRA adaptation. The repository contains the AI pipeline, serving interface, and experiment records.

### [Korean AI-Generated Text Detection](https://github.com/seongwo/text-deepfake-detection)

*Team project · 2025 SW-Centered University Digital Competition, AI Track*

Our team used KoELECTRA, loss weighting, sampling, windowed inference, and ensembles to address imbalanced labels and long texts. We placed **7th out of 279 teams** and received a **Sponsored Company Award**. The linked repository is my fork of the team's code.

## Earlier work

- **Speech representation pooling:** explored VQ-based pooling of Wav2Vec 2.0 features. Pretraining did not converge reliably within the available compute budget.
- **Emotion-aware dialogue:** fine-tuned Qwen2.5 with LoRA on synthetic instruction data to generate a response and an emotion state.
- **Infectious disease forecasting:** contributed as a coauthor to a spatiotemporal bacterial gastroenteritis forecasting study.
- **Camera assistance:** proposed language-guided camera parameter recommendations in an idea-stage competition project.

I mainly work with **Python and PyTorch**. My project experience also includes LoRA, vLLM, Git, and Linux.

[Email](mailto:growingcow01@gmail.com)
