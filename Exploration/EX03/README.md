# EX03

# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 양지웅
- 리뷰어 : 김하영


# PRT(Peer Review Template)
- [v]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 이번 프로젝트 문제인 사진속 얼굴이미지를 박싱하고 랜드마크를 찾은뒤 고양이 수염을 붙이는 과정이 모두 완성된 코드로 제출되었음
    - 아래 이미지는 해당 코드를 통해 문제를 모두 해결하고 도출된 최종 이미지임   
      ![image](https://github.com/user-attachments/assets/9c86d870-3ae7-425a-85e1-ee1a0016ba1e)

    
- [v]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 이번 프로젝트에서 얼굴의 detection과 그 위에 합성할 이미지를 다루는 것이 가장 어려운 부분이었음.
    - 얼굴 Detestcion 시 사용한 코드들을 기능별로 비교및 작동원리 기술이 잘 되어 있음.
      ![image](https://github.com/user-attachments/assets/ccf651cc-9c31-46ab-ad60-99def4e9ef21)


    - 고양이 콧수염 이미지의 투명도와 기울이는 정도에 대해 복잡한 부분을 코드로 단계별 설명이 있어 이해가 쉬었음
      ![image](https://github.com/user-attachments/assets/09c77523-bf92-4175-8ded-9155266ec052)

        
- [v]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제가 발생한 원인과 해결 과정을 단계별로 잘 기록하였음
      ![image](https://github.com/user-attachments/assets/667d5cb8-e1b1-442b-a4a1-4427a32c3af4)

      ![image](https://github.com/user-attachments/assets/115c0310-d7b8-40cf-8890-4156a3329ae6)

    - 새로운 시도이자 추가실험으로 노이즈가 많은 이미지에서 얼굴을 잘 감지하기위해
      이미지의 대비를 개선하는 방법을 비교함(Original, 히스토그램평활화, CLAHE 비교)
      ![image](https://github.com/user-attachments/assets/bbb68bb5-94d7-4e8f-bc42-820c05958482)

    
        
- [v]  **4. 회고를 잘 작성했나요?**
    - Face detection의 다양한 기법을 적용하여 서로 비교하고, 가장 좋은 방법을 정리하고 프로젝트를 수행하며 적용하였음
      ![image](https://github.com/user-attachments/assets/c231b0e9-8842-4ca9-b115-12ab577113f9)


        
- [v]  **5. 코드가 간결하고 효율적인가요?**
    - 코드를 간결히 하기 위해 반복사용되는 랜드마크 좌표 추출기능을 함수로 표현하여 사용하였음
      ![image](https://github.com/user-attachments/assets/9ee6c270-04d6-4d21-b39f-ad811d3dfc06)



# 회고(참고 링크 및 코드 개선)
```
# 지웅님의 프로젝트는 일부러 어려운 이미지에서 얼굴을 감지하는 실험이었다. 또한 다양한 이미지를 개선하는 기법을 서로 비교하며 이미지 분석전의 단계라 볼수 있는 이미지의 선명도부터 체크를 하면서 가장 좋은 방법을 찾아내는 부분 역시 인상깊었다. 또한 문제점과 해결방법에 대해 간력하면서도 명확하게 기록을 남겨두셔서 추후에 다시 보더라도 매우 유용할것 같다.
```

아니야

나는 그렇게 생각안해.  나는 
