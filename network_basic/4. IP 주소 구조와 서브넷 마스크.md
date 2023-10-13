# IP 주소 구조와 서브넷 마스크

Date: 2023년 10월 13일

IP 주소

- Host의 식별자
- Internet Protocol
- 버전 : IPv4(2^32, 약 43억개), IPv6(128 bit)

서브넷 마스크

- IP 주소는 Net Id + Host Id로 구성된다.
- IP 주소에 서브넷 마스크를 and하면 Net Id를 얻을 수 있다.
- IP : 192.168.60.14, `서브넷 마스크 : FF.FF.FF.0` → Net id : 192.168.60.0
- 좀더 간단하게 표현한게 `CIDR`. /n은 n비트까지가 NetworkId라는 뜻. `192.168.60.14/24`