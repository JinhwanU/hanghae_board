# 프로젝트명 
- hanghae_blog : 주특기PBL 1주차 개인과제

# 프로젝트 기본 정보
**1. 제작 기간**
- 2022.02.11 ~ 2022.02.17
  
  <br>
**2. 프로젝트 인원**
- 1인

  <br>
**3. 개발 도구**
- IDE
  - Intelli J
  
- Language
  - Java8  
  - Html
  - CSS
  - Javascript

- Framework
  - Spring boot
  - Hibernate (Spring Data JPA)
  
- Database
  - H2
  - MySql
  <br>
# 프로젝트 요구사항

1. 전체 게시글 목록 조회
    - 제목, 작성자명, 작성 날짜를 조회하기
    - 작성 날짜 기준으로 내림차순 정렬하기
2. 게시글 작성
    - 제목, 작성자명, 작성 내용을 입력하기
3. 게시글 조회
    - 제목, 작성자명, 작성 날짜, 작성 내용을 조회하기
4. 게시글 수정
    - 제목, 작성자명, 작성 내용 중 원하는 내용을 수정하기
5. 게시글 삭제
    - 원하는 게시물을 삭제하기
6. 댓글 목록 조회
    - 조회하는 게시글에 작성된 모든 댓글을 목록 형식으로 볼 수 있도록 하기
    - 작성 날짜 기준으로 내림차순 정렬하기
7. 댓글 작성
    - 댓글 내용을 비워둔 채 댓글 작성 API를 호출하면 "댓글 내용을 입력해주세요" 라는 메세지를 return하기
    - 댓글 내용을 입력하고 댓글 작성 API를 호출한 경우 작성한 댓글을 추가하기
8. 댓글 수정
    - 댓글 내용을 비워둔 채 댓글 수정 API를 호출하면 "댓글 내용을 입력해주세요" 라는 메세지를 return하기
    - 댓글 내용을 입력하고 댓글 수정 API를 호출한 경우 작성한 댓글을 수정하기
9. 댓글 삭제
    - 원하는 댓글을 삭제하기


# DB 설계
![image](https://user-images.githubusercontent.com/96904426/155465824-cc59ff14-d328-4d9a-a017-e79faf86914e.png)

Post : Comment  ->  1:N 양방향 연관관계

# API 설계
![image](https://user-images.githubusercontent.com/96904426/155468550-02845e6e-1a80-49ed-80be-2e6900835081.png)


# 화면 설계(View)

- 메인화면<br>
  <br>
  ![image](https://user-images.githubusercontent.com/96904426/155469087-4b9f40b0-0e01-4a69-90bb-3c909181f7db.png)
  
- 게시글 작성 화면<br>
  <br>
  ![image](https://user-images.githubusercontent.com/96904426/155469336-2aecff43-9703-4f71-a691-1bbd33f37d73.png)

- 게시글 상세화면<br>
  <br>
  ![image](https://user-images.githubusercontent.com/96904426/155469243-b3e829d5-f879-4e1f-8a03-f77c8f45a592.png)

- 댓글 수정<br>
  <br>
  ![image](https://user-images.githubusercontent.com/96904426/155469519-89d5a331-3065-4455-80a1-2633e1f448b0.png)
  <br>
  ![image](https://user-images.githubusercontent.com/96904426/155469474-9bda43e4-97f5-4814-b4f8-69f6015da3e4.png)


  
