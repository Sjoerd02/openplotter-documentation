What is OpenPlotter?
=======
![OpenPlotter logo](openplotter500x300.png)

There are people who buy boats but some people build them, why not build your own electronics? **OpenPlotter** is a combination of software and hardware to be used as navigational aid on small and medium boats. It works on ARM computers like the [Raspberry Pi](https://www.raspberrypi.org/) and is open-source, low-cost and low-consumption. Its design is modular, so you just have to implement what your boat needs. Do it yourself.

## Features

* **Chartplotter**. With [OpenCPN](http://opencpn.org), a navigation software with useful plugins.
* **Weather Forecast**. Download and visualize GRIB files with [zyGrib](http://www.zygrib.org).
* **NMEA-0183 Multiplexer**. Multiplex data inputs from any number of serial lines and network interfaces and send to any number of outputs.
* **NMEA Inspector**. Check the data traffic to avoid conflicts and overlaps between sources.
* **NMEA WiFi Server**. Share NMEA data with laptops, tablets and phones or connect to internet on port through the same device.
* **Remote Desktop**. Access to OpenPlotter desktop from the cockpit through your mobile devices.
* **SDR-AIS**. Receive and decode AIS with cheap DVB-T dongles. Calibration tools Included.
* **Magnetic Variation**. Calculate magnetic variation for date and position.
* **Electronic Compass**. Calculate magnetic heading with an IMU sensor. Tilt compensated. Calibration tools Included.
* **True Heading**. Calculate true heading from magnetic variation and magnetic heading.
* **True Wind**. Calculate true wind from apparent wind and either speed through water (speed log) or speed over ground (GPS).
* **Barograph and Thermograph**. From IMU sensor. Save logs and display graphs to see trends.
* **System Time Tools**. Set the system time from NMEA data and set the time zone easily.
* **GPSD**. Configure [GPSD](http://www.catb.org/gpsd/).
* **Startup Programs**. Select some program parameters to launch at start.

![OpenPlotter desktop](openplotter.png)