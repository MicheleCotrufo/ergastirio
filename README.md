# Ergastirio

```Ergastirio``` is a Python GUI interface which facilitates collecting data from different instruments commonly used in optics and physic labs. It allows to seamlessly connect different tools with each others, running automatized measurements with multi-variable parameter sweeps, and plotting data in real time. It is built modularly. Each instrument has its own interface/library which needs to be installed separately. Each instrument interface also acts as a standalone software, i.e., it can be run independently from ```Ergastirio``` to control only a specific tool.

## List of Equipment currently supported by Ergastirio

| Vendor | Model | Description | Package name  |
| --- | --- | --- | --- | 
| Thorlabs |  PM100A, PM100D | Powermeter console | [pyThorlabsPM100x](https://github.com/MicheleCotrufo/pyThorlabsPM100x) | 
| Thorlabs |  Any APT-compatible device | Control any motorized element compatible with APT protocol | [pyThorlabsAPT](https://github.com/MicheleCotrufo/pyThorlabsAPT) | 
| Thorlabs | TC300 | Heater Temperature Controller | [pyThorlabsTC300](https://github.com/MicheleCotrufo/pyThorlabsTC300) | 
| SRS | Models testes: SR865A, SR844, SR810 | Lock-in Amplifiers | [pySRSLockin](https://github.com/MicheleCotrufo/pySRSLockin) | 
| Ocean Optics | Any model supported by [pyseabreeze (usb)](https://github.com/ap--/python-seabreeze) | Spectrometer| [pyOceanopticsSpectrometer](https://github.com/MicheleCotrufo/pyOceanopticsSpectrometer) | 

## Installation

It is highly recommended to install in a dedicated environment.
Use the package manager pip to install,

```bash
pip install ergastirio
```
This will install ```ergastirio``` together with all required librariesspecified in the ```requirements.txt``` files.

To test that the installation is succesful, run the command ```ergastirio``` from any command prompt. This will initialize the graphical interface for an empty experiment.
