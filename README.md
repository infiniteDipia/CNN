# CNN MODELS
-------------------------------------


## **LeNet-5**

**framework**:Tensorflow,Keras

**DATASET**:*CIFAR-10*

**학습이미지**:50,000장

**테스트이미지**:10,000장

신경망 학습의 정확도와 손실 그래프


<img width="1189" height="390" alt="image" src="https://github.com/user-attachments/assets/7227b41c-6adf-4ccb-87e4-db44a1dee1b8" />


궁금증


1.x_train,x_test를 왜 flaot하고 255.0으로 나누는가?


2.dropout를 하는 이유


궁금증에 대한 나의 정리된 생각


1.신경망 내부의 계산에서 실수값이 나올 수 있기에 flaot으로 바꾸어주고 255.0으로 나누는 이유는 train과test해야하는 data크기가 크기에 수월하게 학습시키고 기울기 발산을 방지하기 위해 255.0으로 나눠서 픽셀 값을 0~1로 두면 신경망이 계산 중 오버피팅을 방지 할 수 있고 학습이 더 빠르게 가능하다.


2.신경망 학습 도중 나오는 오버피팅을 방지하기 위한 기법이다


한계점


신경망 층이 얕음으로 대규모 학습에 불리하다.

-------------------------------------

## **VGGNet**


<img width="1010" height="470" alt="download" src="https://github.com/user-attachments/assets/23975c50-ace8-4a7e-96ec-ec350d8a9f75" />
