# 📝Git Bash 명령어 정리

<br/><br/>

## 디렉토리(폴더) 관리 명령어

- **`pwd`**(print working directoty) : 현재 디렉토리 출력

- **`cd`**(change directory) : 디렉토리 이동

- **`ls`**(list) : 목록

- **`mkdir`**(make directory) : 디렉토리 생성

- **`touch`** : 파일의 날짜와 시간을 수정(0바이트 빈파일 생성)

- **`rm`** : 파일 삭제 / **`rm -r `** : 폴더 삭제

  > . : 현재 디렉토리, .. : 상위 디렉토리

<br/><br/>

## 기본 명령어

![image-20220706232045741](C:\Users\diehd\AppData\Roaming\Typora\typora-user-images\image-20220706232045741.png)

- **`$ git init`**
  - 특정 폴더에 git 저장소(repository)를 생성
  - .git 폴더가 생성되며, git bash에서는 (master)라는 표기를 확인 가능

- **`$ git add <file>`**
  - working directory 상의 변경 내용을 staging area에 추가
- **`$ git commit -m '<커밋메세지>'`**
  - staged 상태의 파일을 커밋을 통해 버전으로 기록
  - 커밋 메세지는 변경 사항을 나타낼 수 있도록 명확하게 작성 필요

- **`$ git log`**
  - 현재 저장소에 기록된 커밋을 조회
- **`$ git status`** 
  - Git 저장소에 있는 파일의 상태를 확인

<br/><br/>

## 설정 명령어

- 사용자 정보(commit author)

  - `$ git config --global user.name` "username"

  - `$ git config --global user.email` "useremail"

    > Github에서 설정한 username과 email로 설정

- 설정 확인
  - `$ git config -l`
  - `$ git config --global -l`
  - `$ git config user.name`