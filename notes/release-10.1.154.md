#### New Features
* Data protocols abstraction
* KML file display on map
* Stratosphere flight controls upgrade based on HiDRONE flights
* ghanta node GPIO extension (closes [`issue 50`](http://github.com/uavos/apx-releases/issues/50))

#### Bug Fixes
* sites plugin map items mouse events
* Commands widget UI scaling (closes [`issue 37`](http://github.com/uavos/apx-releases/issues/37))
* binding loop removal for commands widget (closes [`issue 44`](http://github.com/uavos/apx-releases/issues/44))
* GCS app close cleanup errors
* gcs SDK include paths replicate project tree

#### Performance Enhancements
* Refactoring of streaming plugin, Merge pull request #58 from uavos/video

#### Comments
**perf: Refactoring of streaming plugin, Merge pull request #58 from uavos/video**

Refactoring of streaming plugin

**kmloverlay: move map to center of overlay**

Add dialog for open files

**streaming: automatically reconnect, if some settings changed**

fix unnecessary unref