# ФИО: Бойматов Юсуфджон Шухратович
# Предмет: Обработка и генерация изображений
## Домашнее задание №2: Аномалии

На первый взгляд показалось несложно, но с нюансами пришлось изголяться порядочно. Некоторые фичи позаимствовал у решений на кагле, но вот аттеншн маска- чисто мое решение.

В итоге почти удалось достичь требуемых метрик:

#### TPR: 0.9224806201550387, TNR: 0.9086766712141883 with threshold = 0.000634

Аугментация, пайплайн, подбор трешхолда - все есть в [ноутбуке](hwanomaly.ipynb). 

 ### График обучения:
![image](https://github.com/PikaChuChuMF/ImageProcessing2/assets/138888156/1532dc90-e43e-4b76-b945-30a41dbeda14)

 ### График подбора трешхолда:    
 ![image](https://github.com/PikaChuChuMF/ImageProcessing2/assets/138888156/f80891ed-7cb6-4709-964e-84199fa9fb60)

 

