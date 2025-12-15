# addon configs
## mosquitto
### config the addon
``` yaml
logins:
  - username: mqtt
    password: mqtt
require_certificate: false
certfile: fullchain.pem
keyfile: privkey.pem
customize:
  active: true
  folder: mosquitto
```
### add another broker
inside /share/mosquitto
add the following files:
* isrgrootx1.pem
* beidge.conf

