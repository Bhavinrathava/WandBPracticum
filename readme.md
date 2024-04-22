# Experimentation Overview  

For this experiment, we are trying to tune the hyper parameters for the XG Boost algorithm. We are using the WandB logging to track the experiments.

Hyper-parameters chosen to tune : 
1. Learning Rate : [0.01,0.03, 0.1, 0.3, 0.5, 0.6, 0.7, 0.8, 0.9, 1.0, 1.2, 1.3, 1.4, 1.5 ]
2. Max Depth : [1,2,3,4,5,6]


- W and B Result link : https://api.wandb.ai/links/zero-monster/1s6p85rk
- Best Parameters : LR = 0.01 , Max Depth = 6

- Best Performance : RMSE on Validation Set = 533.2
- Original Best Performance : 549.10
- Improvement in Performance : 2% 