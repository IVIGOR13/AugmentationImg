# AugmentationImg
Раздутие набора данных из изображений для машинного обучения.
+ скрипт обрезки меток по .xml файлам созданным утилитой LabelImage для обработки алгоритмом.
+ скрипт разметки меток размером с изображение в .csv файл.

## Примеры искаженных изображений созданных программой
### Исходное изображение   
![Исходное изображение](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three.png)
### Искаженные:
Черно-белое иображение: 
![Черно-белое изображение](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_black-white.png)

Размытое изображение: 
![Размытое изображение](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_blur.png)

Сжатое изображение: 
![Сжатое изображение](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_compress.png)

Суженное изображение: 
![Суженное изображение](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_stretch.png)

Изображение с полосой: 
![Изображение с полосой](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_dark_strip_1.png)

Изображение с бликом: 
![Изображение с бликом](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_glare_1.png)

Зашумленное изображение: 
![Зашумленное изображение](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_noises.png)

Повернутое изображение: 
![Повернутое изображение](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_turn-10.png)

Примеры комбинированных искажений: 
![Наложено несколько эффектов](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_combo_0.png)
![Наложено несколько эффектов](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_combo_1.png)
![Наложено несколько эффектов](https://github.com/IVIGOR13/AugmentationImg/blob/master/example/image_three_combo_2.png)

# Установка

Клонирование репозитория
```
$ git clone https://github.com/IVIGOR13/AugmentationImg.git
```
Настройка 
```
$ pip3 install pillow
$ pip3 install opencv-python
$ pip3 install pandas
$ pip3 install numpy
$ pip3 install pyqt5
```
Запуск
```
$ cd AugmentationImg
$ python augmentImg.py
```
