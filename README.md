# study-test-spring
학습 테스트로 배우는 Spring 3기 진행 내용을 정리합니다.

<br />

## 학습에 대한 태도

### Next Edu 학습의 목적
미션을 기반으로 온라인 코드 리뷰 중심의 교육을 통해 프로그래밍 역량을 키움

### 학습 진행방법
배경지식 → 실습 및 학습 테스트 → 미션: 방탈출 예약 애플리케이션 → 코드 리뷰 → 피드백 강의

### 과정을 슬기롭게 임하는 방법
1. 주변 환경을 정리해 꾸준히 연습할 시간을 확보하기..!
2. 매일 1-2시간씩 미션 진행하기
    - 한번에 모두 구현하기 보다는 매일 일정한 시간 투자하는 것이 정말 중요함
    - 최소 하루에 2시간 이상 투자해야 미션을 완료할 수 있음
3. 상반되는 리뷰어의 피드백은 혼란스러워 하지말고 즐기기
4. 정답을 찾기 위해 집착하지 말고, 현 상황에서 최선을 찾으려 노력하기
5. 학습 과정에서 불편함을 느낀다면 제대로 미션을 하고 있는 신호 !!!

### 적절하게 공부하는 방법
1. 내가 적용하는 요구사항을 구체적으로 정리
2. 요구사항에 대한 기술을 적용하기
3. 기술 적용후 해당 기술에 대해 정확히 이해하기
    - 공식 문서는 반드시 읽되, 이해가 안된다면 블로그를 참고
  
### Commit 작성 방식
Title: [진행 프로젝트 이름] - [어떤 기능을 구현했는지 정리]

Body: 구현한 기능에 대한 내용 정리 ( 최대 2줄만 )

<br />

# 주차별 진행 사항
- 학습 테스트 구현시 따로 학습하고 싶은데 만들어지지 않았다면 만들어도 됨
- 어떤 에러가 발생했는지 그리고 어떻게 처리했는지 간단히 정리하기(2-3줄)
- 리팩터링시 AS_IS -> TO_BE를 간단히 정리할 것(2-3줄)
- 구현한 기술은 반드시 공식 문서를 읽고, 간단히 정리할 것(2-3줄)

### 0주차 - 준비하기
- 코드 리뷰를 위한 Slack 이름 설정
- Gradle 프로젝트 구축하기
- API Web Application 만들기
- Database 적용하기
  - Mac 적용 후 H2 Web 접근안되는 문제 있음 
- Git 사용법 준비 ... 사용법 확인 필요
  - [[10분 깃코톡] 와일더의 Git Commands (동영상)](https://www.youtube.com/watch?v=JsRD2AWxxFg)
  - [[10분 깃코톡] 웨지의 Git 브랜치 전략 (동영상)](https://www.youtube.com/watch?v=jeaf8OXYO1g)
  - [git - 간편 안내서](https://rogerdudler.github.io/git-guide/index.ko.html)
  - [git과 github (동영상)](https://www.inflearn.com/course/git-and-github#curriculum)

<br/>

### 1주차 - 학습 테스트 및 방탈출 예약 관리
  - 학습 테스트 구현
      - [MVC Response](https://github.com/OikimiO/study-test-spring/tree/main/1week/initial1)
      - [CRUD API](https://github.com/OikimiO/study-test-spring/tree/main/1week/initial2)
      - [JdbcTemplate](https://github.com/OikimiO/study-test-spring/tree/main/1week/initial4)
      - [Spring Bean](https://github.com/OikimiO/study-test-spring/tree/main/1week/initial5)
      - [Exception](https://github.com/OikimiO/study-test-spring/tree/main/1week/initial3)
  - 페이지 설정
  - 1단계: 예약 기능 구현
  - 2단계: 예외 처리 및 리팩터링
