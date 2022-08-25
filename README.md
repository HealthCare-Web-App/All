# Health Care Web-APP <br>
#### 사용자가 자신의 운동 일지를 기록하는 웹 어플리케이션입니다.
#### 게시판 컨텐츠가 있어 사용자 간 의사소통이 가능합니다. 

<br>

# 기능
- #### 유저 회원가입
- #### 유저 로그인 & 로그아웃
- #### 게시판 기능(CRUD), 해당 게시판에 댓글 달 수 있음
- #### 달력에 원하는 날짜에 사용자가 운동을 기록, 조회할 수 있음
<br><br>

# 사용 기술
- #### frontend : React,
- #### backend : SpringBoot, JPA
- #### 배포 : docker, aws ec2
(각 파트의 자세한 기술스택을 알고 싶다면 fe, be 리포지토리를 방문해주시기 바랍니다.)
<br><br>

# 배포 및 실행
#### AWS ec2에 docker로 무중단 배포.<br>
#### http://3.34.217.132:8080/ 로 접속가능합니다.
<br>
위의 홈페이지로 접속 가능하나, ec2가 무료버전(t2.micro) 이므로 성능이 매우약해 서버가 다운될 가능성이 있습니다. <br>
따라서 접속이 불가한 최악의 경우 경우 다음과 같이 실행해주시기 바랍니다. <br><br>

#### 1. 프로젝트를 받은 후 gradle의 bootJar로 빌드 (꼭 bootJar 일 필요는 없음!) -> jar파일 생성. <br>
#### 2. java -jar (jar파일이름) 을 하면 프로그램이 실행됩니다. 이때 java 버전은 11로 해야합니다.<br>
#### 4. localhost:8080 으로 접속하면 끝입니다. <br>
<br> 

# 기능 시연
### 웹 어플리케이션 실행한 모습입니다.
#### 1. 게시판
![ezgif com-gif-maker](https://user-images.githubusercontent.com/56336436/186668646-2b77995b-19b8-4379-97e2-be589fdb3da2.gif)
<br><br> 

#### 2. 댓글 작성
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/56336436/186670371-affe95b2-3282-4f68-b142-2e1a36b9406a.gif)
<br><br>

#### 3. 게시글 작성
![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/56336436/186670816-fb5ed5f4-069a-40a6-937f-9909d4341eab.gif)
<br><br>

#### 4. 회원가입 예시
![ezgif com-gif-maker (3)](https://user-images.githubusercontent.com/56336436/186671289-a018f5a0-25d1-453f-8463-1f2423bf3cef.gif)
<br><br>

#### 5. 로그인
![ezgif com-gif-maker (4)](https://user-images.githubusercontent.com/56336436/186671645-7e9138f1-3a68-4503-9430-49442c156733.gif)
<br><br>

### 6. 운동로그 작성
![ezgif com-gif-maker (5)](https://user-images.githubusercontent.com/56336436/186671852-1447f060-ee50-44dd-baee-7ff7fa70dba7.gif)

