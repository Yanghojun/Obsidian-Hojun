같은 호스트 내에서 실행중인 컨테이너 간 연결할 수 있도록 돕는 논리적 네트워크

Container 생성하면 그 컨테이너 내부의 eth0에 `172.17.0.2` 와 같은 가상 IP 생김.

이 가상 IP/PORT를 Host IP/PORT에 맵핑 시켜야함.


![[Pasted image 20250526142935.png]]
Default는 docker0 (bridge network)