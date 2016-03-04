#### Test 61703351a2a4153_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  911): Recipient 2570
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/AlarmManager(  911): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@420fff88
I/AlarmManager(  911): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42491e90
--------- beginning of /dev/log/main
D/HtcFingerPrintQuickLaunchProvider( 2868): -onCreate()
V/Settings:HtcSettingsApplication( 2868): [2868/2868] onCreate()
W/ContextImpl( 2868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  911): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42113fe8
D/Process (  911): killProcessQuiet, pid=2584
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
I/ActivityManager(  911): Killing 2584:com.htc.updater/u0a85 (adj 15): empty #17
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  911): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  911): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  911): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  911): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  911): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
D/Process (  911): killProcessQuiet, pid=2613
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  911): Killing 2613:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Recipient 2613
D/TetherSettings( 2868): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2868): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2868): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2868): Cust_ConnectToPC   : spcsc>false
D/        ( 2868): Cust_ConnectToPC   : IPT>true
D/        ( 2868): Cust_ConnectToPC   : Singel_USB>false
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Settings( 2868): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 2868): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2868): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2868): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2868): Cust_ConnectToPC   : spcsc>false
D/        ( 2868): Cust_ConnectToPC   : IPT>true
D/        ( 2868): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2868): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2868): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2868): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2868): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
I/SmartNS_Utility( 2868): setISNotification
D/SmartNS_Utility( 2868): usb_cable_connect = 1
D/SmartNS_Utility( 2868): usb_denied = 0
I/SmartNS_PSService( 2868): usb notificaiton:true
V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  911): bSetPropertyMultiRAB:false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.settings (2868/1000)
D/SmartNS_Utility( 2868): usb_cable_connect = 1
D/SmartNS_Utility( 2868): usb_denied = 0
I/SmartNS_PSService( 2868): usb notificaiton:true
V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  911): bSetPropertyMultiRAB:false
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.settings (2868/1000)
D/Process (  911): killProcessQuiet, pid=2642
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  911): Killing 2642:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/ActivityManager(  911): Recipient 2584
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1111): com.android.settings (true,33751552)
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Recipient 2642
D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41c27078 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1111): com.android.settings 2 10 0 10
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2887 uid=9987 gids={49987}
I/RemoteViews( 1111): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1111): com.android.settings 2 0 10
I/SensorManager(  911): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@424c44b0, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424c44b0, eanble = 1, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208db00
W/SensorService(  911): Listener[1] = com.android.server.power.DisplayPowerController$10@422d6d60
W/SensorService(  911): Listener[2] = com.htc.smartdim.sensor_eye@424c44b0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  911): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@424c44b0, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  911): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{42553c90 u0 ReceiverList{42558658 911 system/1000/u0 local:425c8f48}}
D/NfcUiccLockService( 2887): -- To check whether previous opened channel needed to be closed ...
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 3
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424c44b0, eanble = 1, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208db00
W/SensorService(  911): Listener[1] = com.android.server.power.DisplayPowerController$10@422d6d60
W/SensorService(  911): Listener[2] = com.htc.smartdim.sensor_eye@424c44b0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/Process (  911): killProcessQuiet, pid=2662
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2903 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  911): Killing 2662:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  911): Recipient 2662
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2915 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
D/Process (  911): killProcessQuiet, pid=2674
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 2674:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  911): Recipient 2674
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/cutils-trace( 2891): Error opening trace file: No such file or directory (2)
E/YouTube ( 2915): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 2915): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 2915): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 2915): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/CustomizationManager( 2891): ====startRecUseTime====
D/htc.customization.log.level( 2891):  is 
W/CustomizationLogLevel( 2891): Level value is invalid, use default level 2
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.youtube (2915/10168)
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 2915): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/CustomizationManager( 2891):  Read ACC file spent 0.085 (s)
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2891): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2891): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2891): Parsing tag category name = system
I/CustomizationCIDLoader( 2891): Parsing tag category name = application
I/CustomizationCIDLoader( 2891): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2891): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2891): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2891): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2891): Parsing tag category name = Settings
D/CustomizationManager( 2891):  Read CID file spent 0.135 (s)
D/CustomizationManager( 2891):  All configurations done spent 0.135 (s)
W/HtcNativeFlag( 2891): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2891): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2891): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2891): Fail to get flag for type 'language', use default value: -1
D/YouTube ( 2915): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 2915): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
W/CpuWake (  911): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  911): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  911): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  911): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2891
D/PMS     (  911): acquireHCC(429d1598): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 911 1000 null
W/asset   (  911): Copying FileAsset 0x6f972e48 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  911): @test_code: getHtcIntentFlag: 0 obj: 1114128000
D/PMS     (  911): acquireHCC(4259c048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 911 1000 null
D/PMS     (  911): acquireWL(427b9858): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 911 1000 null
I/FeedHostManager( 1254): [onPause]
I/FeedProviderManager( 1254): onPause
I/SocialFeedProvider( 1254): +onPause
I/FeedHostManager( 1254): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d815a8
I/SocialFeedProvider( 1254): -onPause
D/YouTube ( 2915): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
I/ActivityManager(  911): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2955 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1254): [trimMemory] 20
W/asset   ( 2955): Copying FileAsset 0x5c73c648 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 2955): Binding Chromium to main looper Looper (main, tid 1) {41c1e3f8}
I/LibraryLoader( 2955): Expected native library version number "",actual native library version number ""
I/chromium( 2955): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2955): Initializing chromium process, renderers=0
D/BluetoothManagerService(  911): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  911): java.lang.Throwable: stack dump
D/BluetoothManagerService(  911): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@429d6c98:true
W/System.err(  911): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  911): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  911): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  911): 	at android.os.Binder.execTransact(Binder.java:412)
D/YouTube ( 2915): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
W/System.err(  911): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  911): acquireWL(42740268): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  911): acquireWL(42721f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  911): releaseWL(42740268): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 2955): 1103314656: getState() :  mService = null. Returning STATE_OFF
I/Adreno-EGL( 2955): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2955): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2955): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2955): Local Branch: 
I/Adreno-EGL( 2955): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2955): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2955):                  aa63bbd948f41d15fc72f585e
D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
D/MediaRouterService(  911): Client com.google.android.youtube (pid 2915): Registered
I/MediaRouter( 2915): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
D/YouTube ( 2915): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 2915): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1457094247&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.google.android.youtube (2915/10168)
D/libc    ( 2915): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2915): [NET] getaddrinfo-,err=8
D/libc    ( 2915): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2915): [NET] getaddrinfo-, 1
D/libc    ( 2915): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
W/chromium( 2955): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 2915): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2915): Error sending ping
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 2915): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/dalvikvm( 2955): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2955): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
D/YouTube ( 2915): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/MediaRouter( 2915): getSelectedRoute
W/dalvikvm( 2955): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2955): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2955): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/YouTube ( 2915): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/YouTube ( 2915): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
W/dalvikvm( 2955): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2955): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2955): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2955): CordovaWebView is running on device made by: HTC
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.youtube (2915/10168)
I/ActivityManager(  911): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3001 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/Process (  911): killProcessQuiet, pid=2707
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2707:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  911): Recipient 2707
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/YouTube ( 2915): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 2915): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 2915): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
W/AwContents( 2955): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  911): Disable input method client, pid=1254
W/ResourceType( 2955): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2955): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41c65228, mServedView=org.apache.cordova.engine.SystemWebView{41c2b200 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  911): Displayed com.example.hello/.MainActivity: +280ms
W/XT9_C   ( 1187): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1187): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1187): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  911): Enable input method client, pid=2955
W/AwContents( 2955): nativeOnDraw failed; clearing to background color.
D/PMS     (  911): releaseWL(427b9858): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/dalvikvm( 3001): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3001, uid=10074, userID:0
D/Finsky  ( 3001): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3001/10074)
W/dalvikvm( 3001): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 3001): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3001/10074)
E/AndroidProtocolHandler( 2955): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/Finsky  ( 3001): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/dalvikvm( 3001): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
I/chromium( 2955): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/Settings( 3001): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3001): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 3001): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3001): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3001): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/JsMessageQueue( 2955): Set native->JS mode to OnlineEventsBridgeMode
W/dalvikvm( 3001): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3001, uid=10074, userID:0
W/dalvikvm( 2260): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
W/dalvikvm( 2260): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 2260): VM with version 1.6.0 does not have multidex support
I/MultiDex( 2260): install
I/MultiDex( 2260): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/MultiDex( 2260): loading existing secondary dex files
I/MultiDex( 2260): load found 3 secondary dex files
D/Volley  ( 3001): [289] DiskBasedCache.clear: Cache cleared.
D/Finsky  ( 3001): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3001): [1] Libraries$2.run: Finished loading 1 libraries.
D/Volley  ( 3001): [282] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 3001): Skipping gmscore version check
I/MultiDex( 2260): install done
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/dalvikvm( 2260): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2260): VFY: unable to resolve instance field 36
W/dalvikvm( 2260): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
D/Finsky  ( 3001): [1] GmsCoreHelper.cleanupNlp: result=false type=4
V/JNIHelp ( 2260): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Finsky  ( 3001): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/jxcore_app_log( 2955): JniHelper::setJavaVM(0x417d6010), pthread_self() = 1658334400
I/ProviderInstaller( 2260): Installed default security provider GmsCore_OpenSSL
W/dalvikvm( 2260): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
W/jxcore-log( 2955): Initializing JXcore engine
W/jxcore-log( 2955): JXcore engine is ready
V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 2260): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/jxcore-log( 2955): Starting JXcore engine
W/dalvikvm( 1777): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1777): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1777): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1777): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  911): acquireWL(42722fe0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1777 10029 null
I/ActivityManager(  911): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/FileApkUtils( 1777): Spent 27ms computing apk sha1.
D/FileApkUtils( 1777): Module already staged or being staged:chimera-modules/MapsModule.apk
D/PMS     (  911): acquireWL(42a3cc00): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
D/DexOptUtils( 1777): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1777): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 1777): Reading stored module config
D/PMS     (  911): releaseWL(42722fe0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  911): releaseWL(42a3cc00): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2260): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
I/ActivityManager(  911): Resuming delayed broadcast
D/GmsModuleFndr( 1777): Beginning GMS chimera module scan
D/NativeLibraryUtils( 2260): Install completed successfully. count=14 extracted=0
W/asset   ( 1777): Copying FileAsset 0x617d7bc0 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
W/dalvikvm( 2260): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/ChimeraCfgMgr( 1777): Beginning module configuration check
V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ChimeraCfgMgr( 1777): Module APKs unchanged, check complete
W/dalvikvm( 2260): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2260): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/InstanceID/Rpc( 1777): Found 10029
W/dalvikvm( 2260): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2260): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
W/dalvikvm( 2260): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
W/jxcore-log( 2955): Platform android
W/jxcore-log( 2955): 
W/jxcore-log( 2955): Process ARCH arm
W/jxcore-log( 2955): 
W/dalvikvm( 2260): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
W/dalvikvm( 2260): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
I/jxcore-log( 2955): JXcore Cordova bridge is ready!
I/jxcore-log( 2955): 
W/jxcore-log( 2955): JXcore engine is started
E/jxcore  ( 2955): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 2955): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,E/dalvikvm( 1777): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1777): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1777): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1777): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1777): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1777): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
I/ActivityManager(  911): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1777/10029)
W/dalvikvm( 1777): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1777): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,E/dalvikvm( 1777): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
,W/dalvikvm( 1777): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
E/dalvikvm( 1203): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
,W/dalvikvm( 1203): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1203): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1203): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1203): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1203): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
,W/dalvikvm( 1203): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 1203): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
,W/dalvikvm( 1203): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(427bfa00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,E/dalvikvm( 1777): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
,W/dalvikvm( 1777): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
,W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
,W/dalvikvm( 1777): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.tapandpay.receiver.OnBootCompletedReceiver
,D/PMS     (  911): acquireWL(427be3f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427bfa00): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 1777): COMPAT: Multi user not supported
,D/PMS     (  911): acquireWL(427b9740): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
I/CheckinService( 1777): Checkin interval check for package: unspecified last checkin: 1456764464980 min interval config: 0 actual interval: 329783704
D/GCM     ( 2260): COMPAT: Multi user not supported
D/libc    ( 3001): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3001): [NET] getaddrinfo-,err=8
D/libc    ( 3001): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3001): [NET] getaddrinfo-, 1
D/libc    ( 3001): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3001): [NET] getaddrinfo_proxy-
W/dalvikvm( 2260): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,I/GCoreUlr( 1777): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,I/GCoreUlr( 1203): DispatchingService.onCreate()
,I/CheckinService( 1777): Disabling old GoogleServicesFramework version
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1777, uid=10029, userID:0
,W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2260): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1777, uid=10029, userID:0
D/SystemUpdateService( 1777): onCreate
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
,D/SystemUpdateService( 1777): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/dalvikvm( 2260): VFY: unable to resolve instance field 161
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/CheckinService( 1777): Checking schedule, now: 1457094248765 next: 1457287401930
,I/CheckinService( 1777): active receiver: disabled
,V/AuthZen ( 1777): Handling intent: android.intent.action.BOOT_COMPLETED
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/SystemUpdateService( 1777): cancelUpdate (empty URL)
,I/SystemUpdateService( 1777): active receiver: disabled
D/PMS     (  911): acquireWL(427a9198): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1777, uid=10029, userID:0
D/WifiService(  911): New client listening to asynchronous messages
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1777, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1777, uid=10029, userID:0
,D/PMS     (  911): releaseWL(427a9198): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/PMS     (  911): acquireWL(42783ec8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2260): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/PMS     (  911): releaseWL(427be3f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/AuthZenEventHandler( 1777): Handling event: android.intent.action.BOOT_COMPLETED
,D/SystemUpdateService( 1777): onDestroy
,I/GCoreUlr( 1203): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  911): releaseWL(427b9740): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
,W/dalvikvm( 2260): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,D/PMS     (  911): acquireWL(4256ace0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,D/libc    ( 2260): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 2260): [NET] getaddrinfo-,err=8
D/GCM     ( 2260): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/libc    ( 2260): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 2260): [NET] getaddrinfo-, 1
,D/libc    ( 2260): [NET] getaddrinfo_proxy+
W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 2260): [NET] getaddrinfo_proxy-
,W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
D/ConnectivityService(  911): reportInetCondition for net -1, percentage: 0 by  (2260/10029)
,D/ConnectivityService(  911): handleInetConditionChange: no active default network - ignore
W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
D/PMS     (  911): releaseWL(4256ace0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1203, uid=10029, userID:0
,E/BaseAppContext( 1777): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,I/AuthZen ( 1777): Fetching signing key...
,I/AuthZen ( 1777): Signing key fetched successfully!
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,D/AuthZenTransactionCache( 1777): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 1777): Clearing transaction cache
,I/GCoreUlr( 1203): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(426fc978): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1203): Unbound from all location providers
,I/GCoreUlr( 1203): Place inference reporting - stopped
D/PMS     (  911): releaseWL(426fc978): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42783ec8): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1203): DispatchingService.onDestroy()
,I/GCoreUlr( 1203): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1203): Unbound from all location providers
,I/GCoreUlr( 1203): Place inference reporting - stopped
D/PMS     (  911): acquireWL(42716070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(42716070): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
,D/PMS     (  911): acquireWL(4263fdb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/PMS     (  911): releaseWL(4263fdb0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/BootCompletedReceiver( 1777): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 1777): Got an BootCompleted event.
D/BootCompletedReceiver( 1777): Will NOT schedule AdAttestation signal task because it's disabled.
,W/dalvikvm( 2260): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,W/Auth    ( 2260): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  911): acquireWL(42450840): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 2260 10029 null
I/ActivityManager(  911): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
,D/PMS     (  911): releaseWL(42450840): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PersistentNotificationBroadcastReceiver( 1203): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.people.sync.focus.ContactsSyncBroadcastReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.chromesync.sync.SyncReceiverService$Receiver
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(4270dae0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,D/AutoSetting( 1304): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2868): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2868): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2868): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2868): Cust_ConnectToPC   : spcsc>false
D/        ( 2868): Cust_ConnectToPC   : IPT>true
D/        ( 2868): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2868): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2868): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 2868): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2868): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 2868): onReceive:android.intent.action.USER_PRESENT
,D/PMS     (  911): releaseWL(4270dae0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/SmartNS_PSService( 2868): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 2868): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2868):  defaultType:0
W/ContextImpl( 2868): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  911): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3113 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3113): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3113): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3113): Loading: swewebviewchromium
,I/LibraryLoader( 3113): Time to load native libraries: 28 ms (timestamps 9358-9386)
,I/LibraryLoader( 3113): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3113): Initializing chromium process, renderers=9
,I/LibraryLoader( 3113): Expected native library version number "",actual native library version number ""
,I/chromium( 3113): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/CpuWake (  911): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  911): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  911): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  911): <<release mCpuPerf_Freq wakelock
,D/PMS     (  911): releaseHCC(429d1598): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  911): releaseHCC(4259c048): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/chromium( 3113): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3113): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3113): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3113): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3113): Local Branch: 
I/Adreno-EGL( 3113): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3113): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3113):                  aa63bbd948f41d15fc72f585e
,D/Process (  911): killProcessQuiet, pid=2525
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1268): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  911): Killing 2525:com.android.defcontainer/u0a19 (adj 15): empty #17
I/SIMStateChangeReceiver( 1485): SIM state: ABSENT
I/SIMStateChangeReceiver( 1485): phoneType = 0
,I/SIMStateChangeReceiver( 1485): remove notification
I/ActivityManager(  911): Recipient 2525
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3152 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  911): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3164 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  911): killProcessQuiet, pid=2749
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 2749:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 2749
,W/SystemReader( 2002): Cannot find message_ambs_application_id, use default value instead
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SmsReceiver( 2002): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2002): onReceive()
,D/ExchangePolicystatus( 2002): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2002): onReceive(): else
,D/Process (  911): killProcessQuiet, pid=2689
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  911): Killing 2689:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/HtcBroadcastReceiver( 1221): onReceive: android.intent.action.SIM_STATE_CHANGED
,W/WeatherUtility( 1111): can't get weather sync account
I/ActivityManager(  911): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3180 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1111): request cur loc, but there is no sys cur
,D/AccTypeManager( 3164): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2689
,D/CalendarApplication( 3180): onCreate
D/ProviderChangeReceiver( 3180): ---------------------------------------------------
,D/ProviderChangeReceiver( 3180): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3180): start to updateAlertNotification!
W/ContextImpl( 2843): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  911): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
W/AccTypeManager( 3164): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3164): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/AlertService( 3180): No fired or scheduled alerts
D/HtcAlertUtils( 3180): -- cancelReminderNotification --
D/HtcAlertUtils( 3180): broadcastExistReminder!
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  911): Resuming delayed broadcast
,I/SensorManager(  911): mEventCount = 301
,D/Process (  911): killProcessQuiet, pid=2770
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3199 uid=10041 gids={50041}
I/ActivityManager(  911): Killing 2770:com.google.android.talk/u0a111 (adj 15): empty #17
,E/ExternalAccountType( 3164): Unsupported attribute readOnly
,D/AccTypeManager( 3164): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3164): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3164): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Process (  911): killProcessQuiet, pid=2797
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3212 uid=10078 gids={50078}
I/ActivityManager(  911): Killing 2797:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 2797
,E/ExternalAccountType( 3164): Unsupported attribute readOnly
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SMSBackup( 3212): Got a database change event
,I/ActivityManager(  911): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3224 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/Process (  911): killProcessQuiet, pid=2814
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 2814:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 2814
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2770
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3224): can't get weather sync account
,W/WeatherRequest( 3224): request cur loc, but there is no sys cur
,W/Settings( 3224): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1254): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1254): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1254): com.htc.widget.weatherclock 0 11 17
,D/PMS     (  911): releaseWL(42721f50): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 4 times.
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3239 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=2829
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2829:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2829
,I/DemoRecovery.RestoreReceiver( 3239): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3239): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3239): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3253 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=2856
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 2856:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/PMS     (  911): acquireWL(429daa30): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3253 10071 null
,D/PMS     (  911): acquireWL(42946d90): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3253 10071 null
I/ActivityManager(  911): Recipient 2856
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): releaseWL(429daa30): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  911): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3253): update TASK shortcut>
,I/TodoTaskNotifyService( 3253): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): releaseWL(42946d90): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
,W/NotifyReceiver( 3253): stopSelfResult true
,D/Process (  911): killProcessQuiet, pid=2887
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3268 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  911): Killing 2887:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  911): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3280 uid=10082 gids={50082, 3003, 5012}
,D/Process (  911): killProcessQuiet, pid=2915
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Process (  911): killProcessQuiet, pid=2903
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 2915:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  911): Killing 2903:com.android.smith/u0a163 (adj 15): empty #18
,I/ActivityManager(  911): Recipient 2903
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2887
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WearableService( 1203): callingUid 10029, callindPid: 1203
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{427a4458 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
E/MDM     ( 1203): [91] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 1777): Restart initialization of location
,D/AuthorizationBluetoothService( 2260): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/dalvikvm( 2260): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,E/AuthorizationBluetoothService( 2260): Proximity feature is not enabled.
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MessagingNotification( 2002): New incoming message, can't cancel notification now
,D/MessagingNotification( 2002): newMsgCnt: 0, false
,W/GCoreFlp( 1203): No location to return for getLastLocation()
I/ActivityManager(  911): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3297 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/PMS     (  911): acquireWL(427211d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,W/FusedLocationProvider( 1203): location=null
D/PMS     (  911): releaseWL(427211d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
I/ActivityManager(  911): Recipient 2915
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  911): Client com.google.android.youtube (pid 2915): Died!
,I/ImageRamCache( 3297): create image Cache, size: 31457280.
I/ImageRamCache( 3297): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3297): create image Cache, size: 12582912.
,I/FeedSettings( 3297): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3297): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3297): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3297): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3297): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3297): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3297): [custom highlight] onReceive
,D/CustomHighlightService( 3297): [custom highlight] onHandleIntent
,D/NewsDB  ( 3297): set custom highlight []
,E/MDM     ( 1203): [93] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1777): Restart initialization of location
,D/CustomHighlightService( 3297): [custom highlight] set tags 
D/AuthorizationBluetoothService( 2260): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2260): Proximity feature is not enabled.
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1203): location=null
D/PMS     (  911): acquireWL(4258e570): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(4258e570): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/SMSBackup( 3212): Got a database change event
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
D/MessagingShortcutReceiver( 2002): keep hiding shortcut bubble
D/MessagingShortcut( 2002): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2002): After query: 0
D/MessagingShortcut( 2002): mPresentUnreadCount: -1
D/MessagingShortcut( 2002): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2002): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderNotification, total:0
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcBroadcastReceiver( 1221): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/TodoTaskshortcut( 3253): update TASK shortcut>
,I/ActivityManager(  911): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3318 uid=10091 gids={50091, 3003, 5012}
,D/MtpReceiver( 2478): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2478): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2478): [MTP][handleMessage][startService]
,D/MtpReceiver( 2478): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2478): [MTP][handleMessage]-
,I/ActivityManager(  911): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3333 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/MtpService( 2478): [MTP] startForeground
,I/RemoteViews( 1111): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1111): com.android.providers.media 1 1 10
,I/RemoteViews( 1111): com.android.providers.media (false,0)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
,D/MtpService( 2478): updating state; isCurrentUser=true, mMtpLocked=false
D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews.Performance( 1111): com.android.providers.media 2 3 15
,D/MtpDatabase( 2478): TotalSize=1918604,MediaCacheLimit=6000,
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
D/PMS     (  911): acquireWL(42554270): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1777 10029 null
,D/MtpService( 2478): [isMtpConnected] connected: true
I/ActivityManager(  911): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3346 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  911): sending alarm PendingIntent{420abe00: PendingIntentRecord{426df308 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21821, Int=1800000
V/AlarmManager(  911): sending alarm PendingIntent{426f70d8: PendingIntentRecord{42978268 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=44728, Int=259200000
V/AlarmManager(  911): sending alarm PendingIntent{41f3bcf8: PendingIntentRecord{425900c0 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50909, Int=0
V/AlarmManager(  911): sending alarm PendingIntent{41e300e8: PendingIntentRecord{4264d818 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1457089200001, Int=86400000
,I/iu.UploadsManager( 1777): End new media; added: 0, uploading: 0, time: 72 ms
,D/SyncApplication( 3333): Loading default preferences
D/PMS     (  911): releaseWL(42554270): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,W/Resources( 3333): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/MdScBoot( 3318): [8a8.1.] 30@-132345 -> 40@-132412
,D/Process (  911): killProcessQuiet, pid=3001
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  911): Killing 3001:com.android.vending/u0a74 (adj 15): empty #17
,D/Process (  911): killProcessQuiet, pid=2868
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 2868:com.android.settings/1000 (adj 15): empty #17
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
D/WifiService(  911): New client listening to asynchronous messages
,I/ActivityManager(  911): Recipient 2868
,D/SyncApplication( 3333): Overriding preferences with custom values
,D/SyncApplication( 3333): Updating preferences succeeded
,E/SyncApplication( 3333): Application created.
D/VolumeInfo( 3333): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3333): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3333): Found 0 mount point(s)
,V/VolumeInfo( 3333): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3333): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3333): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3333): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3333): getNewCalendarAuthority()...
,D/SyncApplication( 3333): enableAppOperation()+
,D/SyncApplication( 3333): enableAppOperation()-
,D/HTCUtilities( 3333): isNeorSinged() + 
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3333, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3333, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3333): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3333): isNeorSinged() return false
,D/CDMountReceiver( 3333): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3333): USB connected to PC
,D/FOTAReceiver( 3333): onReceive() enter 
,D/FOTAReceiver( 3333): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  911): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3365 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  911): killProcessQuiet, pid=3113
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 3113:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3001
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3365): -onCreate()
,V/Settings:HtcSettingsApplication( 3365): [3365/3365] onCreate()
I/ActivityManager(  911): Recipient 3113
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 3365): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3365): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3365): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3365): Cust_ConnectToPC   : spcsc>false
D/        ( 3365): Cust_ConnectToPC   : IPT>true
,D/        ( 3365): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3365): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3365): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3365): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3365): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3365): Cust_ConnectToPC   : spcsc>false
D/        ( 3365): Cust_ConnectToPC   : IPT>true
D/        ( 3365): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3365): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3365): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3365): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3365): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3365): usb_cable_connect = 1
,D/SmartNS_Utility( 3365): usb_denied = 0
,W/ProcessCpuTracker(  911): Skipping unknown process pid 3113
I/SmartNS_NSReceiver( 3365): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3365): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3365): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3365): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3365): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3365):  defaultType:0
I/SmartNS_PSService( 3365): fail notificaiton:false
D/SmartNS_Utility( 3365): usb_cable_connect = 1
D/SmartNS_Utility( 3365): usb_denied = 0
I/SmartNS_PSService( 3365): usb notificaiton:true
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  911): bSetPropertyMultiRAB:false
I/ActivityManager(  911): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.settings (3365/1000)
,I/RemoteViews( 1111): com.android.settings (true,33751552)
,D/SmartNS_Utility( 3365): usb_cable_connect = 1
D/SmartNS_Utility( 3365): usb_denied = 0
I/RemoteViews.Performance( 1111): com.android.settings 0 1 10
,I/SmartNS_PSService( 3365): usb notificaiton:true
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  911): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  911): Resuming delayed broadcast
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.settings (3365/1000)
D/Tethering(  911): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  911): bSetPropertyMultiRAB:false
,W/WeatherUtility( 3224): can't get weather sync account
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/SmartNS_Utility( 3365): usb_cable_connect = 1
,D/SmartNS_Utility( 3365): usb_denied = 0
,I/ActivityManager(  911): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1111): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1111): com.android.settings 1 1 10
,I/SmartNS_PSService( 3365): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3365): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  911): Resuming delayed broadcast
,D/AppWidgetHostView( 1254): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1254): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1254): com.google.android.googlequicksearchbox 1 0 5
,W/WeatherRequest( 3224): request cur loc, but there is no sys cur
,W/Settings( 3224): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3382 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AppWidgetHostView( 1254): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1254): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1254): com.htc.widget.weatherclock 1 8 17
,W/ContextImpl( 3382): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3382): call getInstance()
I/ActivityManager(  911): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3382): MY_DEBUG = false
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,W/BatSI   (  911): Couldn't get kernel wake lock stats
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3152
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3152:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  911): acquireWL(42738c18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3382 1000 null
I/ActivityManager(  911): Recipient 3152
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherUtility( 1111): can't get weather sync account
D/WeatherUtility( 1304): Weather sync is On
D/WSP     ( 1304): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  911): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3399 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherUtility( 3224): can't get weather sync account
,W/WeatherRequest( 3224): request cur loc, but there is no sys cur
,W/Settings( 3224): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1254): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1254): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1254): com.htc.widget.weatherclock 0 6 17
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3417 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=3164
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3164:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3164
,I/MusicStore( 3417): Database version: 95
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3417): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
V/AlarmManager(  911): sending alarm PendingIntent{426dfce0: PendingIntentRecord{4270e580 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1457094253989, Int=0
,W/ContextImpl( 3417): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3417): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/Process (  911): killProcessQuiet, pid=3180
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3180:com.htc.calendar/u0a13 (adj 15): empty #17
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3417): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 3180
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3417): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3417, uid=10154, userID:0
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
,D/MediaRouterService(  911): Client com.google.android.music (pid 3417): Registered
,D/WifiDisplayAdapter(  911): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  911):     Client/Owner: Client
D/WifiDisplayAdapter(  911):     GroupId: 
D/WifiDisplayAdapter(  911):     Passphrase: 
D/WifiDisplayAdapter(  911):     SessionId: 0
D/WifiDisplayAdapter(  911):     IP Address: }
I/MediaRouter( 3417): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/TelephonyReceiver( 1221): bind: true
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.music (3417/10154)
,D/DFPI.PIReciver( 3239): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3239): onHandleIntent
,I/DFPI.ApkInstallService( 3239): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3239): check CID = HTC__032
I/DFPI.ApkInstallService( 3239): There is no Demo.apk in sd card or phone storage
,D/GenericMessagesProvider( 2002): query uri: content://htc-messages/wappush/count
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
E/SQLiteLog( 2002): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2002): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2002): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
E/SQLiteConnection( 2002): DB info: errno = 2, errno message = No such file or directory
E/SQLiteDatabase( 2002): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2002): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2002): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2002): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2002): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2002): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2002): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2002): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2002): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2002): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2002): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2002): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2002): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2002): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2002): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2002): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2002): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2002): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2002): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2002): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2002): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
,W/System.err( 2002): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2002): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2002): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2002): ,	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2002): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/MediaRouter( 3417): getSelectedRoute
D/TelephonyReceiver( 1221): switchBindHtcMsgCursor: null
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3417, uid=10154, userID:0
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (911/1000)
D/PMS     (  911): acquireWL(4292fe60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 911 1000 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): releaseWL(4292fe60): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  911): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3440 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  911): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.musicenhancer (3440/10053)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3440): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/PMS     (  911): releaseWL(42738c18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3459 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  911): Killing 2843:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  911): killProcessQuiet, pid=2843
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 2843
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3459): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3459): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3459): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3459): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
,I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 5 times.
,I/ActivityManager(  911): Resuming delayed broadcast
,D/DFPI.PIReciver( 3239): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3239): onHandleIntent
,I/DFPI.ApkInstallService( 3239): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3239): check CID = HTC__032
,I/DFPI.ApkInstallService( 3239): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/Process (  911): killProcessQuiet, pid=3268
,I/ActivityManager(  911): Killing 3268:com.htc.stock/u0a82 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 3268
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3280
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3280:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3459): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3459): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
,V/SoundPicker( 3459): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3459): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
,I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7,
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): TurnFileToMediaUriService [checkFileExistence],
,D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  911): Recipient 3280
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  911): Resuming delayed broadcast,
,I/ActivityManager(  911): Delay finish: com.htc.task/.TodoTaskReceiver,
,I/SensorManager(  911): mEventCount = 450
,I/ActivityManager(  911): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3480 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3239): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  911): Resuming delayed broadcast
,I/DFPI.ApkInstallService( 3239): onHandleIntent
,I/DFPI.ApkInstallService( 3239): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3239): check CID = HTC__032
,I/DFPI.ApkInstallService( 3239): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3480): [ NA ]- onCreate()
,I/EASAppSvc( 3480): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3253): put()
,D/WifiService(  911): New client listening to asynchronous messages
,D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.android.mail (3480/10064)
,I/EASAppSvc( 3480): [ NA ]- onDestroy()
,I/EASAppSvc( 3480): [ NA ]> uninitEASService
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.htc.android.mail (3480/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=55 called by com.htc.android.mail (3480/10064)
,I/EASRequestController( 3480): [ NA ]release
,I/EASAppSvc( 3480): [ NA ]< uninitEASService
,I/EASAppSvc( 3480): [ NA ]- onCreate()
,I/EASAppSvc( 3480): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  911): getNetworkInfo networkType=1 called by com.htc.android.mail (3480/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=0 called by com.htc.android.mail (3480/10064)
D/ConnectivityService(  911): getNetworkInfo networkType=55 called by com.htc.android.mail (3480/10064)
,D/ORMLib  ( 3253): put()
,I/EASAppSvc( 3480): [ NA ]- onDestroy(),
,I/EASAppSvc( 3480): [ NA ]> uninitEASService
,I/EASRequestController( 3480): [ NA ]release
,I/EASAppSvc( 3480): [ NA ]< uninitEASService
,I/ActivityManager(  911): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3518 uid=10068 gids={50068, 3003, 5012}
,D/Process (  911): killProcessQuiet, pid=3297
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3297:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3297
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 3253): put()
,I/SocialFeedProvider( 1254): +disConnect socialManager
,I/SocialFeedProvider( 1254): disconnect socialManager
,I/SocialFeedProvider( 1254): -disConnect socialManager
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=1777, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=1777, uid=10029, userID:0
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=1777, uid=10029, userID:0
,I/ActivityManager(  911): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3532 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  911): sending alarm PendingIntent{4265cb88: PendingIntentRecord{42662ab8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457094258745, Int=0
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
,W/SystemReader( 1238): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1254): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/ImageRamCache( 3532): create image Cache, size: 31457280.
I/ImageRamCache( 3532): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3532): create image Cache, size: 12582912.
I/Launcher( 1254): Deferring update until onResume
,D/Launcher( 1254): waitUntilResume // bindAppsUpdated
,I/FeedSettings( 3532): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3532): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3532): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3532): changeLocale(): en_GB
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/Prism.AllAppsOptionsMa_( 3532): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3532): loadGridSize() with Alternative
,I/ActivityManager(  911): Resuming delayed broadcast
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,E/ExternalAccountType( 1326): Unsupported attribute readOnly
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "smsto"
,D/Process (  911): killProcessQuiet, pid=3199
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/ActivityManager(  911): Killing 3199:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3199
,I/SocialManager[SocialBiLogHelper]( 3532): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3532): last commit ulog time 1457013622347
,I/SocialManager[SocialBiLogHelper]( 3532): skip commit this time
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mms"
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
W/ContextImpl( 3459): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  911):   Scheme: "mmsto"
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3459): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3459): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3459): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,W/PackageManager(  911): Unable to load service info ResolveInfo{428c0210 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
,I/MediaStoreImporter( 3417): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/AutoSetting( 1304): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1304): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1304): service - requestNLP() NetworkLocationProvider not enabled
,D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  911): start
,I/GCoreNlp( 1203): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  911): applying state to connected service
,D/PMS     (  911): acquireWL(42a22cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42a22cf0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  911): applying state to connected service
,D/PMS     (  911): acquireWL(4247d600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4247ddb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4247d600): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4247ddb0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42730988): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42730988): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(425f8500): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1485 10014 null
,D/Process (  911): killProcessQuiet, pid=3212
,I/ActivityManager(  911): Killing 3212:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  911): Recipient 3212
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  911): releaseWL(425f8500): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,D/DFPI.PIReciver( 3239): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3239): onHandleIntent
,I/DFPI.ApkInstallService( 3239): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3239): check CID = HTC__032
,I/DFPI.ApkInstallService( 3239): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  911): sending alarm PendingIntent{42607660: PendingIntentRecord{426110e8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457094260269, Int=0
,I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1254): loadItems() com.htc.launcher.pageview.WidgetManager@41ca9ea8 +
,I/Prism.WidgetManager( 1254): onLoadItems() +
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 6 times.
,E/Prism.WidgetManager( 1254): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1254): onLoadItems() -
,I/Prism.ItemManager( 1254): loadItems() com.htc.launcher.pageview.WidgetManager@41ca9ea8 -
,I/ActivityManager(  911): Resuming delayed broadcast
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3459): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3459): SoundPickerReceiver [onReceive] startService,
I/SoundPicker( 3459): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3459): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3459): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3459): MODE_GSM access default DB
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  911): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3459): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPi,cker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3459): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3459): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3459): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/PhoneApp( 1221): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1221): -- N1 =0
,D/PhoneApp( 1221): -- N2 =0
,D/PhoneApp( 1221): -- N3 =0
,I/MediaStoreImporter( 3417): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  911): Resuming delayed broadcast
D/TelephonyReceiver( 1221): bind: false
D/TelephonyReceiver( 1221): switchBindHtcMsgCursor: null
,I/ActivityManager(  911): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3563 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  911): killProcessQuiet, pid=3318
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3318:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3318
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3576 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  911): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1111): com.htc.updater (true,33751552)
D/NotificationService(  911): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41d797e0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.updater 4 8 0 10
,I/RemoteViews( 1111): com.htc.updater (true,33751552)
I/ActivityManager(  911): Resuming delayed broadcast
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41d3c570 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.htc.updater 1 8 1 10
I/ActivityManager(  911): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3346
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3346:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
,D/Prism.PackageStateRece_( 1254): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Recipient 3346
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2598): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/PMS     (  911): acquireWL(4269e5d8): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4269e5d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42053f28): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42053f28): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42326810): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42326810): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(425f9c38): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(425f9c38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(421b7a38): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(421b7a38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42309530): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42309530): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42561458): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,W/asset   ( 2598): Copying FileAsset 0x5cc54eb0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2598): UpdateCorporaTask done [took 459 ms] updated apps [took 459 ms] 
,V/AlarmManager(  911): sending alarm PendingIntent{42641f38: PendingIntentRecord{42600e20 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1457094262044, Int=0
,I/iu.UploadsManager( 1777): End new media; added: 0, uploading: 0, time: 86 ms
,I/Icing   ( 1777): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
,D/Icing   ( 1777): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1777): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
,I/Icing   ( 1777): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
,I/Icing   ( 1777): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
,D/PMS     (  911): releaseWL(42561458): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3604 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 3604): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3604 dbg=false s=true
,I/DeviceManagement( 3604): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3617 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,W/GAV2    ( 3617): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  911): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42724210 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3637 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/GAV2    ( 3617): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  911): killProcessQuiet, pid=3333
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3333:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3333
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  911): Client connection lost with reason: 4
,I/htcbackup-core( 3637): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3637): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3637): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3604): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3604): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.lockscreen, com.htc.autobot.cargps.provider, com.qualcomm.timeservice, com.android.settings, com.htc.smartdim, com.android.keychain, com.qualcomm.privinit, com.htc.backup, com.htc.home.personalize, com.android.inputdevices, com.htc.android.htcsetupwizard, com.android.providers.settings, com.htc.guide, com.htc.cirmodule, android, com.htc.htcpowermanager, com.htc.mirrorlinkserver, com.htc.usage, com.htc.checkinprovider, com.htc.android.htcloglevel, com.android.location.fused, com.android.CSDFunctionG, com.htc.feedback, com.htc.backupreset, com.htc.drive.activator]
,D/Process (  911): killProcessQuiet, pid=3365
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3654 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  911): Killing 3365:com.android.settings/1000 (adj 15): empty #17
I/DeviceManagement( 3604): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/DeviceManagement( 3604): WorkflowService: Starting workflow service
I/DeviceManagement( 3604): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41c50728] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3604): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 3604): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3604): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3604): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3654):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  911): Recipient 3365
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3671 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/DeviceManagement( 3604): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 3604): SessionStateController: Checking invariants...
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(427651c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3671 10160 null
,D/PMS     (  911): releaseWL(427651c8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(42612b78): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3671 10160 null,
,I/DeviceManagement( 3604): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3604): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41c50728]
,I/DeviceManagement( 3604): WorkflowService: Stopping workflow service
,D/Process (  911): killProcessQuiet, pid=3382
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3382:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3382
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(429fac30): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3671 10160 null
,D/PMS     (  911): releaseWL(42612b78): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  911): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=3695 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3671/10160)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.apps.plus (3671/10160)
,D/HtcFingerPrintQuickLaunchProvider( 3695): -onCreate()
,D/Process (  911): killProcessQuiet, pid=3224
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/Settings:HtcSettingsApplication( 3695): [3695/3695] onCreate()
D/PMS     (  911): releaseWL(429fac30): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  911): Killing 3224:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3224
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3711 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  911): killProcessQuiet, pid=2002
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 2002:com.htc.sense.mms/u0a65 (adj 15): empty #17
,D/Settings:HtcWirelessFeatureFlags( 3695): id/is att sku: 99/false
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 2002
,W/SystemReader( 3695): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/SystemReader( 3695): Cannot find support_harman, use default value instead
,W/SystemReader( 3695): Cannot find effect_manager_id, use default value instead
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3711, uid=10074, userID:0
,E/Settings:HtcWrapHeaderInfo( 3695): no such activity!
,D/Finsky  ( 3711): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3711/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3695): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3695): updateDevelopment, bPrefShow = true
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): acquireWL(42783f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(42783f68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
,D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/Settings:HtcUmcWidgetEnabler( 3695): isSupportMusicChannel(): false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]support         :false
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  911): << updateStatus
,W/FingerprintManager( 3695): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3695): isSupportVoWifi: null
I/ActivityManager(  911): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3695): Failed to find provider info for com.htc.vowifi
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  911): getAllNetworkInfo called by com.android.vending (3711/10074)
,D/Finsky  ( 3711): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,W/Settings( 3711): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3711): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3695): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3695): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3695): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3695): [supportHomeButton]support         :false
,W/FingerprintManager( 3695): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3695): isSupportVoWifi: null
I/ActivityManager(  911): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3695): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3711, uid=10074, userID:0
,D/Finsky  ( 3711): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Ads     ( 3711): Skipping gmscore version check
,D/Finsky  ( 3711): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3711): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 1777): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/Finsky  ( 3711): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,D/Finsky  ( 3711): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/Process (  911): killProcessQuiet, pid=3253
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1777): Loading module APK com.google.android.play.games
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Killing 3253:com.htc.task/u0a71 (adj 15): empty #17
,D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
I/ActivityManager(  911): Recipient 3253
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/dalvikvm( 1777): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1777): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 1777): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 1777): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,D/PMS     (  911): acquireWL(424c2a48): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
D/PMS     (  911): releaseWL(424c2a48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(424bd018): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
,W/BaseAppContext( 1777): Using Auth Proxy for data requests.
W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1777): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1777): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1777): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1777): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1777, uid=10029, userID:0
,I/PeopleDatabaseHelper( 1777): cleanUpNonGplusAccounts done.
,W/dalvikvm( 1777): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 7 times.
,D/Finsky  ( 3711): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3711): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  911): sending alarm PendingIntent{42106740: PendingIntentRecord{429a9c68 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457094265763, Int=0
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3711): [NET] getaddrinfo-,err=8
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3711): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3711): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ActivityManager(  911): Resuming delayed broadcast
,D/AsyncTaskServiceImpl( 1777): Submit a task: k
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1777): Processing package: com.example.hello
I/ActivityManager(  911): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,D/GassUtils( 1777): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 1777): Found info for package com.example.hello in db.
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,I/Icing   ( 1777): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
,D/libc    ( 3711): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
,D/libc    ( 3711): [NET] getaddrinfo_proxy+
,W/asset   ( 1777): Copying FileAsset 0x65678c20 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7,
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3711): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/Finsky  ( 3711): [1] DailyHygiene.access$600: Logging device features
,D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
I/Icing   ( 1777): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,V/AlarmManager(  911): sending alarm PendingIntent{42979778: PendingIntentRecord{427bf108 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1457094266254, Int=0
,D/Finsky  ( 3711): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
D/PMS     (  911): releaseWL(424bd018): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WearableService( 1203): callingUid 10029, callindPid: 1203
,D/DeviceConnectionService( 1203): client connected with version: 8296000
,D/Finsky  ( 3711): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3711): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/ActivityManager(  911): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/IcingCorporaProvider( 2598): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2598): UpdateCorporaTask done [took 43 ms] updated apps [took 43 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(426eec60): PARTIAL_WAKE_LOCK  AsyncService 0x1 3671 10160 null
,D/PMS     (  911): releaseWL(426eec60): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,W/dalvikvm( 3711): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/PackageBroadcastService( 1777): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  911): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  911): acquireWL(42950640): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1777, uid=10029, userID:0
,I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3784 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,W/GAV2    ( 3784): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  911): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3480
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3480:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3480
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  911): Client connection lost with reason: 4
,D/PMS     (  911): acquireWL(4292b758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3807 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,D/PMS     (  911): releaseWL(4292b758): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Gmail   ( 3784): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3784): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3784): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3784): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Babel   ( 3807): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3807): MmsConfig.loadMmsSettings
,W/dalvikvm( 3807): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3807): VFY: unable to resolve instance field 36
,W/dalvikvm( 3807): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3807): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  911): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=3833 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3807, uid=10111, userID:0
,W/Settings( 3807): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3807, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3807, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3807, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3807, uid=10111, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3807, uid=10111, userID:0
,D/MessageFrequencyProvider( 3833): onCreate
D/PMS     (  911): acquireWL(42a27b00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3807 10111 null
,I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
V/GetPrviateResource( 3833): GetPrviateResource
V/GetPrviateResource( 3833): GetPrviateResource
D/MmsCustomizationProvider( 3833): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3833): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 3807): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3807): MmsConfig.loadFromDatabase
,D/Process (  911): killProcessQuiet, pid=3518
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  911): Killing 3518:com.htc.task.gtask/u0a68 (adj 15): empty #17
,E/Babel   ( 3807): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3807): MmsConfig.loadFromResources
,E/Babel   ( 3807): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3807): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  911): Recipient 3518
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ProviderInstaller( 3807): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 3833): sense_version=6.0
,D/BTAccessoryUtil( 3833): createReceiver
,D/BTAccessoryUtil( 3833): registerReceiver return intent = null
D/MessageCustFlag( 3833): sku_id=99
,W/SystemReader( 3833): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 3833): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3833): networkCode: 
,D/MessageCustFlag( 3833): sku_id=99
D/MmsConfig( 3833): SIE smsPri: null
,D/MmsConfig( 3833): networkCode: 
,D/HtcTelephonyCapability( 3833): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 3833): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3833): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3833): Cannot find qct_8960_interface, use default value instead
D/PMS     (  911): releaseWL(42a27b00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(42956720): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3807 10111 null
I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  911): releaseWL(42956720): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/Process (  911): killProcessQuiet, pid=3532
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3532:com.htc.sense.news/u0a76 (adj 15): empty #17
,D/LocationInitializer( 1777): Restart initialization of location
,E/MDM     ( 1203): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  911): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 2260): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 2260): Proximity feature is not enabled.
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  911): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  911): Resuming delayed broadcast
I/ActivityManager(  911): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
D/PMS     (  911): acquireWL(427bce60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1203): location=null
D/PMS     (  911): releaseWL(427bce60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(427bb4b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Recipient 3532
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(427bb4b0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427b8be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(427b8be8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1203): No location to return for getLastLocation()
,W/FusedLocationProvider( 1203): location=null
D/PMS     (  911): acquireWL(427947c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  911): releaseWL(427947c8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by com.google.android.gms (1777/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/GCM     ( 2260): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,D/PMS     (  911): acquireWL(42756160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(42756160): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41e05c10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(41e05c10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42646fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(42646fd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42700e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(42700e40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1777): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1777): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  911): releaseWL(42950640): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(41eaf800): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  911): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3878 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(41eaf800): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(427843c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3878 10071 null
,D/PMS     (  911): acquireWL(4247f388): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3878 10071 null
,D/Process (  911): killProcessQuiet, pid=3239
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  911): Killing 3239:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
E/TodoTaskNotifyService( 3878): java.lang.NullPointerException
D/PMS     (  911): releaseWL(427843c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  911): acquireWL(42942248): PARTIAL_WAKE_LOCK  NetworkStats 0x1 911 1000 null
W/System.err( 3878): java.lang.NullPointerException
W/System.err( 3878): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3878): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3878): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3878): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3878): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3878): stopSelfResult true,
D/PMS     (  911): releaseWL(4247f388): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/PMS     (  911): releaseWL(42942248): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  911): acquireWL(42770998): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3807 10111 null
,D/ConnectivityService(  911): Sampling interval elapsed, updating statistics ..
,D/PMS     (  911): releaseWL(42770998): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  911): Done.
,I/WSP     ( 1304): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/ConnectivityService(  911): Setting timer for 720seconds
D/WeatherUtility( 1304): Weather sync is On
I/WSP     ( 1304): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Mar 04 14:24:27 CET 2016
,W/WSP     ( 1304): [Receiver] can't get active network info
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
,V/WSP     ( 1304): [SyncService] no data connection, stop sync service
D/ConnectivityService(  911): getActiveNetworkInfo called by com.htc.sense.hsp (1304/10055)
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  911): Recipient 3239
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TodoTaskshortcut( 3878): update TASK shortcut>
,W/MediaManager( 3399): [DualLensScanUtil]	mmpCursor count is 0
,I/SensorManager(  911): mEventCount = 600
,W/MediaManager( 3399): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): acquireWL(42a27a38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3807 10111 null
I/ActivityManager(  911): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  911): releaseWL(42a27a38): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
I/ActivityManager(  911): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  911): Resuming delayed broadcast
,I/IcingCorporaProvider( 2598): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  911): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  911): acquireWL(429e42f8): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(429e42f8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429da248): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(429da248): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429d40e8): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(429d40e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429ba648): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(429ba648): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429aea08): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(429aea08): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429a4258): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(429a4258): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42977100): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
I/GAV2    ( 3617): Thread[GAThread,5,main]: No campaign data found.
,I/GAv4-SVC( 1777): Google Analytics 8.4.89 is starting up.
D/PMS     (  911): releaseWL(42977100): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2598): UpdateCorporaTask done [took 377 ms] updated apps [took 377 ms] 
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  911): acquireWL(42957508): PARTIAL_WAKE_LOCK  AsyncService 0x1 3671 10160 null
,D/PMS     (  911): releaseWL(42957508): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  911): Resuming delayed broadcast
,D/PackageBroadcastService( 1777): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1777): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
D/PMS     (  911): acquireWL(4294a1c0): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1777): updateResources: need to parse f{com.google.android.gms}
,W/MediaManager( 3399): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(4269c308): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3417 10154 null
,I/ActivityManager(  911): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3417): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3417, uid=10154, userID:0
,I/MusicLeanback( 3417): Conditions not met for autocaching.
,I/MusicLeanback( 3417): Stop autocaching.
,W/ContextImpl( 3417): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  911): releaseWL(4269c308): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  911): Resuming delayed broadcast
,I/ActivityManager(  911): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3923 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1777, uid=10029, userID:0
,I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1777, uid=10029, userID:0
,I/CheckinService( 1777): Done disabling old GoogleServicesFramework version
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1777, uid=10029, userID:0
,D/SyncApplication( 3923): Loading default preferences
,W/Resources( 3923): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  911): New client listening to asynchronous messages
,D/SyncApplication( 3923): Overriding preferences with custom values
,D/SyncApplication( 3923): Updating preferences succeeded
,E/SyncApplication( 3923): Application created.
D/VolumeInfo( 3923): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3923): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3923): Found 0 mount point(s)
,V/VolumeInfo( 3923): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3923): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 3923): getNewCalendarAuthority()...
,D/VolumeInfo( 3923): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3923): Can not create volume ID for unmounted volume null
,D/SyncApplication( 3923): enableAppOperation()+
,D/SyncApplication( 3923): enableAppOperation()-
,D/HTCUtilities( 3923): isNeorSinged() + 
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3923, uid=10008, userID:0
W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  911):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3923, uid=10008, userID:0
,W/PackageManager(  911): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3923): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3923): isNeorSinged() return false
,D/CDMountReceiver( 3923): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3923): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 3923): enable CD Auto-mount: true
,D/DotMatrix( 1537): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 3923): enable auto-mount
,D/HTCUtilities( 3923): enable auto-mount
I/ActivityManager(  911): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  911): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews( 1111): com.nero.android.htc.sync (false,0)
I/ActivityManager(  911): Resuming delayed broadcast
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41c25420 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  911): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/RemoteViews.Performance( 1111): com.nero.android.htc.sync 2 12 4 11
,I/RemoteViews( 1111): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1111): release indeterminate drawable android.widget.OnDemandProgressBar{41e3e2b0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1111): com.nero.android.htc.sync 1 9 3 16
,W/MediaManager( 3399): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  911): Resuming delayed broadcast
,D/PMS     (  911): acquireWL(428c3480): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3711 10074 null
,I/ActivityManager(  911): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
,D/Finsky  ( 3711): [406] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Messaging( 3833): mNeedToUpdateDate2 start
,D/MmsConfig( 3833): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 3833): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3833): 
D/MmsAsyncWorkHandler( 3833): HM tk = 20001
D/ReportIndicatorCache( 3833): MSG_QUERY_REPORTS >>
,D/SettingsManager( 3833): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41c203a8
,I/Messaging( 3833): mccmnc> 
D/DraftCache( 3833): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3833): [DraftCache/1] refresh
,D/MmsConfig( 3833): networkCode: 
,D/Messaging( 3833): ViewCache CreatePreloadOnlyConversationList
,V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2260): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 3833): sense_version=6.0
D/PhoneStorageUtil( 3833): HtcWrapEnvironment.getSupportedStorages() >1
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3711): [NET] getaddrinfo-,err=8
D/libc    ( 3711): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3711): [NET] getaddrinfo-, 1
D/libc    ( 3711): [NET] getaddrinfo_proxy+
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1221):  phoneType = -1
D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/Jerry   ( 3833): start to preload cursor >>>>>>>
D/libc    (  365): [NET] get_iface_protocol fail: 
D/PhoneStorageUtil( 3833): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/PhoneStorageUtil( 3833): createReceiver
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3711): [NET] getaddrinfo_proxy-
,D/Messaging( 3833): mNeedToUpdateDate2: false
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1221):  phoneType = -1
D/TelephUtils( 1221): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
V/MmsProvider( 1221): Update uri=content://mms, match=0
,V/MmsProvider( 1221): selection=st=129 AND m_type!=134
,D/Messaging( 3833): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3833): TransactionService is going to be woken up.
D/Messaging( 3833): ViewCache CreatePreload
,D/Messaging( 3833): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 3833): _has_set_default_values_2=true
,V/TransactionService( 3833): 1-Creating TransactionService
I/ActivityManager(  911): Delaying start of: ServiceRecord{42979488 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/PMS     (  911): releaseWL(428c3480): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
D/MsgPreferenceUtils( 3833): def_index: 0
V/TransactionService( 3833): onStartCommand: 1
D/MmsSystemEventReceiver( 3833): unRegisterForConnectionStateChanges
V/TransactionService( 3833): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3833): Loading previous transactions.
D/MsgPreferenceUtils( 3833): globalIndex = 1
D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 57
D/AccFlag ( 1221): device_type: 1
D/MsgPreferenceUtils( 3833): phone state: true
D/MsgPreferenceUtils( 3833): sd state: false
D/MsgPreferenceUtils( 3833): vIndex = 0
D/TransactionService( 3833): Force set service start id to 1
V/TransactionService( 3833): stopSelfIfIdle: unRegisterForConnectionStateChanges
D/MmsSystemEventReceiver( 3833): unRegisterForConnectionStateChanges
,V/TransactionService( 3833): Destroying TransactionService
,D/TransactionService( 3833): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 3833): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/Finsky  ( 3711): [1] VerifyInstalledPackagesReceiver.onReceive: Skipping verification because network inactive
I/ActivityManager(  911): Resuming delayed broadcast
D/PMS     (  911): releaseWL(42732590): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/ConnectivityService(  911): getActiveNetworkInfo called by com.android.vending (3711/10074)
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42759af0 u0 com.htc.musicenhancer/.EnhancerService}
,D/Process (  911): killProcessQuiet, pid=3459
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3459:com.htc.sdm/u0a81 (adj 15): empty #17
,D/PMS     (  911): acquireWL(42919398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(42919398): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1221):  phoneType = -1
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 57
,D/AccFlag ( 1221): sku_id=99
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1221):  phoneType = -1
D/DraftCache( 3833): [DraftCache/385] rebuildCache
,D/MmsSmsV2Provider( 1221): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 3833): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 57
,D/Jerry   ( 1221): URI_DRAFT
D/PMS     (  911): acquireWL(428c7688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
D/DraftCache( 3833): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3833): [DraftCache/385] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 3833): 
D/MmsAsyncWorkHandler( 3833): HM tk = 20002
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1221): sku_id=99
I/ActivityManager(  911): Recipient 3459
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  911): releaseWL(428c7688): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/TelephUtils( 1221): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 57
,D/AccFlag ( 1221): sku_id=99
,D/PMS     (  911): acquireWL(427c2560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(427c2560): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 1777): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1777): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  911): releaseWL(4294a1c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 8 times.
,I/GAV2    ( 3784): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 3807): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 1485): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1485): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  911): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3977 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3977): onCreate
D/ProviderChangeReceiver( 3977): ---------------------------------------------------
,D/ProviderChangeReceiver( 3977): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3977): start to updateAlertNotification!
,I/ActivityManager(  911): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3991 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  911): killProcessQuiet, pid=3563
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  911): Killing 3563:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3563
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AlertService( 3977): No fired or scheduled alerts
D/HtcAlertUtils( 3977): -- cancelReminderNotification --
D/HtcAlertUtils( 3977): broadcastExistReminder!
D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3991): [3991/3991] onCreate()
W/ContextImpl( 3991): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  911): killProcessQuiet, pid=3576
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3576:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3576
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  911): killProcessQuiet, pid=3617
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3617:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3617
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(42769940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(42769940): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/PowerUI ( 1111): closing low battery warning: level=100
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  911): updateBatteryInfo,
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 9 times.
,I/SensorManager(  911): mEventCount = 750
,D/AutoSetting( 1304): service - handleMessage() stop self
,D/AutoSetting( 1304): service - onDestroy() END
,D/AutoSetting( 1304): service - handleMessage() quit looper
,D/Process (  911): killProcessQuiet, pid=3637
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3637:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3637
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 10 times.
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
D/PMS     (  911): acquireWL(425ad5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
V/AlarmManager(  911): sending alarm PendingIntent{423765c8: PendingIntentRecord{42515aa0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=82264, Int=0
V/AlarmManager(  911): sending alarm PendingIntent{426f1350: PendingIntentRecord{4219c520 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457094280965, Int=0
D/PMS     (  911): releaseWL(425ad5b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 3711): [395] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3711): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 11 times.
,I/SensorManager(  911): mEventCount = 900
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 12 times.
,D/PMS     (  911): acquireWL(426c66c0): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(426c66c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(428d28c0): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(428d28c0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(42982b88): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(42982b88): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1485): handler message = 4011
,E/HtcModeClient( 1485): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1485): Don't start project servcice
,D/HtcModeClient( 1485): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1485): connectState: CONNECTION_READY = false
,D/SilentMusic( 1485): call stop
,D/HtcModeClient( 1485): close connection
,W/HtcModeClient( 1485): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1485): read the terminate packet, so break
,D/Process (  911): killProcessQuiet, pid=3604
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3604:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3604
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  911): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4007 uid=10078 gids={50078}
,D/PMS     (  911): acquireWL(4244b7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10078}
,V/AlarmManager(  911): sending alarm PendingIntent{42918dc8: PendingIntentRecord{426f4cd8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457094296517, Int=60000
,D/PMS     (  911): releaseWL(4244b7b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4007): SMSBackupAgentService started
,D/SMSBackup( 4007): Checking restore status
,D/SMSBackup( 4007): Restore complete
,D/SMSBackup( 4007): cancelCheckAlarm
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,D/SMSBackup( 4007): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/Process (  911): killProcessQuiet, pid=3654
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3654:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3654
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  911): mEventCount = 1050
,D/PMS     (  911): acquireWL(42552908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42112f98: PendingIntentRecord{41ec3e10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=98855, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(42552908): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1111): now=1457094300056 next=59944
,V/LightsService(  911): setLight #0: color=#26
,V/LightsService(  911): setLight #0: color=#23
,V/LightsService(  911): setLight #0: color=#19
,V/LightsService(  911): setLight #0: color=#14
,I/PMS     (  911): Going to sleep due to screen timeout...
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@422d6d60
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = CM36282 Light sensor
,I/ActivityManager(  911): mThumbnailWidth=360, mThumbnailHeight=640
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@422d6d60, eanble = 0, strlen(mName) = 59
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  911): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208db00
W/SensorService(  911): Listener[1] = com.htc.smartdim.sensor_eye@424c44b0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/BatSI   (  911): Couldn't get kernel wake lock stats
V/LightsService(  911): setLight #2: color=#0
D/qdlights(  911): set_light_buttons_func: on=0 brightness=0
V/LightsService(  911): setLight #0: color=#0
,D/WirelessDisplayService(  911): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  911): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  911): mWirelessDisplayManager is null
,I/SensorManager(  911): mEventCount = 1200
,D/SurfaceControl(  911): Excessive delay in blankDisplay() while turning screen off: 337ms
D/PMS     (  911): nativeSetInteractive:false
D/PMS     (  911): nativeSetInteractive:false done
D/PMS     (  911): nativeSetAutoSuspend:true
D/PMS     (  911): nativeSetAutoSuspend:true done
D/HABCtrl (  911): TPE algorithm. remove timeout.
D/PMS     (  911): OOBE c monitor 11
,V/KeyguardServiceDelegate(  911): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@428dc4d0)
D/NfcService( 1238): ScreenObserver: OFF
,D/NfcService( 1238): applyRouting - 0
I/InputMethodManagerService(  911): screenObserver, isScreenOn=false
I/InputMethodManagerService(  911): Disable input method client, pid=2955
D/PMN     (  911): wakingUp
I/InputManager(  911): Cancel all due to getting PMS screen off broadcast
D/PMS     (  911): acquireWL(429bd1f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1238 1027 null
,V/KeyguardServiceDelegate(  911): **** SHOWN CALLED ****
,D/NfcService( 1238): applyRouting -2
I/WindowManager(  911): No lock screen! windowToken=null
D/PMS     (  911): releaseWL(429bd1f0): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/IntentController( 1111): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,D/WirelessDisplayService(  911): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): acquireWL(4273e7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
D/PMN     (  911): onScreenOn
I/BatteryService(  911): n_update end
D/PMS     (  911): releaseWL(4273e7f8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,D/MtpService( 2478): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2478): [MTP][onReceive]-
,D/NfcService( 1238): applyRouting - 0
,D/AutoSetting( 1304): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1238): applyRouting -2
I/HtcPowerSaver(  911): << updateStatus
D/AlarmManager(  911): ACTION_SCREEN_ON
I/AlarmManager(  911): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done recovering
I/AlarmManager(  911): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  911): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  911): acquireWL(42718d78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1238 1027 null
D/PMS     (  911): releaseWL(42718d78): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
,D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  911): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  911): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_ON
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1304): service - onCreate()
D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 1
D/WifiNative-wlan0(  911):    returned false
,D/AutoSetting( 1304): service - AddressCache: using context: com.htc.Weather
V/NotificationService(  911): batLight: Full, plugged
V/LightsService(  911): setLight #8: color=#c8c800
D/qdlights(  911): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  911): setLight #8: color=#c800
D/qdlights(  911): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  911): [LedInfo] has indicator attribute
D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  911): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/TetherSettings( 3695): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3695): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3695): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3695): Cust_ConnectToPC   : spcsc>false
D/        ( 3695): Cust_ConnectToPC   : IPT>true
D/        ( 3695): Cust_ConnectToPC   : Singel_USB>false
D/WirelessDisplayService(  911): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/AutoSetting( 1304): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/ClockThread( 1111): stop update clock
D/LocationManagerService(  911): request 424a5d40 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  911): provider request: passive ProviderRequest[ON interval=0]
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,D/NetworkPolicy(  911): updateScreenOn: false
W/Settings( 3695): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3695): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3695): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3695): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,I/PSReceiver( 3695): onReceive:android.intent.action.USER_PRESENT
,W/ContextImpl( 3695): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3695): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3695): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3695):  defaultType:0
,I/ActivityManager(  911): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4034 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  911): acquireWL(429fd678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  911): releaseWL(429fd678): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4292e498): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4292e498): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208db00
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 2
W/SensorService(  911): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@4208db00, eanble = 0, strlen(mName) = 91
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  911): Listener[0] = com.htc.smartdim.sensor_eye@424c44b0
,W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  911): goingToSleep
D/PMS     (  911): acquireWL(428c51a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 911 1000 null
,D/AlarmManager(  911): ACTION_SCREEN_OFF
I/AlarmManager(  911): [AlarmQueuing] screen off now: 
I/AlarmManager(  911): [AlarmQueuing] data connection: true
,I/AlarmManager(  911): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  911): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  911): stopDataStallAlarm: current tag=20854 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  911): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  911):    returned false
D/PMS     (  911): releaseWL(428c51a8): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
W/ContextImpl( 4034): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  911): acquireWL(428e2e28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 911 1000 null
,D/PMS     (  911): releaseWL(428e2e28): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
V/SRS_Proc(  372): ParamSet string: screen_state=off
,D/NetworkPolicy(  911): updateScreenOn: false
,D/ContactMessageStore( 1221): start background delete task...
D/ContactMessageStore( 1221): size: 0 , 0
,D/ContactMessageStore( 1221): Background delete complete
,D/SmartSyncUtils( 4034): isEpsOn(), nState = 0
D/PMS     (  911): acquireWL(429bb8a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4034 1000 null
,D/PMS     (  911): releaseWL(429bb8a8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 4034): getMobilePolicyEnabled, result = true
W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4034): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4034): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4034): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4034): isEpsOn(), nState = 0,
I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424c44b0
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  911): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 1
D/WifiService(  911): New client listening to asynchronous messages
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  911): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424c44b0, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  911): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  911): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  911): pid=911, uid=1000
W/SensorService(  911): Active sensors: size = 0
W/SensorService(  911): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@424c44b0, eanble = 0, strlen(mName) = 36
W/SensorService(  911): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  911): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  911): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@424c44b0
E/ActivityThread(  911): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425cee20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425cee20 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  911): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  911): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  911): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  911): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  911): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  911): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  911): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  911): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  911): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  911): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  911): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  911): acquireWL(42918100): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] getTotalRam: 1873 Mb
D/PMS     (  911): releaseWL(42918100): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(422386b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(422386b8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1304): service - mHandler: cancel location update
,D/AutoSetting( 1304): service -           changes count: 0
,D/Process (  911): killProcessQuiet, pid=3440
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3440:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3440
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  911): Waited long enough for: ServiceRecord{42966c40 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  911): acquireWL(42792248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  911): updateBatteryInfo
D/PMS     (  911): releaseWL(42792248): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  911): acquireWL(42755108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{42720bb0: PendingIntentRecord{42612c10 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137685, Int=0
,D/PMS     (  911): releaseWL(42755108): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1304): service - handleMessage() stop self
,D/AutoSetting( 1304): service - handleMessage() quit looper
,D/AutoSetting( 1304): service - onDestroy() END
,D/Process (  911): killProcessQuiet, pid=3878
,D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  911): Killing 3878:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  911): Recipient 3878
,I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  911): acquireWL(4276ddf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{426be988: PendingIntentRecord{42715cd0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126252, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{423765c8: PendingIntentRecord{42515aa0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=142282, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{4222f3a8: PendingIntentRecord{4257b090 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=142293, Int=0
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  911): [NET] getaddrinfo-,err=8
,D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  911): [NET] getaddrinfo-, 1
,D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
D/PMS     (  911): acquireWL(429340c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,D/PMS     (  911): releaseWL(429340c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  911): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  911): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  911): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  911): acquireWL(42a0a0e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 911 1000 null
D/PMS     (  911): releaseWL(4276ddf0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): releaseWL(42a0a0e8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  911): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  911): acquireWL(428cd120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{1000}
,V/AlarmManager(  911): sending alarm PendingIntent{42112f98: PendingIntentRecord{41ec3e10 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=158856, Int=0
,I/IntentController( 1111): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  911): releaseWL(428cd120): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  911): acquireWL(427a0238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  911): releaseWL(427a0238): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,I/ClearcutLoggerApiImpl( 2260): disconnect managed GoogleApiClient
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1221): switchBindHtcMsgCursor: null
,D/PMS     (  911): acquireWL(429e8270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  911): n_update end
,D/PMS     (  911): releaseWL(429e8270): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  911): updateBatteryInfo
D/PowerUI ( 1111): closing low battery warning: level=100
,I/IntentController( 1111): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/PowerUI ( 1111): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/UsbnetService(  911): BroadcastReceiver::onReceive+
D/UsbnetService(  911): onReceive BATTERY_CHANGED
D/UsbnetService(  911):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  911): BroadcastReceiver::onReceive-
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1537): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1537): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  911): runPSCheck
D/HtcPowerSaver(  911): Checking...
I/HtcPowerSaver(  911): >> updateStatus
,I/HtcPowerSaver(  911): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  911): << updateStatus
,I/BatteryController( 1111): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  911): acquireWL(4274d988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 911 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  911): sending alarm PendingIntent{428d3e00: PendingIntentRecord{42715cd0 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186079, Int=0
,V/AlarmManager(  911): sending alarm PendingIntent{423765c8: PendingIntentRecord{42515aa0 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=202319, Int=0
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  911): [NET] getaddrinfo-,err=8
D/libc    (  911): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  911): [NET] getaddrinfo-, 1
D/libc    (  911): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  911): [NET] getaddrinfo_proxy-
D/PMS     (  911): releaseWL(4274d988): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  911): acquireWL(4297ca18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,D/PMS     (  911): acquireWL(4290ffc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4297ca18): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(4290ffc8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429296f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(429296f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(4296fe10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): acquireWL(427adcb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1203): Vacuum at: now=1457094403763 tag=VacuumService
D/PMS     (  911): releaseWL(4296fe10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): releaseWL(427adcb0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(428d1928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(428d1928): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  911): acquireWL(429de298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 2260 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  911): getActiveNetworkInfo called by  (2260/10029)
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024274
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024606
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024685
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024693
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024705
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360024710
W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025909
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360025924
,W/AlarmManager(  911): Converted elapesd time is over 1 year! when = 315360027197
,D/PMS     (  911): releaseWL(429de298): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4065): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4065): ====startRecUseTime====
D/htc.customization.log.level( 4065):  is 
W/CustomizationLogLevel( 4065): Level value is invalid, use default level 2
D/CustomizationManager( 4065):  Read ACC file spent 0.065 (s)
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4065): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4065): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4065): Parsing tag category name = system
I/CustomizationCIDLoader( 4065): Parsing tag category name = application
I/CustomizationCIDLoader( 4065): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4065): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4065): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4065): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4065): Parsing tag category name = Settings
D/CustomizationManager( 4065):  Read CID file spent 0.106 (s)
D/CustomizationManager( 4065):  All configurations done spent 0.106 (s)
W/HtcNativeFlag( 4065): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4065): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4065): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4065): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  911): deletePackageAsUser: pkg=com.example.hello, pid=4065, uid=2000 user=0
I/ActivityManager(  911): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
D/Process (  911): killProcessQuiet, pid=2955
W/asset   (  911): Copying FileAsset 0x62e00ed8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  911): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  911): Killing 2955:com.example.hello/u0a397 (adj 0): stop com.example.hello
I/ActivityManager(  911):   Force finishing activity ActivityRecord{4242de60 u0 com.example.hello/.MainActivity t2}
W/PackageSettings(  911): Skipping PackageSetting{42366da8 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  911): Force stopping com.example.hello appid=10397 user=0: pkg removed
E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder(  911): !!! FAILED BINDER TRANSACTION !!!
E/JavaBinder( 1187): !!! FAILED BINDER TRANSACTION !!!
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1111): ApplicationsIntentReceiver replacing:false
W/InputMethodManagerService(  911): Got RemoteException sending setActive(false) notification to pid 2955 uid 10397
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1537): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1537): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
D/AccTypeManager( 1326): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  911): acquireWL(4283b910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1203 10029 WorkSource{10029 com.google.android.gms}
W/GeofencerStateMachine( 1203): Ignoring removeGeofence because network location is disabled.
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
D/VoicemailCleanupService( 1268): Cleaning up data for package: com.example.hello
W/InputDispatcher(  911): channel '429bdc80 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  911): channel '429bdc80 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  911): WIN DEATH: Window{429d8af8 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher(  911): Attempted to unregister already unregistered input channel '429bdc80 com.example.hello.MainActivity (s)'
I/WindowState(  911): WIN DEATH: Window{429bdc80 u0 com.example.hello/com.example.hello.MainActivity}
W/AccTypeManager( 1326): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1326): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
D/PMS     (  911): releaseWL(4283b910): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/InputMethodManagerService(  911): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/[PluginManager]RegisterService( 1304): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/WindowManager(  911): WINDOW DIED Window{429bdc80 u0 com.example.hello/com.example.hello.MainActivity}
I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1254): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/[PluginManager]RegisterService( 1304): handle notify Blinkfeed plugin client changed
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
W/SystemReader( 1238): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1254): Deferring update until onResume
D/Launcher( 1254): waitUntilResume // bindAppsRemoved
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
E/ExternalAccountType( 1326): Unsupported attribute readOnly
D/Prism.PackageStateRece_( 1254): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "sms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "smsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/IcingCorporaProvider( 2598): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mms"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  911):   Action: "android.intent.action.SENDTO"
I/PackageManager(  911):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  911):   Scheme: "mmsto"
I/PackageManager(  911): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
I/ActivityManager(  911): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4080 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
D/PMS     (  911): acquireWL(42613c58): PARTIAL_WAKE_LOCK  Icing 0x1 1777 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2598): UpdateCorporaTask done [took 171 ms] updated apps [took 171 ms] 
W/PackageManager(  911): Unable to load service info ResolveInfo{42561108 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  911): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  911): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  911): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  911): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  911): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  911): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  911): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  911): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  911): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  911): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  911): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  911): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4080): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4080): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4080): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4080): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4080): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4080): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4080): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4080): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4080): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4080): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4080): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4080): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4080): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4080): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4080): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4080): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4080): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4080): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4080): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4080): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4080): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4080): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4080): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4080): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4080): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4080): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4080): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4080): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4080): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4080): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4080): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4080): threadid=11: thread exiting with uncaught exception (group=0x417e7e30)
E/ActivityManager(  911): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4080): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4080): Process: com.google.android.apps.docs, PID: 4080
E/AndroidRuntime( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4080): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4080): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4080): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4080): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4080): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
E/SQLiteDatabase( 4080): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4080): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4080): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4080): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4080): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4080): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4080): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4080): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4080): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4080): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4080): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4080): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4080): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4080): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4080): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4080): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4080): Opened ClientFlag.db in read-only mode
D/Process ( 4080): killProcess, pid=4080
D/Process ( 4080): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  911): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4098 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/RemoteDisplayProvider(  911): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  911): start
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  911): Recipient 4080
I/ActivityManager(  911): Process com.google.android.apps.docs (pid 4080) has died.
W/AtomicFile(  911): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  911): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/ContextImpl( 4098): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4098): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4098): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4098): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4098): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4098): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4098): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4098): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4098): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4098): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4098): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4098): threadid=10: thread exiting with uncaught exception (group=0x417e7e30)
E/AndroidRuntime( 4098): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4098): Process: com.android.keychain, PID: 4098
E/AndroidRuntime( 4098): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4098): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4098): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4098): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4098): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4098): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4098): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4098): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4098): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4098): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  911): App crashed! Process: com.android.keychain
I/ActivityManager(  911): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4112 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4098): killProcess, pid=4098
D/Process ( 4098): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457094410253.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more
I/ActivityManager(  911): Recipient 4098
I/ActivityManager(  911): Process com.android.keychain (pid 4098) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 4112): getInstance(Context context)
D/AppTag  ( 4112): getInstance(Context context)
D/AppTag  ( 4112): onCreate()
D/PMS     (  911): acquireWL(426b2f18): PARTIAL_WAKE_LOCK  AsyncService 0x1 3671 10160 null
D/PMS     (  911): releaseWL(426b2f18): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3711): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1777): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1777): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1777): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1777): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 1777): Removing dialog suppression flag for package com.example.hello
I/ActivityManager(  911): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
E/SQLiteLog( 1777): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1777): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6567c550
W/dalvikvm( 1777): threadid=35: thread exiting with uncaught exception (group=0x417e7e30)
E/AndroidRuntime( 1777): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1777): Process: com.google.android.gms, PID: 1777
E/AndroidRuntime( 1777): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1777): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1777): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1777): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1777): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1777): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1777): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1777): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1777): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1777): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1777): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1777): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1777): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1777): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  911): App crashed! Process: com.google.android.gms
D/Process ( 1777): killProcess, pid=1777
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process ( 1777): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  911): handleWLDeath(42613c58): PARTIAL_WAKE_LOCK  Icing 0x1
I/ActivityManager(  911): Recipient 1777
I/ActivityManager(  911): Process com.google.android.gms (pid 1777) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 11000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20999ms
I/ActivityManager(  911): Resuming delayed broadcast
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20997ms
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 30996ms
E/SQLiteLog( 2260): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 2260): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x63fb36f8
W/dalvikvm( 2260): threadid=1: thread exiting with uncaught exception (group=0x417e7e30)
E/ActivityManager(  911): App crashed! Process: com.google.process.gapps
E/AndroidRuntime( 2260): FATAL EXCEPTION: main
E/AndroidRuntime( 2260): Process: com.google.process.gapps, PID: 2260
E/AndroidRuntime( 2260): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2260): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2260): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2260): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2260): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2260): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2260): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2260): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2260): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2260): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2260): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2260): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2260): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2260): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2260): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 2260): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2260): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2260): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 2260): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2260): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2260): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2260): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 2260): 	... 10 more
E/DropBoxManagerService(  911): Can't write: system_app_crash
E/DropBoxManagerService(  911): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  911): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  911): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  911): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  911): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  911): 	... 5 more
D/Process ( 2260): killProcess, pid=2260
I/ActivityManager(  911): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4145 uid=10098 gids={50098, 3003, 5012}
D/Process ( 2260): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/DeviceManagement( 4145): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4145 dbg=false s=true
I/DeviceManagement( 4145): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4145): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/DeviceManagement( 4145): WorkflowService: Starting workflow service
I/DeviceManagement( 4145): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41c44ca8] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4145): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4145): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4145): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4145): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  911): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4159 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4145): BackgroundController: *** Processing package remove for appID=com.example.hello
I/DeviceManagement( 4145): SessionStateController: Checking invariants...
I/ActivityManager(  911): Recipient 2260
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  911): Client connection lost with reason: 4
I/ActivityManager(  911): Process com.google.process.gapps (pid 2260) has died.
W/ActivityManager(  911): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30785ms
D/Documents( 4159): Loading roots for com.android.providers.downloads.documents
D/Documents( 4159): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4159): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4159): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4159): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4159): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4159): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4159): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4159): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4159): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4159): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4159): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4159): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4159): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4159): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4159): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4159): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4159): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4159): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4159): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4159): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4159): threadid=1: thread exiting with uncaught exception (group=0x417e7e30)
E/AndroidRuntime( 4159): FATAL EXCEPTION: main
E/AndroidRuntime( 4159): Process: com.android.documentsui, PID: 4159
E/AndroidRuntime( 4159): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4159): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4159): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4159): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4159): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4159): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4159): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4159): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4159): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4159): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4159): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4159): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4159): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4159): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4159): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4159): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4159): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4159): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4159): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4159): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4159): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4159): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4159): 	... 10 more
I/ActivityManager(  911): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4173 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  911): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4185 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  911): killProcessQuiet, pid=3807
I/ActivityManager(  911): Killing 3807:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  911): killProcessQuiet, pid=3417
D/Process (  911): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ActivityManager(  911): App crashed! Process: com.android.documentsui
I/ActivityManager(  911): Killing 3417:com.google.android.music:main/u0a154 (adj 15): empty #17
D/ErrorReport(  911): HtcErrorReportManager Begin---add error logs to dropbox
I/ActivityManager(  911): Recipient 3417
I/DisplayManagerService(  911): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  911): Client com.google.android.music (pid 3417): Died!
E/ErrorReport(  911): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  911): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457094410837.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  911): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  911): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  911): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  911): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  911): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  911): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  911): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  911): 	... 4 more

```
