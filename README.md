# Introduction to Computer Systems

### Overview

+ `/exam/`
  + 지난 기출문제
+ `/lesson/`
  + 지난 학기 강의자료
+ `/homework/`
  - 지난 학기 과제
  - `CSAPP1e-solution-manual`
    - CSAPP 1판 공식 manual
    - 공식 manual이라고는 하지만 오답도 꽤 있음
  - `CSAPP-solution-Vincent-Lee`
    - 제가 작성한 CSAPP solution
    - 전반부는 CSAPP 2판 solution, 후반부는 CSAPP 3판 solution
      - 2016년에는 CSAPP 3판 인쇄가 늦어져서, 2016년 전반 학기는 CSAPP 2판으로, 후반 학기는 CSAPP 3판으로 수업 진행
    - 문의사항은 ihalbmond@gmail.com 로 연락 바람
+ `/labs/`
  + 랭킹 경쟁에 빠져서 당시 lab 절반 정도를 rank 1까지 올렸음
+ `/notes/`
  + 필기 노트
+ `/audio-lectures/`
  + 2016년 하반기 수업 녹음, 강의자료와 함께 들으면 좋음. 공유해주신 森聚(썬쥐)님께 감사드립니다.

### FAQ

Q: How to read my textbook?

A: In a nutshell, skim the book first, then pursue deeper comprehension.

Q: 교재는 어떻게 읽어야 하나요?

A: 교재보다는 강의자료의 모든 디테일을 이해하는 것이 더 중요합니다. 한마디로 말하면, 먼저 책 전체를 대충 훑어본 다음, 여러 번 반복하며 읽는 깊이를 더해가면 됩니다. 중국어판에는 속 답답한 오역이 꽤 있는데, 예를 들면 C언어의 'switch'가 '开关(스위치/전등 스위치)'로 번역되어 있기도 합니다. 영어 원서/원본 강의자료를 함께 보는 것을 추천합니다.

Q: 북경대(PKU) ICS 수업은 청강(投点)할 필요가 있나요?

A: 필요 없습니다. 본 수업: 한 교수님 수업으로 수강신청을 해두고 실제로는 다른 교수님 강의실에 가서 들어도 무방함; 토론 수업(discussion): 학생들이 소그룹에 랜덤 배정되므로 청강 신청이 필요 없음.

Q: How to log into the *server*?

A: connect through *SSH*: `linux> ssh –p xx22 student-id@ics9.pku.edu.cn`

Q: 서버에는 어떻게 로그인하나요?

A: SSH로 접속하세요: `linux> ssh –p xx22 student-id@ics9.pku.edu.cn`

### Making use of Official Resources

#### CMU course site

+ [Schedule](https://www.cs.cmu.edu/~213/schedule.html)
  + CMU 강의자료/영상 다운로드
+ [Exams](https://www.cs.cmu.edu/~213/exams.html)
  + CMU의 지난 기출문제, PKU보다 난이도가 낮음

#### Text Book

+ [Student Site](http://csapp.cs.cmu.edu/3e/students.html)
  + GDB Materials
    + Beej's [Quick Guide to GDB](http://beej.us/guide/bggdb/)
    + Two-page x86-64 GDB cheat sheet ([pdf](http://csapp.cs.cmu.edu/3e/docs/gdbnotes-x86-64.pdf), [txt](http://csapp.cs.cmu.edu/3e/docs/gdbnotes-x86-64.txt))
      + cheat sheet에 본 강의에서 필요한 gdb 명령어가 모두 포함되어 있음
  + [Unix FAQ](http://csapp.cs.cmu.edu/3e/unixfaq.html)
    + unix 명령어 / 시스템 콜 / C 표준 라이브러리 관련 궁금증은 구글 검색을 적극 활용하는 것을 추천, 명확하고 풍부한 자료를 쉽게 찾을 수 있음
  + [Code examples](http://csapp.cs.cmu.edu/3e/code.html)
    + quite useful resource for lab
    + lab을 진행할 때 특히 후반부 lab에서 code examples가 매우 유용함
  + [Labs for self-study students (without solutions)](http://csapp.cs.cmu.edu/3e/labs.html)
    + CMU의 lab을 미리 해볼 수 있으나, PKU lab의 요구사항과는 다소 차이가 있음. 다만 다루는 지식 포인트는 대체로 동일함
      + PKU의 lab은 x86-64 아키텍처 위주
      + [*Attack Lab*](http://csapp.cs.cmu.edu/im/labs/attacklab.tar)과 [*Buffer Lab (IA32)*](http://csapp.cs.cmu.edu/im/labs/buflab32.tar)의 내용은 기본적으로 동일하나, PKU는 x86-64 버전의 Attack Lab을 사용함
      + [*Performance Lab*](http://csapp.cs.cmu.edu/im/labs/perflab.tar)은 이미 [*Cache Lab*](http://csapp.cs.cmu.edu/im/labs/cachelab.tar)으로 대체됨
    + autolab의 랭킹은 1차적으로 score를 기준으로 하고, 그 다음으로 lab 완료 날짜를 기준으로 함

