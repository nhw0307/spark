스파크 완벽 가이드 
=================

## 1. 설치

  #### 1.docker 이용한 설치
     
     1. docker 설치 
         yum -y install java-1.8.0-openjdk
         yum -y install java-1.8.0-openjdk-devel
         yum -y install wget
         
   ##### * docker 설치
     yum install -y yum-utils device-mapper-persistent-data lvm2
      yum-config-manager --add-repo https://download.docker.com/linux/centos/docker-ce.repo
      yum install docker-ce -y
   
   ##### * docker-compose 설치
      curl -L "https://github.com/docker/compose/releases/download/1.22.0/docker-compose-$(uname -s)-$(uname -m)" -o 
      /usr/local/bin/docker-compose
      chmod +x /usr/local/bin/docker-compose

   ##### * docker 실행
      systemctl start docker
     1.https://hub.docker.com 계정 생성 
     1.docker login docker.io
     1.계정 로그인
