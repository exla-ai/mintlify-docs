# InferX Documentation

[![Deployment Status](https://img.shields.io/badge/deployment-active-success)](https://exla.ai)

Official documentation for InferX - Open-source tool to run AI models on different devices with same API.

## Overview

This repository contains the documentation for InferX, built with [Mintlify](https://mintlify.com). InferX is an open-source tool that enables you to run AI models on different devices using the same API, with automatic hardware optimization.

## Features

- **Universal API**: Same code works across all supported hardware platforms
- **Hardware-Aware Optimization**: Automatically detects and optimizes for your specific device (NVIDIA Jetson, GPU, CPU)
- **Open Source**: Fully open-source with no tokens or authentication required
- **Easy Integration**: Drop-in replacement for existing model inference pipelines
- **Multi-Platform Support**: Works across different edge computing platforms

## Available Models

- **CLIP**: Multimodal image-text matching
- **RoboPoint**: Keypoint affordance prediction for robotics
- **SAM2**: Advanced image segmentation
- **MobileNet**: Efficient image classification
- **ResNet34**: High-accuracy image classification
- **Whisper**: Speech recognition and transcription
- **DeepSeek**: Large language model capabilities
- **InternVL2.5**: Advanced multimodal understanding

## Quick Start

```bash
# Install InferX
pip install git+https://github.com/exla-ai/InferX.git

# Use a model - same code works on any device
from inferx.models.clip import clip
model = clip()
results = model.inference(
    image_paths=["image1.jpg", "image2.jpg"],
    text_queries=["a photo of a dog", "a photo of a cat"]
)
```

## Development

To run the documentation locally:

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```

## Deployment

The documentation is automatically deployed to [https://exla.ai](https://exla.ai) when changes are pushed to the main branch.

## Community & Support

- **GitHub**: [github.com/exla-ai/InferX](https://github.com/exla-ai/InferX)
- **Email**: contact@exla.ai
- **Twitter**: [@exla_ai](https://x.com/exla_ai)
- **LinkedIn**: [Exla](https://linkedin.com/company/106019408) 
