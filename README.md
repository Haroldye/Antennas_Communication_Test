# Antennas_Communication_Test

Antennas communication test with RFM69CW transceiver module and Arduino kits

The RFM69CW is a transceiver module that has been built for inexpensive, short range wireless
network applications that enables you to send data via byte arrays. The benefit of this transceiver
is that it allows control over a range of modulation schemes and bandwidths via simple functions
calls. The RFM69CW has two communication protocols on board; SPI to communicate with a
microcontroller and a wireless module. The transceiver has multiple modes of wireless operation
which include; receiver, transmitter, idle and sleep mode. Inside of receiver mode, the
transceiver is limited to sending and receiving SPI commands, and watching for an interrupt for
when data arrives. Inside of transmit mode, the transceiver is limited to serial SPI
communication and sending data via the antenna port. The final mode of operation is idle, which
allows the transceiver to check an on-chip temperature sensor. It is not recommended to use the
sensor because it has not been calibrated. 

Used keypad as input and then transfer the data to receiver and caculate the power receive.
