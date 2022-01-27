---
title:  "[IBM Qiskit] IBM Quantum Composer 사용하기"
excerpt: "IBM Quantum Circuit Composer"

categories:
  - IBM Qiskit
tags:
  - [Quantum Computation]

toc: true
toc_sticky: true
 
date: 2022-01-27
last_modified_at: 2022-01-27
---

#IBM Quantum Composer
##서론
![image](https://user-images.githubusercontent.com/79438062/151334474-acd4619b-6e45-41a5-a3b2-0051f15f6856.png)

IBM Quantum에서 실제로 일반 유저들이 양자 회로를 만들어서 실제 양자컴퓨터나 시뮬레이터에서 실행 할 수 있게 IBM Quantum Composer이라는 programming tool을 지원한다.

##시작하기
![image](https://user-images.githubusercontent.com/79438062/151337312-53c66448-944a-4b03-85c8-260884bf3bc6.png)
[IBM Quantum Composer](https://quantum-computing.ibm.com/composer/files/new)에 들어가면 간편하게 양자 회로를 구축 할 수 있는 화면이 보인다.

![image](https://user-images.githubusercontent.com/79438062/151338299-46fa0795-da40-4fec-8bde-ec02236ffeb7.png)
우선 개인적으로 눈부신 하얀 화면보다 검은 **다크 테마**가 편하기 때문에 Sign in을 눌러서 IBMid를 이용해 IBM Quantum에 로그인 하고고 테마를 검정색으로 바꿔주었다.

추가적으로 5개 이상의 큐비트를 사용하거나 실행하려는 시뮬레이터를 고르거나 실제 양자 장치에서 테스트를 하려면 IBM Quantum에 로그인이 필수적이다.

##양자 회로 준비

![image](https://user-images.githubusercontent.com/79438062/151347750-f2bc1966-35f0-4ed8-9481-39277e43590e.png)

우선 IBM Quantum Composer에 들어가게 되면 생소할수도 있고 익숙할수도 있는 줄과 알파벳이나 그림이 그려진 네모들이 보일 것이다.

![image](https://user-images.githubusercontent.com/79438062/151348269-5a9483ff-c87e-4866-b38d-845cfed24aa4.png)

혹시나 빈 회로가 보이지 않는다면 **New file +** 을 눌러서 새로운 빈 회로를 만들어 주자

###게이트
![image](https://user-images.githubusercontent.com/79438062/151348603-e3184ce5-a632-4a80-b8df-4b1cfcf86f47.png)
위 네모 안에 그러져 있는것들은 게이트 들이다. 원하는 게이트를 줄 안에 끌어당겨서 원하는 위치(큐비트)에 놓을 수 있다.


###큐비트
![image](https://user-images.githubusercontent.com/79438062/151348815-451914c5-0b50-4419-9cbd-831f1fb31c97.png)
줄 옆에 그려져 있는 알파벳은 각 큐비트와 일반 비트를 의미한다. 큐비트의 갯수를 늘리고 싶다면 q와 c사이에 있는 **+** 를 눌러서 추가해줄 수 있다. 또한 큐비트를 없애고 싶다면 원하는 큐비트에 마우스를 올려서 쓰레기통 모양 **🗑** 을 눌러서 없에주자.
- q는 큐비트를 의미한다
- c는 고전적 일반 비트를 의미한다.

##양자 회로 만들기
이 포스트에서 만들어볼 회로는 `Bell State`라는 회로다.
간단히 말하면 `Bell State`는 Bell test를 통해 얽힌 상태의 국소 숨김 변수 이론 (local hidden variable theory)으로 설명할 수 없으며 고전적인 것을 벗어나 그 이상과 상관관계가 있어야 한다는 것을 보여준다. 이후의 포스트에서 더욱 자세히 설명할 예정이다.

![image](https://user-images.githubusercontent.com/79438062/151350195-4fa75d75-2a09-444c-a42d-1768fa36fe88.png)
`Bell State`회로를 만들기 위해서는 2개의 큐비트와 1개의 일반적인 비트가 필요하니 그림과 같에 준비해주자. 우선 아무런 게이트가 없기 때문에 아래 Probabilities를 보면 두개의 큐비트들, `q0`과 `q1`이 `00`으로 100%확률로 나타내는것이 보여진다.

###H gate (하다마드 게이트) 회로에 추가하기
![image](https://user-images.githubusercontent.com/79438062/151350384-91d7458f-c841-4310-8641-b4ee2fc106b3.png)
위 gate가 있는 리스트에서 ![image](https://user-images.githubusercontent.com/79438062/151351134-a5dc5404-28cc-4946-8cdf-4b5c3474eafc.png)를 끌어당겨서 큐비트 0에다가 놓아주었다. H gate를 빈 회로에 놓는 순간 아래 그래프들이 바뀌어 50%확률로 `00`, 50%확률로 `01`으로 회로 결과가 바뀌었다.

###CNOT gate 회로에 추가하기
![image](https://user-images.githubusercontent.com/79438062/151350924-94a57dd5-c22b-4f4b-9113-1861bbef61c7.png)
이번에는 위 게이트에서 ![image](https://user-images.githubusercontent.com/79438062/151351056-0e17301b-d192-48f0-bf1e-4f4f661f72ba.png)를 끌어당겨서 ![image](https://user-images.githubusercontent.com/79438062/151351310-c8d8d9bf-cbb4-4be0-a1c9-590153ba0d6e.png)를 큐비트 `q0`에, ![image](https://user-images.githubusercontent.com/79438062/151351471-06865fa3-cc64-48aa-9614-25b353c190a0.png)를 큐비트 `q1`에 놓아서 위 사진과 같에 양자 회로를 만들어주자. CNOT(Control-Not) gate는 ![image](https://user-images.githubusercontent.com/79438062/151351310-c8d8d9bf-cbb4-4be0-a1c9-590153ba0d6e.png)가 있는 큐비트의 상태에 따라서 ![image](https://user-images.githubusercontent.com/79438062/151351471-06865fa3-cc64-48aa-9614-25b353c190a0.png)가 놓아진 큐비트의 상태가 바뀌어진다. 따라서 위의 회로에서는 50%확률로 `00`, 50%확률로 `11`으로 회로 결과가 그래프를 통해서 바뀌었다는것을 확인할수 있다.

###측정 연산자 회로에 추가하기
![image](https://user-images.githubusercontent.com/79438062/151352161-36ca4dd9-4b66-4885-95b7-57fb1be8a81d.png)
측정 연산자는 ![image](https://user-images.githubusercontent.com/79438062/151352239-d947621b-f828-4d67-bf08-7c97bcf661ea.png)와 같이 생겼다. 측정 연산자를 각 큐비트 `q0`과 `q1`에 추가해 **고전적 일반 비트(classical bit)** 에 기록한다. 위와 다르게 중첩 상태의 큐비트들이 측정 되었기에 결과적으로 Statevector 그래프를 통해서 `00`이라는 측정 결과가 나왔다는것을 확인할수 있다.

##시뮬레이터/장치를 고르고 실행하기
![image](https://user-images.githubusercontent.com/79438062/151352981-4c86bd55-8c32-4807-9f77-d38158a511f7.png)
위와 같이 양자회로를 만들었다면 **Setup and run**을 눌러 양자회로를 테스트 해볼 시뮬레이터나 실제 양자기계를 선택해보자.

![image](https://user-images.githubusercontent.com/79438062/151353190-7963371a-32f3-4e73-b265-552dfedc2800.png)
**Setup and run**을 누르게 되면 위와 같이 사용할 시뮬레이터/기계 이름과 얼마나 shot을 보낼건지 물어본다. 여기서 shots은 양자 중첩 상태를 관찰하여 측정하는 횟수이다. 많은 관찰을 하여 높은 확률로 정확한 결과를 얻을 수 있다. 각 기계나 시뮬레이터에서 ``See details``를 눌러서 상세 정보를 확인할수 있다.

![image](https://user-images.githubusercontent.com/79438062/151353640-7596f0ff-a8e1-420c-a7ac-f702583d413c.png)
실제 양자장치를 사용하지 않고 시뮬레이터를 사용하는것이고 특별한 일이 아니면 검색창에서 qasm을 검색해 `ibmq_qasm_simulator`을 사용하는것을 추천한다. 이번 **bell state** 양자 회로를 이용하여 사진과 같이 qasm 시뮬레이터에 1024번 shots을 쏴주었다.

![image](https://user-images.githubusercontent.com/79438062/151354357-2e99342d-babd-47a6-a919-d32b4780567d.png)
시뮬레이터나 장치를 골라 실행을 눌러주었다면 Composer Jobs아래에 대기중이나 완료된 결과를 볼 수 있다.

![image](https://user-images.githubusercontent.com/79438062/151354961-9e31b055-e283-44fe-a865-a5f38b54b06d.png)
완료된 결과를 누르게 되면 간단하게 측정 결과를 보여주고 `See more details`를 누르면 더 상세 정보를 알 수 있다.

###Transpiled circuit
![image](https://user-images.githubusercontent.com/79438062/151355239-8e320747-c05a-451b-b8a9-23e059242b9a.png)
상세 정보중에 **Transpiled circuit**을 볼 수 있는데 이는 선택한 시뮬레이터나 실제 양자 기계가 기존 회로(Original circuit)을 어떻게 transpile하는지 보여준다. 따라서 사용하는 시뮬레이터나 장치에 따라 다른 Transpiled circuit을 보여줄수도 있다.

유명한 회로들도 IBM Quantum Composer에 돌려서 가지고 놀아보면 은근 재미있다.
- [GHZ states](https://quantum-computing.ibm.com/composer/docs/iqx/example-circuits/ghz)
- [W states](https://quantum-computing.ibm.com/composer/docs/iqx/example-circuits/w-state)
- [Grover's algorithm(그로버 알고리즘)](https://quantum-computing.ibm.com/composer/docs/iqx/example-circuits/grover) 