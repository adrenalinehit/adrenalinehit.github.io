---
layout: post
title:  "IOT Temperature Sensor"
date:   2018-09-16 21:00:00 +0100
categories: hacking iot
---

A write up of my raspberry pi home made temperature sensor that logs data to the cloud so that it can be visualised.

# Raspberry Pi based temperature sensor

...reporting live data into a variety of cloud based systems

# Tech

- Raspberry Pi (running ubuntu)
- python ([FluentMetrics](https://github.com/awslabs/cloudwatch-fluent-metrics) in particular)
- GPIO pins and a bit of soldering
- AWS
- Some custom code to log ([Code here](https://github.com/adrenalinehit/HomeTempChecker/blob/main/templogger.py))

# See the Data!

[Live Data Here](https://cloudwatch.amazonaws.com/dashboard.html?dashboard=HomeTemp&context=eyJSIjoidXMtZWFzdC0xIiwiRCI6ImN3LWRiLTQ3NTg4ODk1NjE1MyIsIlUiOiJ1cy1lYXN0LTFfUVFnZHlMWU5hIiwiQyI6Ijd2NDg2bHBkaWs1Z2luMThjbWt2NnJzdWs2IiwiSSI6InVzLWVhc3QtMTo2NjhhZWI5MC00MGIyLTQyMTktYjM0Ny1hZTk5MGJkZWE4ODYiLCJNIjoiUHVibGljIn0=)


# Pictures

![Pin Out]({{"/assets/images/288466632-feba9cf9-f83d-4c81-bfc5-4a6d95dba968.jpg"}})
![AWS logged]({{"/assets/images/templog.png"}})

# Credits

There were many sources of info for this project...

- [instructables](http://www.instructables.com/id/Read-temperature-with-DS18B20-Raspberry-Pi-2/)
- [some cambridge site](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/temperature/)
- [various aws docs](https://aws.amazon.com/serverless/)

