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
- Gunicorn
- Influxdb
- Nginx
- Supervisor
- Freeswitch with mod_json and mod_curl
- OpenSips with module fifo, xmlrpc or unixsock

Schema
------
```
image here
```

Overview
--------
Using Grafana
```
image here
```
