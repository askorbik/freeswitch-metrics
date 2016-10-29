# VOIP METRICS
==============
IMS Dynamics VoIP Metrics - FreeSwitch + OpenSips

20160205 sam j. muller

Description
-----------

voip statistics for freeswitch and opensips
stats are parsed in real-time using Tornado then pushed to influxdb

Requirements
------------
- Python 2.7.x
- Celery
- Influxdb
- Supervisor
- Freeswitch with mod_json and mod_curl
- OpenSips with module fifo, xmlrpc or unixsock


Overview
--------
Using Grafana as GUI:

opensips dialogs number (active + early states)

![opensips dialogs](http://195.154.255.170/img/cscf.png)

opensips release causes (using redis for opensips "onreply" log storage)

![opensips releases](http://195.154.255.170/img/releases_causes.png)

freeswitch (using mod_json_cdr)

![freeswitch stats](http://195.154.255.170/img/hpbx.png)
