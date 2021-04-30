# d4-nifi-templates
This repository holds nifi templates used to interact with d4.


# d4-grok-logs
This folders contains two templates:
- d4-grok-logs.xml is used to feed `analyzer-d4-logs`
- d4-grok-geo-logs.xml is used to feed `analyzer-d4-logs` and `analyzer-d4-pewpew` (this one needs a maxmind geolite database file not provided here)

![Screenshot of the flow in NiFi](https://github.com/D4-project/d4-nifi-templates/blob/master/d4-grok-logs/analyzer-d4-log-nifi.png)
