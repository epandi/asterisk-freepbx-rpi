# FreePBX on Docker (Raspberry Pi)

FreePBX container image for running a complete Asterisk server.

With this container you can create a telephony system in your office or house with integration among various office branches and integration to external VOIP providers with features such as call recording and IVR (interactive voice response) Menus.

### Image includes

 * Debian 9 Stretch with NodeJS 12
 * PHP 5.6
 * Legacy Debian Jessie MySQL ODBC Connector
 * Asterisk 16-current
 * Freepbx 15.0.15.3
 * Opensource G729 v1.0.4
 * Modules: IVR, Time Conditions, Backup, Recording, callrecordings, conferences, dashboard, featurecodeadmin, infoservices, logfiles, msuic, sipsettings, voicemail, certman, userman, pm2, ucp
 * Automatic backup script
 * Container size: approx 2.3GB

### Run FreePBX image

* Run ```docker-compose up -d```
* Open web admin panel at your raspberry pi's ip-address


### Credits

* https://github.com/flaviostutz/freepbx
* https://github.com/tiredofit/docker-freepbx
* https://tecadmin.net/install-php-debian-9-stretch/
* https://www.raspberrypi.org/forums/viewtopic.php?p=1229991&sid=103f6ac150a6194bbd990647ddd50a6f#p1229991
* https://community.freepbx.org/t/ucp-upgrade-error/58273/4
