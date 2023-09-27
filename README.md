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

    ![Alt text](https://blogfiles.pstatic.net/MjAyMzA5MjdfNzAg/MDAxNjk1ODI2NzYxMzc5.BZyEvfu8t3g32ijfzxX6OC7hWjGlVtzMd3r4JjmkaTkg.u7Lnkr6TFj9reJWIhVbEUmjQOvFs0NG5IG2WooV_zOYg.PNG.hyedaning118/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-09-27_183104.png)
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
    ![Alt text](https://postfiles.pstatic.net/MjAyMzA5MjhfMiAg/MDAxNjk1ODI2ODIyNDc2.lospzi6mu7O8oo9TKrQSRMkZFTgsJZBENf_zTa5vCwIg.asuJ1nVWZ-GDf5TyqqLDxC3GGgd-LdVm3zUoj1alV90g.PNG.hyedaning118/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-09-27_184220.png?type=w966)
    * Diffs
   ![Alt text](https://postfiles.pstatic.net/MjAyMzA5MjhfMjIx/MDAxNjk1ODI2ODI5ODQx.FPGhnJ8PAbpx6rbiyqLi66nyxt4EgqGSFx18TotXP4wg.oWu657RcwxGXpCOiLSH4ScFcFjtcaxmWiMYqZFPj-6og.PNG.hyedaning118/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-09-27_184314.png?type=w966)
    * Branching
    * Merging
    ![Alt text](https://postfiles.pstatic.net/MjAyMzA5MjhfMjkz/MDAxNjk1ODI2ODM4NTE3.Ut1WzKM7LjrScZcpVO79M8mRcqJtZdNUIpKor6zJegYg.pTQIBZtZ8PQgSJN8cJ4rrq9-eBGTfKnITwGU4ZqeWtog.PNG.hyedaning118/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-09-27_184402.png?type=w966)
    * Conflicts
    ![Alt text](https://postfiles.pstatic.net/MjAyMzA5MjhfMjc5/MDAxNjk1ODI2ODQyNTk5.6EDnMO_2OF5FsJ_70dSuKzwTDme5DRWtNo5hUFPbXlsg.x_aSLHMQ3pdGb7bIFQfyIIp-S9c1sc5h4TS7xltHAvQg.PNG.hyedaning118/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-09-27_184611.png?type=w966)
    * Tagging
    ![Alt text](https://postfiles.pstatic.net/MjAyMzA5MjhfOTMg/MDAxNjk1ODI2ODQ2OTE3.-UUCDR_z8oD_gl9xZOCibTdtLZhpR50wsAPjKU_kb90g.bkeT470YeePqd6QGsRI0Zgu8al4DdAxkCDUjMxwsdaAg.PNG.hyedaning118/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-09-27_184627.png?type=w966)

-------------
### Week2-2 Git
* Git workflow (_명령어알아두기_)

![Alt text](https://postfiles.pstatic.net/MjAyMzA5MjhfMjIx/MDAxNjk1ODI2ODUxMDgx.amC3CVVWkQmxXRSYWa6JxedqOc-4h5JHgRiQlI8I80Mg.jQSk2VvIP0UM3EYA_qdYcnuaXYD2TblGbZ-JUkk7LaQg.PNG.hyedaning118/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2023-09-27_184749.png?type=w966)


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

