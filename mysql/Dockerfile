FROM jianzi/base
MAINTAINER Jian Jiang <jian0307@icloud.com>

#install mysql
ADD ./src/mysql-5.5.42.tar.gz /data/install
ADD ./scripts/install.sh /data/install/install.sh

RUN chmod 755 /data/install/install.sh
RUN /data/install/install.sh

#RUN groupadd mysql
#RUN useradd -g mysql mysql
#USER mysql

EXPOSE 3306
