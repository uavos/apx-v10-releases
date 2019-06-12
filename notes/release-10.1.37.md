#### Bug Fixes
* GCS console commands (closes #46)
* Another segfault fix on UDP discovery read (closes #44)
* ghanta RS232 driver power off until configured (closes uavos/apx-releases#24)
* IFC AP10 RS422x2 TX driver turn on when configured (closes uavos/apx-releases#9)

#### Comments
`fix: ghanta RS232 driver power off until configured (closes uavos/apx-releases#24)`  
RS232 was always on after reset. Now it is off, but turned on when RS232 configured.