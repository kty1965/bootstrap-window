# bootstrap-window
Bootstrap for window

## Winget Install
- [link](https://github.com/microsoft/winget-cli)
- [download](https://www.microsoft.com/ko-kr/p/app-installer/9nblggh4nns1?activetab=pivot:overviewtab)
- [regist preview](http://aka.ms/winget-InsiderProgram)

```bash
winget install 1Password
winget install aws-cli
winget install Bandizip
winget install Dropbox
winget install 1Password
winget install "Google Chrome"
winget install "Visual Studio Code"
winget install "Sublime Text"
winget install "TunnelBear"
winget install "Markdown Monster"
winget install vim
```

아직 확인 필요

```bash
winget install Git
winget install "GitHub Desktop"
winget install Ruby
winget install sbt
```

Game

```bash
winget install Battle.Net
```

## tfenv install

https://github.com/tfutils/tfenv

## Git eol Settings

Visual Studio Code 혹은 Editor 에서 eol 설정이 `crlf`(default windoe) `lf`(default mac, linux) `lf`로 셋팅 필요

```bash
 git config --global core.eol lf
 git config --global core.autocrlf false
 ```