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

### docker로 실행
#### 컴퓨터에 Docker Desktop 이 설치되어 있어야 합니다. 도커 데스크탑을 실행해줍니다.
#### 최초 실행 시
: 터미널을 열어 다음 명령어를 복붙합니다.
> docker run -it --name app -p 8080:8080 matt1235/healthcare_web:0.0.1 bash
<br>
실행되면, localhost:8080으로 접속하면 끝입니다. <br>

#### 중단 후 재실행시
> docker start -ai matt1235/healthcare_web:0.0.1 
<br>
<br> 

# 기능 시연
#### [1. 운동로그 작성](https://user-images.githubusercontent.com/56336436/187936410-7831b502-6b26-49f6-89b1-c0982f223036.gif)<br>

#### [2. 회원가입 예시](https://user-images.githubusercontent.com/56336436/187938807-2855a86b-589c-43b2-a394-c63ebc6098fa.gif)<br>

#### [3. 로그인](https://user-images.githubusercontent.com/56336436/187938926-6689c5d5-c617-4b7d-8869-b8a56a82b7a4.gif)<br>

#### [4. 게시글 작성](https://user-images.githubusercontent.com/56336436/187939227-d7a1c376-6765-425e-98a7-f646d737e049.gif)<br>

#### [5. 댓글 작성](https://user-images.githubusercontent.com/56336436/187939322-8a7929a8-b760-444b-aeb4-b4f917e229aa.gif)<br>

#### [6. 게시글 삭제](https://user-images.githubusercontent.com/56336436/187939560-99d1bdad-e309-43a8-8a8e-960f301f02b9.gif)
