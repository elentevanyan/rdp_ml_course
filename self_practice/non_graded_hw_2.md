# Самостоятельное задание 2.

## Задание 1.

Возьмите датасет kc_house_data. Можно сделать это задание сразу в тетрадке, где мы разбирали этот датасет.
Обучите регрессионное дерево на этих данных. 
Вам нужна функция DecisionTreeRegressor().
Посчитайте MAE. Сравните с результатами линейной регрессии. 

## Задание 2.

	Реализуйте функцию стохастического градиентного спуска для функционала MSE. Для реализации вам понадобится градиент, который в матричной форме выглядит следующим образом:
∇Q(w)=2X^T (Xw-y)

Назовите функцию stochastic_gd, входные параметры:
	step_size – размер шага
	w – начальные веса
	cnt_steps – количество шагов градиентного спуска
	X – матрица признаков
	y – вектор целевой переменной
	Примените написанную функцию к данным задачи kc_house_data
  
Критерий останова - на ваш выбор.