# Github 스터디 시즌 1,2

### 개요  
- 목표: 블로그를 직접 만들면서 Github 사용법을 익혀보자!
- 대상: 한동대학교 재학생 및 졸업생
- 일시: 1월 13일(시즌1), 2월 10일(시즌2) 토요일 15시 ~ 18시

### 사전 준비 작업
- Git 설치: [Window](https://youtu.be/JKT9laOAPIs) | [Mac](https://youtu.be/nw0x0cvg-iM) | [Linux](https://youtu.be/S1BYwbkrojw)
- Editor 설치: [VS Code](https://code.visualstudio.com/) | [Atom](https://atom.io/) | [Sublime Text](https://www.sublimetext.com/) (택1)
- Node.js 설치: [Node.js](https://nodejs.org/ko/)
- Github 가입: [Github.com](https://github.com)

--- 

### 기본 개념
- Git: Git은 버전 관리 시스템(VCS)이다. 리누스 토발즈가 만든 프로그램. 이전에는 Subversion(SVN)이라는 버전 관리 시스템을 주로 사용했다. Git은 분산 버전 관리 시스템(DVCS)이다. [관련 문서](https://git-scm.com/book/ko/v2)
- Github: Git을 사용하여 관리되는 오픈소스를 호스팅하는 웹 서비스. 대부분의 오픈소스가 이 서비스에 등록되어 있다. 오픈소스 활동을 하는 개발자에게는 물론 오픈소스를 이용하는 개발자라면 반드시 알아야할 서비스. 마스코트는 옥토캣(Octocat).
- [Github Pages](https://pages.github.com/): Github에서 제공하는 웹 호스팅 서비스. 무료로 자신의 웹 사이트를 등록할 수 있다. [관련 강의](https://opentutorials.org/course/3084/18891)

### Git 사용법
- [GUI](https://git-scm.com/downloads/guis): [SourceTree](https://www.sourcetreeapp.com/), [Github Desktop](https://desktop.github.com/)
- CLI: Bash, Zsh, Powershell
  - Bash 기본 명령어
    - 디렉토리 이동: `cd`
    - 디렉토리 조회: `ls` 
  - Git 명령어
    - 초기화: `git init`
    - 추가하고: `git add /path/file`
    - 저지르고: `git commit -m "msg"`
    - 상태확인: `git status`
    - 기록확인: `git log`
    - 원격저장소 주소 확인: `git remote -v`
    - 원격저장소를 복제해서 로컬에 가져오기: `git clone https://username@hostname/project/repository.git`

### Github 사용법
- Repository(저장소) 만들기
- 명령어로 추가(add)하고 저지르고(commit) 밀어넣고(push)

### Github Pages로 블로그 만들기
- [github.io](https://opentutorials.org/course/3084/18891)
- 쉽게 하는 두가지 방법: [Hexo](https://hexo.io/ko/) | [Jekyll](https://jekyllrb-ko.github.io/)
- 프레임워크로 간지나게 방법: [React](https://reactjs.org/) | [Vue](https://kr.vuejs.org/v2/guide/index.html) | [Angular](https://angularjs.org/)
- 제일 많이 배우는 방법: DIY (HTML, CSS, JS)

### Hexo
- [공식 홈페이지](https://hexo.io/ko/)
- [참고](https://www.holaxprogramming.com/2017/04/16/github-page-and-hexo/)
- 명령어
  - 서버 띄우기: `hexo s`
  - .md -> .html 변환하기: `hexo g`
  - 배포하기: `hexo d`


### 시간이 남으면...
- 도메인 등록하기: [참고](https://www.holaxprogramming.com/2017/05/15/github-page-and-custom-domain/)
- Github으로 오픈소스 활동하기: [DjangoGirls 사례](https://github.com/DjangoGirls/tutorial/pull/1036)
- Github Organizations: [MARPPLE](https://github.com/marpple), [Facebook](https://github.com/facebook), [Jieum](https://github.com/jieumjigi)