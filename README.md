# Computer-Graphics-Project
## 📜 Blender를 이용한 애니메이션 만들기

개발 기간: 2023.11.27~2023.12.07 

개발 툴: <img src="https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=Blender&logoColor=white">

## 🔍 미리 보기
- [프로젝트 소개](#-프로젝트-소개)
- [실행 영상](#-실행-영상)
- [Blender란?](#-blender란)
- [구현 과정](#-구현-과정)
- [프로젝트를 하며 느낀점](#-프로젝트를-하며-느낀점)

## 💻 프로젝트 소개
- 컴퓨터 그래픽스 수업을 듣고 만든 프로젝트입니다.
- 좋아하는 애니메이션 캐릭터인 토토로를 가지고 애니메이션을 만들었습니다.
- Blender를 사용했습니다.
  
## 📽 실행 영상
![프로젝트 동영상_202015333_한승희](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/fc03625f-3480-45d6-9888-5442ef502b5b)


## 💎 Blender란?

- 무료 및 오픈 소스의 3D 컴퓨터 그래픽스 소프트웨어
- 모델링, 애니메이션, 렌더링, 비디오 편집 등 다양한 기능을 제공
- 다양한 기능:
  
  1)3D 모델링: 다양한 모델링 도구를 사용하여 3D 모델을 만들 수 있음
  
  2)애니메이션: 오브젝트 및 캐릭터를 움직이고 애니메이션화할 수 있음
  
  3)렌더링: Cycles 및 Eevee와 같은 렌더 엔진을 사용하여 고품질의 이미지 및 애니메이션을 렌더링할 수 있음
  
  4)비디오 편집: 비디오 시퀀싱 및 편집을 위한 기능이 내장되어 있음
  
  5)게임 개발: 게임 엔진과 관련된 기능을 제공하며, 게임 개발에 사용될 수 있음
  
- 인터페이스:
  
  1)초기 입문자에게는 다소 복합할 수 있지만, 다양한 작업을 수행할 수 있는 강력하고 유연한 도구 제공
  
  2)3D 뷰포트, 속성 편집기, 아웃라인 패널 등 다양한 패널과 창으로 구성
  
- 지원되는 파일 형식:
  
  1)다양한 3D 파일 형식을 가져오고 내보낼 수 있음 EX) OBJ, FBX, STL
  
- 커뮤니티 및 리소스:
  
  1)강력한 개발 및 사용자 커뮤니티를 가지고 있으며, 사용자 간의 지원 및 자원 공유가 활발함
  
  2)공식 웹사이트, 온라인 포럼, 튜토리얼, 애드온 등을 통해 다양한 지원과 자료에 접근할 수 있음
  
- 업데이트와 확장성:
  
  1)정기적인 업데이트를 통해 새로운 기능과 개선 사항 제공 최근 blender 4.0 출시


## ▶ 구현 과정

 노트북 그래픽카드 버전이 오래되어 blender 2.8을 사용하였습니다.


1. 3D 모델
   
![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/96c3e620-07d3-4525-85dd-f84288508dc0)

- Object mode
- 솔리드 렌더링
- 형태 다듬기


![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/2fde755b-06a0-4c85-a06a-838f1a9b81c4)
- Edit mode
- 와이어 프레임
- 드로잉 속도가 빠름

  
![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/8c287e09-6b6d-4588-862d-befec283b8d8)
- 여러 개의 오브젝트 Join


![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/3ac4cafb-6d37-4bcf-86df-0d0260900cc6)
- Material을 이용해 재질 입히기




2. 리깅 (뼈대 넣기)
   
![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/89262d6e-2f5a-47e3-9bb0-4b1df44a972f)
- Shading


![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/b1e673ea-faf7-42e8-bef8-65e5bfea0dd2)
- Texture Mapping
- 3D 캐릭터 모델에 뼈대(bones)와 관련된 제어 시스템을 적용하여 애니메이션을 할 수 있도록 만드는 과정
- 리깅 주요 요소: 1. 뼈대 2. 관절 및 제어기 3. 스킨 4. 웨이팅 5. 애니메이션 컨트롤러




3. 애니메이션
   
![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/508bdfd4-32b5-4374-9729-45b6c068c9e0)
- 타임라인 열기
- 현재 상태를 키프레임으로 설정
- 위치 이동 후  다시 키프레임 설정




4. 카메라 이동
   
![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/34877a2a-6c90-49a5-b076-e1f996cc3cb6)
- 카메라 위치에서 본 화면(투영)

  
![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/c10deb72-522f-480b-afda-12c3bad61e7f)
- 카메라, light 이동




5. 결과(사진)

![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/3b280e3f-367a-4dae-8620-0e781f0b69c1)


![image](https://github.com/SeungHuiHan/Computer-Graphics-Project/assets/98226400/7918e6c8-17ed-46ce-8728-72962fca2a6b)




## 💣 프로젝트를 하며 느낀점
- 캐릭터를 제자리에서 움직이는 것이 아니라 앞으로 걷게끔 만들고 싶었지만, 해당 동작의 난이도가 높아서 주어진 시간 내에 완성하지 못했습니다.
- 캐릭터의 걷는 동작이 크지 않아서, 작업물 전반에 걸쳐 명확하게 시각적인 효과를 얻지 못한게 아쉽습니다.
- 애니메이션 제작 과정이 기대보다 더 어려웠습니다.
- 이번 프로젝트를 통해 컴퓨터 그래픽수 수업에서 배운 렌더링, 쉐이딩, 투영 등의 이론을 실전에 적용하는 경험을 쌓았습니다.

