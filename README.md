Copy script to /usr/local/bin/ssh-keyput
chmod a+x /usr/local/bin/ssh-keyput

**Add SSH key to REMOTE host where VPS needs to migrate.

ssh-keyput 192.168.1.1

Migrate VPS

**vzmigrate --online 192.168.1.1 102

192.168.1.1-Remote host
102 CTID to migrate to remote host

