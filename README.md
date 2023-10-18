# Portfolio-Dev.HyunJun

## 정현준  

### [👨‍💻 Notion 포트폴리오](http://)

#### Web Developer 

**1985.05.19**  
email - kerberos0519@gmail.com  
github - http://github.com/kerberos0519     
blog - https://blog.naver.com/kerbeos0519


> 

> 

>


# **목차**
1. [활동 요약](#활동-요약)  
  1-1. [교육/캠프] Nano Jetson 기반의 딥러닝 실습  
  1-2. [교육/캠프] 딥러닝 실습과 Java Framework 현장 실무  
  1-3. [교육/캠프] Unity(유니티) & Blender(블렌더)를 활용한 게임 콘텐츠 제작  
  1-4. [교육/캠프] 진주시 청소년들을 위한 교육 프로그램
  1-5. [경진대회/해커톤] ICT멘토링 
  1-6. [교육/캠프] 진주 폴리텍대학 AI소프트웨어학과  
  
1. [프로젝트 요약](#프로젝트-요약)  
  2-1. [NBE 모니터링 시스템](#ai-software-요약)  
  2-2. [NEAR](#web-요약)  
  

1. [프로젝트 상세](#프로젝트-상세)  
  3-1. [Python] [NBE 모니터링 시스템](#Python-NBE-모니터링-시스템)  
  3-2. [JetsonNano] [JetsonNano](#ios-lifem)   
 

  
<br><br><br>
# **활동 요약**
| 기간 | 프로젝트 명 | 내용     |
|:----|:---------|:--------|
| 2023.08.26 - 2023.09.24  | <img src="./img/jetsonnano.png">Nano Jetson 기반의 딥러닝 실습| Embedded 기초 및 딥러닝 기초, 자율주행 모듈 딥러닝 <br> https://blog.naver.com/PostList.naver?blogId=na03266&from=postList&categoryNo=75|
| 2023.07.24 - 2023.08.04  | 파이썬, 딥러닝, JAVA Framework| 파이썬 딥러닝 실습과 Java기초, Java Framework(Maven) 현장 실무<br>https://www.kopo.ac.kr/jinju/content.do?menu=12979|
| 2023.07.10 - 2023.07.21  | <img src="./img/unity.png">Unity(유니티) & Blender(블렌더) | Unity(유니티) & Blender(블렌더)를 활용한 게임 콘텐츠 제작 <br>https://www.kopo.ac.kr/jinju/board.do?menu=14508&mode=view&post=696877|
| 2023.04 - 2023.11 | <img src="."> NEAR | 청각장애인을 위한 AR글래스 <br> `프로보노`에서 진행하는 ICT멘토링 공모전으로 ICT기업전문가와 대학생(멘티)가 팀을 이루어 수행하는 프로젝트   <br> **참가 주제** : [NEAR](#ios-) <br> https://www.hanium.or.kr/portal/index.do |
| 2023.02.   | 한국산업인력공단 | 정보처리기사 필기 합격 <br>|
| 2023.03   | 진주폴리텍 대학 AI소프트웨어과 | 웹 & 앱개발(Front-End), 서버/제어(Back-End), 빅데이터 관리, 딥러닝/인공지능 모델 학습, 기업 융합 프로젝트 <br>https://www.kopo.ac.kr/jinju/content.do?menu=12979|


<br><br><br>

# **프로젝트 요약**

## AI Software 요약
| 기간 | 프로젝트 명 | 내용     |
|:----|:---------|:--------|
| 2023.08.27 - 2023.10.07 | **[NBE 모니터링 시스템](#ios-옛다)**  <br> *외주* | 485포트로 전송받는 값을 파싱해서 모니터링이 가능한 정보로 보여주는 프로그램  <br> **PART** : 문서 및 API부분 (기여도 25%) <br> **LIST** : 전송 값 파싱 및 송수신, 회의록, 회고록 등의 문서  <br> **STACK** : `python`|
| 2023.09.01 - 2023.10.07 | **[JetsonNano And Ubuntu]()**  <br> *외주* | Jetson Nano를 처음 배우는 학생들을 위한 가이드북 제작  <br> **PART** : 문서, OS, 응용소프트웨어 (기여도 30%) <br> **LIST** : Ubuntu, Nvidia,  <br> **STACK** : `Ubuntu`,`한글`, `Python`|



<br><br><br>

## Web 요약
| 기간 | 프로젝트 명 | 내용     |
|:----|:---------|:--------|


## ICT멘토링 요약
| 기간 | 프로젝트 명 | 내용     |
|:----|:---------|:--------|
| 2023.07. - 2023.11  | [NEAR](#pm-) <br> *프로보노* | VR Glass를 이용한 청각장애인 <br> **PART** : 전체 문서 및 시나리오 관리 (기여도 20%)  <br> **LIST** : SW세부 설계서 <br> STACK : `DeepLearning`, `Python` |

<br>

# **프로젝트 상세**
## [Python] NBE 모니터링 시스템 상세
<img src="./img/NBE.png"  width="200">

> 485포트로 전송 받은 값을 파싱하여 Python GUI로 모니터링이 편하도록 하는 프로그램
- Source : https://github.com/NaHwangje/NSENG  


- 첫 외주 프로젝트 입니다. rs232포트로 먼저 수신값을 확인하고 발신값과 수신 값이 일치하는지 확인하는 코드를 작성한 후에 각 값을 파싱하여 변수에 담아주고 GUI에 연결해주는 프로그램입니다. 현재 UI 디자인 작업이 진행중입니다. 

---
## [Linux] Jetson Nano And Ubuntu
<img src="./img/jetsonnano.png"  width="200">

> Jetson Nano를 처음 진입하는 사람들을 위한 교재 제작

- NVIDIA에서 제작한 싱글보드컴퓨터(Single Board Computer) 젯슨나노(Jetson Nano)를 기반으로 데이터수집, 모델학습, 영상인식, 자율주행 등 인공지능 교육학습에 필요한 다양한 요소기술을 실험 실습하기 위한 장치, 최초 진입장벽이 높아 더 쉽게 접근 할 수 있는 교육 자료 제작

---






## [Python] NEAR
<img src="./img/near.png"  width="200">

> 홀로렌즈(VR글래스)를 이용해서 청각 장애우들이 시간, 장소에 구애받지 않고 어디에서든 편의기능을 제공하기 위한 프로그램

- 청각장애인은 소통, 교육적인 측면과 업무 관련된 문제에서 어려움을 겪고 있는데, AR글래스 NEAR을 통해 시간, 장소에 구애받지 않고 언제 어디서든 사용할 수 있는 편의를 제공하고자 기획한 프로젝트, 추가하려 했던 부가기능이 너무 많았기 때문에, 조금씩 기능을 추가하면서 업데이트를 목적으로 기본기능 제작에 중심을 두고 추가 유지보수를 계획했었음.

---

