FROM randomdude/gcc-cross-x86_64-elf

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y nasm
RUN apt-get install -y XORRISO
RUN apt-get install -y grub-pc-bin
RUN apt-get install -y grub-common

VOLUME /ROOT/ENV
WORKDIR /ROOT/ENV