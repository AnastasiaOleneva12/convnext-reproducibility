# ConvNeXt Reproducibility

Reproducibility study of *Enhancing ConvNeXt for Efficient Small-Size Image Classification* (Feng et al., 2025).

The project investigates:

- Reproduction of the reported CIFAR-100 classification accuracy.
- Isolating the contribution of the modified patch embedding (stem).
- Comparison against ResNet with a matched parameter count.
- Evaluation protocol correctness and reproducibility across random seeds.

## Current status

The original implementation has been adapted for a modern Google Colab environment and tested on an NVIDIA Tesla T4.

A two-epoch smoke test completed successfully, reaching 11.91% Top-1 accuracy on CIFAR-100. Full reproduction experiments are planned.

## Project structure

- `prereg/` — pre-registration document.
- `notebooks/` — experiment notebooks.
- `environment/` — environment information and compatibility patches.
- `results/` — experimental metrics.

## Original implementation

https://github.com/southerly7/Proposed
