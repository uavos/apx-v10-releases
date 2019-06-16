#### New Features
* ADC bias and multiplier configuration parameters (closes [`issue 27`](http://github.com/uavos/apx-releases/issues/27))
* Shiva gimbal default control mode - 'speed' option (closes [`issue 25`](http://github.com/uavos/apx-releases/issues/25))
* GCS overridable main layout QML (closes [`issue 10`](http://github.com/uavos/apx-releases/issues/10))
* GCS Map support for external tile providers (closes [`issue 11`](http://github.com/uavos/apx-releases/issues/11))

#### Bug Fixes
* GCS mission auto-shot by distance (closes [`issue 13`](http://github.com/uavos/apx-releases/issues/13))

#### Comments
`feat: ADC bias and multiplier configuration parameters (closes [`issue 27`](http://github.com/uavos/apx-releases/issues/27))`  
Value written to `bind` variable equals `adc_voltage * mult + bias`. MCU reboot is needed when configuration changes.

`fix: GCS mission auto-shot by distance (closes [`issue 13`](http://github.com/uavos/apx-releases/issues/13))`  
Auto shot start/stop is controlled now via Waypoint/Actions/Shot setting. When started, the Auto Shot distance must be non-zero.

`feat: GCS overridable main layout QML (closes [`issue 10`](http://github.com/uavos/apx-releases/issues/10))`  
`GroundControl.qml` source file is included in SDK and can be put in `Documents/UAVOS/Plugins` to override and customize the main window contents. The plugins pathh is now in search paths for QML engine.

`feat: GCS Map support for external tile providers (closes [`issue 11`](http://github.com/uavos/apx-releases/issues/11))`  
The provider can be selected through `Tools/Tile Loader`. The GCS plugin subclassing QGeoServiceProviderFactory could be loaded from `Documents/UAVOS/Plugins` and provide Map tiles when selected in Tools menu.