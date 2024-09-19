# 설치과정 
1. git 프로그램을 Download하고 설치(default). 
2. git을 설정하기 위한 workspace 폴더 생성.
3. gitHub 사이트에 접속하여 회원가입 및 로그인 진행.
4. 우측상단 "new Repository"클릭
    - 내용을 입력하고 생성. 
5. workspace 폴더 내에서 "git Bash" 실행.
6. 초기 설정 
   : git config --list(내용확인)
   : git config --global user.name "leedakyubg-rosa"
   : git config --global user.email "damy619@naver.com"
   * Git 을 설치하고 나서 제일 먼저 해야하는 것은 "계정정보" 설정
   * Git은 commit할 때마다, 이 정보를 사용 
      (한번 커밋한 뒤, 정보변경 불가능)
7. 초기화 
  - git init
8. 원격저장소 설정 
   * git remote add first_remote_repo https://github.com/.../first_repositon
9. workspace 폴더 내 REAME.md 파일 생성 및 내용 작성
10. 상태 확인 
   * git status 
11. 저장소에 변경된 파일을 관리할 수 있도록 추가 
   * git add .
   * git add README.md
12. Local Repository에 저장 
   *git commit -m "first_commit"
   *commit 이름은 해당 작업에서 추가/변경된 사항을 간략히 작성 
   * 다른 작업자가 알아볼 수 있도록 작성 및 되도록이면 영어로 작성하는 것을 추천 
13. Remote Repository에 저장 
   * git push first_remote_repo master