# HyPyP ðã°ï¸ð

The **Hy**perscanning **Py**thon **P**ipeline

[![PyPI version shields.io](https://img.shields.io/pypi/v/hypyp.svg)](https://pypi.org/project/HyPyP/) <a href="https://travis-ci.org/ppsp-team/HyPyP"><img src="https://travis-ci.org/ppsp-team/HyPyP.svg?branch=master"></a> [![license](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![Mattermost](https://img.shields.io/static/v1?label=chat&message=Mattermost&color=Blue)](https://mattermost.brainhack.org/brainhack/channels/hypyp)

â ï¸ This software is in beta and thus should be considered with caution. While we have done our best to test all the functionalities, there is no guarantee that the pipeline is entirely bug-free. 

ð See our [paper](https://academic.oup.com/scan/advance-article/doi/10.1093/scan/nsaa141/5919711) for more explanation and our plan for upcoming functionalities (aka Roadmap).

ð¤ If you want to help you can submit bugs and suggestions of enhancements in our Github [Issues section](https://github.com/ppsp-team/HyPyP/issues).

ð¤ For the motivated contributors, you can even help directly in the developpment of HyPyP. You will need to install [Poetry](https://python-poetry.org/) (see section below).

## Contributors
Florence BRUN, AnaÃ«l AYROLLES, Phoebe CHEN, Amir DJALOVSKI, Yann BEAUXIS, Suzanne DIKKER, Guillaume DUMAS

## Installation

```
pip install HyPyP
```

## Documentation

HyPyP documentation of all the API functions is available online at [hypyp.readthedocs.io](https://hypyp.readthedocs.io/)

For getting started with HyPyP, we have designed a little walkthrough: [getting_started.ipynb](https://github.com/ppsp-team/HyPyP/blob/master/tutorial/getting_started.ipynb)

## API

ð  [io.py](https://github.com/ppsp-team/HyPyP/blob/master/hypyp/io.py) â Loaders (Florence, AnaÃ«l, Guillaume)

ð§° [utils.py](https://github.com/ppsp-team/HyPyP/blob/master/hypyp/utils.py) â Basic tools (Amir, Florence, Guilaume)

âï¸ [prep.py](https://github.com/ppsp-team/HyPyP/blob/master/hypyp/prep.py) â Preprocessing (ICA & AutoReject) (AnaÃ«l, Florence, Guillaume)

ð  [analyses.py](https://github.com/ppsp-team/HyPyP/blob/master/hypyp/analyses.py) â Power spectral density and wide choice of connectivity measures (Phoebe, Suzanne, Florence, Guillaume)

ð [stats.py](https://github.com/ppsp-team/HyPyP/blob/master/hypyp/stats.py) â Statistics (permutations & cluster statistics) (Florence, Guillaume)

ð§  [viz.py](https://github.com/ppsp-team/HyPyP/blob/master/hypyp/viz.py) â Inter-brain visualization (AnaÃ«l, Amir, Florence, Guillaume)

ð [Tutorials](https://github.com/ppsp-team/HyPyP/tree/master/tutorial) - Examples & documentation (AnaÃ«l, Florence, Yann, Guillaume)

## Poetry installation (only for developpers)

Step 1: ```pip install poetry```

Step 2: ```git clone git@github.com:ppsp-team/HyPyP.git```

Step 3: ```cd HyPyP```

Step 4: ```poetry install```

Step 5: ```poetry shell```
