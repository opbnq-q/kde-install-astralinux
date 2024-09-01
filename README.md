# kde-install-astralinux

запустить ```sudo apt update && sudo apt upgrade && sudo apt install -y plasma-workspace && sudo reboot``` и ввести пароль (12345678).
компьютер скачает пакеты и перезагрузится. 
После этого в меню ```тип сессии``` выбрать ```plasma(x)```. Исправить переменные GRUB_DEFAULT и GRUB_TIMEOUT в /etc/default/grub на 0 и 1 соответственно: ```sudo nano /etc/default/grub```


# startx running
```
dpkg --configure -a
sudo apt upgrade 
startx 
```

# repos
```
deb https://dl.astralinux.ru/astra/stable/1.7_x86-64/repository-main/     1.7_x86-64 main contrib non-free
 
deb https://dl.astralinux.ru/astra/stable/1.7_x86-64/repository-update/   1.7_x86-64 main contrib non-free
 
deb https://dl.astralinux.ru/astra/stable/1.7_x86-64/repository-base/     1.7_x86-64 main contrib non-free
 
deb https://dl.astralinux.ru/astra/stable/1.7_x86-64/repository-extended/ 1.7_x86-64 main contrib non-free
 
deb https://dl.astralinux.ru/astra/stable/1.7_x86-64/repository-extended/ 1.7_x86-64 astra-ce

#deb https://download.astralinux.ru/astra/stable/1.7_x86-64/uu/last/repository-update/ 1.7_x86-64 main contrib non-free
