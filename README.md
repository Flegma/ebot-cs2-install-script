# ebot-cs2-install-script
Installation script for eBot that works with CS2. Tested on Ubuntu 20.04 and Ubuntu 22.04 (Hetzner Cloud). 
I will be updating the script with new stuff, this is only first release because many people reached out to me to help them install their own versions.

RUN THE SCRIPT AS ROOT (everything should be pretty straighforward):

```
git clone https://github.com/Flegma/ebot-cs2-install-script.git ebot-cs2-install && cd ebot-cs2-install && chmod +x ebot-cs2-install.sh && ./ebot-cs2-install.sh
```

After everything is installed, you can check the status of the ebot services by running:
```
service ebot-cs2-app status
```
or
```
service ebot-cs2-logs status
```
to check the status respectively. Commands available: service start/stop/restart service_name.

You can also check/edit the cronjobs with:
```
crontab -e
```

TODO: Ask if the installation is on .tld, IP address and/or LAN environment

## Credits
* Julien 'deStrO' Pardons (destro@esport-tools.net)

## Thanks
* Loic Peron (RegnaM)
* Ph3nol
* Fabian 'Basert' Gruber
* Vintric
