<개발환경>

1. Raspberry Pi 4B
2. Ubuntu 22.04 LTS

* Raspberry Pi imager 를 통해 운영체제 업로드 

<설치과정>

1. ROS2 humble 설치 
https://docs.ros.org/en/humble/Installation/Ubuntu-Install-Debs.html

2. rosbridge server 설치
sudo apt install ros-humble-rosbridge-server

<실행 명령어> 

0. source /opt/ros/humble/setup.bash (모든 터미널)
1. ros2 run turtlesim turtlesim_node
2. ros2 launch rosbridge_server rosbridge_websocket_launch.xml

* 위 명령어 실행 완료되면 무선 네트워크 공유하는 PC에서 코드 실행 (이때 기기 ip 확인하고 올바르게 수정 필요)