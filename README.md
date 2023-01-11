# jsp 게시판 만들기
출처 : https://dogsavestheworld.tistory.com/260

공통내용 : 뷰, 디비, 컨트롤러 등.
1. 뷰에서 넘기는 command 부분 설명.
2. command 부분 컨트롤러 부분 찾기
3. 해당 디비로 전달하는 메서드 부분
4. dao 부분 코드 설명
5. 해당 디비 테이블에 입력 되는 부분 확인해 주기.
6. Ocam으로 녹화 소리녹화 파일 제출 금요일까지
7. 
# 기획의도
- 개발도구 : JAVA, mysql
- 화면 설계 및 구현 메인페이지, 로그인, 회원가입, 게시판
- jsp 파일로 만들고 mysql DB를 사용해 데이터베이스 연결
  게시판 글쓰기, 목록, 수정, 삭제, 로그인해야 글을 쓸 수 있도록 함.

# 이슈
- 게시판에 첨부 파일이 없고, 검색도 없음...추가 개발 필요
- 초반 DB 생성시 연결이 되지 않았던 문제이슈 발생, 대소문자 구분문제로 해결
- 부트스트랩으로 기존 디자인 변경

# 개선사항
- 이후 첨부파일 개발, 검색 개발 필요

# 게시판 구현 이미지

### 1. 메인 화면

![image](https://github.com/taiji9203/jsp_bbs/blob/main/images/main01.jpg)

### 2. 로그인 화면

![image](https://github.com/taiji9203/jsp_bbs/blob/main/images/main02.jpg)

### 3. 회원가입 화면

![image](https://github.com/taiji9203/jsp_bbs/blob/main/images/main03.jpg)

### 4. 게시판 화면

![image](https://github.com/taiji9203/jsp_bbs/blob/main/images/main04.jpg)

### 5. MYSQL DB 생성 화면

![image](https://github.com/taiji9203/jsp_bbs/blob/main/images/main05.jpg)

