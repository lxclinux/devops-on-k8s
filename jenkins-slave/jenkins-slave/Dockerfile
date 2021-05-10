FROM 172.20.48.53/devops/jnlp-slave:latest

ADD . /etc/apt/
RUN apt-get update && apt-get install maven -y

RUN /bin/cp /usr/share/zoneinfo/Asia/Shanghai /etc/localtime && echo 'Asia/Shanghai' >/etc/timezone


