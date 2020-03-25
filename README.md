# hadoop-framework-1.0
- 하둡 설치 및 클러스터 운영
- 개발환경: VirtualBox6.0, CentOS8 lunux, Hadoop1.0


1. vm설치
    - CentOs8
    - 가상머신 설정: 메모리 2GB, 하드디스크 20GB , Server SW type(only cli)
    

2. 자바설치
3. 하둡설치
4. 클러스터 구성
    - 4개의 서버 호스트 생성.
    - master/slave 설정
    - 보조마스터 설정 (secondarynamenode)
5. 하둡실행
6. HDFS 명령어

### 제고사항
- CentOS 버전에 따른 리소스 지원 제
- firewall 비활성화 꼭 필요한지



<br><br>
용어정리
- 프로토버프(Protobuf): 프로토콜 버퍼. 구글이 개발한 데이터 전송 규칙이다. 직렬화 라이브러리 라고도 부른다.
- 직렬화 라이브러리: json, xml같은 데이터 직렬화 포맷
- 직렬화: 데이터를 파일로 저장 또는 네트워크로 전송하기 위해 binary stream 형태로 저장하는 작업

---
참고 사이트
- [vm설치](https://jyoondev.tistory.com/59?category=825340)
- [하둡실행](https://jyoondev.tistory.com/33?category=824268)
- [프로토버프](https://jyoondev.tistory.com/32)
