# public

git (vs. dropbox) 
- dropbox 크게 두가지로 이루어져있는데 dropbox client / dropbox.com server 
- dropbox client 와 git client 유사함 
- git 은 오픈소스위에서 만들어짐 
- git에서 만들어진 내용들을 git server에 저장하는 것 (여기서 가장 유명한 것이 github) 

Repository 
- 저장소 

git 기본기능 
- git init: 새로운 저장소 생성 
- git add: 파일을 추가함 
- git commit: local repository 로 올리는 것 
- git push: Remote repository 로 올리는 것 
- git fetch: 다른 사람의 작업을 자신의 컴퓨터에 사용
- git merge: 병합 (충돌 발생할 때) // 컴퓨터와 remote 모두에 동일하게 

git branch
- 동시에 여러 개발자들이 프로젝트에서 각기 다른 기능을 개발할 수 있도록 하는 기능 (프로젝트가 끊키지 않게 하는 것) 
- 서로 다른 브랜치는 작업을 할 때 서로에게 영향받지 않음 
- 마스터브랜치가 생성됨 (배포버전) 
