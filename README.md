# Окружения для разработки приложений на Angular

Настройки Vagrant и плаэйбуки Ansible для того, чтобы быстро развернуть окружение для разработки приложений на Angular.

## Системные требования

 * Ubuntu 16.04 64-bit
 * Vagrant 1.8.6
 * VirtualBox 5.1
 * Ansible 2.3.0
 * Git 2.7.4

## Использование

Выполнить из директории ~/projects/angular/dev
```bash
sudo mount -t cifs -o uid=ilya,gid=ilya,password=vagrant,username=vagrant,iocharset=utf8,sec=ntlm //192.168.36.10/www ./www
```
чтобы примонтировать к хостовой машине директорию с исходным кодом с виртуальной машины по SMB.