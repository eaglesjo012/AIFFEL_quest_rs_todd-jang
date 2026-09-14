# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 장기훈
- 리뷰어 : 김나연


# PRT(Peer Review Template)
- [X]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 챗봇 훈련데이터를 위한 전처리와 augmentation이 적절히 수행되어 3만개 가량의 훈련데이터셋이 구축되었다.
        - <img width="732" height="507" alt="image" src="https://github.com/user-attachments/assets/246f782c-eb9e-4092-84ba-fc49912ffd61" />
    - 과적합을 피할 수 있는 하이퍼파라미터 셋이 적절히 제시되었다.
        - <img width="787" height="215" alt="image" src="https://github.com/user-attachments/assets/039165ca-6fe8-47b0-bb15-4034b3f6f110" />
    - 주어진 예문을 포함하여 챗봇에 던진 질문에 적절히 답하는 사례가 제출되었다.
        - <img width="502" height="672" alt="image" src="https://github.com/user-attachments/assets/d644a20e-afa2-4350-a73c-93e1bd189204" />

    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - - 적용한 기술, 방법, 흐름을 정리해 이해를 돕고 있다.
        - <img width="1692" height="557" alt="image" src="https://github.com/user-attachments/assets/1d193984-aafe-451c-9085-54f4bb9c1eb5" />
        
- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    
        
- [X]  **4. 회고를 잘 작성했나요?**
    - 최종 하이퍼파라미터를 정리해 모델에 대한 이해를 돕고 있다.
        - <img width="876" height="421" alt="image" src="https://github.com/user-attachments/assets/07e41c2c-e864-437d-8486-38e2195a56b8" />
        
- [X]  **5. 코드가 간결하고 효율적인가요?**
    - `ChatbotDataset`, `PositionalEncoding`, `TransformerChatbot`, `generate_square_subsequent_mask` 등으로 코드를 함수화, 클래스화하여 효율적으로 사용하고 있다.


# 회고(참고 링크 및 코드 개선)
```
항상 같은 과제를 수행해도 결과가 사람마다 다른게 신기한 것 같습니다 수고하셨습니다!
```
