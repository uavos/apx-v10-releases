#### New Features
* Blackbox reader
* WPT index in status instrument (closes [`issue 47`](http://github.com/uavos/apx-releases/issues/47))
* map with tiles is available to plugins via JS `ui.mapbase`
* MHX RS4xx interface (closes [`issue 33`](http://github.com/uavos/apx-releases/issues/33))

#### Bug Fixes
* telemetry auto recorder (closes [`issue 53`](http://github.com/uavos/apx-releases/issues/53))
* AHRS service menu commands (closes [`issue 48`](http://github.com/uavos/apx-releases/issues/48))
* limit bandwidth <10Hz of mandala value updates sent to datalink (closes [`issue 54`](http://github.com/uavos/apx-releases/issues/54))

#### Performance Enhancements
* qwt lib upgrade for telemetry display (closes [`issue 51`](http://github.com/uavos/apx-releases/issues/51))
* mission view optimizations

#### Comments
**feat: MHX RS4xx interface**

To connect `mhx` serial interface `RS4xx` to a PC, it must be configured as `MANDALA` or `DOWNLINK` serial port. Moreover, when the `mhx` function is selected as `gcu` - the RS232 port can not be used as protocols driven virtual serial port, because it always acts as bus interface for node locking protection. `RS232` port, when it is used to connect to a PC is always have default baud rate **460800**.