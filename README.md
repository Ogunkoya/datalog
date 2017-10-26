# DataLog: a library for interacting with PicoLog hardware
This is a Python library to interface with the [PicoLog ADC 24](https://www.picotech.com/data-logger/adc-20-adc-24/precision-data-acquisition).
It provides a Python class to interact with the `ADC24`, and data structures
to represent its outputs. The `ADC24` is implemented, but the library is
designed to be easily extended for other PicoLog (and potentially non-PicoLog)
hardware.

## Prerequisites
  * Python 3.5+
  * PicoLog ADC 20/24 hardware and driver (`libpicohrdl`)

The PicoLog ADC driver can be obtained from
[PicoLog](https://www.picotech.com/downloads/) and must be installed and working
before using this library.

## Use
The documentation should help to get you started. The main functionality is
implemented in `datalog/adc/hrdl/picolog.py` and this class can be used on its
own. A data server is also provided in `network.py` which is capable of providing
network access to the data recorded by the unit.

## Contributing
I welcome contributions to the codebase - just open a pull request!

Sean Leavey  
https://github.com/SeanDS/
