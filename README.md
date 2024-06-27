# Reference-Auto-Detection
Linked Open Data(LOD)와 자연어처리를 활용한 학술 데이터베이스 참고문헌의 서지 정보 식별 자동화 알고리즘

1. 연구 데이터
https://docs.google.com/spreadsheets/d/1CC69XtooihQurCSjyqPyu721LvQfNutS/edit?usp=sharing&ouid=102864613966848491919&rtpof=true&sd=true 
참고: https://byungjunkim.com/publication/2022-03-31-paper-title-number-12 
* 연구자 인용 데이터를 통한 학계의 동향 파악
  * 특정 연구자가 어떻게 이해되고 수용되었는지 파악
  * 인구사회학적 배경이 학계 동향에 미친 영향 통계적으로 검정

2. author disambiguation
: 참고문헌 목록 안에서 같은 문헌을 가리키는 걸 합치기
how? 문자열 유사도 (편집거리) 라이브러리 활용

3. 수작업 데이터를 통해 GPT fine-tuning
* 저자 정보 정도만 일치시킨 데이터 존재 => 데이터 확보 어려움

4. 국립중앙도서관 LOD 매칭

5. LLM을 통해서 위 과정을 자동화
