# Wiktor Zoga

I study Mathematics and Artificial Intelligence. I am interested in deep learning: how a model is trained, how inference works, and what changes its runtime and memory.

Most of this work is in PyTorch and Python. I also write C++.

## Projects

### [LLM Systems Lab](https://github.com/WiktorZoga/llm-systems-lab)

A GPT-style Transformer in PyTorch, with the training loop, gradient accumulation, activation checkpointing, and KV-cached generation. The checked-in scaling, attention, and memory measurements are from an M4 Mac on MPS. CUDA configs in the repo have not been run.

### [FI-2010 knowledge distillation](https://github.com/WiktorZoga/hft-knowledge-distillation)

Mid-price direction on the FI-2010 limit-order book. A reduced DeepLOB-style CNN/LSTM teacher is distilled into an MLP with a temperature-scaled KL loss. In the recorded test results the student is less accurate and has a lower single-sample forward latency. There is no student trained without distillation, so that gap is not a distillation gain. This is not a trading system.

### [Endometriosis lesion segmentation](https://github.com/WiktorZoga/endometriosis)

Binary segmentation of laparoscopic frames with U-Net, U-Net++, SwinUNETR, and a custom ResNet-50 multi-scale decoder. The `rt-detr` name is legacy and is not an RT-DETR model. Dice and IoU are on a 38-image test set. The split is image-level, so frames from the same video can land in different folds. This is not a clinical result.

I also spend time on coding agents, including how they can help with mathematical work.

[Personal site](https://wiktorzoga.com) · [X](https://x.com/WiktorZoga)
