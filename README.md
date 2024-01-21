# ФИО: Бойматов Юсуфджон Шухратович
# Предмет: Обработка и генерация изображений
## Домашнее задание №2: Аномалии

На первый взгляд показалось несложно, но с нюансами пришлось изголяться порядочно. Некоторые фичи позаимствовал у решений на кагле, но вот, например, аттеншн маска- чисто мое решение.

В итоге почти удалось достичь требуемых метрик:

#### TPR: 0.9224806201550387, TNR: 0.9086766712141883 with threshold = 0.000634

Аугментация, пайплайн, подбор трешхолда - все есть в [ноутбуке](hwanomaly.ipynb). 

 ### График обучения:
![image](https://github.com/PikaChuChuMF/ImageProcessing2/assets/138888156/1532dc90-e43e-4b76-b945-30a41dbeda14)

 ### График подбора трешхолда:    
 ![image](https://github.com/PikaChuChuMF/ImageProcessing2/assets/138888156/f80891ed-7cb6-4709-964e-84199fa9fb60)

## Домашнее задание №1: Многоклассовая классификация

Классическая задача, решение подсматривал немного на каггле, добавил чутка специй. 

Старался оформлять ноутбук аккуратно. 

Результаты: 

   precision    recall  f1-score   support

           0       0.78      0.90      0.84      1000
           1       0.92      0.90      0.91      1000
           2       0.76      0.74      0.75      1000
           3       0.71      0.63      0.67      1000
           4       0.83      0.76      0.80      1000
           5       0.74      0.77      0.76      1000
           6       0.85      0.84      0.85      1000
           7       0.84      0.88      0.86      1000
           8       0.88      0.90      0.89      1000
           9       0.88      0.87      0.87      1000

    accuracy                           0.82     10000
   macro avg       0.82      0.82      0.82     10000
weighted avg       0.82      0.82      0.82     10000

Сводка по классам:

![image](https://github.com/PikaChuChuMF/ImageProcessing2/assets/138888156/cc15d2f7-5a97-42db-9a71-5d5e70229e52)

Матрица ошибок:


![image](https://github.com/PikaChuChuMF/ImageProcessing2/assets/138888156/e2f2d5d5-4f22-400d-be4e-255300a4aed2)

Пример изображений с результатми классификации 

(я спациально выбрал не самые удачные кейсы, чтобы было видно, на чем модель ошибается)


![image](https://github.com/PikaChuChuMF/ImageProcessing2/assets/138888156/f1138733-29cf-41ab-ad2a-1a62f5746bca)

Графики c wandb:









 

