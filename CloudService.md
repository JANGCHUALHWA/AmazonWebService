## 아마존 서비스 클라우드 컴퓨팅 정리 
클라우드 시스템 구축 관련1

## 인프라 = 어떤 시스템이나 서비스를 운영하는 데 필요한 기초적인 기반 시설
ec2 S3 이런게 다 인프라다 모든 기반의 요소 라고 생각하자



## 클라우드 : 클라우드란 IT 자원 물리적인 개념 IT 인터넷 을 통해 제공되는 플랫폼

클라우드 컴퓨팅 : 클라우드를 활용하는 서비스 적인 개념 
클라우드 컴퓨팅은 클라우드 인프라를 활용해 IT 자원을 온디맨드로 제공받고, 
사용한 만큼 비용을 지불하는 서비스 중심의 컴퓨팅 방식이다.

필요한 클라우드 IT 자원(서버, 저장소, 네트워크 등)을

온디맨드 : 필요할 때 즉시가 포인트(On-Demand) 사용한느것


## 클라우드 컴퓨팅의 이점:
민첩성 : 클라우드를 활용해 광범위한 기술에 쉽게 접근 가능해서 모든것을 빠르고 혁신적 구축 가능 

탄력성 : 클라우드 자원을 과하게 구성할 필요가없고 손쉽게 자원을 확장하거나 축소하여 탄력적 이용 가능

비용절감 : 사용한 만큼만 비용을 내는(Pay-as-you-go) 구조  IT자원을 구축하는 공간을 만들때 소요되는 비용을 
생각 하면 클라우드 컴퓨팅 서비스를 사용하는 것이 훨씬 비용 절감 할수 있다.

이런 이점으로 인해

손쉬운 글로벌 서비스 

예상치 못한 트래픽 폭주의 대응

빅데이터 인공지능 서비스 확장

## 클라우드 컴퓨팅 인프라에 대한 클라우드 서비스 유형

클라우드 사용자가 어느 영역까지 관리 하고 ,
클라우드의 공급자는 어느 영역까지 관리하느냐에 따른 유형 분리

서비스 유형 3가지  (laaS), (Paas), (SaaS)  aas= as a Service
laaS: Infrastructure as a Service 서버 공급자 나머지 사용자 애플리케이션배포

클라우드 공급자는 : 서버,네트워크,스토리지,가상화 기능을 관리 인프라를 관리한다라고 생각하자
인프라의 제공자

클라우스 사용자: OS: 운영체제 미들웨어 런타임 데이터 애플리케이션
간단하게 운영체제 및 애플리케이션을 관리한다 

인프라의 위에서 시스템을 운영하는 사람

PaaS (Platform as a Service) 서버/운영체제 공급자 나머지 사용자 애플리케이션배포
개발 및 배포를 위한 플랫폼을 제공한다 
클라우드 공급자: 인프라를 제공하고 운영체제 를 제공함
사용자 : 서버 및 OS관리 불필요 애플리케이션 코드와 데이터만 관리


SaaS (SoftWare as a Service) 그냥 다해줄께 로그인해서 써라잉
클라우드 공급자가 소프트 웨어 를 설치 없이 이용 유지보수 업데이트 다해줄께


클라우드 사용자 : 우리는 그냥 써비스를 받기만 할께 돈내고 

## 온프레미스의 : 정의 전통적인 방법
 premise : 기본 건물 토지 라는 뜻

자체적인 공간과 자원을 이용하여
사용자가 직접 구축 운영하는 방식 클라우드를 제공받아서 쓰는게아닌 우리가
직접 다 해야댐

