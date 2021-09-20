# Dimensionality Reduction

우리가 머신러닝을 위해 어떠한 데이터셋을 열어보았을 때 수천만개의 샘플과 수천개 아니 수십, 수백만개의 Feature를 만날 가능성을 낮지 않다. 아니 꽤나 높다. 이것은 훈련을 느리게 만들고 좋은 솔루션을찾기 어렵게 만든다.
이런 문제를 차원의 저주(curse of dimensionality)라고 말한다.
<br>
차원축소는 features를 결합하는 일이니 당연하게도 훈련 속도를 높일 수 있게 한다. 또한 차원을 엄청나게 축소한다면 시각화에도 아주 유용할 수 있을 것이다. 나는 시각화의 본질을 사람이 보기 편하게 만드는 것이라고 생각한다.
이를 통해서 어떠한 통찰을 얻어낼수도 있다. 물론 3차원이 넘어가는 경우에는 시각화의 효율이 급속도로 떨어진다. 그리고 수백, 수천개의 features를 2개, 3개로 축소시키는 것도 엄청난 리스크가 있는 행위일 것이다.
하여튼 차원축소는 훈련 속도, 시각화의 가능성 등을 만드는 기법 중 하나이다.

# 차원의 저주
