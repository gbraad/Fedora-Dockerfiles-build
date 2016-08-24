FROM registry.gitlab.com/gbraad/fedora:24
MAINTAINER Gerard Braad <me@gbraad.nl

RUN dnf -y install docker-io git python-docker-py python-setuptools koji atomic-reactor; \
    dnf clean all

CMD ["atomic-reactor", "-v", "inside-build", "--input", "path"]
