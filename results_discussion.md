# Yolov5 vs Yolov8 Results Discussion
In this experiment, Yolov8 nano and Yolov5 nano models were trained for car body parts detection.<br>
Yolov8 results were higher than Yolov5 in nearly all aspects as inference time, mean average precision(mAP), and True Positives Rate (TPR);
however, Yolov8 took 6x the training time of Yolov5 on the same data, which reflects the extensive computational capabilities required for v8.

## Rusults Details
**Train Time:**<br>
Both models were trained for 100 epochs, 16 batch size, 640 image size, 1840 train images, and 220 validation images.<br>
* _Yolov5_: 30 Minutes, 36 Seconds<br>
* _Yolov8_: 3 Hours, 14 Minutes, 42 Seconds<br>

**Inference Time:**<br>
At image shape (1, 3, 640, 640)<br>
* _Yolov5_: 0.6ms pre-process, 11.2ms inference, 1.2ms NMS per image <br>
* _Yolov8_: 0.3ms pre-process, 2.5ms inference, 0.0ms loss, 3.7ms post-process per image<br>

**Validation Confusion Matrix:**<br>
* _Yolov5_:
![Yolov5_CM](https://user-images.githubusercontent.com/86476979/219353702-1741f0d8-99b3-44b6-a423-df348036a36d.png)

* _Yolov8_:
![Yolov8_CM](https://user-images.githubusercontent.com/86476979/219353729-abede686-1d93-4025-864e-f1cc413e648c.png)

**Validation PR Curve:**<br>

* _Yolov5_:
<img width="1038" alt="Yolov5_PR" src="https://user-images.githubusercontent.com/86476979/219354458-b8ab7bfb-2d29-4176-adfa-f9cf83b570ef.png">

* _Yolov8_:
<img width="1046" alt="Yolov8_PR" src="https://user-images.githubusercontent.com/86476979/219354431-f0038155-2200-473e-81e5-3a3f455a5d70.png">
