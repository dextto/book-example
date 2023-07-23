# book-example
Sample source of site for learning Django unit test

Test-Driven Development with Python, 2nd Edition 의 예제 코드를 따라 한 것입니다.  
책의 소스가 [https://github.com/hjwp/book-example](https://github.com/hjwp/book-example)의 소스와는 다른 부분이 있습니다.
저자가 3판을 준비중인 것으로 보입니다.  
 

### 책과의 차이점:
1. browser driver: ChromeDriverManager
2. 호스팅 site명 (superlist-staging.sytes.net ==> noip.com에서 설정) 
3. 서버 로그인 유저이름
4. Pop3: Gmail 사용
5. EMAIL_PASSWORD: Google app password 사용

### 테스트 코드를 수행하기 위한 선행작업:
1. 서버 셋업 (2판, 9장~11장 참고)
2. 로컬에서 GMAIL_PASSWORD 셋업: export GMAIL_PASSWORD=YOUR_GOOGLE_APP_PASSWORD
