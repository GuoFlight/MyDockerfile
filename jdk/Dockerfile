FROM centos:7

ADD jdk-8u162-linux-x64.tar.gz /usr/local/java/ 
RUN echo "export JAVA_HOME=/usr/local/java/jdk1.8.0_162" >> /etc/bashrc && \
	echo "export PATH=\$PATH:\$JAVA_HOME/bin" >> /etc/bashrc
	
