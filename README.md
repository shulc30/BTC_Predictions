# BTC_Predictions
Прогнозирование Btc с использованием LSTM

Долговременная кратковременная память — это архитектура искусственной рекуррентной нейронной сети, используемая в области глубокого обучения. В отличие от стандартных нейронных сетей с прямой связью, LSTM имеет связи с обратной связью. Он может обрабатывать не только отдельные точки данных, но и целые последовательности данных. Сети с долговременной кратковременной памятью (LSTM) представляют собой тип рекуррентной нейронной сети, способной изучать зависимость порядка в задачах прогнозирования последовательности. Это поведение требуется в сложных предметных областях, таких как машинный перевод, распознавание речи и т. д. LSTM — сложная область глубокого обучения. LSTM часто называют причудливыми RNN. Ванильные RNN не имеют состояния ячейки. У них есть только скрытые состояния, и эти скрытые состояния служат памятью для RNN. Между тем, LSTM имеет как состояния ячеек, так и скрытые состояния.
____
- [X] Для того чтобы проект заработал зарегестрируйтесь на Binance и добавьте свои api_key и api_secret для получения котировок
~~~python
api_key = ''  
api_secret = ''
client = Client(api_key, api_secret, testnet=True)
~~~
