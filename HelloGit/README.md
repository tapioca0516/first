# 형상관리 | 버젼관리

* SCM Software Configuration Management
	* 프로젝트 전반에 대한 관리. 
	* vcs, source code build, pakaging, deploy까지 포함
	
* VCS Version Controll System
	* scm의 하위개념
	* versiong에 집중
	* subversion, git 프로그램 등을 사용
	
---

* git vcs에 해당하는 프로그램
* github 버젼관리중인 프로젝트를 웹상에서 공유

* repository : 버젼관리하는 단위
	* local repository : 사용자 컴퓨터에 있는 저장소 repoA
	* remote repository : github에 있는 저장소 repoA

* branch: 작업의 주체. 기본적으로 저장소내에 master branch에서 시작한다.
	* master
	* 특정기능을 추가하기 위한 브랜치
	* bug를 수정하긴 브랜치
* commit: 프로젝트에서 버젼을 생성하는 행위. 스냅샷

---
## 버젼 되돌리기
* reset: 특정버젼으로 돌아간다.
	* --hard: 특정버젼 이후 내역 모두 삭제
	* --mixed: 특정버젼 이후 내역은 uncommited chages에 보관
	* --soft: 특정버젼 이후 내역은 staging area에 보관
* revert: 특정버젼을 취소한 새로운 버젼을 생성.






