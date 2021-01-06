
## Week 2 - Logistic Regression as a Neural Network

1. Binary Classification

**Neural Network을 구현할 때 매우 중요한 몇 가지 기술**  

* for문을 돌리지 않고 m개의 training dataset을 처리하는 방법  
* 신경망 학습시 forward/backward propagation 사용 이유 

  * 로지스틱 회귀: 이진 분류를 위한 알고리즘
    > 예) 고양이 일 때는 1로, 고양이가 아닐 때는 0으로 레이블을 출력
<a href="http://img.etoday.co.kr/pto_db/2018/02/20180212094232_1185877_710_340.jpg"><img src="http://img.etoday.co.kr/pto_db/2018/02/20180212094232_1185877_710_340.jpg" width="500px" title="source: imgur.com" /></a>

$${ W }_{ ij }=exp\left( -\frac { d{ ({ x }_{ i },{ x }_{ j }) }^{ 2 } }{ 2\sigma^{2}  }  \right) $$
