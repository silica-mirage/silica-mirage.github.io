<p align="center">
<h1 align="center"><strong>SILICA: Project Website</strong></h1>
  <p align="center">
    <strong>IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2026</strong><br>
    <br>
    <a href="https://www.linkedin.com/in/rtarun1/" target="_blank">Tarun R</a>, 
    <a href="https://scholar.google.com/citations?user=KI2RjboAAAAJ&hl=en" target="_blank">Anuj Verma</a>, 
    <a href="https://scholar.google.com/citations?user=XCF-6gcAAAAJ&hl=en" target="_blank">Laksh Nanwani</a>, 
    <a href="https://scholar.google.com/citations?user=oVS3HHIAAAAJ&hl=en" target="_blank">Sourav Garg</a>,  
    <a href="https://scholar.google.co.in/citations?user=QDuPGHwAAAAJ&hl=en" target="_blank">K. Madhava Krishna</a>
    <br>
    Robotics Research Center (RRC), IIIT Hyderabad, India
    <br>
  </p>
</p>

<div id="top" align="center">

[![Project](https://img.shields.io/badge/Project-Website-pink?logo=googlechrome&logoColor=white)](https://silica-mirage.github.io/)
[![Main Repo](https://img.shields.io/badge/GitHub-Codebase-black?logo=github&logoColor=white)](https://github.com/rtarun1/Silica)
[![arXiv](https://img.shields.io/badge/arXiv-Paper-b31b1b?logo=arxiv&logoColor=white)](https://arxiv.org/abs/2607.24249)
[![Model](https://img.shields.io/badge/🤗%20Silica-Model-yellow)](https://huggingface.co/rtarun1/silica-v1-0)
[![Dataset](https://img.shields.io/badge/🤗%20Mirage18k-Dataset-green)](https://huggingface.co/datasets/rtarun1/mirage18k/)

</div>

## 📖 About This Repository

This repository contains the source code for the official project website of **SILICA: Repurposing Diffusion Priors for Joint Glass Segmentation and Depth Estimation**. 

SILICA leverages the priors of text-to-image diffusion models to jointly predict glass segmentation and glass-aware depth. This mutual information exchange establishes a robust spatial hierarchy, entirely eliminating the need for paired real-world glass depth annotations. We use the predicted segmentation mask to explicitly filter incorrect glass depth points from standard sensors, recovering accurate metric glass depth for downstream 3D mapping and autonomous collision avoidance.

**Note:** For the actual model implementation, training scripts, and ROS2 deployment code, please visit our **[Main Codebase Repository](https://github.com/rtarun1/Silica)**.



## 🔗 Citation

If you find our work useful in your research, please consider citing our paper:

```bibtex
@misc{r2026silicarepurposingdiffusionpriors,
      title={SILICA: Repurposing Diffusion Priors for Joint Glass Segmentation and Depth Estimation}, 
      author={Tarun R and Anuj Verma and Laksh Nanwani and Sourav Garg and K. Madhava Krishna},
      year={2026},
      eprint={2607.24249},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2607.24249}
}
```