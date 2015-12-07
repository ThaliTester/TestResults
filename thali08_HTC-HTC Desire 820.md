#### Test 50242285e132180_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/YouTube ( 3007): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
--------- beginning of /dev/log/system
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3007): Registered
I/MediaRouter( 3007): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/YouTube ( 3007): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.youtube (3007/10168)
I/GoogleConversionPing( 3007): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449501102&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 3007): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3007): [NET] getaddrinfo-,err=8
D/libc    ( 3007): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3007): [NET] getaddrinfo-, 1
D/libc    ( 3007): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3007): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 3007): Error sending ping
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3007): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3007): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3007): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/MediaRouter( 3007): getSelectedRoute
D/YouTube ( 3007): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.youtube (3007/10168)
W/BroadcastQueue(  906): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
I/SensorManager(  906): mEventCount = 300
D/YouTube ( 3007): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3007): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/Process (  906): killProcessQuiet, pid=2761
I/ActivityManager(  906): Killing 2761:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/AutoSetting( 1377): receiver - intent: android.intent.action.USER_PRESENT
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/AutoSetting( 1377): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/TetherSettings( 2965): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2965): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2965): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2965): Cust_ConnectToPC   : spcsc>false
D/        ( 2965): Cust_ConnectToPC   : IPT>true
D/        ( 2965): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2965): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2965): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2965): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2965): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/YouTube ( 3007): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/PSReceiver( 2965): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2965): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  906): Recipient 2761
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SmartNS_PSService( 2965): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2965): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2965):  defaultType:0
I/ActivityManager(  906): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3063 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/browser ( 3063): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3063): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3063): Loading: swewebviewchromium
W/PackageManager(  906): Unable to load service info ResolveInfo{42572ef8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
I/LibraryLoader( 3063): Time to load native libraries: 35 ms (timestamps 2271-2306)
I/LibraryLoader( 3063): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3063): Initializing chromium process, renderers=9
I/LibraryLoader( 3063): Expected native library version number "",actual native library version number ""
I/chromium( 3063): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
W/chromium( 3063): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
I/Adreno-EGL( 3063): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3063): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3063): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3063): Local Branch: 
I/Adreno-EGL( 3063): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3063): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3063):                  aa63bbd948f41d15fc72f585e
D/CustomizationManager( 3058): ====startRecUseTime====
D/htc.customization.log.level( 3058):  is 
W/CustomizationLogLevel( 3058): Level value is invalid, use default level 2
D/Process (  906): killProcessQuiet, pid=2773
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
V/IccIntentReceiver( 1272): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/ActivityManager(  906): Killing 2773:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/SIMStateChangeReceiver( 1464): SIM state: ABSENT
I/SIMStateChangeReceiver( 1464): phoneType = 0
I/SIMStateChangeReceiver( 1464): remove notification
I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3109 uid=10031 gids={50031, 3003, 5012}
I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41b66008 +
I/Prism.WidgetManager( 1246): onLoadItems() +
I/ActivityManager(  906): Recipient 2773
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3058):  Read ACC file spent 0.084 (s)
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3058): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3058): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3058): Parsing tag category name = system
I/CustomizationCIDLoader( 3058): Parsing tag category name = application
I/CustomizationCIDLoader( 3058): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3058): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3058): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3058): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3058): Parsing tag category name = Settings
D/CustomizationManager( 3058):  Read CID file spent 0.135 (s)
D/CustomizationManager( 3058):  All configurations done spent 0.135 (s)
W/HtcNativeFlag( 3058): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3058): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3058): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3058): Fail to get flag for type 'language', use default value: -1
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  906): start
I/ActivityManager(  906): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3121 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=2169
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2169:com.android.defcontainer/u0a19 (adj 15): empty #17
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3058
W/asset   (  906): Copying FileAsset 0x69c13a10 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1113231984
D/PMS     (  906): acquireHCC(425aa280): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(427046d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
E/cutils-trace( 3058): Error opening trace file: No such file or directory (2)
D/PMS     (  906): acquireWL(425ca930): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/ActivityManager(  906): Recipient 2169
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/FeedHostManager( 1246): [onPause]
I/FeedProviderManager( 1246): onPause
I/FeedHostManager( 1246): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41b81618
I/SocialFeedProvider( 1246): +onPause
I/SocialFeedProvider( 1246): -onPause
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3134 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
W/SystemReader( 2548): Cannot find message_ambs_application_id, use default value instead
W/asset   ( 3134): Copying FileAsset 0x5c7f9428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/SmsReceiver( 2548): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
I/TrimMemoryManager( 1246): [trimMemory] 20
D/ExchangePolicystatus( 2548): onReceive()
D/ExchangePolicystatus( 2548): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2548): onReceive(): else
D/Process (  906): killProcessQuiet, pid=2805
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1221): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  906): Killing 2805:com.google.android.gm/u0a107 (adj 15): empty #17
V/WebViewChromiumFactoryProvider( 3134): Binding Chromium to main looper Looper (main, tid 1) {41ad34c8}
I/LibraryLoader( 3134): Expected native library version number "",actual native library version number ""
I/chromium( 3134): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3134): Initializing chromium process, renderers=0
W/WeatherUtility( 1108): can't get weather sync account
I/ActivityManager(  906): Recipient 2805
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(42608f30): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): acquireWL(425fdbc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  906): releaseWL(425fdbc0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424e3d30:true
D/BluetoothAdapter( 3134): 1101962496: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  906): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3153 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/AccTypeManager( 3121): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3121): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Adreno-EGL( 3134): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3134): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3134): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3134): Local Branch: 
I/Adreno-EGL( 3134): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3134): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3134):                  aa63bbd948f41d15fc72f585e
W/WeatherRequest( 1108): request cur loc, but there is no sys cur
D/AccTypeManager( 3121): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/Prism.WidgetManager( 1246): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1246): onLoadItems() -
I/Prism.ItemManager( 1246): loadItems() com.htc.launcher.pageview.WidgetManager@41b66008 -
W/chromium( 3134): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/CalendarApplication( 3153): onCreate
D/ProviderChangeReceiver( 3153): ---------------------------------------------------
D/ProviderChangeReceiver( 3153): ProviderChangeReceiver onReceive, start to update notification!
D/AlertService( 3153): start to updateAlertNotification!
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/ContextImpl( 2941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
W/dalvikvm( 3134): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3134): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3134): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3134): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3134): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
E/ExternalAccountType( 3121): Unsupported attribute readOnly
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3185 uid=10038 gids={50038}
W/dalvikvm( 3134): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3134): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3134): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3134): CordovaWebView is running on device made by: HTC
D/AlertService( 3153): No fired or scheduled alerts
D/HtcAlertUtils( 3153): -- cancelReminderNotification --
D/HtcAlertUtils( 3153): broadcastExistReminder!
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/Process (  906): killProcessQuiet, pid=2840
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2840:com.htc.backup/1000 (adj 15): empty #17
W/AccTypeManager( 3121): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3121): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 3121): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
E/ExternalAccountType( 3121): Unsupported attribute readOnly
D/Process (  906): killProcessQuiet, pid=2788
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3203 uid=10077 gids={50077}
I/ActivityManager(  906): Killing 2788:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/SMSBackup( 3203): Got a database change event
D/Process (  906): killProcessQuiet, pid=2864
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/GCM     ( 1337): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Killing 2864:com.google.android.talk/u0a111 (adj 15): empty #17
W/AwContents( 3134): nativeOnDraw failed; clearing to background color.
I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3222 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
I/InputMethodManagerService(  906): Disable input method client, pid=1246
I/InputMethodManagerService(  906): Enable input method client, pid=3134
W/ResourceType( 3134): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3134): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b1b088, mServedView=org.apache.cordova.engine.SystemWebView{41ae1020 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1184): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1184): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1184): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3134): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +365ms
I/ActivityManager(  906): Recipient 2840
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): releaseWL(425ca930): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/ActivityManager(  906): Recipient 2788
I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3237 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3222): can't get weather sync account
I/ActivityManager(  906): Recipient 2864
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherRequest( 3222): request cur loc, but there is no sys cur
W/Settings( 3222): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DemoRecovery.RestoreReceiver( 3237): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3237): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3237): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 0 9 17
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3251 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=2896
I/ActivityManager(  906): Killing 2896:com.htc.backupreset/1000 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
E/AndroidProtocolHandler( 3134): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3134): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/PMS     (  906): acquireWL(41edb9b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3251 10070 null
D/PMS     (  906): acquireWL(41bf17d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3251 10070 null
D/PMS     (  906): releaseWL(41edb9b8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3251): update TASK shortcut>
I/ActivityManager(  906): Recipient 2896
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/TodoTaskNotifyService( 3251): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/JsMessageQueue( 3134): Set native->JS mode to OnlineEventsBridgeMode
W/NotifyReceiver( 3251): stopSelfResult true
D/PMS     (  906): releaseWL(41bf17d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3269 uid=10081 gids={50081, 3003, 5012}
D/Process (  906): killProcessQuiet, pid=2911
I/ActivityManager(  906): Killing 2911:com.htc.htccupd/u0a17 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PhoneApp( 1221): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1221): -- N1 =0
D/PhoneApp( 1221): -- N2 =0
D/PhoneApp( 1221): -- N3 =0
I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3281 uid=10081 gids={50081, 3003, 5012}
D/jxcore_app_log( 3134): JniHelper::setJavaVM(0x415ab048), pthread_self() = 1658159984
D/JX-Cordova( 3134): jxcore cordova android initializing
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2911
D/Process (  906): killProcessQuiet, pid=2927
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/SMSBackup( 3203): Got a database change event
I/ActivityManager(  906): Killing 2927:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  906): Recipient 2927
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3293 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
D/Process (  906): killProcessQuiet, pid=2954
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 2954:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
W/jxcore-log( 3134): Initializing JXcore engine
W/jxcore-log( 3134): JXcore engine is ready
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/jxcore-log( 3134): Starting JXcore engine
I/ActivityManager(  906): Recipient 2954
I/ImageRamCache( 3293): create image Cache, size: 31457280.
I/ImageRamCache( 3293): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3293): create image Cache, size: 12582912.
I/FeedSettings( 3293): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3293): GroupBudget 0.500000 0.380000
I/FeedSettings( 3293): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3293): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3293): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3293): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3293): [custom highlight] onReceive
D/CustomHighlightService( 3293): [custom highlight] onHandleIntent
D/NewsDB  ( 3293): set custom highlight []
I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1221): MSG_NOTIFY_CS_TO_SYNC <<
D/CustomHighlightService( 3293): [custom highlight] set tags 
D/MessagingShortcutReceiver( 2548): keep hiding shortcut bubble
D/MessagingShortcut( 2548): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2548): After query: 0
D/MessagingShortcut( 2548): mPresentUnreadCount: -1
D/MessagingShortcut( 2548): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2548): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] reorderNotification, total:0
D/DotMatrix( 1533): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1533): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  906): Resuming delayed broadcast
D/TodoTaskshortcut( 3251): update TASK shortcut>
D/HtcBroadcastReceiver( 1221): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  906): killProcessQuiet, pid=2981
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2981:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2981
I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3309 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
W/jxcore-log( 3134): Platform android
W/jxcore-log( 3134): 
W/jxcore-log( 3134): Process ARCH arm
W/jxcore-log( 3134): 
I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3323 uid=10091 gids={50091, 3003, 5012}
D/MessagingNotification( 2548): New incoming message, can't cancel notification now
D/MessagingNotification( 2548): newMsgCnt: 0, false
I/jxcore-log( 3134): JXcore Cordova bridge is ready!
I/jxcore-log( 3134): 
W/jxcore-log( 3134): JXcore engine is started
D/MdScBoot( 3309): [828.1.] 30@-161114 -> 40@-161143
D/Process (  906): killProcessQuiet, pid=2995
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  906): killProcessQuiet, pid=3007
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 2995:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  906): Killing 3007:com.google.android.youtube/u0a168 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/GCM     ( 1337): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Recipient 2995
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3336 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
E/jxcore-log( 3134): >> HTC-HTC Desire 820
E/jxcore-log( 3134): 
I/jxcore-log( 3134): Total memory 1964650496
I/jxcore-log( 3134): 
I/jxcore-log( 3134): Free memory 728576000
I/jxcore-log( 3134): 
I/jxcore-log( 3134): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3134): 
I/jxcore-log( 3134): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3134): 
I/jxcore-log( 3134): userPath [ 'www' ]
I/jxcore-log( 3134): 
I/jxcore-log( 3134): Size 720 1184
I/jxcore-log( 3134): 
I/jxcore-log( 3134): Screen Brightness 10
I/jxcore-log( 3134): 
E/jxcore-log( 3134): Dummy Error Log.
E/jxcore-log( 3134): 
I/ActivityManager(  906): Recipient 3007
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3007): Died!
I/Babel   ( 3336): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3336): MmsConfig.loadMmsSettings
E/dalvikvm( 3336): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
E/ProviderInstaller( 3336): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3336): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
E/ProviderInstaller( 3336): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
V/JNIHelp ( 3336): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
D/MmsCustomizationProvider( 2548): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2548): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3336): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3336): MmsConfig.loadFromDatabase
E/Babel   ( 3336): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3336): MmsConfig.loadFromResources
E/Babel   ( 3336): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 3336): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3336, uid=10111, userID:0
W/Settings( 3336): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Process (  906): killProcessQuiet, pid=2965
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3336, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3336, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3336, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3336, uid=10111, userID:0
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3336, uid=10111, userID:0
I/ActivityManager(  906): Killing 2965:com.android.settings/1000 (adj 15): empty #17
D/GCM     ( 1337): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  906): Recipient 2965
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MtpReceiver( 2223): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2223): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2223): [MTP][handleMessage][startService]
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1740/10178)
D/MtpReceiver( 2223): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2223): [MTP][handleMessage]-
D/MtpService( 2223): [MTP] startForeground
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3362 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2223): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2223): TotalSize=1918604,MediaCacheLimit=6000
D/MtpService( 2223): [isMtpConnected] connected: true
I/ProviderInstaller( 3336): Installed default security provider GmsCore_OpenSSL
I/RemoteViews( 1108): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1108): com.android.providers.media 0 1 10
I/RemoteViews( 1108): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1108): com.android.providers.media 0 1 15
D/SyncApplication( 3362): Loading default preferences
W/Resources( 3362): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/WifiService(  906): New client listening to asynchronous messages
D/SyncApplication( 3362): Overriding preferences with custom values
D/SyncApplication( 3362): Updating preferences succeeded
E/SyncApplication( 3362): Application created.
D/VolumeInfo( 3362): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3362): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3362): Found 0 mount point(s)
V/VolumeInfo( 3362): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/VolumeInfo( 3362): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3362): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3362): Can not create volume ID for unmounted volume null
I/CalendarDefines( 3362): getNewCalendarAuthority()...
D/SyncApplication( 3362): enableAppOperation()+
D/SyncApplication( 3362): enableAppOperation()-
D/HTCUtilities( 3362): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3362, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3362, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3362): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
D/HTCUtilities( 3362): isNeorSinged() return false
D/CDMountReceiver( 3362): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/CDMountReceiver( 3362): USB connected to PC
D/FOTAReceiver( 3362): onReceive() enter 
D/FOTAReceiver( 3362): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3381 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=3063
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3063:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3063
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  906): killProcessQuiet, pid=3109
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3109:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3109
D/HtcFingerPrintQuickLaunchProvider( 3381): -onCreate()
V/Settings:HtcSettingsApplication( 3381): [3381/3381] onCreate()
D/TetherSettings( 3381): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3381): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3381): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3381): Cust_ConnectToPC   : spcsc>false
D/        ( 3381): Cust_ConnectToPC   : IPT>true
D/        ( 3381): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3381): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3381): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3381): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3381): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3381): Cust_ConnectToPC   : spcsc>false
D/        ( 3381): Cust_ConnectToPC   : IPT>true
D/        ( 3381): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3381): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3381): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3381): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3381): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3381): usb_cable_connect = 1
D/SmartNS_Utility( 3381): usb_denied = 0
I/SmartNS_NSReceiver( 3381): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3381): USB = true hasTethered = false isNSOpening: false
I/PSReceiver( 3381): onReceive:com.htc.intent.action.USB_CONNECT2PC
I/SmartNS_PSService( 3381): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3381): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3381): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3381):  defaultType:0
I/SmartNS_PSService( 3381): fail notificaiton:false
D/SmartNS_Utility( 3381): usb_cable_connect = 1
D/SmartNS_Utility( 3381): usb_denied = 0
I/SmartNS_PSService( 3381): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3381/1000)
D/SmartNS_Utility( 3381): usb_cable_connect = 1
D/SmartNS_Utility( 3381): usb_denied = 0
I/SmartNS_PSService( 3381): usb notificaiton:true
V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  906): bSetPropertyMultiRAB:false
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/SmartNS_Utility( 3381): usb_cable_connect = 1
D/SmartNS_Utility( 3381): usb_denied = 0
D/DotMatrix( 1533): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3381/1000)
I/SmartNS_PSService( 3381): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3381): USB Plugged, Set USBPlugged=  truePSenabled:false
D/Process (  906): killProcessQuiet, pid=3121
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/RemoteViews( 1108): com.android.settings (true,33751552)
I/ActivityManager(  906): Killing 3121:com.htc.contacts/u0a41 (adj 15): empty #17
I/RemoteViews.Performance( 1108): com.android.settings 0 1 10
I/RemoteViews( 1108): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1108): com.android.settings 1 0 10
W/WeatherUtility( 3222): can't get weather sync account
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1246): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1246): com.google.android.googlequicksearchbox 0 0 5
I/HtcModeClient( 1464): handler message = 4011
E/HtcModeClient( 1464): Check connection and retry 5 times.
I/jxcore-log( 3134): getBuffer is called!!!!
I/jxcore-log( 3134): 
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/WeatherRequest( 3222): request cur loc, but there is no sys cur
W/Settings( 3222): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  906): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3121
I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 1 11 17
D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1246): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1246): pl.k2.droidoaudioteka 1 1 8
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
I/ActivityManager(  906): Resuming delayed broadcast
V/AlarmManager(  906): sending alarm PendingIntent{425da468: PendingIntentRecord{425da3e8 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1449501104563, Int=0
I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,V/AlarmManager(  906): sending alarm PendingIntent{41b6f7f0: PendingIntentRecord{425455a0 com.google.android.gms startService}}, i=null, t=0, cnt=17069, w=84918423, Int=84918423
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1203/10028)
,I/AdsMeasurementBroadcastReceiver( 1203): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1203): Unauthorized to start the main service
,D/SnetService( 1203): snet destroyed
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
,D/PMS     (  906): releaseHCC(425aa280): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(427046d8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
D/PackageBroadcastService( 1203): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  906): acquireWL(427ff110): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(427ff110): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1203): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1203, uid=10028, userID:0
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3417 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1377): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1377): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3433 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3433, uid=10073, userID:0
,D/Finsky  ( 3433): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3433/10073)
,D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3433/10073)
,D/Finsky  ( 3433): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3433): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3433): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3433, uid=10073, userID:0
,D/Process (  906): killProcessQuiet, pid=3153
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1246): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  906): Killing 3153:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  906): Recipient 3153
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Finsky  ( 3433): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3433): [1] 2.run: Finished loading 1 libraries.
I/IcingCorporaProvider( 2663): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,D/Finsky  ( 3433): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  906): Delaying start of: ServiceRecord{4254eae0 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  906): acquireWL(425aaf30): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/Process (  906): killProcessQuiet, pid=2941
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2941:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 2941
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(425aaf30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(41f60928): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
D/Finsky  ( 3433): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PMS     (  906): releaseWL(41f60928): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3471 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  906): acquireWL(4214d500): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(4214d500): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42049f88): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,I/DeviceManagement( 3471): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3471 dbg=false s=true
,I/DeviceManagement( 3471): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  906): killProcessQuiet, pid=3237
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/ActivityManager(  906): Killing 3237:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3237
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(42049f88): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3484 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  906): acquireWL(41c2bf70): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(41c2bf70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42324990): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(42324990): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4203a858): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(4203a858): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42327f58): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(42327f58): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(41c9df98): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(41c9df98): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(424d7ca0): PARTIAL_WAKE_LOCK  Icing 0x1 1203 10028 null
,D/PMS     (  906): releaseWL(424d7ca0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2663): Copying FileAsset 0x63cc7128 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2663): UpdateCorporaTask done [took 454 ms] updated apps [took 454 ms] 
,D/PMS     (  906): releaseWL(42608f30): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/GAV2    ( 3484): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3504 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3504): ModelRegistry: Loading model meta data from resources...
,V/AlarmManager(  906): sending alarm PendingIntent{424a77b0: PendingIntentRecord{425f0f28 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449501106342, Int=0
,W/ContextImpl( 3504): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3504): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3471): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3471): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.inputdevices, com.htc.checkinprovider, com.android.settings, com.htc.feedback, com.htc.drive.activator, com.qualcomm.privinit, com.htc.android.htcloglevel, com.htc.autobot.cargps.provider, com.htc.home.personalize, com.android.CSDFunctionG, android, com.htc.backup, com.htc.smartdim, com.qualcomm.timeservice, com.htc.cirmodule, com.htc.lockscreen, com.htc.usage, com.htc.backupreset, com.android.providers.settings, com.htc.android.htcsetupwizard, com.android.keychain, com.htc.htcpowermanager, com.android.location.fused, com.htc.guide, com.htc.mirrorlinkserver]
,I/DeviceManagement( 3471): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3523 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/DeviceManagement( 3471): WorkflowService: Starting workflow service
I/DeviceManagement( 3471): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b11508] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3471): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3471): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3471): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3471): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3523):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  906): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,W/GLSUser ( 1337): GoogleAccountDataService.getToken()
,I/ActivityManager(  906): Resuming delayed broadcast
,I/GoogleHttpClient( 1337): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1337): Using GMS GoogleHttpClient
,I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3537 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
W/GAV2    ( 3484): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  906): killProcessQuiet, pid=3269
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3269:com.htc.stock/u0a81 (adj 15): empty #17
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1337): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  906): Recipient 3269
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1337): GoogleAccountDataService.getToken()
,I/DeviceManagement( 3471): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1337): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3433): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3433): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3471): SessionStateController: Checking invariants...
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(425156d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3537 10160 null
,D/PMS     (  906): acquireWL(425e7770): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3537 10160 null
,D/PMS     (  906): releaseWL(425156d8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  906): acquireWL(425764a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3537 10160 null
,D/PMS     (  906): releaseWL(425e7770): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/DeviceManagement( 3471): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3471): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b11508]
,I/DeviceManagement( 3471): WorkflowService: Stopping workflow service
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3537/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3537/10160)
I/ActivityManager(  906): Resuming delayed broadcast
D/Process (  906): killProcessQuiet, pid=3281
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3281:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3281
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(425764a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3565 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3185
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3185:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3185
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Settings:HtcWirelessFeatureFlags( 3381): id/is att sku: 99/false
,W/SystemReader( 3381): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3381): Cannot find support_harman, use default value instead
,W/SystemReader( 3381): Cannot find effect_manager_id, use default value instead
,W/ContextImpl( 3565): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3565): call getInstance()
,E/Settings:HtcWrapHeaderInfo( 3381): no such activity!
,D/PowerUsageList:PowerUsageHelper( 3565): MY_DEBUG = false
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3381): The wrap header doesn't exist in header list.
D/PMS     (  906): acquireWL(425c7710): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3565 1000 null
,E/Settings:HtcWrapHeaderInfo( 3381): updateDevelopment, bPrefShow = true
,W/WeatherUtility( 1108): can't get weather sync account
,D/WeatherUtility( 1377): Weather sync is On
,D/WSP     ( 1377): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherUtility( 3222): can't get weather sync account
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,E/Settings:HtcUmcWidgetEnabler( 3381): isSupportMusicChannel(): false
,W/GLSUser ( 1337): GoogleAccountDataService.getToken()
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]support         :false
W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1337): GLS error: BadAuthentication thalitester@gmail.com androidmarket
W/WeatherRequest( 3222): request cur loc, but there is no sys cur
,W/Settings( 3222): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/GLSActivity( 1337): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/FingerprintManager( 3381): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,D/AppWidgetHostView( 1246): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1246): com.htc.widget.weatherclock (true,33751552)
,W/Finsky  ( 3433): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,E/Settings:HtcVoWifiWidgetEnabler( 3381): isSupportVoWifi: null
,D/Finsky  ( 3433): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3381): Failed to find provider info for com.htc.vowifi
D/Finsky  ( 3433): [1] DailyHygiene.reschedule: Scheduling new run in 288 minutes (failures=4)
I/RemoteViews.Performance( 1246): com.htc.widget.weatherclock 1 9 17
W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3381): The wrap header doesn't exist in header list.
E/Settings:HtcWrapHeaderInfo( 3381): updateDevelopment, bPrefShow = true
E/Settings:HtcUmcWidgetEnabler( 3381): isSupportMusicChannel(): false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportRecentAppsButton]support         :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3381): [supportHomeButton]support         :false
,W/FingerprintManager( 3381): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3381): isSupportVoWifi: null
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3381): Failed to find provider info for com.htc.vowifi
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3589 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,D/Process (  906): killProcessQuiet, pid=3203
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3203:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3203
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SocialFeedProvider( 1246): +disConnect socialManager
,I/SocialFeedProvider( 1246): disconnect socialManager
,I/SocialFeedProvider( 1246): -disConnect socialManager
,I/SocialManager[SocialBiLogHelper]( 3293): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3293): last commit ulog time 1449467994035
,I/SocialManager[SocialBiLogHelper]( 3293): skip commit this time
V/AlarmManager(  906): sending alarm PendingIntent{41d80bb8: PendingIntentRecord{42391580 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449501107974, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42596f50: PendingIntentRecord{4249c750 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449501108120, Int=0
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3608 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3251
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3251:com.htc.task/u0a70 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=3309
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3309:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3251
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3309
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3608): Database version: 95
,W/ContextImpl( 3608): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3608): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3608): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3608): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3608): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3608, uid=10154, userID:0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 3608): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
I/MediaRouter( 3608): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3627 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3608/10154)
,D/MediaRouter( 3608): getSelectedRoute
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3608, uid=10154, userID:0
,D/Process (  906): killProcessQuiet, pid=3323
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Killing 3323:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/DFPI.PIReciver( 3627): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  906): Recipient 3323
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DFPI.ApkInstallService( 3627): onHandleIntent
I/DFPI.ApkInstallService( 3627): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3627): check CID = HTC__032
I/DFPI.ApkInstallService( 3627): There is no Demo.apk in sd card or phone storage
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3642 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3642/10051)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3642): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
,W/Settings:Agent(  906): >> traceCallingStack()
,W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1100
,W/Settings:Agent(  906): Process.myUid(): 1000
,W/Settings:Agent(  906): 
,W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 12(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
,D/WifiManager( 3134): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
D/WifiService(  906): New client listening to asynchronous messages
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
,W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
,W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
,W/Settings:Agent(  906): Process.myTid(): 1245
W/Settings:Agent(  906): Process.myUid(): 1000
,W/Settings:Agent(  906): 
,W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
D/WifiService(  906): setWifiEnabled: false pid=3134, uid=10355
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
W/Settings:Agent(  906): << traceCallingStack(): 7(ms)
I/jxcore-log( 3134): ****TEST TOOK:  5061  ms ****
I/jxcore-log( 3134): 
I/jxcore-log( 3134): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3134): 
,D/PMS     (  906): releaseWL(425c7710): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,E/cutils-trace( 3662): Error opening trace file: No such file or directory (2)
,D/CustomizationManager( 3662): ====startRecUseTime====
D/htc.customization.log.level( 3662):  is 
,W/CustomizationLogLevel( 3662): Level value is invalid, use default level 2
,I/HtcModeClient( 1464): handler message = 4011
,E/HtcModeClient( 1464): Check connection and retry 6 times.
,D/CustomizationManager( 3662):  Read ACC file spent 0.052 (s)
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 3662): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3662): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3662): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3662): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3662): Parsing tag category name = system
,I/CustomizationCIDLoader( 3662): Parsing tag category name = application
,I/CustomizationCIDLoader( 3662): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3662): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3662): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3662): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3662): Parsing tag category name = Settings
D/CustomizationManager( 3662):  Read CID file spent 0.091 (s)
,D/CustomizationManager( 3662):  All configurations done spent 0.092 (s)
W/HtcNativeFlag( 3662): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3662): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3662): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3662): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=3662, uid=2000 user=0
,W/asset   (  906): Copying FileAsset 0x69897098 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  906): Resuming delayed broadcast
,I/SensorManager(  906): mEventCount = 450
,W/PackageSettings(  906): Skipping PackageSetting{421cb4f8 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3673 uid=10080 gids={50080, 5001, 1028, 1015}
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
D/Process (  906): killProcessQuiet, pid=3134
I/ActivityManager(  906): Killing 3134:com.example.hello/u0a355 (adj 0): stop com.example.hello
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  906): Force removing ActivityRecord{425a9c10 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=0: pkg removed
,W/InputDispatcher(  906): channel '424af3e8 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  906): channel '424af3e8 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '424af3e8 com.example.hello.MainActivity (s)'
I/WindowManager(  906): WINDOW DIED Window{424af3e8 u0 com.example.hello/com.example.hello.MainActivity}
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/Process (  906): killProcessQuiet, pid=3336
I/FeedHostManager( 1246): [onResume]
,I/FeedProviderManager( 1246): onResume
I/SocialFeedProvider( 1246): +onResume
I/SocialFeedProvider( 1246): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1246): -onResume
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3336:com.google.android.talk/u0a111 (adj 15): empty #17
W/WindowManager(  906): Failed looking up window
W/WindowManager(  906): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@41ad77a8 does not exist
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  906): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  906): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  906): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  906): WIN DEATH: null
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1533): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1533): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/acms    ( 1766): Unregistering com.example.hello
,E/acms    ( 1766): Could not unregister removed application com.example.hello
W/AccTypeManager( 1306): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1306): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1399): Ignoring removeGeofence because network location is disabled.
,D/PMS     (  906): acquireWL(427610e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1399 10028 null
I/Prism.ItemManager( 3293): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3293): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/ConnectivityHelper( 1246): [getCurrentConnectionType] no network connection
,I/SoundPicker( 3673): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3673): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1246/10075)
,D/AccTypeManager( 1306): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/SoundPicker( 3673): SoundPickerReceiver [onReceive] startService
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/SoundPicker( 3673): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3673): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3673): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
D/PMS     (  906): releaseWL(427610e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3673): MODE_GSM access default DB
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3673): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3673): MODE_GSM access default DB
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1246): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/ActivityManager(  906): Recipient 3336
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,E/ExternalAccountType( 1306): Unsupported attribute readOnly
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42789470 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager(  906): Resuming delayed broadcast
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/PackageManager(  906):   Scheme: "smsto"
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1221 :
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
D/PhoneApp( 1221): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  906): Resuming delayed broadcast
,W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3134 uid 10355
,W/Binder  ( 1184): Caught a RuntimeException from the binder stub implementation.,
W/Binder  ( 1184): java.lang.NullPointerException
W/Binder  ( 1184): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1184): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1184): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1184): 	at dalvik.system.NativeStart.run(Native Method)
,D/DFPI.PIReciver( 3627): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/InputMethodManagerService(  906): Enable input method client, pid=1246
I/DFPI.ApkInstallService( 3627): onHandleIntent
,I/DFPI.ApkInstallService( 3627): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3627): check CID = HTC__032
,I/DFPI.ApkInstallService( 3627): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3673): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3673): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3673): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3673): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3673): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3673): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3673): MODE_GSM access default DB
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3673): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3673): MODE_GSM access default DB
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/DFPI.PIReciver( 3627): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3627): onHandleIntent
,I/DFPI.ApkInstallService( 3627): Media Scan Finished Case 
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/DFPI.ApkInstallService( 3627): check CID = HTC__032
,I/DFPI.ApkInstallService( 3627): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3673): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3673): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3673): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3673): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3673): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3673): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3673): MODE_GSM access default DB
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3673): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3673): MODE_GSM access default DB
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3673): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58,
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86,
I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3673): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3673): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3673): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,E/SharedPreferencesImpl( 3608): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/SQLiteDatabase( 3608): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 3608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3608): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3608): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 3608): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 3608): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3608): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3608): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 3608): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3608): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3608): threadid=16: thread exiting with uncaught exception (group=0x416a3e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.music:main
E/AndroidRuntime( 3608): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 3608): Process: com.google.android.music:main, PID: 3608
E/AndroidRuntime( 3608): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3608): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3608): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3608): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 3608): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 3608): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3608): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3608): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 3608): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3608): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,W/PackageManager(  906): Unable to load service info ResolveInfo{42614090 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/GAV2    ( 3484): Thread[GAThread,5,main]: No campaign data found.

```
