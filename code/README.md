# PL-DPO-NLL Code

Training and evaluation code will be released upon paper acceptance.

## Structure (Planned)
```
code/
├── train_pldpo.py          # Main training script
├── evaluate.py             # CARLA evaluation
├── models/
│   ├── lmdrive.py         # LMDrive base model
│   └── lora_adapter.py    # LoRA implementation
├── data/
│   └── pl_dataset.py      # Plackett-Luce dataloader
└── configs/
    └── pldpo_nll.yaml     # Training config
```

## Requirements
- Python 3.8+
- PyTorch 2.0+
- Transformers
- CARLA 0.9.10+

Stay tuned!
