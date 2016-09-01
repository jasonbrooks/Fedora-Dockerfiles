FROM fedora
MAINTAINER Solly Ross <sross@redhat.com>

RUN dnf -y update && dnf clean all
RUN dnf install -y kubernetes-node && dnf clean all
