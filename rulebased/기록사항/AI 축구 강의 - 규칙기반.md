## 영상 링크
https://www.youtube.com/watch?v=oZEEd_X57mw&list=PLHOyURVffDsDqjkfaA5Yh5qrGWx40nBXa&index=2

---

- 주니어, 시니어 로봇 존재
- AI 시뮬레이터(Webots)존재해야함-이를 이용하여 로봇 위치에 대한 좌표 수신받음, 매 시간마다 로봇 컨트롤 변수 되돌려보냄
- 6개 변수 존재(left_wheel,right_wheel,front_slider,front_slider_height,bottom_slider,dribble_mode) (AI축구 메뉴얼 참조할 것)

---
## 규칙기반 알고리즘 2가지 파트로 나누어짐: 전략파트, 제어파트
### 전략파트: 게임의 좌표값 사용 - 로봇 위치, 공의 포지션이 중요함
- lower field/opponent filed에 공이 있나 확인, shoot chance 고려..

### 제어파트
- High level action을 Low level action으로-6개변수 어떻게 움직여아하는지?
- 거리편차/속도편차 고려하여 속도 조절, 방향 틀리면 각속도(?)를 바꾸어 회전(ppt에 있는 수식 이용)

>일단 전략 먼저 하기

## 어려운점
- 최적의 규칙 규정 어려움
- 시간오래걸림(사용자의 작업시간, 시행착오..)
