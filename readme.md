# New Relic Infrastructure Agent + Nginx Integration without installation

* install nginx server
* enable http status module
* clone repo and execute
```sh
mkdir -p /home/nandha/Workspace/
cd /home/nandha/Workspace/
git clone https://github.com/navayuvan/newrelic-infra.git
cd cd /home/nandha/Workspace/newrelic-infra
clear && NRIA_LICENSE_KEY=MYKEY usr/bin/newrelic-infra -config etc/newrelic-infra.yml
```