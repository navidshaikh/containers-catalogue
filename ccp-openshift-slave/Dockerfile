FROM registry.centos.org/openshift/jenkins-slave-base-centos7

RUN yum install -y PyYAML docker epel-release && \
    yum install -y npm && \
    yum clean all && \
    npm install -g dockerfile_lint

ADD scanning /opt/scanning
VOLUME ["/opt/scanning"]
