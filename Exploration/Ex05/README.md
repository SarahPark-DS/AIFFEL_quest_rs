# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 박세희
- 리뷰어 : 양지웅


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
     * RNN 분석
     ![image](https://github.com/user-attachments/assets/3ba60941-6552-4e41-8ed7-246d039ff4b5)

     * CNN 분석
     ![image](https://github.com/user-attachments/assets/bbe9ddfb-b094-4968-a834-de2b9cdc7f15)

     * Gloval max pooling 분석
     ![image](https://github.com/user-attachments/assets/4071832f-6f04-4fc3-8515-0ba37d14a069)

     * 사전학습된 임베딩을 통한 분석
     ![image](https://github.com/user-attachments/assets/f28de7ba-ef8e-4697-ac5d-af45c51af37e)

- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    * 사전학습된 임베딩을 활용하기 전에 분석을 진행하였다.
    ![image](https://github.com/user-attachments/assets/24bb3f3f-9ec4-4e6e-823d-e7629e92e5b7)

- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    * 추적을 통한 콜백 활용
    ![image](https://github.com/user-attachments/assets/dee009ca-32cf-4e3c-9ec0-082c582aef68)
      
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
    ![image](https://github.com/user-attachments/assets/eec52257-e544-49ac-b5d0-02a4d5209c9c)
    * 추가 시도 및 인사이트 도출을 위한 결론 및 회고를 다음과 같이 작성하였다. 

- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부


    * 전체적으로 간결하고 비교 분석을 위한 그래프가 적절하게 활용되었다.
    ![image](https://github.com/user-attachments/assets/0ed3d6e7-623b-4278-8750-fd38c74bb69c)


# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
세희님,사전 임베딩 라이브러리를 뜯어내서 관계를 분석한 시도가 굉장히 흥미로웠습니다. 비교분석도 깔끔하고 굉장히 많은 인사이트를 도출하려고 노력하신게 딱 보입니다!! 고생하셨습니다.
