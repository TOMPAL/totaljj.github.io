# DB
```bash
yum -y install http://dev.mysql.com/get/mysql-community-release-el7-5.noarch.rpm
yum -y install mysql-community-server
systemctl start mysqld
systemctl enable mysqld
mysql
reboot
mysql

my.cnf 변경
systemctl restart mysqld

​myslq -uroot ?
```

#접속방법
```
mysql -uchatbot -p{pwd}
```
