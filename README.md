# monolithic-rpi
(Unofficial RPI Version) - A monolithic lancache service capable of caching all CDNs in a single instance

# Important steps
+ If using Pi Wifi, put dtoverlay=pi3-enable-wifi at the end of your /boot/config.txt regardless if it's a pi3/4. I'm having some issues where Wifi doesn't play nice with the jwilder proxy.
+ In the .env, modify LANCACHE_IP and DNS_IP to be the IP on the interface you want to expose this on. 0.0.0.0 might work but I recommend a single interface.

## Actions
This repo uses Github Actions. Click the Actions tab to view the script output.

The docker images can be found on my docker hub account.


## Manually triggered runs (Dates I decide to rerun the script and update the containers)
+ 2/1/2020 - I
