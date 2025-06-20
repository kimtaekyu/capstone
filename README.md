# capstone
Use Hw for submit
Dataset Can download Here (https://www.kaggle.com/competitions/lanesegmentationchallenge/data)
```
pip install -r requirement.txt  
```
## 1. ASPP 적용 여부 epoch 1
| ASPP | Base Model | VGG   | ResNet |
| ---- | ---------- | ----- | ------ |
| No   | 0.384      | 0.626 | 0.625  |
| Yes  | 0.100      | 0.180 | 0.190  |

## 2. Skip-Connection 적용 여부 epoch 1

| Skip Connection | Base Model | VGG   | ResNet |
| --------------- | ---------- | ----- | ------ |
| No              | 0.384      | 0.626 | 0.625  |
| Yes             | 0.010      | 0.090 | 0.110  |

## 3. Color Jitter 증강 효과 epoch (5) 

| Jitter | Base Model | VGG   | ResNet |
| ------ | ---------- | ----- | ------ |
| No     | 0.384      | 0.626 | 0.625  |
| Yes    | 0.420      | 0.664 | 0.660  |

## 4. Horizontal Flip 증강 효과 epoch (5)

| Flip | Base Model | VGG   | ResNet |
| ---- | ---------- | ----- | ------ |
| No   | 0.384      | 0.626 | 0.625  |
| Yes  | 0.280      | 0.420 | 0.420  |
