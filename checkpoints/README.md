# Model Checkpoints

Pre-trained model weights will be released upon paper acceptance.

## Available Checkpoints (Planned)

| Model | Description | Size |
|-------|-------------|------|
| `pldpo_nll_best.pth` | Best performing PL-DPO-NLL model | ~500MB |
| `pldpo_baseline.pth` | PL-DPO without NLL | ~500MB |
| `sft_baseline.pth` | SFT baseline | ~500MB |

## Usage
```python
from models import LMDriveAgent

agent = LMDriveAgent.load_from_checkpoint("pldpo_nll_best.pth")
```

Stay tuned!
