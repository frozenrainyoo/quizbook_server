quizbook_server
===============

This is SNS Server using Ruby On Rails


ㅁ. 실행 방법
 1. bundle install
 2. rake db:migrate
 3. rails s

ㅁ. REST API 목록
 * API 테스트하기 편리한 크롭웹앱
   - https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo?hl=ko

 1). 회원등록 API
 URL : http://localhost:3000/users.json 
 Query : ‘user[email]=user_email&user[password]=user_password’

 2). 로그인 API
 URL : http://localhost:3000/users/sign_in
 Query : ‘email=user_email&password=user_password’