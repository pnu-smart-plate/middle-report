# 중간보고서 

## 윈도우 환경 latex 설치
$\LaTeX$ [설치 참고 자료](https://it4edu.tistory.com/183)

## 실행

터미널을 이용한다면 아래의 명령어를 통해 실행할 수 있다.
```Bash
mkdir out
lualatex -file-line-error -interaction=nonstopmode -synctex=1 -output-format=pdf -output-directory=out ./middle_report.tex
lualatex -file-line-error -interaction=nonstopmode -synctex=1 -output-format=pdf -output-directory=out ./middle_report.tex
```

**Intellij**를 이용한다면 해당 tex파일 실행을 통해 pdf생성을 할 수 있다.

