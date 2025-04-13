├── configs/              # Training configurations
│   ├── base.yaml         # Hyperparameter settings
│   └── adversarial.yaml # Adversarial training params
├── data_loader/          # Dataset processing modules
├── models/               # Model architectures
│   ├── bert_base.py      # Standard BERT implementation
│   └── lora_adapter.py   # LoRA adaptation layers
├── trainers/             # Training workflows
├── evaluators/           # Evaluation metrics
│   ├── accuracy.py       # Detection performance
│   └── hallucination.py  # Hallucination metrics
