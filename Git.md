## Git

- Git 은 분산버전관리시스템 이다.
- 2005년 리누스 토르발스 개발
- 파일의 변경사항을 추적, 사용자들 간 작업 조율



## 분산버전관리시스템(DVCS)

- 중앙에서 버전을 관리하고 파일을 받아서 사용
- 원격 저장소를 통해 협업하고, 모든 히스토리를 클라이언트들이 공유



## 기본 흐름

- 작업하면 Add
- Staging area 에 Stack
- Commit 으로 버전 기록



## File Lifecycle

- Tracked : 이전부터 부전으로 관리되고 있는 파일
  - Unmodified : not appear 
  - Modified
  - Staged
- Untracked : 버전으로 관리된 적 없는 파일

- Difference between 'Clone' and 'zip'
  - .git directory



git clone 'url'

git init



git add 'file'

git commit -m 'file'



git log

git status



get remote add origin 'url'

git push origin master









