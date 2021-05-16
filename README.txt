## 层数3，学习率 0.0001，其他都是默认参数
## result 可查看log文件下test结果
## gowalla 'recall': 0.1575, 'ndcg':0.13343
## amazon-book 'recall': 0.0339, 'ndcg': 0.0261
## 层数为4，未验证。
python train.py --dataset gowalla --lr 0.0001
python train.py --dataset amazon-book --lr 0.0001 