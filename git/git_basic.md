## Git Config 설정

```bash
// 전체 config 리스트 확인
git config //list

// git config 설정하는 방법
git config //global user.email "[email]"
git config //global user.name "[name]"

// git config 삭제
git config //unset user.email

// 삭제 해도 남아 있는 경우
git config //unset //global user.email
```

## Git 기본 명령어
```bash
// 현재 상태 확인
git status

// 전체 로그 확인
git log

// git 저장소 생성하기
git init

// 저장소 복제 및 다운로드
git clone [https:~~]

// 저장소에 코드 추가
git add
git add *

// 커밋에 파일 변경 사항을 한버넹 모두 포함
git add -A

// 커밋 생성
git commit -m "message"

// 변경 사항 원격 서버 업로드(push)
git push origin master

// 원격 저장소의 변경 내용을 현재 디렉토리에 가져오기(pull)
git pull

// 변경 내용을 merge 하기 전에 바뀐 내용 비교
git diff [브랜치 이름] [다른 브랜치 이름]
```

## Git Branch 관련
```bash
// git init을 설정하면 해당 폴더에 .git이라는 파일이 생성됨
git init

// github 주소와 연결
git remote add origin [github 주소]

// 브랜치 생성
git branch [브랜치명]

// 해당 브랜치로 이동
git checkout [브랜치명]

// 브랜치를 생성하고 해당 브랜치로 바로 이동
git branch -b [브랜치명]

// 원하는 브랜치로 이동했는지 확인
git branch

// 모든 브랜치 확인
git branch -a

// 파일 및 폴더 add
git add .

// 커밋
git commit 

// 원하는 브랜치로 push하여 원격 서버에 전성
git push origin [브랜치명]

// 브랜치 삭제
git branch -d [브랜치명]

// 현재 브랜치에 다른 브랜치 수정사항 병합
git merge [다른 브랜치명]
```
