Dependencies
============

-   Python over version 3
-   qrcode
-   PIL
-   numpy

Install
=======

-   먼저 해당 깃 클론
-   Dependencies 설치
-   pip install Pillow numpy qrcode

사용법
======

python main<sub>gui</sub>.py 를 커맨드 창이 입력하면 됩니다. 이후 GUI 창이 뜨며 자동으로 기본 QR이 생성되어 좌측에 나타납니다. size에 원하는 바이트 사이즈를 입력 후 Make 버튼을 누르면 QR 코드가 생성됩니다. x, y distortion의 슬라이더를 조정하며 distortion 비율을 설정합니다. 그리고 하단의 show distorted를 누를 시 왜곡된 QR 코드가 좌측에 나타납니다. 다시 원래 코드를 보려면 show original을 누르시면 됩니다.
