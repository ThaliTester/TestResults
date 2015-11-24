#### Test 50388019b17f598_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  907): Recipient 2880
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2832
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Resuming delayed broadcast
--------- beginning of /dev/log/main
D/TetherSettings( 3212): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3212): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3212): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3212): Cust_ConnectToPC   : spcsc>false
D/        ( 3212): Cust_ConnectToPC   : IPT>true
D/        ( 3212): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3212): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3212): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3212): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3212): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3212): Cust_ConnectToPC   : spcsc>false
D/        ( 3212): Cust_ConnectToPC   : IPT>true
D/        ( 3212): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3212): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3212): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3212): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3212): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 3212): setISNotification
D/SmartNS_Utility( 3212): usb_cable_connect = 1
D/SmartNS_Utility( 3212): usb_denied = 0
I/SmartNS_PSService( 3212): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3212/1000)
D/SmartNS_Utility( 3212): usb_cable_connect = 1
D/SmartNS_Utility( 3212): usb_denied = 0
I/SmartNS_PSService( 3212): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
V/Tethering(  907): bSetPropertyMultiRAB:false
D/Process (  907): killProcessQuiet, pid=2894
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3212/1000)
I/ActivityManager(  907): Killing 2894:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2894
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1116): com.android.settings (true,33751552)
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e987a8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1116): com.android.settings 1 7 0 10
I/RemoteViews( 1116): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1116): com.android.settings 1 0 10
D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  907): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=3232 uid=9987 gids={49987}
I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42387bd8, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42387bd8, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f75288
W/SensorService(  907): Listener[1] = com.android.server.power.DisplayPowerController$10@4211dd80
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@42387bd8
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@42387bd8, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{425bd310 u0 ReceiverList{425fba30 907 system/1000/u0 local:42384ea8}}
D/NfcUiccLockService( 3232): -- To check whether previous opened channel needed to be closed ...
D/Process (  907): killProcessQuiet, pid=2923
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=3248 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  907): Killing 2923:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2923
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 3
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42387bd8, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41f75288
W/SensorService(  907): Listener[1] = com.android.server.power.DisplayPowerController$10@4211dd80
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@42387bd8
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/Process (  907): killProcessQuiet, pid=2983
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3260 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 2983:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2983
D/PMS     (  907): releaseWL(425c69f8): PARTIAL_WAKE_LOCK  GmailProviderProviderChangedBroadcastWakeLock 0x1 null
E/cutils-trace( 3233): Error opening trace file: No such file or directory (2)
E/YouTube ( 3260): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 3260): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3260): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 3260): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/CustomizationManager( 3233): ====startRecUseTime====
D/htc.customization.log.level( 3233):  is 
W/CustomizationLogLevel( 3233): Level value is invalid, use default level 2
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3260/10168)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3260): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/CustomizationManager( 3233):  Read ACC file spent 0.074 (s)
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3233): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3233): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3233): Parsing tag category name = system
I/CustomizationCIDLoader( 3233): Parsing tag category name = application
I/CustomizationCIDLoader( 3233): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3233): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3233): Parsing tag category name = AudioService
D/YouTube ( 3260): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
I/CustomizationCIDLoader( 3233): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3233): Parsing tag category name = Settings
D/CustomizationManager( 3233):  Read CID file spent 0.118 (s)
D/CustomizationManager( 3233):  All configurations done spent 0.118 (s)
W/HtcNativeFlag( 3233): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3233): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3233): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3233): Fail to get flag for type 'language', use default value: -1
D/YouTube ( 3260): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3260): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3233
D/PMS     (  907): acquireHCC(4234cc78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(4227b770): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x62cad198 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1110886552
D/PMS     (  907): acquireWL(4207cea8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1270): [onPause]
I/FeedProviderManager( 1270): onPause
I/FeedHostManager( 1270): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41be7278
I/SocialFeedProvider( 1270): +onPause
I/SocialFeedProvider( 1270): -onPause
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3302 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.htc.aurora
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 1329): Unsupported attribute readOnly
W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
W/asset   ( 3302): Copying FileAsset 0x5c897328 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/TrimMemoryManager( 1270): [trimMemory] 20
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
V/WebViewChromiumFactoryProvider( 3302): Binding Chromium to main looper Looper (main, tid 1) {41afa380}
I/LibraryLoader( 3302): Expected native library version number "",actual native library version number ""
I/chromium( 3302): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3302): Initializing chromium process, renderers=0
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/YouTube ( 3260): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
D/PMS     (  907): acquireWL(42876c08): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(4287ac90): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4240a118:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
D/PMS     (  907): releaseWL(4287ac90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3302): 1102118504: getState(). Returning 12
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
I/Adreno-EGL( 3302): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3302): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3302): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3302): Local Branch: 
I/Adreno-EGL( 3302): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3302): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3302):                  aa63bbd948f41d15fc72f585e
D/MediaRouterService(  907): Client com.google.android.youtube (pid 3260): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3260): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.youtube (3260/10168)
D/YouTube ( 3260): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3260): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448385975&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 3260): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3260): [NET] getaddrinfo-,err=8
D/libc    ( 3260): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3260): [NET] getaddrinfo-, 1
D/libc    ( 3260): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =6f4c +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
W/chromium( 3302): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3260): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3260): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/dalvikvm( 3302): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3302): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 3260): getSelectedRoute
D/YouTube ( 3260): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3260): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/YouTube ( 3260): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
W/dalvikvm( 3302): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3302): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3302): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/YouTube ( 3260): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3260/10168)
W/dalvikvm( 3302): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3302): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3302): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3302): CordovaWebView is running on device made by: HTC
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=96
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3260): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3260/10168)
W/BroadcastQueue(  907): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3260/10168)
D/AutoSetting( 1420): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3212): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3212): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3212): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3212): Cust_ConnectToPC   : spcsc>false
D/        ( 3212): Cust_ConnectToPC   : IPT>true
D/        ( 3212): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3212): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3212): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3212): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3212): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 3212): onReceive:android.intent.action.USER_PRESENT
D/AutoSetting( 1420): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/SmartNS_PSService( 3212): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3212): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3212):  defaultType:0
W/ContextImpl( 3212): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/Process (  907): killProcessQuiet, pid=3003
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3003:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3003
D/YouTube ( 3260): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3260): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3260): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
W/AwContents( 3302): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1270
W/ResourceType( 3302): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3302): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b412d8, mServedView=org.apache.cordova.engine.SystemWebView{41b07188 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1206): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1206): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1206): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Enable input method client, pid=3302
W/AwContents( 3302): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +366ms
I/GoogleConversionPing( 3260): Ping responded with response code 200
D/PMS     (  907): releaseWL(4207cea8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/AndroidProtocolHandler( 3302): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3302): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3302): Set native->JS mode to OnlineEventsBridgeMode
W/PackageManager(  907): Unable to load service info ResolveInfo{4260c0a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
D/jxcore_app_log( 3302): JniHelper::setJavaVM(0x415cd048), pthread_self() = 1658698464
D/JX-Cordova( 3302): jxcore cordova android initializing
W/jxcore-log( 3302): Initializing JXcore engine
W/jxcore-log( 3302): JXcore engine is ready
W/jxcore-log( 3302): Starting JXcore engine
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3362 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/browser ( 3362): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3362): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3362): Loading: swewebviewchromium
I/LibraryLoader( 3362): Time to load native libraries: 33 ms (timestamps 5800-5833)
I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3362): Initializing chromium process, renderers=9
I/LibraryLoader( 3362): Expected native library version number "",actual native library version number ""
I/chromium( 3362): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
W/jxcore-log( 3302): Platform android
W/jxcore-log( 3302): 
W/jxcore-log( 3302): Process ARCH arm
W/jxcore-log( 3302): 
I/jxcore-log( 3302): JXcore Cordova bridge is ready!
I/jxcore-log( 3302): 
W/jxcore-log( 3302): JXcore engine is started
E/jxcore-log( 3302): >> HTC-HTC Desire 820
E/jxcore-log( 3302): 
I/jxcore-log( 3302): Total memory 1964650496
I/jxcore-log( 3302): 
I/jxcore-log( 3302): Free memory 647176192
I/jxcore-log( 3302): 
I/jxcore-log( 3302): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3302): 
I/jxcore-log( 3302): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3302): 
I/jxcore-log( 3302): userPath [ 'www' ]
I/jxcore-log( 3302): 
I/jxcore-log( 3302): Size 720 1184
I/jxcore-log( 3302): 
I/jxcore-log( 3302): Screen Brightness 10
I/jxcore-log( 3302): 
E/jxcore-log( 3302): Dummy Error Log.
E/jxcore-log( 3302): 
I/Adreno-EGL( 3362): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3362): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3362): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3362): Local Branch: 
I/Adreno-EGL( 3362): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3362): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3362):                  aa63bbd948f41d15fc72f585e
D/Process (  907): killProcessQuiet, pid=3015
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3015:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
V/IccIntentReceiver( 1285): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1488): SIM state: ABSENT
I/SIMStateChangeReceiver( 1488): phoneType = 0
I/SIMStateChangeReceiver( 1488): remove notification
I/ActivityManager(  907): Recipient 3015
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3401 uid=10031 gids={50031, 3003, 5012}
I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3413 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
D/Process (  907): killProcessQuiet, pid=2422
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2422:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2422
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=40 [5][2][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 96
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
W/SystemReader( 2793): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2793): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2793): onReceive()
D/ExchangePolicystatus( 2793): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2793): onReceive(): else
D/Process (  907): killProcessQuiet, pid=3047
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1241): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Killing 3047:com.google.android.gm/u0a107 (adj 15): empty #17
W/WeatherUtility( 1116): can't get weather sync account
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3429 uid=10038 gids={50038}
D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
W/WeatherRequest( 1116): request cur loc, but there is no sys cur
W/AccTypeManager( 3413): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3413): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/Process (  907): killProcessQuiet, pid=3030
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3445 uid=10077 gids={50077}
I/ActivityManager(  907): Killing 3030:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/AccTypeManager( 3413): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  907): Recipient 3047
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 3445): Got a database change event
I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3457 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/Process (  907): killProcessQuiet, pid=3108
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3108:com.google.android.talk/u0a111 (adj 15): empty #17
E/ExternalAccountType( 3413): Unsupported attribute readOnly
W/AccTypeManager( 3413): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3413): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 3413): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/CalendarApplication( 3457): onCreate
D/ProviderChangeReceiver( 3457): ---------------------------------------------------
D/ProviderChangeReceiver( 3457): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3457): start to updateAlertNotification!
W/ContextImpl( 3187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
E/ExternalAccountType( 3413): Unsupported attribute readOnly
D/AlertService( 3457): No fired or scheduled alerts
D/HtcAlertUtils( 3457): -- cancelReminderNotification --
D/HtcAlertUtils( 3457): broadcastExistReminder!
D/GCM     ( 1408): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/Process (  907): killProcessQuiet, pid=3083
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3083:com.htc.backup/1000 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
I/AdsMeasurementBroadcastReceiver( 1223): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1223): Unauthorized to start the main service
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3474 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
I/ActivityManager(  907): Recipient 3030
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3489 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3474): can't get weather sync account
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherRequest( 3474): request cur loc, but there is no sys cur
W/Settings( 3474): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  907): Recipient 3108
D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b88dd0 +
I/Prism.WidgetManager( 1270): onLoadItems() +
I/jxcore-log( 3302): getBuffer is called!!!!
I/jxcore-log( 3302): 
I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 0 12 17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3083
I/MusicStore( 3489): Database version: 95
W/ContextImpl( 3489): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
W/ContextImpl( 3489): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3489): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3489): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3489): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3489, uid=10154, userID:0
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/MediaRouterService(  907): Client com.google.android.music (pid 3489): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3489): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
I/NetworkMonitor( 3489): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3489/10154)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1997/10021)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3510 uid=10026 gids={50026, 1028, 1015, 3003, 5012}
D/WIFI_ICON( 1116): WifiActivity: 0
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/MediaRouter( 3489): getSelectedRoute
I/NetworkMonitor( 3489): type=WIFI subType= reason=null isConnected=true
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3489/10154)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/Process (  907): killProcessQuiet, pid=3136
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3489, uid=10154, userID:0
I/ActivityManager(  907): Killing 3136:com.htc.backupreset/1000 (adj 15): empty #17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Recipient 3136
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
W/asset   ( 1270): Copying FileAsset 0x686bb788 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Prism.WidgetManager( 1270): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1270): onLoadItems() -
I/Prism.ItemManager( 1270): loadItems() com.htc.launcher.pageview.WidgetManager@41b88dd0 -
D/ACRA    ( 3510): ACRA is enabled for com.facebook.katana, intializing...
D/ACRA    ( 3510): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
D/ACRA    ( 3510): Looking for error files in /data/data/com.facebook.katana/app_minidumps
W/SystemClassLoaderAdder( 3510): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
V/DexLibLoader( 3510): Preparing secondary program dexes.
V/DexLibLoader( 3510): Loaded 4 raw lines of metadata.
V/DexLibLoader( 3510): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3510): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3510): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
V/DexLibLoader( 3510): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
W/DexLibLoader( 3510): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3510): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3510): Dex already copied
D/OdexVerifier( 3510): Odex verification is skipped.
V/DexLibLoader( 3510): Creating class loader
V/DexLibLoader( 3510): Finished creating class loader
V/DexLibLoader( 3510): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3510): Dex already copied
D/OdexVerifier( 3510): Odex verification is skipped.
V/DexLibLoader( 3510): Creating class loader
V/DexLibLoader( 3510): Finished creating class loader
V/DexLibLoader( 3510): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3510): Dex already copied
D/OdexVerifier( 3510): Odex verification is skipped.
V/DexLibLoader( 3510): Creating class loader
V/DexLibLoader( 3510): Finished creating class loader
V/DexLibLoader( 3510): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3510): Dex already copied
D/OdexVerifier( 3510): Odex verification is skipped.
V/DexLibLoader( 3510): Creating class loader
V/DexLibLoader( 3510): Finished creating class loader
V/DexLibLoader( 3510): Verifying classes from secondary dexes.
W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(4234cc78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  907): releaseHCC(4227b770): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
I/SensorManager(  907): mEventCount = 300
D/DexLibLoader( 3510): DexLibLoader.ensureDexLoaded took 82 ms
D/PhoneApp( 1241): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1241): -- N1 =0
D/PhoneApp( 1241): -- N2 =0
D/PhoneApp( 1241): -- N3 =0
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3524 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  907): sending alarm PendingIntent{42431918: PendingIntentRecord{42518cc8 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53375, Int=0
,I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3538 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3524): [7f0.1.] 30@-182547 -> 40@-182617
,D/Process (  907): killProcessQuiet, pid=3154
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  907): killProcessQuiet, pid=3171
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3154:com.htc.htccupd/u0a17 (adj 15): empty #17
I/ActivityManager(  907): Killing 3171:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3154
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3171
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=3200
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3200:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3200
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 5 times.
,W/dalvikvm( 3510): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3510): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3510): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3510): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3510): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3510): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3510): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/PMS     (  907): releaseWL(42876c08): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/dalvikvm( 3510): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3510): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 3510): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 3510): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3510/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3510): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3510): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,I/ActivityManager(  907): Killing 3232:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3232
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/PMS     (  907): acquireWL(42689f78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
I/ActivityManager(  907): Recipient 3232
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42678c68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(42689f78): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,D/GCM     ( 1408): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1408/10028)
D/PMS     (  907): releaseWL(42678c68): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1408/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1408/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1408/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
D/AutoSetting( 1420): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3559 uid=10078 gids={50078, 3003, 5012}
,D/AutoSetting( 1420): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1420/10053)
D/AutoSetting( 1420): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1420): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1420): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1420): service - handleMessage() setting current location null
D/AutoSetting( 1420): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1420): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1420/10053)
W/fb4a(:<default>):UserScope( 3510): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 3510): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):UserScope( 3510): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3510): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/MobileConnectivityChangeReceiver( 3559): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3559): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3559): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3559): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3577 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3248
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3248:com.android.smith/u0a163 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3559/10078)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3559/10078)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3559/10078)
,D/PMS     (  907): acquireWL(42420558): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
,D/PMS     (  907): acquireWL(423a5c48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(42420558): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,I/CheckinService( 1223): Preparing to send checkin request
,I/EventLogService( 1223): Accumulating logs since 1448385742504
,E/dalvikvm( 3510): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3510): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3510): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3510): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3510): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3510): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3510): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3510): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3510): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3510): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3510): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3510): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3510): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3510): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3510): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3510): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3510): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3510): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3592 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3260
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3260:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3260
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.youtube (pid 3260): Died!
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 9.921MB for 39954-byte allocation
,W/EventLogAggregator( 1223): Unknown tag: install_package_attempt
W/EventLogAggregator( 1223): Unknown tag: snet
,W/EventLogAggregator( 1223): Unknown tag: snet_gcore
,I/ActivityManager(  907): Recipient 3248
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 9.998MB for 79892-byte allocation
,W/ContextImpl( 3592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/GoogleHttpClient( 1223): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1223): Using GMS GoogleHttpClient
,W/GAV2    ( 3592): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3592): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/WifiService(  907): New client listening to asynchronous messages
I/dalvikvm-heap( 3510): Grow heap (frag case) to 10.068MB for 84664-byte allocation
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (1223/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (1223/10028)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [2][0][0]
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 10.094MB for 28144-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3592/10151)
,V/WebViewChromiumFactoryProvider( 3592): Binding Chromium to main looper Looper (main, tid 1) {41afcbc8}
,I/LibraryLoader( 3592): Expected native library version number "",actual native library version number ""
,I/chromium( 3592): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3592): Initializing chromium process, renderers=0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/GLSUser ( 1408): GoogleAccountDataService.getToken()
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4254c570): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(425ab2f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
E/AudioManagerAndroid( 3592): BLUETOOTH permission is missing!
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -55 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 168
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1165): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/PMS     (  907): releaseWL(425ab2f0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3592): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3592): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3592): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3592): Local Branch: 
I/Adreno-EGL( 3592): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3592): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3592):                  aa63bbd948f41d15fc72f585e
,I/GoogleHttpClient( 1408): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1408): Using GMS GoogleHttpClient
,W/GLSActivity( 1408): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1408): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1408): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/dalvikvm-heap( 3510): Grow heap (frag case) to 10.282MB for 75760-byte allocation
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/NSApplication( 3592): Starting up...
I/NotificationStore( 1408): System rebooted after Notification storage file was last written
,I/NotificationStore( 1408): Deleting the file
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3510/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3592/10151)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4269f970 u0 ReceiverList{4269ab20 3510 com.facebook.katana/10026/u0 remote:4266a700}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4269f970 u0 ReceiverList{4269ab20 3510 com.facebook.katana/10026/u0 remote:4266a700}}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3592/10151)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425fa220 u0 ReceiverList{425fa1c0 3510 com.facebook.katana/10026/u0 remote:4252ddf8}}
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3631 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3212
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3212:com.android.settings/1000 (adj 15): empty #17
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3510/10026)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3510/10026)
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
,W/CheckinRequestBuilder( 1223): awaiting user notification for token
I/ActivityManager(  907): Recipient 3212
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3510/10026)
D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1116): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e21b58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/PMS     (  907): acquireWL(42360460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1502 10028 null
,I/RemoteViews.Performance( 1116): com.google.android.gms 3 7 3 12
D/PMS     (  907): releaseWL(42360460): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/GCoreFlp( 1502): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(4267c680): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1502 10028 null
D/PMS     (  907): releaseWL(4267c680): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3648 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 3648): install
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/MultiDex( 3648): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,W/ContextImpl( 3510): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/MultiDex( 3648): loading existing secondary dex files
,I/MultiDex( 3648): load found 1 secondary dex files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3510): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/MultiDex( 3648): install done
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/PMS     (  907): acquireWL(428df950): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3631 10160 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
,I/ProviderInstaller( 3648): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3631/10160)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42310818): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3631 10160 null
D/PMS     (  907): releaseWL(428df950): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,D/AlertReceiver( 3457): beginStartingService
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(427f49e0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3457 10013 null
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: survey data missing!
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1165): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(42310818): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/AlertService( 3457): start to updateAlertNotification!
,D/AlertService( 3457): No fired or scheduled alerts
,D/HtcAlertUtils( 3457): -- cancelReminderNotification --
,D/HtcAlertUtils( 3457): broadcastExistReminder!
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3457): stopSelfResult true
D/PMS     (  907): acquireWL(4263e150): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1223 10028 null
D/PMS     (  907): releaseWL(427f49e0): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,D/Process (  907): killProcessQuiet, pid=3362
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(4263e150): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/ActivityManager(  907): Killing 3362:com.htc.sense.browser/u0a12 (adj 15): empty #17
,W/WeatherUtility( 3474): can't get weather sync account
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3677 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 1116): request cur loc, but there is no sys cur
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3362
,W/WeatherRequest( 3474): request cur loc, but there is no sys cur
,W/Settings( 3474): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 0 7 17
,D/PMS     (  907): acquireWL(428bdf70): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3677 10070 null
,D/PMS     (  907): acquireWL(42878328): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3677 10070 null
,D/PMS     (  907): releaseWL(428bdf70): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3677): update TASK shortcut>
I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3692 uid=10090 gids={50090, 3003, 5012, 1028}
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/TodoTaskNotifyService( 3677): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 3677): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/WorldClock.Global( 3692): isHtcDevice = true
,W/NotifyReceiver( 3677): stopSelfResult true
D/PMS     (  907): releaseWL(42878328): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/ContextImpl( 3187): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/WorldClock.Global( 3692): isHtcDevice = true
,I/WorldClock.AlarmUtils( 3692): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3692): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3692): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1116): receive(android.intent.action.ALARM_CHANGED,1,false)
I/ActivityManager(  907): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3709 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/Adreno-EGL( 3648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3648): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3648): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3648): Local Branch: 
I/Adreno-EGL( 3648): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3648): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3648):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 3648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3648): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3648): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3648): Local Branch: 
I/Adreno-EGL( 3648): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3648): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3648):                  aa63bbd948f41d15fc72f585e
,D/Process (  907): killProcessQuiet, pid=3401
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  907): Killing 3401:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/TimeService( 3709): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448385980117
,D/Process (  907): killProcessQuiet, pid=3413
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3413:com.htc.contacts/u0a41 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (3648/10028)
,I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3726 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/ActivityManager(  907): Recipient 3401
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DemoRecovery.RestoreReceiver( 3726): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3726): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3726): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(4260a408): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3677 10070 null
,D/PMS     (  907): acquireWL(42609d40): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3677 10070 null
,D/PMS     (  907): releaseWL(4260a408): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3677): update TASK shortcut>
I/TodoTaskNotifyService( 3677): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(42609d40): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,W/NotifyReceiver( 3677): stopSelfResult true
,D/Process (  907): killProcessQuiet, pid=3429
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3743 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  907): Killing 3429:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3429
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3413
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3755 uid=10081 gids={50081, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3489
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Process (  907): killProcessQuiet, pid=3445
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1223): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1223): Unauthorized to start the main service
I/ActivityManager(  907): Killing 3489:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Killing 3445:com.htc.mms.backupagent/u0a77 (adj 15): empty #18
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3767 uid=10038 gids={50038}
,I/ActivityManager(  907): Recipient 3445
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3780 uid=10077 gids={50077}
,D/Process (  907): killProcessQuiet, pid=3510
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/Adreno-EGL( 3648): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3648): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3648): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3648): Local Branch: 
I/Adreno-EGL( 3648): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3648): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3648):                  aa63bbd948f41d15fc72f585e
I/ActivityManager(  907): Killing 3510:com.facebook.katana/u0a26 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3489
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SMSBackup( 3780): Got a database change event
D/MediaRouterService(  907): Client com.google.android.music (pid 3489): Died!
,I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3792 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  907): killProcessQuiet, pid=3524
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3524:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3524
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3792): create image Cache, size: 31457280.
I/ImageRamCache( 3792): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3792): create image Cache, size: 12582912.
,I/FeedSettings( 3792): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3792): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3792): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3792): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3792): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3792): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3792): [custom highlight] onReceive
,D/CustomHighlightService( 3792): [custom highlight] onHandleIntent
,D/NewsDB  ( 3792): set custom highlight []
I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3792): [custom highlight] set tags 
,D/Process (  907): killProcessQuiet, pid=3538
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3538:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1408): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Recipient 3538
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Recipient 3510
D/WifiService(  907): Client connection lost with reason: 4
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(42325a48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1502 10028 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(420337e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1502 10028 null
,D/MessagingShortcutReceiver( 2793): keep hiding shortcut bubble
D/MessagingShortcut( 2793): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2793): After query: 0
D/MessagingShortcut( 2793): mPresentUnreadCount: -1
D/MessagingShortcut( 2793): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2793): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/PMS     (  907): releaseWL(42325a48): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/PMS     (  907): releaseWL(420337e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] reorderNotification, total:0
D/DotMatrix( 1559): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TodoTaskshortcut( 3677): update TASK shortcut>
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1241): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3810 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3559
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1408): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  907): Killing 3559:com.google.android.setupwizard/u0a78 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3559
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3824 uid=10091 gids={50091, 3003, 5012}
,D/MtpReceiver( 1997): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 1997): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 1997): [MTP][handleMessage][startService]
,D/MtpReceiver( 1997): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 1997): [MTP][handleMessage]-
,D/MtpService( 1997): [MTP] startForeground
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3837 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews( 1116): com.android.providers.media (false,0)
D/MtpService( 1997): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 1997): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews.Performance( 1116): com.android.providers.media 2 1 10
I/RemoteViews( 1116): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1116): com.android.providers.media 2 2 15
,D/PMS     (  907): acquireWL(423eda88): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3631 10160 null
D/MtpService( 1997): [isMtpConnected] connected: true
,D/MessagingNotification( 2793): New incoming message, can't cancel notification now
,D/MessagingNotification( 2793): newMsgCnt: 0, false
,D/MdScBoot( 3810): [988.1.] 40@-182617
,I/dalvikvm-heap( 3631): Grow heap (frag case) to 15.217MB for 1821008-byte allocation
,D/Process (  907): killProcessQuiet, pid=3577
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3577:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3577
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/SyncApplication( 3837): Loading default preferences
,W/Resources( 3837): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/PMS     (  907): releaseWL(423eda88): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/Process (  907): killProcessQuiet, pid=3592
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3592:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,D/WifiService(  907): New client listening to asynchronous messages,
,I/ActivityManager(  907): Recipient 3592
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3837): Overriding preferences with custom values
,D/SyncApplication( 3837): Updating preferences succeeded
,E/SyncApplication( 3837): Application created.
D/VolumeInfo( 3837): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3837): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3837): Found 0 mount point(s)
,V/VolumeInfo( 3837): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3837): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3837): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3837): Can not create volume ID for unmounted volume null
,W/Settings( 3648): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CalendarDefines( 3837): getNewCalendarAuthority()...
,D/SyncApplication( 3837): enableAppOperation()+
,D/SyncApplication( 3837): enableAppOperation()-
,D/HTCUtilities( 3837): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3837, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3837, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3837): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3837): isNeorSinged() return false
D/CDMountReceiver( 3837): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3837): USB connected to PC
,D/FOTAReceiver( 3837): onReceive() enter 
,D/FOTAReceiver( 3837): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/CheckinTask( 1223): Sending checkin request (9034 bytes)
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3859 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3457
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3457:com.htc.calendar/u0a13 (adj 15): empty #17
,W/ActivityThread( 1223): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/ActivityManager(  907): Recipient 3457
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1223): [NET] getaddrinfo-, 1
,D/libc    ( 1223): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =c363 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 291
D/libc    (  363): [NET]res_nsend:resplen=84
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1223): [NET] getaddrinfo_proxy-, success
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42518310 mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1100
,W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 8(ms)
,D/HtcFingerPrintQuickLaunchProvider( 3859): -onCreate()
,V/Settings:HtcSettingsApplication( 3859): [3859/3859] onCreate()
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  907): Sending off request.
D/TetherSettings( 3859): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3859): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3859): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3859): Cust_ConnectToPC   : spcsc>false
D/        ( 3859): Cust_ConnectToPC   : IPT>true
D/        ( 3859): Cust_ConnectToPC   : Singel_USB>false
,D/libc    ( 1223): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1223): [NET] getaddrinfo-,err=8
D/BluetoothAdapterState( 1588): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1588): Setting state to 13
I/BluetoothAdapterState( 1588): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1588): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 1588): onBluetoothDisable()
I/BluetoothAdapterState( 1588): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1588): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 1588): adapterPropertyChangedCallback with type:7 len:4
,I/bt-btm  ( 1588): BTM_SetDiscoverability
I/bt-btm  ( 1588): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1588): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1588): br_edr_supported=0x0
W/Settings( 3859): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/bt-btm  ( 1588): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1588): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1588): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1588): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1588): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1588): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1588): BTM_SetConnectability
I/bt-btm  ( 1588): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1588): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1588): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 1588): Scan Mode:20
E/BTIF_CORE( 1588): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1588): HAL bt_hal_cbacks->wake_state_changed_cb
D/BluetoothAdapterState( 1588): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1588): BTA_JvDeleteRecord
I/bt-btif ( 1588): BTA_JvRfcommStopServer
D/bt-btm  ( 1588): BTM_FreeSCN 
I/bt-btif ( 1588): BTA_JvDeleteRecord
I/bt-btif ( 1588): BTA_JvRfcommStopServer
D/bt-btm  ( 1588): BTM_FreeSCN 
I/bt-btif ( 1588): BTA_JvDeleteRecord
I/bt-btif ( 1588): BTA_JvRfcommStopServer
D/bt-btm  ( 1588): BTM_FreeSCN 
I/bt-btif ( 1588): BTA_JvDeleteRecord
I/bt-btif ( 1588): BTA_JvRfcommStopServer
D/bt-btm  ( 1588): BTM_FreeSCN 
I/bt-btif ( 1588): BTA_JvDeleteRecord
I/bt-btif ( 1588): BTA_JvRfcommStopServer
D/bt-btm  ( 1588): BTM_FreeSCN 
I/bt-btif ( 1588): BTA_JvDeleteRecord
I/bt-btif ( 1588): BTA_JvRfcommStopServer
D/bt-btm  ( 1588): BTM_FreeSCN 
,E/BtOppRfcommListener( 1588): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:15
V/BluetoothSapService( 1588): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1588): bta_jv_rfcomm_stop_server
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/bt-btm  ( 1588): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1588): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1588): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1588): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1588): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1588): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1588): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1588): bta_jv_rfcomm_stop_server
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
I/bt-btm  ( 1588): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1588): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1588): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1588): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1588): Write Extended Inquiry Response to controller
I/bt-btm  ( 1588): Write Extended Inquiry Response to controller
I/bt-btm  ( 1588): Write Extended Inquiry Response to controller
I/bt-btm  ( 1588): Write Extended Inquiry Response to controller
I/bt-btm  ( 1588): BTM_SetDiscoverability
I/bt-btm  ( 1588): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1588): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1588): br_edr_supported=0x0
I/bt-btm  ( 1588): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1588): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1588): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1588): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1588): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1588): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1588): BTM_SetConnectability
I/bt-btm  ( 1588): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1588): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1588): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1588): BTM_IsInquiryActive
I/bt-btm  ( 1588): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1588): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/BluetoothManagerService(  907): Bluetooth State Change Intent: 12 -> 13
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1588): BTM_FreeSCN 
I/bt-btm  ( 1588): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1588): BTM_FreeSCN 
I/bt-btm  ( 1588): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1588): AVRC_Close handle:0
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1588): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1588): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1588): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1588): GATT_Deregister gatt_if=3
I/bt-att  ( 1588): GATT_Deregister gatt_if=4
,D/BluetoothRemoteDevices( 1588): Wake lock Aquired
D/PMS     (  907): acquireWL(424dced8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1588 1002 null
I/IntentController( 1116): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 1588): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1588): ***********state = 13
D/BluetoothMasReceiver( 1588): Bluetooth STATE CHANGED to 13
D/WifiManager( 3302): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
V/BluetoothSapReceiver( 1588): SapReceiver onReceive 
V/BluetoothSapReceiver( 1588): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1588):  Bluetooth Adapter state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1794): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b1d5d0
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1794): onDeInitialized
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1794): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1794): getNotificationManager
V/BluetoothSapReceiver( 1588): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1349
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 1(ms)
D/WifiService(  907): setWifiEnabled: false pid=3302, uid=10355
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
D/WifiService(  907): New client listening to asynchronous messages
V/BluetoothPbapService( 1588): Pbap Service closeService in
D/Process (  907): killProcessQuiet, pid=3474
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/PMS     (  907): acquireWL(4266c980): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3859 1000 null
W/ContextImpl( 3859): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3877 uid=10037 gids={50037, 3002, 3001}
I/ActivityManager(  907): Killing 3474:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,V/BluetoothPbapService( 1588): successfully stopped pbap service
V/BluetoothPbapService( 1588): Pbap Service closeService out
V/BluetoothSapService( 1588): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1588): state: 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onScreenOff.
D/BluetoothAdapter( 1588): 1102141328: getState(). Returning 13
V/BluetoothSapService( 1588): Stopping SAP server process
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1794): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1794):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1794): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1794): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1794): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1794):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1794): deinit: 0
D/BluetoothManagerService(  907): Message: MESSAGE_UNREGISTER_ADAPTER
D/BluetoothManagerService(  907): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@422f4378:true
V/BluetoothSapService( 1588): Sap Service closeSapService in
V/BluetoothSapService( 1588): Close listen Socket : 
V/BluetoothSapService( 1588): Close rfcomm Socket : 
V/BluetoothSapService( 1588): Close sapd  Socket : 
V/BluetoothSapReceiver( 1588): BluetoothSapReceiver deinit
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1794): disableBatteryAlarm: null
V/BluetoothSapService( 1588): successfully stopped Sap service
V/BluetoothSapService( 1588): Sap Service closeSapService out
I/BtOppRfcommListener( 1588): stopping Accept Thread
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1794): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1794): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1794): init: null
I/BtOppRfcommListener( 1588): BluetoothSocket listen thread finished
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1794): setPendingRequestAlarm: false, mContext = null, null
I/jxcore-log( 3302): ****TEST TOOK:  5115  ms ****
I/jxcore-log( 3302): 
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1794): Exit IdleState
V/BluetoothPbapService( 1588): Pbap Service onDestroy
I/jxcore-log( 3302): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3302): 
V/BluetoothPbapService( 1588): Pbap Service closeService in
V/BluetoothPbapService( 1588): Pbap Service closeService out
V/BluetoothSapService( 1588): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b4e3b8
D/WirelessDisplayService(  907): getMirrorDisplayStatus:falsecurState:1
V/BluetoothSapService( 1588): Sap Service closeSapService in
V/BluetoothSapService( 1588): Close listen Socket : 
V/BluetoothSapService( 1588): Close rfcomm Socket : 
V/BluetoothSapService( 1588): Close sapd  Socket : 
D/WifiPerfLock(  907): release()
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
V/BluetoothSapService( 1588): Sap Service closeSapService out
D/PMS     (  907): releaseWL(4266c980): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  907): acquireWL(42861d68): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3859 1000 null
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
V/BluetoothSapService( 1588): ***onDestroyed***
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
I/QuickSettingBluetooth( 1116): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1116): removeIcon slot=bluetooth index=12 viewIndex=0
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4245f010:true
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
I/ActivityManager(  907): Recipient 3474
D/PMS     (  907): acquireWL(425bd9f8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/LocationAgent( 3859): new LocationAgent instance!!
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
D/HtcTagManager( 3859): HtcTagManager construction complete
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=19639 mDataStallAlarmIntent=PendingIntent{42526820: PendingIntentRecord{425af750 android broadcastIntent}}
D/WifiNative-wlan0(  907):    returned null
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  907):    returned null
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WifiP2pService(  907): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1165): Power_Mode_Type mode = 0
I/wpa_supplicant( 1165): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1165): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1165): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  907):    returned true
D/BluetoothAdapter( 3859): 1102258344: getState(). Returning 13
D/HtcBtWidget_BTWidgetProvider( 3877): onBTStateChanged() for widget: 
D/BluetoothInputDevice( 3859): BluetoothInputDevice()
V/AudioService(  907): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  907):     Client/Owner: Client
V/AudioService(  907):     GroupId: 
V/AudioService(  907):     Passphrase: 
V/AudioService(  907):     SessionId: 0
V/AudioService(  907):     IP Address: }
D/HtcEffectManagerBase(  907): onEventChanged id=5 status=false
D/HtcEffectManager(  907): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  907): convertEffect before=902
D/WifiP2pService(  907): P2pDisablingState
D/WifiP2pService(  907): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/WifiP2pService(  907): p2p socket connection lost
D/ConnectivityService(  907): Provision feature enable=false
D/WifiP2pService(  907): P2pDisabledState
D/WifiP2pService(  907): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDisplayController(  907): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  907): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  907): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  907): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  907): P2pDisabledState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  907):  WFD CtrlPort: 0
D/WifiP2pService(  907):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  907):  WFD CtrlPort: 0
D/WifiP2pService(  907):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  907): updateConnection
I/WifiDisplayController(  907): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  907): updateConnection enter step 4
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiDisplayController(  907): Failed to set WFD info with reason 2.
D/HtcEffectManager(  907): convertEffect after=902
D/HtcBtWidget_BTWidgetProvider( 3877): updateWidget(context) for widget: 
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/WifiNative-p2p0(  907): doBoolean: TERMINATE
D/UsbnetStateTracker(  907): isAvailable+-
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
W/WifiHW  (  907): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1165): Supplicant Terminat @ wpa_supplicant_deinit function
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/wpa_supplicant( 1165): TDLS: Tear down peers
I/wpa_supplicant( 1165): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 7
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-p2p0(  907):    returned true
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1116): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothAdapter( 3859): 1102258344: getState(). Returning 13
D/BluetoothInputDevice( 3859): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3859): Bluetooth service connected
W/BluetoothInputDevice( 3859): Proxy not attached to service
D/BluetoothPan( 3859): BluetoothPan()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 8
D/BluetoothAdapter( 3859): 1102258344: getState(). Returning 13
D/BluetoothPan( 3859): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3859): Bluetooth service connected
D/BluetoothMap( 3859): Create BluetoothMap proxy object
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 9
E/BluetoothMap( 3859): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WIFI_ICON( 1116): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3859): BluetoothSap() call bindService
D/BluetoothManagerService(  907): Registered receivers: 10
E/BluetoothFtpService:RfcommSocketAcceptThread( 1588): Shutdown
D/BluetoothPbap( 3859): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 11
D/BluetoothAdapter( 3859): 1102258344: getState(). Returning 13
D/BluetoothPbap( 3859): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3859): Bluetooth service connected
D/LocalBluetoothProfileManager( 3859): LocalBluetoothProfileManager construction complete
D/BluetoothMasReceiver( 1588): Bluetooth STATE CHANGED to 13
D/DockEventReceiver( 3859): finishStartingService: stopping service
W/ContextImpl( 3859): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1165): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1165): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/wpa_supplicant( 1165): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1165): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8b52bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1165):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1165): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1165): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1165): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1165): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2462
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1794): Received state change = 13
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/TetherSettings( 3859): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3859): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3859): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3859): Cust_ConnectToPC   : spcsc>false
D/        ( 3859): Cust_ConnectToPC   : IPT>true
D/        ( 3859): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3859): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1794): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b1d5d0
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): onDestroy() called...
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1794): deinitLeServices: null
E/SmartNS_Utility( 3859): hasRemovableStorageSlot: true
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/SmartNS_Utility( 3859): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3859): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3859): usb_cable_connect = 1
D/SmartNS_Utility( 3859): usb_denied = 0
D/libc    (  363): [NET] entry_id:5   entry:0xb7ed38e0  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb7ed8818  removed 
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/PMS     (  907): acquireWL(4265edb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1408 10028 null
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/libc    (  363): [NET] entry_id:4   entry:0xb7ed82d8  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb7ed8108  removed 
D/libc    (  363): [NET] entry_id:7   entry:0xb7ed8718  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb7ed81d0  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb7ed8410  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
E/CheckinTask( 1223): Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.ConnectException: failed to connect to android.clients.google.com/216.58.209.46 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
W/GoogleHttpClient( 1223): Unable to close GMS GoogleHttpClient
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1408/10028)
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(428cd2e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
I/SmartNS_NSReceiver( 3859): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3859): USB = true hasTethered = false isNSOpening: false
I/QuickSettingWifi( 1116): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
I//system/bin/ip(  363): RTNETLINK answers: No such process
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/PMS     (  907): acquireWL(428d53b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1408 10028 null
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1408/10028)
D/PMS     (  907): releaseWL(42861d68): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/PMS     (  907): releaseWL(428cd2e0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/PSReceiver( 3859): onReceive:com.htc.intent.action.USB_CONNECT2PC
E/WifiStateMachine(  907): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  907): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  907): New client listening to asynchronous messages
D/PMS     (  907): releaseWL(428d53b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
W/ContextImpl( 3859): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): releaseWL(4265edb8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1408/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1408/10028)
,D/ConnectivityService(  907): mActiveDefaultNetwork: -1
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/SmartNS_PSService( 3859): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3859): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3859):  defaultType:0
,I/SmartNS_PSService( 3859): fail notificaiton:false
,D/SmartNS_Utility( 3859): usb_cable_connect = 1
,D/SmartNS_Utility( 3859): usb_denied = 0
,I/SmartNS_PSService( 3859): usb notificaiton:true
,D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3859/1000)
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3903 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3692
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/bt-btif ( 1588): ag scb idx 1 not allocated
W/bt-btif ( 1588): ag scb idx 2 not allocated
E/bt-btif ( 1588): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1588): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1588): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1588): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1588): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1588): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1588): L2CAP - PSM: 0x0017 not found for deregistration
I/ActivityManager(  907): Killing 3692:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,D/SmartNS_Utility( 3859): usb_cable_connect = 1
D/SmartNS_Utility( 3859): usb_denied = 0
,I/SmartNS_PSService( 3859): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1116): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1116): com.android.settings 9 1 10
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
I/ActivityManager(  907): Recipient 3692
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3859/1000)
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/SmartNS_Utility( 3859): usb_cable_connect = 1
,D/SmartNS_Utility( 3859): usb_denied = 0
,D/DotMatrix( 1559): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1116): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1116): com.android.settings 2 1 10
,E/bt_userial_mct( 1588): userial_close userial_thread_created userial_running is 1 
,I/SmartNS_PSService( 3859): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3859): USB Plugged, Set USBPlugged=  truePSenabled:false
,D/Process (  907): killProcessQuiet, pid=3709
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3709:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3709
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(423a5c48): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1223): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b8d2a0 that was originally bound here
E/ActivityThread( 1223): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b8d2a0 that was originally bound here
E/ActivityThread( 1223): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1223): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1223): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1223): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1223): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1223): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1223): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1223): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1223): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1223): 	at bks.a(SourceFile:298)
E/ActivityThread( 1223): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1223): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1223): 	at java.lang.Thread.run(Thread.java:864)
,I/SocialFeedProvider( 1270): +disConnect socialManager
,I/SocialFeedProvider( 1270): disconnect socialManager
,I/SocialFeedProvider( 1270): -disConnect socialManager
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1270): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1270): com.google.android.googlequicksearchbox 1 0 5
,W/WeatherUtility( 3903): can't get weather sync account
,D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/ActivityManager(  907): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,I/ActivityManager(  907): Resuming delayed broadcast
I/RemoteViews( 1270): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1270): pl.k2.droidoaudioteka 1 0 8
E/wpa_supplicant( 1165): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1165): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 1165): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/SMSBackup( 3780): Got a database change event
D/PMS     (  907): acquireWL(428cce98): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,W/WeatherRequest( 3903): request cur loc, but there is no sys cur
,W/Settings( 3903): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  907): releaseWL(428cce98): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  907): acquireWL(42841d50): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1488 10014 null
,I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
D/AppWidgetHostView( 1270): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1270): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1270): com.htc.widget.weatherclock 1 5 17
,D/PMS     (  907): releaseWL(42841d50): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onDataStallAlarm: ignore, tag=19639 expecting 19640
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1165): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1165): nl80211: Unsubscribe mgmt frames handle 0xb8b53718 (mode change)
I/wpa_supplicant( 1165): htc_wext_command_deinit +
I/wpa_supplicant( 1165): htc_wext_command_deinit -
E/wpa_supplicant( 1165): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1165): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1165): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1165): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1165): TDLS: Tear down peers
I/wpa_supplicant( 1165): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1165): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1165): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1165): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1165): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1165): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1165): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1165): send_and_recv error 0 - cmd 18
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  907): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0x62b39640
,I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0x62b39a10
W/WifiHW  (  907): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  907): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  907): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  907):    returned false
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  907): WIFI Trun OFF
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,I/IntentController( 1116): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
,E/WifiStateMachine(  907): [MLHD] Error! unhandled message 6 { when=-14ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1116): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  907): acquireWL(42638640): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
,E/cutils-trace( 3898): Error opening trace file: No such file or directory (2)
,D/WISPrService( 3859): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3859): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
,V/AlarmManager(  907): sending alarm PendingIntent{424be678: PendingIntentRecord{420c6918 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1448385981472, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
,I/ActivityManager(  907): Resuming delayed broadcast
,I/QuickSettingWifi( 1116): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
I/bt-btif ( 1588): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1588): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1588): Received stop request...Stopping profile...
V/AlarmManager(  907): sending alarm PendingIntent{4244f888: PendingIntentRecord{42498238 com.google.android.gms startService}}, i=null, t=0, cnt=17056, w=84918423, Int=84918423
I/ActivityManager(  907): Resuming delayed broadcast
,D/BluetoothHeadset(  907): Proxy object disconnected
D/BluetoothHeadset( 1241): Proxy object disconnected
,D/BluetoothHeadset( 1241): Proxy object disconnected
D/BluetoothHeadset( 1116): Proxy object disconnected
I/QuickSettingMiniLite( 1116): btListener.disconnect:HEADSET
D/BluetoothAdapterState( 1588): Stopping profile services that were post enabled
,D/BluetoothPhoneService( 1241): BluetoothHeadset onServiceDisconnected
D/A2dpService( 1588): Received stop request...Stopping profile...
D/A2dpStateMachine( 1588): doQuit
,D/A2dpStateMachine( 1588): Exit Disconnected: -1
,D/BluetoothA2dp(  907): Proxy object disconnected
,D/HidService( 1588): Received stop request...Stopping profile...
,D/HealthService( 1588): Received stop request...Stopping profile...
D/PanService( 1588): Received stop request...Stopping profile...
,D/PanService( 1588): stop
,D/PanService( 1588): stop: mTetherAc send disconnect
,D/BluetoothTethering(  907): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  907): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  907): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  907): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService( 1588): Profile still running: com.android.bluetooth.hdp.HealthService
,D/BtGatt.DebugUtils( 1588): handleDebugAction() action=null
D/BtGatt.GattService( 1588): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1588): stop()
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1223/10028)
W/BluetoothHeadsetServiceJni( 1588): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1588): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1588): Profile still running: com.android.bluetooth.hdp.HealthService
D/A2dpStateMachine( 1588): cleanup
D/Avrcp   ( 1588): Unregistering previous receiver
D/BluetoothAdapterService( 1588): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1588): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1588): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1588): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1588): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1588): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1588): Cleaning up Bluetooth Health object
D/PanService( 1588): CMD_CHANNEL_DISCONNECTED
D/PanService( 1588): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1588): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1588): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1588): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1588): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1588): Setting state to 10
I/BluetoothAdapterState( 1588): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1588): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 1588): Entering OffState
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  907): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothInputDevice( 3859): onBluetoothStateChange: up=false
E/BluetoothInputDevice( 3859): 
E/BluetoothInputDevice( 3859): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41b40738
E/BluetoothInputDevice( 3859): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3859): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3859): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3859): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3859): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3859): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3859): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=false
I/AdsMeasurementBroadcastReceiver( 1223): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1223): Unauthorized to start the main service
D/SnetService( 1223): snet destroyed
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=false
D/BluetoothMap( 3859): onBluetoothStateChange: up=false
E/BluetoothMap( 3859): 
E/BluetoothMap( 3859): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41b432f0
E/BluetoothMap( 3859): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3859): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3859): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3859): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3859): 	at android.bluetooth.IBluetoothStateChange,Callback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3859): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3859): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset( 1116): onBluetoothStateChange: up=false
D/BluetoothSap( 3859): onBluetoothStateChange on: false
D/BluetoothHeadset(  907): onBluetoothStateChange: up=false
E/BluetoothPan( 3859): 
E/BluetoothPan( 3859): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41b41f70
E/BluetoothPan( 3859): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3859): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3859): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3859): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3859): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3859): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3859): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothA2dp(  907): onBluetoothStateChange: up=false
D/BluetoothPbap( 3859): onBluetoothStateChange: up=false
E/BluetoothPbap( 3859): 
E/BluetoothPbap( 3859): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41b49408
E/BluetoothPbap( 3859): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3859): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3859): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3859): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3859): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3859): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3859): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1502): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c522c8
D/BluetoothAdapter( 1502): onBluetoothServiceDown: done
D/BluetoothAdapter( 1116): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ed4ad0
D/BluetoothAdapter( 1116): onBluetoothServiceDown: done
D/BluetoothAdapter(  907): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42518310
D/BluetoothAdapter(  907): onBluetoothServiceDown: done
D/BluetoothAdapter( 1241): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d9a718
D/BluetoothAdapter( 1241): onBluetoothServiceDown: done
D/BluetoothAdapter( 1253): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bcdd30
D/BluetoothAdapter( 1253): onBluetoothServiceDown: done
D/BluetoothAdapter( 1794): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b1dea0
D/BluetoothAdapter( 1794): onBluetoothServiceDown: done
D/BluetoothAdapter( 1588): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b13c00
D/BluetoothDevice( 1588): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 1588): onBluetoothServiceDown: done
D/BluetoothAdapter( 3302): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b108d0
D/BluetoothAdapter( 3302): onBluetoothServiceDown: done
D/BluetoothAdapter( 3859): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b32b10
D/BluetoothAdapter( 3859): onBluetoothServiceDown: done
D/BluetoothAdapter( 1838): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bf87e0
D/BluetoothAdapter( 1838): onBluetoothServiceDown: done
D/BluetoothManagerService(  907): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42518310 mBinding = false
D/CustomizationManager( 3898): ====startRecUseTime====
,D/htc.customization.log.level( 3898):  is 
W/CustomizationLogLevel( 3898): Level value is invalid, use default level 2
D/BluetoothManagerService(  907): Sending unbind request.
,D/BluetoothManagerService(  907): Bluetooth State Change Intent: 13 -> 10
,D/PackageBroadcastService( 1223): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/LocalBluetoothProfileManager( 3859): setBluetoothStateOff
I/IntentController( 1116): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/HtcTagManager( 3859): stopProxy
W/BluetoothEventManager( 3859): unregister mProfileBroadcastReceiver fail
,D/NfcHandover( 1253): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/BluetoothAdapterService( 1588): Cleaning up adapter native....
,I/bt-btif ( 1588): HAL bt_hal_cbacks->thread_evt_cb
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  907): releaseWL(424dced8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/BluetoothAdapterService( 1588): Done cleaning up adapter native....
D/BluetoothAdapterService(1102123152)( 1588): ****onDestroy()********
D/BtGatt.GattService( 1588): cleanup()
W/bt-btif ( 1588): GATTC Module not enabled/already disabled
D/TetherPref( 3859): persistRestoreBluetoothState false
W/bt-btif ( 1588): GATTS Module not enabled/already disabled
,D/BluetoothMasReceiver( 1588): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 1588): onDestroy: mIsEmailEnabled: true
D/PMS     (  907): acquireWL(422a7858): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3859 1000 null
W/ContextImpl( 3859): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/HtcBtWidget_BTWidgetProvider( 3877): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3877): updateWidget(context) for widget: 
,D/DockEventReceiver( 3859): finishStartingService: stopping service
D/PMS     (  907): releaseWL(422a7858): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  907): acquireWL(41f53688): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3859 1000 null
D/PMS     (  907): releaseWL(41f53688): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 1588): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1794): Received state change = 10
D/PMS     (  907): acquireWL(421701f8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,W/BluetoothHeadset( 1116): Proxy not attached to service
,I/QuickSettingMiniLite( 1116): updateLiteState:no connect device!
,W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425aeaa8:true
,D/BluetoothAdapter( 1116): 1104827424: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1116): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,I/LocationAgent( 3187): new LocationAgent instance!!
,D/HtcTagManager( 3187): HtcTagManager construction complete
,D/BluetoothAdapter( 3187): 1102229736: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 3187): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 12
D/BluetoothAdapter( 3187): 1102229736: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3187): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3187): Bluetooth service connected
,W/BluetoothInputDevice( 3187): Proxy not attached to service
,D/BluetoothPan( 3187): BluetoothPan()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/PMS     (  907): releaseWL(421701f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 13
D/BluetoothAdapter( 3187): 1102229736: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3187): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3187): Bluetooth service connected
D/BluetoothMap( 3187): Create BluetoothMap proxy object
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
I/PeopleContactsSync( 1223): CP2 sync disabled
D/BluetoothManagerService(  907): Registered receivers: 14
E/BluetoothMap( 3187): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  907): registerStateChangeCallback+
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothSap( 3187): BluetoothSap() call bindService
,D/BluetoothManagerService(  907): Registered receivers: 15
,D/BluetoothPbap( 3187): BluetoothPbap()
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothAdapter( 3187): 1102229736: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3187): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3187): Bluetooth service connected
D/LocalBluetoothProfileManager( 3187): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3187): 1102229736: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3187): 1102229736: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3187): setBluetoothStateOff
,D/HtcTagManager( 3187): stopProxy
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/BluetoothEventManager( 3187): unregister mProfileBroadcastReceiver fail
,D/BluetoothManagerService(  907): Registered receivers: 16
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1223, uid=10028, userID:0
W/ContextImpl( 3187): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/Process (  907): killProcessQuiet, pid=3726
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3726:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3726
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CustomizationManager( 3898):  Read ACC file spent 0.062 (s)
,D/CIDMapFileReader( 3898): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3898): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3898): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3898): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3898): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3898): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3898): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3898): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3898): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3898): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3898): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3898): Parsing tag category name = system
,I/CustomizationCIDLoader( 3898): Parsing tag category name = application
,I/CustomizationCIDLoader( 3898): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3898): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3898): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3898): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3898): Parsing tag category name = Settings
,D/CustomizationManager( 3898):  Read CID file spent 0.108 (s)
,D/CustomizationManager( 3898):  All configurations done spent 0.108 (s)
W/HtcNativeFlag( 3898): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3898): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3898): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3898): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=3898, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=3302
,W/asset   (  907): Copying FileAsset 0x6c751510 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Killing 3302:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  907): Force removing ActivityRecord{42463140 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{422d3ca0 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=0: pkg removed
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/InputDispatcher(  907): channel '4286ab28 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  907): channel '4286ab28 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4286ab28 com.example.hello.MainActivity (s)'
D/WifiService(  907): Client connection lost with reason: 4
I/WindowState(  907): WIN DEATH: Window{4286ab28 u0 com.example.hello/com.example.hello.MainActivity}
,D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
I/acms    ( 1894): Unregistering com.example.hello
I/FeedHostManager( 1270): [onResume]
I/FeedProviderManager( 1270): onResume
,E/acms    ( 1894): Could not unregister removed application com.example.hello
I/SocialFeedProvider( 1270): +onResume
I/SocialFeedProvider( 1270): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1270): -onResume
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/WindowManager(  907): WINDOW DIED Window{4286ab28 u0 com.example.hello/com.example.hello.MainActivity}
,I/ConnectivityHelper( 1270): [getCurrentConnectionType] no network connection
,I/Prism.ItemManager( 3792): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3792): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/GeofencerStateMachine( 1502): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,W/SystemReader( 1253): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1270/10075)
D/PMS     (  907): acquireWL(428ccdd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1502 10028 null
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
D/PMS     (  907): releaseWL(428ccdd0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1329): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1502/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1894/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1838/10178)
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1270): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ConnectivityHelper( 1270): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1270/10075)
,D/PMS     (  907): releaseWL(4254c570): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/GameAgent( 1223): Caller attempted to insert game data for non-existent package.
E/GameAgent( 1223): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/GameAgent( 1223): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:227)
E/GameAgent( 1223): 	at duo.a(SourceFile:1369)
E/GameAgent( 1223): 	at dug.c(SourceFile:3101)
E/GameAgent( 1223): 	at dug.c(SourceFile:3083)
E/GameAgent( 1223): 	at ezc.a(SourceFile:24)
E/GameAgent( 1223): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/GameAgent( 1223): 	at bpu.run(SourceFile:101)
E/GameAgent( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/GameAgent( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/GameAgent( 1223): 	at java.lang.Thread.run(Thread.java:864)
,I/ActivityManager(  907): Resuming delayed broadcast
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3302 uid 10355
,W/Binder  ( 1206): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1206): java.lang.NullPointerException
W/Binder  ( 1206): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1206): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1206): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1206): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  907): Enable input method client, pid=1270
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3956 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,V/AlarmManager(  907): sending alarm PendingIntent{4236cb80: PendingIntentRecord{42641210 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448385982324, Int=0
,I/SocialManager[SocialBiLogHelper]( 3792): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3792): last commit ulog time 1448344785931
,I/SocialManager[SocialBiLogHelper]( 3792): skip commit this time
,D/Process (  907): killProcessQuiet, pid=3743
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3743:com.htc.stock/u0a81 (adj 15): empty #17
I/[PluginManager]RegisterService( 1420): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1420): handle notify Blinkfeed plugin client changed
,E/[PluginManager]RegisterService( 1420): Unable to getApplicationInfo for com.example.hello
E/[PluginManager]RegisterService( 1420): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/[PluginManager]RegisterService( 1420): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:227)
E/[PluginManager]RegisterService( 1420): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.a(Unknown Source)
E/[PluginManager]RegisterService( 1420): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
E/[PluginManager]RegisterService( 1420): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/[PluginManager]RegisterService( 1420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/[PluginManager]RegisterService( 1420): 	at android.os.Looper.loop(Looper.java:157)
E/[PluginManager]RegisterService( 1420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 3743
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3975 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  907): remove iface:wlan0
D/Tethering(  907): interfaceRemoved wlan0
,E/Tethering(  907): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,D/Process (  907): killProcessQuiet, pid=3755
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3755:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3755
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3975, uid=10073, userID:0
,D/Finsky  ( 3975): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3975/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3975/10073)
,V/AlarmManager(  907): sending alarm PendingIntent{41daabd8: PendingIntentRecord{424ac1b8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=58632, Int=0
,D/Finsky  ( 3975): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3975): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/PackageManager(  907): Unable to load service info ResolveInfo{42877ca0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  907): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  907): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  907): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  907): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  907): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  907): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  907): 	at dalvik.system.NativeStart.main(Native Method)
,W/Settings( 3975): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 3975): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 3975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 3975): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3975): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3975): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3975): threadid=25: thread exiting with uncaught exception (group=0x416c5e30)
,E/ActivityManager(  907): App crashed! Process: com.android.vending
E/AndroidRuntime( 3975): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 3975): Process: com.android.vending, PID: 3975
E/AndroidRuntime( 3975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3975): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:247)
E/AndroidRuntime( 3975): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 3975): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 3975): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3975): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3975): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3975): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3975, uid=10073, userID:0
,I/ActivityManager(  907): Killing 2793:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=2793
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1270): action: android.intent.action.PACKAGE_ADDED
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,I/IcingCorporaProvider( 2908): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4009 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  907): acquireWL(42880858): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,E/SQLiteDatabase( 3975): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 3975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:237)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:265)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:54)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:75)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:162)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:149)
E/SQLiteDatabase( 3975): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3975): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3975): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3975): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3975): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3975): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3975): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 3975): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:237)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:265)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:54)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:75)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:60)
E/SQLiteDatabase( 3975): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:32)
E/SQLiteDatabase( 3975): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 3975): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 3975): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 3975): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 3975): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 3975): 	at java.lang.Thread.run(Thread.java:864)
,W/dalvikvm( 3975): threadid=27: thread exiting with uncaught exception (group=0x416c5e30)
E/AndroidRuntime_2_crash( 3975): crash in the same process: AsyncTask #3
E/AndroidRuntime_2_crash( 3975): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_2_crash( 3975): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_2_crash( 3975): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_2_crash( 3975): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_2_crash( 3975): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_2_crash( 3975): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_2_crash( 3975): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_2_crash( 3975): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_2_crash( 3975): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime_2_crash( 3975): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime_2_crash( 3975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime_2_crash( 3975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime_2_crash( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime_2_crash( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:237)
E/AndroidRuntime_2_crash( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:265)
E/AndroidRuntime_2_crash( 3975): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:54)
E/AndroidRuntime_2_crash( 3975): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:75)
E/AndroidRuntime_2_crash( 3975): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:60)
E/AndroidRuntime_2_crash( 3975): 	at com.google.android.finsky.appstate.MigrationAsyncTask.doInBackground(MigrationAsyncTask.java:32)
E/AndroidRuntime_2_crash( 3975): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_2_crash( 3975): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_2_crash( 3975): 	... 4 more
,W/dalvikvm( 3975): threadid=26: thread exiting with uncaught exception (group=0x416c5e30)
,E/SharedPreferencesImpl( 1223): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2793
,E/AndroidRuntime_3_crash( 3975): crash in the same process: AsyncTask #2
E/AndroidRuntime_3_crash( 3975): java.lang.RuntimeException: An error occured while executing doInBackground()
E/AndroidRuntime_3_crash( 3975): 	at android.os.AsyncTask$3.done(AsyncTask.java:300)
E/AndroidRuntime_3_crash( 3975): 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
E/AndroidRuntime_3_crash( 3975): 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
E/AndroidRuntime_3_crash( 3975): 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
E/AndroidRuntime_3_crash( 3975): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/AndroidRuntime_3_crash( 3975): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime_3_crash( 3975): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime_3_crash( 3975): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime_3_crash( 3975): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime_3_crash( 3975): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime_3_crash( 3975): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime_3_crash( 3975): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime_3_crash( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:237)
E/AndroidRuntime_3_crash( 3975): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:265)
E/AndroidRuntime_3_crash( 3975): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:54)
E/AndroidRuntime_3_crash( 3975): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:75)
E/AndroidRuntime_3_crash( 3975): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:162)
E/AndroidRuntime_3_crash( 3975): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:149)
E/AndroidRuntime_3_crash( 3975): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/AndroidRuntime_3_crash( 3975): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/AndroidRuntime_3_crash( 3975): 	... 4 more
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.cor,pusid-12
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.deleted
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1223): Writing status failed
I/DeviceManagement( 4009): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4009 dbg=false s=true
E/Icing   ( 1223): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1223): 	at ghk.a(SourceFile:192)
E/Icing   ( 1223): 	at gga.n(SourceFile:1223)
E/Icing   ( 1223): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1223): 	at ger.run(SourceFile:301)
E/Icing   ( 1223): 	at ght.a(SourceFile:259)
E/Icing   ( 1223): 	at ghz.d(SourceFile:73)
E/Icing   ( 1223): 	at ghu.run(SourceFile:250)
E/Icing   ( 1223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265),
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1223): 	at ghy.run(SourceFile:50)
E/Icing   ( 1223): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1223): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1223): 	... 17 more
,I/DeviceManagement( 4009): PackageUpdateReceiver: vvv Package added: [com.example.hello]
D/PMS     (  907): releaseWL(42880858): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4028 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3677
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3677:com.htc.task/u0a70 (adj 15): empty #17
D/PMS     (  907): acquireWL(426c1fc8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,E/SharedPreferencesImpl( 1223): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.deleted
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1223): Writing status failed
,E/Icing   ( 1223): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1223): 	at ghk.a(SourceFile:192)
E/Icing   ( 1223): 	at gga.n(SourceFile:1223)
E/Icing   ( 1223): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1223): 	at ger.run(SourceFile:301)
E/Icing   ( 1223): 	at ght.a(SourceFile:259)
E/Icing   ( 1223): 	at ghz.d(SourceFile:73)
E/Icing   ( 1223): 	at ghu.run(SourceFile:250)
E/Icing   ( 1223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1223): 	at ghy.run(SourceFile:50)
E/Icing   ( 1223): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1223): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1223): 	... 17 more
I/ActivityManager(  907): Recipient 3677
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): releaseWL(426c1fc8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/PMS     (  907): acquireWL(426784e8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,E/SharedPreferencesImpl( 1223): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
,E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.deleted
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._i.e66c36715ed1937e
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
,E/Icing   ( 1223): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
E/Icing   ( 1223): Writing status failed
E/Icing   ( 1223): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1223): 	at ghk.a(SourceFile:192)
E/Icing   ( 1223): 	at gga.n(SourceFile:1223)
E/Icing   ( 1223): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1223): 	at ger.run(SourceFile:301)
E/Icing   ( 1223): 	at ght.a(SourceFile:259)
E/Icing   ( 1223): 	at ghz.d(SourceFile:73)
E/Icing   ( 1223): 	at ghu.run(SourceFile:250)
E/Icing   ( 1223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1223): 	at ghy.run(SourceFile:50)
E/Icing   ( 1223): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1223): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1223): 	... 17 more
,E/SharedPreferencesImpl( 1223): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
,E/Icing   ( 1223): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.deleted
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1223): Writing status failed
,E/Icing   ( 1223): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1223): 	at ghk.a(SourceFile:192)
E/Icing   ( 1223): 	at gga.n(SourceFile:1223)
E/Icing   ( 1223): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1223): 	at ger.run(SourceFile:301)
E/Icing   ( 1223): 	at ght.a(SourceFile:259)
E/Icing   ( 1223): 	at ghz.d(SourceFile:73)
E/Icing   ( 1223): 	at ghu.run(SourceFile:250)
E/Icing   ( 1223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1223): 	at ghy.run(SourceFile:50)
E/Icing   ( 1223): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1223): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1223): 	... 17 more
D/PMS     (  907): releaseWL(426784e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(426b6df8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  907): remove iface:p2p0
D/Tethering(  907): interfaceRemoved p2p0
,E/Tethering(  907): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 6 times.
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
,E/SharedPreferencesImpl( 1223): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-config.xml.bak
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.deleted
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1223): Writing status failed
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
D/PMS     (  907): acquireWL(425ff348): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,D/PMS     (  907): releaseWL(425ff348): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/Icing   ( 1223): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1223): 	at ghk.a(SourceFile:192)
E/Icing   ( 1223): 	at gga.n(SourceFile:1223)
E/Icing   ( 1223): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1223): 	at ger.run(SourceFile:301)
E/Icing   ( 1223): 	at ght.a(SourceFile:259)
E/Icing   ( 1223): 	at ghz.d(SourceFile:73)
E/Icing   ( 1223): 	at ghu.run(SourceFile:250)
E/Icing   ( 1223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1223): 	at ghy.run(SourceFile:50)
E/Icing   ( 1223): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1223): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1223): 	... 17 more
D/PMS     (  907): releaseWL(426b6df8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,E/SharedPreferencesImpl( 1223): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml to backup file /data/data/com.google.android.gms/shared_prefs/AppDataSearch-main-icing-settings.xml.bak
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-1 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-1
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.corpusid-12 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.corpusid-12
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.deleted for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.deleted
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._i.e66c36715ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._i.e66c36715ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._iim.c6e5dff4518fbbd9 for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._iim.c6e5dff4518fbbd9
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_im.1f9d7d94f051768f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_im.1f9d7d94f051768f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._io_unim.b8d0a49354216c2f for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._io_unim.b8d0a49354216c2f
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._o.0f0f93445ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._o.0f0f93445ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._sq_ig_i_person.df4a28e480c88f1e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._sq_ig_i_person.df4a28e480c88f1e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._u.f26d6a3e5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._u.f26d6a3e5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.tag.user._us.da9dbfca5ed1937e for write failed: Read-only file system
E/Icing   ( 1223): Could not init tag ds.tag.user._us.da9dbfca5ed1937e
E/Icing   ( 1223): Opening file /data/data/com.google.android.gms/files/AppDataSearch/main/cur/ds.status for write failed: Read-only file system
,E/Icing   ( 1223): Writing status failed
,E/Icing   ( 1223): Error while writing to AppDataSearch-main-config-corpus-scratch-data.tmp
E/Icing   ( 1223): java.io.FileNotFoundException: /data/data/com.google.android.gms/files/AppDataSearch/main/AppDataSearch-main-config-corpus-scratch-data.tmp: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/Icing   ( 1223): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/Icing   ( 1223): 	at ghk.a(SourceFile:192)
E/Icing   ( 1223): 	at gga.n(SourceFile:1223)
E/Icing   ( 1223): 	at gdz.q(SourceFile:2247)
E/Icing   ( 1223): 	at ger.run(SourceFile:301)
E/Icing   ( 1223): 	at ght.a(SourceFile:259)
E/Icing   ( 1223): 	at ghz.d(SourceFile:73)
E/Icing   ( 1223): 	at ghu.run(SourceFile:250)
E/Icing   ( 1223): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/Icing   ( 1223): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.access$201(ScheduledThreadPoolExecutor.java:152)
E/Icing   ( 1223): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:265)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Icing   ( 1223): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Icing   ( 1223): 	at ghy.run(SourceFile:50)
E/Icing   ( 1223): 	at java.lang.Thread.run(Thread.java:864)
E/Icing   ( 1223): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/Icing   ( 1223): 	at libcore.io.Posix.open(Native Method)
E/Icing   ( 1223): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/Icing   ( 1223): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/Icing   ( 1223): 	... 17 more
D/PMS     (  907): acquireWL(426980d8): PARTIAL_WAKE_LOCK  Icing 0x1 1223 10028 null
,D/PMS     (  907): releaseWL(426980d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,E/SQLiteDatabase( 2908): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 2908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2908): 	at clo.getWritableDatabase(PG:568)
E/SQLiteDatabase( 2908): 	at apa.a(PG:378)
E/SQLiteDatabase( 2908): 	at apg.i(PG:325)
E/SQLiteDatabase( 2908): 	at apf.call(PG:156)
E/SQLiteDatabase( 2908): 	at apg.a(PG:299)
E/SQLiteDatabase( 2908): 	at apd.a(PG:171)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.b(PG:415)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.k(PG:369)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:286)
E/SQLiteDatabase( 2908): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/SQLiteDatabase( 2908): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/SQLiteDatabase( 2908): 	at clp.Rl(PG:910)
E/SQLiteDatabase( 2908): 	at clr.tL(PG:827)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/SQLiteDatabase( 2908): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2908): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2908): Exception thrown from registerCorpora
E/IcingCorporaProvider( 2908): java.lang.RuntimeException: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/IcingCorporaProvider( 2908): 	at apg.a(PG:301)
E/IcingCorporaProvider( 2908): 	at apd.a(PG:171)
E/IcingCorporaProvider( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.b(PG:415)
E/IcingCorporaProvider( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.k(PG:369)
E/IcingCorporaProvider( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:286)
E/IcingCorporaProvider( 2908): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/IcingCorporaProvider( 2908): 	at android.content.Content,Resolver.update(ContentResolver.java:1339)
E/IcingCorporaProvider( 2908): 	at clp.Rl(PG:910)
E/IcingCorporaProvider( 2908): 	at clr.tL(PG:827)
E/IcingCorporaProvider( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/IcingCorporaProvider( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/IcingCorporaProvider( 2908): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/IcingCorporaProvider( 2908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/IcingCorporaProvider( 2908): 	at android.os.Looper.loop(Looper.java:157)
E/IcingCorporaProvider( 2908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/IcingCorporaProvider( 2908): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/IcingCorporaProvider( 2908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/IcingCorporaProvider( 2908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/IcingCorporaProvider( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/IcingCorporaProvider( 2908): 	at clo.getWritableDatabase(PG:568)
E/IcingCorporaProvider( 2908): 	at apa.a(PG:378)
E/IcingCorporaProvider( 2908): 	at apg.i(PG:325)
E/IcingCorporaProvider( 2908): 	at apf.call(PG:156)
E/IcingCorporaProvider( 2908): 	at apg.a(PG:299)
E/IcingCorporaProvider( 2908): 	... 14 more
,W/IcingCorporaProvider( 2908): Corpora registration failed
,E/SQLiteDatabase( 2908): Failed to open database '/data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db'.
E/SQLiteDatabase( 2908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2908): 	at clo.getWritableDatabase(PG:568)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:294)
E/SQLiteDatabase( 2908): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/SQLiteDatabase( 2908): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/SQLiteDatabase( 2908): 	at clp.Rl(PG:910)
E/SQLiteDatabase( 2908): 	at clr.tL(PG:827)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/SQLiteDatabase( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/SQLiteDatabase( 2908): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 2908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2908): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 2908): threadid=27: thread exiting with uncaught exception (group=0x416c5e30)
E/AndroidRuntime( 2908): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2908): Process: com.google.android.googlequicksearchbox:search, PID: 2908
E/AndroidRuntime( 2908): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 2908): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 2908): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 2908): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2908): 	at clo.getWritableDatabase(PG:568)
E/AndroidRuntime( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:294)
E/AndroidRuntime( 2908): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2908): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2908): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2908): 	at clr.tL(PG:827)
E/AndroidRuntime( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2908): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2908): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2908): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2908): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2908): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,E/SQLiteDatabase( 4028): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4028): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4028): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4028): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4028): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4028): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4028): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4028): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4028): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4028): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4028): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4028): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4028): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4028): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4028): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4028): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4028): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4028): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4028): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4028): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4028): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4028): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4028): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4028): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4028): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4028): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4028): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4028): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4028): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4028): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4028): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4028): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4028): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4028): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4028): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4028): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4028): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4028): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4028): threadid=11: thread exiting with uncaught exception (group=0x416c5e30)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4028): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4028): Process: com.google.android.apps.docs, PID: 4028
E/AndroidRuntime( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4028): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4028): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4046 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,E/SQLiteDatabase( 4028): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4028): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4028): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4028): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4028): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4028): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4028): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4028): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4028): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4028): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4028): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4028): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4028): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4028): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4028): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4028): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4028): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4028): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4028): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4028): Opened ClientFlag.db in read-only mode
,D/Process (  907): killProcessQuiet, pid=3810
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3810:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3810
,W/GAV2    ( 4028): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4028): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4028): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/SQLiteDatabase( 4028): 	at aid.a(DatabaseModelLoader.java:340)
E/SQLiteDatabase( 4028): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/SQLiteDatabase( 4028): 	at fv.run(DocsApplication.java:288)
E/AbstractDatabaseInstance( 4028): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AbstractDatabaseInstance( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AbstractDatabaseInstance( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AbstractDatabaseInstance( 4028): 	at android.database.sqlite.SQLiteOp,enHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AbstractDatabaseInstance( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AbstractDatabaseInstance( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AbstractDatabaseInstance( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AbstractDatabaseInstance( 4028): 	at azJ.a(Suppliers.java:125)
E/AbstractDatabaseInstance( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/AbstractDatabaseInstance( 4028): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4028): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4028): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4028): 	at fv.run(DocsApplication.java:288)
,W/dalvikvm( 4028): threadid=12: thread exiting with uncaught exception (group=0x416c5e30)
W/BroadcastQueue(  907): Skipping deliver [background] BroadcastRecord{428b4000 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{4268e338 4028 com.google.android.apps.docs/10100/u0 remote:4289ebd0}: process crashing
E/AndroidRuntime_2_crash( 4028): crash in the same process: Background initialization thread
E/AndroidRuntime_2_crash( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime_2_crash( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime_2_crash( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime_2_crash( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime_2_crash( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime_2_crash( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime_2_crash( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime_2_crash( 4028): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime_2_crash( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/AndroidRuntime_2_crash( 4028): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime_2_crash( 4028): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime_2_crash( 4028): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime_2_crash( 4028): 	at fv.run(DocsApplication.java:288)
,E/SQLiteDatabase( 4028): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4028): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4028): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4028): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4028): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4028): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4028): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4028): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4028): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4028): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4028): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4028): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4028): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4028): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4028): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4028): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4028): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 4028): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4028): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4028): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4028): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4028): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4028): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4028): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4028): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4028): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4028): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4028): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4028): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4028): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4028): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4028): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4028): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4028): 	at java.lang.Thread.run(Thread.java:864)
,I/htcbackup-core( 4046): ModelRegistry: Loading model meta data from resources...
,E/SQLiteDatabase( 4028): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4028): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4028): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4028): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4028): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4028): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4028): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4028): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4028): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4028): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4028): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4028): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4028): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4028): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4028): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4028): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4028): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4028): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4028): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4028): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4028): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4028): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4028): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4028): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4028): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4028): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4028): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4028): 	at java.lang.Thread.run(Thread.java:864)
,W/ContextImpl( 4046): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 4046): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{425b4700 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/DeviceManagement( 4009): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 4009): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.drive.activator, com.htc.cirmodule, com.htc.feedback, com.htc.guide, com.htc.home.personalize, com.android.settings, com.qualcomm.privinit, com.htc.smartdim, com.htc.htcpowermanager, android, com.htc.android.htcsetupwizard, com.android.keychain, com.htc.backupreset, com.android.providers.settings, com.htc.checkinprovider, com.htc.usage, com.android.location.fused, com.htc.android.htcloglevel, com.htc.backup, com.android.CSDFunctionG, com.htc.lockscreen, com.android.inputdevices, com.htc.mirrorlinkserver, com.qualcomm.timeservice, com.htc.autobot.cargps.provider]
,I/DeviceManagement( 4009): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4070 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/DeviceManagement( 4009): WorkflowService: Starting workflow service
I/DeviceManagement( 4009): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b31f88] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 4009): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 4009): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4009): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4009): SessionStateController: Checking invariants...

```
