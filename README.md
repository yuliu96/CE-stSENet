# CE-stSENet
Original PyTorch implementation of "Epileptic Seizure Detection in EEG Signals Using a Unified Temporal-Spectral Squeeze-and-Excitation Network" (IEEE Transactions on Neural Systems and Rehabilitation Engineering 2020).

**Paper: [https://ieeexplore.ieee.org/document/8995501](https://ieeexplore.ieee.org/document/8995501)**

![CE-stSENet](https://raw.githubusercontent.com/YuLiu-web/CE-stSENet/main/Figures/CE-stSENet.png)

## Requirements
The code was implemented using Python 3.8.3 and the following packages:
- torch==1.4.0
- numpy==1.18.5
- scipy==1.5.0

## Datasets
CE-stSENet with maximum mean discrepancy-based information maximizing loss is evaluated on three public datasets:
- [Bonn Dataset](https://journals.aps.org/pre/abstract/10.1103/PhysRevE.64.061907)
- [TUSZ Dataset](https://www.isip.piconepress.com/projects/tuh_eeg/downloads/tuh_eeg_seizure/)
- [CHB-MIT dataset](http://archive.physionet.org/physiobank/database/chbmit/) 

## Main Results

![results](https://raw.githubusercontent.com/YuLiu-web/CE-stSENet/main/Figures/results.jpg)

## Citations
If you find the paper or this repo useful, please cite:
```
@ARTICLE{8995501,
  author={Li, Yang and Liu, Yu and Cui, Wei-Gang and Guo, Yu-Zhu and Huang, Hui and Hu, Zhong-Yi},
  journal={IEEE Transactions on Neural Systems and Rehabilitation Engineering}, 
  title={Epileptic Seizure Detection in EEG Signals Using a Unified Temporal-Spectral Squeeze-and-Excitation Network}, 
  year={2020},
  volume={28},
  number={4},
  pages={782-794},
  doi={10.1109/TNSRE.2020.2973434}}
```
## Contacts
For questions or help, feel welcome to write an email to [sy1803113@buaa.edu.cn](sy1803113@buaa.edu.cn) or [liyang@buaa.edu.cn](liyang@buaa.edu.cn).
