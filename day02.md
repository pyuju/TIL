#github에 로컬자료 업로드
1. github에 주소 만들기
2. vscode에서 git init 하기
3. 파일 만들기
4. 내용 작성하고 add. 하기
5. commit -m "수정사항" 하기
6. get remote add origin "주소"
7. get push -u origin master 하기
8. github 새로고침해서 업데이트 내용확인

#github에서 로컬로 내려받기
1. 내려받을 자료가 있는 github주소확인, 복사
2. 터미널에서 git clone "주소" 입력하고 home에 파일생성확인
3. vscode에서 폴더열고 git pull 
4. 자료 수정하거나 추가해서 add, commit, push 진행
5. github에서 수정사항 업데이트 확인

#git으로 프로젝트 만들때 필요한 2가지
1. README.md
2. .gitignore 

#.gitignore이란
github에 공유하고 싶지 않은 파일을 넣은 곳
한번 git에 add하면 ignore에 넣어도 적용되지 않음. add전에 ignore로 옮기기

git init은 push할떄, git clone은 pull할때 한번씩만 하면 된다.

#주의사항
1. 중첩 init 금지
2. home에 init 금지
3. 폴더를 다른 곳으로 이동하는 것은 상관없지만 그 안에 있는 .git폴더안에 다른 저장소를 널으면 안됨

