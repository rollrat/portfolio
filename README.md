# portpolio

## Experience

 - Inha University. Computer Science Engineering: 2017 ~ 2023
   - High Performance Computing Lab (~2019)
 - Software Maestro 9th (2018)
 - Military Service (Army) (2020.11 ~ 2022.03)

## Interests

### Highlight

 - Computer Science
 - Create a service that many users use
   - Startup, Startup Company Foundation
 - Meta Community System (Metaverse)
 - Micro Service Cloud Native Architecture
 - Cloud Architecture Optimizing (Price, Performance, Automation, Orchestration)
 - Realtime Bigdata Handling
 - High ~ Assembly Level Code Optimizing
 - Reading World Masterpiece Novels

### Keywords

`flutter`, `v8`, `node.js`, `c#`, `mysql`, `nosql(mongodb, redis)`, `fuzzing string search`, `image searching engine`, `code reverse tracing`,
`docker(kubernates)`, `low pricing architecturing`, `compiler`, `llvm`, `html/css/react`

## Web Sites

Naver Blog (2012 ~ currently): https://blog.naver.com/rollrat

### Articles

 - [LLVM 요약](https://blog.naver.com/rollrat/221198005924)
 - [이미지 유사도 분석기](https://blog.naver.com/rollrat/221942105385)
 - [웹 크롤링. 정적 웹 페이지 분석](https://blog.naver.com/rollrat/221717318880)
 - 웹 크롤링. 동적 웹 페이지 분석 
    - [Element Creation 루트 찾기](https://blog.naver.com/rollrat/221905945071)
    - [동적요소랑 연결된 데이터 찾기(설계)](https://blog.naver.com/rollrat/221906735915)
    - [동적요소랑 연결된 데이터 찾기(구현)](https://blog.naver.com/rollrat/221908229380)
 - JSon Parser 제작 [1](https://blog.naver.com/rollrat/221713831868), [2](https://blog.naver.com/rollrat/221714507357)
 - strlen 최적화 [1](https://blog.naver.com/rollrat/220547839447), [2](https://blog.naver.com/rollrat/221485261011)
 - [Bit 단위로 구현한 정수형](https://blog.naver.com/rollrat/220665429006)
 - 스도쿠
    - [스도쿠 Solver](https://blog.naver.com/rollrat/220466846958)
    - [빠른 스도쿠 Solver](https://blog.naver.com/rollrat/220467970924)
    - [스도쿠 생성기](https://blog.naver.com/rollrat/220468749712)
 - [Flutter에서 Python 실행하기](https://github.com/rollrat/run-python-on-flutter)

## Projects

### Business Projects

#### [2021] Mevy (Memoir)

 - 사용자 정보추적 일기장

#### [2021] Free Debate

 - 자유주제 토론 커뮤니티 기획

#### [2022] Candy

 - 리워드 기반 자유주제 토론 커뮤니티

#### [2022] Auction

 - 부동산 경매 정보제공 앱

### Toy Projects

#### [2019] Fault Injector based on LLVM (c++)

 - 바이너리에 소프트웨어 Fault를 주입할 수 있는 도구
 - Project Link: https://github.com/rollrat/llvm-fault-injector
 - Information: https://blog.naver.com/rollrat/221467365547

```
 * LLVM 소스코드 사용
 * 프로시저간 변수 의존성 검사, 함수 파라미터간 의존성 검사, 함수 반환값과 함수 인자간 의존성 검사, 브랜치 의존성 검사 Pass 구현
 * 컴파일된 후 프로그램의 Machine Instruction의 어떤 부분이 Fault Injection에 사용되는지 마킹함
```
 
#### [2020] Custom Crawler (c#)

 - 생산성있게 크롤러를 제작하기 위한 도구
 - Link: https://github.com/rollrat/custom-crawler
 - Concept: https://github.com/rollrat/custom-crawler/blob/master/CONCEPT.md

```
 * Cef 및 ChromeDevTools를 이용하여 구현
 * HTML XPath를 통한 정적 HTML 분석 도구 구현
   - LCA를 이용한 공통 노드 분석
   - Edit Dist를 이용한 노드 패턴 분석
 * HTML 동적 분석 도구 구현
   - Element 생성 루트 찾기 (https://blog.naver.com/rollrat/221905945071)
   - 동적 요소랑 연결된 요청 데이터 찾기 (https://blog.naver.com/rollrat/221908229380)
```

#### [2020] Community Explorer (Flutter)

 - 각종 커뮤니티를 구독하고 최신 게시글을 모아볼 수 있는 앱
 - Link: https://github.com/rollrat/community-explorer

#### [2021~] Community Engine (typescript, js)

 - 모바일 앱 내 구현에서 사용할 수 있는 확장가능한 커뮤니티 API 라이브러리
 - Link: https://github.com/rollrat/community-engine

#### [2019] Compiler Compiler (c#)

 - 컴파일러 컴파일러 (토커나이저, LALR파서) 구현
 - Link: https://github.com/rollrat/compiler-compiler

```
 * NFA to DFA, DFA Optimization, DFA Merge를 통한 Regex Matcher와 Scanner Generator 구현
   - lex와 비싯한 REGEX 및 BNF 형식의 텍스트 입력 방법 제공
   - 각 과정을 시각적으로 볼 수 있게 그래프를 Graphviz 코드로 변환하는 기능 구현
 * SLR LR(0), LR(1), LALR 기반 Parser Generator 구현
   - yacc와 비슷한 EBNF 형식의 텍스트 입력 방법 제공
 * 범용 Shift Reduce Parser 및 Attributed 기능 구현
```

#### [2015] Intercode Generator (c++)

 - JIT, 런타임에 수식을 입력받아 어셈블리어로 컴파일하고 메모리에 로드하여 실행할 수 있는 도구
 - Link1: https://github.com/rollrat/intercode-generator
 - Link2: https://github.com/rollrat/old-library/tree/master/src/other/Lately/rtc
 - Article: [효율적인 단문 명령처리를 위한 컴파일러형식의 구문분석 방법](https://blog.naver.com/rollrat/221722890631)

#### [2020] jsonhead (c++)

 - json 파일 파싱 및 구조 분석
 - Link: https://github.com/rollrat/jsonhead

```
 * LALR 파서를 이용하여 파싱
 * json 파일 구조 분석 후 C# 데이터 모델 클래스로 변환
```

#### [2022] ranked (c++)

 - expired zincrby를 지원하는 redis like sorted set
 - Link: https://github.com/rollrat/ranked

```
 * set, vector, priority_queue, timestamp 등을 이용하여 구현함
```

#### [2020] inha-alarmbot (c#)

 - 공지사항 알림 봇
 - Project Link: https://github.com/rollrat/inha-alarmbot
 - Information: https://blog.naver.com/rollrat/221852470704

```
 * Discord 및 Telegram 봇 사용
 * 효율적인 크롤러 관리를 위한 학과 웹사이트 단위별 테스트 코드 작성
```

#### [2017~2018] inhaTT (c#)

 - 시간표 작성 프로그램
 - Link1: https://github.com/rollrat/InhaTT
 - 수강신청 API (과목입력기능삭제)
 - Link2: https://github.com/rollrat/inha-sugang

```
 * Stack 두 개를 이용한 History 기능 구현
 * DFS를 이용한 시간표 자동 생성도구 구현
 * Everytime에 등록된 시간표를 자동으로 수강신청 장바구니에 등록
```

#### [2020] gallery explorer (c#)

 - 커뮤니티 게시글 및 댓글 전체를 저장하고 열람/검색할 수 있는 도구
 - Link: https://github.com/rollrat/gallery-explorer

```
 * 커뮤니티 웹 사이트 아카이빙 기능
 * 제목 및 내용 검색 기능 구현
   - Trie, Aho Corasick 트리를 이용한 실시간 병렬 검색/탐색 기능 구현 (https://github.com/rollrat/gallery-explorer/blob/master/Img/s5.gif)
   - 게시물 검색을 위한 Auto Complete 기능 구현 (일반 매칭 검색, 퍼지 매칭 검색)
 * Vp Tree 및 OpenCV 이미지 해싱 기능, 파일 Crc32, Cosine Distance를 이용한 이미지 유사도 분석기 기능 구현 (https://blog.naver.com/rollrat/221942105385)
```

#### [2019] Process packet filtering machine (c++)

 - Windows에서 특정 프로세스가 사용하는 포트를 검색할 수 있는 도구
 - Link: https://github.com/rollrat/process-packet-filter
 - Info: https://blog.naver.com/rollrat/221546185443

```
 * Windivert를 통한 TCP 패킷 하이재킹
 * 패킷 포트를 통한 프로세스 아이디 찾기 구현
 * 프로세스 아이디를 통한 프로세스 이름 찾기 구현
```

#### [2019] KakaoTalk-Analyzer (c#)

 - 카카오톡 채팅방의 메시지를 분석해주는 도구
 - Project Link: https://github.com/rollrat/KakaoTalk-Analyzer2
 - Information: https://blog.naver.com/rollrat/221627185108

```
 * TwitterKoreanProcessor의 형태소 분석기를 사용한 키워드 분석기 구현
 * 멤버 별 활동 기록 및 키워드 분석
 * 월별 키워드 순위 목록 제공
```

#### [2015~2017] Rollrat Renamer (VB.Net)
 
 - 파일 이름을 일괄 변경할 수 있는 도구
 - Project Link: https://github.com/rollrat/file-renamer
 - Information: https://blog.naver.com/rollrat/220565572162
 - Manual: https://github.com/rollrat/file-renamer/releases/download/manual/RollRat.Rename.Tool.Manual.1.7.2.pdf 

```
 * 문자, 기호, 숫자 세 가지 유형의 세그먼트를 통한 효율적인 파일이름 변경 방법 제공
 * 간단한 자체 문법을 이용한 파일 이름 변경 유연성 제공
```

---

### Library

#### [2016~2018] rollrat-framework (c++)
 
 - String, BigInteger, Polynomial 등을 구현한 라이브러리
 - Link1: https://github.com/rollrat/rollrat-framework-2
 - Link2: https://github.com/rollrat/wstring-master
 - Link3: https://github.com/rollrat/biginteger

#### [2020] download queue (c#)
 
 - 파일 병렬 다운로드 기능을 구현한 라이브러리
 - Project Link: https://github.com/rollrat/download-queue
 - Information: https://blog.naver.com/rollrat/221993368803

#### [2019] autocomplete (c#)

 - 자동완성 기능을 구현한 예제 프로젝트
 - Link: https://github.com/rollrat/AutoComplete
 - Information: https://blog.naver.com/rollrat/221617146618
