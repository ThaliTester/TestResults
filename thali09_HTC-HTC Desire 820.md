#### Test 5038801932cd575_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/HtcFingerPrintQuickLaunchProvider( 2860): -onCreate()
V/Settings:HtcSettingsApplication( 2860): [2860/2860] onCreate()
--------- beginning of /dev/log/system
W/ContextImpl( 2860): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcIntentReceiver.onReceive:54 android.app.ActivityThread.handleReceiver:2687 
I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42958fc0
I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcIntentReceiver
D/Process (  907): killProcessQuiet, pid=2556
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2556:com.htc.showme/u0a83 (adj 15): empty #17
I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@426ac190
I/ActivityManager(  907): Recipient 2556
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/AlarmManager(  907): [AlarmQueuing] cursor: android.content.ContentResolver$CursorWrapperInner@42802fe8
I/ActivityManager(  907): Resuming delayed broadcast
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.apps.maps
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.gsf
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.google.android.location
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.CruiserPwrExpert
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.katana
I/AlarmManager(  907): [AlarmQueuing] add queuing package: jp.naver.line.android
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.viber.voip
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.tencent.mm
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.htc.android.mail
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.sina.weibo
I/AlarmManager(  907): [AlarmQueuing] add queuing package: com.facebook.orca
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.intent.action.GCM_RECONNECT
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS list: package=com.google.android.gms, action=com.google.android.gms.nlp.ALARM_WAKEUP_LOCATOR
I/AlarmManager(  907): [AlarmQueuing] Adding target to EPS screen off list: package=android, action=android.appwidget.action.APPWIDGET_UPDATE
D/Process (  907): killProcessQuiet, pid=2570
D/TetherSettings( 2860): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2860): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2860): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2860): Cust_ConnectToPC   : spcsc>false
D/        ( 2860): Cust_ConnectToPC   : IPT>true
D/        ( 2860): Cust_ConnectToPC   : Singel_USB>false
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2570:com.htc.updater/u0a85 (adj 15): empty #17
W/Settings( 2860): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 2860): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2860): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2860): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2860): Cust_ConnectToPC   : spcsc>false
D/        ( 2860): Cust_ConnectToPC   : IPT>true
D/        ( 2860): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2860): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2860): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2860): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2860): onReceive : android.intent.action.BOOT_COMPLETED hasTethered:false isNSOpening:false
,I/SmartNS_Utility( 2860): setISNotification
I/ActivityManager(  907): Recipient 2570
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SmartNS_Utility( 2860): usb_cable_connect = 1
D/SmartNS_Utility( 2860): usb_denied = 0
I/SmartNS_PSService( 2860): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/SmartNS_Utility( 2860): usb_cable_connect = 1
D/SmartNS_Utility( 2860): usb_denied = 0
I/SmartNS_PSService( 2860): usb notificaiton:true
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (2860/1000)
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/DotMatrix( 1514): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (2860/1000)
D/DotMatrix( 1514): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Process (  907): killProcessQuiet, pid=2599
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2599:com.google.android.partnersetup/u0a32 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2599
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1109): com.android.settings (true,33751552)
D/OnDemandProgressBar( 1109): release indeterminate drawable android.widget.OnDemandProgressBar{42224080 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1109): com.android.settings 3 7 0 10
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/RemoteViews( 1109): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1109): com.android.settings 0 1 10
I/ActivityManager(  907): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2881 uid=9987 gids={49987}
I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@427484a0, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427484a0, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427801c8
W/SensorService(  907): Listener[1] = com.android.server.power.DisplayPowerController$10@425d3d80
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@427484a0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  907): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@427484a0, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{428045f8 u0 ReceiverList{427ed238 907 system/1000/u0 local:42782d28}}
D/NfcUiccLockService( 2881): -- To check whether previous opened channel needed to be closed ...
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 3
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@427484a0, eanble = 1, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@427801c8
W/SensorService(  907): Listener[1] = com.android.server.power.DisplayPowerController$10@425d3d80
W/SensorService(  907): Listener[2] = com.htc.smartdim.sensor_eye@427484a0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/Process (  907): killProcessQuiet, pid=2639
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2898 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
I/ActivityManager(  907): Killing 2639:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2639
D/Process (  907): killProcessQuiet, pid=2659
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=2910 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 2659:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2659
E/cutils-trace( 2895): Error opening trace file: No such file or directory (2)
E/YouTube ( 2910): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 2910): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 2910): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 2910): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/CustomizationManager( 2895): ====startRecUseTime====
D/htc.customization.log.level( 2895):  is 
W/CustomizationLogLevel( 2895): Level value is invalid, use default level 2
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (2910/10168)
E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 2910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
D/CustomizationManager( 2895):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2895): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2895): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2895): Parsing tag category name = system
I/CustomizationCIDLoader( 2895): Parsing tag category name = application
I/CustomizationCIDLoader( 2895): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2895): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2895): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2895): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2895): Parsing tag category name = Settings
D/CustomizationManager( 2895):  Read CID file spent 0.115 (s)
D/CustomizationManager( 2895):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 2895): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2895): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2895): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2895): Fail to get flag for type 'language', use default value: -1
D/YouTube ( 2910): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 2910): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
W/asset   (  907): Copying FileAsset 0x6346ed80 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1119812568
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2895
D/PMS     (  907): acquireHCC(42a2e298): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(42a0fe28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/FeedHostManager( 1252): [onPause]
I/FeedProviderManager( 1252): onPause
I/FeedHostManager( 1252): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41fbed10
I/SocialFeedProvider( 1252): +onPause
I/SocialFeedProvider( 1252): -onPause
D/PMS     (  907): acquireWL(427f5cf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=2951 uid=10396 gids={50396, 3003, 5012, 3001, 3002}
W/asset   ( 2951): Copying FileAsset 0x5c7d9428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/YouTube ( 2910): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
I/TrimMemoryManager( 1252): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 2951): Binding Chromium to main looper Looper (main, tid 1) {41eae460}
I/LibraryLoader( 2951): Expected native library version number "",actual native library version number ""
I/chromium( 2951): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 2951): Initializing chromium process, renderers=0
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42880c38:true
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 2951): 1106001496: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  907): acquireWL(42949878): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  907): acquireWL(429c1290): PARTIAL_WAKE_LOCK  AudioMix 0x1 374 1013 null
D/PMS     (  907): releaseWL(429c1290): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 2951): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 2951): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 2951): Build Date: 08/28/14 Thu
I/Adreno-EGL( 2951): Local Branch: 
I/Adreno-EGL( 2951): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 2951): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 2951):                  aa63bbd948f41d15fc72f585e
I/GAV2    ( 2584): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 1956): Google Analytics 8.3.01 is starting up.
D/YouTube ( 2910): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
W/chromium( 2951): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
W/dalvikvm( 2951): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 2951): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
I/MediaRouter( 2910): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
W/dalvikvm( 2951): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2951): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 2951): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/MediaRouterService(  907): Client com.google.android.youtube (pid 2910): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
W/dalvikvm( 2951): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 2951): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 2951): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 2951): CordovaWebView is running on device made by: HTC
D/YouTube ( 2910): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 2910): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448315171&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.youtube (2910/10168)
D/libc    ( 2910): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2910): [NET] getaddrinfo-,err=8
D/libc    ( 2910): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2910): [NET] getaddrinfo-, 1
D/libc    ( 2910): [NET] getaddrinfo_proxy+
D/libc    (  366): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  366): [NET] get_iface_protocol fail: 
D/libc    (  366): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  366): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  366): [NET] getaddrinfo-,err=7
D/libc    ( 2910): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2910): Error sending ping
E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 2910): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 2910): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 2910): getSelectedRoute
D/YouTube ( 2910): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (2910/10168)
,D/YouTube ( 2910): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
W/AwContents( 2951): nativeOnDraw failed; clearing to background color.
D/YouTube ( 2910): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 2910): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 2910): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/InputMethodManagerService(  907): Disable input method client, pid=1252
W/ResourceType( 2951): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 2951): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41ef51e0, mServedView=org.apache.cordova.engine.SystemWebView{41ebb178 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=2951
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 2951): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +269ms
D/PMS     (  907): releaseWL(427f5cf8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/chromium( 2951): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 2951): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 2951): Set native->JS mode to OnlineEventsBridgeMode
W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/FileApkUtils( 1956): Spent 35ms computing apk sha1.
D/FileApkUtils( 1956): Module already staged or being staged:chimera-modules/MapsModule.apk
D/jxcore_app_log( 2951): JniHelper::setJavaVM(0x41a68010), pthread_self() = 1658424408
D/JX-Cordova( 2951): jxcore cordova android initializing
D/DexOptUtils( 1956): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1956): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
D/GmsModuleFndr( 1956): Beginning GMS chimera module scan
W/asset   ( 1956): Copying FileAsset 0x652a0680 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk:/resources.arsc) to buffer size 369648 to make it aligned.
W/dalvikvm( 1956): VFY: unable to resolve static field 134 (SUPPORTED_ABIS) in Landroid/os/Build;
D/ChimeraCfgMgr( 1956): Beginning module configuration check
D/ChimeraCfgMgr( 1956): Module APKs unchanged, check complete
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(42b25380): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
W/jxcore-log( 2951): Initializing JXcore engine
W/jxcore-log( 2951): JXcore engine is ready
D/PMS     (  907): acquireWL(42b22000): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1956 10029 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
E/dalvikvm( 1956): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1956): VFY: unable to resolve check-cast 408 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1956): VFY: unable to resolve virtual method 1731: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
W/jxcore-log( 2951): Starting JXcore engine
W/dalvikvm( 1956): VFY: unable to resolve static field 162 (SUPPORTED_ABIS) in Landroid/os/Build;
D/GCM     ( 1956): COMPAT: Multi user not supported
D/PMS     (  907): acquireWL(42b21f38): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1320): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1320/10029)
D/PMS     (  907): acquireWL(42b21da8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42b25380): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 1956): Checkin interval check for package: unspecified last checkin: 1448298643009 min interval config: 0 actual interval: 16529300
I/GCoreUlr( 1956): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1202): DispatchingService.onCreate()
I/CheckinService( 1956): Disabling old GoogleServicesFramework version
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
D/SystemUpdateService( 1956): onCreate
D/PMS     (  907): acquireWL(42a9b1c8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  907): acquireWL(42a5f528): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1956, uid=10029, userID:0
D/SystemUpdateService( 1956): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
W/dalvikvm( 1956): VFY: unable to resolve virtual method 208: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
V/AuthZen ( 1956): Handling intent: android.intent.action.BOOT_COMPLETED
D/AuthZenEventHandler( 1956): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  907): acquireWL(4275de60): PARTIAL_WAKE_LOCK  Icing 0x1 1956 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  907): releaseWL(42b22000): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  907): releaseWL(42a9b1c8): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/SystemUpdateService( 1956): cancelUpdate (empty URL)
I/SystemUpdateService( 1956): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1956, uid=10029, userID:0
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/CheckinService( 1956): Checking schedule, now: 1448315172409 next: 1448298672940
I/CheckinService( 1956): active receiver: enabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
D/PMS     (  907): releaseWL(4275de60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1956, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1956/10029)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1956, uid=10029, userID:0
I/GCoreUlr( 1202): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1956, uid=10029, userID:0
W/BaseAppContext( 1956): Using Auth Proxy for data requests.
D/PMS     (  907): releaseWL(42b21f38): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42b21da8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/SystemUpdateService( 1956): onDestroy
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1956): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1956): VFY: unable to resolve virtual method 1040: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
W/dalvikvm( 1956): VFY: unable to resolve virtual method 1135: Landroid/os/UserManager;.isManagedProfile ()Z
W/jxcore-log( 2951): Platform android
W/jxcore-log( 2951): 
W/jxcore-log( 2951): Process ARCH arm
W/jxcore-log( 2951): 
I/AuthZen ( 1956): Fetching signing key...
I/AuthZen ( 1956): Signing key fetched successfully!
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1202, uid=10029, userID:0
W/BaseAppContext( 1956): Using Auth Proxy for data requests.
I/jxcore-log( 2951): JXcore Cordova bridge is ready!
I/jxcore-log( 2951): 
W/jxcore-log( 2951): JXcore engine is started
D/AuthZenTransactionCache( 1956): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1956): Clearing transaction cache
I/ActivityManager(  907): Resuming delayed broadcast
I/GCoreUlr( 1202): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  907): acquireWL(42a7e790): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1202): Unbound from all location providers
D/PMS     (  907): releaseWL(42a7e790): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42a5f528): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
I/ActivityManager(  907): Resuming delayed broadcast
E/jxcore-log( 2951): >> HTC-HTC Desire 820
E/jxcore-log( 2951): 
I/jxcore-log( 2951): Total memory 1964650496
I/jxcore-log( 2951): 
I/jxcore-log( 2951): Free memory 691662848
I/jxcore-log( 2951): 
I/jxcore-log( 2951): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2951): 
I/jxcore-log( 2951): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 2951): 
I/jxcore-log( 2951): userPath [ 'www' ]
I/jxcore-log( 2951): 
I/jxcore-log( 2951): Size 720 1184
I/jxcore-log( 2951): 
I/jxcore-log( 2951): Screen Brightness 142
I/jxcore-log( 2951): 
W/dalvikvm( 1320): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
E/jxcore-log( 2951): Dummy Error Log.
E/jxcore-log( 2951): 
I/GCoreUlr( 1202): DispatchingService.onDestroy()
I/GCoreUlr( 1202): Stopping handler for UlrDispSvcFast
V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCoreUlr( 1202): Unbound from all location providers
V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  907): acquireWL(427caa68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(427caa68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/Auth    ( 1320): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  907): acquireWL(429c6998): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1320 10029 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
D/PMS     (  907): releaseWL(429c6998): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
W/dalvikvm( 1320): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 1320): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
I/HtcModeClient( 1466): handler message = 4011
E/HtcModeClient( 1466): Check connection and retry 4 times.
D/PersistentNotificationBroadcastReceiver( 1320): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3053 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42a326f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42a326f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3053, uid=10074, userID:0
,I/GAV2    ( 2700): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 3053): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3053/10074)
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3053/10074)
,D/Finsky  ( 3053): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3053): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3053): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 20807: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3053): VFY: unable to resolve virtual method 9030: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3053, uid=10074, userID:0
,D/Volley  ( 3053): [283] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 3053): [276] DiskBasedCache.clear: Cache cleared.
,D/Process (  907): killProcessQuiet, pid=2671
D/Ads     ( 3053): Skipping gmscore version check
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2671:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,D/Finsky  ( 3053): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3053): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3053): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/AutoSetting( 1300): receiver - intent: android.intent.action.USER_PRESENT
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.weather.location.AutoSettingReceiver
,D/AutoSetting( 1300): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 2860): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2860): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2860): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2860): Cust_ConnectToPC   : spcsc>false
D/        ( 2860): Cust_ConnectToPC   : IPT>true
D/        ( 2860): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2860): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 2860): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2860): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 2860): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/Finsky  ( 3053): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/PSReceiver( 2860): onReceive:android.intent.action.USER_PRESENT
I/ActivityManager(  907): Resuming delayed broadcast
,W/ContextImpl( 2860): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 2860): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2860): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2860):  defaultType:0
,W/WeatherUtility( 1109): can't get weather sync account
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2671
,I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3095 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1109): request cur loc, but there is no sys cur
,D/browser ( 3095): Browser versionCode = 760001523 versionName = 7.0.2512153020
,I/jxcore-log( 2951): getBuffer is called!!!!
I/jxcore-log( 2951): 
,W/SWE_UI  ( 3095): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3095): Loading: swewebviewchromium
,I/LibraryLoader( 3095): Time to load native libraries: 29 ms (timestamps 3167-3196)
,I/LibraryLoader( 3095): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3095): Initializing chromium process, renderers=9
,I/LibraryLoader( 3095): Expected native library version number "",actual native library version number ""
,I/chromium( 3095): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/chromium( 3095): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3095): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3095): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3095): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3095): Local Branch: 
I/Adreno-EGL( 3095): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3095): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3095):                  aa63bbd948f41d15fc72f585e
,D/Process (  907): killProcessQuiet, pid=2456
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Killing 2456:com.android.defcontainer/u0a19 (adj 15): empty #17
V/IccIntentReceiver( 1276): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1466): SIM state: ABSENT
I/SIMStateChangeReceiver( 1466): phoneType = 0
,I/SIMStateChangeReceiver( 1466): remove notification
I/ActivityManager(  907): Recipient 2456
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3134 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3146 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=2700
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2700:com.google.android.gm/u0a107 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2700
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2478): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2478): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2478): onReceive()
D/ExchangePolicystatus( 2478): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2478): onReceive(): else
D/Process (  907): killProcessQuiet, pid=2743
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1221): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Killing 2743:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3161 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
,D/PMS     (  907): releaseHCC(42a2e298): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(42a0fe28): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/CalendarApplication( 3161): onCreate
D/ProviderChangeReceiver( 3161): ---------------------------------------------------
,D/ProviderChangeReceiver( 3161): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3161): start to updateAlertNotification!
,W/ContextImpl( 2837): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AccTypeManager( 3146): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3178 uid=10041 gids={50041}
,D/AlertService( 3161): No fired or scheduled alerts
,D/HtcAlertUtils( 3161): -- cancelReminderNotification --
,D/HtcAlertUtils( 3161): broadcastExistReminder!
,D/DotMatrix( 1514): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
W/AccTypeManager( 3146): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3146): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/Process (  907): killProcessQuiet, pid=2686
I/ActivityManager(  907): Recipient 2743
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Killing 2686:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/ExternalAccountType( 3146): Unsupported attribute readOnly
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3192 uid=10078 gids={50078}
,D/Process (  907): killProcessQuiet, pid=2764
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2764:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3146): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3146): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3146): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3192): Got a database change event
,E/ExternalAccountType( 3146): Unsupported attribute readOnly
,D/Process (  907): killProcessQuiet, pid=2791
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3204 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
I/ActivityManager(  907): Killing 2791:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2791
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2686
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3219 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3204): can't get weather sync account
,I/ActivityManager(  907): Recipient 2764
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DemoRecovery.RestoreReceiver( 3219): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3219): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
W/WeatherRequest( 3204): request cur loc, but there is no sys cur
,W/Settings( 3204): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/RestoreService( 3219): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=2808
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3233 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 2808:com.htc.htccupd/u0a17 (adj 15): empty #17
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  907): Recipient 2808
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 1 16 17
,D/PMS     (  907): acquireWL(42b773c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3233 10071 null
,D/PMS     (  907): acquireWL(42b74938): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3233 10071 null
,D/PMS     (  907): releaseWL(42b773c8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null,
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3233): update TASK shortcut>
,I/TodoTaskNotifyService( 3233): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1514): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(42b74938): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3248 uid=10082 gids={50082, 3003, 5012}
W/NotifyReceiver( 3233): stopSelfResult true
,D/Process (  907): killProcessQuiet, pid=2823
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2823:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2823
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3260 uid=10082 gids={50082, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=2850,
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2850:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/SMSBackup( 3192): Got a database change event,
I/ActivityManager(  907): Recipient 2850
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3272 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ActivityManager(  907): Killing 2881:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=2881
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  907): Recipient 2881
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3272): create image Cache, size: 31457280.
I/ImageRamCache( 3272): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3272): create image Cache, size: 12582912.
,I/FeedSettings( 3272): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3272): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3272): GroupBudget 60 45 15
D/MessagingNotification( 2478): New incoming message, can't cancel notification now
,D/MessagingNotification( 2478): newMsgCnt: 0, false
,I/Prism.ExternalStringMa_( 3272): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3272): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3272): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3272): [custom highlight] onReceive
,D/CustomHighlightService( 3272): [custom highlight] onHandleIntent
,D/NewsDB  ( 3272): set custom highlight []
I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3272): [custom highlight] set tags 
,D/MessagingShortcutReceiver( 2478): keep hiding shortcut bubble
D/MessagingShortcut( 2478): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2478): After query: 0
D/MessagingShortcut( 2478): mPresentUnreadCount: -1
,D/MessagingShortcut( 2478): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2478): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1514): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/ActivityManager(  907): Resuming delayed broadcast
D/DotMatrix( 1514): [EventService] reorderNotification, total:0
D/DotMatrix( 1514): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1514): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3233): update TASK shortcut>
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=2898
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/HtcBroadcastReceiver( 1221): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  907): Killing 2898:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2898
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3288 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023989
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024198
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024207
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028373
,V/AlarmManager(  907): sending alarm PendingIntent{4240daa8: PendingIntentRecord{429a4650 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=20405, Int=1800000
,I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3302 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  907): sending alarm PendingIntent{42612798: PendingIntentRecord{4289c450 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=47276, Int=259200000
,V/AlarmManager(  907): sending alarm PendingIntent{421701e0: PendingIntentRecord{42874b78 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=49529, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{42898d18: PendingIntentRecord{428f5bb0 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1448276400000, Int=86400000
,D/MdScBoot( 3288): [2b8.1.] 30@-224546 -> 40@-224614
,D/Process (  907): killProcessQuiet, pid=2910
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 2910:com.google.android.youtube/u0a168 (adj 15): empty #17
,D/Process (  907): killProcessQuiet, pid=3053
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  907): Killing 3053:com.android.vending/u0a74 (adj 15): empty #17
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
,D/WearableService( 1202): callingUid 10029, callindPid: 1202
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,E/MDM     ( 1202): [63] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/LocationInitializer( 1956): Restart initialization of location
,W/GCoreFlp( 1202): No location to return for getLastLocation()
,W/FusedLocationProvider( 1320): location=null
D/PMS     (  907): acquireWL(4278e030): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4278e030): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42949878): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023989
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024198
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028373
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 2910
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3053
,D/GCM     ( 1320): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/MediaRouterService(  907): Client com.google.android.youtube (pid 2910): Died!
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1320/10029)
,D/AuthorizationBluetoothService( 1320): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1320): Proximity feature is not enabled.
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(41ea3d70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1320 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1320/10029)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.SmsMonitor, state=1, flag=1, pid=1956, uid=10029, userID:0
,E/MDM     ( 1202): [64] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.AppsMonitor, state=2, flag=1, pid=1956, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.icing.proxy.ApplicationLauncherReceiver, state=2, flag=1, pid=1956, uid=10029, userID:0
,D/PMS     (  907): releaseWL(41ea3d70): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationInitializer( 1956): Restart initialization of location
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,W/GCoreFlp( 1202): No location to return for getLastLocation()
,W/FusedLocationProvider( 1320): location=null
D/PMS     (  907): acquireWL(42acb7d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42acb7d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023989
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024198
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028373
I/ActivityManager(  907): Resuming delayed broadcast
,D/GCM     ( 1320): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1320): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1320): Proximity feature is not enabled.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1320/10029)
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
,V/GLSActivity( 1320): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  907): Resuming delayed broadcast
,V/GmsCoreStatsServiceLauncher( 1956): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/Process (  907): killProcessQuiet, pid=2860
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2860:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2860
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42929f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1320 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1320/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023989
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024198
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024207
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028373
,D/PMS     (  907): releaseWL(42929f50): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/MtpReceiver( 2169): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2169): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2169): [MTP][handleMessage][startService]
D/MtpReceiver( 2169): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2169): [MTP][handleMessage]-
D/PMS     (  907): acquireWL(42abec10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1320 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1320/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023989
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024087
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024192
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024198
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024207
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028373
,D/PMS     (  907): releaseWL(42abec10): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/MtpService( 2169): [MTP] startForeground
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3328 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews( 1109): com.android.providers.media (false,0)
D/DotMatrix( 1514): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews.Performance( 1109): com.android.providers.media 0 1 10
I/RemoteViews( 1109): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1109): com.android.providers.media 2 2 15
D/MtpService( 2169): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2169): TotalSize=1918604,MediaCacheLimit=6000
,D/PMS     (  907): acquireWL(42abd988): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1956 10029 null
D/MtpService( 2169): [isMtpConnected] connected: true
,I/iu.UploadsManager( 1956): End new media; added: 0, uploading: 0, time: 52 ms
,D/SyncApplication( 3328): Loading default preferences
D/PMS     (  907): releaseWL(42abd988): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,W/Resources( 3328): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 3328): Overriding preferences with custom values
,D/SyncApplication( 3328): Updating preferences succeeded
,E/SyncApplication( 3328): Application created.
D/VolumeInfo( 3328): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3328): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3328): Found 0 mount point(s)
,V/VolumeInfo( 3328): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3328): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3328): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3328): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3328): getNewCalendarAuthority()...
,D/SyncApplication( 3328): enableAppOperation()+
,D/SyncApplication( 3328): enableAppOperation()-
,D/HTCUtilities( 3328): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3328, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3328, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3328): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3328): isNeorSinged() return false
,D/CDMountReceiver( 3328): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3328): USB connected to PC
,D/FOTAReceiver( 3328): onReceive() enter 
,D/FOTAReceiver( 3328): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  907): killProcessQuiet, pid=3095
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3348 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 3095:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3095
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3348): -onCreate()
,V/Settings:HtcSettingsApplication( 3348): [3348/3348] onCreate()
,D/TetherSettings( 3348): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3348): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3348): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3348): Cust_ConnectToPC   : spcsc>false
D/        ( 3348): Cust_ConnectToPC   : IPT>true
,D/        ( 3348): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3348): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3348): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3348): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3348): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3348): Cust_ConnectToPC   : spcsc>false
D/        ( 3348): Cust_ConnectToPC   : IPT>true
D/        ( 3348): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3348): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3348): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3348): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3348): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3348): usb_cable_connect = 1
,D/SmartNS_Utility( 3348): usb_denied = 0
I/SmartNS_NSReceiver( 3348): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3348): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3348): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3348): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3348): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3348):  defaultType:0
,I/SmartNS_PSService( 3348): fail notificaiton:false
,D/SmartNS_Utility( 3348): usb_cable_connect = 1
D/SmartNS_Utility( 3348): usb_denied = 0
,I/SmartNS_PSService( 3348): usb notificaiton:true
,W/ContextImpl( 3348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3348): usb_cable_connect = 1
D/SmartNS_Utility( 3348): usb_denied = 0
,I/SmartNS_PSService( 3348): usb notificaiton:true
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3348/1000)
,I/ActivityManager(  907): Resuming delayed broadcast
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/RemoteViews( 1109): com.android.settings (true,33751552)
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,I/RemoteViews.Performance( 1109): com.android.settings 2 2 10
,D/DotMatrix( 1514): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3348/1000)
,I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
W/WeatherUtility( 3204): can't get weather sync account
D/SmartNS_Utility( 3348): usb_cable_connect = 1
D/SmartNS_Utility( 3348): usb_denied = 0
D/DotMatrix( 1514): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews( 1109): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1109): com.android.settings 2 1 10
I/SmartNS_PSService( 3348): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3348): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  907): Resuming delayed broadcast
,W/WeatherRequest( 3204): request cur loc, but there is no sys cur
,W/Settings( 3204): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1252): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1252): com.google.android.googlequicksearchbox 1 1 5
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3365 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 1 6 17
,W/ContextImpl( 3365): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3365): call getInstance()
I/ActivityManager(  907): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3365): MY_DEBUG = false
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3134
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3134:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/PMS     (  907): acquireWL(42a91da0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3365 1000 null,
,W/WeatherUtility( 1109): can't get weather sync account
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3134
,D/WeatherUtility( 1300): Weather sync is On
,D/WSP     ( 1300): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/WeatherUtility( 3204): can't get weather sync account
I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3382 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherRequest( 3204): request cur loc, but there is no sys cur
,W/Settings( 3204): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1252): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1252): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1252): com.htc.widget.weatherclock 0 8 17
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC <<
,I/SensorManager(  907): mEventCount = 300
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3400 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3146
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3146:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3146
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  907): sending alarm PendingIntent{42668998: PendingIntentRecord{42a5dac0 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448315177095, Int=0
,I/MusicStore( 3400): Database version: 95
,W/ContextImpl( 3400): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3400): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3400): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/Process (  907): killProcessQuiet, pid=3161
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3161:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3161
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3400): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3400): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3400, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 3400): Registered
,I/MediaRouter( 3400): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/DFPI.PIReciver( 3219): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3400/10154)
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3219): onHandleIntent
I/DFPI.ApkInstallService( 3219): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3219): check CID = HTC__032
,I/DFPI.ApkInstallService( 3219): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,D/MediaRouter( 3400): getSelectedRoute
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3400, uid=10154, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42bec4b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42bec4b0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3423 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3423/10053)
,E/cutils  (  356): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3423): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  356): Returning OperationFailed - no handler for errno 30
,D/PMS     (  907): releaseWL(42a91da0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1248
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
W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 7(ms)
D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
D/WifiManager( 2951): setWifiEnabled: Base Package Name=com.example.hello, uid=10396
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
D/WifiService(  907): New client listening to asynchronous messages
D/WifiService(  907): setWifiEnabled: false pid=2951, uid=10396
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1102
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
W/Settings:Agent(  907): << traceCallingStack(): 4(ms)
I/jxcore-log( 2951): ****TEST TOOK:  5052  ms ****
I/jxcore-log( 2951): 
I/jxcore-log( 2951): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 2951): 
,I/HtcModeClient( 1466): handler message = 4011
,E/HtcModeClient( 1466): Check connection and retry 5 times.
,E/cutils-trace( 3442): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 3442): ====startRecUseTime====
D/htc.customization.log.level( 3442):  is 
,W/CustomizationLogLevel( 3442): Level value is invalid, use default level 2
,D/CustomizationManager( 3442):  Read ACC file spent 0.055 (s)
,D/CIDMapFileReader( 3442): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3442): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3442): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3442): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3442): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3442): Parsing tag category name = system
,I/CustomizationCIDLoader( 3442): Parsing tag category name = application
,I/CustomizationCIDLoader( 3442): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3442): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3442): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3442): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3442): Parsing tag category name = Settings
D/CustomizationManager( 3442):  Read CID file spent 0.097 (s)
,D/CustomizationManager( 3442):  All configurations done spent 0.097 (s)
W/HtcNativeFlag( 3442): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3442): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3442): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3442): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=3442, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.example.hello appid=10396 user=-1: uninstall pkg
,D/Process (  907): killProcessQuiet, pid=2951
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  907): Copying FileAsset 0x6c0fa370 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  907): Killing 2951:com.example.hello/u0a396 (adj 0): stop com.example.hello
W/ActivityManager(  907): Force removing ActivityRecord{4297a1a0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{42613648 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  907): Force stopping com.example.hello appid=10396 user=0: pkg removed
,W/InputDispatcher(  907): channel '42b28d58 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  907): channel '42b28d58 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '42b28d58 com.example.hello.MainActivity (s)'
I/WindowManager(  907): WINDOW DIED Window{42b28d58 u0 com.example.hello/com.example.hello.MainActivity}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@42a26b90 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1514): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
I/FeedHostManager( 1252): [onResume]
,I/FeedProviderManager( 1252): onResume
,I/SocialFeedProvider( 1252): +onResume
D/DotMatrix( 1514): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1514): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/SocialFeedProvider( 1252): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1252): -onResume
,I/ConnectivityHelper( 1252): [getCurrentConnectionType] no network connection
,W/GeofencerStateMachine( 1202): Ignoring removeGeofence because network location is disabled.
I/WindowState(  907): WIN DEATH: null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1252/10076)
D/PMS     (  907): acquireWL(42b7c150): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1202 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42b7c150): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 3272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/Prism.ItemManager( 3272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1233): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1334): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 1334): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1334): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1252): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/ActivityManager(  907): Resuming delayed broadcast
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,D/Process (  907): killProcessQuiet, pid=2837
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3455 uid=10081 gids={50081, 5001, 1028, 1015}
,I/ActivityManager(  907): Killing 2837:com.android.settings:remote/1000 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2837
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,E/ExternalAccountType( 1334): Unsupported attribute readOnly
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/SoundPicker( 3455): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/PackageManager(  907):   Scheme: "smsto"
W/ContextImpl( 3455): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/SoundPicker( 3455): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3455): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3455): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3455): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3455): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3455): MODE_GSM access default DB
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 2951 uid 10396
I/InputMethodManagerService(  907): Enable input method client, pid=1252
W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3455): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3455): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3455): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3455): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,W/PackageManager(  907): Unable to load service info ResolveInfo{42a8c0a0 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/RemoteDisplayProvider(  907): start
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/ActivityManager(  907): Resuming delayed broadcast
,D/DFPI.PIReciver( 3219): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3219): onHandleIntent
I/DFPI.ApkInstallService( 3219): Media Scan Finished Case 
I/SocialFeedProvider( 1252): +disConnect socialManager
I/SocialFeedProvider( 1252): disconnect socialManager
D/DFPI.ApkInstallService( 3219): check CID = HTC__032
I/DFPI.ApkInstallService( 3219): There is no Demo.apk in sd card or phone storage
,I/SocialFeedProvider( 1252): -disConnect socialManager
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  907): sending alarm PendingIntent{423fc980: PendingIntentRecord{4287a938 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448315179400, Int=0
,I/SocialManager[SocialBiLogHelper]( 3272): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3272): last commit ulog time 1448256937773
,I/SocialManager[SocialBiLogHelper]( 3272): skip commit this time

```
