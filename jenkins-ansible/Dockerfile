FROM jenkins/jenkins

USER root

RUN apt-get update
RUN apt-get install -f
RUN apt-get -y install python3 python3-pip ansible
RUN pip3 install ansible

USER jenkins


