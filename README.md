# 라인봇 만들기

## 1.1 라인 개발자 계정 생성

[https://developers.line.biz](https://developers.line.biz/)

에서 개발자 계정 생성후 

`create new provider` 버튼 클릭해서 Provider 생성

## 1.2 채널 생성

`create new chanel` 으로 채널 생성후 

봇 을 만들거기 때문에 `messaging API ` 를 선택해준다

다음과 같은 화면이 나온다

![image-20191031151825887](/Users/tomlee/Library/Application Support/typora-user-images/image-20191031151825887.png)

## 1.3 봇 친구 추가

만들어진 봇을 클릭하면 세팅 페이지가 나온다 

밑으로 내리면 qr 코드가 있는데 핸드폰 라인앱을 켜서 친구추가를 해준다

![image-20191031151951546](/Users/tomlee/Library/Application Support/typora-user-images/image-20191031151951546.png)

## 1.4 자동응답, 환영메세지 끄기

옆에 set message 눌러서

![image-20191031152000543](/Users/tomlee/Library/Application Support/typora-user-images/image-20191031152000543.png)

![image-20191031152201390](/Users/tomlee/Library/Application Support/typora-user-images/image-20191031152201390.png)

다음과 같이 설정해준다

![image-20191031152344837](/Users/tomlee/Library/Application Support/typora-user-images/image-20191031152344837.png)

## 1.5 토큰 발급 

![image-20191031152454311](/Users/tomlee/Library/Application Support/typora-user-images/image-20191031152454311.png)

![image-20191031152544763](/Users/tomlee/Library/Application Support/typora-user-images/image-20191031152544763.png)



`channel secret`,` channel access token` 값을 잘 복사해서 따로 저장해둔다.

이값들은 봇의 아이디, 패스워드와 같은 인증수단으로 사용하기 때문에 공개되면 안된다. 




heroku login



 

