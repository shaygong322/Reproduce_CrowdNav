# Reproduce_IntentionCrowdNav
This repository contains the codes for reproducing the paper titled "Intention Aware Robot Crowd Navigation with Attention-Based Interaction Graph" in ICRA 2023.  
Please check the [original code repo](https://github.com/Shuijing725/CrowdNav_Prediction_AttnGraph), and the [project website](https://sites.google.com/view/intention-aware-crowdnav/home) and [arXiv preprint](https://arxiv.org/abs/2203.01821).

## Environment Setup
I tested the code on Windows 11.

`python test.py`

1. In a conda environment with Python 3.8.19, install the required python package
```
pip install -r requirements.txt
```

2. Install Pytorch 1.12.1 following the instructions [here](https://pytorch.org/get-started/previous-versions/#v1121)

3. Install [OpenAI Baselines](https://github.com/openai/baselines#installation) 
```
git clone https://github.com/openai/baselines.git
cd baselines
pip install -e .
```

4. Install [Python-RVO2](https://github.com/sybrenstuvel/Python-RVO2) library. For problems that may appear on Windows systems, please refer to issue #22 of the repo, there have been detailed instructions on how to install this library.
