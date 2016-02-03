#### Test 58135655c662d33_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
D/TimaKeyStoreProvider( 6313): TimaSignature is unavailable
D/ActivityThread( 6313): Added TimaKeyStore provider
W/System.err( 6271): java.lang.NoSuchMethodException: getImeiInCDMAGSMPhone []
I/SystemUtils( 6169): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
I/SystemUtils( 6169): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities( 6169): [#DCM#] OSUpgrade not required 
W/System.err( 6271): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 6271): 	at com.sec.pcw.util.c.c(SourceFile:295)
W/System.err( 6271): 	at com.sec.pcw.service.account.a.b(SourceFile:250)
W/System.err( 6271): 	at com.sec.pcw.service.account.a.a(SourceFile:52)
W/System.err( 6271): 	at com.mfluent.asp.datamodel.Device.r(SourceFile:359)
W/System.err( 6271): 	at com.mfluent.asp.datamodel.Device.<init>(SourceFile:248)
W/System.err( 6271): 	at com.mfluent.asp.datamodel.t.a(SourceFile:136)
W/System.err( 6271): 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:484)
W/System.err( 6271): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
W/System.err( 6271): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
W/System.err( 6271): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
W/System.err( 6271): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
W/System.err( 6271): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
W/System.err( 6271): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6271): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6271): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6271): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6271): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6271): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6271): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6271): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6271): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 6313): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
I/SL_DEBUG( 6271): isLoggable:: isProductShip = 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SL_DEBUG( 6271): isLoggable:: SL_DEBUG_EXIST = false
--------- beginning of system
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SLinkClient( 6231): queryDevices : cursor.getCount() = [ 0 ]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SLinkClient( 6231): onStorageUpdated(), uri = [ slink://slink ]
I/ThumbnailProvider( 6313): ThumbnailProvider onCreate()
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/DocumentBroadcastReceiver( 6313): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
I/BroadcastProcessorService( 6313): [START] processBroadcastIntent ...
I/SLinkClient( 6231): SlinkBackgroundJob: slink wake up ok!
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/libprocessgroup(  890): failed to open /acct/uid_10081/pid_5100/cgroup.procs: No such file or directory
W/libprocessgroup(  890): failed to open /acct/uid_10192/pid_5117/cgroup.procs: No such file or directory
D/GalleryCacheReady( 6231): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 6231): handleMeidaScanFinish()
D/FaceInterface( 6231): requestFaceScan() is called.
I/BroadcastProcessorService( 6313): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
I/FaceInterface( 6231): startFaceScan() : waiting 5 sec
W/LocalSuggestAlbumData( 6231): query fail: 
W/LocalSuggestAlbumData( 6231): query fail: 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SystemInfo( 6313): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 6313): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 6313): [START] DocumentService startDocumentService
I/DocumentService( 6313): DocumentService onCreate ... service
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6271): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6313): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6313): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
W/ContextImpl( 6271): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
D/GalleryCacheReady( 6231): Receive : home resume
D/Mms/UIEventReceiver( 6115): ui event
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/Transcoder( 6271): Transcoder(0xaee74830)::constructor
V/Transcoder( 6271): addObitRecipient
V/TMI-JNI ( 6271): Mobile Transcoder JNI version 1.6.0/20131120/4.4
E/SystemInfo( 6313): [SIOP LEVEL] : 0
W/BroadcastQueue(  890): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1489, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Zygote  ( 6349): MountEmulatedStorage()
E/Zygote  ( 6349): v2
I/libpersona( 6349): KNOX_SDCARD checking this for 10094
I/libpersona( 6349): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6349 uid=10094 gids={50094, 9997} abi=armeabi-v7a
I/SELinux ( 6349): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 6349): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6349): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/DocumentService( 6313): [BEGIN SYNC] DocumentService beginIndexing :16
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ContextImpl( 6313): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 6349): TimaSignature is unavailable
D/ActivityThread( 6349): Added TimaKeyStore provider
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/File    ( 6313): fail readDirectory() errno=13
E/File    ( 6313): fail readDirectory() errno=13
I/DocumentServiceUtils( 6313):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo( 6313): DocumentService [SIOP LEVEL] changed to 0
E/SystemInfo( 6313): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
I/SystemInfo( 6313): [SYSTEM STATUS] Battery and Storage levels are OK:
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 6349): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
I/DocumentService( 6313): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 6313): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :58
E/DocumentService( 6313): [THUMBNAIL] Total Time taken for each file :0
E/        ( 6313): [INDEX] Total time taken for each file :0
I/DocumentService( 6313): DocumentService onDestroy start
I/DocumentService( 6313): DocumentService onDestroy end
I/DocumentService( 6313): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 6313): InterruptedException: null
I/SystemInfo( 6313): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 6313): DocumentService cleanupEverything end
I/Process ( 6313): Sending signal. PID: 6313 SIG: 9
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ResourcesManager( 6349): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/lowmemorykiller(  246): Error writing /proc/6313/oom_score_adj; errno=22
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  890): Process com.samsung.indexservice (pid 6313)(adj 13) has died(59,612)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
I/MediaStoreImporter( 5988): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Zygote  ( 6371): MountEmulatedStorage()
I/libpersona( 6371): KNOX_SDCARD checking this for 10103
E/Zygote  ( 6371): v2
I/libpersona( 6371): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6371 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6371): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  890): Killing 5147:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
D/AndroidRuntime( 6351): 
D/AndroidRuntime( 6351): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/AndroidRuntime( 6351): CheckJNI is OFF
D/AndroidRuntime( 6351): setted country_code = Germany
D/AndroidRuntime( 6351): setted countryiso_code = DE
D/AndroidRuntime( 6351): setted sales_code = DBT
D/AndroidRuntime( 6351): readGMSProperty: start
D/AndroidRuntime( 6351): readGMSProperty: already setted!!
D/AndroidRuntime( 6351): readGMSProperty: end
D/AndroidRuntime( 6351): addProductProperty: start
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 6371): TimaSignature is unavailable
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/8)
D/ActivityThread( 6371): Added TimaKeyStore provider
I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/8)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 6371): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/ResourcesManager( 6371): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6371): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_5147/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/Zygote  ( 6394): MountEmulatedStorage()
E/Zygote  ( 6394): v2
I/libpersona( 6394): KNOX_SDCARD checking this for 10113
I/libpersona( 6394): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=6394 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
I/ActivityManager(  890): Killing 5187:com.sec.chaton/u0a86 (adj 15): bgCount ##41
I/SELinux ( 6394): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 6394): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6394): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/TimaKeyStoreProvider( 6394): TimaSignature is unavailable
D/ActivityThread( 6394): Added TimaKeyStore provider
E/AffinityControl( 6351): AffinityControl: registerfunction enter
D/ResourcesManager( 6394): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/libprocessgroup(  890): failed to open /acct/uid_10086/pid_5187/cgroup.procs: No such file or directory
D/AndroidRuntime( 6351): Calling main entry com.android.commands.am.Am
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/PersonaManagerService(  890): inState():  stateMachine is null !!
I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 6351): Shutting down VM
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  890): mDVFSHelper.release()
I/Timeline(  890): Timeline: Activity_windows_visible id: ActivityRecord{e2ee16c u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t17} time:51525
D/Launcher.HomeView( 1489): onStop
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/CustomFrequencyManagerService(  890): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  pkgName : ACTIVITY_RESUME_BOOSTER@10
W/GeoLookout( 6394): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
I/GeoLookout( 6394): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
D/SettingsProvider(  890): name = safetycare_geolookout_registering
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 10113
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2138): [237392/6] Surface widget pause on instance = 1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SettingsProvider(  890): ret = -1
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2138): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/Launcher( 1489): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/accuweather( 2138): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2138): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2138): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/GeoLookout( 6394): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/accuweather( 2138): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2138): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
V/TaskCloserActivity( 6079): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
I/ActivityManager(  890): Killing 5033:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
D/BootupListener( 1476): ACTION_DRIVELINK
D/SettingsProvider(  890): name = drivelink_navigation
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1001
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
D/BootupListener( 1476): NAVI : com.google.android.apps.maps
D/SettingsProvider(  890): name = internet_call_settings_visibility
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1001
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6414): MountEmulatedStorage()
E/Zygote  ( 6414): v2
I/libpersona( 6414): KNOX_SDCARD checking this for 10054
I/libpersona( 6414): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=6414 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
I/SELinux ( 6414): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6414): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6414): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6414): TimaSignature is unavailable
D/ActivityThread( 6414): Added TimaKeyStore provider
D/ResourcesManager( 6414): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 6414): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6414): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6414): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6414): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6414): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/libprocessgroup(  890): failed to open /acct/uid_10017/pid_5033/cgroup.procs: No such file or directory
D/PowerManagerService(  890): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/lights  (  890): lcd : 1 +
,D/lights  (  890): lcd : 1 -
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/CustomFrequencyManagerService(  890): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 890  tag : ACTIVITY_RESUME_BOOSTER@10
E/TranscodeReceiver( 6414): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/videowall-Global( 6414): core_num = 4
I/art     (  890): Background sticky concurrent mark sweep GC freed 209011(7MB) AllocSpace objects, 0(0B) LOS objects, 12% free, 57MB/64MB, paused 2.080ms total 107.131ms
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
W/linker  ( 6414): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
W/linker  ( 6414): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
D/videowall-Global( 6414): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 6414): dsp : 1080, swkey : false, Cores : 4, Clock : 0
D/TranscodeReceiver( 6414):  SIOP_LEVEL: 0
D/SHealthUpgrade(SHealthUpgradeUtil)( 4905): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4905): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4905): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
I/ActivityManager(  890): Killing 5137:com.google.android.gm/u0a114 (adj 15): bgCount ##41
I/SettingSearchManagerReceiver( 1476): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1476): addSearchInfoDB
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
E/Zygote  ( 6430): MountEmulatedStorage()
E/Zygote  ( 6430): v2
I/libpersona( 6430): KNOX_SDCARD checking this for 10168
I/libpersona( 6430): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6430 uid=10168 gids={50168, 9997} abi=armeabi-v7a
I/SELinux ( 6430): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6430): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6430): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6430): TimaSignature is unavailable
D/ActivityThread( 6430): Added TimaKeyStore provider
W/libprocessgroup(  890): failed to open /acct/uid_10114/pid_5137/cgroup.procs: No such file or directory
D/ResourcesManager( 6430): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
I/SettingSearchManagerReceiver( 1476): endInsert
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6446): MountEmulatedStorage()
I/libpersona( 6446): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6446): v2
I/libpersona( 6446): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=6446 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
I/SELinux ( 6446): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  890): Killing 5354:com.google.android.talk/u0a117 (adj 15): bgCount ##41
I/SELinux ( 6446): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6446): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6446): TimaSignature is unavailable
D/ActivityThread( 6446): Added TimaKeyStore provider
D/ResourcesManager( 6446): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/AssistantMenuSettingSearch( 6446): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 6446): Make Setting DB
W/libprocessgroup(  890): failed to open /acct/uid_10117/pid_5354/cgroup.procs: No such file or directory
W/ContextImpl( 6446): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
I/ActivityManager(  890): Killing 5330:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6462): MountEmulatedStorage()
E/Zygote  ( 6462): v2
I/libpersona( 6462): KNOX_SDCARD checking this for 10114
I/libpersona( 6462): KNOX_SDCARD not a persona
I/ActivityManager(  890): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6462 uid=10114 gids={50114, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
I/SELinux ( 6462): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6462): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6462): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 4905): RegionGroup for  is null
D/TimaKeyStoreProvider( 6462): TimaSignature is unavailable
D/ActivityThread( 6462): Added TimaKeyStore provider
D/ResourcesManager( 6462): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
W/libprocessgroup(  890): failed to open /acct/uid_10091/pid_5330/cgroup.procs: No such file or directory
D/BluetoothManager( 4905): getConnectedDevices
D/BluetoothManager( 4905): getConnectedDevices
D/BluetoothManager( 4905): getConnectedDevices
W/ActivityManager(  890): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 6462): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager(  890): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6462): getAccountsCursor
W/ActivityManager(  890): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  890): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6462): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  890): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6462): Observing account changes for notifications
W/ActivityManager(  890): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
W/ActivityManager(  890): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6462): Error finding the version of the Email provider.....
E/Gmail   ( 6462): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6462): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:135)
E/Gmail   ( 6462): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 6462): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 6462): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6462): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6462): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 6462): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6462): We do not support migrating this version of the Email provider.
I/Gmail   ( 6462): getAccountsCursor
V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog( 6462): (283) recovered 554 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,E/SMD     (  284): DCD ON
,D/ResourcesManager( 2468): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/File    ( 6462): fail readDirectory() errno=2
,I/Gmail   ( 6462): notifyAccountChanged
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/Gmail   ( 6462): getAccountsCursor
,I/Gmail   ( 6462): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6462): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6462): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6462): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4905): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4905): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4905): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/Gmail   ( 6462): getAccountsCursor
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6511): MountEmulatedStorage()
E/Zygote  ( 6511): v2
I/libpersona( 6511): KNOX_SDCARD checking this for 10036
I/libpersona( 6511): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6511 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 6511): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6511): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6511): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/TimaKeyStoreProvider( 6511): TimaSignature is unavailable
,D/ActivityThread( 6511): Added TimaKeyStore provider
,D/ResourcesManager( 6511): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/NotifUtils( 6462): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 6462): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
I/NotifUtils( 6462): Showing notification with unreadCount of 7 and unseenCount of 7
W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ResourcesManager( 6511): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 6511): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6511): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6511): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6511): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6511): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6511): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6511): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6511): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
,I/ActivityManager(  890): Waited long enough for: ServiceRecord{2d7358c u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,W/ResourcesManager( 6511): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6511): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,D/SSRM:m  (  890): SIOP:: AP = 480, PST = 439, CUR = 300
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/PeopleDatabaseHelper( 2468): cleanUpNonGplusAccounts done.
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
,I/ActivityManager(  890): Killing 5379:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,D/GCM     ( 1680): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1680): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2468): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/WearableService( 5449): callingUid 10012, callindPid: 5449
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,E/MDM     ( 2266): [246] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2468): Restart initialization of location
,W/libprocessgroup(  890): failed to open /acct/uid_10012/pid_5379/cgroup.procs: No such file or directory
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_in.png
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/art     (  890): Explicit concurrent mark sweep GC freed 183351(6MB) AllocSpace objects, 3(1855KB) LOS objects, 22% free, 55MB/71MB, paused 2.056ms total 143.989ms
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GCM     ( 1680): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1680): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2468): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/MDM     ( 2266): [239] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/LocationInitializer( 2468): Restart initialization of location
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,V/BitmapFactory( 6462): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/NotifUtils( 6462): Account: 61035162 vibrate: false
,I/NotifUtils( 6462): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|1729800001|null|10114
,D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,I/ValidateNoPeople(  890): Executing: validation for: 0|com.google.android.gm|1729800001|null|10114
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,V/AudioPolicyManager(  291): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  890): getStreamVolume 5 index 110
D/LightsService(  890): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  890): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,D/ResourcesManager( 1170): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,E/SQLiteLog( 1792): (284) automatic index on sqlite_sq_AD312FB0(STAT_DATA_ID)
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|-2100714965|null|10114
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|-913293406|null|10114
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,E/Zygote  ( 6565): MountEmulatedStorage()
I/libpersona( 6565): KNOX_SDCARD checking this for 10117
E/Zygote  ( 6565): v2
I/libpersona( 6565): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6565 uid=10117 gids={50117, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ValidateNoPeople(  890): final affinity: 0.0
,I/ValidateNoPeople(  890): Executing: validation for: 0|com.google.android.gm|-2100714965|null|10114
,I/art     (  310): Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 11.717ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 252us total 7.382ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 7.642ms
,I/SELinux ( 6565): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
I/SELinux ( 6565): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
E/SELinux ( 6565): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/KnoxNotification( 1170): ----- inflateViews : modified KnoxViewLocal -----
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|-865450363|null|10114
I/ValidateNoPeople(  890): final affinity: 0.0
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,D/TimaKeyStoreProvider( 6565): TimaSignature is unavailable
,D/ActivityThread( 6565): Added TimaKeyStore provider
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/PersonaManager( 1170): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1170): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@27cbbc8b
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ResourcesManager( 6565): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 6565): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ValidateNoPeople(  890): final affinity: 0.0
D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  890): Executing: validation for: 0|com.google.android.gm|-913293406|null|10114
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|-633420634|null|10114
I/ValidateNoPeople(  890): final affinity: 0.0
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|438982678|null|10114
I/ValidateNoPeople(  890): final affinity: 0.0
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,I/ValidateNoPeople(  890): final affinity: 0.0
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|1919793178|null|10114
I/ValidateNoPeople(  890): final affinity: 0.0
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  890): Validating: 0|com.google.android.gm|2046740944|null|10114
I/ValidateNoPeople(  890): final affinity: 0.0
D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,I/Babel   ( 6565): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 6565): MmsConfig.loadMmsSettings
,I/Babel   ( 6565): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
I/Babel   ( 6565): MmsConfig.loadFromDatabase
,W/AudioCapabilities( 6565): Unsupported mime audio/evrc
,D/ResourcesManager( 6565): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/AudioCapabilities( 6565): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6565): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6565): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 6565): Unsupported mime audio/mpeg-L2
,E/Babel   ( 6565): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 6565): MmsConfig.loadFromResources
,E/Babel   ( 6565): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 6565): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G900F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G900F.xml
,W/AudioCapabilities( 6565): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6565): Unsupported mime audio/x-ima
,W/AudioCapabilities( 6565): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6565): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6565): Unsupported mime audio/evrc
,W/Settings( 6565): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/VideoCapabilities( 6565): Unsupported mime video/wvc1
,W/VideoCapabilities( 6565): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6565): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 6565): Unsupported mime video/wvc1
,W/VideoCapabilities( 6565): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities( 6565): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 6565): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 6565): Unsupported mime video/mp43
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 6565): Unsupported mime video/sorenson
,E/Zygote  ( 6591): MountEmulatedStorage()
E/Zygote  ( 6591): v2
I/libpersona( 6591): KNOX_SDCARD checking this for 1000
I/libpersona( 6591): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6591 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/SELinux ( 6591): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6591): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6591): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6591): TimaSignature is unavailable
,D/ActivityThread( 6591): Added TimaKeyStore provider
,I/VideoCapabilities( 6565): Unsupported profile 4 for video/mp4v-es
,D/ResourcesManager( 6591): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
,D/PopupuiReceiver( 6591): onReceive() getAction : com.android.systemui.power.action.ACTION_CABLE_CONNECTED
,D/SecContentProvider2(  890): uri = -1 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,I/PopupuiReceiver_KNOX( 6591): getSealedState : true
,D/SecContentProvider2(  890): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,I/PopupuiReceiver_KNOX( 6591): getSealedHideNotificationMessages : 1
,D/SecContentProvider2(  890): uri = 15 selection = getCheckCoverPopupState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,I/PopupuiReceiver_KNOX( 6591): getCheckCoverPopupState : true
,W/ContextImpl( 6591): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:407 android.app.ActivityThread.handleReceiver:2945 
,D/PopupuiReceiver( 6591): Action cable connected ! on - 
,D/PopupuiReceiver( 6591): PopupuiService.java: dismissUSBCDetacheddDialog() unReigister
,W/ContextImpl( 6591): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 com.sec.android.app.popupuireceiver.PopupuiService.dismissUSBCDetacheddDialog:130 com.sec.android.app.popupuireceiver.PopupuiService.onStartCommand:103 
,W/ContextImpl( 6591): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 android.app.ActivityThread.handleStopService:3289 android.app.ActivityThread.access$2300:172 
,I/ActivityManager(  890): Killing 5416:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,E/SQLiteLog( 6565): (284) automatic index on conversation_participants_view(conversation_id)
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  890): failed to open /acct/uid_10037/pid_5416/cgroup.procs: No such file or directory
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/SQLiteLog( 6565): (284) automatic index on conversation_participants_view(conversation_id)
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/SQLiteLog( 6565): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6565): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 6565): (284) automatic index on conversation_participants_view(conversation_id)
,I/art     ( 1680): Explicit concurrent mark sweep GC freed 13183(672KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 17MB/29MB, paused 484us total 24.457ms
,D/GCM     ( 1680): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ChimeraCfgMgr( 2468): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ChimeraCfgMgr( 2468): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 6565): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: ac2dm
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> ac2dm without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SPPClientService( 5543): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,D/ResourcesManager( 6565): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 6565): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6565): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/Zygote  ( 6621): MountEmulatedStorage()
E/Zygote  ( 6621): v2
I/libpersona( 6621): KNOX_SDCARD checking this for 10038
I/libpersona( 6621): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=6621 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6621): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6621): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6621): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/Kids    ( 2468): [AccountUtils] Account not ready
W/Kids    ( 2468): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/Kids    ( 2468): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/Kids    ( 2468): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/Kids    ( 2468): 	at com.google.android.gms.auth.p.c(SourceFile:550)
W/Kids    ( 2468): 	at com.google.android.gms.auth.p.b(SourceFile:477)
W/Kids    ( 2468): 	at com.google.android.gms.kids.account.k.d(SourceFile:103)
W/Kids    ( 2468): 	at com.google.android.gms.kids.account.p.a(SourceFile:70)
W/Kids    ( 2468): 	at com.google.android.gms.kids.account.t.a(SourceFile:62)
W/Kids    ( 2468): 	at com.google.android.gms.chimera.f.run(SourceFile:179)
W/Kids    ( 2468): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Kids    ( 2468): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Kids    ( 2468): 	at java.lang.Thread.run(Thread.java:818)
,V/JNIHelp ( 6565): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/TimaKeyStoreProvider( 6621): TimaSignature is unavailable
D/ActivityThread( 6621): Added TimaKeyStore provider
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/ResourcesManager( 6621): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6621): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6621): [PushClientApplication] Push log off : This is Ship build version
,W/ActivityThread( 6565): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6565): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@136082a2: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6565): Installed default security provider GmsCore_OpenSSL
,D/SPPClientService( 6621): PushLog.txt file is not deleted.
D/SPPClientService( 6621): PushLog.txt file is not deleted.
D/SPPClientService( 6621): ============PushLog. stop!
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6642): MountEmulatedStorage()
,E/Zygote  ( 6642): v2
I/libpersona( 6642): KNOX_SDCARD checking this for 10038
I/libpersona( 6642): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=6642 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5159:com.android.vending/u0a30 (adj 15): bgCount ##41
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/SELinux ( 6642): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6642): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6642): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6642): TimaSignature is unavailable
,D/ActivityThread( 6642): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10030/pid_5159/cgroup.procs: No such file or directory
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 6642): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/Babel   ( 6565): UserRecoverableAuthException.
,E/Babel   ( 6565): cfq: BadAuthentication
E/Babel   ( 6565): 	at cfn.a(Unknown Source)
E/Babel   ( 6565): 	at f.a(PG:191)
E/Babel   ( 6565): 	at ava.a(PG:88)
E/Babel   ( 6565): 	at ava.a(PG:128)
E/Babel   ( 6565): 	at bjs.a(PG:255)
E/Babel   ( 6565): 	at bep.a(PG:602)
E/Babel   ( 6565): 	at bep.a(PG:469)
E/Babel   ( 6565): 	at bpo.run(PG:1141)
E/Babel   ( 6565): Error getting auth token
E/Babel   ( 6565): bxl
E/Babel   ( 6565): 	at f.a(PG:201)
E/Babel   ( 6565): 	at ava.a(PG:88)
E/Babel   ( 6565): 	at ava.a(PG:128)
E/Babel   ( 6565): 	at bjs.a(PG:255)
E/Babel   ( 6565): 	at bep.a(PG:602)
E/Babel   ( 6565): 	at bep.a(PG:469)
E/Babel   ( 6565): 	at bpo.run(PG:1141)
,I/Babel_RequestWriter( 6565): error sending REQ[fc:0; creat:1454523112826; type:bev-563500856]; took 92 ms (error code == 100)
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Babel   ( 6565): Account registration failedRedacted-21
,E/Babel   ( 6565): bph: null -- null
E/Babel   ( 6565): 	at ava.a(PG:120)
E/Babel   ( 6565): 	at ava.a(PG:128)
E/Babel   ( 6565): 	at bjs.a(PG:255)
E/Babel   ( 6565): 	at bep.a(PG:602)
E/Babel   ( 6565): 	at bep.a(PG:469)
E/Babel   ( 6565): 	at bpo.run(PG:1141)
I/Babel   ( 6565): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 6565): Account sign in complete with state 106account: Redacted-21
,I/art     ( 6565): Note: end time exceeds epoch: 
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SPPClientService( 6642): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6642): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 1680): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/SPPClientService( 6642): PushLog.txt file is not deleted.
D/SPPClientService( 6642): PushLog.txt file is not deleted.
D/SPPClientService( 6642): ============PushLog. stop!
,E/LNoti   ( 6642): [PhoneStatusChangeReceiver] This device doesn't register yet.
W/ResourcesManager( 1680): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/ic_launcher_babel.png
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
E/Babel   ( 6565): Unexpected exception while authenticating.
,E/Babel   ( 6565): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 6565): 	at cfn.b(Unknown Source)
E/Babel   ( 6565): 	at cfn.a(Unknown Source)
E/Babel   ( 6565): 	at f.a(PG:188)
E/Babel   ( 6565): 	at ava.b(PG:143)
E/Babel   ( 6565): 	at bnr.run(PG:5415)
E/Babel   ( 6565): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 6565): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 6565): 	at java.lang.Thread.run(Thread.java:818)
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/art     (  890): Explicit concurrent mark sweep GC freed 193744(7MB) AllocSpace objects, 3(178KB) LOS objects, 22% free, 56MB/72MB, paused 1.582ms total 150.243ms
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/SMD     (  284): DCD ON
,I/FaceInterface( 6231): startFaceScan() : going on
D/FaceInterface( 6231): startFaceScan() is called.
,D/ContentApp( 1221): startScan() is called.
,D/FaceValue( 1221): mSleepTime: 800
,D/FaceValue( 1221): mMaxThreadNum: 2
,D/ContentApp( 1221): startScan() is end.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1221): isNeedToRestore : start
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6673): MountEmulatedStorage()
,E/Zygote  ( 6673): v2
I/libpersona( 6673): KNOX_SDCARD checking this for 10034
I/libpersona( 6673): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6673 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager(  890): Killing 5466:com.policydm/1000 (adj 15): bgCount ##41
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/SELinux ( 6673): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6673): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6673): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6673): TimaSignature is unavailable
,D/ActivityThread( 6673): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_5466/cgroup.procs: No such file or directory
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 6673): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/FaceInterface( 6231): startFaceScan() : going on
D/FaceInterface( 6231): startFaceScan() is called.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ContentApp( 1221): startScan() is called.
,D/ContentApp( 1221): startScan() is end.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1221): isNeedToRestore : start
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,W/ResourcesManager( 6673): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  890): Killing 5506:com.samsung.helphub/1000 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1556): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_5506/cgroup.procs: No such file or directory
,E/Zygote  ( 6697): MountEmulatedStorage()
,E/Zygote  ( 6697): v2
I/libpersona( 6697): KNOX_SDCARD checking this for 10075
,I/libpersona( 6697): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6697 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/SELinux ( 6697): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6697): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6697): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6697): TimaSignature is unavailable
,D/ActivityThread( 6697): Added TimaKeyStore provider
,D/ResourcesManager( 6697): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,I/UpdateIcingCorporaServi( 1556): UpdateCorporaTask done [took 110 ms] updated apps [took 110 ms] 
,D/FileShare-Server( 6697): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6712): MountEmulatedStorage()
E/Zygote  ( 6712): v2
I/libpersona( 6712): KNOX_SDCARD checking this for 1000
I/libpersona( 6712): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6712 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5576:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/art     (  890): Background partial concurrent mark sweep GC freed 309960(19MB) AllocSpace objects, 3(3MB) LOS objects, 24% free, 48MB/64MB, paused 1.868ms total 130.264ms
,I/SELinux ( 6712): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6712): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6712): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6712): TimaSignature is unavailable
,D/ActivityThread( 6712): Added TimaKeyStore provider
,D/ResourcesManager( 6712): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 6712): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_5576/cgroup.procs: No such file or directory
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6734): MountEmulatedStorage()
,E/Zygote  ( 6734): v2
I/libpersona( 6734): KNOX_SDCARD checking this for 10086
I/libpersona( 6734): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.chaton for broadcast com.sec.chaton/.plugin.PlugInMonitor: pid=6734 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5607:com.LocalFota/u0a120 (adj 15): bgCount ##41
,I/SELinux ( 6734): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6734): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6734): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6734): TimaSignature is unavailable
,D/ActivityThread( 6734): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10120/pid_5607/cgroup.procs: No such file or directory
,D/ResourcesManager( 6734): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 6734): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 6394): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/PushModule( 6734): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 6734): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 6734): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 6734): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 6734): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  890): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ChatON  ( 6734): [1][a] ChatONV isn't installed.
,D/ChatON  ( 6734): [1][a] ChatONVPlugIn.isAvailable()
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6753): MountEmulatedStorage()
E/Zygote  ( 6753): v2
I/libpersona( 6753): KNOX_SDCARD checking this for 1000
I/libpersona( 6753): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6753 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5642:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
,W/PackageManager(  890): verifying app can be installed or not
,D/ApplicationPolicy(  890): isApplicationInstallationEnabled
,D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking PKG WL - false
,D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking PKG WL - false
,D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  Checking SIG BL - true
,I/SELinux ( 6753): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6753): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6753): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ApplicationPolicy(  890): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall(  890): product true
,D/TimaKeyStoreProvider( 6753): TimaSignature is unavailable
,D/ActivityThread( 6753): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_5642/cgroup.procs: No such file or directory
,D/ResourcesManager( 6753): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/ShortcutReceiver( 6753):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6769): MountEmulatedStorage()
,E/Zygote  ( 6769): v2
I/libpersona( 6769): KNOX_SDCARD checking this for 10030
I/libpersona( 6769): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6769 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6769): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6769): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6769): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  890): Killing 5661:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6769): TimaSignature is unavailable
,D/ActivityThread( 6769): Added TimaKeyStore provider
,D/ResourcesManager( 6769): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10138/pid_5661/cgroup.procs: No such file or directory
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/Finsky  ( 6769): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     (  890): Background partial concurrent mark sweep GC freed 221609(13MB) AllocSpace objects, 8(7MB) LOS objects, 24% free, 48MB/64MB, paused 2.757ms total 104.539ms
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/Finsky  ( 6769): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6806): MountEmulatedStorage()
E/Zygote  ( 6806): v2
I/libpersona( 6806): KNOX_SDCARD checking this for 10012
I/libpersona( 6806): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6806 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,I/SELinux ( 6806): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6806): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6806): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6769): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6769): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6806): TimaSignature is unavailable
,D/ActivityThread( 6806): Added TimaKeyStore provider
,D/ResourcesManager( 6806): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6806): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6806): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6806): VM with version 2.1.0 has multidex support
I/MultiDex( 6806): install
I/MultiDex( 6806): VM has multidex support, MultiDex support library is disabled.
,D/Finsky  ( 6769): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6769): [1] 2.run: Finished loading 1 libraries.
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,V/JNIHelp ( 6806): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/ActivityManager(  890): Killing 5622:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,D/Finsky  ( 6769): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 2468): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,D/Finsky  ( 6769): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PeopleContactsSync( 2468): CP2 sync disabled
,W/ActivityThread( 6806): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6806): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@207d16e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6806): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  890): failed to open /acct/uid_10045/pid_5622/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1556): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/FileShare-Server( 6697): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,I/GAV2    ( 6462): Thread[GAThread,5,main]: No campaign data found.
,D/ShortcutReceiver( 6753):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ResourcesManager( 2468): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/PackageBroadcastService( 2468): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2468): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2468): updateResources: need to parse f{com.google.android.gms}
,D/ResourcesManager( 6806): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  890): [s] UserActivityState : 2 -> 4
,I/PowerManagerService(  890): Nap time (uid 1000)...
I/PowerManagerService(  890): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  890): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  890): setDeviceInteractive: 0
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  890): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  890): SecHardwareInterface.setBatteryADC : false
,D/PackageManager(  890): Existing package
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  890): handleSandman : startDream()
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  890): 	.unregisterCallback : 1, client=
D/SContextService(  890): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@9bc4a6f, Service = Auto Rotation, used = 1
,D/ResourcesManager( 1556): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/PackageManager(  890): Renaming /data/app/vmdl708751544.tmp to /data/app/com.test.thalitest-1
,E/PowerManagerService(  890): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  890): Sleeping (uid 1000)...
D/PowerManagerService(  890): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  890): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  890): [input device light] handleInputDeviceLightOff
D/PackageManager(  890): installNewPackageLI: Package{18a51d70 com.test.thalitest}
,I/UpdateIcingCorporaServi( 1556): UpdateCorporaTask done [took 286 ms] updated apps [took 286 ms] 
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  890): stop(ContextProvider.java:149)
,V/CAE     (  890): clear(AutoRotationRunner.java:182)
V/CAE     (  890): disable(AutoRotationRunner.java:171)
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,I/Adreno-EGL(  890): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  890): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  890): Build Date: 03/03/15 Tue
I/Adreno-EGL(  890): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  890): Remote Branch: 
I/Adreno-EGL(  890): Local Patches: 
I/Adreno-EGL(  890): Reconstruct Branch: 
,D/CAE     (  890): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  890): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/ResourcesManager( 6806): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,V/Finsky  ( 6769): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,D/CAE     (  890): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  890): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  890): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  890): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  890): removeSContextService() : service = Auto Rotation
D/SContextService(  890): ===== SContext Service List =====
D/SContextManager(  890):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3f5837f, service=Auto Rotation
,D/KeyguardViewMediator( 1170): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1170): *** KeyguardEffectView getInstanceIfExists ***
,D/KeyguardEffectViewController( 1170): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1170): notifyScreenOffLocked
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
I/SQLiteSecureOpenHelper( 3254): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3254): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): timeout : 5000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KeyguardViewMediator( 1170): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 1170): handleNotifyScreenOff
,I/CAE     (  890): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  890): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
,D/SensorHubManager(  890): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService(  890): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/DisplayPowerController(  890): ColorFade: onAnimationStart
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  890):  handler : SCREEN_ON end
,D/lights  (  890): lcd : 0 +
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,D/NotificationService(  890): ACTION_SCREEN_ON
,D/LightsService(  890): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 890) 
,D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  890): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=on
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,V/voice   (  291): voice_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,D/lights  (  890): lcd : 0 -
D/WifiStateMachine(  890): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  890): handleScreenStateChanged Exit: true
,I/ActivityManager(  890): Killing 5697:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
,I/SecExternalDisplayIntents_Java(  890): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  890): do suspend false
,I/wpa_supplicant( 1269): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1269): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1269): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1269): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController(  890): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController(  890): Bridge Server is not available
,D/PersonaManagerService(  890): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  890): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1470): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1470): call the applyRotuiing
,I/SamsungIME( 1864): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,W/libprocessgroup(  890): failed to open /acct/uid_10143/pid_5697/cgroup.procs: No such file or directory
,D/accuweather( 2138): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
,D/DisplayPowerState(  890): !@ ColorFade entry
,D/DisplayPowerController(  890): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  890): Light old sensor_state 8705, new sensor_state : 8193 en : 0
I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager(  890): unregisterListener ::   
,E/Sensors (  890): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  890): unregisterListener ::   
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  890): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  890): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/AlarmManager(  890): waitForAlarm result :4
,I/SystemBroadcastReceiver( 6169): [#DCM#] [DCM_Performance] onReceive completed in time  328 microsec. 
,I/SystemBroadcastReceiver( 6169): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 6169): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 6169): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/Finsky  ( 6769): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 890) 
,D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,E/LightSensor(  890): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  890): turn on LED for charging
,D/BatteryService(  890): level:100, scale:100, status:2, health:2, present:true, voltage: 4175, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for charging
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,I/CAE     (  890): handleMessage(CaPowerManager.java:182) - AP_SLEEP
I/CAE     (  890): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 18, 11, 56,
D/SensorHubManager(  890): SendSensorHubData: send data = -63, 14, 18, 11, 56
,D/Sensorhubs(  297): sendContextData: -63, 14, 18, 11, 56
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:m  (  890): SIOP:: AP = 480, PST = 444, CUR = 300
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  890):  handler : SCREEN_OFF end 
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/WifiStateMachine(  890): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  890): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  890): do suspend true
D/NotificationService(  890): ACTION_SCREEN_OFF
D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x12 | SvcLED(id=4) set On
V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  890): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,I/SELinux (  294): selinux_android_setcategory: no category for userid: 0, path: /data/data/com.test.thalitest/lib 
,I/art     (  890): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     (  890): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
,D/PackageManager(  890): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,D/IpRemoteDisplayController(  890): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  890): Bridge Server is not available
,W/Finsky  ( 6769): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1170): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1170): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PersonaManagerService(  890): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  890): MSG_ACTION_SCREEN_OFF called
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/dex2oat ( 6861): ----------------------------------------------------
,I/dex2oat ( 6861): <SS>: S T A R T I N G . . .
I/dex2oat ( 6861): <SS>: going to process manifest...
I/        ( 6861): SS_ART_lib [I]: Processing Manifest...
,D/NfcService( 1470): call the applyRotuiing
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/        ( 6861): SS_ART_lib [I]: XML is parsed (58 > 55)
,I/        ( 6861): SS_ART_lib [I]: XML is parsed (58 > 55)
I/dex2oat ( 6861): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/STATUSBAR-PhoneStatusBar( 1170):      ACTION_SCREEN_OFF is finished!!!! 
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  890): Excessive delay in setPowerMode(): 272ms
D/PowerManagerService(  890): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  890): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  890): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  890): Invalid hint ID.
I/QCOM PowerHAL(  890): Got set_interactive hint
,I/PowerManagerService(  890): [PWL] Off : 0s ago
I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2468, ws=null) (elapsedTime=17044)
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=890, ws=WorkSource{10046}) (elapsedTime=16909)
I/PowerManagerService(  890): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  890): [PWL]     mDisplayReady : false
I/PowerManagerService(  890): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Display
,E/StatusBar( 1170): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1170): dismissHelpPopup 
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2138): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/Finsky  ( 6769): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/SSRM:m  (  890): SIOP:: AP = 490, PST = 450, CUR = 300
D/X       (  890): broadcastSiopLevelIntent:: currentSiopLevel = 1
,I/SystemBroadcastReceiver( 6169): [#DCM#] [DCM_Performance] onReceive completed in time  68 microsec. 
,I/SystemBroadcastReceiver( 6169): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6169): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 6169): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,I/SystemBroadcastReceiver( 6169): [#DCM#] [DCM_Performance] onReceive completed in time  61 microsec. 
I/SystemBroadcastReceiver( 6169): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6169): [#DCM#] onReceive action = EVENT_SIOP
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ContentApp( 1221):  LEVEL : 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  890): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  890): unregisterListener ::   
D/lights  (  890): led_pattern : 3 +
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,E/SMD     (  284): DCD ON
,D/lights  (  890): led_pattern : 3 -
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Broadcasts
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6873): MountEmulatedStorage()
I/libpersona( 6873): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6873): v2
I/libpersona( 6873): KNOX_SDCARD not a persona
,E/SQLiteLog( 5681): (284) automatic index on view_events(_id)
,I/ActivityManager(  890): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6873 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6873): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  310): Explicit concurrent mark sweep GC freed 8762(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 280us total 20.993ms
,I/SELinux ( 6873): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6873): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 8.278ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 7.983ms
,D/CalendarAlarmManager( 5681): sys current time:1454523117024
,D/CalendarAlarmManager( 5681): reminder amount:0
,I/dex2oat ( 6861): <SS>: going to form and sign ss id...
I/dex2oat ( 6861): dex2oat took 474.592ms (threads: 4)
,D/TimaKeyStoreProvider( 6873): TimaSignature is unavailable
,D/ActivityThread( 6873): Added TimaKeyStore provider
,I/PackageManager(  890): do mInstaller.dexopt : 0
D/PackageManager(  890): Time to dexopt: 0.548 seconds
,W/System.err(  890): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err(  890): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err(  890): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err(  890): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5071)
,W/System.err(  890): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:17035)
W/System.err(  890): 	at com.android.server.pm.PackageManagerService.access$5100(PackageManagerService.java:313)
W/System.err(  890): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:17020)
,W/System.err(  890): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err(  890): 	at libcore.io.IoBridge.open(IoBridge.java:446)
D/ResourcesManager( 6873): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,W/System.err(  890): 	... 5 more
,D/PackageManager(  890): New package installed
,I/HarmonyEASService(  890): Updating for all 1
,D/SSRM:a  (  890): DeviceInfo:: 000000000000
D/SSRM:a  (  890): SettingsAirViewInfo:: 000000000
,D/PackageManager(  890): doPostInstall for uid{10200}
,D/PackageManager(  890): token 1 to BM for possible restore
,E/MTPRx   ( 6873): In MtpReceiverandroid.hardware.usb.action.USB_STATE
V/BackupManagerService(  890): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService(  890): Finishing install immediately
D/PackageManager(  890): BM finishing package install for 1
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/SecContentProvider2(  890): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
V/MTPRx   ( 6873): sealedState: false
V/MTPRx   ( 6873): sealedUsbMassStorageState: false
,E/MTPRx   ( 6873): check value of boot_completed is1
E/MTPRx   ( 6873): check booting is completed_sys.boot_completed
,E/MTPRx   ( 6873): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 6873): Status for mount/Unmount :removed
E/MTPRx   ( 6873): SDcard is not available
,W/MTPRx   ( 6873): value of connected istrue
W/MTPRx   ( 6873): value of configured istrue
W/MTPRx   ( 6873): value of mtpEnabled istrue
W/MTPRx   ( 6873): value of ptpEnabled isfalse
,E/MTPRx   ( 6873): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 6873): mFirstTime: false
,D/PackageManager(  890): [MSG] MCS_UNBIND
,D/PackageManager(  890): [MSG] POST_INSTALL: observer{245012378}
D/PackageManager(  890):           Handling post-install for 1
,W/Settings(  890): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,E/SQLiteLog( 1680): (10) POSIX Error : 11 SQLite Error : 3850
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/        ( 6873): MTP: reading debug level property
,E/MTPRx   ( 6873):  String obtained from jar = 0b1e96db05d64ea4
E/MTPJNIInterface( 6873): Getting CryptionKey from JAVA
E/MTPRx   ( 6873): currentUserId is 0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/MTPRx   ( 6873): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 6873): usbMode is 0210
E/MTPRx   ( 6873): is_Privatemode is NOT 1
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SettingsProvider(  890): name = mtp_usb_conditions_met
,E/SamsungIME( 1864): mOCRHelper is null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 1489): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/SecContentProvider(  890): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 6873): sending MTP_ICON_ENABLED to stack
,D/ResourcesManager( 1489): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/SettingsProvider(  890): name = mtp_running_status
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/SettingsProvider(  890): name = mtp_usb_conditions_met
,E/MTPRx   ( 6873): else part ... so first time!!!
,E/MTPPlaObsrvr( 6873): inside setContext()
E/MTPPlaObsrvr( 6873):  inside createplafiles
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 1489): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1489): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/MTPPlaObsrvr( 6873): playlist count is0
E/MTPPlaObsrvr( 6873):  inside try branch createplafiles
,V/BitmapFactory( 1489): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/icon.png
E/MTPPlaObsrvr( 6873):  inside deleteing plas createplafiles
,D/ResourcesManager( 1489): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,E/MTPPlaObsrvr( 6873): Inside registerContentObserver
,E/MtpAdbObserver( 6873): inside setContext()
E/MtpAdbObserver( 6873): Inside registerContentObserver
W/Settings( 6873): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 1489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/SettingsProvider(  890): name = mtp_running_status
W/ResourcesManager( 1489): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/SettingsProvider(  890): name = mtp_usb_conditions_met
,E/MtpService( 6873): onCreate.
,E/MtpService( 6873): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 6873): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/MtpService( 1221): updating state; isCurrentUser=true, mMtpLocked=false
,E/MtpService( 6873): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/TMNetworkReceiver( 6059): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() Enter
,D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
,D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = true, mIsFileUpdated= false
D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() mThread.interrupt()
,D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() USB CONNECTED
,D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() Exit 
E/MtpService( 6873): onStartCommand.
,D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() interrupted while sleeping 
D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() UsbCheck Thread Exit
,D/TMNetworkReceiver( 6059): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
,W/MTPRx   ( 6873): calling native method
E/MTPJNIInterface( 6873): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 6873): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,D/RegisteredServicesCache( 1470): empty dynamic service
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/TMSLogRemovalReceiver( 6059): TMLogRemovalReceiver.onReceive() Enter isCalled =true
,D/TMSLogRemovalReceiver( 6059): TMLogRemovalReceiver.onReceive() Exit
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,E/MTPJNIInterface( 6873): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 6873): noti = 10
,D/MediaScannerReceiver( 1221): action: android.intent.action.MTP_FILE_SCAN
,E/MtpService( 6873): onStartCommand.
,W/MTPRx   ( 6873): calling native method
E/MTPRx   ( 6873): Checking the driver time out
E/MTPJNIInterface( 6873): noti = 2
D/        ( 6873): deleting sockets before message queue initialization
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/        ( 6873): event handler thread is created, so set the flag
,E/MTPRx   ( 6873): called native method
E/MTPJNIInterface( 6873): setting Media scanner status0
E/MTPJNIInterface( 6873): After setting Media scanner status0
W/MTPRx   ( 6873): notification from stack 1
,E/        ( 6873): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
,E/MTPJNIInterface( 6873): Getting media scanner status0
,E/MtpService( 6873): handleMessage. msg= { when=-2ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MTPJNIInterface( 6873): DeviceName is Thali Test (Galaxy S5)
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,E/Zygote  ( 6896): MountEmulatedStorage()
,E/Zygote  ( 6896): v2
I/libpersona( 6896): KNOX_SDCARD checking this for 1000
I/libpersona( 6896): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=6896 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ThermalEngine(  305): Sensor:tsens_tz_sensor5:87000 mC
,I/ThermalEngine(  305): Sensor:tsens_tz_sensor5:87000 mC
I/ThermalEngine(  305): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm raised 1 at 87.0 degC
,I/ThermalEngine(  305): ACTION: OPT_CURR_REQ 1
,I/SELinux ( 6896): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6896): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6896): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/TimaKeyStoreProvider( 6896): TimaSignature is unavailable
,D/ActivityThread( 6896): Added TimaKeyStore provider
,D/RCPManagerService(  890): PackageReceiver onReceive()
,D/MediaScannerService( 1221): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,I/Avrcp   ( 3872): Received the onChange database event
,I/Avrcp   ( 3872): onChange on thread: 1 Uri: content://media/ selfchange: false
I/Avrcp   ( 3872): send MSG_CHECK_NOW_PLAYING_CONTENT_CHANGED after 500ms
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
D/MediaProvider( 1221): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1221): savePlaylistTableInBulkDeleter finished
,D/RCPManagerService(  890): App Installed with packageNAme = com.test.thalitest
D/ResourcesManager( 6896): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/RCPManagerService(  890):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService(  890):  PackageReceiver onReceive() bundle null
D/EnterpriseDeviceManagerService(  890): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  890): Admin package name: com.google.android.gms
,D/KnoxMUMContainerPolicy(  890): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/MediaScanner( 1221): Prescan. DB items number : 21 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,W/BackupManagerService(  890): Removing schedule queue dupe of com.test.thalitest
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
,V/EnterpriseBillingPolicy(  890): uID is 10200
V/EnterpriseBillingPolicy(  890): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  890): getProfileForApplication - exit null
,V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  890): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  890): getBillingProfileForVpnEngine - end - null
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,V/MediaScanner( 1221): processDirectory :  /storage/emulated/0
,D/PersonaPolicyManagerService(  890): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,D/MediaScanner( 1221): Skipping:
,D/MediaScanner( 1221): 7klwibgf7fvntblfd7(75ebcf7
,D/KnoxMUMContainerPolicy(  890): packageInstalledForExternalStorage com.test.thalitest
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/MediaScanner( 1221): Skipping:
D/MediaScanner( 1221): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,I/DIAGMON_AGENT( 6896): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,V/MediaScanner( 1221): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1221): Error opening directory, reason : Permission denied.
W/MediaScanner( 1221): 7klwibgf7fxlKdCbid7
,E/File    ( 1221): fail readDirectory() errno=2
,V/MediaScanner( 1221): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@1cd5f141
,I/DIAGMON_AGENT( 6896): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
V/MediaScanner( 1221): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@1cd5f141
,V/MediaScanner( 1221):  prescan time: 86ms (DB items: 21)
V/MediaScanner( 1221):     scan time: 32ms (Caching mode: true), (makeEntry time: 17ms ~53%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1221): postscan time: 21ms (bulkDeleter : 0), (delete DeadThumbnail time : 14ms)
V/MediaScanner( 1221):    total time: 139ms
V/MediaScanner( 1221): checked files: 4  directories : 17  (I: 0, U: 0)
,I/art     (  890): Explicit concurrent mark sweep GC freed 138885(8MB) AllocSpace objects, 16(3MB) LOS objects, 23% free, 51MB/67MB, paused 4.946ms total 476.605ms
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/art     (  890): WaitForGcToComplete blocked for 84.282ms for cause Explicit
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,E/MTPJNIInterface( 6873): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
D/MediaScannerService( 1221): !@done scanning volume external
,D/PackageManager(  890): result of install: 1{245012378}
,I/PackageManager(  890): Observer no longer exists.
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/art     (  890): Explicit concurrent mark sweep GC freed 9601(530KB) AllocSpace objects, 0(0B) LOS objects, 23% free, 51MB/67MB, paused 2.009ms total 116.114ms
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/iu.UploadsManager( 2468): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ActivityManager(  890): Killing 5868:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
,I/iu.UploadsManager( 2468): End new media; added: 0, uploading: 0, time: 64 ms
,E/MTPJNIInterface( 6873): Status for mount/Unmount :removed
E/MTPJNIInterface( 6873): SDcard is not available
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,I/DIAGMON_AGENT( 6896): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/        ( 6873): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_5868/cgroup.procs: No such file or directory
,E/MTPJNIInterface( 6873): Status for mount/Unmount :removed
E/MTPJNIInterface( 6873): SDcard is not available
,E/SQLiteLog( 6873): (21) API call with NULL database connection pointer
E/SQLiteLog( 6873): (21) misuse at line 105654 of [9491ba7d73]
E/SQLiteLog( 6873): (21) API call with NULL database connection pointer
E/SQLiteLog( 6873): (21) misuse at line 100436 of [9491ba7d73]
E/SQLiteLog( 6873): (21) API call with NULL database connection pointer
E/SQLiteLog( 6873): (21) misuse at line 100436 of [9491ba7d73]
E/SQLiteLog( 6873): (21) API call with NULL database connection pointer
E/SQLiteLog( 6873): (21) misuse at line 105654 of [9491ba7d73]
,W/MTPRx   ( 6873): notification from stack 2
,I/DIAGMON_AGENT( 6896): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,D/        ( 6873): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 6873): [mtp_init_device 692]  After open the MTP fd = 32 and line = 692...
D/        ( 6873): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 6873):  [sua_support_present:1275] returning false 
D/        ( 6873): *****Starting mtp_io()
,D/        ( 6873): [mtp_start_io] source_thread Creation 
W/MTPRx   ( 6873): notification from stack 3
D/        ( 6873): [mtp_start_io] sink_thread Creation 
,D/        ( 6873): [mtp_start_io:368] sink thread created so set th_sink
I/DIAGMON_AGENT( 6896): [com.diagmondm.XDMBroadcastReceiver(34/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/ActivityManager(  890): Killing 5874:com.android.email/u0a163 (adj 15): bgCount ##41
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/DBG_DM  ( 4425): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,V/TaskCloserActivity( 6079): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/SettingSearch/SearchIntentReceiver( 1297): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1297): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,I/SettingSearch/SearchIntentReceiver( 1297): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,I/SettingSearch/SearchIntentReceiver( 1297): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1297): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10163/pid_5874/cgroup.procs: No such file or directory
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/Avrcp   ( 3872): handleMessage, msg=207
D/BluetoothMediaBrowser( 3872):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/BluetoothMediaBrowser( 3872): no now playing list
D/BluetoothMediaBrowser( 3872):  getNowPlayingId now playing id : -1
D/Avrcp   ( 3872):  checkNowPlayingList start
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,I/SettingSearch/SettingsSearchManager( 1297): Infomation -> numtitleinfo : 0 numSearchinfo : 334
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/WearableService( 5449): callingUid 10012, callindPid: 5449
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/MusicLeanback( 5988): Conditions not met for autocaching.
,I/MusicLeanback( 5988): Stop autocaching.
,I/CrashAnrDetector(  890): onPackageAdded : com.test.thalitest
,D/WearableClient( 5988): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5988): WearableClientImpl.onPostInitHandler: done
,W/Finsky  ( 6769): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/WearableClient( 5988): WearableClientImpl.onPostInitHandler: done
,D/Finsky  ( 6769): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/WearableClient( 5988): WearableClientImpl.onPostInitHandler: done
,D/GCM     ( 1680): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Finsky  ( 6769): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/GmsUtils( 5988): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/Finsky  ( 6769): [1] DailyHygiene.reschedule: Giving up. (failures=6)
,D/AuthorizationBluetoothService( 1680): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/GmsUtils( 5988): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/DeviceConnectionService( 2266): client connected with version: 7571000
,I/SettingSearch/SettingsSearchManager( 1297):  Infomation -> getItem size : 334
,V/GmsCoreStatsServiceLauncher( 2468): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  890): Killing 5812:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,I/ActivityManager(  890): Killing 6095:com.sec.factory/1000 (adj 15): bgCount ##42
,D/ResourcesManager( 1297): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 1297): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,E/MDM     ( 2266): [242] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2468): Restart initialization of location
,I/art     ( 2266): Explicit concurrent mark sweep GC freed 26666(1555KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 18MB/30MB, paused 505us total 47.344ms
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6095/cgroup.procs: No such file or directory
,W/libprocessgroup(  890): failed to open /acct/uid_10078/pid_5812/cgroup.procs: No such file or directory
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,W/ResourcesManager( 1297): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1297): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
W/ResourcesManager( 1297): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1297): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/comsamsunglog( 1368): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1368): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
D/comsamsunglog( 1368): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1368): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1454544660000
D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1454523118274
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1368): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/ResourcesManager( 1297): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1368): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,E/TranscodeReceiver( 6414): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 6414):  SIOP_LEVEL: 1
,I/HomeSyncInstallReceiver( 1470): This pkg do not need BT addr. Do nothing
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6938): MountEmulatedStorage()
I/libpersona( 6938): KNOX_SDCARD checking this for 10015
E/Zygote  ( 6938): v2
I/libpersona( 6938): KNOX_SDCARD not a persona
D/ResourcesManager( 3343): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/ActivityManager(  890): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6938 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6938): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6938): TimaSignature is unavailable
,D/ActivityThread( 6938): Added TimaKeyStore provider
,V/AlarmManager(  890): waitForAlarm result :8
,D/ResourcesManager( 6938): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6956): MountEmulatedStorage()
,E/Zygote  ( 6956): v2
I/libpersona( 6956): KNOX_SDCARD checking this for 10016
I/libpersona( 6956): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=6956 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6956): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6956): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6956): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6956): TimaSignature is unavailable
,D/ActivityThread( 6956): Added TimaKeyStore provider
,D/ResourcesManager( 6956): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
,W/ResourcesManager( 6956): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6956): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/GroupCast_FileTools( 6956): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 6956): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,W/System.err( 6956): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 6956): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
,W/System.err( 6956): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 6956): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 6956): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
,W/System.err( 6956): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6956): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6956): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6956): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 6956): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6956): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6956): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 6956): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6956): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6971): MountEmulatedStorage()
,E/Zygote  ( 6971): v2
I/libpersona( 6971): KNOX_SDCARD checking this for 1000
I/libpersona( 6971): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SettingSearch/SearchIntentReceiver( 1297): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1297): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager(  890): Killing 6149:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6971): TimaSignature is unavailable
,D/ActivityThread( 6971): Added TimaKeyStore provider
,D/ResourcesManager( 6971): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,I/PCWCLIENTTRACE_LOG( 6971): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 6971): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6971): new DMDBOpenHelper instance
,I/PCWCLIENTTRACE_PushUtil( 6971): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6971): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6971): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6971): [onReceive] - android.intent.action.PACKAGE_ADDED
,W/libprocessgroup(  890): failed to open /acct/uid_10025/pid_6149/cgroup.procs: No such file or directory
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6989): MountEmulatedStorage()
,E/Zygote  ( 6989): v2
I/libpersona( 6989): KNOX_SDCARD checking this for 1000
I/libpersona( 6989): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=6989 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6249:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,I/SELinux ( 6989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6989): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SettingSearch/SearchIntentReceiver( 1297): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/libprocessgroup(  890): failed to open /acct/uid_10002/pid_6249/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6989): TimaSignature is unavailable
,D/ActivityThread( 6989): Added TimaKeyStore provider
,I/SettingSearch/SearchIntentReceiver( 1297): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1297): LOCALE_CHANGED call search setting db finish!!
,D/ResourcesManager( 6989): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7009): MountEmulatedStorage()
,E/Zygote  ( 7009): v2
I/libpersona( 7009): KNOX_SDCARD checking this for 10045
I/libpersona( 7009): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=7009 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6289:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,I/SELinux ( 7009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SELinux ( 7009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7009): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7009): TimaSignature is unavailable
,W/libprocessgroup(  890): failed to open /acct/uid_10172/pid_6289/cgroup.procs: No such file or directory
,D/ActivityThread( 7009): Added TimaKeyStore provider
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 7009): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/SA      ( 7009): [SSP] onCreated
,I/SA      ( 7009): [TPM] There is no property file
,I/SA      ( 7009): [SCU] isHaveSA() - false
,I/SA      ( 7009): [TPM] getModelProperty : null
I/SA      ( 7009): [TPM] getCSCProperty : null
,I/SA      ( 7009): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 7009): [DM] init START
,I/SA      ( 7009): [DM] This device is not a Vodafone
,W/ResourceType( 7009): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 7009): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,W/ResourceType( 7009): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 7009): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 7009): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 7009): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7009): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
,W/ResourceType( 7009): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 7009): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 7009): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 7009): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 7009): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 7009): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 7009): [SCU] isHaveSA() - false
I/SA      ( 7009): support phone number id : false
,I/SA      ( 7009): [DM] init END
I/SA      ( 7009): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 7009): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10200 extra.user_handle.:0 ]
,I/ActivityManager(  890): Killing 6169:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,W/libprocessgroup(  890): failed to open /acct/uid_10004/pid_6169/cgroup.procs: No such file or directory
,D/Mms/FreeMessageReceiver( 6115): onReceive, action : android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService( 6115): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 6115): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 7030): MountEmulatedStorage()
I/libpersona( 7030): KNOX_SDCARD checking this for 10051
E/Zygote  ( 7030): v2
I/libpersona( 7030): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7030 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/SELinux ( 7030): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7030): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7030): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7030): TimaSignature is unavailable
,D/ActivityThread( 7030): Added TimaKeyStore provider
,D/ResourcesManager( 7030): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 7030): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7030): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/MyFiles ( 7030): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,I/TactileAssist(  890): enable value -1
I/TactileAssist(  890): internal enable value -1
I/TactileAssist(  890): intensity value -1
I/TactileAssist(  890): saveAppList value true
,E/installd(  294): system dir 0 : /system/app/
E/installd(  294): system dir 1 : /system/priv-app/
E/installd(  294): system dir 2 : /vendor/app/
E/installd(  294): system dir 3 : /oem/app/
I/TactileAssist(  890): List of disabled apps :
I/TactileAssist(  890): de.zalando.mobile
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7046): MountEmulatedStorage()
E/Zygote  ( 7046): v2
I/libpersona( 7046): KNOX_SDCARD checking this for 10058
I/libpersona( 7046): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7046 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 7046): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7046): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7046): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/PackageManager(  890): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/TimaKeyStoreProvider( 7046): TimaSignature is unavailable
,D/ActivityThread( 7046): Added TimaKeyStore provider
,D/ResourcesManager( 7046): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,I/ThermalEngine(  305): Sensor:tsens_tz_sensor5:75000 mC
,I/ThermalEngine(  305): Sensor:tsens_tz_sensor5:75000 mC
I/ThermalEngine(  305): TM Id 'OPT_CURR_MONITOR-TSENS5' Sensor 'tsens_tz_sensor5' - alarm cleared 1 at 75.0 degC
,I/ThermalEngine(  305): ACTION: OPT_CURR_REQ 0
,W/ResourcesManager( 7046): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 7046): onReceive() it will make start service
,D/Compatibility( 7046): onHandleIntent()
,D/Compatibility( 7046): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10200, android.intent.extra.user_handle=0}]
,D/Compatibility( 7046): found: 2
,I/UpdateIcingCorporaServi( 1556): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 7046): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 7046): skipping ResolveInfo{2f5ae3f3 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7046): considering ResolveInfo{1c1948b0 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7046): default: com.sec.android.app.soundalive.SAControlPanelActivity
,W/ContextImpl( 6446): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,D/Compatibility( 7046): enabling receiver ResolveInfo{1309c329 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 7046): enabling receiver ResolveInfo{2f54c6ae com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7046): enabling receiver ResolveInfo{1435cc4f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 7046): enabling receiver ResolveInfo{13423fdc com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7046): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7067): MountEmulatedStorage()
I/libpersona( 7067): KNOX_SDCARD checking this for 10098
E/Zygote  ( 7067): v2
I/libpersona( 7067): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7067 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  890): Killing 6211:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,D/ResourcesManager( 1556): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/SELinux ( 7067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7067): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  890): failed to open /acct/uid_10044/pid_6211/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 7067): TimaSignature is unavailable
,D/ActivityThread( 7067): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 1556): UpdateCorporaTask done [took 100 ms] updated apps [took 100 ms] 
,D/ResourcesManager( 7067): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/DocsApplication( 7067): Installing DEX configuration.
,D/DexInstaller( 7067): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 7067): Provided clientMode=RELEASE, packageInfo=PackageInfo{3f2ea662 com.google.android.apps.docs}
,D/TAG     ( 7067): onCreate()
,D/CrossAppStateProvider( 7067): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Search.LoginHelper( 1556): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,E/SMD     (  284): DCD ON
,I/wpa_supplicant( 1269): nl80211: Received scan results (5 BSSes)
,D/WifiP2pService(  890): InactiveState{ what=147461 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147461 }
D/WifiP2pService(  890): DefaultState{ what=147461 }
,E/WifiStateMachine(  890): [1,454,523,119,921 ms] noteScanEnd no scan source
,E/WifiStateMachine(  890): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@160fe2c3 sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  890): External Intent Received android.net.wifi.SCAN_RESULTS
,I/CheckinService( 2468): Done disabling old GoogleServicesFramework version
,V/AlarmManager(  890): waitForAlarm result :8
,I/Icing   ( 2468): Indexing EF63CEC2998F8E1A114BBA3A5515DD2FA8B6047E from com.google.android.googlequicksearchbox
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/GAV2    ( 7067): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 7097): MountEmulatedStorage()
I/libpersona( 7097): KNOX_SDCARD checking this for 10099
E/Zygote  ( 7097): v2
I/libpersona( 7097): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7097 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,I/SELinux ( 7097): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7097): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7097): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7097): TimaSignature is unavailable
,D/ActivityThread( 7097): Added TimaKeyStore provider
,D/ResourcesManager( 7097): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 7097): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 2468): Explicit concurrent mark sweep GC freed 23063(1645KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 19MB/32MB, paused 535us total 70.361ms
,D/Icing   ( 2468): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 2468): Indexing done EF63CEC2998F8E1A114BBA3A5515DD2FA8B6047E
,E/[CarMode]( 7097): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7097): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7097): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7126): MountEmulatedStorage()
E/Zygote  ( 7126): v2
I/libpersona( 7126): KNOX_SDCARD checking this for 10033
I/libpersona( 7126): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7126 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7126): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7126): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7126): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     (  310): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 291us total 11.045ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 8.187ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 249us total 8.209ms
,D/TimaKeyStoreProvider( 7126): TimaSignature is unavailable
,D/ActivityThread( 7126): Added TimaKeyStore provider
,D/ResourcesManager( 7126): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7126): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 7067): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ActivityManager(  890): Killing 6349:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,I/System.out( 7126): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 7126): Inside WakeupProvider
,E/DatabaseUtils( 7126): Writing exception to parcel
E/DatabaseUtils( 7126): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7126): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7126): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7126): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7126): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7126): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7126): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7126): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7126): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7126): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7126): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7097): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7097): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 7097): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7097): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7097): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
,W/System.err( 7097): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7097): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7097): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7097): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
,W/System.err( 7097): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
,W/System.err( 7097): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7097): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7097): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7097): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
,W/System.err( 7097): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7097): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7097): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7097): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
,W/System.err( 7097): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7097): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 7097): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7097): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7097): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7097): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 7097): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7097): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/libprocessgroup(  890): failed to open /acct/uid_10094/pid_6349/cgroup.procs: No such file or directory
,I/VlingoApplication( 7126): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,E/DatabaseUtils( 7126): Writing exception to parcel
E/DatabaseUtils( 7126): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7126): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7126): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7126): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7126): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7126): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7126): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7126): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7126): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7126): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7126): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7097): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7097): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7097): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7097): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
,W/System.err( 7097): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7097): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7097): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7097): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
,W/System.err( 7097): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7097): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
,W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7097): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7097): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
,W/System.err( 7097): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7097): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7097): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7097): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
,W/System.err( 7097): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7097): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7097): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7097): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 7097): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7097): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7097): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 7097): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7097): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 7097): [DLApplication]-Init Called!:false
,E/[CarMode]( 7097): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 7097): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7097): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7097): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7097): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7097): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7097): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7097): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7097): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7097): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7097): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7097): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7097): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7097): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7097): ### com.android.internal.os.ZygoteInit::main(1194)
,I/VlingoAndroidCore( 7126): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MessageDataHandler( 7097): initialize
,D/[CarModeFW]( 7097): CDH-initiazlieCaches : before sync
,D/[CarModeFW]( 7097): CDH-initiazlieCaches : after sync
,D/[CarModeFW]( 7097): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7097): CDH-ContactDataHandler initiazlieCaches time : 15
,D/[CarModeFW]( 7097): CDH-initiazlieCaches : end sync
,D/[CarModeFW]( 7097): DrivingManager-initialize...
,I/SensorService(  890): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
I/SensorService(  890): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  890): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/VlingoApplication( 7126): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 7126): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 7097): Need to enable context aware info
V/MediaPlayer-JNI( 7097): native_setup
V/MediaPlayer( 7097): constructor
,V/MediaPlayer( 7097): setListener
E/MediaPlayer-JNI( 7097): QCMediaPlayer mediaplayer NOT present
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,I/art     (  890): Explicit concurrent mark sweep GC freed 196670(12MB) AllocSpace objects, 3(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.624ms total 116.104ms
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/[CarModeFW]( 7097): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 7097): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 7097): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarMode]( 7097): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1454523121110
D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1454523121110
D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1454523121110
,D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1454523121110
D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1454523121111
,D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1454523121112
,I/[CarMode]( 7097): [LogNotNull]-Package name is: com.google.android.apps.maps
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 1476): query,matched:2, calling pid = 7097
,D/TP/SmsProvider( 1476): match 2:Elapsed time : 1.475 ms
,E/Zygote  ( 7165): MountEmulatedStorage()
I/libpersona( 7165): KNOX_SDCARD checking this for 10003
E/Zygote  ( 7165): v2
I/libpersona( 7165): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7165 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,E/[CarMode]( 7097): [DLApplication]-Init End!:true
,I/SELinux ( 7165): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/TP/SmsProvider( 1476): query,matched:2, calling pid = 7097
I/SELinux ( 7165): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7165): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TP/SmsProvider( 1476): match 2:Elapsed time : 2.248 ms
,D/[CarModeFW]( 7097): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 7097):  getInboxList smsCursor : 64
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7165): TimaSignature is unavailable
,D/ActivityThread( 7165): Added TimaKeyStore provider
,E/Zygote  ( 7179): MountEmulatedStorage()
E/Zygote  ( 7179): v2
I/libpersona( 7179): KNOX_SDCARD checking this for 10020
I/libpersona( 7179): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7179 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,I/SELinux ( 7179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7179): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 7097): CDH-buildContactCacheWireFrame : cur len =0
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ResourcesManager( 7165): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/TP/MmsProvider( 1476): Query uri=content://mms/inbox, match=2, calling pid = 7097
,D/TP/MmsProvider( 1476): Query uri=content://mms, match=0, calling pid = 7097
,D/[CarModeFW]( 7097): RecommendHandler-selection = type = '3'
,D/[CarMode]( 7097): [DLApplication]-GooglePlayServices SUCCESS.
,E/[CarMode]( 7097): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
D/MessageDataHandler( 7097):  getInboxList mmsCursor : 81
,I/UpdateManagerReceiver( 7097): Intent : android.intent.action.PACKAGE_ADDEDWed Feb 03 19:12:01 GMT+01:00 2016
,D/TimaKeyStoreProvider( 7179): TimaSignature is unavailable
,D/ActivityThread( 7179): Added TimaKeyStore provider
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7202): MountEmulatedStorage()
I/libpersona( 7202): KNOX_SDCARD checking this for 1000
E/Zygote  ( 7202): v2
I/libpersona( 7202): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7202 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/UserAnalysis.PlaceProvider( 7165): PlaceProvider onCreate()
,I/SELinux ( 7202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 7097): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7097): RecommendHandler-selection = type = '3'
,I/MessageDataHandler( 7097): getUnreadMessageCount :0
D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 231
,I/ActivityManager(  890): Killing 6371:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,D/MessageDataHandler( 7097):  getInboxList mms,sms cursor join : 90
,D/ResourcesManager( 7179): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,D/TimaKeyStoreProvider( 7202): TimaSignature is unavailable
,D/ActivityThread( 7202): Added TimaKeyStore provider
,D/[CarModeFW]( 7097): PushMessageService-onCreate
D/TP/MmsSmsProvider( 1476): query,matched:0, calling pid = 7097
V/TP/MmsSmsProvider( 1476): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1476): match 0:Elapsed time : 0.796 ms
,D/UserAnalysis.SecureDbManager( 7165): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7165): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7165): Create SecureDbHelper
,D/TP/MmsSmsProvider( 1476): query,matched:13, calling pid = 7097
,D/TP/MmsSmsProvider( 1476): match 13:Elapsed time : 0.854 ms
,I/ActivityManager(  890): Killing 6511:com.sec.android.app.sns3/u0a36 (adj 15): bgCount ##41
,I/ActivityManager(  890): Killing 5744:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##42
,D/ResourcesManager( 7202): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
I/ActivityManager(  890): Killing 6394:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##43
,D/[CarModeFW]( 7097): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7097): PushMessageService-registerPushMessageServiceListener
,D/IntelligenceServiceApplication( 7165): onCreate()
,I/SQLiteSecureOpenHelper( 7165): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7165): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7165): Open Place.db in secure mode
,D/MessageDataHandler( 7097):  getInboxList address cursor : 21
,D/TP/MmsSmsProvider( 1476): query,matched:0, calling pid = 7097
,V/TP/MmsSmsProvider( 1476): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1476): match 0:Elapsed time : 1.166 ms
,D/MessageDataHandler( 7097):  getInboxList thread cursor : 5
,D/MessageDataHandler( 7097):  thread, addr result: 3
,I/[CarModeFW]( 7097): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 290
I/[CarModeFW]( 7097): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 291
,W/ContextImpl( 7202): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,I/SQLiteSecureOpenHelper( 7165): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7165): ...getDatabaseLocked(b,b,pwd)
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7202): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  ( 7219): MountEmulatedStorage()
,E/Zygote  ( 7219): v2
I/libpersona( 7219): KNOX_SDCARD checking this for 10112
I/libpersona( 7219): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7219 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/FilterInstaller( 7202): There is no requred permission
D/[CarModeFW]( 7097): MyPlaceProvider-+++Begin print all data in content provider+++
,D/[CarModeFW]( 7097): MyPlaceProvider-=============
D/[CarModeFW]( 7097): MyPlaceProvider-=============
D/[CarModeFW]( 7097): MyPlaceProvider-=============
D/[CarModeFW]( 7097): MyPlaceProvider-=============
D/[CarModeFW]( 7097): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 7097): MyPlaceProvider-==============
D/[CarModeFW]( 7097): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7097): MyPlaceProvider-==============
D/[CarModeFW]( 7097): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7097): MyPlaceProvider-==============
D/[CarModeFW]( 7097): MyPlaceProvider-latitude is not valid
,I/SELinux ( 7219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager(  890): Killing 6591:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##41
,D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 360
,D/[CarMode]( 7097): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@352e9868, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@9149d83e] LOCATIONS
,D/TimaKeyStoreProvider( 7219): TimaSignature is unavailable
,D/ActivityThread( 7219): Added TimaKeyStore provider
,D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 395
,D/ResourcesManager( 7219): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,I/[CarModeFW]( 7097): -[snowdeer] Rec : Missed Call : 168
,I/[CarModeFW]( 7097): -[snowdeer] Rec : Favorite : 6
,W/libprocessgroup(  890): failed to open /acct/uid_10103/pid_6371/cgroup.procs: No such file or directory
,W/libprocessgroup(  890): failed to open /acct/uid_10154/pid_5744/cgroup.procs: No such file or directory
I/[CarModeFW]( 7097): -[snowdeer] Rec : CallLog : 4
,W/libprocessgroup(  890): failed to open /acct/uid_10113/pid_6394/cgroup.procs: No such file or directory
,W/libprocessgroup(  890): failed to open /acct/uid_10036/pid_6511/cgroup.procs: No such file or directory
,I/[CarModeFW]( 7097): -[snowdeer] Rec : Schedule : 10
,I/[CarModeFW]( 7097): -[snowdeer] Rec : During DL app : 2
,I/[CarModeFW]( 7097): -[snowdeer] Rec : Location Sharing : 3
I/[CarModeFW]( 7097): -[snowdeer] Rec : POI : 0
I/[CarModeFW]( 7097): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7097): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7097): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
I/[CarModeFW]( 7097): -[snowdeer] Rec : getContactListFromHashMap : 0
D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 424
,I/[CarModeFW]( 7097): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7097): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7097): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7097): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 426
D/PackageIntentReceiver( 7219): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7219): Not GearManger package! 
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7237): MountEmulatedStorage()
,E/Zygote  ( 7237): v2
I/libpersona( 7237): KNOX_SDCARD checking this for 10118
I/libpersona( 7237): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7237 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6621:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): bgCount ##41
,I/SELinux ( 7237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6591/cgroup.procs: No such file or directory
,I/SELinux ( 7237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7237): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7237): TimaSignature is unavailable
,D/ActivityThread( 7237): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10038/pid_6621/cgroup.procs: No such file or directory
,D/ResourcesManager( 7237): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7237): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MagazineService Version( 7237): Magazine-Administrator: 11
,D/MagazineService Version( 7237): Magazine-Provider: 14
,D/MagazineService Version( 7237): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7237): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7237): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7237): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,I/PowerManagerService(  890): [PWL] Off : 5s ago
I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2468, ws=null) (elapsedTime=22045)
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=890, ws=WorkSource{1000}) (elapsedTime=1916)
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=562)
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=562)
,E/Zygote  ( 7253): MountEmulatedStorage()
,E/Zygote  ( 7253): v2
I/libpersona( 7253): KNOX_SDCARD checking this for 1000
I/libpersona( 7253): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7253 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7237): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 7253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/ActivityManager(  890): Killing 6642:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): bgCount ##41
,I/SELinux ( 7253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7253): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7253): TimaSignature is unavailable
,D/ActivityThread( 7253): Added TimaKeyStore provider
,D/ResourcesManager( 7253): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10038/pid_6642/cgroup.procs: No such file or directory
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7268): MountEmulatedStorage()
,E/Zygote  ( 7268): v2
I/libpersona( 7268): KNOX_SDCARD checking this for 1000
I/libpersona( 7268): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5946:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,I/System.out( 7126): INFO:Resource not found:/Common.properties Using default values
,I/SELinux ( 7268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7268): TimaSignature is unavailable
,D/ActivityThread( 7268): Added TimaKeyStore provider
,D/ResourcesManager( 7268): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10149/pid_5946/cgroup.procs: No such file or directory
,D/AcmsPackageEventListener( 7268): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7268): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7268): Enter Oncreate
,D/AcmsServiceMonitor( 7268): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7268): creating AcmsCore
D/AcmsCore( 7268): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7268): AcmsCore
,D/AcmsCore( 7268): init
,D/AcmsCore( 7268): Looper handler is not null
D/AcmsCore( 7268): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7268): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7268): Incrementing - Counter value: 1
D/AcmsCore( 7268): Incremented Counter Value: postToAcmsCoreHandler =>1
,D/AcmsService( 7268): onStartCommand
D/AcmsCertificateMngr( 7268): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7268): AcmsRevocationMngr
,D/AcmsService( 7268): Action: android.intent.action.PACKAGE_ADDED
,D/AcmsServiceMonitor( 7268): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7268): Incrementing - Counter value: 2
D/AcmsService( 7268): Incremented Counter Value : onStartCommand
,D/ActivityThread( 7268): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7268): Inside handle Intent
,D/AcmsService( 7268): App added - package name: com.test.thalitest
D/AcmsCore( 7268): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7268): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7268): Incrementing - Counter value: 3
D/AcmsCore( 7268): Incremented Counter Value: postToAcmsCoreHandler =>2
,D/AcmsService( 7268): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7268): Decrementing - Counter value: 2
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7295): MountEmulatedStorage()
,E/Zygote  ( 7295): v2
I/libpersona( 7295): KNOX_SDCARD checking this for 10166
I/libpersona( 7295): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7295 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7295): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7295): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7295): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/TimaKeyStoreProvider( 7295): TimaSignature is unavailable
,D/ActivityThread( 7295): Added TimaKeyStore provider
,D/ResourcesManager( 7295): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7295): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7295): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7310): MountEmulatedStorage()
I/libpersona( 7310): KNOX_SDCARD checking this for 10170
E/Zygote  ( 7310): v2
I/libpersona( 7310): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7310 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 5723:com.android.calendar/u0a150 (adj 15): bgCount ##41
,I/SELinux ( 7310): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7310): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7310): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7310): TimaSignature is unavailable
,D/ActivityThread( 7310): Added TimaKeyStore provider
,D/ResourcesManager( 7310): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,E/SQLiteLog( 7310): (284) automatic index on shooting_modes(title_id)
,W/libprocessgroup(  890): failed to open /acct/uid_10150/pid_5723/cgroup.procs: No such file or directory
,I/ActivityManager(  890): Killing 6565:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2468): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2468): Loading module com.google.android.gms.games from APK com.google.android.gms
,I/ConfigFetchService( 2468): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/ConfigFetchService( 2468): launchTask
,D/ChimeraCfgMgr( 2468): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/ResourcesManager( 2468): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/Vision  ( 2468): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 2468): Failed to find package metadata for com.test.thalitest
,D/Vision  ( 2468): No vision deps
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,V/ConfigFetchTask( 2468): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UJZK0L-Yo0AJIjBr5Co-xBnuPP5IVWaeRhV67L20KdaniknjpdHITqjhRe5Km2vsliasyfkVSCQX3wzmQTzu8wkU1063KNY7z7Zt7IhHC693o16pRtBocUi4gLL5LPbey1A3JgrTYvcJfYd6ok8AhMJ7-AbJNiybFh80aJkCGleLxjIAb4XnzSTL8GMiGZh3SGMhLW50gND9R-mTPB8ElUr203B-sSACQVFI3QJpBB3eaeTsI
,I/PeopleContactsSync( 2468): CP2 sync disabled
,I/GoogleURLConnFactory( 2468): Using platform SSLCertificateSocketFactory
,E/Zygote  ( 7330): MountEmulatedStorage()
E/Zygote  ( 7330): v2
I/libpersona( 7330): KNOX_SDCARD checking this for 10040
I/libpersona( 7330): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7330 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 7330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  890): failed to open /acct/uid_10117/pid_6565/cgroup.procs: No such file or directory
,I/SELinux ( 7330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7330): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7330): TimaSignature is unavailable
,D/ActivityThread( 7330): Added TimaKeyStore provider
,D/ResourcesManager( 7330): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/System.out( 2468): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2468): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2468): (HTTPLog)-Thread-327-79288725: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2468): Tagging socket 91 with tag 40b00000000{1035,0} uid -1, pid: 2468, getuid(): 10012
,I/qtaguid ( 2468): Tagging socket 104 with tag 40b00000000{1035,0} uid -1, pid: 2468, getuid(): 10012
,E/CscFactoryReceiver( 1476): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1476): Media DB Scanner finished.
D/CscFactoryReceiver( 1476): start service to Set Ringtone
,I/ActivityManager(  890): Killing 6697:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/CscFactoryReceiver( 1476): start service to Set Notification
,D/CscFactoryReceiver( 1476): start service to Set Alarmtone
,D/CscUpdateService( 1476): onStart
,E/CscUpdateService( 1476): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1476): only ringtone update
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1476): onStart
,E/CscUpdateService( 1476): costomer file is exists : it has been preconfiged.
,D/CscUpdateService( 1476): only notification update
,D/CscUpdateService( 1476): onStart
E/CscUpdateService( 1476): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1476): only alarmtone update
,E/CscParser( 1476): update(): xml file exist
,E/CscParser( 1476): update(): xml file exist
,E/CscParser( 1476): update(): xml file exist
,E/Zygote  ( 7353): MountEmulatedStorage()
I/libpersona( 7353): KNOX_SDCARD checking this for 10004
E/Zygote  ( 7353): v2
I/libpersona( 7353): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=7353 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/CSCSettings( 1476): Setting Ringtones (type) : 4
,W/CSCSettings( 1476): Setting Ringtones (type) : 1
D/CscParser( 1476): RingTone: null
D/CscParser( 1476): AlarmTone: null
W/CSCSettings( 1476): 1. Tag_Str: null
W/CSCSettings( 1476): 1. Tag_Str: null
,W/CSCSettings( 1476): Setting Ringtones (type) : 2
,D/CscParser( 1476): MessageTone: null
W/CSCSettings( 1476): 1. Tag_Str: null
,I/art     (  310): Explicit concurrent mark sweep GC freed 8750(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 276us total 12.283ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 251us total 7.742ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 7.712ms
,I/SELinux ( 7353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7353): TimaSignature is unavailable
,D/ActivityThread( 7353): Added TimaKeyStore provider
,D/ResourcesManager( 7353): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,W/libprocessgroup(  890): failed to open /acct/uid_10075/pid_6697/cgroup.procs: No such file or directory
,I/qtaguid ( 2468): Untagging socket 91
,I/DCMProvider( 7353): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@3f2ea662 Provider Ref Count:1
,I/ConfigFetchService( 2468): fetch service done; releasing wakelock
,I/ConfigFetchService( 2468): stopping self
,I/DCMConfig( 7353): [#DCM#] initializeTransport.SystemBroadcastReceiver  7 ms
,I/StorageController( 7353): [#DCM#]  state through storage volume =  mounted
,I/StorageController( 7353): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 7353): [#DCM#]  state through storage volume =  unmounted
,I/StorageController( 7353): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
I/StorageController( 7353): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,I/DCMPolicyManager( 7353): [#DCM#] setCriticalStateFromSystem screenOn =  false high siop = false camera running = false
,I/DCMPolicyManager( 7353): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig( 7353): [#DCM#] initializeTransport.DCMPolicyManager  24 ms
,I/DCMConfig( 7353): [#DCM#] initializeTransport.MediaManager  26 ms
,D/AcmsKeyStoreHelper( 7268):  getKeyStoreForApplication Enter
,I/DCMConfig( 7353): [#DCM#] initializeTransport.DCMNRTManager  34 ms
,I/DCMConfig( 7353): [#DCM#] No of CPU Core 4
I/DCMConfig( 7353): [#DCM#] initializeTransport took  35 ms
,I/DCMProvider( 7353): [#DCM#] onCreate end 
,I/SystemBroadcastReceiver( 7353): [#DCM#] [DCM_Performance] onReceive completed in time  14 microsec. 
,I/SystemBroadcastReceiver( 7353): [#DCM#] [DCM_Performance] onReceive completed in time  13 microsec. 
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/DCMNRTManager( 7353): [#DCM#] intialize 
,I/SystemBroadcastReceiver( 7353): [#DCM#] Calling notifyListeners. 
,I/StorageController( 7353): [#DCM#]  state through storage volume =  mounted
,I/StorageController( 7353): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 7353): [#DCM#]  state through storage volume =  unmounted
,I/StorageController( 7353): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
,I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
,I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/StorageController( 7353): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
,E/Zygote  ( 7370): MountEmulatedStorage()
I/ActivityManager(  890): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=7370 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 7370): v2
I/libpersona( 7370): KNOX_SDCARD checking this for 10007
I/libpersona( 7370): KNOX_SDCARD not a persona
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
,I/ActivityManager(  890): Killing 6712:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,I/WriterFactory( 7353): [#DCM#] verifyLuceneDB ++ 
,I/WriterFactory( 7353): [#DCM#] verifyLuceneDB OK breaking 
I/WriterFactory( 7353): [#DCM#] verifyLuceneDB OK -- 
I/WriterFactory( 7353): [#DCM#] TAXO in mode CREATE_OR_APPEND
,I/AcmsKeyStoreHelper( 7268): Key Store exist
,I/AcmsKeyStoreHelper( 7268): Hence loading the keystore file
,I/WriterFactory( 7353): [#DCM#] Before facet 
,I/WriterFactory( 7353): [#DCM#] After facet=!null ? true
I/SELinux ( 7370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/StorageController( 7353): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController( 7353): [#DCM#]  state through storage volume =  removed
I/SELinux ( 7370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/StorageController( 7353): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController( 7353): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
E/SELinux ( 7370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/StorageController( 7353): [#DCM#] Sending intent for OS Upgrade for Phone contents 
,I/DCMUtilities( 7353): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,I/SystemUtils( 7353): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
,I/SystemUtils( 7353): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities( 7353): [#DCM#] OSUpgrade not required 
,I/DCMUtilities( 7353): [#DCM#] isCommitOk; kKeyOnCommit = true
,I/DCMController( 7353): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
I/SystemBroadcastReceiver( 7353): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7353): [#DCM#] onReceive action = EVENT_SIOP
I/SystemBroadcastReceiver( 7353): [#DCM#] Calling notifyListeners. 
I/SystemBroadcastReceiver( 7353): [#DCM#] No one is registered with Event Id EVENT_NETWORK_CHANGED
,D/TimaKeyStoreProvider( 7370): TimaSignature is unavailable
I/DCMConfig( 7353): [#DCM#] setSuccessState =  true
,D/ActivityThread( 7370): Added TimaKeyStore provider
,D/ResourcesManager( 7370): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6712/cgroup.procs: No such file or directory
,I/ThumbnailProvider( 7370): ThumbnailProvider onCreate()
,D/AcmsKeyStoreHelper( 7268):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr( 7268): getKeyStoreForApplication success 
D/AcmsCore( 7268): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7268): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7268): Decrementing - Counter value: 1
D/AcmsCore( 7268): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore( 7268): This is NOT a valid MirrorLink app
D/AcmsCore( 7268): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7268): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7268): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7268): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7268): getSvcCounter - Counter value: 0
D/AcmsService( 7268): Enter onDestroy
I/AcmsService( 7268): cleanUp(): inside service clean up
D/AcmsCore( 7268): AcmsCore: inside DeInit
D/AcmsCore( 7268): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7268): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr( 7268): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7268): KeyStoreHelper: inside cleanup
I/DocumentBroadcastReceiver( 7370): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/AcmsAppEntryInterface( 7268): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7268): getSvcCounter - Counter value: 0
D/AcmsService( 7268): killing acms process
I/Process ( 7268): Sending signal. PID: 7268 SIG: 9
,I/BroadcastProcessorService( 7370): [START] processBroadcastIntent ...
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,I/BroadcastProcessorService( 7370): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,E/Zygote  ( 7389): MountEmulatedStorage()
,E/Zygote  ( 7389): v2
I/libpersona( 7389): KNOX_SDCARD checking this for 10044
I/libpersona( 7389): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=7389 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/SELinux ( 7389): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7389): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7389): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  890): Process ACMS.Process (pid 7268)(adj 0) has died(49,582)
I/SystemInfo( 7370): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 7370): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 7370): [START] DocumentService startDocumentService
,I/DocumentService( 7370): DocumentService onCreate ... service
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7370): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/TimaKeyStoreProvider( 7389): TimaSignature is unavailable
,D/ActivityThread( 7389): Added TimaKeyStore provider
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7370): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,D/ResourcesManager( 7389): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 7389): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 7389): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 7389): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7389): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 7389): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/SystemInfo( 7370): [SIOP LEVEL] : 1
,I/DocumentService( 7370): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7370): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/File    ( 7370): fail readDirectory() errno=13
E/File    ( 7370): fail readDirectory() errno=13
I/DocumentServiceUtils( 7370):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo( 7370): DocumentService [SIOP LEVEL] changed to 1
E/SystemInfo( 7370): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
,I/SystemInfo( 7370): [SYSTEM STATUS] Battery and Storage levels are OK:
,E/SMD     (  284): DCD ON
,I/DocumentService( 7370): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 7370): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :25
E/DocumentService( 7370): [THUMBNAIL] Total Time taken for each file :0
E/        ( 7370): [INDEX] Total time taken for each file :0
,I/DocumentService( 7370): DocumentService onDestroy start
,I/DocumentService( 7370): DocumentService onDestroy end
,I/DocumentService( 7370): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 7370): InterruptedException: null
,I/ActivityManager(  890): Killing 6753:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/SystemInfo( 7370): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 7370): DocumentService cleanupEverything end
,I/Process ( 7370): Sending signal. PID: 7370 SIG: 9
,D/GalleryCacheReady( 6231): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 6231): handleMeidaScanFinish()
,D/FaceInterface( 6231): requestFaceScan() is called.
,E/lowmemorykiller(  246): Error writing /proc/7370/oom_score_adj; errno=22
,W/LocalSuggestAlbumData( 6231): query fail: 
,I/FaceInterface( 6231): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 6231): query fail: 
,I/ActivityManager(  890): Process com.samsung.indexservice (pid 7370)(adj 11) has died(57,582)
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6753/cgroup.procs: No such file or directory
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardViewMediator( 1170): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): doKeyguard: not showing because lockscreen is off
,D/BootupListener( 1476): ACTION_DRIVELINK
,D/SettingsProvider(  890): name = drivelink_navigation
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1001
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,D/BootupListener( 1476): NAVI : com.google.android.apps.maps
D/SettingsProvider(  890): name = internet_call_settings_visibility
D/SettingsProvider(  890): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  890): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  890): selectionArgs: false
D/SettingsProvider(  890): selectionArgs: 1001
D/SecContentProvider(  890): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  890): ret = -1
,I/art     ( 1221): Explicit concurrent mark sweep GC freed 8314(515KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 315us total 19.811ms
,I/MediaStoreImporter( 5988): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  890): Killing 6806:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,W/libprocessgroup(  890): failed to open /acct/uid_10012/pid_6806/cgroup.procs: No such file or directory
,I/GAV2    ( 7067): Thread[GAThread,5,main]: No campaign data found.
,E/SMD     (  284): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  890): SIOP:: AP = 460, PST = 453, CUR = 300
,V/AlarmManager(  890): waitForAlarm result :4
,I/ConfigService( 1680): onDestroy
,D/BatteryService(  890): level:100, scale:100, status:2, health:2, present:true, voltage: 4385, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  890): stay LED for charging
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/FaceInterface( 6231): startFaceScan() : going on
D/FaceInterface( 6231): startFaceScan() is called.
,D/ContentApp( 1221): startScan() is called.
,D/ContentApp( 1221): startScan() is end.
,D/ContentApp( 1221): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1221): isNeedToRestore : start
,I/art     (  890): Explicit concurrent mark sweep GC freed 24359(1550KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 36MB/52MB, paused 3.907ms total 200.314ms
,I/iu.UploadsManager( 2468): End new media; added: 0, uploading: 0, time: 345 ms
,E/SMD     (  284): DCD ON
,D/PackageManager(  890): [MSG] MCS_UNBIND
,I/ActivityManager(  890): Killing 5681:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,W/libprocessgroup(  890): failed to open /acct/uid_10046/pid_5681/cgroup.procs: No such file or directory
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  890): [PWL] Off : 15s ago
,I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2468, ws=null) (elapsedTime=32056)
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,E/Watchdog(  890): !@Sync 2
,I/ActivityManager(  890): Waited long enough for: ServiceRecord{fa30018 u0 com.samsung.android.MtpApplication/.MtpService}
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  890): SIOP:: AP = 400, PST = 450, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6769): [1] 5.onFinished: Scheduling replication attempt 1.
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 890) 
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,E/LightSensor(  890): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  890): turn on LED for fully charged
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  890): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService(  890): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1170
,I/PowerManagerService(  890): !@[ps] Screen__On wl: PowerUI.Notification
I/PowerManagerService(  890): Waking up from sleep (uid 10059)...
,D/PowerManagerService(  890): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  890): [s] UserActivityState : 0 -> 1
V/KeyguardServiceDelegate(  890): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@4d11c9e)
,D/PowerManagerService(  890): [PWL] sb acquire: PowerManagerService.Display
,D/KeyguardViewMediator( 1170): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1170): notifyScreenOnLocked
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,I/DisplayPowerController(  890): Blocking screen on until initial contents have been drawn.
D/LockPatternUtilsCache( 1170): value : false
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SContextService(  890): 	.registerCallback : 1, client=
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  890): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : registerListener mLightSensor
,D/MISC PowerHAL(  890): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  890): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/QCOM PowerHAL(  890): Got set_interactive hint
,W/CAE     (  890): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/AutomaticBrightnessController(  890): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
,I/DisplayManagerService(  890): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,I/CAE     (  890): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,I/CAE     (  890): setCAProperty(ContextAwareService.java:469) - result : true
,W/CAE     (  890): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  890): sendProperty() : service = Auto Rotation
W/CAE     (  890): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
V/CAE     (  890): start(ContextProvider.java:126)
,V/CAE     (  890): clear(AutoRotationRunner.java:182)
,V/CAE     (  890): enable(AutoRotationRunner.java:158)
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -79, 7, 0, 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/PowerManagerService(  890): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 37ms
,E/Sensors (  890): Acc old sensor_state 8704, new sensor_state : 8705 en : 1
D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Sensorhubs(  297): sendContextData: -79, 7, 0, 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SensorManager(  890): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,D/PowerManagerService(  890): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 22ms
,D/CAE     (  890): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  890): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,E/SMD     (  284): DCD ON
,D/CAE     (  890): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  890): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  890): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  890): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@203ac8e, Service : AUTO_ROTATION(1)
W/CAE     (  890): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  890): addSContextService() : service = Auto Rotation
D/SContextService(  890): ===== SContext Service List =====
D/SContextService(  890): Listener : android.hardware.scontext.SContextService$Listener@3df7ecaf, Service : Auto Rotation
D/SContextManager(  890):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3f5837f, service=Auto Rotation
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KeyguardViewMediator( 1170): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1170): onScreenTurnedOn()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,D/InputManager-JNI(  890): setDeviceInteractive: 1
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/UserPresentBroadcastReceiver( 2266): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,D/KnoxNotification( 1170): ----- inflateViews : modified publicViewLocal -----
,D/SamsungIME( 1864): showDlgMsgBox : false true true
I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 80
,D/NfcService( 1470): call the applyRotuiing
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/KnoxNotification( 1170): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1170): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1170): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@27cbbc8b
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 80
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,V/KeyguardServiceDelegate(  890): **** SHOWN CALLED ****
,D/DisplayPowerController(  890): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
I/DisplayPowerController(  890): Unblocked screen on after 260 ms
D/DisplayPowerState(  890): !@ ColorFade exit
,D/StatusBarKeyguardViewManager( 1170): callback.onShown()
D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/SurfaceFlinger(  249): id=14 Removed ColorFade (8/8)
,I/SurfaceFlinger(  249): id=14 Removed ColorFade (-2/8)
E/libEGL  (  890): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/BatteryMeterView( 1170): onDraw batteryColor : -1
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
D/SurfaceControl(  890): Excessive delay in setPowerMode(): 297ms
D/lights  (  890): lcd : 8 +
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/lights  (  890): lcd : 8 -
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  890): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  890): [input device light] setInputDeviceLightOn is called : 1
,D/PowerManagerService(  890): [input device light] handleInputDeviceLightOn
,D/lights  (  890): button : 1 +
D/lights  (  890): button : 1 -
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 80
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 4425): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 4425): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  890): unregisterListener ::   
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/ActivityManager(  890): post active user change for 0
D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 4425): Timeline: Activity_idle id: android.os.BinderProxy@f3bf8f2 time:79891
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,V/ActivityManager(  890): Display changed displayId=0
,V/ActivityManager(  890): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PalmMotion(  890): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotion(  890): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/LightsService(  890): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  890): unregisterListener ::   
,D/lights  (  890): led_pattern : 5 +
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SSRM:a  (  890): DeviceInfo:: 000000000000
,D/SSRM:a  (  890): SettingsAirViewInfo:: 000000000
,D/SLocation(  890): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
W/System.err(  890): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
W/System.err(  890): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
W/System.err(  890): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  890): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  890): 	at com.samsung.location.SLocationService.run(Unknown Source)
W/System.err(  890): 	at java.lang.Thread.run(Thread.java:818)
,D/LightsService(  890): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 890) 
,D/lights  (  890): led_pattern : 5 -
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/BatteryService(  890): turn off LED
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/CAE     (  890): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  890): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,D/LightsService(  890): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/lights  (  890): led_pattern : 0 +
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
D/lights  (  890): led_pattern : 0 -
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/InputMethodManagerService(  890): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  890):  handler : SCREEN_ON end
,D/NotificationService(  890): ACTION_SCREEN_ON
D/LightsService(  890): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  890): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WifiStateMachine(  890): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  890): handleScreenStateChanged Exit: true
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  890): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController(  890): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  890): Bridge Server is not available
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  890): do suspend false
D/PersonaManagerService(  890): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  890): MSG_ACTION_SCREEN_ON called
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/wpa_supplicant( 1269): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1269): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1269): P2P: Current p2p state = IDLE
,I/NfcService( 1470): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,I/wpa_supplicant( 1269): Scan requested (ret=0) - scan timeout 30 seconds
,D/NfcService( 1470): call the applyRotuiing
,I/SamsungIME( 1864): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2138): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2138): [237392/6] SurfaceWidget drawing first frame
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/SystemBroadcastReceiver( 7353): [#DCM#] [DCM_Performance] onReceive completed in time  607 microsec. 
,D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Broadcasts
,I/SystemBroadcastReceiver( 7353): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7353): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 7353): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/SSRM:m  (  890): SIOP:: AP = 400, PST = 447, CUR = 300
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1680): (10) POSIX Error : 11 SQLite Error : 3850
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1368): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1368): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1368): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1368): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 1368): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1454544660000
,D/daemonapp( 1368): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1454523138606
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1368): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1368): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1368): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/SSRM:a  (  890): DeviceInfo:: 000000000000
,D/SSRM:a  (  890): SettingsAirViewInfo:: 000000000
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/PowerManagerService(  890): [input device light] handleInputDeviceLightOff
D/lights  (  890): button : 0 +
,D/lights  (  890): button : 0 -,
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560,
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/wpa_supplicant( 1269): nl80211: Received scan results (3 BSSes)
,D/WifiP2pService(  890): InactiveState{ what=147461 }
,D/WifiP2pService(  890): P2pEnabledState{ what=147461 }
,E/WifiStateMachine(  890): [1,454,523,142,159 ms] noteScanEnd no scan source
,D/WifiP2pService(  890): DefaultState{ what=147461 }
,E/WifiStateMachine(  890): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@160fe2c3 sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  890): External Intent Received android.net.wifi.SCAN_RESULTS
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth,
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560,
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness(),
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,I/PhoneStatusBar( 1170): Icon Only
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8,
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  890): SIOP:: AP = 360, PST = 440, CUR = 300
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8,
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  284): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4,
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,E/Zygote  ( 7492): MountEmulatedStorage()
E/Zygote  ( 7492): v2
I/libpersona( 7492): KNOX_SDCARD checking this for 10082
I/libpersona( 7492): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7492 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/SELinux ( 7492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
E/SELinux ( 7492): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/TimaKeyStoreProvider( 7492): TimaSignature is unavailable
,D/ActivityThread( 7492): Added TimaKeyStore provider
,D/ResourcesManager( 7492): creating new AssetManager and set to /system/app/Books/Books.apk
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/ReaderUtils( 7492): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
,W/GAV2    ( 7492): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7492): Created application version: 3.3.11 (30311)
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 2468): creating new AssetManager and set to /system/app/Books/Books.apk
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7492): Starting books sync, d
,E/SQLiteLog( 7492): (284) automatic index on view_volumes(volume_id)
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/art     ( 1680): Explicit concurrent mark sweep GC freed 25119(1460KB) AllocSpace objects, 6(486KB) LOS objects, 40% free, 17MB/29MB, paused 692us total 36.735ms
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ResourcesManager( 1680): creating new AssetManager and set to /system/app/Books/Books.apk
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/ResourcesManager( 1680): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1680): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1680): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1680): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1680): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7492): null auth token
,D/PanelView( 1170): There is/are notification(s) 
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/PanelView( 1170): There is/are notification(s) 
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,I/System.out( 7492): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 7492): (HTTPLog)-Static: isShipBuild true
I/System.out( 7492): (HTTPLog)-Thread-1242-766173533: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5838): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at kff.l(PG:132)
E/HttpOperation( 5838): 	at dsf.a(PG:807)
E/HttpOperation( 5838): 	at fhk.a(PG:1126)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 8 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 10 more
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5838): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at kff.l(PG:132)
E/HttpOperation( 5838): 	at ieo.a(PG:43)
E/HttpOperation( 5838): 	at iep.a(PG:93)
E/HttpOperation( 5838): 	at fhn.a(PG:59)
E/HttpOperation( 5838): 	at lex.a(PG:85)
E/HttpOperation( 5838): 	at lex.b(PG:132)
E/HttpOperation( 5838): 	at fhk.a(PG:1146)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 12 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 14 more
,E/ExperimentLoader( 5838): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
E/ExperimentLoader( 5838): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5838): 	at kfv.a(PG:65)
E/ExperimentLoader( 5838): 	at kff.u(PG:385)
E/ExperimentLoader( 5838): 	at kfb.a(PG:29)
E/ExperimentLoader( 5838): 	at kff.l(PG:132)
E/ExperimentLoader( 5838): 	at ieo.a(PG:43)
E/ExperimentLoader( 5838): 	at iep.a(PG:93)
E/ExperimentLoader( 5838): 	at fhn.a(PG:59)
E/ExperimentLoader( 5838): 	at lex.a(PG:85)
E/ExperimentLoader( 5838): 	at lex.b(PG:132)
E/ExperimentLoader( 5838): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5838): 	at fhk.a(PG:908)
E/ExperimentLoader( 5838): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5838): 	at ihi.a(PG:22)
E/ExperimentLoader( 5838): 	at kft.a(PG:91)
E/ExperimentLoader( 5838): 	at kfv.a(PG:62)
E/ExperimentLoader( 5838): 	... 12 more
E/ExperimentLoader( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5838): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5838): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5838): 	at ihi.a(PG:19)
E/ExperimentLoader( 5838): 	... 14 more
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/PanelView( 1170): There is/are notification(s) 
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/HttpOperation( 5838): [getaccountstatus] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at ixd.a(PG:248)
E/HttpOperation( 5838): 	at ixd.b(PG:206)
E/HttpOperation( 5838): 	at ixd.a(PG:175)
E/HttpOperation( 5838): 	at fig.a(PG:78)
E/HttpOperation( 5838): 	at lex.a(PG:85)
E/HttpOperation( 5838): 	at lex.b(PG:132)
E/HttpOperation( 5838): 	at fhk.a(PG:1146)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 12 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 14 more
,D/PanelView( 1170): There is/are notification(s) 
E/EsSyncAdapterService( 5838): Sync failure
E/EsSyncAdapterService( 5838): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5838): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5838): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5838): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5838): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5838): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5838): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5838): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5838): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5838): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5838): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5838): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5838): 	... 10 more
E/EsSyncAdapterService( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5838): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5838): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5838): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5838): 	... 12 more
E/EsSyncAdapterService( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5838): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5838): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5838): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5838): 	... 14 more
,D/PanelView( 1170): There is/are notification(s) 
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 66086, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2089327587418009451&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SQLiteLog( 1680): (10) POSIX Error : 11 SQLite Error : 3850
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1680): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1680): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1680): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1680): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2089327587418009451&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8,
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1680): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1680): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1680): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1680): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7492): null auth token
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,V/AlarmManager(  890): waitForAlarm result :4,
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService(  890): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1170 (0x0)
,E/Zygote  ( 7551): MountEmulatedStorage()
I/ActivityManager(  890): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7551 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,E/Zygote  ( 7551): v2
,I/libpersona( 7551): KNOX_SDCARD checking this for 10179
I/libpersona( 7551): KNOX_SDCARD not a persona
,I/SELinux ( 7551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7551): TimaSignature is unavailable
,D/ActivityThread( 7551): Added TimaKeyStore provider
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 7551): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 7551): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,I/art     (  890): Explicit concurrent mark sweep GC freed 47163(2MB) AllocSpace objects, 18(678KB) LOS objects, 30% free, 36MB/52MB, paused 2.775ms total 173.182ms
,D/UMC:Core( 7551): onCreate(): 
,D/USER_AGENT( 7551): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/[SAMSUNG SMARCART NATIVE]( 7551): initialize...
,D/[SAMSUNG SMARCART NATIVE]( 7551): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 7551): ================================================
,I/CSTORAGE( 7551):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 7551): ================================================
I/TZ_CCM_C_GetFunctionList: ( 7551): TZ_CCM_C_GetFunctionList was called
,D/[SAMSUNG SMARCART NATIVE]( 7551): FINISHED: initialize rv:0
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/UMC:SecurityUtils( 7551): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7551): Loaded server certificates: 0
,D/UMC:SecurityUtils( 7551): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 7551): New Flow
,D/TimaService(  890): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  890): TIMA: in getTimaVersion
,I/        (  890): CCM JNI: In ccm_register_for_default_cert
I/        (  890): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  890): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
I/TZ_CCM_C_Initialize: (  890): pInitArgs 0x9d8e4814 has not called C_Init before.
I/TZ_CCM_C_Initialize: (  890): &ctx = 0x9ffb2c1c
I/TLC_TZ_CCM: (  890): creating new ccm context...
I/TLC_TZ_CCM: (  890): initializing ccm context...
I/TLC_TZ_CCM: (  890): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  890): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  890): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  890): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  890): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  890): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  890): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  890): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  890): Client_Server_Open was called
I/TZ: client_server_communication(  890): IClientServer::IClientServer()
I/TZ: client_server_communication(  890): BpClientServer::BpClientServer()
I/TZ: client_server_communication(  890): IClientServer::~IClientServer()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1077): OPENSWCONN
I/TZ_CCM_SERVER( 1077): creating new ccm context...
I/TZ_CCM_SERVER( 1077): initializing ccm context...
I/TZ_CCM_SERVER( 1077): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1077): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1077): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1077): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1077): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1077): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1077): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1077): QSEECom_get_handle sb_length = 0x9800
D/QSEECOMAPI: ( 1077): App is not loaded in QSEE
,D/QSEECOMAPI: ( 1077): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication( 1077): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,I/TZ: client_server_communication(  890): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  890): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  890): ctx = 0x6e483860, comm = 0x8e42be50, sendmsg = 0x94824000, recvmsg = 0x94828c00
I/TZ_init: (  890): TZ_init: sending initialization request...
I/TZ: client_server_communication(  890): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/TZ_init: (  890): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  890): Exercising TZ_DB_INIT in TLC
,I/TZ: client_server_communication(  890): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
,I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/GAV2    ( 7492): Thread[GAThread,5,main]: No campaign data found.
,I/TZ_COMMON: tlc_key_db_util: (  890): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  890): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  890): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
,I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/TLC_TZ_CCM: register for default cert: (  890): TZ_CCM_register_default_TLC_END: DB file size to update is 0
,I/TLC_TZ_CCM: register for default cert: (  890): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  890): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  890): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  890): Calling Communicate()
,I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1077): COMM
,I/TZ: client_server_communication(  890): Client_Server_Close was called
I/TZ_CCM_SERVER( 1077): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1077): CLOSESWCONN
D/QSEECOMAPI: ( 1077): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1077): QSEECom_shutdown_app, app_id = 2
,I/TZ: client_server_communication(  890): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 7551): ccmRegisterForDefaultCertificate: 0
,D/UMC:CloudMDMSecurity( 7551): TIMA service call for password change success!!
,D/UMC:AdminManager( 7551): init - start
,D/UMC:AdminManager( 7551): loadAdmins
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/UMC:AdminManager( 7551): startPolicyHandlers
I/UMC:TestPolicyHandler( 7551): Setup is called in testpolicyhandler
,D/UMC:AdminManager( 7551): init - end
,V/UMC:AlarmHandler( 7551): Enter loadList
,D/GSLBManager( 7551): migrateStoredUrlFromOldPref
,D/GSLBManager( 7551): migrateStoredUrlFromOldPref : Migration Not Needed
,D/UMC:UMCAdmin( 7551): deactivateUMCAdminIfNotRequired : -1
,E/UMC:Utils( 7551): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 7551): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 7551): isContainer : 0
,W/LicenseLogService(  890): log() failed
,D/EnterpriseDeviceManagerService(  890): isManagedProfileUser(): userId = 0
,E/UMC:UMCAdmin( 7551): No active admin owned by uid 10179
D/UMC:UMCAdmin( 7551): isContainer : 0
,D/UMC:UMCAdmin( 7551): deactivateUMCAdmin - UMC App Admin deactivated
,V/UMC:AlarmHandler( 7551): onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,D/QuickStartReceiver( 7551): Msg Id : 2
,D/QuickStartReceiver( 7551): model : SM-G900F
D/QuickStartReceiver( 7551): id : 100
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/Finsky  ( 6769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6769): [1] 5.onFinished: Scheduling replication attempt 2.
,I/ActivityManager(  890): Killing 6059:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6059/cgroup.procs: No such file or directory
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  890): SIOP:: AP = 350, PST = 432, CUR = 300
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2089327587418009451&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/BooksSync( 7492): Soft error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2089327587418009451&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7492): Sync error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2089327587418009451&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7492): Finished books sync
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 69070, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/ActivityManager(  890): Killing 6896:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,W/libprocessgroup(  890): failed to open /acct/uid_1000/pid_6896/cgroup.procs: No such file or directory
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  890): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  (  890): lcd : 1 +
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/lights  (  890): lcd : 1 -
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/Watchdog(  890): !@Sync 3
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/SMD     (  284): DCD ON
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1,
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  890): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  890): CMD_RSSI_POLL : out!
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560,
D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
,I/Atfwd_Daemon(  324): result : -1 ,	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
,D/DisplayPowerController(  890): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  890): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  890): Nap time (uid 1000)...
I/PowerManagerService(  890): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  890): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI(  890): setDeviceInteractive: 0
,D/PowerManagerService(  890): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService(  890): SecHardwareInterface.setBatteryADC : false
,D/PowerManagerService(  890): handleSandman : startDream()
,E/PowerManagerService(  890): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService(  890): Sleeping (uid 1000)...
,D/PowerManagerService(  890): [s] UserActivityState : 4 -> 0
D/PowerManagerService(  890): [input device light] setInputDeviceLightOn is called : 0
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/PowerManagerService(  890): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger(  249): id=15 createSurf (1080x1920),2 flag=404, ColorFade
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  890): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  890): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService(  890): 	.unregisterCallback : 1, client=
D/SContextService(  890): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3df7ecaf, Service = Auto Rotation, used = 1
,W/CAE     (  890): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  890): stop(ContextProvider.java:149)
,V/CAE     (  890): clear(AutoRotationRunner.java:182)
,V/CAE     (  890): disable(AutoRotationRunner.java:171)
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  890): SendSensorHubData: send data = -78, 7, 0, 0
D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  890): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  890): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,E/SMD     (  284): DCD ON
,D/CAE     (  890): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  890): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  890): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  890): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  890): removeSContextService() : service = Auto Rotation
D/SContextService(  890): ===== SContext Service List =====
D/SContextManager(  890):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@3f5837f, service=Auto Rotation
D/KeyguardViewMediator( 1170): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 1170): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1170): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1170): notifyScreenOffLocked
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): timeout : 5000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KeyguardViewMediator( 1170): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 1170): handleNotifyScreenOff
,I/SQLiteSecureOpenHelper( 3254): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3254): getDatabaseLocked(b,b,pwd)...
,D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
,D/DisplayPowerController(  890): ColorFade: onAnimationStart
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService(  890): turn on LED for fully charged
,D/SensorManager(  890): unregisterListener ::   
D/lights  (  890): led_pattern : 5 +
,D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,D/lights  (  890): led_pattern : 5 -
D/lights  (  890): lcd : 0 +
,D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,I/CAE     (  890): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  890): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  890): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,D/lights  (  890): lcd : 0 -
,I/CAE     (  890): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 18, 12, 47,
,D/SensorHubManager(  890): SendSensorHubData: send data = -63, 14, 18, 12, 47
D/Sensorhubs(  297): sendContextData: -63, 14, 18, 12, 47
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  890):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  890): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  890): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  890): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  890): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/native  (  890): do suspend true
,D/NotificationService(  890): ACTION_SCREEN_OFF
D/LightsService(  890): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 890) 
D/LightsService(  890): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,D/LightsService(  890): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  890): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  890): unregisterListener ::   
D/LightsService(  890): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
,V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  890): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  890): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  890): Bridge Server is not available
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1170): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1170): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1170): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/PersonaManagerService(  890): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  890): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 1470): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1170):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1170): onReceive : Intent.ACTION_SCREEN_OFF
D/Recents_AlternateRecentsComponent( 1170): dismissHelpPopup 
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2138): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2138): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,E/LightSensor(  890): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=0, bp1=0, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  890): mCallbacks.updateBrightness()
D/DisplayPowerController(  890): getFinalBrightness : 8 -> 0
,D/DisplayPowerState(  890): !@ ColorFade entry
,D/DisplayPowerController(  890): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController(  890): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/AutomaticBrightnessController(  890): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  890): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,D/SensorManager(  890): unregisterListener ::   
E/Sensors (  890): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SensorManager(  890): unregisterListener ::   
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
I/DisplayManagerService(  890): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,V/ActivityManager(  890): Display changed displayId=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  890): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/SSRM:m  (  890): SIOP:: AP = 330, PST = 422, CUR = 300
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/X       (  890): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1170): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/ContentApp( 1221):  LEVEL : 0
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/SystemBroadcastReceiver( 7353): [#DCM#] [DCM_Performance] onReceive completed in time  3295 microsec. 
,I/SystemBroadcastReceiver( 7353): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 7353): [#DCM#] onReceive action = EVENT_SIOP
,E/TranscodeReceiver( 6414): onReceive : android.intent.action.CHECK_SIOP_LEVEL
D/TranscodeReceiver( 6414):  SIOP_LEVEL: 0
,I/SystemBroadcastReceiver( 7353): [#DCM#] [DCM_Performance] onReceive completed in time  99 microsec. 
I/SystemBroadcastReceiver( 7353): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7353): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController( 7353): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6c01090
,I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  270): wakelock acquired: 1, error no: 42
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1228406656)
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1228406656) wakelock released: 1, error no: 22
I/rmt_storage(  270): 
,I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6c01090
,D/PackageManager(  890): [MSG] SEND_PENDING_BROADCAST
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  890): Excessive delay in setPowerMode(): 257ms
,D/PowerManagerService(  890): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL(  890): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  890): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/ResourcesManager(  890): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/QCOM PowerHAL(  890): Got set_interactive hint
,I/PowerManagerService(  890): [PWL] Off : 0s ago
,I/PowerManagerService(  890): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  890): [PWL]     mDisplayReady : false
D/DisplayPowerController(  890): getFinalBrightness : 0 -> 0
,D/PowerManagerService(  890): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  890): [PWL] sb release: PowerManagerService.Display
D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/InputReader(  890): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/RegisteredServicesCache( 1470): empty dynamic service
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Drive/Drive.apk
,I/UpdateIcingCorporaServi( 1556): Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Music2/Music2.apk
,E/Zygote  ( 7603): MountEmulatedStorage()
E/Zygote  ( 7603): v2
I/libpersona( 7603): KNOX_SDCARD checking this for 10075
I/libpersona( 7603): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7603 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/SELinux ( 7603): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7603): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7603): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BackupManagerService(  890): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/TimaKeyStoreProvider( 7603): TimaSignature is unavailable
,D/ActivityThread( 7603): Added TimaKeyStore provider
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/UpdateIcingCorporaServi( 1556): UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7603): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/FileShare-Server( 7603): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  890): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  890): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  890): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,E/Zygote  ( 7618): MountEmulatedStorage()
E/Zygote  ( 7618): v2
I/libpersona( 7618): KNOX_SDCARD checking this for 1000
I/libpersona( 7618): KNOX_SDCARD not a persona
,I/ActivityManager(  890): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7618 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6079:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,I/SELinux ( 7618): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7618): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7618): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/TimaKeyStoreProvider( 7618): TimaSignature is unavailable
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ActivityThread( 7618): Added TimaKeyStore provider
,W/libprocessgroup(  890): failed to open /acct/uid_10158/pid_6079/cgroup.procs: No such file or directory
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager(  890): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  890): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 7618): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 7618): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  890): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 7633): MountEmulatedStorage()
E/Zygote  ( 7633): v2
I/libpersona( 7633): KNOX_SDCARD checking this for 1000
I/libpersona( 7633): KNOX_SDCARD not a persona
,W/ResourcesManager( 6673): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/ActivityManager(  890): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=7633 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  890): Killing 6430:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,I/SELinux ( 7633): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7633): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7633): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/TimaKeyStoreProvider( 7633): TimaSignature is unavailable
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ActivityThread( 7633): Added TimaKeyStore provider
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,D/ResourcesManager( 7633): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup(  890): failed to open /acct/uid_10168/pid_6430/cgroup.procs: No such file or directory
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ShortcutReceiver( 7633):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6673): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 6673): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 6673): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6673): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager(  890): Killing 6938:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2468): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,I/PeopleContactsSync( 2468): CP2 sync disabled
,W/libprocessgroup(  890): failed to open /acct/uid_10015/pid_6938/cgroup.procs: No such file or directory
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardViewMediator( 1170): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1170): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/KeyguardViewMediator( 1170): doKeyguard: not showing because lockscreen is off
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  890): [PWL] Off : 5s ago
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/FactoryTest( 6873): Not factory mode
,D/FactoryTest( 6873): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6873): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6873): still no open session command from host, so toast
,W/ContextImpl( 6873): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6873): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
,I/Timeline( 6873): Timeline: Activity_launch_request id:com.android.settings time:119311
,E/PersonaManagerService(  890): inState():  stateMachine is null !!
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  890): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,W/ActivityManager(  890): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/MTPRx   ( 6873): started activity for popup
,I/SQLiteSecureOpenHelper( 3254): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 3254): getDatabaseLocked(b,b,pwd)...
,D/ResourcesManager( 6873): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6873): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6873): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 6873): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager( 6873): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6873): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6873): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6873): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/SettingsReceiverActivity( 6873): PREF_DONT_ASK_AGAIN : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  890): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService(  890): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3f06a4bf attribute=android.view.inputmethod.EditorInfo@6c0878c, token = android.os.BinderProxy@2e6e9759
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6873): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6873): dev.kiessupport is : TRUE
,D/Activity( 6873): performCreate Call secproduct feature valuefalse
,D/Activity( 6873): performCreate Call debug elastic valuetrue
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 80
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 80
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 80
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 4425): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 4425): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 4425): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager(  890): post active user change for 0
,D/KnoxTimeoutHandler(  890): postActiveUserChange for user 0
,D/KnoxTimeoutHandler(  890): handleActiveUserChange for user 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 4425): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,I/Timeline( 4425): Timeline: Activity_idle id: android.os.BinderProxy@f3bf8f2 time:119887
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SSRM:m  (  890): SIOP:: AP = 330, PST = 408, CUR = 300
,D/X       (  890): broadcastSiopLevelIntent:: currentSiopLevel = -1
,E/TranscodeReceiver( 6414): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 6414):  SIOP_LEVEL: -1
,D/ContentApp( 1221):  LEVEL : -1
,I/SystemBroadcastReceiver( 7353): [#DCM#] [DCM_Performance] onReceive completed in time  8624 microsec. 
,I/SystemBroadcastReceiver( 7353): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 7353): [#DCM#] onReceive action = EVENT_SIOP
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6769): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  284): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,W/ActivityManager(  890): mDVFSHelper.release()
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/TaskPersister(  890): removeObsoleteFile: deleting file=17_task.xml
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PowerManagerService(  890): [PWL] Off : 15s ago
,W/ProcessCpuTracker(  890): Skipping unknown process pid 7682
,W/ProcessCpuTracker(  890): Skipping unknown process pid 7683
,W/ProcessCpuTracker(  890): Skipping unknown process pid 7692
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,D/SSRM:m  (  890): SIOP:: AP = 320, PST = 392, CUR = 300
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  284): DCD ON
,E/Watchdog(  890): !@Sync 4
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...,
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 375, CUR = 300
,I/PowerManagerService(  890): [PWL] Off : 30s ago
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6769): [1] 5.onFinished: Scheduling replication attempt 4.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 310, PST = 357, CUR = 300
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/HttpOperation( 5838): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at kff.l(PG:132)
E/HttpOperation( 5838): 	at dsf.a(PG:807)
E/HttpOperation( 5838): 	at fhk.a(PG:1126)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 8 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 10 more
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5838): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at kff.l(PG:132)
E/HttpOperation( 5838): 	at ieo.a(PG:43)
E/HttpOperation( 5838): 	at iep.a(PG:93)
E/HttpOperation( 5838): 	at fhn.a(PG:59)
E/HttpOperation( 5838): 	at lex.a(PG:85)
E/HttpOperation( 5838): 	at lex.b(PG:132)
E/HttpOperation( 5838): 	at fhk.a(PG:1146)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 12 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 14 more
,E/ExperimentLoader( 5838): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5838): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5838): 	at kfv.a(PG:65)
E/ExperimentLoader( 5838): 	at kff.u(PG:385)
E/ExperimentLoader( 5838): 	at kfb.a(PG:29)
E/ExperimentLoader( 5838): 	at kff.l(PG:132)
E/ExperimentLoader( 5838): 	at ieo.a(PG:43)
E/ExperimentLoader( 5838): 	at iep.a(PG:93)
E/ExperimentLoader( 5838): 	at fhn.a(PG:59)
E/ExperimentLoader( 5838): 	at lex.a(PG:85)
E/ExperimentLoader( 5838): 	at lex.b(PG:132)
E/ExperimentLoader( 5838): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5838): 	at fhk.a(PG:908)
E/ExperimentLoader( 5838): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5838): 	at ihi.a(PG:22)
E/ExperimentLoader( 5838): 	at kft.a(PG:91)
E/ExperimentLoader( 5838): 	at kfv.a(PG:62)
E/ExperimentLoader( 5838): 	... 12 more
E/ExperimentLoader( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5838): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5838): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5838): 	at ihi.a(PG:19)
E/ExperimentLoader( 5838): 	... 14 more
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
E/HttpOperation( 5838): [getaccountstatus] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at ixd.a(PG:248)
E/HttpOperation( 5838): 	at ixd.b(PG:206)
E/HttpOperation( 5838): 	at ixd.a(PG:175)
E/HttpOperation( 5838): 	at fig.a(PG:78)
E/HttpOperation( 5838): 	at lex.a(PG:85)
E/HttpOperation( 5838): 	at lex.b(PG:132)
E/HttpOperation( 5838): 	at fhk.a(PG:1146)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 12 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 14 more
E/EsSyncAdapterService( 5838): Sync failure
E/EsSyncAdapterService( 5838): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5838): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5838): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5838): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5838): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5838): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5838): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5838): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5838): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5838): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5838): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5838): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5838): 	... 10 more
E/EsSyncAdapterService( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5838): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5838): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5838): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5838): 	... 12 more
E/EsSyncAdapterService( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5838): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5838): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5838): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5838): 	... 14 more
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 159533, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  890): mCursor = null
,I/PowerManagerService(  890): [PWL] Off : 50s ago
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 341, CUR = 300
,E/SQLiteLog( 1680): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/AlarmManager(  890): waitForAlarm result :4
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6769): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6769): [1] 5.onFinished: Scheduling replication attempt 5.
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/Watchdog(  890): !@Sync 5
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 331, CUR = 300
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 321, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,I/art     (  890): Explicit concurrent mark sweep GC freed 73740(4MB) AllocSpace objects, 36(771KB) LOS objects, 30% free, 36MB/52MB, paused 2.417ms total 217.810ms
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1680): Vacuum at: now=1454523240900 tag=VacuumService
,I/GoogleURLConnFactory( 1680): Using platform SSLCertificateSocketFactory
,W/Uploader( 1680): No account for auth token provided
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/System.out( 1680): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1680): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1680): (HTTPLog)-Thread-203-997708509: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 1680): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1680, getuid(): 10012
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 1680): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1680, getuid(): 10012
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6769): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6769): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6769): [1] 5.onFinished: Giving up after 6 failures.
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  890): [PWL] Off : 75s ago
I/PowerManagerService(  890): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  890): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  890): [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10012, pid=1680, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=2592)
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/art     ( 1680): Explicit concurrent mark sweep GC freed 58299(3MB) AllocSpace objects, 25(1915KB) LOS objects, 40% free, 18MB/30MB, paused 711us total 60.265ms
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/Uploader( 1680): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1680): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1680): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1680): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1680): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1680): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1680): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1680): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1680): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1680): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1680): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1680): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1680): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/qtaguid ( 1680): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1680, getuid(): 10012
,W/Uploader( 1680): No account for auth token provided
,I/qtaguid ( 1680): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1680, getuid(): 10012
,W/Uploader( 1680): No account for auth token provided
,I/qtaguid ( 1680): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1680, getuid(): 10012
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Uploader( 1680): No account for auth token provided
,I/qtaguid ( 1680): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1680, getuid(): 10012
,W/Uploader( 1680):  no longer exists, so no auth token.
,I/qtaguid ( 1680): Tagging socket 57 with tag 120100000000{4609,0} uid -1, pid: 1680, getuid(): 10012
,E/SQLiteLog( 1680): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7492): Starting books sync, d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1680): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1680): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1680): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1680): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1680): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5154010611219337158&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 315, CUR = 300,
,E/SMD     (  284): DCD ON
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,W/GLSActivity( 1680): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1680): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1680): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1680): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5154010611219337158&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  890): stay LED for fully charged
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/GLSActivity( 1680): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1680): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1680): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1680): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1680): 	at android.os.Binder.execTransact(Binder.java:446)
,I/PhoneStatusBar( 1170): Icon Only
,E/BooksAccountManager( 7492): Authentication error
E/BooksAccountManager( 7492): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7492): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,E/HttpHelper( 7492): null auth token
,I/qtaguid ( 7492): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7492, getuid(): 10082
,I/qtaguid ( 7492): Untagging socket 34
,W/ApiaryClient( 7492): Error response from books API: {
W/ApiaryClient( 7492):  "error": {
W/ApiaryClient( 7492):   "errors": [
W/ApiaryClient( 7492):    {
W/ApiaryClient( 7492):     "domain": "global",
W/ApiaryClient( 7492):     "reason": "required",
W/ApiaryClient( 7492):     "message": "Login Required",
W/ApiaryClient( 7492):     "locationType": "header",
W/ApiaryClient( 7492):     "location": "Authorization"
W/ApiaryClient( 7492):    }
W/ApiaryClient( 7492):   ],
W/ApiaryClient( 7492):   "code": 401,
W/ApiaryClient( 7492):   "message": "Login Required"
W/ApiaryClient( 7492):  }
W/ApiaryClient( 7492): }
,W/ApiaryClient( 7492): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5154010611219337158&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7492): Headers suppressed
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/BooksSync( 7492): Soft error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5154010611219337158&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7492): Sync error
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7492): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5154010611219337158&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7492): Headers suppressed
E/BooksSync( 7492): 
E/BooksSync( 7492): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7492): Finished books sync
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 166335, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Watchdog(  890): !@Sync 6
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 310, CUR = 300
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 300, PST = 307, CUR = 300
,E/SMD     (  284): DCD ON
,I/Atfwd_Sendcmd(  324): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  324): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 105s ago
,E/SMD     (  284): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager(  890): waitForAlarm result :4
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 303, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/Watchdog(  890): !@Sync 7
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 300, CUR = 300
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 2
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/PowerManagerService(  890): [PWL] Off : 140s ago
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 296, CUR = 300
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 3
,E/Watchdog(  890): !@Sync 8
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
,I/MotionRecognitionService(  890): setPowerConnected  = true
,D/BatteryService(  890): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 295, CUR = 300
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 294, CUR = 300
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 293, CUR = 300
,E/Watchdog(  890): !@Sync 9
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON
,V/AlarmManager(  890): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
,D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
,D/BatteryService(  890): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  890): online:4, current avg:300, charge type:1, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  890): stay LED for fully charged
D/BatteryService(  890): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  890):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  890): Plugged
I/MotionRecognitionService(  890): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3872): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3872): Disconnected process message: 10
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1680): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
D/SecContentProvider2(  890): mCursor = null
,D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5838): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at kff.l(PG:132)
E/HttpOperation( 5838): 	at dsf.a(PG:807)
E/HttpOperation( 5838): 	at fhk.a(PG:1126)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 8 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 10 more
,I/PhoneStatusBar( 1170): Icon Only
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5838): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at kff.l(PG:132)
E/HttpOperation( 5838): 	at ieo.a(PG:43)
E/HttpOperation( 5838): 	at iep.a(PG:93)
E/HttpOperation( 5838): 	at fhn.a(PG:59)
E/HttpOperation( 5838): 	at lex.a(PG:85)
E/HttpOperation( 5838): 	at lex.b(PG:132)
E/HttpOperation( 5838): 	at fhk.a(PG:1146)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 12 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 14 more
,E/ExperimentLoader( 5838): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5838): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5838): 	at kfv.a(PG:65)
E/ExperimentLoader( 5838): 	at kff.u(PG:385)
E/ExperimentLoader( 5838): 	at kfb.a(PG:29)
E/ExperimentLoader( 5838): 	at kff.l(PG:132)
E/ExperimentLoader( 5838): 	at ieo.a(PG:43)
E/ExperimentLoader( 5838): 	at iep.a(PG:93)
E/ExperimentLoader( 5838): 	at fhn.a(PG:59)
E/ExperimentLoader( 5838): 	at lex.a(PG:85)
E/ExperimentLoader( 5838): 	at lex.b(PG:132)
E/ExperimentLoader( 5838): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5838): 	at fhk.a(PG:908)
E/ExperimentLoader( 5838): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5838): 	at ihi.a(PG:22)
E/ExperimentLoader( 5838): 	at kft.a(PG:91)
E/ExperimentLoader( 5838): 	at kfv.a(PG:62)
E/ExperimentLoader( 5838): 	... 12 more
E/ExperimentLoader( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5838): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5838): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5838): 	at ihi.a(PG:19)
E/ExperimentLoader( 5838): 	... 14 more
,E/SQLiteLog( 1680): (10) POSIX Error : 11 SQLite Error : 3850
I/GLSUser ( 1680): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1680): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1680): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1680): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1680): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1680): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  890): uri = 14 selection = getSealedState
,D/SecContentProvider2(  890): mCursor = null
D/SecContentProvider2(  890): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  890): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  890): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1170): Icon Only
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,E/HttpOperation( 5838): [getaccountstatus] Unexpected exception
E/HttpOperation( 5838): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5838): 	at kfv.a(PG:65)
E/HttpOperation( 5838): 	at kff.u(PG:385)
E/HttpOperation( 5838): 	at kfb.a(PG:29)
E/HttpOperation( 5838): 	at ixd.a(PG:248)
E/HttpOperation( 5838): 	at ixd.b(PG:206)
E/HttpOperation( 5838): 	at ixd.a(PG:175)
E/HttpOperation( 5838): 	at fig.a(PG:78)
E/HttpOperation( 5838): 	at lex.a(PG:85)
E/HttpOperation( 5838): 	at lex.b(PG:132)
E/HttpOperation( 5838): 	at fhk.a(PG:1146)
E/HttpOperation( 5838): 	at fhk.a(PG:908)
E/HttpOperation( 5838): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5838): 	at ihi.a(PG:22)
E/HttpOperation( 5838): 	at kft.a(PG:91)
E/HttpOperation( 5838): 	at kfv.a(PG:62)
E/HttpOperation( 5838): 	... 12 more
E/HttpOperation( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5838): 	at gde.c(Unknown Source)
E/HttpOperation( 5838): 	at gde.b(Unknown Source)
E/HttpOperation( 5838): 	at ihi.a(PG:19)
E/HttpOperation( 5838): 	... 14 more
,E/EsSyncAdapterService( 5838): Sync failure
E/EsSyncAdapterService( 5838): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5838): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5838): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5838): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5838): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5838): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5838): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5838): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5838): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5838): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5838): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5838): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5838): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5838): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5838): 	... 10 more
E/EsSyncAdapterService( 5838): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5838): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5838): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5838): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5838): 	... 12 more
E/EsSyncAdapterService( 5838): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5838): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5838): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5838): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5838): 	... 14 more
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  890): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 286819, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  890): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  890): mCursor = null
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 1680): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  284): DCD ON
,I/PowerManagerService(  890): [PWL] Off : 180s ago
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 292, CUR = 300
,D/ConnectivityService(  890): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,E/SMD     (  284): DCD ON
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,I/ServiceManager(  324): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  324): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  890): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  284): DCD ON
,D/SSRM:m  (  890): SIOP:: AP = 290, PST = 291, CUR = 300
,E/SMD     (  284): DCD ON
,V/AlarmManager(  890): waitForAlarm result :8
,E/SMD     (  284): DCD ON
,E/SMD     (  284): DCD ON

```
