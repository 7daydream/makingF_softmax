# Making_F Softmax Classification을 이용한 진로추천 모델 구현

> 환경
> Python : 3.8.3
> Tensorflow : 2.3.1
> Numpy : 1.18.5
> Pandas : 1.0.5

> 사용한 데이터셋
> 1350개의 데이터로 구성
> 각 과목별 관심도 : 앞 7개의 column, 0~10까지의 데이터로 구성
> 추천 직업 : 뒤의 5개의 column, one-hot incoding 적용
> Train data, Test data로 구분

따라서 만들어진 모델은 7개의 input, 5개의 output 노드를 가지는 모델
현재 정확도는 높은 수준이 아니어서 추가적인 개선 작업 예정
