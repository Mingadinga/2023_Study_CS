OSI 7 Layer는 Abstraction에 해당한다. TCP/IP나 HTTP는 Implementation이다. TCP/IP나 HTTP를 알고 싶다면 개념으로 가득한 OSI 7 Layer보다는 `구현체` 자체를 공부해야 한다. OSI 7 Layer을 외우려고 애쓸 필요 없다. 

![image](https://github.com/Mingadinga/2023_Study_CS/assets/53958188/1445cbfb-dc9d-4dc2-a3aa-ac8dfca7f39e)

# 컴퓨터의 구성

- User
- Kernel
- HW

# 인터페이스 - OSI 7 Layer

- Application
- Presentation
- Session

---

- Transport
- Network

---

- Data Link
- Physical

# 인터페이스 - DOD

- Application

---

- Transport
- Network

---

- Access

# 구현

- Window Process

(Socket)

---

- TCP
- IP

(Driver)

---

- NIC

# 계층 간 매개체

- Socker : 커널 레벨의 TCP 프로토콜을 추상화하여 애플리케이션에서 사용할 수 있도록 제공되는 파일
- Driver : HW를 움직일 수 있는 Device Driver
