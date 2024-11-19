# EX04

# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 양지웅
- 리뷰어 : [이예지](https://github.com/ilxxixxli)

# PRT(Peer Review Template)
- [V]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - ![image](https://github.com/user-attachments/assets/0bce2bbc-84d6-444c-940d-56997658abb3)

    
- [V]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - ![image](https://github.com/user-attachments/assets/9cfe4aef-59d7-410b-9486-b3bcdec940de)
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 : 마스크를 만드는 것이 가장 중요하기 때문에
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 : 주석은 따로 달려있지 않지만, 위 쪽 코드에서 참조가 가능하고, 중요하지만 간결하게 잘 작성되어있습니다.
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인 : 주석으로 기재되어있지않으나 코드로 간결하게 작성되어있어 이해가 잘 됩니다.
    - 주석을 보고 코드 이해가 잘 되었는지 확인 : 확인했습니다.
        
- [V]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - ![image](https://github.com/user-attachments/assets/dbde0fe7-724b-42fd-af01-4e8dd0b74d4c)
    - 팔목을 보틀로 인식하는 문제 확인 후, 팔목에 가우시안 블러링을 적용했습니다.
    - ![image](https://github.com/user-attachments/assets/3464ecbf-b2f5-4593-bd33-6aff67165d8e)
    - 이후 추가적인 문제(팔을 인식하기 어려워하는)가 발생했으나, 블러링 커널 사이즈를 적정한 값으로 찾아내었습니다.

        
- [V]  **4. 회고를 잘 작성했나요?**
     [image](https://github.com/user-attachments/assets/0c0fc5ef-d235-4848-bb11-70d0425e1fcc)
    - 잘 작성되어 있습니다.
        
- [V]  **5. 코드가 간결하고 효율적인가요?**
      - 전체적으로 아주 간결하고 효율적으로 작성되어 있습니다.


# 회고(참고 링크 및 코드 개선)
```
모델에 대한 이해를 바탕으로 다양한 시도를 해보신 점이 인상적입니다.
크로마키 실험에서는 제한사항을 실험 전에 명확하게 기재하여 실험의 목적과 과정을 명료히 표현해 주셔서 전문적으로 실험을 진행하셨다는 느낌이 듭니다!
많은 것을 배우는 것 같습니다. 오늘 실험 하시느라 고생 많으셨습니다!


```

