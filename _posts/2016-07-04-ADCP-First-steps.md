---
title:  "Acoustic Doppler Current Profiler: First steps connecting and testing on `BBTalK`."
author: Uggo & Saulo
excerpt: "ADCPs."
categories:
  - Data
tags:
  - instrumentation
  - data analysis
comments: true
---

# Acoustic Doppler Current Profiler (ADCP)

There are a large source of information available on the web about ADCPs and its functionalities. Our intention here is to to provide a quick and basic introduction on the operation of this instrument.

For more information about ADCPs, you should visit the <a href="http://www.rdinstruments.com/">Teledyne RD Instruments</a> page.

If you are working with a Vessel Mounted (VM) ADCP, we refer to <a href="http://currents.soest.hawaii.edu/docs/doc/">UHDAS website</a>.

## ADCP first connection

The first step after the proper energy and data cable connection is to open the BBTalk manufacturer software and test the communication with the instrument.

### 1) When you first open BBTalk, you may see the following screen:

<img src="images/bbtalk1.jpg" alt>

![BBTalk1](images/bbtalk1.jpg "BBTalk first screen")
*BBTalK first screen.*

![My helpful screenshot]({{ /home/wind/Public/OceanNimbus/oceannimbus/ }}/images/bbtalk1.jpg)

[![alt text](/home/wind/Public/OceanNimbus/oceannimbus/images/bbtalk1.jpg)](http://blogs.agu.org/wildwildscience/2016/06/08/world-oceans-day-little-celebrate/)
*Photo credit:*

At this point, you have to indicate the model and the COM port.

### 2) Configuration of *Baud rate*, *Parity*, *stop Bits*, *Flow Control*:

![BBTalk2](./figures/bbtalk2.jpg "BBTalk second screen")
*Connection configuration of the ADCP*

### 3) Starting ADCP command options on *BBTalk*:

![BBTalk3](./figures/bbtalk3.jpg "BBTalk 3rd screen")
*Screen showing the commands to be sent to the instrument.*

### 4) Now, the sensor can be tested through BBTalk. The first test is the communication test:
It is easily performed by sending a *Break* by clicking on the button `B`:

![BBTalk4](./figures/bbtalk4.jpg "BBTalk 4th screen")
*The first communication with the instrument being performed.*

### 5) The next test will be if the instrument is operating properly:

The command to check the main parts of the ADCP as well as the signal path is the `PA`. This command checks the *CPU*,*DSP*, the *System* itself, the *storage devices* and the *sensor*:

![BBTalk5](./figures/bbtalk5.jpg "BBTalk 5th screen")
*`PA` test to check the equipment functionality.*

### 6) Attitude test: Heading (compass), Pitch and Roll.

The command `PC2` is sent to check *Heading*,*Pitch* and *Roll*. While performing this test, one can move the sensor in it's 3 axis and check if the output values are changing.

![BBTalk6](./figures/bbtalk6.jpg "BBTalk 6th screen")
*`PC2` test showing the movements of the sensor.*
