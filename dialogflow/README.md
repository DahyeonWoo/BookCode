# Dialogflow Study
![다운로드](https://user-images.githubusercontent.com/68543150/114038996-52c7d180-98bd-11eb-8794-ef977d70e1c1.png)

- Contributor: 유재성, 장윤아
## 1. Intent Matching

### **사용자가 무엇을 원하는지 인식하는 것**

- 시작하려면 몇 가지 예만 있으면 된다.

    예를 들어 자전거 수리점에서 dialogflow를 이용하고 싶다면

    - 자전거를 고치고 싶어.
    - 내 자전거가 고장났어.
    - 이번 주에 자전거를 고칠 수 있을까?
- 이를 통해 dialogflow는 기계 학습을 진행해서, 비슷한  예시(ex. 자전거 수리 예약해줘, 브레이크가 고장났어 등)에 대해서도 응답할 수 있게 만듦.
- 따라서 사용자가 말하는 **의도(Intent)를 파악**하여 앱이 어떻게 반응할 지 정해줘야 한다!

## 2. Intent Examples

다음과 같은 Intent Matching의 사례를 살펴보겠다.

1. 가격확인
    - 가장 잘 팔리는 모델이 얼마야?
    - 튜닝 비용이 어떻게 돼?
    - 수리 비용이 어떻게 돼?
2. 수리예약
    - 자전거를 고치고 싶어
    - 자전거가 망가졌어
    - 이번 주에 자전거 수리 가능할까?
3. 영업시간
    - 영업시간이 어떻게 돼?
    - 언제 열어?
    - 언제 닫아?

위와 같이 자전거 수리점에서 Intent(1,2,3)와 각각에 맞는 예시를 설정해 놨다면 다음과 같은 질문을 받았을 때,

> 개장 시간이 언제야?

- 10시 부터 5시까지 영업합니다

라는 답변을 사용자가 받을 수 있다.