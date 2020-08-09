# XBee-Based-Serial-Communication-using-Arduino

A set of codes that aids to accomplish the simple task of serial communication using Digi International's XBee wireless radio modules.


## Getting Started

#### Serial communication
An XBee module can operate as a stand-alone device or it can be attached to an intelligent device. For example, you can place several battery-powered XBee modules in remote locations to gather data such as temperature, humidity, light, or liquid level.

When operating as a stand-alone device, an XBee module simply sends sensor data to a central node.
When an XBee module is connected to an intelligent device (such as a computer, Arduino, or Raspberry Pi), it uses serial communication:
The intelligent device sends data through the serial interface to the XBee module to be transmitted to other devices over the air.
The XBee module receives wireless data from other devices, and then sends the data through the serial interface to the intelligent device.
The XBee modules interface to a host device such as a microcontroller or computer through a logic-level asynchronous serial port. They use a UART for serial communication with those devices.
<a href="https://github.com/firebolt7/XBee-Based-Serial-Communication-using-Arduino-"><img src="https://www.digi.com/resources/documentation/Digidocs/90001456-13/resources/images/rf_kits/dwg_xbee_serial_connection_700x166.png" title="BASS" alt="BASS"></a>

### Prerequisites

#### Hardware Requirements
- 1 x Arduino Uno
- 2 x  XBee Pro S2C modules (any other model can be used)
- 1 x Xbee explorer board (optional)
- 1 x Xbee Breakout board (optional)
- USB cables

#### Software Requirements

- Arduino Software (IDE)


## Contributing

Please read [CONTRIBUTING.md](https://) for details on our code of conduct, and the process for submitting pull requests to us.
 

## Authors

* **BS** - *Initial work* - [firebolt7](https://github.com/firebolt7)

See also the list of [contributors](https://) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* [Digi](https://www.digi.com/)
* BASS 
