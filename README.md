# kde-install-astralinux

запустить ```sudo apt update && sudo apt upgrade && sudo apt install -y plasma-workspace-wayland && sudo reboot``` и ввести пароль (12345678).
компьютер скачает пакеты и перезагрузится. 
После этого в меню ```тип сессии``` выбрать ```plasma(x)```. Исправить переменные GRUB_DEFAULT и GRUB_TIMEOUT в /etc/default/grub на 0 и 1 соответственно: ```sudo nano /etc/default/grub```


#startx running
```
dpkg --configure -a
sudo apt upgrade 
startx 
```