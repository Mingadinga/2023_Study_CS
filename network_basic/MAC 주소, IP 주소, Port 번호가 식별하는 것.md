![image](https://github.com/Mingadinga/2023_Study_CS/assets/53958188/be056993-3e21-41a3-8c01-68f5d6c57bf7)

| 종류 | Layer | 식별 대상 | 할당 개수 | 비고 |
| --- | --- | --- | --- | --- |
| MAC 주소 | L1 Access Level | NIC (Network Interface Card - 랜 카드) | NIC 하나당 MAC 한개 | ex) 노트북 - 유선, 무선 NIC 하나씩 있으므로 MAC 2개 | MAC 주소 변경 가능 |
| IP 주소 | L3 Network Level | HOST(인터넷에 연결된 컴퓨터) | N개. NIC 하나에 IP 주소 여러개 매핑됨 |  |
| Port 번호 | L4 Transport Level | User Mode : Process<br>Kernel Mode : Service<br>HW Mode : Interface |  | Kernel 관리 : HTTP 서비스 열어주세요<br>네트워크 장치 설치 : 공유기 단자 번호 |
