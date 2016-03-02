#### Test 613623661dfc74c_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
I/SL_DEBUG( 6209): isLoggable:: isProductShip = 1
I/SL_DEBUG( 6209): isLoggable:: SL_DEBUG_EXIST = false
I/SELinux ( 6253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/StorageController( 6102): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController( 6102): [#DCM#]  state through storage volume =  unmounted
I/SELinux ( 6253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/StorageController( 6102): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
E/SELinux ( 6253): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController( 6102): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController( 6102): [#DCM#] getSDCardSubSystemEntry Rebooted ?
I/StorageController( 6102): [#DCM#] Sending intent for OS Upgrade for Phone contents 
I/DCMUtilities( 6102): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
--------- beginning of system
W/libprocessgroup(  886): failed to open /acct/uid_10082/pid_4086/cgroup.procs: No such file or directory
W/libprocessgroup(  886): failed to open /acct/uid_10109/pid_5097/cgroup.procs: No such file or directory
D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/SystemUtils( 6102): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
I/SystemUtils( 6102): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities( 6102): [#DCM#] OSUpgrade not required 
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/TimaKeyStoreProvider( 6253): TimaSignature is unavailable
D/ActivityThread( 6253): Added TimaKeyStore provider
I/SLinkClient( 6165): queryDevices : cursor.getCount() = [ 0 ]
D/SLinkClient( 6165): onStorageUpdated(), uri = [ slink://slink ]
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/ResourcesManager( 6253): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
I/SLinkClient( 6165): SlinkBackgroundJob: slink wake up ok!
W/libprocessgroup(  886): failed to open /acct/uid_10112/pid_5083/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
W/ContextImpl( 6209): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6209): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
I/ThumbnailProvider( 6253): ThumbnailProvider onCreate()
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
V/Transcoder( 6209): Transcoder(0xaefcf830)::constructor
V/Transcoder( 6209): addObitRecipient
V/TMI-JNI ( 6209): Mobile Transcoder JNI version 1.6.0/20131120/4.4
I/DocumentBroadcastReceiver( 6253): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
I/BroadcastProcessorService( 6253): [START] processBroadcastIntent ...
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/GalleryCacheReady( 6165): Receive action.ACTION_MEDIA_SCANNER_FINISHED
D/GalleryCacheReady( 6165): handleMeidaScanFinish()
D/FaceInterface( 6165): requestFaceScan() is called.
W/LocalSuggestAlbumData( 6165): query fail: 
W/LocalSuggestAlbumData( 6165): query fail: 
I/FaceInterface( 6165): startFaceScan() : waiting 5 sec
I/BroadcastProcessorService( 6253): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
I/SystemInfo( 6253): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 6253): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
I/BroadcastProcessorService( 6253): [START] DocumentService startDocumentService
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
I/DocumentService( 6253): DocumentService onCreate ... service
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6253): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6253): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
E/SystemInfo( 6253): [SIOP LEVEL] : 0
D/CustomFrequencyManagerService(  886): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 886  tag : ACTIVITY_RESUME_BOOSTER@6
W/ActivityManager(  886): mDVFSHelper.release()
I/Timeline(  886): Timeline: Activity_windows_visible id: ActivityRecord{10eef530 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t27} time:50294
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/CustomFrequencyManagerService(  886): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 886  pkgName : ACTIVITY_RESUME_BOOSTER@10
D/Launcher.HomeView( 1487): onStop
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/Launcher( 1487): onTrimMemory. Level: 20
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2014): [237392/6] Surface widget pause on instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2014): [237392/6] Surface widget visibility changed visibility = false on instance = 1
D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/DocumentService( 6253): [BEGIN SYNC] DocumentService beginIndexing :16
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6253): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/accuweather( 2014): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/accuweather( 2014): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2014): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
D/GalleryCacheReady( 6165): Receive : home resume
D/accuweather( 2014): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2014): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/Mms/UIEventReceiver( 6049): ui event
E/File    ( 6253): fail readDirectory() errno=13
E/File    ( 6253): fail readDirectory() errno=13
I/SystemInfo( 6253): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 6253): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 6253): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :48
E/DocumentService( 6253): [THUMBNAIL] Total Time taken for each file :0
E/        ( 6253): [INDEX] Total time taken for each file :0
W/BroadcastQueue(  886): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1487, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6290): MountEmulatedStorage()
E/Zygote  ( 6290): v2
I/libpersona( 6290): KNOX_SDCARD checking this for 10094
I/libpersona( 6290): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6290 uid=10094 gids={50094, 9997} abi=armeabi-v7a
I/SELinux ( 6290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/DocumentService( 6253): DocumentService onDestroy start
E/SELinux ( 6290): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/DocumentService( 6253): DocumentService onDestroy end
I/DocumentService( 6253): DocumentService cleanupEverything start
I/IndexParserThreadsManager( 6253): InterruptedException: null
I/SystemInfo( 6253): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 6253): DocumentService cleanupEverything end
I/Process ( 6253): Sending signal. PID: 6253 SIG: 9
D/TimaKeyStoreProvider( 6290): TimaSignature is unavailable
D/ActivityThread( 6290): Added TimaKeyStore provider
I/ActivityManager(  886): Process com.samsung.indexservice (pid 6253)(adj 11) has died(64,603)
D/ResourcesManager( 6290): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
W/ResourcesManager( 6290): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6306): MountEmulatedStorage()
E/Zygote  ( 6306): v2
I/libpersona( 6306): KNOX_SDCARD checking this for 10103
I/libpersona( 6306): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6306 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 6306): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6306): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/MediaStoreImporter( 5939): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
E/SELinux ( 6306): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
I/ActivityManager(  886): Killing 5113:com.blurb.checkout/u0a81 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 6306): TimaSignature is unavailable
D/ActivityThread( 6306): Added TimaKeyStore provider
D/ResourcesManager( 6306): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
W/ResourcesManager( 6306): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6306): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
W/libprocessgroup(  886): failed to open /acct/uid_10081/pid_5113/cgroup.procs: No such file or directory
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
D/CustomFrequencyManagerService(  886): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 886  tag : ACTIVITY_RESUME_BOOSTER@10
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
V/TaskCloserActivity( 6015): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
I/ActivityManager(  886): Killing 5145:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/BootupListener( 1478): ACTION_DRIVELINK
D/SettingsProvider(  886): name = drivelink_navigation
D/SettingsProvider(  886): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  886): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  886): selectionArgs: false
D/SettingsProvider(  886): selectionArgs: 1001
D/SecContentProvider(  886): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  886): ret = -1
D/BootupListener( 1478): NAVI : com.google.android.apps.maps
D/SettingsProvider(  886): name = internet_call_settings_visibility
D/SettingsProvider(  886): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  886): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  886): selectionArgs: false
D/SettingsProvider(  886): selectionArgs: 1001
D/SecContentProvider(  886): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  886): ret = -1
I/SettingSearchManagerReceiver( 1478): onReceive : android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
I/SettingSearchManagerReceiver( 1478): addSearchInfoDB
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6324): MountEmulatedStorage()
E/Zygote  ( 6324): v2
I/libpersona( 6324): KNOX_SDCARD checking this for 10168
I/libpersona( 6324): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=6324 uid=10168 gids={50168, 9997} abi=armeabi-v7a
I/SELinux ( 6324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_5145/cgroup.procs: No such file or directory
I/SELinux ( 6324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6324): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6324): TimaSignature is unavailable
D/ActivityThread( 6324): Added TimaKeyStore provider
D/ResourcesManager( 6324): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
I/SettingSearchManagerReceiver( 1478): endInsert
I/ActivityManager(  886): Killing 5171:com.sec.chaton/u0a86 (adj 15): bgCount ##41
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 6339): MountEmulatedStorage()
I/libpersona( 6339): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6339): v2
I/libpersona( 6339): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuSettingSearch: pid=6339 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 6339): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6339): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6339): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 6339): TimaSignature is unavailable
D/ActivityThread( 6339): Added TimaKeyStore provider
W/libprocessgroup(  886): failed to open /acct/uid_10086/pid_5171/cgroup.procs: No such file or directory
D/ResourcesManager( 6339): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
D/AssistantMenuSettingSearch( 6339): onReceive - action:android.settings.INSERT_SEARCHDB_VER_TWO_EXTRA_APPS
D/AssistantMenuSettingSearch( 6339): Make Setting DB
W/ContextImpl( 6339): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.updateSearchInfoDB:158 com.samsung.android.app.assistantmenu.AssistantMenuSettingSearch.onReceive:38 
,D/SHealthUpgrade(SHealthUpgradeUtil)( 4891): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4891): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4891): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 4891): RegionGroup for  is null
D/BluetoothManager( 4891): getConnectedDevices
D/BluetoothManager( 4891): getConnectedDevices
D/BluetoothManager( 4891): getConnectedDevices
I/ActivityManager(  886): Killing 5065:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
W/libprocessgroup(  886): failed to open /acct/uid_10017/pid_5065/cgroup.procs: No such file or directory
D/GCM     ( 1679): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  886): Killing 5313:com.sec.android.app.clockpackage/u0a91 (adj 15): bgCount ##41
D/AuthorizationBluetoothService( 1679): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GmsCoreStatsServiceLauncher( 2457): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
E/MDM     ( 2272): [246] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
D/AndroidRuntime( 6357): 
D/AndroidRuntime( 6357): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6357): CheckJNI is OFF
D/AndroidRuntime( 6357): setted country_code = Germany
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6357): setted countryiso_code = DE
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
D/AndroidRuntime( 6357): setted sales_code = DBT
D/AndroidRuntime( 6357): readGMSProperty: start
D/AndroidRuntime( 6357): readGMSProperty: already setted!!
D/AndroidRuntime( 6357): readGMSProperty: end
D/AndroidRuntime( 6357): addProductProperty: start
E/Zygote  ( 6364): MountEmulatedStorage()
I/libpersona( 6364): KNOX_SDCARD checking this for 10036
E/Zygote  ( 6364): v2
I/libpersona( 6364): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=6364 uid=10036 gids={50036, 9997, 1028, 1015, 3003} abi=armeabi-v7a
D/LocationInitializer( 2457): Restart initialization of location
I/SELinux ( 6364): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6364): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6364): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  886): failed to open /acct/uid_10091/pid_5313/cgroup.procs: No such file or directory
D/PowerManagerService(  886): [s] UserActivityState : 1 -> 2
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
D/PowerManagerService(  886): [s] DisplayPowerCallbacks : onStateChanged()
D/TimaKeyStoreProvider( 6364): TimaSignature is unavailable
D/ActivityThread( 6364): Added TimaKeyStore provider
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
D/lights  (  886): lcd : 1 +
D/lights  (  886): lcd : 1 -
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
D/ResourcesManager( 6364): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/AffinityControl( 6357): AffinityControl: registerfunction enter
D/ResourcesManager( 6364): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
W/ResourcesManager( 6364): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
D/AndroidRuntime( 6357): Calling main entry com.android.commands.am.Am
E/PersonaManagerService(  886): inState():  stateMachine is null !!
I/ActivityManager(  886): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ResourcesManager( 6364): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/AndroidRuntime( 6357): Shutting down VM
W/ResourcesManager( 6364): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager( 6364): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
W/ResourcesManager( 6364): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/SHealthUpgrade(SHealthUpgradeUtil)( 4891): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4891): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 4891): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/GCM     ( 1679): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,I/art     (  886): Explicit concurrent mark sweep GC freed 379416(13MB) AllocSpace objects, 0(0B) LOS objects, 22% free, 56MB/72MB, paused 2.463ms total 181.173ms
I/art     (  886): WaitForGcToComplete blocked for 75.849ms for cause Background
,D/AuthorizationBluetoothService( 1679): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2457): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/MDM     ( 2272): [240] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2457): Restart initialization of location
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6423): MountEmulatedStorage()
I/libpersona( 6423): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6423): v2
I/libpersona( 6423): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6423 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 6423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/SELinux ( 6423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NotifUtils( 5197): Validating Notification, mapSize: 1 getAttention: true ignoreUnobtrusive: false
,D/TimaKeyStoreProvider( 6423): TimaSignature is unavailable
,D/ActivityThread( 6423): Added TimaKeyStore provider
,I/NotifUtils( 5197): Unseen count doesn't match cursor count.  unseen: 13 cursor count: 7
,E/SQLiteLog( 5375): (284) automatic index on conversation_participants_view(conversation_id)
,D/ResourcesManager( 6423): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
,I/NotifUtils( 5197): Showing notification with unreadCount of 7 and unseenCount of 7
,E/SQLiteLog( 5375): (284) automatic index on conversation_participants_view(conversation_id)
,D/PopupuiReceiver( 6423): onReceive() getAction : com.android.systemui.power.action.ACTION_CABLE_CONNECTED
,D/SecContentProvider2(  886): uri = -1 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,I/PopupuiReceiver_KNOX( 6423): getSealedState : true
D/SecContentProvider2(  886): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,I/PopupuiReceiver_KNOX( 6423): getSealedHideNotificationMessages : 1
D/SecContentProvider2(  886): uri = 15 selection = getCheckCoverPopupState
D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
I/PopupuiReceiver_KNOX( 6423): getCheckCoverPopupState : true
W/ContextImpl( 6423): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:407 android.app.ActivityThread.handleReceiver:2945 
D/PopupuiReceiver( 6423): Action cable connected ! on - 
D/PopupuiReceiver( 6423): PopupuiService.java: dismissUSBCDetacheddDialog() unReigister
W/ContextImpl( 6423): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 com.sec.android.app.popupuireceiver.PopupuiService.dismissUSBCDetacheddDialog:130 com.sec.android.app.popupuireceiver.PopupuiService.onStartCommand:103 
W/ContextImpl( 6423): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2000 android.content.ContextWrapper.stopService:538 com.sec.android.app.popupuireceiver.PopupuiService.onDestroy:310 android.app.ActivityThread.handleStopService:3289 android.app.ActivityThread.access$2300:172 
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SQLiteLog( 5375): (284) automatic index on conversation_participants_view(conversation_id)
,E/SQLiteLog( 5375): (284) automatic index on conversation_participants_view(conversation_id)
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 5375): (284) automatic index on conversation_participants_view(conversation_id)
,D/ResourcesManager( 5375): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/art     ( 2457): Explicit concurrent mark sweep GC freed 22281(1670KB) AllocSpace objects, 22(352KB) LOS objects, 39% free, 19MB/32MB, paused 1.010ms total 41.702ms
,E/SPPClientService( 5514): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 5375): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,E/Zygote  ( 6444): MountEmulatedStorage()
E/Zygote  ( 6444): v2
I/libpersona( 6444): KNOX_SDCARD checking this for 10038
I/libpersona( 6444): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=6444 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5375): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5375): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/SELinux ( 6444): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6444): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6444): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,V/JNIHelp ( 5375): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/TimaKeyStoreProvider( 6444): TimaSignature is unavailable
,D/ActivityThread( 6444): Added TimaKeyStore provider
,E/SMD     (  285): DCD ON
,D/ResourcesManager( 6444): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,E/SPPClientService( 6444): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 6444): [PushClientApplication] Push log off : This is Ship build version
,I/PeopleDatabaseHelper( 2457): cleanUpNonGplusAccounts done.
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/ActivityThread( 5375): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5375): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26b62ce5: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5375): Installed default security provider GmsCore_OpenSSL
,D/SPPClientService( 6444): PushLog.txt file is not deleted.
D/SPPClientService( 6444): PushLog.txt file is not deleted.
D/SPPClientService( 6444): ============PushLog. stop!
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/SSRM:m  (  886): SIOP:: AP = 470, PST = 429, CUR = 300
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-nodpi-v4/bg_email.png
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6469): MountEmulatedStorage()
E/Zygote  ( 6469): v2
I/libpersona( 6469): KNOX_SDCARD checking this for 10038
I/libpersona( 6469): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=6469 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6469): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6469): TimaSignature is unavailable
,D/ActivityThread( 6469): Added TimaKeyStore provider
,D/ResourcesManager( 6469): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Babel   ( 5375): UserRecoverableAuthException.
,E/Babel   ( 5375): cfq: BadAuthentication
E/Babel   ( 5375): 	at cfn.a(Unknown Source)
E/Babel   ( 5375): 	at f.a(PG:191)
E/Babel   ( 5375): 	at ava.a(PG:88)
E/Babel   ( 5375): 	at ava.a(PG:128)
E/Babel   ( 5375): 	at bjs.a(PG:255)
E/Babel   ( 5375): 	at bep.a(PG:602)
E/Babel   ( 5375): 	at bep.a(PG:469)
E/Babel   ( 5375): 	at bpo.run(PG:1141)
E/Babel   ( 5375): Error getting auth token
E/Babel   ( 5375): bxl
E/Babel   ( 5375): 	at f.a(PG:201)
E/Babel   ( 5375): 	at ava.a(PG:88)
E/Babel   ( 5375): 	at ava.a(PG:128)
E/Babel   ( 5375): 	at bjs.a(PG:255)
E/Babel   ( 5375): 	at bep.a(PG:602)
E/Babel   ( 5375): 	at bep.a(PG:469)
E/Babel   ( 5375): 	at bpo.run(PG:1141)
,I/Babel_RequestWriter( 5375): error sending REQ[fc:0; creat:1456920166083; type:bev-420363219]; took 90 ms (error code == 100)
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/Babel   ( 5375): Account registration failedRedacted-21
,E/Babel   ( 5375): bph: null -- null
E/Babel   ( 5375): 	at ava.a(PG:120)
E/Babel   ( 5375): 	at ava.a(PG:128)
E/Babel   ( 5375): 	at bjs.a(PG:255)
E/Babel   ( 5375): 	at bep.a(PG:602)
E/Babel   ( 5375): 	at bep.a(PG:469)
E/Babel   ( 5375): 	at bpo.run(PG:1141)
I/Babel   ( 5375): Account setup failed with error state:106 account:Redacted-21
I/Babel   ( 5375): Account sign in complete with state 106account: Redacted-21
,I/art     ( 5375): Note: end time exceeds epoch: 
,I/ActivityManager(  886): Waited long enough for: ServiceRecord{56dd84d u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/identity.plus.page.impersonation https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/SPPClientService( 6469): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 6469): [PushClientApplication] Push log off : This is Ship build version
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SPPClientService( 6469): PushLog.txt file is not deleted.
,D/SPPClientService( 6469): PushLog.txt file is not deleted.
D/SPPClientService( 6469): ============PushLog. stop!
,E/LNoti   ( 6469): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 1679): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi/ic_launcher_babel.png
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/ActivityManager(  886): Killing 5338:com.google.android.gms:car/u0a12 (adj 15): bgCount ##41
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/Babel   ( 5375): Unexpected exception while authenticating.
,E/Babel   ( 5375): cfr: User intervention required. Notification has been pushed.
E/Babel   ( 5375): 	at cfn.b(Unknown Source)
E/Babel   ( 5375): 	at cfn.a(Unknown Source)
E/Babel   ( 5375): 	at f.a(PG:188)
E/Babel   ( 5375): 	at ava.b(PG:143)
E/Babel   ( 5375): 	at bnr.run(PG:5415)
E/Babel   ( 5375): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 5375): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 5375): 	at java.lang.Thread.run(Thread.java:818)
,D/GCM     ( 1679): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ChimeraCfgMgr( 2457): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/Kids    ( 2457): [GCoreUtils] Current gmscore version, 7899438 is smaller than the required version 8400000
,W/libprocessgroup(  886): failed to open /acct/uid_10012/pid_5338/cgroup.procs: No such file or directory
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,V/BitmapFactory( 5197): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_anonymous_avatar_40dp.png
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/NotifUtils( 5197): Account: 61035162 vibrate: false
,I/NotifUtils( 5197): New email in 61035162 vibrateWhen: false, playing notification: content://settings/system/notification_sound
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|1729800001|null|10114
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
I/ValidateNoPeople(  886): Executing: validation for: 0|com.google.android.gm|1729800001|null|10114
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,V/AudioPolicyManager(  291): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  886): getStreamVolume 5 index 110
D/LightsService(  886): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 886) 
D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  886): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|-2100714965|null|10114
D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,D/ResourcesManager( 1178): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,V/BitmapFactory( 1178): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,V/BitmapFactory( 1178): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_notification_multiple_mail_24dp.png
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|-913293406|null|10114
D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|-865450363|null|10114
D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|-633420634|null|10114
D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
E/SQLiteLog( 1793): (284) automatic index on sqlite_sq_AF626D30(STAT_DATA_ID)
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : 0
D/PhoneStatusBar( 1178): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3a5c4dd4
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|438982678|null|10114
D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|1919793178|null|10114
,D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gm,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
,I/ValidateNoPeople(  886): Validating: 0|com.google.android.gm|2046740944|null|10114
,I/ValidateNoPeople(  886): final affinity: 0.0
D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,I/ValidateNoPeople(  886): final affinity: 0.0
,I/ValidateNoPeople(  886): Executing: validation for: 0|com.google.android.gm|-2100714965|null|10114
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/ValidateNoPeople(  886): final affinity: 0.0
,I/ValidateNoPeople(  886): Executing: validation for: 0|com.google.android.gm|-913293406|null|10114
,I/ValidateNoPeople(  886): final affinity: 0.0
,I/ValidateNoPeople(  886): Executing: validation for: 0|com.google.android.gm|-865450363|null|10114
,I/ValidateNoPeople(  886): final affinity: 0.0
,I/ValidateNoPeople(  886): Executing: validation for: 0|com.google.android.gm|-633420634|null|10114
,I/ValidateNoPeople(  886): final affinity: 0.0
,I/ValidateNoPeople(  886): Executing: validation for: 0|com.google.android.gm|438982678|null|10114
,I/ActivityManager(  886): Killing 5028:com.android.vending/u0a30 (adj 15): bgCount ##41
,I/ValidateNoPeople(  886): final affinity: 0.0
,I/ValidateNoPeople(  886): Executing: validation for: 0|com.google.android.gm|1919793178|null|10114
,W/libprocessgroup(  886): failed to open /acct/uid_10030/pid_5028/cgroup.procs: No such file or directory
,I/ValidateNoPeople(  886): final affinity: 0.0
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/art     (  886): Background sticky concurrent mark sweep GC freed 17898(784KB) AllocSpace objects, 0(0B) LOS objects, 1% free, 71MB/72MB, paused 5.590ms total 47.035ms
,I/art     (  886): Background partial concurrent mark sweep GC freed 354823(20MB) AllocSpace objects, 5(6MB) LOS objects, 24% free, 48MB/64MB, paused 1.969ms total 131.274ms
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6507): MountEmulatedStorage()
,E/Zygote  ( 6507): v2
I/libpersona( 6507): KNOX_SDCARD checking this for 1000
I/libpersona( 6507): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=6507 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SQLiteLog( 4745): (284) automatic index on view_events(_id)
,W/PackageManager(  886): verifying app can be installed or not
,D/ApplicationPolicy(  886): isApplicationInstallationEnabled
,D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  Checking SIG BL - true
,I/SELinux ( 6507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ApplicationPolicy(  886): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall(  886): product true
,D/TimaKeyStoreProvider( 6507): TimaSignature is unavailable
,D/ActivityThread( 6507): Added TimaKeyStore provider
,D/CalendarAlarmManager( 4745): sys current time:1456920168153
,D/CalendarAlarmManager( 4745): reminder amount:0
,D/ResourcesManager( 6507): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 6507): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,I/DIAGMON_AGENT( 6507): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/DIAGMON_AGENT( 6507): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 6507): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 6507): [com.diagmondm.XDMBroadcastReceiver(34/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager(  886): Killing 5427:com.sec.android.soagent/u0a37 (adj 15): bgCount ##41
,I/DBG_DM  ( 4413): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6522): MountEmulatedStorage()
E/Zygote  ( 6522): v2
I/libpersona( 6522): KNOX_SDCARD checking this for 1000
I/libpersona( 6522): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=6522 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 290us total 18.233ms
,W/art     (  886): Suspending all threads took: 9.404ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 288us total 8.588ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 8.963ms
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,I/SELinux ( 6522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6522): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  886): Background sticky concurrent mark sweep GC freed 100731(6MB) AllocSpace objects, 5(248KB) LOS objects, 4% free, 60MB/64MB, paused 11.671ms total 89.997ms
,W/libprocessgroup(  886): failed to open /acct/uid_10037/pid_5427/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6522): TimaSignature is unavailable
,D/ActivityThread( 6522): Added TimaKeyStore provider
,D/ResourcesManager( 6522): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,E/MTPRx   ( 6522): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/SecContentProvider2(  886): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
V/MTPRx   ( 6522): sealedState: false
V/MTPRx   ( 6522): sealedUsbMassStorageState: false
,E/MTPRx   ( 6522): check value of boot_completed is1
E/MTPRx   ( 6522): check booting is completed_sys.boot_completed
,E/MTPRx   ( 6522): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 6522): Status for mount/Unmount :removed
E/MTPRx   ( 6522): SDcard is not available
,W/MTPRx   ( 6522): value of connected istrue
,W/MTPRx   ( 6522): value of configured istrue
W/MTPRx   ( 6522): value of mtpEnabled istrue
W/MTPRx   ( 6522): value of ptpEnabled isfalse
,E/MTPRx   ( 6522): Received USB_STATE with sdCardLaunch = 0
E/MTPRx   ( 6522): mFirstTime: false
,D/        ( 6522): MTP: reading debug level property
,E/MTPRx   ( 6522):  String obtained from jar = 0b1e96db05d64ea4
,E/MTPJNIInterface( 6522): Getting CryptionKey from JAVA
E/MTPRx   ( 6522): currentUserId is 0
,I/FaceInterface( 6165): startFaceScan() : going on
,D/FaceInterface( 6165): startFaceScan() is called.
,E/MTPRx   ( 6522): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 6522): usbMode is 0210
,E/MTPRx   ( 6522): is_Privatemode is NOT 1
,D/SettingsProvider(  886): name = mtp_usb_conditions_met
,D/ContentApp( 1226): startScan() is called.
,D/FaceValue( 1226): mSleepTime: 800
,D/FaceValue( 1226): mMaxThreadNum: 2
D/SecContentProvider(  886): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 6522): sending MTP_ICON_ENABLED to stack
D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
,D/SettingsProvider(  886): name = mtp_running_status
D/SettingsProvider(  886): name = mtp_usb_conditions_met
E/MTPRx   ( 6522): else part ... so first time!!!
E/MTPPlaObsrvr( 6522): inside setContext()
E/MTPPlaObsrvr( 6522):  inside createplafiles
E/MTPPlaObsrvr( 6522): playlist count is0
E/MTPPlaObsrvr( 6522):  inside try branch createplafiles
E/MTPPlaObsrvr( 6522):  inside deleteing plas createplafiles
E/MTPPlaObsrvr( 6522): Inside registerContentObserver
E/MtpAdbObserver( 6522): inside setContext()
E/MtpAdbObserver( 6522): Inside registerContentObserver
W/Settings( 6522): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
D/SettingsProvider(  886): name = mtp_running_status
D/SettingsProvider(  886): name = mtp_usb_conditions_met
,E/MtpService( 6522): onCreate.
,E/MtpService( 6522): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 6522): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,D/TMNetworkReceiver( 5995): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
,D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = true, mIsFileUpdated= false
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() mThread.interrupt()
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() Exit 
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() interrupted while sleeping 
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() UsbCheck Thread Exit
,E/MtpService( 6522): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/MtpService( 1226): updating state; isCurrentUser=true, mMtpLocked=false
,D/TMSLogRemovalReceiver( 5995): TMLogRemovalReceiver.onReceive() Enter isCalled =true
D/TMSLogRemovalReceiver( 5995): TMLogRemovalReceiver.onReceive() Exit
,E/MtpService( 6522): onStartCommand.
,E/MtpService( 6522): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   ( 6522): calling native method
E/MTPJNIInterface( 6522): < MTP > Registering BroadCast receiver :::::
D/TMNetworkReceiver( 5995): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
I/art     (  886): Background partial concurrent mark sweep GC freed 222318(13MB) AllocSpace objects, 14(9MB) LOS objects, 25% free, 46MB/62MB, paused 1.772ms total 125.147ms
,E/MTPJNIInterface( 6522): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 6522): noti = 10
D/MediaScannerReceiver( 1226): action: android.intent.action.MTP_FILE_SCAN
,E/MtpService( 6522): onStartCommand.
,E/MtpService( 6522): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   ( 6522): calling native method
E/MTPRx   ( 6522): Checking the driver time out
E/MTPJNIInterface( 6522): noti = 2
D/        ( 6522): deleting sockets before message queue initialization
,D/        ( 6522): event handler thread is created, so set the flag
,E/MTPRx   ( 6522): called native method
E/MTPJNIInterface( 6522): setting Media scanner status0
E/MTPJNIInterface( 6522): After setting Media scanner status0
W/MTPRx   ( 6522): notification from stack 1
,E/        ( 6522): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 6522): Getting media scanner status0
,E/MTPJNIInterface( 6522): DeviceName is Thali Test (Galaxy S5)
,V/TaskCloserActivity( 6015): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/SettingSearch/SearchIntentReceiver( 1301): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
,I/SettingSearch/SearchIntentReceiver( 1301): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 1301): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 1301): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SettingsSearchManager( 1301): Infomation -> numtitleinfo : 0 numSearchinfo : 334
,I/MusicLeanback( 5939): Conditions not met for autocaching.
,I/MusicLeanback( 5939): Stop autocaching.
,D/WearableClient( 5939): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5939): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5939): WearableClientImpl.onPostInitHandler: done
,D/WearableClient( 5939): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils( 5939): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 5939): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/MediaScannerService( 1226): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,I/Avrcp   ( 3879): Received the onChange database event
I/Avrcp   ( 3879): onChange on thread: 1 Uri: content://media/ selfchange: false
I/Avrcp   ( 3879): send MSG_CHECK_NOW_PLAYING_CONTENT_CHANGED after 500ms
,I/SettingSearch/SettingsSearchManager( 1301):  Infomation -> getItem size : 334
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started
D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1226): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 1226): Prescan. DB items number : 21 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/FaceInterface( 6165): startFaceScan() : going on
,D/FaceInterface( 6165): startFaceScan() is called.
,D/ContentApp( 1226): startScan() is called.
,D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
,D/ResourcesManager( 1301): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,I/iu.UploadsManager( 2457): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: FULL; maxMobile: 157286400
,V/MediaScanner( 1226): processDirectory :  /storage/emulated/0
,D/ResourcesManager( 1301): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,W/ResourcesManager( 1301): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 1301): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/MediaScanner( 1226): Skipping:
D/MediaScanner( 1226): 7klwibgf7fvntblfd7(75ebcf7
,I/iu.UploadsManager( 2457): End new media; added: 0, uploading: 0, time: 46 ms
,D/ResourcesManager( 1301): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/MediaScanner( 1226): Skipping:
,D/MediaScanner( 1226): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,V/MediaScanner( 1226): processDirectory :  /storage/extSdCard
,W/MediaScanner( 1226): Error opening directory, reason : Permission denied.
W/MediaScanner( 1226): 7klwibgf7fxlKdCbid7
,E/File    ( 1226): fail readDirectory() errno=2
,V/MediaScanner( 1226): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@1ea27401
,V/MediaScanner( 1226): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@1ea27401
,V/MediaScanner( 1226):  prescan time: 62ms (DB items: 21)
,V/MediaScanner( 1226):     scan time: 131ms (Caching mode: true), (makeEntry time: 57ms ~43%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1226): postscan time: 5ms (bulkDeleter : 0), (delete DeadThumbnail time : 4ms)
V/MediaScanner( 1226):    total time: 198ms
V/MediaScanner( 1226): checked files: 4  directories : 17  (I: 0, U: 0)
,E/MTPJNIInterface( 6522): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,D/MediaScannerService( 1226): !@done scanning volume external
,E/CscFactoryReceiver( 1478): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 1478): Media DB Scanner finished.
D/CscFactoryReceiver( 1478): start service to Set Ringtone
,D/CscFactoryReceiver( 1478): start service to Set Notification
,D/CscFactoryReceiver( 1478): start service to Set Alarmtone
,D/CscUpdateService( 1478): onStart
E/CscUpdateService( 1478): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1478): only ringtone update
,D/CscUpdateService( 1478): onStart
E/CscUpdateService( 1478): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1478): only notification update
,E/CscParser( 1478): update(): xml file exist
D/CscUpdateService( 1478): onStart
E/CscUpdateService( 1478): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 1478): only alarmtone update
,E/CscParser( 1478): update(): xml file exist
,I/SystemBroadcastReceiver( 6102): [#DCM#] Calling notifyListeners. 
E/CscParser( 1478): update(): xml file exist
,I/StorageController( 6102): [#DCM#]  state through storage volume =  mounted
,I/StorageController( 6102): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
,I/StorageController( 6102): [#DCM#]  state through storage volume =  unmounted
I/StorageController( 6102): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
,I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
I/StorageController( 6102): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
,I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6102): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6102): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6102): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6102): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
,I/StorageController( 6102): [#DCM#]  state through storage volume =  removed
,I/StorageController( 6102): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController( 6102): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController( 6102): [#DCM#] Sending intent for OS Upgrade for Phone contents 
,I/DCMUtilities( 6102): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
I/SystemUtils( 6102): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
I/SystemUtils( 6102): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
,I/DCMUtilities( 6102): [#DCM#] OSUpgrade not required 
,E/Zygote  ( 6569): MountEmulatedStorage()
,E/Zygote  ( 6569): v2
I/libpersona( 6569): KNOX_SDCARD checking this for 10007
I/libpersona( 6569): KNOX_SDCARD not a persona
,W/CSCSettings( 1478): Setting Ringtones (type) : 4
I/ActivityManager(  886): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=6569 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
D/CscParser( 1478): AlarmTone: null
W/CSCSettings( 1478): 1. Tag_Str: null
,W/CSCSettings( 1478): Setting Ringtones (type) : 2
,D/CscParser( 1478): MessageTone: null
,W/CSCSettings( 1478): Setting Ringtones (type) : 1
D/CscParser( 1478): RingTone: null
W/CSCSettings( 1478): 1. Tag_Str: null
,W/CSCSettings( 1478): 1. Tag_Str: null
,E/SMD     (  285): DCD ON
,I/SELinux ( 6569): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6569): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6569): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6569): TimaSignature is unavailable
,D/ActivityThread( 6569): Added TimaKeyStore provider
,D/ResourcesManager( 6569): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,E/MTPJNIInterface( 6522): Status for mount/Unmount :removed
E/MTPJNIInterface( 6522): SDcard is not available
,D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,I/ThumbnailProvider( 6569): ThumbnailProvider onCreate()
,D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,E/        ( 6522): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
D/GeoLookout( 5133): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/MTPJNIInterface( 6522): Status for mount/Unmount :removed
E/MTPJNIInterface( 6522): SDcard is not available
,E/SQLiteLog( 6522): (21) API call with NULL database connection pointer
E/SQLiteLog( 6522): (21) misuse at line 105654 of [9491ba7d73]
E/SQLiteLog( 6522): (21) API call with NULL database connection pointer
E/SQLiteLog( 6522): (21) misuse at line 100436 of [9491ba7d73]
E/SQLiteLog( 6522): (21) API call with NULL database connection pointer
E/SQLiteLog( 6522): (21) misuse at line 100436 of [9491ba7d73]
E/SQLiteLog( 6522): (21) API call with NULL database connection pointer
E/SQLiteLog( 6522): (21) misuse at line 105654 of [9491ba7d73]
,W/MTPRx   ( 6522): notification from stack 2
,D/        ( 6522): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
E/        ( 6522): [mtp_init_device 692]  After open the MTP fd = 32 and line = 692...
D/        ( 6522): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 6522):  [sua_support_present:1275] returning false 
D/        ( 6522): *****Starting mtp_io()
,W/MTPRx   ( 6522): notification from stack 3
D/        ( 6522): [mtp_start_io] source_thread Creation 
,D/        ( 6522): [mtp_start_io] sink_thread Creation 
D/        ( 6522): [mtp_start_io:368] sink thread created so set th_sink
,I/DocumentBroadcastReceiver( 6569): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService( 6569): [START] processBroadcastIntent ...
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/GalleryCacheReady( 6165): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady( 6165): handleMeidaScanFinish()
,D/FaceInterface( 6165): requestFaceScan() is called.
,I/BroadcastProcessorService( 6569): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,W/LocalSuggestAlbumData( 6165): query fail: 
,I/FaceInterface( 6165): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData( 6165): query fail: 
,I/SystemInfo( 6569): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService( 6569): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService( 6569): [START] DocumentService startDocumentService
,I/DocumentService( 6569): DocumentService onCreate ... service
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6569): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6569): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/SystemInfo( 6569): [SIOP LEVEL] : 0
,I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 1301): LOCALE_CHANGED call search setting db finish!!
,V/Avrcp   ( 3879): handleMessage, msg=207
D/BluetoothMediaBrowser( 3879):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/DocumentService( 6569): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6569): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/MediaStoreImporter( 5939): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/BluetoothMediaBrowser( 3879): no now playing list
D/BluetoothMediaBrowser( 3879):  getNowPlayingId now playing id : -1
D/Avrcp   ( 3879):  checkNowPlayingList start
,E/File    ( 6569): fail readDirectory() errno=13
E/File    ( 6569): fail readDirectory() errno=13
,I/SystemInfo( 6569): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService( 6569): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService( 6569): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :29
E/DocumentService( 6569): [THUMBNAIL] Total Time taken for each file :0
E/        ( 6569): [INDEX] Total time taken for each file :0
,I/DocumentService( 6569): DocumentService onDestroy start
,I/DocumentService( 6569): DocumentService onDestroy end
,I/DocumentService( 6569): DocumentService cleanupEverything start
,I/IndexParserThreadsManager( 6569): InterruptedException: null
,I/SystemInfo( 6569): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService( 6569): DocumentService cleanupEverything end
,I/Process ( 6569): Sending signal. PID: 6569 SIG: 9
,I/ActivityManager(  886): Killing 5465:com.policydm/1000 (adj 15): bgCount ##41
,I/SettingSearch/SearchIntentReceiver( 1301): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 1301): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager(  886): Process com.samsung.indexservice (pid 6569)(adj 9) has died(58,615)
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_5465/cgroup.procs: No such file or directory
,D/PackageManager(  886): Existing package
,D/PackageManager(  886): Renaming /data/app/vmdl626845013.tmp to /data/app/com.test.thalitest-1
,D/PackageManager(  886): installNewPackageLI: Package{1372082a com.test.thalitest}
,W/ProcessCpuTracker(  886): Skipping unknown process pid 6537
,W/ProcessCpuTracker(  886): Skipping unknown process pid 6538
,W/ProcessCpuTracker(  886): Skipping unknown process pid 6541
W/ProcessCpuTracker(  886): Skipping unknown process pid 6543
,W/ProcessCpuTracker(  886): Skipping unknown process pid 6598
,I/SELinux (  294): selinux_android_setcategory: no category for userid: 0, path: /data/data/com.test.thalitest/lib 
,I/art     (  886): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
,I/art     (  886): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
,D/PackageManager(  886): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,I/dex2oat ( 6604): ----------------------------------------------------
,I/dex2oat ( 6604): <SS>: S T A R T I N G . . .
I/dex2oat ( 6604): <SS>: going to process manifest...
I/        ( 6604): SS_ART_lib [I]: Processing Manifest...
,I/        ( 6604): SS_ART_lib [I]: XML is parsed (58 > 55)
,I/        ( 6604): SS_ART_lib [I]: XML is parsed (58 > 55)
,I/dex2oat ( 6604): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=-1 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6604): <SS>: going to form and sign ss id...
I/dex2oat ( 6604): dex2oat took 388.475ms (threads: 4)
,I/PackageManager(  886): do mInstaller.dexopt : 0
,D/PackageManager(  886): Time to dexopt: 0.455 seconds
,W/System.err(  886): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,W/System.err(  886): 	at libcore.io.IoBridge.open(IoBridge.java:456)
,W/System.err(  886): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err(  886): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5071)
W/System.err(  886): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:17035)
,W/System.err(  886): 	at com.android.server.pm.PackageManagerService.access$5100(PackageManagerService.java:313)
W/System.err(  886): 	at com.android.server.pm.PackageManagerService$19.run(PackageManagerService.java:17020)
W/System.err(  886): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
,W/System.err(  886): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err(  886): 	... 5 more
,W/PackageSettings(  886): Skipping PackageSetting{36f7fd8a com.example.hello/10201} due to missing metadata
,I/HarmonyEASService(  886): Updating for all 1
D/PackageManager(  886): New package installed
,W/PackageSettings(  886): Skipping PackageSetting{36f7fd8a com.example.hello/10201} due to missing metadata
,D/PackageManager(  886): doPostInstall for uid{10200}
,D/PackageManager(  886): token 1 to BM for possible restore
,V/BackupManagerService(  886): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
,V/BackupManagerService(  886): Finishing install immediately
,D/PackageManager(  886): BM finishing package install for 1
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/PackageManager(  886): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager(  886): [MSG] MCS_UNBIND
,D/ResourcesManager(  886): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 1478): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 1478): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 1478): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/RegisteredServicesCache( 1472): empty dynamic service
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 1487): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/PackageManager(  886): [MSG] POST_INSTALL: observer{1069752315}
D/PackageManager(  886):           Handling post-install for 1
,D/ResourcesManager( 1487): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Settings(  886): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,W/ResourcesManager( 1487): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BitmapFactory( 1487): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_settings_icon.png
W/ResourcesManager( 1487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1487): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager( 1487): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,W/ResourcesManager( 1487): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 1487): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
,E/SamsungIME( 1870): mOCRHelper is null
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Books/Books.apk
,E/Zygote  ( 6632): MountEmulatedStorage()
E/Zygote  ( 6632): v2
I/libpersona( 6632): KNOX_SDCARD checking this for 10034
I/libpersona( 6632): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6632 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 6632): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6632): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6632): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/TimaKeyStoreProvider( 6632): TimaSignature is unavailable
,D/ActivityThread( 6632): Added TimaKeyStore provider
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,I/ActivityManager(  886): Killing 5496:com.samsung.helphub/1000 (adj 15): bgCount ##41
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/RegisteredServicesCache( 1472): empty dynamic service
,I/FeatureConfig( 6632): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  886): mCursor = null
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_5496/cgroup.procs: No such file or directory
,D/ResourcesManager( 1487): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,V/BitmapFactory( 1487): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/icon.png
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  886): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  886): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/art     (  886): Explicit concurrent mark sweep GC freed 109078(5MB) AllocSpace objects, 10(2MB) LOS objects, 23% free, 50MB/66MB, paused 1.956ms total 346.690ms
D/PackageManager(  886): result of install: 1{1069752315}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/PackageManager(  886): Observer no longer exists.
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,D/RCPManagerService(  886): PackageReceiver onReceive()
D/RCPManagerService(  886): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService(  886):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService(  886):  PackageReceiver onReceive() bundle null
,D/KnoxMUMContainerPolicy(  886): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
,D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/BackupManagerService(  886): Removing schedule queue dupe of com.test.thalitest
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(  886): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  886): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy(  886): uID is 10200
V/EnterpriseBillingPolicy(  886): Removed Packageuid is0
,V/EnterpriseBillingPolicyStorage(  886): getProfileForApplication - enter
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,V/EnterpriseBillingPolicyStorage(  886): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  886): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage(  886): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService(  886): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,V/BackupManagerService(  886): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  886): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2bccfc6a
,D/KnoxMUMContainerPolicy(  886): packageInstalledForExternalStorage com.test.thalitest
,D/ResourcesManager(  886): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PowerManagerService(  886): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  886): Nap time (uid 1000)...
I/PowerManagerService(  886): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  886): Going to sleep due to screen timeout (uid 1000)...
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
D/PowerManagerService(  886): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  886): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  886): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI(  886): setDeviceInteractive: 0
,D/InputManager-JNI(  886): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  886): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/PowerManagerService(  886): handleSandman : startDream()
,D/InputManager-JNI(  886): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,E/PowerManagerService(  886): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService(  886): Sleeping (uid 1000)...
D/PowerManagerService(  886): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  886): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService(  886): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  886): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,I/SurfaceFlinger(  249): id=14 createSurf (1080x1920),2 flag=404, ColorFade
,D/SContextService(  886): 	.unregisterCallback : 1, client=
D/SContextService(  886): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@1a08e332, Service = Auto Rotation, used = 1
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 6632): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6632): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/CAE     (  886): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
W/ResourcesManager( 6632): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/CAE     (  886): stop(ContextProvider.java:149)
,V/CAE     (  886): clear(AutoRotationRunner.java:182)
,V/CAE     (  886): disable(AutoRotationRunner.java:171)
,I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  886): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,I/Adreno-EGL(  886): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  886): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL(  886): Build Date: 03/03/15 Tue
I/Adreno-EGL(  886): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL(  886): Remote Branch: 
I/Adreno-EGL(  886): Local Patches: 
I/Adreno-EGL(  886): Reconstruct Branch: 
,D/CAE     (  886): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
I/CAE     (  886): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 6632): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/GmsNetworkLocationProvi( 2272): DISABLE
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/GCoreNlp( 2272): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 6632): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,W/ResourcesManager( 6632): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/CAE     (  886): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  886): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     (  886): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     (  886): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  886): removeSContextService() : service = Auto Rotation
D/SContextService(  886): ===== SContext Service List =====
D/SContextManager(  886):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@20bd5401, service=Auto Rotation
,D/KeyguardViewMediator( 1178): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1178): *** KeyguardEffectView getInstanceIfExists ***
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
D/KeyguardEffectViewController( 1178): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 1178): notifyScreenOffLocked
,I/SQLiteSecureOpenHelper( 3258): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3258): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/KeyguardViewMediator( 1178): timeout : 5000
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/CAE     (  886): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  886): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  886): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService(  886): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/KeyguardViewMediator( 1178): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 1178): handleNotifyScreenOff
D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/ResourcesManager( 6632): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_SCREEN_ON
,W/ResourcesManager( 6632): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/MotionRecognitionService(  886):  handler : SCREEN_ON end
,D/DisplayPowerController(  886): ColorFade: onAnimationStart
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 0
,D/RampAnimator(  886): mAnimationCallback timeDelta calculate error!! -8.65546E-4
,D/WifiStateMachine(  886): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  886): handleScreenStateChanged Exit: true
,D/NotificationService(  886): ACTION_SCREEN_ON
D/LightsService(  886): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 886) 
,D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  886): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  886): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/lights  (  886): lcd : 0 +
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 0
,D/IpRemoteDisplayController(  886): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController(  886): Bridge Server is not available
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 6632): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/lights  (  886): lcd : 0 -
,D/PersonaManagerService(  886): ACTION_SCREEN_ON onReceive
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  886): do suspend false
D/PersonaManagerServiceHandler(  886): MSG_ACTION_SCREEN_ON called
,I/wpa_supplicant( 1260): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1260): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1260): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1260): Scan requested (ret=0) - scan timeout 30 seconds
,I/NfcService( 1472): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,D/NfcService( 1472): call the applyRotuiing
,W/ResourcesManager( 6632): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/EnterpriseDeviceManagerService(  886): Package has changed for user 0
,D/EnterpriseDeviceManagerService(  886): Admin package name: com.google.android.gms
,I/ActivityManager(  886): Killing 5556:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2014): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
D/accuweather( 2014): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/accuweather( 2014): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
W/ResourcesManager( 6632): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6632): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,I/SamsungIME( 1870): getNextShiftState() cursorCapsMode : 0
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_5556/cgroup.procs: No such file or directory
,D/DisplayPowerState(  886): !@ ColorFade entry
,D/DisplayPowerController(  886): ColorFade: onAnimationEnd
,D/ResourcesManager( 6632): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,W/ResourcesManager( 6632): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 6632): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/AutomaticBrightnessController(  886): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController(  886): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,E/LightSensor(  886): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorManager(  886): unregisterListener ::   
,E/Sensors (  886): Acc old sensor_state 8193, new sensor_state : 8192 en : 0
,D/SensorManager(  886): unregisterListener ::   
,D/DisplayPowerController(  886): getFinalBrightness : 0 -> 0
,D/DisplayPowerController(  886): getFinalBrightness : 0 -> 0
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
I/DisplayManagerService(  886): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,V/ActivityManager(  886): Display changed displayId=0
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SystemBroadcastReceiver( 6102): [#DCM#] [DCM_Performance] onReceive completed in time  182 microsec. 
,I/SystemBroadcastReceiver( 6102): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager( 6102): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController( 6102): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/LockPatternUtilsCache( 1178): value : false
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/LightsService(  886): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 886) 
,D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/LightSensor(  886): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/SensorManager(  886): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  886): turn on LED for charging
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/CAE     (  886): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  886): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SensorHubManager(  886): SendSensorHubData: send data = -76, 13, -46, 0
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CrashAnrDetector(  886): onPackageAdded : com.test.thalitest
,D/LocationProviderProxy(  886): applying state to connected service
,D/LocationProviderProxy(  886): applying state to connected service
,I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 2, 51,
D/SensorHubManager(  886): SendSensorHubData: send data = -63, 14, 12, 2, 51
D/Sensorhubs(  297): sendContextData: -63, 14, 12, 2, 51
,D/SSRM:m  (  886): SIOP:: AP = 470, PST = 434, CUR = 300
D/X       (  886): broadcastSiopLevelIntent:: currentSiopLevel = 0
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SystemBroadcastReceiver( 6102): [#DCM#] [DCM_Performance] onReceive completed in time  75 microsec. 
,I/SystemBroadcastReceiver( 6102): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6102): [#DCM#] onReceive action = EVENT_SIOP
,D/ContentApp( 1226):  LEVEL : 0
,D/ResourcesManager( 3332): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  886):  handler : SCREEN_OFF end 
,D/WifiStateMachine(  886): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine(  886): handleScreenStateChanged Exit: false
,D/NotificationService(  886): ACTION_SCREEN_OFF
,D/LightsService(  886): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 886) 
D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x12 | SvcLED(id=4) set On
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  886): do suspend true
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/ActivityManager(  886): Killing 5631:com.LocalFota/u0a120 (adj 15): bgCount ##41
,I/SecExternalDisplayIntents_Java(  886): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  886): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController(  886): Bridge Server is not available
,D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 1178): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1178): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,W/libprocessgroup(  886): failed to open /acct/uid_10120/pid_5631/cgroup.procs: No such file or directory
,D/PersonaManagerService(  886): ACTION_SCREEN_OFF onReceive
,I/UpdateIcingCorporaServi( 1574): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  886): Excessive delay in setPowerMode(): 274ms
D/PersonaManagerServiceHandler(  886): MSG_ACTION_SCREEN_OFF called
,D/PowerManagerService(  886): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  886): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  886): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,E/QCOM PowerHAL(  886): Invalid hint ID.
I/QCOM PowerHAL(  886): Got set_interactive hint
,I/PowerManagerService(  886): [PWL] Off : 0s ago
,I/PowerManagerService(  886): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  886): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2457, ws=null) (elapsedTime=16645)
I/PowerManagerService(  886): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  886): [PWL]     mDisplayReady : false
,I/PowerManagerService(  886): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/DisplayPowerController(  886): getFinalBrightness : 0 -> 0
D/PowerManagerService(  886): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService(  886): [PWL] sb release: PowerManagerService.Display
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6663): MountEmulatedStorage()
I/libpersona( 6663): KNOX_SDCARD checking this for 10075
E/Zygote  ( 6663): v2
I/libpersona( 6663): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6663 uid=10075 gids={50075, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6663): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6663): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6663): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/NfcService( 1472): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1178):      ACTION_SCREEN_OFF is finished!!!! 
,D/TimaKeyStoreProvider( 6663): TimaSignature is unavailable
,D/ActivityThread( 6663): Added TimaKeyStore provider
,E/StatusBar( 1178): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1178): dismissHelpPopup 
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2014): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ResourcesManager( 6663): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 6663): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6685): MountEmulatedStorage()
E/Zygote  ( 6685): v2
I/libpersona( 6685): KNOX_SDCARD checking this for 1000
I/libpersona( 6685): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6685 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 5599:com.osp.app.signin/u0a45 (adj 15): bgCount ##41
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 17040(943KB) AllocSpace objects, 3(243KB) LOS objects, 40% free, 17MB/29MB, paused 440us total 24.704ms
,I/SELinux ( 6685): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6685): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6685): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LightsService(  886): [SvcLED]  onSensorChanged::light value = 1
,E/LightSensor(  886): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  886): unregisterListener ::   
,D/lights  (  886): led_pattern : 3 +
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/lights  (  886): led_pattern : 3 -
,D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ResourcesManager( 2457): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/TimaKeyStoreProvider( 6685): TimaSignature is unavailable
,D/ActivityThread( 6685): Added TimaKeyStore provider
,I/SystemBroadcastReceiver( 6102): [#DCM#] [DCM_Performance] onReceive completed in time  61 microsec. 
I/SystemBroadcastReceiver( 6102): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager( 6102): [#DCM#] onReceive action = EVENT_SCREEN_OFF
,I/DCMController( 6102): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,W/libprocessgroup(  886): failed to open /acct/uid_10045/pid_5599/cgroup.procs: No such file or directory
,D/PowerManagerService(  886): [PWL] sb release: PowerManagerService.Broadcasts
,D/ResourcesManager( 6685): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 6685): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/SSRM:m  (  886): SIOP:: AP = 470, PST = 439, CUR = 300
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6705): MountEmulatedStorage()
E/Zygote  ( 6705): v2
I/libpersona( 6705): KNOX_SDCARD checking this for 10086
I/libpersona( 6705): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.chaton for broadcast com.sec.chaton/.plugin.PlugInMonitor: pid=6705 uid=10086 gids={50086, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 5657:com.sec.android.app.mt/1000 (adj 15): bgCount ##41
,I/SELinux ( 6705): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6705): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6705): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6705): TimaSignature is unavailable
,D/ActivityThread( 6705): Added TimaKeyStore provider
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_5657/cgroup.procs: No such file or directory
,D/ResourcesManager( 6705): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/ResourcesManager( 6705): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/SMD     (  285): DCD ON
,D/PushModule( 6705): [PushClientApplication] (main) PushClientApplication.onCreate()
,I/PushModule( 6705): [PushClientApplication] (main) PushModule version: 0.9.01.12
,D/PushModule( 6705): [PushClientApplication] (main) Discovered public push client. disable in app push client.
,D/ChatON  ( 6705): [1][isApplicationInstalled] com.android.mms was installed
,W/ContextImpl( 6705): Implicit intents with startService are not safe: Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } android.content.ContextWrapper.startService:533 com.sec.chaton.global.GlobalApplication.onCreate:358 android.app.Instrumentation.callApplicationOnCreate:1020 
,W/ActivityManager(  886): Unable to start service Intent { act=com.sec.chaton.push.PUSH_CLIENT_SERVICE_ACTION } U=0: not found
,D/ResourcesManager( 1574): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/ChatON  ( 6705): [1][a] ChatONV isn't installed.
,D/ChatON  ( 6705): [1][a] ChatONVPlugIn.isAvailable()
,I/UpdateIcingCorporaServi( 1574): UpdateCorporaTask done [took 435 ms] updated apps [took 435 ms] 
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6724): MountEmulatedStorage()
,E/Zygote  ( 6724): v2
I/libpersona( 6724): KNOX_SDCARD checking this for 1000
I/libpersona( 6724): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=6724 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 5681:com.samsung.android.sconnect/u0a138 (adj 15): bgCount ##41
,I/SELinux ( 6724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6724): TimaSignature is unavailable
,D/ActivityThread( 6724): Added TimaKeyStore provider
,D/ResourcesManager( 6724): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,W/libprocessgroup(  886): failed to open /acct/uid_10138/pid_5681/cgroup.procs: No such file or directory
,D/ShortcutReceiver( 6724):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6740): MountEmulatedStorage()
E/Zygote  ( 6740): v2
I/libpersona( 6740): KNOX_SDCARD checking this for 10030
I/libpersona( 6740): KNOX_SDCARD not a persona
,D/SSRM:a  (  886): DeviceInfo:: 000000000000
D/SSRM:a  (  886): SettingsAirViewInfo:: 000000000
,I/ActivityManager(  886): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6740 uid=10030 gids={50030, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
I/ActivityManager(  886): Killing 5701:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
,E/SELinux ( 6740): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6740): TimaSignature is unavailable
,D/ActivityThread( 6740): Added TimaKeyStore provider
,D/ResourcesManager( 6740): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,W/libprocessgroup(  886): failed to open /acct/uid_10143/pid_5701/cgroup.procs: No such file or directory
,D/Finsky  ( 6740): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6740): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6780): MountEmulatedStorage()
,E/Zygote  ( 6780): v2
I/libpersona( 6780): KNOX_SDCARD checking this for 10012
I/libpersona( 6780): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6780 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,V/AlarmManager(  886): waitForAlarm result :8
,I/SELinux ( 6780): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 6780): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 6780): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/Settings( 6740): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6740): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TimaKeyStoreProvider( 6780): TimaSignature is unavailable
,D/ActivityThread( 6780): Added TimaKeyStore provider
,D/ResourcesManager( 6780): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,W/ResourcesManager( 6780): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6780): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6780): VM with version 2.1.0 has multidex support
,I/MultiDex( 6780): install
I/MultiDex( 6780): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6780): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,D/Finsky  ( 6740): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6740): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  886): Killing 5863:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
,D/Finsky  ( 6740): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 2457): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 2457): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 6740): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 2457): updateResources: need to parse f{com.google.android.gms}
,I/HomeSyncInstallReceiver( 1472): This pkg do not need BT addr. Do nothing
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,W/ActivityThread( 6780): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6780): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@5698ba9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6780): Installed default security provider GmsCore_OpenSSL
,E/Zygote  ( 6814): MountEmulatedStorage()
E/Zygote  ( 6814): v2
I/libpersona( 6814): KNOX_SDCARD checking this for 10015
I/libpersona( 6814): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=6814 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 6814): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_5863/cgroup.procs: No such file or directory
,I/SELinux ( 6814): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6814): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6814): TimaSignature is unavailable
,D/ActivityThread( 6814): Added TimaKeyStore provider
,D/ResourcesManager( 6814): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6836): MountEmulatedStorage()
E/Zygote  ( 6836): v2
I/libpersona( 6836): KNOX_SDCARD checking this for 10016
I/libpersona( 6836): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.groupcast for broadcast com.samsung.groupcast/.receiver.SSPReceiver: pid=6836 uid=10016 gids={50016, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 6836): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6836): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  886): Killing 6030:com.sec.factory/1000 (adj 15): bgCount ##41
E/SELinux ( 6836): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6836): TimaSignature is unavailable
,D/ActivityThread( 6836): Added TimaKeyStore provider
,D/ResourcesManager( 6836): creating new AssetManager and set to /system/priv-app/GroupPlay_27/GroupPlay_27.apk
,W/ResourcesManager( 6836): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 6836): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_6030/cgroup.procs: No such file or directory
,D/ResourcesManager( 6780): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/GroupCast_FileTools( 6836): [getDirectoryForImageResized : 295] cleaning!!
,W/System.err( 6836): android.content.pm.PackageManager$NameNotFoundException: com.sec.android.app.ma.recorder
,W/System.err( 6836): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:302)
W/System.err( 6836): 	at com.samsung.groupcast.application.App.preLoadGroupCamcoderCheck(App.java:339)
W/System.err( 6836): 	at com.samsung.groupcast.application.App.onCreate(App.java:146)
W/System.err( 6836): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 6836): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 6836): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 6836): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 6836): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6836): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 6836): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 6836): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6836): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6836): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 6836): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6852): MountEmulatedStorage()
E/Zygote  ( 6852): v2
I/libpersona( 6852): KNOX_SDCARD checking this for 1000
I/libpersona( 6852): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6852 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 5813:com.sec.android.provider.badge/u0a78 (adj 15): bgCount ##41
,I/art     (  311): Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 11.050ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 256us total 8.098ms
,I/SELinux ( 6852): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6852): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6852): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 299us total 11.196ms
,I/ActivityManager(  886): Killing 6082:com.wsomacp/u0a25 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 6852): TimaSignature is unavailable
,D/ActivityThread( 6852): Added TimaKeyStore provider
,W/libprocessgroup(  886): failed to open /acct/uid_10078/pid_5813/cgroup.procs: No such file or directory
,D/ResourcesManager( 6780): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 6852): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,V/Finsky  ( 6740): [1] GearheadStateMonitor.onReady: sIsProjecting:false
,I/PCWCLIENTTRACE_LOG( 6852): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 6852): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 6852): new DMDBOpenHelper instance
,W/libprocessgroup(  886): failed to open /acct/uid_10025/pid_6082/cgroup.procs: No such file or directory
,I/PCWCLIENTTRACE_PushUtil( 6852): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6852): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6852): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6852): [onReceive] - android.intent.action.PACKAGE_ADDED
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6870): MountEmulatedStorage()
I/libpersona( 6870): KNOX_SDCARD checking this for 1000
E/Zygote  ( 6870): v2
I/libpersona( 6870): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=6870 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6182:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,I/SELinux ( 6870): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6870): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6870): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6870): TimaSignature is unavailable
,D/ActivityThread( 6870): Added TimaKeyStore provider
,W/libprocessgroup(  886): failed to open /acct/uid_10002/pid_6182/cgroup.procs: No such file or directory
,D/ResourcesManager( 6870): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6890): MountEmulatedStorage()
E/Zygote  ( 6890): v2
I/libpersona( 6890): KNOX_SDCARD checking this for 10045
I/libpersona( 6890): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=6890 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6227:com.sec.smartcard.manager/u0a172 (adj 15): bgCount ##41
,I/SELinux ( 6890): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6890): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6890): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  886): failed to open /acct/uid_10172/pid_6227/cgroup.procs: No such file or directory
,D/TimaKeyStoreProvider( 6890): TimaSignature is unavailable
,D/ActivityThread( 6890): Added TimaKeyStore provider
,D/ResourcesManager( 6890): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SA      ( 6890): [SSP] onCreated
,I/SA      ( 6890): [TPM] There is no property file
,I/SA      ( 6890): [SCU] isHaveSA() - false
,I/SA      ( 6890): [TPM] getModelProperty : null
I/SA      ( 6890): [TPM] getCSCProperty : null
,I/SA      ( 6890): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 6890): [DM] init START
,I/SA      ( 6890): [DM] This device is not a Vodafone
,W/ResourceType( 6890): Failure getting entry for 0x7f06000f (t=5 e=15) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 6890): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 6890): Failure getting entry for 0x7f060001 (t=5 e=1) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f060013 (t=5 e=19) (error -75)
,W/ResourceType( 6890): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6890): Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
W/ResourceType( 6890): Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f060024 (t=5 e=36) (error -75)
W/ResourceType( 6890): Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 6890): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 6890): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 6890): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 6890): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 6890): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
W/ResourceType( 6890): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,I/SA      ( 6890): [SCU] isHaveSA() - false
I/SA      ( 6890): support phone number id : false
,I/SA      ( 6890): [DM] init END
,I/SA      ( 6890): [SUR] onReceive log=[SA = 2.1.0142 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = DBT MCC = 0 MNC 0 T = user DEVICE = klte P = kltexx I = LRX21T M = SM-G900F OKLEFT false DIS LRX21T.G900FXXU1BOD3 PSS = 5.219788042639568  ]
,I/SA      ( 6890): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10200 extra.user_handle.:0 ]
,I/ActivityManager(  886): Killing 6049:com.android.mms/u0a50 (adj 15): bgCount ##41
,D/CountryDetector(  886): No listener is left
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup(  886): failed to open /acct/uid_10050/pid_6049/cgroup.procs: No such file or directory
,E/Zygote  ( 6915): MountEmulatedStorage()
I/libpersona( 6915): KNOX_SDCARD checking this for 10050
E/Zygote  ( 6915): v2
I/libpersona( 6915): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageReceiver: pid=6915 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 6915): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6915): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6915): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6915): TimaSignature is unavailable
,D/ActivityThread( 6915): Added TimaKeyStore provider
,D/ResourcesManager( 6915): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 6915): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 6915): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6915): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 6915): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6915): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/Mms/MmsApp( 6915): [start]    onCreate() consume time = 0.0
,D/Mms/TelephonyPermission( 6915): start operation mode monitor
,D/ResourcesManager( 6915): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,V/AlarmManager(  886): waitForAlarm result :4
,W/ResourcesManager( 6915): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Finsky  ( 6740): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Mms/TelephonyPermission( 6915): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 6915): isDefault true
,D/Mms/MmsApp( 6915): onCreate() com.android.mms
,D/Mms/MmsConfig( 6915): [start]    MmsConfig.init() consume time = 39.793021
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/MmsConfig( 6915): before partial update
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  886): level:100, scale:100, status:2, health:2, present:true, voltage: 4268, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for charging
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/Mms/MmsConfig( 6915): Load Resize quality : 80
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/ActivityThread( 6915): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
D/EasySignUpManager( 6915): serviceId : 1, features : -1
D/Mms/MmsConfig( 6915): setFreeMessageEnabled, free message policy(getSupportedFeatures) is = -1
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TP/MmsSmsProvider( 1478): query,matched:2117, calling pid = 6915
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/art     (  886): Explicit concurrent mark sweep GC freed 226376(14MB) AllocSpace objects, 7(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.276ms total 131.117ms
,D/TP/MmsSmsProvider( 1478): match 2117:Elapsed time : 126.997 ms
,W/Finsky  ( 6740): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/ActivityThread( 6915): Failed to find provider info for com.samsung.android.coreapps.easysignup.public
,D/EasySignUpManager( 6915): serviceId : 3, features : -1
D/Mms/MmsConfig( 6915): Shop agent feature value :-1
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/MmsConfig( 6915):  enable multiwindow = true
,E/Mms/MessageUtils( 6915): setCountryDetector : update country detector info 
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/Mms/MessageUtils( 6915): updateCountryIso : update country iso info 
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/MmsConfig( 6915): [end]    init() consume time = 239.84401
D/Mms/MmsApp( 6915): [start]    initCountryIso consume time = 0.063958
,D/CountryDetector(  886): The first listener is added
,D/Mms/MmsApp( 6915): [end]    initCountryIso consume time = 5.821876
,D/Mms/Contact( 6915): [start]    init() consume time = 1.537604
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_list_thumbnail.pkm
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,D/TP/MmsSmsProvider( 1478): query,matched:13, calling pid = 6915
,D/TP/MmsSmsProvider( 1478): match 13:Elapsed time : 0.677 ms
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/Mms/Contact( 6915): [end]    init consume time = 14.905572
,D/Mms/DraftCache( 6915): [start]    rebuildCache consume time = 2.099688
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/TP/MmsSmsProvider( 1478): query,matched:12, calling pid = 6915
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/TP/MmsSmsProvider( 1478): match 12:Elapsed time : 0.614 ms
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/Mms/Conversation( 6915): [start]    init() consume time = 5.330729
,D/TP/MmsSmsProvider( 1478): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1478): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/Search.LoginHelper( 1574): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/Mms/DraftCache( 6915): [end]    rebuildCache consume time = 10.044427
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,D/TP/MmsSmsProvider( 1478): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1478): need read changed broadcast:false
,D/Mms/Conversation( 6915): [end]    init consume time = 3.541667
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/TelephonyUtils( 6915): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager( 6915): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6915): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6915): auto download without roaming -> true
D/Mms/DownloadManager( 6915): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
E/Mms/TelephonyUtils( 6915): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 6915): getSubId from simSlot 1, return Value = -1000
D/Mms/DownloadManager( 6915): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 6915): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 6915): auto download without roaming -> true
D/Mms/DownloadManager( 6915): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 6915): auto download during roaming secondary -> false
D/Mms/DownloadManager( 6915): mAutoDownload ------> true
,D/Mms/MessagingNotification( 6915): [start]    init() consume time = 7.452604
,D/Mms/MessagingNotification( 6915): [end]    init consume time = 1.059635
,D/Mms/SpamFilter( 6915): [start]    SpamFilter fill() begin consume time = 1.268282
,D/TP/MmsSmsProvider( 1478): query,matched:400, calling pid = 6915
,D/Mms/ComposeMessageFragment( 6915): [start]    fillCache consume time = 2.27849
,D/Mms/ComposeMessageFragment( 6915): fillCache, easy = false
,D/Mms/SpamFilter( 6915): [end]    SpamFilter fill() finished consume time = 2.696822
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,W/Finsky  ( 6740): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_add.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_contacts.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template_left.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_emotion_off.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_recieved_check_msg.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_icon_title_read_check_msg.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/messages_btn_send.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_attach_small.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/message_btn_template.pkm
,D/AbsListView( 6915): Get MotionRecognitionManager
,D/MotionRecognitionService(  886):  ssp status : true
,D/Mms/ComposeMessageFragment( 6915): [end]    fillCache consume time = 89.499323
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_contact_picture.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/sms_msg_bt.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_priority_vzw_2.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/msg_bubble_icon_locked.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate1.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate2.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xhdpi-v4/progressbar_indeterminate3.png
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_translator_normal.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_press.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_focus.pkm
,V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_disable.pkm
V/BitmapFactory( 6915): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/icon_failed_normal.pkm
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6740): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6740): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6740): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6740): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
,D/Mms/BubbleViewCache( 6915): fillCache bubble = 8
,D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 6915
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 0.675 ms
,D/Mms/Synchronizer( 6915): [start]    doSync consume time = 267.089792
,D/TP/MmsSmsProvider( 1478): update uri: content://mms-sms/db_synchronization
,V/TP/MmsSmsProvider( 1478): syncDBData start
,V/TP/MmsSmsProvider( 1478): syncDBData sms end
,V/TP/MmsSmsProvider( 1478): syncDBData mms end
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
V/TP/MmsSmsProvider( 1478): syncDBData end
,I/art     ( 2272): Explicit concurrent mark sweep GC freed 26025(1511KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 18MB/30MB, paused 446us total 31.903ms
,D/DeviceConnectionService( 2272): client connected with version: 7571000
,I/ActivityManager(  886): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=6951 uid=10078 gids={50078, 9997} abi=armeabi-v7a
,D/Mms/Synchronizer( 6915): [end]    doSync consume time = 15.6875
,E/Zygote  ( 6951): MountEmulatedStorage()
E/Zygote  ( 6951): v2
I/libpersona( 6951): KNOX_SDCARD checking this for 10078
I/libpersona( 6951): KNOX_SDCARD not a persona
,I/FaceInterface( 6165): startFaceScan() : going on
D/FaceInterface( 6165): startFaceScan() is called.
,I/SELinux ( 6951): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6951): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6951): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ContentApp( 1226): startScan() is called.
,D/ContentApp( 1226): startScan() is end.
,D/ContentApp( 1226): face_restore FINISHED_TYPE: 3
D/FaceScanner( 1226): isNeedToRestore : start
,D/TimaKeyStoreProvider( 6951): TimaSignature is unavailable
,D/ActivityThread( 6951): Added TimaKeyStore provider
,D/ResourcesManager( 6951): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider( 6951): onCreate
,D/BadgeProvider( 6951): DatabaseHelper
,I/art     ( 1226): Explicit concurrent mark sweep GC freed 8401(529KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 14MB/19MB, paused 354us total 35.417ms
,D/Mms/MessagingNotification( 6915): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1478): query,matched:26, calling pid = 6915
,D/TP/SmsProvider( 1478): match 26:Elapsed time : 0.992 ms
,D/TP/MmsSmsProvider( 1478): query,matched:6, calling pid = 6915
,D/TP/MmsSmsProvider( 1478): match 6:Elapsed time : 0.827 ms
,I/Mms/ReservationManager( 6915): ReservationManager()
,I/Mms/ReservationManager( 6915): resetAfterConnected()
,D/TP/MmsSmsProvider( 1478): query,matched:7, calling pid = 6915
,D/TP/MmsSmsProvider( 1478): match 7:Elapsed time : 1.771 ms
,I/Mms/ReservationManager( 6915): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 6975): MountEmulatedStorage()
E/Zygote  ( 6975): v2
I/libpersona( 6975): KNOX_SDCARD checking this for 10025
I/libpersona( 6975): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6975 uid=10025 gids={50025, 9997} abi=armeabi-v7a
,I/SELinux ( 6975): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6975): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6975): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 6975): TimaSignature is unavailable
,D/ActivityThread( 6975): Added TimaKeyStore provider
,D/ResourcesManager( 6975): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager( 6975): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Mms/Omacp( 6915): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/MmsApp( 6915): [end]    onCreate() consume time = 236.197552
,D/Mms/PerformanceUtils( 6915): link cahcing start
,D/Mms/FreeMessageReceiver( 6915): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/Mms/DownloadManager( 6915): Service state changed: Bundle[mParcelledData.dataSize=692]
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/Mms/DownloadManager( 6915): roaming ------> false, mSimSlot = 0
,D/Mms/TelephonyUtils( 6915): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager( 6915): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 6915): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 6915): auto download without roaming -> true
D/Mms/DownloadManager( 6915): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 6915): mAutoDownload ------> true
,E/Zygote  ( 6991): MountEmulatedStorage()
I/libpersona( 6991): KNOX_SDCARD checking this for 10051
E/Zygote  ( 6991): v2
I/libpersona( 6991): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6991 uid=10051 gids={50051, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6290:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/Mms/PerformanceUtils( 6915): link cahcing done
,I/SELinux ( 6991): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 6991): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 6991): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  886): Killing 6306:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,D/Mms/FreeMessageReceiverService( 6915): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
,D/Mms/FreeMessageReceiverService( 6915): onHandleIntent: ACTION_PACKAGE_ADDED
,D/TimaKeyStoreProvider( 6991): TimaSignature is unavailable
,D/ActivityThread( 6991): Added TimaKeyStore provider
,I/ActivityManager(  886): Killing 5133:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
,D/ResourcesManager( 6991): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 6991): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 6991): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup(  886): failed to open /acct/uid_10094/pid_6290/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10103/pid_6306/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10113/pid_5133/cgroup.procs: No such file or directory
,D/MyFiles ( 6991): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,E/installd(  294): system dir 0 : /system/app/
E/installd(  294): system dir 1 : /system/priv-app/
E/installd(  294): system dir 2 : /vendor/app/
E/installd(  294): system dir 3 : /oem/app/
,I/TactileAssist(  886): enable value -1
I/TactileAssist(  886): internal enable value -1
I/TactileAssist(  886): intensity value -1
I/TactileAssist(  886): saveAppList value true
,I/TactileAssist(  886): List of disabled apps :
I/TactileAssist(  886): de.zalando.mobile
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/PackageManager(  886): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,E/Zygote  ( 7009): MountEmulatedStorage()
,E/Zygote  ( 7009): v2
I/libpersona( 7009): KNOX_SDCARD checking this for 10058
I/libpersona( 7009): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7009 uid=10058 gids={50058, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 7009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7009): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/AlarmManager(  886): waitForAlarm result :4
,D/TimaKeyStoreProvider( 7009): TimaSignature is unavailable
,D/ActivityThread( 7009): Added TimaKeyStore provider
,D/ResourcesManager( 7009): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 7009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/Compatibility( 7009): onReceive() it will make start service
,D/Compatibility( 7009): onHandleIntent()
,D/Compatibility( 7009): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10200, android.intent.extra.user_handle=0}]
,D/Compatibility( 7009): found: 2
,I/UpdateIcingCorporaServi( 1574): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 7009): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 7009): skipping ResolveInfo{216b7e22 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 7009): considering ResolveInfo{2b7f40b3 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 7009): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 7009): enabling receiver ResolveInfo{8574670 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,W/ContextImpl( 6339): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2945 
,D/Compatibility( 7009): enabling receiver ResolveInfo{f3f4de9 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7009): enabling receiver ResolveInfo{32e75a6e com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 7009): enabling receiver ResolveInfo{923350f com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 7009): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7029): MountEmulatedStorage()
E/Zygote  ( 7029): v2
I/libpersona( 7029): KNOX_SDCARD checking this for 10098
I/libpersona( 7029): KNOX_SDCARD not a persona
,D/ResourcesManager( 1574): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/ActivityManager(  886): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7029 uid=10098 gids={50098, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  886): Killing 5745:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,I/UpdateIcingCorporaServi( 1574): UpdateCorporaTask done [took 65 ms] updated apps [took 64 ms] 
,I/SELinux ( 7029): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7029): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7029): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7029): TimaSignature is unavailable
,D/ActivityThread( 7029): Added TimaKeyStore provider
,W/libprocessgroup(  886): failed to open /acct/uid_10154/pid_5745/cgroup.procs: No such file or directory
,D/ResourcesManager( 7029): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/DocsApplication( 7029): Installing DEX configuration.
,D/DexInstaller( 7029): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PackageInfoHelper( 7029): Provided clientMode=RELEASE, packageInfo=PackageInfo{1b3b9fed com.google.android.apps.docs}
,D/TAG     ( 7029): onCreate()
,D/CrossAppStateProvider( 7029): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,I/wpa_supplicant( 1260): nl80211: Received scan results (18 BSSes)
,E/WifiStateMachine(  886): [1,456,920,174,987 ms] noteScanEnd no scan source
,D/WifiP2pService(  886): InactiveState{ what=147461 }
,D/WifiP2pService(  886): P2pEnabledState{ what=147461 }
D/WifiP2pService(  886): DefaultState{ what=147461 }
,E/WifiStateMachine(  886): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@185d4f83 sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  886): External Intent Received android.net.wifi.SCAN_RESULTS
,E/SMD     (  285): DCD ON
,I/CheckinService( 2457): Done disabling old GoogleServicesFramework version
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7054): MountEmulatedStorage()
,E/Zygote  ( 7054): v2
I/libpersona( 7054): KNOX_SDCARD checking this for 10099
I/libpersona( 7054): KNOX_SDCARD not a persona
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  886): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/.framework.manager.update.UpdateManagerReceiver: pid=7054 uid=10099 gids={50099, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
I/ActivityManager(  886): Killing 5906:com.sec.android.widgetapp.SPlannerAppWidget/u0a149 (adj 15): bgCount ##41
,I/SELinux ( 7054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/GAV2    ( 7029): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/TimaKeyStoreProvider( 7054): TimaSignature is unavailable
,D/ActivityThread( 7054): Added TimaKeyStore provider
,W/libprocessgroup(  886): failed to open /acct/uid_10149/pid_5906/cgroup.procs: No such file or directory
,D/ResourcesManager( 7054): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 7054): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/[CarMode]( 7054): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 7054): SampleAppCoreManager VACVersion '2.2.0.11867'
,I/VlingoAndroidCore( 7054): AppName: SamsungCCKProject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7079): MountEmulatedStorage()
,E/Zygote  ( 7079): v2
I/libpersona( 7079): KNOX_SDCARD checking this for 10033
I/libpersona( 7079): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=7079 uid=10033 gids={50033, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 7079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7079): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7079): TimaSignature is unavailable
,D/ActivityThread( 7079): Added TimaKeyStore provider
,D/ResourcesManager( 7079): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 7079): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/GAV2    ( 7029): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,V/AlarmManager(  886): waitForAlarm result :4
,I/System.out( 7079): Inside onCreate() of WakeupTriggerProvide
,I/System.out( 7079): Inside WakeupProvider
,E/DatabaseUtils( 7079): Writing exception to parcel
E/DatabaseUtils( 7079): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7079): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7079): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7079): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7079): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7079): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7079): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7079): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7079): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7079): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7079): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7054): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7054): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7054): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 7054): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7054): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7054): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 7054): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7054): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7054): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7054): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 7054): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 7054): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 7054): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 7054): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:108)
W/System.err( 7054): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:206)
W/System.err( 7054): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7054): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7054): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
W/System.err( 7054): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
W/System.err( 7054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7054): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7054): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7054): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7054): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/VlingoApplication( 7079): VlingoApplication appVersion ='11.7.0.0.37633', coreVersion = '2.5.0.13002', ro.csc.sales_code=DBT
,E/DatabaseUtils( 7079): Writing exception to parcel
E/DatabaseUtils( 7079): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 7079): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 7079): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 7079): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1520)
E/DatabaseUtils( 7079): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 7079): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 7079): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 7079): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/DatabaseUtils( 7079): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/DatabaseUtils( 7079): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 7079): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 7054): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 7054): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 7054): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
,W/System.err( 7054): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 7054): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 7054): 	at android.content.ContentResolver.query(ContentResolver.java:484)
,W/System.err( 7054): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 7054): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 7054): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 7054): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
,W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
,W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 7054): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 7054): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
,W/System.err( 7054): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:251)
W/System.err( 7054): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:72)
W/System.err( 7054): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 7054): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5007)
,W/System.err( 7054): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err( 7054): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
,W/System.err( 7054): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7054): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 7054): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 7054): 	at java.lang.reflect.Method.invoke(Native Method)
,W/System.err( 7054): 	at java.lang.reflect.Method.invoke(Method.java:372)
,W/System.err( 7054): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 7054): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/[CarMode]( 7054): [DLApplication]-Init Called!:false
,E/[CarMode]( 7054): [DLApplication]-Init Started!:true
,I/[CarModeFW]( 7054): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 7054): ### com.sec.android.automotive.drivelink.framework.DriveLinkServiceInterfaceImp::initialize(142)
I/[CarModeFW]( 7054): ### com.sec.android.automotive.drivelink.DLApplication::init(145)
I/[CarModeFW]( 7054): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(73)
I/[CarModeFW]( 7054): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 7054): ### android.app.ActivityThread::handleBindApplication(5007)
I/[CarModeFW]( 7054): ### android.app.ActivityThread::access$1600(172)
I/[CarModeFW]( 7054): ### android.app.ActivityThread$H::handleMessage(1483)
I/[CarModeFW]( 7054): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 7054): ### android.os.Looper::loop(145)
I/[CarModeFW]( 7054): ### android.app.ActivityThread::main(5832)
I/[CarModeFW]( 7054): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 7054): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 7054): ### com.android.internal.os.ZygoteInit::main(1194)
,I/VlingoAndroidCore( 7079): AppName: SamsungTproject, Core: 2.5.0.13002, SDK: 2.0.1111, EDM:13002
,I/MessageDataHandler( 7054): initialize
,D/[CarModeFW]( 7054): CDH-initiazlieCaches : before sync
,D/[CarModeFW]( 7054): CDH-initiazlieCaches : after sync
,D/[CarModeFW]( 7054): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 7054): DrivingManager-initialize...
,I/SensorService(  886): Skipped sensor HRM Sensor because it requires permission com.samsung.permission.SSENSOR
,I/SensorService(  886): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
I/SensorService(  886): Skipped sensor MAX86900 because it requires permission com.samsung.permission.SSENSOR
,D/[CarModeFW]( 7054): CDH-ContactDataHandler initiazlieCaches time : 43
D/[CarModeFW]( 7054): CDH-initiazlieCaches : end sync
,D/VlingoApplication( 7079): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 7079): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/MediaPlayer( 7054): Need to enable context aware info
V/MediaPlayer-JNI( 7054): native_setup
V/MediaPlayer( 7054): constructor
,V/MediaPlayer( 7054): setListener
,E/MediaPlayer-JNI( 7054): QCMediaPlayer mediaplayer NOT present
,D/[CarModeFW]( 7054): PushMessageManager-bindPushMessageService
,I/[CarModeFW]( 7054): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 7054): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarMode]( 7054): [DLServiceManager]-requestRecommendedLocationList
,D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => start time : 1456920176285
,D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => start time : 1456920176286
D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => start time : 1456920176286
D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => start time : 1456920176286
,D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => start time : 1456920176286
D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => start time : 1456920176286
,D/TP/SmsProvider( 1478): query,matched:2, calling pid = 7054
,D/TP/SmsProvider( 1478): match 2:Elapsed time : 1.196 ms
,I/[CarMode]( 7054): [LogNotNull]-Package name is: com.google.android.apps.maps
,E/[CarMode]( 7054): [DLApplication]-Init End!:true
,D/TP/SmsProvider( 1478): query,matched:2, calling pid = 7054
,D/MessageDataHandler( 7054):  getInboxList smsCursor : 16
,D/TP/SmsProvider( 1478): match 2:Elapsed time : 1.634 ms
,D/[CarModeFW]( 7054): CDH-buildContactCacheWireFrame : cur len =0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
D/TP/MmsProvider( 1478): Query uri=content://mms/inbox, match=2, calling pid = 7054
,E/Zygote  ( 7123): MountEmulatedStorage()
E/Zygote  ( 7123): v2
I/libpersona( 7123): KNOX_SDCARD checking this for 10003
I/libpersona( 7123): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=7123 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 279us total 10.822ms
,I/SELinux ( 7123): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 7.736ms
I/SELinux ( 7123): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/[CarModeFW]( 7054): RecommendHandler-selection = type = '3'
E/SELinux ( 7123): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/MessageDataHandler( 7054):  getInboxList mmsCursor : 40
,D/[CarMode]( 7054): [DLApplication]-GooglePlayServices SUCCESS.
,D/TP/MmsProvider( 1478): Query uri=content://mms, match=0, calling pid = 7054
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 242us total 8.181ms
,D/[CarModeFW]( 7054): CDH-buildContactCacheWireFrame : cur len =0
,D/MessageDataHandler( 7054):  getInboxList mms,sms cursor join : 13
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 7123): TimaSignature is unavailable
,D/ActivityThread( 7123): Added TimaKeyStore provider
,E/Zygote  ( 7138): MountEmulatedStorage()
E/Zygote  ( 7138): v2
I/libpersona( 7138): KNOX_SDCARD checking this for 10020
I/libpersona( 7138): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.provider.logsprovider for content provider com.sec.android.provider.logsprovider/.LogsProvider: pid=7138 uid=10020 gids={50020, 9997, 3003, 1028, 1015, 3002, 1023} abi=armeabi-v7a
,D/[CarModeFW]( 7054): RecommendHandler-selection = type = '3'
,E/[CarMode]( 7054): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,I/UpdateManagerReceiver( 7054): Intent : android.intent.action.PACKAGE_ADDEDWed Mar 02 13:02:56 GMT+01:00 2016
,I/SELinux ( 7138): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7138): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 7054
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
E/SELinux ( 7138): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 3.084 ms
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/MessageDataHandler( 7054): getUnreadMessageCount :0
,D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestUnreadMessageCount => execute time : 112
,E/Zygote  ( 7149): MountEmulatedStorage()
E/Zygote  ( 7149): v2
I/libpersona( 7149): KNOX_SDCARD checking this for 1000
I/libpersona( 7149): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7149 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 7149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  886): Killing 5721:com.android.calendar/u0a150 (adj 15): bgCount ##41
I/SELinux ( 7149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7149): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 7138): TimaSignature is unavailable
,D/ActivityThread( 7138): Added TimaKeyStore provider
,D/ResourcesManager( 7123): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/[CarModeFW]( 7054): CDH-buildContactCacheWireFrame : cur len =0
,D/TP/MmsSmsProvider( 1478): query,matched:13, calling pid = 7054
,D/[CarModeFW]( 7054): PushMessageService-onCreate
,I/ActivityManager(  886): Killing 6444:com.sec.spp.push:RemoteDlcProcess/u0a38 (adj 15): bgCount ##41
,I/ActivityManager(  886): Killing 6423:com.sec.android.app.popupuireceiver/1000 (adj 15): bgCount ##42
,D/TP/MmsSmsProvider( 1478): match 13:Elapsed time : 4.973 ms
I/ActivityManager(  886): Killing 6364:com.sec.android.app.sns3/u0a36 (adj 15): bgCount ##43
,D/TimaKeyStoreProvider( 7149): TimaSignature is unavailable
,D/ActivityThread( 7149): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 7123): PlaceProvider onCreate()
,D/[CarModeFW]( 7054): PushMessageManager-onServiceConnected
D/[CarModeFW]( 7054): PushMessageService-registerPushMessageServiceListener
,D/UserAnalysis.SecureDbManager( 7123): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 7123): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 7123): Create SecureDbHelper
,I/art     (  886): Explicit concurrent mark sweep GC freed 26127(1459KB) AllocSpace objects, 1(81KB) LOS objects, 30% free, 36MB/52MB, paused 1.400ms total 93.959ms
,D/MessageDataHandler( 7054):  getInboxList address cursor : 115
,D/IntelligenceServiceApplication( 7123): onCreate()
,D/TP/MmsSmsProvider( 1478): query,matched:0, calling pid = 7054
V/TP/MmsSmsProvider( 1478): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1478): match 0:Elapsed time : 0.777 ms
,D/MessageDataHandler( 7054):  getInboxList thread cursor : 4
,D/MessageDataHandler( 7054):  thread, addr result: 1
I/[CarModeFW]( 7054): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxList() : 289
I/[CarModeFW]( 7054): ContentManager-com.sec.android.automotive.drivelink.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestInboxList => execute time : 289
,D/ResourcesManager( 7149): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/ResourcesManager( 7138): creating new AssetManager and set to /system/priv-app/LogsProvider/LogsProvider.apk
,I/SQLiteSecureOpenHelper( 7123): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 7123): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 7123): Open Place.db in secure mode
,W/ContextImpl( 7149): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2945 
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7149): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/Zygote  ( 7170): MountEmulatedStorage()
E/Zygote  ( 7170): v2
I/libpersona( 7170): KNOX_SDCARD checking this for 10112
I/libpersona( 7170): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7170 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SQLiteSecureOpenHelper( 7123): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 7123): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 7170): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/FilterInstaller( 7149): There is no requred permission
,I/SELinux ( 7170): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7170): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/PowerManagerService(  886): [PWL] Off : 5s ago
I/PowerManagerService(  886): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  886): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2457, ws=null) (elapsedTime=21646)
I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=886, ws=WorkSource{1000}) (elapsedTime=2038)
I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=368)
I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=366)
,I/ActivityManager(  886): Killing 6469:com.sec.spp.push:RemoteNotiProcess/u0a38 (adj 15): bgCount ##41
,D/[CarModeFW]( 7054): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 7054): MyPlaceProvider-=============
,D/[CarModeFW]( 7054): MyPlaceProvider-=============
D/[CarModeFW]( 7054): MyPlaceProvider-=============
D/[CarModeFW]( 7054): MyPlaceProvider-=============
D/[CarModeFW]( 7054): MyPlaceProvider----End print all data in content provider---
,D/[CarModeFW]( 7054): MyPlaceProvider-==============
D/[CarModeFW]( 7054): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7054): MyPlaceProvider-==============
,D/[CarModeFW]( 7054): MyPlaceProvider-latitude is not valid
D/[CarModeFW]( 7054): MyPlaceProvider-==============
D/[CarModeFW]( 7054): MyPlaceProvider-latitude is not valid
,D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedLocationList => execute time : 353
,D/TimaKeyStoreProvider( 7170): TimaSignature is unavailable
,D/[CarMode]( 7054): [DLServiceManager]-[LOADINGLIST] Loading list[com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@d00a4481, com.sec.android.automotive.drivelink.framework.manager.content.location.DLLocationMyPlace@6397bce3] LOCATIONS
D/ActivityThread( 7170): Added TimaKeyStore provider
,D/ResourcesManager( 7170): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestCallLogList => execute time : 382
,I/[CarModeFW]( 7054): -[snowdeer] Rec : Missed Call : 330
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
I/[CarModeFW]( 7054): -[snowdeer] Rec : Favorite : 7
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/libprocessgroup(  886): failed to open /acct/uid_10150/pid_5721/cgroup.procs: No such file or directory
W/libprocessgroup(  886): failed to open /acct/uid_10036/pid_6364/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_6423/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10038/pid_6444/cgroup.procs: No such file or directory
,I/[CarModeFW]( 7054): -[snowdeer] Rec : CallLog : 7
,I/[CarModeFW]( 7054): -[snowdeer] Rec : getContactListFromHashMap - core : 0
,I/[CarModeFW]( 7054): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
I/[CarModeFW]( 7054): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForMessage => execute time : 414
I/[CarModeFW]( 7054): -[snowdeer] Rec : Schedule : 16
,I/[CarModeFW]( 7054): -[snowdeer] Rec : During DL app : 1
,D/PackageIntentReceiver( 7170): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 7170): Not GearManger package! 
,I/[CarModeFW]( 7054): -[snowdeer] Rec : Location Sharing : 1
I/[CarModeFW]( 7054): -[snowdeer] Rec : POI : 0
,I/[CarModeFW]( 7054): -[snowdeer] Rec : getContactListFromHashMap - core : 0
I/[CarModeFW]( 7054): -[snowdeer] Rec : getContactListFromHashMap - duplicated : 0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/[CarModeFW]( 7054): -[snowdeer] Rec : getContactListFromHashMap - rescan[New] : 0
,I/[CarModeFW]( 7054): -[snowdeer] Rec : getContactListFromHashMap : 1
D/[CarModeFW]( 7054): Framework-Request-com.sec.android.automotive.drivelink.framework.command.RequestRecommendedContactListForCall => execute time : 419
,W/libprocessgroup(  886): failed to open /acct/uid_10038/pid_6469/cgroup.procs: No such file or directory
,E/Zygote  ( 7186): MountEmulatedStorage()
,E/Zygote  ( 7186): v2
I/libpersona( 7186): KNOX_SDCARD checking this for 10118
I/libpersona( 7186): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.magazine.service for broadcast com.samsung.android.app.headlines/com.samsung.android.magazine.service.MagazineBroadcastReceiver: pid=7186 uid=10118 gids={50118, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 4745:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,I/SELinux ( 7186): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7186): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7186): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7186): TimaSignature is unavailable
,D/ActivityThread( 7186): Added TimaKeyStore provider
,D/ResourcesManager( 7186): creating new AssetManager and set to /system/app/Headlines/Headlines.apk
,W/ResourcesManager( 7186): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup(  886): failed to open /acct/uid_10046/pid_4745/cgroup.procs: No such file or directory
,D/MagazineService Version( 7186): Magazine-Administrator: 11
,D/MagazineService Version( 7186): Magazine-Provider: 14
,D/MagazineService Version( 7186): Magazine-Channel: 14
,D/HeadlinesChannelApplication( 7186): [onCreate]
,D/MagazineService::MagazineBroadcastReceiver( 7186): [onReceive] android.intent.action.PACKAGE_ADDED com.test.thalitest
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,I/MagazineService::MagazineService( 7186): [onHandleIntent] ACTION_PACKAGE_INSTALLED
,E/Zygote  ( 7202): MountEmulatedStorage()
,E/Zygote  ( 7202): v2
I/libpersona( 7202): KNOX_SDCARD checking this for 1000
I/libpersona( 7202): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7202 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MagazineService::MagazineService( 7186): [onHandleIntent] Send broadcast to (com.test.thalitest).
,I/SELinux ( 7202): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7202): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7202): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  886): Killing 6507:com.sec.android.diagmonagent/1000 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 7202): TimaSignature is unavailable
,D/ActivityThread( 7202): Added TimaKeyStore provider
,D/ResourcesManager( 7202): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7217): MountEmulatedStorage()
E/Zygote  ( 7217): v2
I/libpersona( 7217): KNOX_SDCARD checking this for 1000
I/libpersona( 7217): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7217 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 5995:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_6507/cgroup.procs: No such file or directory
I/SELinux ( 7217): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7217): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7217): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7217): TimaSignature is unavailable
,D/ActivityThread( 7217): Added TimaKeyStore provider
,D/ResourcesManager( 7217): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_5995/cgroup.procs: No such file or directory
,I/System.out( 7079): INFO:Resource not found:/Common.properties Using default values
,D/AcmsPackageEventListener( 7217): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl( 7217): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,D/AcmsService( 7217): Enter Oncreate
,D/AcmsServiceMonitor( 7217): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService( 7217): creating AcmsCore
D/AcmsCore( 7217): AcmsCore.getAcmsCore() - Enter
D/AcmsCore( 7217): AcmsCore
,D/AcmsCore( 7217): init
,D/AcmsCore( 7217): Looper handler is not null
D/AcmsCore( 7217): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7217): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7217): Incrementing - Counter value: 1
,D/AcmsCore( 7217): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsCertificateMngr( 7217): AcmsCertificateMngr
,D/AcmsRevocationMngr( 7217): AcmsRevocationMngr
,D/ActivityThread( 7217): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AcmsService( 7217): onStartCommand
D/AcmsService( 7217): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor( 7217): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor( 7217): Incrementing - Counter value: 2
,D/AcmsService( 7217): Incremented Counter Value : onStartCommand
,D/AcmsService( 7217): Inside handle Intent
D/AcmsService( 7217): App added - package name: com.test.thalitest
D/AcmsCore( 7217): Post to AcmsCoreHandler
D/AcmsServiceMonitor( 7217): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7217): Incrementing - Counter value: 3
D/AcmsCore( 7217): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService( 7217): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor( 7217): Decrementing - Counter value: 2
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7237): MountEmulatedStorage()
E/Zygote  ( 7237): v2
I/libpersona( 7237): KNOX_SDCARD checking this for 10166
I/libpersona( 7237): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.kidsplat.installer for broadcast com.sec.kidsplat.installer/.KidsModeInstallReceiver: pid=7237 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7237): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7237): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7237): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7237): TimaSignature is unavailable
,D/ActivityThread( 7237): Added TimaKeyStore provider
,D/ResourcesManager( 7237): creating new AssetManager and set to /system/app/SecKidsModeInstaller/SecKidsModeInstaller.apk
,W/ResourcesManager( 7237): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/KidsPlatformStub( 7237): Package not found : com.sec.android.app.kidshome
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7252): MountEmulatedStorage()
,E/Zygote  ( 7252): v2
I/libpersona( 7252): KNOX_SDCARD checking this for 10170
I/libpersona( 7252): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7252 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6015:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,I/SELinux ( 7252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7252): TimaSignature is unavailable
,D/ActivityThread( 7252): Added TimaKeyStore provider
,D/ResourcesManager( 7252): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,W/libprocessgroup(  886): failed to open /acct/uid_10158/pid_6015/cgroup.procs: No such file or directory
,E/SQLiteLog( 7252): (284) automatic index on shooting_modes(title_id)
,I/ActivityManager(  886): Killing 6324:com.sec.providers.settingsearch/u0a168 (adj 15): bgCount ##41
,D/PackageBroadcastService( 2457): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 2457): Loading module com.google.android.gms.games from APK com.google.android.gms
,D/ChimeraCfgMgr( 2457): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/Vision  ( 2457): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
,D/Vision  ( 2457): Failed to find package metadata for com.test.thalitest
,D/Vision  ( 2457): No vision deps
I/ConfigFetchService( 2457): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,I/ConfigFetchService( 2457): launchTask
,D/ResourcesManager( 2457): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,E/Zygote  ( 7270): MountEmulatedStorage()
I/libpersona( 7270): KNOX_SDCARD checking this for 10040
E/Zygote  ( 7270): v2
I/libpersona( 7270): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7270 uid=10040 gids={50040, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,V/ConfigFetchTask( 2457): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WcniZpQ_JrGHGvHfHMp4PZBHHKxjP2AxRF573XnZddoY0zqQH4dIOwHpcvoXWkKWWGj_-LW0pKFV2rGjnDIz9Ckmp4Avx31PTnbK4F49ayXCOM1DsOn4jLf5KX7ccCzvBodjO5fMBkgwNDaDIeBDxPY0vtBSmIUlEp3YPXMG-5_EkXrYnDQBWDASesdJMeJyyEp366Q7a3hSZV-JPiBtufS5cQFKuOTlFTxXmH_-sDZk7W7YA
,I/SELinux ( 7270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,W/libprocessgroup(  886): failed to open /acct/uid_10168/pid_6324/cgroup.procs: No such file or directory
,E/SELinux ( 7270): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/PeopleContactsSync( 2457): CP2 sync disabled
,I/GoogleURLConnFactory( 2457): Using platform SSLCertificateSocketFactory
,D/TimaKeyStoreProvider( 7270): TimaSignature is unavailable
,D/ActivityThread( 7270): Added TimaKeyStore provider
,D/ResourcesManager( 7270): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-1/base.apk
,I/System.out( 2457): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 2457): (HTTPLog)-Static: isShipBuild true
,I/System.out( 2457): (HTTPLog)-Thread-324-431090000: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/qtaguid ( 2457): Tagging socket 95 with tag 40b00000000{1035,0} uid -1, pid: 2457, getuid(): 10012
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7289): MountEmulatedStorage()
E/Zygote  ( 7289): v2
I/libpersona( 7289): KNOX_SDCARD checking this for 10054
I/libpersona( 7289): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.app.videoplayer for broadcast com.sec.android.app.videoplayer/.videowall.TranscodeReceiver: pid=7289 uid=10054 gids={50054, 9997, 3003, 3002, 1028, 1015, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 5197:com.google.android.gm/u0a114 (adj 15): bgCount ##41
,I/SELinux ( 7289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/qtaguid ( 2457): Tagging socket 104 with tag 40b00000000{1035,0} uid -1, pid: 2457, getuid(): 10012
,D/TimaKeyStoreProvider( 7289): TimaSignature is unavailable
,D/ActivityThread( 7289): Added TimaKeyStore provider
,D/ResourcesManager( 7289): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 7289): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 7289): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7289): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 7289): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7289): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/libprocessgroup(  886): failed to open /acct/uid_10114/pid_5197/cgroup.procs: No such file or directory
,D/AcmsKeyStoreHelper( 7217):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper( 7217): Key Store exist
,I/AcmsKeyStoreHelper( 7217): Hence loading the keystore file
,E/TranscodeReceiver( 7289): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/videowall-Global( 7289): core_num = 4
,W/linker  ( 7289): libsthmb.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/linker  ( 7289): libvwengine.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/videowall-Global( 7289): density : 3.0 width : 1080 height : 1920 Raw width : 1080 Raw height : 1920
D/videowall-Global( 7289): dsp : 1080, swkey : false, Cores : 4, Clock : 0
,D/TranscodeReceiver( 7289):  SIOP_LEVEL: 0
,I/ActivityManager(  886): Killing 6102:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##41
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/AcmsKeyStoreHelper( 7217):  getKeyStoreForApplication Exit
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,I/AcmsCertificateMngr( 7217): getKeyStoreForApplication success 
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1456941720000
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1456920177817
D/AcmsCore( 7217): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor( 7217): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7217): Decrementing - Counter value: 1
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/AcmsCore( 7217): AcmsCore: ACMS_APP_INSTALLED
D/AcmsCore( 7217): This is NOT a valid MirrorLink app
,D/AcmsCore( 7217): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor( 7217): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor( 7217): Decrementing - Counter value: 0
D/AcmsServiceMonitor( 7217): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor( 7217): getSvcCounter - Counter value: 0
,D/AcmsService( 7217): Enter onDestroy
I/AcmsService( 7217): cleanUp(): inside service clean up
D/AcmsCore( 7217): AcmsCore: inside DeInit
D/AcmsCore( 7217): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr( 7217): AcmsCertificateMngr: inside cleanup
,D/AcmsRevocationMngr( 7217): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper( 7217): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface( 7217): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor( 7217): getSvcCounter - Counter value: 0
,D/AcmsService( 7217): killing acms process
I/Process ( 7217): Sending signal. PID: 7217 SIG: 9
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1323): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/GCM     ( 1679): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1679): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GmsCoreStatsServiceLauncher( 2457): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/ActivityManager(  886): Process ACMS.Process (pid 7217)(adj 0) has died(62,606)
,W/libprocessgroup(  886): failed to open /acct/uid_10004/pid_6102/cgroup.procs: No such file or directory
,D/WearableService( 5420): callingUid 10012, callindPid: 5420
,E/MDM     ( 2272): [243] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/LocationInitializer( 2457): Restart initialization of location
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/KeyguardViewMediator( 1178): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PersonaManager( 1178): isKioskContainerExistOnDevice
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/KeyguardViewMediator( 1178): doKeyguard: not showing because lockscreen is off
,D/BootupListener( 1478): ACTION_DRIVELINK
,D/SettingsProvider(  886): name = drivelink_navigation
D/SettingsProvider(  886): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  886): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  886): selectionArgs: false
D/SettingsProvider(  886): selectionArgs: 1001
D/SecContentProvider(  886): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  886): ret = -1
D/BootupListener( 1478): NAVI : com.google.android.apps.maps
,D/SettingsProvider(  886): name = internet_call_settings_visibility
D/SettingsProvider(  886): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  886): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  886): selectionArgs: false
D/SettingsProvider(  886): selectionArgs: 1001
D/SecContentProvider(  886): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  886): ret = -1
,I/qtaguid ( 2457): Untagging socket 95
,I/ConfigFetchService( 2457): fetch service done; releasing wakelock
,I/ConfigFetchService( 2457): stopping self
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,V/AlarmManager(  886): waitForAlarm result :4
,I/iu.UploadsManager( 2457): End new media; added: 0, uploading: 0, time: 62 ms
,V/AlarmManager(  886): waitForAlarm result :8
,I/GAV2    ( 7029): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  886): SIOP:: AP = 440, PST = 441, CUR = 300,
,I/ConfigService( 1679): onDestroy
,I/ActivityManager(  886): Waited long enough for: ServiceRecord{3a8cac4b u0 com.samsung.android.MtpApplication/.MtpService}
,D/BatteryService(  886): level:100, scale:100, status:2, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/BatteryService(  886): stay LED for charging
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/SMD     (  285): DCD ON
,D/PackageManager(  886): [MSG] MCS_UNBIND
,I/ActivityManager(  886): Killing 6144:com.sec.android.app.music:service/u0a44 (adj 15): bgCount ##41
,W/libprocessgroup(  886): failed to open /acct/uid_10044/pid_6144/cgroup.procs: No such file or directory
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  886): [PWL] Off : 15s ago
,I/PowerManagerService(  886): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  886): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2457, ws=null) (elapsedTime=31657)
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog(  886): !@Sync 2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 390, PST = 438, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,I/art     (  886): Explicit concurrent mark sweep GC freed 21567(1400KB) AllocSpace objects, 8(128KB) LOS objects, 30% free, 36MB/52MB, paused 1.327ms total 116.214ms
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  886): [PWL] Off : 30s ago
,I/PowerManagerService(  886): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  886): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.config.ConfigFetchService' (uid=10012, pid=2457, ws=null) (elapsedTime=46668)
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/LightsService(  886): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 886) 
,D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,E/LightSensor(  886): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/SensorManager(  886): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  886): turn on LED for fully charged
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy(  886): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService(  886): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1178
I/PowerManagerService(  886): !@[ps] Screen__On wl: PowerUI.Notification
I/PowerManagerService(  886): Waking up from sleep (uid 10059)...
,D/PowerManagerService(  886): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService(  886): [s] UserActivityState : 0 -> 1
,V/KeyguardServiceDelegate(  886): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@15ffb5e8)
,I/DisplayPowerController(  886): Blocking screen on until initial contents have been drawn.
,D/KeyguardViewMediator( 1178): onScreenTurnedOn, seq = 3
D/KeyguardViewMediator( 1178): notifyScreenOnLocked
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/AutomaticBrightnessController(  886): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController(  886): getFinalBrightness : 0 -> 0
D/SContextService(  886): 	.registerCallback : 1, client=
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/AutomaticBrightnessController(  886): [DAB] setLightSensorEnabled : registerListener mLightSensor
,W/CAE     (  886): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,I/CAE     (  886): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,D/PowerManagerService(  886): [PWL] sb acquire: PowerManagerService.Display
I/CAE     (  886): setCAProperty(ContextAwareService.java:469) - result : true
D/AutomaticBrightnessController(  886): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 1.0 < 15.0 (0.0)
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
W/CAE     (  886): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 1
D/SContextService(  886): sendProperty() : service = Auto Rotation
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
W/CAE     (  886): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
D/PowerManagerService(  886): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL(  886): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL(  886): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
,V/CAE     (  886): start(ContextProvider.java:126)
,I/QCOM PowerHAL(  886): Got set_interactive hint
,V/CAE     (  886): clear(AutoRotationRunner.java:182)
,V/CAE     (  886): enable(AutoRotationRunner.java:158)
I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager(  886): SendSensorHubData: send data = -79, 7, 0, 0
,I/DisplayManagerService(  886): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Unblanking display: 0
,D/SensorManager(  886): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/PowerManagerService(  886): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 20ms
,E/Sensors (  886): Acc old sensor_state 8704, new sensor_state : 8705 en : 1
,D/Sensorhubs(  297): sendContextData: -79, 7, 0, 0
D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SensorManager(  886): registerListener :: 0, MPU6500 Acceleration Sensor, 200000, 0,  
,D/PowerManagerService(  886): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 15ms
,D/CAE     (  886): getFaultDetectionResult(AutoRotationRunner.java:195) - true
D/SSRM:m  (  886): SIOP:: AP = 340, PST = 430, CUR = 300
,I/CAE     (  886): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,D/CAE     (  886): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  886): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     (  886): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
I/CAE     (  886): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@2a5a379, Service : AUTO_ROTATION(1)
,W/CAE     (  886): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService(  886): addSContextService() : service = Auto Rotation
D/SContextService(  886): ===== SContext Service List =====
D/SContextService(  886): Listener : android.hardware.scontext.SContextService$Listener@eba8be, Service : Auto Rotation
D/SContextManager(  886):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@20bd5401, service=Auto Rotation
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/InputManager-JNI(  886): setDeviceInteractive: 1
,D/InputManager-JNI(  886): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/InputManager-JNI(  886): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,D/KeyguardViewMediator( 1178): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 1178): onScreenTurnedOn()
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,V/BitmapFactory( 1178): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,D/NfcService( 1472): call the applyRotuiing
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(477/onResume)] 
,D/SamsungIME( 1870): showDlgMsgBox : false true true
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/BitmapFactory( 1178): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_battery_full.png
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 96
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,V/UserPresentBroadcastReceiver( 2272): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(487/onResume)] Postpone Count : 96
,D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1178): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3a5c4dd4
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/SecContentProvider2(  886): mCursor = null
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
V/KeyguardServiceDelegate(  886): **** SHOWN CALLED ****
D/StatusBarKeyguardViewManager( 1178): callback.onShown()
D/DisplayPowerController(  886): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController(  886): Unblocked screen on after 210 ms
D/DisplayPowerState(  886): !@ ColorFade exit
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/SurfaceFlinger(  249): id=14 Removed ColorFade (8/8)
,I/SurfaceFlinger(  249): id=14 Removed ColorFade (-2/8)
E/libEGL  (  886): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 96
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/InputManager-JNI(  886): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 4413): [IIlllIlIIlIllIlllIll(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 4413): [IIlllIlIIlIllIlllIll(397/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
D/BatteryMeterView( 1178): onDraw batteryColor : -1
,D/ActivityManager(  886): post active user change for 0
,D/KnoxTimeoutHandler(  886): postActiveUserChange for user 0
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/Timeline( 4413): Timeline: Activity_idle id: android.os.BinderProxy@241472bd time:88731
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 1
,E/qdexternal(  249): writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
D/qdhwcomposer(  249): hwc_blank: Done unblanking display: 0
,D/SurfaceControl(  886): Excessive delay in setPowerMode(): 295ms
D/lights  (  886): lcd : 8 +
,D/lights  (  886): lcd : 8 -
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
D/PowerManagerService(  886): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  886): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService(  886): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService(  886): [input device light] handleInputDeviceLightOn
D/lights  (  886): button : 1 +
,D/lights  (  886): button : 1 -
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/LightsService(  886): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager(  886): unregisterListener ::   
,D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,D/InputManager-JNI(  886): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,V/ActivityManager(  886): Display changed displayId=0
,V/ActivityManager(  886): Display changed displayId=0
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PalmMotion(  886): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotion(  886): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/LightsService(  886): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 886) 
D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService(  886): [SvcLED]  onSensorChanged::light value = 0
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/SensorManager(  886): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  886): unregisterListener ::   
D/lights  (  886): led_pattern : 5 +
,D/SSRM:a  (  886): DeviceInfo:: 000000000000
D/SSRM:a  (  886): SettingsAirViewInfo:: 000000000
,D/SLocation(  886): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
,W/System.err(  886): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at com.samsung.location.SLocationService.run(Unknown Source)
W/System.err(  886): 	at java.lang.Thread.run(Thread.java:818)
,D/KnoxTimeoutHandler(  886): handleActiveUserChange for user 0
,D/lights  (  886): led_pattern : 5 -
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=4) OUT; SvcLED(id=3) IN
,D/LightsService(  886): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 886) 
D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService(  886): turn off LED
,D/LightsService(  886): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/lights  (  886): led_pattern : 0 +
,D/lights  (  886): led_pattern : 0 -
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/CAE     (  886): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     (  886): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager(  886): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs(  297): sendContextData: -76, 13, -47, 0
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,D/InputMethodManagerService(  886): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService(  886):  handler : SCREEN_ON end
,D/WifiStateMachine(  886): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  886): handleScreenStateChanged Exit: true
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NotificationService(  886): ACTION_SCREEN_ON
D/LightsService(  886): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 886) 
,D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService(  886): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=on
V/voice   (  291): voice_set_parameters: enter: screen_state=on
,V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,I/SecExternalDisplayIntents_Java(  886): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  886): do suspend false
,I/wpa_supplicant( 1260): reset timer : RESET_TIMER 1
I/wpa_supplicant( 1260): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1260): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 1260): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController(  886): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController(  886): Bridge Server is not available
,D/PersonaManagerService(  886): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler(  886): MSG_ACTION_SCREEN_ON called
,I/NfcService( 1472): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 1472): call the applyRotuiing
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 1.
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:479 [0:0] doChangeDayOrNight : 1
D/accuweather( 2014): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2014): [KK AccuPhone]>>> SWW:496 [0:0] makeClock : 1
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
D/accuweather( 2014): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,I/SamsungIME( 1870): getNextShiftState() cursorCapsMode : 0
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/PowerManagerService(  886): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:m  (  886): SIOP:: AP = 340, PST = 422, CUR = 300
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:41 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:418 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:421 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:422 [0:0] [ASO][NUT] = 1456941720000
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:423 [0:0] [ASO][CT] = 1456920202684
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 1323): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/SSRM:a  (  886): DeviceInfo:: 000000000000
D/SSRM:a  (  886): SettingsAirViewInfo:: 000000000
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560,
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/PowerManagerService(  886): [input device light] handleInputDeviceLightOff
D/lights  (  886): button : 0 +
,D/lights  (  886): button : 0 -
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560,
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/SMD     (  285): DCD ON
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/wpa_supplicant( 1260): nl80211: Received scan results (15 BSSes)
,D/WifiP2pService(  886): InactiveState{ what=147461 }
,D/WifiP2pService(  886): P2pEnabledState{ what=147461 }
,D/WifiP2pService(  886): DefaultState{ what=147461 }
,E/WifiStateMachine(  886): [1,456,920,206,244 ms] noteScanEnd no scan source
,E/WifiStateMachine(  886): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@185d4f83 sup_state=COMPLETED debouncing=false
,I/CLocInfoService(  886): External Intent Received android.net.wifi.SCAN_RESULTS
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7408): MountEmulatedStorage()
,E/Zygote  ( 7408): v2
I/libpersona( 7408): KNOX_SDCARD checking this for 10082
I/libpersona( 7408): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=7408 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 8746(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 416us total 22.361ms
,E/SMD     (  285): DCD ON
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 386us total 13.205ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 387us total 12.044ms
,I/SELinux ( 7408): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 7408): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 7408): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/TimaKeyStoreProvider( 7408): TimaSignature is unavailable
,D/ActivityThread( 7408): Added TimaKeyStore provider
,D/ResourcesManager( 7408): creating new AssetManager and set to /system/app/Books/Books.apk
,I/ReaderUtils( 7408): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,W/GAV2    ( 7408): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/BooksApp( 7408): Created application version: 3.3.11 (30311)
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/BooksSync( 7408): Starting books sync, d
,D/ResourcesManager( 2457): creating new AssetManager and set to /system/app/Books/Books.apk
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,E/SQLiteLog( 7408): (284) automatic index on view_volumes(volume_id)
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 19986(1113KB) AllocSpace objects, 3(243KB) LOS objects, 40% free, 17MB/29MB, paused 722us total 49.277ms
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at dsf.a(PG:807)
E/HttpOperation( 5768): 	at fhk.a(PG:1126)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 8 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 10 more
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/lcd/panel/lux  value : 0
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/System.out( 7408): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 7408): (HTTPLog)-Static: isShipBuild true
,I/System.out( 7408): (HTTPLog)-Thread-1227-695288052: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5768): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at ieo.a(PG:43)
E/HttpOperation( 5768): 	at iep.a(PG:93)
E/HttpOperation( 5768): 	at fhn.a(PG:59)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/ExperimentLoader( 5768): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): 	at kfv.a(PG:65)
E/ExperimentLoader( 5768): 	at kff.u(PG:385)
E/ExperimentLoader( 5768): 	at kfb.a(PG:29)
E/ExperimentLoader( 5768): 	at kff.l(PG:132)
E/ExperimentLoader( 5768): 	at ieo.a(PG:43)
E/ExperimentLoader( 5768): 	at iep.a(PG:93)
E/ExperimentLoader( 5768): 	at fhn.a(PG:59)
E/ExperimentLoader( 5768): 	at lex.a(PG:85)
E/ExperimentLoader( 5768): 	at lex.b(PG:132)
E/ExperimentLoader( 5768): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5768): 	at fhk.a(PG:908)
E/ExperimentLoader( 5768): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5768): 	at ihi.a(PG:22)
E/ExperimentLoader( 5768): 	at kft.a(PG:91)
E/ExperimentLoader( 5768): 	at kfv.a(PG:62)
E/ExperimentLoader( 5768): 	... 12 more
E/ExperimentLoader( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5768): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5768): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5768): 	at ihi.a(PG:19)
E/ExperimentLoader( 5768): 	... 14 more
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getaccountstatus] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at ixd.a(PG:248)
E/HttpOperation( 5768): 	at ixd.b(PG:206)
E/HttpOperation( 5768): 	at ixd.a(PG:175)
E/HttpOperation( 5768): 	at fig.a(PG:78)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/EsSyncAdapterService( 5768): Sync failure
E/EsSyncAdapterService( 5768): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5768): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5768): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5768): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5768): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5768): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5768): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5768): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5768): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5768): 	... 10 more
E/EsSyncAdapterService( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5768): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5768): 	... 12 more
E/EsSyncAdapterService( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5768): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5768): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5768): 	... 14 more
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 67217, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2338310538429725861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  886): mCursor = null
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2338310538429725861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 7408): null auth token
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2338310538429725861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  886): SIOP:: AP = 340, PST = 414, CUR = 300
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/BooksSync( 7408): Soft error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2338310538429725861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7408): Sync error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2338310538429725861&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
I/BooksSync( 7408): Finished books sync
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 71294, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  886): Killing 5939:com.google.android.music:main/u0a126 (adj 15): bgCount ##41
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  886): failed to open /acct/uid_10126/pid_5939/cgroup.procs: No such file or directory
,I/art     (  886): Explicit concurrent mark sweep GC freed 47234(2MB) AllocSpace objects, 16(646KB) LOS objects, 30% free, 36MB/52MB, paused 1.675ms total 134.263ms
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/GAV2    ( 7408): Thread[GAThread,5,main]: No campaign data found.
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/Watchdog(  886): !@Sync 3
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  886): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10059 pid=1178 (0x0)
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,V/AlarmManager(  886): waitForAlarm result :4
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/SSRM:m  (  886): SIOP:: AP = 320, PST = 404, CUR = 300
,D/X       (  886): broadcastSiopLevelIntent:: currentSiopLevel = -1
,D/ContentApp( 1226):  LEVEL : -1
,E/TranscodeReceiver( 7289): onReceive : android.intent.action.CHECK_SIOP_LEVEL
,D/TranscodeReceiver( 7289):  SIOP_LEVEL: -1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 2.
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/SMD     (  285): DCD ON
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 8
,D/PowerManagerService(  886): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  886): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
D/lights  (  886): lcd : 1 +
,D/lights  (  886): lcd : 1 -
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/SMD     (  285): DCD ON
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/FactoryTest( 6522): Not factory mode,
D/FactoryTest( 6522): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 6522): DRIVER_TIME_OUT 60s lapsed
,D/MTPRx   ( 6522): still no open session command from host, so toast
,W/ContextImpl( 6522): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 6522): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:713 
I/Timeline( 6522): Timeline: Activity_launch_request id:com.android.settings time:115168
,E/PersonaManagerService(  886): inState():  stateMachine is null !!
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager(  886): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService(  886): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 886  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  886): mDVFSHelper.acquire()
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(415/onUserLeaveHint)] 
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/SQLiteSecureOpenHelper( 3258): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3258): getDatabaseLocked(b,b,pwd)...
,E/MTPRx   ( 6522): started activity for popup
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 96
E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(573/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onUserLeaveHint)] Home Key!!
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.llIlIllIIIlIIlllIlII(325/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/LightsService(  886): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 886) 
D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  886): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
I/PhoneStatusBar( 1178): Icon Only
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager(  886): showStatusBarByNotification() mOpenByNotification=false
I/DBG_DM  ( 4413): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,V/BitmapFactory( 1178): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 4413): [com.wssyncmldm.ui.XUIInstallConfirmActivity(469/onPause)] 
,V/ActivityManager(  886): Display changed displayId=0
,D/Launcher( 1487): onRestart, Launcher: 90796936
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,V/BitmapFactory( 1178): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/indicator_postpone.qmg
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/KnoxNotification( 1178): ----- inflateViews : modified publicViewLocal -----
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/Launcher( 1487): onStart, Launcher: 90796936
D/Launcher.HomeView( 1487): onStart
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2014): [237392/6] Surface widget visibility changed visibility = true on instance = 1
D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,I/SurfaceFlinger(  249): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager(  886): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  886): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/KnoxNotification( 1178): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1178): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1178): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3a5c4dd4
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/ResourcesManager( 6522): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 6522): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 6522): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 6522): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 6522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 6522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 6522): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/SettingsReceiverActivity( 6522): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame(  886): Set to : 0
,D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
E/ActivityManager(  886): Invalid thumbnail dimensions: 576x576
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/SQLiteSecureOpenHelper( 3258): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3258): getDatabaseLocked(b,b,pwd)...
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/InputMethodManagerService(  886): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 6522): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/SettingsReceiverActivity( 6522): dev.kiessupport is : TRUE
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/Activity( 6522): performCreate Call secproduct feature valuefalse
D/Activity( 6522): performCreate Call debug elastic valuetrue
,D/Launcher( 1487): onResume, Launcher: 90796936
,D/SettingsProvider(  886): name = kids_home_mode
D/SettingsProvider(  886): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  886): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  886): selectionArgs: false
D/SettingsProvider(  886): selectionArgs: 10008
D/SecContentProvider(  886): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  886): ret = -1
,D/Launcher.HomeView( 1487): onResume
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2014): [237392/6] Surface widget resume on instance = 1
D/LockPatternUtilsCache( 1178): value : false
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/Launcher( 1487): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/MenuAppsGridFragment( 1487): onResume
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/MicrophoneInputStream( 1574): mic_starting gfk@241472bd
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/WallpaperManager( 1487): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/GalleryCacheReady( 6165): Receive : home resume
,I/HotwordRecognitionRnr( 1574): Starting hotword detection.
,V/AudioPolicyManager(  291): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  291): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  291): adev_open_input_stream: enter
,E/audio_hw_primary(  291): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  291): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  291): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  291): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  291): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  291): adev_open_input_stream: exit
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
I/AudioFlinger(  291): AudioFlinger's thread 0xaf740000 ready to run
V/audio_hw_primary(  291): in_standby: enter
V/audio_hw_primary(  291): in_standby: exit:  status(0)
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,V/audio_hw_primary(  291): in_standby: enter
V/audio_hw_primary(  291): in_standby: exit:  status(0)
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
I/EDMNativeHelperService(  886): isMicrophoneEnabled
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/SMD     (  285): DCD ON
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/Mms/UIEventReceiver( 6915): ui event
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
V/AudioPolicyManager(  291): startInput() input 30
D/LockPatternUtilsCache( 1178): value : false
,V/AudioPolicyManager(  291): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  291): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  291): DeviceVector::refreshTypes() mDeviceTypes 80000004
,V/AudioPolicyManager(  291): DeviceVector::getDevicesFromType() for type 80000004 found 0xb2a5b3c0
V/audio_hw_primary(  291): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  291): in_set_parameters: exit: status(11)
,V/AudioPolicyManager(  291): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  291): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 1574): mic_started gfk@241472bd
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,W/BroadcastQueue(  886): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1487, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
V/msm8974_platform(  291): platform_update_usecase_from_source: input source :6
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
V/audio_hw_primary(  291): start_input_stream: enter: usecase(7)
V/voice   (  291): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  291): start_input_stream: usecase(7)
D/PreProcess(  291): new SamsungRecord
D/PreProcess(  291): new NS
I/samsungRecord(  291): [samsungrecord] SamsungRecInit 
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/samsungRecord(  291): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  291): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  291): 1
D/SamsungRecord_NS(  291): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  291): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  291): select_devices: ENTER
V/audio_hw_primary(  291): select_devices: usecase(normal)
V/audio_hw_primary(  291): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  291): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  291): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  291): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  291): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  291): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  291): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  291): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  291): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  291): ACDB -> send_adm_topology
D/ACDB-LOADER(  291): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  291): ACDB -> send_asm_topology
D/ACDB-LOADER(  291): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  291): ACDB -> send_audtable
D/ACDB-LOADER(  291): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/        (  291): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  291): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  291): ACDB -> send_audvoltable
D/ACDB-LOADER(  291): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  291): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  291): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  291): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  291): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  291): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  291): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
D/audio_route(  291): ++++ audio_route_update_mixer ==============
D/audio_route(  291): Setting mixer control: DEC2 Volume
D/audio_route(  291): Setting mixer control: value: 106
,D/audio_route(  291): Setting mixer control: SLIM TX7 MUX, value: 9
,D/audio_route(  291): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  291): Setting mixer control: value: 1
,D/audio_route(  291): Setting mixer control: DEC2 MUX, value: 1
D/audio_route(  291): ------ audio_route_update_mixer ==============
,V/audio_hw_primary(  291): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  291): enable_audio_route: apply mixer path: audio-record
D/audio_route(  291): ++++ audio_route_update_mixer ==============
D/audio_route(  291): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  291): Setting mixer control: value: 1
D/audio_route(  291): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  291): enable_audio_route: exit
V/audio_hw_primary(  291): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  291): start_input_stream: exit
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/Zygote  ( 7492): MountEmulatedStorage()
I/libpersona( 7492): KNOX_SDCARD checking this for 10094
E/Zygote  ( 7492): v2
I/libpersona( 7492): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7492 uid=10094 gids={50094, 9997} abi=armeabi-v7a
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/ActivityManager(  886): handle home activity for 0
I/WallpaperManagerService(  886): switchPersonaWallpaper is called for personaId-0
,D/ActivityManager(  886): post active user change for 0
D/WallpaperManagerService(  886):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  886): postActiveUserChange for user 0
D/accuweather( 2014): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
I/SELinux ( 7492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/KnoxTimeoutHandler(  886): handleActiveUserChange for user 0
D/accuweather( 2014): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
D/accuweather( 2014): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
,I/SELinux ( 7492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
,E/SELinux ( 7492): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/accuweather( 2014): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
,D/accuweather( 2014): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/Timeline( 1487): Timeline: Activity_idle id: android.os.BinderProxy@3a9b11c8 time:115594
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,E/Zygote  ( 7505): MountEmulatedStorage()
E/Zygote  ( 7505): v2
I/libpersona( 7505): KNOX_SDCARD checking this for 10071
I/libpersona( 7505): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=7505 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 7505): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7505): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7505): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/TimaKeyStoreProvider( 7492): TimaSignature is unavailable
,D/ActivityThread( 7492): Added TimaKeyStore provider
,D/ResourcesManager( 7492): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,W/ResourcesManager( 7492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/HotwordWorker( 1574): onReady
,V/BitmapFactory( 1487): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic.png
,D/TimaKeyStoreProvider( 7505): TimaSignature is unavailable
,D/ActivityThread( 7505): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 7505): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
W/ResourcesManager( 7505): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7505): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7505): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/Zygote  ( 7522): MountEmulatedStorage()
E/Zygote  ( 7522): v2
I/libpersona( 7522): KNOX_SDCARD checking this for 10103
I/libpersona( 7522): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7522 uid=10103 gids={50103, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 5375:com.google.android.talk/u0a117 (adj 15): bgCount ##41
,I/SELinux ( 7522): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7522): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7522): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/TimaKeyStoreProvider( 7522): TimaSignature is unavailable
,D/ActivityThread( 7522): Added TimaKeyStore provider
,D/comsamsunglog( 7505): [KK AccuPhone]>>> ==============================================================================================
W/libprocessgroup(  886): failed to open /acct/uid_10117/pid_5375/cgroup.procs: No such file or directory
D/comsamsunglog( 7505): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7505): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7505): [KK AccuPhone]>>> ==============================================================================================
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/comsamsunglog( 7505): [KK AccuPhone]>>> ==============================================================================================
,D/comsamsunglog( 7505): [KK AccuPhone]>>> widgetappapheroaccuweather [Version : 15030401] [ 1 ] 
,D/comsamsunglog( 7505): [KK AccuPhone]>>> Header set to : ===> "accuweather" <===  Port fHD
D/comsamsunglog( 7505): [KK AccuPhone]>>> ==============================================================================================
,D/SettingsProvider(  886): name = aw_daemon_service_key_agree_popup_check
D/SettingsProvider(  886): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  886): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  886): selectionArgs: false
D/SettingsProvider(  886): selectionArgs: 10071
D/SecContentProvider(  886): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  886): ret = -1
,D/ResourcesManager( 7522): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 2014): [KK AccuPhone]>>> DBH:3354 [0:0] gADWI : count = 0
,W/ResourcesManager( 7522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 7522): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/CustomFrequencyManagerService(  886): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 886  tag : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  886): mDVFSHelper.release()
,D/accuweather( 2014): [KK AccuPhone]>>> SM:442 [0:0] updateView iSA = false, mCI = 0, mSL = null , cls = 0 , cls = 1
,D/accuweather( 2014): [KK AccuPhone]>>> SM:447 [0:0] bg transparency val = 0
,D/CustomFrequencyManagerService(  886): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 886  pkgName : ACTIVITY_RESUME_BOOSTER@10
,I/Timeline(  886): Timeline: Activity_windows_visible id: ActivityRecord{2eaa45f1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t25} time:115764
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/accuweather( 2014): [KK AccuPhone]>>> SM:679 [0:0] [sCCTZ] set default tZ
D/accuweather( 2014): [KK AccuPhone]>>> SM:1044 [0:0] setLayoutContentEmptyMsg = 2131558522
,D/accuweather( 2014): [KK AccuPhone]>>> U:1012 [0:0] icon = 99, isDay = true, type = 261
,D/accuweather( 2014): [KK AccuPhone]>>> U:1187 [0:0] resID = 2130837848
D/accuweather( 2014): [KK AccuPhone]>>> SM:1402 [0:0] setClockLayoutContent
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,D/accuweather( 2014): [KK AccuPhone]>>> SM:1072 [0:0] complete setLayoutContentEmptyMsg Content
E/Zygote  ( 7540): MountEmulatedStorage()
E/Zygote  ( 7540): v2
I/libpersona( 7540): KNOX_SDCARD checking this for 10113
I/libpersona( 7540): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.GeoLookout for broadcast com.sec.android.GeoLookout/.widget.SafetyCareWidget: pid=7540 uid=10113 gids={50113, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6663:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
I/SELinux ( 7540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1178): value : false
,I/SELinux ( 7540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,I/ActivityManager(  886): Killing 6685:com.sec.knox.bridge/1000 (adj 15): bgCount ##41
,E/SELinux ( 7540): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/TimaKeyStoreProvider( 7540): TimaSignature is unavailable
,D/ActivityThread( 7540): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/ResourcesManager( 7540): creating new AssetManager and set to /system/app/GeoLookout/GeoLookout.apk
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,D/SurfaceWidget.Renderer( 2014): [237392/6] SurfaceWidget drawing first frame
,W/libprocessgroup(  886): failed to open /acct/uid_10075/pid_6663/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_6685/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (7/8)
,I/SurfaceFlinger(  249): id=13 Removed com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity (-2/8)
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,W/GeoLookout( 7540): H: zOXtzplbN+8pOR8lXMN+zuVFxvDlCo+Yzxg4ugbhd7A04DIT5nFf+o6jguBECoC9dC8nZsnXtcP6wJ/Do8CKbApjnmitl3AiTeKReyJRDttBktCZIh1mNkZuovfXxXoAjd37PhyBM3ng3bcKYjYGOEDyKJaWZrwK1FfNJWfEtzYH8n1Joa422xGgCu3P2tNC0syzQpcTEb6CNvuJmw0Apg==
,I/GeoLookout( 7540): H: zOXtzplbN+8pOR8lXMN+zq5rYKS75KQLo4xvOOBhIY6eGw1/GT6WQYb1SRYOugxmkGHzev/Lb2j+GB0+6UGDnw==
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/SettingsProvider(  886): name = safetycare_geolookout_registering
D/SettingsProvider(  886): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  886): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  886): selectionArgs: false
D/SettingsProvider(  886): selectionArgs: 10113
,D/SecContentProvider(  886): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  886): ret = -1
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/GeoLookout( 7540): H: mmqeDLqBgrS1PY9ZxjAERmjpyYDSyckxRVEBLahXFCCjxEHkYkZuzwjV7ldL9/y2wUiG8ZXusFQQzoKG1FCUjw==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1MpblPvMyD8bF5o9h5mVT9aba68PSLy9IpSfBXGHVgOg==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjRATu9ZqRwmv7A7uEos9Q9mvO4YDA6qaoxYEtGEMNH1w
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjRej64htfcxG5kL3SHyGYDnr4brh3hp83PTv8sTeWgfzb09Wu8w+l9FeW3bXb18r1tcp17zAuCthjNMD7/ctUpMsPOZWZzY9gg1XBOkZWTGk
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjVjhROowReQZ6uZ83+PHbxXxfrUuNQHmPlY4PsIKqeHXpHMfmw7BKa8EvZP1XFE95vEpSHlOxg9XQoR6KQvcMJUezCj+VlRSvYmiaFKv4yMdF9ANJ7ri8t1rvBR++sDAZA==
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 7557): MountEmulatedStorage()
E/Zygote  ( 7557): v2
I/libpersona( 7557): KNOX_SDCARD checking this for 10154
I/libpersona( 7557): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7557 uid=10154 gids={50154, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6724:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##41
,I/SELinux ( 7557): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7557): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7557): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7557): TimaSignature is unavailable
,D/ActivityThread( 7557): Added TimaKeyStore provider
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_6724/cgroup.procs: No such file or directory
,D/ResourcesManager( 7557): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/ResourcesManager( 7557): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 7557): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 7557): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 7557): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService(  886): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 886  tag : ACTIVITY_RESUME_BOOSTER@10
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/Zygote  ( 7572): MountEmulatedStorage()
E/Zygote  ( 7572): v2
I/libpersona( 7572): KNOX_SDCARD checking this for 10158
I/libpersona( 7572): KNOX_SDCARD not a persona
,I/SELinux ( 7572): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7572): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7572): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  886): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7572 uid=10158 gids={50158, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  886): Killing 6814:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/TimaKeyStoreProvider( 7572): TimaSignature is unavailable
,D/ActivityThread( 7572): Added TimaKeyStore provider
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  886): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  886): CMD_RSSI_POLL : out!
,D/ResourcesManager( 7572): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/TaskCloserActivity( 7572): TaskCloserActivity enter()
,V/TaskCloserActivity( 7572): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/ActivityManager(  886): Killing 6836:com.samsung.groupcast/u0a16 (adj 15): bgCount ##41
,W/libprocessgroup(  886): failed to open /acct/uid_10015/pid_6814/cgroup.procs: No such file or directory
,W/libprocessgroup(  886): failed to open /acct/uid_10016/pid_6836/cgroup.procs: No such file or directory
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,D/StatusBar.NetworkController( 1178): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1178): applyOpen
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
,D/DisplayPowerController(  886): getFinalBrightness : 1 -> 1
,D/PowerManagerService(  886): [s] UserActivityState : 2 -> 4
I/PowerManagerService(  886): Nap time (uid 1000)...
I/PowerManagerService(  886): !@[ps] Screen__Off(2) : 
I/PowerManagerService(  886): Going to sleep due to screen timeout (uid 1000)...
D/InputManager-JNI(  886): setDeviceInteractive: 0
,D/PowerManagerService(  886): [PWL] sb acquire: PowerManagerService.Broadcasts,
,D/PowerManagerService(  886): SecHardwareInterface.setBatteryADC : false,
,D/PowerManagerService(  886): handleSandman : startDream(),
,E/PowerManagerService(  886): handleSandman : startDreaming, but isDreaming false
I/SurfaceFlinger(  249): id=16 createSurf (1080x1920),2 flag=404, ColorFade
,I/PowerManagerService(  886): Sleeping (uid 1000)...
D/PowerManagerService(  886): [s] UserActivityState : 4 -> 0
,D/PowerManagerService(  886): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService(  886): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI(  886): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  886): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI(  886): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI(  886): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/SContextService(  886): 	.unregisterCallback : 1, client=
,D/SContextService(  886): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@eba8be, Service = Auto Rotation, used = 1
,W/CAE     (  886): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     (  886): stop(ContextProvider.java:149)
,V/CAE     (  886): clear(AutoRotationRunner.java:182)
,V/CAE     (  886): disable(AutoRotationRunner.java:171)
,I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager(  886): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs(  297): sendContextData: -78, 7, 0, 0
,D/CAE     (  886): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     (  886): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,E/SMD     (  285): DCD ON
,D/DisplayPowerController(  886): ColorFade: onAnimationStart
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 0
,D/CAE     (  886): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     (  886): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     (  886): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
W/CAE     (  886): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService(  886): removeSContextService() : service = Auto Rotation
D/SContextService(  886): ===== SContext Service List =====
D/SContextManager(  886):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@20bd5401, service=Auto Rotation
,D/Launcher.HomeView( 1487): onPause
,D/KeyguardViewMediator( 1178): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 1178): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 1178): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 1178): notifyScreenOffLocked
,D/Launcher( 1487): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/KeyguardViewMediator( 1178): timeout : 5000
,D/DisplayPowerController(  886): getFinalBrightness : 8 -> 0
,D/lights  (  886): lcd : 0 +
,D/lights  (  886): lcd : 0 -
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/AutomaticBrightnessController(  886): mCallbacks.updateBrightness()
D/DisplayPowerController(  886): getFinalBrightness : 8 -> 0
,D/KeyguardViewMediator( 1178): setting alarm to turn off keyguard, seq = 3
D/KeyguardViewMediator( 1178): handleNotifyScreenOff
,V/TaskCloserActivity( 7572): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/StatusBarManagerService(  886): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LightsService(  886): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 886) 
D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService(  886): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager(  886): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager(  886): unregisterListener ::   
D/lights  (  886): led_pattern : 5 +
D/Launcher.HomeView( 1487): onStop
,D/BatteryService(  886): turn on LED for fully charged
,I/MicrophoneInputStream( 1574): mic_close gfk@241472bd
,V/AudioPolicyManager(  291): stopInput() input 30,
,D/lights  (  886): led_pattern : 5 -
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,V/audio_hw_primary(  291): in_standby: enter
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2014): [237392/6] Surface widget pause on instance = 1
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
,I/HotwordRecognitionRnr( 1574): Hotword detection finished
,D/accuweather( 2014): [KK AccuPhone]>>> WR:132 [0:0] onPause
,D/accuweather( 2014): [KK AccuPhone]>>> SM:538 [0:0] onPause
,I/HotwordRecognitionRnr( 1574): Stopping hotword detection.
,I/CAE     (  886): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     (  886): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
,D/SensorHubManager(  886): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs(  297): sendContextData: -76, 13, -46, 0
,I/CAE     (  886): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 3, 52,
,D/SensorHubManager(  886): SendSensorHubData: send data = -63, 14, 12, 3, 52
,D/Sensorhubs(  297): sendContextData: -63, 14, 12, 3, 52
,V/audio_hw_primary(  291): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  291): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  291): disable_audio_route: reset mixer path: audio-record
D/audio_route(  291): ++++ audio_route_update_mixer ==============
,D/audio_route(  291): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  291): Setting mixer control: value: 0
,D/audio_route(  291): ------ audio_route_update_mixer ==============
,V/audio_hw_primary(  291): disable_audio_route: exit
V/audio_hw_primary(  291): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  291): ++++ audio_route_update_mixer ==============
D/audio_route(  291): Setting mixer control: DEC2 Volume
D/audio_route(  291): Setting mixer control: value: 0
,D/audio_route(  291): Setting mixer control: SLIM TX7 MUX, value: 0
,D/audio_route(  291): Setting mixer control: AIF1_CAP Mixer SLIM TX7
,D/audio_route(  291): Setting mixer control: value: 0
,D/audio_route(  291): Setting mixer control: DEC2 MUX, value: 0
,D/audio_route(  291): ------ audio_route_update_mixer ==============
,V/audio_hw_primary(  291): stop_input_stream: exit: status(0)
V/audio_hw_primary(  291): in_standby: exit:  status(0)
,V/AudioPolicyManager(  291): releaseInput() 30
V/AudioPolicyManager(  291): closeInput(30)
,V/audio_hw_primary(  291): adev_close_input_stream
,V/audio_hw_primary(  291): in_standby: enter
V/audio_hw_primary(  291): in_standby: exit:  status(0)
E/audio_hw_primary(  291): adev_close_input_stream, set jack_in to null
,V/AudioPolicyManager(  291): releaseInput() exit
,D/DisplayPowerState(  886): !@ ColorFade entry
,V/BitmapFactory( 1487): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic_none.png
,D/DisplayPowerController(  886): ColorFade: onAnimationEnd
D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService(  886):  handler : SCREEN_OFF end 
D/AutomaticBrightnessController(  886): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/AutomaticBrightnessController(  886): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
E/LightSensor(  886): Light old sensor_state 8705, new sensor_state : 8193 en : 0
,I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController(  886): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/NotificationService(  886): ACTION_SCREEN_OFF
D/LightsService(  886): [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 886) 
D/LightsService(  886): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,E/LightSensor(  886): Light old sensor_state 8193, new sensor_state : 8705 en : 1
,D/WifiStateMachine(  886): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine(  886): handleScreenStateChanged Exit: false
,E/WifiStateMachine(  886): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
,E/WifiStateMachine(  886): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16800 - processMessage - processMsg
E/native  (  886): do suspend true
,D/SensorManager(  886): unregisterListener ::   
,E/Sensors (  886): Acc old sensor_state 8705, new sensor_state : 8704 en : 0
D/SensorManager(  886): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/audio_hw_primary(  291): adev_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: enter: screen_state=off
V/voice   (  291): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  291): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  291): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  291): audio_extn_hfp_set_parameters: enter
V/audio_hw_primary(  291): adev_set_parameters: exit
,D/SensorManager(  886): unregisterListener ::   
,I/SecExternalDisplayIntents_Java(  886): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController(  886): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController(  886): Bridge Server is not available
,D/DisplayPowerController(  886): getFinalBrightness : 0 -> 0
,I/DisplayManagerService(  886): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 422.03 x 424.069 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6a62000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
D/DisplayPowerController(  886): getFinalBrightness : 0 -> 0
,D/TaskPersister(  886): removeObsoleteFile: deleting file=27_task_thumbnail.png
,V/ActivityManager(  886): Display changed displayId=0
,D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF start
,D/VolumePanel( 1178): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/VolumePanel( 1178): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 1178): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PersonaManagerService(  886): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler(  886): MSG_ACTION_SCREEN_OFF called
,D/StatusBar.NetworkController( 1178): onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
,D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
D/StatusBar.NetworkController( 1178): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1178): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020468/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/NfcService( 1472): call the applyRotuiing
,D/STATUSBAR-PhoneStatusBar( 1178):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 1178): onReceive : Intent.ACTION_SCREEN_OFF
,D/Recents_AlternateRecentsComponent( 1178): dismissHelpPopup 
,D/accuweather( 2014): [KK AccuPhone]>>> SWW:66 [0:0] action : androidintentactionSCREEN_OFF
D/accuweather( 2014): [KK AccuPhone]>>> SWW:467 [0:0] stopRefreshIcon : 1
D/accuweather( 2014): [KK AccuPhone]>>> SWW:364 [0:0] getWeatherRenderer : 1
,D/ConnectivityService(  886): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
,I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/SSRM:m  (  886): SIOP:: AP = 320, PST = 390, CUR = 300
,W/ActivityManager(  886): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,W/ActivityManager(  886): getTasks: caller 10086 does not hold GET_TASKS; limiting output
,D/PowerManagerService(  886): [PWL] sb release: PowerManagerService.Broadcasts
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 22
I/rmt_storage(  272): 
,I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
,D/SurfaceControl(  886): Excessive delay in setPowerMode(): 278ms
D/PowerManagerService(  886): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL(  886): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL(  886): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/QCOM PowerHAL(  886): Got set_interactive hint
,I/PowerManagerService(  886): [PWL] Off : 0s ago
I/PowerManagerService(  886): [PWL]   PowerManagerService.Display: ref count=2
I/PowerManagerService(  886): [PWL]     mDisplayReady : false
,D/DisplayPowerController(  886): getFinalBrightness : 0 -> 0
D/PowerManagerService(  886): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService(  886): [PWL] sb release: PowerManagerService.Display
,E/LightSensor(  886): RED : 2, GREEN : 3, BLUE : 4, CLEAR : 8, CALCULATED LUX : 0.000000, CCT : 11625.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=1, rp1=1, gp1=2, bp1=3, cp1=7, cpl=3202560
,D/LightsService(  886): [SvcLED]  onSensorChanged::light value = 0
,E/LightSensor(  886): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  886): unregisterListener ::   
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: priority changed! SvcLED(id=3) OUT; SvcLED(id=4) IN
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p0X1S2Rcjfuoz/uR69LW7q4dRvDIbb+p93sEFNr9NIFsA==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjYXOqDX8ezzeYFlqIugeVh9tddYklHQaYJQeZ5D1n0CWhpLwjVw6z1MjJ35DMCBpaiDarp/XHnFoZkDEv7L3KA0=
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p22QnYVOq7PKBLe2qMCpGYydjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTh7G11qed9LU9uS7nht+c434ovyAFMeLCkHYTLVI5fwY=
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3XGW9731/b3rcTnBUpVV7cdjAdGQcIiahEY/ZKpSgLLdWk9sWz2GyOXv6qxHaW2H26fDXZ20X1h16kWUzITBbTuusrI/cx+kAef/132msRDOjT1uSoU6fTNM2FcLdxHvc=
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p2JyN4reRVmsjd9hDStHSrotCc+mJqVQceay8W/Aon4dQ==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1uWsUHzWsv+tlyIgF4nsoYQRDW3di+2lqtjRvD6Foc0OSK79yglawLMq2qfKHF0t+rzoiO7awSXeKcgiSJMfNZu89EQ821mpIbyCdOp1WNyQ==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p3cXw/c05/SMEtFN8iBNLnY4tvU5wsp5Dwccfz++DFQoQ==
,D/GeoLookout( 7540): H: oG7yKmvlgCB+MeB9ScCFjfFK6n2WxeJSk2pAGNbQ5p1QdJyd/p15/7HTe6I45I69M4svW0ahfvr+YIey5W092wGcTlQvpBSgOqyfO72Z3wUxq59dXfXVWbt+zgy3TJ0U
,E/SMD     (  285): DCD ON,
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardViewMediator( 1178): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 3
,D/PersonaManager( 1178): isKioskContainerExistOnDevice,
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/KeyguardViewMediator( 1178): doKeyguard: not showing because lockscreen is off
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/PowerManagerService(  886): [PWL] Off : 5s ago
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,V/AlarmManager(  886): waitForAlarm result :8
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 2
,V/AlarmManager(  886): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,W/Search.LoginHelper( 1574): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:m  (  886): SIOP:: AP = 310, PST = 374, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :4
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 4
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  886): stay LED for fully charged
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  886): [PWL] Off : 15s ago
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 300, PST = 357, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 30s ago
,D/SSRM:m  (  886): SIOP:: AP = 300, PST = 340, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService(  886): stay LED for fully charged
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 300, PST = 326, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at dsf.a(PG:807)
E/HttpOperation( 5768): 	at fhk.a(PG:1126)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 8 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 10 more
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at ieo.a(PG:43)
E/HttpOperation( 5768): 	at iep.a(PG:93)
E/HttpOperation( 5768): 	at fhn.a(PG:59)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/ExperimentLoader( 5768): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): 	at kfv.a(PG:65)
E/ExperimentLoader( 5768): 	at kff.u(PG:385)
E/ExperimentLoader( 5768): 	at kfb.a(PG:29)
E/ExperimentLoader( 5768): 	at kff.l(PG:132)
E/ExperimentLoader( 5768): 	at ieo.a(PG:43)
E/ExperimentLoader( 5768): 	at iep.a(PG:93)
E/ExperimentLoader( 5768): 	at fhn.a(PG:59)
E/ExperimentLoader( 5768): 	at lex.a(PG:85)
E/ExperimentLoader( 5768): 	at lex.b(PG:132)
E/ExperimentLoader( 5768): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5768): 	at fhk.a(PG:908)
E/ExperimentLoader( 5768): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5768): 	at ihi.a(PG:22)
E/ExperimentLoader( 5768): 	at kft.a(PG:91)
E/ExperimentLoader( 5768): 	at kfv.a(PG:62)
E/ExperimentLoader( 5768): 	... 12 more
E/ExperimentLoader( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5768): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5768): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5768): 	at ihi.a(PG:19)
E/ExperimentLoader( 5768): 	... 14 more
,E/SMD     (  285): DCD ON
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getaccountstatus] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at ixd.a(PG:248)
E/HttpOperation( 5768): 	at ixd.b(PG:206)
E/HttpOperation( 5768): 	at ixd.a(PG:175)
E/HttpOperation( 5768): 	at fig.a(PG:78)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
E/EsSyncAdapterService( 5768): Sync failure
E/EsSyncAdapterService( 5768): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5768): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5768): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5768): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5768): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5768): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5768): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5768): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5768): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5768): 	... 10 more
E/EsSyncAdapterService( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5768): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5768): 	... 12 more
E/EsSyncAdapterService( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5768): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5768): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5768): 	... 14 more
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 160137, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/art     (  886): Explicit concurrent mark sweep GC freed 50763(2MB) AllocSpace objects, 24(3MB) LOS objects, 30% free, 36MB/52MB, paused 1.868ms total 158.762ms
D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 5
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 50s ago
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 316, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 311, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/VacuumService( 1679): Vacuum at: now=1456920293856 tag=VacuumService
,I/GoogleURLConnFactory( 1679): Using platform SSLCertificateSocketFactory
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/common_ic_googleplayservices.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/Uploader( 1679): Failed to get auth token: User intervention required. Notification has been pushed.
E/Uploader( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
E/Uploader( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.c(SourceFile:550)
E/Uploader( 1679): 	at com.google.android.gms.auth.p.b(SourceFile:477)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
E/Uploader( 1679): 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
E/Uploader( 1679): 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/System.out( 1679): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 1679): (HTTPLog)-Static: isShipBuild true
,I/System.out( 1679): (HTTPLog)-Thread-194-481413667: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/qtaguid ( 1679): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,I/qtaguid ( 1679): Tagging socket 63 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,V/AlarmManager(  886): waitForAlarm result :8
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 52413(3MB) AllocSpace objects, 36(2MB) LOS objects, 39% free, 18MB/30MB, paused 1.013ms total 133.389ms
,W/Uploader( 1679): No account for auth token provided
,I/qtaguid ( 1679): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,W/Uploader( 1679): No account for auth token provided
,I/qtaguid ( 1679): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,W/Uploader( 1679): No account for auth token provided
,I/qtaguid ( 1679): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Uploader( 1679): No account for auth token provided
,I/qtaguid ( 1679): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,W/Uploader( 1679):  no longer exists, so no auth token.
,I/qtaguid ( 1679): Tagging socket 58 with tag 120100000000{4609,0} uid -1, pid: 1679, getuid(): 10012
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 306, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7408): Starting books sync, d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,E/SMD     (  285): DCD ON
D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5430501563962354912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5430501563962354912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5430501563962354912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 6
,I/PowerManagerService(  886): [PWL] Off : 75s ago
I/PowerManagerService(  886): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService(  886): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=886, ws=WorkSource{10082}) (elapsedTime=3721)
,E/BooksSync( 7408): Soft error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5430501563962354912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7408): Sync error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-5430501563962354912&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7408): Finished books sync
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 164793, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  886): mCursor = null
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 301, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Giving up after 6 failures.
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 298, CUR = 300
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 295, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,E/SMD     (  285): DCD ON
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 7
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/PowerManagerService(  886): [PWL] Off : 105s ago
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 293, CUR = 300
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 292, CUR = 300
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): stay LED for fully charged
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 291, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 8
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService(  886): [PWL] Off : 140s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 290, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 290, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 280, PST = 289, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 9
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 280, PST = 288, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 180s ago
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 286, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 284, CUR = 300
,E/SMD     (  285): DCD ON
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1
,D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize(  886): initializing...
,I/TLC_TIMA_PKM_initialize(  886): root = /firmware/image, root_strlen = 15
,I/TLC_TIMA_PKM_initialize(  886): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  886): root = /firmware/image, root_len = 15
,I/TZ: qc_tlc_communication(  886): process = tima_pkm, process_strlen = 8
,I/TZ: qc_tlc_communication(  886): aligned max_sendmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  886): aligned max_recvmsg_size = 262208 = 0x40040
,I/TZ: qc_tlc_communication(  886): max_message_size = 524416 = 0x80080,
D/QSEECOMAPI: (  886): QSEECom_get_handle sb_length = 0x80080,
,D/QSEECOMAPI: (  886): App is not loaded in QSEE
,D/QSEECOMAPI: (  886): Loaded image: APP id = 2
,I/TZ: qc_tlc_communication(  886): TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,I/TLC_TIMA_PKM_initialize(  886): Trustlet response is completed
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
D/BatteryService(  886): stay LED for fully charged
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0,
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5768): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at dsf.a(PG:807)
E/HttpOperation( 5768): 	at fhk.a(PG:1126)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 8 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 10 more
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at ieo.a(PG:43)
E/HttpOperation( 5768): 	at iep.a(PG:93)
E/HttpOperation( 5768): 	at fhn.a(PG:59)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/ExperimentLoader( 5768): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): 	at kfv.a(PG:65)
E/ExperimentLoader( 5768): 	at kff.u(PG:385)
E/ExperimentLoader( 5768): 	at kfb.a(PG:29)
E/ExperimentLoader( 5768): 	at kff.l(PG:132)
E/ExperimentLoader( 5768): 	at ieo.a(PG:43)
E/ExperimentLoader( 5768): 	at iep.a(PG:93)
E/ExperimentLoader( 5768): 	at fhn.a(PG:59)
E/ExperimentLoader( 5768): 	at lex.a(PG:85)
E/ExperimentLoader( 5768): 	at lex.b(PG:132)
E/ExperimentLoader( 5768): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5768): 	at fhk.a(PG:908)
E/ExperimentLoader( 5768): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5768): 	at ihi.a(PG:22)
E/ExperimentLoader( 5768): 	at kft.a(PG:91)
E/ExperimentLoader( 5768): 	at kfv.a(PG:62)
E/ExperimentLoader( 5768): 	... 12 more
E/ExperimentLoader( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5768): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5768): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5768): 	at ihi.a(PG:19)
E/ExperimentLoader( 5768): 	... 14 more
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getaccountstatus] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at ixd.a(PG:248)
E/HttpOperation( 5768): 	at ixd.b(PG:206)
E/HttpOperation( 5768): 	at ixd.a(PG:175)
E/HttpOperation( 5768): 	at fig.a(PG:78)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/EsSyncAdapterService( 5768): Sync failure
E/EsSyncAdapterService( 5768): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5768): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5768): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5768): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5768): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5768): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5768): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5768): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5768): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5768): 	... 10 more
E/EsSyncAdapterService( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5768): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5768): 	... 12 more
E/EsSyncAdapterService( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5768): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5768): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5768): 	... 14 more
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 289694, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  886): Explicit concurrent mark sweep GC freed 52250(3MB) AllocSpace objects, 56(1351KB) LOS objects, 30% free, 36MB/52MB, paused 1.838ms total 132.360ms
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  886): mCursor = null
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 290, PST = 284, CUR = 300
,E/SMD     (  285): DCD ON
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 280, PST = 283, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,V/AlarmManager(  886): waitForAlarm result :4
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/Zygote  ( 7798): MountEmulatedStorage()
,E/Zygote  ( 7798): v2
I/libpersona( 7798): KNOX_SDCARD checking this for 10081
I/libpersona( 7798): KNOX_SDCARD not a persona
,I/ActivityManager(  886): Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7798 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 7798): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 7798): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 7798): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 7798): TimaSignature is unavailable
,D/ActivityThread( 7798): Added TimaKeyStore provider
,D/ResourcesManager( 7798): creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,I/ActivityManager(  886): Killing 6852:com.sec.pcw.device/1000 (adj 15): bgCount ##41
,W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_6852/cgroup.procs: No such file or directory
,I/ServiceManager(  339): Waiting for service AtCmdFwd...,
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 281, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 11
,I/PowerManagerService(  886): [PWL] Off : 225s ago
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7408): Starting books sync, d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4926005208917771288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4926005208917771288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4926005208917771288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 279, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/BooksSync( 7408): Soft error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4926005208917771288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7408): Sync error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-4926005208917771288&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7408): Finished books sync
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 325299, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  886): mCursor = null
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_store.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
E/PlayEventLogger( 6740): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6740): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 6740): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/PlayEventLogger( 6740): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 6740): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1736)
E/PlayEventLogger( 6740): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 6740): 	at android.os.Binder.execTransact(Binder.java:446)
I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,W/System  ( 6740): Ignoring header User-Agent because its value was null.
,I/System.out( 6740): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 6740): (HTTPLog)-Static: isShipBuild true
,I/System.out( 6740): (HTTPLog)-Thread-1103-919241362: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 277, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,V/AlarmManager(  886): waitForAlarm result :8
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 3
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 275, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 12
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 274, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 275s ago
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 273, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 13
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 273, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 270, PST = 271, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 269, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 14
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 268, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 330s ago
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 267, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 266, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 1
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 15
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 265, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 2
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 264, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/bootchecker(  329): bootchecker wake up!!
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 3
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 263, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 16
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 262, CUR = 300
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 4
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 390s ago
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 261, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 17
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,E/SMD     (  285): DCD ON
,W/Atfwd_Sendcmd(  339): AtCmdFwd service not published, waiting... retryCnt : 5
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 18
,E/SMD     (  285): DCD ON
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Atfwd_Sendcmd(  339): AtCmdFwd service not ready - Exhausted retry attempts - :6
I/Atfwd_Daemon(  339): result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,I/PowerManagerService(  886): [PWL] Off : 455s ago
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/HttpOperation( 5768): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at dsf.a(PG:807)
E/HttpOperation( 5768): 	at fhk.a(PG:1126)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 8 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 10 more
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at ieo.a(PG:43)
E/HttpOperation( 5768): 	at iep.a(PG:93)
E/HttpOperation( 5768): 	at fhn.a(PG:59)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/ExperimentLoader( 5768): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): 	at kfv.a(PG:65)
E/ExperimentLoader( 5768): 	at kff.u(PG:385)
E/ExperimentLoader( 5768): 	at kfb.a(PG:29)
E/ExperimentLoader( 5768): 	at kff.l(PG:132)
E/ExperimentLoader( 5768): 	at ieo.a(PG:43)
E/ExperimentLoader( 5768): 	at iep.a(PG:93)
E/ExperimentLoader( 5768): 	at fhn.a(PG:59)
E/ExperimentLoader( 5768): 	at lex.a(PG:85)
E/ExperimentLoader( 5768): 	at lex.b(PG:132)
E/ExperimentLoader( 5768): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5768): 	at fhk.a(PG:908)
E/ExperimentLoader( 5768): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5768): 	at ihi.a(PG:22)
E/ExperimentLoader( 5768): 	at kft.a(PG:91)
E/ExperimentLoader( 5768): 	at kfv.a(PG:62)
E/ExperimentLoader( 5768): 	... 12 more
E/ExperimentLoader( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5768): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5768): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5768): 	at ihi.a(PG:19)
E/ExperimentLoader( 5768): 	... 14 more
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 47785(2MB) AllocSpace objects, 68(4MB) LOS objects, 40% free, 18MB/30MB, paused 659us total 45.455ms
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getaccountstatus] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at ixd.a(PG:248)
E/HttpOperation( 5768): 	at ixd.b(PG:206)
E/HttpOperation( 5768): 	at ixd.a(PG:175)
E/HttpOperation( 5768): 	at fig.a(PG:78)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/EsSyncAdapterService( 5768): Sync failure
E/EsSyncAdapterService( 5768): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5768): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5768): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5768): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5768): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5768): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5768): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5768): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5768): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5768): 	... 10 more
E/EsSyncAdapterService( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5768): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5768): 	... 12 more
E/EsSyncAdapterService( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5768): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5768): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5768): 	... 14 more
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 575882, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300,
,I/Atfwd_Daemon(  339): Stop the daemon....,
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 19
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/AlarmManager(  886): waitForAlarm result :8
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1,
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300,
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7408): Starting books sync, d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6582637360088359426&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/ContextImpl(  886): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Tagging socket 39 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6582637360088359426&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6582637360088359426&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/BooksSync( 7408): Soft error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6582637360088359426&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7408): Sync error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=6582637360088359426&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7408): Finished books sync
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  886): Killing 6632:com.samsung.android.app.galaxyfinder/u0a34 (adj 15): bgCount ##41
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 612894, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  886): failed to open /acct/uid_10034/pid_6632/cgroup.procs: No such file or directory
,I/art     (  886): Explicit concurrent mark sweep GC freed 59198(4MB) AllocSpace objects, 108(2MB) LOS objects, 30% free, 36MB/52MB, paused 1.871ms total 201.071ms
D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 21
,I/PowerManagerService(  886): [PWL] Off : 525s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,V/AlarmManager(  886): waitForAlarm result :8
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 22
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 23
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 600s ago
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  886): stay LED for fully charged
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 24
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/BatteryService(  886): stay LED for fully charged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 25
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 26
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService(  886): [PWL] Off : 680s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 27
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,E/SMD     (  285): DCD ON
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 28
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/Watchdog(  886): !@Sync 29
,I/PowerManagerService(  886): [PWL] Off : 765s ago
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,D/BatteryService(  886): stay LED for fully charged
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
,D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1,
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,E/SMD     (  285): DCD ON
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/Finsky  ( 6740): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/LightsService(  886): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,E/LightSensor(  886): Light old sensor_state 8192, new sensor_state : 8704 en : 1
,D/SensorManager(  886): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/EventLogService( 2457): Aggregate from 1456919127749 (log), 1456919127749 (data)
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1679): Message class com.google.f.a.a.i
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Finsky  ( 6740): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/LightSensor(  886): RED : 0, GREEN : 0, BLUE : 0, CLEAR : 0, CALCULATED LUX : 0.000000, CCT : 1596.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=0, cp1=0, cpl=3202560
,D/LightsService(  886): [SvcLED]  onSensorChanged::light value = 0
E/LightSensor(  886): Light old sensor_state 8704, new sensor_state : 8192 en : 0
,D/SensorManager(  886): unregisterListener ::   
D/LightsService(  886): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6740): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/Finsky  ( 6740): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 6740): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 6740): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6740): [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,D/DeviceConnectionService( 2272): client connected with version: 7571000
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 31
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :4
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 1.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager(  886): waitForAlarm result :8
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 2.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 32
,I/PowerManagerService(  886): [PWL] Off : 855s ago
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 3.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 33
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 4.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
D/Finsky  ( 6740): [1] 5.onFinished: Scheduling replication attempt 5.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 34
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/BatteryService(  886): stay LED for fully charged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidsecure
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidsecure without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6740): [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,D/Finsky  ( 6740): [1] 5.onFinished: Installation state replication failed.
,D/Finsky  ( 6740): [1] 5.onFinished: Giving up after 6 failures.
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 35
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,I/PowerManagerService(  886): [PWL] Off : 950s ago
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1679): Explicit concurrent mark sweep GC freed 35312(2MB) AllocSpace objects, 10(810KB) LOS objects, 40% free, 18MB/30MB, paused 437us total 26.873ms
,E/SMD     (  285): DCD ON
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/Watchdog(  886): !@Sync 36
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/HttpOperation( 5768): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at dsf.a(PG:807)
E/HttpOperation( 5768): 	at fhk.a(PG:1126)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 8 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 10 more
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getmobileexperiments] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at kff.l(PG:132)
E/HttpOperation( 5768): 	at ieo.a(PG:43)
E/HttpOperation( 5768): 	at iep.a(PG:93)
E/HttpOperation( 5768): 	at fhn.a(PG:59)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/ExperimentLoader( 5768): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 5768): 	at kfv.a(PG:65)
E/ExperimentLoader( 5768): 	at kff.u(PG:385)
E/ExperimentLoader( 5768): 	at kfb.a(PG:29)
E/ExperimentLoader( 5768): 	at kff.l(PG:132)
E/ExperimentLoader( 5768): 	at ieo.a(PG:43)
E/ExperimentLoader( 5768): 	at iep.a(PG:93)
E/ExperimentLoader( 5768): 	at fhn.a(PG:59)
E/ExperimentLoader( 5768): 	at lex.a(PG:85)
E/ExperimentLoader( 5768): 	at lex.b(PG:132)
E/ExperimentLoader( 5768): 	at fhk.a(PG:1146)
E/ExperimentLoader( 5768): 	at fhk.a(PG:908)
E/ExperimentLoader( 5768): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 5768): 	at ihi.a(PG:22)
E/ExperimentLoader( 5768): 	at kft.a(PG:91)
E/ExperimentLoader( 5768): 	at kfv.a(PG:62)
E/ExperimentLoader( 5768): 	... 12 more
E/ExperimentLoader( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 5768): 	at gde.c(Unknown Source)
E/ExperimentLoader( 5768): 	at gde.b(Unknown Source)
E/ExperimentLoader( 5768): 	at ihi.a(PG:19)
E/ExperimentLoader( 5768): 	... 14 more
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,E/HttpOperation( 5768): [getaccountstatus] Unexpected exception
E/HttpOperation( 5768): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 5768): 	at kfv.a(PG:65)
E/HttpOperation( 5768): 	at kff.u(PG:385)
E/HttpOperation( 5768): 	at kfb.a(PG:29)
E/HttpOperation( 5768): 	at ixd.a(PG:248)
E/HttpOperation( 5768): 	at ixd.b(PG:206)
E/HttpOperation( 5768): 	at ixd.a(PG:175)
E/HttpOperation( 5768): 	at fig.a(PG:78)
E/HttpOperation( 5768): 	at lex.a(PG:85)
E/HttpOperation( 5768): 	at lex.b(PG:132)
E/HttpOperation( 5768): 	at fhk.a(PG:1146)
E/HttpOperation( 5768): 	at fhk.a(PG:908)
E/HttpOperation( 5768): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 5768): 	at ihi.a(PG:22)
E/HttpOperation( 5768): 	at kft.a(PG:91)
E/HttpOperation( 5768): 	at kfv.a(PG:62)
E/HttpOperation( 5768): 	... 12 more
E/HttpOperation( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 5768): 	at gde.c(Unknown Source)
E/HttpOperation( 5768): 	at gde.b(Unknown Source)
E/HttpOperation( 5768): 	at ihi.a(PG:19)
E/HttpOperation( 5768): 	... 14 more
,E/EsSyncAdapterService( 5768): Sync failure
E/EsSyncAdapterService( 5768): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 5768): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 5768): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 5768): 	at fig.a(PG:78)
E/EsSyncAdapterService( 5768): 	at lex.a(PG:85)
E/EsSyncAdapterService( 5768): 	at lex.b(PG:132)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 5768): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 5768): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 5768): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 5768): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 5768): 	at kff.u(PG:385)
E/EsSyncAdapterService( 5768): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 5768): 	... 10 more
E/EsSyncAdapterService( 5768): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 5768): 	at kft.a(PG:91)
E/EsSyncAdapterService( 5768): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 5768): 	... 12 more
E/EsSyncAdapterService( 5768): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 5768): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 5768): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 5768): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 5768): 	... 14 more
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1093198, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  886): Explicit concurrent mark sweep GC freed 64389(4MB) AllocSpace objects, 142(2MB) LOS objects, 30% free, 36MB/52MB, paused 7.261ms total 258.405ms
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
,E/SQLiteLog( 1679): (10) POSIX Error : 11 SQLite Error : 3850
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 37
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :8
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 38
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1178): handleTimeUpdate
,D/KeyguardEffectViewController( 1178): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 1178): *** don't update sliding image ***
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
D/BatteryService(  886): stay LED for fully charged
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
I/MotionRecognitionService(  886): setPowerConnected  = true
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1178): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/BooksSync( 7408): Starting books sync, d
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ResourcesManager( 1679): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
,D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300,
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9027590701682317337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
,D/PanelView( 1178): There is/are notification(s) 
D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Tagging socket 40 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9027590701682317337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GLSUser ( 1679): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1679): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1679): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1679): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1679): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 1679): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  886): uri = 14 selection = getSealedState
,D/SecContentProvider2(  886): mCursor = null
D/SecContentProvider2(  886): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  886): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  886): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/StatusBar( 1178): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/PhoneStatusBar( 1178): Icon Only
,D/LockPatternUtilsCache( 1178): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1178): value : false
D/PanelView( 1178): There is/are notification(s) 
,D/PanelView( 1178): There is/are notification(s) 
,W/GLSActivity( 1679): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1679): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1679): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1679): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1679): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 7408): Authentication error
E/BooksAccountManager( 7408): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 7408): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,E/HttpHelper( 7408): null auth token
,I/qtaguid ( 7408): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 7408, getuid(): 10082
,I/qtaguid ( 7408): Untagging socket 34
,W/ApiaryClient( 7408): Error response from books API: {
W/ApiaryClient( 7408):  "error": {
W/ApiaryClient( 7408):   "errors": [
W/ApiaryClient( 7408):    {
W/ApiaryClient( 7408):     "domain": "global",
W/ApiaryClient( 7408):     "reason": "required",
W/ApiaryClient( 7408):     "message": "Login Required",
W/ApiaryClient( 7408):     "locationType": "header",
W/ApiaryClient( 7408):     "location": "Authorization"
W/ApiaryClient( 7408):    }
W/ApiaryClient( 7408):   ],
W/ApiaryClient( 7408):   "code": 401,
W/ApiaryClient( 7408):   "message": "Login Required"
W/ApiaryClient( 7408):  }
W/ApiaryClient( 7408): }
,W/ApiaryClient( 7408): errCount = 3: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9027590701682317337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 7408): Headers suppressed
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/BooksSync( 7408): Soft error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9027590701682317337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,E/BooksSync( 7408): Sync error
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
E/BooksSync( 7408): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-9027590701682317337&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 7408): Headers suppressed
E/BooksSync( 7408): 
E/BooksSync( 7408): com.google.android.apps.books.net.HttpHelper.wrapExceptionBasedOnStatus(HttpHelper.java:212)
,I/BooksSync( 7408): Finished books sync
,I/PowerManagerService(  886): [PWL] Off : 1050s ago
,I/PowerManagerService(  886): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService(  886): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService(  886): [PWL]       PARTIAL_WAKE_LOCK              '*sync*/com.google.android.apps.books/com.google/eM_ADDR' (uid=1000, pid=886, ws=WorkSource{10082}) (elapsedTime=4409)
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SyncManager(  886): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1164613, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager( 2866): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/ResourcesManager( 2866): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2(  886): mCursor = null
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 39
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,V/AlarmManager(  886): waitForAlarm result :4
,D/ConnectivityService(  886): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,V/AlarmManager(  886): waitForAlarm result :8
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,D/BatteryService(  886): stay LED for fully charged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/TimaService(  886): TIMA: TimaService scheduler is intialized. 
D/TimaService(  886): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService(  886): TimaServiceHandler.handleMessage what =1,
,I/UsageStatsService(  886): User[0] Flushing usage stats to disk
,I/ApplicationUsage(  886): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage(  886): Updating Usage Statistics in DB @ 1456921325376
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
,W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb(  886): ::getAppControlDB: Exception to create DB
W/System.err(  886): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err(  886): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err(  886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  886): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage(  886): Done Updating Usage Statistics in DB @ 1456921325697
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel(  886): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService(  886): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 40
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/Watchdog(  886): !@Sync 41
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,D/BatteryService(  886): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
,D/BatteryService(  886): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  886): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  886):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
,I/MotionRecognitionService(  886): Plugged
,I/MotionRecognitionService(  886): setPowerConnected  = true
,D/BatteryService(  886): stay LED for fully charged
,D/KeyguardUpdateMonitor( 1178): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1178): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 1178):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3879): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3879): Disconnected process message: 10
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1178): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,E/SMD     (  285): DCD ON
,D/SSRM:m  (  886): SIOP:: AP = 260, PST = 260, CUR = 300
,E/SMD     (  285): DCD ON
,TIME-OUT KILL (timeout was 1200000ms),E/SMD     (  285): DCD ON
D/AndroidRuntime( 8146): 
D/AndroidRuntime( 8146): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8146): CheckJNI is OFF
D/AndroidRuntime( 8146): setted country_code = Germany
D/AndroidRuntime( 8146): setted countryiso_code = DE
D/AndroidRuntime( 8146): setted sales_code = DBT
D/AndroidRuntime( 8146): readGMSProperty: start
D/AndroidRuntime( 8146): readGMSProperty: already setted!!
D/AndroidRuntime( 8146): readGMSProperty: end
D/AndroidRuntime( 8146): addProductProperty: start
E/AffinityControl( 8146): AffinityControl: registerfunction enter
D/AndroidRuntime( 8146): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService(  886): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager(  886): START PACKAGE DELETE: observer{8818751}
D/PackageManager(  886): pkg{<packageName>}
D/PackageManager(  886): user{0}
D/PackageManager(  886): caller{2000}
D/PackageManager(  886): flags{3}
D/PersonaManagerService(  886): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  886): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  886): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  886): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag3
D/PackageManager(  886): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  886): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService(  886): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy(  886): getApplicationUninstallationEnabled
D/ApplicationPolicy(  886): getApplicationUninstallationEnabled :  enabled true
D/PackageManager(  886): !@killApplicatoin: 10200, uninstall pkg
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10200 user=-1: uninstall pkg
W/PackageSettings(  886): Skipping PackageSetting{36f7fd8a com.example.hello/10201} due to missing metadata
I/ActivityManager(  886): Force stopping com.test.thalitest appid=10200 user=0: pkg removed
I/art     ( 1574): Explicit concurrent mark sweep GC freed 36035(2MB) AllocSpace objects, 2(689KB) LOS objects, 40% free, 16MB/27MB, paused 843us total 78.814ms
D/ResourcesManager(  886): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
I/art     ( 3332): Explicit concurrent mark sweep GC freed 34417(1859KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 14MB/24MB, paused 677us total 45.775ms
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
I/InputReader(  886): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
E/SamsungIME( 1870): mOCRHelper is null
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Zygote  ( 8169): MountEmulatedStorage()
E/Zygote  ( 8169): v2
I/libpersona( 8169): KNOX_SDCARD checking this for 10019
I/libpersona( 8169): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=8169 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
W/GeofencerStateMachine( 2272): Ignoring removeGeofence because network location is disabled.
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
I/SELinux ( 8169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8169): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/TimaKeyStoreProvider( 8169): TimaSignature is unavailable
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ActivityThread( 8169): Added TimaKeyStore provider
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 8169): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/SecContentProvider2(  886): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  886): mCursor = null
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/RegisteredServicesCache( 1472): empty dynamic service
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
I/KLMS-2.4.503: ( 8169): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.503: ( 8169): MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1456921378148
I/KLMS-2.4.503: ( 8169): MainReciver(): PACKAGE_REMOVED
I/KLMS-2.4.503: ( 8169): MainReciver(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/RCPManagerService(  886): PackageReceiver onReceive()
I/HarmonyEASService(  886): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/KnoxMUMContainerPolicy(  886): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
D/BackupManagerService(  886): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  886): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  886): uID is 10200
V/EnterpriseBillingPolicy(  886): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  886): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage(  886): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy(  886): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  886): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage(  886): getBillingProfileForVpnEngine - end - null
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/talkback/talkback.apk
I/art     (  886): Explicit concurrent mark sweep GC freed 49990(3MB) AllocSpace objects, 63(1203KB) LOS objects, 30% free, 37MB/53MB, paused 7.824ms total 357.062ms
D/EnterpriseDeviceManagerService(  886): Package has changed for user 0
D/EnterpriseDeviceManagerService(  886): Admin package name: com.google.android.gms
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
E/Zygote  ( 8191): MountEmulatedStorage()
E/Zygote  ( 8191): v2
I/libpersona( 8191): KNOX_SDCARD checking this for 10104
I/libpersona( 8191): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8191 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 8191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/ActivityManager(  886): Killing 4891:com.sec.android.app.shealth/u0a35 (adj 15): bgCount ##41
I/SELinux ( 8191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8191): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Books/Books.apk
D/PackageManager(  886): delete codoeFile: 
D/TimaKeyStoreProvider( 8191): TimaSignature is unavailable
D/ActivityThread( 8191): Added TimaKeyStore provider
D/PackageManager(  886): result of delete: 1{8818751}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/AndroidRuntime( 8146): Shutting down VM
D/ResourcesManager( 8191): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/SMD     (  285): DCD ON
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/elm:14451( 8191): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14451( 8191): ELMEngine.ELMEngine( context ).
D/elm:14451( 8191): MDMBridge.setEnterpriseBridge()
D/elm:14451( 8191): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/elm:14451( 8191): ElmAgentService : onCreate()
D/elm:14451( 8191): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
E/Zygote  ( 8207): MountEmulatedStorage()
E/Zygote  ( 8207): v2
I/libpersona( 8207): KNOX_SDCARD checking this for 10017
I/libpersona( 8207): KNOX_SDCARD not a persona
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/elm:14451( 8191): MainReceiver.listeningToPackageRemoved()
D/elm:14451( 8191): MDMBridge.getInstance()
D/elm:14451( 8191): MDMBridge.getAllLicenseInfoFromSDK()
I/ActivityManager(  886): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8207 uid=10017 gids={50017, 9997} abi=armeabi-v7a
W/ResourcesManager(  886): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  886): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
D/ResourcesManager(  886): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
D/ResourcesManager(  886): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
I/SELinux ( 8207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14451( 8191): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux ( 8207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
E/SELinux ( 8207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
D/elm:14451( 8191): ElmAgentService : onDestroy().
I/ActivityManager(  886): Killing 6870:com.policydm/1000 (adj 15): bgCount ##41
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TimaKeyStoreProvider( 8207): TimaSignature is unavailable
W/libprocessgroup(  886): failed to open /acct/uid_10035/pid_4891/cgroup.procs: No such file or directory
D/ResourcesManager(  886): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
D/ActivityThread( 8207): Added TimaKeyStore provider
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  886): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 8207): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
W/Resources(  886): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager(  886): clearDefaults: com.test.thalitest
I/CrashAnrDetector(  886): onPackageRemoved : com.test.thalitest
W/libprocessgroup(  886): failed to open /acct/uid_1000/pid_6870/cgroup.procs: No such file or directory
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8207): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 8207): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 8207): onReceive() : package name is not s health. Return !!!
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8224): MountEmulatedStorage()
E/Zygote  ( 8224): v2
I/libpersona( 8224): KNOX_SDCARD checking this for 1000
I/libpersona( 8224): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=8224 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager(  886): Killing 5514:com.sec.spp.push/u0a38 (adj 15): bgCount ##41
I/SELinux ( 8224): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 8224): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 8224): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  311): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 1.990ms total 70.238ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 2.546ms total 38.764ms
D/TimaKeyStoreProvider( 8224): TimaSignature is unavailable
D/ActivityThread( 8224): Added TimaKeyStore provider
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 805us total 26.106ms
W/libprocessgroup(  886): failed to open /acct/uid_10038/pid_5514/cgroup.procs: No such file or directory
D/ResourcesManager( 8224): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
I/PCWCLIENTTRACE_LOG( 8224): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 8224): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 8224): new DMDBOpenHelper instance
E/SQLiteLog( 8224): (14) cannot open file at line 32470 of [9491ba7d73]
E/SQLiteLog( 8224): (14) os_unix.c:32470: (2) open(/data/data/com.sec.pcw.device/databases/value.db) - 
F/libc    ( 8224): Fatal signal 7 (SIGBUS), code 2, fault addr 0x7581654e in tid 8224 (.sec.pcw.device)
E/audit_log( 2201): File locking failed. error= Bad file number
E/audit_log( 2201): File locking failed. error= Bad file number
I/EventHub(  886): Removing device '/dev/input/event4' due to inotify event
I/EventHub(  886): Removing device '/dev/input/event5' due to inotify event
I/ActivityManager(  886): Process com.sec.pcw.device (pid 8224)(adj 0) has died(92,621)
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/EventHub(  886): Removing device '/dev/input/event6' due to inotify event
I/Zygote  (  311): Process 8224 exited due to signal (7)
I/EventHub(  886): Removing device '/dev/input/event7' due to inotify event
E/Zygote  ( 8241): MountEmulatedStorage()
E/Zygote  ( 8241): v2
I/libpersona( 8241): KNOX_SDCARD checking this for 10034
I/libpersona( 8241): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8241 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 8241): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8241): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/EventHub(  886): Removing device '/dev/input/event8' due to inotify event
D/TimaKeyStoreProvider( 8241): TimaSignature is unavailable
D/ActivityThread( 8241): Added TimaKeyStore provider
I/EventHub(  886): Removing device '/dev/input/event9' due to inotify event
D/ResourcesManager( 8241): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/ContextImpl( 8241): Unable to create files subdir /data/data/com.samsung.android.app.galaxyfinder/cache
E/ActivityThread( 8241): Unable to setupGraphicsSupport due to missing cache directory
F/libc    ( 8241): Fatal signal 7 (SIGBUS), code 2, fault addr 0xb3b64000 in tid 8241 (pp.galaxyfinder)
F/libc    ( 8241): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2201): File locking failed. error= Bad file number
I/EventHub(  886): Removing device '/dev/input/event10' due to inotify event
I/ActivityManager(  886): Process com.samsung.android.app.galaxyfinder (pid 8241)(adj 0) has died(91,621)
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
I/EventHub(  886): Removing device '/dev/input/event11' due to inotify event
E/Zygote  ( 8256): MountEmulatedStorage()
E/Zygote  ( 8256): v2
I/libpersona( 8256): KNOX_SDCARD checking this for 10035
I/libpersona( 8256): KNOX_SDCARD not a persona
I/Zygote  (  311): Process 8241 exited due to signal (7)
I/ActivityManager(  886): Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8256 uid=10035 gids={50035, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 8256): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8256): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 8256): TimaSignature is unavailable
D/ActivityThread( 8256): Added TimaKeyStore provider
D/ResourcesManager( 8256): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
W/ContextImpl( 8256): Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
E/ActivityThread( 8256): Unable to setupGraphicsSupport due to missing cache directory
F/libc    ( 8256): Fatal signal 7 (SIGBUS), code 2, fault addr 0xa029f000 in tid 8256 (oid.app.shealth)
F/libc    ( 8256): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2201): File locking failed. error= Bad file number
I/ActivityManager(  886): Process com.sec.android.app.shealth (pid 8256)(adj 0) has died(91,622)
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  886): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8271): MountEmulatedStorage()
I/libpersona( 8271): KNOX_SDCARD checking this for 10038
E/Zygote  ( 8271): v2
I/libpersona( 8271): KNOX_SDCARD not a persona
I/ActivityManager(  886): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=8271 uid=10038 gids={50038, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Zygote  (  311): Process 8256 exited due to signal (7)
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
I/SELinux ( 8271): Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-G900F_5.0_0011
E/SELinux ( 8271): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL

```
