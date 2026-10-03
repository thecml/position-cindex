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
