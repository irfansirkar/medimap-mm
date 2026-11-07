# MediMap MM

Multimodal emergency diagnostics that read symptom notes together with X-ray and CT images.

**Live demo:** https://irfansirkar.github.io/medimap-mm/

Built by **Mohammad Irfan Sirkar** for **Expogenix 2025**.

## What the project does

In an emergency room, MediMap MM takes a free-text symptom note plus a chest X-ray or head CT. A medical vision-language model reads both together. It returns findings tagged by source (text, image or both), suggests a triage level, and supports follow-up chat.

## Original stack

- PyTorch and Hugging Face Transformers
- BiMediX2 (medical vision-language model)
- CUDA

## About this repository

This repository holds an interactive demo of the project. The demo runs entirely in the browser on GitHub Pages and uses built-in sample data, so it never needs a server, a GPU or an API key.

The demo has 3 sample cases: pneumonia, ischemic stroke and pneumothorax. The scans are drawn illustrations, not real patient images. **This demo is not a diagnosis and must not be used for medical decisions.**

The original project code is not included here.

## Run the demo locally

Open `index.html` in any browser. There is no build step.

## More projects

See the full portfolio at https://irfansirkar.github.io/PERSONAL-PORFOLIO-WEBSITE/
