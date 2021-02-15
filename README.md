# SK-Tree
Code for "SK-Tree: a systematic malware detection algorithmon streaming trees via the signature kernel"

## Overview

Contrary to many other areas of data science, the development of effective machine learning algorithms in the cyber-security domain has not seen a dramatic escalation in
recent years, mainly because of the complex, hierarchical, sequential and multimodal nature of the data involved. In this paper we introduce the notion of streaming tree as a fairly generic data structure that encompasses a large portion of realworld data encountered in cyber-security. In particular, starting from host-based event logs we represent computer processes as streaming trees that evolve in continuous time. Leveraging the properties of the signature kernel, a machine learning tool that recently emerged as leading technology for learning with complex sequences of data, we develop the SK-Tree algorithm. SK-Tree is a supervised learning method for systematic malware detection on streaming trees that is robust to irregular sampling and high dimensionality of the underlying streams. We demonstrate the effectiveness of SK-Tree to detect malicious events on a portion of the DARPA OpTC dataset, achieving a AUROC score of 98%.


<p align="center">
    <img class="center" src="./pictures/trees_pic.png" width="500"/>
</p>


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
