#### Test 61248225a3bd1fe_thali07_samsung-SM-G900F Logs


```
--------- beginning of main
E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
--------- beginning of system
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
I/Hs20UtilService( 1315): Starting #1
I/Hs20UtilService( 1315): Message received 5007
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/SHealthUpgrade(SHealthUpgradeUtil)( 1628): isShealthServiceInstalled() : HealthService is Installed.
D/SHealthUpgrade(SHealthUpgradeUtil)( 1628): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 1628): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
D/ResourcesManager( 1462): creating new AssetManager and set to /system/priv-app/CSC/CSC.apk
E/CscReceiver( 1462): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 1462): Recieve Sim State Changed : NOT_READY
W/ResourcesManager( 1462): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/BroadcastQueue(  883): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=1462, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
D/Mms/SmsReceiver( 2964): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
I/WifiApBroadcastReceiver( 1315): onReceive: action android.intent.action.SIM_STATE_CHANGED
D/SettingsProvider(  883): name = internet_call_settings_visibility
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1001
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
D/UsimDownloadBroadcastReceiver( 1462): SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 2964): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
D/Mms/TelephonyPermission( 2964): isDefault true
D/Mms/SmsReceiverService( 2964): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/Mms/SmsReceiverService( 2964): handleSIMStatus()
D/Mms/SmsReceiverService( 2964): handleSIMStatus(): SIM_STATUS = NOT_READY
E/Zygote  ( 3124): MountEmulatedStorage()
E/Zygote  ( 3124): v2
I/libpersona( 3124): KNOX_SDCARD checking this for 1000
I/libpersona( 3124): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3124 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3124): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3124): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3124): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
D/TimaKeyStoreProvider( 3124): TimaSignature is unavailable
D/ActivityThread( 3124): Added TimaKeyStore provider
D/ResourcesManager( 3124): creating new AssetManager and set to /system/app/MobileTrackerEngineTwo/MobileTrackerEngineTwo.apk
D/StatusChecker( 3124): onReceive : android.intent.action.SIM_STATE_CHANGED
D/StatusChecker( 3124): onReceive : preference initializing
E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3142): MountEmulatedStorage()
E/Zygote  ( 3142): v2
I/libpersona( 3142): KNOX_SDCARD checking this for 1000
I/libpersona( 3142): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.android.omc for broadcast com.sec.android.omc/.Receiver: pid=3142 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3142): TimaSignature is unavailable
D/ActivityThread( 3142): Added TimaKeyStore provider
D/ResourcesManager( 3142): creating new AssetManager and set to /system/app/Omc-release/Omc-release.apk
I/Omc:Receiver( 3142): onReceive : android.intent.action.SIM_STATE_CHANGED
E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.omc/files/Download/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 3142): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.omc/files/Download
I/Omc:Receiver( 3142): no simcard
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3157): MountEmulatedStorage()
E/Zygote  ( 3157): v2
I/libpersona( 3157): KNOX_SDCARD checking this for 10143
I/libpersona( 3157): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=3157 uid=10143 gids={50143, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
I/SELinux ( 3157): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3157): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3157): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3157): TimaSignature is unavailable
D/ActivityThread( 3157): Added TimaKeyStore provider
D/ResourcesManager( 3157): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
W/ResourcesManager( 3157): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3157): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3157): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
E/LightSensor(  883): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
I/VerificationLog( 3157): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
E/OperatorBookmarksSIMReceiver( 3157): onReceive runs..android.intent.action.SIM_STATE_CHANGED
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3176): MountEmulatedStorage()
E/Zygote  ( 3176): v2
I/libpersona( 3176): KNOX_SDCARD checking this for 1000
I/libpersona( 3176): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=3176 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/art     (  327): Explicit concurrent mark sweep GC freed 8725(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 281us total 14.156ms
I/SELinux ( 3176): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3176): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3176): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 260us total 8.401ms
D/TimaKeyStoreProvider( 3176): TimaSignature is unavailable
D/ActivityThread( 3176): Added TimaKeyStore provider
I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 301us total 9.060ms
D/ResourcesManager( 3176): creating new AssetManager and set to /system/app/SecSetupWizard2013/SecSetupWizard2013.apk
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3192): MountEmulatedStorage()
E/Zygote  ( 3192): v2
I/libpersona( 3192): KNOX_SDCARD checking this for 1000
I/libpersona( 3192): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=3192 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3192): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3192): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3192): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/LightSensor(  883): RED : 1, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/TimaKeyStoreProvider( 3192): TimaSignature is unavailable
D/ActivityThread( 3192): Added TimaKeyStore provider
D/ResourcesManager( 3192): creating new AssetManager and set to /system/app/SilentLog/SilentLog.apk
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3207): MountEmulatedStorage()
E/Zygote  ( 3207): v2
I/libpersona( 3207): KNOX_SDCARD checking this for 1000
I/libpersona( 3207): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=3207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3207): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3207): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SMD     (  287): DCD ON
E/SELinux ( 3207): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3207): TimaSignature is unavailable
D/ActivityThread( 3207): Added TimaKeyStore provider
D/ResourcesManager( 3207): creating new AssetManager and set to /system/app/TcpdumpService/TcpdumpService.apk
D/Mms/SmsReceiver( 2964): filterMsgServiceIntent : intent.getAction() : android.intent.action.SERVICE_STATE
D/SettingsProvider(  883): name = internet_call_settings_visibility
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1001
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
D/Mms/SmsReceiverService( 2964): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SERVICE_STATE
D/Mms/TelephonyPermission( 2964): isDefault true
D/Mms/SmsReceiverService( 2964): [SMS]Receiver handleMessage : Action =android.intent.action.SERVICE_STATE
D/Mms/TelephonyUtils( 2964): ril.currentplmn=
D/Mms/TelephonyUtils( 2964): network is not roaming
D/StatusChecker( 3124): onReceive : android.intent.action.SERVICE_STATE
D/StatusChecker( 3124): Service state changed : 3 mSub-1
D/com.sec.android.service.health.cp.common.HttpConnectionConstants( 1628): RegionGroup for  is null
D/ResourcesManager( 1685): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
W/ResourcesManager( 1685): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 1685): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/DatabaseUtils(  883): Writing exception to parcel
E/DatabaseUtils(  883): java.lang.NullPointerException: key == null
E/DatabaseUtils(  883): 	at android.util.LruCache.get(LruCache.java:112)
E/DatabaseUtils(  883): 	at com.android.providers.settings.SettingsProvider.lookupValue(SettingsProvider.java:982)
E/DatabaseUtils(  883): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:822)
E/DatabaseUtils(  883): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:370)
E/DatabaseUtils(  883): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:282)
E/DatabaseUtils(  883): 	at android.os.Binder.execTransact(Binder.java:446)
I/MultiDex( 1685): VM with version 2.1.0 has multidex support
I/MultiDex( 1685): install
D/BluetoothManager( 1628): getConnectedDevices
I/MultiDex( 1685): VM has multidex support, MultiDex support library is disabled.
D/AdaptiveEventManager( 1170): removeAdaptiveEvent() requestClass = com.sec.android.app.shealth.walkingmate.service.WalkingMateDayStepService
D/AdaptiveEventManager( 1170): M updateContainers()
D/AdaptiveEventContainerSmall( 1170): C updatePedoContainer()
D/AdaptiveEventContainerSmall( 1170): handlePedoUpdate()
D/AdaptiveEventContainerSmall( 1170): pedoEvent == null
E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 2, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=2, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/BluetoothManager( 1628): getConnectedDevices
V/JNIHelp ( 1685): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
W/ActivityThread( 1685): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 1685): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@346dba: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 1685): Installed default security provider GmsCore_OpenSSL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/ActivityManager(  883): Killing 1189:com.samsung.android.MtpApplication/1000 (adj 15): bgCount ##41
,V/UserPresentBroadcastReceiver( 2213): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_1189/cgroup.procs: No such file or directory
I/Hs20UtilService( 1315): Starting #2
I/Hs20UtilService( 1315): Message received 5007
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
I/Hs20UtilService( 1315): Starting #3
I/Hs20UtilService( 1315): Message received 5007
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 1315): DMSUtil.isNetworkConnected - flag-null, state-null
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI: CONNECTED
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     ( 1685): Explicit concurrent mark sweep GC freed 32218(1641KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 17MB/28MB, paused 349us total 49.634ms
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1315): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
I/Hs20UtilService( 1315): Starting #4
I/Hs20UtilService( 1315): Message received 5007
D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 1315): MountReceiver.onReceive - Keep current state
I/WifiStateMachine(  883): callSECApi what=220
D/WifiStateMachine(  883): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
I/SurfaceFlinger(  249): id=10 createSurf (1x1),1 flag=4, Toast
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SIP     ( 1462): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/File    ( 1462): fail readDirectory() errno=2
D/PowerManagerService(  883): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=883
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/art     ( 2213): Explicit concurrent mark sweep GC freed 37484(2MB) AllocSpace objects, 17(272KB) LOS objects, 40% free, 18MB/30MB, paused 469us total 83.824ms
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:41 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:106 [0:0] start_app:true, packagename:comandroidsystemui, cp:Accuweather, aRS:false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/AndroidRuntime( 3232): 
D/AndroidRuntime( 3232): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3232): CheckJNI is OFF
D/AndroidRuntime( 3232): setted country_code = Germany
D/AndroidRuntime( 3232): setted countryiso_code = DE
D/AndroidRuntime( 3232): setted sales_code = DBT
D/AndroidRuntime( 3232): readGMSProperty: start
D/AndroidRuntime( 3232): readGMSProperty: already setted!!
D/AndroidRuntime( 3232): readGMSProperty: end
D/AndroidRuntime( 3232): addProductProperty: start
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:150 [0:0] app on 
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/daemonapp( 1323): [MSC_Daemon]>>> WU:950 [0:0] chkNW: true
D/daemonapp( 1323): [MSC_Daemon]>>> WU:642 [0:0] Cncl30MinRftAl
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/daemonapp( 1323): [MSC_Daemon]>>> WU:950 [0:0] chkNW: true
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1026 [0:0] == cityListItem Size : 0
D/daemonapp( 1323): [MSC_Daemon]>>> RM:175 [0:0] ============== Start refreshType : 3
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1323): [MSC_Daemon]>>> RM:206 [0:0] checkCuL:0, mCityDataList : 0
D/daemonapp( 1323): [MSC_Daemon]>>> WU:796 [0:0] MR pcknme : Manual systemui
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> RM:257 [0:0] == rCL 1456842779444
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> RM:273 [0:0] EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1323): [MSC_Daemon]>>> RM:278 [0:0] checkCuL:0, getRefreshType():3
D/daemonapp( 1323): [MSC_Daemon]>>> WMCL:455 [0:0] MCL pfGetCL@NP:false
D/daemonapp( 1323): [MSC_Daemon]>>> WMCL:461 [0:0] MCL pfL set:t
D/daemonapp( 1323): [MSC_Daemon]>>> WMCL:1893 [0:0] MCL getLLoc@
D/daemonapp( 1323): [MSC_Daemon]>>> WMCL:244 [0:0] MCL getCPrvdr@
D/daemonapp( 1323): [MSC_Daemon]>>> WMCL:1952 [0:0] PrvdrErr!!
D/daemonapp( 1323): [MSC_Daemon]>>> WMCL:1954 [0:0] PrvdrErr getPerformLoc:true
D/daemonapp( 1323): [MSC_Daemon]>>> WMCL:1956 [0:0] MCL pfL set:f
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:161 [0:0] getDmCL
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1748 [0:0] CnclAtRftAl
E/SQLiteLog( 1685): (283) recovered 41 frames from WAL file /data/data/com.google.android.gms/databases/playlog.db-wal
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1818 [0:0] [setARfAam]now :1456842779473
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1820 [0:0] [setARfAam]LUT :1456864379471
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1822 [0:0] [setARfAam]interval       :3
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1824 [0:0] [setARfAam]interval ms    : 3 (21600000 ms)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1554 [0:0] util getnext by config 1456864320000
D/daemonapp( 1323): [MSC_Daemon]>>> WDBH:2171 [0:0] ud NT1456864320000
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
I/Scheduler( 1685): Use PeriodicScheduler
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1829 [0:0] [dbset]NT :1456864320000
D/SecurityLogAgent( 1721):  SeDenialReceiver : Intent Received : samsung.intent.action.knox.DENIAL_NOTIFICATION
D/SecurityLogAgent( 1721):  SeDenialReceiver : File path = /data/misc/audit/audit.old
D/daemonapp( 1323): [MSC_Daemon]>>> AWCLRH:43 [0:0] ==============rLH=====================
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/SecurityLogAgent( 1721):  SeDenialReceiver : Start file Zipping Service 
W/ContextImpl( 1721): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 android.support.v4.a.c.a:-1 com.samsung.android.securitylogagent.receivers.SeDenialReceiver.onReceive:-1 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
W/InstanceID/Rpc( 1685): Found 10012
E/Zygote  ( 3252): MountEmulatedStorage()
E/Zygote  ( 3252): v2
I/libpersona( 3252): KNOX_SDCARD checking this for 1000
I/libpersona( 3252): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.factory for broadcast com.sec.factory/.entry.FactoryTestBroadcastReceiver: pid=3252 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
D/SecurityLogAgent( 1721): FileZippingService : onHandleIntent 
D/SecurityLogAgent( 1721): FileZippingService : file path =  /data/misc/audit/audit.old
I/SELinux ( 3252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 3252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1284 [0:0] CL@AtRfr = 3
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/SecurityLogAgent( 1721): FileZippingService : onPremise disabled. Zipping..  
D/SecurityLogAgent( 1721): DenialLogFileZipCreator : createZip
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1291 [0:0]  AR_lasttime: 1456864320000
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1507 [0:0] util getnext by widget 1456864320000
D/daemonapp( 1323): [MSC_Daemon]>>> WDBH:2171 [0:0] ud NT1456864320000
D/SecurityLogAgent( 1721): DenialLogFileZipCreator : Not empty 
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1302 [0:0] NextTime       :1456864320000
D/daemonapp( 1323): [MSC_Daemon]>>> AWCLRH:191 [0:0] CLPRERtoDm
D/daemonapp( 1323): [MSC_Daemon]>>> AWCLRH:192 [0:0] send broad cast error to clock
E/AffinityControl( 3232): AffinityControl: registerfunction enter
D/SecurityLogAgent( 1721): DenialLogFileZipCreator File existence : true audit.old file size 572
D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:379 [0:0] [sendPak] PakNme size = 5
D/SecurityLogAgent( 1721): DenialLogFileZipCreator : There is no denied message in audit.old . Dismisses zipping . 
E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/SecurityLogAgent( 1721): FileZippingService : completed task. Returning wakelock . 
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/TimaKeyStoreProvider( 3252): TimaSignature is unavailable
D/ActivityThread( 3252): Added TimaKeyStore provider
D/AndroidRuntime( 3232): Calling main entry com.android.commands.am.Am
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
E/PersonaManagerService(  883): inState():  stateMachine is null !!
D/ResourcesManager( 3252): creating new AssetManager and set to /system/priv-app/DeviceTest/DeviceTest.apk
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.example.hello
I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
W/ResourcesManager( 3252): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
D/daemonapp( 1323): [MSC_Daemon]>>> WU:391 [0:0] [sendPak] PakNme = comandroidsystemui
W/ActivityManager(  883): mDVFSHelper.acquire()
D/daemonapp( 1323): [MSC_Daemon]>>> WU:438 [0:0] sendBroadcast -> resultcode = 201
D/FocusedStackFrame(  883): Set to : 0
D/Launcher.HomeView( 1476): onPause
D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 40000000
D/AndroidRuntime( 3232): Shutting down VM
D/daemonapp( 1323): [MSC_Daemon]>>> WU:391 [0:0] [sendPak] PakNme = sviewcover
D/AdaptiveEventManager( 1170): action=com.sec.android.widgetapp.ap.accuweatherdaemon.action.WEATHER_DATE_SYNC
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/daemonapp( 1323): [MSC_Daemon]>>> WU:452 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1323): [MSC_Daemon]>>> WU:391 [0:0] [sendPak] PakNme = comandroidcalendar
I/SurfaceFlinger(  249): id=11 createSurf (1x1),1 flag=404, Starting com.example.hello
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:438 [0:0] sendBroadcast -> resultcode = 201
E/Zygote  ( 3270): MountEmulatedStorage()
E/Zygote  ( 3270): v2
I/libpersona( 3270): KNOX_SDCARD checking this for 10201
I/libpersona( 3270): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3270 uid=10201 gids={50201, 9997, 3003, 3001, 3002} abi=armeabi-v7a
D/FactoryTestApp( 3252): [FactoryTestBroadcastReceiver$onReceive](3252) onReceive action=android.intent.action.BOOT_COMPLETED
W/ActivityThread( 3252): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/FactoryTestApp( 3252): [XMLDataStorage$parseXML](3252) is Live Demo : false
D/FactoryTestApp( 3252): [XMLDataStorage$parseXML](3252) modelXML=sm-g900f.dat
D/FactoryTestApp( 3252): [XMLDataStorage$parseXML](3252) deviceXML=klte.dat
D/FactoryTestApp( 3252): [XMLDataStorage$parseXML](3252) nameXML=kltexx.dat
D/FactoryTestApp( 3252): [XMLDataStorage$parseAsset](3252) parseAsset Is Started
I/SELinux ( 3270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/SELinux ( 3270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3270): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> WU:391 [0:0] [sendPak] PakNme = comyahoomobileclientandroidliveweather
I/FactoryTestApp( 3252): [XMLDataStorage$parseAsset](3252) Convert dat file: sm-g900f.dat
E/daemonapp( 1323): [MSC_Daemon]>>> WU:452 [0:0] [NameNotFoundException] sandPakage !!!!!
D/daemonapp( 1323): [MSC_Daemon]>>> WU:391 [0:0] [sendPak] PakNme = widgetappapheroaccuweather
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1323): [MSC_Daemon]>>> WU:438 [0:0] sendBroadcast -> resultcode = 201
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1314 [0:0] RhTy : 3, ResponseCount :1, Listsize : 0
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1319 [0:0] =======RefreshType:1 End RetThd Current===========
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1206 [0:0] resetRefreshThread : 0
D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/AdaptiveEventManager( 1170): getCheckCurrent: result = 0
D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020464/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_signal_in.png
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/TimaKeyStoreProvider( 3270): TimaSignature is unavailable
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1409 [0:0] getBManualRefreshState : false, checkCurrentLocation : 0
D/daemonapp( 1323): [MSC_Daemon]>>> RM:1323 [0:0] send broad cast to clock Cur
D/ActivityThread( 3270): Added TimaKeyStore provider
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  883): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/MicrophoneInputStream( 1559): mic_close gfk@1aabab86
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/Launcher.HomeView( 1476): onStop
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2151): [237392/6] Surface widget pause on instance = 1
D/accuweather( 2151): [KK AccuPhone]>>> SWW:239 [0:0] [SWW] onPause : instance = 1
D/SurfaceWidgetClient$ISurfaceWidgetStub( 2151): [237392/6] Surface widget visibility changed visibility = false on instance = 1
V/AudioPolicyManager(  292): stopInput() input 23
D/accuweather( 2151): [KK AccuPhone]>>> SWW:254 [0:0] onPause : size = 0
D/accuweather( 2151): [KK AccuPhone]>>> SWW:545 [0:0]  unRegisterTTReceiver !! 
V/AudioPolicyManager(  292): releaseInput() 23
V/AudioPolicyManager(  292): closeInput(23)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/audio_hw_primary(  292): in_standby: enter
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/HotwordRecognitionRnr( 1559): Hotword detection finished
I/HotwordRecognitionRnr( 1559): Stopping hotword detection.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetView( 1476): destroyHardwareResources():121082362
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/FactoryTestApp( 3252): [XMLDataStorage$parseAsset](3252) Decode base file: factory.dat
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/accuweather( 2151): [KK AccuPhone]>>> WR:132 [0:0] onPause
D/accuweather( 2151): [KK AccuPhone]>>> SM:538 [0:0] onPause
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 3270): creating new AssetManager and set to /data/app/com.example.hello-1/base.apk
E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/audio_hw_primary(  292): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  292): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  292): disable_audio_route: reset mixer path: audio-record
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  292): Setting mixer control: value: 0
,D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): disable_audio_route: exit
V/audio_hw_primary(  292): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: DEC2 Volume
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): Setting mixer control: SLIM TX7 MUX, value: 0
D/audio_route(  292): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  292): Setting mixer control: value: 0
D/audio_route(  292): Setting mixer control: DEC2 MUX, value: 0
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): stop_input_stream: exit: status(0)
V/audio_hw_primary(  292): in_standby: exit:  status(0)
V/audio_hw_primary(  292): adev_close_input_stream
V/audio_hw_primary(  292): in_standby: enter
V/audio_hw_primary(  292): in_standby: exit:  status(0)
E/audio_hw_primary(  292): adev_close_input_stream, set jack_in to null
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/AudioPolicyManager(  292): releaseInput() exit
D/Launcher( 1476): onTrimMemory. Level: 20
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/SurfaceWidgetView( 1476): destroyHardwareResources():121082362
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/BitmapFactory( 1476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic_none.png
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FACTORY_TEST_APP
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FACTORY_TEST_COMMAND
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=MODEL_NAME
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=MODEL_NUMBER
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=MODEL_HARDWARE_REVISION
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=MODEL_COMMUNICATION_MODE
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=CHIPSET_MANUFACTURE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=CHIPSET_NAME
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=DEVICE_TYPE
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=PANEL_TYPE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SENSOR_NAME_ACCELEROMETER
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SENSOR_NAME_MAGNETIC
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SENSOR_NAME_GYROSCOPE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SENSOR_NAME_GESTURE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=REAR_CAMERA_TYPE
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FRONT_CAMERA_TYPE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=ISP_FLASH_TEST_SMD
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TORCH_MODE_FLASH_ON_CURRENT
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SPEAKER_COUNT
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=MIC_COUNT
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SVC_LED_TEST_BRIGHTNESS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_VIBRATOR
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_LTE
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_QWERTY_KEY
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_FRONT_CAMERA
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_RCV
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FACTORY_TEST_APO
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_NVBACKUP_CMD
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_EPEN
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_SENSORHUB
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_CAM_ISP
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_SECOND_MIC_TEST
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_IRLED_FEEDBACK_IC
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HW_VER_EFS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_BOOK_COVER
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_INNER_OUTER_TOUCHKEY
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=USE_DIFFERENT_THD
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_HOVER_HIGHTLIGHT
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FACTOLOG_SYSTEM_INFO_UPDATE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_AUTO_WAKELOCK
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_SUPPORT_SENSOR_HUB_CHG
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_GLOVE_MODE
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_AP_EX_THERM_ADC
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FONT_SIZE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SEMI_FUNCTION_FONT_SIZE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=RAM_SIZE_IF
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_SEMI_FUNCTION_TEST
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SEMI_FUNCTION_TEST_UI_ORIENTATION
I/WebViewFactory( 3270): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SUPPORT_WATERPROOF_TEST
D/ResourcesManager( 3270): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_VOLUME_UP
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_VOLUME_DOWN
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_POWER
,I/LibraryLoader( 3270): Loading: webviewchromium
,I/LibraryLoader( 3270): Time to load native libraries: 2 ms (timestamps 6446-6448)
,I/LibraryLoader( 3270): Expected native library version number "",actual native library version number ""
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_APP_RECENT
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_HOME
,V/WebViewChromiumFactoryProvider( 3270): Binding Chromium to main looper Looper (main, tid 1) {318038ec}
,I/LibraryLoader( 3270): Expected native library version number "",actual native library version number ""
I/chromium( 3270): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_BACK
,I/BrowserStartupController( 3270): Initializing chromium process, renderers=0
,W/art     ( 3270): Attempt to remove local handle scope entry from IRT, ignoring
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_SEARCH
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_FOCUS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_CAMERA
W/chromium( 3270): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
I/chromium( 3270): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
I/chromium( 3270): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
D/BluetoothAdapter( 3270): 393761973: getState() :  mService = null. Returning STATE_OFF
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_F1
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_TOUCH_KEY_ODER
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_TEST_VIEW_TABLE
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_KEY_TEST_THRESHOLD
I/Adreno-EGL( 3270): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 3270): OpenGL ES Shader Compiler Version: E031.25.01.03
I/Adreno-EGL( 3270): Build Date: 03/03/15 Tue
I/Adreno-EGL( 3270): Local Branch: LA.BF.1.1_RB1_20150108_025_1077123_1158499
I/Adreno-EGL( 3270): Remote Branch: 
I/Adreno-EGL( 3270): Local Patches: 
I/Adreno-EGL( 3270): Reconstruct Branch: 
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_TSP_STANDARD_CHANNEL
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_SENSOR_TEST_ACC_REVERSE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SENSOR_TEST_ACC_BIT
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SEMI_KEY_TEST_VOLUME_UP
,E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SEMI_KEY_TEST_VOLUME_DOWN
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_VIBETONZ_UNSUPPORTED
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_IRLED_TEST_SPLIT_COMMAND
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=AT_GPSSTEST
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=AT_BATTEST_RESET_WHEN_READ
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=PA0_TEMP_ADC
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=PA1_TEMP_ADC
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=NEED_ACK_FOR_CAMERA_STOP
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HALL_IC_TEST
,W/chromium( 3270): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HUMITEMP_TEST
,W/chromium( 3270): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_NEW_TSP_SELFTEST_SYNAPTICS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=GESTURE_SENSOR_PEEK_TO_PEEK
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=GESTURE_SENSOR_IR_CURRENT_CHANGE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=IS_TSP_HOVERING_TEST_SET_EDGE_DEADLOCK
W/art     ( 3270): Attempt to remove local handle scope entry from IRT, ignoring
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SIMPLE_TEST_MEGACAM_SCALE_VALUE
,W/AwContents( 3270): onDetachedFromWindow called when already detached. Ignoring
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SYS_INFO_FONT_SIZE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SYS_INFO_MEMORY_SIZE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SYS_INFO_OUT_POSITION
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_NODE_COUNT_WIDTH
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_NODE_COUNT_HEIGHT
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_DEADZONE_WIDTH
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_DEADZONE_HEIGHT
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SPEN_NODE_COUNT_WIDTH
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SPEN_NODE_COUNT_HEIGHT
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_SPEC_MAX_MINUS_MIN
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_MIN_SYNAPTICS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_MAX_SYNAPTICS
,D/SystemWebViewEngine( 3270): CordovaWebView is running on device made by: samsung
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_HOVERING_MIN_Y_SYNAPTICS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_HOVERING_MAX_Y_SYNAPTICS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_HOVERING_MIN_X_SYNAPTICS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_HOVERING_MAX_X_SYNAPTICS
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_REFRENCE_GAP_X_SYNAPTICS
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_SELFTEST_REFRENCE_GAP_Y_SYNAPTICS
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TOUCH_KEY_SPEC_MIN
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TOUCH_KEY_SPEC_MAX
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TOUCH_KEY_OUTER_SPEC_MIN
V/AlarmManager(  883): waitForAlarm result :8
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TOUCH_KEY_OUTER_SPEC_MAX
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_PRIMARY_PIXEL_START
,W/art     ( 3270): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3270): Attempt to remove local handle scope entry from IRT, ignoring
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1170): handleTimeUpdate
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_PRIMARY_PIXEL_END
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_SECONDARY_PIXEL_START
D/KeyguardEffectViewController( 1170): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1170): *** don't update sliding image ***
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_SECONDARY_PIXEL_END
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_PRIMARY_SPEC_MIN
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_PRIMARY_SPEC_MAX
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_SECONDARY_SPEC_MIN
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_SECONDARY_SPEC_AVG
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_PRIMARY_SPEC_AVG
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_PRIMARY_SPEC_MAX
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_SECONDARY_SPEC_AVG
,D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_SECONDARY_SPEC_MAX
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_SECTION1_SPEC_MAX
D/DateView( 1170): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_SECTION1_SPEC_AVG
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_SECTION2_SPEC_MAX
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=FINGERPRINT_STDEV_SECTION2_SPEC_AVG
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MIN
,D/BatteryService(  883): level:100, scale:100, status:2, health:2, present:true, voltage: 4228, temperature: 264, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303749, invalid charger:0
D/BatteryService(  883): online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000
,D/BatteryService(  883): Sending ACTION_BATTERY_CHANGED.
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BATTERY_CHANGED
I/MotionRecognitionService(  883): Plugged
I/MotionRecognitionService(  883): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1170): handleBatteryUpdate
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=GESTURESENSOR_PEEK_TO_PEEK_SPEC_MAX
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=BOOTLOADER_VERSION
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=BATTERY_TEST_MODE
,D/STATUSBAR-PhoneStatusBar( 1170):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=BATTERY_VOLT_AVER
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=BATTERY_VF_OCV
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=APCHIP_TEMP_ADC
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=PA0_THERMISTER_CELCIUS
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1170): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=SEC_EXT_THERMISTER_TEMP
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=PA0_THERMISTER_ADC
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=PA1_THERMISTER_ADC
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/GAV4    ( 2807): Thread[GAThread,5,main]: No campaign data found.
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_COMMAND_CMD
,E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
D/Activity( 3270): performCreate Call secproduct feature valuefalse
D/Activity( 3270): performCreate Call debug elastic valuetrue
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_COMMAND_STATUS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=TSP_COMMAND_RESULT
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/OpenGLRenderer( 3270): Render dirty regions requested: true
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=LED_RED
,D/ActivityManager(  883): post active user change for 0
,D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=LED_GREEN
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=LED_BLUE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode(),
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=PATH_HALLIC_STATE
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=KEY_PRESSED_POWER
,I/SurfaceFlinger(  249): id=12 createSurf (1x1),1 flag=404, com.example.hello/com.example.hello.MainActivity
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HUMITEMP_THERMISTER_PAM
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HUMITEMP_THERMISTER_BATT
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HUMITEMP_THERMISTER_BATT_CELCIUS
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HUMITEMP_THERMISTER_S_HUB_BATT
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=HUMITEMP_THERMISTER_S_HUB_BATT_CELCIUS
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [XMLDataStorage$redefinitionById](3252) id=USB3_TYPE_CHECK
,I/OpenGLRenderer( 3270): Initialized EGL, version 1.4
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/OpenGLRenderer( 3270): HWUI protection enabled for context ,  &this =0xa161eb00 ,&mEglDisplay = 1 , &mEglConfig = 8 
,D/OpenGLRenderer( 3270): Enabling debug mode 0
,D/FactoryTestApp( 3252): [XMLDataStorage$parseAsset](3252) SemiFunctionMenu
,D/FactoryTestApp( 3252): [XMLDataStorage$parseAsset](3252) parseAsset Is Completed
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=EFS_FACTORYAPP_ROOT_PATH, path=/efs/FactoryApp/
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=CHIPSET_MANUFACTURE, value=Qualcomm
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=CHIPSET_MANUFACTURE, value=Qualcomm
D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=CHIPSET_MANUFACTURE, value=Qualcomm
I/FactoryTestApp( 3252): [ModuleCommon$ModuleCommon](3252) Create ModuleCommon
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=FACTORY_MODE, path=/efs/FactoryApp/factorymode
,D/FactoryTestApp( 3252): [Support$Kernel.read](3252) path=/efs/FactoryApp/factorymode, value=ON
I/FactoryTestApp( 3252): [ModuleCommon$readFactoryMode](3252) mode: ON
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 3252): [FactoryTestBroadcastReceiver$onReceive](3252) KEYSTRING_BLOCK is already existed...
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=KEYSTRING_BLOCK, path=/efs/FactoryApp/keystr
D/FactoryTestApp( 3252): [Support$Values.getBoolean](3252) id=INBATT_SAVE_SOC, value=false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=BINARY_TYPE, key=ro.factory.factory_binary
D/FactoryTestApp( 3252): [Support$Properties.get](3252) property=ro.factory.factory_binary
,D/FactoryTestApp( 3252): [FactoryTestBroadcastReceiver$onReceive](3252) Boot completed, IS_FACTORY_BINARY = USER MODE
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (4/10)
,I/SurfaceFlinger(  249): id=8 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/10)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/FactoryTestApp( 3252): [ModuleCommon$getFtClientEnableState](3252) result : false
,I/FactoryTestApp( 3252): [ModuleCommon$connectedJIG](3252) ...
D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=ANYWAY_JIG_CABLE_TYPE, value=ANYWAY_JIG
I/FactoryTestApp( 3252): [ModuleCommon$connectedJIG](3252) cable_type = ANYWAY_JIG
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=ANYWAY_JIG, path=/sys/class/sec/switch/adc
,D/FactoryTestApp( 3252): [Support$Kernel.read](3252) path=/sys/class/sec/switch/adc, value=1f
,I/FactoryTestApp( 3252): [ModuleCommon$connectedJIG](3252) value = 1f, JIG_ON = 1C
D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3252): [ModuleCommon$isConnectionModeNone](3252) mConnectionMode = gsm
I/FactoryTestApp( 3252): [ModuleCommon$isRunningFtClient](3252) RUNNING_FTCLIENT : false
,I/FactoryTestApp( 3252): [FactoryTestBroadcastReceiver$startDummyFtClientForBootCompleted](3252) start DummyFtClient service for APO
,W/ContextImpl( 3252): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.factory.entry.FactoryTestBroadcastReceiver.startDummyFtClientForBootCompleted:326 com.sec.factory.entry.FactoryTestBroadcastReceiver.onReceive:187 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/FactoryTest( 3252): User mode
,I/FactoryTestApp( 3252): [ModuleCommon$disableFtClient](3252) ...
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 3322): MountEmulatedStorage()
I/libpersona( 3322): KNOX_SDCARD checking this for 10150
E/Zygote  ( 3322): v2
I/libpersona( 3322): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.android.calendar for broadcast com.android.calendar/.preference.CscReceiver: pid=3322 uid=10150 gids={50150, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,D/FactoryTestApp( 3252): [DummyFtClient$onCreate](3252) Create DummyFtClient service
I/FactoryTestApp( 3252): [XMLDataStorage$parsingXML](3252) FtClient => data parsing was completed.
D/FactoryTestApp( 3252): [DummyFtClient$onReceive](3252) ACTION_SIM_STATE_CHANGED => XML data parsing was failed.
,E/LightSensor(  883): RED : 0, GREEN : 0, BLUE : 1, CLEAR : 1, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=0, bp1=1, cp1=1, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/SELinux ( 3322): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3252): [ModuleCommon$isConnectionModeNone](3252) mConnectionMode = gsm
,I/SELinux ( 3322): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3322): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/FactoryTestApp( 3252): [Support$Values.getBoolean](3252) id=SUPPORT_AUTO_WAKELOCK, value=false
,D/FactoryTestApp( 3252): [DummyFtClient$onStartCommand](3252) ...
,I/ActivityManager(  883): Displayed com.example.hello/.MainActivity: +695ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 3270): Timeline: Activity_idle id: android.os.BinderProxy@3279b51c time:26898
,I/SamsungIME( 1869): getCurrentCandidateView
,D/TimaKeyStoreProvider( 3322): TimaSignature is unavailable
,D/ActivityThread( 3322): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 3322): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ResourcesManager( 3322): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3322): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3322): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/chromium( 3270): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3270): Unable to open asset URL: file:///android_asset/www/jxcore.js
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 1869): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/candidate_button_bg_expand_pressed.qmg
,V/BitmapFactory( 1869): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/candidate_button_bg_expand.qmg
,D/SamsungIME( 1869): Dismiss ExpandCandiate
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SamsungIME( 1869): getDebugLevel  : 0x4f4c
,D/JsMessageQueue( 3270): Set native->JS mode to OnlineEventsBridgeMode
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/chromium( 3270): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3270): 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/ActivityManager(  883): mDVFSHelper.release()
,I/Timeline(  883): Timeline: Activity_windows_visible id: ActivityRecord{1ffbd012 u0 com.example.hello/.MainActivity t26} time:27064
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/DevicePolicyManagerService(  883): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  883): getAllowBluetoothMode - value retunrs : 2
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
I/SamsungIME( 1869): getDebugLevel  : 0x4f4c
E/Zygote  ( 3345): MountEmulatedStorage()
E/Zygote  ( 3345): v2
I/libpersona( 3345): KNOX_SDCARD checking this for 1002
I/libpersona( 3345): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=3345 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,I/SELinux ( 3345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
E/SELinux ( 3345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiService(  883): android.intent.action.BOOT_COMPLETED
,D/UsbDeviceManager(  883): boot completed
,D/UsbDeviceManager(  883): handleMessage -> MSG_BOOT_COMPLETED
,D/UsbDeviceManager(  883): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/UsbDeviceManager(  883): broadcasting Intent { act=android.hardware.usb.action.USB_STATE flg=0x20000000 (has extras) } connected: true configured: true
,D/UsbDeviceManager(  883): sending intent : ACTION_USB_STATE : connected = true, configured = true, functions = mtp,adb
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=11 Removed Starting com.example.hello (6/9)
D/jxcore_app_log( 3270): JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1259361664
,D/JX-Cordova( 3270): jxcore cordova android initializing
I/SurfaceFlinger(  249): id=11 Removed Starting com.example.hello (-2/9)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SamsungIME( 1869): KeybaordView init() : load resources
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KeyguardUpdateMonitor( 1170): received broadcast android.intent.action.BOOT_COMPLETED
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/talkback/talkback.apk
,E/Adreno-ES20( 3270): <check_framebuffer_attachment:854>: Invalid texture format! Returning error!
E/Adreno-ES20( 3270): <check_framebuffer_object_status:1237>: Framebuffer color attachment incomplete. Returning GL_FRAMEBUFFER_INCOMPLETE_ATTACHMENT!
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PalmMotion(  883): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotion(  883): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/LightsService(  883): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 883) 
D/LightsService(  883): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService(  883): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService(  883): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TimaKeyStoreProvider( 3345): TimaSignature is unavailable
,D/NfcService( 1455): call the applyRotuiing
,D/ActivityThread( 3345): Added TimaKeyStore provider
,V/BitmapFactory( 1869): DecodeImagePath(decodeResourceStream3) : res/drawable/popup_bg_left.qmg
,D/SLocation(  883): handleMessage got exceptionjava.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
,D/ResourcesManager( 3345): creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,W/ResourcesManager( 3345): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,W/ResourcesManager( 3345): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/RecoverySystem(  883): !@RecoverySystem handleAftermath
,I/RecoverySystem(  883): No recovery log file
,E/RecoverySystem(  883): Error copy recovery logs : /cache/recovery/last_last_kernel: open failed: ENOENT (No such file or directory)
E/RecoverySystem(  883): Error copy recovery logs : /cache/recovery/last_recovery_contents: open failed: ENOENT (No such file or directory)
E/RecoverySystem(  883): Error copy recovery logs : /cache/recovery/last_history: open failed: ENOENT (No such file or directory)
,V/BitmapFactory( 1869): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/preview_qwerty_key_icon_space_left_arrow.qmg
,V/BitmapFactory( 1869): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/preview_qwerty_key_icon_space_right_arrow.qmg
I/SamsungIME( 1869): getCurrentKeyboard
I/SamsungIME( 1869): getTextKeyboard
,D/BluetoothAdapterApp( 3345): Load D/L JNI Library
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,W/System.err(  883): java.lang.NullPointerException: Attempt to invoke virtual method 'void com.samsung.location.currentloc.SCurrentLocationManager.handleSCurLocScreenOn()' on a null object reference
W/System.err(  883): 	at com.samsung.location.lib.h.handleMessage(Unknown Source)
,W/System.err(  883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(  883): 	at android.os.Looper.loop(Looper.java:145)
W/System.err(  883): 	at com.samsung.location.SLocationService.run(Unknown Source)
,W/System.err(  883): 	at java.lang.Thread.run(Thread.java:818)
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/BluetoothA2dpSinkServiceJni( 3345): register_com_android_bluetooth_a2dp_sink
,D/BluetoothAdapterApp( 3345): REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@29d04bf2 Instance Count = 1
,E/Zygote  ( 3370): MountEmulatedStorage()
E/Zygote  ( 3370): v2
I/libpersona( 3370): KNOX_SDCARD checking this for 1000
I/libpersona( 3370): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.android.keychain for service com.android.keychain/.KeyChainService: pid=3370 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Books/Books.apk
,W/jxcore-log( 3270): Initializing JXcore engine
W/jxcore-log( 3270): JXcore engine is ready
,W/jxcore-log( 3270): Starting JXcore engine
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/Reset_Reason(  883): resetString = BPON
,V/BitmapFactory( 1869): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/qwerty_key_icon_backspace_pressed.qmg
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,V/BitmapFactory( 1869): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/qwerty_key_icon_backspace.qmg
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/BootReceiver(  883): Copying audit failures to DropBox
,I/BootReceiver(  883): Checking for fsck errors
,I/SELinux ( 3370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/BootReceiver(  883): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
I/SELinux ( 3370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3370): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3380): MountEmulatedStorage()
,E/Zygote  ( 3380): v2
I/libpersona( 3380): KNOX_SDCARD checking this for 1000
E/SharedPreferencesImpl(  883): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
I/libpersona( 3380): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=3380 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/SamsungIME( 1869): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/BootReceiver(  883): Copying /data/tombstones/tombstone_01 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  883): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,D/SamsungIME( 1869): showDlgMsgBox : false true true
,I/BootReceiver(  883): Copying /data/tombstones/tombstone_02 to DropBox (SYSTEM_TOMBSTONE)
,E/SharedPreferencesImpl(  883): Couldn't create directory for SharedPreferences file shared_prefs/log_files.xml
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,E/auditd  ( 2137): In denial and Property audit_ondenial is set to 1 
,D/SecurityLogAgent:SEDenialService(  883): Got Modify Event and sending Denial Intent foraudit.log
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/SELinux ( 3380): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3380): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3380): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3370): TimaSignature is unavailable
,D/ActivityThread( 3370): Added TimaKeyStore provider
,D/BluetoothAdapterApp( 3345): onCreate
,D/BtSettings.ProfileConfig( 3345): Adding GattService
,D/SecurityLogAgent:SEDenialService(  883): audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,D/BtSettings.ProfileConfig( 3345): Adding HeadsetService
,D/BtSettings.ProfileConfig( 3345): Adding A2dpService
D/BtSettings.ProfileConfig( 3345): Adding HidService
,D/BtSettings.ProfileConfig( 3345): Adding HealthService
,D/BtSettings.ProfileConfig( 3345): Adding PanService
D/BtSettings.ProfileConfig( 3345): Adding BluetoothMapService
,D/BtSettings.ProfileConfig( 3345): Adding SapService
D/BtSettings.ProfileConfig( 3345): Adding HeadsetClientService
D/BtSettings.ProfileConfig( 3345): Adding A2dpSinkService
,D/BtSettings.ProfileConfig( 3345): Adding SapClientService
,D/BtSettings.ProfileConfig( 3345): Adding HidDevService
,I/BtSettings.ProfileConfig( 3345): *********Initializing Bluetooth Profile Settings*******
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3380): TimaSignature is unavailable
,D/ActivityThread( 3380): Added TimaKeyStore provider
,D/ResourcesManager( 3370): creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,I/ActivityManager(  883): Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=3405 uid=10135 gids={50135, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,E/Zygote  ( 3405): MountEmulatedStorage()
I/libpersona( 3405): KNOX_SDCARD checking this for 10135
E/Zygote  ( 3405): v2
I/libpersona( 3405): KNOX_SDCARD not a persona
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/SELinux ( 3405): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3405): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3405): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/CrashAnrDetector(  883): Build: samsung/kltexx/klte:5.0/LRX21T/G900FXXU1BOD3:user/release-keys
D/CrashAnrDetector(  883): Hardware: MSM8974
D/CrashAnrDetector(  883): Revision: 14
D/CrashAnrDetector(  883): Bootloader: G900FXXU1BOD3
D/CrashAnrDetector(  883): Radio: unknown
D/CrashAnrDetector(  883): Kernel: Linux version 3.4.0-4664691 (dpi@SWDD6202) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Thu Apr 9 17:38:07 KST 2015
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector(  883): Build fingerprint: 'samsung/kltexx/klte:5.0/LRX21T/G900FXXU1BOD3:user/release-keys'
D/CrashAnrDetector(  883): Revision: '14'
D/CrashAnrDetector(  883): ABI: 'arm'
D/CrashAnrDetector(  883): pid: 7505, tid: 8839, name: Thread-1242  >>> com.test.thalitest <<<
D/CrashAnrDetector(  883): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x8ed5dff0
D/CrashAnrDetector(  883):     r0 70d27380  r1 730abb58  r2 13275f80  r3 131ee240
D/CrashAnrDetector(  883):     r4 000000c4  r5 70d27380  r6 730abb58  r7 131ee240
D/CrashAnrDetector(  883):     r8 730abb00  r9 ab533000  sl 13275f80  fp 8ee5f840
D/CrashAnrDetector(  883):     ip 8ed5dff0  sp 8ed5fff0  lr 75a9e299  pc 75a9e21c  cpsr a00f0030
D/CrashAnrDetector(  883):     d0  0000000000000000  d1  0000000000000000
D/CrashAnrDetector(  883):     d2  0000000000000000  d3  0000000000000000
D/CrashAnrDetector(  883):     d4  4040404000404040  d5  0004000400040004
D/CrashAnrDetector(  883):     d6  0000000000000000  d7  0000000300040004
D/CrashAnrDetector(  883):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector(  883):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector(  883):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector(  883):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector(  883):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector(  883):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector(  883):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector(  883):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector(  883):     d24 4040404040004040  d25 0040404000404040
D/CrashAnrDetector(  883):     d26 0b0b0b0b0b0b0b0b  d27 0b0b0b0b0b0b0b0b
D/CrashAnrDetector(  883):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector(  883):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector(  883):     scr 20000013
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): backtrace:
D/CrashAnrDetector(  883):     #00 pc 0009221c  /system/framework/arm/boot.oat
D/CrashAnrDetector(  883):     #01 pc 00092297  /system/framework/arm/boot.oat
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): stack:
D/CrashAnrDetector(  883):          8ed5ffb0  00000000  
D/CrashAnrDetector(  883):          8ed5ffb4  00000000  
D/CrashAnrDetector(  883):          8ed5ffb8  00000000  
D/CrashAnrDetector(  883):          8ed5ffbc  00000000  
D/CrashAnrDetector(  883):          8ed5ffc0  00000000  
D/CrashAnrDetector(  883):          8ed5ffc4  00000000  
D/CrashAnrDetector(  883):          8ed5ffc8  00000000  
D/CrashAnrDetector(  883):          8ed5ffcc  00000000  
D/CrashAnrDetector(  883):          8ed5ffd0  70d14b10  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          8ed5ffd4  00000000  
D/CrashAnrDetector(  883):          8ed5ffd8  00000000  
D/CrashAnrDetector(  883):          8ed5ffdc  00000000  
D/CrashAnrDetector(  883):          8ed5ffe0  00000000  
D/CrashAnrDetector(  883):          8ed5ffe4  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          8ed5ffe8  e3a070ad  
D/CrashAnrDetector(  883):          8ed5ffec  ef9000ad  
D/CrashAnrDetector(  883):     #00  8ed5fff0  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          ........  ........
D/CrashAnrDetector(  883):     #01  8ed5fff0  70d27380  /data/dalvik-cache/arm/system@framewo,rk@boot.art
D/CrashAnrDetector(  883):          8ed5fff4  00000000  
D/CrashAnrDetector(  883):          8ed5fff8  00000000  
D/CrashAnrDetector(  883):          8ed5fffc  00000000  
D/CrashAnrDetector(  883):          8ed60000  00000000  
D/CrashAnrDetector(  883):          8ed60004  00000000  
D/CrashAnrDetector(  883):          8ed60008  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          8ed6000c  730abb00  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          8ed60010  131ee240  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  883):          8ed60014  730abb58  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          8ed60018  13275f80  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  883):          8ed6001c  75a9e24d  /system/framework/arm/boot.oat
D/CrashAnrDetector(  883):          8ed60020  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          8ed60024  00000000  
D/CrashAnrDetector(  883):          8ed60028  00000000  
D/CrashAnrDetector(  883):          8ed6002c  00000000  
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): memory near r0:
D/CrashAnrDetector(  883):     70d27360 00000002 70d268d8 70d27370 00000000  
D/CrashAnrDetector(  883):     70d27370 70c2e700 00000000 00000001 70d27380  
D/CrashAnrDetector(  883):     70d27380 70c2e8a0 00000000 70d26cc0 70c2ead0  
D/CrashAnrDetector(  883):     70d27390 70c44268 70c46d30 75a0c009 00000000  
D/CrashAnrDetector(  883):     70d273a0 00000000 00000000 75a9e219 00000000  
D/CrashAnrDetector(  883):     70d273b0 752d061a 00000000 00080001 000b43d4  
D/CrashAnrDetector(  883):     70d273c0 00000e2e 00000023 70c469c0 00000000  
D/CrashAnrDetector(  883):     70d273d0 70d273e0 00000015 32ca2cc1 00000000  
D/CrashAnrDetector(  883):     70d273e0 70c5e178 00000000 00000015 0061006a  
D/CrashAnrDetector(  883):     70d273f0 00610076 006c002e 006e0061 002e0067  
D/CrashAnrDetector(  883):     70d27400 00680054 00650072 00640061 00720047  
D/CrashAnrDetector(  883):     70d27410 0075006f 00000070 70c5e640 00000000  
D/CrashAnrDetector(  883):     70d27420 00000002 70d27430 70d27448 00000000  
D/CrashAnrDetector(  883):     70d27430 70c5e7e0 00000000 70d26cc0 00000018  
D/CrashAnrDetector(  883):     70d27440 000008a9 00000200 70c5e7e0 00000000  
D/CrashAnrDetector(  883):     70d27450 70d26cc0 00000018 000008ad 00000204  
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): memory near r1:
D/CrashAnrDetector(  883): processName:com.test.thalitest
D/CrashAnrDetector(  883): broadcastEvent : null SYSTEM_TOMBSTONE
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1643 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/TimaKeyStoreProvider( 3405): TimaSignature is unavailable
,D/ActivityThread( 3405): Added TimaKeyStore provider
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.gatt.GattService
,D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/ResourcesManager( 3380): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
,D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,W/jxcore-log( 3270): Platform android
W/jxcore-log( 3270): 
,W/jxcore-log( 3270): Process ARCH arm
W/jxcore-log( 3270): 
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/CrashAnrDetector(  883): Build: samsung/kltexx/klte:5.0/LRX21T/G900FXXU1BOD3:user/release-keys
D/CrashAnrDetector(  883): Hardware: MSM8974
D/CrashAnrDetector(  883): Revision: 14
D/CrashAnrDetector(  883): Bootloader: G900FXXU1BOD3
D/CrashAnrDetector(  883): Radio: unknown
D/CrashAnrDetector(  883): Kernel: Linux version 3.4.0-4664691 (dpi@SWDD6202) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Thu Apr 9 17:38:07 KST 2015
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector(  883): Build fingerprint: 'samsung/kltexx/klte:5.0/LRX21T/G900FXXU1BOD3:user/release-keys'
D/CrashAnrDetector(  883): Revision: '14'
D/CrashAnrDetector(  883): ABI: 'arm'
D/CrashAnrDetector(  883): pid: 7363, tid: 8405, name: Thread-1230  >>> com.test.thalitest <<<
D/CrashAnrDetector(  883): signal 11 (SIGSEGV), code 2 (SEGV_ACCERR), fault addr 0x9112dff0
D/CrashAnrDetector(  883):     r0 70d27380  r1 730abb58  r2 12d5fc50  r3 1302ec80
D/CrashAnrDetector(  883):     r4 000000c4  r5 70d27380  r6 730abb58  r7 1302ec80
D/CrashAnrDetector(  883):     r8 730abb00  r9 94622c00  sl 12d5fc50  fp 9122f840
D/CrashAnrDetector(  883):     ip 9112dff0  sp 9112fff0  lr 75a9e299  pc 75a9e21c  cpsr a00f0030
D/CrashAnrDetector(  883):     d0  0000000000000000  d1  0000000000000000
D/CrashAnrDetector(  883):     d2  0000000000000000  d3  0000000000000000
D/CrashAnrDetector(  883):     d4  4040404000404040  d5  0004000400040004
D/CrashAnrDetector(  883):     d6  0000000000000000  d7  0000000300040004
D/CrashAnrDetector(  883):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector(  883):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector(  883):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector(  883):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector(  883):     d16 0000000000000000  d17 7320656d69746e75
D/CrashAnrDetector(  883):     d18 0069007200750064  d19 007200200067006e
D/CrashAnrDetector(  883):     d20 0101010101010101  d21 0101010101010101
D/CrashAnrDetector(  883):     d22 8080808080808080  d23 8080808080808080
D/CrashAnrDetector(  883):     d24 4040404040004040  d25 0040404000404040
D/CrashAnrDetector(  883):     d26 0b0b0b0b0b0b0b0b  d27 0b0b0b0b0b0b0b0b
D/CrashAnrDetector(  883):     d28 0101010101010101  d29 0101010101010101
D/CrashAnrDetector(  883):     d30 0000000000000000  d31 0000000000000000
D/CrashAnrDetector(  883):     scr 20000013
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): backtrace:
D/CrashAnrDetector(  883):     #00 pc 0009221c  /system/framework/arm/boot.oat
D/CrashAnrDetector(  883):     #01 pc 00092297  /system/framework/arm/boot.oat
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): stack:
D/CrashAnrDetector(  883):          9112ffb0  00000000  
D/CrashAnrDetector(  883):          9112ffb4  00000000  
D/CrashAnrDetector(  883):          9112ffb8  00000000  
D/CrashAnrDetector(  883):          9112ffbc  00000000  
D/CrashAnrDetector(  883):          9112ffc0  00000000  
D/CrashAnrDetector(  883):          9112ffc4  00000000  
D/CrashAnrDetector(  883):          9112ffc8  00000000  
D/CrashAnrDetector(  883):          9112ffcc  00000000  
D/CrashAnrDetector(  883):          9112ffd0  70d14b10  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          9112ffd4  00000000  
D/CrashAnrDetector(  883):          9112ffd8  00000000  
D/CrashAnrDetector(  883):          9112ffdc  00000000  
D/CrashAnrDetector(  883):          9112ffe0  00000000  
D/CrashAnrDetector(  883):          9112ffe4  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          9112ffe8  e3a070ad  
D/CrashAnrDetector(  883):          9112ffec  ef9000ad  
D/CrashAnrDetector(  883):     #00  9112fff0  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          ........  ........
D/CrashAnrDetector(  883):     #01  9112fff0  70d27380  /data/dalvik-cache/arm/system@framewo,rk@boot.art
D/CrashAnrDetector(  883):          9112fff4  00000000  
D/CrashAnrDetector(  883):          9112fff8  00000000  
D/CrashAnrDetector(  883):          9112fffc  00000000  
D/CrashAnrDetector(  883):          91130000  00000000  
D/CrashAnrDetector(  883):          91130004  00000000  
D/CrashAnrDetector(  883):          91130008  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          9113000c  730abb00  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          91130010  1302ec80  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  883):          91130014  730abb58  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          91130018  12d5fc50  /dev/ashmem/dalvik-main space (deleted)
D/CrashAnrDetector(  883):          9113001c  75a9e24d  /system/framework/arm/boot.oat
D/CrashAnrDetector(  883):          91130020  70d27380  /data/dalvik-cache/arm/system@framework@boot.art
D/CrashAnrDetector(  883):          91130024  00000000  
D/CrashAnrDetector(  883):          91130028  00000000  
D/CrashAnrDetector(  883):          9113002c  00000000  
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): memory near r0:
D/CrashAnrDetector(  883):     70d27360 00000002 70d268d8 70d27370 00000000  
D/CrashAnrDetector(  883):     70d27370 70c2e700 00000000 00000001 70d27380  
D/CrashAnrDetector(  883):     70d27380 70c2e8a0 00000000 70d26cc0 70c2ead0  
D/CrashAnrDetector(  883):     70d27390 70c44268 70c46d30 75a0c009 00000000  
D/CrashAnrDetector(  883):     70d273a0 00000000 00000000 75a9e219 00000000  
D/CrashAnrDetector(  883):     70d273b0 752d061a 00000000 00080001 000b43d4  
D/CrashAnrDetector(  883):     70d273c0 00000e2e 00000023 70c469c0 00000000  
D/CrashAnrDetector(  883):     70d273d0 70d273e0 00000015 32ca2cc1 00000000  
D/CrashAnrDetector(  883):     70d273e0 70c5e178 00000000 00000015 0061006a  
D/CrashAnrDetector(  883):     70d273f0 00610076 006c002e 006e0061 002e0067  
D/CrashAnrDetector(  883):     70d27400 00680054 00650072 00640061 00720047  
D/CrashAnrDetector(  883):     70d27410 0075006f 00000070 70c5e640 00000000  
D/CrashAnrDetector(  883):     70d27420 00000002 70d27430 70d27448 00000000  
D/CrashAnrDetector(  883):     70d27430 70c5e7e0 00000000 70d26cc0 00000018  
D/CrashAnrDetector(  883):     70d27440 000008a9 00000200 70c5e7e0 00000000  
D/CrashAnrDetector(  883):     70d27450 70d26cc0 00000018 000008ad 00000204  
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): memory near r1:
D/CrashAnrDetector(  883): processName:com.test.thalitest
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1643 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/CrashAnrDetector(  883): broadcastEvent : null SYSTEM_TOMBSTONE
E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/CrashAnrDetector(  883): Build: samsung/kltexx/klte:5.0/LRX21T/G900FXXU1BOD3:user/release-keys
D/CrashAnrDetector(  883): Hardware: MSM8974
D/CrashAnrDetector(  883): Revision: 14
D/CrashAnrDetector(  883): Bootloader: G900FXXU1BOD3
D/CrashAnrDetector(  883): Radio: unknown
D/CrashAnrDetector(  883): Kernel: Linux version 3.4.0-4664691 (dpi@SWDD6202) (gcc version 4.8 (GCC) ) #1 SMP PREEMPT Thu Apr 9 17:38:07 KST 2015
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
D/CrashAnrDetector(  883): Build fingerprint: 'samsung/kltexx/klte:5.0/LRX21T/G900FXXU1BOD3:user/release-keys'
D/CrashAnrDetector(  883): Revision: '14'
D/CrashAnrDetector(  883): ABI: 'arm'
D/CrashAnrDetector(  883): pid: 5716, tid: 5792, name: Thread-893  >>> com.example.hello <<<
D/CrashAnrDetector(  883): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 0x0
D/CrashAnrDetector(  883):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
D/CrashAnrDetector(  883):     r4 9b883e48  r5 9b883e08  r6 af07b020  r7 9b883e08
D/CrashAnrDetector(  883):     r8 00000000  r9 9b883e44  sl 9b8853a0  fp 9b883dec
D/CrashAnrDetector(  883):     ip 9c359ba0  sp 9b883dd0  lr 9c060308  pc b6e8b474  cpsr 600d0030
D/CrashAnrDetector(  883):     d0  5701003a0f000000  d1  0000008851030000
D/CrashAnrDetector(  883):     d2  563e0a0000003502  d3  000000b80c030000
D/CrashAnrDetector(  883):     d4  000a007b0029006e  d5  0020007200610076
D/CrashAnrDetector(  883):     d6  0074003d00730074  d7  002e007300690068
D/CrashAnrDetector(  883):     d8  0000000000000000  d9  0000000000000000
D/CrashAnrDetector(  883):     d10 0000000000000000  d11 0000000000000000
D/CrashAnrDetector(  883):     d12 0000000000000000  d13 0000000000000000
D/CrashAnrDetector(  883):     d14 0000000000000000  d15 0000000000000000
D/CrashAnrDetector(  883):     d16 0088000000560a10  d17 0a00000035020000
D/CrashAnrDetector(  883):     d18 1b0000004549ffd7  d19 00b80c0200005651
D/CrashAnrDetector(  883):     d20 01003a3e0a0d0000  d21 0007490c0000003d
D/CrashAnrDetector(  883):     d22 0c00000088490000  d23 3d0a0e000000b80c
D/CrashAnrDetector(  883):     d24 0000000000000000  d25 0000000000000000
D/CrashAnrDetector(  883):     d26 0002000200020001  d27 0002000200020002
D/CrashAnrDetector(  883):     d28 0080008000800080  d29 0080008000800080
D/CrashAnrDetector(  883):     d30 0800080008000800  d31 0800080008000800
D/CrashAnrDetector(  883):     scr 20000013
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): backtrace:
D/CrashAnrDetector(  883):     #00 pc 00011474  /system/lib/libc.so (strlen+83)
D/CrashAnrDetector(  883):     #01 pc 007da304  /data/app/com.example.hello-1/lib/arm/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): stack:
D/CrashAnrDetector(  883):          9b883d90  9882b040  
D/CrashAnrDetector(  883):          9b883d94  af0a4000  
D/CrashAnrDetector(  883):          9b883d98  985203c8  
D/CrashAnrDetector(  883):          9b883d9c  00000001  
D/CrashAnrDetector(  883):          9b883da0  98849160  
D/CrashAnrDetector(  883):          9b883da4  af07b020  
D/CrashAnrDetector(  883):          9b883da8  9884f1c0  
D/CrashAnrDetector(  883):          9b883dac  00000000  
D/CrashAnrDetector(  883):          9b883db0  00000000  
D/CrashAnrDetector(  883):          9b883db4  00000000  
D/CrashAnrDetector(  883):          9b883db8  00000003  
D/CrashAnrDetector(  883):          9b883dbc  000000aa  
D/CrashAnrDetector(  883):          9b883dc0  0000006b  
D/CrashAnrDetector(  883):          9b883dc4  0001416e  
D/CrashAnrDetector(  883):          9b883dc8  00000000  
D/,CrashAnrDetector(  883):          9b883dcc  9b883e00  [stack:5792]
D/CrashAnrDetector(  883):     #00  9b883dd0  9b883e48  [stack:5792]
D/CrashAnrDetector(  883):          ........  ........
D/CrashAnrDetector(  883):     #01  9b883dd0  9b883e48  [stack:5792]
D/CrashAnrDetector(  883):          9b883dd4  00000000  
D/CrashAnrDetector(  883):          9b883dd8  9b883e48  [stack:5792]
D/CrashAnrDetector(  883):          9b883ddc  9b883e2c  [stack:5792]
D/CrashAnrDetector(  883):          9b883de0  9b883e18  [stack:5792]
D/CrashAnrDetector(  883):          9b883de4  00000000  
D/CrashAnrDetector(  883):          9b883de8  9b884e64  [stack:5792]
D/CrashAnrDetector(  883):          9b883dec  9c0373f0  /data/app/com.example.hello-1/lib/arm/libjxcore.so
D/CrashAnrDetector(  883):          9b883df0  9b883e20  [stack:5792]
D/CrashAnrDetector(  883):          9b883df4  00000000  
D/CrashAnrDetector(  883):          9b883df8  9b883e14  [stack:5792]
D/CrashAnrDetector(  883):          9b883dfc  9be69184  /data/app/com.example.hello-1/lib/arm/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
D/CrashAnrDetector(  883):          9b883e00  00000000  
D/CrashAnrDetector(  883):          9b883e04  00000000  
D/CrashAnrDetector(  883):          9b883e08  b6ee3e04  
D/CrashAnrDetector(  883):          9b883e0c  00000000  
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): memory near r4:
D/CrashAnrDetector(  883):     9b883e28 98851d80 98853b00 af07b020 00000000  
D/CrashAnrDetector(  883):     9b883e38 985202b8 985202c8 00000001 b6ee002f  
D/CrashAnrDetector(  883):     9b883e48 00001000 b6ee3e04 00001000 af07b020  
D/CrashAnrDetector(  883):     9b883e58 98520360 9b883e70 9b8841ec 9bf45ab0  
D/CrashAnrDetector(  883):     9b883e68 00000002 00000000 98520360 00000000  
D/CrashAnrDetector(  883):     9b883e78 9c34bf28 00000001 98853b00 9b883e70  
D/CrashAnrDetector(  883):     9b883e88 00000000 80000000 00000000 00000000  
D/CrashAnrDetector(  883):     9b883e98 00000000 00000000 00000002 9b883761  
D/CrashAnrDetector(  883):     9b883ea8 9fab0100 ffffffff 00000000 00000000  
D/CrashAnrDetector(  883):     9b883eb8 0000000e af0a8000 9b883ecc 9b883e00  
D/CrashAnrDetector(  883):     9b883ec8 e0000000 00000006 00000000 00000001  
D/CrashAnrDetector(  883):     9b883ed8 9b8842e8 00000040 af0e7400 9882b940  
D/CrashAnrDetector(  883):     9b883ee8 0000000c 985faa80 9b8842e8 00000040  
D/CrashAnrDetector(  883):     9b883ef8 0000000c 9be9ea20 9b8843e0 00000001  
D/CrashAnrDetector(  883):     9b883f08 9fabe6d0 00000068 00000000 00000000  
D/CrashAnrDetector(  883):     9b883f18 00000000 00000000 9b883f30 00000000  
D/CrashAnrDetector(  883): 
D/CrashAnrDetector(  883): memory near r5:
D/CrashAnrDetector(  883):     9b883de8 9b884e64 9c0373f0 9b883e20 00000000  
D/CrashAnrDetector(  883):     9b883df8 9b883e14 9be69184 00000000 00000000  
D/CrashAnrDetector(  883):     9b883e08 b6ee3e04 00000000 9b88419c 9bf45b34  
D/CrashAnrDetector(  883):     
D/CrashAnrDetector(  883): processName:com.example.hello
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1643 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/CrashAnrDetector(  883): broadcastEvent : com.example.hello SYSTEM_TOMBSTONE
D/SettingsProvider(  883): ret = -1
W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.hid.HidService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.hdp.HealthService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.pan.PanService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
,E/Zygote  ( 3425): MountEmulatedStorage()
D/SettingsProvider(  883): ret = -1
E/Zygote  ( 3425): v2
I/libpersona( 3425): KNOX_SDCARD checking this for 10082
I/libpersona( 3425): KNOX_SDCARD not a persona
D/ResourcesManager( 3405): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
I/ActivityManager(  883): Start proc com.google.android.apps.books for service com.google.android.apps.books/.service.SyncService: pid=3425 uid=10082 gids={50082, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
W/ResourcesManager( 3405): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(  883): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(  883): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(  883): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/jxcore-log( 3270): JXcore Cordova bridge is ready!
I/jxcore-log( 3270): 
,W/jxcore-log( 3270): JXcore engine is started
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SmartRemote_KL/SmartRemote_KL.apk
,I/SELinux ( 3425): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3425): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3425): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SettingsProvider(  883): name = bt_svcst_com.broadcom.bt.service.sap.SapService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,E/File    ( 3370): fail readDirectory() errno=2
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,D/TimaKeyStoreProvider( 3425): TimaSignature is unavailable
,D/ActivityThread( 3425): Added TimaKeyStore provider
,D/PopupuiReceiver( 3380): onReceive() getAction : android.intent.action.BOOT_COMPLETED
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/SettingsProvider(  883): name = bt_svcst_com.android.bluetooth.hid.HidDevService
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterApp( 3345): checkSWUpdate
D/BluetoothAdapterApp( 3345): sw version in prop is 1428568983
,D/BluetoothAdapterApp( 3345): sw version in file is 1428568983
D/BluetoothAdapterApp( 3345): sw version is same
,E/jxcore-log( 3270): >> samsung-SM-G900F
E/jxcore-log( 3270): 
,I/jxcore-log( 3270): Total memory 1787449344
I/jxcore-log( 3270): 
,I/jxcore-log( 3270): Free memory 31399936
I/jxcore-log( 3270): 
I/jxcore-log( 3270): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3270): 
I/jxcore-log( 3270): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3270): 
,I/jxcore-log( 3270): userPath [ 'rList-com.example.hello.MainActivity', 'www' ]
I/jxcore-log( 3270): 
,I/jxcore-log( 3270): Size 1080 1920
I/jxcore-log( 3270): 
,I/jxcore-log( 3270): Screen Brightness 134
I/jxcore-log( 3270): 
,E/jxcore-log( 3270): Dummy Error Log.
E/jxcore-log( 3270): 
,D/BluetoothAdapterState( 3345): make
,I/bluedroid( 3345): init
,E/LightSensor(  883): RED : 1, GREEN : 1, BLUE : 1, CLEAR : 3, CALCULATED LUX : 0.000000, CCT : 4939.000000, REAL LUX : 0.000000 a_time = 238, gain = 64, ir=0, rp1=1, gp1=1, bp1=1, cp1=3, cpl=3202560
,D/AutomaticBrightnessController(  883): mCallbacks.updateBrightness()
D/DisplayPowerController(  883): getFinalBrightness : 8 -> 8
,I/BluetoothAdapterState( 3345): Entering OffState
,I/bte_conf( 3345): bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,I/bte_conf( 3345): bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,E/bt_osi_config( 3345): config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
I/bte_conf( 3345): bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,E/bt-btif ( 3345): btif_fetch_local_ble_random_bdaddr
,I/bluedroid( 3345): get_profile_interface socket
I/bluedroid( 3345): get_profile_interface map_client
,D/BluetoothAdapterService( 3345): checkAddrForIOP: Loading from conf
,D/ResourcesManager( 3425): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /data/app/de.pizza-1/base.apk
,I/GKI_LINUX( 3345): gki_task_entry task_id=1 [BTIF] starting
,D/BluetoothAdapterService( 3345): Inband Ring is supported
,D/BluetoothAdapterProperties( 3345): Address is:B0:C5:59:3F:75:69
E/BluetoothServiceJni( 3345): populateRssiValuesNative
I/bluedroid( 3345): getModelRssiValues
E/BluetoothServiceJni( 3345): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 3345): modelRssiValuesCallback, low, mid, high = -70,-60,127
,D/BluetoothAdapterProperties( 3345): Name is: Thali Test (Galaxy S5)
,D/SettingsProvider(  883): name = bluetooth_name
,I/bluedroid( 3345): config_hci_snoop_log
,D/BluetoothManagerService(  883): Broadcasting onBluetoothServiceUp() to 11 receivers.
,E/DevicePolicyManagerService(  883): getAllowBluetoothMode - value retunrs : 2
E/DevicePolicyManagerService(  883): getAllowBluetoothMode - value retunrs : 2
,D/SecContentProvider2(  883): uri = -1 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider(  883): uri = 3 selection = isBluetoothEnabled
,I/PopupuiReceiver_KNOX( 3380): getSealedState : true
,D/BluetoothAdapterState( 3345): CURRENT_STATE=OFF, MSG = USER_TURN_ON
,D/BluetoothAdapterProperties( 3345): Setting state to 11
I/BluetoothAdapterState( 3345): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 3345): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3345): updateAdapterState state is 11
,D/BluetoothAdapterService( 3345): Autoconnection is available 
,D/SecContentProvider2(  883): uri = 15 selection = getSealedHideNotificationMessages
D/SecContentProvider2(  883): mCursor = null
D/BluetoothAdapterService( 3345): updateAdapterState prevState = 10newState = 11
D/BluetoothSecureManager( 3345): getInstant: null
,D/BluetoothSecureManager( 3345): calling getMethod for getService
D/BluetoothSecureManager( 3345): calling getService
,D/BluetoothSecureManager( 3345): getService return binder: android.os.BinderProxy@20ab656d
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,I/PopupuiReceiver_KNOX( 3380): getSealedHideNotificationMessages : 1
D/BluetoothSecureManagerService(  883): isSecureModeEnabled
D/BluetoothSecureManagerService(  883): getSecureModeSetting, name: secure_mode_enable
,D/BtConfig.SecureMode( 3345): isSecureModeOn:false
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 3345): isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 3345): processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/SecContentProvider2(  883): uri = 15 selection = getCheckCoverPopupState
,W/BluetoothAdapterService( 3345): processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
D/SecContentProvider2(  883): mCursor = null
,W/BluetoothAdapterService( 3345): processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 3345): processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,D/BluetoothBondStateMachine( 3345): make
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.gatt.GattService
,I/BluetoothBondStateMachine( 3345): StableState(): Entering Off State
,W/InputMethodManagerService(  883): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  883): [BT Setting State] State =11
,I/PopupuiReceiver_KNOX( 3380): getCheckCoverPopupState : true
D/PopupuiReceiver( 3380): Batterycover is on
D/PopupuiReceiver( 3380): ril. condition
,I/SamsungIME( 1869): STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/ResourcesManager(  883): creating new AssetManager and set to /data/app/de.kaufda.android-1/base.apk
,D/BluetoothTile( 1170): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/STATUSBAR-QSTileView( 1170): onStateChanged: Bluetooth
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_bluetooth_dim.png
,D/PopupuiReceiver( 3380): FINISH condition
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
I/BtGatt.JNI( 3345): classInitNative(L890): classInitNative: Success!
,W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 3345): handleDebugAction() action=null
,D/BtGatt.GattService( 3345): Received start request. Starting profile...
D/BtGatt.GattService( 3345): start()
I/bluedroid( 3345): get_profile_interface gatt
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
D/BtGatt.AdvertiseManager( 3345): advertise manager created
,W/ContextImpl( 3380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1526 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:370 android.app.ActivityThread.handleReceiver:2945 
,W/ContextImpl( 3380): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1538 android.app.ContextImpl.startActivity:1527 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.sec.android.app.popupuireceiver.PopupuiReceiver.onReceive:370 
,I/Timeline( 3380): Timeline: Activity_launch_request id:com.sec.android.app.popupuireceiver time:27945
,E/PersonaManagerService(  883): inState():  stateMachine is null !!
W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.hid.HidService
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,E/Zygote  ( 3452): MountEmulatedStorage()
E/Zygote  ( 3452): v2
I/libpersona( 3452): KNOX_SDCARD checking this for 10088
I/libpersona( 3452): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=3452 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.popupuireceiver
,I/ActivityManager(  883): START u0 {flg=0x10000000 cmp=com.sec.android.app.popupuireceiver/.BatteryCover} from uid 1000 on display 0
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
,I/art     (  327): Explicit concurrent mark sweep GC freed 8772(373KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 284us total 18.596ms
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,W/ActivityManager(  883): mDVFSHelper.acquire()
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 250us total 9.372ms
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 254us total 9.121ms
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 3452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3452): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (189 us)
,D/TimaKeyStoreProvider( 3452): TimaSignature is unavailable
,D/ActivityThread( 3452): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.hdp.HealthService
,D/HeadsetService( 3345): Received start request. Starting profile...
,I/BluetoothHeadsetServiceJni( 3345): classInitNative: succeeds
,D/HeadsetStateMachine( 3345): make
,E/HeadsetStateMachine( 3345): # of Max HF connection is 2
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/ReaderUtils( 3425): PortraitW 1080 LandscapeW 1920 SmallestSize 1005 LargestSize 1920 textZoom 3.3749998 isTablet false Memory 128
D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  883): Killing 1409:com.sec.android.provider.emergencymode/u0a107 (adj 15): bgCount ##41
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.pan.PanService
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 3452): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3474): MountEmulatedStorage()
I/libpersona( 3474): KNOX_SDCARD checking this for 1001
E/Zygote  ( 3474): v2
I/libpersona( 3474): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.phone for broadcast com.sec.phone/.BootCompleteReceiver: pid=3474 uid=1001 gids={41001, 9997, 1007, 1028, 1015, 3002, 3001, 3003, 1023, 3006} abi=armeabi-v7a
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.map.BluetoothMapService
,I/SELinux ( 3474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3474): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/TimaKeyStoreProvider( 3474): TimaSignature is unavailable
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ActivityThread( 3474): Added TimaKeyStore provider
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bluedroid( 3345): get_profile_interface handsfree
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 3345): Not skipping com.broadcom.bt.service.sap.SapService
,W/libprocessgroup(  883): failed to open /acct/uid_10107/pid_1409/cgroup.procs: No such file or directory
,I/DualScoManager( 3345): Instantiating Dual Sco Manager
,I/DualScoManager( 3345): Set HeadsetServiceHelper
,D/BluetoothAtMessage( 3345): createCMTIContentObservers
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SettingsProvider(  883): name = bluetooth_hfp_allowed_bvra
,D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
,V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_2.qmg
V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_4.qmg
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_5.qmg
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,D/HeadsetStateMachine( 3345): Enter Disconnected: -2
,W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_6.qmg
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 3345): check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,E/HeadsetStateMachine( 3345): set to mRemoteBrsf = 0
,D/BluetoothA2dp(  883): Proxy object connected
,V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_7.qmg
D/A2dpService( 3345): Received start request. Starting profile...
,I/BluetoothAvrcpServiceJni( 3345): classInitNative: succeeds
,V/Avrcp   ( 3345): make
V/Avrcp   ( 3345): Avrcp
I/bluedroid( 3345): get_profile_interface avrcp
,W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
I/BluetoothAdapterState( 3345): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_3.qmg
,V/Avrcp   ( 3345): start
,D/HeadsetStateMachine( 3345): map size, before remove : 0
D/HeadsetStateMachine( 3345): map size, after remove: 0
D/HeadsetStateMachine( 3345): mNextConnectingDevice : null
,V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_1.qmg
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/jxcore-log( 3270): getBuffer is called!!!!
I/jxcore-log( 3270): 
,E/RemoteController( 3345): Cannot set synchronization mode on an unregistered RemoteController
,V/Avrcp   ( 3345): ++registerMediaPlayers++
,I/Avrcp   ( 3345): No of Audio players :: 2
I/Avrcp   ( 3345): App Package name is com.google.android.music
,D/ResourcesManager( 3345): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/Avrcp   ( 3345): App pkg name is Google Play Music
,I/Avrcp   ( 3345): Name::Google Play Music
V/Avrcp   ( 3345): MediaPlayerInfo: mPlayerId=1
I/Avrcp   ( 3345): App Package name is com.sec.android.app.music
,D/ResourcesManager( 3345): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_8.qmg
,D/PopupuiReceiver( 3380): on BatteryCover Delete to FirstValue
,I/Avrcp   ( 3345): App pkg name is Music
,I/Avrcp   ( 3345): Name::Music
V/Avrcp   ( 3345): MediaPlayerInfo: mPlayerId=2
I/Avrcp   ( 3345):  set player publishabilty with player id::2 toBePublished ::true
,V/BitmapFactory( 3380): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/animation_battery_10.qmg
I/Avrcp   ( 3345): No of Video players :: 1
I/Avrcp   ( 3345): Video App Package name is com.sec.android.app.videoplayer
,D/ResourcesManager( 3345): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,I/Avrcp   ( 3345): Video App pkg name is Video Player
,I/Avrcp   ( 3345): Name::Video Player
V/Avrcp   ( 3345): MediaPlayerInfo: mPlayerId=3
I/Avrcp   ( 3345): Add tempPlayer
V/Avrcp   ( 3345): MediaPlayerInfo: mPlayerId=4
I/Avrcp   ( 3345): Total no of players: 4
V/Avrcp   ( 3345): swapping the samsung player with 1st player
I/Avrcp   ( 3345):  Updating now playing list upon AVRCP Start
,I/BluetoothA2dpServiceJni( 3345): classInitNative: succeeds
D/A2dpStateMachine( 3345): make
,V/Avrcp   ( 3345): handleMessage, msg=207
D/BluetoothMediaBrowser( 3345):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/PopupuiReceiver( 3380): on BatteryCover  : firstvalue
,D/Activity( 3380): performCreate Call secproduct feature valuefalse
D/Activity( 3380): performCreate Call debug elastic valuetrue
,I/bluedroid( 3345): get_profile_interface a2dp
,I/GKI_LINUX( 3345): gki_task_entry task_id=2 [A2DP-MEDIA] starting
E/bt-btif ( 3345): warning : media task started media_task_refcnt 1 
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,D/A2dpStateMachine( 3345): Enter Disconnected: -2
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,I/BluetoothHidServiceJni( 3345): classInitNative: succeeds
,D/HidService( 3345): Received start request. Starting profile...
I/bluedroid( 3345): get_profile_interface hidhost
D/HidService( 3345): setHidService(): set to: null
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,I/BluetoothHealthServiceJni( 3345): classInitNative: succeeds
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/HealthService( 3345): Received start request. Starting profile...
,I/bluedroid( 3345): get_profile_interface health
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,I/BluetoothPanServiceJni( 3345): classInitNative(L105): succeeds
,D/BluetoothMediaBrowser( 3345): no now playing list
,D/BluetoothMediaBrowser( 3345):  getNowPlayingId now playing id : -1
D/Avrcp   ( 3345):  checkNowPlayingList start
,D/BluetoothPan(  883): BluetoothPAN Proxy object connected
,D/PanService( 3345): Received start request. Starting profile...
D/BluetoothPanServiceJni( 3345): initializeNative(L110): pan
I/bluedroid( 3345): get_profile_interface pan
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,D/BluetoothMapService( 3345): Received start request. Starting profile...
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3474): creating new AssetManager and set to /system/app/SecFactoryPhoneTest/SecFactoryPhoneTest.apk
,E/Zygote  ( 3509): MountEmulatedStorage()
I/libpersona( 3509): KNOX_SDCARD checking this for 10163
E/Zygote  ( 3509): v2
I/libpersona( 3509): KNOX_SDCARD not a persona
,W/ResourcesManager( 3474): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=3509 uid=10163 gids={50163, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/ActivityManager(  883): post active user change for 0
D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
,E/SMD     (  287): DCD ON
,W/GAV2    ( 3425): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/dhcpcd  ( 1921): wlan0: sending IPv6 Router Solicitation
,I/dhcpcd  ( 1921): wlan0: no IPv6 Routers available
,I/SELinux ( 3509): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3509): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3509): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/SurfaceFlinger(  249): id=13 createSurf (1x1),2 flag=404, com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/DelayedSyncController( 3452): Delaying sync.
,I/Timeline( 3380): Timeline: Activity_idle id: android.os.BinderProxy@239569ee time:28573
,I/Timeline( 3380): Timeline: Activity_idle id: android.os.BinderProxy@239569ee time:28573
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/TimaKeyStoreProvider( 3509): TimaSignature is unavailable
,I/PopupuiReceiver( 3380): showPopupBatteryCover()+
D/ActivityThread( 3509): Added TimaKeyStore provider
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/BooksApp( 3425): Created application version: 3.3.11 (30311)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 3509): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  883): Displayed com.sec.android.app.popupuireceiver/.BatteryCover: +512ms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/ResourcesManager( 3509): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3509): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3509): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 3509): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/DriveInitializer( 2457): Background init thread started
,I/ActivityManager(  883): Killing 1540:com.samsung.android.app.mirrorlink/1000 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/Vold    (  248): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 2457): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_1540/cgroup.procs: No such file or directory
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SamsungIME( 1869): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/art     (  883): Explicit concurrent mark sweep GC freed 62057(3MB) AllocSpace objects, 50(4MB) LOS objects, 31% free, 34MB/50MB, paused 1.465ms total 186.371ms
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/SurfaceFlinger(  249): id=14 createSurf (49x49),1 flag=4, com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover
,W/IInputConnectionWrapper( 3270): showStatusIcon on inactive InputConnection
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
W/DriveInitializer( 2457): Background init thread ended
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 1315): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SettingsProvider(  883): name = db_smartlock_supported
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/RCPManagerService(  883): exchangeData() failure , invalid userId
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/BooksSync( 3425): Starting books sync, d
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,D/HeadsetStateMachine( 3345): Proxy object connected
D/HeadsetStateMachine( 3345): Try to query the phonestate on bind
,D/BadgeProvider( 1604): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Telecom ( 1449): BluetoothPhoneService: queryPhoneState
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/Telecom ( 1449): BluetoothPhoneService: updateHeadsetWithCallState
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/Telecom ( 1449): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/BadgeProvider( 1604): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 1604): sendNotify, [notify] : null
D/BadgeProvider( 1604): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 1604): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1604): update, [UpdateCount] : 1
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Launcher.Model( 1476): reloadBadges entered.
,W/BluetoothHeadset( 1449): Proxy not attached to service
,I/Telecom ( 1449): BluetoothPhoneService: Result of Message : true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
I/GLSActivity( 1685): [ac] getting account id
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/BluetoothSAPServiceJni( 3345): classInitNative(L204): succeeds
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SapService( 3345): Received start request. Starting profile...
,D/BluetoothSAPServiceJni( 3345): initializeNative(L209): sap
I/bluedroid( 3345): get_profile_interface sap
I/AccessibilityManagerService(  883): setmDNIeNegative (false)
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,V/HeadsetService( 3345): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BluetoothA2dp( 3345): Proxy object connected
D/BluetoothAdapterService( 3345): Bluetooth A2dp source service connected
D/HeadsetStateMachine( 3345): Disconnected process message: 10
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
D/HeadsetPhoneState( 3345): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 3345): Disconnected process message: 11
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
D/BluetoothAdapterState( 3345): CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 3345): enable
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bt_hci_bdroid( 3345): init
I/GKI_LINUX( 3345): gki_task_entry task_id=0 [BTU] starting
,I/bt_vendor( 3345): init
,I/bt_vnd_conf( 3345): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,I/bt_vnd_conf( 3345): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
D/bt_userial( 3345): userial_init
D/bt_vendor( 3345): op for 5
,D/bt_vendor( 3345): op for 0
,D/bt_upio ( 3345): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 3345): is_emulator_context : 0
,D/bt_upio ( 3345): is_rfkill_disabled ? [0]
D/bt_upio ( 3345): is_rfkill_disabled ? [0]
,D/bt_vendor( 3345): op for 0
D/bt_upio ( 3345): upio_set_bluetooth_power(on: 1)
,D/bt_upio ( 3345): is_emulator_context : 0
D/bt_upio ( 3345): is_rfkill_disabled ? [0]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/bt_vendor( 3345): op for 3
I/bt_userial_vendor( 3345): userial vendor open: opening /dev/ttyHS0
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/bt_userial_vendor( 3345): userial_vendor_open():UART is setup
I/bt_userial_vendor( 3345): device fd = 65 open
,D/bt_vendor( 3345): op for 1
D/bt_userial( 3345): Entering userial_read_thread()
E/bt_hwcfg( 3345): Start CFG HW, HCI reset
,I/ActivityManager(  883): Killing 1773:com.sec.android.service.health/u0a17 (adj 15): bgCount ##41
,I/Icing   ( 2457): Storage manager: low false usage 1.78MB avail 8.19GB capacity 10.03GB
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/Settings( 1315): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/SettingsProvider(  883): name = block_emergency_message
,D/SettingsProvider(  883): name = safetycare_geolookout_registering
,D/SettingsProvider(  883): name = dormant_disable_led_indicator
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/libprocessgroup(  883): failed to open /acct/uid_10017/pid_1773/cgroup.procs: No such file or directory
,D/BatteryService(  883): bootCompleted
,D/BatteryService(  883): Dormant OnOff Settings = false
D/BatteryService(  883): Dormant Disable LED Settings = true
D/BatteryService(  883): Dormant Always Settings = true
D/BatteryService(  883): Dormant time Settings = 21:0 ~ 6:0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_000.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_001.png
,D/SSRM:CustomFrequencyManagerService(  883): SmartManager App not installed
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_002.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_003.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_004.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_005.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_006.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_007.png
,E/bt_hwcfg( 3345): Read Local Name after HCI reset
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_008.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_010.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_011.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_012.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_013.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_014.png
,I/GLSUser ( 1685): [ChannelManager] Attempting to channel bind connection HttpClient.
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_on_mtrl_015.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_000.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_001.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_002.png
,I/GLSUser ( 1685): [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_003.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_004.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_005.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_006.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_007.png
,D/bt_hwcfg( 3345): Chipset BCM4350C0
,D/bt_hwcfg( 3345): Target name = [BCM4350C0]
,I/bt_hwcfg( 3345): module_type[semco3rd] is invalid.
,E/bt_hwcfg( 3345): finish scan emr path. reset chip id to BCM4350C0
E/bt_hwcfg( 3345): patchram path ORG . BCM4350C0
E/bt_hwcfg( 3345): patchram path ORG .. BCM4350C0
,E/bt_hwcfg( 3345): patchram path ORG bcm4350_V0301.0561.hcd BCM4350C0
E/bt_hwcfg( 3345): patchram path ORG libpn547_fw.so BCM4350C0
E/bt_hwcfg( 3345): fw ver (emr)0.0 // (org)0.0
E/bt_hwcfg( 3345): vendor lib preload failed to locate firmware patch file
E/bt_hwcfg( 3345): Remove module rev, try again BCM4350
D/bt_hwcfg( 3345): Target name = [BCM4350]
I/bt_hwcfg( 3345): module_type[semco3rd] is invalid.
,E/bt_hwcfg( 3345): finish scan emr path. reset chip id to BCM4350
E/bt_hwcfg( 3345): patchram path ORG . BCM4350
E/bt_hwcfg( 3345): patchram path ORG .. BCM4350
E/bt_hwcfg( 3345): patchram path ORG bcm4350_V0301.0561.hcd BCM4350
I/bt_hwcfg( 3345): patch(org) : bcm4350_V0301.0561.hcd
I/bt_hwcfg( 3345): Found patchfile: /vendor/firmware/bcm4350_V0301.0561.hcd
,E/bt_hwcfg( 3345): ORG patchram base 0301
V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_008.png
E/bt_hwcfg( 3345): ORG patchram minor 0561
E/bt_hwcfg( 3345): fw ver (emr)0.0 // (org)301.561
E/bt_hwcfg( 3345): Final Patchram is /vendor/firmware/bcm4350_V0301.0561.hcd
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_010.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_011.png
,E/SQLiteLog( 3425): (284) automatic index on view_volumes(volume_id)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/bt_hwcfg( 3345): Axi patch failure or not include AXI patching
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_012.png
,I/bt_hwcfg( 3345): bt vendor lib: set UART baud 3000000
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_013.png
,I/GLSUser ( 1685): [t] Fetched account id for thalitester@gmail.com : 105256135866144380227
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_014.png
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_btn_check_to_off_mtrl_015.png
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_line.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/delete_glance_icon_undo.pkm
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_calendar_1.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_attach_icon_etc.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate.pkm
,W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_white.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_off.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_attach_icon_star_on.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_f.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_complate_f.pkm
V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_flag_off_f.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_foward_focus.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_reply_forward.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply.pkm
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_icon_reply_focus.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_vip.pkm
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_high_priority.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/email_list_low_priority.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_server_draft.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_client_draft.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/permission.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_voicemail.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sms.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_sign.pkm
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/list_icon_encryption.pkm
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/SmartFaceService(  883): onReceive: android.intent.action.BOOT_COMPLETED
,D/SmartFaceIndicator(  883): no icon
E/SmartFaceService(  883): mActiveServiceType: 0
E/SmartFaceService(  883): mLightIntensityEnough: true mLux: 0.0
D/Scroll/Pause Worker(  883): updateClientsDone.
,D/Stay/Rotation Worker(  883): updateClientsDone. def. do nothing.
E/SmartFaceService(  883): Service Type to Worker: 0
E/SmartFaceService(  883): Last Active clients:0 Current Active clients: 0
E/SmartFaceService(  883): Last Smart Pause clients: 0 Current Smart Pause clients: 0
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,I/Timeline(  883): Timeline: Activity_windows_visible id: ActivityRecord{e929363 u0 com.sec.android.app.popupuireceiver/.BatteryCover t27} time:29397
W/ActivityManager(  883): mDVFSHelper.release()
,D/RCPManagerService(  883): ACTION_BOOT_COMPLETED
E/RCPManagerService(  883):  BootReceiver : calling scanAndStartRCPProxy ACTION_BOOT_COMPLETED 
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_open_01_holo_light.pkm
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 3509): DecodeImagePath(decodeResourceStream3) : res/drawable-sw360dp-xxhdpi-v13/tw_expander_close_01_holo_light.pkm
,D/RCPManagerService(  883): BootReceiver.onReceive(): Starting RCP Proxy for user = null
D/PersonaManagerService(  883): getPersonasForUser(): returning null!
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@10
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PowerManagerService(  883): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 883) eventTime = 29426
,D/PowerManagerService(  883): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=883 (0x0)
D/PowerManagerService(  883): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=883, ws=WorkSource{10059}) (elapsedTime=3496)
,D/MotionRecognitionService(  883):   mReceiver.onReceive : ACTION_BOOT_COMPLETED
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1643 b.ao.ci:-1 b.p.a:-1 b.p.b:-1 com.android.server.ssrm.ag.c:-1 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SQLiteSecureOpenHelper(  883): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper(  883): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper(  883): Open ssrm_secure.db in secure mode
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,I/SQLiteSecureOpenHelper(  883): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper(  883): ...getDatabaseLocked(b,b,pwd)
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/EnterpriseDeviceManagerService(  883): android.intent.action.BOOT_COMPLETED
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/ApplicationPolicy(  883): boot completed - refreshWidgetStatus
,V/ApplicationPolicy(  883): refresh widget status for user 0
D/EnterpriseDeviceManagerService(  883): Creating context as user 0
,D/EnterpriseDeviceManagerService(  883): runAdminUpdate
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.ssrm.aI.bx:-1 com.android.server.ssrm.aI.<init>:-1 com.android.server.ssrm.ag.onBootCompleted:-1 com.android.server.ssrm.ag.c:-1 
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.GeoLookout
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.books
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.music
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.GeoLookout
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclockeasy
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.sbrowser
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.vending
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.magazines
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.digitalclock
D/EnterpriseUtils(  883): File Not Found : /data/system/selfUpdateAdmin.conf
D/EnterpriseDeviceManagerService(  883): nothing to selfUpdate
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.chrome
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.music
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname flipboard.app
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.memo
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gm
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.vending
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.talk
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.mms
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.gallery3d
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.music
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.dualclockdigital
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.vending
W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1796 com.android.server.ssrm.ag.c:-1 com.android.server.ssrm.ag.onBootCompleted:-1 com.android.server.ssrm.ag.c:-1 com.android.server.ssrm.ah.handleMessage:-1 
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.docs
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname de.kaufda.android
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.kidsplat.installer
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.settings
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.clockpackage
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widget.samsungapps
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.android.email
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.activeapplicationwidget
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.easymodecontactswidget
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.apps.plus
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.ap.hero.accuweather
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.sec.android.widgetapp.SPlannerAppWidget
,I/NotificationStore( 1685): System rebooted after Notification storage file was last written
I/NotificationStore( 1685): Deleting the file
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/PhoneRestrictionPolicy(  883): Message received - msg { when=-7ms what=2 target=com.android.server.enterprise.restriction.PhoneRestrictionPolicy$SmsMmsDeliveryHandler }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,I/h       (  883): No model
D/LockPatternUtilsCache( 1170): value : false
,D/KnoxMUMContainerPolicy(  883): mContainerReceiver : action - android.intent.action.BOOT_COMPLETED
,I/KnoxMUMContainerPolicy(  883): MSG_REMOVE_ORPHANED_CONTAINERS received
W/PhoneRestrictionPolicy(  883):  >>>> deliveryBlockedMsgs
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Books/Books.apk
,W/PhoneRestrictionPolicy(  883): cvList size 0
,W/PhoneRestrictionPolicy(  883):  >>>> deliveryBlockedMsgs
W/PhoneRestrictionPolicy(  883): cvList size 0
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,D/FactoryTest(  883): Not factory mode
,D/FactoryTest(  883): Not factory mode. isFactoryMode() returend false
D/r       (  883): isUserBuild = true
,D/WifiP2pService(  883): InactiveState{ what=143415 }
D/WifiP2pService(  883): P2pEnabledState{ what=143415 }
D/WifiP2pService(  883): DefaultState{ what=143415 }
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/ConnectivityService(  883): Got NetworkFactory Messenger for WIFI_P2P
D/ConnectivityService(  883): NetworkFactory connected
,D/WIFI_P2P(  883): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,D/Tethering(  883): Boot complete.
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/ConnectivityService(  883): Got NetworkFactory Messenger for WIFI
D/ConnectivityService(  883): NetworkFactory connected
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/WifiStateMachine(  883): Blacklist file delete
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/SecContentProvider2(  883): uri = 14 selection = getSealedUsbNetState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/SSRM:m  (  883): SIOP:: AP = 430, CUR = 300
,V/EnterpriseBillingEngine(  883): ACTION_BOOT_COMPLETED
,V/EnterpriseBillingEngine(  883): handleAllprofiles - start
V/EnterpriseBillingPolicyStorage(  883): getCurrentActiveProfiles - start - 
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,V/EnterpriseBillingPolicyStorage(  883): getCurrentActiveProfiles - end - null
V/EnterpriseBillingEngine(  883): handleAllprofiles - end
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.intent.action.BOOT_COMPLETED
,D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): EVENT_BOOT_COMPLETED called / enable : false
D/SmartBondingService(  883): getSBEnabled() enabled =false
,I/CLocInfoService(  883): External Intent Received android.intent.action.BOOT_COMPLETED
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
D/SSRM:a  (  883): DeviceInfo:: 000000000000
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
D/SSRM:a  (  883): SettingsAirViewInfo:: 000000000
,I/CLocInfoCtrl(  883): getPolicyVersion 1
I/CLocInfoCtrl(  883): Version : 20150826-14:25
,W/Settings(  883): Setting device_provisioned has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UsbHostNotification(  883): boot completed
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/UsbDeviceManager(  883): isUsb30Enabled: read '/sys/class/android_usb/android0/bcdUSB', state = 0210
D/UsbManager(  883):  :::: isUsb30Enabled :: return = false from pid = 883
,D/WindowManager(  883): showStatusBarByNotification() mOpenByNotification=false
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/BooksAccountManager( 3425): Authentication error
E/BooksAccountManager( 3425): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 3425): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
,D/PersonaManagerService(  883): ACTION_BOOT_COMPLETED
,D/ResourcesManager( 1170): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,D/UsbStorageNotification(  883): boot completed
,D/StorageNotification( 1170): boot completed
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/WindowManager(  883): showStatusBarByNotification() mOpenByNotification=false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ResourcesManager( 1170): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 1170): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/HttpHelper( 3425): null auth token
,E/PersonaManagerServiceHandler(  883):  MSG_BOOT_COMPLETE_RECEIVED : soft start personas 
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_warning.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/CustomFrequencyManagerService(  883): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  tag : ACTIVITY_RESUME_BOOSTER@10
,D/GpsLocationProvider_ex(  883): BOOT_COMPLETED native_init 
,D/PersonaManagerService(  883): getPersonasForUser(): returning null!
,D/GpsLocationProvider(  883): set_capabilities_callback: 55u
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/        (  883): E/open failed: /dev/mdm: No such file or directory
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/stat_sys_warning.png
I/libmdmdetect(  883): ESOC framework not supported
,D/qmi_secgps_clnt(  883): qmi_secgps_client_init()
,E/PerMgrLib(  883): Peripheral manager is not supported on this device
,E/LocSvc_afw(  883): E/Error:  open failed: No such file or directory
,E/        (  883): E/open failed: /dev/mdm: No such file or directory
,D/qmi_secgps_clnt(  883): SECGPS: qmi_client_get_service_list() returned 0 num_services = 2
,D/qmi_secgps_clnt(  883): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 0 num_services = 2
,D/qmi_secgps_clnt(  883): SECGPS: qmi_client_get_service_list() returned 0 num_entries = 2 num_services = 2
,D/WIFI    (  883): got request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] with score 60
,E/Geofence_Adapter(  883): I/===> void GeofenceAdapter::addGfClients(GeoFencer*) line 65 
E/Geofence_Adapter(  883): I/===> void GeofenceAdapter::updateRegisteredEvents() line 81 
,I/System.out( 3425): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 3425): (HTTPLog)-Static: isShipBuild true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/System.out( 3425): (HTTPLog)-Thread-397-75155245: SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,D/KnoxNotification( 1170): ----- inflateViews : modified publicViewLocal -----
,D/SLocation(  883): BOOT_COMPLETED
,E/HttpOperation( 3405): [kfu{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
E/HttpOperation( 3405): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3405): 	at kfv.a(PG:65)
E/HttpOperation( 3405): 	at kff.u(PG:385)
E/HttpOperation( 3405): 	at kfb.a(PG:29)
E/HttpOperation( 3405): 	at kff.l(PG:132)
E/HttpOperation( 3405): 	at dsf.a(PG:807)
E/HttpOperation( 3405): 	at fhk.a(PG:1126)
E/HttpOperation( 3405): 	at fhk.a(PG:908)
E/HttpOperation( 3405): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3405): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3405): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3405): 	at ihi.a(PG:22)
E/HttpOperation( 3405): 	at kft.a(PG:91)
E/HttpOperation( 3405): 	at kfv.a(PG:62)
E/HttpOperation( 3405): 	... 8 more
E/HttpOperation( 3405): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3405): 	at gde.c(Unknown Source)
E/HttpOperation( 3405): 	at gde.b(Unknown Source)
E/HttpOperation( 3405): 	at ihi.a(PG:19)
E/HttpOperation( 3405): 	... 10 more
,I/bt_hwcfg( 3345): bt vendor lib: set UART baud 115200
I/bt_hwcfg( 3345): FW Download delta = 632499
,D/bt_hwcfg( 3345): Settlement delay -- 100 ms
I/bt_hwcfg( 3345): Setting fw settlement delay to 100 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/KnoxNotification( 1170): ----- inflateViews : modified KnoxViewLocal -----
,W/ActivityManager(  883): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/PersonaManager( 1170): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1170): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2d57e1ea
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/LocSvc_utils_cfg(  883): W/loc_read_sec_gps_conf: no secgps conf file, using defaults
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KnoxNotification( 1170): ----- inflateViews : modified publicViewLocal -----
,I/bt_hwcfg( 3345): bt vendor lib: set UART baud 3000000
,E/Diag_Lib(  883):  Diag_LSM_Init: Failed to open handle to diag driver, error = 2
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/KnoxNotification( 1170): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 1170): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 1170): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@2d57e1ea
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/bt_hwcfg( 3345): vendor lib fwcfg completed
,E/LocSvc_ApiV02(  883): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SERVER_REQ_V02
I/qmi_secgps_clnt(  883): SECGPS: Set AGPS Mode : 7
,D/qmi_secgps_clnt(  883): SECGPS: send a qmi message to secgps_server OK
,I/SurfaceFlinger(  249): id=10 Removed Toast (10/10)
,I/SurfaceFlinger(  249): id=10 Removed Toast (-2/10)
,E/LocSvc_ApiV02(  883): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02(  883): I/virtual loc_api_adapter_err LocApiV02::setSUPLVersion(uint32_t):1551]: supl version = 131072
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/        ( 3345): BTE_InitTraceLevels -- TRC_HCI
I/        ( 3345): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 3345): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 3345): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 3345): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 3345): BTE_InitTraceLevels -- TRC_A2D
I/        ( 3345): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 3345): BTE_InitTraceLevels -- TRC_BTM
I/        ( 3345): BTE_InitTraceLevels -- TRC_GAP
I/        ( 3345): BTE_InitTraceLevels -- TRC_PAN
I/        ( 3345): BTE_InitTraceLevels -- TRC_SAP
I/        ( 3345): BTE_InitTraceLevels -- TRC_SDP
I/        ( 3345): BTE_InitTraceLevels -- TRC_GATT
I/        ( 3345): BTE_InitTraceLevels -- TRC_SMP
I/        ( 3345): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 3345): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 3345): BTE_InitTraceLevels -- TRC_PROTOCOL
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/LocSvc_ApiV02(  883): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
E/LocSvc_ApiV02(  883): I/virtual loc_api_adapter_err LocApiV02::setAGLONASSProtocol(long unsigned int):1868]: aGlonassProtocolMask = 0x0
,I/art     ( 1685): Explicit concurrent mark sweep GC freed 17930(1194KB) AllocSpace objects, 8(518KB) LOS objects, 40% free, 17MB/29MB, paused 1.931ms total 51.433ms
,E/LocSvc_ApiV02(  883): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,I/qmi_secgps_clnt(  883): SECGPS: Set XTRA enable : 1
,D/qmi_secgps_clnt(  883): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt(  883): SECGPS: Set GNSS RF CONFIG : 1
,D/qmi_secgps_clnt(  883): SECGPS: send a qmi message to secgps_server OK
I/qmi_secgps_clnt(  883): SECGPS: Set CERT TYPE : 15
,D/qmi_secgps_clnt(  883): SECGPS: send a qmi message to secgps_server OK
E/LocSvc_ApiV02(  883): I/virtual loc_api_adapter_err LocApiV02::setLPPConfig(uint32_t):1592]: lpp profile = 0
,I/qtaguid ( 3425): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 3425, getuid(): 10082
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/SQLiteConnectionPool( 1685): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,E/LocSvc_ApiV02(  883): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_PROTOCOL_CONFIG_PARAMETERS_REQ_V02
,E/LocSvc_ApiV02(  883): I/virtual loc_api_adapter_err LocApiV02::setSensorControlConfig(int, int):1631]: sensors disabled = 0
,E/LocSvc_ApiV02(  883): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_CONTROL_CONFIG_REQ_V02
,E/LocSvc_ApiV02(  883): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 125 QMI_LOC_SET_SENSOR_PERFORMANCE_CONTROL_CONFIGURATION_REQ_V02
,E/LocSvc_ApiV02(  883): E/virtual loc_api_adapter_err LocApiV02::setXtraVersionCheck(loc_core::xtra_version_check):3262]: Set xtra version check failed. status: eLOC_CLIENT_FAILURE_INTERNAL, ind status:eQMI_LOC_SUCCESS_V02
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,D/StatusBar-DoNotDistrub( 1170): Received intent with android.intent.action.BOOT_COMPLETED action
,D/StatusBar-DoNotDistrub( 1170): Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,D/StatusBar-DoNotDistrub( 1170): sendBroadcast android.intent.action.DORMANT_MODE_OFF
,V/AudioPolicyManager(  292): getOutputsForDevice device 0002 -> 0002
,I/AudioService(  883): getStreamVolume 5 index 110
D/StatusBar-DoNotDistrub( 1170): The STREAM NOTIFICATION volume is 0
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=com.android.systemui
I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3624): MountEmulatedStorage()
I/libpersona( 3624): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3624): v2
I/libpersona( 3624): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.mobeam.barcodeService for broadcast com.mobeam.barcodeService/.system.AppBroadcastReceiver: pid=3624 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3624): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/quantum_logo_google_plus_color_44in48.png
,D/TimaKeyStoreProvider( 3624): TimaSignature is unavailable
,D/ActivityThread( 3624): Added TimaKeyStore provider
,D/ResourcesManager( 3624): creating new AssetManager and set to /system/app/BeamService/BeamService.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,I/Icing   ( 2457): updateResources: need to parse f{com.google.android.gms}
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,W/ContextImpl( 3624): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.mobeam.barcodeService.system.AppBroadcastReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2945 
,E/HttpOperation( 3405): [getmobileexperiments] Unexpected exception
E/HttpOperation( 3405): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3405): 	at kfv.a(PG:65)
E/HttpOperation( 3405): 	at kff.u(PG:385)
E/HttpOperation( 3405): 	at kfb.a(PG:29)
E/HttpOperation( 3405): 	at kff.l(PG:132)
E/HttpOperation( 3405): 	at ieo.a(PG:43)
E/HttpOperation( 3405): 	at iep.a(PG:93)
E/HttpOperation( 3405): 	at fhn.a(PG:59)
E/HttpOperation( 3405): 	at lex.a(PG:85)
E/HttpOperation( 3405): 	at lex.b(PG:132)
E/HttpOperation( 3405): 	at fhk.a(PG:1146)
E/HttpOperation( 3405): 	at fhk.a(PG:908)
E/HttpOperation( 3405): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3405): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3405): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3405): 	at ihi.a(PG:22)
E/HttpOperation( 3405): 	at kft.a(PG:91)
E/HttpOperation( 3405): 	at kfv.a(PG:62)
E/HttpOperation( 3405): 	... 12 more
E/HttpOperation( 3405): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3405): 	at gde.c(Unknown Source)
E/HttpOperation( 3405): 	at gde.b(Unknown Source)
E/HttpOperation( 3405): 	at ihi.a(PG:19)
E/HttpOperation( 3405): 	... 14 more
,E/ExperimentLoader( 3405): [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3405): java.io.IOException: Cannot obtain authentication token
E/ExperimentLoader( 3405): 	at kfv.a(PG:65)
E/ExperimentLoader( 3405): 	at kff.u(PG:385)
E/ExperimentLoader( 3405): 	at kfb.a(PG:29)
E/ExperimentLoader( 3405): 	at kff.l(PG:132)
E/ExperimentLoader( 3405): 	at ieo.a(PG:43)
E/ExperimentLoader( 3405): 	at iep.a(PG:93)
E/ExperimentLoader( 3405): 	at fhn.a(PG:59)
E/ExperimentLoader( 3405): 	at lex.a(PG:85)
E/ExperimentLoader( 3405): 	at lex.b(PG:132)
E/ExperimentLoader( 3405): 	at fhk.a(PG:1146)
E/ExperimentLoader( 3405): 	at fhk.a(PG:908)
E/ExperimentLoader( 3405): 	at fhk.onPerformSync(PG:636)
E/ExperimentLoader( 3405): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/ExperimentLoader( 3405): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/ExperimentLoader( 3405): 	at ihi.a(PG:22)
E/ExperimentLoader( 3405): 	at kft.a(PG:91)
E/ExperimentLoader( 3405): 	at kfv.a(PG:62)
E/ExperimentLoader( 3405): 	... 12 more
E/ExperimentLoader( 3405): Caused by: gdi: User intervention required. Notification has been pushed.
E/ExperimentLoader( 3405): 	at gde.c(Unknown Source)
E/ExperimentLoader( 3405): 	at gde.b(Unknown Source)
E/ExperimentLoader( 3405): 	at ihi.a(PG:19)
E/ExperimentLoader( 3405): 	... 14 more
,I/ActivityManager(  883): split this intent : android.intent.action.BOOT_COMPLETED !!   mSplitNum[0] = 90 dividenum = 38 r.nextReceiver = 52 receivers.size =204
,I/ActivityManager(  883): finish to split intent : android.intent.action.BOOT_COMPLETED !! Enqueue -> schedule it!!
,I/DrmEventReceiver(  883): DrmEventReceiver : onReceive
I/DrmEventReceiver(  883): DrmEventReceiver : onReceiveWithPrivilege intent.getTypenull
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/DrmEventReceiver(  883): DrmEventReceiver : beginStartingService
I/System.out(  883): start Service
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.server.DrmEventReceiver.beginStartingService:59 com.android.server.DrmEventReceiver.onReceiveWithPrivilege:47 
,E/Zygote  ( 3640): MountEmulatedStorage()
,E/Zygote  ( 3640): v2
I/libpersona( 3640): KNOX_SDCARD checking this for 10091
I/libpersona( 3640): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.timer.TimerReceiver: pid=3640 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/bt-l2cap( 3345): l2c_link_processs_ble_num_bufs 15
,E/bt-btm  ( 3345): BTM_SecRegister:p_cb_info->p_le_callback == 0xb3b2a231 
E/bt-btm  ( 3345): BTM_SecRegister: btm_cb.api.p_le_callback = 0xb3b2a231 
,D/MediaScannerReceiver( 1223): action: android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3640): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3640): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3640): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SecurityLogAgent( 1721): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 1721): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 1721): StateMachine : Current State = 1
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     ( 1170): Explicit concurrent mark sweep GC freed 38219(1906KB) AllocSpace objects, 3(157KB) LOS objects, 30% free, 36MB/52MB, paused 587us total 80.519ms
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3640): TimaSignature is unavailable
,D/ActivityThread( 3640): Added TimaKeyStore provider
,E/Zygote  ( 3656): MountEmulatedStorage()
E/Zygote  ( 3656): v2
I/libpersona( 3656): KNOX_SDCARD checking this for 1000
I/libpersona( 3656): KNOX_SDCARD not a persona
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/ActivityManager(  883): Start proc com.sec.android.service.sm for broadcast com.sec.android.service.sm/.receiver.SecurityManagerReceiver: pid=3656 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3656): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3656): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3656): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WVMDrmPlugIn(  291): WVMDrmPlugin::onInitialize : 1483
D/WVMDrmPlugIn(  291): WVMDrmPlugin::onSetOnInfoListener : add 1483
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
,I/DrmEventService(  883): action event :android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 3656): TimaSignature is unavailable
,D/ActivityThread( 3656): Added TimaKeyStore provider
,I/ActivityManager(  883): Killing 2025:com.sec.android.widget.samsungapps/u0a153 (adj 15): bgCount ##41
,I/TimaServiceEventReceiver(  883): TimaServiceEventReceiver : onReceive
,E/CscReceiver( 1462): onReceive android.intent.action.BOOT_COMPLETED
,D/ResourcesManager( 3640): creating new AssetManager and set to /system/app/ClockPackage/ClockPackage.apk
,D/ResourcesManager( 3656): creating new AssetManager and set to /system/app/SecurityManagerService/SecurityManagerService.apk
,I/ANDROID_DRM_FRWORKS_DrmManager(  291): DrmManager::acquireDrmInfo::No decrypt session open not need to handle TV out or HDMI
,W/ResourcesManager( 3640): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3640): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3640): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3640): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3640): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/CscUpdateService( 1462): onStart
,E/CscUpdateService( 1462): costomer file is exists : it has been preconfiged.
I/CscUpdateService( 1462): set_CSC_version
,E/Zygote  ( 3675): MountEmulatedStorage()
E/Zygote  ( 3675): v2
I/libpersona( 3675): KNOX_SDCARD checking this for 10003
I/libpersona( 3675): KNOX_SDCARD not a persona
,E/CscParser( 1462): update(): xml file exist
,I/ActivityManager(  883): Start proc com.samsung.android.providers.context for broadcast com.samsung.android.providers.context/.ContextSystemBroadcastReceiver: pid=3675 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/SSRM:a  (  883): DeviceInfo:: 000000000000
D/SSRM:a  (  883): SettingsAirViewInfo:: 000000000
,I/SELinux ( 3675): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3675): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3675): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  883): failed to open /acct/uid_10153/pid_2025/cgroup.procs: No such file or directory
,I/System.out( 1462): HandDataNode = null
I/CscUpdateService( 1462): PATH_CSCNAME =CustomerDataSet.CSCName
,I/CscUpdateService( 1462): This is normal boot : CSC not updated
,W/ContextImpl( 3656): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.service.sm.receiver.SecurityManagerReceiver.onReceive:31 android.app.ActivityThread.handleReceiver:2945 
,E/CscParser( 1462): update(): xml file exist
,I/CscUpdateService( 1462): same CSC Version
,D/CscUtil ( 1462): Set Build Fingerprint to samsung/kltexx/klte:5.0/LRX21T/G900FXXU1BOD3:user/release-keys
,D/BluetoothAdapterProperties( 3345): BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true
,E/bt-btif ( 3345): Calling BTA_HhEnable
,E/bt-btif ( 3345): BTM_SEC_REG[8  : sec: 0x1086, service name [] (up to 21 
D/BluetoothAdapterProperties( 3345): Address is:B0:C5:59:3F:75:69
E/BluetoothServiceJni( 3345): populateRssiValuesNative
I/bluedroid( 3345): getModelRssiValues
E/BluetoothServiceJni( 3345): model_rssi_values_callback: low = -70, mid = -60, high = 127
D/BluetoothAdapterProperties( 3345): modelRssiValuesCallback, low, mid, high = -70,-60,127
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/SecurityManager( 3656): v1.0.14
,D/SecurityManager( 3656): check the current status #1 ...
,D/SecurityManager( 3656): the current mode : 4
,D/SecurityManager( 3656): rv generation start
,D/TimaKeyStoreProvider( 3675): TimaSignature is unavailable
,D/ActivityThread( 3675): Added TimaKeyStore provider
,D/CscGPS  ( 1462): CSCGPS.updateParameters
D/CscGPS  ( 1462): supl host : null
,D/CscGPS  ( 1462): SUPL Host is null or invalid
D/CscGPS  ( 1462): supl_ver : null
,D/CscGPS  ( 1462): SUPL Ver is null or invalid
E/Zygote  ( 3693): MountEmulatedStorage()
I/libpersona( 3693): KNOX_SDCARD checking this for 10170
E/Zygote  ( 3693): v2
I/libpersona( 3693): KNOX_SDCARD not a persona
,D/CscGPS  ( 1462): supl port : null
D/CscGPS  ( 1462): SUPL PORT is null or invalid
D/CscGPS  ( 1462): LPP : null
D/CscGPS  ( 1462): LPP is null or invalid
D/CscGPS  ( 1462): CSC don't have any AGPS value.
,I/ActivityManager(  883): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=3693 uid=10170 gids={50170, 9997, 1023} abi=armeabi-v7a
,D/BluetoothAdapterProperties( 3345): Name is: Thali Test (Galaxy S5)
,D/MediaScannerService( 1223): !@start scanning volume internal: [/system/media, /oem/media]
,D/SecurityManager( 3656): security.mdpp : Ready
I/SecurityManager( 3656): init CCMode : 0
,I/SELinux ( 3693): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/SettingsProvider(  883): name = bluetooth_name
I/SELinux ( 3693): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3693): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothAdapterProperties( 3345): Scan Mode:20
,D/BluetoothAdapterProperties( 3345): Discoverable Timeout:120
D/BluetoothAdapterProperties( 3345): LE Address is:F0:8B:B2:7E:EA:D2
E/bt-btif ( 3345): btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
D/bt_vendor( 3345): op for 2
D/bt_vendor( 3345): op for 6
E/bt-btif ( 3345): btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,D/TimaKeyStoreProvider( 3693): TimaSignature is unavailable
,D/ActivityThread( 3693): Added TimaKeyStore provider
,E/bt-btif ( 3345): btif_sock_init: !radio_req && !rfc_init
E/bt-btif ( 3345): btif_sock_init: !vhci_init
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): proc btwrite assertion
,D/IOP_DB_BT( 3345): db_open: file /etc/bluetooth/iop_bt.db
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/IOP_DB_BT( 3345): db_open: db_open : handle 3014221840l, read 13774 bytes onto local cache
D/IOP_DB_BT( 3345): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 3345): db_query: result 1
I/        ( 3345): iop_db_open: iop_db_open status 0
,D/bte_conf( 3345): Device ID record 1 : primary
D/bte_conf( 3345):   vendorId            = 0075
D/bte_conf( 3345):   vendorIdSource      = 0001
D/bte_conf( 3345):   product             = 0100
D/bte_conf( 3345):   version             = 0200
,D/bte_conf( 3345):   clientExecutableURL = 
D/bte_conf( 3345):   serviceDescription  = 
D/bte_conf( 3345):   documentationURL    = 
D/bte_conf( 3345): bte_load_did_conf no section named DID2.
D/BluetoothAdapterState( 3345): CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 3345): ScanMode =  20
D/BluetoothAdapterProperties( 3345): State =  11
,D/BluetoothPanServiceJni( 3345): control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,D/SecContentProvider(  883): uri = 3 selection = isDiscoverableEnabled
,D/BluetoothAdapterProperties( 3345): Setting state to 12
I/BluetoothAdapterState( 3345): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterProperties( 3345): Scan Mode:21
D/BluetoothAdapterProperties( 3345): Discoverable Timeout:120
,D/MtpService( 1223): updating state; isCurrentUser=true, mMtpLocked=false
D/SettingsProvider(  883): name = bluetooth_a2dp_sink_mode
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1002
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,D/BluetoothAdapterService( 3345): Bluetooth PBAP supproted is true
,D/BluetoothAdapterService( 3345): updateAdapterState state is 12
,E/bt_h4   ( 3345): vendor lib postload completed
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/ResourcesManager( 3675): creating new AssetManager and set to /system/priv-app/ContextProvider/ContextProvider.apk
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/ResourcesManager( 3693): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
,D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/BluetoothA2dp(  883): onBluetoothStateChange: up=true
,D/BluetoothA2dp( 3345): onBluetoothStateChange: up=true
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/BluetoothAdapterService( 3345): Autoconnection is available 
,D/BluetoothAdapterService( 3345): updateAdapterState prevState = 11newState = 12
D/BluetoothAdapterService( 3345): starting service from this receiver
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,I/BluetoothPbapService( 3345): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,I/BluetoothPbapService( 3345): Handler(): got msg=1
,I/BluetoothAdapterState( 3345): Entering On State from state = 11
,D/TP/MmsProvider( 1462): Update uri=content://mms, match=0
,W/InputMethodManagerService(  883): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  883): [BT Setting State] State =12
I/InputMethodManagerService(  883): [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/TP/MmsProvider( 1462): update , handleReadChangedBroadcast
D/TP/MmsSmsProvider( 1462): need read changed broadcast:false
,D/SecContentProvider(  883): uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,V/BluetoothPbapService( 3345): PBAP Service initSocket try: 0
,I/SamsungIME( 1869): STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/BluetoothHeadset( 1449): registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1d024238, true
,D/BluetoothTile( 1170): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothHeadset( 1449): registerMessageListener
,D/STATUSBAR-QSTileView( 1170): onStateChanged: Bluetooth
,D/HeadsetService( 3345): registerMessageListener
D/HeadsetService( 3345): registerMessageListener
D/HeadsetStateMachine( 3345): Disconnected process message: 70
D/HeadsetStateMachine( 3345): processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3af0ba5a
,I/Mms:transaction( 2964): [MmsSystemEventReceiver] restorePduNotificationStatus count=0
,D/Mms/MessagingNotification( 2964): [start]    nonBlockingUpdateMessageIndicator() consume time = 6071.16453
,I/Telecom ( 1449): BluetoothPhoneService: updateHeadsetWithCallState
I/Telecom ( 1449): BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,D/[CarModeFW]( 2647): ConnectivityManager-handleMessage INITIAL_STATE_ON
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_bluetooth_on.png
,I/Mms/ReservationManager( 2964): resetAfterConnected()
,D/BluetoothManagerService(  883): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/Mms/MessagingNotification( 2964): sDisableVibrateForCamera = false
,D/Mms/TelephonyPermission( 2964): isDefault true
,W/BluetoothAdapter( 3345): getBluetoothService() called with no BluetoothManagerCallback
,D/HeadsetStateMachine( 3345): Disconnected process message: 9
,D/HeadsetStateMachine( 3345): mNumActive: 0 mNumHeld: 0 mCallState: 6
D/TP/MmsProvider( 1462): Query uri=content://mms, match=0, calling pid = 2964
,D/BluetoothSocket( 3345): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
D/BluetoothSocket( 3345): bindListen(), new LocalSocket 
D/BluetoothSocket( 3345): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 3345): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e0a4e67
D/TP/MmsSmsProvider( 1462): query,matched:7, calling pid = 2964
D/BluetoothSocket( 3345): channel: 19
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/BluetoothPbapService( 3345): PBAP Socket is BluetoothServerSocket
,D/BluetoothMapMasInstance( 3345): set MAP SDP message type : 1
,D/TP/MmsSmsProvider( 1462): match 7:Elapsed time : 6.877 ms
,E/SQLiteLog( 1223): (283) recovered 155 frames from WAL file /data/data/com.android.providers.media/databases/internal.db-wal
,E/SQLiteLog( 3693): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/audio_hw_primary(  292): adev_set_parameters: enter: A2dpSuspended=false
,V/voice   (  292): voice_set_parameters: enter: A2dpSuspended=false
V/voice   (  292): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  292): platform_set_parameters: enter: A2dpSuspended=false
V/msm8974_platform(  292): platform_set_parameters: exit with code(-2)
D/audio_hw_hfp(  292): audio_extn_hfp_set_parameters: enter
,V/audio_hw_primary(  292): adev_set_parameters: exit
E/HeadsetStateMachine( 3345): terminateScoUsingVirtualVoiceCall:No present call to terminate
,E/Zygote  ( 3718): MountEmulatedStorage()
I/libpersona( 3718): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3718): v2
I/libpersona( 3718): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.samsung.android.app.colorblind for broadcast com.samsung.android.app.colorblind/.ColorBlindBootReceiver: pid=3718 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/BluetoothAdapter( 3345): getBluetoothService() called with no BluetoothManagerCallback
,I/SELinux ( 3718): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/BluetoothSocket( 3345): bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
D/BluetoothSocket( 3345): bindListen(), new LocalSocket 
D/BluetoothSocket( 3345): bindListen(), new LocalSocket.getInputStream() 
D/BluetoothSocket( 3345): bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38f0f414
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/BluetoothSocket( 3345): channel: 5
,I/SELinux ( 3718): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3718): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/TimaKeyStoreProvider( 3718): TimaSignature is unavailable
,D/ActivityThread( 3718): Added TimaKeyStore provider
,I/art     (  883): Explicit concurrent mark sweep GC freed 49540(3MB) AllocSpace objects, 29(553KB) LOS objects, 31% free, 34MB/50MB, paused 1.284ms total 134.499ms
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TP/MmsSmsProvider( 1462): query,matched:200, calling pid = 2964
,D/MediaScanner( 1223): Prescan. DB items number : 152 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/TP/MmsSmsProvider( 1462): match 200:Elapsed time : 4.018 ms
,D/ResourcesManager( 3718): creating new AssetManager and set to /system/app/ColorBlind/ColorBlind.apk
,I/Mms/ReservationManager( 2964): getReservedSendMessageCount(): retMessageCount=0
,W/ResourcesManager( 3718): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,I/SecureStorage( 3675): [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,I/SecureStorage( 3675): [INFO]: SPID(0x00000000)This device supports Secure Storage
,I/SecureStorage(  357): [INFO]: SPID(0x00000003)Credentials: uid 10003, gid 10003, pid 3675
I/SecureStorage(  357): [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
I/SecureStorage( 3675): [INFO]: SPID(0x00000000)SS Daemon is running
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/SecureStorage( 3675): [INFO]: SPID(0x00000000)Processing data
,I/SecureStorage(  357): [INFO]: SPID(0x00000003)Credentials: uid 10003, gid 10003, pid 3675
I/SecureStorage(  357): [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,E/Zygote  ( 3738): MountEmulatedStorage()
,E/Zygote  ( 3738): v2
I/libpersona( 3738): KNOX_SDCARD checking this for 10052
I/libpersona( 3738): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.app.safetyassurance for broadcast com.sec.android.app.safetyassurance/.SafetyAssuranceReceiver: pid=3738 uid=10052 gids={50052, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 3738): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/Mms/SmsReceiverService( 2964): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.BOOT_COMPLETED
,I/SELinux ( 3738): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3738): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Mms/TelephonyPermission( 2964): isDefault true
,D/Mms/SmsReceiverService( 2964): [SMS]Receiver handleMessage : Action =android.intent.action.BOOT_COMPLETED
D/Mms/SmsReceiverService( 2964): [start]    handleBootCompleted() consume time = 292.675781
,E/Zygote  ( 3750): MountEmulatedStorage()
E/Zygote  ( 3750): v2
,I/libpersona( 3750): KNOX_SDCARD checking this for 10092
I/libpersona( 3750): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=3750 uid=10092 gids={50092, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 2096:com.sec.kidsplat.installer/u0a166 (adj 15): bgCount ##41
,D/tv.peel.samsung.widget.NotiRemoteService( 1835): action com.peel.widget.notification.SETUP_SERVICE_CONNECTION
,D/tv.peel.samsung.widget.NotiRemoteService( 1835): connectToPeelService 0
,W/ContextImpl( 1835): Implicit intents with startService are not safe: Intent { act=tv.peel.samsung.widget.service.IPeelService } android.content.ContextWrapper.bindService:559 tv.peel.samsung.widget.a.<init>:76 tv.peel.samsung.widget.NotiRemoteService.a:561 
,I/SELinux ( 3750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3750): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2964
,D/TimaKeyStoreProvider( 3738): TimaSignature is unavailable
,D/TP/SmsProvider( 1462): match 0:Elapsed time : 0.884 ms
D/ActivityThread( 3738): Added TimaKeyStore provider
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 3750): TimaSignature is unavailable
D/ActivityThread( 3750): Added TimaKeyStore provider
,I/ActivityManager(  883): Start proc com.sec.dsm.system for broadcast com.sec.dsm.system/.DSMReceiver: pid=3768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 3768): MountEmulatedStorage()
E/Zygote  ( 3768): v2
I/libpersona( 3768): KNOX_SDCARD checking this for 1000
I/libpersona( 3768): KNOX_SDCARD not a persona
,V/MediaScanner( 1223): processDirectory :  /system/media
,I/art     (  327): Explicit concurrent mark sweep GC freed 8766(372KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 275us total 19.106ms
,I/SELinux ( 3768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 8.334ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 262us total 8.099ms
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3783): MountEmulatedStorage()
,E/Zygote  ( 3783): v2
I/libpersona( 3783): KNOX_SDCARD checking this for 1101
I/libpersona( 3783): KNOX_SDCARD not a persona
,W/libprocessgroup(  883): failed to open /acct/uid_10166/pid_2096/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=3783 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,D/tv.peel.samsung.widget.NotiRemoteService( 1835): onServiceOn() mServiceState = 1
D/tv.peel.samsung.widget.NotiRemoteService( 1835): Send action to self com.peel.widget.notification.SERVICE_BINDED
,I/qtaguid ( 3425): Untagging socket 34
,W/ApiaryClient( 3425): Error response from books API: {
W/ApiaryClient( 3425):  "error": {
W/ApiaryClient( 3425):   "errors": [
W/ApiaryClient( 3425):    {
W/ApiaryClient( 3425):     "domain": "global",
W/ApiaryClient( 3425):     "reason": "required",
W/ApiaryClient( 3425):     "message": "Login Required",
W/ApiaryClient( 3425):     "locationType": "header",
W/ApiaryClient( 3425):     "location": "Authorization"
W/ApiaryClient( 3425):    }
W/ApiaryClient( 3425):   ],
W/ApiaryClient( 3425):   "code": 401,
W/ApiaryClient( 3425):   "message": "Login Required"
W/ApiaryClient( 3425):  }
W/ApiaryClient( 3425): }
,W/ApiaryClient( 3425): errCount = 1: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 3425): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2458281435795576837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 3425): Headers suppressed
,V/MediaScanner( 1223):  prescan time: 388ms (DB items: 152)
V/MediaScanner( 1223):     scan time: 84ms (Caching mode: true), (makeEntry time: 20ms ~23%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 0ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 1223):    total time: 472ms
V/MediaScanner( 1223): checked files: 144  directories : 6  (I: 0, U: 0)
,D/MediaScanner( 1223): checkDefaultSounds
,D/MediaScanner( 1223): system alarm_alert  : Vwiurug_etwofi5wgg
,I/SELinux ( 3783): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TimaKeyStoreProvider( 3768): TimaSignature is unavailable
,I/SELinux ( 3783): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/ActivityThread( 3768): Added TimaKeyStore provider
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
E/SELinux ( 3783): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  883): Killing 2405:com.sec.android.widgetapp.ap.hero.accuweather/u0a71 (adj 15): bgCount ##41
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine(  883): CMD_RSSI_POLL : out!
D/tv.peel.samsung.widget.NotiRemoteService( 1835): action com.peel.widget.notification.SERVICE_BINDED
,D/tv.peel.samsung.widget.NotiRemoteService( 1835): feature is Off. Stop service
,D/tv.peel.samsung.widget.NotiRemoteService( 1835): Send action to self com.peel.widget.notification.STOP_PROCESS
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/TimaKeyStoreProvider( 3783): TimaSignature is unavailable
,D/ActivityThread( 3783): Added TimaKeyStore provider
D/tv.peel.samsung.widget.NotiRemoteService( 1835): action com.peel.widget.notification.STOP_PROCESS
D/TP/SmsProvider( 1462): query,matched:51, calling pid = 2964
,D/tv.peel.samsung.widget.NotiRemoteService( 1835): onDestroy()
D/TP/SmsProvider( 1462): match 51:Elapsed time : 0.976 ms
,D/tv.peel.samsung.widget.NotiRemoteService( 1835): mOrientationChangeReceier was not registered
,D/ResourcesManager( 3738): creating new AssetManager and set to /system/priv-app/SecSafetyAssurance/SecSafetyAssurance.apk
,D/ResourcesManager( 3750): creating new AssetManager and set to /system/app/ConfigUpdater/ConfigUpdater.apk
,D/ResourcesManager( 3768): creating new AssetManager and set to /system/priv-app/DSMLawmo/DSMLawmo.apk
,W/ResourcesManager( 3738): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3738): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3738): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,D/MediaScanner( 1223): OK. alarm_alert is already exist in setting DB.
,I/Icing   ( 2457): Internal init done: storage state 0
,D/TP/MmsSmsProvider( 1462): deleteConversation threadId: 9223372036854775806
,D/MediaScanner( 1223): system notification_sound  : K_Oprkltf5wgg
,D/TP/MmsSmsProvider( 1462): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1462): (284) automatic index on im_threads(normal_thread_id)
,D/ResourcesManager( 3783): creating new AssetManager and set to /system/app/SmartcardService/SmartcardService.apk
,D/MediaScanner( 1223): OK. notification_sound is already exist in setting DB.
,D/Mms/MessagingNotification( 2964): isBlockingModeEnabled() = false, Zen mode = 0
,W/ResourcesManager( 3783): Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,D/MediaScanner( 1223): system ringtone  : Wmfi_lpf_pwirywu5wgg
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/MediaScanner( 1223): OK. ringtone is already exist in setting DB.
,D/TP/MmsSmsProvider( 1462): delete threadId: 9223372036854775806
D/TP/MmsSmsProvider( 1462): need read changed broadcast:false
,D/Mms/Conversation( 2964): deleteTempConversation(),deleted=0
,W/libprocessgroup(  883): failed to open /acct/uid_10071/pid_2405/cgroup.procs: No such file or directory
,D/SettingsProvider(  883): name = block_emergency_message
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 10052
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,V/SmartcardService( 3783): main Received broadcast
V/SmartcardService( 3783): Starting smartcard service after boot completed
,D/FactoryTestApp( 3252): [DummyFtClient$mBroadcastReceiver](3252) action= = android.intent.action.MEDIA_SCANNER_FINISHED
W/ActivityManager(  883): getTasks: caller 10052 is using old GET_TASKS but privileged; allowing
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/BadgeProvider( 1604): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
D/FactoryTestApp( 3252): [DummyFtClient$mBroadcastReceiver](3252) ACTION_MEDIA_SCANNER_FINISHED = /system/media
,D/FactoryTestApp( 3252): [DummyFtClient$mBroadcastReceiver](3252) ACTION_MEDIA_SCANNER_FINISHED = Ignored
D/MediaScannerService( 1223): !@done scanning volume internal
,D/MediaScannerService( 1223): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,E/SQLiteLog( 3768): (283) recovered 8 frames from WAL file /data/data/com.sec.dsm.system/databases/profile.db-wal
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/ActivityManager(  883): Killing 2670:com.sec.android.app.videoplayer/u0a54 (adj 15): bgCount ##41
,D/BadgeProvider( 1604): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1604): sendNotify, [notify] : null
D/BadgeProvider( 1604): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1604): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1604): update, [UpdateCount] : 1
,D/Launcher.Model( 1476): reloadBadges entered.
,D/SmsProvider( 1462): Update uri=content://sms/outbox, match=8
,D/Mms/MessagingNotification( 2964): setBadgeCount(), count=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/Mms/MessagingNotification( 2964): remove alarm
,D/DSM     ( 3768): [Lines:108] Normal booted
,D/DSM     ( 3768): [Lines:115] Boot completed
,E/Zygote  ( 3801): MountEmulatedStorage()
I/libpersona( 3801): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3801): v2
I/libpersona( 3801): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=3801 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 1531:com.android.printspooler/u0a151 (adj 15): bgCount ##41
,D/TP/MmsSmsProvider( 1462): need read changed broadcast:false
,I/SELinux ( 3801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/WifiCredService( 1315): onCreate
,I/Avrcp   ( 3345): Received the onChange database event
I/Avrcp   ( 3345): onChange on thread: 1 Uri: content://media/ selfchange: false
I/Avrcp   ( 3345): send MSG_CHECK_NOW_PLAYING_CONTENT_CHANGED after 500ms
,D/Mms/SmsReceiverService( 2964): moveOutboxMessagesToFailedBox messageCount: 0
D/Mms/SmsReceiverService( 2964): handle boot completed, sendFirstQueuedMessage()
D/Mms/SmsReceiverService( 2964): [SIM-1]sendFirstQueuedMessage()
,E/UpdateRequestReceiver( 3750): ignoring update request
,I/Icing   ( 2457): Post-init done
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2964
,D/TP/SmsProvider( 1462): match 0:Elapsed time : 2.671 ms
,D/TP/SmsProvider( 1462): query,matched:26, calling pid = 2964
,D/TimaKeyStoreProvider( 3801): TimaSignature is unavailable
,D/WifiTimerReceiver( 1315): action: android.intent.action.BOOT_COMPLETED
,D/WifiTimerReceiver( 1315): extra: Bundle[mParcelledData.dataSize=84]
D/ActivityThread( 3801): Added TimaKeyStore provider
,D/MY_TAG  ( 1315): Action boot completed received
,E/HttpOperation( 3405): [getaccountstatus] Unexpected exception
E/HttpOperation( 3405): java.io.IOException: Cannot obtain authentication token
E/HttpOperation( 3405): 	at kfv.a(PG:65)
E/HttpOperation( 3405): 	at kff.u(PG:385)
E/HttpOperation( 3405): 	at kfb.a(PG:29)
E/HttpOperation( 3405): 	at ixd.a(PG:248)
E/HttpOperation( 3405): 	at ixd.b(PG:206)
E/HttpOperation( 3405): 	at ixd.a(PG:175)
E/HttpOperation( 3405): 	at fig.a(PG:78)
E/HttpOperation( 3405): 	at lex.a(PG:85)
E/HttpOperation( 3405): 	at lex.b(PG:132)
E/HttpOperation( 3405): 	at fhk.a(PG:1146)
E/HttpOperation( 3405): 	at fhk.a(PG:908)
E/HttpOperation( 3405): 	at fhk.onPerformSync(PG:636)
E/HttpOperation( 3405): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/HttpOperation( 3405): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/HttpOperation( 3405): 	at ihi.a(PG:22)
E/HttpOperation( 3405): 	at kft.a(PG:91)
E/HttpOperation( 3405): 	at kfv.a(PG:62)
E/HttpOperation( 3405): 	... 12 more
E/HttpOperation( 3405): Caused by: gdi: User intervention required. Notification has been pushed.
E/HttpOperation( 3405): 	at gde.c(Unknown Source)
E/HttpOperation( 3405): 	at gde.b(Unknown Source)
E/HttpOperation( 3405): 	at ihi.a(PG:19)
E/HttpOperation( 3405): 	... 14 more
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
,E/EsSyncAdapterService( 3405): Sync failure
E/EsSyncAdapterService( 3405): java.io.IOException: Rpc failed
E/EsSyncAdapterService( 3405): 	at ixd.a(PG:348)
E/EsSyncAdapterService( 3405): 	at ixd.a(PG:248)
E/EsSyncAdapterService( 3405): 	at ixd.b(PG:206)
E/EsSyncAdapterService( 3405): 	at ixd.a(PG:175)
E/EsSyncAdapterService( 3405): 	at fig.a(PG:78)
E/EsSyncAdapterService( 3405): 	at lex.a(PG:85)
E/EsSyncAdapterService( 3405): 	at lex.b(PG:132)
E/EsSyncAdapterService( 3405): 	at fhk.a(PG:1146)
E/EsSyncAdapterService( 3405): 	at fhk.a(PG:908)
E/EsSyncAdapterService( 3405): 	at fhk.onPerformSync(PG:636)
E/EsSyncAdapterService( 3405): 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
E/EsSyncAdapterService( 3405): Caused by: java.io.IOException: Cannot obtain authentication token
E/EsSyncAdapterService( 3405): 	at kfv.a(PG:65)
E/EsSyncAdapterService( 3405): 	at kff.u(PG:385)
E/EsSyncAdapterService( 3405): 	at kfb.a(PG:29)
E/EsSyncAdapterService( 3405): 	... 10 more
E/EsSyncAdapterService( 3405): Caused by: android.accounts.AuthenticatorException: Cannot get Oauth2 token from GMS
E/EsSyncAdapterService( 3405): 	at ihi.a(PG:22)
E/EsSyncAdapterService( 3405): 	at kft.a(PG:91)
E/EsSyncAdapterService( 3405): 	at kfv.a(PG:62)
E/EsSyncAdapterService( 3405): 	... 12 more
E/EsSyncAdapterService( 3405): Caused by: gdi: User intervention required. Notification has been pushed.
E/EsSyncAdapterService( 3405): 	at gde.c(Unknown Source)
E/EsSyncAdapterService( 3405): 	at gde.b(Unknown Source)
E/EsSyncAdapterService( 3405): 	at ihi.a(PG:19)
E/EsSyncAdapterService( 3405): 	... 14 more
,D/Mms/MessagingNotification( 2964): updateAllHistoryAsRead()
,D/WifiCredService( 1315): Action received :android.net.wifi.WIFI_STATE_CHANGED
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/TP/SmsProvider( 1462): match 26:Elapsed time : 24.497 ms
,E/Zygote  ( 3822): MountEmulatedStorage()
I/libpersona( 3822): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3822): v2
I/libpersona( 3822): KNOX_SDCARD not a persona
I/WifiStateMachine(  883): callSECApi what=207
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,I/ActivityManager(  883): Start proc com.sec.android.app.factorykeystring for broadcast com.sec.android.app.factorykeystring/com.sec.android.app.entry.FactoryKeyStringBroadcastReceiver: pid=3822 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
,E/WifiStateMachine(  883): DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
D/WifiNative-HAL(  883): callSECStringApiVoid - ID [215]
E/WifiNative-HAL(  883): invaild command id : 215
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 1223): savePlaylistTableInBulkDeleter finished
,I/SecureStorage(  357): [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
I/SecureStorage(  357): [INFO]: SPID(0x00000003)PID: 3675, TID: 3735
,I/art     ( 1462): Explicit concurrent mark sweep GC freed 35286(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 14MB/24MB, paused 483us total 44.385ms
,I/SELinux ( 3822): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3822): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3822): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/ActivityManager(  883): Killing 2698:com.sec.android.app.mv.player/u0a56 (adj 15): bgCount ##41
,W/libprocessgroup(  883): failed to open /acct/uid_10054/pid_2670/cgroup.procs: No such file or directory
,D/Mms/MessagingNotification( 2964): [end]    nonBlockingUpdateMessageIndicator() consume time = 531.01578
,D/TimaKeyStoreProvider( 3822): TimaSignature is unavailable
W/libprocessgroup(  883): failed to open /acct/uid_10151/pid_1531/cgroup.procs: No such file or directory
,D/MediaScanner( 1223): Prescan. DB items number : 21 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,D/ActivityThread( 3822): Added TimaKeyStore provider
,E/UpdateRequestReceiver( 3750): ignoring update request
,D/ResourcesManager( 3801): creating new AssetManager and set to /system/app/SysScope/SysScope.apk
,D/Mms/SmsReceiver( 2964): unregisterForServiceStateChanges, already unregistered
D/Mms/MessagingNotification( 2964): sDisableVibrateForCamera = false
D/Mms/TelephonyPermission( 2964): isDefault true
,I/Hs20UtilService( 1315): Starting #5
,I/Hs20UtilService( 1315): Message received 5003
,D/ResourcesManager( 3822): creating new AssetManager and set to /system/priv-app/DeviceKeystring/DeviceKeystring.apk
,W/ResourcesManager( 3822): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,V/MediaScanner( 1223): processDirectory :  /storage/emulated/0
,D/TP/MmsProvider( 1462): Query uri=content://mms, match=0, calling pid = 2964
,D/MediaScanner( 1223): Skipping:
D/MediaScanner( 1223): 7klwibgf7fvntblfd7(75ebcf7
,D/NearbySettings( 1315): MountReceiver.onReceive - ACTION: android.intent.action.BOOT_COMPLETED
,D/SettingsProvider(  883): name = com.samsung.android.nearby.mediaserver.NEARBY_SERVER_STARTED
,V/NearbySettings( 1315): MountReceiver.mPrefHandler - 7002
,E/UpdateRequestReceiver( 3750): ignoring update request
,D/ResourcesManager( 2457): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ContextImpl( 3801): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:2945 
,D/SyncManager(  883): failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 19690, reason: Periodic, SyncResult: stats [ numIoExceptions: 2]
,D/TP/MmsSmsProvider( 1462): query,matched:200, calling pid = 2964
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/NearbySettings( 1315): MountReceiver.onReceive - Path: (systemPath)/storage/emulated/0/Download, (internalPath)/storage/emulated/0/Download, (externalPath)/storage/extSdCard/Download
I/NearbySettings( 1315): MountReceiver.onReceive - Internal Path
,D/TP/MmsSmsProvider( 1462): match 200:Elapsed time : 7.440 ms
,D/ResourcesManager( 2881): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,D/SettingsProvider(  883): name = personal_mode_enabled
W/ActivityThread( 3822): ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/UpdateRequestReceiver( 3750): ignoring update request
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]parseXML, [Message]modelXML=sm-g900f.dat
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]parseXML, [Message]deviceXML=klte.dat
,E/Zygote  ( 3850): MountEmulatedStorage()
E/Zygote  ( 3850): v2
I/libpersona( 3850): KNOX_SDCARD checking this for 10176
I/libpersona( 3850): KNOX_SDCARD not a persona
,E/SMD     (  287): DCD ON
,I/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]parseAsset, [Message]Convert enc file to xml file: sm-g900f.dat
,I/ActivityManager(  883): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=3850 uid=10176 gids={50176, 9997} abi=armeabi-v7a
,D/MediaScanner( 1223): Skipping:
,D/MediaScanner( 1223): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/MediaScanner( 1223): processDirectory :  /storage/extSdCard
W/MediaScanner( 1223): Error opening directory, reason : Permission denied.
W/MediaScanner( 1223): 7klwibgf7fxlKdCbid7
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]parseAsset, [Message]Decode base xml file: lcdtest.dat
,I/SELinux ( 3850): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3850): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3850): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/libprocessgroup(  883): failed to open /acct/uid_10056/pid_2698/cgroup.procs: No such file or directory
,E/File    ( 1223): fail readDirectory() errno=2
,I/SmartcardBootCompleteReceiver( 1315): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1315): Received intent with action - android.intent.action.BOOT_COMPLETED
,V/MediaScanner( 1223): pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@78cab52
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,V/MediaScanner( 1223): /pruneDeadThumbnailFiles... android.database.sqlite.SQLiteCursor@78cab52
,E/UpdateRequestReceiver( 3750): ignoring update request
,V/MediaScanner( 1223):  prescan time: 101ms (DB items: 21)
V/MediaScanner( 1223):     scan time: 80ms (Caching mode: true), (makeEntry time: 55ms ~68%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 1223): postscan time: 44ms (bulkDeleter : 0), (delete DeadThumbnail time : 19ms)
V/MediaScanner( 1223):    total time: 225ms
V/MediaScanner( 1223): checked files: 4  directories : 17  (I: 0, U: 0)
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:2945 
,D/TimaKeyStoreProvider( 3850): TimaSignature is unavailable
,D/ActivityThread( 3850): Added TimaKeyStore provider
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_NAME
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_ACCELEROMETER
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_MAGNETIC
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_NAME_GYROSCOPE
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MAGNETIC_ROTATE_DEGREE
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LCD_TYPE
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IRLED_CONCEPT
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_EPEN
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=MODEL_COMMUNICATION_MODE
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=DEVICE_TYPE
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TOUCHKEY_GRAPH
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_TSP_SUPPORT_CONFIG_VERSION
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_COMPLEX_LOOPBACK_TEST
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_FW_UPDATE_INTERNAL
I/SmartcardBootCompleteReceiver( 1315): Broadcast sent with current lockscreen type
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_NEED_TURNON_LEDKEY
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_TSK_PATH_AUTOCAL_SKIP
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SIMPLE_TEST_ACC_SYSFS
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_SENSOR_TEST_ACC_REVERSE
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SENSOR_TEST_ACC_BIT
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_DISPLAY_LUX_ADC
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_PROXIMITY_TEST_MOTOR_FEEDBACK
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=IS_INNER_OUTER_TOUCHKEY
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=SUPPORT_COMPLEX_LOOPBACK_PATH
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_APP_RECENT
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=KEY_TEST_BACK
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=NO_RGBSENSOR_SUPPORT_REV
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=GESTURE_CROSSTALK_RAW
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_X_AXIS_CHANNEL
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2964
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=TSP_Y_AXIS_CHANNEL
E/UpdateRequestReceiver( 3750): ignoring update request
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_LEVEL_2_MAX
D/ResourcesManager( 2881): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_1
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_2
D/TP/SmsProvider( 1462): match 0:Elapsed time : 2.317 ms
D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_3
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_4
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_UP_LEVEL_5
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_2
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_3
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_4
,D/FactoryTestApp( 3252): [DummyFtClient$mBroadcastReceiver](3252) action= = android.intent.action.MEDIA_SCANNER_FINISHED
D/FactoryTestApp( 3252): [DummyFtClient$mBroadcastReceiver](3252) ACTION_MEDIA_SCANNER_FINISHED = /storage/emulated/0
D/FactoryTestApp( 3252): [DummyFtClient$sendBootCompletedAndFinish](3252) ...
,D/FactoryTestApp( 3252): [Support$Values.getString](3252) id=MODEL_COMMUNICATION_MODE, value=gsm
I/FactoryTestApp( 3252): [ModuleCommon$isConnectionModeNone](3252) mConnectionMode = gsm
,D/LcdtestApp( 3822): [Class]XMLDataStorage, [Method]redefinitionById, [Message]id=LIGHT_SENSOR_DOWN_LEVEL_5
,D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/FactoryTestApp( 3252): [IPCWriterToSecPhoneService$ResponseWriter](3252) Create IPCWriterToSecPhoneService
I/FactoryTestApp( 3252): [IPCWriterToSecPhoneService$connectToSecPhoneService](3252)  
,D/MediaScannerService( 1223): !@done scanning volume external
,W/ContextImpl( 3252): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2067 android.content.ContextWrapper.bindService:559 com.sec.factory.aporiented.IPCWriterToSecPhoneService.connectToSecPhoneService:97 com.sec.factory.aporiented.IPCWriterToSecPhoneService.<init>:64 com.sec.factory.aporiented.DummyFtClient.sendBootCompletedAndFinish:147 
,I/LcdtestApp( 3822): [Class]FactoryKeyStringBroadcastReceiver, [Method]onReceive, , [Message]pref_hardReset : N
,D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,D/MediaScannerService( 1223): send command to ssrm : REQ_DROP_CACHE
,D/ResourcesManager( 3850): creating new AssetManager and set to /system/app/TaskManager/TaskManager.apk
,W/ResourcesManager( 3850): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3874): MountEmulatedStorage()
I/libpersona( 3874): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3874): v2
I/libpersona( 3874): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3874 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3874): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3874): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3874): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TP/SmsProvider( 1462): query,matched:51, calling pid = 2964
,I/FactoryTestApp( 3252): [IPCWriterToSecPhoneService$onServiceConnected](3252) connected done
D/FactoryTestApp( 3252): [IPCWriterToSecPhoneService$write](3252) Send Response Message to SecPhone
D/FactoryTestApp( 3252): [IPCWriterToSecPhoneService$write](3252) Response ��
,D/TP/SmsProvider( 1462): match 51:Elapsed time : 15.010 ms
,D/TimaKeyStoreProvider( 3874): TimaSignature is unavailable
,D/ActivityThread( 3874): Added TimaKeyStore provider
I/SecureStorage( 3675): [INFO]: SPID(0x00000000)Processing data has been completed
,I/SecureStorage( 3675): [INFO]: SPID(0x00000000)WARNING! Failed to find SecureStorageExceptionJNI!..
,D/FactoryTestApp( 3252): [IPCWriterToSecPhoneService$handleMessage](3252) Send BOOT COMPLETED done
,I/SQLiteSecureOpenHelper( 3675): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3675): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 3675): Open SecureContextLog.db in secure mode
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/[SBeam] ( 1315): SBeamEnabler.initPreferenceForSbeam : 0
,E/Zygote  ( 3894): MountEmulatedStorage()
E/Zygote  ( 3894): v2
I/libpersona( 3894): KNOX_SDCARD checking this for 10100
I/libpersona( 3894): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.automotive.drivelinkremote for broadcast com.sec.android.automotive.drivelinkremote/.BootCompleteReceiver: pid=3894 uid=10100 gids={50100, 9997} abi=armeabi-v7a
,I/SELinux ( 3894): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3894): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3894): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  883): Killing 2624:com.vlingo.midas/u0a33 (adj 15): bgCount ##41
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 3874): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,E/Zygote  ( 3908): MountEmulatedStorage()
I/libpersona( 3908): KNOX_SDCARD checking this for 10178
E/Zygote  ( 3908): v2
I/libpersona( 3908): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=3908 uid=10178 gids={50178, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 2609:com.samsung.android.intelligenceservice/u0a3 (adj 15): bgCount ##41
,V/Avrcp   ( 3345): handleMessage, msg=207
D/BluetoothMediaBrowser( 3345):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
I/SQLiteSecureOpenHelper( 3675): ...getDatabaseLocked(b,b,pwd)
D/SQLiteSecureOpenHelper( 3675): ...getDatabaseLocked(b,b,pwd)
,I/SELinux ( 3908): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3908): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3908): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3894): TimaSignature is unavailable
,D/ActivityThread( 3894): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 2964): isBlockingModeEnabled() = false, Zen mode = 0
,D/BluetoothMediaBrowser( 3345): no now playing list
D/BluetoothMediaBrowser( 3345):  getNowPlayingId now playing id : -1
D/Avrcp   ( 3345):  checkNowPlayingList start
,D/TimaKeyStoreProvider( 3908): TimaSignature is unavailable
,D/ActivityThread( 3908): Added TimaKeyStore provider
,I/SQLiteSecureOpenHelper( 3675): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3675): getDatabaseLocked(b,b,pwd)...
,I/SQLiteSecureOpenHelper( 3675): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3675): getDatabaseLocked(b,b,pwd)...
I/SQLiteSecureOpenHelper( 3675): Open SecureSurveyLog.db in secure mode
,D/ResourcesManager( 3894): creating new AssetManager and set to /system/app/DriveLinkRemote/DriveLinkRemote.apk
,I/SettingSearch/SearchIntentReceiver( 1315): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1315): search setting db init!!
,W/ContextImpl( 1315): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1672 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
,W/libprocessgroup(  883): failed to open /acct/uid_10003/pid_2609/cgroup.procs: No such file or directory
,W/[BootCompleteReceiver]( 3894): onReceive action:android.intent.action.BOOT_COMPLETED
,W/libprocessgroup(  883): failed to open /acct/uid_10033/pid_2624/cgroup.procs: No such file or directory
,I/SQLiteSecureOpenHelper( 3675): ...getDatabaseLocked(b,b,pwd)
,D/SQLiteSecureOpenHelper( 3675): ...getDatabaseLocked(b,b,pwd)
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/art     (  883): Explicit concurrent mark sweep GC freed 18625(1086KB) AllocSpace objects, 3(113KB) LOS objects, 31% free, 34MB/50MB, paused 3.546ms total 92.454ms
,D/BadgeProvider( 1604): query, [selection] : package='com.android.mms' AND class='com.android.mms.ui.ConversationComposer' AND extraData='base_extra_badge'
,E/BluetoothHeadset( 3675): BTStateChangeCB is registed
,D/PackageManager(  883): [MSG] MCS_UNBIND
,I/SettingSearch/SearchIntentReceiver( 1315): BOOT_COMPLETED call InitSerachDBThread thread start!
,W/System.err( 3894): android.provider.Settings$SettingNotFoundException: car_mode_on
,E/BluetoothHeadset( 3675): BluetoothHeadset service is binded
,W/System.err( 3894): 	at android.provider.Settings$System.getIntForUser(Settings.java:1586)
D/ResourcesManager( 3908): creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
W/System.err( 3894): 	at android.provider.Settings$System.getInt(Settings.java:1576)
W/System.err( 3894): 	at com.sec.android.automotive.drivelinkremote.BootCompleteReceiver.onReceive(BootCompleteReceiver.java:26)
W/System.err( 3894): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2945)
W/System.err( 3894): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 3894): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1499)
W/System.err( 3894): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3894): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3894): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
W/System.err( 3894): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3894): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3894): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 3894): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/DIAGMON_AGENT( 3874): [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3925): MountEmulatedStorage()
I/libpersona( 3925): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3925): v2
I/libpersona( 3925): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3925 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3925): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3925): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 3925): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Intent to TravelDirActivity( 3908): inside TravelBroadcastReceiver
,I/DIAGMON_AGENT( 3874): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,E/Zygote  ( 3938): MountEmulatedStorage()
E/Zygote  ( 3938): v2
I/libpersona( 3938): KNOX_SDCARD checking this for 10168
I/libpersona( 3938): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3938 uid=10168 gids={50168, 9997} abi=armeabi-v7a
,I/SELinux ( 3938): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/TimaKeyStoreProvider( 3925): TimaSignature is unavailable
I/SELinux ( 3938): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3938): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/ActivityThread( 3925): Added TimaKeyStore provider
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Zygote  ( 3950): MountEmulatedStorage()
E/Zygote  ( 3950): v2
I/libpersona( 3950): KNOX_SDCARD checking this for 10101
I/libpersona( 3950): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=3950 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 3950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/BadgeProvider( 1604): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1604): sendNotify, [notify] : null
D/BadgeProvider( 1604): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1604): update, [BadgeCount] : badgecount=0
D/Launcher.Model( 1476): reloadBadges entered.
D/BadgeProvider( 1604): update, [UpdateCount] : 1
E/SELinux ( 3950): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3938): TimaSignature is unavailable
,D/ActivityThread( 3938): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 2964): setBadgeCount(), count=0
,I/ActivityManager(  883): Killing 2730:flipboard.app/u0a111 (adj 15): bgCount ##41
,D/ResourcesManager( 3925): creating new AssetManager and set to /system/priv-app/SyncmlDM/SyncmlDM.apk
,D/Mms/MessagingNotification( 2964): remove alarm
,D/ResourcesManager( 3938): creating new AssetManager and set to /system/app/SettingSearchProvider/SettingSearchProvider.apk
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3971): MountEmulatedStorage()
E/Zygote  ( 3971): v2
I/libpersona( 3971): KNOX_SDCARD checking this for 1000
I/libpersona( 3971): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.usbsettings for broadcast com.sec.usbsettings/.UltraKeyStringBroadcastReceiver: pid=3971 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/art     (  327): Explicit concurrent mark sweep GC freed 8765(373KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 286us total 11.221ms
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 245us total 7.882ms
,I/SELinux ( 3971): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 3971): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 3971): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 253us total 7.828ms
,D/TimaKeyStoreProvider( 3950): TimaSignature is unavailable
,D/ActivityThread( 3950): Added TimaKeyStore provider
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/MessagingNotification( 2964): updateAllHistoryAsRead()
,I/ActivityManager(  883): Killing 2715:com.android.providers.calendar/u0a46 (adj 15): bgCount ##41
,D/TimaKeyStoreProvider( 3971): TimaSignature is unavailable
,D/ActivityThread( 3971): Added TimaKeyStore provider
,I/ActivityManager(  883): Killing 2807:com.google.android.apps.magazines/u0a128 (adj 15): bgCount ##41
,D/TP/SmsProvider( 1462): query,matched:0, calling pid = 2964
,D/TP/SmsProvider( 1462): match 0:Elapsed time : 1.628 ms
,D/bt_vendor( 3345): op for 7
,W/libprocessgroup(  883): failed to open /acct/uid_10111/pid_2730/cgroup.procs: No such file or directory
,D/ResourcesManager( 3971): creating new AssetManager and set to /system/app/USBSettings/USBSettings.apk
,D/ResourcesManager( 3950): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/SQLiteSecureOpenHelper( 3675): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3675): getDatabaseLocked(b,b,pwd)...
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DIAGMON_AGENT( 3874): [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Mms/SmsReceiverService( 2964): [end]    handleBootCompleted() consume time = 804.042032
,I/SQLiteSecureOpenHelper( 3675): getReadableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3675): getDatabaseLocked(b,b,pwd)...
,I/ActivityManager(  883): Killing 2866:com.samsung.android.app.FileShareServer/u0a75 (adj 15): bgCount ##41
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/app/Books/Books.apk
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_play_books.png
,I/FOTA    ( 3925): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
,D/SecContentProvider2(  883): mCursor = null
D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/BluetoothA2dp( 3675): Proxy object connected
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,I/DIAGMON_AGENT( 3874): [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 3874): [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
,I/DIAGMON_AGENT( 3874): [lIIllllllllIlIlIllll(45/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3874): [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,E/Zygote  ( 3986): MountEmulatedStorage()
E/Zygote  ( 3986): v2
I/libpersona( 3986): KNOX_SDCARD checking this for 10179
I/libpersona( 3986): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=3986 uid=10179 gids={50179, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 2924:com.sec.android.cloudagent/u0a2 (adj 15): bgCount ##41
,I/SELinux ( 3986): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 3986): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 3986): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/BooksAccountManager( 3425): Authentication error
E/BooksAccountManager( 3425): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 3425): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 3425): null auth token
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
D/PanelView( 1170): There is/are notification(s) 
,I/qtaguid ( 3425): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 3425, getuid(): 10082
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  883): failed to open /acct/uid_10046/pid_2715/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3925): [IIlllIlIIlIllIlllIll(363/IllIlIIIIlIIlIIIllIl)] Voice : true
,I/DBG_DM  ( 3925): [IIlllIlIIlIllIlllIll(364/IllIlIIIIlIIlIIIllIl)] SMS : true
,I/DBG_DM  ( 3925): [IIlllIlIIlIllIlllIll(365/IllIlIIIIlIIlIIIllIl)] isDataOnly : false
,I/qtaguid ( 3425): Tagging socket 38 with tag 10000000000{256,0} uid -1, pid: 3425, getuid(): 10082
,D/TimaKeyStoreProvider( 3986): TimaSignature is unavailable
,D/ActivityThread( 3986): Added TimaKeyStore provider
,D/ResourcesManager( 3986): creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,W/ResourcesManager( 3986): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4005): MountEmulatedStorage()
I/libpersona( 4005): KNOX_SDCARD checking this for 10011
E/Zygote  ( 4005): v2
I/libpersona( 4005): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4005 uid=10011 gids={50011, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMApplication(44/onCreate)] myUserId : 0
,I/SELinux ( 4005): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 4005): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 4005): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/libprocessgroup(  883): failed to open /acct/uid_10002/pid_2924/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10128/pid_2807/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10075/pid_2866/cgroup.procs: No such file or directory
,I/ActivityManager(  883): Killing 2949:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##41
D/TimaKeyStoreProvider( 4005): TimaSignature is unavailable
,D/ActivityThread( 4005): Added TimaKeyStore provider
,I/DBG_DM  ( 3925): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2673/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
,D/ResourcesManager( 4005): creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMApplication(82/onCreate)] XDMApplication Start ! - Fumo State
,W/ContextImpl( 3925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:83 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5007 
,I/qtaguid ( 3425): Untagging socket 34
,W/ApiaryClient( 3425): Error response from books API: {
W/ApiaryClient( 3425):  "error": {
W/ApiaryClient( 3425):   "errors": [
W/ApiaryClient( 3425):    {
W/ApiaryClient( 3425):     "domain": "global",
W/ApiaryClient( 3425):     "reason": "required",
W/ApiaryClient( 3425):     "message": "Login Required",
W/ApiaryClient( 3425):     "locationType": "header",
W/ApiaryClient( 3425):     "location": "Authorization"
W/ApiaryClient( 3425):    }
W/ApiaryClient( 3425):   ],
W/ApiaryClient( 3425):   "code": 401,
W/ApiaryClient( 3425):   "message": "Login Required"
W/ApiaryClient( 3425):  }
W/ApiaryClient( 3425): }
,W/ApiaryClient( 3425): errCount = 2: com.google.android.apps.books.net.HttpHelper$TokenExpiredException: com.google.api.client.http.HttpResponseException: 401: Unauthorized
W/ApiaryClient( 3425): URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2458281435795576837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 3425): Headers suppressed
D/ConnectivityService(  883): returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] android.intent.action.BOOT_COMPLETED
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1682/llllIllIIIIIlIIllIII)] 
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1687/llllIllIIIIIlIIllIII)] m_WakeLock is acquire!!
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1547/lllIlIlIIIllIIlIllIl)] 0
,I/DBG_DM  ( 3925): [IIIlllIlIIlllIIIIllI(222/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1590/llIlIIIIlIIIIIlIlIII)] 0
,I/DBG_DM  ( 3925): [IIIlllIlIIlllIIIIllI(251/IIllIlIIIIlIIIllIllI)] Roaming Check : true
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1675/llIIllllIIlllIIIIlll)] 0
,D/OverheatReceiver( 1170): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1170): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1170): VZW on -> change to Global UX [safe mode]
,D/OverheatReceiver( 1170): isSafeMode = false
I/DBG_DM  ( 3925): [IIIlllIlIIlllIIIIllI(283/llIIlIlIlIlIIIIIIlIl)] validation Check On
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1632/IllIlIIIIlIIlIIIllIl)] 0
,I/DBG_DM  ( 3925): [IIIlllIlIIlllIIIIllI(264/lllllllIlllIIlllIlIl)] SSL Check On
,D/UMC:Core( 3986): onCreate(): 
,I/DBG_DM  ( 3925): [llIlIIIIlllIlllllIll(187/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
,I/DBG_DM  ( 3925): [lIIllllllIlllllIlIIl(153/llIIIIlllllIIllIIllI)] nSync = 0
,W/ContextImpl( 3925): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2067 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.llIlIllIIIlIIlllIlII.llIIIIlllllIIllIIllI:72 com.wssyncmldm.ui.llIlIllIIIlIIlllIlII.llIIIIlllllIIllIIllI:112 llIlIIIIlllIlllllIll.llIIIIlllllIIllIIllI:191 
,I/DBG_DM  ( 3925): [IIlllIlIIlIllIlllIll(109/lllIlIlIIIllIIlIllIl)] 
,D/PhoneMultiSimUtils( 1462): getInsertedSimCard: returnValue =0
,D/SettingsProvider(  883): name = internet_call_settings_visibility
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 1001
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,W/libprocessgroup(  883): failed to open /acct/uid_10042/pid_2949/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3925): [IIlllIlIIlIllIlllIll(459/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
,I/DBG_DM  ( 3925): [IIlllIlIIlIllIlllIll(166/lllIlIlIIIllIIlIllIl)] bExternalStorageAvailable [true]
,I/DBG_DM  ( 3925): [IIlllIlIIlIllIlllIll(167/lllIlIlIIIllIIlIllIl)] bExternalSDStorageAvailable [false]
,I/Velvet.VelvetFactory( 1559): refreshing internal icing corpora
I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1708/IIllIlIIIIlIIIllIllI)] 
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/Velvet.VelvetFactory( 1559): checking for language pack updates
,I/DBG_DM  ( 3925): [com.wssyncmldm.db.file.XDB(1962/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1713/IIllIlIIIIlIIIllIllI)] m_WakeLock is release!!
,D/USER_AGENT( 3986): UMC/1.1.39 (SM-G900F) SAFE-5.3 KNOX-2.3
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(186/onStartCommand)] 
,E/Zygote  ( 4025): MountEmulatedStorage()
E/Zygote  ( 4025): v2
I/libpersona( 4025): KNOX_SDCARD checking this for 1000
I/libpersona( 4025): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=4025 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Tethering(  883): No numeric data
I/ActivityManager(  883): Killing 3023:com.wsomacp/u0a25 (adj 15): bgCount ##41
,I/ActivityManager(  883): Killing 2533:com.google.android.gms.wearable/u0a12 (adj 15): bgCount ##42
,D/bt_upio ( 3345): ..proc_btwrite_timeout..
,I/SELinux ( 4025): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 4025): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 4025): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Tethering(  883): No numeric data
,E/Tethering(  883): No numeric data
,E/Tethering(  883): No numeric data
,I/com.dropbox.android.service.DropboxNetworkReceiver( 3950): Setting receiver enabled: false
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,E/Tethering(  883): No numeric data
,D/TimaKeyStoreProvider( 4025): TimaSignature is unavailable
,D/ActivityThread( 4025): Added TimaKeyStore provider
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/Tethering(  883): No numeric data
,I/DBG_DM  ( 3925): [lllllllIlllIIlllIlIl(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : true
,I/DBG_DM  ( 3925): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(49/onServiceConnected)] 
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
I/Velvet.VelvetFactory( 1559): refreshing search history.
,I/Search.GservicesUpdateTask( 1559): Updating Gservices keys
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,E/Zygote  ( 4045): MountEmulatedStorage()
I/libpersona( 4045): KNOX_SDCARD checking this for 10003
E/Zygote  ( 4045): v2
I/libpersona( 4045): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=4045 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,D/[SAMSUNG SMARCART NATIVE]( 3986): initialize...
D/[SAMSUNG SMARCART NATIVE]( 3986): DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,I/CSTORAGE( 3986): ================================================
I/CSTORAGE( 3986):  CSTORAGE_SKM_LIB v1.0.8
I/CSTORAGE( 3986): ================================================
I/TZ_CCM_C_GetFunctionList: ( 3986): TZ_CCM_C_GetFunctionList was called
D/[SAMSUNG SMARCART NATIVE]( 3986): FINISHED: initialize rv:0
,I/SELinux ( 4045): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 4045): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 4045): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 4025): creating new AssetManager and set to /system/priv-app/FmmDM/FmmDM.apk
,W/libprocessgroup(  883): failed to open /acct/uid_10025/pid_3023/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10012/pid_2533/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3925): [llIlIIIIlllIlllllIll(197/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
,D/TimaKeyStoreProvider( 4045): TimaSignature is unavailable
,D/ActivityThread( 4045): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/com.dropbox.sync.android.a( 3950): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/DBG_DM  ( 3925): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/ResourcesManager( 4045): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1504/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
,I/DBG_DM  ( 3925): [llIlIIIIlllIlllllIll(224/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/UserAnalysis.PlaceProvider( 4045): PlaceProvider onCreate()
,D/CustomFrequencyManagerService(  883): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 883  pkgName : ACTIVITY_RESUME_BOOSTER@6
,W/ActivityManager(  883): mDVFSHelper.acquire()
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/libDropboxSync.so(log)( 3950): opendir /dH failed: No such file or directory
,D/ActivityManager(  883): post active user change for 0
,D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
,I/com.dropbox.sync.android.aa( 3950): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/231222 DropboxSync/2.0.2 (Android; 5.0; samsung SM-G900F armeabi-v7a; en_US))
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/Timeline( 3270): Timeline: Activity_idle id: android.os.BinderProxy@3279b51c time:32686
,I/ActivityManager(  883): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=4067 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/Zygote  ( 4067): MountEmulatedStorage()
I/libpersona( 4067): KNOX_SDCARD checking this for 1000
E/Zygote  ( 4067): v2
I/libpersona( 4067): KNOX_SDCARD not a persona
,D/UserAnalysis.SecureDbManager( 4045): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 4045): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 4045): Create SecureDbHelper
,I/SELinux ( 4067): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 4067): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 4067): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager(  883): Killing 3045:com.sec.android.widgetapp.digitalclock/u0a94 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/UMC:SecurityUtils( 3986): Loaded server certificates: 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/UMC:SecurityUtils( 3986): Loaded server certificates: 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/IntelligenceServiceApplication( 4045): onCreate()
,D/UMC:SecurityUtils( 3986): timaVersion on the device: 3.0
,D/UMC:CloudMDMSecurity( 3986): New Flow
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/TimaService(  883): TIMA3: in ccmRegisterForDefaultCertificate
D/TimaService(  883): TIMA: in getTimaVersion
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 4045): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,D/UserAnalysis.SecurePlaceDbHelper( 4045): SecurePlaceDbHelper() 
D/UserAnalysis.UserAnalysisBroadcastReceiver( 4045): Create SecureDbHelper
D/UserAnalysis.MyPlaceDbPreference( 4045): Constructor Preference
,I/        (  883): CCM JNI: In ccm_register_for_default_cert
I/        (  883): CCM JNI: In ccm_create_slot
I/TZ_CCM_C_Initialize: (  883): DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
,I/TZ_CCM_C_Initialize: (  883): pInitArgs 0x94101814 has not called C_Init before.
E/Tethering(  883): No numeric data
I/TZ_CCM_C_Initialize: (  883): &ctx = 0x9fb3ac1c
D/TimaKeyStoreProvider( 4067): TimaSignature is unavailable
I/TLC_TZ_CCM: (  883): creating new ccm context...
I/TLC_TZ_CCM: (  883): initializing ccm context...
I/TLC_TZ_CCM: (  883): root = /firmware/image, root_strlen = 15
I/TLC_TZ_CCM: (  883): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  883): input max_sendmsg_size = 19420
I/TZ: client_server_communication(  883): input max_recvmsg_size = 19420
I/TZ: client_server_communication(  883): root = /firmware/image, root_len = 15
I/TZ: client_server_communication(  883): process = tz_ccm, process_strlen = 6
I/TZ: client_server_communication(  883): aligned max_sendmsg_size = 19456
I/TZ: client_server_communication(  883): aligned max_recvmsg_size = 19456
I/TZ: client_server_communication(  883): Client_Server_Open was called
,D/ActivityThread( 4067): Added TimaKeyStore provider
,D/BluetoothAdapter( 3270): disable()
,E/Zygote  ( 4088): MountEmulatedStorage()
E/Zygote  ( 4088): v2
I/libpersona( 4088): KNOX_SDCARD checking this for 10104
I/libpersona( 4088): KNOX_SDCARD not a persona
,I/TZ: client_server_communication(  883): IClientServer::IClientServer()
I/TZ: client_server_communication(  883): BpClientServer::BpClientServer()
,I/ActivityManager(  883): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=4088 uid=10104 gids={50104, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 3060:com.sec.android.widgetapp.dualclockdigital/u0a103 (adj 15): bgCount ##41
,D/SettingsProvider(  883): name = bluetooth_on
,I/SELinux ( 4088): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/TZ_CCM_SERVER( 1088): BnCCM::onTransact(0) 16
I/TZ_CCM_SERVER( 1088): OPENSWCONN
I/TZ_CCM_SERVER( 1088): creating new ccm context...
I/TZ_CCM_SERVER( 1088): initializing ccm context...
I/TZ_CCM_SERVER( 1088): root = /firmware/image, root_strlen = 15
I/TZ_CCM_SERVER( 1088): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1088): root = /firmware/image, root_len = 15
I/TZ: qc_tlc_communication( 1088): process = tz_ccm, process_strlen = 6
I/TZ: qc_tlc_communication( 1088): aligned max_sendmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1088): aligned max_recvmsg_size = 19456 = 0x4c00
I/TZ: qc_tlc_communication( 1088): max_message_size = 38912 = 0x9800
D/QSEECOMAPI: ( 1088): QSEECom_get_handle sb_length = 0x9800
I/SELinux ( 4088): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/QSEECOMAPI: ( 1088): App is not loaded in QSEE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/SELinux ( 4088): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/Tethering(  883): No numeric data
,I/WebViewFactory( 1559): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/BluetoothAdapterState( 3345): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/BluetoothAdapterProperties( 3345): Setting state to 13
I/BluetoothAdapterState( 3345): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 3345): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3345): updateAdapterState state is 13
,D/ResourcesManager( 1559): creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,I/WifiManager( 3270): packageName : com.example.hello
,E/Tethering(  883): No numeric data
,E/Zygote  ( 4102): MountEmulatedStorage()
E/Zygote  ( 4102): v2
I/libpersona( 4102): KNOX_SDCARD checking this for 10065
I/libpersona( 4102): KNOX_SDCARD not a persona
,D/SecContentProvider(  883): uri = 18 selection = isWifiEnabled
D/SecContentProvider2(  883): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2(  883): mCursor = null
,D/WifiService(  883): New client listening to asynchronous messages
,I/ActivityManager(  883): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=4102 uid=10065 gids={50065, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/WifiService(  883): setWifiEnabled: false pid=3270, uid=10201
E/WifiService(  883): Invoking mWifiStateMachine.setWifiEnabled
,D/SettingsProvider(  883): name = wifi_on
,D/QSEECOMAPI: ( 1088): Loaded image: APP id = 3
,I/jxcore-log( 3270): ****TEST TOOK:  5110  ms ****
I/jxcore-log( 3270): 
I/jxcore-log( 3270): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3270): 
,I/TZ: qc_tlc_communication( 1088): TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
I/TZ: client_server_communication(  883): OpenSWConn(CCM) is successful
I/TZ: client_server_communication(  883): Client_Server_Open succeeded, serverName = CCM
I/TZ_CCM_C_Initialize: (  883): ctx = 0x917d8730, comm = 0x9d63c280, sendmsg = 0x6dc23000, recvmsg = 0x6dc27c00
I/TZ_init: (  883): TZ_init: sending initialization request...
I/TZ: client_server_communication(  883): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  883): Calling Communicate()
E/WifiStateMachine(  883): WifiStateMachine: Leaving Connected state
I/wpa_supplicant( 1296): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1296): wlan0: Setting scan request: 0 sec 0 usec
I/ActivityManager(  883): Killing 1922:com.sec.android.GeoLookout/u0a113 (adj 15): bgCount ##41
I/wpa_supplicant( 1296): P2P: Current p2p state = IDLE
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - exit - invokeExitMethods
E/WifiStateMachine(  883): handleNetworkDisconnect f4:f2:6d:22:99:3e config "NG700"WPA_PSK config.bssid any
E/WifiStateMachine(  883): handleNetworkDisconnect "NG700" nid=0
E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/SELinux ( 4102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/SELinux ( 4102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1170): value : false
I/TZ_CCM_SERVER( 1088): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1088): COMM
E/SELinux ( 4102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4088): TimaSignature is unavailable
,I/wpa_supplicant( 1296): Scan requested (ret=0) - scan timeout 30 seconds
D/ActivityThread( 4088): Added TimaKeyStore provider
,E/TZ_init: (  883): TZ_init Process: Secure memory is not initialized!
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/TZ_init: (  883): trustlet initialization failed
I/TZ_init: (  883): TZ_init_START...
E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
E/Tethering(  883): No numeric data
I/TZ_init: (  883): TZ_init_with_data: sending initialization request...
I/TZ: client_server_communication(  883): Cmd id = 2, len = 19456
I/TZ: client_server_communication(  883): Calling Communicate()
D/WifiP2pService(  883): InactiveState{ what=143375 }
D/WifiP2pService(  883): P2pEnabledState{ what=143375 }
I/TZ_CCM_SERVER( 1088): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1088): COMM
I/TZ_init: (  883): TZ_init: successful initialization
I/TLC_TZ_COMMON: key_db_init: (  883): Exercising TZ_DB_INIT in TLC
I/BluetoothPbapService( 3345): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothSocket( 3345): close() in, this: android.bluetooth.BluetoothSocket@46e34bd, channel: 19, state: LISTENING
D/BluetoothSocket( 3345): close() this: android.bluetooth.BluetoothSocket@46e34bd, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e0a4e67, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e2c3ab2mSocket: android.net.LocalSocket@a636a03 impl:android.net.LocalSocketImpl@37f33d80 fd:FileDescriptor[72]
D/BluetoothSocket( 3345): Closing mSocket: android.net.LocalSocket@a636a03 impl:android.net.LocalSocketImpl@37f33d80 fd:FileDescriptor[72]
I/TZ: client_server_communication(  883): Cmd id = 17, len = 19456
I/TZ: client_server_communication(  883): Calling Communicate()
,I/TZ_CCM_SERVER( 1088): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1088): COMM
,D/BluetoothAdapterService( 3345): Autoconnection is available 
D/BluetoothAdapterService( 3345): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 3345): terminating service from this receiver
,D/ResourcesManager( 4067): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,W/ActivityManager(  883): Duplicate finish request for ActivityRecord{e929363 u0 com.sec.android.app.popupuireceiver/.BatteryCover t27 f}
,I/TZ_COMMON: tlc_key_db_util: (  883): DB Operation suceeded
I/TLC_TZ_CCM: register for default cert: (  883): Exercising TZ_CCM_register_default_TLC
I/TZ: client_server_communication(  883): Cmd id = 25, len = 19456
I/TZ: client_server_communication(  883): Calling Communicate()
,I/TZ_CCM_SERVER( 1088): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1088): COMM
,I/TLC_TZ_CCM: register for default cert: (  883): TZ_CCM_register_default_TLC_END: DB file size to update is 0
I/TLC_TZ_CCM: register for default cert: (  883): TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
I/TZ_CCM_C_Finalize: (  883): DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
I/TZ: client_server_communication(  883): Cmd id = 41, len = 19456
I/TZ: client_server_communication(  883): Calling Communicate()
,I/TZ_CCM_SERVER( 1088): BnCCM::onTransact(2) 16
I/TZ_CCM_SERVER( 1088): COMM
D/TimaKeyStoreProvider( 4102): TimaSignature is unavailable
,D/ActivityThread( 4102): Added TimaKeyStore provider
,I/TZ: client_server_communication(  883): Client_Server_Close was called
I/TZ_CCM_SERVER( 1088): BnCCM::onTransact(1) 16
I/TZ_CCM_SERVER( 1088): CLOSESWCONN
D/QSEECOMAPI: ( 1088): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1088): QSEECom_shutdown_app, app_id = 3
,I/TZ: client_server_communication(  883): Client_Server_Close succeeded
D/UMC:CloudMDMSecurity( 3986): ccmRegisterForDefaultCertificate: 0
D/UMC:CloudMDMSecurity( 3986): TIMA service call for password change success!!
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/UMC:AdminManager( 3986): init - start
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/[SBeam] ( 1315): SBeamEnabler.isSBeamSupported : [-1]
,D/[SBeam] ( 1315): SBeamEnabler.isSBeamSupported : EXIST
,D/BluetoothAdapterProperties( 3345): onBluetoothDisable()
,D/SecContentProvider(  883): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 3345): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): proc btwrite assertion
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/ResourcesManager( 4088): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/WifiStateMachine(  883): setDetailed state, old =CONNECTED and new state=DISCONNECTED hidden=false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/ConnectivityService(  883): updateNetworkInfo()
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService(  883): updateNetworkInfo()
D/ConnectivityService(  883): ignoring duplicate network state non-change
D/ConnectivityService(  883): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 2
I/SurfaceFlinger(  249): id=14 Removed com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover (8/9)
I/SurfaceFlinger(  249): id=14 Removed com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover (-2/9)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/UMC:AdminManager( 3986): loadAdmins
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/InputMethodManagerService(  883): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
I/InputMethodManagerService(  883): [BT Setting State] State =13
,W/libprocessgroup(  883): failed to open /acct/uid_10094/pid_3045/cgroup.procs: No such file or directory
,W/libprocessgroup(  883): failed to open /acct/uid_10103/pid_3060/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
W/libprocessgroup(  883): failed to open /acct/uid_10113/pid_1922/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1170): value : false
,I/LibraryLoader( 1559): Loading: webviewchromium
,D/StatusBar.NetworkController( 1170): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020495/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02012b/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,I/LibraryLoader( 1559): Time to load native libraries: 7 ms (timestamps 2968-2975)
,I/LibraryLoader( 1559): Expected native library version number "",actual native library version number ""
,I/System.out( 3950): Thread-505(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/BluetoothTile( 1170): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/STATUSBAR-QSTileView( 1170): onStateChanged: Bluetooth
,I/SamsungIME( 1869): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,D/ResourcesManager( 4102): creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,E/WifiConfigStore(  883): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,D/BluetoothAdapterProperties( 3345): Scan Mode:20
,D/BluetoothAdapterState( 3345): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 3345): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,E/bt-btif ( 3345): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,E/bt-btif ( 3345): cmd socket is not created
,D/ConnectivityService(  883): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService(  883): calling update connectivity
,D/EntConnectivity(  883): Not allowed due to - mEnabled false
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/ConnectivityService(  883):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
E/bt-btm  ( 3345): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 3345): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,D/btif_config_util( 3345): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
W/bt-l2cap( 3345): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x001b not found for deregistration
,I/System.out( 3950): Thread-505(ApacheHTTPLog):isShipBuild true
,D/bt_vendor( 3345): op for 7
D/ConnectivityService(  883): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/bt_upio ( 3345): BT_WAKE is asserted already
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ConnectivityManager.CallbackHandler( 1170): CM callback handler got msg 524292
,D/Nat464Xlat(  883): requiresClat: netType=1, connected=false, hasIPv4Address=true
D/ConnectivityService(  883): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  883): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,I/WifiTrafficPoller(  883): evaluateTrafficStatsPolling
,D/TelephonyNetworkFactory( 1462): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): ValidatedState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): DefaultState{ when=-7ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,D/bt_vendor( 3345): op for 7
D/CSLegacyTypeTracker(  883): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.105/24,fe80::ee1f:72ff:fe18:8b78/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/bt_upio ( 3345): BT_WAKE is asserted already
D/CSLegacyTypeTracker(  883): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitorNetworkAgentInfo [WIFI () - null](  883): Disconnected - quitting
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
,D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
I/System.out( 3950): Thread-505(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
I/PCWCLIENTTRACE_LOG( 4067): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 4067): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4067): new DMDBOpenHelper instance
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
V/VibratorService(  883): hasVibrator - useVibetonz: true
D/ConnectivityService(  883): sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/SmartBondingService(  883): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
V/NetworkStats(  883): updateIfacesLocked()
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
V/NetworkStats(  883): performPollLocked(flags=0x1)
D/NetworkStatsFactory(  883): UpdateStatsForKnox
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,E/ActivityThread( 3345): Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@2ce2f48b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3345): android.app.IntentReceiverLeaked: Service com.samsung.ble.BleAutoConnectService has leaked IntentReceiver com.samsung.ble.BleAutoConnectService$4@2ce2f48b that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread( 3345): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:960)
E/ActivityThread( 3345): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:761)
E/ActivityThread( 3345): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1945)
E/ActivityThread( 3345): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1925)
E/ActivityThread( 3345): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1919)
E/ActivityThread( 3345): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
E/ActivityThread( 3345): 	at com.samsung.ble.BleAutoConnectService.onCreate(BleAutoConnectService.java:139)
E/ActivityThread( 3345): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3100)
E/ActivityThread( 3345): 	at android.app.ActivityThread.access$1900(ActivityThread.java:172)
E/ActivityThread( 3345): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1505)
E/ActivityThread( 3345): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3345): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3345): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/ActivityThread( 3345): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 3345): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 3345): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread( 3345): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,V/NetworkStats(  883): performPollLocked() took 11ms
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/BluetoothSocket( 3345): close() in, this: android.bluetooth.BluetoothSocket@49f4ffe, channel: 5, state: LISTENING
D/BluetoothSocket( 3345): close() this: android.bluetooth.BluetoothSocket@49f4ffe, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@38f0f414, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1ea8a35fmSocket: android.net.LocalSocket@2a0eb1ac impl:android.net.LocalSocketImpl@396c3e75 fd:FileDescriptor[74]
D/BluetoothSocket( 3345): Closing mSocket: android.net.LocalSocket@2a0eb1ac impl:android.net.LocalSocketImpl@396c3e75 fd:FileDescriptor[74]
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/SmartBondingService(  883): getNetworkEnabled : wifi : true mobile : true
,D/X       (  883): broadcastSiopLevelIntent:: currentSiopLevel = 0
,W/art     ( 1559): Attempt to remove local handle scope entry from IRT, ignoring
,D/StatusBar.NetworkController( 1170): getUpdateDataNetType(): 0
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/StatusBar.NetworkController( 1170): updateDataNetType()
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1170): NoService, mRoamingIconId = 0
V/NetworkStats(  883): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/ContentApp( 1223):  LEVEL : 0
,D/PCWCLIENTTRACE_DMContentProvider( 4067): [URIMatcher] - result : 2
,D/StatusBar.NetworkController( 1170): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength: hasService=false ss=null
,D/StatusBar.NetworkController( 1170): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,E/WifiStateMachine(  883): scanCount==0 - aborting
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/WifiStateMachine(  883): [1,456,842,786,493 ms] noteScanEnd no scan source
,D/WifiScanningService(  883): SCAN_AVAILABLE : 1
,D/WifiScanningService(  883): DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  883): InactiveState{ what=131204 }
D/WifiP2pService(  883): P2pEnabledState{ what=131204 }
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
D/WifiP2pService(  883): sending p2p connection changed broadcast: FAILED
,E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
D/WifiNetworkAgent(  883): NetworkAgent: NetworkAgent channel lost
,D/RttService(  883): SCAN_AVAILABLE : 1
,D/RttService(  883): EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,E/ConnectivityService(  883): updateNetworkInfo()
D/ConnectivityService(  883): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,D/WifiDisplayController(  883): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter(  883): onP2pDisconnected
,D/WifiP2pService(  883): sending p2p connection changed broadcast: DISCONNECTED
,E/WifiStateMachine(  883): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,D/IpRemoteDisplayController(  883): disconnectWfdBridgeServer
D/IpRemoteDisplayController(  883): WfdBridgeServer is already null
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WifiP2pService(  883): P2pDisablingState
,E/ConnectivityService(  883): updateNetworkInfo()
D/ConnectivityService(  883): ignoring duplicate network state non-change
,D/WifiP2pService(  883): P2pDisablingState{ what=147458 }
,D/WifiP2pService(  883): p2p socket connection lost
D/WifiP2pService(  883): P2pDisabledState
,D/WifiDisplayController(  883): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,D/WifiDisplayController(  883): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
E/WifiStateMachine(  883): handleNetworkDisconnect: Stopping DHCP and clearing IP stack:handleNetworkDisconnect - access$11200 - enter - invokeEnterMethods
D/WifiDisplayController(  883): disconnect
D/WifiDisplayController(  883): updateConnection
,D/WifiDisplayController(  883): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  883): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
D/WifiDisplayAdapter(  883): onP2pDisconnected
D/IpRemoteDisplayController(  883): disconnectWfdBridgeServer
,D/IpRemoteDisplayController(  883): WfdBridgeServer is already null
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/WifiStateMachine(  883): setSuspendOptimizationsNative: 1 true -want true stack:setSuspendOptimizationsNative - handlePostDhcpSetup - stopDhcp - handleNetworkDisconnect
,D/WifiDisplayAdapter(  883): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService(  883): P2pDisabledState{ what=143375 }
D/WifiP2pService(  883): DefaultState{ what=143375 }
,I/System.out( 3950): pool-4-thread-1 calls detatch()
,D/elm:14451( 4088): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/CommandListener(  280): Clearing all IP addresses on wlan0
,E/WifiStateMachine(  883): setDetailed state, old =DISCONNECTED and new state=DISCONNECTED hidden=false
,D/elm:14451( 4088): ELMEngine.ELMEngine( context ).
,D/elm:14451( 4088): MDMBridge.setEnterpriseBridge()
,I/ActivityManager(  883): Killing 3076:com.sec.android.app.camera/u0a154 (adj 15): bgCount ##41
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/AllShareCastTile( 1170): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,E/WifiStateMachine(  883): stopping supplicant
I/wpa_supplicant( 1296): p2p0: State: DISCONNECTED -> DISCONNECTED
,E/WifiStateMachine(  883): setWifiState: disabling
,D/WifiDisplayAdapter(  883): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/AllShareCastTile( 1170): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/SecContentProvider2(  883): uri = 20 selection = getPromptCredentialsEnabled
,D/SecContentProvider2(  883): mCursor = null
,D/elm:14451( 4088): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/WifiTrafficPoller(  883): evaluateTrafficStatsPolling
,D/elm:14451( 4088): ElmAgentService : onCreate()
,D/elm:14451( 4088): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,I/CLocInfoService(  883): External Intent Received android.net.wifi.STATE_CHANGE
,D/elm:14451( 4088): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:14451( 4088): BootCompletedState : startBootCompleted() call
,D/elm:14451( 4088): MDMBridge.getAllLicenseInfoFromSDK()
,I/FOTA_Client( 4005): [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService(  883): getNetworkEnabled : wifi : false mobile : true
,D/SLocation(  883): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
,I/elm:14451( 4088): Get License : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/WifiCredService( 1315): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020498/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020133/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
,D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/StatusBar.NetworkController( 1170): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1170): applyOpen
D/elm:14451( 4088): ElmAgentService : onDestroy().
,D/STATUSBAR-WifiQuickSettingButton( 1170): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-WifiQuickSettingButton( 1170): Wifi onReceive(0)
D/STATUSBAR-QSTileView( 1170): onStateChanged: Wi-Fi
,D/AndroidRuntime( 4123): 
D/AndroidRuntime( 4123): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,W/bt-l2cap( 3345): btif_mce_execute_service enable:0
D/bt_vendor( 3345): op for 6
D/AndroidRuntime( 4123): CheckJNI is OFF
W/bt-l2cap( 3345): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 3345): L2CAP - PSM: 0x001b not found for deregistration
D/bt_userial( 3345): RX termination
W/bt_userial( 3345): select_read return size <=0:-1, exiting userial_read_thread
D/bt_userial( 3345): Leaving userial_read_thread()
D/bt_userial( 3345): userial_close_reader Joined userial reader thread: 0
D/AndroidRuntime( 4123): setted country_code = Germany
D/bt_vendor( 3345): op for 9
D/bt_hwcfg( 3345): hw_epilog_process
D/bt_vendor( 3345): op for 7
D/bt_upio ( 3345): BT_WAKE is asserted already
D/AndroidRuntime( 4123): setted countryiso_code = DE
,W/bt-btif ( 3345): ag scb idx 1 not allocated
D/bt_vendor( 3345): op for 4
W/bt-btif ( 3345): ag scb idx 2 not allocated
E/bt-btif ( 3345): BTA AG is already disabled, ignoring ...
I/bt_userial_vendor( 3345): device fd = 65 close
D/AndroidRuntime( 4123): setted sales_code = DBT
,D/AndroidRuntime( 4123): readGMSProperty: start
D/AndroidRuntime( 4123): readGMSProperty: already setted!!
D/AndroidRuntime( 4123): readGMSProperty: end
D/AndroidRuntime( 4123): addProductProperty: start
,D/bt_vendor( 3345): op for 0
D/bt_upio ( 3345): upio_set_bluetooth_power(on: 0)
D/bt_upio ( 3345): is_emulator_context : 0
D/bt_upio ( 3345): is_rfkill_disabled ? [0]
,D/HotspotTile( 1170): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/bt_vendor( 3345): cleanup
,I/GKI_LINUX( 3345): gki_task task_id=0 [BTU] terminating
,D/HotspotTile( 1170): onReceive : 0, 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/GKI_LINUX( 3345): GKI_exit_task 0 done
,I/GKI_LINUX( 3345): GKI_shutdown(): task [BTU] terminated
D/BluetoothAdapterState( 3345): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/BtConfig.SecureMode( 3345): isSecureModeOn:false
D/PermissionCache(  883): checking com.samsung.permission.SSENSOR for uid=1000 => granted (67 us)
D/PermissionCache(  883): checking android.permission.BODY_SENSORS for uid=1000 => granted (32 us)
D/BluetoothAdapterService( 3345): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.gatt.GattService
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_dim.png
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 3345): handleDebugAction() action=null
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,I/FOTA_Client( 4005): [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,D/BtGatt.GattService( 3345): Received stop request...Stopping profile...
D/BtGatt.GattService( 3345): stop()
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BtGatt.AdvertiseManager( 3345): advertise clients cleared
D/UMC:AdminManager( 3986): startPolicyHandlers
I/UMC:TestPolicyHandler( 3986): Setup is called in testpolicyhandler
,D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.a2dp.A2dpService
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  883): Killing 3094:com.sec.android.widgetapp.activeapplicationwidget/u0a158 (adj 15): bgCount ##41
,D/UMC:AdminManager( 3986): init - end
,V/UMC:AlarmHandler( 3986): Enter loadList
,V/EmergencyMode( 1434): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidService
,W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.hid.HidService
,D/GSLBManager( 3986): migrateStoredUrlFromOldPref
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.hdp.HealthService
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.pan.PanService
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/GSLBManager( 3986): migrateStoredUrlFromOldPref : Migration Not Needed
,I/wpa_supplicant( 1296): Blacklist: Clear (all) 
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/UMC:UMCAdmin( 3986): deactivateUMCAdminIfNotRequired : -1
W/BluetoothAdapterService( 3345): Not skipping com.android.bluetooth.map.BluetoothMapService
,E/UMC:Utils( 3986): Admin not found in package com.samsung.knoxpb.mdm
D/UMC:UMCAdmin( 3986): deactivateUMCAdmin : -1
D/UMC:UMCAdmin( 3986): isContainer : 0
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,W/BluetoothAdapterService( 3345): Not skipping com.broadcom.bt.service.sap.SapService
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/LicenseLogService(  883): log() failed
W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 3345): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,W/BluetoothAdapterService( 3345): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 3345): Stopping profile services that were post enabled
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HeadsetService( 3345): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/AudioService(  883): onServiceDisconnected: Bluetooth profile: 1
D/A2dpService( 3345): Received stop request...Stopping profile...
V/Avrcp   ( 3345): doQuit
D/A2dpStateMachine( 3345): Exit Disconnected: -1
D/Avrcp   ( 3345): Unregistering previous receiver
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
D/BluetoothA2dp(  883): Proxy object disconnected
D/AudioService(  883): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 3345): Received stop request...Stopping profile...
D/HidService( 3345): Stopping Bluetooth HidService
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
D/HealthService( 3345): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/PanService( 3345): Received stop request...Stopping profile...
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
D/BluetoothA2dp( 3675): Proxy object disconnected
D/BluetoothPan(  883): BluetoothPAN Proxy object disconnected
D/BluetoothMapService( 3345): Received stop request...Stopping profile...
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/SapService( 3345): Received stop request...Stopping profile...
D/SapService( 3345): Stopping Bluetooth SapService
D/BluetoothAdapterService( 3345): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2109674a
,D/LockPatternUtilsCache( 1170): value : false
I/wpa_supplicant( 1296): p2p0: CTRL-EVENT-TERMINATING 
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3345): Profile still running: com.android.bluetooth.hid.HidService
,W/BluetoothHeadsetServiceJni( 3345): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 3345): Cleaning up Bluetooth Handsfree callback object
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 3345): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 3345): Proxy object disconnected
D/BluetoothAdapterService( 3345): Bluetooth A2dp source service disconnected
,I/GKI_LINUX( 3345): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 3345): GKI_exit_task 2 done
I/GKI_LINUX( 3345): GKI_shutdown(): task [A2DP-MEDIA] terminated
V/Avrcp   ( 3345): cleanup
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3345): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHidServiceJni( 3345): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 3345): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 3345): Cleaning up Bluetooth GID callback object
E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 3345): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 3345): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 3345): Cleaning up Bluetooth Health object
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
,D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
I/wpa_supplicant( 1296): CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
D/BluetoothAdapterService( 3345): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 3345): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 3345): Cleaning up Bluetooth PAN callback object
I/wpa_supplicant( 1296): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1296): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
I/wpa_supplicant( 1296): wlan0: State: DISCONNECTED -> DISCONNECTED
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 3345): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 3345): Profile still running: com.broadcom.bt.service.sap.SapService
,E/BluetoothAdapterService(554264394)( 3345): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 3345): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 3345): Setting state to 10
I/BluetoothAdapterState( 3345): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 3345): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 3345): updateAdapterState state is 10
D/BluetoothAdapterService( 3345): Autoconnection is available 
D/BluetoothAdapterService( 3345): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 3345): Entering OffState
,W/BluetoothSAPServiceJni( 3345): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 3345): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
D/BluetoothA2dp(  883): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3345): onBluetoothStateChange: up=false
,D/BluetoothA2dp( 3675): onBluetoothStateChange: up=false
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/BluetoothManagerService(  883): Broadcasting onBluetoothServiceDown() to 12 receivers.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/BluetoothManagerService(  883): Broadcasting onBluetoothServiceUp() to 0 receivers.
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/FileWriteThread_Telephony( 1462): FileWriteThread : threadType = 3
,V/EmergencyMode( 1434): [EmergencyBase] setBootTime
,V/EmergencyMode( 1434): [EmergencyFactory] No Recovery State, kill my self.
,W/InputMethodManagerService(  883): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService(  883): [BT Setting State] State =10
I/InputMethodManagerService(  883): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,I/GKI_LINUX( 3345): gki_task task_id=1 [BTIF] terminating
,I/GKI_LINUX( 3345): GKI_exit_task 1 done
,I/GKI_LINUX( 3345): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 3345): cleanupNative: return from cleanup
,I/art     ( 3345): System.exit called, status: 0
,I/AndroidRuntime( 3345): VM exiting with result code 0, cleanup skipped.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/EnterpriseDeviceManagerService(  883): isManagedProfileUser(): userId = 0
,I/wpa_supplicant( 1296): Blacklist: Clear (all) 
,I/SamsungIME( 1869): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,I/Process ( 1434): Sending signal. PID: 1434 SIG: 9
,D/[CarModeFW]( 2647): ConnectivityManager-handleMessage INITIAL_STATE_OFF
,E/UMC:UMCAdmin( 3986): No active admin owned by uid 10179
D/UMC:UMCAdmin( 3986): isContainer : 0
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/BluetoothAdapter( 1170): 572520597: getState() :  mService = null. Returning STATE_OFF
D/BluetoothTile( 1170): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapter( 1170): 572520597: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1170): 572520597: getState() :  mService = null. Returning STATE_OFF
,D/STATUSBAR-QSTileView( 1170): onStateChanged: Bluetooth
,I/FOTA_Client( 4005): [lllllllllllIlllllIIl(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,D/UMC:UMCAdmin( 3986): deactivateUMCAdmin - UMC App Admin deactivated
,D/UMC:CoreReceiver( 3986): Intent : android.intent.action.BOOT_COMPLETED
D/UMC:CoreReceiver( 3986):  check PreETag 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_bluetooth_off.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=13 Removed com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover (7/8)
,I/SurfaceFlinger(  249): id=13 Removed com.sec.android.app.popupuireceiver/com.sec.android.app.popupuireceiver.BatteryCover (-2/8)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
W/libprocessgroup(  883): failed to open /acct/uid_10154/pid_3076/cgroup.procs: No such file or directory
D/LockPatternUtilsCache( 1170): value : false
,W/libprocessgroup(  883): failed to open /acct/uid_10158/pid_3094/cgroup.procs: No such file or directory
,I/ServiceManager(  247): service 'emergency_service' died
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ScoverManager( 1315): serviceVersion : 16908288
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/Zygote  ( 4163): MountEmulatedStorage()
,E/Zygote  ( 4163): v2
I/libpersona( 4163): KNOX_SDCARD checking this for 1000
I/libpersona( 4163): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=4163 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  883): Process com.android.bluetooth (pid 3345)(adj 0) has died(64,600)
,I/ActivityManager(  883): Process com.sec.android.emergencymode.service (pid 1434)(adj 0) has died(64,600)
,I/SELinux ( 4163): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 4163): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 4163): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/AffinityControl( 4123): AffinityControl: registerfunction enter
,V/QuickStartReceiver( 3986): addAlarm()
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AndroidRuntime( 4123): Calling main entry com.android.commands.pm.Pm
,D/TimaKeyStoreProvider( 4163): TimaSignature is unavailable
,D/ActivityThread( 4163): Added TimaKeyStore provider
,D/UMC:ByodSetupStarter( 3986): Container ID : 0
,I/FOTA_Client( 4005): [com.sec.android.fotaclient.FotaUpdaterReceiver(126/onReceive)] Heartbeat settings is activated.
,W/ActivityManager(  883): getTasks: caller 10179 does not hold GET_TASKS; limiting output
,V/UMC:Utils( 3986): checkAppScreen() : com.sec.android.app.launcher
I/UMC:Core( 3986): shutdown
,I/FOTA_Client( 4005): [llIlIIIIlllIlllllIll(125/llIlIIIIlIIIIIlIlIII)] heartbeat time is vaild
,D/PackageManager(  883): START PACKAGE DELETE: observer{248616512}
D/PackageManager(  883): pkg{<packageName>}
D/PackageManager(  883): user{0}
D/PackageManager(  883): caller{2000}
D/PackageManager(  883): flags{3}
,D/PersonaManagerService(  883): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService(  883): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService(  883): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager(  883): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager(  883): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,I/GAV2    ( 3425): Thread[GAThread,5,main]: No campaign data found.
,D/PackageManager(  883): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService(  883): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService(  883): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy(  883): getApplicationUninstallationEnabled
D/ApplicationPolicy(  883): getApplicationUninstallationEnabled :  enabled true
,D/ResourcesManager( 4163): creating new AssetManager and set to /system/app/FactoryCamera_FB/FactoryCamera_FB.apk
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{2bd06656 u0 tv.peel.smartremote/tv.peel.samsung.widget.service.WidgetTimerService}
,I/wpa_supplicant( 1296): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering(  883): InitialState.processMessage what=4
,E/WifiStateMachine(  883): Supplicant connection lost
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,I/art     ( 3986): System.exit called, status: 0
,I/AndroidRuntime( 3986): VM exiting with result code 0, cleanup skipped.
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,D/ConnectivityService(  883): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PackageManager(  883): !@killApplicatoin: 10201, uninstall pkg
,E/Zygote  ( 4188): MountEmulatedStorage()
E/Zygote  ( 4188): v2
I/libpersona( 4188): KNOX_SDCARD checking this for 10014
I/libpersona( 4188): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=4188 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 1668:com.google.android.partnersetup/u0a15 (adj 15): bgCount ##41
,I/SELinux ( 4188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
E/Tethering(  883): No numeric data
,I/SELinux ( 4188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 4188): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4188): TimaSignature is unavailable
,W/PackageSettings(  883): Skipping PackageSetting{300b15a com.test.thalitest/10200} due to missing metadata
,D/ActivityThread( 4188): Added TimaKeyStore provider
,E/WifiStateMachine(  883): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,D/WifiNative-HAL(  883): callSECApiBoolean - ID [21]
,E/WifiStateMachine(  883): setWifiState: disabled
,I/ActivityManager(  883): Force stopping com.example.hello appid=10201 user=-1: uninstall pkg
I/ActivityManager(  883): Killing 3270:com.example.hello/u0a201 (adj 0): stop com.example.hello
,W/ActivityManager(  883): Force removing ActivityRecord{1ffbd012 u0 com.example.hello/.MainActivity t26}: app died, no saved state
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/SurfaceFlinger(  249): id=12 Removed com.example.hello/com.example.hello.MainActivity (5/7)
,I/SurfaceFlinger(  249): id=12 Removed com.example.hello/com.example.hello.MainActivity (-2/7)
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
I/SQLiteSecureOpenHelper( 3675): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 3675): getDatabaseLocked(b,b,pwd)...
,I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.apps.books, service: print
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> print without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/DBG_DM  ( 3925): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 0 sec
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
V/WindowManager(  883): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=0 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener(  883): mSContextAutoRotationListener.getProposedRotation, Rotation: 0
,D/SurfaceWidgetView( 1476): destroyHardwareResources():121082362
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/CameraApp( 4163): CameraApp.onCreate()... mFeature : null
,D/LockPatternUtilsCache( 1170): value : false
I/testFeature( 4163): Feature.Feature(context)
I/testFeature( 4163): Feature.readInternalDefaultXml()
I/testFeature( 4163): ResetFeatureValue
,D/FocusedStackFrame(  883): Set to : 0
,D/Launcher( 1476): onRestart, Launcher: 430343985
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/Tethering(  883): sendTetherStateChangedBroadcast 0, 0, 0
,I/ActivityManager(  883): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3986)(adj 0) has died(97,603)
,D/WifiService(  883): Client connection lost with reason: 4
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/GAV2    ( 3405): Thread[GAThread,5,main]: No campaign data found.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/CameraFirmware_broadcast( 4163): CameraFirmwareBroadCastReceiver...
I/CameraApp( 4163): CameraApp.getAppFeature()...
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,I/UpdateIcingCorporaServi( 1559): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/ActivityManager(  883): Force stopping com.example.hello appid=10201 user=0: pkg removed
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/GAV2    ( 1559): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ResourcesManager( 4188): creating new AssetManager and set to /system/priv-app/GoogleOneTimeInitializer/GoogleOneTimeInitializer.apk
,W/GAV2    ( 1559): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,D/Launcher( 1476): onStart, Launcher: 430343985
D/Launcher.HomeView( 1476): onStart
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Launcher( 1476): onResume, Launcher: 430343985
,D/SettingsProvider(  883): name = kids_home_mode
D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 10008
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider(  883): ret = -1
,D/Launcher.HomeView( 1476): onResume
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,V/OneTimeInitializerReceiver( 4188): OneTimeInitializerReceiver.onReceive
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2151): [237392/6] Surface widget resume on instance = 1
,E/Zygote  ( 4210): MountEmulatedStorage()
E/Zygote  ( 4210): v2
I/libpersona( 4210): KNOX_SDCARD checking this for 1000
I/libpersona( 4210): KNOX_SDCARD not a persona
,D/accuweather( 2151): [KK AccuPhone]>>> SWW:209 [0:0] [SWW] onResume : instance = 1
,I/ActivityManager(  883): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=4210 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 3142:com.sec.android.omc/1000 (adj 15): bgCount ##41
,I/ApplicationPolicy(  883): updateDataUsageMap
,D/Tethering(  883): MasterInitialState.processMessage what=3
,D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/CLocInfoService(  883): External Intent Received android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/CLocInfoService(  883): CLoinfo wifi false
D/SmartBondingService(  883): EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
D/SmartBondingService(  883): getSBEnabled() enabled =false
,W/SLocation(  883): No Active Data Connection
,V/NetworkStats(  883): performPollLocked(flags=0x1)
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/NetworkStatsFactory(  883): UpdateStatsForKnox
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
V/NetworkStats(  883): performPollLocked() took 2ms
,D/ResourcesManager(  883): creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,I/SELinux ( 4210): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 4210): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 4210): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/HotspotTile( 1170): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1170): updateTetherState():false, false
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/SmartBondingService(  883): getNetworkEnabled : wifi : false mobile : true
,D/Launcher( 1476): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,I/InputReader(  883): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/NetworkUtils( 1559): OkHttp exception
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1111/IlIlllIIlIlIIIlIlIll)] WiFi network Connected : false
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,W/libprocessgroup(  883): failed to open /acct/uid_10015/pid_1668/cgroup.procs: No such file or directory
,D/ConnectivityService(  883): returning getNetworkInfo(networkType - 7) :[type: BLUETOOTH[] - BLUETOOTH, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/DBG_DM  ( 3925): [com.wssyncmldm.XDMService(1125/lllllIlIlIIIIIIIIlIl)] Bluetooth Data Connected : false
,D/TimaKeyStoreProvider( 4210): TimaSignature is unavailable
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ActivityThread( 4210): Added TimaKeyStore provider
,E/SamsungIME( 1869): mOCRHelper is null
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 1462): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,D/ResourcesManager( 1462): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/StatusBar.NetworkController( 1170): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020466/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x1080907/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1170): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1170): Wifi onReceive(1)
D/HotspotTile( 1170): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,W/ResourcesManager( 1462): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/STATUSBAR-QSTileView( 1170): onStateChanged: Wi-Fi
,D/HotspotTile( 1170): onReceive : 1, 0
,V/BitmapFactory( 1170): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/tw_quick_panel_icon_wifi_off.png
,D/WifiCredService( 1315): Action received :android.net.wifi.WIFI_STATE_CHANGED
,W/GeofencerStateMachine( 2213): Ignoring removeGeofence because network location is disabled.
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecGallery2014/SecGallery2014.apk
W/Settings( 2213): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,V/OneTimeService( 4188): OneTimeService.onHandleIntent
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/sCloudSyncSNote3/sCloudSyncSNote3.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_3142/cgroup.procs: No such file or directory
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 4210): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/SecContentProvider2(  883): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2(  883): mCursor = null
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:41 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1323): [MSC_Daemon]>>> daemonapp [Version : 15010801 ] [ 2 ] 
,D/comsamsunglog( 1323): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1323): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:82 [0:0] c:null, r:3
D/daemonapp( 1323): [MSC_Daemon]>>> WDSM:84 [0:0] ABOOTCOPLD
,D/NtpTrustedTime(  883): currentTimeMillis() cache hit
D/NtpTrustedTime(  883): currentTimeMillis() cache hit
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4232): MountEmulatedStorage()
,E/Zygote  ( 4232): v2
I/libpersona( 4232): KNOX_SDCARD checking this for 10015
I/libpersona( 4232): KNOX_SDCARD not a persona
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,I/art     (  327): Explicit concurrent mark sweep GC freed 8741(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 273us total 11.830ms
,E/WifiStateMachine(  883): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
I/ActivityManager(  883): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=4232 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,E/WifiStateMachine(  883): Link configuration changed for netId: -1 old: {InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576} new: {InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0}
E/WifiStateMachine(  883): updateLinkProperties nid: -1 state: DISCONNECTED reason: CMD_UPDATE_LINKPROPERTIES
,W/ContextImpl( 4210): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1994 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:2945 
,D/MenuAppsGridFragment( 1476): onResume
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 261us total 7.863ms
,I/SELinux ( 4232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/SettingsProvider(  883): name = aw_daemon_service_key_version_check
,I/SELinux ( 4232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,D/SurfaceWidgetClient$ISurfaceWidgetStub( 2151): [237392/6] Surface widget visibility changed visibility = true on instance = 1
E/SELinux ( 4232): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/SurfaceWidget.Renderer( 2151): [237392/6] SurfaceWidget drawing first frame
,D/SettingsProvider(  883): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider(  883): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider(  883): selectionArgs: false
D/SettingsProvider(  883): selectionArgs: 10182
D/SecContentProvider(  883): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider(  883): ret = -1
,I/art     (  327): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 14MB/23MB, paused 255us total 8.034ms
,I/sCloudBackupApp( 4102): sCloudBackupApp Version Info : 4.02.2.KK_APP
,D/RCPManagerService(  883): PackageReceiver onReceive()
,W/BackupManagerService(  883): dataChanged but no participant pkg='com.android.providers.settings' uid=10182
,I/HarmonyEASService(  883): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy(  883): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/BackupManagerService(  883): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  883): Receieved: android.intent.action.PACKAGE_REMOVED
D/ActivityManager(  883): handle home activity for 0
I/WallpaperManagerService(  883): switchPersonaWallpaper is called for personaId-0
D/ActivityManager(  883): post active user change for 0
D/KnoxTimeoutHandler(  883): postActiveUserChange for user 0
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy(  883): uID is 10201
V/EnterpriseBillingPolicy(  883): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage(  883): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage(  883): getProfileForApplication - exit null
V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - personal application - profile null
,V/EnterpriseBillingPolicy(  883): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage(  883): getBillingProfileForVpnEngine - start - com.example.hello
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1622 [0:0] PakNme size = 5
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:262 [0:0] regintype : EUR
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:318 [0:0] cp type is : cp_eng
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1626 [0:0] CP Name cp_eng
,I/SurfaceFlinger(  249): id=15 createSurf (1080x1920),1 flag=4, com.sec.android.app.launcher/com.android.launcher2.Launcher
,D/TimaKeyStoreProvider( 4232): TimaSignature is unavailable
,D/ActivityThread( 4232): Added TimaKeyStore provider
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/EnterpriseBillingPolicyStorage(  883): getBillingProfileForVpnEngine - end - null
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/daemonapp( 1323): [MSC_Daemon]>>> WU:1606 [0:0] [NameNotFoundException] !!
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ResourcesManager( 2457): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1949 [0:0] [boot]now           :1456842787384
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1950 [0:0] [boot]NUT :1456864320000
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1951 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1323): [MSC_Daemon]>>> WU:1952 [0:0] [boot]NUT - now :true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/SLocation(  883): BroadcastReceiver : WIFI_STATE_CHANGED_ACTION
D/SmartBondingService(  883): SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,D/SmartBondingService(  883): getNetworkEnabled : wifi : false mobile : true
,I/ActivityManager(  883): Killing 3157:com.sec.android.app.sbrowser/u0a143 (adj 15): bgCount ##41
,D/daemonapp( 1323): [MSC_Daemon]>>> WDBH:2171 [0:0] ud NT1456864320000
,I/ActivityManager(  883): Killing 3176:com.sec.android.app.SecSetupWizard/1000 (adj 15): bgCount ##41
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/daemonapp( 1323): [MSC_Daemon]>>> WU:1962 [0:0] Boot set AR_nexttime :1456864320000
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 1476): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,W/ResourcesManager( 1476): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1476): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/WallpaperManagerService(  883):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler(  883): handleActiveUserChange for user 0
,D/ResourcesManager( 1476): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,D/accuweather( 2151): [KK AccuPhone]>>> RM:150 [0:0]  onFirstUpdate :: mFU = false
,D/accuweather( 2151): [KK AccuPhone]>>> SWW:223 [0:0]  onResume :: isFirst = false, cnt = 0
D/accuweather( 2151): [KK AccuPhone]>>> SWW:230 [0:0] onResume : size = 1
,W/ResourcesManager( 1476): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 1476): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/accuweather( 2151): [KK AccuPhone]>>> SWW:512 [0:0]  registerTTReceiver ! 
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/Launcher( 1476): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 1476): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 8000
I/GLSUser ( 1685): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,I/GLSUser ( 1685): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1685): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1685): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 4232): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/RegisteredServicesCache( 1455): empty dynamic service
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/TaskPersister(  883): removeObsoleteFile: deleting file=26_task.xml
D/TaskPersister(  883): removeObsoleteFile: deleting file=26_task_thumbnail.png
D/TaskPersister(  883): removeObsoleteFile: deleting file=27_task_thumbnail.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/LockPatternUtils( 1315): isSmartCardAuthenticationAvailable: false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/art     (  883): Explicit concurrent mark sweep GC freed 58647(3MB) AllocSpace objects, 13(2MB) LOS objects, 31% free, 35MB/51MB, paused 1.622ms total 239.414ms
I/art     (  883): WaitForGcToComplete blocked for 134.852ms for cause Explicit
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 1315): creating new AssetManager and set to /system/app/SamsungTTS/SamsungTTS.apk
,D/ResourcesManager( 1315): creating new AssetManager and set to /system/app/GoogleTTS/GoogleTTS.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/PackageManager(  883): delete codoeFile: 
,D/PackageManager(  883): result of delete: 1{248616512}
,D/AndroidRuntime( 4123): Shutting down VM
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
E/BargeInRecognizer( 1315): make new BargeInRecognizer
,E/BargeInRecognizer( 1315): stringLanguage : en
E/BargeInRecognizer( 1315): stringCountry : US
E/BargeInRecognizer( 1315): sVoiceLanguage : null
E/BargeInRecognizer( 1315): isEnableBargeIn : true
E/BargeInRecognizer( 1315): uselanguage : 1
E/BargeInRecognizer( 1315): isEnableChineseBargeIn : false
E/BargeInRecognizer( 1315): isEnableJapaneseBargeIn : true
E/BargeInRecognizer( 1315): isEnableRussianBargeIn : true
E/BargeInRecognizer( 1315): mState : 0
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_3176/cgroup.procs: No such file or directory
W/libprocessgroup(  883): failed to open /acct/uid_10143/pid_3157/cgroup.procs: No such file or directory
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,I/art     (  883): Explicit concurrent mark sweep GC freed 6914(352KB) AllocSpace objects, 0(0B) LOS objects, 31% free, 34MB/50MB, paused 1.742ms total 103.812ms
,D/InputMethodManagerService(  883): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,D/EnterpriseDeviceManagerService(  883): Package has changed for user 0
D/EnterpriseDeviceManagerService(  883): Admin package name: com.google.android.gms
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.android.server.InputMethodManagerService$6.run:2728 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService(  883): Got RemoteException sending setActive(false) notification to pid 3270 uid 10201
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
,W/GLSActivity( 1685): com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.e(SourceFile:1268)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.p.d(SourceFile:599)
W/GLSActivity( 1685): 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
W/GLSActivity( 1685): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1685): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1685): 	at android.os.Binder.execTransact(Binder.java:446)
,E/Zygote  ( 4253): MountEmulatedStorage()
E/Zygote  ( 4253): v2
I/libpersona( 4253): KNOX_SDCARD checking this for 10067
I/libpersona( 4253): KNOX_SDCARD not a persona
,D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecContacts/SecContacts.apk
,I/ActivityManager(  883): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4253 uid=10067 gids={50067, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  883): Killing 3207:com.sec.tcpdumpservice/1000 (adj 15): bgCount ##41
,D/accuweather( 2151): [KK AccuPhone]>>> WR:139 [0:0] onResume orientation = 1, from res = Port fHD
,D/accuweather( 2151): [KK AccuPhone]>>> SM:523 [0:0] onResume : false, rsStep = 2
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/EditorsDocs/EditorsDocs.apk
,E/Zygote  ( 4259): MountEmulatedStorage()
I/libpersona( 4259): KNOX_SDCARD checking this for 10109
E/Zygote  ( 4259): v2
I/libpersona( 4259): KNOX_SDCARD not a persona
,I/ActivityManager(  883): Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=4259 uid=10109 gids={50109, 9997, 1023} abi=armeabi-v7a
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/ActivityManager(  883): Waited long enough for: ServiceRecord{13098a66 u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,I/SELinux ( 4253): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,E/BooksAccountManager( 3425): Authentication error
E/BooksAccountManager( 3425): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/BooksAccountManager( 3425): android.accounts.AccountManager.convertErrorToException(AccountManager.java:1893)
E/HttpHelper( 3425): null auth token
,V/GLSActivity( 1685): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/qtaguid ( 3425): Tagging socket 34 with tag 10000000000{256,0} uid -1, pid: 3425, getuid(): 10082
,I/SELinux ( 4253): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
E/SELinux ( 4253): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,E/Zygote  ( 4273): MountEmulatedStorage()
E/Zygote  ( 4273): v2
I/libpersona( 4273): KNOX_SDCARD checking this for 10112
I/libpersona( 4273): KNOX_SDCARD not a persona
,W/ApiaryClient( 3425): errCount = 3: com.google.android.apps.books.net.HttpHelper$OfflineIoException: java.net.UnknownHostException: URL: https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2458281435795576837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
W/ApiaryClient( 3425): Headers suppressed
,I/ActivityManager(  883): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=4273 uid=10112 gids={50112, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/SecMemoDL/SecMemoDL.apk
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/SELinux ( 4259): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 4259): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 4259): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4253): TimaSignature is unavailable
,D/ActivityThread( 4253): Added TimaKeyStore provider
,E/BooksSync( 3425): Soft error
E/BooksSync( 3425): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2458281435795576837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 3425): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
E/BooksSync( 3425): Sync error
E/BooksSync( 3425): com.google.android.apps.books.net.HttpHelper$OfflineIoException: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Device offline, skipping https://www.googleapis.com/books/v1/myconfig/syncVolumeLicenses?cpksver=2%3DS0HXd4TFLU4&nonce=-2458281435795576837&features=RENTALS&key=AIzaSyCuLL2piIVBGOtu196oSi3-ndISBYPOjCU&source=ge-android-app
E/BooksSync( 3425): com.google.android.apps.books.net.HttpHelper.shouldSkipRetry(HttpHelper.java:88)
I/SELinux ( 4273): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/BooksSync( 3425): Finished books sync
,I/SELinux ( 4273): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 4273): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,I/MicrophoneInputStream( 1559): mic_starting gfk@2e4dca21
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,I/HotwordRecognitionRnr( 1559): Starting hotword detection.
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PanelView( 1170): There is/are notification(s) 
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,W/libprocessgroup(  883): failed to open /acct/uid_1000/pid_3207/cgroup.procs: No such file or directory
,D/WallpaperManager( 1476): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/daemonapp( 1323): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/AudioPolicyManager(  292): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager(  292): getDeviceForInputSource()input source 1999, device 80000004
V/audio_hw_primary(  292): adev_open_input_stream: enter
E/audio_hw_primary(  292): adev_open_input_stream : jack_config 0
,E/audio_hw_primary(  292): can not make /data/snd/hal_input.pcm 
E/audio_hw_primary(  292): can not make /data/snd/hal_input_before_ns.pcm 
E/audio_hw_primary(  292): can not make /data/snd/hal_input_after_ns.pcm 
E/audio_hw_primary(  292): adev_open_input_stream input is null, set new input stream
V/audio_hw_primary(  292): adev_open_input_stream: exit
,D/TimaKeyStoreProvider( 4273): TimaSignature is unavailable
,D/TimaKeyStoreProvider( 4259): TimaSignature is unavailable
D/ActivityThread( 4259): Added TimaKeyStore provider
D/ActivityThread( 4273): Added TimaKeyStore provider
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,I/AudioFlinger(  292): AudioFlinger's thread 0xafa44000 ready to run
V/audio_hw_primary(  292): in_standby: enter
V/audio_hw_primary(  292): in_standby: exit:  status(0)
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/audio_hw_primary(  292): in_standby: enter
V/audio_hw_primary(  292): in_standby: exit:  status(0)
,I/EDMNativeHelperService(  883): isMicrophoneEnabled
,D/StatusBarManagerService(  883): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,I/Timeline( 1476): Timeline: Activity_idle id: android.os.BinderProxy@2e7fe32c time:34404
,V/AudioPolicyManager(  292): startInput() input 26
V/AudioPolicyManager(  292): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  292): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  292): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  292): DeviceVector::getDevicesFromType() for type 80000004 found 0xb295b3c0
,V/audio_hw_primary(  292): in_set_parameters: enter: kvpairs=input_source=6;keyIsHotword=true;routing=-2147483644
V/audio_hw_primary(  292): in_set_parameters: exit: status(11)
,V/AudioPolicyManager(  292): setInputDevice() createAudioPatch returned 11 patchHandle 0
V/AudioPolicyManager(  292): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 1559): mic_started gfk@2e4dca21
D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager( 4253): creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,V/msm8974_platform(  292): platform_update_usecase_from_source: input source :6
V/audio_hw_primary(  292): start_input_stream: enter: usecase(7)
V/voice   (  292): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  292): start_input_stream: usecase(7)
D/PreProcess(  292): new SamsungRecord
D/PreProcess(  292): new NS
I/samsungRecord(  292): [samsungrecord] SamsungRecInit 
,I/samsungRecord(  292): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord(  292): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord(  292): 1
D/SamsungRecord_NS(  292): [SamsungRecord_NS] Init SR 16000
D/SamsungRecord_NS(  292): [SamsungRecord_NS] getLevel inputsource 6, ret_level 3
V/audio_hw_primary(  292): select_devices: ENTER
V/audio_hw_primary(  292): select_devices: usecase(normal)
V/audio_hw_primary(  292): select_devices: usecase(PCM_CAPTURE)
V/msm8974_platform(  292): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  292): get_INPUT_snd_device: check by Input_source(6)
V/msm8974_platform(  292): platform_get_input_snd_device_by_source: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  292): get_INPUT_snd_device: AUDIO_SOURCE_VOICE_RECOGNITION
V/msm8974_platform(  292): platform_get_input_snd_device: exit: in_snd_device(vr-main-mic)
D/audio_hw_primary(  292): select_devices: out_snd_device(0: dummy)
D/audio_hw_primary(  292): select_devices: in_snd_device(122: vr-main-mic)
D/ACDB-LOADER(  292): ACDB -> send_audio_cal, acdb_id = 53, path =  1
D/ACDB-LOADER(  292): ACDB -> send_adm_topology
D/ACDB-LOADER(  292): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
,D/ACDB-LOADER(  292): ACDB -> send_asm_topology
D/ACDB-LOADER(  292): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  292): ACDB -> send_audtable
D/ACDB-LOADER(  292): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/        (  292): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/ACDB-LOADER(  292): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  292): ACDB -> send_audvoltable
D/ACDB-LOADER(  292): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  292): ACDBFILE_MGR:Read the devices count as zero, please check the acdb file
D/        (  292): Failed to fetch the lookup information of the device 00000035 
E/ACDB-LOADER(  292): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  292): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  292): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  292): enable_snd_device: snd_device(122: vr-main-mic, vr-main-mic)
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: DEC2 Volume
D/audio_route(  292): Setting mixer control: value: 106
,D/audio_route(  292): Setting mixer control: SLIM TX7 MUX, value: 9
,D/audio_route(  292): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  292): Setting mixer control: value: 1
,D/audio_route(  292): Setting mixer control: DEC2 MUX, value: 1
,D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): enable_audio_route: enter: usecase(7)
V/audio_hw_primary(  292): enable_audio_route: apply mixer path: audio-record
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  292): Setting mixer control: value: 1
,D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): enable_audio_route: exit
V/audio_hw_primary(  292): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
,V/audio_hw_primary(  292): start_input_stream: exit
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/ResourcesManager( 1685): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 4273): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/ResourcesManager( 4259): creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,E/Zygote  ( 4305): MountEmulatedStorage()
I/libpersona( 4305): KNOX_SDCARD checking this for 10071
E/Zygote  ( 4305): v2
I/libpersona( 4305): KNOX_SDCARD not a persona
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/mipmap-xxhdpi-v4/ic_launcher_google_search.png
,I/ActivityManager(  883): Start proc com.sec.android.widgetapp.ap.hero.accuweather for content provider com.sec.android.widgetapp.ap.hero.accuweather/.provider.accuweather.AccuContentProvider: pid=4305 uid=10071 gids={50071, 9997, 3003, 1028} abi=armeabi-v7a
,I/SELinux ( 4305): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,I/SELinux ( 4305): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
D/comdaemonstockapp( 1323): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
,D/comdaemonstockapp( 1323): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
E/SELinux ( 4305): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,V/BitmapFactory( 1685): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_google_selected.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
D/ResourcesManager(  883): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/SecContentProvider2(  883): uri = 14 selection = getSealedState
D/SecContentProvider2(  883): mCursor = null
,E/SMD     (  287): DCD ON
,D/SecContentProvider2(  883): KnoxCustomManagerService offline: service is not available
,I/HotwordWorker( 1559): onReady
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/TimaKeyStoreProvider( 4305): TimaSignature is unavailable
,D/ActivityThread( 4305): Added TimaKeyStore provider
,D/ApplicationPolicy(  883): isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
,V/ApplicationPolicy(  883): isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,D/PackageIntentReceiver( 4273): ACTION_BOOT_COMPLETED
,W/FileUtils( 1685): Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,V/BitmapFactory( 1476): DecodeImagePath(decodeResourceStream3) : res/drawable-xxhdpi-v4/ic_mic.png
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,E/SharedPreferencesImpl( 2457): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1643 com.android.server.ssrm.ag.bo:-1 com.android.server.ssrm.ah.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,D/ResourcesManager( 4305): creating new AssetManager and set to /system/app/AccuweatherPhone2014_K_LMR_fHD/AccuweatherPhone2014_K_LMR_fHD.apk
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Drive/Drive.apk
,E/Zygote  ( 4328): MountEmulatedStorage()
I/libpersona( 4328): KNOX_SDCARD checking this for 10185
E/Zygote  ( 4328): v2
I/libpersona( 4328): KNOX_SDCARD not a persona
,D/StatusBar( 1170): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,W/ResourcesManager( 4305): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  883): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4328 uid=10185 gids={50185, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager( 4305): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4305): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/Icing   ( 2457): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
,W/Search.LoginHelper( 1559): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,W/Search.LoginHelper( 1559): User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
,I/ContactAccountLoggerTas( 1559): canRun() : Opted Out
,E/SQLiteDatabase( 4232): Failed to open database '/data/data/com.google.android.partnersetup/databases/rlz_data.db'.
E/SQLiteDatabase( 4232): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 4232): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 4232): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4232): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4232): 	at com.google.android.partnersetup.RlzProvider.update(RlzProvider.java:411)
E/SQLiteDatabase( 4232): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/SQLiteDatabase( 4232): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/SQLiteDatabase( 4232): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntentWithContext(RlzPingIntentService.java:137)
E/SQLiteDatabase( 4232): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntent(RlzPingIntentService.java:111)
E/SQLiteDatabase( 4232): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4232): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4232): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4232): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Search.SharedPreferencesProto( 1559): Failed to rename to backup file /data/data/com.google.android.googlequicksearchbox/app_shared_prefs/SearchSettings.bin.bak
,E/SQLiteDatabase( 4253): Failed to open database '/data/data/com.samsung.android.scloud.sync/databases/smemofiletracker.db'.
E/SQLiteDatabase( 4253): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 4253): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 4253): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4253): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 4253): 	at com.sec.android.sCloudSync.Providers.SMemoFileTracker.onCreate(SMemoFileTracker.java:75)
E/SQLiteDatabase( 4253): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
E/SQLiteDatabase( 4253): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
E/SQLiteDatabase( 4253): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5453)
E/SQLiteDatabase( 4253): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5048)
E/SQLiteDatabase( 4253): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4988)
E/SQLiteDatabase( 4253): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 4253): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1483)
E/SQLiteDatabase( 4253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4253): 	at android.os.Looper.loop(Looper.java:145)
E/SQLiteDatabase( 4253): 	at android.app.ActivityThread.main(ActivityThread.java:5832)
E/SQLiteDatabase( 4253): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 4253): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 4253): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/SQLiteDatabase( 4253): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/PackageIntentReceiver( 4273): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,E/SQLiteDatabase( 4259): Failed to open database '/data/user/0/com.samsung.android.provider.filterprovider/databases/filter.db'.
E/SQLiteDatabase( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteDatabase( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteDatabase( 4259): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteDatabase( 4259): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/SQLiteDatabase( 4259): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteDatabase( 4259): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteDatabase( 4259): 	at android.os.Binder.execTransact(Binder.java:446)
,E/SQLiteOpenHelper( 4259): Couldn't open filter.db for writing (will try read-only):
E/SQLiteOpenHelper( 4259): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 4259): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/SQLiteOpenHelper( 4259): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteOpenHelper( 4259): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
E/SQLiteOpenHelper( 4259): 	at com.samsung.android.provider.filterprovider.FilterProvider.query(FilterProvider.java:438)
E/SQLiteOpenHelper( 4259): 	at android.content.ContentProvider.query(ContentProvider.java:978)
E/SQLiteOpenHelper( 4259): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:213)
E/SQLiteOpenHelper( 4259): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/SQLiteOpenHelper( 4259): 	at android.os.Binder.execTransact(Binder.java:446)
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/SQLiteOpenHelper( 4259): Opened filter.db in read-only mode
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
I/SMemoFileTracker( 4253): Runtime Exception when creating DB not an error (code 0): Could not open the database in read/write mode.
,D/LockPatternUtilsCache( 1170): value : false
,I/SELinux ( 4328): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
,D/LockPatternUtilsCache( 1170): value : false
D/PanelView( 1170): There is/are notification(s) 
,D/PanelView( 1170): There is/are notification(s) 
I/SELinux ( 4328): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
,E/SELinux ( 4328): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/AndroidRuntime( 4232): FATAL EXCEPTION: IntentService[GooglePartnerSetup]
E/AndroidRuntime( 4232): Process: com.google.android.partnersetup, PID: 4232
E/AndroidRuntime( 4232): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:891)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:861)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 4232): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1450)
E/AndroidRuntime( 4232): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 4232): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 4232): 	at com.google.android.partnersetup.RlzProvider.update(RlzProvider.java:411)
E/AndroidRuntime( 4232): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
E/AndroidRuntime( 4232): 	at android.content.ContentResolver.update(ContentResolver.java:1343)
E/AndroidRuntime( 4232): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntentWithContext(RlzPingIntentService.java:137)
E/AndroidRuntime( 4232): 	at com.google.android.partnersetup.RlzPingIntentService.onHandleIntent(RlzPingIntentService.java:111)
E/AndroidRuntime( 4232): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4232): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4232): 	at android.os.Looper.loop(Looper.java:145)
E/AndroidRuntime( 4232): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources(  883): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteLog( 4259): (284) automatic index on titles(filter_id)
D/ResourcesManager(  883): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,E/APS     (  883): Persistence Service Logger writeToLogFile failed for entry: Start sending PS_READY intents . Got exception: /persdata/absolute/abt-persistence-service4.log: open failed: EROFS (Read-only file system) Re-initializing log.
,W/ContextImpl(  883): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1629 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
E/ActivityManager(  883): checkUser: useridlist=null, currentuser=0
,V/VibratorService(  883): hasVibrator - useVibetonz: true
,D/LockPatternUtilsCache( 1170): getCarrierLockPlusMode()
D/LockPatternUtilsCache( 1170): value : false
,E/Zygote  ( 4342): MountEmulatedStorage()
E/Zygote  ( 4342): v2
I/libpersona( 4342): KNOX_SDCARD checking this for 10019
I/libpersona( 4342): KNOX_SDCARD not a persona
I/ActivityManager(  883): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=4342 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,E/SQLiteLog( 4259): (10) unixRead() File Descriptor : 25 gets errno : 5
,E/SQLiteLog( 4259): (266) statement aborts at 45: [SELECT _ID, name, filename, version, vendor, title, package_name, deleted, filter_order FROM view_filters ORDER BY filter_order] 
E/SQLiteQuery( 4259): exception: disk I/O error (code 266); query: SELECT _ID, name, filename, version, vendor, title, package_name, deleted, filter_order FROM view_filters ORDER BY filter_order
,D/ResourcesManager(  883): creating new AssetManager and set to /system/app/PlayGames/PlayGames.apk
,F/libc    (  883): Fatal signal 7 (SIGBUS), code 2, fault addr 0x776fcf28 in tid 1232 (Binder_4)
,E/audit_log( 2137): File locking failed. error= Bad file number
,E/audit_log( 2137): File locking failed. error= Bad file number
,E/audit_log( 2137): File locking failed. error= Bad file number
,I/SELinux ( 4342): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-G900F_5.0 ver=27
I/SELinux ( 4342): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-G900F_5.0_0027
E/SELinux ( 4342): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_DM  ( 3925): [IIllIIllIIIlllIlIIll(412/llllllIllIlIlllIIlIl)] waits 1 sec
,I/FactoryTestApp( 3252): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3890)  
,I/ServiceManager(  247): service 'wifip2p' died
,I/ServiceManager(  247): service 'backup' died
I/ServiceManager(  247): service 'appwidget' died
I/ServiceManager(  247): service 'voiceinteraction' died
I/ServiceManager(  247): service 'SecExternalDisplayService' died
I/ServiceManager(  247): service 'diskstats' died
W/Sensors ( 2902): sensorservice died [0xaed71540]
I/ServiceManager(  247): service 'spengestureservice' died
I/ServiceManager(  247): service 'quickconnect' died
I/ServiceManager(  247): service 'samplingprofiler' died
,I/ServiceManager(  247): service 'commontime_management' died
W/Sensors ( 1462): sensorservice died [0xaed64380]
I/ServiceManager(  247): service 'dreams' died
I/ServiceManager(  247): service 'print' died
I/ServiceManager(  247): service 'restrictions' died
I/ServiceManager(  247): service 'media_session' died
I/ServiceManager(  247): service 'media_router' died
I/ServiceManager(  247): service 'trust' died
I/ServiceManager(  247): service 'fingerprint' died
I/ServiceManager(  247): service 'launcherapps' died
I/ServiceManager(  247): service 'voip' died
I/ServiceManager(  247): service 'media_projection' died
W/Sensors ( 1170): sensorservice died [0xaedd20c0]
I/ServiceManager(  247): service 'imms' died
I/ServiceManager(  247): service 'clinfo' died
I/ServiceManager(  247): service 'servicediscovery' died
I/ServiceManager(  247): service 'updatelock' died
I/ServiceManager(  247): service 'notification' died
I/ServiceManager(  247): service 'devicestoragemonitor' died
E/WifiManager( 2213): Channel connection lost
E/WifiManager( 1835): Channel connection lost
,D/SurfaceFlinger(  249): Set power mode=2, type=0 flinger=0xb6a62000
D/SurfaceFlinger(  249): Screen type=0 is already mode=2
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (4/7)
E/WifiManager( 1170): Channel connection lost
F/libc    ( 4328): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759acd71 in tid 4328 (android.youtube)
F/libc    ( 4328): Unable to open connection to debuggerd: Connection refused
,E/WifiManager( 1462): Channel connection lost
E/audit_log( 2137): File locking failed. error= Bad file number
,F/libc    ( 4342): Fatal signal 7 (SIGBUS), code 2, fault addr 0x759acd71 in tid 4342 (msung.klmsagent)
,F/libc    ( 4342): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2137): File locking failed. error= Bad file number
,I/SurfaceFlinger(  249): restart the boot-animation @ binderDied
,W/Sensors ( 1476): sensorservice died [0xaedc1400]
F/libc    ( 2151): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b65bd in tid 2151 (r:SurfaceWidget)
F/libc    ( 2151): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2137): File locking failed. error= Bad file number
E/WifiManager( 1315): Channel connection lost
,W/Sensors ( 2647): sensorservice died [0xaed7c080]
,F/libc    ( 1315): Fatal signal 7 (SIGBUS), code 2, fault addr 0x747937b0 in tid 3924 (Thread-56)
W/Sensors ( 2213): sensorservice died [0xaedc1ec0]
,F/libc    ( 1315): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2137): File locking failed. error= Bad file number
,F/libc    ( 1476): Fatal signal 7 (SIGBUS), code 2, fault addr 0x781c37f3 in tid 1793 (menu_app_thread)
,F/libc    ( 4232): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b74a2 in tid 4314 (IntentService[G)
F/libc    ( 4232): Unable to open connection to debuggerd: Connection refused
,I/ServiceManager(  247): service 'location' died
E/audit_log( 2137): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'country_detector' died
I/ServiceManager(  247): service 'sec_location' died
I/ServiceManager(  247): service 'search' died
I/ServiceManager(  247): service 'dropbox' died
I/ServiceManager(  247): service 'wallpaper' died
I/ServiceManager(  247): service 'audio' died
I/ServiceManager(  247): service 'DockObserver' died
I/ServiceManager(  247): service 'wifi' died
I/ServiceManager(  247): service 'msapwifi' died
I/ServiceManager(  247): service 'wifiscanner' died
I/ServiceManager(  247): service 'rttmanager' died
I/ServiceManager(  247): service 'connectivity' died
I/ServiceManager(  247): service 'sb_service' died
I/ServiceManager(  247): service 'mum_container_policy' died
I/ServiceManager(  247): service 'enterprise_billing_policy' died
I/ServiceManager(  247): service 'knox_timakeystore_policy' died
I/ServiceManager(  247): service 'enterprise_policy' died
I/ServiceManager(  247): service 'statusbar' died
I/ServiceManager(  247): service 'clipboard' died
I/ServiceManager(  247): service 'clipboardEx' died
I/ServiceManager(  247): service 'network_management' died
I/ServiceManager(  247): service 'usb' died
I/ServiceManager(  247): service 'serial' died
I/ServiceManager(  247): service 'uimode' died
I/ServiceManager(  247): service 'jobscheduler' died
F/libc    ( 1476): Unable to open connection to debuggerd: Connection refused
I/ServiceManager(  247): service 'ABTPersistenceService' died
I/ServiceManager(  247): service 'textservices' died
I/ServiceManager(  247): service 'network_score' died
I/ServiceManager(  247): service 'netstats' died
I/ServiceManager(  247): service 'netpolicy' died
I/ServiceManager(  247): service 'tactileassist' died
I/ServiceManager(  247): service 'bluetooth_manager' died
I/ServiceManager(  247): service 'bluetooth_secure_mode_manager' died
I/ServiceManager(  247): service 'rcp' died
I/ServiceManager(  247): service 'input_method' died
I/ServiceManager(  247): service 'sec_analytics' died
I/ServiceManager(  247): service 'entropy' died
I/ServiceManager(  247): service 'batterystats' died
I/ServiceManager(  247): service 'appops' died
I/ServiceManager(  247): service 'power' died
I/ServiceManager(  247): service 'display' died
I/ServiceManager(  247): service 'context_aware' died
I/ServiceManager(  247): service 'scontext' died
I/ServiceManager(  247): service 'barbeam' died
I/ServiceManager(  247): service 'multiwindow_facade' died
I/ServiceManager(  247): service 'window' died
I/ServiceManager(  247): service 'input' died
I/ServiceManager(  247): service 'persona_policy' died
I/ServiceManager(  247): service 'SEAMService' died
I/ServiceManager(  247): service 'persona' died
I/ServiceManager(  247): service 'account' died
I/ServiceManager(  247): service 'content' died
I/ServiceManager(  247): service 'DirEncryptService' died
I/ServiceManager(  247): service 'ReactiveService' died
I/ServiceManager(  247): service 'enterprise_license_policy' died
I/ServiceManager(  247): service 'application_policy' died
I/ServiceManager(  247): service 'wifi_policy' died
I/ServiceManager(  247): service 'phone_restriction_policy' died
I/ServiceManager(  247): service 'remoteinjection' died
I/ServiceManager(  247): service 'accessibility' died
I/ServiceManager(  247): service 'motion_recognition' died
I/ServiceManager(  247): service 'cover' died
I/ServiceManager(  247): service 'mount' died
I/ServiceManager(  247): service 'lock_settings' died
I/ServiceManager(  247): service 'device_policy' died
I/ServiceManager(  247): service 'harmony_eas_service' died
I/ServiceManager(  247): service 'sdp' died
I/ServiceManager(  247): service 'log_manager_service' died
I/ServiceManager(  247): service 'sedenial' died
I/ServiceManager(  247): service 'vibrator' died
I/ServiceManager(  247): service 'tw_toolbox' died
I/ServiceManager(  247): service 'tima' died
E/audit_log( 2137): File locking failed. er,ror= Bad file number
I/ServiceManager(  247): service 'cepproxyks' died
I/ServiceManager(  247): service 'CustomFrequencyManagerService' died
I/ServiceManager(  247): service 'samsung.smartfaceservice' died
I/ServiceManager(  247): service 'consumer_ir' died
I/ServiceManager(  247): service 'alarm' died
I/ServiceManager(  247): service 'procstats' died
E/audit_log( 2137): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'activity' died
I/ServiceManager(  247): service 'permission' died
I/ServiceManager(  247): service 'package' died
I/ServiceManager(  247): service 'telephony.registry' died
I/ServiceManager(  247): service 'cpuinfo' died
I/ServiceManager(  247): service 'hardware' died
I/ServiceManager(  247): service 'edmnativehelper' died
I/ServiceManager(  247): service 'sensorservice' died
I/ServiceManager(  247): service 'mdm.remotedesktop' died
I/ServiceManager(  247): service 'meminfo' died
E/audit_log( 2137): File locking failed. error= Bad file number
I/ServiceManager(  247): service 'dbinfo' died
I/ServiceManager(  247): service 'battery' died
I/ServiceManager(  247): service 'gfxinfo' died
I/ServiceManager(  247): service 'user' died
I/ServiceManager(  247): service 'webviewupdate' died
I/ServiceManager(  247): service 'usagestats' died
I/ServiceManager(  247): service 'scheduling_policy' died
W/Sensors ( 2243): sensorservice died [0xaedbec00]
W/Sensors ( 1449): sensorservice died [0xaedbebc0]
D/AndroidRuntime( 4305): Shutting down VM
F/libc    ( 4305): Fatal signal 7 (SIGBUS), code 2, fault addr 0x747937b0 in tid 4305 (ero.accuweather)
F/libc    ( 4305): Unable to open connection to debuggerd: Connection refused
F/libc    ( 4232): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6aa1 in tid 4326 (IntentService[G)
F/libc    ( 4232): Unable to open connection to debuggerd: Connection refused
F/libc    ( 2457): Fatal signal 7 (SIGBUS), code 2, fault addr 0x9de7e375 in tid 3560 (Icing-Worker-0)
,F/libc    ( 2457): Unable to open connection to debuggerd: Connection refused
,E/WifiManager( 1559): Channel connection lost
,W/AudioFlinger(  292): power manager service died !!!
,F/libc    ( 1685): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b626f in tid 4096 (Binder_7)
W/AudioFlinger(  292): power manager service died !!!
,W/AudioFlinger(  292): power manager service died !!!
F/libc    ( 1685): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2137): File locking failed. error= Bad file number
,E/audit_log( 2137): File locking failed. error= Bad file number
,I/SurfaceFlinger(  249): id=5 Removed DimLayer (2/6)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (4/5)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (2/4)
I/SurfaceFlinger(  249): id=7 Removed com.android.systemui.ImageWallpaper (-2/4)
I/SurfaceFlinger(  249): id=15 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (2/3)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (2/2)
I/SurfaceFlinger(  249): id=9 Removed StatusBar (-2/2)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (0/1)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (0/0)
I/SurfaceFlinger(  249): id=5 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=6 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=15 Removed com.sec.android.app.launcher/com.android.launcher2.Launcher (-2/0)
I/SurfaceFlinger(  249): id=2 Removed FocusedStackFrame (-2/0)
I/SurfaceFlinger(  249): id=3 Removed DimLayer (-2/0)
I/SurfaceFlinger(  249): id=4 Removed DimLayer (-2/0)
F/libc    ( 3252): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b6c2d in tid 3890 (Timer-0)
,F/libc    ( 3252): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2137): File locking failed. error= Bad file number
,E/DatabaseUtils( 4259): Writing exception to parcel
E/DatabaseUtils( 4259): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 266)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:144)
E/DatabaseUtils( 4259): 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:133)
E/DatabaseUtils( 4259): 	at android.database.CursorToBulkCursorAdaptor.getBulkCursorDescriptor(CursorToBulkCursorAdaptor.java:145)
E/DatabaseUtils( 4259): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:122)
E/DatabaseUtils( 4259): 	at android.os.Binder.execTransact(Binder.java:446)
,F/libc    ( 4253): Fatal signal 7 (SIGBUS), code 2, fault addr 0x758b65bd in tid 4350 (Thread-561)
,W/System.err( 4210): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 266)
,F/libc    ( 4210): Fatal signal 7 (SIGBUS), code 2, fault addr 0x73d672d9 in tid 4249 (FilterPackageSe)
,I/Zygote  (  327): Process 4342 exited due to signal (7)
,I/Zygote  (  327): Process 2151 exited due to signal (7)
,F/libc    ( 4253): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2137): File locking failed. error= Bad file number
,F/libc    ( 4210): Unable to open connection to debuggerd: Connection refused
,E/audit_log( 2137): File locking failed. error= Bad file number
,I/Zygote  (  327): Process 4305 exited due to signal (7)
I/Zygote  (  327): Process 4328 exited due to signal (7)
,I/ServiceManager(  339): Waiting for service AtCmdFwd...
,F/libc    ( 1559): Fatal signal 7 (SIGBUS), code 2, fault addr 0x747937b0 in tid 4205 (IntentService[U)
,F/libc    ( 1559): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2137): File locking failed. error= Bad file number
I/Zygote  (  327): Process 1476 exited due to signal (7)
,I/Zygote  (  327): Process 3252 exited due to signal (7)
F/libc    ( 1628): Fatal signal 7 (SIGBUS), code 2, fault addr 0xaecb0070 in tid 1628 (oid.app.shealth)
I/Zygote  (  327): Process 1685 exited due to signal (7)
,I/Zygote  (  327): Process 4232 exited due to signal (7)
F/libc    ( 1628): Unable to open connection to debuggerd: Connection refused
E/audit_log( 2137): File locking failed. error= Bad file number
,I/Zygote  (  327): Process 4253 exited due to signal (7)
,I/Zygote  (  327): Process 4210 exited due to signal (7)
I/Zygote  (  327): Process 2457 exited due to signal (7)
,V/AudioPolicyManager(  292): stopInput() input 26
,V/AudioPolicyManager(  292): releaseInput() 26
V/AudioPolicyManager(  292): closeInput(26)
,I/Zygote  (  327): Process 1559 exited due to signal (7)
I/Zygote  (  327): Process 1628 exited due to signal (7)
,V/audio_hw_primary(  292): in_standby: enter
,V/audio_hw_primary(  292): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  292): disable_audio_route: enter: usecase(7)
V/audio_hw_primary(  292): disable_audio_route: reset mixer path: audio-record
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: MultiMedia1 Mixer SLIM_0_TX
D/audio_route(  292): Setting mixer control: value: 0
,D/audio_route(  292): ------ audio_route_update_mixer ==============
V/audio_hw_primary(  292): disable_audio_route: exit
V/audio_hw_primary(  292): disable_snd_device: snd_device(122: vr-main-mic)
D/audio_route(  292): ++++ audio_route_update_mixer ==============
D/audio_route(  292): Setting mixer control: DEC2 Volume
D/audio_route(  292): Setting mixer control: value: 0
,D/audio_route(  292): Setting mixer control: SLIM TX7 MUX, value: 0
,D/audio_route(  292): Setting mixer control: AIF1_CAP Mixer SLIM TX7
D/audio_route(  292): Setting mixer control: value: 0
I/Zygote  (  327): Process 1315 exited due to signal (7)
D/audio_route(  292): Setting mixer control: DEC2 MUX, value: 0
,D/audio_route(  292): ------ audio_route_update_mixer ==============
,V/audio_hw_primary(  292): stop_input_stream: exit: status(0)
V/audio_hw_primary(  292): in_standby: exit:  status(0)
V/audio_hw_primary(  292): adev_close_input_stream
V/audio_hw_primary(  292): in_standby: enter
V/audio_hw_primary(  292): in_standby: exit:  status(0)
E/audio_hw_primary(  292): adev_close_input_stream, set jack_in to null
V/AudioPolicyManager(  292): releaseInput() exit
,I/SurfaceFlinger(  249): Disp[0] Orientation 0=>0
,E/installd(  295): eof
E/installd(  295): failed to read size
I/installd(  295): closing connection
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0

```
