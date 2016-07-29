FROM datadoglt/php70

RUN yum -y update systemd

RUN yum install --enablerepo=remi,remi-php70 -y php-mysql php-gd php-common php-curl && yum clean all
