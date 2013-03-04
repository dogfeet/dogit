Git 사용자를 위한 커뮤니티 인덱스 페이지.

이 프로젝트 이름은 `두깃`으로 읽는다.

한글로 번역된 자료가 있으면 영문 링크는 생략하고 한글 링크만 달았다.

## 읽을거리

Git과 관련된 읽을거리를 모았다.

### 책, 가이드

* [git-scm](http://git-scm.com/) - git 홈페이지
* [progit][] - 필독서.
* [A Visual Git Reference](http://marklodato.github.com/visual-git-guide/index-ko.html) - git의 핵심 용어를 이해하는데 매우 유용함.
* [Git In The Trenches](http://cbx33.github.com/gitt/) - git을 가르치는 사람을 위해 만들어진 문서.
* [Git Magic](http://www-cs-students.stanford.edu/~blynn/gitmagic/?utm_source=twitterfeed&utm_medium=twitter)
* [Git - 간편 가이드](http://rogerdudler.github.com/git-guide/index.ko.html)
* [Egit User Guide](http://wiki.eclipse.org/EGit/User_Guide)
* [Git For Designers](http://hoth.entp.com/output/git_for_designers.html) - designer를 위해서 나름 쉽게 정리됨.
* [Just Do Git](http://keedi.pe.kr/presentations/just_do_git/) by [Keedi Kim](http://keedi.pe.kr). SCM으로서 Git을 쓸 때의 여러가지 내용을 재미있게 담고 있으며 Git-flow에 대해서 소개하는 자료입니다.
* [teach.github.com](http://teach.github.com/) - GitHub에서 배포하는 교육자료로 굉장히 훌륭하다.
* [http://atlassian.com/git/](http://atlassian.com/git/) - atlassian의 Git Tutorials & Training
* [Git 브랜치 배우기](http://pcottle.github.com/learnGitBranching/?NODEMO&locale=ko&command=levels) - Git 브랜치 배우기. 매우 훌륭. [@urigit][]에서 번역함.

### conf

* [eclipseConf의 Git 자료](http://wiki.eclipse.org/EGit/Training) - eclipse에서 git을 사용할 때 필독.
* [@chacon][]님의 [Getting Git](http://www.slideshare.net/chacon/getting-git)
* [@chacon][]님의 [Git 101](http://www.slideshare.net/chacon/git-101-presentation)
* [Advanced Git](http://www.slideshare.net/ajaxiankr/2011-kth-h3-track-b-4-advanced-git-by-aj) - [@andrwj][]님의 h3 2011 발표자료
* [WordCamp San Francisco 2011: Version Control for Designers](http://www.slideshare.net/chexee/wordcamp-san-francisco-2011-version-control-for-designers) 워드프레스 컨퍼런스에서 [Chelsea Otakan](http://twitter.com/chexee)이 발표한 자료인데 브랜치 관리를 나무에 비유한 것이 인상적입니다.
 * 마지막에 소개된 앱 중에 [KaleidoScope](http://www.kaleidoscopeapp.com) 인상적입니다.
* [@holman][]님의 [How GitHub Works](http://zachholman.com/posts/how-github-works/)
* [@holman][]님의 [How GitHub Uses GitHub to Build GitHub](http://zachholman.com/talk/how-github-uses-github-to-build-github)
* [@holman][]님의 [Git and GitHub Secrets](http://zachholman.com/talk/git-github-secrets)

### 브랜치 사용법(Workflow)

git은 브랜치 사용법이 매우 중요하므로 브랜치 사용법과 관련된 자료를 따로 모았다.

* [Git: branch-a-v](http://dogfeet.github.com/articles/2012/git-branch-a-v.html) - `git branch -a -v` 명령을 설명함
* [Git: Remote Tracking Branch vs Tracking Branch](http://dogfeet.github.com/articles/2012/git-tracking-vs-remote-tracking.html) - Remote Tracking Branch와 Tracking Branch가 무엇이 다른지 설명함 
* [git-flow](http://dogfeet.github.com/articles/2011/git-flow.html) - [@nvie][]님이 정리한 Workflow. 배포가 개념이 있는 패키지를 개발할 때 참고 하면 좋다.
* [github-flow](http://dogfeet.github.com/articles/2011/github-flow.html) - github에서 사용하는 Workflow. 배포가 없는 웹을 개발할 때 참고하면 좋다.
* [Git: 번역 Workflow](http://dogfeet.github.com/articles/2012/git-translate-flow.html) - progit을 번역할 때 사용한 Workflow.
* [Git: Rebase는 언제 어떻게 해야 할까?](http://dogfeet.github.com/articles/2012/git-merge-rebase.html) - Rebase는 언제 어떻게 해야 하는지 정리
* [Git: merge](http://dogfeet.github.com/articles/2011/git-merge.html) - Merge하는 방법을 정리

### 나머지 git 사용법

* [Git: git-svn](http://dogfeet.github.com/articles/2012/git-svn.html) - SVN 서버, Git 클라이언트로 사용하는 방법을 정리
* [GitHub로 남의 프로젝트에 감 놓고 배 놓기](http://dogfeet.github.com/articles/2012/how-to-github.html) - Github 사용법
* [Git: conflict](http://dogfeet.github.com/articles/2012/git-conflict.html) - Confict가 났을 때 필요한 명령어를 정리
* [Git: diff](http://dogfeet.github.com/articles/2011/git-diff.html) - diff 명령어 사용법을 정리
* [Git: refs](http://dogfeet.github.com/articles/2011/git-merge.html) - git의 Refs를 정리. progit 6장에 나오는 refs를 정리한 것임
* [diff::Unified format](http://dogfeet.github.com/articles/2011/1316924580.html) - git이 사용하는 diff 포멧인 unified 포멧을 정리함. 
* [Git: 델타와 스냅샷](http://dogfeet.github.com/articles/2012/git-delta.html) - 델타와 스냅샷을 관점에서 git을 설명함.

### @semtlnori님 git 연재.

* [3-way merge 알고리즘에 대해](http://npcode.com/blog/archives/708) - [@semtlnori][]님
* [git의 revision에 대해](http://npcode.com/blog/archives/655) - [@semtlnori][]님
* [git에서 특정 파일만 남기기 (git 기반 위키에서 특정 파일만 공개하기)](http://npcode.com/blog/archives/608) - [@semtlnori][]님
* [Git의 blob은 어떻게 발음하는가.](http://npcode.com/blog/archives/601) - [@semtlnori][]님
* [디스크 공간 절약을 위해 파일을 Git 저장소에 보관하기](http://npcode.com/blog/archives/591) - [@semtlnori][]님
* [git bisect 응용 – 줄바꿈 문자 잘못 넣은 사람 찾기](http://npcode.com/blog/archives/582) - [@semtlnori][]님
* [git으로 특정 기능이 언제 도입되었는지 찾기](http://npcode.com/blog/archives/463) - [@semtlnori][]님
* [깔끔하게 커밋하기](http://npcode.com/blog/archives/449) - [@semtlnori][]님
* [git pull 할 때 인자 안줘도 알아서 되게 하기](http://npcode.com/blog/archives/391) - [@semtlnori][]님
* [Git의 Staging Area는 어떤 점이 유용한가](http://npcode.com/blog/archives/736) - [@semtlnori][]님

### 뒷이야기

* [새로운 시장을 창조한 스타트업 GitHub의 비하인드 스토리](http://allaboutetp.wordpress.com/2012/03/18/github/)
* [Git에 대한 Linus Torvalds의 연설](http://www.youtube.com/watch?v=4XpnKHJAok8)

## SSH

### Set Up Git

githup:help에 있는 [Set Up Git](https://help.github.com/articles/set-up-git). Windows, Mac, Linux 환경에서 사용하는 설정 방법이 잘 설명돼 있다.

### keychain

터미널에서 ssh-agent를 사용할 때 유용하다. ssh-agent를 직접 사용하는 것보다 keychain를 사용하는 것이 더 편리하다. 사용방법은 [keychain for ssh login](http://dogfeet.github.com/articles/2011/1320111077.html)에서 설명한다.

keychain이 없다면 1.7.10 부터 지원하는 [패스워드 캐싱](https://help.github.com/articles/set-up-git#platform-linux) 기능을 사용하는 것도 괜찮다. 

## CLI

CLI 사용 시 유용한 자료.

### dotfiles

무려 [github][]에서 관리하는 프로젝트로 [dotfiles][]에 가면 자세한 설명이 나와 있다. git뿐만 아니라 다양한 앱에서 사용하는 dotfile이 정리돼 있다.

### bash-it

[bash-it][]은 bash 환경에서 유용한 프레임워크다. git, git-flow 명령어 자동완성, 프롬프트 테마 등 bash 환경에서 필요한 스크립트들이 모두 들어 있다. 다음은 bash-it의 zork 테마를 적용한 프롬프트 화면이다:

![bash-it-zork](https://raw.github.com/dogfeet/dogit/master/img/bash-it-zork.png)

프로젝트를 포크해서 github에 올려놓으면 여러 서버에서 같은 환경으로 작업할 수 있다. bash-it을 포크 해두고 linux, mac 환경에서 동일한 bash 프롬프트와 개발환경을 설정해 사용할 수 있다. bash-it은 확장하기 쉬운 구조로 돼 있기 때문에 나에게 필요한 bash 스크립트를 github 저장소에 등록해두고 사용하기도 좋다.

### oh-my-zsh

[bash-it][]과 마찬가지로 zsh에서 유용한 프레임워크다. [bash-it][]은 이 [oh-my-zsh][]을 보고 따라 만든 것이다. [bash-it][]과 마찬가지로 git, git-flow 명령어 자동완성, 프롬프트 테마 등 zsh 환경에서 필요한 것이 들어 있을 것이다.

### prezto

zsh 프레임워크로 [oh-my-zsh][]보다 관리가 잘되고 있는 것 같다. 나는 [bash-it][]을 사용하다가 [oh-my-zsh][]로 변경했다가 [prezto][]를 발견해서 [prezto][]로 바꿨다.

### msysgit

Window 사용자라면 [msysgit][]을 사용하고 있을 텐데 [@gypark][]님의 [Git](http://gypark.pe.kr/wiki/Git)을 반드시 읽어봐야 한다. msysgit 사용자가 고생하는 한글 문제, 멍청한 cmd 터미널 문제 등을 고민하고 실험하고 정리하였다. 그리고 그것을 공유해 주었다. 그 외 difftool 설정하고 고르는 방법 등 msysgit을 사용하려면 이 글이 꼭 필요하다.

### hg-git

![hg-git](http://hg-git.github.com/images/server.png)

http://hg-git.github.com/ - mercurial to git bridge

### git config

기타설정.

```sh
git config --global user.email "me@here.com"
git config --global user.name "Billy Everyteen"
git config --global color.ui 1
```

### git alias

`git alias` 명령으로 간단한 단축 명령을 만들 수 있다. 다음과 같이 등록해서 쓰면 편리하다:

```sh
git config --global alias.st status
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.br branch
git config --global alias.unstage 'reset HEAD --'
git config --global alias.cs "commit -s"
git config --global alias.amend "commit --amend -C HEAD"
git config --global alias.undo "reset --soft HEAD^"
git config --global alias.count "shortlog -sn"
git config --global alias.credit '!f() { git commit --amend --author "$0 <$1>" -C HEAD; }; f'
```

* `git credit "Changwoo Park" pismute@gmail.com` - 최근 커밋의 author 수정
* `git count` - 커미터 통계
* `git undo` - 이전 커밋으로 돌리고 staged 상태로 만든다.
* `git amend` - 최근 커밋을 수정. 커밋 메시지는 수정할 수 없다. 커밋 메시지를 수정하려면 `git undo;git commit`이나 `git commit --amend`

### git log

다음과 같이 등록하면 커밋 로그 하나가 한 줄로 나온다:

```sh
git config --global alias.lg "log --name-status \
  --color --abbrev-commit --date=relative --graph \
  --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset \
    %s %Cgreen(%cr) %C(bold blue)<%an>%Creset'"
```

`git lg`라고 실행하면 다음과 같이 나타난다:

![alias.lg](https://raw.github.com/dogfeet/dogit/master/img/git-lg.png)

보면 알겠지만, 매우 보기 편하다. 커밋하나가 한 줄로 나올 뿐만 아니라 각 브랜치가 가리키는 커밋도 함께 표시된다. 그리고 그 커밋에서 어떤 파일을 수정했는지도 보여준다.

`lg`로도 읽을 수 없는 히스토리라면 gitx같은 GUI 도구를 사용하는 것이 좋다.

### git mergetool, git difftool

* [본격 diff 툴 비교 리뷰 - Beyond Compare의 승!](http://ljh131.tistory.com/143)
* [Git: mergetool, difftool](http://dogfeet.github.com/articles/2011/git-mergediff.html) - `git mergetool`, `git difftool` 사용법

## GUI

유용한 GUI 도구들

* [git-scm.com의 GUI clients](http://git-scm.com/downloads/guis)
* [egit](http://www.eclipse.org/egit/) - for eclipse
* [github:mobile](http://mobile.github.com/) - for iphone, android

## 기타 프로젝트

### gitignore

이 [gitignore](https://github.com/github/gitignore) 프로젝트는 `.gitignore` 파일에 대한 템플릿 프로젝트다. 무려 [@github][]에서 관리하고 로컬에 Clone 해두면 매우 편리하다. 각 OS, 에디터, 개발도구, 언어에 따라서 다양한 `.gitignore` 파일 템플릿이 담겨 있다.

자세한 것은 [gitignore 방법에 대한 글](http://dogfeet.github.com/articles/2012/git-global-ignore.html)을 살펴보기 바란다.

### git-tles

[git-tles](https://github.com/dogfeet/git-tles)는 [@pismute][]님이 만들어서 사용하는 프로젝트 간단한 스크립트로 해당 저장소에 대해서 `git fetch`를 하고 Fastforward-Merge가 가능한 브랜치가 있으면 Merge하는 [git ff](http://dogfeet.github.com/articles/2012/git-ff.html) 명령과 브랜치 정보를 요약해서 보여주는 [git todo](http://dogfeet.github.com/articles/2012/git-todo.html) 명령이 들어 있다.

[git ff](http://dogfeet.github.com/articles/2012/git-ff.html)는 간단히 fetch할 때 Fast-forward될 수 있는 브랜치는 그냥 자동으로 Merge한다. Merge나 Rebase가 필요하면 수동으로 할 수 있도록 알려준다.

[git todo](http://dogfeet.github.com/articles/2012/git-todo.html)는 브랜치 정보를 요약해주는 도구로 로컬 브랜치와 원격 브랜치를 나눠서 볼 수 있다.

### git-extras

[git-extras](https://github.com/visionmedia/git-extras)는 [@visionmedia][]님의 git 확장 프로젝트다. 구현된 게 매우 많고 가끔 이런 게 있으면 좋을 텐데라고 생각날 만한 것이 들어 있다. 어떤 것이 있는지 한번은 살펴보길 바란다.

## 참여

추가하거나 수정할 게 있으면 Pull Request를 보내주거나 저장소에 이슈를 남겨주세요.

[progit]: http://dogfeet.github.com/articles/2012/progit.html
[dotfiles]: http://dotfiles.github.com
[github]: https://github.com/
[bash-it]: https://github.com/revans/bash-it
[oh-my-zsh]: https://github.com/robbyrussell/oh-my-zsh
[msysgit]: http://code.google.com/p/msysgit/
[prezto]: https://github.com/sorin-ionescu/prezto

[@gypark]: https://twitter.com/gypark
[@github]: https://twitter.com/github
[@pismute]: https://twitter.com/pismute
[@visionmedia]: https://twitter.com/visionmedia
[@nvie]: https://twitter.com/nvie
[@holman]: https://twitter.com/holman
[@chacon]: https://twitter.com/chacon
[@andrwj]: https://twitter.com/andrwj
[@semtlnori]: https://twitter.com/semtlnori
[@urigit]: https://github.com/urigit


