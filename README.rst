

Analog to Digital Converter (ADC)
#################################

Overview
********
This is a simple ADC program.

The ADC peripheral converts a continuous analog voltage to a discrete
digital number. The application samples and displays the output from a
simple variable voltage source once per second.

Requirements
************

The following development board:

  * |nRF9160DK|

The board hardware must have a sensor or a variable resistor connected
to analog pin AIN0.

Building and Running
********************
This sample can be built for multiple boards, in this example we will build it
for the nrf9160dk_nrf9160ns board:

Running:
After flashing, the sample starts to convert the analog input as described above.
It also prints information to the board's console.

Sample Output
=============

*** Booting Zephyr OS build v2.4.99-ncs2  ***
nrf91 saadc sampling AIN0 (P0.13)
Example requires secure_boot to have SAADC set to non-secure!
If not; BusFault/UsageFault will be triggered
ADC raw value: 301
Measured voltage: 1066.71 mV
ADC raw value: 441
Measured voltage: 1552.94 mV
ADC raw value: 582
Measured voltage: 2051.13 mV
ADC raw value: 860
Measured voltage: 3015.07 mV