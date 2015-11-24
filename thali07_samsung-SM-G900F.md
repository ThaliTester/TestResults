#### Test 50388019b17f598_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
W/ContextImpl( 5392): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
I/SLinkClient( 5323): queryDevices : cursor.getCount() = [ 0 ]
--------- beginning of system
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
D/SLinkClient( 5323): onStorageUpdated(), uri = [ slink://slink ]
W/ContextImpl( 5392): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5423): MountEmulatedStorage()
E/Zygote  ( 5423): v2
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
I/libpersona( 5423): KNOX_SDCARD checking this for 1000
I/libpersona( 5423): KNOX_SDCARD not a persona
I/ActivityManager(  805): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=5423 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SystemInfo( 5392): [SIOP LEVEL] : 0
I/SELinux ( 5423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/SLinkClient( 5323): SlinkBackgroundJob: slink wake up ok!
E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 8
D/TimaKeyStoreProvider( 5423): TimaSignature is unavailable
D/ActivityThread( 5423): Added TimaKeyStore provider
I/DocumentService( 5392): [BEGIN SYNC] DocumentService beginIndexing :16
W/ContextImpl( 5392): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
D/ResourcesManager( 5423): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
E/File    ( 5392): fail readDirectory() errno=13
E/File    ( 5392): fail readDirectory() errno=13
I/DocumentServiceUtils( 5392):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo( 5392): DocumentService [SIOP LEVEL] changed to 0
I/SystemInfo( 5392): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5392): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5392): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :41
E/DocumentService( 5392): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5392): [INDEX] Total time taken for each file :0
E/SystemInfo( 5392): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5369): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
I/DocumentService( 5392): DocumentService onDestroy start
I/DocumentService( 5392): DocumentService onDestroy end
I/DocumentService( 5392): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 5392): InterruptedException: null
,I/SystemInfo( 5392): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5392): DocumentService cleanupEverything end
I/Process ( 5392): Sending signal. PID: 5392 SIG: 9
D/PopupuiReceiver( 5423): onReceive() getAction : com.android.systemui.power.action.ACTION_CABLE_CONNECTED
D/SecContentProvider2(  805): uri = -1 selection = getSealedState
D/SecContentProvider2(  805): mCursor = null
I/PopupuiReceiver_KNOX( 5423): getSealedState : true
D/SecContentProvider2(  805): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2(  805): mCursor = null
D/SecContentProvider2(  805): KnoxCustomManagerService offline: service is not available
I/PopupuiReceiver_KNOX( 5423): getSealedHideNotificationMessages : 1
D/SecContentProvider2(  805): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2(  805): mCursor = null
D/SecContentProvider2(  805): KnoxCustomManagerService offline: service is not available
I/PopupuiReceiver_KNOX( 5423): getCheckCoverPopupState : true
W/ContextImpl( 5423): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:407 android.app.ActivityThread.handleReceiver:2945 
D/PopupuiReceiver( 5423): Action cable connected ! on - 
I/ActivityManager(  805): Process com.samsung.indexservice (pid 5392)(adj 9) has died(56,647)
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
D/GalleryCacheReady( 5323): Receive : home resume
W/ContextImpl( 5369): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/PopupuiReceiver( 5423): PopupuiService.java: dismissUSBCDetacheddDialog() unReigister
W/ContextImpl( 5423): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 com.sec.android.app.popupuireceiver.PopupuiService.dismissUSBCDetacheddDialog:130 com.sec.android.app.popupuireceiver.PopupuiService.onStartCommand:103 
W/ContextImpl( 5423): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 android.app.ActivityThread.handleStopService:3289 android.app.ActivityThread.access$2300:172 
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
V/Transcoder( 5369): Transcoder(0xaef0c830)::constructor
V/Transcoder( 5369): addObitRecipient
V/TMI-JNI ( 5369): Mobile Transcoder JNI version 1.6.0/20131120/4.4
D/Mms/UIEventReceiver( 5179): ui event
W/BroadcastQueue(  805): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1498, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5452): MountEmulatedStorage()
E/Zygote  ( 5452): v2
I/libpersona( 5452): KNOX_SDCARD checking this for 10094
I/libpersona( 5452): KNOX_SDCARD not a persona
I/ActivityManager(  805): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5452 uid=10094 gids={50094, 9997} abi=armeabi-v7a
I/SELinux ( 5452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5452): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/ConnectivityService(  805): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
I/art     (  805): Explicit concurrent mark sweep GC freed 49156(2MB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 1.269ms total 104.654ms
D/TimaKeyStoreProvider( 5452): TimaSignature is unavailable
D/ActivityThread( 5452): Added TimaKeyStore provider
E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 8
D/ResourcesManager( 5452): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
W/ResourcesManager( 5452): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 4320): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
I/MediaStoreImporter( 5144): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
E/Zygote  ( 5468): MountEmulatedStorage()
E/Zygote  ( 5468): v2
I/libpersona( 5468): KNOX_SDCARD checking this for 10103
I/libpersona( 5468): KNOX_SDCARD not a persona
I/ActivityManager(  805): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5468 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  805): Killing 2523:com.sec.android.automotive.drivelink/u0a99 (adj 15): bgCount ##41
I/SELinux ( 5468): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5468): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5468): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager(  805): Killing 4222:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 5468): TimaSignature is unavailable
D/ActivityThread( 5468): Added TimaKeyStore provider
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
W/libprocessgroup(  805): failed to open /acct/uid_10099/pid_2523/cgroup.procs: No such file or directory
D/ResourcesManager( 5468): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
W/ResourcesManager( 5468): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5468): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
W/libprocessgroup(  805): failed to open /acct/uid_10033/pid_4222/cgroup.procs: No such file or directory
E/Zygote  ( 5485): MountEmulatedStorage()
E/Zygote  ( 5485): v2
I/libpersona( 5485): KNOX_SDCARD checking this for 10113
I/libpersona( 5485): KNOX_SDCARD not a persona
E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
I/ActivityManager(  805): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=5485 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 8
I/ActivityManager(  805): Killing 4306:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
I/ActivityManager(  805): Waited long enough for: ServiceRecord{19a76eb0 u0 com.sec.android.service.sm/.service.SecurityManagerService}
D/AndroidRuntime( 5450): 
D/AndroidRuntime( 5450): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/SELinux ( 5485): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AndroidRuntime( 5450): CheckJNI is OFF
I/SELinux ( 5485): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/AndroidRuntime( 5450): setted country_code = Germany
D/AndroidRuntime( 5450): setted countryiso_code = DE
D/AndroidRuntime( 5450): setted sales_code = DBT
D/AndroidRuntime( 5450): readGMSProperty: start
D/AndroidRuntime( 5450): readGMSProperty: already setted!!
D/AndroidRuntime( 5450): readGMSProperty: end
D/AndroidRuntime( 5450): addProductProperty: start
E/SELinux ( 5485): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 5485): TimaSignature is unavailable
D/ActivityThread( 5485): Added TimaKeyStore provider
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
E/SMD     (  298): DCD ON
W/libprocessgroup(  805): failed to open /acct/uid_10091/pid_4306/cgroup.procs: No such file or directory
D/ResourcesManager( 5485): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
W/GeoLookout( 5485): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
I/GeoLookout( 5485): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
D/SettingsProvider(  805): name = safetycare_geolookout_registering
D/SettingsProvider(  805): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  805): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  805): selectionArgs: false
D/SettingsProvider(  805): selectionArgs: 10113
D/SecContentProvider(  805): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  805): ret = -1
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
D/GeoLookout( 5485): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
I/DBG_DM  ( 3500): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 12 sec
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
V/TaskCloserActivity( 5113): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
I/ActivityManager(  805): Killing 4383:com.samsung.helphub/1000 (adj 15): bgCount ##41
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/LightSensor(  805): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 8
E/Zygote  ( 5510): MountEmulatedStorage()
I/libpersona( 5510): KNOX_SDCARD checking this for 10054
E/Zygote  ( 5510): v2
I/libpersona( 5510): KNOX_SDCARD not a persona
E/AffinityControl( 5450): AffinityControl: registerfunction enter
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
I/ActivityManager(  805): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=5510 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
D/AndroidRuntime( 5450): Calling main entry com.android.commands.am.Am
I/SELinux ( 5510): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5510): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5510): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/PersonaManagerService(  805): inState():  stateMachine is null !!
V/ApplicationPolicy(  805): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  805): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  805): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  805): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 805  pkgName : ACTIVITY_RESUME_BOOSTER@6
D/TimaKeyStoreProvider( 5510): TimaSignature is unavailable
D/ActivityThread( 5510): Added TimaKeyStore provider
W/ActivityManager(  805): mDVFSHelper.acquire()
W/libprocessgroup(  805): failed to open /acct/uid_1000/pid_4383/cgroup.procs: No such file or directory
D/FocusedStackFrame(  805): Set to : 0
D/Launcher.HomeView( 1498): onPause
V/AlarmManager(  805): waitForAlarm result :4
D/Launcher( 1498): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 5450): Shutting down VM
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Zygote  ( 5527): MountEmulatedStorage()
E/Zygote  ( 5527): v2
I/libpersona( 5527): KNOX_SDCARD checking this for 10374
I/libpersona( 5527): KNOX_SDCARD not a persona
I/SurfaceFlinger(  249): id=12 createSurf (1x1),1 flag=404, Starting com.example.hello
I/ActivityManager(  805): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5527 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
I/SELinux ( 5527): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 5527): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5527): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  805): Waited long enough for: ServiceRecord{bd795ba u0 com.samsung.android.providers.context/.ContextService}
D/TimaKeyStoreProvider( 5527): TimaSignature is unavailable
D/ActivityThread( 5527): Added TimaKeyStore provider
V/WindowOrientationListener(  805): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  805): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  805): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  805): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  805): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/BatteryService(  805): level:100, scale:100, status:2, health:2, present:true, voltage: 4262, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  805): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  805): Sending ACTION_BATTERY_CHANGED.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5510): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/MotionRecognitionService(  805):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  805): Plugged
I/MotionRecognitionService(  805): setPowerConnected  = true
D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
D/ResourcesManager( 5527): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
W/ResourcesManager( 5510): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5510): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5510): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ResourcesManager( 5510): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/StatusBarManagerService(  805): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ResourcesManager( 5510): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ConnectivityService(  805): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  805): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Launcher.HomeView( 1498): onStop
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/MicrophoneInputStream( 1565): mic_close gfk@1c54589b
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1955): [237392/6] Surface widget pause on instance = 1
V/AudioPolicyManager(  305): stopInput() input 26
V/AudioPolicyManager(  305): releaseInput() 26
V/AudioPolicyManager(  305): closeInput(26)
D/SurfaceWidgetClient$ISurfaceWidgetStub( 1955): [237392/6] Surface widget visibility changed visibility = false on instance = 1
I/HotwordRecognitionRnr( 1565): Hotword detection finished
D/Launcher( 1498): onTrimMemory. Level: 20
I/HotwordRecognitionRnr( 1565): Stopping hotword detection.
V/audio_hw_primary(  305): in_standby: enter
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
D/PowerManagerService(  805): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
D/PowerManagerService(  805): [s] DisplayPowerCallbacks : onStateChanged()
D/lights  (  805): lcd : 7 +
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/lights  (  805): lcd : 7 -
D/accuweather( 1955): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
E/ActivityThread( 1498): Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1498): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1498): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 1498): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 1498): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1498): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 1498): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1498): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 1498): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 1498): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1498): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1498): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 1498): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/SurfaceWidgetView( 1498): destroyHardwareResources():372620389
D/accuweather( 1955): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 1955): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/accuweather( 1955): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 1955): [KK AccuPhone]>>> SM:538 [0:0] onPause
V/BitmapFactory( 1498): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic_none.png
I/ActivityManager(  805): Activity reported stop, but no longer stopping: ActivityRecord{2aecb336 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9}
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
D/lights  (  805): lcd : 1 +
D/LockPatternUtilsCache( 1170): value : false
V/audio_hw_primary(  305): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  305): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  305): disable_audio_route: reset mixer path: audio-record
D/audio_route(  305): ++++ audio_route_update_mixer ==============
D/audio_route(  305): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  305): Setting mixer control: value: 0
D/lights  (  805): lcd : 1 -
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/audio_route(  305): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  305): disable_audio_route: exit
V/audio_hw_primary(  305): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  305): ++++ audio_route_update_mixer ==============
D/audio_route(  305): Setting mixer control: DEC2 Volume
D/audio_route(  305): Setting mixer control: value: 0
D/audio_route(  305): Setting mixer control: SLIM TX7 MUX, value: 0
I/WebViewFactory( 5527): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 5527): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/audio_route(  305): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  305): Setting mixer control: value: 0
D/audio_route(  305): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  305): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  305): stop_input_stream: exit: status(0)
V/audio_hw_primary(  305): in_standby: exit:  status(0)
V/audio_hw_primary(  305): adev_close_input_stream
V/audio_hw_primary(  305): in_standby: enter
V/audio_hw_primary(  305): in_standby: exit:  status(0)
E/audio_hw_primary(  305): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  305): releaseInput() exit
I/LibraryLoader( 5527): Loading: webviewchromium
I/LibraryLoader( 5527): Time to load native libraries: 2 ms (timestamps 922-924)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/LibraryLoader( 5527): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1170): value : false
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,E/TranscodeReceiver( 5510): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/videowall-Global( 5510): core_num = 4
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  805): Waited long enough for: ServiceRecord{2459c6b u0 com.android.settings/.wifi.WifiCredService}
W/linker  ( 5510): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
V/WebViewChromiumFactoryProvider( 5527): Binding Chromium to main looper Looper (main, tid 1) {3d46b4cd}
I/LibraryLoader( 5527): Expected native library version number "",actual native library version number ""
I/chromium( 5527): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5527): Initializing chromium process, renderers=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/art     ( 5527): Attempt to remove local handle scope entry from IRT, ignoring
W/linker  ( 5510): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/chromium( 5527): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
D/videowall-Global( 5510): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 5510): dsp : 1080, swkey : false, Cores : 4, Clock : 0
W/chromium( 5527): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5527): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5527): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter( 5527): 96444802: getState() :  mService = null. Returning STATE_OFF
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TranscodeReceiver( 5510):  SIOP_LEVEL: 0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
I/Adreno-EGL( 5527): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5527): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5527): Build Date: 03/03/15 Tue
I/Adreno-EGL( 5527): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 5527): Remote Branch: 
I/Adreno-EGL( 5527): Local Patches: 
I/Adreno-EGL( 5527): Reconstruct Branch: 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  805): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5555 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  805): Killing 4412:com.zalando.samsung.provider/u0a192 (adj 15): bgCount ##41
E/Zygote  ( 5555): MountEmulatedStorage()
E/Zygote  ( 5555): v2
I/libpersona( 5555): KNOX_SDCARD checking this for 10114
I/libpersona( 5555): KNOX_SDCARD not a persona
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
I/SELinux ( 5555): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 5555): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5555): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 5555): TimaSignature is unavailable
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ActivityThread( 5555): Added TimaKeyStore provider
I/ActivityManager(  805): Waited long enough for: ServiceRecord{2a1f9447 u0 com.android.settings/.wifi.hs20.Hs20UtilityService}
D/ResourcesManager( 5555): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/libprocessgroup(  805): failed to open /acct/uid_10192/pid_4412/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/chromium( 5527): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/chromium( 5527): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/art     ( 5527): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5527): onDetachedFromWindow called when already detached. Ignoring
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SystemWebViewEngine( 5527): CordovaWebView is running on device made by: samsung
W/art     ( 5527): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5527): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ActivityManager(  805): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ActivityThread( 5555): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager(  805): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Activity( 5527): performCreate Call secproduct feature valuefalse
D/Activity( 5527): performCreate Call debug elastic valuetrue
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
D/OpenGLRenderer( 5527): Render dirty regions requested: true
D/ActivityManager(  805): post active user change for 0
D/KnoxTimeoutHandler(  805): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  805): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/Gmail   ( 5555): getAccountsCursor
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=13 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  805): Killing 4423:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OpenGLRenderer( 5527): Initialized EGL, version 1.4
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/OpenGLRenderer( 5527): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/GAV2    ( 5555): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/OpenGLRenderer( 5527): Enabling debug mode 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/libprocessgroup(  805): failed to open /acct/uid_1000/pid_4423/cgroup.procs: No such file or directory
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ActivityManager(  805): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  805): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  805): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5555): Observing account changes for notifications
W/ActivityManager(  805): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/InputMethodManagerService(  805): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
W/ActivityManager(  805): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ContextImpl(  805): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/LightSensor(  805): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
I/ActivityManager(  805): Displayed com.example.hello/.MainActivity: +656ms
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/Timeline( 5527): Timeline: Activity_idle id: android.os.BinderProxy@1bbb6b3d time:41413
I/Gmail   ( 5555): getAccountsCursor
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/art     ( 1684): Explicit concurrent mark sweep GC freed 11049(609KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 484us total 41.404ms
E/Gmail   ( 5555): Error finding the version of the Email provider.....
E/Gmail   ( 5555): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5555): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:135)
E/Gmail   ( 5555): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 5555): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5555): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5555): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5555): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5555): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5555): We do not support migrating this version of the Email provider.
V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  805): Killing 4463:com.LocalFota/u0a120 (adj 15): bgCount ##41
I/chromium( 5527): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5527): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/HomeSyncInstallReceiver( 1477): This pkg do not need BT addr. Do nothing
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ContextImpl( 3670): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1796 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
E/Zygote  ( 5614): MountEmulatedStorage()
E/Zygote  ( 5614): v2
I/libpersona( 5614): KNOX_SDCARD checking this for 10015
I/libpersona( 5614): KNOX_SDCARD not a persona
I/ActivityManager(  805): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5614 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
D/JsMessageQueue( 5527): Set native->JS mode to OnlineEventsBridgeMode
E/SQLiteLog( 5555): (283) recovered 358 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/SELinux ( 5614): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 5614): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5614): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/DBG_DM  ( 3500): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(522/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
I/DBG_DM  ( 3500): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(526/onReceive)] status  = 1
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
E/DBG_DM  ( 3500): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(537/onReceive)] Device is ok
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/libprocessgroup(  805): failed to open /acct/uid_10120/pid_4463/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 5614): TimaSignature is unavailable
D/ActivityThread( 5614): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  805): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/DBG_DM  ( 3500): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.example.hello.MainActivity
D/CustomFrequencyManagerService(  805): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 805  tag : ACTIVITY_RESUME_BOOSTER@6
I/Process ( 3670): Sending signal. PID: 3670 SIG: 9
W/ActivityManager(  805): mDVFSHelper.release()
D/CustomFrequencyManagerService(  805): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 805  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline(  805): Timeline: Activity_windows_visible id: ActivityRecord{2923a839 u0 com.example.hello/.MainActivity t11} time:41581
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:79000 mC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 5614): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (6/8)
I/SurfaceFlinger(  249): id=12 Removed Starting com.example.hello (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/File    ( 5555): fail readDirectory() errno=2
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/DBG_DM  ( 3500): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 13 sec
D/ConnectivityService(  805): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3500): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/ConnectivityService(  805): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3500): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
I/Gmail   ( 5555): getAccountsCursor
I/Gmail   ( 5555): notifyAccountChanged
I/ActivityManager(  805): Process com.sec.android.app.sysscope (pid 3670)(adj 0) has died(67,642)
E/DBG_DM  ( 3500): [llIlIIIIlllIlllllIll(232/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DBG_DM  ( 3500): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.example.hello.MainActivity
I/Gmail   ( 5555): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
I/Gmail   ( 5555): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
E/Adreno-ES20( 5527): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5527): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
I/chromium( 5527): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5527): 
E/Zygote  ( 5634): MountEmulatedStorage()
E/Zygote  ( 5634): v2
I/libpersona( 5634): KNOX_SDCARD checking this for 10016
I/libpersona( 5634): KNOX_SDCARD not a persona
I/Gmail   ( 5555): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  805): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=5634 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 5555): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/SELinux ( 5634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5634): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  805): Killing 4503:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 1971): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/TimaKeyStoreProvider( 5634): TimaSignature is unavailable
,D/ActivityThread( 5634): Added TimaKeyStore provider
,D/ResourcesManager( 5634): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
,W/ResourcesManager( 5634): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5634): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/jxcore_app_log( 5527): JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358531584
,D/JX-Cordova( 5527): jxcore cordova android initializing
,W/libprocessgroup(  805): failed to open /acct/uid_1000/pid_4503/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:79000 mC
,I/Gmail   ( 5555): getAccountsCursor
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GroupCast_FileTools( 5634): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 5634): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,W/System.err( 5634): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
,W/System.err( 5634): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5634): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5634): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5634): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5634): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5634): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5634): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5634): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5634): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5634): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5634): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5634): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5634): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/jxcore-log( 5527): Initializing JXcore engine
W/jxcore-log( 5527): JXcore engine is ready
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
W/jxcore-log( 5527): Starting JXcore engine
E/Zygote  ( 5652): MountEmulatedStorage()
E/Zygote  ( 5652): v2
I/libpersona( 5652): KNOX_SDCARD checking this for 1000
I/libpersona( 5652): KNOX_SDCARD not a persona
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
I/ActivityManager(  805): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5652 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  805): Killing 4553:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
,D/CustomFrequencyManagerService(  805): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 805  tag : ACTIVITY_RESUME_BOOSTER@10
,E/auditd  ( 2089): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  805): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  805): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  805): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,I/SELinux ( 5652): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5652): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5652): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 5652): TimaSignature is unavailable
,D/ActivityThread( 5652): Added TimaKeyStore provider
,D/ResourcesManager( 5652): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/libprocessgroup(  805): failed to open /acct/uid_10138/pid_4553/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_LOG( 5652): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5652): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5652): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 5652): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5652): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5652): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5652): [onReceive] - android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5667): MountEmulatedStorage()
E/Zygote  ( 5667): v2
I/libpersona( 5667): KNOX_SDCARD checking this for 10034
I/libpersona( 5667): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5667 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/ActivityManager(  805): Killing 4574:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,W/jxcore-log( 5527): Platform android
W/jxcore-log( 5527): 
W/jxcore-log( 5527): Process ARCH arm
W/jxcore-log( 5527): 
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,I/art     (  331): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 278us total 15.543ms
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.240ms
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 8.035ms
,I/jxcore-log( 5527): JXcore Cordova bridge is ready!
I/jxcore-log( 5527): 
,W/jxcore-log( 5527): JXcore engine is started
,I/SELinux ( 5667): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5667): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5667): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,D/TimaKeyStoreProvider( 5667): TimaSignature is unavailable
D/ActivityThread( 5667): Added TimaKeyStore provider
,W/libprocessgroup(  805): failed to open /acct/uid_10012/pid_4574/cgroup.procs: No such file or directory
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/jxcore-log( 5527): >> samsung-SM-G900F
E/jxcore-log( 5527): 
,I/jxcore-log( 5527): Total memory 1787449344
I/jxcore-log( 5527): 
I/jxcore-log( 5527): Free memory 74665984
I/jxcore-log( 5527): 
I/jxcore-log( 5527): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5527): 
I/jxcore-log( 5527): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5527): 
I/jxcore-log( 5527): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5527): 
I/jxcore-log( 5527): Size 1080 1920
I/jxcore-log( 5527): 
,I/jxcore-log( 5527): Screen Brightness 134
I/jxcore-log( 5527): 
,E/jxcore-log( 5527): Dummy Error Log.
E/jxcore-log( 5527): 
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
I/FeatureConfig( 5667): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 5667): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 5667): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5667): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5667): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 5667): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 5667): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
,D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/SA      ( 4973): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4973): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 4973): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10374 extra.user_handle.:0 ]
,I/ActivityManager(  805): Killing 4446:com.android.vending/u0a30 (adj 15): bgCount ##41
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:72000 mC
,D/Mms/FreeMessageReceiver( 5179): onReceive, action : android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService( 5179): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 5179): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 5693): MountEmulatedStorage()
E/Zygote  ( 5693): v2
I/libpersona( 5693): KNOX_SDCARD checking this for 10051
I/libpersona( 5693): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5693 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/SELinux ( 5693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  805): failed to open /acct/uid_10030/pid_4446/cgroup.procs: No such file or directory
,I/SELinux ( 5693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5693): TimaSignature is unavailable
,D/ActivityThread( 5693): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:70000 mC
,D/ResourcesManager( 5693): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 5693): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5693): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/MyFiles ( 5693): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/TactileAssist(  805): enable value -1
I/TactileAssist(  805): internal enable value -1
I/TactileAssist(  805): intensity value -1
I/TactileAssist(  805): saveAppList value true
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:70000 mC
,I/TactileAssist(  805): List of disabled apps :
I/TactileAssist(  805): de.zalando.mobile
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/installd(  308): system dir 0 : /system/app/
E/installd(  308): system dir 1 : /system/priv-app/
E/installd(  308): system dir 2 : /vendor/app/
E/installd(  308): system dir 3 : /oem/app/
,E/Zygote  ( 5716): MountEmulatedStorage()
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
E/Zygote  ( 5716): v2
I/libpersona( 5716): KNOX_SDCARD checking this for 10058
,I/libpersona( 5716): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5716 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 5716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5716): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5716): TimaSignature is unavailable
,D/ActivityThread( 5716): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:69000 mC
,D/PackageManager(  805): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/ResourcesManager( 5716): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 5716): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 5716): onReceive() it will make start service
,D/Compatibility( 5716): onHandleIntent()
,D/Compatibility( 5716): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10374, android.intent.extra.user_handle=0}]
,D/Compatibility( 5716): found: 2
,D/Compatibility( 5716): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5716): skipping ResolveInfo{b39a091 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5716): considering ResolveInfo{179bbbf6 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5716): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5716): enabling receiver ResolveInfo{16d82bf7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5716): enabling receiver ResolveInfo{f7a2a64 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5716): enabling receiver ResolveInfo{3d46b4cd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:72000 mC
I/UpdateIcingCorporaServi( 1565): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5716): enabling receiver ResolveInfo{5bfa182 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5716): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Zygote  ( 5740): MountEmulatedStorage()
E/Zygote  ( 5740): v2
I/libpersona( 5740): KNOX_SDCARD checking this for 1000
I/libpersona( 5740): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5740 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5740): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5740): TimaSignature is unavailable
,D/ActivityThread( 5740): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/jxcore-log( 5527): getBuffer is called!!!!
I/jxcore-log( 5527): 
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
I/art     (  805): Explicit concurrent mark sweep GC freed 26368(1609KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 1.141ms total 82.356ms
D/ResourcesManager( 5740): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/ResourcesManager( 1971): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/ContextImpl( 5740): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,E/Zygote  ( 5759): MountEmulatedStorage()
E/Zygote  ( 5759): v2
I/libpersona( 5759): KNOX_SDCARD checking this for 10086
I/libpersona( 5759): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=5759 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5759): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5759): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  805): Killing 4600:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
E/SELinux ( 5759): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/TimaKeyStoreProvider( 5759): TimaSignature is unavailable
,D/ActivityThread( 5759): Added TimaKeyStore provider
,D/ResourcesManager( 5759): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5759): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  805): failed to open /acct/uid_10143/pid_4600/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,D/PushModule( 5759): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 5759): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 5759): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 5759): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 5759): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  805): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 5759): [1][a] ChatONV isn't installed.
D/ChatON  ( 5759): [1][a] ChatONVPlugIn.isAvailable()
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5778): MountEmulatedStorage()
E/Zygote  ( 5778): v2
I/libpersona( 5778): KNOX_SDCARD checking this for 10098
I/libpersona( 5778): KNOX_SDCARD not a persona
,D/ResourcesManager( 1565): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/SELinux ( 5778): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  805): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5778 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5778): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5778): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager(  805): Killing 4544:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
,D/TimaKeyStoreProvider( 5778): TimaSignature is unavailable
,D/ActivityThread( 5778): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 1565): UpdateCorporaTask done [took 465 ms] updated apps [took 464 ms] 
,W/libprocessgroup(  805): failed to open /acct/uid_10017/pid_4544/cgroup.procs: No such file or directory
,D/ResourcesManager( 5778): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:73000 mC
,D/DocsApplication( 5778): Installing DEX configuration.
,D/DexInstaller( 5778): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 5778): Provided clientMode=RELEASE, packageInfo=PackageInfo{27621ab8 com.google.android.apps.docs}
,D/TAG     ( 5778): onCreate()
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:73000 mC
,D/CrossAppStateProvider( 5778): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:72000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:69000 mC
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:68000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:68000 mC
,E/Watchdog(  805): !@Sync 1
,D/SettingsProvider(  805): name = audio_safe_volume_state
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:67000 mC
,E/SMD     (  298): DCD ON
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:67000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5803): MountEmulatedStorage()
,E/Zygote  ( 5803): v2
I/libpersona( 5803): KNOX_SDCARD checking this for 10099
I/libpersona( 5803): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=5803 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  805): Killing 4845:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,I/SELinux ( 5803): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5803): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5803): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/GAV2    ( 5778): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 5803): TimaSignature is unavailable
,D/ActivityThread( 5803): Added TimaKeyStore provider
,D/ResourcesManager( 5803): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,I/Icing   ( 1971): Indexing EF63CEC2998F8E1A114BBA3A5515DD2FA8B6047E from com.google.android.googlequicksearchbox
,W/ResourcesManager( 5803): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  805): failed to open /acct/uid_10037/pid_4845/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
,D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,D/Icing   ( 1971): Loaded CLD2 Version V2.0 - 20141016
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:66000 mC
,I/Icing   ( 1971): Indexing done EF63CEC2998F8E1A114BBA3A5515DD2FA8B6047E
,E/[CarMode]( 5803): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 5803): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 5803): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:68000 mC
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5835): MountEmulatedStorage()
E/Zygote  ( 5835): v2
I/libpersona( 5835): KNOX_SDCARD checking this for 10033
I/libpersona( 5835): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=5835 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5835): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5835): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5835): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5835): TimaSignature is unavailable
,D/ActivityThread( 5835): Added TimaKeyStore provider
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,D/ResourcesManager( 5835): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:69000 mC
,W/ResourcesManager( 5835): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/System.out( 5835): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 5835): Inside WakeupProvider
,E/DatabaseUtils( 5835): Writing exception to parcel
E/DatabaseUtils( 5835): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5835): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5835): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5835): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5835): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5835): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5835): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5835): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5835): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5835): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5835): 	at android.os.Binder.execTransact(Binder.java:446)
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:69000 mC
W/System.err( 5803): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,I/VlingoApplication( 5835): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,W/System.err( 5803): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
,W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5803): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 5803): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 5803): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 5803): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 5803): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 5803): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 5803): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5803): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5803): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5803): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5803): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5803): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 5835): Writing exception to parcel
E/DatabaseUtils( 5835): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5835): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5835): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5835): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5835): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5835): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5835): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5835): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5835): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5835): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5835): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 5803): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 5803): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5803): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5803): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5803): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5803): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 5803): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 5803): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 5803): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 5803): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5803): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5803): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5803): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5803): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5803): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5803): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,D/BluetoothAdapter( 5835): 396848946: getState() :  mService = null. Returning STATE_OFF
,E/[CarMode]( 5803): [DLApplication]-Init Called!:false
E/[CarMode]( 5803): [DLApplication]-Init Started!:true
D/BluetoothAdapter( 5835): 396848946: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5835): 396848946: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 5835): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/[CarModeFW]( 5803): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 5803): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 5803): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 5803): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 5803): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 5803): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 5803): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 5803): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 5803): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 5803): ### android.os.Looper::loop(145)
I/[CarModeFW]( 5803): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 5803): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 5803): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 5803): ### com.android.internal.os.ZygoteInit::main(1194)
,W/GAV2    ( 5778): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/MessageDataHandler( 5803): initialize
,D/[CarModeFW]( 5803): CDH-initiazlieCaches : before sync
,D/[CarModeFW]( 5803): CDH-initiazlieCaches : after sync
,D/BluetoothAdapter( 5803): 926105851: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5803): 926105851: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 5803): DrivingManager-initialize...
,I/SensorService(  805): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  805): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  805): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 5803): CDH-ContactDataHandler initiazlieCaches time : 18
,D/[CarModeFW]( 5803): CDH-initiazlieCaches : end sync
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:72000 mC
,D/VlingoApplication( 5835): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 5835): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/MediaPlayer( 5803): Need to enable context aware info
V/MediaPlayer-JNI( 5803): native_setup
V/MediaPlayer( 5803): constructor
,V/MediaPlayer( 5803): setListener
,E/MediaPlayer-JNI( 5803): QCMediaPlayer mediaplayer NOT present
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
D/[CarModeFW]( 5803): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 5803): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 5803): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1448385953945
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1448385953947
,D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1448385953950
,D/[CarModeFW]( 5803): RecommendHandler-selection = type = '3'
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1448385953952
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1448385953954
D/[CarMode]( 5803): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1448385953958
,I/[CarMode]( 5803): [LogNotNull]-Package name is: com.google.android.apps.maps
,E/Zygote  ( 5869): MountEmulatedStorage()
,E/Zygote  ( 5869): v2
I/libpersona( 5869): KNOX_SDCARD checking this for 10020
I/libpersona( 5869): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=5869 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,E/[CarMode]( 5803): [DLApplication]-Init End!:true
,I/SELinux ( 5869): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
,I/SELinux ( 5869): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/SELinux ( 5869): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5880): MountEmulatedStorage()
E/Zygote  ( 5880): v2
I/libpersona( 5880): KNOX_SDCARD checking this for 10003
I/libpersona( 5880): KNOX_SDCARD not a persona
,D/[CarMode]( 5803): [DLApplication]-GooglePlayServices SUCCESS.
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
,I/ActivityManager(  805): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=5880 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/[CarModeFW]( 5803): RecommendHandler-selection = type = '3'
,I/SELinux ( 5880): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5880): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/TP/SmsProvider( 1483): query,matched:2, calling pid = 5803
,E/SELinux ( 5880): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/SmsProvider( 1483): match 2:Elapsed time : 1.251 ms
,D/TimaKeyStoreProvider( 5869): TimaSignature is unavailable
,D/ActivityThread( 5869): Added TimaKeyStore provider
,E/[CarMode]( 5803): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/MessageDataHandler( 5803):  getInboxList smsCursor : 95
,D/TP/SmsProvider( 1483): query,matched:2, calling pid = 5803
,D/TP/SmsProvider( 1483): match 2:Elapsed time : 1.795 ms
,I/UpdateManagerReceiver( 5803): Intent : android.intent.action.PACKAGE_ADDEDTue Nov 24 18:25:54 GMT+01:00 2015
,D/[CarModeFW]( 5803): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsProvider( 1483): Query uri=content://mms/inbox, match=2, calling pid = 5803
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 5880): TimaSignature is unavailable
,D/ActivityThread( 5880): Added TimaKeyStore provider
,D/ResourcesManager( 5869): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,E/Zygote  ( 5899): MountEmulatedStorage()
I/libpersona( 5899): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5899): v2
I/libpersona( 5899): KNOX_SDCARD not a persona
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:72000 mC
,I/ActivityManager(  805): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5899 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/SELinux ( 5899): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5899): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5899): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  805): Killing 4984:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
,D/MessageDataHandler( 5803):  getInboxList mmsCursor : 75
,D/ResourcesManager( 5880): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/TP/MmsProvider( 1483): Query uri=content://mms, match=0, calling pid = 5803
,D/TimaKeyStoreProvider( 5899): TimaSignature is unavailable
,D/ActivityThread( 5899): Added TimaKeyStore provider
,D/MessageDataHandler( 5803):  getInboxList mms,sms cursor join : 7
,I/MessageDataHandler( 5803): getUnreadMessageCount :0
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:71000 mC
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 181
,D/TP/MmsSmsProvider( 1483): query,matched:0, calling pid = 5803
,D/[CarModeFW]( 5803): PushMessageService-onCreate
V/TP/MmsSmsProvider( 1483): getSimpleConversations entered.
D/ResourcesManager( 5899): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/TP/MmsSmsProvider( 1483): match 0:Elapsed time : 2.518 ms
,I/ActivityManager(  805): Killing 4717:com.android.calendar/u0a150 (adj 15): bgCount ##41
,I/ActivityManager(  805): Killing 5062:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##42
,I/ActivityManager(  805): Killing 4999:com.android.email/u0a163 (adj 15): bgCount ##43
,D/[CarModeFW]( 5803): PushMessageManager-onServiceConnected
,D/[CarModeFW]( 5803): PushMessageService-registerPushMessageServiceListener
,D/TP/MmsSmsProvider( 1483): query,matched:13, calling pid = 5803
,D/TP/MmsSmsProvider( 1483): match 13:Elapsed time : 0.880 ms
,D/MessageDataHandler( 5803):  getInboxList address cursor : 5
,D/TP/MmsSmsProvider( 1483): query,matched:0, calling pid = 5803
V/TP/MmsSmsProvider( 1483): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1483): match 0:Elapsed time : 0.874 ms
,D/MessageDataHandler( 5803):  getInboxList thread cursor : 8
,D/MessageDataHandler( 5803):  thread, addr result: 1
I/[CarModeFW]( 5803): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 213
I/[CarModeFW]( 5803): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 213
,W/ContextImpl( 5899): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5916): MountEmulatedStorage()
E/Zygote  ( 5916): v2
I/libpersona( 5916): KNOX_SDCARD checking this for 10112
I/libpersona( 5916): KNOX_SDCARD not a persona
,D/ResourcesManager( 5899): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/ActivityManager(  805): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5916 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
,I/art     (  331): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 334us total 11.419ms
,D/UserAnalysis.PlaceProvider( 5880): PlaceProvider onCreate()
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.946ms
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.672ms
,I/SELinux ( 5916): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5916): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5916): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/FilterInstaller( 5899): There is no requred permission
,I/ActivityManager(  805): Killing 4803:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 5916): TimaSignature is unavailable
,D/ActivityThread( 5916): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 336
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Missed Call : 333
,D/UserAnalysis.SecureDbManager( 5880): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5880): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 5880): Create SecureDbHelper
,D/ResourcesManager( 5916): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/IntelligenceServiceApplication( 5880): onCreate()
,D/PackageIntentReceiver( 5916): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5916): Not GearManger package! 
,I/SQLiteSecureOpenHelper( 5880): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 5880): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 5880): Open Place.db in secure mode
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5933): MountEmulatedStorage()
E/Zygote  ( 5933): v2
I/libpersona( 5933): KNOX_SDCARD checking this for 10118
I/libpersona( 5933): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=5933 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  805): Killing 4268:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,I/SQLiteSecureOpenHelper( 5880): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 5880): ...getDatabaseLocked(b,b,pwd)
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
,I/SELinux ( 5933): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5933): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Favorite : 75
E/SELinux ( 5933): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 5803): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 5803): MyPlaceProvider-=============
D/[CarModeFW]( 5803): MyPlaceProvider-=============
,D/[CarModeFW]( 5803): MyPlaceProvider-=============
,D/[CarModeFW]( 5803): MyPlaceProvider-=============
,D/[CarModeFW]( 5803): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 5803): MyPlaceProvider-==============
D/[CarModeFW]( 5803): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5803): MyPlaceProvider-==============
D/[CarModeFW]( 5803): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5803): MyPlaceProvider-==============
D/[CarModeFW]( 5803): MyPlaceProvider-latitude is not valid
,I/FaceInterface( 5323): startFaceScan() : going on
D/FaceInterface( 5323): startFaceScan() is called.
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 414
,D/ContentApp( 1226): startScan() is called.
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,D/[CarMode]( 5803): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@cd15e144, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@ed1ee5ea] LOCATIONS
,D/FaceValue( 1226): mSleepTime: 800
D/FaceValue( 1226): mMaxThreadNum: 2
,D/ContentApp( 1226): startScan() is end.
D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
D/TimaKeyStoreProvider( 5933): TimaSignature is unavailable
D/ActivityThread( 5933): Added TimaKeyStore provider
,E/Zygote  ( 5948): MountEmulatedStorage()
E/Zygote  ( 5948): v2
I/libpersona( 5948): KNOX_SDCARD checking this for 10046
I/libpersona( 5948): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5948 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
,I/SELinux ( 5948): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5948): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5948): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 5803): -[snowdeer] Rec : CallLog : 62
,W/libprocessgroup(  805): failed to open /acct/uid_10149/pid_5062/cgroup.procs: No such file or directory
,W/libprocessgroup(  805): failed to open /acct/uid_1000/pid_4984/cgroup.procs: No such file or directory
,W/libprocessgroup(  805): failed to open /acct/uid_10163/pid_4999/cgroup.procs: No such file or directory
W/libprocessgroup(  805): failed to open /acct/uid_10150/pid_4717/cgroup.procs: No such file or directory
,D/ResourcesManager( 5933): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,D/TimaKeyStoreProvider( 5948): TimaSignature is unavailable
W/ResourcesManager( 5933): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityThread( 5948): Added TimaKeyStore provider
,I/ActivityManager(  805): Killing 5096:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 5948): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 5948): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/libprocessgroup(  805): failed to open /acct/uid_10046/pid_4803/cgroup.procs: No such file or directory
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,W/ContextImpl(  805): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
,D/MagazineService Version( 5933): Magazine-Administrator: 11
,I/CalendarProvider2( 5948): CalendarProvider2.onCreate() called
,D/MagazineService Version( 5933): Magazine-Provider: 14
,D/MagazineService Version( 5933): Magazine-Channel: 14
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5964): MountEmulatedStorage()
,W/libprocessgroup(  805): failed to open /acct/uid_10117/pid_4268/cgroup.procs: No such file or directory
E/Zygote  ( 5964): v2
I/libpersona( 5964): KNOX_SDCARD checking this for 10118
I/libpersona( 5964): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=5964 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 5933): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5933): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,I/SELinux ( 5964): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  805): failed to open /acct/uid_1000/pid_5096/cgroup.procs: No such file or directory
,I/SELinux ( 5964): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5964): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:73000 mC
,I/FaceInterface( 5323): startFaceScan() : going on
D/FaceInterface( 5323): startFaceScan() is called.
,E/Zygote  ( 5980): MountEmulatedStorage()
E/Zygote  ( 5980): v2
I/libpersona( 5980): KNOX_SDCARD checking this for 1000
I/libpersona( 5980): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 5964): TimaSignature is unavailable
,D/ActivityThread( 5964): Added TimaKeyStore provider
,I/MagazineService::MagazineService( 5933): [onHandleIntent] ACTION_PACKAGE_INSTALLED
I/ActivityManager(  805): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5980 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5980): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5980): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5980): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/MagazineService::MagazineService( 5933): [onHandleIntent] Send broadcast to (com.example.hello).
,D/SSRM:m  (  805): SIOP:: AP = 480, PST = 440, CUR = 300
,I/ActivityManager(  805): Killing 5129:com.sec.factory/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 5964): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 5964): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 5980): TimaSignature is unavailable
,D/ActivityThread( 5980): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
,D/ResourcesManager( 5980): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/HeadlinesChannelApplication( 5964): [onCreate]
,D/Headlines( 5964): Breath.onCreate
,D/HeadlinesCardManager( 5964): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5964): HeadlinesCardManager : ctor = image_cache size is 42MB
,D/SA Version( 5964): CardProvider Library : 14
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/art     (  805): Explicit concurrent mark sweep GC freed 15492(937KB) AllocSpace objects, 2(32KB) LOS objects, 31% free, 35MB/51MB, paused 1.866ms total 102.999ms
,D/ContentApp( 1226): startScan() is called.
D/MagazineService::CardProviderContentProvider( 5933): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/ContentApp( 1226): startScan() is end.
,D/MagazineService::CardProviderContentProvider( 5933): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5964): registerCardProvider: provider already exists.
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
,W/libprocessgroup(  805): failed to open /acct/uid_1000/pid_5129/cgroup.procs: No such file or directory
,D/Headlines( 5964): HeadlinesDataCenter ctor
,D/Headlines( 5964): HeadlinesDataCenter. mLocale = en_US
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6000): MountEmulatedStorage()
I/libpersona( 6000): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6000): v2
I/libpersona( 6000): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/HeadlinesChannelUtil( 5964): getCountryCode(): countryCode = DE
,D/HeadlinesCardManager( 5964): HeadlinesCardManager : constructor welcome :YES
,I/SELinux ( 6000): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6000): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6000): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
,I/ActivityManager(  805): Killing 4933:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6000): TimaSignature is unavailable
,D/ActivityThread( 6000): Added TimaKeyStore provider
,I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 794
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Schedule : 324
,I/[CarModeFW]( 5803): -[snowdeer] Rec : During DL app : 0
,I/[CarModeFW]( 5803): -[snowdeer] Rec : Location Sharing : 0
,I/[CarModeFW]( 5803): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 5803): -[snowdeer] Rec : getContactListFromHashMap : 0
,D/[CarModeFW]( 5803): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 802
D/ResourcesManager( 6000): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,I/ActivityManager(  805): Waited long enough for: ServiceRecord{2e6583ec u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,W/libprocessgroup(  805): failed to open /acct/uid_10078/pid_4933/cgroup.procs: No such file or directory
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 6000): Received: android.intent.action.PACKAGE_ADDED
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:76000 mC
,E/Zygote  ( 6019): MountEmulatedStorage()
E/Zygote  ( 6019): v2
I/libpersona( 6019): KNOX_SDCARD checking this for 10135
I/libpersona( 6019): KNOX_SDCARD not a persona
,W/ContextImpl( 6000): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/ActivityManager(  805): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6019 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/SELinux ( 6019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/System.out( 5835): INFO:Resource not found:/Common.properties Using default values
I/SELinux ( 6019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6019): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 6000): Enter Oncreate
,D/AcmsServiceMonitor( 6000): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 6000): creating AcmsCore
D/AcmsCore( 6000): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 6000): AcmsCore
,D/AcmsCore( 6000): init
D/AcmsCore( 6000): Looper handler is not null
,D/AcmsCore( 6000): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6000): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6000): Incrementing - Counter value: 1
D/AcmsCore( 6000): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 6000): onStartCommand
D/AcmsCertificateMngr( 6000): AcmsCertificateMngr
,D/AcmsRevocationMngr( 6000): AcmsRevocationMngr
D/AcmsService( 6000): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 6000): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 6000): Incrementing - Counter value: 2
D/AcmsService( 6000): Incremented Counter Value : onStartCommand
,D/ActivityThread( 6000): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/TimaKeyStoreProvider( 6019): TimaSignature is unavailable
,D/ActivityThread( 6019): Added TimaKeyStore provider
,D/ResourcesManager( 6019): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:73000 mC
,D/AcmsService( 6000): Inside handle Intent
D/AcmsService( 6000): App added - package name: com.example.hello
D/AcmsCore( 6000): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 6000): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 6000): Incrementing - Counter value: 3
,D/AcmsCore( 6000): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 6000): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 6000): Decrementing - Counter value: 2
,W/ResourcesManager( 6019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:79000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 5485): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:79000 mC
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6050): MountEmulatedStorage()
I/libpersona( 6050): KNOX_SDCARD checking this for 10166
E/Zygote  ( 6050): v2
I/libpersona( 6050): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=6050 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,I/SELinux ( 6050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6050): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,D/TimaKeyStoreProvider( 6050): TimaSignature is unavailable
,D/ActivityThread( 6050): Added TimaKeyStore provider
,I/GLSActivity( 1684): [ac] getting account id
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,D/ResourcesManager( 6050): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,I/GLSUser ( 1684): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/ResourcesManager( 6050): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
I/ThermalEngine(  319): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 85.0 degC
,I/ThermalEngine(  319): ACTION: OPT_CURR_REQ 1
,D/KidsPlatformStub( 6050): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6069): MountEmulatedStorage()
I/libpersona( 6069): KNOX_SDCARD checking this for 10170
E/Zygote  ( 6069): v2
I/libpersona( 6069): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6069 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,I/SELinux ( 6069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6069): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6069): TimaSignature is unavailable
,D/ActivityThread( 6069): Added TimaKeyStore provider
,D/ResourcesManager( 6069): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 6069): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,E/Zygote  ( 6084): MountEmulatedStorage()
I/libpersona( 6084): KNOX_SDCARD checking this for 10030
E/Zygote  ( 6084): v2
I/libpersona( 6084): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6084 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  805): Killing 5228:com.wsomacp/u0a25 (adj 15): bgCount ##41
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/SELinux ( 6084): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6084): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6084): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6084): TimaSignature is unavailable
,D/ActivityThread( 6084): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
,D/ResourcesManager( 6084): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/libprocessgroup(  805): failed to open /acct/uid_10025/pid_5228/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,D/Finsky  ( 6084): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
I/ThermalEngine(  319): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm cleared 1 at 74.0 degC
I/ThermalEngine(  319): ACTION: OPT_CURR_REQ 0
,I/GAV2    ( 5555): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
,D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,D/Finsky  ( 6084): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/CalendarProvider2( 5948): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:74000 mC
,I/ActivityManager(  805): Killing 5244:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6122): MountEmulatedStorage()
I/libpersona( 6122): KNOX_SDCARD checking this for 10012
E/Zygote  ( 6122): v2
I/libpersona( 6122): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6122 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:75000 mC
,I/SELinux ( 6122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  805): failed to open /acct/uid_10172/pid_5244/cgroup.procs: No such file or directory
E/SELinux ( 6122): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6084): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6084): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6122): TimaSignature is unavailable
,D/ActivityThread( 6122): Added TimaKeyStore provider
,D/ResourcesManager( 6122): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6122): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6122): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:73000 mC
,I/MultiDex( 6122): VM with version 2.1.0 has multidex support
I/MultiDex( 6122): install
I/MultiDex( 6122): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  805): Killing 5340:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,D/Finsky  ( 6084): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6084): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 6084): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1971): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/Finsky  ( 6084): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.games from APK com.google.android.gms
,V/JNIHelp ( 6122): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
,W/libprocessgroup(  805): failed to open /acct/uid_10002/pid_5340/cgroup.procs: No such file or directory
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor5:85000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor5:85000 mC
I/ThermalEngine(  319): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm raised 1 at 85.0 degC
,I/ThermalEngine(  319): ACTION: OPT_CURR_REQ 1
,I/ConfigFetchService( 1971): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1971): launchTask
,D/ResourcesManager( 1971): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ChimeraCfgMgr( 1971): Loading module com.google.android.gms.vision from APK com.google.android.gms
,V/ConfigFetchTask( 1971): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WVEVSmpBsg3AtHcJcjWTdxQQ6ddTYgfFUtm2mt36S4pRHvyAaCrgfHcJOBYXy3lwoROF5smSIzB3-Rb6ioacjaL1t1STLwQMmZORCU2BpdOGdpr-D9YbkpnChRVYNaIn-oFtHBHD9Yv3dG_vR8ewHvp0Kqj-HcJ-wwvThQuzTt0NeRx4v7p98lQxhA16GqKKlsRd1MUN-zTHSUcSX8_Ne99mdL44E0NCUIe4zgfOuZ5pGrBig
,I/GoogleURLConnFactory( 1971): Using platform SSLCertificateSocketFactory
,D/Vision  ( 1971): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1971): Failed to find package metadata for com.example.hello
,D/Vision  ( 1971): No vision deps
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6148): MountEmulatedStorage()
E/Zygote  ( 6148): v2
I/libpersona( 6148): KNOX_SDCARD checking this for 10040
I/libpersona( 6148): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6148 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/art     (  331): Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 284us total 10.550ms
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:78000 mC
,W/ActivityThread( 6122): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6122): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1c12db24: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6122): Installed default security provider GmsCore_OpenSSL
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.627ms
,E/SMD     (  298): DCD ON
,I/art     (  331): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 7.680ms
,I/SELinux ( 6148): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6148): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6148): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/PeopleContactsSync( 1971): CP2 sync disabled
,D/TimaKeyStoreProvider( 6148): TimaSignature is unavailable
,D/ActivityThread( 6148): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:82000 mC
,D/ResourcesManager( 6148): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/System.out( 1971): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1971): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1971): (HTTPLog)-Thread-241-271407067: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,W/ConfigFetchTask( 1971): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1971): fetch service done; releasing wakelock
,I/ConfigFetchService( 1971): stopping self
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/ResourcesManager( 6122): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:77000 mC
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
,I/ActivityManager(  805): Killing 5270:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,D/ResourcesManager( 6122): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/Finsky  ( 6084): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/ActivityManager(  805): Killing 5305:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,I/SettingSearchManagerReceiver( 1483): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1483): addSearchInfoDB
,W/libprocessgroup(  805): failed to open /acct/uid_10004/pid_5270/cgroup.procs: No such file or directory
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6172): MountEmulatedStorage()
,E/Zygote  ( 6172): v2
I/libpersona( 6172): KNOX_SDCARD checking this for 10168
I/libpersona( 6172): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6172 uid=10168 gids={50168, 9997} abi=armeabi-v7a
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
I/ThermalEngine(  319): TM Id 'OPT_CURR_MONITOR-TSENS6' Sensor 'tsens_tz_sensor6' - alarm raised 1 at 85.0 degC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,D/PowerManagerService(  805): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  805): Nap time (uid 1000)...
,I/PowerManagerService(  805): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  805): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  805): setDeviceInteractive: 0
D/DisplayPowerController(  805): getFinalBrightness : 1 -> 1
D/PowerManagerService(  805): [s] DisplayPowerCallbacks : onStateChanged()
,D/InputManager-JNI(  805): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  805): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI(  805): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService(  805): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  805): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  805): handleSandman : startDream()
D/InputManager-JNI(  805): sysfs_write -: /sys/class/input/event1/device/enabled: 0
E/PowerManagerService(  805): handleSandman : startDreaming, but isDreaming false
,D/SContextService(  805): 	.unregisterCallback : 1, client=
D/SContextService(  805): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@330db001, Service = Auto Rotation, used = 1
,I/PowerManagerService(  805): Sleeping (uid 1000)...
D/PowerManagerService(  805): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  805): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  805): [input device light] handleInputDeviceLightOff
,I/SELinux ( 6172): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  805): failed to open /acct/uid_10044/pid_5305/cgroup.procs: No such file or directory
,I/SELinux ( 6172): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6172): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,W/CAE     (  805): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  805): stop(ContextProvider.java:149)
,V/CAE     (  805): clear(AutoRotationRunner.java:182)
V/CAE     (  805): disable(AutoRotationRunner.java:171)
,I/CAE     (  805): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  805): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  311): sendContextData: -78, 7, 0, 0
,D/CAE     (  805): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  805): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,I/Adreno-EGL(  805): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  805): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  805): Build Date: 03/03/15 Tue
I/Adreno-EGL(  805): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  805): Remote Branch: 
I/Adreno-EGL(  805): Local Patches: 
I/Adreno-EGL(  805): Reconstruct Branch: 
,D/TimaKeyStoreProvider( 6172): TimaSignature is unavailable
,D/ActivityThread( 6172): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,D/ResourcesManager( 6172): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
,E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/CAE     (  805): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  805): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  805): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  805): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  805): removeSContextService() : service = Auto Rotation
D/SContextService(  805): ===== SContext Service List =====
,D/SContextManager(  805):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@28ec82ef, service=Auto Rotation
,D/KeyguardViewMediator( 1170): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1170): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1170): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1170): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3313): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3313): getDatabaseLocked(b,b,pwd)...
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): timeout : 5000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/CAE     (  805): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/CAE     (  805): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  805): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  805): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  311): sendContextData: -76, 13, -47, 0
,D/KeyguardViewMediator( 1170): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1170): handleNotifyScreenOff
,D/InputMethodManagerService(  805): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/DisplayPowerController(  805): ColorFade: onAnimationStart
,D/DisplayPowerController(  805): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 0
,D/MotionRecognitionService(  805):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  805):  handler : SCREEN_ON end
,D/NotificationService(  805): ACTION_SCREEN_ON
,D/LightsService(  805): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 805) 
D/LightsService(  805): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  805): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  805): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,D/lights  (  805): lcd : 0 +
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 0
,D/audio_hw_primary(  305): adev_set_parameters: enter: screen_state=on
V/voice   (  305): voice_set_parameters: enter: screen_state=on
V/voice   (  305): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  305): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  305): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  305): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  305): adev_set_parameters: exit
,I/WifiNative-HAL(  805): startHal
I/SecExternalDisplayIntents_Java(  805): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/wifi    (  805): getStaticLongField sWifiHalHandle 0x958df7fc
D/wifi    (  805): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x102222
I/WifiNative-HAL(  805): Could not start hal
D/WifiStateMachine(  805): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  805): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  805): setSuspendOptimizations: 4 false
E/WifiStateMachine(  805): mSuspendOptNeedsDisabled 4
,D/lights  (  805): lcd : 0 -
,D/BluetoothAdapter( 5527): disable()
,D/IpRemoteDisplayController(  805): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  805): Bridge Server is not available
,E/BluetoothManagerService(  805): Bluetooth is already disabled. DO NOT disable again.
,I/SettingSearchManagerReceiver( 1483): endInsert
,D/WifiService(  805): New client listening to asynchronous messages
,I/WifiManager( 5527): packageName : com.example.hello
,D/SecContentProvider(  805): uri = 18 selection = isWifiEnabled
,D/SecContentProvider2(  805): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  805): mCursor = null
,D/AssistantMenuSettingSearch( 5740): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5740): Make Setting DB
,D/PersonaManagerService(  805): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  805): MSG_ACTION_SCREEN_ON called
D/WifiService(  805): setWifiEnabled: false pid=5527, uid=10374
,E/WifiService(  805): Invoking mWifiStateMachine.setWifiEnabled
D/SettingsProvider(  805): name = wifi_on
,I/jxcore-log( 5527): ****TEST TOOK:  5049  ms ****
I/jxcore-log( 5527): 
,I/jxcore-log( 5527): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5527): 
,I/NfcService( 1477): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
E/LightSensor(  805): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  805): mCallbacks.updateBrightness()
D/DisplayPowerController(  805): getFinalBrightness : 8 -> 0
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
D/NfcService( 1477): call the applyRotuiing
,D/accuweather( 1955): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 1955): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 1955): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 1955): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 1955): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 1955): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/SurfaceWidget.Renderer( 1955): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 1955): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 1955): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 1955): [237392/6] SurfaceWidget drawing first frame
,D/DisplayPowerState(  805): !@ ColorFade entry
,D/DisplayPowerController(  805): ColorFade: onAnimationEnd
,I/SamsungIME( 1854): getNextShiftState() cursorCapsMode : 0
,D/ConnectivityService(  805): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AutomaticBrightnessController(  805): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,I/AutomaticBrightnessController(  805): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  805): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  805): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  805): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,V/AlarmManager(  805): waitForAlarm result :4
W/ContextImpl( 5740): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
,D/SensorManager(  805): unregisterListener ::   
,E/Sensors (  805): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  805): unregisterListener ::   
,D/Finsky  ( 6084): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/DisplayPowerController(  805): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  805): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  805): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SSRM:m  (  805): SIOP:: AP = 480, PST = 445, CUR = 300
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
,D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,D/LightsService(  805): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 805) 
,D/LightsService(  805): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,E/LightSensor(  805): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,D/SensorManager(  805): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  805): turn on LED for charging
V/ActivityManager(  805): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/CAE     (  805): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  805): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  805): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  805): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  311): sendContextData: -76, 13, -46, 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/CAE     (  805): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 17, 25, 56,
,D/SensorHubManager(  805): SendSensorHubData: send data = -63, 14, 17, 25, 56
D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/Sensorhubs(  311): sendContextData: -63, 14, 17, 25, 56
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/MotionRecognitionService(  805):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/AndroidRuntime( 6193): 
D/AndroidRuntime( 6193): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,E/MotionRecognitionService(  805):  handler : SCREEN_OFF end 
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:82000 mC
,D/AndroidRuntime( 6193): CheckJNI is OFF
,D/AndroidRuntime( 6193): setted country_code = Germany
,D/AndroidRuntime( 6193): setted countryiso_code = DE
,D/AndroidRuntime( 6193): setted sales_code = DBT
D/AndroidRuntime( 6193): readGMSProperty: start
D/AndroidRuntime( 6193): readGMSProperty: already setted!!
D/AndroidRuntime( 6193): readGMSProperty: end
D/AndroidRuntime( 6193): addProductProperty: start
,I/WifiNative-HAL(  805): startHal
,E/wifi    (  805): getStaticLongField sWifiHalHandle 0x958df7fc
D/wifi    (  805): halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x10224a
I/WifiNative-HAL(  805): Could not start hal
D/WifiStateMachine(  805): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  805): handleScreenStateChanged Exit: false
,D/NotificationService(  805): ACTION_SCREEN_OFF
D/LightsService(  805): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 805) 
,D/LightsService(  805): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
E/WifiStateMachine(  805): setSuspendOptimizations: 4 true
,E/WifiStateMachine(  805): mSuspendOptNeedsDisabled 0
,D/audio_hw_primary(  305): adev_set_parameters: enter: screen_state=off
V/voice   (  305): voice_set_parameters: enter: screen_state=off
V/voice   (  305): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  305): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  305): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  305): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  305): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  805): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  805): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  805): Bridge Server is not available
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,I/art     (  805): Explicit concurrent mark sweep GC freed 25852(1745KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 35MB/51MB, paused 1.283ms total 123.133ms
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1170): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF end
,D/VolumePanel( 1170): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6205): MountEmulatedStorage()
,E/Zygote  ( 6205): v2
I/libpersona( 6205): KNOX_SDCARD checking this for 10117
I/libpersona( 6205): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6205 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,E/AffinityControl( 6193): AffinityControl: registerfunction enter
,I/SELinux ( 6205): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6205): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6205): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  805): Excessive delay in setPowerMode(): 252ms
D/PowerManagerService(  805): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/AndroidRuntime( 6193): Calling main entry com.android.commands.pm.Pm
V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/MISC PowerHAL(  805): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  805): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  805): Invalid hint ID.
I/PowerManagerService(  805): [PWL] Off : 0s ago
I/QCOM PowerHAL(  805): Got set_interactive hint
I/PowerManagerService(  805): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  805): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  805): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=805, ws=WorkSource{10117}) (elapsedTime=19847)
I/PowerManagerService(  805): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1971, ws=null) (elapsedTime=13839)
I/PowerManagerService(  805): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  805): [PWL]     mDisplayReady : false
I/PowerManagerService(  805): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/DisplayPowerController(  805): getFinalBrightness : 0 -> 0
D/PowerManagerService(  805): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  805): [PWL] sb release: PowerManagerService.Display
,D/PersonaManagerService(  805): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  805): MSG_ACTION_SCREEN_OFF called
,D/PersonaManagerService(  805): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  805): START PACKAGE DELETE: observer{696873499}
D/PackageManager(  805): pkg{<packageName>}
D/PackageManager(  805): user{0}
D/PackageManager(  805): caller{2000}
D/PackageManager(  805): flags{3}
D/PersonaManagerService(  805): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  805): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  805): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  805): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/TimaKeyStoreProvider( 6205): TimaSignature is unavailable
,D/ActivityThread( 6205): Added TimaKeyStore provider
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/PackageManager(  805): [MSG] DELETE_PACKAGE_AS_USER
,D/ResourcesManager( 6205): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/NfcService( 1477): call the applyRotuiing
,D/PackageManagerService(  805): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  805): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/STATUSBAR-PhoneStatusBar( 1170):      ACTION_SCREEN_OFF is finished!!!! 
,D/ApplicationPolicy(  805): getApplicationUninstallationEnabled
D/ApplicationPolicy(  805): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager(  805): !@killApplicatoin: 10374, uninstall pkg
,W/ResourcesManager( 6205): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  805): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  805): Killing 5527:com.example.hello/u0a374 (adj 0): stop com.example.hello
,I/ActivityManager(  805):   Force finishing activity ActivityRecord{2923a839 u0 com.example.hello/.MainActivity t11}
,D/FocusedStackFrame(  805): Set to : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/StatusBar( 1170): onReceive : Intent.ACTION_SCREEN_OFF
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Recents_AlternateRecentsComponent( 1170): dismissHelpPopup 
,I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (5/8)
I/SurfaceFlinger(  249): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/accuweather( 1955): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 1955): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 1955): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WifiService(  805): Client connection lost with reason: 4
,D/ConnectivityService(  805): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  805): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/LightsService(  805): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  805): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/SensorManager(  805): unregisterListener ::   
D/lights  (  805): led_pattern : 1 +
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:79000 mC
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/lights  (  805): led_pattern : 1 -
D/LightsService(  805): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ActivityManager(  805): Force stopping com.example.hello appid=10374 user=0: pkg removed
,I/NotifUtils( 5555): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
,I/art     ( 4320): Explicit concurrent mark sweep GC freed 2996(168KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 14MB/24MB, paused 311us total 16.882ms
,I/art     ( 1565): Explicit concurrent mark sweep GC freed 14612(928KB) AllocSpace objects, 2(689KB) LOS objects, 39% free, 16MB/27MB, paused 459us total 35.058ms
,I/art     ( 5899): Explicit concurrent mark sweep GC freed 9294(429KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 1.115ms total 33.514ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  805): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 1498): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,E/SamsungIME( 1854): mOCRHelper is null
,W/GeofencerStateMachine( 1666): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  805): Reconfiguring input devices.  changes=0x00000010
,W/ResourcesManager( 1498): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1498): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1498): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager( 1498): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 1498): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1498): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Finsky  ( 6084): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,I/NotifUtils( 5555): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Books/Books.apk
,D/RegisteredServicesCache( 1477): empty dynamic service
,D/SecContentProvider2(  805): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  805): mCursor = null
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/NotifUtils( 5555): Showing notification with unreadCount of 7 and unseenCount of 7
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService(  805): Package has changed for user 0
D/EnterpriseDeviceManagerService(  805): Admin package name: com.google.android.gms
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,I/Babel   ( 6205): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6205): MmsConfig.loadMmsSettings
,I/Babel   ( 6205): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
I/Babel   ( 6205): MmsConfig.loadFromDatabase
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,E/Babel   ( 6205): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6205): MmsConfig.loadFromResources
,E/Babel   ( 6205): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6205): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/AudioCapabilities( 6205): Unsupported mime audio/evrc
,D/ResourcesManager( 6205): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/AudioCapabilities( 6205): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6205): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6205): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6205): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6205): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6205): Unsupported mime audio/x-ima
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,W/AudioCapabilities( 6205): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6205): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6205): Unsupported mime audio/evrc
,D/SSRM:a  (  805): DeviceInfo:: 000000000000
,D/SSRM:a  (  805): SettingsAirViewInfo:: 000000000
,W/VideoCapabilities( 6205): Unsupported mime video/wvc1
,D/RCPManagerService(  805): PackageReceiver onReceive()
,I/HarmonyEASService(  805): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv
,D/KnoxMUMContainerPolicy(  805): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,W/Settings( 6205): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BackupManagerService(  805): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  805): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  805): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  805): uID is 10374
V/EnterpriseBillingPolicy(  805): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  805): getProfileForApplication - enter
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/EnterpriseBillingPolicyStorage(  805): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  805): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  805): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  805): getBillingProfileForVpnEngine - start - com.example.hello
D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,V/EnterpriseBillingPolicyStorage(  805): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  805): removeObsoleteFile: deleting file=11_task.xml
,D/ConnectivityService(  805): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/VideoCapabilities( 6205): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6205): Unsupported mime video/wvc1
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6205): Unsupported mime video/x-ms-wmv8
,W/ActivityManager(  805): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  805): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  805): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  805): SIOP:: AP = 480, PST = 450, CUR = 300
D/X       (  805): broadcastSiopLevelIntent:: currentSiopLevel = 1
,W/VideoCapabilities( 6205): Unsupported mime video/mp43
,D/ConnectivityService(  805): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ContentApp( 1226):  LEVEL : 1
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/VideoCapabilities( 6205): Unsupported mime video/sorenson
,I/VideoCapabilities( 6205): Unsupported profile 4 for video/mp4v-es
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,I/GLSUser ( 1684): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1684): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1684): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1684): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1684): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,I/PeopleDatabaseHelper( 1971): cleanUpNonGplusAccounts done.
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/SQLiteLog( 6205): (284) automatic index on conversation_participants_view(conversation_id)
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
,W/Finsky  ( 6084): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/art     (  805): Explicit concurrent mark sweep GC freed 32132(2MB) AllocSpace objects, 8(128KB) LOS objects, 31% free, 35MB/51MB, paused 7.909ms total 648.575ms
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  805): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  805): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  805): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/PackageManager(  805): delete codoeFile: 
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/PackageManager(  805): result of delete: 1{696873499}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/AndroidRuntime( 6193): Shutting down VM
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:85000 mC
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  805): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  805): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  805): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:82000 mC
,D/UsbSettingsManager(  805): clearDefaults: com.example.hello
,I/CrashAnrDetector(  805): onPackageRemoved : com.example.hello
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,W/FileUtils( 1971): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/ServiceConnection( 1971): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 1971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 1971): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1284)
W/ServiceConnection( 1971): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:196)
W/ServiceConnection( 1971): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 1971): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 1971): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 1971): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 1971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1971): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 1971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 1971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 1971): 	... 7 more
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/GAV2    ( 5778): Thread[GAThread,5,main]: No campaign data found.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4473): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4473): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4473): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,D/GCM     ( 1684): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor7:85000 mC
I/ThermalEngine(  319): Sensor:tsens_tz_sensor7:85000 mC
I/ThermalEngine(  319): TM Id 'OPT_CURR_MONITOR-TSENS7' Sensor 'tsens_tz_sensor7' - alarm raised 1 at 85.0 degC
,D/AuthorizationBluetoothService( 1684): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,F/libc    ( 4473): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78bb8dd4 in tid 6269 (hIntentService])
,W/FileUtils( 1971): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/ServiceConnection( 1971): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/service.connections: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1971): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/ServiceConnection( 1971): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
W/ServiceConnection( 1971): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1284)
W/ServiceConnection( 1971): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:196)
W/ServiceConnection( 1971): 	at com.google.android.gms.common.internal.cm.b(SourceFile:80)
W/ServiceConnection( 1971): 	at com.google.android.gms.common.internal.cm.a(SourceFile:27)
W/ServiceConnection( 1971): 	at com.google.android.gms.common.internal.cn.run(SourceFile:64)
W/ServiceConnection( 1971): 	at java.lang.Thread.run(Thread.java:818)
W/ServiceConnection( 1971): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
W/ServiceConnection( 1971): 	at libcore.io.Posix.open(Native Method)
W/ServiceConnection( 1971): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/ServiceConnection( 1971): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/ServiceConnection( 1971): 	... 7 more
,F/libc    ( 4473): Failed while talking to debuggerd: Broken pipe
E/audit_log( 2089): File locking failed. error= Bad file number
,E/audit_log( 2089): File locking failed. error= Bad file number
,V/GmsCoreStatsServiceLauncher( 1971): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,F/libc    ( 6084): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa06b6fb6 in tid 6084 (android.vending)
,F/libc    ( 6084): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2089): File locking failed. error= Bad file number
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,V/BitmapFactory( 5555): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/WearableService( 5036): callingUid 10012, callindPid: 5036
,F/libc    ( 1666): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7554e7a2 in tid 3051 (Binder_4)
,F/libc    ( 1666): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2089): File locking failed. error= Bad file number
,I/ActivityManager(  805): Process com.sec.android.app.shealth (pid 4473)(adj 5) has died(116,582)
,W/ActivityManager(  805): Scheduling restart of crashed service com.sec.android.app.shealth/.cignacoach.receiver.CoachIntentService in 1000ms
,F/libc    ( 5803): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78f364ae in tid 5816 (HeapTrimmerDaem)
,F/libc    ( 5803): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2089): File locking failed. error= Bad file number
,I/EventHub(  805): Removing device '/dev/input/event4' due to inotify event
,E/lowmemorykiller(  246): Error writing /proc/1666/oom_score_adj; errno=22
,D/LocationInitializer( 1971): Restart initialization of location
,I/NotifUtils( 5555): Account: 61035162 vibrate: false
,I/NotifUtils( 5555): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,F/libc    ( 5555): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7255e0d0 in tid 6196 (IntentService[G)
,D/GpsStatusListenerHelper(  805): Remote Listener died: android.location.IGpsStatusListener$Stub$Proxy@28b1b3ae
D/LocationManagerService(  805): Location listener died
I/LocationManagerService(  805): remove a620230 by com.google.android.gms
,D/LocationManagerService(  805): Location listener died
D/LocationManagerService(  805): provider request: passive ProviderRequest[ON interval=0]
I/ActivityManager(  805): Process com.google.android.gms.persistent (pid 1666)(adj 0) has died(142,583)
,V/BackupManagerService(  805): Disconnected from transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  805): Registering transport com.google.android.gms/.backup.BackupTransportService::null = null
I/LocationManagerService(  805): remove 15de28f8 by com.google.android.gms
D/WifiService(  805): Client connection lost with reason: 4
,D/LocationManagerService(  805): provider request: passive ProviderRequest[ON interval=0]
,E/SensorService(  805): Error disabling sensor 13 (Operation not permitted)
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:82000 mC
,W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/.backup.BackupTransportService in 1000ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/.common.stats.GmsCoreStatsService in 11000ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.fused.FusedLocationService in 21000ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.network.NetworkLocationService in 31000ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.server.GoogleLocationService in 41000ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.geocode.GeocodeService in 51000ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/.deviceconnection.service.DeviceConnectionServiceBroker in 61000ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService in 71000ms
,I/Zygote  (  331): Process 4473 exited due to signal (7)
F/libc    ( 5555): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2089): File locking failed. error= Bad file number
,I/ActivityManager(  805): Process com.android.vending (pid 6084)(adj 5) has died(143,583)
,W/ActivityManager(  805): Scheduling restart of crashed service com.android.vending/com.google.android.finsky.services.DailyHygiene in 80995ms
,F/libc    ( 6122): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f945000 in tid 6122 (android.gms:car)
F/libc    ( 6122): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2089): File locking failed. error= Bad file number
,I/EventHub(  805): Removing device '/dev/input/event5' due to inotify event
,I/ActivityManager(  805): Process com.sec.android.automotive.drivelink (pid 5803)(adj 15) has died(152,583)
,I/Zygote  (  331): Process 1666 exited due to signal (7)
,I/Zygote  (  331): Process 6084 exited due to signal (7)
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,I/ActivityManager(  805): Process com.google.android.gms:car (pid 6122)(adj 0) has died(166,583)
,I/ActivityManager(  805): Process com.google.android.gm (pid 5555)(adj 5) has died(176,583)
,W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gm/.GmailIntentService in 80925ms
,I/Zygote  (  331): Process 5803 exited due to signal (7)
,I/Zygote  (  331): Process 6122 exited due to signal (7)
,I/Zygote  (  331): Process 5555 exited due to signal (7)
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor8:85000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor8:85000 mC
I/ThermalEngine(  319): TM Id 'OPT_CURR_MONITOR-TSENS8' Sensor 'tsens_tz_sensor8' - alarm raised 1 at 85.0 degC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:80000 mC
,I/EventHub(  805): Removing device '/dev/input/event6' due to inotify event
,F/libc    ( 1684): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e5b3bb2 in tid 1684 (e.process.gapps)
F/libc    ( 1684): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2089): File locking failed. error= Bad file number
,I/EventHub(  805): Removing device '/dev/input/event7' due to inotify event
,I/ActivityManager(  805): Process com.google.process.gapps (pid 1684)(adj 0) has died(191,583)
,W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 80824ms
,W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 90823ms
W/ActivityManager(  805): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 100823ms
,F/libc    ( 5835): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb4bee61c in tid 5848 (HeapTrimmerDaem)
,F/libc    ( 5835): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2089): File locking failed. error= Bad file number
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  805): checkUser: useridlist=null, currentuser=0
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:81000 mC
,E/Zygote  ( 6274): MountEmulatedStorage()
E/Zygote  ( 6274): v2
I/libpersona( 6274): KNOX_SDCARD checking this for 10012
I/libpersona( 6274): KNOX_SDCARD not a persona
,I/ActivityManager(  805): Start proc com.google.process.gapps for broadcast com.google.android.gms/.gcm.nts.SchedulerReceiver: pid=6274 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/EventHub(  805): Removing device '/dev/input/event8' due to inotify event
,I/Zygote  (  331): Process 1684 exited due to signal (7)
,I/SELinux ( 6274): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6274): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  805): Process com.vlingo.midas (pid 5835)(adj 15) has died(212,583)
,F/libc    ( 6274): Fatal signal 7 (SIGBUS), code 2, fault addr 0x72e2e680 in tid 6274 (e.process.gapps)
,F/libc    ( 6274): Unable to open connection to debuggerd: Connection refused
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:87000 mC
,I/EventHub(  805): Removing device '/dev/input/event9' due to inotify event
,I/Zygote  (  331): Process 5835 exited due to signal (7)
,E/audit_log( 2089): File locking failed. error= Bad file number
,I/EventHub(  805): Removing device '/dev/input/event10' due to inotify event
,I/Zygote  (  331): Process 6274 exited due to signal (7)
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:88000 mC
,D/AcmsKeyStoreHelper( 6000):  getKeyStoreForApplication Enter
,F/libc    ( 6000): Fatal signal 7 (SIGBUS), code 2, fault addr 0x735e3101 in tid 6028 (AcmsHandlerThre)
,F/libc    ( 6000): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2089): File locking failed. error= Bad file number
,I/EventHub(  805): Removing device '/dev/input/event11' due to inotify event
,I/ActivityManager(  805): Process ACMS.Process (pid 6000)(adj 5) has died(221,583)
,W/ActivityManager(  805): Scheduling restart of crashed service com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService in 110640ms
,I/Zygote  (  331): Process 6000 exited due to signal (7)
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:83000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor7:75000 mC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor7:75000 mC
I/ThermalEngine(  319): TM Id 'OPT_CURR_MONITOR-TSENS7' Sensor 'tsens_tz_sensor7' - alarm cleared 1 at 75.0 degC
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC
,E/SMD     (  298): DCD ON
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,I/ThermalEngine(  319): Sensor:tsens_tz_sensor6:84000 mC

```
