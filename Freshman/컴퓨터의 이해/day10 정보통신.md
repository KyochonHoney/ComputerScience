## 정보통신

1. 정보통신의 역사
    * SAGE(Semi-Automatic Ground Environment) 시스템(1958)
        - 컴퓨터와 통신을 결합시킨 최초의 컴퓨터 통신 시스템
    * SABRE(Semi-Automatic Business Research Environment) 시스템(1964)
        - American Airline사의 여객기 좌석 예약 업무 처리
    * ★ARPA(Advanced Research Project Agency) Network (1960년대)
        - Internet의 전신 (- TCP/IP 개발)
        - 패킷 교환 네트워크 (1968년 계획, 1969년 구축)
    * ALOHA (Addictive Links Online Hawaii Area) 시스템 (1968년)
        - 하와이 대학, 실험적 무선 패킷 교환 네트워크
    * 1970년대 상용화
        - TELENET : 최초의 상용 패킷 교환 네트워크
        - TYMNET : 부가가치 통신망
    <br/>
    <br/>
    <br/>
    정보통신의 역사
    1940 : 원격 계산기에 데이터 통신
    1958 : SAGE 시스템
    1964 : SABRE 시스템
    1968 : ARPA Network, ALOHA 시스템
    1974 : TELENET
    ___

2. 정보통신망의 목적
    * 자원의 공유
    * 신뢰도 향상
    * 처리기능의 분산
    
    ___

3. 데이터통신 시스템의 구성요소
> 단말장치 - 신호변환장치 - 신호변환장치 - 통신제어장치 - 컴퓨터 <br/>
> <------------------데이터 전송 시스템 --------------------> <-데이터 처리 시스템->

___
4. 통신선로의 구성
    - 점대점 선로와 멀티드롭 선로
___
5. 네트워크 연결장치
    - 네트워크 세그먼트를 서로 연결하거나 네트워크를 인터넷에 연결시키기 위한 통신 장치
    * Modem
    * NIC ( Network Interface Card )
    * HUB ( dumb hub; switching hub)
        - 하나의 노드에서 수신한 신호를 정확히 재생하여 다른 노드로 전송하는 장치
    * Repeater
        - 장거리 전송을 위해 신호를 새로 재생시키거나 출력 전압을 높여 재전송해줌
    * Bridge
        - 복수개의 LAN을 연결하는 장치
    * Router
        - IP 네트워크 간의 연결 또는 IP 네트워크와 인터넷 간의 연결하기 위한 장치
    * Gateway
        - 서로 다른 통신 프로토콜을 사용하는 네트워크들을 연결하기 위한 장치
___
6. 데이터 전송방식
    1. 전송방향에 따른 전송방식
        * 단향식 (simplex) 방송
        * 반이중식 (half duplex) 무전기
        * 전이중식 (full duplex) 전화

    2. 전송모드에 따른 전송방식
        * 직렬전송 (serial transmission)
        * 병렬전송 (parriel transmission)
___
7. 데이터 교환방식
    * 회선교환(circuit switching) 방식
    * 축적교환(store-and-forward switching) 방식
        - 메시지교환 방식
        - 패킷교환 방식
            - 가산회선 방식
            - 데이터그램 방식
___
8. 정보통신망 유형
    1. 위상에 따른 유형
        * 성형(star)
        * 환형(ring)
        * 버스형(bus)
        * 그물형(mesh)
        * 트리형(tree)
    
    2. 규모에 따른 유형
        * PAN (Personal Area Network)
        * LAN (Local Area Network)
        * CAN (Campus Area Network)
        * MAN (Metroplitan Area Network)
        * WAN (Wide Area Network)

    3. 활용 목적에 따른 유형
        * VAN (Value Added Network)
            - 통신망사업자에게 전용선을 임차하여 구성
            - 홈뱅킹, 홈쇼핑 등의 서비스 제공
        * ISDN (Integrated Services Digital Network)
            - 여러 서비스를 통합하여 제공 ( 전화망과 컴퓨터망의 통합 )
            - 하나의 망에서 음성 통신과 영상 통신이 가능함
        * B-ISDN (Broadband ISDN)
            - 광대역 서비스가 가능한 ISDN
            - 광케이블을 이용한 통신 (수백Mbps)
___
9. 통신 프로토콜의 종류
    * TCP(Transmission Control Protocol)
    * IP(Internet Protocol)
    * UDP(User Datagram Protocol)
    * SMTP(Simple Mail Transfer Protocol)
    * POP3(Post Office Protocol 3)
    * HTTP(Hyper-Text Transfer Protocol)