# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 코더의 이름을 작성하세요.
- 리뷰어 : 리뷰어의 이름을 작성하세요.


# PRT(Peer Review Template)
- [ ]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/f2486f25-b72f-4f67-9a81-5ae70b925057)
        - 외에도 RandomForest, linearSVC, CalibratedCV, Voting-soft, RNN등 다양한 모델들로 accuracy 및 f1-score 지표를 보여주셨습니다.
        - 모든 지표들을 dataframe형태로 저장하거나 시각화하면 한눈에 보기 편해서 추천드려요

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/92a4b6f2-f0b7-4908-902f-7bb277103431)
        - voting 하기위해서 예측값을 보정하는 작업을 잘 작성해주셨습니다.

        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/8fb474d2-1696-40a6-b3ec-768a0750ec4e)
        - ![image](https://github.com/user-attachments/assets/5568026c-2710-4b4d-a375-7a0e59cf38be)
        - linear svc의 경우 확률 예측값을 제공하지 않아서 calibratedclassiifierCV 클래스를 활용하여 해결하는점이 인상깊었습니다.


        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/aa106ce4-51ff-447a-87c1-fd2302b1fbb6)
        - 저는 모든 코드에서 Voting이 제일 좋게 나왔는데 같은 파라미터지만 다른 모델 조합으로 최고 성능 모델이 바뀐점이 인상깊었습니다.
        - 시간적 측면이나 성능으로 봤을때 저도 LogisticRegression이 좋다고 생각했습니다.

        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/aecce982-9c70-4bda-85ab-045e9fefad09)
        - 딥러닝 모델에서 데이터를 처리할떄 간결하게 코드 잘 작성해주셨습니다.


# 회고(참고 링크 및 코드 개선)
```
vocab_size를 늘려가면서 잘 실험해주셔서 마지막에 성능 비교하기 편했습니다.
저는 Gradient Boosting 모델을 선택했는데 제가 하지 못한 linearSVC, CalibratedClassifierCV를 활용한 지표도 간접적올 도움이 많이 되었습니다.
수고많으셨습니다.
```
