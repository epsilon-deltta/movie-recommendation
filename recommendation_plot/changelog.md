## Changelog





4/21)
기존 markdown 수정

4/20)
키워드 기반 추천에서의 구조를 초기 구조에서 개선된 구조로 수정
	=> 개선된 구조 : 벡터 기반 코딩 중 테스트를 해 기존보다 더 좋은 결과를 낸 구조

초기 구조 : 장르 유사도 기준 topn=600개 데이터 => 가중치 평점 & 키워드 유사도 계산 => 가중치 합
개선된 구조 : 데이터에서 장르 & 가중치 평점 & 키워드 유사도를 각각 구한 후 polynomial 구조의 가중치 합 계산

4/17)
클러스터링 기반 추천 알고리즘 보완 => KMeans to MiniBatchKMeans
KMeans, MiniBatchKMeans 간의 차이 시각화

4/16)
코드 스타일 통일 => 벡터, 클러스터링 기반

4/14)
클러스터링 기반 추천 완성

4/13)
클러스터링 기반 추천 테스트 시도 => kmeans

4/10)
벡터 기반 추천 클래스 완성

4/9)
벡터 기반 추천 테스트 시도 => tfidf or count from sklearn