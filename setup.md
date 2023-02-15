1.   Arrange the dataset in the following structure.
```
carDamageDataset
|
|_ train
|    |
|    |_ labels 
|    |      |_ .txt train images labels
|    |
|    |_ images 
|           |_ .jpg/.JPEG test images
|
|_ test / val (same as train)
```    
2.   Clone Yolov5 GitHub [repository](https://github.com/ultralytics/yolov5), install [dependencies](https://github.com/ultralytics/yolov5/blob/master/requirements.txt) and check PyTorch and GPU.
3.   Create the data.yaml for the dataset location and labels.
4.   Edit the global variables and run the [notebook](https://colab.research.google.com/drive/1FZOthiKvyGF50wGMABCTrBgC9__PxK-n?authuser=8#scrollTo=DaF94XwbKF_R).
