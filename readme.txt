-------------------------------------------------

			# AWS-WORK #

-------------------------------------------------

########################################################
### AWS

https://aws.amazon.com
https://aws.amazon.com/ko/

https://docs.aws.amazon.com/index.html

https://health.aws.amazon.com/health/status

########################################################
### Reference

https://www.gilbut.co.kr/book/view?bookcode=BN001010
https://pyrasis.com/aws.html
https://github.com/pyrasis/awsbook

########################################################
### AWS

아마존 웹 서비스를 다루는 기술
https://pyrasis.com/aws.html
[목차]

1장 왜 AWS인가?
__1.1 가상화와 클라우드 컴퓨팅
__1.2 아마존 웹 서비스
__1.3 스타트업과 클라우드 컴퓨팅
__1.4 다양한 활용 사례
____1.4.1 화성탐사로버 큐리오시티
____1.4.2 넷플릭스
____1.4.3 애니모토
____1.4.4 아모레퍼시픽
____1.4.5 모바일 게임 쿠키런

2장 AWS 기본 개념 살펴보기
__2.1 리전, 지역
__2.2 가용 영역
__2.3 에지 로케이션

3장 AWS 계정 생성하기

4장 가상 서버를 제공하는 EC2
__4.1 EC2 인스턴스 유형
__4.2 EC2 인스턴스 구매 옵션
__4.3 EC2 인스턴스 생성하기
__4.4 EC2 인스턴스에 접속하기
____4.4.1 Windows에서 PuTTY로 접속하기
____4.4.2 Linux, Mac OS X에서 접속하기
__4.5 가상 스토리지를 제공하는 EBS
____4.5.1 EBS 볼륨 생성하기
____4.5.2 EC2 인스턴스에 EBS 볼륨 장착하기
____4.5.3 EC2 인스턴스에서 EBS 볼륨 포맷하기
____4.5.4 EC2 인스턴스에서 EBS 볼륨 마운트하기
____4.5.5 EC2 인스턴스에서 EBS 볼륨 제거하기
__4.6 EBS 스냅샷 활용하기
____4.6.1 EBS 스냅샷 생성하기
____4.6.2 EBS 스냅샷으로 EBS 볼륨 생성하기
____4.6.3 EBS 스냅샷으로 AMI 생성하기
____4.6.4 EBS 스냅샷을 다른 리전으로 복사하기
__4.7 인스턴스 스토리지를 Root 장치로 사용하는 EC2 인스턴스 생성하기
__4.8 EC2 기타 설정 및 기능

5장 Security Group으로 방화벽 설정하기

6장 고정 IP를 제공하는 Elastic IP
__6.1 Elastic IP 할당받기
__6.2 Elastic IP 연결하기

7장 EC2 인스턴스 접속을 위한 키 쌍
__7.1 키 쌍 생성하기
__7.2 외부 키 쌍 파일 사용하기
____7.2.1 PuTTY로 생성한 키 쌍 파일 활용하기
____7.2.2 Linux와 Mac OS X에서 생성한 키 쌍 파일 활용하기
__7.3 이미 생성된 EC2 인스턴스에서 공개 키 바꾸기

8장 AMI
__8.1 AWS Marketplace
__8.2 EC2 인스턴스로 AMI 생성하기
__8.3 AMI를 다른 리전으로 복사하기
__8.1 인스턴스 스토리지를 Root 장치로 사용하는 EC2 인스턴스 생성하기

9장 API와 툴 사용을 위한 액세스 키 생성하기

10장 AWS 리소스의 상태를 모니터링하는 CloudWatch
__10.1 CloudWatch 알람 생성하기
__10.2 CloudWatch 커스텀 측정치 사용하기

11장 HTTP 프로토콜과 연동되는 스토리지 S3
__11.1 S3 버킷 생성하기
__11.2 S3 버킷에 파일 올리기/받기
__11.3 S3 세부 설정하기
____11.3.1 S3 객체 권한 관리하기
____11.3.2 S3 버킷 권한 관리하기
____11.3.3 S3 정적 웹사이트 호스팅 사용하기
____11.3.4 HTTP Referer로 S3 접근 제한하기
____11.3.5 S3 객체 스토리지 클래스, 암호화 설정하기
____11.3.6 S3 객체 메타데이터 설정하기
____11.3.7 S3 버킷 로그 설정하기
____11.3.8 S3 버킷 버저닝 설정하기
____11.3.9 S3 버킷 수명 주기(Lifecyle) 설정하기
____11.3.10 S3 버킷 기타 설정

12장 전 세계에 콘텐츠를 배포하는 CDN 서비스인 CloudFront
__12.1 CloudFront 배포(Distribution)
__12.2 S3와 CloudFront 연동하기
__12.3 CloudFront 커스텀 오리진 사용하기
____12.3.1 EC2와 CloudFront 연동하기
____12.3.2 외부 서버와 CloudFront 연동하기
__12.4 Signed URL로 CloudFront 콘텐츠 사용 제한하기
____12.4.1 Signed URL 사용 설정하기
____12.4.2 Signed URL 서명을 위한 CloudFront 키 쌍 생성하기
____12.4.3 Canned Policy를 사용한 Signed URL 생성하기
____12.4.4 Custom Policy를 사용한 Signed URL 생성하기
__12.5 Invalidation으로 CloudFront 콘텐츠 갱신하기

13장 확장 가능한 관계형 데이터베이스를 제공하는 RDS
__13.1 RDS DB 인스턴스 클래스
__13.2 RDS 예약 인스턴스
__13.3 RDS 데이터베이스 엔진과 라이선스 모델
__13.4 RDS DB 인스턴스 생성하기
__13.5 RDS DB 인스턴스 Security Group 생성 및 설정하기
__13.6 RDS DB 인스턴스 사용하기
__13.7 RDS DB 스냅샷 활용하기
____13.7.1 RDS DB 스냅샷 생성하기
____13.7.2 RDS DB 스냅샷으로 RDS DB 인스턴스 생성하기
____13.7.3 RDS 스냅샷을 다른 리전으로 복사하기
__13.8 RDS를 특정 시점으로 복구하기
__13.9 RDS DB 인스턴스 Read Replica 생성하기
__13.10 RDS DB 인스턴스 성능 확장하기
__13.11 RDS 기타 설정 및 기능

14장 확장 가능한 NoSQL 분산 데이터베이스를 제공하는 DynamoDB
__14.1 DynamoDB의 데이터 모델
__14.2 DynamoDB에 맞는 데이터 구조 설계하기
__14.3 DynamoDB 테이블 생성하기
__14.4 DynamoDB 테이블에 데이터 추가하기
__14.5 DynamoDB 데이터 쿼리하기
__14.6 DynamoDB 기타 설정 및 기능

15장 확장 가능한 분산 인 메모리 캐시를 제공하는 ElastiCache
__15.1 ElastiCache 캐시 노드 유형
__15.2 ElastiCache 예약 캐시 노드
__15.3 ElastiCache Memcached 클러스터 생성하기
__15.4 ElastiCache Memcached 클러스터 Security Group 생성 및 설정하기
__15.5 ElastiCache Memcached 클러스터에 캐시 노드 추가하기
__15.6 ElastiCache Redis 클러스터 생성하기
__15.7 ElastiCache Redis 클러스터 Security Group 생성 및 설정하기
__15.8 ElastiCache Redis 클러스터 스냅샷 활용하기
____15.8.1 ElastiCache Redis 클러스터 스냅샷 생성하기
____15.8.2 ElastiCache Redis 클러스터 스냅샷으로 Redis 클러스터 생성하기
__15.9 ElastiCache Redis 클러스터 Read Replica 생성하기

16장 사용자와 그룹을 생성하여 접근제어 및 권한관리를 제공하는 IAM
__16.1 IAM 그룹 생성하기
__16.2 IAM 사용자 생성하기
__16.3 IAM 사용자로 AWS 콘솔에 접속하기
__16.4 IAM 역할 활용하기
____16.4.1 IAM 역할 생성하기
____16.4.2 IAM 역할을 사용하는 EC2 인스턴스 생성하기
__16.5 IAM 기타 설정 및 기능

17장 AWS 리소스와 연동 가능한 DNS 서비스 Route 53
__17.1 Route 53 Hosted Zone 생성하기
__17.2 Route 53 A 레코드 생성하기
__17.3 Route 53와 S3 연동하기
__17.4 Route 53와 CloudFront 연동하기
__17.5 Route 53 DNS Failover 활용하기
__17.6 Route53 Latency Based Routing, Weighted Round Robin, Geo Routing 설정하기
__17.7 Route 53에서 도메인 구입하기

18장 부하 분산과 고가용성을 제공하는 ELB
__18.1 ELB 로드 밸런서 생성하기
__18.2 EC2 인스턴스에 웹 서버 실행하기
__18.3 ELB 로드 밸런서 Sticky Session 기능 사용하기

19장 자동으로 EC2 인스턴스를 생성하여 서비스를 확장하는 Auto Scaling
__19.1 Auto Scaling에 사용할 AMI 생성하기
__19.2 EC2 생성 옵션 설정과 Auto Scaling 그룹 생성하기

20장 가상 네트워크를 제공하는 VPC
__20.1 VPC 생성하기
__20.2 VPC 서브넷 생성하기
__20.3 VPC 인터넷 게이트웨이 생성하기
__20.4 VPC 기타 설정 및 기능

21장 데이터 보관 및 백업을 위한 매우 저렴한 스토리지 서비스 Glacier
__21.1 Glacier 볼트 생성하기
__21.2 Glacier 볼트에 파일 올리기
__21.3 Glacier 볼트에서 파일 받기

22장 서버 구성을 자동화하는 CloudFormation
__22.1 CloudFormation 템플릿 기본 구조
__22.2 EC2 인스턴스를 생성하는 CloudFormation 템플릿
__22.3 EC2 인스턴스를 생성하고 웹 서버를 설치, 실행하는 CloudFormation 템플릿
__22.4 EC2 인스턴스를 생성하고 Security Group을 설정하는 템플릿
__22.5 CloudFormation 템플릿으로 CloudFormation 스택 생성하기

23장 간편하게 사용하는 애플리케이션 플랫폼 서비스 Elastic Beanstalk
__23.1 Elastic Beanstalk으로 Node.js 애플리케이션과 환경 생성하기
__23.2 AWS 콘솔에서 Elastic Beanstalk Node.js 애플리케이션 배포하기
__23.3 Git으로 Elastic Beanstalk Node.js 애플리케이션 배포하기
__23.4 Elastic Beanstalk 환경 URL 교체로 무중단 배포하기

24장 애플리케이션 구성과 배포를 자동화하는 OpsWorks
__24.1 OpsWorks 스택 생성하기
__24.2 OpsWorks PHP 레이어 생성하기
__24.3 OpsWorks PHP 인스턴스 생성하기
__24.4 OpsWorks PHP App 생성하기
__24.5 OpsWorks PHP App 배포하기
__24.6 OpsWorks 커스텀 Chef 레시피 사용하기

25장 검색 서비스를 제공하는 CloudSearch
__25.1 CloudSearch 검색 인스턴스 유형
__25.2 CloudSearch 검색 도메인 생성하기
__25.3 CloudSearch 검색 도메인에 데이터 올리기
__25.4 CloudSearch 검색 도메인에서 검색하기
____25.4.1 CloudSearch 검색 자동완성 사용하기
____25.4.2 CloudSearch 검색 식 사용하기
__25.5 CloudSearch 검색 도메인 엔드포인트 주소 활용하기
____25.5.1 CloudSearch 인덱스 구조를 설계하고 검색 도메인 생성하기
____25.5.2 CloudSearch 검색 도메인 엔드포인트로 데이터 올리기
____25.5.3 CloudSearch 검색 도메인 엔드포인트 주소로 검색하기

26장 푸시 알림 서비스 SNS
__26.1 SNS 토픽과 이메일 구독 생성하기
__26.2 SNS 토픽에 메시지 보내기
__26.3 SNS로 구글 안드로이드에 푸시 알림 보내기
____26.3.1 구글 GCM API 사용 등록하기
____26.3.2 SNS 애플리케이션 생성하기
____26.3.3 예제 안드로이드 애플리케이션 실행 및 Registration ID 생성하기
____26.3.4 SNS 애플리케이션에 엔드포인트 추가하기
____26.3.5 SNS 애플리케이션의 엔드포인트에 메시지 보내기
____26.3.6 SNS 토픽에 GCM 구독 생성하기
__26.4 SNS로 애플 iOS에 푸시 알림 보내기
____26.4.1 iOS App ID 생성하기
____26.4.2 인증서 요청 생성하기
____26.4.3 APNS 인증서 생성하기
____26.4.4 SNS 애플리케이션 생성하기
____26.4.5 예제 iOS 애플리케이션 실행 및 Device Token 생성하기
____26.4.6 SNS 애플리케이션에 엔드포인트 추가하기
____26.4.7 SNS 애플리케이션의 엔드포인트에 메시지 보내기
____26.4.8 SNS 토픽에 APNS 구독 생성하기

27장 이메일 전송 서비스 SES
__27.1 이메일 주소 인증하기
__27.2 도메인 인증하기
__27.3 프로덕션 액세스 권한 얻기
__27.4 SES로 테스트 메일 보내기
__27.5 SES SMTP로 메일 보내기

28장 메시지 큐를 제공하는 SQS
__28.1 SQS 큐 생성하기
__28.2 SQS 처리 실패 큐 생성하기
__28.3 SQS 큐에 메시지 보내기/받기

29장 동영상 인코딩 서비스 Elastic Transcoder
__29.1 Elastic Transcoder 파이프라인과 작업 생성하기

30장 AWS API, CLI 활용하기
__30.1 Node.js용 AWS SDK 설치하기
__30.2 AWS CLI 설치하기
__30.3 EC2
__30.4 CloudWatch
__30.5 ELB
__30.6 Auto Scaling
__30.7 S3
__30.8 CloudFront
__30.9 DynamoDB
__30.10 CloudSearch
__30.11 SNS
__30.12 SES
__30.13 SQS

31장 글로벌 사진 사이트 구축하기
__31.1 이미지, 소스 저장용 S3 버킷 생성하기
__31.2 이미지 정보 저장용 RDS DB 인스턴스 생성하기
__31.3 이미지 처리용 SQS 큐 생성하기
__31.4 S3, SQS 접근용 IAM 역할 생성하기
__31.5 웹 서버용 ELB 로드 밸런서 생성하기
__31.6 웹 서버, 이미지용 CloudFront 배포 생성하기
__31.7 Route 53로 도메인 연결하기
__31.8 Node.js로 웹 서버 작성하기
____31.8.1 웹 서버 및 사이트 내용 둘러보기
__31.9 웹 서버 AMI 생성하기
__31.10 웹 서버 Auto Scaling 설정하기
__31.11 Node.js로 이미지 변환 서버 작성 및 구축하기
____31.11.1 이미지 변환 서버 내용 둘러보기
____31.11.2 이미지 변환 서버 구축하기
__31.12 사진 사이트 동작 확인하기

32장 자동 확장 가능한 콘서트 티켓 예매 사이트 구축하기
__32.1 소스 저장용 S3 버킷 생성하기
__32.2 좌석 데이터 저장용 RDS DB 인스턴스 생성하기
__32.3 좌석 상태 갱신용 ElastiCache 캐시 클러스터 생성하기
__32.4 S3 접근용 IAM 역할 생성하기
__32.5 웹 서버용 ELB 로드 밸런서 생성하기
__32.6 웹 서버용 CloudFront 배포 생성하기
__32.7 Route 53로 도메인 연결하기
__32.8 Node.js로 웹 서버 작성하기
____32.8.1 웹 서버 및 사이트 내용 둘러보기
__32.9 웹 서버 AMI 생성하기
__32.10 웹 서버 Auto Scaling 설정하기
__32.11 티켓 예매 사이트 동작 확인하기

33장 자동 확장 가능한 모바일 게임 서버 구축하기
__33.1 소스 저장용 S3 버킷 생성하기
__33.2 순위 산출용 ElastiCache 캐시 클러스터 생성하기
__33.3 게임 데이터 저장용 RDS DB 인스턴스 생성하기
__33.4 로그 저장용 DynamoDB 테이블 생성하기
__33.5 S3, DynamoDB 접근용 IAM 역할 생성하기
__33.6 게임 서버용 ELB 로드 밸런서 생성하기
__33.7 Route 53로 도메인 연결하기
__33.8 Node.js로 게임 서버 작성하기
____33.8.1 게임 서버 내용 둘러보기
__33.9 게임 서버 AMI 생성하기
__33.10 게임 서버 Auto Scaling 설정하기
__33.11 게임 서버 동작 확인하기

부록
요금 계산기
Windows EC2 인스턴스 사용하기
S3을 s3fs로 파일시스템처럼 사용하기
S3을 s3cmd로 관리하기
Auto Scaling 그룹의 EC2 인스턴스에 소스 배포하기
AWS Visual Studio 툴킷
AWS Eclipse 툴킷
요금 절약하기 

