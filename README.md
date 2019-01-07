# Logic Design and Experiments (논리 회로 및 실험)
## 2019 봄학기, 한림대학교 소프트웨어융합대학 
*  *  *
## [알림] Github 수업 페이지 오픈

## QnA는 [여기](./QnA.md)를 눌러 작성해주세요!

*  *  *

> 현대 디지탈 논리학의 역사적 배경과 기호논리학 및 부울대수학을 강의한다. 부울 대수학 이론을 바탕으로 한 회로 대수학 및 디지털 논리학을 강의하고 디지털 논리에 의한 디지털 회로의 구현에 대해서 세부적으로 살펴본다. ```"조합회로"```와 ```"순차회로"```의 구분에 대해서 살펴보고, 각 회로를 효과적으로 최적화 하여 설계하는 방법에 대해서 강의한다.

*  *  *

## 강의 스탭
### 담당교수: 이정근
   - 연구실:(성호관 1306호실) / Email: Jeonggun.Lee (AT) gmail.com
   - 전화번호: 033-248-2312 (연구실)
   - 홈페이지: [www.onchip.net](www.onchip.net)
   
### 담당조교: X X X
   - ( xxx 연구실, Email: xxx@gmail.com)
   
## 교재
   - 주교재: "[디지털논리와 컴퓨터설계](http://www.yes24.com/24/goods/3311366)," 데이비드 해리스,사라 해리스 공저/조영완 등역, 사이텍미디어
   
## 평가방법
   - 중간 35%, 기말 35%, 실습 20%, 숙제 & 퀴즈 10%
   - 결석 3회 이상 "F", 사유가 있어도 결석임!
   - 결석 1회를 만회하기 위해서는 "추가로 숙제를 제출"해야함
   - 실습 숙제의 경우 smart campus를 통하여 수집 및 

## 강의노트
   - Chapter 6 :: MIPS 어셈블리 언어와 명령어 포맷, [PPT](https://github.com/jeonggunlee/Computer_Arch_2018_Fall/blob/master/DDCA_Ch6%20-%201.pptx)
      - 6.1 소개
      - 6.2 어셈블리 언어
      - 6.3 기계어
      - 6.4 어셈블리를 이용한 프로그래밍 구조
      - 참조 동영상
          - [ISA 1.1 Introduction to the ISA](https://www.youtube.com/watch?v=PlavjNH_RRU)
          - [ISA 1.2 MIPS Instructions](https://www.youtube.com/watch?v=ykI9nwSNFfM)
   - Chapter 7 :: Microarchitecture: MIPS 프로세서의 구조, Pipelining
      - 7.1 소개
         - 7.1.1 아키텍쳐의 상태 및 명령어 집합(Instruction Set)
         - 7.1.2 설계 과정 (데이터패스, 제어패스)
         - 7.1.3 MIPS 마이크로아키텍쳐
      - 7.2 성능 분석
      - 7.3 Single-Cycle 프로세서
         - 7.3.1 Single-Cycle 데이터패스
         - 7.3.2 Single-Cycle 제어
         - 7.3.3 추가적인 명령어 지원
         - 7.3.4 성능 분석
   - Chapter 8 :: Memory Systems: 메모리 계층, 캐쉬메모리 구조
      - 8.1 소개
      - 8.2 메모리 시스템 성능 분석
      - 8.3 Caches (캐시 메모리)
         - 8.3.1 어떤 데이터를 캐시 메모리에 넣을것인가?
         - 8.3.2 캐시 메모리에서 데이터를 어떻게 찾을 것인가?
         - 8.3.3 어떤 데이터를 바꿀 것인가?
         - 8.3.4 고급 캐시 설계

## 실습
   - QtSpim 을 이용한 MIPS 어셈블러 프로그래밍 ([Youtube](https://www.youtube.com/results?search_query=Qtsim+PCSIM+MIPS))
   - [요기-한국어!!!](https://www.joinc.co.kr/w/Site/Assembly/Documents/Spim) : SPIM에 대한 자세한 한글 설명을 볼수 있습니다.
   - [조기](http://chortle.ccsu.edu/AssemblyTutorial/index.html) : 위 사이트의 영문 원본 문서를 볼수 있습니다.
   - Spim 공부를 위한 [좋은 곳](http://www.cs.ccsu.edu/~markov/ccsu_courses/254syllabus.html)!
   
   > SPIM은 오픈소스 SW로 구현된 MIPS 프로세서 시뮬레이터입니다. [MIPS 시뮬레이터](http://spimsimulator.sourceforge.net/)
   > 관심있는 학생들은 SPIM 시뮬레이터의 소스코드를 분석하고 수행시켜봄으로써 보다 자세히 명령어의 수행 구조 및 프로세서 구조에 대해서 이해할수 있습니다.
   > 컴퓨터구조 교과목은 오픈소스 SW에 대한 이해도 함께 증진시키는 것을 목적으로 합니다.
   
   ![Alt text](https://github.com/jeonggunlee/Computer_Arch_2018_Fall/blob/master/img/openss.png "오픈소스교과목")

## 참조 사이트
   - [MIPS 프로세서 위키백과사전](https://ko.wikipedia.org/wiki/MIPS_%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98) : 밉스 프로세서에 대한 자세한 설명을 한글로 볼수 있습니다.

