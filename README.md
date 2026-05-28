<p align="left">
  <img height="60" alt="ICML 2026" src="https://github.com/user-attachments/assets/e42c745a-f9f0-4b38-b72b-0fcd172e63ba" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img height="70" alt="ChatGPT Image May 28, 2026, 09_31_21 PM" src="https://github.com/user-attachments/assets/ce359a67-ec8a-48a9-bfe5-7f30a56cbdaa" />
  <img height="60" alt="Alberta Machine Intelligence Institute" src="https://github.com/user-attachments/assets/55dcaa79-637d-4443-b179-61fe3ffbe815" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img height="48" alt="University of Alberta" src="https://github.com/user-attachments/assets/56fc3423-9969-4009-859c-e67919916dd4" />

</p>

This repository contains the code for the position paper:

**Stop Chasing the C-index when Evaluating Survival Analysis Models**  
Christian Marius Lillelund, Shi-ang Qi, Russell Greiner, and Christian Fischer Pedersen<br>
**Accepted at ICML 2026 (Spotlight)**

Preprint: [arXiv:2506.02075](https://arxiv.org/abs/2506.02075)

The paper argues that survival models should be evaluated with metrics whose assumptions match the modeling objective and the censoring mechanism. The experiments in this repository illustrate the **ladder hypothesis of model-metric consistency**, which shows that model evaluation can introduce significant bias if censoring is not adjusted for.

Repository contents
--------
```text
├── data/                  # Saved experiment outputs
├── dgp.py                 # Weibull data-generating process
├── ladder_hypo.ipynb      # Main experiments
├── plot_metrics.ipynb     # Plotting code for metric-error curves
├── stats.ipynb            # Summary statistics for literature survey
├── utility.py             # Helper functions for splitting, formatting, and evaluation
├── requirements.txt       # Python dependencies
├── LICENSE
└── README.md
```

Experiments
--------
See this [Notebook](https://github.com/thecml/position-cindex/blob/main/ladder_hypo.ipynb) for controlled experiments of the ladder hypothesis.

Citation
--------
If you find this paper useful in your work, please consider citing it:
 
```
@article{lillelund_stop_2026,
  title={Position: Stop Chasing the C-index when Evaluating Survival Analysis Models},
  author={Christian Marius Lillelund and Shi-ang Qi and Russell Greiner and Christian Fischer Pedersen},
  journal={preprint, arXiv:2506.02075},
  year={2026},
}
```
