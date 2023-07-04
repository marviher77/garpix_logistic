# Исследовательская: анализ данных (“бигдата”) из системы GLS
В системе GLS накапливаются данные о грузах и грузовых пространствах, о достигнутых метриках качества укладки. 
Есть гипотезы о том, как использовать эти данные для решения некоторых задач повышения продуктивности GLS.

# Задача на практике
- “развернутый вариант” предполагает выделить метрики геометрических характеристик грузов, на основе которых грузы можно было бы сортировать по контейнерам таким образом, чтобы плотность укладки с сортировкой была бы выше, чем без сортировки (отбор случайным образом); вариантом решения также может быть нейронная сеть обученная для выполнения данной задачи;
- “базовый вариант” - сделать модель (и естественно “закодить”), которая будет предсказывать значение плотности укладки грузов в контейнере (грузовом пространстве). 

# Требования к результату
- описание математической постановки выбранной задачи;
- описание выбранного метода решения задачи;
- написан программный код, реализующий описанный метод;
- приведена  документация достаточно подробная (минимально необходимая) для самостоятельного запуска кода.
