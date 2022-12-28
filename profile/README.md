# REmember ME
## AI 복원 기술을 이용한 추억 공유 메타버스 플랫폼
> <b>음성, 챗팅 복원 기술</b>을 통하여 그리운 사람을 추억하고, <br>3D 멀티 유저 플랫폼에서 
추억을 쌓는 데이터 리사이클링 프로젝트 

## 기획의도
- 그리워 하는순간을 다시 만날 수 있다면 어떨까? 라는 질문에 시장이 제시한 방법인 다큐, 캠페인, 추모였습니다.
![planing intention](https://github.com/Team-Remember/.github/blob/main/img/planing%20intention.png)
- 시장의 한계를 파악하고 해결하기 위한 프로젝트 REmember ME
![solution](https://github.com/Team-Remember/.github/blob/main/img/solution.png)
<br>

## 주요 기능
![main function](https://github.com/Team-Remember/.github/blob/main/img/main%20function.png)

## REmember Me 구조
![technology structure](https://github.com/Team-Remember/.github/blob/main/img/data%20structure.png)
1. 유저는 공개, 비공개 방에서 문자, 음성 채팅, 공간, 캐릭터 커스텀이 가능하며 커뮤니티 활동 또한 가능합니다.
2. 플랫폼 내에서 쌓인 데이터는 플랫폼 DB에 쌓이며 유저가 복원을 원할 때 데이터 기반으로 복원된 AI를 제공합니다. **(데이터 리사이클링)**
3. 유저가 플랫폼에서 활동을 하지 않았더라도 즉각복원 기능을 사용하여 카카오톡과 같은 외부데이터로 AI 복원기능을 사용 가능합니다.

## 주요 사용 기술
- Client(Desktop)<br>
<img src="https://img.shields.io/badge/Unity-000?style=for-the-badge&logo=unity&logoColor=white"> <img src="https://img.shields.io/badge/photon-000?style=for-the-badge&logo=Unity&logoColor=white">

- Applications API Server<br>
<img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=AmazonAWS&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon s3&logoColor=white"> <img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">

- AI Server<br>
<img src="https://img.shields.io/badge/Google Compute Engine-4285F4?style=for-the-badge&logo=Google Cloud&logoColor=white"> <img src="https://img.shields.io/badge/Google Cloud storage-4285F4?style=for-the-badge&logo=Google Cloud&logoColor=white"> <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"> <img src="https://img.shields.io/badge/ONNX Runtime-005CED?style=for-the-badge&logo=ONNX&logoColor=white"> <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=FastAPI&logoColor=white"> <img src="https://img.shields.io/badge/elasticsearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white"> <img src="https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white"> <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white">

## 기술 융합 구조도
![technology structure](https://github.com/Team-Remember/.github/blob/main/img/technology%20convergence%20structure%20diagram.png)
1. 유저의 회원, 로비, 방 정보와 채팅기능, 통신 - Unity를 활용
2. 다중사용자 환경 - photon 기술
3. Unity와 통신하는 EC2서버는 트래픽량에 따라서 탄력적으로 관리되어 안정적인 서버 구축
4. 응용 Api서버에서 필요한 AI api 를 호출하여 AI 의 서버에 부하를 방지하고 기능에 집중
5. 학습 서버와 추론서버, 자연어 서버와 음성 서버를 분리하여 안정적인 파이프라인을 구축 
6. 개인화 음성의 경우 model Storage에서 개인별로 checkpoint를 관리

## AI 파이프라인
![AI pipeline](https://github.com/Team-Remember/.github/blob/main/img/AI%20pipeline.png)<br>

## 수상 결과
- 최종 성과공유회 우수상 수상 (한국전파진흥협회장)
<img src="https://github.com/Team-Remember/.github/blob/main/img/remember.jpg" style=" width:100mm; height:120mm;"/><br>


## 시연 영상
[![REmember ME 시연 영상](https://github.com/Team-Remember/.github/blob/main/img/youtube%20link.png)](https://youtu.be/0zYosRkKpBA?t=0s) 
