![magicpos_title](https://github.com/baekjaeseok/magicpos/assets/133929822/848f4869-16e1-46cb-be3a-cc7bd5c4770e)
#### 기술 스택
* Spring Framwork 활용
* Java / JavaScript / Ajax
* HTML / CSS / JSP
* MySQL DB
* Python / COLAB / Pycharm
* Apache Tomcat v8.5
* Github

#### 담당
* 데이터베이스(MySQL)설계
* OpenCV와 MediaPipe를 활용한 데이터 수집, 데이터 전처리
* LSTM모델을 활용한 모델학습 및 평가

#### 데이터 수집
Open computer vision(OpenCV)와 Mediapipe hands 라이브러리를 이용하여 자체 데이터 수집
* 8개의 동작을 동작별로 30초씩 수집(동작별 15730개)
* 총 125000개 데이터 수집
* code location : create_dataset.py

#### 모델 학습
LSTM - tanh
![그림1](https://github.com/baekjaeseok/magicpos/assets/133929822/3d94188a-3d7b-4d70-b482-0c330ce59f2a)
* code location : train_tanh_seq30.ipynb

#### 모션인식
![magicpos](https://github.com/baekjaeseok/magicpos/assets/133929822/42c7e6a0-fa7a-4578-82a8-88f417a6812c)
* code location : gesture_control.py

  
