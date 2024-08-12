FROM ghcr.io/almalinux/9-base:9.4

RUN dnf update -y

RUN dnf update -y && \
    dnf install -y selinux-policy-targeted \
                   policycoreutils \
                   policycoreutils-devel \
                   setools-console \
                   setroubleshoot
