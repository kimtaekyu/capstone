# capstone
Use Hw for submit
Dataset Can download Here (https://www.kaggle.com/competitions/lanesegmentationchallenge/data)
```
pip install -r requirement.txt  
```
ASPP 

| ASPP    | base model | VGG | resnet                         |
| ---------- | ---------------------------------------------- |
| No | 0.384          |  0.626|         0.625 |
| Yes |  0.1          |  0.18|         0.19 |

skip-connection

| skip connection    | base model | VGG | resnet                    |
| ---------- | ---------------------------------------------- |
| No | 0.384          |  0.626|         0.625 |
| Yes |  0.01          |  0.09|         0.11 |

Augmenataion 
| jitter | base model | VGG | resnet                    |
| ---------- | ---------------------------------------------- |
| No | 0.384          |  0.626|         0.625 |
| Yes |  0.42          |  0.664|         0.66 |

| flip  | base model | VGG | resnet                    |
| ---------- | ---------------------------------------------- |
| No | 0.384          |  0.626|         0.625 |
| Yes |  0.28        |  0.42|         0.42 |
