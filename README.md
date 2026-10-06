# customllm

## My Custom Shakespeare LLM: A Step-by-Step Guide

Welcome! This notebook showcases my custom **Generative Pre-trained Transformer (GPT)** built, trained, and evaluated from absolute scratch using PyTorch.

My custom model consists of **10.8 Million parameters** trained on the works of William Shakespeare. It is fully capable of generating unique, Shakespeare-like dialogue using creative sampling techniques!

This notebook breaks down how my custom model is configured and executed:

1. **Data Prep & Tokenization**: Converting raw text characters into integers that my network processes.
2. **Network Architecture**: Building my Transformer model block-by-block (Attention, MLP, LayerNorm).
3. **Training Setup**: Defining my training objective, optimizer, learning rate schedules, and data batching.
4. **The Training Loop**: Interactively training my model, logging loss values, and saving progress checkpoints.
5. **Text Generation (Inference)**: Loading my trained checkpoint and using top-k/temperature sampling to generate creative text.
