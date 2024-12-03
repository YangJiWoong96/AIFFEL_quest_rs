# EX07

# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 양지웅
- 리뷰어 : 김준석


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부  
        <img width="450" alt="image" src="https://github.com/user-attachments/assets/e8b44969-d607-4865-9a65-2a6899fd604c"><br>
        <img width="550" alt="image" src="https://github.com/user-attachments/assets/8a9b4359-40b9-4f97-b423-16f540e4d415"><br>
        -> 데이터셋 확인 및 라벨의 특징을 파악한 점이 인상깊었습니다.  
        <img width="271" alt="image" src="https://github.com/user-attachments/assets/e8285f50-123e-4c57-a500-58822eb024e8"><br>
        -> 한국어 문장에선, korean_contraction을 따로 설정할 필요가 있는데, 위 부분에서 적절하게 GPT를 활용하여 전처리 한 점이 좋았습니다.  
        <img width="585" alt="image" src="https://github.com/user-attachments/assets/42b15104-b46f-46ae-ba03-18229de68c64"><br>
        <img width="559" alt="image" src="https://github.com/user-attachments/assets/b87a51f7-c459-41d6-ae1b-32a69ff16f55"><br>
        -> 트랜스포머 모델을 구축 및 학습을 원할히 진행하였고, 추가적인 코멘트를 잘 남겨두셨습니다.  
        <img width="505" alt="image" src="https://github.com/user-attachments/assets/0734b146-3cc5-446a-b54e-408ff8ddee3d"><br>
        -> 한국어 입력문장에 대한 함수를 잘 구현하였습니다.  
    
- [O]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
        <img width="548" alt="image" src="https://github.com/user-attachments/assets/eaab4264-885d-4ea6-bbe0-27dfcc18caaa"><br>
        -> 모델을 구축하기 전, 전처리에서 데이터의 특성을 파악한 점이 훌륭하다고 생각합니다! 위 과정이 추후 모델의 성능 향상에 도움이 됐을 수 있다고 생각합니다.  

        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
        - <img width="558" alt="image" src="https://github.com/user-attachments/assets/b3d070c7-1466-4bd6-ac7c-8300cbb7f822">
        
- [O]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부   
          <img width="400" alt="image" src="https://github.com/user-attachments/assets/9ca567a2-ef66-41e9-b129-452d49ddc44d"><br>
          <img width="644" alt="image" src="https://github.com/user-attachments/assets/a5c96dc6-4181-458b-8f00-d36012afa385"><br>
          <img width="435" alt="image" src="https://github.com/user-attachments/assets/3c44479c-a4a1-4c2f-ad80-9cf149105017"><br>
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부  
        -> 리뷰어 입장에서 이해하기 쉽게 코드를 구현하셨고, 중간중간 결과물에 대한 생각을 잘 정리해 주셨습니다.

# 회고(참고 링크 및 코드 개선)
모델 성능 개선에 있어, 저는 모델의 크기만 생각하고 더이상 전처리에 대해서는 신경쓰지 않았는데, 지웅님 코드를 보며 데이터 전처리의 중요성을 다시금 느끼게 됐습니다! 아이디어를 구현하시는 점도 특히 좋았습니다. 오늘도 고생많으셨습니다!
