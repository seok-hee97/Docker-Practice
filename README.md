# Docker-Practice





#### [reference]

- 네트워크를 사용하여 두 컨테이너 연결(django 백엔드, 반응/node.js 프론트엔드)
https://forums.docker.com/t/connecting-two-containers-using-a-network-django-backend-react-nodejs-frontend/107472


- Hands-On Cross-Container Communication(Django&Postgres) 
https://medium.com/@simofirdoussi/hands-on-cross-container-communication-django-postgres-202c7c9a41d4
(But not use docker-compose)


- Django Development with Docker Compose and Machine
https://realpython.com/django-development-with-docker-compose-and-machine/


- How To Deploy Django Using Docker Compose on Windows In 9 Steps

https://medium.com/powered-by-django/deploy-django-using-docker-compose-windows-3068f2d981c4



##### [books]

- 시작하세요! 도커/쿠버네티스: 친절한 설명으로 쉽게 이해하는 컨테이너 관리
(Getting-started-with-Docker/k8s)


##### 2.4 Dockerfile
2.4.1 이미지를 생성하는 방법   
개발한 애플리케이션을 컨테이너화할 때 가장 먼저 생각나는 방법은 아래와 같습니다.

1. 아무것도 존재하지 않는 이미지(우분투,CentOS 등)로 컨테이너 생ㅅ겅
2. 애플리케이션을 위한 환경을 설치하고 소스코드 등을 복하새 잘 동작하는 것을 확인
3. 컨테이너를 이미지로 커밋(Commit)

