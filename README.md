# Awesome Weight-Space Programming

A curated list of papers on **weight-space programming** and **weight-space learning** — reading, auditing, editing, generating, and reasoning over neural network weights.

> [!NOTE]
> All entries link exclusively to verified, non-redirecting open academic URLs (with optional official GitHub code repositories) and are audited daily by an automated maintainer.

## Table of Contents

- [Direct Weight-Space Programming, Auditing & Compilation](#direct-weight-space-programming-auditing--compilation) (6)
- [Weight-Space Understanding, Symmetries & Optimization](#weight-space-understanding-symmetries--optimization) (20)
- [Weight-Space Representation & Metanetworks](#weight-space-representation--metanetworks) (20)
- [Weight-Space Generation & Hypernetworks](#weight-space-generation--hypernetworks) (46)
- [Model Editing, Merging & Steering](#model-editing-merging--steering) (28)
- [Applications & Related Domains](#applications--related-domains) (12)
- [Datasets & Model Zoos](#datasets--model-zoos) (10)
- [Surveys & Theses](#surveys--theses) (10)
- [Contributing](#contributing)
- [Citation](#citation)
- [License](#license)

## Direct Weight-Space Programming, Auditing & Compilation

Works on LLM weight-space programming, auditing weight readers, and compiling programs into weights.

- **[Function-Preserving Audits of Visual Weight Readers](https://arxiv.org/abs/2611.05798v2)** — *Preprint 2026*
- **[WeightLoop: Weight-Space Programming with Experimental Feedback](https://arxiv.org/abs/2611.07319)** — *Preprint 2026*
- **[Weight-space programming for auditing clinical decision networks](https://arxiv.org/abs/2611.05341)** — *Preprint 2026*
- **[Learning Transformer Programs](https://arxiv.org/abs/2306.01128)** — *NeurIPS 2023* · [Code](https://github.com/princeton-nlp/TransformerPrograms)
- **[Tracr: Compiled Transformers as a Laboratory for Interpretability](https://arxiv.org/abs/2301.05062)** — *NeurIPS 2023* · [Code](https://github.com/google-deepmind/tracr)
- **[Thinking Like Transformers](https://arxiv.org/abs/2106.06981)** — *ICML 2021*

## Weight-Space Understanding, Symmetries & Optimization

Parameter-space symmetries, invariance, equivariance, mode connectivity, compression, and optimization.

- **[Generalized Linear Mode Connectivity for Transformers](https://arxiv.org/abs/2506.22712)** — *2025*
- **[Understanding Mode Connectivity via Parameter Space Symmetry](https://arxiv.org/abs/2505.23681)** — *2025*
- **[Few-shot Implicit Function Generation via Equivariance](https://arxiv.org/abs/2501.01601)** — *CVPR 25* · [Code](https://github.com/JeanDiable/EquiGen)
- **[Universal neural functionals](https://arxiv.org/abs/2402.05232)** — *NeurIPS 24* · [Code](https://github.com/AllanYangZhou/universal_neural_functional)
- **[Improved generalization of weight space networks via augmentations](https://arxiv.org/abs/2402.04081)** — *ICML 24* · [Code](https://github.com/AvivSham/deep-weight-space-augmentations)
- **[TQCompressor: improving tensor decomposition methods in neural networks via permutations](https://arxiv.org/abs/2401.16367)** — *MIPR 24*
- **[Data Augmentations in Deep Weight Spaces](https://arxiv.org/abs/2311.08851)** — *NeurIPS-NeurReps 23*
- **[Merge, Then Compress: Demystify Efficient SMoE with Hints from Its Routing Policy](https://arxiv.org/abs/2310.01334)** — *ICLR 24*
- **[Git Re-Basin: Merging Models modulo Permutation Symmetries](https://arxiv.org/abs/2209.04836)** — *ICLR 23* · [Code](https://github.com/samuela/git-re-basin)
- **[The Role of Permutation Invariance in Linear Mode Connectivity of Neural Networks](https://arxiv.org/abs/2110.06296)** — *ICLR 22* · [Code](https://github.com/Neurips21Permutation/PermutationInvariance)
- **[Universal approximation and model compression for radial neural networks](https://arxiv.org/abs/2107.02550)** — *2021*
- **[Geometry of the loss landscape in overparameterized neural networks: Symmetries and invariances](https://arxiv.org/abs/2105.12221)** — *ICML 21*
- **[Accelerating training of batch normalization: A manifold perspective](https://arxiv.org/abs/2101.02916)** — *UAI 22*
- **[Neural optimizer adaptations for weight spaces](https://arxiv.org/abs/2012.01118)** — *Mathematics 23*
- **[Permute, quantize, and fine-tune: Efficient compression of neural networks](https://arxiv.org/abs/2010.15703)** — *CVPR 21*
- **[Optimizing deep models: practical methods](https://arxiv.org/abs/2009.02439)** — *NeurIPS 20* · [Code](https://github.com/IBM/NeuronAlignment)
- **[Lossless Compression of Structured Convolutional Models via Lifting](https://arxiv.org/abs/2007.06567)** — *2021* · [Code](https://github.com/GustikS/NeuraLifting)
- **[Weight-space symmetry in deep networks gives rise to permutation saddles, connected by equal-loss valleys across the loss landscape](https://arxiv.org/abs/1907.02911)** — *2022*
- **[G-SGD: Optimizing ReLU Neural Networks in its Positively Scale-Invariant Space](https://arxiv.org/abs/1802.03713)** — *ICLR 19*
- **[Path-sgd: Path-normalized optimization in deep neural networks](https://arxiv.org/abs/1506.02617)** — *NeurIPS 15* · [Code](https://github.com/bneyshabur/path-sgd)

## Weight-Space Representation & Metanetworks

Architectures and probes that read, embed, retrieve, or predict properties from neural network weights.

- **[Weight Space Representation Learning via Neural Field Adaptation](https://arxiv.org/abs/2512.01759)** — *CVPR 2026*
- **[Shape Generation via Weight Space Learning](https://arxiv.org/abs/2503.21830)** — *2025*
- **[We Should Chart an Atlas of All the World's Models](https://arxiv.org/abs/2503.10633)** — *2025*
- **[Weight Space Representation Learning on Diverse NeRF Architectures](https://arxiv.org/abs/2502.09623)** — *2025*
- **[Can this Model Also Recognize Dogs? Zero-Shot Model Search from Weights](https://arxiv.org/abs/2502.09619)** — *2025*
- **[Beyond the Permutation Symmetry of Transformers: The Role of Rotation for Model Fusion](https://arxiv.org/abs/2502.00264)** — *ICML 25* · [Code](https://github.com/zhengzaiyi/RotationSymmetry)
- **[Learning on Model Weights using Tree Experts](https://arxiv.org/abs/2410.13569)** — *CVPR 25*
- **[Deep Linear Probe Generators for Weight Space Learning](https://arxiv.org/abs/2410.10811)** — *2024*
- **[Revisiting Multi-Permutation Equivariance through the Lens of Irreducible Representations](https://arxiv.org/abs/2410.06665)** — *ICLR 25* · [Code](https://github.com/yonatansverdlov/SchurNet)
- **[Equivariant Polynomial Functional Networks](https://arxiv.org/abs/2410.04213)** — *ICML 25* · [Code](https://github.com/Fsoft-AIC/MAGEP-NFN)
- **[Learning on LoRAs: GL-Equivariant Processing of Low-Rank Weight Spaces for Large Finetuned Models](https://arxiv.org/abs/2410.04207)** — *2024*
- **[Monomial matrix group equivariant neural functional networks](https://arxiv.org/abs/2409.11697)** — *NeurIPS 24* · [Code](https://github.com/MathematicalAI-NUS/Monomial-NFN)
- **[Scale equivariant graph metanetworks](https://arxiv.org/abs/2406.10685)** — *NeurIPS 24* · [Code](https://github.com/jkalogero/scalegmn)
- **[The Empirical Impact of Neural Parameter Symmetries, or Lack Thereof](https://arxiv.org/abs/2405.20231)** — *2024*
- **[On genuine invariance learning without weight-tying](https://arxiv.org/abs/2308.03904)** — *ICML-TAGML 23*
- **[Set-based Neural Network Encoding Without Weight Tying](https://arxiv.org/abs/2305.16625)** — *NeurIPS 24*
- **[Predicting trends in the quality of state-of-the-art neural networks without access to training or testing data](https://arxiv.org/abs/2002.06716)** — *Natural Communications 21* · [Code](https://github.com/CalculatedContent/ww-trends-2021)
- **[Meta-Consolidation for Continual Learning](https://proceedings.neurips.cc/paper/2020/file/a5585a4d4b12277fee5cad0880611bc6-Paper.pdf)** — *2020*
- **[Deep models of interactions across sets](https://arxiv.org/abs/1803.02879)** — *ICML 18*
- **[Deep sets](https://arxiv.org/abs/1703.06114)** — *NeurIPS 17* · [Code](https://github.com/manzilzaheer/DeepSets)

## Weight-Space Generation & Hypernetworks

Hypernetworks, weight-space diffusion, flow matching, initialization, and parameter synthesis.

- **[Learning Model Representations Using Publicly Available Model Hubs](https://arxiv.org/abs/2510.02096)** — *2025*
- **[Text2Weight: Bridging Natural Language and Neural Network Weight Spaces](https://arxiv.org/abs/2508.13633)** — *MM 25*
- **[Continual Adaptation: Environment-Conditional Parameter Generation for Object Detection in Dynamic Scenarios](https://arxiv.org/abs/2506.24063)** — *2025*
- **[Reimagining Parameter Space Exploration with Diffusion Models](https://arxiv.org/abs/2506.17807)** — *ICML-EXAIT 25*
- **[Drag-and-Drop LLMs: Zero-Shot Prompt-to-Weights](https://arxiv.org/abs/2506.16406)** — *Preprint 2025*
- **[Weight-Space Linear Recurrent Neural Networks](https://arxiv.org/abs/2506.01153)** — *ICLR 26* · [Code](https://github.com/ddrous/warp)
- **[NeuroGen: Neural Network Parameter Generation via Large Language Models](https://arxiv.org/abs/2505.12470)** — *2025*
- **[Instruction-Guided Autoregressive Neural Network Parameter Generation](https://arxiv.org/abs/2504.02012)** — *ICLR-WSL 25*
- **[ORAL: Prompting Your Large-Scale LoRAs via Conditional Recurrent Diffusion](https://arxiv.org/abs/2503.24354)** — *2025*
- **[Flow to Learn: Flow Matching on Neural Network Parameters](https://arxiv.org/abs/2503.19371)** — *ICLR-WSL 25*
- **[Structure Is Not Enough: Leveraging Behavior for Neural Network Weight Reconstruction](https://arxiv.org/abs/2503.17138)** — *ICLR-WSL 25* · [Code](https://github.com/HSG-AIML/ICLR_WSL_2025-Structure_is_not_enough)
- **[Recurrent Diffusion for Large-Scale Parameter Generation](https://arxiv.org/abs/2501.11587)** — *2025* · [Code](https://github.com/NUS-HPC-AI-Lab/Recurrent-Parameter-Generation)
- **[Neural Metamorphosis](https://arxiv.org/abs/2410.11878)** — *ECCV 24*
- **[Accelerating Training with Neuron Interaction and Nowcasting Networks](https://arxiv.org/abs/2409.04434)** — *ICLR 25* · [Code](https://github.com/SamsungSAILMontreal/nino)
- **[DiffLoRA: Generating Personalized Low-Rank Adaptation Weights with Diffusion](https://arxiv.org/abs/2408.06740)** — *2024*
- **[BEND: Bagging Deep Learning Training Based on Efficient Neural Network Diffusion](https://arxiv.org/abs/2403.15766)** — *2024*
- **[Diffusion-Based Neural Network Weights Generation](https://arxiv.org/abs/2402.18153)** — *ICLR 25*
- **[Neural Network Diffusion](https://arxiv.org/abs/2402.13144)** — *2024* · [Code](https://github.com/NUS-HPC-AI-Lab/Neural-Network-Diffusion)
- **[Spatio-Temporal Few-Shot Learning via Diffusive Neural Network Generation](https://arxiv.org/abs/2402.11922)** — *ICLR 24* · [Code](https://github.com/tsinghua-fib-lab/GPD)
- **[Hypereditor: Achieving both authenticity and cross-domain capability in image editing via hypernetworks](https://arxiv.org/abs/2312.13537)** — *AAAI 24*
- **[Learning to Generate Parameters of ConvNets for Unseen Image Data](https://arxiv.org/abs/2310.11862)** — *TIP 24*
- **[Hyperdreambooth: Hypernetworks for fast personalization of text-to-image models](https://arxiv.org/abs/2307.06949)** — *CVPR 24* · [Code](https://github.com/JiauZhang/hyperdreambooth)
- **[HyperDiffusion: Generating Implicit Neural Fields with Weight-Space Diffusion](https://arxiv.org/abs/2303.17015)** — *ICCV 23*
- **[Can We Scale Transformers to Predict Parameters of Diverse ImageNet Models?](https://arxiv.org/abs/2303.04143)** — *ICML 23* · [Code](https://github.com/SamsungSAILMontreal/ghn3)
- **[Meta-Learning via Classifier(-free) Diffusion Guidance](https://arxiv.org/abs/2210.08942)** — *TMLR 23*
- **[Polyhistor: Parameter-Efficient Multi-Task Adaptation for Dense Vision Tasks](https://arxiv.org/abs/2210.03265)** — *NeurIPS 22*
- **[Learning to Learn with Generative Models of Neural Network Checkpoints](https://arxiv.org/abs/2209.12892)** — *2022*
- **[Sylph: A Hypernetwork Framework for Incremental Few-shot Object Detection](https://arxiv.org/abs/2203.13903)** — *CVPR 22*
- **[HyperTransformer: Model Generation for Supervised and Semi-Supervised Few-Shot Learning](https://arxiv.org/abs/2201.04182)** — *ICML 22* · [Code](https://github.com/google-research/google-research)
- **[HyperInverter: Improving StyleGAN Inversion via Hypernetwork](https://arxiv.org/abs/2112.00719)** — *CVPR 22* · [Code](https://github.com/VinAIResearch/HyperInverter)
- **[HyperStyle: StyleGAN Inversion With HyperNetworks for Real Image Editing](https://arxiv.org/abs/2111.15666)** — *CVPR 22* · [Code](https://github.com/yuval-alaluf/hyperstyle)
- **[Parameter Prediction for Unseen Deep Architectures](https://arxiv.org/abs/2110.13100)** — *NeurIPS 2021* · [Code](https://github.com/facebookresearch/ppuda)
- **[Parameterefficient multi-task fine-tuning for transformers via shared hypernetworks](https://arxiv.org/abs/2106.04489)** — *ACL-IJCNLP 21* · [Code](https://github.com/rabeehk/hyperformer)
- **[Personalized Federated Learning using Hypernetworks](https://arxiv.org/abs/2103.04628)** — *ICML 21* · [Code](https://github.com/AvivSham/pFedHN)
- **[Hyperseg: Patch-wise hypernetwork for real-time semantic segmentation](https://arxiv.org/abs/2012.11582)** — *CVPR 21*
- **[pi-gan: Periodic implicit generative adversarial networks for 3d-aware image synthesis](https://arxiv.org/abs/2012.00926)** — *CVPR 21* · [Code](https://github.com/ssumin6/pigan)
- **[DHP: Differentiable Meta Pruning via HyperNetworks](https://arxiv.org/abs/2003.13683)** — *ECCV 20* · [Code](https://github.com/ofsoundof/dhp)
- **[Deep meta functionals for shape representation](https://arxiv.org/abs/1908.06277)** — *ICCV 19*
- **[Continual learning with hypernetworks](https://arxiv.org/abs/1906.00695)** — *ICLR 20* · [Code](https://github.com/chrhenning/hypercl)
- **[Hypergan: A generative model for diverse, performant neural networks](https://arxiv.org/abs/1901.11058)** — *ICML 19* · [Code](https://github.com/simeetnayan81/hypergan-pytorch)
- **[Graph HyperNetworks for Neural Architecture Search](https://arxiv.org/abs/1810.05749)** — *ICLR 19*
- **[Implicit weight uncertainty in neural networks](https://arxiv.org/abs/1711.01297)** — *2017* · [Code](https://github.com/pawni/BayesByHypernet)
- **[Bayesian Hypernetworks](https://arxiv.org/abs/1710.04759)** — *2017*
- **[SMASH: One-Shot Model Architecture Search through HyperNetworks](https://arxiv.org/abs/1708.05344)** — *ICLR 18*
- **[HyperNetworks](https://arxiv.org/abs/1609.09106)** — *2016 preprint* · [Code](https://github.com/g1910/HyperNetworks)
- **[Generative Models as Distributions of Functions](https://proceedings.mlr.press/v151/dupont22a.html)** — *AISTATS 22* · [Code](https://github.com/EmilienDupont/neural-function-distributions)

## Model Editing, Merging & Steering

Task arithmetic, localized weight editing, activation steering, and policy adaptation.

- **[Behavioral Steering of Vision-Language-Action Models in the Low-Parameter Regime](https://arxiv.org/abs/2611.00522)** — *NeurIPS 2026 RoboPAD Workshop*
- **[Causal Analysis of Robot Foundation Models Enables Efficiency Gains](https://arxiv.org/abs/2610.20750)** — *Preprint 2026*
- **[RoboIRS: Inference-Time Internal Representation Steering for Generalist Robot Policies](https://arxiv.org/abs/2610.04681)** — *Preprint 2026*
- **[Suppression Sticks, Locality Is Fragile: A Closed-Loop Audit of Task-Vector Negation in VLA Policies](https://arxiv.org/abs/2608.04692)** — *Preprint 2026*
- **[Steering Robustness into World Action Models via Mechanistic Interpretability and Optimal Control (WA-LQR)](https://arxiv.org/abs/2607.14943)** — *Preprint 2026*
- **[DiMaS: Distribution Matching for Steering Vision-Language-Action Models](https://arxiv.org/abs/2607.14280)** — *Preprint 2026* · [Code](https://github.com/pegah-kh/dimas)
- **[Domain Arithmetic: One-Shot VLA Adaptation under Environmental Shifts (DART)](https://arxiv.org/abs/2607.00666)** — *Preprint 2026*
- **[Robotic Policy Adaptation via Weight-Space Meta-Learning (WIZARD)](https://arxiv.org/abs/2606.07217)** — *Preprint 2026*
- **[Contrastive Conceptor Activation Steering (COAST): Unlocking Vision-Language-Action Models through Hidden States](https://arxiv.org/abs/2605.17144)** — *Preprint 2026*
- **[Sparse Autoencoders Reveal Interpretable and Steerable Features in VLA Models](https://arxiv.org/abs/2603.19183)** — *CoRL 2026* · [Code](https://github.com/swannaiden/drvla)
- **[Mechanistic Interpretability for Steering Vision-Language-Action Models](https://arxiv.org/abs/2509.00328)** — *CoRL 2025*
- **[Generative Modeling of Weights: Generalization or Memorization?](https://arxiv.org/abs/2506.07998)** — *2025* · [Code](https://github.com/boyazeng/weight_memorization)
- **[Refusal in Language Models Is Mediated by a Single Direction](https://arxiv.org/abs/2406.11717)** — *NeurIPS 2024*
- **[Towards Scalable and Versatile Weight Space Learning](https://arxiv.org/abs/2406.09997)** — *ICML 24* · [Code](https://github.com/HSG-AIML/SANE)
- **[Interpreting the Weight Space of Customized Diffusion Models](https://arxiv.org/abs/2406.09413)** — *NeurIPS 24*
- **[Graph Neural Networks for Learning Equivariant Representations of Neural Networks](https://arxiv.org/abs/2403.12143)** — *ICLR 24* · [Code](https://github.com/mkofinas/neural-graphs)
- **[Steering Llama 2 via Contrastive Activation Addition (CAA)](https://arxiv.org/abs/2312.06681)** — *ACL 2024*
- **[Graph Metanetworks for Processing Diverse Neural Architectures](https://arxiv.org/abs/2312.04501)** — *ICLR 24*
- **[Equivariant Deep Weight Space Alignment](https://arxiv.org/abs/2310.13397)** — *ICML 2024* · [Code](https://github.com/AvivNavon/deep-align)
- **[Representation Engineering: A Top-Down Approach to AI Transparency](https://arxiv.org/abs/2310.01405)** — *Preprint 2023* · [Code](https://github.com/andyzoujm/representation-engineering)
- **[Steering Language Models With Activation Engineering (ActAdd)](https://arxiv.org/abs/2308.10248)** — *Preprint 2023*
- **[Neural Functional Transformers](https://arxiv.org/abs/2305.13546)** — *NeurIPS 2023* · [Code](https://github.com/AllanYangZhou/nfn)
- **[Permutation Equivariant Neural Functionals](https://arxiv.org/abs/2302.14040)** — *NeurIPS 2023* · [Code](https://github.com/AllanYangZhou/nfn)
- **[Equivariant Architectures for Learning in Deep Weight Spaces](https://arxiv.org/abs/2301.12780)** — *ICML 23* · [Code](https://github.com/AvivNavon/DWSNets)
- **[Editing Models with Task Arithmetic](https://arxiv.org/abs/2212.04089)** — *ICLR 2023* · [Code](https://github.com/mlfoundations/task_vectors)
- **[Mass-Editing Memory in a Transformer (MEMIT)](https://arxiv.org/abs/2210.07229)** — *ICLR 2023* · [Code](https://github.com/kmeng01/memit)
- **[Hyper-Representations as Generative Models: Sampling Unseen Neural Network Weights](https://arxiv.org/abs/2209.14733)** — *NeurIPS 22* · [Code](https://github.com/HSG-AIML/NeurIPS_2022-Generative_Hyper_Representations)
- **[Locating and Editing Factual Associations in GPT (ROME)](https://arxiv.org/abs/2202.05262)** — *NeurIPS 2022* · [Code](https://github.com/kmeng01/rome)

## Applications & Related Domains

Implicit neural representations, continual learning, meta-learning, federated learning, and architecture search.

- **[GNN-based Unified Deep Learning](https://arxiv.org/abs/2508.10583)** — *Preprint 2025* · [Code](https://github.com/basiralab/uGNN)
- **[End-to-End Implicit Neural Representations for Classification](https://arxiv.org/abs/2503.18123)** — *CVPR 25* · [Code](https://github.com/SanderGielisse/MWT)
- **[Learning to Learn Weight Generation via Local Consistency Diffusion](https://arxiv.org/abs/2502.01117)** — *Preprint 2025*
- **[From MLP to NeoMLP: Leveraging Self-Attention for Neural Fields](https://arxiv.org/abs/2412.08731)** — *Preprint 2024* · [Code](https://github.com/mkofinas/neomlp)
- **[pFedGPA: Diffusion-based Generative Parameter Aggregation for Personalized Federated Learning](https://arxiv.org/abs/2409.05701)** — *AAAI 25*
- **[Weight Diffusion for Future: Learn to Generalize in Non-Stationary Environments](https://proceedings.neurips.cc/paper_files/paper/2024/hash/0c1124bd3be769dacf491d92d499c7d8-Abstract-Conference.html)** — *NeurIPS 24* · [Code](https://github.com/BIT-DA/W-Diff)
- **[MetaDiff: Meta-Learning with Conditional Diffusion for Few-Shot Learning](https://arxiv.org/abs/2307.16424)** — *AAAI 24*
- **[Deep Learning on Implicit Neural Representations of Shapes](https://arxiv.org/abs/2302.05438)** — *ICLR 23* · [Code](https://github.com/CVLAB-Unibo/inr2vec)
- **[Spatial Functa: Scaling Functa to ImageNet Classification and Generation](https://arxiv.org/abs/2302.03130)** — *Preprint 2023* · [Code](https://github.com/samuelepapa/spatial_functa)
- **[From data to functa: Your data point is a function and you can treat it like one](https://arxiv.org/abs/2201.12204)** — *ICML 22* · [Code](https://github.com/JurrivhLeon/Functa_pytorch_version)
- **[Learning signal-agnostic manifolds of neural fields](https://arxiv.org/abs/2111.06387)** — *NeurIPS 21* · [Code](https://github.com/yilundu/gem)
- **[Graf: Generative radiance fields for 3d-aware image synthesis](https://arxiv.org/abs/2007.02442)** — *NeurIPS 20* · [Code](https://github.com/autonomousvision/graf)

## Datasets & Model Zoos

Model zoos and datasets for training and evaluating weight-space methods.

- **[Scaling LLaNA: Advancing NeRF-Language Understanding Through Large-Scale Training](https://arxiv.org/abs/2504.13995)** — *Preprint 2025*
- **[A Model Zoo of Vision Transformers](https://arxiv.org/abs/2504.10231)** — *ICLR-WSL 25* · [Code](https://github.com/ModelZoos/ViTModelZoo)
- **[Implicit-Zoo: A Large-Scale Dataset of Neural Implicit Functions for 2D Images and 3D Scenes](https://arxiv.org/abs/2406.17438)** — *NeurIPS 24* · [Code](https://github.com/qimaqi/Implicit-Zoo)
- **[Unsupervised Model Tree Heritage Recovery](https://arxiv.org/abs/2405.18432)** — *ICLR 25*
- **[Learning Useful Representations of Recurrent Neural Network Weight Matrices](https://arxiv.org/abs/2403.11998)** — *ICML 24*
- **[Sparsified Model Zoo Twins: Investigating Populations of Sparsified Neural Network Models](https://arxiv.org/abs/2304.13718)** — *ICLR-SNN 23* · [Code](https://github.com/ModelZoos/ModelZooDataset)
- **[Model Zoos: A Dataset of Diverse Populations of Neural Network Models](https://arxiv.org/abs/2209.14764)** — *NeurIPS 22* · [Code](https://github.com/ModelZoos/ModelZooDataset)
- **[Self-supervised representation learning on neural network weights for model characteristic prediction](https://arxiv.org/abs/2110.15288)** — *NeurIPS 21* · [Code](https://github.com/HSG-AIML/NeurIPS_2021-Weight_Space_Learning)
- **[Predicting Neural Network Accuracy from Weights](https://arxiv.org/abs/2002.11448)** — *2020* · [Code](https://github.com/google-research/google-research)
- **[Classifying the classifier: dissecting the weight space of neural networks](https://arxiv.org/abs/2002.05688)** — *ECAL 20* · [Code](https://github.com/gabrieleilertsen/nws)

## Surveys & Theses

Literature surveys and doctoral/master theses on weight-space learning.

- **[A Survey of Weight Space Learning: Understanding, Representation, and Generation](https://arxiv.org/abs/2603.10090)** — *Preprint 2026*
- **[Acquiring and Adapting Priors for Novel Tasks via Neural Meta-Architectures](https://arxiv.org/abs/2507.10446)** — *PhD Thesis*
- **[Symmetry in Neural Network Parameter Spaces](https://arxiv.org/abs/2506.13018)** — *Preprint 2025*
- **[Geometric Flow Models over Neural Network Weights](https://arxiv.org/abs/2504.03710)** — *MSc Thesis* · [Code](https://github.com/ege-erdogan/weightflow)
- **[Where Do We Stand with Implicit Neural Representations? A Technical and Performance Survey](https://arxiv.org/abs/2411.03688)** — *Preprint 2024*
- **[Hyper-Representations: Learning from Populations of Neural Networks](https://arxiv.org/abs/2410.05107)** — *PhD Thesis*
- **[Model Merging in LLMs, MLLMs, and Beyond: Methods, Theories, Applications and Opportunities](https://arxiv.org/abs/2408.07666)** — *Preprint 2024*
- **[Model Lakes](https://arxiv.org/abs/2403.02327)** — *EDBT 25*
- **[Implicit Neural Representation in Medical Imaging: A Comparative Survey](https://arxiv.org/abs/2307.16142)** — *Preprint 2023*
- **[A Brief Review of Hypernetworks in Deep Learning](https://arxiv.org/abs/2306.06955)** — *Preprint 2023*

## Contributing

Only **paper additions** in `README.md` are accepted from external contributors. Deletions, edits to existing entries, or modifications to any other file are automatically closed. See [CONTRIBUTING.md](CONTRIBUTING.md) for the exact format, allowed domains, and verification rules.

## Citation

If you find this repository helpful in your research, please cite:

```bibtex
@misc{cha2026awesomewsp,
  author       = {Cha, Sungguk},
  title        = {Awesome Weight-Space Programming},
  year         = {2026},
  howpublished = {\url{https://github.com/sunggukcha/awesome-weight-space-programming}}
}
```

## License

This repository's original text is dedicated to the public domain under [CC0 1.0 Universal](LICENSE).
