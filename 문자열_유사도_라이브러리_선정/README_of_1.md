# 참고문헌 목록 안에서 같은 문헌을 가리키는 걸 합치기

## - How? : 문자열 유사도 (편집거리) 라이브러리 활용

1. PolyFuzz: https://github.com/MaartenGr/PolyFuzz
* 성능 아쉬움(아래 예시의 경우 1990가 등장하는 title 다 묶어버림)
![스크린샷 2024-06-27 오후 1 56 00](https://github.com/WooYoungSeok/Reference-Auto-Detection/assets/138356414/9b6a1e96-6dc1-4af9-b7cb-bddea92891f6)

2. RapidFuzz: https://github.com/rapidfuzz/RapidFuzz
* GPT가 속도와 성능 면에서 가장 추천한 라이브러리
* polyfuzz보다 훨씬 나은 성능을 보임(12817개 ==  통일화  ==> 8966개)<img width="506" alt="스크린샷 2024-06-27 오후 2 01 24" src="https://github.com/WooYoungSeok/Reference-Auto-Detection/assets/138356414/ac4eacc7-7d46-41ec-845d-20aa90c03221">
