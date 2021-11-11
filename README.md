On the router (alpine):

* Name resolver cache : unbound
* time server : chrony

In containers:

* SMTP relay : postfix
* HTTP reverse proxy : nginx
* HTTP proxy : squid + privoxy + tor
* repositories mirror : cron + rsync + lighttpd
* git : gitlab
* CI : jenkins
* influxDB
* grafana
* ...
