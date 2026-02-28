<h1 align="center">Awesome 3D Reconstruction and Generation</h1>

<p align="center">
    <a href="" alt="">
        <img src="https://img.shields.io/github/commit-activity/m/PolySummit/Awesome-3D-Reconstruction-and-Generation?colorB=b74e45" /></a>
    <a href="" alt="">
        <img src="https://img.shields.io/github/last-commit/PolySummit/Awesome-3D-Reconstruction-and-Generation?colorB=54b345" /></a>
</p>

🌟 A curate list of papers, datasets, and projects for 3D Reconstruction and Generation.

:heart: Pull requests or issues for updates are very welcome.

## 📖 Contents
- [🧊 3D Reconstruction](#reconstruction)
    - [Feedforward Recon](#reconstruction-class1)
    - [Efficient 3D Vision Transformers](#reconstruction-class1b)
    - [Few-Shot Generated Recon](#reconstruction-class2)
    - [3D Recon-based SLAM & SFM](#reconstruction-class3)
- [🧸 Physical Object Generation](#physics)
- [🤖 Articulated Object Generation and Reconstruction](#articulate)
- [🕺 Human Motion Generation](#human-motion)
    - [Human-Scene Interaction](#human-motion-class1)
    - [Human-Scene Reconstruction](#human-motion-class2)
- [🏠 Indoor Scene Layout Generation](#layout)
- [🏠 Any-to-3D Scene](#any-to-3d)
- [🌟 Star History](#star)


## <span id="reconstruction">🧊 3D Reconstruction</span>

### <span id="reconstruction-class1">Feedforward Recon</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [Emergent Extreme-View Geometry in 3D Foundation Models](https://arxiv.org/abs/2411.18311) | 11/2025 | [project](https://ext-3dfms.github.io/) | CVPR 2026 |
| [Emergent Outlier View Rejection in Visual Geometry Grounded Transformers](https://arxiv.org/abs/2512.04012) | 12/2025 | [project](https://cvlab-kaist.github.io/RobustVGGT) | CVPR 2026 |
| [AMB3R: Accurate Feed-forward Metric-scale 3D Reconstruction with Backend](https://arxiv.org/abs/2411.17851) | 11/2025 | [project](https://hengyiwang.github.io/projects/amber) | CVPR 2026 |
| [Depth Anything 3: Recovering the Visual Space from Any Views](https://arxiv.org/abs/2511.10647) | 11/2025 | [project](https://depth-anything-3.github.io/) | ICLR 2026 |
| [Dens3R: A Foundation Model for 3D Geometry Prediction](https://arxiv.org/abs/2505.15011) | 2025 |  | ICLR 2026 |
| [WorldMirror: Universal 3D World Reconstruction with Any-Prior Prompting](https://arxiv.org/abs/2510.09015) | 10/2025 |  | arXiv |
| [PAGE-4D: Disentangled Pose and Geometry for 4D Perception](https://arxiv.org/abs/2510.17568) | 10/2025 |  | ICLR 2026 |
| [DriveVGGT: Visual Geometry Transformer for Autonomous Driving](https://arxiv.org/abs/2511.18108) | 11/2025 |  | ECCV 2025 |
| [π3: Scalable Permutation-Equivariant Visual Geometry Learning](https://arxiv.org/abs/2507.00613) | 07/2025 |  | CVPR 2025 |
| [BoxFusion: Reconstruction-Free Open-Vocabulary 3D Object Detection](https://arxiv.org/abs/2506.14736) | 06/2025 |  | arXiv |
| [Depth Anything with Any Prior](https://arxiv.org/abs/2505.17535) | 05/2025 | [project](https://prior-depth-anything.github.io/) | ICML 2025 |
| [MonoSplat: Generalizable 3D Gaussian Splatting from Monocular Depth Foundation Models](https://arxiv.org/pdf/2505.15185) |  05/2025 | [code](https://github.com/CUHK-AIM-Group/MonoSplat) | CVPR 2025 |
| [VGGT:Visual Geometry Grounded Transformer](https://arxiv.org/pdf/2503.11651) |  03/2025 | [code](https://github.com/facebookresearch/vggt) | CVPR 2025 |
| [MUSt3R: Multi-view Network for Stereo 3D Reconstruction](https://www.arxiv.org/abs/2503.01661) |  03/2025 |  | CVPR 2025 |
| [Pow3R: Empowering Unconstrained 3D Reconstruction with Camera and Scene Priors](https://arxiv.org/abs/2503.17316) |  03/2025 |  | CVPR 2025 |
| [FLARE: Feed-forward Geometry, Appearance and Camera Estimation from Uncalibrated Sparse Views](https://arxiv.org/pdf/2502.12138) |  02/2025 | [code](https://github.com/ant-research/FLARE) | CVPR 2025 |
| [EquiPose: Exploiting Permutation Equivariance for Relative Camera Pose Estimation](https://arxiv.org/abs/2502.09435) | 02/2025 |  | CVPR 2025 |
| [RePoseD: Efficient Relative Pose Estimation With Known Depth Information](https://arxiv.org/abs/2501.12345) | 01/2025 |  | ICCV 2025 |
| [Fast3R: Towards 3D Reconstruction of 1000+ Images in One Forward Pass](https://arxiv.org/abs/2501.13928) |  01/2025 | [code](https://github.com/facebookresearch/fast3r) | CVPR 2025 |
| [Continuous 3D Perception Model with Persistent State](https://arxiv.org/pdf/2501.12387) |  01/2025 | [code](https://github.com/CUT3R/CUT3R) | CVPR 2025 (Oral) |
| [Reloc3r: Large-Scale Training of Relative Camera Pose Regression for Generalizable, Fast, and Accurate Visual Localization](https://arxiv.org/pdf/2412.08376) |  12/2024 | [code](https://github.com/ffrivera0/reloc3r) | CVPR 2025 |
| [MV-DUSt3R+: Single-Stage Scene Reconstruction from Sparse Views In 2 Seconds](https://arxiv.org/pdf/2412.06974) | 12/2024 | [code](https://github.com/facebookresearch/mvdust3r) | CVPR 2025 |
| [Relative Pose Estimation through Affine Corrections of Monocular Depth Priors](https://arxiv.org/abs/2412.12345) | 12/2024 | [code](https://github.com/MarkYu98/madpose) | CVPR 2025 |
| [Understanding multi-view transformers](https://arxiv.org/abs/2412.12345) | 2025 | [code](https://github.com/JulienGaubil/und3rstand) | ICCV 2025 |
| [Peering into the Unknown: Active View Selection for 3D Reconstruction](https://arxiv.org/abs/2412.12345) | 2025 |  | ICLR 2026 |
| [3D Reconstruction with Spatial Memory](https://arxiv.org/abs/2408.16061) | 08/2024 |  [code](https://github.com/HengyiWang/spann3r)  | 3DV 2025 |
| [Grounding Image Matching in 3D with MASt3R](https://arxiv.org/abs/2406.09756) | 06/2024 |  [code](https://github.com/naver/mast3r)  | Arxiv 2024 |
| [UniDepthV2: Universal Monocular Metric Depth Estimation](https://arxiv.org/abs/2406.09414) | 06/2024 |  | CVPR 2024 |
| [DUSt3R: Geometric 3D Vision Made Easy](https://arxiv.org/pdf/2312.14132) | 12/2023 |  [code](https://github.com/naver/dust3r)  | CVPR 2024 |
| [RaCalNet: Radar Calibration Network for Sparse-Supervised Metric Depth Estimation](https://arxiv.org/abs/2506.15560) | 06/2025 |  | arXiv |


### <span id="reconstruction-class1b">Efficient 3D Vision Transformers</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [GPA-VGGT: Adapting VGGT to Large scale Localization by Self-Supervised Learning](https://arxiv.org/abs/2601.16885) | 01/2026 | [code](https://github.com/X-yangfan/GPA-VGGT) | arXiv |
| [InfiniteVGGT: Visual Geometry Grounded Transformer for Endless Streams](https://arxiv.org/abs/2601.02281) | 01/2026 | [code](https://github.com/AutoLab-SAI-SJTU/InfiniteVGGT) | arXiv |
| [AVGGT: Rethinking Global Attention for Accelerating VGGT](https://arxiv.org/abs/2512.02541) | 12/2025 |  | arXiv |
| [FlashVGGT: Efficient and Scalable Visual Geometry Transformers](https://arxiv.org/abs/2512.01896) | 12/2025 | [project](https://wzpscott.github.io/flashvggt_page/) | arXiv |
| [LiteVGGT: Boosting Vanilla VGGT via Geometry-aware Cached Token Merging](https://arxiv.org/abs/2512.03596) | 12/2025 | [project](https://garlicba.github.io/LiteVGGT/) | arXiv |
| [HTTM: Head-wise Temporal Token Merging for Faster VGGT](https://arxiv.org/abs/2511.17396) | 11/2025 |  | arXiv |
| [FastVGGT: Training-Free Acceleration of Visual Geometry Transformer](https://arxiv.org/abs/2509.02560) | 09/2025 | [project](https://mystorm16.github.io/fastvggt/) | ICLR 2026 |
| [Faster VGGT with Block-Sparse Global Attention](https://arxiv.org/abs/2509.05483) | 09/2025 |  | arXiv |
| [VGGT-Long: Chunk it, Loop it, Align it – Pushing VGGT's Limits on Long RGB Sequences](https://arxiv.org/abs/2507.16443) | 07/2025 | [code](https://github.com/DengKaiCQ/VGGT-Long) | arXiv |


### <span id="reconstruction-class2">Few-Shot Generative Recon</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [MIRROR: Make Your Object-Level Multi-View Generation Consistent](https://arxiv.org/abs/2501.12345) | 2025 |  | ICML 2026 |
| [Refine Any Object in Any Scene (RAISE)](https://arxiv.org/abs/2506.12345) | 06/2025 | [code](https://github.com/PolySummit/RAISE) | arXiv |
| [GenFusion: Closing the Loop between Reconstruction and Generation via Videos](https://arxiv.org/pdf/2503.21219) | 03/2025 | [code](https://github.com/Inception3D/GenFusion) | CVPR 2025 |
| [Difix3D+: Improving 3D Reconstructions with Single-Step Diffusion Models](https://arxiv.org/abs/2503.01774) | 03/2025 |  | CVPR 2025 |
| [Free360: Layered Gaussian Splatting for Unbounded 360-Degree View Synthesis from Extremely Sparse and Unposed Views](https://arxiv.org/pdf/2503.24382) | 03/2025 |  | CVPR 2025 |
| [LiftImage3D: Lifting Any Single Image to 3D Gaussians with Video Generation Priors](https://arxiv.org/abs/2412.09597) | 12/2024 | [code](https://github.com/AbrahamYabo/LiftImage3D) | arXiv |
| [MVSplat360: Feed-Forward 360 Scene Synthesis from Sparse Views](https://arxiv.org/abs/2411.04924) | 11/2024 | [code](https://github.com/donydchen/mvsplat360) | NeurIPS 2024 |
| [3DGS-Enhancer: Enhancing Unbounded 3D Gaussian Splatting with View-consistent 2D Diffusion Priors](https://arxiv.org/abs/2410.16266) | 10/2024 |  | NeurIPS 2024 |
| [ViewCrafter: Taming Video Diffusion Models for High-fidelity Novel View Synthesis](https://arxiv.org/abs/2409.02048) | 09/2024 | [code](https://drexubery.github.io/ViewCrafter/) | arXiv |
| [ReconX: Reconstruct Any Scene from Sparse Views with Video Diffusion Model](https://arxiv.org/abs/2408.16767) | 08/2024 |  | arXiv |

### <span id="reconstruction-class3">3D Recon-based SLAM & SFM</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [VGGT-SLAM 2.0: Real-time Dense Feed-forward SLAM](https://arxiv.org/abs/2601.19887) | 01/2026 |  | CVPR 2026 |
| [FUSER: Feed-Forward Multiview 3D Registration Transformer](https://arxiv.org/abs/2512.07458) | 12/2025 | [code](https://github.com/Jiang-HB/FUSER) | arXiv |
| [VGGT4D: Mining Motion Cues in Visual Geometry Transformers](https://arxiv.org/abs/2511.12345) | 11/2025 |  | 3DV 2026 |
| [DropD-SLAM: RGB-D SLAM Without the Depth Sensor](https://arxiv.org/abs/2510.07890) | 10/2025 |  | arXiv |
| [PointSt3R: Point Tracking through 3D Grounded Correspondence](https://arxiv.org/abs/2510.12345) | 10/2025 | [project](http://rhodriguerrier.github.io/PointSt3R) | arXiv |
| [Evict3R: Training-Free Token Eviction for Memory-Bounded Streaming](https://arxiv.org/abs/2509.12345) | 09/2025 |  | arXiv |
| [WinT3R: Window-Based Streaming Reconstruction with Camera Token Pool](https://arxiv.org/abs/2509.05296) | 09/2025 | [code](https://github.com/LiZizun/WinT3R) | ICLR 2026 |
| [SAIL-Recon: Large SfM by Augmenting Scene Regression with Localization](https://arxiv.org/abs/2508.12345) | 08/2025 | [project](https://hkust-sail.github.io/) | 3DV 2026 (Oral) |
| [StreamVGGT: Streaming 4D Visual Geometry Transformer](https://arxiv.org/abs/2507.11539) | 07/2025 | [code](https://github.com/wzzheng/StreamVGGT) | ICLR 2026 |
| [VGGT-SLAM: Dense RGB SLAM Optimized on the SL(4) Manifold](https://arxiv.org/abs/2505.12345) | 05/2025 |  | NeurIPS 2025 |
| [MP-SfM: Monocular Surface Priors for Robust Structure-from-Motion](https://arxiv.org/pdf/2504.20040v1) |  04/2025 | [code](https://github.com/cvg/mpsfm) | CVPR 2025 |
| [Easi3R: Estimating Disentangled Motion from DUSt3R Without Training](https://arxiv.org/abs/2501.12345) | 2025 |  | ICCV 2025 |
| [RA-NeRF: Robust Neural Radiance Field Reconstruction with Accurate Camera Pose Estimation](https://arxiv.org/abs/2501.12345) | 2025 |  | IROS 2025 |
| [MonST3R: Motion DUSt3R for Dynamic Scene Reconstruction](https://arxiv.org/abs/2410.12345) | 2024 | [project](https://monst3r-project.github.io/) | ICLR 2025 |
| [MASt3R-SLAM: Real-Time Dense SLAM with 3D Reconstruction Priors](https://arxiv.org/pdf/2412.12392) |  12/2024 | [code](https://github.com/rmurai0610/MASt3R-SLAM) | CVPR 2025 |
| [SLAM3R: Real-Time Dense Scene Reconstruction from Monocular RGB Videos](https://arxiv.org/pdf/2412.09401) |  12/2024 | [code](https://github.com/PKU-VCL-3DV/SLAM3R) | CVPR 2025 |
| [MASt3R-SfM: a Fully-Integrated Solution for Unconstrained Structure-from-Motion](https://arxiv.org/abs/2409.19152) |  09/2024 | [code](https://github.com/naver/mast3r/tree/mast3r_sfm) | CVPR 2025 |

## <span id="physics">🧸 Physical Object Generation</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [SOPHY: Generating Simulation-Ready Objects with PHYsical Materials](https://arxiv.org/pdf/2504.12684) | 04/2025 |  [project](https://xjay18.github.io/SOPHY/)  | arXiv |
| [PhysTwin: Physics-Informed Reconstruction and Simulation of Deformable Objects from Videos](https://arxiv.org/abs/2503.17973)| 03/2025 |  [code](https://github.com/Jianghanxiao/PhysTwin)  | arXiv |
| [DreamPhysics: Learning Physics-Based 3D Dynamics with Video Diffusion Priors](https://arxiv.org/abs/2406.01476)| 12/2024 |  [code](https://github.com/tyhuang0428/DreamPhysics)  | AAAI 2025 |
| [PhysDreamer: Physics-Based Interaction with 3D Objects via Video Generation](https://arxiv.org/abs/2404.13026) | 10/2024 |  [code](https://github.com/a1600012888/PhysDreamer)  | ECCV 2024 |
| [GIC: Gaussian-Informed Continuum for Physical Property Identification and Simulation](https://arxiv.org/abs/2406.14927v3) | 10/2024 |  [code](https://github.com/Jukgei/gic)  |NeurIPS 2024 |
| [PhysGen: Rigid-Body Physics-Grounded Image-to-Video Generation](https://arxiv.org/abs/2409.18964)| 09/2024 |  [code](https://github.com/stevenlsw/physgen)  | ECCV 2024 |
| [Reconstruction and Simulation of Elastic Objects with Spring-Mass 3D Gaussians](https://arxiv.org/abs/2403.09434) | 07/2024 |  [code](https://github.com/Colmar-zlicheng/Spring-Gaus)  |ECCV 2024 |
| [Sync4D: Video Guided Controllable Dynamics for Physics-Based 4D Generation](https://arxiv.org/abs/2405.16849)| 07/2024 |  [project](https://sync4dphys.github.io/)  | arXiv |
| [Physics3D: Learning Physical Properties of 3D Gaussians via Video Diffusion](https://arxiv.org/abs/2406.04338)| 06/2024 |  [code](https://liuff19.github.io/Physics3D/)  | arXiv |


## <span id="articulate">🤖 Articulated Object Generation and Reconstruction</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [Infinite Mobility: Scalable High-Fidelity Synthesis of Articulated Objects via Procedural Generation](https://arxiv.org/abs/2503.13424) | 03/2025 |  [code](https://github.com/OpenRobotLab/Infinite-Mobility)  | arXiv |
| [Articulate AnyMesh: Open-Vocabulary 3D Articulated Objects Modeling](https://arxiv.org/abs/2502.02590) | 02/2025 |  [project](https://articulate-anymesh.github.io/)  | arXiv |
| [Articulate-Anything: Automatic Modeling of Articulated Objects via a Vision-Language Foundation Model](https://arxiv.org/abs/2410.13882) | 10/2024 | [code](https://github.com/vlongle/articulate-anything) | ICLR 2025 |
| [SINGAPO: Single Image Controlled Generation of Articulated Parts in Objects](https://arxiv.org/abs/2410.16499) | 10/2024 | [code](https://github.com/3dlg-hcvc/singapo) | ICLR 2025 |
| [CAGE: Controllable Articulation GEneration](https://arxiv.org/abs/2312.09570v2) | 03/2024 |  [code](https://github.com/3dlg-hcvc/cage)  | CVPR 2024 |


## <span id="human-motion">🕺 Human Motion Generation</span>

### <span id="human-motion-class1">Human-Scene Interaction</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [ZeroHSI: Zero-Shot 4D Human-Scene Interaction by Video Generation](https://arxiv.org/abs/2412.18600) | 12/2024 |  [project](https://awfuact.github.io/zerohsi/)  | arXiv |
| [Autonomous Character-Scene Interaction Synthesis from Text Instruction](https://arxiv.org/abs/2410.03187) | 10/2024 |  [code](https://github.com/mileret/lingo-release)  | SIGGRAPH Aisa 2024 |
| [Human-Object Interaction from Human-Level Instructions](https://arxiv.org/pdf/2406.17840) | 06/2024 |  [project](https://hoifhli.github.io/)  | arXiv |
| [Generating Human Motion in 3D Scenes from Text Descriptions](https://arxiv.org/abs/2405.07784) | 05/2024 |  [code](https://github.com/zju3dv/text_scene_motion)  | CVPR 2024 |
| [Generating Human Interaction Motions in Scenes with Text Control](https://arxiv.org/abs/2404.10685) | 04/2024 |  [code](https://github.com/nv-tlabs/tesmo)  | ECCV 2024 |
| [Controllable Human-Object Interaction Synthesis](https://arxiv.org/abs/2312.03913) | 12/2023 |  [code](https://github.com/lijiaman/chois_release)  | ECCV 2024 oral |
| [HUMANISE: Language-conditioned Human Motion Generation in 3D Scenes](https://arxiv.org/abs/2210.09729) | 10/2022 |  [project](https://silverster98.github.io/HUMANISE/)  | NeurIPS 2022 |

### <span id="human-motion-class2">Human-Scene Reconstruction</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [HUMAN3R: Everyone Everywhere All at Once](https://arxiv.org/abs/2510.05284) | 10/2025 | [project](https://fanegg.github.io/Human3R) | ICLR 2026 |


## <span id="layout">🏠 Indoor Scene Layout Generation</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [LLM-driven Indoor Scene Layout Generation via Scaled Human-aligned Data Synthesis and Multi-Stage Preference Optimization](https://arxiv.org/abs/2506.07570) | 06/2025 |  [project](https://polysummit.github.io/optiscene.github.io/)  | arXiv |
| [LAYOUTVLM: Differentiable Optimization of 3D Layout via Vision-Language Models](https://arxiv.org/pdf/2412.02193) | 12/2024 |  [project](https://ai.stanford.edu/~sunfanyun/layoutvlm/)  | CVPR 2025 |
| [LLplace: The 3D Indoor Scene Layout Generation and Editing via Large Language Model](https://arxiv.org/abs/2406.03866) | 06/2024 |  [project]()  | arXiv |
| [EchoScene: Indoor Scene Generation via Information Echo over Scene Graph Diffusion](https://arxiv.org/abs/2405.00915) | 05/2024 |  [code](https://github.com/ymxlzgy/echoscene)  | ECCV 2024 |
| [I-Design: Personalized LLM Interior Designer](https://arxiv.org/abs/2404.02838) | 04/2024 |  [code](https://github.com/atcelen/IDesign)  | arXiv |
| [InstructScene: Instruction-Driven 3D Indoor Scene Synthesis with Semantic Graph Prior](https://arxiv.org/pdf/2402.04717) | 02/2024 |  [code](https://github.com/chenguolin/InstructScene)  | ICLR 2024 |
| [Holodeck: Language Guided Generation of 3D Embodied AI Environments](https://arxiv.org/abs/2312.09067) | 12/2023 |  [code](https://github.com/allenai/Holodeck)  | CVPR 2024 |
| [LayoutGPT: Compositional Visual Planning and Generation with Large Language Models](https://arxiv.org/abs/2305.15393) | 05/2023 |  [code](https://github.com/weixi-feng/LayoutGPT)  | arXiv |
| [DiffuScene: Denoising Diffusion Models for Generative Indoor Scene Synthesis](https://arxiv.org/pdf/2303.14207) | 03/2023 |  [code](https://github.com/tangjiapeng/DiffuScene)  | CVPR 2024 |
| [ATISS: Autoregressive Transformers for Indoor Scene Synthesis](https://arxiv.org/pdf/2110.03675) | 10/2021 |  [code](https://github.com/nv-tlabs/ATISS)  | NeurIPS 2021 |

## <span id="any-to-3d">🏠 Any-to-3D Scene</span>
| Title                                                        | Date   |                             Link                             | Venue |
| :----------------------------------------------------------- | :-----: | :----------------------------------------------------------: | :---: |
| [CAST: Component-Aligned 3D Scene Reconstruction from an RGB Image](https://arxiv.org/abs/2502.12894) | 06/2025 | -  | SIGGRAPH (Best paper) |


## <span id="star">🌟 Star History</span>

[![Star History Chart](https://api.star-history.com/svg?repos=PolySummit/Awesome-3D-Reconstruction-and-Generation&type=Date)](https://star-history.com/#PolySummit/Awesome-3D-Reconstruction-and-Generation&Date)
