FROM python:3.8

RUN ln -fs /usr/share/zoneinfo/Asia/Shanghai /etc/localtime \
		&& dpkg-reconfigure -f noninteractive tzdata \
		&& mkdir ~/.pip
COPY pip.conf /root/.pip
