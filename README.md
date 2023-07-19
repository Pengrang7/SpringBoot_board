# SpringBoot_board

참고 영상: https://youtu.be/YshcPPHClR4

구조
![image](https://github.com/Pengrang7/SpringBoot_board/assets/79880461/1f0bf7b6-67fc-4a92-88aa-a3af3b5ad8b4)

src/main/java: 자바 소스 코드가 위치하는 디렉토리입니다.

board.config: 웹 설정과 관련된 클래스나 설정 파일이 위치합니다. 예를 들어, WebConfig는 웹 애플리케이션의 설정을 구성할 수 있는 클래스일 수 있습니다.
board.controller: 컨트롤러 클래스들이 위치하는 디렉토리입니다. BoardController, HomeController, CommentController 등이 여기에 포함됩니다. 이 컨트롤러들은 웹 요청을 처리하고 적절한 응답을 반환합니다.
board.dto: 데이터 전달을 위한 DTO(Data Transfer Object) 클래스들이 위치하는 디렉토리입니다. BoardDTO, CommentDTO 등이 여기에 포함됩니다. 이 클래스들은 컨트롤러와 서비스 간의 데이터 전달에 사용될 수 있습니다.
board.entity: 엔티티 클래스들이 위치하는 디렉토리입니다. BaseEntity, BoardEntity, BoardFileEntity, CommentEntity 등이 여기에 포함됩니다. 이 클래스들은 데이터베이스 테이블과 매핑되는 객체로, 데이터베이스 조작에 사용될 수 있습니다.
board.repository: 리포지토리 인터페이스들이 위치하는 디렉토리입니다. BoardFileRepository, BoardRepository, CommentRepository 등이 여기에 포함됩니다. 이 인터페이스들은 데이터베이스 조작을 추상화하고, 서비스에서 데이터베이스에 접근할 수 있도록 도와줍니다.
board.service: 서비스 클래스들이 위치하는 디렉토리입니다. BoardService, CommentService 등이 여기에 포함됩니다. 이 클래스들은 비즈니스 로직을 처리하고, 컨트롤러와 리포지토리 간의 중재 역할을 수행합니다.
BoardApplication: 애플리케이션의 진입점인 메인 클래스입니다. 이 클래스는 애플리케이션을 시작하는 데 필요한 설정을 담당합니다.
src/main/resources: 리소스 파일들이 위치하는 디렉토리입니다.

static: 정적 파일(이미지, CSS, JavaScript 등)이 위치하는 디렉토리입니다.
templates: 템플릿 파일(HTML, Thymeleaf 등)이 위치하는 디렉토리입니다. detail.html, index.html, list.html 등의 파일들이 여기에 있습니다. 이 템플릿 파일들은 웹 페이지의 레이아웃과 내용을 정의하는 데 사용됩니다.
application.yml: 애플리케이션의 설정 파일입니다. 여기에는 데이터베이스 연결 정보, 로깅 설정, 서버 포트 등의 설정이 포함될 수 있습니다.

이 구조를 통해 게시판의 CRUD(Create, Read, Update, Delete) 기능을 개발하고, 사용자들이 게시물을 작성하고 댓글을 달 수 있는 웹 애플리케이션을 구현할 수 있습니다. 필요에 따라 구조를 확장하거나 수정하여 기능을 추가하거나 변경할 수도 있습니다.

