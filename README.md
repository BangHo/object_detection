1. object_detection/amz : 노란 라바콘과 파란 라바콘을 구분하기 위한 소스코드가 포함되어 있습니다. 라바콘의 위치와 클래스가 담겨있는 바운딩박스의 정보를 fusion 패키지로 publish하여 LiDAR 데이터와 결합하여 사용했습니다.
2. object_detection/deli : 표지판을 인지하는 배달 미션과 신호등 미션을 위한 소스코드가 포함되어 있습니다. 신호등의 정보는 camera/src/yolo_traffic.cpp로 이동하여 판단에게 신호를 전달했습니다. 배달 표지판의 정보는 위의 amz와 같은 방식으로 표지판의 위치와 클래스가 담겨있는 바운딩 박스의 정보를 fusion 패키지로 publish하여 LiDAR 데이터와 결합하여 사용했습니다.
