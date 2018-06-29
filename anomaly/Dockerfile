FROM registry.centos.org/centos/centos:latest

LABEL RUN='docker run --rm --privileged $IMAGE /dev/tail -f /dev/null'

RUN useradd foo && touch /bin/ls && touch /bin/pwd && chown root:foo /bin/ls
