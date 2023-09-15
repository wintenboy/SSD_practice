# Dataset Download
```bash
# train dataset
wget http://images.cocodataset.org/zips/train2017.zip
# validation dataset
wget http://images.cocodataset.org/zips/val2017.zip
# annotations
wget http://images.cocodataset.org/annotations/annotations_trainval2017.zip
```
# Directory structure
```bash
├── SSD-pytorch
│   ├── checkpoints
│   │    └── SSD.pth
│   ├── coco
│   │    ├── annotations
│   │    ├── annotations_trainval2017
│   │    ├── train2017
│   │    └── val2017
│   ├── src
│   │    ├── __init__.py
│   │    ├── dataset.py
│   │    ├── loss.py
│   │    ├── model.py
│   │    ├── preprocess.py
│   │    ├── transform.py
│   │    └── utils.py
│   └── tensorboard

```