# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 최창식
- 리뷰어 : 김요한


# PRT(Peer Review Template)
- [v]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 시멘틱 세그먼테이션을 사용하여 사진에서 사람인 부분을 찾아냈습니다. 그리고 머리카락과 안경, 뒤에 있는 사람도 포함되는 문제 3가지를 발견했습니다.
        - <img width="1091" height="135" alt="image" src="https://github.com/user-attachments/assets/d22c00bd-bfc6-4fae-b330-c1f278c04011" />
        - <img width="563" height="115" alt="image" src="https://github.com/user-attachments/assets/553872a5-365b-4e50-aa66-873541673b69" />
        - 고양이 사진 역시 세그먼테이션을 진행했습니다.
        - <img width="882" height="267" alt="image" src="https://github.com/user-attachments/assets/ba2af68d-dd07-4dd9-86f2-0844e5800bea" />
        - 배경과 세그먼테이션된 고양이 사진을 잘 합성하였습니다.
        - <img width="1454" height="240" alt="image" src="https://github.com/user-attachments/assets/e9a744aa-c14d-4a09-8bb5-702fd9ea44fb" />
        - <img width="909" height="250" alt="image" src="https://github.com/user-attachments/assets/3540608b-0cea-4a24-a5ea-cabaca2abd3d" />
        - 사람은 세그먼테이션하고 배경은 불러처리해서 잘 합성하였습니다.     


    
- [v]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - <img width="886" height="277" alt="image" src="https://github.com/user-attachments/assets/570acbbf-d4c7-46e7-9886-769ddd829ed7" />
        - 커널사이즈를 다양하게 사용하여 고양이의 털부분과 배경이 잘 합성되도록 형태학적연을 시도 하였습니다.
        -<img width="817" height="73" alt="image" src="https://github.com/user-attachments/assets/b4770c9e-3a78-4d96-b1a0-20d054581b13" />
        - 가우시안 블러를 활요해서 경계를 부드럽게 처리하였습니다.


- [ ]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        
- [ ]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부


# 회고(참고 링크 및 코드 개선)
```
- 합성하는 사진이 이미 아웃포커스 효과가 있어서 사막 배경에 합성했을때 위화감이 덜 느껴졌습니다.
- 개선점으로 CCA와 뎁스맵을 활용했으면 좋았을꺼 같습니다.
```
