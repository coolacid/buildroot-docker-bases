FROM debian:buster-slim

ARG VERSION=master
RUN echo "Building version: ${VERSION}"
RUN git clone --branch ${VERSION} --depth 1 https://git.buildroot.net/buildroot
RUN make raspberrypi3_defconfig
RUN make
