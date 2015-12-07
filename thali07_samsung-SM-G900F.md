#### Test 50242285e132180_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
I/SystemInfo( 5352): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 5352): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 5352): [START] DocumentService startDocumentService
D/GalleryCacheReady( 5284): handleMeidaScanFinish()
D/FaceInterface( 5284): requestFaceScan() is called.
I/DocumentService( 5352): DocumentService onCreate ... service
I/FaceInterface( 5284): startFaceScan() : waiting 5 sec
W/LocalSuggestAlbumData( 5284): query fail: 
W/LocalSuggestAlbumData( 5284): query fail: 
W/ContextImpl( 5352): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/ContextImpl( 5352): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
--------- beginning of system
E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
E/SystemInfo( 5352): [SIOP LEVEL] : 0
I/art     (  847): Explicit concurrent mark sweep GC freed 21846(1451KB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 1.354ms total 73.685ms
I/DocumentService( 5352): [BEGIN SYNC] DocumentService beginIndexing :16
D/GalleryCacheReady( 5284): Receive : home resume
D/Mms/UIEventReceiver( 5144): ui event
E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5352): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,W/BroadcastQueue(  847): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5385): MountEmulatedStorage()
E/Zygote  ( 5385): v2
I/libpersona( 5385): KNOX_SDCARD checking this for 10094
I/libpersona( 5385): KNOX_SDCARD not a persona
W/System.err( 5325): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
I/ActivityManager(  847): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5385 uid=10094 gids={50094, 9997} abi=armeabi-v7a
W/System.err( 5325): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 5325): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 5325): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 5325): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 5325): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 5325): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 5325): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 5325): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 5325): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 5325): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 5325): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 5325): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 5325): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 5325): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5325): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5325): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5325): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5325): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5325): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5325): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5325): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
I/SELinux ( 5385): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SL_DEBUG( 5325): isLoggable:: isProductShip = 1
I/SELinux ( 5385): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/SL_DEBUG( 5325): isLoggable:: SL_DEBUG_EXIST = false
E/SELinux ( 5385): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
E/File    ( 5352): fail readDirectory() errno=13
E/File    ( 5352): fail readDirectory() errno=13
I/SystemInfo( 5352): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5352): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 5352): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :75
E/DocumentService( 5352): [THUMBNAIL] Total Time taken for each file :0
E/        ( 5352): [INDEX] Total time taken for each file :0
I/DocumentService( 5352): DocumentService onDestroy start
I/DocumentService( 5352): DocumentService onDestroy end
D/TimaKeyStoreProvider( 5385): TimaSignature is unavailable
I/SLinkClient( 5284): queryDevices : cursor.getCount() = [ 0 ]
D/ActivityThread( 5385): Added TimaKeyStore provider
D/SLinkClient( 5284): onStorageUpdated(), uri = [ slink://slink ]
W/art     ( 5325): No such thread id for suspend: 11
I/DocumentService( 5352): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 5352): InterruptedException: null
I/SystemInfo( 5352): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 5352): DocumentService cleanupEverything end
I/Process ( 5352): Sending signal. PID: 5352 SIG: 9
I/SLinkClient( 5284): SlinkBackgroundJob: slink wake up ok!
D/ResourcesManager( 5385): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
W/ResourcesManager( 5385): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager(  847): Process com.samsung.indexservice (pid 5352)(adj 11) has died(55,659)
E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5325): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/Zygote  ( 5409): MountEmulatedStorage()
E/Zygote  ( 5409): v2
I/libpersona( 5409): KNOX_SDCARD checking this for 10103
I/libpersona( 5409): KNOX_SDCARD not a persona
I/ActivityManager(  847): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5409 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 5409): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5409): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5409): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
E/Vold    (  249): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5325): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
V/Transcoder( 5325): Transcoder(0xaee08830)::constructor
V/Transcoder( 5325): addObitRecipient
V/TMI-JNI ( 5325): Mobile Transcoder JNI version 1.6.0/20131120/4.4
D/TimaKeyStoreProvider( 5409): TimaSignature is unavailable
D/ActivityThread( 5409): Added TimaKeyStore provider
D/ResourcesManager( 5409): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
W/ResourcesManager( 5409): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5409): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
D/ConnectivityService(  847): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5429): MountEmulatedStorage()
I/libpersona( 5429): KNOX_SDCARD checking this for 10113
E/Zygote  ( 5429): v2
I/libpersona( 5429): KNOX_SDCARD not a persona
I/ActivityManager(  847): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=5429 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/art     ( 1683): Explicit concurrent mark sweep GC freed 10588(574KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 17MB/29MB, paused 398us total 39.910ms
D/AndroidRuntime( 5400): 
D/AndroidRuntime( 5400): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/SELinux ( 5429): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/AndroidRuntime( 5400): CheckJNI is OFF
I/SELinux ( 5429): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5429): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/AndroidRuntime( 5400): setted country_code = Germany
D/AndroidRuntime( 5400): setted countryiso_code = DE
D/AndroidRuntime( 5400): setted sales_code = DBT
D/AndroidRuntime( 5400): readGMSProperty: start
D/AndroidRuntime( 5400): readGMSProperty: already setted!!
D/AndroidRuntime( 5400): readGMSProperty: end
D/AndroidRuntime( 5400): addProductProperty: start
I/ActivityManager(  847): Killing 4163:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
D/PowerManagerService(  847): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  847): getFinalBrightness : 1 -> 1
D/PowerManagerService(  847): [s] DisplayPowerCallbacks : onStateChanged()
D/TimaKeyStoreProvider( 5429): TimaSignature is unavailable
D/ActivityThread( 5429): Added TimaKeyStore provider
D/DisplayPowerController(  847): getFinalBrightness : 1 -> 1
D/lights  (  847): lcd : 1 +
D/ResourcesManager( 5429): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
D/lights  (  847): lcd : 1 -
D/DisplayPowerController(  847): getFinalBrightness : 1 -> 1
I/MediaStoreImporter( 5092): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  847): Killing 4315:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
W/libprocessgroup(  847): failed to open /acct/uid_10033/pid_4163/cgroup.procs: No such file or directory
W/GeoLookout( 5429): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
I/GeoLookout( 5429): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
W/libprocessgroup(  847): failed to open /acct/uid_10091/pid_4315/cgroup.procs: No such file or directory
D/SettingsProvider(  847): name = safetycare_geolookout_registering
D/SettingsProvider(  847): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  847): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  847): selectionArgs: false
D/SettingsProvider(  847): selectionArgs: 10113
D/SecContentProvider(  847): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  847): ret = -1
D/GeoLookout( 5429): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
V/TaskCloserActivity( 5060): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
I/ActivityManager(  847): Killing 4334:com.samsung.helphub/1000 (adj 15): bgCount ##41
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 5400): AffinityControl: registerfunction enter
E/Zygote  ( 5457): MountEmulatedStorage()
I/libpersona( 5457): KNOX_SDCARD checking this for 10114
E/Zygote  ( 5457): v2
I/libpersona( 5457): KNOX_SDCARD not a persona
I/ActivityManager(  847): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5457 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AndroidRuntime( 5400): Calling main entry com.android.commands.am.Am
E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
I/SELinux ( 5457): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5457): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5457): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
E/PersonaManagerService(  847): inState():  stateMachine is null !!
V/ApplicationPolicy(  847): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  847): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  847): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/CustomFrequencyManagerService(  847): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 847  pkgName : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  847): mDVFSHelper.acquire()
D/FocusedStackFrame(  847): Set to : 0
D/TimaKeyStoreProvider( 5457): TimaSignature is unavailable
D/ActivityThread( 5457): Added TimaKeyStore provider
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_4334/cgroup.procs: No such file or directory
D/Launcher.HomeView( 1481): onPause
D/Launcher( 1481): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 5400): Shutting down VM
I/DBG_DM  ( 3472): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 12 sec
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  250): id=12 createSurf (1x1),1 flag=404, Starting com.example.hello
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
E/Zygote  ( 5474): MountEmulatedStorage()
I/libpersona( 5474): KNOX_SDCARD checking this for 10374
D/LockPatternUtilsCache( 1171): value : false
I/libpersona( 5474): KNOX_SDCARD not a persona
E/Zygote  ( 5474): v2
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/ActivityManager(  847): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=5474 uid=10374 gids={50374, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 5474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5474): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5457): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 5474): TimaSignature is unavailable
D/ActivityThread( 5474): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/MicrophoneInputStream( 1549): mic_close gfk@32701577
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  847): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/Launcher.HomeView( 1481): onStop
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2265): [237392/6] Surface widget pause on instance = 1
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2265): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1481): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/accuweather( 2265): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2265): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2265): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
E/ActivityThread( 1481): Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1481): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.sec.android.app.launcher/com.android.launcher2.Launcher}
E/ActivityThread( 1481): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3743)
E/ActivityThread( 1481): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3824)
E/ActivityThread( 1481): 	at android.app.ActivityThread.access$1200(ActivityThread.java:172)
E/ActivityThread( 1481): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1451)
E/ActivityThread( 1481): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1481): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 1481): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 1481): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 1481): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 1481): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 1481): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/AudioPolicyManager(  292): stopInput() input 26
D/SurfaceWidgetView( 1481): destroyHardwareResources():50998773
V/AudioPolicyManager(  292): releaseInput() 26
V/AudioPolicyManager(  292): closeInput(26)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/StatusBarManagerService(  847): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/HotwordRecognitionRnr( 1549): Hotword detection finished
V/audio_hw_primary(  292): in_standby: enter
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/HotwordRecognitionRnr( 1549): Stopping hotword detection.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/accuweather( 2265): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2265): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/ConnectivityService(  847): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 5474): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/audio_hw_primary(  292): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  292): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  292): disable_audio_route: reset mixer path: audio-record
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): disable_audio_route: exit
V/audio_hw_primary(  292): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: DEC2 Volume
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): Setting mixer control: SLIM TX7 MUX, value: 0
E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
D/audio_route(  292): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): Setting mixer control: DEC2 MUX, value: 0
D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): stop_input_stream: exit: status(0)
V/audio_hw_primary(  292): in_standby: exit:  status(0)
V/audio_hw_primary(  292): adev_close_input_stream
V/audio_hw_primary(  292): in_standby: enter
V/audio_hw_primary(  292): in_standby: exit:  status(0)
E/audio_hw_primary(  292): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  292): releaseInput() exit
D/SurfaceWidgetView( 1481): destroyHardwareResources():50998773
I/ActivityManager(  847): Activity reported stop, but no longer stopping: ActivityRecord{30c3ccd3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9}
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/WebViewFactory( 5474): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
D/ResourcesManager( 5474): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/ActivityManager(  847): Waited long enough for: ServiceRecord{6c4fdc u0 com.sec.android.service.sm/.service.SecurityManagerService}
I/LibraryLoader( 5474): Loading: webviewchromium
I/LibraryLoader( 5474): Time to load native libraries: 1 ms (timestamps 1364-1365)
I/LibraryLoader( 5474): Expected native library version number "",actual native library version number ""
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Gmail   ( 5457): getAccountsCursor
V/WebViewChromiumFactoryProvider( 5474): Binding Chromium to main looper Looper (main, tid 1) {26eb72c9}
I/LibraryLoader( 5474): Expected native library version number "",actual native library version number ""
I/chromium( 5474): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/BrowserStartupController( 5474): Initializing chromium process, renderers=0
W/art     ( 5474): Attempt to remove local handle scope entry from IRT, ignoring
V/AlarmManager(  847): waitForAlarm result :4
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/chromium( 5474): [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/chromium( 5474): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 5474): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 5474): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
W/GAV2    ( 5457): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/BluetoothAdapter( 5474): 531582414: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 5474): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5474): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 5474): Build Date: 03/03/15 Tue
I/Adreno-EGL( 5474): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 5474): Remote Branch: 
I/Adreno-EGL( 5474): Local Patches: 
I/Adreno-EGL( 5474): Reconstruct Branch: 
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  847): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Gmail   ( 5457): Observing account changes for notifications
W/ActivityManager(  847): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  847): Waited long enough for: ServiceRecord{5c8dc8 u0 com.samsung.android.providers.context/.ContextService}
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/chromium( 5474): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/chromium( 5474): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
W/art     ( 5474): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5474): onDetachedFromWindow called when already detached. Ignoring
E/Gmail   ( 5457): Error finding the version of the Email provider.....
E/Gmail   ( 5457): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5457): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:135)
E/Gmail   ( 5457): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 5457): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 5457): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5457): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5457): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 5457): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Gmail   ( 5457): getAccountsCursor
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/EmailMigration( 5457): We do not support migrating this version of the Email provider.
V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  847): Killing 4361:com.zalando.samsung.provider/u0a192 (adj 15): bgCount ##41
D/SystemWebViewEngine( 5474): CordovaWebView is running on device made by: samsung
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/HomeSyncInstallReceiver( 1461): This pkg do not need BT addr. Do nothing
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
W/art     ( 5474): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5474): Attempt to remove local handle scope entry from IRT, ignoring
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Zygote  ( 5530): MountEmulatedStorage()
I/libpersona( 5530): KNOX_SDCARD checking this for 10015
E/Zygote  ( 5530): v2
I/libpersona( 5530): KNOX_SDCARD not a persona
I/ActivityManager(  847): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5530 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 5530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5530): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/libprocessgroup(  847): failed to open /acct/uid_10192/pid_4361/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 5530): TimaSignature is unavailable
D/ActivityThread( 5530): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/Activity( 5474): performCreate Call secproduct feature valuefalse
D/Activity( 5474): performCreate Call debug elastic valuetrue
E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/OpenGLRenderer( 5474): Render dirty regions requested: true
D/ResourcesManager( 5530): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
I/ActivityManager(  847): Waited long enough for: ServiceRecord{1b3b4647 u0 com.android.settings/.wifi.WifiCredService}
D/ActivityManager(  847): post active user change for 0
D/KnoxTimeoutHandler(  847): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  847): handleActiveUserChange for user 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  250): id=13 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/ResourcesManager( 1998): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
E/SQLiteLog( 5457): (283) recovered 522 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/OpenGLRenderer( 5474): Initialized EGL, version 1.4
I/OpenGLRenderer( 5474): HWUI protection enabled for context ,  &this =0xa1853060 ,&mEglDisplay = 1 , &mEglConfig = 8 
D/OpenGLRenderer( 5474): Enabling debug mode 0
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 5561): MountEmulatedStorage()
I/libpersona( 5561): KNOX_SDCARD checking this for 10016
E/Zygote  ( 5561): v2
I/libpersona( 5561): KNOX_SDCARD not a persona
I/ActivityManager(  847): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=5561 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
I/SELinux ( 5561): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1171): value : false
I/SELinux ( 5561): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5561): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager(  847): Killing 4376:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  250): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/9)
I/SurfaceFlinger(  250): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/9)
D/InputMethodManagerService(  847): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 5561): TimaSignature is unavailable
D/ActivityThread( 5561): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
I/ActivityManager(  847): Waited long enough for: ServiceRecord{34dbffe3 u0 com.android.settings/.wifi.hs20.Hs20UtilityService}
W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/File    ( 5457): fail readDirectory() errno=2
I/ActivityManager(  847): Displayed com.example.hello/.MainActivity: +676ms
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Timeline( 5474): Timeline: Activity_idle id: android.os.BinderProxy@3139a039 time:41811
E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
D/ResourcesManager( 5561): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
I/Gmail   ( 5457): getAccountsCursor
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ResourcesManager( 5561): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
W/ResourcesManager( 5561): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
I/Gmail   ( 5457): notifyAccountChanged
V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_4376/cgroup.procs: No such file or directory
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5457): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/chromium( 5474): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 5474): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/GroupCast_FileTools( 5561): [getDirectoryForImageResized : 295] cleaning!!
W/System.err( 5561): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
W/System.err( 5561): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 5561): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 5561): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 5561): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5561): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5561): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5561): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5561): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5561): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5561): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5561): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5561): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5561): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5561): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
I/Gmail   ( 5457): getAccountsCursor
E/Zygote  ( 5583): MountEmulatedStorage()
I/libpersona( 5583): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5583): v2
I/libpersona( 5583): KNOX_SDCARD not a persona
I/ActivityManager(  847): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5583 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/JsMessageQueue( 5474): Set native->JS mode to OnlineEventsBridgeMode
I/ActivityManager(  847): Killing 4412:com.LocalFota/u0a120 (adj 15): bgCount ##41
I/SELinux ( 5583): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/chromium( 5474): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 5474): 
I/SELinux ( 5583): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5583): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/TimaKeyStoreProvider( 5583): TimaSignature is unavailable
W/libprocessgroup(  847): failed to open /acct/uid_10120/pid_4412/cgroup.procs: No such file or directory
D/ActivityThread( 5583): Added TimaKeyStore provider
E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/CustomFrequencyManagerService(  847): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 847  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  847): mDVFSHelper.release()
D/ResourcesManager( 5583): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/CustomFrequencyManagerService(  847): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 847  pkgName : ACTIVITY_RESUME_BOOSTER@10
I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{1372f116 u0 com.example.hello/.MainActivity t11} time:42009
I/ActivityManager(  847): Killing 4451:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  250): id=12 Removed Starting com.example.hello (6/8)
I/SurfaceFlinger(  250): id=12 Removed Starting com.example.hello (-2/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/PCWCLIENTTRACE_LOG( 5583): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 5583): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 5583): new DMDBOpenHelper instance
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
E/Adreno-ES20( 5474): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 5474): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
I/PCWCLIENTTRACE_PushUtil( 5583): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 5583): sales region : global
I/PCWCLIENTTRACE_PushUtil( 5583): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 5583): [onReceive] - android.intent.action.PACKAGE_ADDED
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_4451/cgroup.procs: No such file or directory
I/ActivityManager(  847): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=5598 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  847): Killing 4474:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
E/Zygote  ( 5598): MountEmulatedStorage()
E/Zygote  ( 5598): v2
I/libpersona( 5598): KNOX_SDCARD checking this for 10034
I/libpersona( 5598): KNOX_SDCARD not a persona
I/SELinux ( 5598): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5598): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5598): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  847): failed to open /acct/uid_10138/pid_4474/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3472): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 13 sec
,D/jxcore_app_log( 5474): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1359588480
,D/JX-Cordova( 5474): jxcore cordova android initializing
,D/TimaKeyStoreProvider( 5598): TimaSignature is unavailable
,D/ActivityThread( 5598): Added TimaKeyStore provider
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 5598): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,W/jxcore-log( 5474): Initializing JXcore engine
W/jxcore-log( 5474): JXcore engine is ready
,W/jxcore-log( 5474): Starting JXcore engine
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
W/ResourcesManager( 5598): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/ResourcesManager( 5598): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/ResourcesManager( 5598): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager( 5598): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager( 5598): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 5598): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
E/auditd  ( 2095): In denial and Property audit_ondenial is set to 1 
D/SecurityLogAgent:SEDenialService(  847): Got Modify Event and sending Denial Intent foraudit.log
,W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/SecurityLogAgent:SEDenialService(  847): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 5598): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 5598): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService(  847): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 847  tag : ACTIVITY_RESUME_BOOSTER@10
,W/jxcore-log( 5474): Platform android
W/jxcore-log( 5474): 
W/jxcore-log( 5474): Process ARCH arm
W/jxcore-log( 5474): 
,I/jxcore-log( 5474): JXcore Cordova bridge is ready!
I/jxcore-log( 5474): 
,W/jxcore-log( 5474): JXcore engine is started
,I/SA      ( 4951): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 4951): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
I/SA      ( 4951): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10374 extra.user_handle.:0 ]
,E/jxcore-log( 5474): >> samsung-SM-G900F
E/jxcore-log( 5474): 
,I/ActivityManager(  847): Killing 4507:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
I/jxcore-log( 5474): Total memory 1787449344
I/jxcore-log( 5474): 
I/jxcore-log( 5474): Free memory 51527680
I/jxcore-log( 5474): 
I/jxcore-log( 5474): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5474): 
I/jxcore-log( 5474): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 5474): 
,I/jxcore-log( 5474): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 5474): 
I/jxcore-log( 5474): Size 1080 1920
I/jxcore-log( 5474): 
,I/jxcore-log( 5474): Screen Brightness 134
I/jxcore-log( 5474): 
,E/jxcore-log( 5474): Dummy Error Log.
E/jxcore-log( 5474): 
,D/Mms/FreeMessageReceiver( 5144): onReceive, action : android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 3714): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1796 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,D/Mms/FreeMessageReceiverService( 5144): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 5144): onHandleIntent: ACTION_PACKAGE_ADDED
,W/libprocessgroup(  847): failed to open /acct/uid_10143/pid_4507/cgroup.procs: No such file or directory
,E/Zygote  ( 5619): MountEmulatedStorage()
I/libpersona( 5619): KNOX_SDCARD checking this for 10051
E/Zygote  ( 5619): v2
I/libpersona( 5619): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=5619 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/SELinux ( 5619): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5619): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5619): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Process ( 3714): Sending signal. PID: 3714 SIG: 9
,I/DBG_DM  ( 3472): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(522/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3472): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(526/onReceive)] status  = 1
,E/DBG_DM  ( 3472): [com.wssyncmldm.IllIlIIIIlIIlIIIllIl(537/onReceive)] Device is ok
,I/DBG_DM  ( 3472): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.example.hello.MainActivity
D/TimaKeyStoreProvider( 5619): TimaSignature is unavailable
D/ActivityThread( 5619): Added TimaKeyStore provider
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,I/ActivityManager(  847): Process com.sec.android.app.sysscope (pid 3714)(adj 0) has died(60,649)
D/ResourcesManager( 5619): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 5619): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5619): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/MyFiles ( 5619): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/TactileAssist(  847): enable value -1
I/TactileAssist(  847): internal enable value -1
I/TactileAssist(  847): intensity value -1
I/TactileAssist(  847): saveAppList value true
,I/TactileAssist(  847): List of disabled apps :
,I/TactileAssist(  847): de.zalando.mobile
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/installd(  298): system dir 0 : /system/app/
E/installd(  298): system dir 1 : /system/priv-app/
E/installd(  298): system dir 2 : /vendor/app/
E/installd(  298): system dir 3 : /oem/app/
,E/Zygote  ( 5642): MountEmulatedStorage()
,E/Zygote  ( 5642): v2
I/libpersona( 5642): KNOX_SDCARD checking this for 10058
I/libpersona( 5642): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=5642 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 279us total 13.128ms
,I/SELinux ( 5642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 7.570ms
,E/SELinux ( 5642): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/PackageManager(  847): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 248us total 9.715ms
,D/TimaKeyStoreProvider( 5642): TimaSignature is unavailable
,D/ActivityThread( 5642): Added TimaKeyStore provider
,D/ResourcesManager( 5642): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 5642): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 5642): onReceive() it will make start service
,D/Compatibility( 5642): onHandleIntent()
,D/Compatibility( 5642): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10374, android.intent.extra.user_handle=0}]
,D/Compatibility( 5642): found: 2
,D/Compatibility( 5642): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 5642): skipping ResolveInfo{83536cd com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 5642): considering ResolveInfo{24e8fb82 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 5642): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 5642): enabling receiver ResolveInfo{3c60e293 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,I/UpdateIcingCorporaServi( 1549): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
D/Compatibility( 5642): enabling receiver ResolveInfo{afb72d0 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 5642): enabling receiver ResolveInfo{26eb72c9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 5642): enabling receiver ResolveInfo{1faf4dce com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 5642): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/Zygote  ( 5661): MountEmulatedStorage()
E/Zygote  ( 5661): v2
I/libpersona( 5661): KNOX_SDCARD checking this for 1000
I/libpersona( 5661): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=5661 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5661): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5661): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5661): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5661): TimaSignature is unavailable
,D/ActivityThread( 5661): Added TimaKeyStore provider
,I/art     (  847): Explicit concurrent mark sweep GC freed 23930(1524KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 35MB/51MB, paused 1.068ms total 79.242ms
,D/ResourcesManager( 5661): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/ResourcesManager( 1998): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,W/ContextImpl( 5661): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5680): MountEmulatedStorage()
E/Zygote  ( 5680): v2
I/libpersona( 5680): KNOX_SDCARD checking this for 10086
I/libpersona( 5680): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.chaton for broadcast com.sec.chaton/.receiver.PublicPushClientChangedReceiver: pid=5680 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5680): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  847): Killing 4537:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,I/SELinux ( 5680): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5680): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5680): TimaSignature is unavailable
,D/ActivityThread( 5680): Added TimaKeyStore provider
,D/ResourcesManager( 5680): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 5680): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5474): getBuffer is called!!!!
I/jxcore-log( 5474): 
,D/PushModule( 5680): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 5680): [PushClientApplication] (main) PushModule version: 0.9.01.12
D/PushModule( 5680): [PushClientApplication] (main) Discovered public push client. disable in app push client.
W/libprocessgroup(  847): failed to open /acct/uid_10012/pid_4537/cgroup.procs: No such file or directory
D/ChatON  ( 5680): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 5680): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
W/ActivityManager(  847): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,I/DBG_DM  ( 3472): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 14 sec
,D/ConnectivityService(  847): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3472): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
D/ConnectivityService(  847): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DBG_DM  ( 3472): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
D/ChatON  ( 5680): [1][a] ChatONV isn't installed.
D/ChatON  ( 5680): [1][a] ChatONVPlugIn.isAvailable()
,E/DBG_DM  ( 3472): [llIlIIIIlllIlllllIll(232/llIIIIlllllIIllIIllI)] Network Status is not ready. DM Not Initialized
,I/DBG_DM  ( 3472): [com.wssyncmldm.XDMService(809/llIlIIIIlIIIIIlIlIII)] TopActivity : com.example.hello.MainActivity
,D/ResourcesManager( 1549): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/UpdateIcingCorporaServi( 1549): UpdateCorporaTask done [took 455 ms] updated apps [took 455 ms] 
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5700): MountEmulatedStorage()
E/Zygote  ( 5700): v2
I/libpersona( 5700): KNOX_SDCARD checking this for 10098
I/libpersona( 5700): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5700 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 4391:com.android.vending/u0a30 (adj 15): bgCount ##41
,I/SELinux ( 5700): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5700): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5700): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5700): TimaSignature is unavailable
,W/libprocessgroup(  847): failed to open /acct/uid_10030/pid_4391/cgroup.procs: No such file or directory
,D/ActivityThread( 5700): Added TimaKeyStore provider
,D/ResourcesManager( 5700): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/DocsApplication( 5700): Installing DEX configuration.
,D/DexInstaller( 5700): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 5700): Provided clientMode=RELEASE, packageInfo=PackageInfo{2e97464 com.google.android.apps.docs}
,D/TAG     ( 5700): onCreate()
,D/CrossAppStateProvider( 5700): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/SMD     (  287): DCD ON
,E/Watchdog(  847): !@Sync 1
,D/SettingsProvider(  847): name = audio_safe_volume_state
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5725): MountEmulatedStorage()
E/Zygote  ( 5725): v2
I/libpersona( 5725): KNOX_SDCARD checking this for 10099
I/libpersona( 5725): KNOX_SDCARD not a persona
,I/SELinux ( 5725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  847): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=5725 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,E/SELinux ( 5725): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  847): Killing 4519:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
,W/GAV2    ( 5700): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 5725): TimaSignature is unavailable
,D/ActivityThread( 5725): Added TimaKeyStore provider
,D/ResourcesManager( 5725): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 5725): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  847): failed to open /acct/uid_10017/pid_4519/cgroup.procs: No such file or directory
,E/[CarMode]( 5725): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 5725): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 5725): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5756): MountEmulatedStorage()
E/Zygote  ( 5756): v2
I/libpersona( 5756): KNOX_SDCARD checking this for 10033
I/libpersona( 5756): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=5756 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 5756): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5756): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5756): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 5756): TimaSignature is unavailable
,D/ActivityThread( 5756): Added TimaKeyStore provider
,D/ResourcesManager( 5756): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 5756): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,I/System.out( 5756): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 5756): Inside WakeupProvider
,E/DatabaseUtils( 5756): Writing exception to parcel
E/DatabaseUtils( 5756): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5756): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5756): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5756): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5756): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5756): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5756): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5756): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5756): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5756): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5756): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 5725): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 5725): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5725): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5725): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5725): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5725): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5725): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5725): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5725): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5725): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 5725): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 5725): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 5725): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 5725): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 5725): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 5725): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5725): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5725): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5725): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5725): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5725): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5725): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5725): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5725): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5725): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5725): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/VlingoApplication( 5756): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
E/DatabaseUtils( 5756): Writing exception to parcel
E/DatabaseUtils( 5756): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 5756): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 5756): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 5756): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 5756): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 5756): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 5756): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 5756): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 5756): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 5756): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 5756): 	at android.os.Binder.execTransact(Binder.java:446)
W/System.err( 5725): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 5725): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 5725): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 5725): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 5725): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 5725): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 5725): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 5725): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 5725): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 5725): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 5725): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 5725): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 5725): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 5725): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 5725): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 5725): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 5725): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 5725): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 5725): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5725): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 5725): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 5725): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5725): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5725): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 5725): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 5725): [DLApplication]-Init Called!:false
E/[CarMode]( 5725): [DLApplication]-Init Started!:true
I/[CarModeFW]( 5725): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 5725): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 5725): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 5725): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 5725): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 5725): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 5725): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 5725): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 5725): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 5725): ### android.os.Looper::loop(145)
I/[CarModeFW]( 5725): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 5725): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 5725): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 5725): ### com.android.internal.os.ZygoteInit::main(1194)
D/BluetoothAdapter( 5756): 695256702: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5756): 695256702: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5756): 695256702: getState() :  mService = null. Returning STATE_OFF
I/VlingoAndroidCore( 5756): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MessageDataHandler( 5725): initialize
W/GAV2    ( 5700): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/PackageManager(  847): [MSG] SEND_PENDING_BROADCAST
D/[CarModeFW]( 5725): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 5725): CDH-initiazlieCaches : after sync
D/ResourcesManager(  847): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager( 1481): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,V/BitmapFactory( 1481): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_settings_icon.png
,D/BluetoothAdapter( 5725): 249492676: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5725): 249492676: getState() :  mService = null. Returning STATE_OFF
D/[CarModeFW]( 5725): DrivingManager-initialize...
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/RegisteredServicesCache( 1461): empty dynamic service
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/SensorService(  847): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  847): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  847): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/[CarModeFW]( 5725): CDH-buildContactCacheWireFrame : cur len =0
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/[CarModeFW]( 5725): CDH-ContactDataHandler initiazlieCaches time : 75
,D/[CarModeFW]( 5725): CDH-initiazlieCaches : end sync
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/VlingoApplication( 5756): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/VlingoApplication( 5756): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/SecContentProvider2(  847): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  847): mCursor = null
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/MediaPlayer( 5725): Need to enable context aware info
,I/BackupManagerService(  847): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/MediaPlayer-JNI( 5725): native_setup
V/MediaPlayer( 5725): constructor
,I/BackupManagerService(  847): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/MediaPlayer( 5725): setListener
E/MediaPlayer-JNI( 5725): QCMediaPlayer mediaplayer NOT present
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/[CarModeFW]( 5725): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 5725): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,V/BackupManagerService(  847): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  847): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@28b63c16
D/[CarMode]( 5725): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1449501081001
D/[CarMode]( 5725): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1449501081002
D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1449501081002
D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1449501081002
D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1449501081002
,D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1449501081003
,D/TP/SmsProvider( 1473): query,matched:2, calling pid = 5725
,D/TP/SmsProvider( 1473): match 2:Elapsed time : 0.897 ms
,I/[CarMode]( 5725): [LogNotNull]-Package name is: com.google.android.apps.maps
,D/[CarModeFW]( 5725): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/SmsProvider( 1473): query,matched:2, calling pid = 5725
,D/TP/SmsProvider( 1473): match 2:Elapsed time : 0.815 ms
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/[CarModeFW]( 5725): RecommendHandler-selection = type = '3'
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/MessageDataHandler( 5725):  getInboxList smsCursor : 17
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,E/[CarMode]( 5725): [DLApplication]-Init End!:true
,D/TP/MmsProvider( 1473): Query uri=content://mms/inbox, match=2, calling pid = 5725
,D/TP/MmsProvider( 1473): Query uri=content://mms, match=0, calling pid = 5725
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  ( 5801): MountEmulatedStorage()
E/Zygote  ( 5801): v2
I/libpersona( 5801): KNOX_SDCARD checking this for 10003
I/libpersona( 5801): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=5801 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,W/ResourcesManager(  847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,E/Zygote  ( 5807): MountEmulatedStorage()
E/Zygote  ( 5807): v2
I/libpersona( 5807): KNOX_SDCARD checking this for 10020
I/libpersona( 5807): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=5807 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,D/MessageDataHandler( 5725):  getInboxList mmsCursor : 36
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/SELinux ( 5801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 5807): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5807): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5807): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,E/SELinux ( 5801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarMode]( 5725): [DLApplication]-GooglePlayServices SUCCESS.
,D/[CarModeFW]( 5725): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 5725):  getInboxList mms,sms cursor join : 81
I/GCoreNlp( 1724): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/MessageDataHandler( 5725): getUnreadMessageCount :0
D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 135
,D/TP/MmsSmsProvider( 1473): query,matched:0, calling pid = 5725
V/TP/MmsSmsProvider( 1473): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1473): match 0:Elapsed time : 3.914 ms
,E/[CarMode]( 5725): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/LocationProviderProxy(  847): applying state to connected service
,D/TimaKeyStoreProvider( 5801): TimaSignature is unavailable
D/ActivityThread( 5801): Added TimaKeyStore provider
,I/UpdateManagerReceiver( 5725): Intent : android.intent.action.PACKAGE_ADDEDMon Dec 07 16:11:21 GMT+01:00 2015
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/TP/MmsSmsProvider( 1473): query,matched:13, calling pid = 5725
,D/TP/MmsSmsProvider( 1473): match 13:Elapsed time : 1.058 ms
,D/TimaKeyStoreProvider( 5807): TimaSignature is unavailable
,D/ActivityThread( 5807): Added TimaKeyStore provider
,E/Zygote  ( 5833): MountEmulatedStorage()
E/Zygote  ( 5833): v2
I/libpersona( 5833): KNOX_SDCARD checking this for 1000
I/libpersona( 5833): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=5833 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 5833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5833): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LocationProviderProxy(  847): applying state to connected service
,D/[CarModeFW]( 5725): CDH-buildContactCacheWireFrame : cur len =0
,V/GmsNetworkLocationProvi( 1724): DISABLE
,D/[CarModeFW]( 5725): RecommendHandler-selection = type = '3'
,I/ActivityManager(  847): Killing 4814:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,D/MessageDataHandler( 5725):  getInboxList address cursor : 80
,D/TimaKeyStoreProvider( 5833): TimaSignature is unavailable
,D/ActivityThread( 5833): Added TimaKeyStore provider
,D/[CarModeFW]( 5725): PushMessageService-onCreate
,D/ResourcesManager( 5807): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,I/ActivityManager(  847): Killing 4656:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,D/TP/MmsSmsProvider( 1473): query,matched:0, calling pid = 5725
V/TP/MmsSmsProvider( 1473): getSimpleConversations entered.
,I/ActivityManager(  847): Killing 4934:com.android.email/u0a163 (adj 15): bgCount ##42
I/ActivityManager(  847): Killing 4918:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##43
D/TP/MmsSmsProvider( 1473): match 0:Elapsed time : 0.956 ms
,D/ResourcesManager( 5801): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/MessageDataHandler( 5725):  getInboxList thread cursor : 19
,D/ResourcesManager( 5833): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/MessageDataHandler( 5725):  thread, addr result: 7
I/[CarModeFW]( 5725): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 277
I/[CarModeFW]( 5725): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 277
,D/[CarModeFW]( 5725): PushMessageManager-onServiceConnected
D/[CarModeFW]( 5725): PushMessageService-registerPushMessageServiceListener
,W/ContextImpl( 5833): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/UserAnalysis.PlaceProvider( 5801): PlaceProvider onCreate()
,E/Zygote  ( 5850): MountEmulatedStorage()
I/libpersona( 5850): KNOX_SDCARD checking this for 10112
E/Zygote  ( 5850): v2
I/libpersona( 5850): KNOX_SDCARD not a persona
,D/ResourcesManager( 5833): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
,I/ActivityManager(  847): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=5850 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/UserAnalysis.SecureDbManager( 5801): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 5801): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 5801): Create SecureDbHelper
,I/SELinux ( 5850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 5850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5850): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/FilterInstaller( 5833): There is no requred permission
,D/IntelligenceServiceApplication( 5801): onCreate()
,I/ActivityManager(  847): Killing 5009:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,I/SQLiteSecureOpenHelper( 5801): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 5801): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 5801): Open Place.db in secure mode
,D/TimaKeyStoreProvider( 5850): TimaSignature is unavailable
,D/ActivityThread( 5850): Added TimaKeyStore provider
,I/SQLiteSecureOpenHelper( 5801): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 5801): ...getDatabaseLocked(b,b,pwd)
,D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 430
,D/ResourcesManager( 5850): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/[CarModeFW]( 5725): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 5725): MyPlaceProvider-=============
,D/[CarModeFW]( 5725): MyPlaceProvider-=============
D/[CarModeFW]( 5725): MyPlaceProvider-=============
,D/[CarModeFW]( 5725): MyPlaceProvider-=============
D/[CarModeFW]( 5725): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 5725): MyPlaceProvider-==============
D/[CarModeFW]( 5725): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5725): MyPlaceProvider-==============
D/[CarModeFW]( 5725): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 5725): MyPlaceProvider-==============
D/[CarModeFW]( 5725): MyPlaceProvider-latitude is not valid
,I/[CarModeFW]( 5725): -[snowdeer] Rec : Missed Call : 424
,D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 439
,D/[CarMode]( 5725): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@8190ccc8, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@e54f651e] LOCATIONS
,D/PackageIntentReceiver( 5850): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 5850): Not GearManger package! 
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5868): MountEmulatedStorage()
E/Zygote  ( 5868): v2
I/libpersona( 5868): KNOX_SDCARD checking this for 10118
I/libpersona( 5868): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=5868 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 4565:com.android.calendar/u0a150 (adj 15): bgCount ##41
,I/SELinux ( 5868): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5868): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5868): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/FaceInterface( 5284): startFaceScan() : going on
D/FaceInterface( 5284): startFaceScan() is called.
,W/libprocessgroup(  847): failed to open /acct/uid_10037/pid_4814/cgroup.procs: No such file or directory
W/libprocessgroup(  847): failed to open /acct/uid_10046/pid_4656/cgroup.procs: No such file or directory
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_4918/cgroup.procs: No such file or directory
,W/libprocessgroup(  847): failed to open /acct/uid_10163/pid_4934/cgroup.procs: No such file or directory
,D/ContentApp( 1223): startScan() is called.
,D/FaceValue( 1223): mSleepTime: 800
,D/FaceValue( 1223): mMaxThreadNum: 2
,D/ContentApp( 1223): startScan() is end.
,I/art     (  847): Explicit concurrent mark sweep GC freed 25457(1465KB) AllocSpace objects, 1(16KB) LOS objects, 31% free, 35MB/51MB, paused 3.924ms total 95.344ms
,D/ContentApp( 1223): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1223): isNeedToRestore : start
,D/TimaKeyStoreProvider( 5868): TimaSignature is unavailable
,D/ActivityThread( 5868): Added TimaKeyStore provider
,I/[CarModeFW]( 5725): -[snowdeer] Rec : Favorite : 120
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5868): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/libprocessgroup(  847): failed to open /acct/uid_10149/pid_5009/cgroup.procs: No such file or directory
W/ResourcesManager( 5868): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,E/Zygote  ( 5884): MountEmulatedStorage()
I/libpersona( 5884): KNOX_SDCARD checking this for 10046
E/Zygote  ( 5884): v2
I/libpersona( 5884): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5884 uid=10046 gids={50046, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  322): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 279us total 10.425ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.063ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 247us total 7.708ms
,I/SELinux ( 5884): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  847): failed to open /acct/uid_10150/pid_4565/cgroup.procs: No such file or directory
,I/SELinux ( 5884): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5884): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 5725): -[snowdeer] Rec : CallLog : 63
,D/TimaKeyStoreProvider( 5884): TimaSignature is unavailable
,D/ActivityThread( 5884): Added TimaKeyStore provider
,I/ActivityManager(  847): Killing 4207:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,D/ResourcesManager( 5884): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,I/FaceInterface( 5284): startFaceScan() : going on
D/FaceInterface( 5284): startFaceScan() is called.
,D/ContentApp( 1223): startScan() is called.
,W/ResourcesManager( 5884): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ContentApp( 1223): startScan() is end.
,D/ContentApp( 1223): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1223): isNeedToRestore : start
,I/CalendarProvider2( 5884): CalendarProvider2.onCreate() called
,D/MagazineService Version( 5868): Magazine-Administrator: 11
,D/MagazineService Version( 5868): Magazine-Provider: 14
,D/MagazineService Version( 5868): Magazine-Channel: 14
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5903): MountEmulatedStorage()
,E/Zygote  ( 5903): v2
I/libpersona( 5903): KNOX_SDCARD checking this for 10118
I/libpersona( 5903): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.samsung.android.internal.headlines for service com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService: pid=5903 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/HeadlinesChannelApplication( 5868): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 5868): [onReceive] android.intent.action.PACKAGE_ADDED com.example.hello
,I/SELinux ( 5903): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  847): failed to open /acct/uid_10117/pid_4207/cgroup.procs: No such file or directory
,I/SELinux ( 5903): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5903): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5919): MountEmulatedStorage()
I/libpersona( 5919): KNOX_SDCARD checking this for 1000
E/Zygote  ( 5919): v2
I/libpersona( 5919): KNOX_SDCARD not a persona
E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,I/ActivityManager(  847): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=5919 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/MagazineService::MagazineService( 5868): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/SELinux ( 5919): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TimaKeyStoreProvider( 5903): TimaSignature is unavailable
D/MagazineService::MagazineService( 5868): [onHandleIntent] Send broadcast to (com.example.hello).
,I/SELinux ( 5919): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5919): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityThread( 5903): Added TimaKeyStore provider
I/ActivityManager(  847): Killing 5043:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 5919): TimaSignature is unavailable
,D/ActivityThread( 5919): Added TimaKeyStore provider
,D/ResourcesManager( 5903): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,D/ResourcesManager( 5919): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/ResourcesManager( 5903): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 4261): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/HeadlinesChannelApplication( 5903): [onCreate]
,D/Headlines( 5903): Breath.onCreate
,D/HeadlinesCardManager( 5903): HeadlinesCardManager : constructor
,E/HeadlinesCardManager( 5903): HeadlinesCardManager : ctor = image_cache size is 42MB
D/SA Version( 5903): CardProvider Library : 14
,D/MagazineService::CardProviderContentProvider( 5868): insertProvider: provider already exists.: com.samsung.android.app.headlines
,D/MagazineService::CardProviderContentProvider( 5868): insertProvider: provider is updated.: com.samsung.android.app.headlines
,D/com.samsung.android.magazine.cardprovider.ConfigurationManager( 5903): registerCardProvider: provider already exists.
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_5043/cgroup.procs: No such file or directory
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/Headlines( 5903): HeadlinesDataCenter ctor
,D/Headlines( 5903): HeadlinesDataCenter. mLocale = en_US
,E/Zygote  ( 5936): MountEmulatedStorage()
E/Zygote  ( 5936): v2
I/libpersona( 5936): KNOX_SDCARD checking this for 1000
I/libpersona( 5936): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=5936 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/HeadlinesChannelUtil( 5903): getCountryCode(): countryCode = DE
,I/SELinux ( 5936): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/HeadlinesCardManager( 5903): HeadlinesCardManager : constructor welcome :YES
,I/SELinux ( 5936): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 5936): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/[CarModeFW]( 5725): -[snowdeer] Rec : Schedule : 288
,I/[CarModeFW]( 5725): -[snowdeer] Rec : During DL app : 3
,I/[CarModeFW]( 5725): -[snowdeer] Rec : Location Sharing : 1
,I/[CarModeFW]( 5725): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 5725): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 5725): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 5725): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 5725): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
,I/[CarModeFW]( 5725): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 914
,I/[CarModeFW]( 5725): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
,I/[CarModeFW]( 5725): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 5725): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 917
,D/TimaKeyStoreProvider( 5936): TimaSignature is unavailable
,D/ActivityThread( 5936): Added TimaKeyStore provider
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,D/ResourcesManager( 5936): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener( 5936): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 5936): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  ( 5953): MountEmulatedStorage()
E/Zygote  ( 5953): v2
I/libpersona( 5953): KNOX_SDCARD checking this for 10135
I/libpersona( 5953): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5953 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 5076:com.sec.factory/1000 (adj 15): bgCount ##41
,D/SSRM:m  (  847): SIOP:: AP = 460, PST = 428, CUR = 300
,I/System.out( 5756): INFO:Resource not found:/Common.properties Using default values
,I/ActivityManager(  847): Waited long enough for: ServiceRecord{77b1c76 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,I/SELinux ( 5953): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5953): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5953): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AcmsService( 5936): Enter Oncreate
,D/AcmsServiceMonitor( 5936): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 5936): creating AcmsCore
D/AcmsCore( 5936): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 5936): AcmsCore
,D/AcmsCore( 5936): init
D/AcmsCore( 5936): Looper handler is not null
,D/AcmsCore( 5936): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5936): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,D/AcmsServiceMonitor( 5936): Incrementing - Counter value: 1
,D/AcmsCore( 5936): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsCertificateMngr( 5936): AcmsCertificateMngr
D/AcmsRevocationMngr( 5936): AcmsRevocationMngr
D/TimaKeyStoreProvider( 5953): TimaSignature is unavailable
,D/AcmsService( 5936): onStartCommand
D/ActivityThread( 5953): Added TimaKeyStore provider
,D/AcmsService( 5936): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 5936): Enter incrementSvcCounter with startId 1
W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_5076/cgroup.procs: No such file or directory
,D/AcmsServiceMonitor( 5936): Incrementing - Counter value: 2
D/AcmsService( 5936): Incremented Counter Value : onStartCommand
,D/ActivityThread( 5936): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/ResourcesManager( 5953): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 5953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AcmsService( 5936): Inside handle Intent
D/AcmsService( 5936): App added - package name: com.example.hello
D/AcmsCore( 5936): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 5936): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5936): Incrementing - Counter value: 3
D/AcmsCore( 5936): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 5936): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 5936): Decrementing - Counter value: 2
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 5429): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5984): MountEmulatedStorage()
E/Zygote  ( 5984): v2
I/libpersona( 5984): KNOX_SDCARD checking this for 10166
I/libpersona( 5984): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=5984 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SMD     (  287): DCD ON
,I/SELinux ( 5984): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 5984): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 5984): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GAV2    ( 5457): Thread[GAThread,5,main]: No campaign data found.
,I/GLSActivity( 1683): [ac] getting account id
,D/TimaKeyStoreProvider( 5984): TimaSignature is unavailable
,D/ActivityThread( 5984): Added TimaKeyStore provider
,D/ResourcesManager( 5984): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,I/GLSUser ( 1683): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,W/ResourcesManager( 5984): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 5984): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6002): MountEmulatedStorage()
I/libpersona( 6002): KNOX_SDCARD checking this for 10170
E/Zygote  ( 6002): v2
I/libpersona( 6002): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6002 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/SELinux ( 6002): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6002): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6002): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6002): TimaSignature is unavailable
,D/ActivityThread( 6002): Added TimaKeyStore provider
,D/ResourcesManager( 6002): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 6002): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6019): MountEmulatedStorage()
E/Zygote  ( 6019): v2
I/libpersona( 6019): KNOX_SDCARD checking this for 10030
I/libpersona( 6019): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6019 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  847): Killing 5126:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,I/SELinux ( 6019): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6019): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6019): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6019): TimaSignature is unavailable
,D/ActivityThread( 6019): Added TimaKeyStore provider
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,D/ResourcesManager( 6019): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/libprocessgroup(  847): failed to open /acct/uid_1000/pid_5126/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5884): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/Finsky  ( 6019): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager(  847): Killing 4858:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,W/libprocessgroup(  847): failed to open /acct/uid_10078/pid_4858/cgroup.procs: No such file or directory
,D/Finsky  ( 6019): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6055): MountEmulatedStorage()
,E/Zygote  ( 6055): v2
I/libpersona( 6055): KNOX_SDCARD checking this for 10012
I/libpersona( 6055): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6055 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,D/PowerManagerService(  847): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  847): Nap time (uid 1000)...
,I/PowerManagerService(  847): !@[ps] Screen__Off(2) : 
,I/PowerManagerService(  847): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  847): setDeviceInteractive: 0
D/DisplayPowerController(  847): getFinalBrightness : 1 -> 1
D/PowerManagerService(  847): [s] DisplayPowerCallbacks : onStateChanged()
,D/InputManager-JNI(  847): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService(  847): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  847): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI(  847): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI(  847): sysfs_write -: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  847): handleSandman : startDream()
,D/InputManager-JNI(  847): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService(  847): handleSandman : startDreaming, but isDreaming false
,D/SContextService(  847): 	.unregisterCallback : 1, client=
D/SContextService(  847): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@22143a72, Service = Auto Rotation, used = 1
,I/PowerManagerService(  847): Sleeping (uid 1000)...
D/PowerManagerService(  847): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  847): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  847): [input device light] handleInputDeviceLightOff
,W/CAE     (  847): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  847): stop(ContextProvider.java:149)
,V/CAE     (  847): clear(AutoRotationRunner.java:182)
V/CAE     (  847): disable(AutoRotationRunner.java:171)
,I/CAE     (  847): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  847): SendSensorHubData: send data = -78, 7, 0, 0
,I/SELinux ( 6055): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/Sensorhubs(  301): sendContextData: -78, 7, 0, 0
,I/SurfaceFlinger(  250): id=14 createSurf (1080x1920),2 flag=404, ColorFade
I/SELinux ( 6055): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6055): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/CAE     (  847): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  847): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/TimaKeyStoreProvider( 6055): TimaSignature is unavailable
,D/ActivityThread( 6055): Added TimaKeyStore provider
,W/Settings( 6019): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/Adreno-EGL(  847): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  847): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  847): Build Date: 03/03/15 Tue
I/Adreno-EGL(  847): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  847): Remote Branch: 
I/Adreno-EGL(  847): Local Patches: 
I/Adreno-EGL(  847): Reconstruct Branch: 
,W/Settings( 6019): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ResourcesManager( 6055): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6055): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6055): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/CAE     (  847): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  847): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  847): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  847): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  847): removeSContextService() : service = Auto Rotation
,D/SContextService(  847): ===== SContext Service List =====
D/SContextManager(  847):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3c4e150d, service=Auto Rotation
,D/KeyguardViewMediator( 1171): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1171): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1171): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1171): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3302): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3302): getDatabaseLocked(b,b,pwd)...
,I/CAE     (  847): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  847): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  847): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
,D/SensorHubManager(  847): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  301): sendContextData: -76, 13, -47, 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/KeyguardViewMediator( 1171): timeout : 5000
,I/MultiDex( 6055): VM with version 2.1.0 has multidex support
I/MultiDex( 6055): install
I/MultiDex( 6055): VM has multidex support, MultiDex support library is disabled.
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/KeyguardViewMediator( 1171): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1171): handleNotifyScreenOff
,D/InputMethodManagerService(  847): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  847):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  847):  handler : SCREEN_ON end
,D/NotificationService(  847): ACTION_SCREEN_ON
,D/LightsService(  847): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 847) 
,D/LightsService(  847): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  847): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService(  847): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  292): adev_set_parameters: enter: screen_state=on
V/voice   (  292): voice_set_parameters: enter: screen_state=on
V/voice   (  292): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  292): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
,D/DisplayPowerController(  847): ColorFade: onAnimationStart
D/DisplayPowerController(  847): getFinalBrightness : 8 -> 0
,I/SecExternalDisplayIntents_Java(  847): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/WifiNative-HAL(  847): startHal
,E/wifi    (  847): getStaticLongField sWifiHalHandle 0x958e37fc
D/wifi    (  847): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x600a3a
,I/WifiNative-HAL(  847): Could not start hal
D/WifiStateMachine(  847): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  847): handleScreenStateChanged Exit: true
,E/WifiStateMachine(  847): setSuspendOptimizations: 4 false
,E/WifiStateMachine(  847): mSuspendOptNeedsDisabled 4
,D/IpRemoteDisplayController(  847): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  847): Bridge Server is not available
,D/lights  (  847): lcd : 0 +
D/DisplayPowerController(  847): getFinalBrightness : 8 -> 0
,D/PersonaManagerService(  847): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  847): MSG_ACTION_SCREEN_ON called
,I/ActivityManager(  847): Killing 5181:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/lights  (  847): lcd : 0 -
,D/Finsky  ( 6019): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6019): [1] 2.run: Finished loading 1 libraries.
,I/NfcService( 1461): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,V/JNIHelp ( 6055): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/NfcService( 1461): call the applyRotuiing
,D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/PackageBroadcastService( 1998): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/ChimeraCfgMgr( 1998): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Vision  ( 1998): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 1998): Failed to find package metadata for com.example.hello
,D/Vision  ( 1998): No vision deps
,I/ConfigFetchService( 1998): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 1998): launchTask
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  847): failed to open /acct/uid_10025/pid_5181/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 5936):  getKeyStoreForApplication Enter
,I/SamsungIME( 1857): getNextShiftState() cursorCapsMode : 0
,E/Zygote  ( 6083): MountEmulatedStorage()
E/Zygote  ( 6083): v2
I/libpersona( 6083): KNOX_SDCARD checking this for 10040
I/libpersona( 6083): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=6083 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/AcmsKeyStoreHelper( 5936): Key Store exist
,I/AcmsKeyStoreHelper( 5936): Hence loading the keystore file
,I/SELinux ( 6083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6083): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/ActivityThread( 6055): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6055): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26486f90: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6055): Installed default security provider GmsCore_OpenSSL
,D/ResourcesManager( 1998): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/accuweather( 2265): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2265): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2265): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2265): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2265): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2265): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,I/PeopleContactsSync( 1998): CP2 sync disabled
,D/DisplayPowerState(  847): !@ ColorFade entry
D/DisplayPowerController(  847): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  847): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  847): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  847): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  847): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  847): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,V/ConfigFetchTask( 1998): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UlE2AO6GNhfMd-QY61KSURC72ULmoP6v5H7TijaBctZZzh5yeWVV7oQd_ypLDW6kH-ACxfvm76Xpbhbb9rrITBeVO4GafXB3lG-e9YIzBDAhX0LdqGaU84ds9pVtBJu9xDy9SXK89kViYww2uTSk_WkTqsNMKFvUOkDtDTzZ95C-XO0tWsWH_BpqXZDdnfUriRUrj8HdeEDm9gOOXbslk2gmQx0n4HN5TXh0hZrWpIZtLoWv4
,D/SurfaceWidget.Renderer( 2265): [237392/6] SurfaceWidget drawing first frame
,D/SensorManager(  847): unregisterListener ::   
,E/Sensors (  847): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SurfaceWidget.Renderer( 2265): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2265): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2265): [237392/6] SurfaceWidget drawing first frame
,D/SensorManager(  847): unregisterListener ::   
,D/TimaKeyStoreProvider( 6083): TimaSignature is unavailable
,D/ActivityThread( 6083): Added TimaKeyStore provider
,D/DisplayPowerController(  847): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  847): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  847): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager(  847): Display changed displayId=0
,D/SurfaceFlinger(  250): Set power mode=0, type=0 flinger=0xb6a62000
,I/GoogleURLConnFactory( 1998): Using platform SSLCertificateSocketFactory
,D/qdhwcomposer(  250): hwc_blank: Blanking display: 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/Finsky  ( 6019): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/ResourcesManager( 6083): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/StatusBar.NetworkController( 1171): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/StatusBar.NetworkController( 1171): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/ConnectivityService(  847): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1171): refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/SystemBroadcastReceiver( 5228): [#DCM#] [DCM_Performance] onReceive completed in time  1700 microsec. 
,I/SystemBroadcastReceiver( 5228): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 5228): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 5228): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/Finsky  ( 6019): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/LightsService(  847): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 847) 
,D/LightsService(  847): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,E/LightSensor(  847): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SSRM:m  (  847): SIOP:: AP = 470, PST = 433, CUR = 300
,D/X       (  847): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/SensorManager(  847): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  847): turn on LED for charging
,D/ContentApp( 1223):  LEVEL : 0
,D/ConnectivityService(  847): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 5228): [#DCM#] [DCM_Performance] onReceive completed in time  72 microsec. 
I/SystemBroadcastReceiver( 5228): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 5228): [#DCM#] onReceive action = EVENT_SIOP
,I/CAE     (  847): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  847): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  847): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  847): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  301): sendContextData: -76, 13, -46, 0
,D/BluetoothAdapter( 5474): disable()
,I/CAE     (  847): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 15, 11, 23,
,D/SensorHubManager(  847): SendSensorHubData: send data = -63, 14, 15, 11, 23
,E/BluetoothManagerService(  847): Bluetooth is already disabled. DO NOT disable again.
D/Sensorhubs(  301): sendContextData: -63, 14, 15, 11, 23
,D/MotionRecognitionService(  847):   mReceiver.onReceive : ACTION_SCREEN_OFF
,D/AcmsKeyStoreHelper( 5936):  getKeyStoreForApplication Exit
,I/AcmsCertificateMngr( 5936): getKeyStoreForApplication success 
D/AcmsCore( 5936): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 5936): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5936): Decrementing - Counter value: 1
D/AcmsCore( 5936): AcmsCore: ACMS_APP_INSTALLED
,I/WifiManager( 5474): packageName : com.example.hello
,D/AcmsCore( 5936): This is NOT a valid MirrorLink app
,D/AcmsCore( 5936): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 5936): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 5936): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 5936): Counter value is 0: Stopping ACMS service
,I/WifiNative-HAL(  847): startHal
E/wifi    (  847): getStaticLongField sWifiHalHandle 0x958e37fc
D/wifi    (  847): halHandle = 0x0, mVM = 0xb4e5c280, mCls = 0x102252
I/WifiNative-HAL(  847): Could not start hal
D/WifiStateMachine(  847): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  847): handleScreenStateChanged Exit: false
D/SecContentProvider(  847): uri = 18 selection = isWifiEnabled
,E/MotionRecognitionService(  847):  handler : SCREEN_OFF end 
D/SecContentProvider2(  847): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  847): mCursor = null
,D/NotificationService(  847): ACTION_SCREEN_OFF
E/WifiStateMachine(  847): setSuspendOptimizations: 4 true
E/WifiStateMachine(  847): mSuspendOptNeedsDisabled 0
D/LightsService(  847): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 847) 
D/LightsService(  847): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
,D/AcmsServiceMonitor( 5936): getSvcCounter - Counter value: 0
,D/AcmsService( 5936): Enter onDestroy
I/AcmsService( 5936): cleanUp(): inside service clean up
D/AcmsCore( 5936): AcmsCore: inside DeInit
D/AcmsCore( 5936): AcmsCore: mLooperHandler is not null and making it null
D/audio_hw_primary(  292): adev_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: enter: screen_state=off
V/voice   (  292): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  292): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  292): adev_set_parameters: exit
D/AcmsCertificateMngr( 5936): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 5936): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 5936): KeyStoreHelper: inside cleanup
,D/AcmsAppEntryInterface( 5936): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 5936): getSvcCounter - Counter value: 0
D/AcmsService( 5936): killing acms process
I/Process ( 5936): Sending signal. PID: 5936 SIG: 9
,I/SecExternalDisplayIntents_Java(  847): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/WifiService(  847): setWifiEnabled: false pid=5474, uid=10374
E/WifiService(  847): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  847): name = wifi_on
,I/jxcore-log( 5474): ****TEST TOOK:  5116  ms ****
I/jxcore-log( 5474): 
I/jxcore-log( 5474): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5474): 
,D/IpRemoteDisplayController(  847): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  847): Bridge Server is not available
I/ActivityManager(  847): Process ACMS.Process (pid 5936)(adj 0) has died(70,581)
,D/qdhwcomposer(  250): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  250): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  847): Excessive delay in setPowerMode(): 257ms
D/PowerManagerService(  847): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  847): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  847): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  847): Invalid hint ID.
I/QCOM PowerHAL(  847): Got set_interactive hint
,I/PowerManagerService(  847): [PWL] Off : 0s ago
I/PowerManagerService(  847): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  847): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  847): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=847, ws=WorkSource{10117}) (elapsedTime=21275)
I/PowerManagerService(  847): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=1998, ws=null) (elapsedTime=13167)
I/PowerManagerService(  847): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2772)
I/PowerManagerService(  847): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=2771)
I/PowerManagerService(  847): [PWL]       PARTIAL_WAKE_LOCK              'Config Service fetch' (uid=10012, pid=1998, ws=WorkSource{10374 com.example.hello}) (elapsedTime=401)
I/PowerManagerService(  847): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  847): [PWL]     mDisplayReady : false
I/PowerManagerService(  847): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/DisplayPowerController(  847): getFinalBrightness : 0 -> 0
D/PowerManagerService(  847): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  847): [PWL] sb release: PowerManagerService.Display
,I/System.out( 1998): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1998): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1998): (HTTPLog)-Thread-246-1025406274: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ResourcesManager( 6055): creating new AssetManager and set to /system/app/Maps/Maps.apk
,W/ConfigFetchTask( 1998): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,I/ConfigFetchService( 1998): fetch service done; releasing wakelock
,I/art     (  847): Explicit concurrent mark sweep GC freed 33062(1922KB) AllocSpace objects, 4(64KB) LOS objects, 31% free, 35MB/51MB, paused 1.350ms total 152.666ms
I/ConfigFetchService( 1998): stopping self
,D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1171): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/WifiService(  847): New client listening to asynchronous messages
D/VolumePanel( 1171): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1171): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  847): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  847): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1461): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1171):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1171): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1171): dismissHelpPopup 
,D/accuweather( 2265): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2265): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2265): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,I/ActivityManager(  847): Killing 5199:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,I/SettingSearchManagerReceiver( 1473): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1473): addSearchInfoDB
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6116): MountEmulatedStorage()
E/Zygote  ( 6116): v2
I/libpersona( 6116): KNOX_SDCARD checking this for 10168
I/libpersona( 6116): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6116 uid=10168 gids={50168, 9997} abi=armeabi-v7a
,E/LightSensor(  847): RED : 9, GREEN : 7, BLUE : 7, CLEAR : 12, CALCULATED LUX : 0.000000, CCT : 2710.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=6, rp1=3, gp1=1, bp1=1, cp1=6, cpl=3202560
,D/LightsService(  847): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  847): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  847): unregisterListener ::   
D/lights  (  847): led_pattern : 1 +
,I/SELinux ( 6116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/AndroidRuntime( 6112): 
D/AndroidRuntime( 6112): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/lights  (  847): led_pattern : 1 -
D/LightsService(  847): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SELinux ( 6116): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/ActivityManager(  847): Killing 5301:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,D/AndroidRuntime( 6112): CheckJNI is OFF
,D/ConnectivityService(  847): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/AndroidRuntime( 6112): setted country_code = Germany
,D/AndroidRuntime( 6112): setted countryiso_code = DE
,D/AndroidRuntime( 6112): setted sales_code = DBT
D/AndroidRuntime( 6112): readGMSProperty: start
D/AndroidRuntime( 6112): readGMSProperty: already setted!!
D/AndroidRuntime( 6112): readGMSProperty: end
D/AndroidRuntime( 6112): addProductProperty: start
,I/SystemBroadcastReceiver( 5228): [#DCM#] [DCM_Performance] onReceive completed in time  60 microsec. 
,I/SystemBroadcastReceiver( 5228): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 5228): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 5228): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/ResourcesManager( 6055): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/SSRM:m  (  847): SIOP:: AP = 470, PST = 438, CUR = 300
,W/libprocessgroup(  847): failed to open /acct/uid_10172/pid_5199/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6116): TimaSignature is unavailable
,D/ActivityThread( 6116): Added TimaKeyStore provider
,V/AlarmManager(  847): waitForAlarm result :4
,W/ActivityManager(  847): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,V/Finsky  ( 6019): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/Finsky  ( 6019): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/ActivityManager(  847): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  847): [PWL] sb release: PowerManagerService.Broadcasts
D/ResourcesManager( 6116): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
,W/libprocessgroup(  847): failed to open /acct/uid_10002/pid_5301/cgroup.procs: No such file or directory
,D/BatteryService(  847): level:100, scale:100, status:2, health:2, present:true, voltage: 4228, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  847): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  847): stay LED for charging
,D/BatteryService(  847): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  847):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  847): Plugged
I/MotionRecognitionService(  847): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1171): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1171): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1171):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1171): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/GLSUser ( 1683): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1683): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1683): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1683): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6019): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1683): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1683): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1683): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1683): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SettingSearchManagerReceiver( 1473): endInsert
,E/AffinityControl( 6112): AffinityControl: registerfunction enter
,D/AssistantMenuSettingSearch( 5661): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 5661): Make Setting DB
,D/AndroidRuntime( 6112): Calling main entry com.android.commands.pm.Pm
,D/PackageManager(  847): START PACKAGE DELETE: observer{734025988}
D/PackageManager(  847): pkg{<packageName>}
D/PackageManager(  847): user{0}
D/PackageManager(  847): caller{2000}
D/PackageManager(  847): flags{3}
,D/PersonaManagerService(  847): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  847): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  847): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  847): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  847): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManager(  847): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManagerService(  847): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  847): deletePackage- pkg:com.example.hello, edmuserId:-1
,D/ApplicationPolicy(  847): getApplicationUninstallationEnabled
,D/ApplicationPolicy(  847): getApplicationUninstallationEnabled :  enabled true
,V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PackageManager(  847): !@killApplicatoin: 10374, uninstall pkg
,I/ActivityManager(  847): Force stopping com.example.hello appid=10374 user=-1: uninstall pkg
,I/ActivityManager(  847): Killing 5474:com.example.hello/u0a374 (adj 0): stop com.example.hello
,I/ActivityManager(  847):   Force finishing activity ActivityRecord{1372f116 u0 com.example.hello/.MainActivity t11}
,D/FocusedStackFrame(  847): Set to : 0
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  250): id=13 Removed com.example.hello/com.example.hello.MainActivity (5/8)
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
I/SurfaceFlinger(  250): id=13 Removed com.example.hello/com.example.hello.MainActivity (-2/8)
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/WifiService(  847): Client connection lost with reason: 4
,D/SSRM:a  (  847): DeviceInfo:: 000000000000
D/SSRM:a  (  847): SettingsAirViewInfo:: 000000000
,W/PackageSettings(  847): Skipping PackageSetting{199f7878 com.test.thalitest/10367} due to missing metadata
,W/ContextImpl( 5661): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
,D/ConnectivityService(  847): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  847): Force stopping com.example.hello appid=10374 user=0: pkg removed
,D/ResourcesManager(  847): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,I/art     ( 5833): Explicit concurrent mark sweep GC freed 7711(361KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/18MB, paused 311us total 23.964ms
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,I/art     ( 4261): Explicit concurrent mark sweep GC freed 2846(160KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 14MB/24MB, paused 331us total 21.536ms
,D/ResourcesManager( 1481): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1481): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
E/SamsungIME( 1857): mOCRHelper is null
W/ResourcesManager( 1481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 1481): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1481): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1481): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,W/GeofencerStateMachine( 1724): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  847): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/GLSUser ( 1683): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1683): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1683): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1683): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/SecContentProvider2(  847): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  847): mCursor = null
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Videos/Videos.apk
,V/GLSActivity( 1683): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/RegisteredServicesCache( 1461): empty dynamic service
,D/RCPManagerService(  847): PackageReceiver onReceive()
,I/HarmonyEASService(  847): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  847): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  847): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  847): Receieved: android.intent.action.PACKAGE_REMOVED
,D/EnterpriseDeviceManagerService(  847): Package has changed for user 0
D/EnterpriseDeviceManagerService(  847): Admin package name: com.google.android.gms
,V/EnterpriseBillingPolicy(  847): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy(  847): uID is 10374
V/EnterpriseBillingPolicy(  847): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  847): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  847): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  847): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  847): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  847): getBillingProfileForVpnEngine - start - com.example.hello
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,V/EnterpriseBillingPolicyStorage(  847): getBillingProfileForVpnEngine - end - null
,D/TaskPersister(  847): removeObsoleteFile: deleting file=11_task.xml
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Finsky  ( 6019): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,E/SQLiteLog( 1683): (10) POSIX Error : 11 SQLite Error : 3850
,I/art     (  847): Explicit concurrent mark sweep GC freed 29558(2MB) AllocSpace objects, 8(128KB) LOS objects, 30% free, 35MB/51MB, paused 5.075ms total 218.612ms
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/PackageManager(  847): delete codoeFile: 
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/NotifUtils( 5457): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,D/PackageManager(  847): result of delete: 1{734025988}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/Zygote  ( 6155): MountEmulatedStorage()
I/libpersona( 6155): KNOX_SDCARD checking this for 10117
E/Zygote  ( 6155): v2
I/libpersona( 6155): KNOX_SDCARD not a persona
,W/ResourcesManager(  847): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  847): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  847): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
I/ActivityManager(  847): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6155 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/AndroidRuntime( 6112): Shutting down VM
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/art     (  322): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 10.904ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 8.056ms
,I/art     (  322): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.981ms
,D/ResourcesManager(  847): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 6155): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6155): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6155): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/TimaKeyStoreProvider( 6155): TimaSignature is unavailable
,D/ActivityThread( 6155): Added TimaKeyStore provider
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  847): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  847): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/NotifUtils( 5457): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
,W/Resources(  847): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager(  847): clearDefaults: com.example.hello
,I/CrashAnrDetector(  847): onPackageRemoved : com.example.hello
,I/NotifUtils( 5457): Showing notification with unreadCount of 7 and unseenCount of 7
,D/ResourcesManager( 6155): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/SurfaceWidgetView( 1481): destroyHardwareResources():50998773
,V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  847): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  847): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/Launcher( 1481): onRestart, Launcher: 819990795
,D/Launcher( 1481): onStart, Launcher: 819990795
D/Launcher.HomeView( 1481): onStart
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2265): [237392/6] Surface widget visibility changed visibility = true on instance = 1
,D/SurfaceWidget.Renderer( 2265): [237392/6] SurfaceWidget drawing first frame
,W/ResourcesManager( 6155): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,I/SurfaceFlinger(  250): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/StatusBarManagerService(  847): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1171): value : false
,D/StatusBarManagerService(  847): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/InputMethodManagerService(  847): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  847): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  847): Got RemoteException sending setActive(false) notification to pid 5474 uid 10374
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Timeline(  847): Timeline: Activity_windows_visible id: ActivityRecord{30c3ccd3 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:48811
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,D/LockPatternUtilsCache( 1171): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1171): value : false
,I/Babel   ( 6155): MmsConfig: mnc/mcc: 0/0
,D/ResourcesManager( 6155): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/Babel   ( 6155): MmsConfig.loadMmsSettings
,I/Babel   ( 6155): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
I/Babel   ( 6155): MmsConfig.loadFromDatabase
,W/AudioCapabilities( 6155): Unsupported mime audio/evrc
,W/AudioCapabilities( 6155): Unsupported mime audio/qcelp
,I/PeopleDatabaseHelper( 1998): cleanUpNonGplusAccounts done.
,W/VideoCapabilities( 6155): Unrecognized profile 2130706433 for video/avc
,E/Babel   ( 6155): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 6155): MmsConfig.loadFromResources
,E/Babel   ( 6155): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 6155): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,V/BitmapFactory( 5457): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,V/BitmapFactory( 5457): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
,W/Settings( 6155): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/AudioCapabilities( 6155): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6155): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 6155): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6155): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6155): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6155): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6155): Unsupported mime audio/evrc
,W/VideoCapabilities( 6155): Unsupported mime video/wvc1
,W/VideoCapabilities( 6155): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6155): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6155): Unsupported mime video/wvc1
,W/VideoCapabilities( 6155): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6155): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6155): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6155): Unsupported mime video/mp43
,W/VideoCapabilities( 6155): Unsupported mime video/sorenson
,E/audit_log( 2095): File locking failed. error= Bad file number
,F/libc    ( 5457): Fatal signal 7 (SIGBUS), code 2, fault addr 0x782f1db2 in tid 6153 (IntentService[G)
,E/audit_log( 2095): File locking failed. error= Bad file number
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/ActivityManager(  847): Process com.google.android.gm (pid 5457)(adj 5) has died(137,578)
,W/ActivityManager(  847): Scheduling restart of crashed service com.google.android.gm/.GmailIntentService in 1000ms
I/EventHub(  847): Removing device '/dev/input/event4' due to inotify event
,F/libc    ( 6019): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0cba4c0 in tid 6019 (android.vending)
F/libc    ( 6019): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,D/PowerManagerService(  847): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'hangouts_rtcs' (uid=10117, pid=6155, ws=null) (elapsedTime=86)
,I/ActivityManager(  847): Process com.google.android.talk (pid 6155)(adj 5) has died(143,578)
,W/ActivityManager(  847): Scheduling restart of crashed service com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService in 1000ms
,I/EventHub(  847): Removing device '/dev/input/event5' due to inotify event
,I/Zygote  (  322): Process 5457 exited due to signal (7)
,I/ActivityManager(  847): Process com.android.vending (pid 6019)(adj 5) has died(153,578)
,W/ActivityManager(  847): Scheduling restart of crashed service com.android.vending/com.google.android.finsky.services.DailyHygiene in 1000ms
,F/libc    ( 6055): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f845000 in tid 6055 (android.gms:car)
F/libc    ( 6055): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/Zygote  (  322): Process 6155 exited due to signal (7)
,I/Zygote  (  322): Process 6019 exited due to signal (7)
,V/AlarmManager(  847): waitForAlarm result :4
,W/ContextImpl( 5700): Unable to create files subdir /data/data/com.google.android.apps.docs/files
,W/ContextImpl( 5700): Unable to create files subdir /data/data/com.google.android.apps.docs/files
,I/ActivityManager(  847): Process com.google.android.gms:car (pid 6055)(adj 0) has died(161,579)
,W/ContextImpl( 5700): Unable to create files subdir /data/data/com.google.android.apps.docs/files
,E/GAV2    ( 5700): Thread[GAThread,5,main]: Error initializing the GAThread: java.lang.NullPointerException: Attempt to invoke virtual method 'boolean java.io.File.mkdir()' on a null object reference
E/GAV2    ( 5700): 	at android.app.ContextImpl.openFileOutput(ContextImpl.java:1279)
E/GAV2    ( 5700): 	at android.content.ContextWrapper.openFileOutput(ContextWrapper.java:196)
E/GAV2    ( 5700): 	at op.a(GAThread.java:347)
E/GAV2    ( 5700): 	at op.b(GAThread.java:368)
E/GAV2    ( 5700): 	at op.a(GAThread.java:414)
E/GAV2    ( 5700): 	at op.run(GAThread.java:504)
E/GAV2    ( 5700): Thread[GAThread,5,main]: Google Analytics will not start up.
,I/EventHub(  847): Removing device '/dev/input/event6' due to inotify event
,I/Zygote  (  322): Process 6055 exited due to signal (7)
,F/libc    ( 4428): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78ad2964 in tid 4428 (oid.app.shealth)
,F/libc    ( 4428): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,F/libc    ( 5725): Fatal signal 7 (SIGBUS), code 2, fault addr 0x78f364ae in tid 5737 (HeapTrimmerDaem)
,F/libc    ( 5725): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/ActivityManager(  847): Process com.sec.android.app.shealth (pid 4428)(adj 0) has died(195,579)
,E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6196): MountEmulatedStorage()
E/Zygote  ( 6196): v2
I/libpersona( 6196): KNOX_SDCARD checking this for 10035
I/libpersona( 6196): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.walkingmate.receiver.WalkingMateReceiver: pid=6196 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  847): Process com.sec.android.automotive.drivelink (pid 5725)(adj 15) has died(200,578)
,I/EventHub(  847): Removing device '/dev/input/event7' due to inotify event
,I/Zygote  (  322): Process 4428 exited due to signal (7)
I/Zygote  (  322): Process 5725 exited due to signal (7)
,I/EventHub(  847): Removing device '/dev/input/event8' due to inotify event
,I/SELinux ( 6196): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6196): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6196): TimaSignature is unavailable
,D/ActivityThread( 6196): Added TimaKeyStore provider
,D/ResourcesManager( 6196): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 6196): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 6196): Unable to setupGraphicsSupport due to missing cache directory
,I/EventHub(  847): Removing device '/dev/input/event9' due to inotify event
,E/SMD     (  287): DCD ON
,F/libc    ( 6196): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e887480 in tid 6196 (oid.app.shealth)
,F/libc    ( 6196): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2095): File locking failed. error= Bad file number
,I/ActivityManager(  847): Process com.sec.android.app.shealth (pid 6196)(adj 0) has died(202,578)
,F/libc    ( 5756): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb50a261c in tid 5770 (HeapTrimmerDaem)
,F/libc    ( 5756): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/EventHub(  847): Removing device '/dev/input/event10' due to inotify event
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  847): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6211): MountEmulatedStorage()
I/libpersona( 6211): KNOX_SDCARD checking this for 10035
E/Zygote  ( 6211): v2
I/libpersona( 6211): KNOX_SDCARD not a persona
,I/ActivityManager(  847): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.cignacoach.receiver.CignaCoachReceiver: pid=6211 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/Zygote  (  322): Process 6196 exited due to signal (7)
,I/ActivityManager(  847): Process com.vlingo.midas (pid 5756)(adj 15) has died(223,578)
,I/EventHub(  847): Removing device '/dev/input/event11' due to inotify event
,I/Zygote  (  322): Process 5756 exited due to signal (7)
,I/SELinux ( 6211): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
,E/SELinux ( 6211): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6211): TimaSignature is unavailable
,D/ActivityThread( 6211): Added TimaKeyStore provider
,D/ResourcesManager( 6211): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/ContextImpl( 6211): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 6211): Unable to setupGraphicsSupport due to missing cache directory
,F/libc    ( 6211): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9e887480 in tid 6211 (oid.app.shealth)
F/libc    ( 6211): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2095): File locking failed. error= Bad file number
,I/ActivityManager(  847): Process com.sec.android.app.shealth (pid 6211)(adj 0) has died(224,578)
,D/GCM     ( 1683): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1683): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 1998): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/Zygote  (  322): Process 6211 exited due to signal (7)
,D/WearableService( 4984): callingUid 10012, callindPid: 4984
,I/qdhwcomposer(  250): handle_blank_event: dpy:0 panel power state: 0
,E/MDM     ( 1724): [184] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 1998): Restart initialization of location

```
