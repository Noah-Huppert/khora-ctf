FROM kalilinux/kali:latest

RUN apt-get update
RUN apt-get upgrade -y
RUN apt-get install -y \
	procps iproute2 dnsutils \
	python3 python3-pip \
	kali-linux-headless metasploit-framework outguess # cewl

RUN mkdir -p /opt/ctf-workbench
WORKDIR /opt/ctf-workbench

ENTRYPOINT /bin/bash -c "while true; do sleep 1000; done"
