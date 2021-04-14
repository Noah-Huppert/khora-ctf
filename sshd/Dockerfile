FROM panubo/sshd:1.3.0

RUN apk add curl

COPY ./sshd_config /etc/sshd/sshd_config

RUN useradd backdoor
RUN usermod -p '*' backdoor

COPY ./authorized_keys /home/backdoor/.ssh/authorized_keys
RUN chown -R backdoor:backdoor /home/backdoor/.ssh
RUN chmod 700 /home/backdoor/.ssh
RUN chmod 600 /home/backdoor/.ssh/authorized_keys
COPY ./this-is-flag-2.txt /home/backdoor

RUN ln -s /var/www /home/backdoor/www
