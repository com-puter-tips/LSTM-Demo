# LSTM-Demo

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

A sample program to run a bidirectional LSTM with TensorFlow.

## Description

This demo trains a bidirectional LSTM on the Sonar dataset (`sonar.csv`) and reports classification accuracy. It is intended as a minimal, runnable reference for building bidirectional LSTM models with TensorFlow and Keras.

## Requirements

- Python 3 (tested on Python 3.9.13)
- Dependencies: `tensorflow`, `pandas`, `scikit-learn`, `matplotlib`

Install them with:

```
pip install -r requirements.txt
```

## Usage

Run the script from a console or IDE:

```
python3 test-fhe.py
```

- The dataset used for analysis is `sonar.csv`.
- A sample run is captured in `out.txt` and the accuracy plot in `Figure_1.png`.

## Developer utility

`auto4mat.py` is an optional helper that upgrades Python syntax and formats the code (using `pyupgrade`, `black`, `isort`) and regenerates `requirements.txt` (using `pipreqs`):

```
pip install pyupgrade black isort pipreqs
python3 auto4mat.py
```

## Citation

If you use this software, please cite it using the metadata in [CITATION.cff](CITATION.cff).

## License

Distributed under the GNU General Public License v3.0. See [LICENSE](LICENSE).
