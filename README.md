# WebRTC

### webRTC란 별도의 서버 플러그인 없이 사용하는 영상통화 api
### WebRTC is a free, open-source project that provides web browsers and mobile applications with real-time communication via simple application programming interfaces.

이 코드 그대로 사용한다고 해서 구동이 되진 않는다.

Node.js에 반드시 SLL을 적용해야한다. Open SLL을 설치하여 개인키(private.pem) 과 공개키(public.pem)을
생성해야 한다. 이후 코드에서 설정해준대로 https://서버ip:3000으로 접속이 가능하다.
여기서 서버ip 란 cmd에서 ipconfig를 실행한후 IPv4주소를 의미한다. 
