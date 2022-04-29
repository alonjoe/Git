## Git 명령어

#### git init - 이제부터 git으로 버전관리 할거야!
#### git add (파일명) - 단일 파일의 변경사항 포함
#### git add . - 모든파일 변경사항 포함
#### git commit -m "메시지" - 커밋 생성
#### git clone (저장소주소) - 원격저장소(github) 복제
#### git status - 파일 상태 확인
#### git branch - 브랜치 확인
#### git branch (이름) - 브랜치 생성
#### git branch -d (이름) - 브랜치 삭제
#### git checkout -b (이름) - 브랜치 생성 후 이동
#### git checkout (이름) - 브랜치로 이동
#### git push origin master - 원격저장소(github)에 업로드
#### git pull - 원격저장소 내용을 가져와서 merge됨
#### git diff (이름) (이름) - merge전에 바뀐 내용 비교
#### git log - 현재 위치한 브랜치 커밋 내용 확인 및 식별자 부여됨

merge 할 때는 항상 master branch의 변경사항을 로컬에 pull로 가져온 후에 merge하도록 하자.
1. 내 branch에서 push
2. git checkout master
3. git pull (origin master)
4. git merge (내 branch)
5. git checkout (내 branch)
6. git pull (origin master)

