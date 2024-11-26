# EX06

# AIFFEL Campus Online Code Peer Review Templete
- 코더 : __양지웅__
- 리뷰어 : __정우철__


# PRT(Peer Review Template)
- []  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 생성된 모델로 학습 진행 확인
![image](https://github.com/user-attachments/assets/279bdadc-78e4-49b9-a4f2-78f309307fc3)
    - summa 을 이용한 추출 요약 진행
![image](https://github.com/user-attachments/assets/57386d02-41f7-4201-90bc-c96a59005074)

    
- [ ]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - LSTM + Attention을 Transformer 기법으로 바꿔 진행 -- 대단...!!
![image](https://github.com/user-attachments/assets/60865bf1-143c-47b3-9875-bf58a268a252)
![image](https://github.com/user-attachments/assets/2bbb1a91-917c-4334-90a6-864cad2658f1)
![image](https://github.com/user-attachments/assets/c99470cb-d09b-4e17-ae6a-875a1f3b4ed7)


    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [X]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 인코더 디코더 분리 부분에서 에러발생, 추정원인 기록
![image](https://github.com/user-attachments/assets/fefb3e97-9af0-457a-8fff-f9333b29df85)
    - 텍스트 전처리 함수 튜닝
![image](https://github.com/user-attachments/assets/51f731f0-cfb2-456f-b40d-53fdd7a75d44)
    - 빈도 역빈도 계산 추가
![image](https://github.com/user-attachments/assets/53a9b4b5-ce6b-49d1-934e-fa0644a532d4)
![image](https://github.com/user-attachments/assets/df730d6f-07a8-44da-b992-32277cd1e104)

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 마지막 결과 도출 후 추기 실험 요하는 부분 정리
![image](https://github.com/user-attachments/assets/796626a6-bfd3-48c9-9822-4dd36c03d030)

        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - 모델 빌딩 함수 활용
![image](https://github.com/user-attachments/assets/79330f5d-6850-4a84-bba7-77fe35dd7b4f)



# 회고(참고 링크 및 코드 개선)
```
빠꾸없는 트랜스포머 감동입니다.
```

아니야

나는 그렇게 생각안해.  나는 
