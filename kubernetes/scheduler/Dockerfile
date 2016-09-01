FROM fedora/kubernetes-master
MAINTAINER Solly Ross <sross@redhat.com>

COPY launch.sh /usr/bin/kube-scheduler-docker.sh

ENTRYPOINT ["/usr/bin/kube-scheduler-docker.sh"]
