# Bangla-Handwritten-Digits-Datasets-NumtaDB-BanglaLekha-Ekush(Compressed and Ready to use) For Machine Learning
## Introduction

This Repository contains three Bangali Numeral Datasets and are preprocessed for Machine Learning Usage:
​
- [Bengali.AI NumtaDB](https://bengali.ai/wp-content/uploads/datasets/assembled-bangla-handwritten.pdf)
- [BanglaLekha](https://www.sciencedirect.com/science/article/pii/S2352340917301117)
- [Ekush](https://shahariarrabby.github.io/ekush/#home)
​

​
> - ০ , ১ , ২ , ৩ , ৪ , ৫ , ৬ , ৭ , ৮ , ৯
> - 0 , 1 , 2 , 3 , 4 , 5 , 6 , 7 , 8 , 9

## Dataset Description
The images are originally of size **[32 x 32]** but this repo the images are all resized into **[28 x 28]** dimension such that these datasets can easily used in the models where [MNIST](https://www.kaggle.com/c/digit-recognizer) Dataset are used. The datasets are resized and loaded in numpy array and then compressed. The sample images are shown below:
- [Bengali.AI NumtaDB](https://bengali.ai/wp-content/uploads/datasets/assembled-bangla-handwritten.pdf)
- [BanglaLekha](https://www.sciencedirect.com/science/article/pii/S2352340917301117)
- [Ekush](https://shahariarrabby.github.io/ekush/#home) <br>
 ![GitHub Logo](/img/numtaDB.png)<br>

 ![GitHub Logo](/img/banglalekha.png)<br>

 ![GitHub Logo](/img/ekush.png)<br>

## How to use

```bash
!git clone https://github.com/naimul011/Bengali-Numeral-Datasets-NumtaDB-BanglaLekha-Ekush.git
```

```python
from zipfile import ZipFile

with ZipFile('banglalekhaX_train.zip', 'r') as zipObj:
   
   zipObj.extractall()
```
```python
import numpy as np

train_x = np.load('banglalekhaX_train.npy')
```
