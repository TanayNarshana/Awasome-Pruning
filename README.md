# Awasome-Pruning [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

### Awasome Research Papers and other Resources in Neural Network Pruning. This collection is prepared inspired by [he-y/Awesome-Pruning](https://github.com/he-y/Awesome-Pruning).

| Notation  | Explanation | 
|:----------|:----------- |
|   `U`       |*Unstructured, Weight Pruning* |
|   `S`       |*Structured, Filter/Channel Pruning* |
|   `A`       |*Official/Author Implementation* |  
|   `O`       |*Unofficial/3rd Party Implementation* |  

## Conference
| Year   | Venue | Title | Type | Code |
|:------:|:-----:|:------|:----:|:----:|
| `2022`   | `CVPR`  | [When to Prune? A Policy towards Early Structural Pruning](https://arxiv.org/pdf/2110.12007v1.pdf) | `S` | |
| `2022`   | `ICLR`  | [Learning Pruning-Friendly Networks via Frank-Wolfe: One-Shot, Any-Sparsity, And No Retraining](https://openreview.net/forum?id=O1DEtITim__) | `U` | [PyTorch[A]](https://github.com/VITA-Group/SFW-Once-for-All-Pruning) |
| `2022`   | `ICLR`  | [SOSP: Efficiently Capturing Global Correlations by Second-Order Structured Pruning ](https://openreview.net/forum?id=t5EmXZ3ZLR) | `S` |  |
| `2022`   | `ICLR`  | [Revisit Kernel Pruning with Lottery Regulated Grouped Convolutions](https://openreview.net/forum?id=LdEhiMG9WLO) | `S` | [PyTorch[A]](https://github.com/choH/lottery_regulated_grouped_kernel_pruning) | 
| `2022`   | `ICLR`  | [Dual Lottery Ticket Hypothesis](https://openreview.net/forum?id=fOsN52jn25l) | `U` |[PyTorch[A]](https://github.com/yueb17/DLTH) | 
| `2020`   | `MLSys` | [Shrinkbench: What is the State of Neural Network Pruning?](https://arxiv.org/abs/2003.03033) | | [PyTorch[A]](https://github.com/JJGO/shrinkbench) |
| `2020`   | `CVPR`  | [HRank: Filter Pruning using High-Rank Feature Map](https://openaccess.thecvf.com/content_CVPR_2020/html/Lin_HRank_Filter_Pruning_Using_High-Rank_Feature_Map_CVPR_2020_paper.html) | `S` | [PyTorch[A]](https://github.com/lmbxmu/HRank) |
| `2020`   | `BMBS`  | [Similarity Based Filter Pruning for Efficient Super-Resolution Models](https://ieeexplore.ieee.org/abstract/document/9379712) | `S` |  |
| `2019`   | `ICLR` | [The Lottery Ticket Hypothesis: Finding Sparse, Trainable Neural Networks](https://openreview.net/forum?id=rJl-b3RcF7) | `U` | [PyTorch[A]](https://github.com/facebookresearch/open_lth) |
| `2019`   | `CVPR` | [Filter Pruning via Geometric Median for Deep Convolutional Neural Networks Acceleration](https://openaccess.thecvf.com/content_CVPR_2019/html/He_Filter_Pruning_via_Geometric_Median_for_Deep_Convolutional_Neural_Networks_CVPR_2019_paper.html) | `S` |[PyTorch[A]](https://github.com/he-y/filter-pruning-geometric-median) | 
| `2018`   | `IJCAI` | [Soft Filter Pruning for Accelerating Deep Convolutional Neural Networks](https://www.ijcai.org/proceedings/2018/0309.pdf) | `S` | [PyTorch[A]](https://github.com/he-y/soft-filter-pruning) | 
| `2018`   | `ICIP` | [Online Filter Clustering and Pruning for Efficient Convnets](https://ieeexplore.ieee.org/abstract/document/8451123) | `S` |  |
| `2017`   | `ICLR` | [Pruning Filters for Efficient ConvNets](https://openreview.net/forum?id=rJqFGTslg) | `S` | [PyTorch[O]](doc/PFEC.md) |


## Journal 

| Year  | Journal | Title | Type | Code |
|:------:|:-----:|:------|:----:|:----:|
| `2022`   | [Computational Intelligence and Neuroscience](https://www.hindawi.com/journals/cin/) | [Differentiable Network Pruning via Polarization of Probabilistic Channelwise Soft Masks](https://www.hindawi.com/journals/cin/2022/7775419/) | `S` |  | 
| `2022`   | [Journal of Systems Architecture](https://www.sciencedirect.com/journal/neural-networks) | [Optimizing deep neural networks on intelligent edge accelerators via flexible-rate filter pruning](https://www.sciencedirect.com/science/article/pii/S1383762122000303) | `S` | | 
| `2022`   | [Neural Networks](https://www.sciencedirect.com/journal/neural-networks) | [HRel: Filter pruning based on High Relevance between activation maps and class labels](https://www.sciencedirect.com/science/article/pii/S0893608021004962) | `S` | [PyTorch[A]*](https://github.com/sarvanichinthapalli/HRel) | 
| `2022`   | [Sensors](https://www.mdpi.com/journal/sensors) | [Filter Pruning via Measuring Feature Map Information](https://www.mdpi.com/1424-8220/21/19/6601) | `S` |  | 
| `2020`   | [IEEE Access](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6287639) | [Filter Pruning Without Damaging Networks Capacity](https://ieeexplore.ieee.org/document/9091183) | `S` |  | 
| `2020`   | [Electronics](https://www.mdpi.com/journal/electronics) | [Pruning Convolutional Neural Networks with an Attention Mechanism for Remote Sensing Image Classification](https://www.mdpi.com/2079-9292/9/8/1209) | `S` |  | 

### Other

|Year |Venue | Title | Type | Code |
|:----:|:---:|:------|:----:|:----:|
| | | Toolbox: Pruning channels for model acceleration | `S/U` | [PyTorch[A]](https://github.com/VainF/Torch-Pruning) |
| | | Toolbox: PyTorchViz | | [PyTorch[A] ](https://github.com/szagoruyko/pytorchviz) |
| | | [Simplify: A Python library for optimizing pruned neural networks](https://www.sciencedirect.com/science/article/pii/S2352711021001576) | | [PyTorch[A] ](https://github.com/
EIDOSlab/simplify) |
