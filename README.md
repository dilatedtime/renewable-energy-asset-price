# Renewable Energy Asset Price Forecasting

This repository contains the data, model code, regression work, and saved results behind a study of renewable-energy exchange-traded fund prices. The research combines market information with two sentiment measures: a fund-level investor sentiment index and a Google Trends index built from ETF-related searches.

The project compares CNN, BiLSTM, and CNN-LSTM forecasting models. In the published study, the CNN-LSTM model performed best, and modified Diebold-Mariano tests were used to compare forecast accuracy.

## Repository layout

| Path | Contents |
| --- | --- |
| `data/` | Market and supporting data used in the study |
| `google trends/` and `google trend share/` | Search-interest inputs and related processing |
| `models/` | Deep-learning model experiments |
| `panel regression/` | Panel-regression analysis |
| `benchmark_analysis/` | Benchmark comparisons |
| `results/` | Saved outputs from the experiments |

This is a research archive rather than a packaged application. Start with the notebooks or scripts inside the folder that matches the part of the paper you want to reproduce. Check the local file paths and data assumptions before running them on a new machine.

## Paper and citation

Lalatendu Mishra, Balaji Dinesh, P. M. Kavyassree, and Nachiketa Mishra, "A Google Trend enhanced deep learning model for the prediction of renewable energy asset price," *Knowledge-Based Systems*, 308, 112733.

- [DOI](https://doi.org/10.1016/j.knosys.2024.112733)
- [Article on ScienceDirect](https://www.sciencedirect.com/science/article/pii/S0950705124013674)

```bibtex
@article{mishra2024google,
  title={A Google Trend enhanced deep learning model for the prediction of renewable energy asset price},
  author={Mishra, Lalatendu and Dinesh, Balaji and Kavyassree, PM and Mishra, Nachiketa},
  journal={Knowledge-Based Systems},
  pages={112733},
  year={2024},
  publisher={Elsevier}
}
```

This repository is a fork of [balajidinesh/renewable-energy-asset-price](https://github.com/balajidinesh/renewable-energy-asset-price). Please cite the paper if you use the research or its materials.
