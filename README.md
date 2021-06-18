# PLUTO example repository
This repository is intended to show how to configure the Analog Devices PLUTO SDR to recieve samples and to transmit sample IQ data.  The code is a simple example of how to interface to the PLUTO API in both the Windows OS and Linux OS without the use of GNU Radio.

## Dependencies

The code in this repository has the following dependecies

1. [CMake 2.8.12+](https://cmake.org/download/ )
2. [davemers0160 common code repository](https://github.com/davemers0160/Common )
3. [Analog Devices Pluto Driver & API](https://wiki.analog.com/university/tools/pluto )
4. [ArrayFire](https://www.arrayfire.com/ )

## PLUTO Driver Installation
The Analog Devices wiki page is not the most organized site for the Pluto.  Depending on which link you follow there are two different driver installation instructions.



### Windows Installation
Download and install the latest release of [LibIIO](https://github.com/analogdevicesinc/libiio/releases ) from the Analog Devices Github page.


## Repository Breakdown

### rx_example
This folder contains the project code that illustrates the example code to configure the BladeRF to recieve samples and display them using the ArrayFire library. 

### tx_example
This folder contains the project code that illustrates the example code to configure the BladeRF to transmit FSK samples.

### common
This folder contains the project code that is shared between all of the projects.
