# FreeSwitch Metrics
==============
Part of IMS Dynamics VoIP Metrics

20161030 Sam J. Muller

Description
-----------

VoIP statistics for FreeSwitch. The module json_cdr permits to send full CDR to several IPs. Tornado catch them, then the stats are parsed in real-time then pushed to InfluxDB.

Requirements
------------
- Python 2.7.x
- Celery
- Influxdb
- Supervisor
- Freeswitch with mod_json_cdr

Overview
--------
Using Grafana as GUI:

freeswitch (using mod_json_cdr)

![freeswitch stats](http://195.154.255.170/img/hpbx.png)
