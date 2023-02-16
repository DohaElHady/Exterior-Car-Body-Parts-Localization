# Car Exterior Body Parts Localization
<a href="https://colab.research.google.com/drive/1J_-m4f9Daur02IENObVmD1rCqaJNuMlb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"></a>

A deep learning-based project that aims to localize 14 exterior car body parts in case of no or partial damage.<br>
The project was implemented using both Yolov5 and Yolov8.


## Dataset Sources

1.   [DSMLR Body Parts Segmentation Dataset Github.](https://github.com/dsmlr/Car-Parts-Segmentation)
2.   [CompCars Dataset.](http://mmlab.ie.cuhk.edu.hk/datasets/comp_cars/)
3.   [Stanford Cars Dataset.](https://ai.stanford.edu/~jkrause/cars/car_dataset.html)
4.   [Used cars Auction Nation live auctions.](https://www.auctionnation.co.za/)

## Project Approach
1.   The data collected from sources 2-4 were manually annotated using [Microsoft VOTT](https://github.com/microsoft/VoTT).
2.   Annotations from source 1 were edited and the labels out of intreset were removed.
3.   Data was splitted over train, validation, and test.
4.   Transfer learning was deployed as Yolov5 and Yolov8 state-of-the-art object detection CNNs were tuned and trained.

## Repo Content 
1.   How to use guide :  [setup.md](https://github.com/DohaElHady/Exterior-Car-Body-Parts-Localization/blob/main/setup.md)
2.   Source code as jupyter notebook : [BodyParts.ipynb](https://github.com/DohaElHady/Exterior-Car-Body-Parts-Localization/blob/main/BodyParts.ipynb)
3.   Detailed compare between Yolov8 and Yolov5 results : [results_discussion.md](https://github.com/DohaElHady/Exterior-Car-Body-Parts-Localization/blob/main/results_discussion.md)


## Results
The model was capable of detecting the body parts even the partially damaged.

https://user-images.githubusercontent.com/86476979/219038155-2b06ce05-1b03-4029-9d80-a579961bc420.mp4



## Contributors
[Doha ElHady](https://github.com/DohaElHady) - [Mohamed Elahl](https://github.com/MohamedElahl) - [Hassan Mohamed](https://github.com/Hsnmhmd) - [Karim Youssef](https://github.com/KarimYoussef98)

## Dataset
The intial dataset is availble at [DSMLR Body Parts Segmentation Dataset.](https://github.com/dsmlr/Car-Parts-Segmentation)

The complete dataset manipulated and manually annotated is available upon request.

[Request complete dataset!](mailto:dohaelhady14@gmail.com,zezo.elahl@gmail.com,hassan.mohamed21997@gmail.com,karimbadreldin98@gmail.com?subject=Request%20Body%20Parts%20Dataset) 
