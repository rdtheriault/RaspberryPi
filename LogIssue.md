Issue with log filling up

Delete logs
```
sudo truncate -s0 auth.log
sudo cp /dev/null auth.log
true |sudo tee auth.log
sudo sh -c 'true > auth.log'


> /var/adm/sylog
```
Turn off logging
```
sudo service rsyslog stop
sudo service rsyslog disable
```
