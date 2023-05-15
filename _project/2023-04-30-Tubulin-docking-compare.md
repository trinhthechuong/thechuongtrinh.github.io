---
title: "Graph Neural Network for ALK inhibitors"
excerpt: "This is a repository containing one part of Le Lai Hoang Son's thesis <br/><img src='/images/Tubulin-docking/score_distribution.png'>"
collection: project
---


# Abstract
Updating...

## Workflow
- Automated docking results extraction - six types of docking softwares
- Retrospective control for 4 types of docking scores (min, max, mean, median) - internal validation in one software
- Comparison among six types of molecular docking softwares


## Requirements

This module requires the following modules:

- [RDkit](https://www.rdkit.org/)
- [scikit-learn](https://scikit-learn.org/stable/)
- [Autodock-GPU](https://github.com/ccsb-scripps/AutoDock-GPU)
- [Vina-GPU](https://github.com/DeltaGroupNJUPT/Vina-GPU)
- [Autodock vina](https://github.com/ccsb-scripps/AutoDock-Vina)
- [smina](https://github.com/mwojcikowski/smina)
- [qvina2](https://qvina.github.io/)
- [gnina](https://github.com/gnina/gnina)

## Installation
Clone this repository to use

## Note
Updating...

## Folder segmentation

Finally the folder structure should look like this:

    Mol2DSimi (project root)
    |__  README.md
    |__  DockValid
    |__  |__ crawl_score.py (not published)
    |    |__ internal_valid.py
    |    |__ validation_compare.py
    |    |__ validation_process.py
    |__  Image (saved images)
    |__  LICENSE
    |......

# Usage

```python
```

## Contributing

Please visit the [Docking-Tubulin](https://github.com/TieuLongPhan/Tubulin_comparedocking) repository.
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. Please make sure to update tests as appropriate.

