# End-to-End-Text-to-SQL-Generator-using-Fine-Tuned-Llama-3-QLoRA

Fine-Tuned Large Language Models: Engineered a domain-specific LLM by fine-tuning Meta’s Llama-3-8B on the sql-create-context dataset to translate natural language into complex SQL queries.

Optimized Training Pipeline: Leveraged QLoRA (4-bit quantization) and PEFT to reduce model memory footprint by 70%, enabling training on a single T4 GPU without performance loss.

Custom Architecture Implementation: Implemented Low-Rank Adaptation (LoRA) logic (Rank=256, Alpha=128) to efficiently update only 1% of model parameters while freezing the backbone.

Evaluation & Deployment: Achieved 97.6% accuracy on test queries and built an interactive inference interface using Streamlit for real-time database querying.
