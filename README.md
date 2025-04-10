***

과제1번 pub1-1

 예제1번을 수정하여 문자열 대신에 정수값을 0으로 초기화하고 1씩 증가 시키면서 퍼블리시 하는 패키지 pub1-1를 작성하시오.

 토픽 메시지 인터페이스는 std_msgs/msg/Int32을 사용할 것

 소스파일 작성시 헤더 파일명과 클래스 명을 수정해야함 (15페이지참고)

 예제 1번과 같이 ROS2 명령어로 실행 결과를 확인하라.

과제2번 pub1-2

 예제 1번을 수정하여 키보드로부터 실수값 3개를 입력받아 퍼블리시 하는 패키지 pub1-2를 작성하시오.

 토픽 메시지 인터페이스는 geometry_msgs/msg/Vector3을 사용

 패키지 생성시 의존패키지에서 std_msgs->geometry_msgs으로 수정해야함

 소스 파일 작성시 헤더 파일명과 클래스 명을 수정해야함 (15페이지참고)

 CMakeLists.txt의 add_executables 명령에서 의존 패키지를 std_msgs-> geometry_msgs으로 수정해야함

 예제1번과 같이ROS2명령어로실행결과를확인하라.

과제3번 pub1-3

 Turtlesim 패키지의 teleop_turtle 노드를 대신하는 패키지 pub1-3를 작 성하라.

 키보드입력시/turtle1/cmd_vel 토픽을 발행하도록 할 것

 f-> 전진, b->후진, l->좌회전, r->우회전

 메시지인터페이스는geometry_msgs/msg/Twist를 사용할 것

 패키지생성시의존패키지에서std_msgs-> geometry_msgs으로 변경

 소스파일작성시헤더파일명과클래스명을수정해야함(15페이지참고)

 CMakeLists.txt의 add_executables 명령에서 의존 패키지를 std_msgs에서 geometry_msgs으로 변경

 turtlesim(subscriber 역할수행) 노드를 실행하고 테스트 할 것


실제 코드 실행 영상입니다.

https://www.youtube.com/watch?v=iJncwlF0ngE

***

과제 1번 pub2-1

 예제 1 번을 수정하여 문자열 대신에 정수값을 0 으로 초기화하고 1씩 증가시키면서 퍼블리시하는 패키지 pub 2 1 를 작성하시오

 토픽 메시지 인터페이스는 std_msgs /msg/Int 32 을 사용할 것 11 페이지 참고

 소스파일작성시 헤더파일명과 클래스명을 수정해야함

 예제 1 번과 같이 ROS 2 명령어로 실행 결과를 확인하라

ros2 run pub2-1 pub2_1

과제 2번 pub2-2

 예제 1 번을 수정하여 키보드로부터 실수값 3 개를 입력받아 퍼블리시하는 패키지 pub 2 2 를 작성하시오

 토픽 메시지 인터페이스는 geometry_msgs /msg/Vector 3 을 사용할것 11 페이지 참고

 패키지 생성시 의존패키지에서 std_msgs 를 geometry_msgs 으로 수정해야함

 소스파일작성시 헤더파일명과 클래스명을 수정해야함

 CMakeLists txt 의 add_executables 명령에서 의존 패키지를 std_msgs 에서 geometry_msgs 으로 수정해야함

 예제 1 번과 같이 ROS 2 명령어로 실행 결과를 확인하라

ros2 run pub2-2 pub2_2

과제 3번 pub2-3

 Turtlesim 패키지의 teleop_turtle 노드를 대신하는 패키지 pub 2 3 를 작성하라

 거북이의 선속도와 각속도를 적당한 값으로 전송하여 거북이가 일정한 반경으로 무한히 회전하도록 /turtle 1 cmd_vel 토픽을 발행할 것

 geometry_msgs /msg/Twist 를 사용할 것 11 페이지 참고

 패키지 생성시 의존패키지에서 std_msgs 를 geometry_msgs 으로 수정해야함

 소스파일작성시 헤더파일명과 클래스명을 수정해야함

 CMakeLists txt 의 add_executables 명령에서 의존 패키지를 std_msgs 에서 geometry_msgs 으로 수정해야함

 turtlesim (subscriber 역할수행 노드를 실행하고 테스트 할 것

ros2 run turtlesim turtlesim_node

ros2 run pub2_3 pub_node

실제 코드 실행 영상입니다.

https://youtu.be/KqpjBvSP1h8

***



