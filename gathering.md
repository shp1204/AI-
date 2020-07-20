https://www.notion.so/0c389df1cddd485496d17a0b50b28980

# 1. 엘렉시

https://www.ellexi.com/

### 01. 보유 기술

- 딥러닝기반 네트워크보안, 물리보안, 스마트공장 설비관리, 금융거래 등의 이상 패턴 감지 솔루션(SaaS)
- 정형/비정형 데이터 전처리, 정ㆍ오탐 분류, 모니터링 솔루션
- 상황인지 서비스 실행 솔루션
- 이미지 & 영상처리 솔루션
- 인공지능 컨설팅 서비스 / 인공지능 데이터 가공 서비스

### 02. philo-ad : 이상패턴 감지

기대하는 Behavior와 다르게 나타나는 패턴

Outlier / Exception / Surprise / 부정거래 레코드 / 이상행동 동영상 / 네트워크 침입 로그 등

이상 패턴은 아주 드물게 나타나는데 이것 때문에 AI화 하기 힘들다

따라서 방향을 바꿔서 정상 패턴을 아주 많이 학습시키고 모델링하면 이상 패턴이 들어왔을 때 더 잘 감지할 수 있을 것.

### 03. philo-v : 딥러닝 기반 영상 분석 솔루션

ex ) 실신 분석 : data가 모아지기가 어려움 / data가 너무 typical 

현재 : 얼굴인식을 통한 공항출입국 이상한 사람 판별 ? 

### 04. data preprocessing

![image-20200720132126658](C:%5CUsers%5C%EB%B0%95%EC%86%8C%ED%9D%AC%5CAppData%5CRoaming%5CTypora%5Ctypora-user-images%5Cimage-20200720132126658.png)

```
* data scientist < data engineer
* 정상 데이터 / 이상 데이터 는 계속 모델링을 반복해야하는데, 비효율적이지 않은가 ?  
- > lstm autoencoder : 정상 패턴 모델링을 한 뒤 -> 이상 패턴이 나오는 경우 error 차이를 이용해서 학습 -> 주로 비지도학습에 사용 -> 더 정확한 결과를 얻고 싶은 경우, supervised learning 을 적용한다.
* 음성인식 != AI 스피커만드는것 
- >  framework 공부할 만한것 ? tensorflow / kerras / pytorch
* b2b사업 어려움 ? 영업력
```

