FROM ubuntu:bionic
ARG DEBIAN_FRONTEND=noninteractive
RUN \
	apt update && \
	apt-get install -y build-essential clang-6.0 gcc g++ pkg-config \
		cmake python-pip git-core ccache libftdi-dev \
		zlib1g-dev libusb-1.0-0-dev libdc1394-22-dev \
		libjpeg-dev libopencv-dev libgtest-dev libeigen3-dev \
		libsuitesparse-dev libopenni2-dev libudev-dev \
		libboost-python-dev libpython-dev python-numpy \
		libwxgtk3.0-dev freeglut3-dev libavformat-dev \
		libswscale-dev libassimp-dev qtbase5-dev \
		libqt5opengl5-dev libpcl-dev curl rsync liboctomap-dev \
		lib3ds-dev libpcap-dev libfreenect-dev libyaml-cpp-dev \
		liblas-dev
