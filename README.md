# Strain as Evidence: Trust-Weighted Kinematically Compatible Refinement of Facial Optical Flow

Mingyang Yin, Aiguo Song, Chaolong Qin, and Siqi Cao  
School of Instrument Science and Engineering, Southeast University

This repository accompanies our paper. We plan to release the implementation and reproduction materials here upon acceptance.

## Planned release

- **Implementation and training.** The strain predictor, trust networks and feature construction, compatible reconstruction, trust weight normalization, image update, and mixing step. The release will also include training scripts and the synthetic warp generator.
- **Reproduction.** Experiment configurations, data split information and subset preparation scripts, and evaluation scripts for displacement and strain errors, the zero motion panel, bootstrap confidence intervals, and the real video checks.
- **Model checkpoints.** One strain predictor and separate trust networks for TV-L1, SEA-RAFT, and DecFlow. The terms for code and model checkpoints will be specified with the release.
- **Base flow interfaces.** TV-L1 and Farnebäck use OpenCV. SEA-RAFT, RAFT, and DecFlow use their official implementations and weights under their respective licenses.

## Data access

The rendered facial motion and ground truth come from the FacialFlowNet release. The planned reproduction materials will describe how to obtain the original data and reconstruct the development and held out subsets.

The synthetic warps use source images from CASME II, SAMM, and SMIC. The real video checks use CAS(ME)². Obtain these datasets from their respective providers under their data use agreements.
