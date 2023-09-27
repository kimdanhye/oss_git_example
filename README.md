# **오픈소스SW개발론**

### Introduction

-------------
### Week1-1 강의 개요 (강의계획서)
* **오픈소스소프트웨어** 2023학년도 2학기 [강의계획서](https://rptbi.jnu.ac.kr/ReportApp/stdhak/reportView.aspx)
* 수업목표
  * 컴퓨팅사고
  * 융합
  * 글로컬
  * 소프트웨어 응용 문제해결능력
* 수업내용
  1. **오픈소스소프트웨어 개요** ([_유튜브강의_](https://www.youtube.com/playlist?list=PLhbaMvGyp99_NphAX7k5OqcM1fXLZne8t)_자료참고_)
  2. **GIT**
  3. **Haskell**
     * [Haskell MOOC][a Haskell learning site]
     * [Haskell MOOC lecture][another Haskell learning site]
    >
     [a Haskell learning site]: https://haskell.mooc.fi
     [another Haskell learning site]: https://www.youtube.com/playlist?list=PLhbaMvGyp99_NphAX7k5OqcM1fXLZne8t
  4. **시험**(_중간고사,기말고사_)
-------------
### Week1-2 오픈소스소프트웨어 개요
* ['Octoverse' at GitHub](https://octoverse.github.com/)
  _; **GitHub**에 대해서 알려주는 사이트_
* **"오픈소스소프트웨어란?"**
  > 소프트웨어 저작권 소유자가 모든 사람에게 소스코드를 게시, 사용, 복사, 수정 및 배포할 권리를 부여한 소프트웨어
  * Free Software (Richard Stallman)![Richard Stallman](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7b/Richard_Stallman_-_F%C3%AAte_de_l%27Humanit%C3%A9_2014_-_010.jpg/1024px-Richard_Stallman_-_F%C3%AAte_de_l%27Humanit%C3%A9_2014_-_010.jpg)
  * Open Source Software (Eric S.Raymond)![Eric S.Raymond](https://upload.wikimedia.org/wikipedia/commons/e/e2/Eric_S_Raymond_portrait.jpg)
* OSS License
  > 오픈소스 소프트웨어의 사용, 복제, 수정, 배포 권한의 범위를 지정

  > Examples
    * GPL
    * LGPL
    * MIT License
    * BSD License
    * Apache License
    * MPL (_Mozilla Public License_)

    ![Alt text](image.png)
-------------
### Week2-1 버전 관리 개요
* **Version Control System** (VCS)
  >  파일을 시간 경과에 따라 추적하여 이전 작업 버전으로 쉽게 돌아갈 수 있다.

  > VCS software
   * CVS (_Concurrent Version System_)
   * SVN (_Subversion_)
   * Mercurial
   * Darcs
   * Git
  > General Actions in VCS
    * Check in (check in a file and modify)
    * Check out and editing
    ![Alt text](image-1.png)
    * Diffs
   ![Alt text](image-2.png)
    * Branching
    * Merging
    ![Alt text](image-3.png)
    * Conflicts
    ![Alt text](image-5.png)
    * Tagging
    ![Alt text](image-4.png)

-------------
### Week2-2 Git
* Git workflow (_명령어알아두기_)

![Alt text](image-7.png)
![Alt text](image-8.png)

-------------
### Week2-3 Github, fork, pull request
* Git-based Source Code Hosting for Social Coding
  >
   (**Fork, Pull request**, Code review facilities)
  > **Fork** 하고싶은 것을 **Fork** 한 후 본인의 원격저장소(_예를들어 GitHub_)를 만들고 이를 로컬 저장소로 가져와 수정한 다음 다시 올리고 **Fork** 해왔던 계정에 **Pull request** 한다.


  [My Github Blog](https://github.com/kimdanhye)

-------------
### Week3     Markdown
* Markdown
  >
  : A lightweight markup language for creating formatted text using a plain-text editor
  > References
    * [Wiki](https://en.wikipedia.org/wiki/Markdown)
    * [Markdown tutorial](https://www.markdowntutorial.com/)
    * [Github tutorial](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
    * [GitHub Flavored markdown spec](https://github.github.com/gfm/)
* Examples
  * Italic(_  _ _), bold(**__ **), etc.
  * Headers (####)
  * Links 
  * Images
  * Blockquotes
  * Lists
  * Paragraphs 
