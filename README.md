# **오픈소스소프트웨어**

### Introduction

-------------
### Week1-1 강의 개요 (강의계획서)
* **수업 설정 역량**
  * 컴퓨팅사고  
    _함수형 프로그래밍 언어 스타일을 익힘_
  * 융합  
    _LLM/ChatGPT를 새로운 프로그래밍을 배우는데 활용_
  * 글로컬  
    _Git/Github를 통해 협업하는 방식을 배움  
    영어 학습 자료를 공개함으로써 영어 활용 기회를 늘림_
  * 소프트웨어 응용 문제해결 능력
    - 오픈소스 소프트웨어 기본 개념과 도구
    - 새로운/낯선 소프트웨어 개발 환경 및 도구를 스스로 배우는 태도
    - 기초 함수형 프로그래밍 하스켈

* 수업방법 세부 기술
>  1. 미리 동영상 공부
>  2. 매 강의 10분 퀴즈 진행
>  3. 요약 강의
>  4. 연습문제 풀이 진행

-------------
### Week1-2 오픈소스소프트웨어 개요
>### 오픈소스 소프트웨어란?  
소프트웨어 저작권 소유자가 모든 사람에게 소스 코드를 게시, 사용, 복사, 수정 및 배포할 권리를 부여한 소프트웨어

-------------
### Week2-1 버전 관리 개요
* Version Control System  
Track your files over time so that **_you can easily get back_** to a previous working version

* ### General Actions in VCS:  
  * Checkin
  * Checkout and edit
  * Diffs
  * Branching
  * Merging
  * Conflicts
  * Tagging

-------------
### Week2-2 Git
![Git Flowchart](https://media.licdn.com/dms/image/v2/D5612AQFLbGka9LaM2Q/article-inline_image-shrink_1000_1488/article-inline_image-shrink_1000_1488/0/1710155247237?e=2147483647&v=beta&t=ZuM95LKWZqLraV6mJoMcXPgMfoSS2FHH18R_sEovkrg)
> _출처: https://www.linkedin.com/pulse/essential-git-commands-cheat-sheet-flow-chart--8awgc_

-------------
### Week2-3 Github, fork, pull request
* GitHub  
Git-based source code hosting for social coding

* Fork  
상대방 프로젝트를 복사해서 내 계정에서 관리되는 프로젝트로 새롭게 만들어  
포크한 프로젝트를 토대로 새로운 commit 내용들을 pull request 할 수 있음

* Pull request  
내가 포크해 관리하는 프로젝트의 변경사항을 원래 프로젝트에 반영 요청할 수 있음



[My Github](https://github.com/Silviron)

-------------
### Week3     Markdown
* ### Markdown
  A lightweight markup language for creating formatted text using a plain-text editor

### 예시 문법들
```Markdown
_이탤릭_
**볼드**
**_이탤릭과 볼드_**

# 헤더
## 다른 헤더
### 더 많은 헤더...

[인라인 링크](https://google.com)
[참조 링크][전남대]


![이미지](https://www.jnu.ac.kr/images/common/logo.png)
![참조 링크 이미지][고양이들]
[고양이들]: https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Katzis1.jpg/1280px-Katzis1.jpg

> 인용문

* 비순서 리스트
* 순서가 없음
  * 하위 리스트 만들수도 있음
    * 하위의 하위

1. 순서 리스트
2. 순서가 있음
   1. 이것도 하위 리스트 됨
   * 섞기도 가능

[전남대]: https://jnu.ac.kr
[고양이들]: https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Katzis1.jpg/1280px-Katzis1.jpg

```

위의 내용을 그대로 작성하면 마크다운에선 아래와 같이 보인다.

_이탤릭_
**볼드**
**_이탤릭과 볼드_**

# 헤더
## 다른 헤더
### 더 많은 헤더...

[인라인 링크](https://google.com)
[참조 링크][전남대]

![이미지](https://www.jnu.ac.kr/images/common/logo.png)
![참조 링크 이미지][고양이들]

> 인용문

* 비순서 리스트
* 순서가 없음
  * 하위 리스트 만들수도 있음
    * 하위의 하위

1. 순서 리스트
2. 순서가 있음
   1. 이것도 하위 리스트 됨
   * 섞기도 가능

[전남대]: https://jnu.ac.kr
[고양이들]: https://upload.wikimedia.org/wikipedia/commons/thumb/6/69/Katzis1.jpg/1280px-Katzis1.jpg