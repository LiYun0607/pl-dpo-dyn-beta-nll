# Plackett-Luce Preference Dataset

The 51K-sample preference dataset will be released upon paper acceptance.

## Dataset Statistics

| Scene Type | Samples | Percentage | Rejected Actions (K) | β Weight |
|------------|---------|------------|---------------------|----------|
| Turn | 20,528 | 40.2% | 3 | 0.40 |
| Normal | 14,220 | 27.8% | 2 | 0.12 |
| Should Brake | 7,497 | 14.7% | 3 | 0.25 |
| Should Slow | 3,090 | 6.0% | 2 | 0.20 |
| Junction | 2,845 | 5.6% | 2 | 0.18 |
| Pedestrian | 1,577 | 3.1% | 3 | 0.35 |
| Red Light | 1,367 | 2.7% | 3 | 0.35 |
| **Total** | **51,124** | 100% | - | - |

## Data Format
```json
{
  "prompt": "<navigation command + scene description>",
  "chosen": {"steering": 0.1, "throttle": 0.5, "brake": 0.0},
  "rejected": [
    {"action": {...}, "risk_level": "critical"},
    {"action": {...}, "risk_level": "high"},
    {"action": {...}, "risk_level": "medium"}
  ],
  "scene_type": "red_light",
  "beta": 0.35
}
```

Stay tuned!
