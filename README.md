# [A Comparative Study of K-Planes vs. V-PCC for 6-DoF Volumetric Video Representation](https://dl.acm.org/doi/abs/10.1145/3652212.3652227)

### Overview
With NeRF, neural scene representations have gained increased popularity in recent years. To date, many models have been designed to represent dynamic scenes that can be explored in 6 degrees-of-freedom (6-DoF) in immersive applications such as virtual reality (VR), augmented reality (AR), and mixed reality (MR). In this paper, we aim to evaluate how newer neural representations of 6-DoF video compare with more-traditional point cloud-based representations in terms of their representation and transmission efficiency. We design a new methodology for fair comparison between K-Planes, anew dynamic neural scene representation model, and video-based point cloud compression (V-PCC). We conduct extensive experiments using three datasets with a total of 11 sequences with different characteristics. Results show that the current K-Planes models excel for moderately dynamic content, but struggle with highly dynamic scenes. In addition, in emulated volumetric data capture scenarios, the recorded point cloud data can be highly noisy, and the visual quality of views rendered by trained K-Planes models are significantly better than V-PCC.

## Citations

If you find our code or paper helps, please consider citing:
```sh
@inproceedings{li2024comparative,
  title={A Comparative Study of K-Planes vs. V-PCC for 6-DoF Volumetric Video Representation},
  author={Li, Na and Zhu, Mufeng and Wang, Shuoqian and Liu, Yao},
  booktitle={Proceedings of the 16th International Workshop on Immersive Mixed and Virtual Environment Systems},
  pages={92--98},
  year={2024}
}
```
