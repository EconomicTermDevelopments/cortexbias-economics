---
language:
- en
license: mit
task_categories:
- tabular-classification
tags:
- economics
- cortexbias
- computational-economics
- neuroeconomics
- emerging-terminology
pretty_name: Cortexbias Economics Dataset
size_categories:
- n<1K
---

# Cortexbias Economics Dataset

## Dataset Description
### Summary
Synthetic 200-row dataset for `Cortexbias` measurement and computational experiments.

### Supported Tasks
- Economic analysis
- Neuroeconomics research
- Computational economics

### Languages
- English (metadata and documentation)
- Python (code examples)

## Dataset Structure
### Data Fields
- `id`: Unique observation id
- `session`: Synthetic task session
- `prefrontal_control`: Deliberative control proxy
- `limbic_reactivity`: Affective reactivity proxy
- `stress_load`: Stress intensity
- `ambiguity_level`: Decision ambiguity level
- `decision_time_ms`: Decision latency (ms)
- `loss_aversion_ratio`: Estimated loss aversion
- `risk_premium_gap`: Gap from benchmark risk premium
- `cortexbias_index`: Composite term index

### Data Splits
- Full dataset: 200 examples

## Dataset Creation
### Source Data
Synthetic data generated for demonstrating Cortexbias applications.

### Data Generation
Channels are sampled from controlled distributions with correlated structure. The term index is computed from normalized channels and directional weights.

## Considerations
### Social Impact
Research-only synthetic data for method development and reproducibility testing.

## Additional Information
### Licensing
MIT License - free for academic and commercial use.

### Citation
@dataset{cortexbias2026,
title={{Cortexbias Economics Dataset}},
author={{Economic Research Collective}},
year={{2026}}
}
