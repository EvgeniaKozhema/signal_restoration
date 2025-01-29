# Практическая часть курсовой работы Разработка архитектуры нейронной сети для восстановления радиосигнала
Включает 2 подчасти: 
- применение классических методов восстановления сигнала к практическим задачам;
- реализация VAE.
Вся реализация происходит на языке `Python` с использованием библиотек и сторонних модулей:
`matplotlib`, `scipy`, `statsmodels`, `sklearn`, `transformers`.
## Part 1
Теоретическая часть о классических методах восстановления сигнала, включает разбор:
- преобразование Фурье;
- вейвлет-преобразование;
- фильтры обработки сигнала: фильтр Кальмана, Буттерворта и Чебышева.
## Part 2
Разобранные в первой главе классические методы восстановления радиосигнала демонстрируются на практике:
- dft_practice
Восстановление зашумленного сигнала с помощью применения ДПФ.
- kalman_practice
Оценка истинного радиосигнала с помощью фильтра Кальмана на основе зашумленных наблюдений.
- wavelet_practice
Восстановление радиосигнала с потерянными данными с помощью вейвлет-преобразования.

## Part 3
