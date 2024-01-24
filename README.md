## Environment Requirement
The code has been tested running under Python 3.6.5. The required packages are as follows:
* tensorflow == 1.11.0
* numpy == 1.14.3
* scipy == 1.1.0
* sklearn == 0.19.1
* cython == 0.29.15


### Cross-Domain Recommendation Command
* Command
```
python LightGCN.py --dataset_s {sourse_domain} --dataset {traget_domain}  --regs [1e-4] --embed_size 64 --layer_size [64,64,64] --batch_size 2048 --pretrain -1 --save_flag 0 --lr 0.00001 --beta 1
```

