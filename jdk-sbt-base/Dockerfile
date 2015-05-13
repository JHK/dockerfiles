FROM fedora:21
MAINTAINER Julian Knocke <knocke.julian@gmail.com>

RUN curl -s https://bintray.com/sbt/rpm/rpm > /etc/yum.repos.d/bintray-sbt-rpm.repo
RUN yum install -y -q java-1.8.0-openjdk sbt git
RUN sbt info
