# ParkingSim

Developed with Unreal Engine 4
# 1. 개요
---
### 1-1. 배경
기술의 발전과 사회적 변화가 가져온 디지털 기기의 활발한 소비와 메타버스의 발전은 게임 내 가상공간에서 다양한 활동을 가능케 하였다. 이런 사회적 흐름은 다양한 언택트 형식의 컨텐츠들의 수요를 낳았고, 교육면에 있어서도 Gamification 기법을 활용한 컨텐츠의 활용이 잦아졌다. 미국 공립학교 “Quest To Learn” 의 경우, 수업, 과제 등을 게임화 시켜 운영되고 있다. 실제로 아이들은 게임을 하면서 문제 해결 방법, 실패를 극복하고 계속 나가는 법을 배운다고 한다. 본 프로젝트 또한 이와 같은 의도로 제작되었으며, 이용자에게 실전과 비슷한 경험을 제공하여 문제 해결 능력과 대처 능력을 키울 수 있도록 기획되었다.

### 1-2. 주요내용
본 과제는 Gamification에 초점을 맞추어 Gamification의 기법들을 게임에 접목시키는 것을 주 내용으로 삼았다. 크게 도전, 성취, 보상 등의 기법들을 게임 요소와 연결시켜 기획 후 구현하였다.
①도전: 게임의 모드를 2가지로 나누어 Easy모드와 Hard모드를 이용자가 직접 선택할 수 있게 하였다. Easy모드는 3인칭 시점과 1인칭 시점을 모두 활용할 수 있고 Hard모드는 1인칭 시점만 사용할 수 있다.
②성취: 레벨을 세분화하여 높은 레벨로 올라갈수록 난이도를 어렵게 기획하였다. 예를 들어 높은 레벨에서는 운전하는 도중에 야생동물이 갑자기 끼어든다거나, 다른 주차하는 차 들을 피해 안전하게 주차해야한다.
③보상: 스테이지를 깨면 보상이 지급되어 더 좋은 차를 이용하거나 차의 스킨을 바꿀 수 있게 된다.

---

# 2. 과제 수행방법
---
개발에 앞서 기획의도를 명확히 하기위해 설문조사를 진행하였다. 연습용 가상 시뮬레이터 경험자들에게 시뮬레이터에 필요한 가장 필요한 기능들이 무엇인지 질문하여 게임 기획에 활용하였다.
1인 개발인 만큼 게임 기획, 필요한 리소스 제작, 개발을 모두 수행해야 했고 결국 몇 개의 리소스들은 외부의 자원을 활용하였다. 중간발표까지 게임기획과 차 디자인 및 기능 구현을 집중적으로 수행하였다. 이 과정에서 차 내부의 몇몇 필요한 파츠들은 직접 모델링을 진행하였고 엔진 사운드나 충돌 사운드 같은 주요 사운드들은 외부 리소스를 활용하였다. 중간발표 이후로 게임의 매커니즘과 UI등을 집중적으로 구현하였다.

---

# 3. 수행결과
---
### 3-1. UI 디자인
![image](https://user-images.githubusercontent.com/83454721/174277425-84cab42a-8391-4882-9015-7737d924569f.png)
![image](https://user-images.githubusercontent.com/83454721/174277435-f1f4f580-490a-41ff-81bd-bae4d3fe5ae2.png)
![image](https://user-images.githubusercontent.com/83454721/174277444-e4df83dd-ab3d-4f6a-ad19-499c638371e2.png)

Main Menu 및 Pause Menu, 클리어 시 UI 구성 모습

### 3-2. 메인 레벨 구성
![image](https://user-images.githubusercontent.com/83454721/174277461-c87476b2-a10b-4dd6-8346-4ddb7beb2840.png)

메인 스테이지들의 구성

### 3-3. 최종결과물 주요특징 및 설명
![image](https://user-images.githubusercontent.com/83454721/174277472-7839e878-8cad-4482-8961-d7b140efe5e8.png)
Figure 1. 플레이어가 Main Menu에서 New Game을 선택하면 모드를 선택하는 화면으로 넘어온다.

![image](https://user-images.githubusercontent.com/83454721/174277481-22d64617-2a3b-4879-bc42-f81429c1c96f.png)
Figure 2. 튜토리얼 스테이지가 시작되고, 게임에 사용되는 주요 키들에 대한 설명이 출력된다.

![image](https://user-images.githubusercontent.com/83454721/174277488-67302850-cec4-438c-b4c7-38dfcf0840ec.png)
Figure 3. 스테이지를 클리어 할 때 마다 충돌 횟수와 걸린 시간이 표시되는 UI가 출력되고 Retry버튼을 통해 스테이지를 다시 시작할 수 있으며 Next버튼을 통해 다음 스테이지로 넘어갈 수 있다.

![image](https://user-images.githubusercontent.com/83454721/174277500-9aabf81e-214b-4f6f-8998-73016cd7c90b.png)
Figure 4. 레이싱 휠을 통해 플레이

---

# 4. 기대효과 및 활용방안
---
### 4-1. 기대효과
본 과제는 언택트 컨텐츠로서, 시공간의 제약을 거의 받지 않고도 이용자들이 쉽게 접근할 수 있을 것이다. 사용자들이 주도적으로, 스스로 연습해봄으로서 주차 실력을 쉽게 향상시킬 수 있을 것으로 기대한다.

### 4-2. 활용방안
기술의 발전과 디지털 기기의 보급이 조금 더 활성화된 시대가 온다면 PC뿐만 아니라 레이싱 휠로도 언제 어디서나 실전과 비슷한 연습을 할 수 있을 것으로 예상한다.

---

# 5. 결론 및 제언
아직 시중에는 단순 오락용 게임보다 교육용 게임이 출시된 사례가 현저히 적다. 교육용 게임을 조금 더 연구하고 Gamification 기법을 잘 적용한다면 교육용 게임도 오락용 게임만큼 상업성을 가질 수 있다는 것을 증명할 수 있을 것이다. 본 프로젝트 또한 최종 연구 단계가 아니기 때문에 부족한 부분이 많지만, 이를 토대로 추후에 게임이 확장됨으로써 교육용 게임의 시장을 넓혀나갈 수 있기를 기대한다.
