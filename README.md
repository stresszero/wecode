# git init
현재 폴더에서 git 관리를 시작하는 명령어이다
이 명령어를 입력하면 숨김폴더로 .git 폴더가 생성된다

# git add
변경된 파일을 git이 관리하게끔 추가해주는 명령어이다
git add . 를 하면 .gitignore에 등록된 것들은 제외되고
git add * 를 하면 .gitignore에 상관없이 모든 파일을 추가한다

# git commit
변경 내용을 확정하는 명령어이다
옵션없이 입력하면 커밋 내용을 입력하는 텍스트 에디터가 열린다
-m "커밋 내용" 옵션을 이용하면 에디터가 열리지 않고 내용이 그대로 입력된다

# git remote add
github 등의 원격 저장소를 추가하는 명령어이다
git remote add origin 원격저장소url
주로 사용하는 저장소에는 보통 origin이라는 이름을 붙여준다

# git push
로컬 저장소에 저장된 내용을 원격 저장소에 저장하는 명령어 이다
원격저장소 이름을 origin이라고 지었다면 git push origin 브랜치명
을 입력하면 된다
