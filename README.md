This is a Gen2 UHF RFID reader, forked from https://github.com/nikosl21/Gen2-UHF-RFID-Reader.

The aim of the project is to extend the functionality of the RFID reader.

In order for the GnuRadio companion flowgraph to work, the GRC needs to be run with the most favourable level of niceness (which affects process scheduling). To run gnuradio-companion (in this example fish syntax is used):

env GR_SCHEDULER=STS nice -n -20 gnuradio-companion
