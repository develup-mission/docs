## 미션 가이드

### 1. 미션을 자신의 계정으로 fork

develup-mission의 repository에 저장되어 있는 미션을 자신의 계정으로 가져옵니다.

<img width="1353" alt="스크린샷 2024-07-15 오후 4 00 12" src="https://github.com/user-attachments/assets/2c835367-78ee-4ac9-8f63-b54ac5b064f1">

### 2. fork한 저장소를 자신의 컴퓨터로 clone

자신의 계정으로 가져온 미션을 로컬 컴퓨터에 저장합니다.

### 3. 기능 구현

`README.md` 파일을 참고하여 미션을 진행합니다.

### 4. 기능 구현 후 add, commit

기능 구현 후 변경된 코드를 저장소에 반영하기 위해 add, commit 명령을 사용합니다.
```
git status // 변경된 파일 확인
git add 파일명 또는 git add . // 변경된 단일 파일 또는 전체 파일 반영
git commit -m '메세지' // 작업한 내용을 메시지에 기록
```

### 5. 본인 원격 저장소에 업로드

로컬에서 commit 명령을 실행하면 로컬 저장소에만 반영되고, 원격 github.com의 저장소에는 반영되지 않습니다.
github.com의 저장소에도 동일하게 반영하기 위해 push 명령어를 사용합니다.
```
git push origin 브랜치이름
ex) git push origin develup
```

### 6. github 서비스에서 Pull Request 제출

Pull Request는 github에서 제공하는 기능으로 코드리뷰 요청을 보낼 때 사용합니다.
Pull Request는 original 저장소의 main 브랜치와 앞 단계에서 생성한 브랜치 이름을 기준으로 합니다.
