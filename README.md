# Reference PyTorch GraphSAGE Implementation
### Author: William L. Hamilton


Basic reference PyTorch implementation of [GraphSAGE](https://github.com/williamleif/GraphSAGE).
This reference implementation is not as fast as the TensorFlow version for large graphs, but the code is easier to read and it performs better (in terms of speed) on small-graph benchmarks.
The code is also intended to be simpler, more extensible, and easier to work with than the TensorFlow version.

Currently, only supervised versions of GraphSAGE-mean and GraphSAGE-GCN are implemented. 

#### Requirements

Xiaokui update the code to run in the following environment:

- Python 3
- PyTorch 1.3
- no GPU in this version

#### Running examples

Run on Cora dataset: `python -m graphsage.model`.

Edit `graphsage/model.py` to enable the pubmed dataset.
