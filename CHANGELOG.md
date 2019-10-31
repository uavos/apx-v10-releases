# Changelog

All notable changes to **APX Software** will be documented in this file.  
For more information refer to [docs.uavos.com](http://docs.uavos.com).

## [Version 10.2.115](https://github.com/uavos/apx-releases/releases/tag/10.2.115) (10/31/19)

> Branch: `master`  
Date: `10/31/19 14:23:44`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/681626cec990a05352758e6d78b8a3c406d84998...e1402f7979fdf17eb50026006074e597de028f0d)

### New Features
* language translations support (closes [`issue 80`](http://github.com/uavos/apx-releases/issues/80))
* Linux AppImage auto update (closes [`issue 28`](http://github.com/uavos/apx-releases/issues/28))
* Fail safe plugins loading

### Documentation Changes
* updates about translations
* main window customization instructions

## [Version 10.2.75](https://github.com/uavos/apx-releases/releases/tag/10.2.75) (10/29/19)

> Branch: `master`  
Date: `10/29/19 12:33:49`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/c07084567035dfbd2d5e0a58840fc4e62bb23bc7...681626cec990a05352758e6d78b8a3c406d84998)

### New Features
* Telemetry database maintenance, empty trash, reset cache, etc.
* Instruments container for plugins
* mission edit tools and UAV commands UI improvements
* camera gimbal target display on map
* map scale sign clickable to change view mode to show distance between map clicked points
* travel path distance display and map info area (closes [`issue 71`](http://github.com/uavos/apx-releases/issues/71))
* global application progress display

### Bug Fixes
* terminal auto scroll updates (closes [`issue 67`](http://github.com/uavos/apx-releases/issues/67))
* Pawn compiler enum values definitions

### Optimizations
* GCS layout refactoring
* Qt 5.13.1 upgrade

## [Version 10.1.229](https://github.com/uavos/apx-releases/releases/tag/10.1.229) (09/24/19)

> Branch: `release`  
Date: `09/24/19 15:15:19`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/4c135947f62cd012c7f2b0a9eeabe3d8df904ee9...c07084567035dfbd2d5e0a58840fc4e62bb23bc7)

### New Features
* Blackbox plugin support import from file
* GCS plugins dependency parameters to control load sequence (closes [`issue 65`](http://github.com/uavos/apx-releases/issues/65))

### Bug Fixes
* Blackbox NAV AP10 refactoring
* xplane moved installation path fix

## [Version 10.1.218](https://github.com/uavos/apx-releases/releases/tag/10.1.218) (09/19/19)

> Branch: `release`  
Date: `09/19/19 10:00:19`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/fa0c0bc87969d04f2408c5013e1cea406bd6c5b0...4c135947f62cd012c7f2b0a9eeabe3d8df904ee9)

### Bug Fixes
* default data sets for GCS first time launch (closes [`issue 63`](http://github.com/uavos/apx-releases/issues/63))

### Documentation Changes
* Docs site updates (simulation)

## [Version 10.1.216](https://github.com/uavos/apx-releases/releases/tag/10.1.216) (09/18/19)

> Branch: `release`  
Date: `09/18/19 08:19:15`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/4afcf63a93ecb86a3816941a3ab7f78e28348c3d...fa0c0bc87969d04f2408c5013e1cea406bd6c5b0)

### New Features
* total travel distance display in telemetry reader

### Bug Fixes
* possible segfault fixes on telemetry load

### Performance Enhancements
* vehicle travel path display improvements
* Telemetry loader no freeze UI

## [Version 10.1.199](https://github.com/uavos/apx-releases/releases/tag/10.1.199) (09/09/19)

> Branch: `release`  
Date: `09/09/19 17:11:50`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/59017cfaa101715760856da335e46b44088ccf5c...4afcf63a93ecb86a3816941a3ab7f78e28348c3d)

### New Features
* UAV travelled path display on map

### Bug Fixes
* Linux version video plugin (closes [`issue 52`](http://github.com/uavos/apx-releases/issues/52))

## [Version 10.1.190](https://github.com/uavos/apx-releases/releases/tag/10.1.190) (09/03/19)

> Branch: `release`  
Date: `09/03/19 22:02:49`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/00b472962d2ef062b4ee82aa903b0dc27b430fa1...59017cfaa101715760856da335e46b44088ccf5c)

### New Features
* telemetry reader geo path display on map (closes [`issue 60`](http://github.com/uavos/apx-releases/issues/60))

### Bug Fixes
* `revert` button title for nodes
* VPN support config files fix

## [Version 10.1.185](https://github.com/uavos/apx-releases/releases/tag/10.1.185) (08/31/19)

> Branch: `release`  
Date: `08/31/19 19:37:36`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/3ee0044b7f75bdbaf201d31c32a054210e688624...00b472962d2ef062b4ee82aa903b0dc27b430fa1)

### New Features
* LOS distance indicator in `status` instrument
* warnings sounds in `numbers`
* GCS warnings panel (closes [`issue 59`](http://github.com/uavos/apx-releases/issues/59))
* datalink remotes in status widget
* `numbers` instrument re-ordering of items
* GCS remote clients can be blocked to send controls or service requests
* Serial Port tool to record dumps

### Bug Fixes
* mandala value type fixes
* KML overlay plugin draws directly on Map tiles undelying layer (closes [`issue 46`](http://github.com/uavos/apx-releases/issues/46))
* GCS nodes value editors accept small numbers (closes [`issue 56`](http://github.com/uavos/apx-releases/issues/56))
* `numbers` list in Map as flow layout (closes [`issue 61`](http://github.com/uavos/apx-releases/issues/61))
* GCS script editor fixed pitch font
* GCS labels and buttons auto resize (closes [`issue 58`](http://github.com/uavos/apx-releases/issues/58))
* GCS modem RSS on the ground is available in `LOCAL` vehicle mandala when received from any other vehicle

## [Version 10.1.165](https://github.com/uavos/apx-releases/releases/tag/10.1.165) (08/25/19)

> Branch: `release`  
Date: `08/25/19 21:41:48`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/2d8b87d333381c85f0897b9498848c92f4449b7b...3ee0044b7f75bdbaf201d31c32a054210e688624)

### New Features
* Blackbox reader
* WPT index in status instrument (closes [`issue 47`](http://github.com/uavos/apx-releases/issues/47))
* map with tiles is available to plugins via JS `ui.mapbase`
* MHX RS4xx interface (closes [`issue 33`](http://github.com/uavos/apx-releases/issues/33))

### Bug Fixes
* telemetry auto recorder (closes [`issue 53`](http://github.com/uavos/apx-releases/issues/53))
* AHRS service menu commands (closes [`issue 48`](http://github.com/uavos/apx-releases/issues/48))
* limit bandwidth <10Hz of mandala value updates sent to datalink (closes [`issue 54`](http://github.com/uavos/apx-releases/issues/54))

### Performance Enhancements
* qwt lib upgrade for telemetry display (closes [`issue 51`](http://github.com/uavos/apx-releases/issues/51))
* mission view optimizations

### Comments
**feat: MHX RS4xx interface**

To connect `mhx` serial interface `RS4xx` to a PC, it must be configured as `MANDALA` or `DOWNLINK` serial port. Moreover, when the `mhx` function is selected as `gcu` - the RS232 port can not be used as protocols driven virtual serial port, because it always acts as bus interface for node locking protection. `RS232` port, when it is used to connect to a PC is always have default baud rate **460800**.

## [Version 10.1.155](https://github.com/uavos/apx-releases/releases/tag/10.1.155) (08/17/19)

> Branch: `release`  
Date: `08/17/19 02:45:22`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/a731468361d286c80a841a70882fe7694a600980...2d8b87d333381c85f0897b9498848c92f4449b7b)

### Bug Fixes
* linux distro upgrade to `bionic` (closes [`issue 52`](http://github.com/uavos/apx-releases/issues/52))

## [Version 10.1.154](https://github.com/uavos/apx-releases/releases/tag/10.1.154) (08/12/19)

> Branch: `release`  
Date: `08/12/19 10:10:28`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/5abd1720b217e30ce3debc20434fba2be9e25672...a731468361d286c80a841a70882fe7694a600980)

### New Features
* Data protocols abstraction
* KML file display on map
* Stratosphere flight controls upgrade based on HiDRONE flights
* ghanta node GPIO extension (closes [`issue 50`](http://github.com/uavos/apx-releases/issues/50))

### Bug Fixes
* sites plugin map items mouse events
* Commands widget UI scaling (closes [`issue 37`](http://github.com/uavos/apx-releases/issues/37))
* binding loop removal for commands widget (closes [`issue 44`](http://github.com/uavos/apx-releases/issues/44))
* GCS app close cleanup errors
* gcs SDK include paths replicate project tree

### Performance Enhancements
* Refactoring of streaming plugin, Merge pull request #58 from uavos/video

### Comments
**perf: Refactoring of streaming plugin, Merge pull request #58 from uavos/video**

Refactoring of streaming plugin

**kmloverlay: move map to center of overlay**

Add dialog for open files

**streaming: automatically reconnect, if some settings changed**

fix unnecessary unref

## [Version 10.1.53](https://github.com/uavos/apx-releases/releases/tag/10.1.53) (06/20/19)

> Branch: `release`  
Date: `06/20/19 19:37:32`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/8e09b9e920e401d2c391127b414d8587da9e6661...5abd1720b217e30ce3debc20434fba2be9e25672)

### Bug Fixes
* GCS sites plugin loader map items type mismatch
* QML main layout override path bug

### Performance Enhancements
* Qt libs upgrade 5.13.0

## [Version 10.1.49](https://github.com/uavos/apx-releases/releases/tag/10.1.49) (06/16/19)

> Branch: `release`  
Date: `06/16/19 20:52:18`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/ee74485e5e69876e3646a0d7f01d9b258d5a87b1...8e09b9e920e401d2c391127b414d8587da9e6661)

### New Features
* ADC bias and multiplier configuration parameters (closes [`issue 27`](http://github.com/uavos/apx-releases/issues/27))
* Shiva gimbal default control mode - 'speed' option (closes [`issue 25`](http://github.com/uavos/apx-releases/issues/25))
* GCS overridable main layout QML (closes [`issue 10`](http://github.com/uavos/apx-releases/issues/10))
* GCS Map support for external tile providers (closes [`issue 11`](http://github.com/uavos/apx-releases/issues/11))

### Bug Fixes
* GCS mission auto-shot by distance (closes [`issue 13`](http://github.com/uavos/apx-releases/issues/13))

### Comments
`feat: ADC bias and multiplier configuration parameters (closes [`issue 27`](http://github.com/uavos/apx-releases/issues/27))`  
Value written to `bind` variable equals `adc_voltage * mult + bias`. MCU reboot is needed when configuration changes.

`fix: GCS mission auto-shot by distance (closes [`issue 13`](http://github.com/uavos/apx-releases/issues/13))`  
Auto shot start/stop is controlled now via Waypoint/Actions/Shot setting. When started, the Auto Shot distance must be non-zero.

`feat: GCS overridable main layout QML (closes [`issue 10`](http://github.com/uavos/apx-releases/issues/10))`  
`GroundControl.qml` source file is included in SDK and can be put in `Documents/UAVOS/Plugins` to override and customize the main window contents. The plugins pathh is now in search paths for QML engine.

`feat: GCS Map support for external tile providers (closes [`issue 11`](http://github.com/uavos/apx-releases/issues/11))`  
The provider can be selected through `Tools/Tile Loader`. The GCS plugin subclassing QGeoServiceProviderFactory could be loaded from `Documents/UAVOS/Plugins` and provide Map tiles when selected in Tools menu.

## [Version 10.1.41](https://github.com/uavos/apx-releases/releases/tag/10.1.41) (06/14/19)

> Branch: `release`  
Date: `06/14/19 14:57:00`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/3575c763bffe5edb8733f21c61a5d735daeccdc0...ee74485e5e69876e3646a0d7f01d9b258d5a87b1)

### Bug Fixes
* IFC AP10 ADC configuration (closes [`issue 6`](http://github.com/uavos/apx-releases/issues/6))
* IFC AP9 PWM output and Mandala var extractor fix (closes [`issue 1`](http://github.com/uavos/apx-releases/issues/1))
* ADC for ghanta and xhawk (closes [`issue 5`](http://github.com/uavos/apx-releases/issues/5))

## [Version 10.1.37](https://github.com/uavos/apx-releases/releases/tag/10.1.37) (06/12/19)

> Branch: `release`  
Date: `06/12/19 22:13:10`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/bb65870fac4257e6f7b09f73b2ac3b24746ecde5...3575c763bffe5edb8733f21c61a5d735daeccdc0)

### Bug Fixes
* GCS console commands (closes #46)
* Another segfault fix on UDP discovery read (closes #44)
* ghanta RS232 driver power off until configured (closes uavos/apx-releases#24)
* IFC AP10 RS422x2 TX driver turn on when configured (closes uavos/apx-releases#9)

### Comments
`fix: ghanta RS232 driver power off until configured (closes uavos/apx-releases#24)`  
RS232 was always on after reset. Now it is off, but turned on when RS232 configured.

## [Version 10.1.28](https://github.com/uavos/apx-releases/releases/tag/10.1.28) (06/11/19)

> Branch: `release`  
Date: `06/11/19 21:28:42`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/3a53ac41c7b819784d2fbb286ddf308b7efa44a6...bb65870fac4257e6f7b09f73b2ac3b24746ecde5)

### New Features
* New APXFW firmware file format (bundle)
* CSV telemetry export (closes #55)

## [Version 10.1.13](https://github.com/uavos/apx-releases/releases/tag/10.1.13) (05/22/19)

> Branch: `release`  
Date: `05/22/19 23:59:24`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/ae7bf5b6d688cc7fd6baf39859349a89e80fd42c...3a53ac41c7b819784d2fbb286ddf308b7efa44a6)

### New Features
* Qt 5.12.3 upgrade
* SDK headers and package
* Qt upgrade and SDK package

### Bug Fixes
* SQUAWK update makes vehicle inaccessible (closes #38)
* map UAV display with extreme attitude angles
* `gcs` Commands widget buttons enabled behavior

### Comments
`feat: SDK headers and package`  
Add sdk package

## [Version 10.1.3](https://github.com/uavos/apx-releases/releases/tag/10.1.3) (04/17/19)

> Branch: `release`  
Date: `04/17/19 12:38:03`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/773d847c5a65050c1682a4425222f8bf004bdb0a...ae7bf5b6d688cc7fd6baf39859349a89e80fd42c)

### New Features
* Heli electric tail control through ctr_steering

### Bug Fixes
* possible segfault fix on UDP datagram reads by datalink discovery

## [Version 10.0.252](https://github.com/uavos/apx-releases/releases/tag/10.0.252) (04/14/19)

> Branch: `release`  
Date: `04/14/19 17:54:09`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/f8b82312d8a72db6ccb273c483eacfdb583ca23e...773d847c5a65050c1682a4425222f8bf004bdb0a)

### New Features
* Qt 5.12.2 upgrade

### Bug Fixes
* numbers editor dialog sets

## [Version 10.0.243](https://github.com/uavos/apx-releases/releases/tag/10.0.243) (03/19/19)

> Branch: `master`  
Date: `03/19/19 03:09:16`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/9e12a78a023983fb0bc4998080cb681804961281...f8b82312d8a72db6ccb273c483eacfdb583ca23e)

### New Features
* `gcs` numbers sets share

### Bug Fixes
* possible segfault crash fix
* vehicle configs offline edit and save

## [Version 10.0.240](https://github.com/uavos/apx-releases/releases/tag/10.0.240) (03/17/19)

> Branch: `master`  
Date: `03/17/19 09:58:39`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/5b113724a0f23bcafcc46ba2ebadea4fd5260465...9e12a78a023983fb0bc4998080cb681804961281)

### New Features
* nodes save edited config

### Bug Fixes
* config editors for arrays arrange and grouping (ports, controls, gpio, etc)

## [Version 10.0.237](https://github.com/uavos/apx-releases/releases/tag/10.0.237) (03/16/19)

> Branch: `master`  
Date: `03/16/19 19:58:16`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/3923665b7039efd58fa72fcd407fbd442925b49b...5b113724a0f23bcafcc46ba2ebadea4fd5260465)

### New Features
* controls and flight modes widget

## [Version 10.0.235](https://github.com/uavos/apx-releases/releases/tag/10.0.235) (03/16/19)

> Branch: `master`  
Date: `03/16/19 10:08:21`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/b3d971aad4da73127e53ec9848fd231143661de0...3923665b7039efd58fa72fcd407fbd442925b49b)

### Performance Enhancements
* graphics optimizations

## [Version 10.0.232](https://github.com/uavos/apx-releases/releases/tag/10.0.232) (03/16/19)

> Branch: `master`  
Date: `03/16/19 01:03:29`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/6b80c693b1c04d62edcd032fd78f968440fb4e61...b3d971aad4da73127e53ec9848fd231143661de0)

### Bug Fixes
* data values types conversion bugfix (hex)
* signals widget NaN check

## [Version 10.0.229](https://github.com/uavos/apx-releases/releases/tag/10.0.229) (02/25/19)

> Branch: `master`  
Date: `02/25/19 19:11:48`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/2f8e251445007066d848d81a13ff2a2e3ab843b5...6b80c693b1c04d62edcd032fd78f968440fb4e61)

Security updates and latest firmware `02/25/19`

## [Version 10.0.228](https://github.com/uavos/apx-releases/releases/tag/10.0.228) (02/24/19)

> Branch: `master`  
Date: `02/24/19 19:08:48`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/8aaa026a3db1e2d7270ddec1e99501fba94f1e33...2f8e251445007066d848d81a13ff2a2e3ab843b5)

Security updates and latest firmware `02/24/19`

## [Version 10.0.226](https://github.com/uavos/apx-releases/releases/tag/10.0.226) (02/23/19)

> Branch: `master`  
Date: `02/23/19 16:17:53`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/f4414059d6455bad1ad3f857aa4f0676b5128cd0...8aaa026a3db1e2d7270ddec1e99501fba94f1e33)

Security updates and latest firmware `02/23/19`

## [Version 10.0.224](https://github.com/uavos/apx-releases/releases/tag/10.0.224) (02/23/19)

> Branch: `master`  
Date: `02/23/19 12:11:49`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/5d3b8aa7935985017247f937f71485f7c77d229a...f4414059d6455bad1ad3f857aa4f0676b5128cd0)

### Bug Fixes
* node firmware update timeouts

## [Version 10.0.192](https://github.com/uavos/apx-releases/releases/tag/10.0.192) (02/18/19)

> Branch: `master`  
Date: `02/18/19 13:52:07`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/f5cc8f4997c6ea170713955a71220b09f3b8d4a9...5d3b8aa7935985017247f937f71485f7c77d229a)

Security updates and latest firmware `02/18/19`

## [Version 10.0.189](https://github.com/uavos/apx-releases/releases/tag/10.0.189) (02/14/19)

> Branch: `master`  
Date: `02/14/19 13:52:39`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/7b3268b41c9660256cb3d539135dac283b6e3335...f5cc8f4997c6ea170713955a71220b09f3b8d4a9)

### Bug Fixes
* segfault on node actions reload

## [Version 10.0.187](https://github.com/uavos/apx-releases/releases/tag/10.0.187) (02/14/19)

> Branch: `master`  
Date: `02/14/19 10:53:08`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/0b8875332ccc302d622c910a305d66817e5dc6b5...7b3268b41c9660256cb3d539135dac283b6e3335)

### New Features
* LOCAL vehicle configuration storage and share

### Bug Fixes
* map vehicle items z-order fix

## [Version 10.0.184](https://github.com/uavos/apx-releases/releases/tag/10.0.184) (02/13/19)

> Branch: `master`  
Date: `02/13/19 16:12:07`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/13fdcd2899a0338740585285d76c3d5efa15761e...0b8875332ccc302d622c910a305d66817e5dc6b5)

Security updates and latest firmware `02/13/19`

## [Version 10.0.182](https://github.com/uavos/apx-releases/releases/tag/10.0.182) (02/08/19)

> Branch: `master`  
Date: `02/08/19 16:08:24`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/df15bd4e7c855d66d49a955da9035968f52cb482...13fdcd2899a0338740585285d76c3d5efa15761e)

### Bug Fixes
* NAV AP10 FRAM error bugfix
* menu sections behavior

## [Version 10.0.180](https://github.com/uavos/apx-releases/releases/tag/10.0.180) (02/08/19)

> Branch: `master`  
Date: `02/08/19 14:32:36`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/1002a6b90063081cb427f20939e6f68ee31d2ff1...df15bd4e7c855d66d49a955da9035968f52cb482)

### New Features
* Node firmware upload through stm32 ROM bootloader

### Documentation Changes
* documentation links update and subscribe to mailing list

## [Version 10.0.176](https://github.com/uavos/apx-releases/releases/tag/10.0.176) (02/04/19)

> Branch: `master`  
Date: `02/04/19 16:56:09`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/ad13f9fe7b46cc61e558b51f26523c351487e8f5...1002a6b90063081cb427f20939e6f68ee31d2ff1)

### New Features
* announcements for releases
* slack and mailjet announcements

## [Version 10.0.174](https://github.com/uavos/apx-releases/releases/tag/10.0.174) (02/01/19)

> Branch: `master`  
Date: `02/01/19 10:13:31`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/9c3566f5b285823c3b9325fedb6047022034094f...ad13f9fe7b46cc61e558b51f26523c351487e8f5)

### New Features
* retain main window activity

### Bug Fixes
* pawncc compiler

## [Version 10.0.172](https://github.com/uavos/apx-releases/releases/tag/10.0.172) (01/31/19)

> Branch: `master`  
Date: `01/31/19 18:47:22`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/8d4071f8d9e6ff4c06b064cf51b1f463586ec10c...9c3566f5b285823c3b9325fedb6047022034094f)

### New Features
* development firmware files

### Bug Fixes
* segfault on app close
* firmware flash feature

## [Version 10.0.167](https://github.com/uavos/apx-releases/releases/tag/10.0.167) (01/31/19)

> Branch: `master`  
Date: `01/31/19 13:22:53`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/41ac9b4f2a66920e1e32353195f1caa8131878f8...8d4071f8d9e6ff4c06b064cf51b1f463586ec10c)

### Bug Fixes
* `gcs` map z-order for elements

## [Version 10.0.154](https://github.com/uavos/apx-releases/releases/tag/10.0.154) (01/20/19)

> Branch: `master`  
Date: `01/20/19 10:44:41`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/454f3d2ed345ef4434e9c6bdb69cf1531a299394...41ac9b4f2a66920e1e32353195f1caa8131878f8)

### Performance Enhancements
* QML map optimizations

## [Version 10.0.153](https://github.com/uavos/apx-releases/releases/tag/10.0.153) (01/19/19)

> Branch: `master`  
Date: `01/19/19 09:44:01`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/3db3d4565a618cf3757435037f1a417ff4167c40...454f3d2ed345ef4434e9c6bdb69cf1531a299394)

### Bug Fixes
* `gcs` Map objects Z

## [Version 10.0.152](https://github.com/uavos/apx-releases/releases/tag/10.0.152) (01/18/19)

> Branch: `master`  
Date: `01/18/19 16:17:33`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/33800bdbab1d0ca70396f8cef697ea25e889a067...3db3d4565a618cf3757435037f1a417ff4167c40)

### Bug Fixes
* DatabaseWorker slow descructor fix
* DatabaseWorker slow descructor fix

## [Version 10.0.149](https://github.com/uavos/apx-releases/releases/tag/10.0.149) (01/18/19)

> Branch: `master`  
Date: `01/18/19 15:07:15`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/70e750e296ec49bdb30d97221e468cdd936a7491...33800bdbab1d0ca70396f8cef697ea25e889a067)

### Bug Fixes
* `gcs` Map overlay display fix

## [Version 10.0.148](https://github.com/uavos/apx-releases/releases/tag/10.0.148) (01/18/19)

> Branch: `master`  
Date: `01/18/19 14:00:19`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/5a949d1dc02a9d23d93f35a75f41191448d2e712...70e750e296ec49bdb30d97221e468cdd936a7491)

### Bug Fixes
* branch name default

## [Version 10.0.141](https://github.com/uavos/apx-releases/releases/tag/10.0.141) (01/18/19)

> Branch: `unknown`  
Date: `01/18/19 09:33:52`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/c3967a85a648d9f027ca4db8999d00d326ef2a1f...5a949d1dc02a9d23d93f35a75f41191448d2e712)

### New Features
* branch master by default

## [Version 10.0.140](https://github.com/uavos/apx-releases/releases/tag/10.0.140) (01/17/19)

> Branch: `unknown`  
Date: `01/17/19 18:21:10`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/9f4be913ec3fc76567d0f0b96e3210d90d7ac5f8...c3967a85a648d9f027ca4db8999d00d326ef2a1f)

Security updates and latest firmware `01/17/19`

## [Version 10.0.139](https://github.com/uavos/apx-releases/releases/tag/10.0.139) (01/17/19)

> Branch: `unknown`  
Date: `01/17/19 17:33:28`  
Diff: [uavos/apx](https://github.com/uavos/apx/compare/e9ede61d480f6613ad3bc92aa99917c1e11d20b7...9f4be913ec3fc76567d0f0b96e3210d90d7ac5f8)

Security updates and latest firmware `01/17/19`

## [Version 10.0.137](https://github.com/uavos/apx-releases/releases/tag/10.0.137) (01/17/19)

> Branch: `unknown`  
Date: `01/17/19 16:00:03`

Security updates and latest firmware `01/17/19`

