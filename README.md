jbug-vagrant
============

> JBoss 유저그룹에서 "vagrant - 활용"이란 주제로 발표

[![](http://farm8.staticflickr.com/7202/13468974154_fd250c6e87_o_d.jpg)](http://www.flickr.com/photos/dkkang1018/13468974154/)

* facebook : http://goo.gl/LLlcb0
* flickr : http://goo.gl/NXWvVY

## screen recording cast by asciinema

* Act1 : https://asciinema.org/a/8441
* Act2 : https://asciinema.org/a/8438
* Act3 : https://asciinema.org/a/8306

### bonus 

* zsh-with-vagrant : https://asciinema.org/a/8462


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
