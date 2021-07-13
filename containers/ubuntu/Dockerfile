FROM ubuntu:18.04
RUN apt update
RUN apt install -y build-essential gdb python3 wget
RUN wget https://github.com/slimm609/checksec.sh/archive/refs/tags/2.4.0.tar.gz
RUN tar zxvf 2.4.0.tar.gz
RUN cp checksec.sh-2.4.0/checksec /usr/local/bin