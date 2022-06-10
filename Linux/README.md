
# Install Sakai on Linux


We will need JDK-11, Maven-3.6, Mariadb-latest and tomcat-9

```bash
  # install jdk-11
   $ sudo apt-get install openjdk-11-jdk

  # install maven-3.6
   $ sudo apt-get install maven

  # install mariadb-server
   $ sudo apt-get install mariadb-server

```

Setup Mariadb for Sakai to use
```bash
  # start mysql
  $ sudo service mysql start

  # create database(unsecure)
  $ sudo mysql -uroot -Bse  "create database sakaidb  default character set utf8; create user 'sakaiuser'@'localhost' identified by 'sakaipassword';grant all on *.* to 'sakaiuser'@'localhost';
  create user 'sakaiuser'@'127.0.0.1' identified by 'sakaipassword';
  grant all on *.* to 'sakaiuser'@'127.0.0.1';
  flush privileges;"
```

Set paths for java
```bash
export JAVA_HOME=$(readlink -f /usr/bin/javac | sed "s:/bin/javac::")
```
