# Installation

Run as root
```
bash <(curl -Ls https://raw.githubusercontent.com/amvmoody/hifi-server/master/setup.sh)
```

# Usage 

- hifi --save : Creates a backup of the live codebase
- hifi --status : give status info on the hifi.service
- hifi --update : Creates a backup of the current live folder then updates the code.
- hifi --restore : restore code from one of the last backups
-  The process is controlled by systemd, to start, restart, stop etc. use systemctl <start,stop,restart,status> hifi.service