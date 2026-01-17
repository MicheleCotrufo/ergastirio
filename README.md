# Ergastirio

```Ergastirio``` is a Python GUI interface which facilitates collecting data from different instruments commonly used in optics and physic labs. It allows to seamlessly connect different tools with each others, running automatized measurements with multi-variable parameter sweeps, and plotting data in real time. It is built modularly. Each instrument has its own interface/library which needs to be installed separately. Each instrument interface also acts as a standalone software, i.e., it can be run independently from ```Ergastirio``` to control only a specific tool.

## List of Equipment currently supported by Ergastirio

| Vendor | Model | Description | Package name  |
| --- | --- | --- | 
| Thorlabs |  PM100A, PM100D | Powermeter console | pyThorlabsPM100x | 
