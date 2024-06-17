# LSK3DNet: Towards Effective and Efficient 3D Perception with Large Sparse Kernels

![](figures/SDS.png)

>[LSK3DNet: Towards Effective and Efficient 3D Perception with Large Sparse Kernels](https://arxiv.org/abs/2403.15173) <br>
>[Tuo Feng](https://orcid.org/0000-0001-5882-3315), [Wenguan Wang](https://sites.google.com/view/wenguanwang), [Fan Ma](https://flowerfan.site/), [Yi Yang](https://scholar.google.com/citations?hl=zh-CN&user=RMSuNFwAAAAJ&view_op=list_works)
>

This is the official implementation of "LSK3DNet: Towards Effective and Efficient 3D Perception with Large Sparse Kernels" (Accepted at CVPR 2024).

## Abstract

Autonomous systems need to process large-scale, sparse, and irregular point clouds with limited compute resources. Consequently, it is essential to develop LiDAR perception methods that are both efficient and effective. Although naively enlarging 3D kernel size can enhance performance, it will also lead to a cubically-increasing overhead. Therefore, it is crucial to develop streamlined 3D large kernel designs that eliminate redundant weights and work effectively with larger kernels. In this paper, we propose an efficient and effective Large Sparse Kernel 3D Neural Network (LSK3DNet) that leverages dynamic pruning to amplify the 3D kernel size. Our method comprises two core components: Spatial-wise Dynamic Sparsity (SDS) and Channel-wise Weight Selection (CWS). SDS dynamically prunes and regrows volumetric weights from the beginning to learn a large sparse 3D kernel. It not only boosts performance but also significantly reduces model size and computational cost. Moreover, CWS selects the most important channels for 3D convolution during training and subsequently prunes the redundant channels to accelerate inference for 3D vision tasks. We demonstrate the effectiveness of LSK3DNet on three benchmark datasets and five tracks compared with classical models and large kernel designs. Notably, LSK3DNet achieves the state-of-the-art performance on SemanticKITTI (i.e., 75.6% on single-scan and 63.4% on multi-scan), with roughly 40% model size reduction and 60% computing operations reduction compared to the naive large 3D kernel model.


## Code

Coming soon......

## Citation

If you find this work useful in your research, please star our repository and consider citing:

```
@inproceedings{feng2024lsk3dnet,
  title={LSK3DNet: Towards Effective and Efficient 3D Perception with Large Sparse Kernels},
  author={Feng, Tuo and Wang, Wenguan and Ma, Fan and Yang, Yi},
  booktitle={CVPR},
  year={2024}
}
```

## Contact

Any comments, please email: feng.tuo@student.uts.edu.au.
