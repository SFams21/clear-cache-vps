[![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/colored.png)](#table-of-contents)
 
<p align="center">
<a href="https://SFams21"><img title="Author" src="https://img.shields.io/badge/Author-SFams21-red.svg?style=for-the-badge&logo=github"></a>
</p>


 > **Warning**: mau make? jangan lupa star

 > **Note**: INI TOOLS UNTUK MENGHAPUS CACHE VPS (ONLY UBUNTU)
 

EROR? CHAT: [KLIK DISINI](https://wa.me/6289637959432)

## INSTALL WITH UBUNTU

[ INSTALLING UBUNTU ]

```bash
apt-get update && apt-get upgrade -y
ls
git clone https://github.com/SFams21/clear-cache-vps.git
cd clear-cache-vps
chmod +x cleaner-tools.sh
sh cleaner-tools.sh

```
---------

[ USE COMMAND FROM TERMINAL ]

```bas
echo 1 > /proc/sys/vm/drop_caches
echo 2 > /proc/sys/vm/drop_caches
echo 3 > /proc/sys/vm/drop_caches
script otomatis flush cache:

# crontab -e
0 * * *  * sync; echo 3 > /proc/sys/vm/drop_caches
perintah diatas akan menjalankan perintah sync; echo 3 > /proc/sys/vm/drop_caches setiap 1 jam

untuk memeriksa cache memory

free -m

```
---------
