[updated 8-November-2017]

[![KiwiSDR](http://www.kiwisdr.com/ks/Seeed.sample.1.780px.jpg)](http://www.kiwisdr.com/ks/Seeed.sample.1.jpg)

Click image for full size.

[![KiwiSDR](http://www.kiwisdr.com/ks/kiwi-with-headphones.130x170.png)© bluebison.net](http://bluebison.net)

KiwiSDR
=======

Software-defined GPS for the BeagleBone Black
----------------------------------------------------------------------

This repository is a GPS-only version of the full [KiwiSDR](https://github.com/jks-prv/Beagle_SDR_GPS) project.
The GPS design is from Andrew Holme's [Homemade GPS Receiver](http://www.aholme.co.uk/GPS/Main.htm).

Most of the SDR-related C/C++ and Verilog code has been removed to make the overall code easier to understand and compile faster.

A reduced version of the KiwiSDR [admin web interface](http://kiwisdr.local:8073/admin) is used to view the GPS receiver status and satellite Az/El information.

Please refer to the [KiwiSDR](https://github.com/jks-prv/Beagle_SDR_GPS) project for additional documentation in addition to the source code here.

Also possibly of interest: Before the KiwiSDR project started, a terminal based version of the software-defined GPS was published
[here](http://www.jks.com/sdgps/sdgps.html). It uses a commercial FPGA development board, BeagleBone Black and also contains a C-code software simulation of the
Verilog portions of the design.

[![KiwiSDR](http://www.kiwisdr.com/ks/GPS.1.780px.jpg)](http://www.kiwisdr.com/ks/GPS.1.jpg)

[end-of-document]
