vice-roms
=========

I became tired of manually copying over the Commodore ROMs whenever I decide to go for a fresh reinstall, so that's why I set up this repo.

Usage
-----
```bash
cd /usr/local/share/vice
sudo git init
sudo git remote add origin https://github.com/asig/vice-roms.git
sudo git fetch origin
sudo git checkout -b master --track origin/master
```
