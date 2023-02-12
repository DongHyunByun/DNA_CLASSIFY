# 월간 데이콘 기계 고장 진단 AI 경진대회

1. **기간 : 2022.12 ~ 2023.01** 

2. **기술스택**
    1. 개발언어 : python
    2. IDE : google colab
    3. 라이브러리 : catboost, LGBM, XGBOOST, tensorflow
 
3. **내용**
    1. 유전체관련 15개의 feature을 이용하여 개체의 품종 분류
    2. SNP_01~SNP_15 전처리(원학코딩, 라벨링 등)
    3. catboost, DNN, LGBM, XGBOOST등 모델사용
4. **파일설명**
    1. /sub : 제출파일
    2. /data : input 데이터
    3. DNA.ipynb : 내코드
    4. dna_1위.ipynb : 공개된 최종순위 1위 코드
      - 주소 : https://dacon.io/competitions/official/236035/codeshare/7430?page=1&dtype=recent
      - 파생변수 생성 부분
      - voteclassifier 
      - 시드고정
    5. dna_2위.ipynb : 공개된 최종순위 2위 코드
      - 주소 : https://dacon.io/competitions/official/236035/codeshare/7487?page=1&dtype=recent
      - 변수 선택(SNP_03 드롭)
      - cat feature 선택(SNP_10)
