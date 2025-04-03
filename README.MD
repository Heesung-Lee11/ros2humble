<개발환경>

1. Raspberry Pi 4B
<img width="50%" src="https://github.com/user-attachments/assets/3b06f4f8-11da-4bce-8c9a-345c44d9a468">

2. Ubuntu 22.04 LTS

* Raspberry Pi imager 를 통해 운영체제를 업로드할 수 있습니다.
<img width="70%" src="https://github.com/user-attachments/assets/e16d31c3-6284-4e79-bdb6-947e33726d83">

<설치과정>

1. ROS2 humble 설치 
https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html

2. rosbridge server 설치
sudo apt install ros-humble-rosbridge-server

<실행 명령어> 

0. source /opt/ros/humble/setup.bash (모든 터미널)
1. ros2 run turtlesim turtlesim_node
2. ros2 launch rosbridge_server rosbridge_websocket_launch.xml

<실행화면><br/>
<img width="70%" src="https://github.com/user-attachments/assets/9f3d9ee4-9a2c-4385-81f8-133827b970fa">

* 위 명령어 실행 완료되면 무선 네트워크 공유하는 PC에서 코드 실행 (이때 기기 ip 확인하고 올바르게 수정 필요)

<웹 컨트롤러 실행화면><br/>
<img width="70%" alt="Image" src="https://github.com/user-attachments/assets/7a28c718-fd54-4e83-a1e7-9ff6f643c4f0" />
