# Reference-Auto-Detection
: Linked Open Data(LOD)와 자연어처리를 활용한 학술 데이터베이스 참고문헌의 서지 정보 식별 자동화 알고리즘
---
1. "한국현대문학 학술논문 참고문헌 데이터베이스"

: 서지 정보 식별 자동화 알고리즘 개발과 활용을 목표로 두고 있는 학술 데이터베이스

참고: https://byungjunkim.com/publication/2022-03-31-paper-title-number-12

or https://github.com/ByungjunKim/CRKMLS
 * 본 데이터베이스는 연구자 인용 데이터를 통한 학계의 동향 파악을 위해 활용되었음
   * 특정 연구자가 어떻게 이해되고 수용되었는지 파악함
   * 인구사회학적 배경이 학계 동향에 미친 영향 통계적으로 검정함
---
2. author disambiguation

: 참고문헌 목록 안에서 같은 문헌을 가리키는 경우 통일화된 제목 부여

**how?** 문자열 유사도(편집거리) 라이브러리 활용


* 통일화된 제목 부여 성능 실험(정성적 평가 중심)

  a. PolyFuzz

  b. RapidFuzz(최종 선정)


* scorer, threshold의 하이퍼 파라미터 튜닝
  * 튜닝 시 고려한 사례
 
    a. 동일한 문헌인데, 제목 내 문장 부호만 다른 경우

    b. 동일한 문헌인데, 제목 내 띄어쓰기만 다른 경우

    c. 연속 간행물(예: 1권, 2권, ...)
---
3. 국립중앙도서관 LOD 매칭
---
4. LLM을 통해서 위 과정을 자동화
---
