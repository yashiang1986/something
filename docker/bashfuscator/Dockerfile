FROM ubuntu:18.04
RUN apt update && \
    apt-get install -y --no-install-recommends python3.7 python3-setuptools python3-pip python3-argcomplete xclip git && \
    git clone https://github.com/Bashfuscator/Bashfuscator && cd Bashfuscator && \
    python3.7 setup.py install && mkdir /opt/data && apt clean
