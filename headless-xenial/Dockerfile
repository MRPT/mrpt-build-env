FROM ubuntu:xenial

RUN apt-get update && \
	apt install -y software-properties-common && \
	add-apt-repository -y ppa:jolting/backport-mrpt && \
	add-apt-repository -y ppa:ubuntu-toolchain-r/test && \
	apt-get update && \
	apt-get install -y build-essential gcc-7 g++-7 pkg-config \
		cmake python3-pip git-core ccache \
		libftdi-dev zlib1g-dev libusb-1.0-0-dev \
		libdc1394-22-dev libjpeg-dev libopencv-dev \
		libjsoncpp-dev libtinyxml2-dev \
		libgtest-dev libeigen3-dev libsuitesparse-dev \
		libopenni2-dev libudev-dev libboost-python3-dev \
		libpython3-dev python3-numpy curl
