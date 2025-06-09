# Efficient Code Auto-Completion
This project demonstrates how to deploy a quantized large language model (LLM) for **code auto-completion** on **resource-constrained devices** such as low-end GPUs or CPUs. By leveraging **quantization techniques** and **parameter-efficient fine-tuning (PEFT)**, we achieve high performance with reduced memory and compute requirements.

---

## Overview

- **Model**: [Phi-2](https://huggingface.co/microsoft/phi-2) (2.7B parameters)
- **Frameworks**: Hugging Face Transformers, PEFT (LoRA)
- **Optimization**: Quantization using `bitsandbytes`
- **Use Case**: Auto-completion of Python/JavaScript code snippets
- **Goal**: Run a capable LLM locally or on edge devices with minimal hardware

---

##  Key Features

-  **Quantized LLM** using 4-bit precision to reduce memory footprint  
-  **PEFT with LoRA** for efficient fine-tuning  
- Deployable in < 8 GB VRAM environments  
-  Script-based code completion for IDE or CLI integration  
-  Sample benchmarks for latency and memory usage

