# Layer-Wise Analysis of Robust Overfitting in Adversarial Training

This branch is developed for layer-wise analysis of robust overfitting in adversarial training, the related paper is as follows:  
[Duke Nguyen, Chaojian Yu, Vinoth Nandakumar, Young Choon Lee, Tongliang Liu. On Intriguing Layer-Wise Properties of Robust Overfitting in Adversarial Training. TMLR 2024](https://openreview.net/forum?id=phk5CcKTcc)

## What is in this repository
We divide a DNN into a series of layers and investigate the effect of different network layers on robust overfitting. We find that different layers exhibit distinct properties towards robust overfitting, and in particular, robust overfitting is mostly related to the optimization of latter parts of the network.

We provide relevant implementations under [AWP](https://github.com/csdongxian/AWP), where the implementation based on [Standard AT](https://github.com/locuslab/robust_overfitting) is placed in `AT_AWP_layer_wise`, and the implementation based on [TRADES](https://github.com/yaodongyu/TRADES/) is placed in `TRADES_AWP_layer_wise`. In each folder, we provide the relevant codes of the layer-wise analysis of robust overfitting under different network structures.

## How to use it

## Reference Code
[1] AT: https://github.com/locuslab/robust_overfitting

[2] TRADES: https://github.com/yaodongyu/TRADES/

[3] AWP: https://github.com/csdongxian/AWP

[4] RWP: https://github.com/ChaojianYu/Robust-Weight-Perturbation
