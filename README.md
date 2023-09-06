# FRIGATE-GARAGE
<b>Mount External HDD:</b></br>
</br>
https://askubuntu.com/questions/125257/how-do-i-add-an-additional-hard-drive</br>
<br>
sudo mkdir /nvr-hdd<br>
sudo nano /etc/fstab<br>
/dev/sdb1    /nvr-hdd    ext4    defaults    0    0<br>
sudo mount /nvr-hdd<br>
<br>
<br>
<br>
<b>Docker Compose:</b></br>
https://linux.how2shout.com/install-and-configure-docker-compose-on-ubuntu-22-04-lts-jammy/<br>
<br>
<br>
<br>
<b>Frigate:</b></br>
sudo mkdir /home/tom/frigate && cd /home/tom/frigate<br>
sudo docker-compose -f frigate.yml up
