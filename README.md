# SK-Tree
Code for "SK-Tree: a systematic malware detection algorithmon streaming trees via the signature kernel"

## Overview

-----
-----

## Code

### Setup the Environment
To setup the environment, install the requirements with

+ `pip install -r requirements.txt`

-----

### Build CPU PDE solver (Cython)
Navigate into `src/` and run

+ `python setup.py build_ext --inplace`

### Run Experiments
The classification on the OpTC dataset can be found in `malware_detection_streaming_trees.ipynb`. 

## Citation

<!-- 

```bibtex
@article{cass2020computing,
  title={The Signature Kernel is the solution of a Goursat PDE},
  author={Salvi, Cristopher and Cass, Thomas and Lyons, Terry and Yang, Weixin},
  journal={arXiv preprint arXiv:2006.14794},
  year={2020}
}
```

-->
