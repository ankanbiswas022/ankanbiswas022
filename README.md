### Ankan Biswas — EEG & physiological time-series ML

I build EEG analysis systems end-to-end: acquisition, signal processing, models, validation, and serving.
PhD (Neuroscience, IISc Bengaluru). Eight years of scalp EEG, intracranial LFP, and closed-loop neurofeedback;
papers in *Imaging Neuroscience*, *European Journal of Neuroscience*, and *eNeuro*.

**Stack:** Python · MNE · scikit-learn · LightGBM · PyTorch (EEGNet / TCN / GRU) · FastAPI · Docker · GitHub Actions · MATLAB

**Recent work**
- [eeg-cognitive-scoring](https://github.com/ankanbiswas022/eeg-cognitive-scoring) — EEG → calibrated 0–100 cognitive-load score, served over an API.
  Subject-wise validated (OOF AUC 0.92, recording AUC 0.98), per-person calibration, SHAP explainability, drift monitoring, CI.
- [p300-erp-detection](https://github.com/ankanbiswas022/p300-erp-detection) — single-trial P300 detection on a public speller dataset:
  xDAWN + Riemannian geometry vs. EEGNet, decision-level aggregation with confidence.
- [meditation-state-scoring](https://github.com/ankanbiswas022/meditation-state-scoring) — the same pipeline on my own 70-subject meditation cohort:
  per-person calibration, drift controls that caught a confound, honest state AUC 0.72 / 0.80 per recording (data under ethics, code public).
- [ProjectDhyaanBK1Programs](https://github.com/ankanbiswas022/ProjectDhyaanBK1Programs) — analysis code for the meditation EEG cohort (N>100), *Imaging Neuroscience* 2026.

[Google Scholar](https://scholar.google.com/citations?user=oG28KRIAAAAJ) · [LinkedIn](https://www.linkedin.com/in/ankan-biswas-45357685/) · ankanbiswas0804@gmail.com
