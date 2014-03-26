jbug-vagrant
============

JBoss 유저그룹에서 vagrant를 주제로 발표

slipp cast - http://asciinema.org/a/8441


slipp 소개

공통작업 : run java application, 포트 포워딩
run java application
git clone https://github.com/SpringSource/spring-petclinic
cd spring-petclinic
소스코드 설명이 필요한 경우
sudo apt-get install tree 
tree .
sudo mvn tomcat7:run
port forwarding : 9966 -> 8888
config.vm.network :forwarded_port, guest: 9966, host: 8888

http://localhost:8888/petclinic/
