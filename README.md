## 0. 실행 환경
- JDK 11버전

---------------------------------------------------
## 1. jar 파일 실행 방법

#### server 파일 실행 방법
	(1) 해당 txt 파일이 있는 디렉터리에서 쉘 창을 연다.
	(2) "cd http2-server/http2-server"를 입력해 디렉터리를 이동한다.
	(3) java -jar server.jar 파일을 실행한다.

#### enhanced server 파일 실행 방법
	(1) 해당 txt 파일이 있는 디렉터리에서 쉘 창을 연다.
	(2) "cd http2-server-evolve/http2-server-evolve"를 입력해 디렉터리를 이동한다.
	(3) java -jar server.jar 파일을 실행한다.

#### client 파일 실행 방법
	(1) 해당 txt 파일이 있는 디렉터리에서 쉘 창을 연다.
	(2) "cd http2-client"를 입력해 디렉터리를 이동한다.
	(3) java -jar client.jar 파일을 실행한다.


### [주의 사항]
인증을 받기 위한 crt 파일이 상대 경로로 입력되어있습니다.
제 로컬 컴퓨터에서만 실행하는 것이 아니기에 상대 경로로 설정해주었기에 디렉터리를 이동해서 jar 파일을 실행해야합니다.


---------------------------------------------------
## 2. IDE를 사용해 main 파일을 run하는 방법
각 폴더에 있는 src 폴더 내의 main 함수를 run 한다.

#### 클라이언트 파일 실행 방법
- client 프로젝트 폴더를 열어서 main 함수(client)를 실행한다.

#### 서버 파일 실행 방법
- 각 디렉터리 내의 build.gradle를 열어서 main 함수(server)를 실행한다.
