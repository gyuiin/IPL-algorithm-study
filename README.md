# 📖 IPL 알고리즘 스터디

`순천향대학교 영상처리 연구실` 코딩테스트 대비 목적 알고리즘 스터디입니다.


## 💡 목표
- AI 시대에 개발자로 살아남기
- 생각한대로 코드로 구현하는 능력 향상
- 코딩테스트 대비
- 어려운 문제라도 시도해보는 것
- 여러 알고리즘 습득
- 특정 알고리즘 유형 이해


## 🚥 규칙

### 1. 참여 방법

> fork 작업은 현재 IPL 알고리즘 스터디 repository를 자신의 계정으로 복사하는 것 입니다.
> 
> fork 한 repository 는 깃허브에 존재하기에 본인이 직접 작업하는 것이 불가능합니다.
> 
> clone 작업으로 자신의 컴퓨터로 깃허브의 repository를 본인 컴퓨터로 복사합니다.
>
> 본인 컴퓨터에서 작업 후 commit 작업을 통해 깃허브의 repository로 기록합니다.


1. 현재 IPL 알고리즘 스터디 repository fork
2. fork 한 repository 본인 컴퓨터로 clone
3. 본인 디렉토리 생성
4. 알고리즘 문제 해결 후 PR

### 2. 진행 방식

- 백준을 우선적으로 이용할 예정입니다.
- 풀이 언어는 Java로 통일합니다.
- 매 주 금요일 세미나 때마다 다같이 풀 문제 2개가 제시됩니다. 세미나 이후 다음주 목요일까지 풀어서 PR
- 문제가 제시되기 전 알고리즘 유형 설명이 먼저 진행됩니다.
  - 누적 합, 이분 탐색, 투 포인터, BFS 등 여러 알고리즘 유형 중 하나를 선택하여 해당 알고리즘을 설명합니다.
  - 알고리즘 설명 후 해당 알고리즘과 관련된 문제 2개를 제시합니다.
  - 알고리즘 설명은 멤버 별 돌아가면서 진행합니다.
  - 문제는 쉬운 난이도 1, 심화 난이도 1 를 제시합니다.
    - ex) (`백준 브론즈 문제 1`, `백준 실버 문제 1`) or (`백준 실버 문제 1`, `백준 골드 문제 1`)
- 해결하지 못한 경우 
  - 문제가 이해되지 않아 손도 못 댄 경우
    - 풀이를 보고 **반드시** 이해한 후 다시 풀어보고 놓쳤던 부분에 대해 주석으로 의견을 작성한 후 코드를 제출합니다.
  - 맞왜틀 (맞게 푼 거 같은데 왜 틀림?)
    - 더 해보고 도저히 모르겠다면 풀이를 보고 맞왜틀 코드와 풀이 코드를 함께, 놓쳤던 부분에 대해 주석으로 의견을 작성한 후 코드를 제출합니다.


### 3. 디렉토리 및 파일 생성 규칙

- 디렉토리 명 : `본인 깃허브 이름`
- 파일 명 : `문제 번호.java`
- ex) `ParkHyunS00/1234.java`


### 4. 커밋 규칙

- 커밋 메시지 : `[문제번호 - {태그}] 문제이름`
- 태그
  - | 태그   | 의미  |
    | ------|----- |
    | solve | 해결  |
    | fail  | 미해결 |
- ex) `[1234 - solve] 문제이름`


### 5. PR 규칙

- PR 제목 : `본인 이름 / 풀이날짜`
  - ex) `박현수 / 2024.07.02`
- PR 설명 : 풀이 과정 (못 푼 문제 이해한 다른 코드도 포함)
