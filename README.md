# OpenVidu 가이드

> !! 준비물 : Linux(Ubuntu), docker, maven, npm !!

## 방법 1
### 1. 프로젝트 Clone
```bash
git clone https://github.com/jaemoon99/openvidu-local-test.git
```
### 1. Deployment 서버 실행
```bash
docker run -p 4443:4443 --rm -e OPENVIDU_SECRET=MY_SECRET openvidu/openvidu-dev:2.31.0
```

### 2. Server 실행
```bash
cd openvidu-local-test/openvidu-basic-java
mvn spring-boot:run

```

### 3. Client 실행
```bash
cd openvidu-local-test/openvidu-react
npm install
npm start
```


>프로젝트 설정 후 Server, Client 각각 커스텀하시면 됩니다.

참고 : https://docs.openvidu.io/en/stable/tutorials/openvidu-react/
