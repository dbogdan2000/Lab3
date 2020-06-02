# Lab3

В первым пунктом лабораторной работы было создание и обучение нейронной сети VGG16. Результаты обучения с разными параметрами:

1. BATCH_SIZE = 8, lr = 0.00000009

Метрики точности:

![Image alt](hhttps://github.com/dbogdan2000/Lab3/blob/master/1/V1_Acc.1:batch%3D8%2Clr%20%3D%200.00000009.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V1_Val_Acc.1:batch%3D8%2Clr%20%3D%200.00000009.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V1_Loss.1:batch%3D8%2Clr%20%3D%200.00000009.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V1_Val_Loss.1:batch%3D8%2Clr%20%3D%200.00000009.png)

2. BATCH_SIZE = 8, lr = 0.0000005

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V2_Acc.1:batch%3D8%2Clr%20%3D%200.0000005.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V2_Val_Acc.1:batch%3D8%2Clr%20%3D%200.0000005.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V2_Loss.1:batch%3D8%2Clr%20%3D%200.0000005.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V2_Val_Loss.1:batch%3D8%2Clr%20%3D%200.0000005.png)

3. BATCH_SIZE = 8, lr = 0.0000008

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V3_Acc.1:batch%3D8%2Clr%20%3D%200.0000008.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V3_Val_Acc.1:batch%3D8%2Clr%20%3D%200.0000008.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V3_Loss.1:batch%3D8%2Clr%20%3D%200.0000008.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V3_Val_Loss.1:batch%3D8%2Clr%20%3D%200.0000008.png)

4. BATCH_SIZE = 8, lr = 0.0000002

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V4_Acc.1:batch%3D8%2Clr%20%3D%200.0000002.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V4_Val_Acc.1:batch%3D8%2Clr%20%3D%200.0000002.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V4_Loss.1:batch%3D8%2Clr%20%3D%200.0000002.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/1/V4_Val_Loss.1:batch%3D8%2Clr%20%3D%200.0000002.png)


Вторым пунктом в данной работе нужно было провести обучение классификатора на предобученной на imagenet сети VGG16. В сети замораживались свёрточные слои. Результаты обучения:

1. BATCH_SIZE = 8, lr = 0.0000000009

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M1_Acc.2:batch%3D8%2Clr%20%3D%200.0000000009.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M1_Val_Acc.2:batch%3D8%2Clr%20%3D%200.0000000009.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M1_Loss.2:batch%3D8%2Clr%20%3D%200.0000000009.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M1_Val_Loss.2:batch%3D8%2Clr%20%3D%200.0000000009.png)


2. BATCH_SIZE = 8, lr = 0.00000001

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M2_Acc.2:batch%3D8%2Clr%20%3D%200.00000001.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M2_Val_Acc.2:batch%3D8%2Clr%20%3D%200.00000001.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M2_Loss.2:batch%3D8%2Clr%20%3D%200.00000001.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M2_Val_Loss.2:batch%3D8%2Clr%20%3D%200.00000001.png)


3. BATCH_SIZE = 8, lr = 0.00000007

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M3_Acc.2:batch%3D8%2Clr%20%3D%200.00000007.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M3_Val_Acc.2:batch%3D8%2Clr%20%3D%200.00000007.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M3_Loss.2:batch%3D8%2Clr%20%3D%200.00000007.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/2/M3_Val_Loss.2:batch%3D8%2Clr%20%3D%200.0000000009.png)


В третьем пункте нужно было разморозить свёрточные слои и использовать весовые коэффициенты из предыдущего пункта. Была выбрана третья модель из предыдущего пункта. Результаты обучения:

1. BATCH_SIZE = 8, lr = 0.000000001

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V1_Acc.3:batch%3D8%2Clr%20%3D%200.000000001.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V1_Val_Acc.3:batch%3D8%2Clr%20%3D%200.000000001.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V1_Loss.3:batch%3D8%2Clr%20%3D%200.000000001.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V1_Val_Loss.3:batch%3D8%2Clr%20%3D%200.000000001.png)


2. BATCH_SIZE = 8, lr = 0.00000000005

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V2_Acc.3:batch%3D8%2Clr%20%3D%200.00000000005.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V2_Val_Acc.3:batch%3D8%2Clr%20%3D%200.00000000005.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V2_Loss.3:batch%3D8%2Clr%20%3D%200.00000000005.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V2_Val_Loss.3:batch%3D8%2Clr%20%3D%200.00000000005.png)


3. BATCH_SIZE = 8, lr = 0.00000000009

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V3_Acc.3:batch%3D8%2Clr%20%3D%200.00000000009.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V3_Val_Acc.3:batch%3D8%2Clr%20%3D%200.00000000009.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V3_Loss.3:batch%3D8%2Clr%20%3D%200.00000000009.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V3_Val_Loss.3:batch%3D8%2Clr%20%3D%200.00000000009.png)


4. BATCH_SIZE = 8, lr = 0.00000000002

Метрики точности:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V4_Acc.3:batch%3D8%2Clr%20%3D%200.00000000002.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V4_Val_Acc.3:batch%3D8%2Clr%20%3D%200.00000000002.png)

Функции потерь:

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V4_Loss.3:batch%3D8%2Clr%20%3D%200.00000000002.png)

![Image alt](https://github.com/dbogdan2000/Lab3/blob/master/3/V4_Val_Loss.3:batch%3D8%2Clr%20%3D%200.00000000002.png)

