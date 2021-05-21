# Git VSC 터미널 사용법

Git 최신버전 설치후

git --version 확인

1. git init

2. git config --global core.autocrlf input - mac  
   git config --global core.autocrlf true - windows

   - git config --global user.name 'id'
   - git config --global user.email 'email'

3. git config --global --list

4. git status
5. 변경사항 추가 후
6. git add .

7. git status

8. git commit -m 'Start project' -

9. git remote add origin '저장소주소.git'

10. git push origin master

# BRANCH 관리

1. git branch
1. git branch -a : 로컬 저장소/리모트 내에 모든 리스트 출력
1. git branch signin : signin 브렌치생성
1. git checkout signin : signin 으로 브렌치로 변경
1. git push origin signin : 해당 signin 브렌치에서 푸시

# 깃 복제

1. git clone http://www.github.com/cksgh2064/starbucks.git
1. git remote add origin '저장소주소.git'

# 브렌치 복제

1. git branch -r : 브렌치 리스트
1. git checkout -t origin/purple : 복제

# 브렌치 삭제

1.  git branch -d 브렌치명

# 기타

- 커밋 되돌리기
  git reset --hard HEAD~1 :  
   HEAD가 최상위버전인데 그 버전에서 앞으로 버전을 한칸되돌리겠다는 말

- 되돌린 커밋 원상복귀시키기  
  git reset --hard ORIG_HEAD

- PULL  
  git pull origin master
