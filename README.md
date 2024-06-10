"https://github.com/seabjh/Crawling"

위 경로에서 제공한 코드를 통해


분석된 Latent Dirichlet Aloocation(LDA) 파일들을 정리한 폴더이다.


LDA는 확률적 토픽 모델 기법 중 하나로


숨겨진 주제를 분류해줄 뿐만 아니라 주제에 포함되는 키워드들을 보여주어


그 키워드들로 해당 주제를 해석하고 정의할 수 있게 하는 모델링이다.


LDA 분석시 적용한 하이퍼 파라미터의 설정은 다음과 같다.

num_topics = 5    (토픽 갯수 추출)


chunksize = 8000  (한번에 처리할 문서의 갯수, 4000 권장)


passes = 50       (모델링 수렴을 위한 전체 코퍼스 훈련값, 10~50 권장)


iterations = 500  (각 Chunk에 대한반복을 통해 수렴치 도출, 10~1000 권장)


eval_every = None    (모델의 로그가능도(log likelihood)를 평가할 빈도, None이면 하지 않음)

해당 파일들은 HTML 파일로 구성되어 있기 때문에, GITHUB상에서 보기는 어려우므로
다운로드 받아서 볼 것을 권장한다.

해당 LDA 파일은 지속적으로 수정보완 예정임.
2024.06.10
