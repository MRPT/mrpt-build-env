FROM ubuntu:jammy
ARG DEBIAN_FRONTEND=noninteractive
RUN \
	apt update && \
	apt-get install -y build-essential clang gcc g++ pkg-config \
	cmake python3-pip git-core ccache \
	doxygen-latex doxygen freeglut3-dev ghostscript graphviz libassimp-dev libavcodec-dev \
	libavformat-dev libavutil-dev libswscale-dev libcv-bridge-dev libdc1394-dev libeigen3-dev \
	libfreenect-dev libftdi1-dev libgeometry-msgs-dev libglfw3-dev libglu1-mesa-dev libicu-dev \
	libjpeg-dev libjsoncpp-dev libnanoflann-dev libnav-msgs-dev liboctomap-dev libopencv-dev \
	libopenni2-dev libpcap-dev libqt5opengl5-dev librosbag-storage-dev libroscpp-dev \
	libsensor-msgs-dev libsimpleini-dev libstd-srvs-dev libstereo-msgs-dev libsuitesparse-dev \
	libtf2-dev libtf2-msgs-dev libtinyxml2-dev libudev-dev libusb-1.0-0-dev libwxgtk3.0-gtk3-dev \
	libxrandr-dev libxxf86vm-dev qtbase5-dev texlive latexmk texlive-latex-extra texlive-science \
	zlib1g-dev libgtest-dev fonts-roboto-fontface libfyaml-dev pybind11-dev python3-dev python3-setuptools \
	clang-format-11
