## 1. 통관 데이터 적재 시스템
본 시스템은 관세청에 신고된 수출입 통관 Raw 데이터(Text)를 파싱하여 RDBMS 기초 테이블에 데이터를 적재하는 시스템이며, 다음과 같은 시스템을 개발 및 운영하는 것을 목표로한다. 
> 1. 기존의 비효율적인 혹은 무거운 Legacy 코드, 처리과정에 대한 알고리즘 수정, 코드 리팩토링 및 모듈화 처리함으로서 데이터 적재에 대한 처리속도 향상을 목표로한다.
> 2. 처리과정 모니터링 서비스를 개발함으로서 시스템 장애 발생 시 신속하게 대응할 수 있도록 안전성 및 유지보수 기능을 개선한다.

* 기간 : 2020.03 ~ 2021.03
* 기술
    - Linux, Shell Script, Oracle PL/SQL, Java
* 역할
    - 시스템 개발 및 운영
    - Legacy 코드 수정 및 리팩토링
    - 적재 처리 과정 모니터링 프로그램 개발
    - 각 처리 스텝별 수동 실행 프로그램 개발
    - 적재 처리 오류 발생 시 문자 알림 서비스 개발
    - `Solaris (SunOS)` -> `Linux (CentOS)`로 이관
    - 잠정치 데이터 적재 오류처리 대응 및 유지보수
* 성과
    - 기존 대비 30% 처리속도 개선
    - 통관데이터 적재 처리과정 모니터링 간편화
    - 적재 오류 대응 처리속도 향상
    - 노후화된 OS(Solaris)에서 개발 보편성 및 처리 안전성이 높은 OS(Linux) 이관 검증을 통해, 애플리케이션 처리속도 및 데이터 적재 안정성 증진


### 화면
#### 적재 처리 과정 모니터링 프로그램
<img src="img/batch/monitoring-1.png" width="75%" height="75%" style="margin-left: auto; margin-right: auto; display: block;">
<img src="img/batch/monitoring-2.png" width="90%" height="90%" style="margin-left: auto; margin-right: auto; display: block;">

#### 각 처리 스텝별 수동 실행 프로그램
<img src="img/batch/main-1.png" width="90%" height="90%" style="margin-left: auto; margin-right: auto; display: block;">

#### 처리과정
<img src="img/batch/log-1.PNG" width="90%" height="90%" style="margin-left: auto; margin-right: auto; display: block;">

<br>

## 2. 중소벤처기업부 수출통계시스템
본 시스템은 관세청에 신고된 수출입 통관 데이터를 분석하여 각 중소기업별 다각적 수출통계 지표, 행정적 실적관리를 제공함으로서 국내 중소벤처기업 진흥을 위한 인사이트를 발굴한다. 주요 서비스 및 목표는 다음과 같다.

> 1. `국가별`, `품목별`, `지역별`, `기업별` 등의 다각적 수출 통계 지표를 산출 및 데이터를 제공한다.
> 2. 중소기업 `수출 지원 상담` 및 `수출 지원 사업`에 대한 업무실적 통계 및 데이터 분석 제공을 통해 행정·사업 실적관리를 지원한다.

* 기간 : 2020.04 ~ 2021.03
* 기술 : Linux, Java, Spring Framework, JSP, jQuery, MyBatis, Tomcat, Oracle
* 역할
    - 중소벤처기업부 수출통계 시스템 개발 및 운영
    - 데이터 통계 API 및 SQL 개발
    - 통합검색 기능 개발

### 화면
#### 로그인
<img src="img/smba/login-renewal.png" width="100%" height="100%" style="margin-left: auto; margin-right: auto; display: block;">

<br>

#### 수출통계
<img src="img/smba/integrated-all-1.png" width="100%" height="100%" style="margin-left: auto; margin-right: auto; display: block;">
<img src="img/smba/integrated-menu-product-5.png" width="100%" height="100%" style="margin-left: auto; margin-right: auto; display: block;">
<img src="img/smba/integrated-all-graph-1.png" width="90%" height="90%" style="margin-left: auto; margin-right: auto; display: block;">
<img src="img/smba/integrated-all-graph-3.png" width="90%" height="90%" style="margin-left: auto; margin-right: auto; display: block;">
<img src="img/smba/integrated-all-graph-4.png" width="90%" height="90%" style="margin-left: auto; margin-right: auto; display: block;">

#### 행정적 실적관리
<img src="img/smba/smba-history-1.png" width="100%" height="100%" style="margin-left: auto; margin-right: auto; display: block;">
<img src="img/smba/smba-history-2.png" width="100%" height="100%" style="margin-left: auto; margin-right: auto; display: block;">
<img src="img/smba/smba-history-4.png" width="100%" height="100%" style="margin-left: auto; margin-right: auto; display: block;">

