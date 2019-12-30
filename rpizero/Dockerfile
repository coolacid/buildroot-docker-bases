FROM coolacid/buildroot-base:base-latest

RUN make raspberrypi0_defconfig
RUN echo BR2_TOOLCHAIN_BUILDROOT_WCHAR=y >> .config
RUN make toolchain
