FROM ros:kinetic

RUN mkdir -p ~/catkin_ws/src
RUN git clone https://github.com/karaage0703/raspberry-pi-setup
RUN raspberry-pi-setup/setup-ros-indigo-raspbian.sh

CMD ["roscore"]
