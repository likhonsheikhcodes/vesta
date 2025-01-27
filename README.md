[Vesta Control Panel](http://vestacp.com/)
==================================================

Vesta is back under active development as of 25 February 2024. We are commited to open source, and will engage with the community to identify the new roadmap for Vesta. Stay tuned!

[![Join the chat at https://gitter.im/vesta-cp/Lobby](https://badges.gitter.im/vesta-cp/Lobby.svg)](https://gitter.im/vesta-cp/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

* Vesta is an open source hosting control panel.
* Vesta has a clean and focused interface without the clutter.
* Vesta has the latest of very innovative technologies.
# Connect to your server as root via SSH

ssh root@your.server

2
# Download installation script

curl -O https://vestacp.com/pub/vst-install.sh

3
# Run it

bash vst-install.sh --nginx yes --apache yes --phpfpm no --vsftpd no --proftpd no --exim no --dovecot no --spamassassin no --clamav no --named yes --iptables no --fail2ban no --softaculous yes --remi no --quota no --mysql yes --postgresql no --hostname likhon.dev --email system@likhon.dev --port 5454 --password
How to install (2 step)
----------------------------
Connect to your server as root via SSH
```bash
ssh root@your.server
```

Download the installation script, and run it:
```bash
curl https://vestacp.com/pub/vst-install.sh | bash
```

How to install (3 step)
----------------------------
If the above example does not work, try this 3 step method:
Connect to your server as root via SSH
```bash
ssh root@your.server
```

Download the installation script:
```bash
curl -O https://vestacp.com/pub/vst-install.sh
```
Then run it:
```bash
bash vst-install.sh
```

License
----------------------------
Vesta is licensed under  [GPL v3 ](https://github.com/outroll/vesta/blob/master/LICENSE) license

