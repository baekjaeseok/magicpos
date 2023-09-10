![magicpos_title](https://github.com/baekjaeseok/magicpos/assets/133929822/848f4869-16e1-46cb-be3a-cc7bd5c4770e)
1인 자영업자의 비율은 꾸준히 상승 중입니다.
2022년 11월 기준으로 고용원이 없는 1인 자영업자의 수는 435만을 넘어섰고 
앞으로도 1인 자영업자의 비율은 증가 될 것으로 예측됩니다.
1인 자영업자의 증가 이유로는 첫 번째 산업구조의 디지털화로 인해 키오스크 등 업무를 보조해주는 기계의 등장으로 1인 자영업에 대한 불편함이 많이 해소되었기 때문입니다.
두 번째로는 취업난의 이유로 창업의 비용 적게든다, 위험부담이 적다는 인식속에 나홀로 창업에 도전하는 비자발적 창업이 늘어남에 따라 1인 자영업자가 늘고 있습니다.
마지막으로 가장 큰 요인인 최저임금의 인상 있습니다. 
이러한 이유들로 인하여 1인 자영업자의 수가 급격하게 증가하는 추세입니다.
1인 매장을 운영함에 있어서 운영에 필요한 손님응대, 조리, 설거지 등 모든 업무를 혼자서 담당해야 합니다. 
특히 요리 중 주문을 받게 되면 장갑을 벗고 손을 씻는 등 시간 및 자원 낭비가 생기는데 불편함을 느끼고 있고 이러한 번거로운 행동으로 인해 교차오염 발생에 대한 우려가 발생합니다.
이러한 교차오염을 방지하기 위해 기존의 포스기에 사용자의 모션을 인식해 비접촉으로 포스기를 조작할 수 있는 서비스를 제작하기로 했습니다.
#### 기술 스택
* Spring Framwork
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

  
