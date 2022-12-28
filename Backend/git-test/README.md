## Git Command

- `git init`
        git init을 해주면 main bracnh 생성 그리고 폴더내의 보이지 않는 .git 생김 확인 방법은 init한 폴더에서 ls -al을 입력하면 터미널에 출력
- `git remote add origin <remote repository url>`
        github에 내 local 과 연결하기 위해 내가 만든 레퍼지토리 url 복사해서 붙여넣으면 git과 github가 연결 
- `git add <file name>`
        수정한 파일을 깃허브에 추가한다. 수정한 파일 이름만 써서 추가해도 가능하지만 git add . 을 사용하자!
- `git commit`
        add 한 파일을 올릴때 이름을 정해서 올려주는 명령어 -m 이 붙고 " " 안에 원하는 내용을 입력해주면 된다
- `git push origin <branch name>`
        깃허브에 올리는 명령어, 작업한 브랜치에서 에드 커밋을 해준후 마지막으로 푸쉬해준다. 브랜치 네임 경로 유의해서 보기!
- `git pull origin <branch name>`
        수정한 파일을 main 브랜치에 update 해준다.
- `git merge <branch name>`
        병합 하고 싶은 파일의 이름을 쓰고 병합한다.

