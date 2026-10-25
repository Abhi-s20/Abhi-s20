# Hi, I'm Abhishek Shamkuwar

M.Tech in Signal Processing and Machine Learning, NIT Jalandhar. I build machine learning models for noisy and incomplete signals, mostly in healthcare. I'm applying for PhD positions in machine learning for healthcare, human-computer interaction and robotics.

[Website](https://abhi-s20.github.io) · [CV](https://abhi-s20.github.io/Abhishek_Shamkuwar_Academic_CV.pdf) · [LinkedIn](https://www.linkedin.com/in/abhishek-shamkuwar-295560223) · [IEEE Xplore](https://ieeexplore.ieee.org/author/335124801307027) · abhishekshamkuwar19@gmail.com

## Research

**M.Tech thesis: Early sepsis prediction using multimodal deep learning**
Supervisor: Dr. Manjeet Singh, NIT Jalandhar

- Designed MultimodalSepsisNet, which splits 40 clinical variables into four groups (vital signs, laboratory values, missingness patterns, static demographics) and fuses them with eight-head cross-modal attention.
- Evaluated on 39,721 ICU records (PhysioNet/CinC 2019) at 6-hour and 12-hour horizons against eight baselines, with 95% bootstrap confidence intervals and ablations.
- Results: AUPRC 0.744 at 6 h and 0.774 at 12 h, the highest among all baselines including XGBoost.

**Other research contributions**

- Distributed active noise control: wrote the manuscript up to the simulation section and made two figures (IEEE Open Journal of Signal Processing, 2026).
- Node localization in wireless sensor networks: ran the simulations for a GAT-GRU model across 15 mobility and noise settings (CIPHER 2026).

**Next:** EEG and medical imaging (CT/MRI) models that stay reliable when data is missing or shifts between sources.

## Publications

- A. S. Shamkuwar, P. Bhardwaj, N. Kumar, M. Singh. Early Sepsis Detection from ICU Data Using Multimodal Deep Learning. CIPHER 2026. [DOI](https://doi.org/10.1109/CIPHER70417.2026.11523895)
- A. Sharma, A. S. Shamkuwar, et al. Spatio-Temporal Node Localization in Wireless Sensor Networks Using Hybrid Recurrent-Graph Neural Network. CIPHER 2026. [DOI](https://doi.org/10.1109/CIPHER70417.2026.11524038)
- A. Kar, P. K. Shill, A. S. Shamkuwar, et al. Adaptive Improved Primal-Dual Distributed Stochastic Gradient Driven Distributed Active Noise Control System. IEEE Open Journal of Signal Processing, vol. 7, 2026. [DOI](https://doi.org/10.1109/OJSP.2026.3701314)

## Projects

- [**Human activity recognition**](https://github.com/Abhi-s20/Human-activity-recognition): signal-processing features vs. 1D-CNN and BiLSTM on smartphone motion sensors. 93.9% leave-one-subject-out accuracy over 30 subjects.
- **Robust brain tumor segmentation** (ongoing): 3D U-Net on BraTS MRI, followed by experiments on missing MRI sequences.
- [**Pothole detection**](https://github.com/Abhi-s20/pothole-detection): real-time YOLO-tiny detector with geotagging (B.Tech final-year project).
- **Finance RAG**: citation-grounded question answering over SEC 10-K/10-Q filings, served with FastAPI and React.

## Tools

Python · PyTorch · PyTorch Geometric · scikit-learn · OpenCV · FastAPI · Docker · Git
