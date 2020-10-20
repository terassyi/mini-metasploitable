FROM kalilinux/kali-rolling:latest

RUN apt-get -y update && \
    apt-get -y install metasploit-framework openssh-server vim 
    # apt-get -y install kali-linux-top10 && \
# RUN apt install -y iproute2　&& \
    # apt install -y iputils-ping net-tools

# see https://www.kali.org/news/kali-linux-metapackages/ for more tools

CMD ["/bin/bash"]
