# NeurologyExploration
![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)


## Quick start
```bash
pip install neuroconnect[full]    # pulls torch-geometric & bctpy
neuroconnect download adh200      # ~2 GB
neuroconnect train config/adhd.yaml
neuroconnect evaluate runs/2025-05-12_baseline
