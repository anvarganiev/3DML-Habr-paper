# Введение в 3D machine learning
![](https://miro.medium.com/max/1400/1*dz0fqQ1KBqIYGexQ_I4SpA.jpeg)
## Содержание
В репозитории содержится код с примерами для заметок по 3D ML на [хабр](https://habr.com/ru/company/itmai/blog/503358/).

1) В ноутбуке `3dml_habr_phygitalism.ipynb` содержатся примеры коды для частей 1, 2.

2) В ноутбуке `raymarch_sdf.ipynb` содержится двумерный пример визуализации объектов, описываемых SDF функциями.
___
## Работа с кодом

Локальная работа с кодом расчитана на ОС семейства Linux. C PyTorch 3D есть проблемы при работе в Windows.

Для того, чтобы работать с кодом локально, прилагается файл `requirements.txt` со всеми необходимыми зависимостями.

Рекомендуемая версия Python 3.6+

Для установки достаточно выполнить команду:
```
pip install -r requirements.txt
```

При локальной работе с ноутбуком `3dml_habr_phygitalism.ipynb` не стоит выполнять первую ячейку с установкой зависимостей, если вы уже установили их с помощью `requirements.txt`.

Пример полигональной модели `bunny.obj` находится в директории `data`.

Для работы с кодом без локальной установки библиотек, можно запустить jupyter notebook `3dml_habr_phygitalism.ipynb` с помощью [Google colab](https://colab.research.google.com/).
___
## Источники
Дополнительно прочитать документацию основных рассмотренных фреймворков для работы с 3D данными можно прочитать на домашних страницах проектов:
- [pytorch3d](https://github.com/facebookresearch/pytorch3d)
- [trimesh](https://github.com/mikedh/trimesh) 
  
Больше интересных материалов по работе с 3D, сканированию и технологиям XR можно найти в нашем блоге на [Medium](https://medium.com/phygitalism).
