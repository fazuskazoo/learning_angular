

Installing nodejs on Ubuntu 20

`cat /etc/os-release`
```
sudo apt intall nodejs

curl -sL https://deb.nodesource.com/setup_18.x | sudo -E bash -

sudo apt-get purge nodejs

sudo apt-get install --only-upgrade nodejs

rm -rf /usr/local/lib/node_modules/

sudo rm -rf /usr/local/lib/node_modules/


```
