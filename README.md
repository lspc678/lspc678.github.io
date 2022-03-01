Theme: plainwhite
Theme Site: https://github.com/samarsault/plainwhite-jekyll
How to install
0. 참조 사이트: https://zeddios.tistory.com/1223
1. 위 사이트에서 파일 다운로드(Download ZIP)
2. ZIP 파일안에 있는 내용을 모두 <username>.github.io 폴더에 복사(모든 파일 덮어쓰기)
3. 터미널에 bundle install 입력
4. 터미널에 bundle exec jekyll serve 입력 (만약 webrick 오류 발생시 bundle add webrick 입력)
5. 로컬에서 잘 실행되는지 확인(localhost:4000/에 접속)
6. 프로젝트 파일에 있는 Gemfile에서 gemspec을 지우고 gem "plainwhite"를 추가
7. _config.yml에서 theme: plainwhite 주석처리 (에러가 많이 발생한다고 함)
8. 터미널에 bundle 입력
9. 터미널에 bundle exec jekyll serve 입력 후 로컬에서 접속되는지 확인
10. 터미널에 
git add . 
git commit -m "본인의 커밋 메세지" 
git push
입력
11. github에 push 후 <username>.github.io을 주소창에 입력했을 때 정상적으로 접속되는지 확인