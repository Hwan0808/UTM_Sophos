# UTM_Sophos

## 1. 보안 인프라 실습 환경 구축

![캡처](https://user-images.githubusercontent.com/57865037/235392286-e4159b33-73e5-480c-9924-cba0ff9d3a19.PNG)

<div align="center">
  <img src="https://user-images.githubusercontent.com/57865037/235393226-0ad294b2-6ec5-40d4-a760-96efd2b54982.png">
</div>

## 2. 접근 제어 정책

* UTM의 정책은 기본적으로 화이트 리스트 방식으로 구현함.
* 외부에서 내부망에 접근이 불가능하도록 설계함.
* 웹 서버와 DB는 외부(허용된 인가장비에 한해서)에서 HTTP/FTP 접속이 가능함.
* UTM의 필터링 기능을 적용, 내부의 Client는 외부로 접속이 가능함.
* IPS는 접근 통제 기능을 함과 동시에 유해사이트를 차단하는 기능을 수행함.
* DDOS 장비는 외부에서의 과도한 트래픽 유입량을 검사함.
