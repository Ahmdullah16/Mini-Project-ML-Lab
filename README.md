# Mini-Project-ML-Lab
Attention - and Transformer-Based Deep Learning for Super-Resolution of Remote Sensing Images

# Mini Project ML Lab

### From Python Fundamentals to Research-Level Remote Sensing Super-Resolution

A structured, hands-on machine learning research laboratory containing **40 progressive mini-projects** that lead toward the development of an efficient CNN–Attention–Transformer architecture for remote-sensing image super-resolution.

## Major Research Project

**Title:** Attention- and Transformer-Based Deep Learning for Super-Resolution of Remote Sensing Images

**Research objective:** Develop and experimentally evaluate a deep-learning framework that reconstructs high-resolution satellite imagery from low-resolution observations, with emphasis on reconstruction quality, robustness, and computational efficiency.

### Research Pipeline

Remote-Sensing Images → Preprocessing → HR–LR Pair Generation → Classical Baselines → CNN → Attention → Transformer → Hybrid Architecture → Reconstruction → Evaluation → Ablation and Robustness Analysis

## Learning Philosophy

Every mini-project follows this sequence:

1. Learn the prerequisites and mathematical concepts.
2. Study university lectures and standard references.
3. Solve small numerical examples.
4. Implement the algorithm from scratch where practical.
5. Compare the implementation with trusted libraries.
6. Visualize intermediate and final results.
7. Run experiments and analyze parameter effects.
8. Write observations and conclusions.
9. Save the reproducible implementation.
10. Reuse the learned components in later projects.

**Core principle:** Understand first, implement second, experiment third, and document everything.

## Complete 40 Mini-Project Roadmap

### Stage 1 — Python, NumPy and Image Fundamentals

- [ ] **MP01 — Digital Image Explorer:** Pixels, RGB channels, grayscale images, image dimensions, bit depth, histograms.
- [ ] **MP02 — NumPy Image Laboratory:** Indexing, slicing, reshaping, broadcasting, normalization, vectorized operations.
- [ ] **MP03 — Image Resizing Laboratory:** Nearest-neighbor, bilinear and bicubic interpolation.
- [ ] **MP04 — Image Comparison Tool:** Image differences, absolute error, MSE and visualization.

### Stage 2 — Image Processing and Degradation

- [ ] **MP05 — Gaussian Blur Simulator:** Convolution, Gaussian kernels, kernel size and blur strength.
- [ ] **MP06 — Low-Resolution Image Generator:** Downsampling, scale factors, sampling and aliasing.
- [ ] **MP07 — Synthetic Degradation Laboratory:** Blur, noise, downsampling and degradation combinations.
- [ ] **MP08 — Frequency-Domain Image Explorer:** Fourier transforms, spatial frequencies, edge and texture information.

### Stage 3 — Image Quality Evaluation

- [ ] **MP09 — MSE and PSNR from Scratch:** Reconstruction error, dynamic range and PSNR.
- [ ] **MP10 — SSIM Evaluation Tool:** Luminance, contrast and structural similarity.
- [ ] **MP11 — Super-Resolution Evaluation Dashboard:** Metrics, error maps, comparison figures and result tables.

### Stage 4 — Mathematics, ML and PyTorch

- [ ] **MP12 — Linear Algebra Visualizer:** Vectors, matrices, tensor shapes, transformations and norms.
- [ ] **MP13 — Gradient Descent from Scratch:** Derivatives, gradients, learning rates and optimization.
- [ ] **MP14 — Neural Network from Scratch:** Forward propagation, activation functions, loss and backpropagation.
- [ ] **MP15 — First PyTorch Neural Network:** Tensors, autograd, optimizers and model training.
- [ ] **MP16 — Reusable Training Pipeline:** Dataset, DataLoader, validation, checkpoints and reproducibility.

### Stage 5 — CNN-Based Super-Resolution

- [ ] **MP17 — Convolution Playground:** Kernels, padding, stride, feature maps and receptive fields.
- [ ] **MP18 — CNN Edge Detection Laboratory:** Sobel filters and learned convolutional features.
- [ ] **MP19 — CNN Image Reconstruction:** Supervised reconstruction using convolutional neural networks.
- [ ] **MP20 — SRCNN Implementation:** Feature extraction, nonlinear mapping and SR reconstruction.
- [ ] **MP21 — Residual CNN Super-Resolution:** Residual blocks, skip connections and deep feature extraction.
- [ ] **MP22 — Upsampling Architecture Comparison:** Interpolation, transposed convolution and PixelShuffle.

### Stage 6 — Attention Mechanisms

- [ ] **MP23 — Channel Attention from Scratch:** Global pooling, channel weights and feature recalibration.
- [ ] **MP24 — Spatial Attention from Scratch:** Spatial attention maps and feature weighting.
- [ ] **MP25 — Combined Attention Module:** Channel attention, spatial attention and CBAM-style integration.
- [ ] **MP26 — Attention-Based SR Network:** Residual attention blocks and SR performance comparisons.

### Stage 7 — Transformers

- [ ] **MP27 — Self-Attention from Scratch:** Queries, keys, values, scaled dot-product attention and softmax.
- [ ] **MP28 — Multi-Head Self-Attention:** Attention heads, feature projections and concatenation.
- [ ] **MP29 — Transformer Encoder Block:** Multi-head attention, normalization, residual connections and feed-forward networks.
- [ ] **MP30 — Image Patches and Window Attention:** Patch embeddings, tokens, local windows and attention complexity.
- [ ] **MP31 — Transformer-Based SR Baseline:** SwinIR-style image restoration and Transformer SR evaluation.

### Stage 8 — Remote Sensing

- [ ] **MP32 — Satellite Image Explorer:** Satellite bands, spatial resolution, GeoTIFF and raster metadata.
- [ ] **MP33 — Satellite Preprocessing Pipeline:** Band selection, normalization, invalid pixels and patch extraction.
- [ ] **MP34 — Satellite HR–LR Pair Builder:** Paired data, synthetic degradation and alignment.
- [ ] **MP35 — Geographic Dataset Splitting:** Scene-independent train, validation and test splits.
- [ ] **MP36 — Cross-Sensor Dataset Investigation:** WorldStrat, Sen2Venµs, geometric and radiometric differences.

### Stage 9 — Hybrid Model and Research Evaluation

- [ ] **MP37 — Feature Fusion Laboratory:** CNN features, Transformer features, addition and concatenation.
- [ ] **MP38 — Hybrid CNN–Attention–Transformer SR Model:** Integrated architecture and reconstruction.
- [ ] **MP39 — Controlled Ablation Study:** CNN, CNN + Attention, CNN + Transformer, full hybrid.
- [ ] **MP40 — Robustness and Efficiency Benchmark:** Blur, noise, cross-sensor shift, parameters, FLOPs, inference time and GPU memory.

## Major Project Deliverables

- [ ] Reproducible remote-sensing data pipeline
- [ ] Classical SR baseline comparison
- [ ] CNN and attention-based SR baselines
- [ ] Transformer-based SR baseline
- [ ] Proposed hybrid architecture
- [ ] PSNR and SSIM evaluation
- [ ] Appropriate spectral and perceptual evaluation
- [ ] Controlled ablation study
- [ ] Robustness and cross-sensor evaluation
- [ ] Computational efficiency analysis
- [ ] Thesis-ready results and figures
- [ ] Final technical report
- [ ] Research paper draft, if the results support a defensible contribution

## Primary Learning References

**Python and NumPy**
- [Python Tutorial](https://docs.python.org/3/tutorial/)
- [NumPy Documentation](https://numpy.org/doc/stable/)

**Mathematics**
- [MIT 18.06 Linear Algebra](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- [Mathematics for Machine Learning](https://mml-book.github.io/)

**Machine Learning and Deep Learning**
- [Stanford CS229](https://cs229.stanford.edu/)
- [Stanford CS231n](https://cs231n.stanford.edu/)
- [MIT Introduction to Deep Learning](https://introtodeeplearning.com/)
- [PyTorch Tutorials](https://docs.pytorch.org/tutorials/)

**Computer Vision and Remote Sensing**
- [Computer Vision: Algorithms and Applications](https://szeliski.org/Book/)
- [OpenCV Documentation](https://docs.opencv.org/)
- [Rasterio Documentation](https://rasterio.readthedocs.io/)
- [ISRO IIRS e-Learning](https://elearning.iirs.gov.in/available_courses.php)

**Super-Resolution Research**
- [SRCNN](https://arxiv.org/abs/1501.00092)
- [VDSR](https://arxiv.org/abs/1511.04587)
- [EDSR](https://arxiv.org/abs/1707.02921)
- [RCAN](https://arxiv.org/abs/1807.02758)
- [SwinIR](https://arxiv.org/abs/2108.10257)
- [HAT](https://arxiv.org/abs/2205.04437)

## How to Run a Mini-Project

1. Open the corresponding mini-project directory.
2. Read its local README for prerequisites and learning objectives.
3. Install the required Python dependencies.
4. Open the Jupyter notebook.
5. Run cells sequentially.
6. Complete the experiments and exercises.
7. Review the outputs and conclusions.
8. Run the associated automated tests where available.
9. Update the project status after successful verification.

Individual project instructions will document exact commands and any dataset requirements.

## Completion Criteria

A mini-project is complete only when:

- The concepts and mathematics are understood.
- The implementation runs successfully.
- Required tests pass.
- Outputs are verified.
- Experimental observations are documented.
- The project README explains how to reproduce the results.

## Research Integrity

- Do not report fabricated experimental results.
- Clearly distinguish executed experiments from planned experiments.
- Document hardware, datasets and evaluation settings.
- Avoid training/test data leakage.
- Do not claim architectural novelty without experimental evidence.
- Preserve scientific and spectral validity when working with satellite imagery.

## Project Status

**Planned:** 40 mini-projects  
**Completed:** 0 / 40  
**Current:** MP01 — Digital Image Explorer  
**Major project:** Planning and foundational learning

---

This repository is a progressive learning and research laboratory, with each mini-project contributing reusable knowledge and code toward the final remote-sensing super-resolution system.
