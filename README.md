# parking_detector

Задание
https://docs.google.com/document/d/196_Fr4nuO0bFKPVk8GvsBLnsUsS7iIPvRQWMYy1eGpk/edit

## ParkingLot

https://github.com/olgarose/ParkingLot

Детекция свободных мест на парковке

https://www.youtube.com/watch?v=SszV59YBn_o


```
cd ParkingLot/parking_lot/

python3 main.py --image images/ufanet2.png --video videos/ufanet2.mp4 --data data/coordinates_ufanet2.yml --start-frame 1

```

Выход из скрипта создания координат, клавиша Q.


## DetectParking

Создан yml файл для демо видео datasets/ufanet2.yml

```
cd DetectParking/python
python ufanet.py
```

## Vechicle_Tracking

Не работает на статичных машинах нейронка.

Завелась только с
```
opencv-contrib-python==3.3.1.11
Keras==1.2.2
tensorflow==1.13.1
```
и изменить на  tracker = cv2.TrackerKCF_create()


#### Другие не исследованные

Нейронки:

* https://github.com/fabiocarrara/deep-parking
* https://github.com/umass-cds/DSFG-Parking-Utilization
* https://github.com/lalona/parking-spot-classifier
* https://github.com/amiltonwong/mil_deep_park
* https://github.com/Pranalirawool/parkingApp
* https://towardsdatascience.com/find-where-to-park-in-real-time-using-opencv-and-tensorflow-4307a4c3da03
* * https://github.com/priya-dwivedi/Deep-Learning/blob/master/parking_spots_detector/identify_parking_spots.ipynb
* https://medium.com/geoai/parking-lot-vehicle-detection-using-deep-learning-49597917bc4a


OpenCV:

* https://github.com/eladj/detectParking
* https://github.com/Milap7/Car-Parking-System-using-OpenCV?files=1
* https://github.com/charakanibm/RWProject_OpenCV
* https://github.com/csaiprashant/parking_lot_vacancy_detector
* https://github.com/luispaulot/DetectParking

Map car detector:

* https://github.com/ahmetozlu/vehicle_counting_tensorflow
* https://github.com/xiaochus/Vehicle_Tracking

Статьи:

* https://github.com/rugbyprof/Parking-Lot-Occupancy-Tracking
* https://lafi.github.io/LPN/



Other:

* https://github.com/bmzhao/opencv-testing
