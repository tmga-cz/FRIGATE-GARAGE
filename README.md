# FRIGATE-GARAGE
</br>
https://askubuntu.com/questions/125257/how-do-i-add-an-additional-hard-drive</br>
<br>
sudo mkdir /nvr-hdd<br>
sudo nano /etc/fstab<br>
/dev/sdb1    /nvr-hdd    ext4    defaults    0    0
<br>

<b>terminal:</b></br>
sudo docker-compose -f frigate.yml up
