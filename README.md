# Logic Design and Experiments (논리 회로 및 실험)
## 2019 봄학기, 한림대학교 소프트웨어융합대학 
*  *  *
## [알림] Github 수업 페이지 오픈

## QnA는 [여기](./QnA.md)를 눌러 작성해주세요!

*  *  *

> 현대 디지탈 논리학의 역사적 배경과 기호논리학 및 부울대수학을 강의한다. 부울 대수학 이론을 바탕으로 한 회로 대수학 및 디지털 논리학을 강의하고 디지털 논리에 의한 디지털 회로의 구현에 대해서 세부적으로 살펴본다. ```"조합회로"```와 ```"순차회로"```의 구분에 대해서 살펴보고, 각 회로를 효과적으로 최적화 하여 설계하는 방법에 대해서 강의한다.

*  *  *

## 강의 스탭
### 담당교수: [이정근](https://sites.google.com/site/embeddedsochallymuniv/esoc/jeonggunlee) (소프트웨어융합대학, 빅데이터전공)
   - 연구실:(성호관 1306호실) / Email: Jeonggun.Lee (AT) gmail.com
   - 전화번호: 033-248-2312 (연구실)
   - 홈페이지: [http://www.onchip.net](http://www.onchip.net)
<img src="https://sites.google.com/site/embeddedsochallymuniv/_/rsrc/1307936693055/esoc/jeonggunlee/jglee.JPG" height="200" width="162">

### 담당조교: 김동영
   - (Email: billy009100@naver.com, 연구실: 성호관 1211 임베디드 SoC 연구실)
   
## 교재
   - 주교재: "[디지털논리와 컴퓨터설계](http://www.yes24.com/24/goods/3311366)," 데이비드 해리스,사라 해리스 공저/조영완 등역, 사이텍미디어
   
## 평가방법
   - 중간 - 35%
   - 기말 - 35%
   - 실습:숙제&퀴즈 - 30%
   - 결석 3회 이상 "F"
   - 실습 숙제의 경우 smart campus를 통하여 수집 및 운영
   

## 강의 스케줄 및 자료/노트
   - **Chapter 1 :: From Zero to One (제로에서 하나까지!, [PPT](https://github.com/jeonggunlee/LogicDesign/blob/master/PPT/DDCA_Ch1.pdf))**
      - 1주차 / 2월 26일: 수업 소개: 왜 논리회로를 공부해야할까 ?
         - 인공지능, IoT (사물인터넷) 시대에 논리회로 및 컴퓨터 구조에 대한 이해는 왜 필요한가?
         - Cloud 컴퓨팅 회사들은 왜 하드웨어 칩을 데이터 센터에 집적하는 것일까 ?
         
            - [자료:인공지능 시대, 인공지능 하드웨어의 현재 상황](https://blog.lgcns.com/1804)
            ```
            최근 데이터 센터에서는 GPU, FPGA, ASIC 형태의 가속기를 서버에 장착 ... 된 프로세서 칩으로 빅데이터 시대에
            엄청난 양의 연산이 필요한 데이터 ...
            
            * GPU : Graphic Processing Unit
            * FPGA : Field Programmable Gate Array
            * ASIC : Application Specific Integrated Circuit
            ```
            
            ```
            빅데이터 및 인공지능이 이 사회에 대두될 수 있었던 것은 고성능 컴퓨팅이 지원했기 때문이며,
            이러한 고성능 컴퓨터는 빠르게 발전한 CPU 및 GPU 등이 없었으면 불가능. 
            ```
            - [동영상:네이버 클라우드 플랫폼의 CPU Intensive 서버](https://www.youtube.com/watch?v=o0fSu1iErGI)
            - 고성능 가속기 데모: 인텔® Movidius **Neural Compute Stick** 2
               - [동영상:Deep Learning with Intel](https://www.youtube.com/watch?time_continue=343&v=KuM67WfTXBQ): 프로젝트에 딥러닝을 쉽게 활용하는 방법에 대해서 설명
            
      - 2주차 / 3월 5일: 수의 표현
         - 컴퓨터를 설계하는 가장 기초적인 작업: 데이터의 표현 - 수의 표현 (양수/음수)
            - [자료:수의 표현](https://namu.wiki/w/%EC%BB%B4%ED%93%A8%ED%84%B0%EC%97%90%EC%84%9C%EC%9D%98%20%EC%88%98%20%ED%91%9C%ED%98%84)
            - [동영상:이진수의 음수개념](https://www.youtube.com/watch?v=TvpBEXOMitE)
            - [동영상:진법과 보수](https://www.youtube.com/watch?v=RF04L7KAmKA)
            ```
            컴퓨터에서 어떻게 양수 / 음수가 표현되는지에 대한 바른 이해와 표현된 이진수 값에 대해서 어떻게 더하기와 같은 
            기본 연산이 수행되는지 반드시 숙지하기 바랍니다.
            ```
            
      - 3주차: 논리소자 / CMOS             
         - 특정 기능을 갖는 회로 블럭을 만드는 기본 회로 소자: AND, OR, NOT, NAND, NOR 등
            - [동영상:마인크래프트를 이용한 논리회로 이해하기](https://www.youtube.com/watch?v=8BCHLK0Aets)
            - [동영상:논리회로의 개념과 논리식](https://www.youtube.com/watch?v=KxO89jV2s8o)
            - [자료:마인크래프트로 컴퓨터 만들기](https://namu.wiki/w/%EB%A7%88%EC%9D%B8%ED%81%AC%EB%9E%98%ED%94%84%ED%8A%B8/%ED%9A%8C%EB%A1%9C)
         - 현대 반도체 기술에 대한 소개 - CMOS / FinFET
            - 최근 프로세서 설계 경향: 클럭 주파수 / 전력 / 온도 문제
            - [CPU 온도로 계란 익히기](https://www.youtube.com/watch?v=IxGtV0CmsT0)
         
   - **Chapter 2 :: Combinational Logic Design ([조합회로 설계, PPT](https://github.com/jeonggunlee/LogicDesign/blob/master/PPT/DDCA_Ch2-%EB%85%BC%EB%A6%AC%ED%9A%8C%EB%A1%9C02.pdf))**
      - 4주차: 부울 식 / 논리 회로
      - 5주차: 카르노맵
      - 6주차: 조합회로 빌딩 블럭
         - [동영상:조합회로와 논리회로](https://www.youtube.com/watch?v=zaWp0U3tXv4&list=PLrFy4sCm2owoj-O71kjLoNc_dMEVzUYlR&index=6)
         
   - **7주차: 중간고사**
   
   - **Chapter 3 :: Sequential Logic Design (순차회로 설계, PPT)**
      - 8주차: 래치 및 플립플롭 (Latch and Flip-Flop)
         - [동영상:플립플롭](https://www.youtube.com/watch?v=n7iyMd2NsUk)
      - 9주차: 유한 상태 기계 (Finite State Machine)
         - [동영상:Digital Logic - State Tables and State Diagrams](https://www.youtube.com/watch?v=2TGfiaCrL2s): 한국어 캡션 활용하기 바랍니다.
      - 10주차: 순차회로의 타이밍 (Timing)
      
   - **Chapter 5 :: Digital Building Blocks (회로 빌딩 블록, PPT)**
      - 11주차: 산술회로 (덧셈기, 뺄셈기, 비교기, ALU, 쉬프터 등)
      - 12주차: Fixed-point (고정소수점) vs Floating-point  (부동소수점)
      - 13주차: 메모리 / Logic Array
   - **Chapter 4 :: Hardware Description Languages (하드웨어 설계 언어, HDL, PPT)**
      - Verilog HDL 소개
      
   - **14주차: 기말고사**
   
## 실습
   ![Alt text](https://github.com/jeonggunlee/Computer_Arch_2018_Fall/blob/master/img/openss.png "오픈소스교과목")
   - 실습 소프트웨어로써, **[LogiSim](http://www.cburch.com/logisim/)** 논리회로 설계 및 시뮬레이터를 사용합니다.
      - Logisim은 Open Source Software이며, 누구나 자유롭게 사용가능하며, 소스코드 역시 오픈되어 있고 수정 가능합니다.
         - It is free! (Logisim is open-source (GPL).)
         
   ![Alt text](http://www.cburch.com/logisim/shot-2.7.0.png)         
      

## 참조 사이트
   - 참조 사이트
   - [한림대학교 오픈소스 SW 교육센터](https://github.com/Hallym-OpenSourceSW/Hallym-OpenSourceSW.github.io)
   

