# 🧮Git의 3가지 영역과 라이프 사이클

<br/>

## Git의 3가지 영역

<br/>![areas](git_lifecycle.assets/areas-16571537887631.png)

- Woring Directory : 파일의 변경 사항

  >  `$ git add` 명령어를 통하여 파일의 변경 사항을 staging area에 추가

- Staging Area : 버전으로 기록하기 위한 파일 사항 내용의 목록

  > `$ commit -m ` 명령어를 통하여 staging area에 있는 파일의 변경 사항을 데이터베이스에 저장

- Git directory : 커밋(버전)들이 기록되는 곳

<br/><br/>

## 파일의 라이프 사이클

<br/>

![lifecycle](git_lifecycle.assets/lifecycle.png)

- untracked :  git으로 관리하기 이전의 상태
- unmodified : 관리 대상으로 add 되었지만 아직 수정하지 않은 상태

- modified : 수정한 파일을 아직 로컬 저장소에 커밋하지 않은 상태

- staged : 현재 수정한 파일을 곧 커밋할 것이라고 표시한 상태 

- committed : 커밋되어 데이터가 로컬 저장소에 안전하게 저장된 상태

  > `$git status` 명령어로 디렉토리에 있는 파일의 상태를 확인할 수 있음

<br/><br/>

### **결론**

Git의 3가지 영역을 이해하고, 이러한 영역이 왜 존재하는지 알고 파일을 관리해야 한다.

각 영역은 사용처가 있으며, 순서에 따라 파일들이 이동하고 기록된다.(Life Cycle)

<br/><br/>

## 참고문서

[Git Documentation Book](https://git-scm.com/book/ko/v2)