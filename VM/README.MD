## Crear VM con LocalStack:

IP address: 10.252.7.169


## Instalacion de Localstack  script de Ansible : 
Dependencias:
java-1.8.0-openjdk
java-1.8.0-openjdk-devel
Maven 3.6
epel-release
python3.6
python3.6-devel
gcc
git
npm

abrir los puertos :
sudo firewall-cmd --zone=public --add-port=4500-46000/tcp --permanent
sudo firewall-cmd --zone=public --add-port=8080/tcp --permanent
