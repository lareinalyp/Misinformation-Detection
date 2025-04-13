This repository presents a novel two-stage adaptation framework for health misinformation detection, combining BERT fine-tuning with Low-Rank Adaptation (LoRA) optimization to address the reliability-security paradox in large language models.  Our implementation systematically evaluates model hallucination patterns through adversarial training protocols and real-world query simulations.  The pipeline processes raw text inputs through domain-specific preprocessing, applies progressive parameter-efficient tuning (standard fine-tuning → LoRA adaptation), and outputs both classification results and hallucination risk scores.  Experimental results demonstrate measurable improvements over baseline models, achieving 51% detection accuracy while reducing hallucination frequency to 1% through our proposed hybrid training approach.  The modular code structure enables reproducibility of key findings and adaptation to related NLP tasks requiring reliability-aware model optimization.
