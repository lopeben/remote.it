# remote.it
Remote it client files
---


Troubleshooting.

1. Make "auto-install.sh" executable
chmod +x auto-install.sh

2. In case of Curl Error like this:

Server certificate verification failed. CAfile: /etc/ssl/certs/ca-certificates.crt CRLfile: none

Fix: Check system date time! 
install ntp: sudo apt-get install ntp -y
