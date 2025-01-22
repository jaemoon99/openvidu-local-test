# OpenVidu 가이드

> !! 도커, maven, npm 필요 !!

## 1. Deployment 서버 실행
```bash
docker run -p 4443:4443 --rm -e OPENVIDU_SECRET=MY_SECRET openvidu/openvidu-dev:2.31.0
```

## 2. Server 실행
```bash
git clone https://github.com/OpenVidu/openvidu-tutorials.git -b v2.31.0
cd openvidu-tutorials/openvidu-basic-java
mvn spring-boot:run

```

## 3. Client 실행
```bash
cd openvidu-tutorials/openvidu-react
npm install
npm start
```