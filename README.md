## AI 기반 회의 녹취록 요약 경진대회

### 사용한 데이터
- https://dacon.io/competitions/official/235813/overview/description

### 사용한 패키지
- textrank : pandas, konlpy(Komoran), textrank(KeysentenceSummarizer)
- transformer : pandas, torch, tqdm, sklearn, konlpy(Mecab), transformer

textrank 라이브러리를 사용했으나 처참한 f1 score를 받고, 제출에 의의를 두기 위해 베이스라인 모델을 돌려 제출했습니다.

시간이 나면 KoBert 모델을 사용해서 돌려볼 예정 !! 
