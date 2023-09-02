<h2>Theme: plainwhite </h2> <br>
<h3> Theme Site: https://github.com/samarsault/plainwhite-jekyll </h3> <br>
<h1> How to install </h1> <br> 

1. 참조 사이트: https://zeddios.tistory.com/1223
2. 위 사이트에서 파일 다운로드(Download ZIP)
3. ZIP 파일안에 있는 내용을 모두 {username}.github.io 폴더에 복사(모든 파일 덮어쓰기)
4. 터미널에 bundle install 입력
5. 터미널에 bundle exec jekyll serve 입력 (만약 webrick 오류 발생시 bundle add webrick 입력)
6. 로컬에서 잘 실행되는지 확인(localhost:4000/에 접속)
7. 프로젝트 파일에 있는 Gemfile에서 gemspec을 지우고 gem "plainwhite"를 추가
8. _config.yml에서 theme: plainwhite 주석처리 (에러가 많이 발생한다고 함)
9. 터미널에 bundle 입력
10. 터미널에 bundle exec jekyll serve 입력 후 로컬에서 접속되는지 확인
11. 터미널에 
git add . <br>
git commit -m "본인의 커밋 메세지" <br>
git push <br>
입력 
12. github에 push 후 {username}.github.io을 주소창에 입력했을 때 정상적으로 접속되는지 확인

<h1> 로컬에서 테스트 하는 방법 </h1> <br>

1. Start Command Prompt with Ruby 클릭 <br>
2. {username}.github.io로 이동 <br>
3. 터미널 창에 bundle install 입력 <br>
4. 터미널 창에 bundle exec jekyll serve 또는 jekyll s입력 <br>
5. localhost:4000/에 접속