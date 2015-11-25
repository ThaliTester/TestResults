#### Test 503880194bce128_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3004): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
--------- beginning of /dev/log/system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3004): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3004): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3004): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3004): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/MediaRouterService(  907): Client com.google.android.youtube (pid 3004): Registered
I/MediaRouter( 3004): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/YouTube ( 3004): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3004): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1448461013&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.youtube (3004/10168)
D/libc    ( 3004): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3004): [NET] getaddrinfo-,err=8
D/libc    ( 3004): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3004): [NET] getaddrinfo-, 1
D/libc    ( 3004): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3004): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 3004): Error sending ping
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3004): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3004): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 3004): getSelectedRoute
D/YouTube ( 3004): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3004/10168)
D/YouTube ( 3004): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
W/BroadcastQueue(  907): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/AutoSetting( 1381): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2960): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2960): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2960): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2960): Cust_ConnectToPC   : spcsc>false
D/        ( 2960): Cust_ConnectToPC   : IPT>true
D/        ( 2960): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2960): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2960): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2960): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2960): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1381): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/PSReceiver( 2960): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2960): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/YouTube ( 3004): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
I/SmartNS_PSService( 2960): onReceive:android.intent.action.USER_PRESENT
D/YouTube ( 3004): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
W/Settings( 2960): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2960):  defaultType:0
D/YouTube ( 3004): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3060 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  907): Killing 2757:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=2757
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Recipient 2757
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/browser ( 3060): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3060): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3060): Loading: swewebviewchromium
E/cutils-trace( 3041): Error opening trace file: No such file or directory (2)
I/LibraryLoader( 3060): Time to load native libraries: 37 ms (timestamps 3942-3979)
I/LibraryLoader( 3060): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3060): Initializing chromium process, renderers=9
I/LibraryLoader( 3060): Expected native library version number "",actual native library version number ""
I/chromium( 3060): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
D/CustomizationManager( 3041): ====startRecUseTime====
D/htc.customization.log.level( 3041):  is 
W/CustomizationLogLevel( 3041): Level value is invalid, use default level 2
I/SensorManager(  907): mEventCount = 300
W/PackageManager(  907): Unable to load service info ResolveInfo{426da8a8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
W/chromium( 3060): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/Adreno-EGL( 3060): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3060): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3060): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3060): Local Branch: 
I/Adreno-EGL( 3060): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3060): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3060):                  aa63bbd948f41d15fc72f585e
D/CustomizationManager( 3041):  Read ACC file spent 0.071 (s)
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3041): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3041): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3041): Parsing tag category name = system
I/CustomizationCIDLoader( 3041): Parsing tag category name = application
I/CustomizationCIDLoader( 3041): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3041): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3041): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3041): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3041): Parsing tag category name = Settings
D/CustomizationManager( 3041):  Read CID file spent 0.123 (s)
D/CustomizationManager( 3041):  All configurations done spent 0.123 (s)
W/HtcNativeFlag( 3041): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3041): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3041): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3041): Fail to get flag for type 'language', use default value: -1
D/Process (  907): killProcessQuiet, pid=2769
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1279): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  907): Killing 2769:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/SIMStateChangeReceiver( 1488): SIM state: ABSENT
I/SIMStateChangeReceiver( 1488): phoneType = 0
I/SIMStateChangeReceiver( 1488): remove notification
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2769
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3108 uid=10031 gids={50031, 3003, 5012}
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3041
D/PMS     (  907): acquireHCC(42597698): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(42742d80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
W/asset   (  907): Copying FileAsset 0x6741e360 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1112964856
D/PMS     (  907): acquireWL(424d4f48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedHostManager( 1253): [onPause]
I/FeedProviderManager( 1253): onPause
I/FeedHostManager( 1253): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41a88750
I/SocialFeedProvider( 1253): +onPause
I/SocialFeedProvider( 1253): -onPause
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3120 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
W/asset   ( 3120): Copying FileAsset 0x5c6ef648 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1253): [trimMemory] 20
D/Process (  907): killProcessQuiet, pid=2801
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3132 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 2801:com.google.android.gm/u0a107 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 3120): Binding Chromium to main looper Looper (main, tid 1) {41a6fde8}
I/LibraryLoader( 3120): Expected native library version number "",actual native library version number ""
I/chromium( 3120): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3120): Initializing chromium process, renderers=0
E/ActivityThread( 1253): Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1253): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.htc.launcher/com.htc.launcher.Launcher}
E/ActivityThread( 1253): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3590)
E/ActivityThread( 1253): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3684)
E/ActivityThread( 1253): 	at android.app.ActivityThread.access$1100(ActivityThread.java:153)
E/ActivityThread( 1253): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1376)
E/ActivityThread( 1253): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 1253): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread( 1253): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/ActivityThread( 1253): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread( 1253): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread( 1253): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread( 1253): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread( 1253): 	at dalvik.system.NativeStart.main(Native Method)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426a5708:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3120): 1101552672: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  907): Activity reported stop, but no longer stopping: ActivityRecord{423a8428 u0 com.htc.launcher/.Launcher t1}
D/PMS     (  907): acquireWL(426a9c80): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(428103a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): releaseWL(426a9c80): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3120): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3120): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3120): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3120): Local Branch: 
I/Adreno-EGL( 3120): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3120): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3120):                  aa63bbd948f41d15fc72f585e
W/SystemReader( 2556): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2556): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2556): onReceive()
D/ExchangePolicystatus( 2556): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2556): onReceive(): else
D/Process (  907): killProcessQuiet, pid=2183
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1224): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Killing 2183:com.android.defcontainer/u0a19 (adj 15): empty #17
W/chromium( 3120): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/ActivityManager(  907): Recipient 2183
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 3120): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3120): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3120): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3120): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3120): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3120): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3120): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3120): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3120): CordovaWebView is running on device made by: HTC
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2801
,I/Prism.ItemManager( 1253): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1253): loadItems() com.htc.launcher.pageview.WidgetManager@41b02ed0 +
I/Prism.WidgetManager( 1253): onLoadItems() +
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
W/WeatherUtility( 1112): can't get weather sync account
D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/AccTypeManager( 3132): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3132): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3177 uid=10038 gids={50038}
D/AccTypeManager( 3132): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/WeatherRequest( 1112): request cur loc, but there is no sys cur
W/AwContents( 3120): nativeOnDraw failed; clearing to background color.
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/InputMethodManagerService(  907): Disable input method client, pid=1253
W/ResourceType( 3120): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3120): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41aba3c8, mServedView=org.apache.cordova.engine.SystemWebView{41a7cf40 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=3120
W/XT9_C   ( 1189): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1189): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1189): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1189): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3120): nativeOnDraw failed; clearing to background color.
E/ExternalAccountType( 3132): Unsupported attribute readOnly
D/Process (  907): killProcessQuiet, pid=2838
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3193 uid=10077 gids={50077}
I/ActivityManager(  907): Killing 2838:com.htc.backup/1000 (adj 15): empty #17
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +418ms
D/PMS     (  907): releaseWL(424d4f48): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2838
W/AccTypeManager( 3132): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3132): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/SMSBackup( 3193): Got a database change event
D/AccTypeManager( 3132): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3205 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/Process (  907): killProcessQuiet, pid=2784
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2784:com.htc.cs.dm/u0a98 (adj 15): empty #17
E/ExternalAccountType( 3132): Unsupported attribute readOnly
D/CalendarApplication( 3205): onCreate
D/ProviderChangeReceiver( 3205): ---------------------------------------------------
D/ProviderChangeReceiver( 3205): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3205): start to updateAlertNotification!
W/ContextImpl( 2938): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
D/AlertService( 3205): No fired or scheduled alerts
D/HtcAlertUtils( 3205): -- cancelReminderNotification --
D/HtcAlertUtils( 3205): broadcastExistReminder!
D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3221 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=2862
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2862:com.google.android.talk/u0a111 (adj 15): empty #17
E/AndroidProtocolHandler( 3120): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3120): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/ActivityManager(  907): Recipient 2784
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3238 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3221): can't get weather sync account
D/JsMessageQueue( 3120): Set native->JS mode to OnlineEventsBridgeMode
I/DemoRecovery.RestoreReceiver( 3238): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3238): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
W/WeatherRequest( 3221): request cur loc, but there is no sys cur
W/Settings( 3221): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/RestoreService( 3238): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  907): Recipient 2862
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppWidgetHostView( 1253): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1253): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  907): Resuming delayed broadcast
D/Process (  907): killProcessQuiet, pid=2894
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3252 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 2894:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2894
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews.Performance( 1253): com.htc.widget.weatherclock 1 27 17
D/jxcore_app_log( 3120): JniHelper::setJavaVM(0x41548048), pthread_self() = 1657399544
D/JX-Cordova( 3120): jxcore cordova android initializing
D/PMS     (  907): acquireWL(42149a68): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3252 10070 null
D/PMS     (  907): acquireWL(4205b630): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3252 10070 null
D/PMS     (  907): releaseWL(42149a68): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3252): update TASK shortcut>
W/asset   ( 1253): Copying FileAsset 0x64bc3358 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
E/Prism.WidgetManager( 1253): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1253): onLoadItems() -
I/Prism.ItemManager( 1253): loadItems() com.htc.launcher.pageview.WidgetManager@41b02ed0 -
I/TodoTaskNotifyService( 3252): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(4205b630): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3267 uid=10081 gids={50081, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=2909
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
W/NotifyReceiver( 3252): stopSelfResult true
I/ActivityManager(  907): Killing 2909:com.htc.htccupd/u0a17 (adj 15): empty #17
W/jxcore-log( 3120): Initializing JXcore engine
W/jxcore-log( 3120): JXcore engine is ready
I/ActivityManager(  907): Recipient 2909
W/jxcore-log( 3120): Starting JXcore engine
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3279 uid=10081 gids={50081, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=2924
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/SMSBackup( 3193): Got a database change event
I/ActivityManager(  907): Killing 2924:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2924
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3291 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
D/Process (  907): killProcessQuiet, pid=2951
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2951:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/ContactMessageStore( 1224): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1224): MSG_NOTIFY_CS_TO_SYNC <<
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2951
D/PhoneApp( 1224): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1224): -- N1 =0
D/PhoneApp( 1224): -- N2 =0
D/PhoneApp( 1224): -- N3 =0
I/ImageRamCache( 3291): create image Cache, size: 31457280.
I/ImageRamCache( 3291): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3291): create image Cache, size: 12582912.
I/FeedSettings( 3291): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3291): GroupBudget 0.500000 0.380000
I/FeedSettings( 3291): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3291): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3291): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3291): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3291): [custom highlight] onReceive
D/CustomHighlightService( 3291): [custom highlight] onHandleIntent
D/NewsDB  ( 3291): set custom highlight []
I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
W/jxcore-log( 3120): Platform android
W/jxcore-log( 3120): 
W/jxcore-log( 3120): Process ARCH arm
W/jxcore-log( 3120): 
D/CustomHighlightService( 3291): [custom highlight] set tags 
D/MessagingShortcutReceiver( 2556): keep hiding shortcut bubble
D/MessagingShortcut( 2556): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2556): After query: 0
D/MessagingShortcut( 2556): mPresentUnreadCount: -1
D/MessagingShortcut( 2556): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2556): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1539): [EventService] reorderNotification, total:1
D/DotMatrix( 1539): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
D/DotMatrix( 1539): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  907): Resuming delayed broadcast
D/TodoTaskshortcut( 3252): update TASK shortcut>
D/HtcBroadcastReceiver( 1224): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  907): Resuming delayed broadcast
D/Process (  907): killProcessQuiet, pid=2978
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2978:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/jxcore-log( 3120): JXcore Cordova bridge is ready!
I/jxcore-log( 3120): 
W/jxcore-log( 3120): JXcore engine is started
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3307 uid=10091 gids={50091, 3003, 5012}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2978
I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
E/jxcore-log( 3120): >> HTC-HTC Desire 820
E/jxcore-log( 3120): 
I/jxcore-log( 3120): Total memory 1964650496
I/jxcore-log( 3120): 
I/jxcore-log( 3120): Free memory 730783744
I/jxcore-log( 3120): 
I/jxcore-log( 3120): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3120): 
I/jxcore-log( 3120): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3120): 
I/jxcore-log( 3120): userPath [ 'www' ]
I/jxcore-log( 3120): 
I/jxcore-log( 3120): Size 720 1184
I/jxcore-log( 3120): 
I/jxcore-log( 3120): Screen Brightness 10
I/jxcore-log( 3120): 
E/jxcore-log( 3120): Dummy Error Log.
E/jxcore-log( 3120): 
I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3321 uid=10091 gids={50091, 3003, 5012}
D/MessagingNotification( 2556): New incoming message, can't cancel notification now
D/MessagingNotification( 2556): newMsgCnt: 0, false
D/MdScBoot( 3307): [790.1.] 30@-151626 -> 40@-151655
D/Process (  907): killProcessQuiet, pid=2992
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 2992:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  907): Killing 3004:com.google.android.youtube/u0a168 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3004
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1343): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Recipient 2992
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3334 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3004
E/dalvikvm( 3334): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3334): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
I/Babel   ( 3334): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3334): MmsConfig.loadMmsSettings
D/MediaRouterService(  907): Client com.google.android.youtube (pid 3004): Died!
E/dalvikvm( 3334): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3334): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3334): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/MmsCustomizationProvider( 2556): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2556): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3334): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3334): MmsConfig.loadFromDatabase
E/Babel   ( 3334): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3334): MmsConfig.loadFromResources
E/Babel   ( 3334): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3334): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3334, uid=10111, userID:0
W/Settings( 3334): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3334, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3334, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3334, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3334, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3334, uid=10111, userID:0
D/Process (  907): killProcessQuiet, pid=2960
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/GCM     ( 1343): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  907): Killing 2960:com.android.settings/1000 (adj 15): empty #17
D/MtpReceiver( 2237): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2237): [MTP][handleMessage][startService]
D/MtpReceiver( 2237): [MTP][MtpReceiver][onReceive]1-
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1750/10178)
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3360 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/MtpReceiver( 2237): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2237): [MTP][handleMessage]-
D/MtpService( 2237): [MTP] startForeground
D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2237): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2237): TotalSize=1918604,MediaCacheLimit=6000
I/ProviderInstaller( 3334): Installed default security provider GmsCore_OpenSSL
D/MtpService( 2237): [isMtpConnected] connected: true
I/RemoteViews( 1112): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1112): com.android.providers.media 0 1 10
I/RemoteViews( 1112): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1112): com.android.providers.media 1 1 15
I/ActivityManager(  907): Recipient 2960
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/SyncApplication( 3360): Loading default preferences
W/Resources( 3360): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  907): New client listening to asynchronous messages
D/SyncApplication( 3360): Overriding preferences with custom values
D/SyncApplication( 3360): Updating preferences succeeded
E/SyncApplication( 3360): Application created.
D/VolumeInfo( 3360): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3360): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3360): Found 0 mount point(s)
V/VolumeInfo( 3360): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3360): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3360): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3360): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3360): getNewCalendarAuthority()...
D/SyncApplication( 3360): enableAppOperation()+
D/SyncApplication( 3360): enableAppOperation()-
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3360, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3360, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3360): isNeorSinged() + 
D/HTCUtilities( 3360): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
I/HtcModeClient( 1488): handler message = 4011
E/HtcModeClient( 1488): Check connection and retry 5 times.
D/HTCUtilities( 3360): isNeorSinged() return false
D/CDMountReceiver( 3360): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3360): USB connected to PC
D/FOTAReceiver( 3360): onReceive() enter 
D/FOTAReceiver( 3360): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3379 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  907): killProcessQuiet, pid=3060
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3060:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3060
,D/Process (  907): killProcessQuiet, pid=3108
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3108:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/jxcore-log( 3120): getBuffer is called!!!!
I/jxcore-log( 3120): 
,D/HtcFingerPrintQuickLaunchProvider( 3379): -onCreate()
,V/Settings:HtcSettingsApplication( 3379): [3379/3379] onCreate()
,D/TetherSettings( 3379): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3379): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3379): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3379): Cust_ConnectToPC   : spcsc>false
D/        ( 3379): Cust_ConnectToPC   : IPT>true
,D/        ( 3379): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3379): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3379): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3379): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3379): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3379): Cust_ConnectToPC   : spcsc>false
D/        ( 3379): Cust_ConnectToPC   : IPT>true
D/        ( 3379): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3379): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3379): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3379): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3379): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3379): usb_cable_connect = 1
,D/SmartNS_Utility( 3379): usb_denied = 0
I/SmartNS_NSReceiver( 3379): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3379): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3379): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3379): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3379): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3379):  defaultType:0
,I/SmartNS_PSService( 3379): fail notificaiton:false
,D/SmartNS_Utility( 3379): usb_cable_connect = 1
D/SmartNS_Utility( 3379): usb_denied = 0
,I/SmartNS_PSService( 3379): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
W/ContextImpl( 3379): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3379/1000)
,D/SmartNS_Utility( 3379): usb_cable_connect = 1
D/SmartNS_Utility( 3379): usb_denied = 0
I/SmartNS_PSService( 3379): usb notificaiton:true
D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  907): bSetPropertyMultiRAB:false
D/SmartNS_Utility( 3379): usb_cable_connect = 1
D/SmartNS_Utility( 3379): usb_denied = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3379/1000)
I/RemoteViews( 1112): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1112): com.android.settings 0 1 10
D/DotMatrix( 1539): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3379): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3379): USB Plugged, Set USBPlugged=  truePSenabled:false
D/Process (  907): killProcessQuiet, pid=3132
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3132:com.htc.contacts/u0a41 (adj 15): empty #17
I/RemoteViews( 1112): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1112): com.android.settings 1 0 10
,W/WeatherUtility( 3221): can't get weather sync account
,D/AppWidgetHostView( 1253): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1253): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1253): com.google.android.googlequicksearchbox 3 2 5
I/ActivityManager(  907): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,D/AppWidgetHostView( 1253): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
,I/RemoteViews( 1253): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1253): pl.k2.droidoaudioteka 0 0 8
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,I/ActivityManager(  907): Recipient 3108
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherRequest( 3221): request cur loc, but there is no sys cur
,W/Settings( 3221): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1253): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1253): com.htc.widget.weatherclock (true,33751552)
,I/ActivityManager(  907): Resuming delayed broadcast
I/RemoteViews.Performance( 1253): com.htc.widget.weatherclock 1 5 17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3132
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(42597698): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(42742d80): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
I/ActivityManager(  907): Resuming delayed broadcast
V/AlarmManager(  907): sending alarm PendingIntent{42215438: PendingIntentRecord{42543008 com.google.android.gms startService}}, i=null, t=0, cnt=17057, w=84918423, Int=84918423
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,D/SnetService( 1203): snet destroyed
,D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  907): acquireWL(42830718): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(42830718): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1203): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3416 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1381): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1381): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3432 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3432, uid=10073, userID:0
,D/Finsky  ( 3432): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3432/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3432/10073)
,D/Finsky  ( 3432): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3432): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3432): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3432, uid=10073, userID:0
,D/Process (  907): killProcessQuiet, pid=3205
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1253): action: android.intent.action.PACKAGE_ADDED
,D/Finsky  ( 3432): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3432): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  907): Killing 3205:com.htc.calendar/u0a13 (adj 15): empty #17
,I/IcingCorporaProvider( 2671): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Recipient 3205
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3432): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  907): Delaying start of: ServiceRecord{426afd00 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
D/PMS     (  907): acquireWL(426974d0): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(426974d0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(426946a8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(426946a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42693fe8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/Process (  907): killProcessQuiet, pid=2938
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2938:com.android.settings:remote/1000 (adj 15): empty #17
,D/PMS     (  907): releaseWL(42693fe8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2938
,D/Finsky  ( 3432): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  907): acquireWL(426907a8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(426907a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3469 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  907): acquireWL(4254d038): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4254d038): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4235b458): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(4235b458): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/DeviceManagement( 3469): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3469 dbg=false s=true
I/DeviceManagement( 3469): PackageUpdateReceiver: vvv Package added: [com.example.hello]
D/Process (  907): killProcessQuiet, pid=3238
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/PMS     (  907): acquireWL(420389b8): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
I/ActivityManager(  907): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/ActivityManager(  907): Killing 3238:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/PMS     (  907): releaseWL(420389b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 3238
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3482 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  907): releaseWL(428103a0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/PMS     (  907): acquireWL(42325508): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(42325508): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42225908): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(42225908): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42033f70): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(42033f70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(41ee2080): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  907): releaseWL(41ee2080): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2671): Copying FileAsset 0x5d8a2f30 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2671): UpdateCorporaTask done [took 469 ms] updated apps [took 469 ms] 
,W/GAV2    ( 3482): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3502 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3502): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3502): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3502): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3518 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  907): killProcessQuiet, pid=3267
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DeviceManagement( 3469): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3469): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.smartdim, com.android.CSDFunctionG, com.android.keychain, com.htc.lockscreen, com.htc.android.htcloglevel, com.android.settings, com.htc.backup, com.htc.backupreset, com.htc.guide, com.android.location.fused, com.htc.android.htcsetupwizard, android, com.qualcomm.timeservice, com.htc.mirrorlinkserver, com.htc.drive.activator, com.htc.feedback, com.htc.checkinprovider, com.android.providers.settings, com.htc.htcpowermanager, com.android.inputdevices, com.htc.cirmodule, com.htc.usage, com.htc.autobot.cargps.provider, com.htc.home.personalize, com.qualcomm.privinit]
,I/ActivityManager(  907): Killing 3267:com.htc.stock/u0a81 (adj 15): empty #17
,I/DeviceManagement( 3469): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 3469): WorkflowService: Starting workflow service
I/DeviceManagement( 3469): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41aae6e0] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3469): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/ActivityManager(  907): Recipient 3267
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 3469): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3469): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3469): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3518):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  907): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,V/AlarmManager(  907): sending alarm PendingIntent{424a0908: PendingIntentRecord{42741950 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448461018102, Int=0
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,I/DeviceManagement( 3469): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/GoogleHttpClient( 1343): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1343): Using GMS GoogleHttpClient
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3536 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,W/GAV2    ( 3482): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/DeviceManagement( 3469): SessionStateController: Checking invariants...
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3432): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
D/Finsky  ( 3432): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3469): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3469): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41aae6e0]
,I/DeviceManagement( 3469): WorkflowService: Stopping workflow service
,D/Process (  907): killProcessQuiet, pid=3279
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3279:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3279
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(425a0e58): PARTIAL_WAKE_LOCK  AsyncService 0x1 3536 10160 null
,D/PMS     (  907): releaseWL(425a0e58): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  907): acquireWL(42598ec0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3536 10160 null
,D/PMS     (  907): acquireWL(4240dca0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3536 10160 null
,D/PMS     (  907): releaseWL(42598ec0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3565 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3536/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3536/10160)
,D/Settings:HtcWirelessFeatureFlags( 3379): id/is att sku: 99/false
,W/SystemReader( 3379): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3379): Cannot find support_harman, use default value instead
,W/SystemReader( 3379): Cannot find effect_manager_id, use default value instead
D/PMS     (  907): releaseWL(4240dca0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  907): killProcessQuiet, pid=3177
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3177:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,E/Settings:HtcWrapHeaderInfo( 3379): no such activity!
W/ContextImpl( 3565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3565): call getInstance()
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3177
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3379): The wrap header doesn't exist in header list.
,W/WeatherUtility( 1112): can't get weather sync account
,D/PowerUsageList:PowerUsageHelper( 3565): MY_DEBUG = false
,E/Settings:HtcWrapHeaderInfo( 3379): updateDevelopment, bPrefShow = true
,D/WeatherUtility( 1381): Weather sync is On
,D/WSP     ( 1381): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherUtility( 3221): can't get weather sync account
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
E/Settings:HtcUmcWidgetEnabler( 3379): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]support         :false
,W/FingerprintManager( 3379): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/WeatherRequest( 3221): request cur loc, but there is no sys cur
,W/Settings( 3221): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Settings:HtcVoWifiWidgetEnabler( 3379): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3379): Failed to find provider info for com.htc.vowifi
,D/AppWidgetHostView( 1253): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1253): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1253): com.htc.widget.weatherclock 1 5 17
,D/PMS     (  907): acquireWL(4252e550): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3565 1000 null
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3379): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3379): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3379): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3379): [supportHomeButton]support         :false
,W/FingerprintManager( 3379): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3379): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3379): Failed to find provider info for com.htc.vowifi
,W/GLSUser ( 1343): GoogleAccountDataService.getToken()
D/PMS     (  907): releaseWL(4252e550): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1343): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1343): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3432): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3432): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3432): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3193
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3586 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
I/ActivityManager(  907): Killing 3193:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3193
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SocialFeedProvider( 1253): +disConnect socialManager
,I/SocialFeedProvider( 1253): disconnect socialManager
,I/SocialFeedProvider( 1253): -disConnect socialManager
,V/AlarmManager(  907): sending alarm PendingIntent{42385680: PendingIntentRecord{4238b4f0 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448461019496, Int=0
,I/SocialManager[SocialBiLogHelper]( 3291): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3291): last commit ulog time 1448443159813
,I/SocialManager[SocialBiLogHelper]( 3291): skip commit this time
,V/AlarmManager(  907): sending alarm PendingIntent{4278daa0: PendingIntentRecord{4253bf20 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448461019691, Int=0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3605 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3252
,I/ActivityManager(  907): Killing 3252:com.htc.task/u0a70 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3252
,D/Process (  907): killProcessQuiet, pid=3307
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3307:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/MusicStore( 3605): Database version: 95
,W/ContextImpl( 3605): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3605): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,V/AlarmManager(  907): sending alarm PendingIntent{422e86b0: PendingIntentRecord{422768f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=56889, Int=0
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/IntentController( 1112): receive(android.intent.action.TIME_TICK,1,false)
,W/ContextImpl( 3605): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/ClockThread( 1112): now=1448461020031 next=59969
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3307
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3605): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3605): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3605, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 3605): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3605): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3624 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3605/10154)
,D/MediaRouter( 3605): getSelectedRoute
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3605, uid=10154, userID:0
,D/Process (  907): killProcessQuiet, pid=3321
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3321:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/DFPI.PIReciver( 3624): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3624): onHandleIntent
,I/DFPI.ApkInstallService( 3624): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3624): check CID = HTC__032
,I/DFPI.ApkInstallService( 3624): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Recipient 3321
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3640 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3640/10051)
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3640): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
,W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 1101
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 12(ms)
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
,D/WifiManager( 3120): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
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
,W/System.err(  907): ,	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 3(ms)
D/WifiService(  907): setWifiEnabled: false pid=3120, uid=10355
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiService(  907): New client listening to asynchronous messages
,D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true,
I/jxcore-log( 3120): ****TEST TOOK:  5058  ms ****,
I/jxcore-log( 3120): 
I/jxcore-log( 3120): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3120): ,
,E/cutils-trace( 3659): Error opening trace file: No such file or directory (2)
,I/HtcModeClient( 1488): handler message = 4011
,E/HtcModeClient( 1488): Check connection and retry 6 times.
,D/CustomizationManager( 3659): ====startRecUseTime====
D/htc.customization.log.level( 3659):  is 
,W/CustomizationLogLevel( 3659): Level value is invalid, use default level 2
,D/CustomizationManager( 3659):  Read ACC file spent 0.060 (s)
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3659): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3659): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3659): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3659): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3659): Parsing tag category name = system
,I/CustomizationCIDLoader( 3659): Parsing tag category name = application
,I/CustomizationCIDLoader( 3659): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3659): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3659): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3659): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3659): Parsing tag category name = Settings
,D/CustomizationManager( 3659):  Read CID file spent 0.107 (s)
,D/CustomizationManager( 3659):  All configurations done spent 0.108 (s)
W/HtcNativeFlag( 3659): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3659): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3659): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3659): Fail to get flag for type 'language', use default value: -1
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3668 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3334
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3334:com.google.android.talk/u0a111 (adj 15): empty #17
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=3659, uid=2000 user=0
,I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,W/asset   (  907): Copying FileAsset 0x6c422a50 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  907): killProcessQuiet, pid=3120
,I/ActivityManager(  907): Killing 3120:com.example.hello/u0a355 (adj 0): stop com.example.hello
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  907): Force removing ActivityRecord{42597228 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  907): Skipping PackageSetting{421a6500 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  907): Recipient 3334
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3668): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3668): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
W/InputDispatcher(  907): channel '42347a68 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '42347a68 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '42347a68 com.example.hello.MainActivity (s)'
I/ActivityManager(  907): Force stopping com.example.hello appid=10355 user=0: pkg removed
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
I/WindowManager(  907): WINDOW DIED Window{42347a68 u0 com.example.hello/com.example.hello.MainActivity}
,W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@425a3c48 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  907): WIN DEATH: null
,I/SoundPicker( 3668): SoundPickerReceiver [onReceive] startService
I/FeedHostManager( 1253): [onResume]
,I/FeedProviderManager( 1253): onResume
I/SocialFeedProvider( 1253): +onResume
,I/SocialFeedProvider( 1253): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1253): -onResume
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/ActivityManager(  907): Waited long enough for: ServiceRecord{422d51a0 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  907): Resuming delayed broadcast
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1112): ApplicationsIntentReceiver replacing:false
I/acms    ( 1768): Unregistering com.example.hello
D/DotMatrix( 1539): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
E/acms    ( 1768): Could not unregister removed application com.example.hello
D/DotMatrix( 1539): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1539): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,I/SoundPicker( 3668): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
,I/ConnectivityHelper( 1253): [getCurrentConnectionType] no network connection
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1253/10075)
,D/PMS     (  907): acquireWL(42819900): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1419 10028 null
W/GeofencerStateMachine( 1419): Ignoring removeGeofence because network location is disabled.
W/AccTypeManager( 1311): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1311): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 3291): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3291): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  907): releaseWL(42819900): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,D/AccTypeManager( 1311): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
V/SoundPicker( 3668): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3668): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3668): MODE_GSM access default DB
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/Prism.ItemManager( 1253): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1253): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3668): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3668): MODE_GSM access default DB
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SystemReader( 1236): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
E/ExternalAccountType( 1311): Unsupported attribute readOnly
I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/SensorManager(  907): mEventCount = 450
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1224 :
I/ActivityManager(  907): Resuming delayed broadcast
,D/PhoneApp( 1224): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/DFPI.PIReciver( 3624): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3624): onHandleIntent
,I/DFPI.ApkInstallService( 3624): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3624): check CID = HTC__032
,I/DFPI.ApkInstallService( 3624): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3120 uid 10355
,I/InputMethodManagerService(  907): Enable input method client, pid=1253
,I/SoundPicker( 3668): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/Binder  ( 1189): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1189): java.lang.NullPointerException
W/Binder  ( 1189): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1189): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1189): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1189): 	at dalvik.system.NativeStart.run(Native Method)
,W/ContextImpl( 3668): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3668): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3668): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3668): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3668): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3668): MODE_GSM access default DB
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3668): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3668): MODE_GSM access default DB
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3624): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3624): onHandleIntent
,I/DFPI.ApkInstallService( 3624): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3624): check CID = HTC__032
,I/DFPI.ApkInstallService( 3624): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3668): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3668): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3668): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3668): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3668): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3668): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3668): MODE_GSM access default DB
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3668): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3668): MODE_GSM access default DB
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3668): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3668): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3668): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3668): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,E/SharedPreferencesImpl( 3605): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/SQLiteDatabase( 3605): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 3605): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3605): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3605): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3605): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 3605): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 3605): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3605): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3605): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 3605): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3605): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3605): threadid=16: thread exiting with uncaught exception (group=0x41640e30)
,E/AndroidRuntime( 3605): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 3605): Process: com.google.android.music:main, PID: 3605
E/AndroidRuntime( 3605): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3605): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3605): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3605): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 3605): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 3605): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3605): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3605): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 3605): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3605): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.google.android.music:main
,E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
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
,W/PackageManager(  907): Unable to load service info ResolveInfo{42399eb8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  907): start
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/GAV2    ( 3482): Thread[GAThread,5,main]: No campaign data found.

```
