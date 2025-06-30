# 🧠 createor-llm-ddata

This repository contains datasets curated for training, fine-tuning, and evaluating large language models (LLMs). The focus is on structured knowledge, creativity, and reasoning skills for LLM development.

## 📂 Dataset: `sk.jsnol`

This dataset is publicly available on the Hugging Face Hub. You can explore it directly in your browser via the embedded viewer below:

<iframe
  src="https://huggingface.co/datasets/sk16er/sk.jsnol/embed/viewer/default/train"
  frameborder="0"
  width="100%"
  height="560px"
></iframe>

Alternatively, you can visit the dataset directly here:  
🔗 [Hugging Face Dataset Page](https://huggingface.co/datasets/sk16er/sk.jsnol)

## 📑 Dataset Structure

- **Name**: `sk.jsnol`
- **Split**: `train`
- **Format**: Likely JSON or JSONL (based on the name)
- **Content**: Structured data for LLM training, including prompts, completions, or knowledge graph-style inputs.

## 📥 Usage

You can load the dataset in Python using the `datasets` library:

```python
from datasets import load_dataset

dataset = load_dataset("sk16er/sk.jsnol", split="train")
print(dataset[0])
