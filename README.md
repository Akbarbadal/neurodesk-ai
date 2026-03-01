# NeuroDesk AI – AMD Ryzen AI Hackathon Project

## Overview

NeuroDesk AI is a fully on-device productivity assistant powered by AMD Ryzen AI NPU (XDNA). It automates email drafting, document Q&A, meeting summarization, and task extraction without any cloud dependency.

All inference is designed to run locally using ONNX Runtime and INT4-quantized models, ensuring complete privacy, low latency, and zero per-query cost.

## Key Features

* Email Co-Pilot
* Document Q&A (Local RAG)
* Meeting Summarization
* Task Extraction
* Fully Offline Operation
* No API keys or cloud usage

## AMD Integration

* AMD Ryzen AI NPU (XDNA) for inference
* ONNX Runtime optimization
* Vitis AI for quantization
* ROCm for GPU-based embeddings

## Demo

Open the demo file:

```
NeuroDesk_AI_Demo.html
```

This browser prototype simulates the local ONNX inference workflow.

## Use Case

Designed for secure environments such as:

* Healthcare
* Legal
* Finance
* Air-gapped enterprise systems

## Future Work

* Full ONNX model integration
* Native desktop deployment
* Multi-language support
  
  Note: This browser prototype simulates the workflow. The production version runs fully on-device using ONNX Runtime optimized for AMD Ryzen AI NPU with no cloud dependency.
