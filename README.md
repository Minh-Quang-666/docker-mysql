mysql-docker-compose
A docker-compose sample to start MySQL database.

How to use?
Clone the project:
  $ git clone https://github.com/Minh-Quang-666/docker-mysql.git
Start MySQL via docker-compose in terminal:
  $ cd ./mysql-docker-compose
  // Please add path "/usr/local/var/mysql" as the sharing folder for your Docker before
  $ docker-compose up -d
Connect to the MySQL server:
  # Enter in the docker container
  $ docker exec -it mysql bash
  # Connect to mysql service, and enter in password 12345678
  $ mysql -h 127.0.0.1 -u root -P 3306 -p
Other commands maybe needed:
  # you can stop service by the command
  $ docker stop mysql
  # you can start service by the command
  $ docker start mysql
  # you can restart service by the command
  $ docker restart mysql
