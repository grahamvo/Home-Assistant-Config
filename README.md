#Home Assistant Setup


##Getting it Going

1. Ssh into Pi `$ ssh 192.168.0.105`

2. Switch to homeassistant user `$ sudo su -s /bin/bash homeassistant`

3. Switch to virtual environment `$ source /srv/homeassistant/homeassistant_venv/bin/activate`
4. `$ hass`

>###Note:
> - If Home Assistant is already running use `$ ps -ef | grep "hass"` to find the PID and then run `$ kill <PID>` to stop it
>
>
> - In order to run Home Assistant in the background use the command `$ nohup hass &`
