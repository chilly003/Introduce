
---

## **ReadME**


| **이메일** | **GitHub** |
|------------|------------|
| chfhchf03@gmail.com | [GitHub Profile](https://github.com/chilly003/readme) |
<br />

## **소개 (Intro)**  
> **"함께하는 성장을 목표로 하는 신입 { } 개발자 정효원입니다."**
<br />


## **자기 소개 (About Me)**  

인사 관리 인턴으로 시작해 프로그램의 실용성을 깨닫고 HTML, CSS, JavaScript를 독학하며 웹 개발 기초를 다졌습니다. 현재 SSAFY에서 전문 소프트웨어 교육을 받고 있으며, 알고리즘과 AI 관련 기술, 웹 프레임워크를 집중적으로 학습 중 입니다.

저는 **사회적 가치를 최우선**으로 생각하며, 기술적 접근을 통해 **기업의 ESG 경영 목표에 기여하고자 합니다.** 특히 인터넷 소외 계층을 위한 웹 및 앱 기능을 개발하여 더 많은 사람들이 기술에 접근할 수 있도록 돕고 싶습니다. 이러한 노력을 통해 **개인의 성장뿐만 아니라 기업에 긍정적인 영향을 미치는 전문 개발자로 성장하고자 합니다.**

<br />

## **직무 및 이력 (Experiences)**  

### **이트너스 | 인사관리 인턴**  
📍 서울시 우면동 ∙ *2023.09 - 2023.12*  

- 임직원 복지(의료비, 학자금, 개인 연금 등) 데이터 관리  
- 엑셀 매크로를 활용해 의료비 검토 과정을 3단계에서 1단계로 축소  
- 학자금 지원 서류 가이드라인 수정 및 배포  
<br />


## **기술 스택 (Tech Stack)**  

### **Programming Languages**  
| Python 🟦🟦🟦🟦🟦 | JavaScript 🟦🟦🟦🟦⬜ | Java 🟦🟦🟦⬜⬜ |

### **Frameworks**  
| Django 🟦🟦🟦🟦⬜ | React 🟦🟦🟦🟦🟦 | Vue 🟦🟦🟦🟦🟦 |

### **Collaboration Tools**  
| Notion 🟦🟦🟦🟦🟦 | Figma 🟦🟦🟦🟦⬜ |

<br />

## Cinerium🌲

https://github.com/SSAFY-MZ-PJT/SSAFY_MZ_PJT?tab=readme-ov-file *(2024.10 ~ 2024.11)*

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f0c7d6eb-9495-4c07-92c8-cdeb0aab59d7/eed367dd-9331-4ca0-9501-6e2e82eacae6/b4600b8b-fac8-4f71-adfc-734d977f6101.png)

### **프로젝트 소개**

Cinerium은 영화 추천 사이트로 단순히 영화를 감상하는 것에서 그치지 않고 사용자의 내적 성장을 돕는 것을 목표로 합니다. 주요 특징은 아래와 같습니다.

| 맞춤형 영화 추천 | 사용자의 취향과 선호도를 분석하여 개인화된 영화 추천 서비스를 제공합니다. |
| --- | --- |
| 직관적인 UI/UX | 사용자 친화적인 인터페이스로 영화 정보에 쉽게 접근할 수 있습니다. |
| AI 토론 파트너 | 다양한 성격의 AI 캐릭터와 영화에 대해 토론할 수 있는 독특한 기능을 제공합니다. |

### **기여한 부분**

- **아이디어 기획**
- **Front**
    - Vue.js를 사용해 사용자에게 친숙한 웹사이트 구성
    - Bootstrap을 활용해 반응형 웹사이트 제작
    - 시행착오를 통해 재사용 가능한 component를 만들어 중복 코드를 방지
    - 계층 구조 효율성을 위해 Pinia 활용
- **생성형 AI 적용**
    - OpenAI API 호출
    - 초기화된 클라이언트에 프롬프트 설정
- **GitHub**
    - GitHub를 통해 프로젝트 관리 생성
    - git 충돌시 원인 및 해결 방법 탐색
- **프로젝트 일정관리 및 정보관리**
    - Notion을 통해 프로젝트의 일정 관리
    - 각 단계별로 구역을 나눠 필요한 부분을 찾게 편성



- **웹사이트 디자인**
    - Figma로 웹사이트의 디자인 제작



### ***문제 및 해결***

**문제 1)**

- 게시판에 게시글 삭제와 수정 기능 오류 발생
- Postmen으로 Django에서 받아오는 데이터의 형식을 보고 원인 파악
- Django에서 urls.py 파일 확인하니 `특정 영화에 대한 리뷰 조회` 주소와 `리뷰 상세 조회` 주소 값이 숫자 값으로 서로 같음을 확인
- Django 쪽에서는 서로 다른 곳에서 온 pk값을 구분하지만 Vue 쪽에서는 pk값 구분 하지 못함
- 서로 다른 주소의 path를 달리 설정 후 해결
- Django의 주소 흐름과 Vue의 주소 흐름이 다르다는 것을 체감

**문제 2)**

- 메인 페이지에 나오는 영화 카드와 리뷰 페이지에 나오는 영화 카드의 형식이 달라 웹페이지의 일관성 부족
- 메인 페이지, 리뷰 페이지, 상세 페이지에 사용되는 영화 카드가 중복 사용됨을 확인
- 영화 카드 컴포넌트를 생성
- 컴포넌트를 각각의 페이지에 적용해 코드 중복 사용 방지 및 유지 보수를 유연하게 수정
- 이 과정을 통해 중복되는 버튼, 입력 창 등 다양한 중복 코드를 컴포넌트로 만들면 유지 보수가 더 쉬워지겠다는 생각을 함

## 활동 (**Activity**)

## **스터디 활동**

### **1) 알고리즘 스터디**

- **활동 기간**: 2024년 8월 ~ 11월 (3개월)
- **목표**: 삼성 SW 역량 테스트 A 등급 취득
- **역할**: 팀장 (총 4명)
- **활동 내용**:
    - 주당 코딩 테스트 문제 3개를 선정하여 풀이 후, 모임 시간에 문제 해석 및 풀이 과정 공유
    - 팀원들이 모두 A 등급을 취득할 수 있도록 독려하며, 긍정적인 학습 분위기 조성
    - 결과적으로 팀원 전원이 A 등급 취득 성공
- **기억에 남는 에피소드**:
    
    SSAFY 알고리즘 강의와 연계된 문제를 선정해 풀면서 재귀 함수와 백트래킹의 중요성을 깊이 이해하게 되었습니다. 특히 백트래킹은 종료 조건을 논리적으로 설정해야 에러 없이 작동할 수 있음을 깨달았고, 이를 통해 완전 탐색과 탐욕 알고리즘을 효과적으로 활용하는 방법을 익혔습니다. 이러한 경험은 복잡한 문제를 체계적으로 해결하는 데 큰 도움이 되었습니다.
    

### **1) 리액트 스터디**

- **활동 기간**: 2024년 12월 (1개월)
- **목표**: 전문적인 리액트 사용자로 성장
- **역할**: 서기(총 6명)
- **활동 내용**:
    - 각자 리액트 강의를 듣고 강의에서 제공하는 미니 프로젝트를 진행
    - 모르는 점이나 궁금한 점은 채팅을 통해 공유하며 학습
- **기억에 남는 에피소드**:
    
    연습 프로젝트에서 **`useState`** 배열에 데이터를 추가하려 했으나 실패했던 경험이 있었습니다. 문제를 해결하기 위해 강의와 자료를 찾아보며 **`prevState`**를 사용하는 방법을 알게 되었고, 이를 통해 React 상태가 비동기적으로 업데이트된다는 점과 이전 상태를 기반으로 새 상태를 계산하는 원리를 이해했습니다. 이 경험은 React 상태 관리에 대한 깊은 이해로 이어졌습니다.
    

---

### **Solved Algorithm**

- **GitHub Repository**: [Solved Algorithm](https://github.com/chilly003/Solved_Algorithm) *(2024.8 ~ 현재)*
- **설명**:알고리즘 학습을 위해 백준, 프로그래머스, SWEA 등 다양한 출처의 알고리즘 문제를 풀이하고 정리한 프로젝트입니다. 현재까지 총 130문제 이상을 풀었으며, 특히 트리 구조와 BFS/DFS 알고리즘에 대한 깊은 이해를 가지고 있습니다.최근에는 자바(Java)를 추가로 학습하여 파이썬과 자바 두 언어로 문제를 해결하고 있으며, Notion을 활용해 각 문제의 풀이 절차와 알고리즘 개념을 체계적으로 정리하고 있습니다.

---

### **SSAFY 채용 박람회 탐방**

- 활동 기간: 2024년 12월 16일 ~ 18일
- **활동 개요**: SSAFY에서 진행된 채용 박람회에서 다양한 기업(우리은행, 현대오토에버, CAL 등)을 탐방하며 취업 시장 동향과 기술 스택 요구사항을 파악했습니다.
- **배운 점 및 느낀 점**:
    - 각 기업이 최근 프로젝트에서 사용하는 기술 스택(예: 스프링, 리액트, 코틀린, 스위프트, 생산형 AI 등)을 분석하며 앞으로의 학습 방향성을 설정했습니다.
    - 금융 IT 분야에서는 클라우드 기술과 AI 활용이 중요하다는 점을 인지하였고, 클라우드 학습 필요성을 깨달았습니다.
    - 기업들이 외부에 공개하는 개발 프로젝트 정보를 통해 기술 트렌드와 조직 문화에 대해 이해하게 되었습니다.
    - 단순히 기술 역량뿐만 아니라 조직에 융화되고 소통 능력을 갖춘 인재가 되어야 한다는 점을 다시 한번 깨닫는 계기가 되었습니다.

---

### **운동**

체력 이슈로 인해 다양한 운동을 취미로 하고 있습니다.

- 🧗 클라이밍
- 🕺 폴댄스
- 👟 런닝
- 🏃‍♂️ 헬스

<br />

## **교육 및 자격증 (Education & Certificates)**  

### **교육 (Education)**  
### **서울여자대학교 경영학 전공**

> *학점: 3.9 / 4.0
∙ 2024년 2월 졸업*
> 

### SSAFY(삼성 청년 소프트웨어 아카데미)

> *삼성의 SW 교육 경험과 고용노동부의 취업 지원 노하우를 바탕으로, 취업 준비생에게 SW 역량 향상 교육 및 다양한 취업지원 서비스를 제공하여 취업에 성공하도록 돕는 프로그램*
> 
> 
> *주관 : 삼성*
> 
> *후원 : 고용노동부*
> 
> *운영 : 멀티캠퍼스*
> 
> *∙ 2025년 6월 수료 예정*
>

### **자격증 (Certificates)**  
- Opic IM3 ∙ *2024년 3월 취득*  
- Toeic 800 ∙ *2024년 3월 취득*  
- 컴퓨터 활용 능력 2급 ∙ *2023년 9월 취득*  
- JLPT N2 ∙ *2022년 7월 취득*  
<br />


## **소셜 미디어 & 포트폴리오 (Social & Portfolio)**  

- **GitHub**: [chilly003](https://github.com/chilly003)  
- **Notion 포트폴리오**: [Notion Link](https://www.notion.so/15860a1ef6728071ae79c6b655775ebc?pvs=21)
<br />

## 별첨
아래는 요청하신 내용을 마크다운으로 깔끔하게 정리한 버전입니다. 각 기술 활용 수준 지표를 표 형식으로 구성하여 보기 쉽게 작성했습니다.

### **프로그래밍 언어**

| **수준**   | **정의**                                                                                     |
|------------|---------------------------------------------------------------------------------------------|
| **하**     | 프로그래밍 언어의 문법을 이해하고 있으나, 구체적인 개념과 기능에 대한 이해는 부족함            |
| **중하**   | 코드를 읽을 수 있으며, 책을 참고하여 약간의 수정 작업 또는 작은 변경사항 추가를 할 수 있다     |
| **중**     | 시스템 동작 방식을 알고 있으며, 기본적인 기능을 구현할 수 있다                                |
| **중상**   | 중간 규모 프로그램 및 시스템을 개발할 수 있으며, 주요 이슈 트러블슈팅을 할 수 있을 정도로 내부 구조에 대해 이해하고 있다 |
| **상**     | 대규모 프로그램 및 시스템을 난해한 부분에 대한 일부 참고(책/인터넷)를 통해 개발할 수 있다       |

---

### **Git**

| **수준**   | **정의**                                                                                     |
|------------|---------------------------------------------------------------------------------------------|
| **하**     | Git의 기본 개념을 이해하고 있으나, 구체적인 명령어 사용법에 대한 이해는 부족함                 |
| **중하**   | 기본적인 Git 명령어(add, commit, push, pull)를 사용할 수 있으며, 온라인 자료를 참고하여 간단한 브랜치 작업을 수행할 수 있음 |
| **중**     | Git의 주요 기능을 이해하고 있으며, 브랜치 생성, 병합, 리베이스 등의 작업을 수행할 수 있음. 기본적인 이슈 해결이 가능함 |
| **중상**   | Git의 고급 기능(cherry-pick, interactive rebase, stash 등)을 활용할 수 있으며, 복잡한 브랜치 전략을 구현하고 주요 충돌 문제를 해결할 수 있음 |
| **상**     | Git의 내부 동작 원리를 이해하고 있으며, 대규모 프로젝트에서 효율적인 워크플로우를 설계하고 구현할 수 있음. 복잡한 이슈를 해결하고 Git 훅을 활용한 자동화 작업을 수행할 수 있음 |

---

아래는 알고리즘 부분을 수정하여 깔끔하고 체계적으로 정리한 마크다운 형식입니다. 각 수준에 대한 정의를 명확히 구분하고, 가독성을 높였습니다.

---

### **알고리즘**

| **수준**   | **정의**                                                                                     |
|------------|---------------------------------------------------------------------------------------------|
| **IM**     | - 기본적인 알고리즘 개념을 이해하고 있음<br>- 간단한 반복문과 조건문을 사용하여 기초적인 문제를 해결할 수 있음<br>- 배열과 문자열 조작의 기본을 알고 있음<br>- 완전탐색 기법으로 문제를 해결할 수 있음 |
| **A**      | - 기본 자료구조(스택, 큐, 해시 테이블)를 이해하고 활용할 수 있음<br>- 정렬 알고리즘의 기본 개념을 알고 있으며 간단한 구현이 가능함<br>- 재귀 함수의 개념을 이해하고 기본적인 문제에 적용할 수 있음<br>- 기초적인 그래프 탐색 알고리즘(DFS, BFS)을 이해하고 적용할 수 있음 |
| **A+**     | - 동적 프로그래밍의 기본 개념을 이해하고 간단한 문제에 적용 가능함<br>- 이진 탐색, 투 포인터 등의 기법을 활용할 수 있음<br>- 복잡한 그래프 알고리즘(프림, 다익스트라)을 활용할 수 있음 |
| **B**      | - 고급 자료구조(세그먼트 트리, 트라이 등)를 이해하고 구현할 수 있음<br>- 동적 프로그래밍을 다른 여러 기법(비트마스킹 등)과 융합하여 적용할 수 있음<br>- 문제의 조건을 분석하고 요구되는 시간복잡도를 계산할 수 있음 |
| **C**      | - 주어진 문제에 따라 요구되는 자료구조, 알고리즘, 시간복잡도를 정확히 파악할 수 있으며<br>- 한정된 언어와 라이브러리만을 활용하여 필요한 자료구조와 알고리즘을 직접 구현 및 최적화 할 수 있음 |

---
