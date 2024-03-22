# 이기재 학번(202030224)

## 2024년 03월 15일 금 강의
github를 비쥬얼 스튜디오와 연동하여 사용하는 법을 익혔다.
커밋 기능을 이용하여 수정,생성한 프로젝트를 github에 업로드하는 법을 익혔다.
-좌측 3번째 항목에 commit 버튼을 이용.이후 Sync Changes 버튼을 푸쉬하면 github에 업로드 된다.(commit 버튼 위에 메세지를 반드시 입력하여야 한다.)
Repository를 생성하고 삭제하는 법을 익혔다.
## 2024 03월 22일 금 강의
-프로그래밍 언어에 대한 강의
기계어:0,1의 이진수로 구성
      CPU는 기계어만 이해할 수 있다.
어셈블리어:기계어와 1대1 대응이 되는 저급 언어

-프로그래밍과 컴파일
소스:프로그래밍 언어로 작성된 텍스트 파일
컴파일:소스 파일을 컴퓨터가 이해할 수 있도록 기계어로 변환하는 것(ex:java->class)

-자바가 만들어진 이유
플랫폼 호환성 문제 해결
플랫폼의 독자적 언어 개발
메모리 사용량이 적고 다양한 플롯폼을 가지는 가전 제품에 적용

-프로그램의 플랫폼 호환성이 없는 이유

기계어가 cpu마다 다름
운영체제마다 API가 다름
운영체제마다 실행파일의  형식이 다름

-WORA 자바의 플랫폼 독립성

WORA는 한번 작성된 코드가 모든 플랫폼에서 실행되는 자바의 특징
C/C++ 같은 기존 언어가 가진 모든 플랫폼의 종속성을 극복하였다.
네트워크가 연결된 어느 클라이언트에서든 실행이 된다.

-JVM
JVM(java virtual machine)이 있기에 자바는 WORA가 가능하다
각기 다른 플랫폼에 설치된다.

-바이트 코드
바이트 코드는 자바 소스를 컴파일한 목적 코드이다
CPU에 종속적이지 않는다
JVM에 의해 해석되고 실행된다

-자바 응용프로그램 실행 환경
실행 환경(JVM + 자바 플랫폼의 다양한 클래스 라이브러리(Java API))

-JDK와 JRE
JDK(Java Development Kit)
자바 응용 개발 환경으로 개발에 필요한 도구가 들어있다.
java,javac,jmod,javadoc,jar 등이 bin 디렉토리에 들어있다
JRE(Java Runtime Environmet)
자바 실행 환경으로 컴파일된 자바 API 들이 포함된 모듈 파일들이다.

-모듈화
Java 9에서 정의한 새로운 기능
모듈:자바 패키지들과 이미지,XML 파일 등의 자원들을 묶은 단위
모듈 프로그래밍:자바 응용 프로그램을 직소 퍼즐 처럼 연결한 것

-Java 플랫폼의 모듈화
실행 시간에 사용되는 자바 API 모든 클래스들을 모듈로 분할했다.

-모듈화의 목적
세밀한 모듈화로 자바 응용프로그램이 실행되는데 필요없는 모듈 배제
작은 크기 실행 환경 구성
하드웨어가 열악한 소형 IoT 장치 지원
모듈화가 아닌 기존 자바 프로그래밍으로 하여도 무관하다.

-Java API
JDK에 포함된 클래스 라이브러리
개발자는 API를 이용해 쉽고 빠르게 자바 프로그램 개발을 가능하다.

-Java 패키지
서로 관련된 클래스들을 분류해 묶어 둔 것
계층구조로 이루어져 있다.
개발자 자신의 패키지 생성이 가능하다.
API는 JDK에 패키지 형태로 제공된다.

-자바 프로그램 개발
자바 소스 편집은 어떤 편집기를 사용하여도 무관하다.
작성 후에 hello2030.java로 저장한다.이때 반드시 클래스와 동일한 이름으로 저장한다.확장자는 .java로 한다.