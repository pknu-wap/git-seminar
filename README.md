# git-seminar
19년 4월 1일에 WAP 신입 회원들을 대상으로 진행한 깃 세미나입니다.


## 개요
이 글을 읽기전, 아래의 사항에 대하여 참고하시고 이 글을 읽는 것을 진행하시기 바랍니다.
```
이 레포지토리는 git에 대한 전반적인 개요만을 설명합니다. 어디까지나 git의 사용이
개발자의 포지션에서 굉장히 중요하다는 것을 각인시키는 것에 초점을 두고 있습니다.
깃에 대한 보다 기술적인 사용법에 포커싱을 두고 있는 독자라면 검색 엔진을 통해 관련
레퍼런스들을 찾아보시거나 아래의 링크를 통해서 개략적인 git의 사용법을 이해하시기
바랍니다.
```

　

본 세미나는 git + GitHub + SourceTree의 조합을 통해 분산 버전 관리를 학습합니다.

　

　

　
## 목표
이번 깃 세미나를 통해서 목표로 하는 것은 다음과 같습니다:
- WAP 신입회원들의 개발에서 git 사용 필수화
- git 사용에 대한 일련의 프로세스의 이해
- git 및 github, sourcetree에 대한 기초적 이해
- 체계적인 커밋 컨벤션에 대한 이해
- README.md 작성에 대한 이해

　

　

　
## 진행 프로세스
1. GIT CMD 맛보기
2. GitHub 레포지토리 생성
3. gitignore 작성
4. SourceTree에서 오리진 레포지토리 클론
5. 간단한 작업 with README.md
6. 풀 - 커밋 - 푸쉬
7. 협업 해보기
8. 무조건 쓰게끔 강조하기

　

　

　
## GIT 협업 워크플로우
#### 생성 단계
1. github에 들어가서 적절한 Owner와 .gitignore를 결정하여 원격 repository를 생성한다.
2. SourceTree 상단의 Clone 버튼을 눌러서 원격 레포지토리에 대한 링크를 가져온다.
---
#### 작업 단계
1. SourceTree 상단의 Pull 버튼을 통해서 원격 저장소의 내용을 가져온다.
2. 작업을 한다.
3. 작업 사항들을 소스트리 내 파일상태 탭에서 모두 스테이지에 올리기 버튼을 클릭하여 스테이지에 등록한다.
4. 하단의 대화창에서 커밋 내용을 입력한다.( 커밋 내용은 꼭 알아볼 수 있도록 )
5. 변경 내용을 SourceTree 상단의 Push 버튼을 통해서 원격 저장소에 등록한다.
( 이후 1번부터 다시 반복)
---
#### 작업물에 문제가 발생했을 때
제가 보여드리지 못했던 현재의 상태를 과거의 상태로 되돌리고 싶을 때 관련된 자료입니다.
- revert : https://gangju.tistory.com/21
- reset : https://gangju.tistory.com/20
```
둘 차이는 https://gangju.tistory.com/21에 적혀있습니다.
```
#### 기타
- 병합 충돌 해결
- 체크아웃
```
상기 두 방법에 대해서는 여기에서 설명하기에는 입문용으로 적합하지 않다고 생각해서 제외했으므로
나중에 동아리 내부 프로젝트 시 필요할 때 관련 자료를 찾거나 동아리 선배 분들에게 물어봐주시면
되겠습니다
```

　

　

　


## 요약
- 학교 과제든 텀프로젝트든 로컬에서만 작업하지 말고 무조건 GIT을 사용해서 개발하는 습관을 가지자.
  즉, 개발자 버전의 일기장이라고 생각하자.
- 협업할 때는 나도 믿지 말고, 팀원도 믿지 말아야 한다. 그렇기 때문에 기록은 항상 꼼꼼히 남겨야 한다.
- 세미나 때는 까먹고 얘기하지 못했지만, 최대한 같은 파일들을 건드리는 것을 피하는 협업을 하자.
  즉, 서로의 개발 영역을 확실히 나누어 겹치지 않도록 하자.

　

## ForkTest by JoByeongcheol

　

## 레퍼런스
##### 필수
 - git 간편 안내서 : https://rogerdudler.github.io/git-guide/index.ko.html
 - git 커맨드 정리 : https://github.com/leeho203/practice/wiki/Git-Command-%EC%A0%95%EB%A6%AC
 - git ignore 작성 : https://www.lesstif.com/pages/viewpage.action?pageId=54952369
 - git 마크다운 : https://gist.github.com/ihoneymon/652be052a0727ad59601

　
##### 참고
 - git Attributes : https://git-scm.com/book/ko/v2/Git%EB%A7%9E%EC%B6%A4-Git-Attributes
