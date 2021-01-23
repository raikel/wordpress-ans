wordpress-ans
=============

Configuration files for automate the installation of a WordPress website.

```bash
sudo apt install python3-apt
sudo apt install ansible
git clone https://github.com/raikel/wordpress-ans
cd wordpress-ans
cp group_vars/all_.yml group_vars/all.yml
nano group_vars/all.yml # Edit required variables here
bash deploy.sh
```



