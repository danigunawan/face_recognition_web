# 얼굴 인식 프로젝트 웹

## Explanation our service

![Recommend](https://user-images.githubusercontent.com/58922804/84978955-2f366d80-b169-11ea-8afa-83fe64597123.jpg)

- 추정한 연령, 성별에 따라 자주 구매하는 제품을 추천상품으로 제안
- 자신의 얼굴을 등록한 고객이 방문한 경우, 그 고객의 이름과 과거 구매이력을 출력
- 얼굴을 등록하지 않은 고객이 얼굴을 등록하고 싶은 경우, 캠을 통해 실시간으로 등록하고 학습시켜 1분 안에 업데이트 되도록 시스템 구성

![Train_Classifier](https://user-images.githubusercontent.com/58922804/84978957-2fcf0400-b169-11ea-92e7-df202a9d2131.jpg)




- 사용 라이브러리

- 가동시 가상환경과 데이터베이스를 맞추어주어야 한다.


||||
|------|---|---|
|Web|Django|
|데이터베이스|Postgre-sql|
|엔진|Tensorflow|
|이미지 처리|opencv|
|css framework|bootstrap|

```
tensorflow          1.7.0
opencv-python       4.2.0.34
pandas              0.25.3
numpy               1.16.2
scipy               1.2.1
Django              2.1.7
djangorestframework 3.11.0
psycopg2            2.7.5
psutil              5.7.0
```



- 가상의 데이터베이스와 뷰를 사용