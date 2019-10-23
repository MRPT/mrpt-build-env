FROM ubuntu:xenial

RUN apt-get update && \
	apt install -y software-properties-common wget && \
	add-apt-repository -y ppa:jolting/backport-mrpt && \
	add-apt-repository -y ppa:ubuntu-toolchain-r/test && \
	wget -O - http://apt.llvm.org/llvm-snapshot.gpg.key | apt-key add - && \
	add-apt-repository "deb http://apt.llvm.org/xenial/ llvm-toolchain-xenial-6.0 main" && \
	apt update && \
	apt-get install -y build-essential clang-6.0 gcc-7 g++-7 pkg-config \
		cmake python3-pip git-core ccache libftdi-dev \
		zlib1g-dev libusb-1.0-0-dev libdc1394-22-dev \
		libjpeg-dev libopencv-dev libgtest-dev libeigen3-dev \
		libsuitesparse-dev libopenni2-dev libudev-dev \
		libboost-python-dev libpython3-dev python3-numpy \
		libwxgtk3.0-dev freeglut3-dev libavformat-dev \
		libswscale-dev libassimp-dev qtbase5-dev \
		libqt5opengl5-dev libpcl-dev curl \
		libxrandr-dev
