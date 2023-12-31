# MACD - Moving Average Convergence Divergence

MACD (схождение - расхождение скользящих средних) показывает силу тренда и указывает на изменение направлений тренда.

При восходящем тренде текущая цена выше, чем средняя цена за выбранный период времени. При нисходящем тренде, наоборот, текущая цена ниже, чем ее усредненное значение за некоторый промежуток времени.

Динамику средних ценовых значений можно отобразить на графике в виде линии. Такая линия называется скользящей средней, или moving average. При восходящем тренде график цены проходит выше скользящей средней, а при нисходящем — ниже. Пересечение ценовым графиком скользящей средней может означать смену тренда. Значит, трейдеру нужно просто наблюдать, когда цена пересечет линию скользящей средней, и покупать или продавать бумаги в зависимости от направления пересечения. На этом строится стратегия торговли на скользящих средних.

Но у этой простой стратегии есть и недостатки — из-за случайных колебаний цен будут и случайные пересечения ценовым графиком скользящей средней, что может давать ложные сигналы к покупке или продаже.

Чтобы устранить ошибку, можно вместо графика цены наблюдать за пересечением скользящих средних с коротким и длинным периодом. Например, смотреть, как скользящую среднюю за 12 дней пересекает не график цены, а более сглаженная линия, построенная по средним значениям цены, к примеру, за 5 дней. Это работает потому, что скользящая средняя всегда более плавная в отличие от ценовых графиков, так как усреднение сглаживает скачки цен.

[Реализация MACD в Python](https://colab.research.google.com/drive/1_UK3ooJDcxHRan2oo1hclTIqoMXl9nU9?usp=sharing)
