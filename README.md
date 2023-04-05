# Asymmetric Polynomial Loss for Multi-Label Classification

Source code for ICASSP 2023 paper: Asymmetric Polynomial Loss for Multi-Label Classification.

APL is one step further beyond [BCE-loss](https://pytorch.org/docs/stable/generated/torch.nn.BCELoss.html?highlight=bceloss#torch.nn.BCELoss), [ASL-loss](https://openaccess.thecvf.com/content/ICCV2021/html/Ridnik_Asymmetric_Loss_for_Multi-Label_Classification_ICCV_2021_paper.html), and [PolyLoss](https://arxiv.org/abs/2204.12511).

Our code is based on [ASL](https://github.com/Alibaba-MIIL/ASL).

## Quick Usage: 
1. Replace your torch.nn.BCELoss() or ASL-loss with APLloss.py.

2. Adjust the parameters according to the discussion in the paper. 

3. See the performance improvement.

