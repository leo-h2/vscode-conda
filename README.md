Visual studio code - conda 환경 연결
=========================

1. VSC (visual studio code) 설치   
 * 다운로드 링크 : <https://code.visualstudio.com/download>   

2. VSC와 anaconda 연동
 extension 선택 및 python, code runner(python:select intepreter) 설치   
 VSC 종료   
 ctrl + shift + p : python : select intepreter 선택 하면, conda 가상환경 list가 나오며 선택하면 됨   
 power shell로 로딩 되는 경우, ctrl + ` (terminal 들어가는 명령어) 선택후 powshell 에서 cmd로 변경   

Reference : 링크 : <https://mylogcenter.tistory.com/7>   


Anaconda 단축키
============
$ conda env list   
$ conda create -n [virtual env name] python = 3.6   
$ conda activate [virtual env name]   
$ conda remove -n [virtual env name] --all    


git 사용 단축키
==========
1. 초기 등록시   
$ git init : 초기화   
$ git add [stage 대상 파일]  or git add * or git add . (모든 파일 업데이트)   
$ git commit -m "first commit"   
$ git branch -M main   
$ git remote add origin [git url address]   
$ git push -u origin main   

2. 변경 파일을 갖고 오는 경우
$ git pull : git에 변경된 내용을 받아 들임     

3. 변경 파일을 반영 하는 경우
$ git add [stage 대상 파일]  or git add * or git add . (모든 파일 업데이트)       
$ git commit -m "first commit"      
$ git push -u origin main      



