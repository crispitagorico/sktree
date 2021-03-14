# SK-Tree
Code for "SK-Tree: a systematic malware detection algorithm on streaming trees via the signature kernel"

## Overview

Contrary to many other areas of data science, the development of effective machine learning algorithms in the cyber-security domain has not seen a dramatic escalation in
recent years, mainly because of the complex, hierarchical, sequential and multimodal nature of the data involved. In this paper we introduce the notion of streaming tree as a fairly generic data structure that encompasses a large portion of realworld data encountered in cyber-security. In particular, starting from host-based event logs we represent computer processes as streaming trees that evolve in continuous time. Leveraging the properties of the signature kernel, a machine learning tool that recently emerged as leading technology for learning with complex sequences of data, we develop the SK-Tree algorithm. SK-Tree is a supervised learning method for systematic malware detection on streaming trees that is robust to irregular sampling and high dimensionality of the underlying streams. We demonstrate the effectiveness of SK-Tree to detect malicious events on a portion of the DARPA OpTC dataset, achieving a AUROC score of 98%.


<p align="center">
    <img class="center" src="./pictures/trees_pic.jpg" width="800"/>
</p>


## Code

### Setup the Environment
To setup the environment, install sigkernel with

+ `pip install git+https://github.com/crispitagorico/sigkernel.git`

and the requirements with

+ `pip install -r requirements.txt`

Requires PyTorch >=1.6.0.

-----

### Run Experiments
The classification on the OpTC dataset can be reproduced running the jupyter notebook `SK_Tree_demo.ipynb`. 

## Citation

```bibtex
@article{cochrane2021sk,
  title={SK-Tree: a systematic malware detection algorithm on streaming trees via the signature kernel},
  author={Cochrane, Thomas and Foster, Peter and Chhabra, Varun and Lemercier, Maud and Salvi, Cristopher and Lyons, Terry},
  journal={arXiv preprint arXiv:2102.07904},
  year={2021}
}
```
