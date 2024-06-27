참고문헌 목록 안에서 같은 문헌을 가리키는 걸 합치기

- How?
: 문자열 유사도 (편집거리)

1.https://github.com/MaartenGr/PolyFuzz
성능 아쉬움(아래 예시의 경우 1990가 등장하는 title 다 묶어버림)
![스크린샷 2024-06-27 오후 1 56 00](https://github.com/WooYoungSeok/Reference-Auto-Detection/assets/138356414/9b6a1e96-6dc1-4af9-b7cb-bddea92891f6)

2.https://github.com/rapidfuzz/RapidFuzz
GPT가 속도와 성능 면에서 가장 추천한 라이브러리
polyfuzz보다 훨씬 나은 성능을 보임(12817개 ==  통일화  ==> 8966개)
<img width="506" alt="스크린샷 2024-06-27 오후 2 01 24" src="https://github.com/WooYoungSeok/Reference-Auto-Detection/assets/138356414/ac4eacc7-7d46-41ec-845d-20aa90c03221">
문제: 통일화한 title에 알 수 없는 공백 특수문자가 포함된 경우가 있음(LOD 매칭에 문제가 있을 수 있음), 시리즈 물 잘못 통합(김현 문학전집3 => 김현 문학전집4 / 김현 문학전집4 => 김현 문학전집3)
