# 댓글데이터 텍스트 분석 프로젝트

- 이커머스 도메인 DA프로젝트
- 디퓨저 제품들의 분석
- 네이버 쇼핑 리뷰 많은 제품 댓글 분석
- 기업의 매출의 향상을 위해서
    - 사람들이 최근에 선호하는 향
        - 단순 통계
        - 리뷰데이터
    - 선호하는 브랜드와 이유
        - 단순 통계 사용
    - 사람들의 불만에서 무엇을 고쳐야 하는가?

## 어떤 종류의 데이터가 있는지

- 네이버 데이터랩 향기 제품 언급문서 데이터
- 제품 댓글 데이터
    - 크롤링 사용
    - 단점들을 추출 → 개선 방안 제안
- 레퍼런스와 통계데이터 수집

## 데이터에서 무엇을 고려해야 할지

- 향기 종류 선호도
- 사용장소 별 선호도
- 성분에 따른 선호도
- 구매 요인 분석
- 소비자가 특정 선호도에 어떻게 반응하는지 판단하고 결과를 분석.
    - 결과를 토대로 벤치마킹

1주차

- 디퓨저 관련 시장 분석을 진행
    - 주로 사람들의 이야기를 들어야 좋은 인사이트를 얻을수있다.
        - 네이버쇼핑 내의 제품의 댓글데이터
            - 방향성 제공
            - 피해야 할점 → 소비자들의 말
            - 선호하는 향 분석
        - 기존에 나와있는 통계데이터를 활용할 예정
            - 시장의 변화
            - 제품 다양한 관점의 선호도 확인
        

2주차

- 네이버 쇼핑의 디퓨저 제품 중 댓글이 많은 5가지 제품을 선택
    - 평점별로 크롤링을 진행
    - Selenium 사용
    
3주차

- 리뷰데이터의 전처리
- 단어분석
- 워드클라우드
- 동시출현빈도 분석
- 단어연관도 분석 
    - Word2Vec

