#### Test 50388019193a02f_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/YouTube ( 3009): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3009): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,D/YouTube ( 3009): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3009): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
--------- beginning of /dev/log/system
D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
D/MediaRouterService(  904): Client com.google.android.youtube (pid 3009): Registered
D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
I/MediaRouter( 3009): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/YouTube ( 3009): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3009): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1449078384&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.youtube (3009/10168)
D/libc    ( 3009): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3009): [NET] getaddrinfo-,err=8
D/libc    ( 3009): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3009): [NET] getaddrinfo-, 1
D/libc    ( 3009): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 3009): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 3009): Error sending ping
E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3009): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3009): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/MediaRouter( 3009): getSelectedRoute
D/YouTube ( 3009): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/YouTube ( 3009): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.youtube (3009/10168)
W/BroadcastQueue(  904): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
D/AutoSetting( 1376): receiver - intent: android.intent.action.USER_PRESENT
D/AutoSetting( 1376): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/YouTube ( 3009): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/TetherSettings( 2968): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/YouTube ( 3009): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/        ( 2968): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2968): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2968): Cust_ConnectToPC   : spcsc>false
D/        ( 2968): Cust_ConnectToPC   : IPT>true
D/        ( 2968): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2968): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2968): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2968): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2968): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/PSReceiver( 2968): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2968): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/YouTube ( 3009): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/SmartNS_PSService( 2968): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2968): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2968):  defaultType:0
D/Process (  904): killProcessQuiet, pid=2778
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2778:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2778
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/cutils-trace( 3046): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3046): ====startRecUseTime====
D/htc.customization.log.level( 3046):  is 
W/CustomizationLogLevel( 3046): Level value is invalid, use default level 2
W/PackageManager(  904): Unable to load service info ResolveInfo{42835610 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
D/CustomizationManager( 3046):  Read ACC file spent 0.078 (s)
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3046): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3046): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3046): Parsing tag category name = system
I/CustomizationCIDLoader( 3046): Parsing tag category name = application
I/CustomizationCIDLoader( 3046): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3046): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3046): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3046): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3046): Parsing tag category name = Settings
D/CustomizationManager( 3046):  Read CID file spent 0.126 (s)
D/CustomizationManager( 3046):  All configurations done spent 0.126 (s)
W/HtcNativeFlag( 3046): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3046): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3046): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3046): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3046
D/PMS     (  904): acquireHCC(42627bd8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
D/PMS     (  904): acquireHCC(4278b310): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
W/asset   (  904): Copying FileAsset 0x67401d20 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1115565488
D/PMS     (  904): acquireWL(42708060): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/FeedHostManager( 1245): [onPause]
I/FeedProviderManager( 1245): onPause
I/FeedHostManager( 1245): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bf3738
I/SocialFeedProvider( 1245): +onPause
I/SocialFeedProvider( 1245): -onPause
I/ActivityManager(  904): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3073 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
W/asset   ( 3073): Copying FileAsset 0x5c73b428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1245): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3073): Binding Chromium to main looper Looper (main, tid 1) {41ac58c0}
I/LibraryLoader( 3073): Expected native library version number "",actual native library version number ""
I/chromium( 3073): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3073): Initializing chromium process, renderers=0
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@421a5558:true
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3073): 1101917328: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  904): acquireWL(425e5a00): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  904): acquireWL(4257f460): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  904): releaseWL(425e5a00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3073): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3073): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3073): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3073): Local Branch: 
I/Adreno-EGL( 3073): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3073): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3073):                  aa63bbd948f41d15fc72f585e
W/chromium( 3073): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3073): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3073): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3073): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3073): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3073): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3073): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3073): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3073): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3073): CordovaWebView is running on device made by: HTC
I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41b5d0f0 +
I/Prism.WidgetManager( 1245): onLoadItems() +
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
,W/WeatherUtility( 1106): can't get weather sync account
I/ActivityManager(  904): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3113 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
W/AwContents( 3073): nativeOnDraw failed; clearing to background color.
W/WeatherRequest( 1106): request cur loc, but there is no sys cur
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
I/InputMethodManagerService(  904): Disable input method client, pid=1245
I/InputMethodManagerService(  904): Enable input method client, pid=3073
I/ActivityManager(  904): Displayed com.example.hello/.MainActivity: +274ms
D/browser ( 3113): Browser versionCode = 760001523 versionName = 7.0.2512153020
W/SWE_UI  ( 3113): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3113): Loading: swewebviewchromium
I/LibraryLoader( 3113): Time to load native libraries: 36 ms (timestamps 5354-5390)
I/LibraryLoader( 3113): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3113): Initializing chromium process, renderers=9
I/LibraryLoader( 3113): Expected native library version number "",actual native library version number ""
I/chromium( 3113): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
W/ResourceType( 3073): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3073): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b10018, mServedView=org.apache.cordova.engine.SystemWebView{41ad5fb0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3073): nativeOnDraw failed; clearing to background color.
W/XT9_C   ( 1182): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1182): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1182): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  904): releaseWL(42708060): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/AndroidProtocolHandler( 3073): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3073): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/asset   ( 1245): Copying FileAsset 0x667686c0 (zip:/data/app/com.gameloft.android.gdc-2.apk:/resources.arsc) to buffer size 405676 to make it aligned.
W/chromium( 3113): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
E/Prism.WidgetManager( 1245): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1245): onLoadItems() -
I/Prism.ItemManager( 1245): loadItems() com.htc.launcher.pageview.WidgetManager@41b5d0f0 -
I/Adreno-EGL( 3113): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3113): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3113): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3113): Local Branch: 
I/Adreno-EGL( 3113): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3113): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3113):                  aa63bbd948f41d15fc72f585e
D/JsMessageQueue( 3073): Set native->JS mode to OnlineEventsBridgeMode
D/Process (  904): killProcessQuiet, pid=2810
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 2810:com.google.android.gm/u0a107 (adj 15): empty #17
V/IccIntentReceiver( 1271): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1494): SIM state: ABSENT
I/SIMStateChangeReceiver( 1494): phoneType = 0
I/SIMStateChangeReceiver( 1494): remove notification
I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3155 uid=10031 gids={50031, 3003, 5012}
I/ActivityManager(  904): Recipient 2810
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3167 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
D/Process (  904): killProcessQuiet, pid=2180
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/jxcore_app_log( 3073): JniHelper::setJavaVM(0x415a2048), pthread_self() = 1658164800
D/JX-Cordova( 3073): jxcore cordova android initializing
I/ActivityManager(  904): Killing 2180:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2180
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/SystemReader( 2568): Cannot find message_ambs_application_id, use default value instead
D/SmsReceiver( 2568): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2568): onReceive()
D/ExchangePolicystatus( 2568): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2568): onReceive(): else
D/Process (  904): killProcessQuiet, pid=2846
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/HtcBroadcastReceiver( 1218): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  904): Killing 2846:com.htc.backup/1000 (adj 15): empty #17
W/jxcore-log( 3073): Initializing JXcore engine
W/jxcore-log( 3073): JXcore engine is ready
W/jxcore-log( 3073): Starting JXcore engine
I/ActivityManager(  904): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3184 uid=10038 gids={50038}
W/AccTypeManager( 3167): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3167): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/AccTypeManager( 3167): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  904): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3199 uid=10077 gids={50077}
D/Process (  904): killProcessQuiet, pid=2793
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 2793:com.htc.cs.dm/u0a98 (adj 15): empty #17
E/ExternalAccountType( 3167): Unsupported attribute readOnly
W/AccTypeManager( 3167): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 3167): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/SMSBackup( 3199): Got a database change event
D/AccTypeManager( 3167): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1218): MSG_NOTIFY_CS_TO_SYNC <<
D/Process (  904): killProcessQuiet, pid=2868
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3211 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
I/ActivityManager(  904): Killing 2868:com.google.android.talk/u0a111 (adj 15): empty #17
E/ExternalAccountType( 3167): Unsupported attribute readOnly
I/ActivityManager(  904): Recipient 2846
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2793
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CalendarApplication( 3211): onCreate
D/ProviderChangeReceiver( 3211): ---------------------------------------------------
D/ProviderChangeReceiver( 3211): ProviderChangeReceiver onReceive, start to update notification!
D/PhoneApp( 1218): EVENT_QUERY_MO_PACKAGES
D/AlertService( 3211): start to updateAlertNotification!
D/PhoneApp( 1218): -- N1 =0
D/PhoneApp( 1218): -- N2 =0
D/PhoneApp( 1218): -- N3 =0
D/GCM     ( 1345): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ContextImpl( 2941): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3211): No fired or scheduled alerts
D/HtcAlertUtils( 3211): -- cancelReminderNotification --
D/HtcAlertUtils( 3211): broadcastExistReminder!
D/DotMatrix( 1535): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/AdsMeasurementBroadcastReceiver( 1198): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1198): Unauthorized to start the main service
I/AdsMeasurementBroadcastReceiver( 1198): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 1198): Unauthorized to start the main service
W/jxcore-log( 3073): Platform android
W/jxcore-log( 3073): 
W/jxcore-log( 3073): Process ARCH arm
W/jxcore-log( 3073): 
I/ActivityManager(  904): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3227 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
D/Process (  904): killProcessQuiet, pid=2895
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2895:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2895
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2868
I/jxcore-log( 3073): JXcore Cordova bridge is ready!
I/jxcore-log( 3073): 
W/jxcore-log( 3073): JXcore engine is started
W/WeatherUtility( 3227): can't get weather sync account
I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3242 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/DemoRecovery.RestoreReceiver( 3242): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
W/ContextImpl( 3242): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
W/WeatherRequest( 3227): request cur loc, but there is no sys cur
W/Settings( 3227): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3242): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  904): Resuming delayed broadcast
E/jxcore-log( 3073): >> HTC-HTC Desire 820
E/jxcore-log( 3073): 
I/jxcore-log( 3073): Total memory 1964650496
I/jxcore-log( 3073): 
I/jxcore-log( 3073): Free memory 734461952
I/jxcore-log( 3073): 
I/jxcore-log( 3073): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3073): 
I/jxcore-log( 3073): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3073): 
D/Process (  904): killProcessQuiet, pid=2912
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/jxcore-log( 3073): userPath [ 'www' ]
I/jxcore-log( 3073): 
I/jxcore-log( 3073): Size 720 1184
I/jxcore-log( 3073): 
I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3256 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Killing 2912:com.htc.htccupd/u0a17 (adj 15): empty #17
I/jxcore-log( 3073): Screen Brightness 10
I/jxcore-log( 3073): 
E/jxcore-log( 3073): Dummy Error Log.
E/jxcore-log( 3073): 
D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/ActivityManager(  904): Recipient 2912
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 2 13 17
D/PMS     (  904): acquireWL(42344fb8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3256 10070 null
D/PMS     (  904): acquireWL(422efb40): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3256 10070 null
D/PMS     (  904): releaseWL(42344fb8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/TodoTaskshortcut( 3256): update TASK shortcut>
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
I/TodoTaskNotifyService( 3256): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1535): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(422efb40): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
W/NotifyReceiver( 3256): stopSelfResult true
D/Process (  904): killProcessQuiet, pid=2927
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3271 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  904): Killing 2927:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2927
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3283 uid=10081 gids={50081, 3003, 5012}
D/Process (  904): killProcessQuiet, pid=2956
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 2956:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2956
D/SMSBackup( 3199): Got a database change event
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3295 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
D/Process (  904): killProcessQuiet, pid=2983
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 2983:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2983
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ImageRamCache( 3295): create image Cache, size: 31457280.
I/ImageRamCache( 3295): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3295): create image Cache, size: 12582912.
I/FeedSettings( 3295): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3295): GroupBudget 0.500000 0.380000
I/FeedSettings( 3295): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 3295): changeLocale(): en_GB
I/Prism.AllAppsOptionsMa_( 3295): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3295): loadGridSize() with Alternative
D/CustomHighlightReceiver( 3295): [custom highlight] onReceive
D/CustomHighlightService( 3295): [custom highlight] onHandleIntent
D/NewsDB  ( 3295): set custom highlight []
I/ActivityManager(  904): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3295): [custom highlight] set tags 
I/ActivityManager(  904): Resuming delayed broadcast
D/Process (  904): killProcessQuiet, pid=2997
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1345): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  904): Killing 2997:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
D/MessagingShortcutReceiver( 2568): keep hiding shortcut bubble
D/MessagingShortcut( 2568): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2568): After query: 0
D/MessagingShortcut( 2568): mPresentUnreadCount: -1
D/MessagingShortcut( 2568): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2568): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1535): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
I/ActivityManager(  904): Recipient 2997
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Resuming delayed broadcast
D/DotMatrix( 1535): [EventService] reorderNotification, total:0
D/DotMatrix( 1535): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1535): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3256): update TASK shortcut>
,D/HtcBroadcastReceiver( 1218): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3313 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  904): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  904): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3327 uid=10091 gids={50091, 3003, 5012}
,D/MessagingNotification( 2568): New incoming message, can't cancel notification now
,D/MessagingNotification( 2568): newMsgCnt: 0, false
,D/MdScBoot( 3313): [798.1.] 30@-184556 -> 40@-184626
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3339 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  904): killProcessQuiet, pid=3009
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  904): killProcessQuiet, pid=2968
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3009:com.google.android.youtube/u0a168 (adj 15): empty #17
I/ActivityManager(  904): Killing 2968:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2968
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/jxcore-log( 3073): getBuffer is called!!!!
I/jxcore-log( 3073): 
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 5 times.
,E/dalvikvm( 3339): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3339): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 3339): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3339): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
I/Babel   ( 3339): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3339): MmsConfig.loadMmsSettings
V/JNIHelp ( 3339): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
I/ActivityManager(  904): Recipient 3009
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MmsCustomizationProvider( 2568): query uri: content://htc-mms-customization/mms-ua/ua_string
D/MmsCustomizationProvider( 2568): query uri: content://htc-mms-customization/mms-ua/ua_profile
,D/MediaRouterService(  904): Client com.google.android.youtube (pid 3009): Died!
I/Babel   ( 3339): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3339): MmsConfig.loadFromDatabase
,E/Babel   ( 3339): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3339): MmsConfig.loadFromResources
E/Babel   ( 3339): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3339): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3339, uid=10111, userID:0
,W/Settings( 3339): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
,D/Process (  904): killProcessQuiet, pid=3113
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/GCM     ( 1345): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3339, uid=10111, userID:0
I/ActivityManager(  904): Killing 3113:com.htc.sense.browser/u0a12 (adj 15): empty #17
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1748/10178)
,D/MtpReceiver( 2234): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2234): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2234): [MTP][handleMessage][startService]
,D/MtpReceiver( 2234): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2234): [MTP][handleMessage]-
,D/MtpService( 2234): [MTP] startForeground
,I/RemoteViews( 1106): com.android.providers.media (false,0)
,I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3366 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews.Performance( 1106): com.android.providers.media 0 1 10
I/RemoteViews( 1106): com.android.providers.media (false,0)
D/DotMatrix( 1535): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2234): updating state; isCurrentUser=true, mMtpLocked=false
I/RemoteViews.Performance( 1106): com.android.providers.media 2 1 15
D/MtpDatabase( 2234): TotalSize=1918604,MediaCacheLimit=6000
I/ProviderInstaller( 3339): Installed default security provider GmsCore_OpenSSL
D/MtpService( 2234): [isMtpConnected] connected: true
,D/SyncApplication( 3366): Loading default preferences
,W/Resources( 3366): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3113
,D/WifiService(  904): New client listening to asynchronous messages
,D/SyncApplication( 3366): Overriding preferences with custom values
,D/SyncApplication( 3366): Updating preferences succeeded
,E/SyncApplication( 3366): Application created.
,D/VolumeInfo( 3366): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3366): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3366): Found 0 mount point(s)
,V/VolumeInfo( 3366): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3366): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3366): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3366): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3366): getNewCalendarAuthority()...
,D/SyncApplication( 3366): enableAppOperation()+
,D/SyncApplication( 3366): enableAppOperation()-
,D/HTCUtilities( 3366): isNeorSinged() + 
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3366, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3366, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3366): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3366): isNeorSinged() return false
D/CDMountReceiver( 3366): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3366): USB connected to PC
D/FOTAReceiver( 3366): onReceive() enter 
,D/FOTAReceiver( 3366): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3385 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  904): Killing 3155:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,D/Process (  904): killProcessQuiet, pid=3155
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  904): Recipient 3155
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
,D/PMS     (  904): releaseHCC(42627bd8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  904): releaseHCC(4278b310): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/HtcFingerPrintQuickLaunchProvider( 3385): -onCreate()
,V/Settings:HtcSettingsApplication( 3385): [3385/3385] onCreate()
,D/Process (  904): killProcessQuiet, pid=3167
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/TetherSettings( 3385): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3385): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3385): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3385): Cust_ConnectToPC   : spcsc>false
D/        ( 3385): Cust_ConnectToPC   : IPT>true
,D/        ( 3385): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3385): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/ActivityManager(  904): Killing 3167:com.htc.contacts/u0a41 (adj 15): empty #17
D/TetherSettings( 3385): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3385): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3385): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3385): Cust_ConnectToPC   : spcsc>false
D/        ( 3385): Cust_ConnectToPC   : IPT>true
D/        ( 3385): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3385): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3385): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3385): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3385): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3385): usb_cable_connect = 1
D/SmartNS_Utility( 3385): usb_denied = 0
I/SmartNS_NSReceiver( 3385): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3385): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3385): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3385): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3385): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3385): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3385):  defaultType:0
I/SmartNS_PSService( 3385): fail notificaiton:false
D/SmartNS_Utility( 3385): usb_cable_connect = 1
D/SmartNS_Utility( 3385): usb_denied = 0
I/SmartNS_PSService( 3385): usb notificaiton:true
V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  904): bSetPropertyMultiRAB:false
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3385/1000)
D/SmartNS_Utility( 3385): usb_cable_connect = 1
D/SmartNS_Utility( 3385): usb_denied = 0
I/SmartNS_PSService( 3385): usb notificaiton:true
V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/DotMatrix( 1535): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  904): bSetPropertyMultiRAB:false
,I/RemoteViews( 1106): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1106): com.android.settings 1 0 10
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3385/1000)
,I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/SmartNS_Utility( 3385): usb_cable_connect = 1
,D/SmartNS_Utility( 3385): usb_denied = 0
,D/DotMatrix( 1535): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/SmartNS_PSService( 3385): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3385): USB Plugged, Set USBPlugged=  truePSenabled:false
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
I/ActivityManager(  904): Resuming delayed broadcast
,W/WeatherUtility( 3227): can't get weather sync account
,I/RemoteViews( 1106): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1106): com.android.settings 0 1 10
,D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1245): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1245): com.google.android.googlequicksearchbox 0 0 5
,I/ActivityManager(  904): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
,I/RemoteViews( 1245): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1245): pl.k2.droidoaudioteka 0 1 8
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Recipient 3167
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  904): getAllProviders()=[passive, gps, network]
,I/ActivityManager(  904): Resuming delayed broadcast
W/WeatherRequest( 3227): request cur loc, but there is no sys cur
W/Settings( 3227): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 1 6 17
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,V/AlarmManager(  904): sending alarm PendingIntent{42559d70: PendingIntentRecord{42579ae8 com.google.android.gms startService}}, i=null, t=0, cnt=17064, w=84918423, Int=84918423
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1198/10028)
,I/AdsMeasurementBroadcastReceiver( 1198): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1198): Unauthorized to start the main service
,D/SnetService( 1198): snet destroyed
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 1198): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/PMS     (  904): acquireWL(423226e8): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(423226e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1198): CP2 sync disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1198, uid=10028, userID:0
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3422 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3211
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3211:com.htc.calendar/u0a13 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1376): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1376): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3211
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3438 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3438, uid=10073, userID:0
,D/Finsky  ( 3438): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3438/10073)
,D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3438/10073)
,D/Finsky  ( 3438): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
D/PMS     (  904): releaseWL(4257f460): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,W/Settings( 3438): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3438): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3438, uid=10073, userID:0
,D/Process (  904): killProcessQuiet, pid=2941
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Prism.PackageStateRece_( 1245): action: android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  904): Killing 2941:com.android.settings:remote/1000 (adj 15): empty #17
D/Finsky  ( 3438): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3438): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  904): Recipient 2941
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2683): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 3438): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  904): Delaying start of: ServiceRecord{426c9088 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  904): acquireWL(425cad18): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(425cad18): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(425c14c8): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(425c14c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/Finsky  ( 3438): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  904): acquireWL(425667a0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(425667a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(4241e880): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/.GelStubAppWatcher
,D/PMS     (  904): releaseWL(4241e880): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3475 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  904): acquireWL(41c18e30): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(41c18e30): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(41cf9c38): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(41cf9c38): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(41c45980): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,I/DeviceManagement( 3475): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3475 dbg=false s=true
,I/DeviceManagement( 3475): PackageUpdateReceiver: vvv Package added: [com.example.hello]
D/PMS     (  904): releaseWL(41c45980): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3488 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,I/ActivityManager(  904): Killing 3242:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3242
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  904): Recipient 3242
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(424132a0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(424132a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(423671e0): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(423671e0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(421b0d88): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(421b0d88): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(41c6c178): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(41c6c178): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2683): Copying FileAsset 0x5ca87d00 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/PMS     (  904): acquireWL(4239c518): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,D/PMS     (  904): releaseWL(4239c518): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(41d51410): PARTIAL_WAKE_LOCK  Icing 0x1 1198 10028 null
,I/IcingCorporaProvider( 2683): UpdateCorporaTask done [took 506 ms] updated apps [took 506 ms] 
,W/GAV2    ( 3488): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  904): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,V/AlarmManager(  904): sending alarm PendingIntent{424411e8: PendingIntentRecord{42788cd8 com.android.vending startService}}, i=null, t=0, cnt=1, w=1449078389125, Int=0
,W/GLSUser ( 1345): GoogleAccountDataService.getToken()
,I/GoogleHttpClient( 1345): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1345): Using GMS GoogleHttpClient
I/ActivityManager(  904): Resuming delayed broadcast
,W/GLSActivity( 1345): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1345): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GAV2    ( 3488): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,W/GLSActivity( 1345): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  904): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3511 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/GLSUser ( 1345): GoogleAccountDataService.getToken()
,W/GLSActivity( 1345): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1345): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1345): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/htcbackup-core( 3511): ModelRegistry: Loading model meta data from resources...
,W/Finsky  ( 3438): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/ContextImpl( 3511): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,D/Finsky  ( 3438): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
W/ContextImpl( 3511): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3475): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3475): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[android, com.htc.android.htcsetupwizard, com.android.providers.settings, com.android.keychain, com.htc.htcpowermanager, com.qualcomm.privinit, com.htc.backupreset, com.htc.usage, com.qualcomm.timeservice, com.android.CSDFunctionG, com.htc.lockscreen, com.htc.autobot.cargps.provider, com.htc.backup, com.htc.guide, com.android.location.fused, com.htc.checkinprovider, com.htc.drive.activator, com.htc.home.personalize, com.htc.feedback, com.htc.smartdim, com.android.inputdevices, com.htc.mirrorlinkserver, com.android.settings, com.htc.cirmodule, com.htc.android.htcloglevel]
,I/DeviceManagement( 3475): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  904): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3530 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,I/ActivityManager(  904): Killing 3271:com.htc.stock/u0a81 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3271
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/DeviceManagement( 3475): WorkflowService: Starting workflow service
I/DeviceManagement( 3475): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b095a8] args=[Bundle[mParcelledData.dataSize=144]]
I/DeviceManagement( 3475): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
I/DeviceManagement( 3475): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3475): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3475): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3530):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
I/ActivityManager(  904): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/ActivityManager(  904): Recipient 3271
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DeviceManagement( 3475): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/Icing   ( 1198): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
,I/DeviceManagement( 3475): SessionStateController: Checking invariants...
,I/DeviceManagement( 3475): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,W/GLSUser ( 1345): GoogleAccountDataService.getToken()
,I/DeviceManagement( 3475): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b095a8]
,I/ActivityManager(  904): Resuming delayed broadcast
I/DeviceManagement( 3475): WorkflowService: Stopping workflow service
,I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3545 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3283
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3283:com.htc.stock:remote/u0a81 (adj 15): empty #17
,W/GLSActivity( 1345): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1345): GLS error: BadAuthentication thalitester@gmail.com androidmarket
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3283
,W/GLSActivity( 1345): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Icing   ( 1198): Indexing done 3E78574859FB8ED28F43D3ECB139F4117F00AB29
,W/Finsky  ( 3438): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3438): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3438): [1] DailyHygiene.reschedule: Scheduling new run in 10 minutes (failures=1)
D/PMS     (  904): releaseWL(41d51410): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/Process (  904): killProcessQuiet, pid=3184
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3184:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3184
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(42810480): PARTIAL_WAKE_LOCK  AsyncService 0x1 3545 10160 null
,D/PMS     (  904): acquireWL(42809ff0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3545 10160 null
,D/PMS     (  904): releaseWL(42810480): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/PMS     (  904): acquireWL(4275fa00): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3545 10160 null
,D/PMS     (  904): releaseWL(42809ff0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3575 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3545/10160)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3545/10160)
,D/Settings:HtcWirelessFeatureFlags( 3385): id/is att sku: 99/false
,D/Process (  904): killProcessQuiet, pid=3199
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  904): releaseWL(4275fa00): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  904): Killing 3199:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
W/ContextImpl( 3575): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,W/SystemReader( 3385): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/PowerUsageService( 3575): call getInstance()
I/ActivityManager(  904): Recipient 3199
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(425ffb58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3575 1000 null
,W/SystemReader( 3385): Cannot find support_harman, use default value instead
,W/SystemReader( 3385): Cannot find effect_manager_id, use default value instead
,W/WeatherUtility( 1106): can't get weather sync account
,D/PowerUsageList:PowerUsageHelper( 3575): MY_DEBUG = false
,D/WeatherUtility( 1376): Weather sync is On
,D/WSP     ( 1376): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/WeatherUtility( 3227): can't get weather sync account
,E/Settings:HtcWrapHeaderInfo( 3385): no such activity!
W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3385): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3385): updateDevelopment, bPrefShow = true
,W/WeatherRequest( 3227): request cur loc, but there is no sys cur
,W/Settings( 3227): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Settings:HtcUmcWidgetEnabler( 3385): isSupportMusicChannel(): false
,D/AppWidgetHostView( 1245): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1245): com.htc.widget.weatherclock (true,33751552)
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]support         :false
,W/FingerprintManager( 3385): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,I/RemoteViews.Performance( 1245): com.htc.widget.weatherclock 2 12 17
,E/Settings:HtcVoWifiWidgetEnabler( 3385): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3385): Failed to find provider info for com.htc.vowifi
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3385): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3385): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3385): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3385): [supportHomeButton]support         :false
,W/FingerprintManager( 3385): hasFingerprint() - sSensorCode = 0
W/BatSI   (  904): Couldn't get kernel wake lock stats
,E/Settings:HtcVoWifiWidgetEnabler( 3385): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3385): Failed to find provider info for com.htc.vowifi
,I/SocialFeedProvider( 1245): +disConnect socialManager
,I/SocialFeedProvider( 1245): disconnect socialManager
,I/SocialFeedProvider( 1245): -disConnect socialManager
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3595 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,V/AlarmManager(  904): sending alarm PendingIntent{42330a88: PendingIntentRecord{4232d140 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1449078390686, Int=0
,I/SocialManager[SocialBiLogHelper]( 3295): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3295): last commit ulog time 1449056441517
,I/SocialManager[SocialBiLogHelper]( 3295): skip commit this time
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SensorManager(  904): mEventCount = 450
,D/BluetoothManagerService(  904): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  904): disable(): mBluetooth = null mBinding = false
,W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  904): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 0
W/Settings:Agent(  904): >> traceCallingStack()
,W/Settings:Agent(  904): Process.myPid(): 904
,W/Settings:Agent(  904): Process.myTid(): 1243
,W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
W/System.err(  904): java.lang.Throwable: stack dump
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  904): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
,W/Settings:Agent(  904): << traceCallingStack(): 4(ms),
,D/BluetoothManagerService(  904): Message: MESSAGE_DISABLE
,D/WifiManager( 3073): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
D/WifiService(  904): New client listening to asynchronous messages
D/WifiService(  904): setWifiEnabled: false pid=3073, uid=10355
E/WifiService(  904): Invoking mWifiStateMachine.setWifiEnabled
,W/HtcDLNAServiceManager(  904): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  904): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  904): Settings:Agentvalue: 0
W/Settings:Agent(  904): >> traceCallingStack()
W/Settings:Agent(  904): Process.myPid(): 904
W/Settings:Agent(  904): Process.myTid(): 1262
W/Settings:Agent(  904): Process.myUid(): 1000
W/Settings:Agent(  904): 
W/Settings:Agent(  904): 
,W/System.err(  904): java.lang.Throwable: stack dump,
W/System.err(  904): ,	,at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  904): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  904): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64),
W/System.err(  904): ,	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  904): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  904): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  904): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  904): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  904): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  904): 
W/Settings:Agent(  904): << traceCallingStack(): 2(ms)
I/jxcore-log( 3073): ****TEST TOOK:  5054  ms ****
I/jxcore-log( 3073): 
,I/jxcore-log( 3073): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3073): 
I/WifiService(  904): isSprintWifiRestricted(): false
I/WifiService(  904): isMdmWifiRestricted(): false
D/WifiSettingsStore(  904): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,V/AlarmManager(  904): sending alarm PendingIntent{4230b708: PendingIntentRecord{4212de18 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1449078391302, Int=0
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3617 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3256
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3256:com.htc.task/u0a70 (adj 15): empty #17
,D/PMS     (  904): releaseWL(425ffb58): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/Process (  904): killProcessQuiet, pid=3313
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3313:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3313
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3617): Database version: 95
,W/ContextImpl( 3617): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3256
,W/ContextImpl( 3617): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils-trace( 3615): Error opening trace file: No such file or directory (2)
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3617): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
W/Vold    (  352): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3617, uid=10154, userID:0
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/MediaRouterService(  904): Client com.google.android.music (pid 3617): Registered
,I/MediaRouter( 3617): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3643 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.music (3617/10154)
,D/MediaRouter( 3617): getSelectedRoute
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3617, uid=10154, userID:0
,D/Process (  904): killProcessQuiet, pid=3327
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Killing 3327:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/DFPI.PIReciver( 3643): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 3643): onHandleIntent
,I/DFPI.ApkInstallService( 3643): Media Scan Finished Case 
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/DFPI.ApkInstallService( 3643): check CID = HTC__032
,I/DFPI.ApkInstallService( 3643): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3659 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/ActivityManager(  904): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3659/10051)
,E/cutils  (  352): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/CustomizationManager( 3615): ====startRecUseTime====
D/htc.customization.log.level( 3615):  is 
,W/CustomizationLogLevel( 3615): Level value is invalid, use default level 2
,W/Vold    (  352): Returning OperationFailed - no handler for errno 30
I/HtcModeClient( 1494): handler message = 4011
E/HtcModeClient( 1494): Check connection and retry 6 times.
,W/ContextImpl( 3659): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 3327
,D/CustomizationManager( 3615):  Read ACC file spent 0.058 (s)
,D/CIDMapFileReader( 3615): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3615): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3615): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3615): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3615): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3615): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3615): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3615): Parsing tag item name = HTC__M27
,D/CIDMapFileReader( 3615): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3615): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3615): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3615): Parsing tag category name = system
,I/CustomizationCIDLoader( 3615): Parsing tag category name = application
,I/CustomizationCIDLoader( 3615): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3615): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3615): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3615): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3615): Parsing tag category name = Settings
D/CustomizationManager( 3615):  Read CID file spent 0.103 (s)
,D/CustomizationManager( 3615):  All configurations done spent 0.103 (s)
W/HtcNativeFlag( 3615): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3615): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3615): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3615): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  904): deletePackageAsUser: pkg=com.example.hello, pid=3615, uid=2000 user=0
,I/ActivityManager(  904): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
,D/Process (  904): killProcessQuiet, pid=3073
,W/asset   (  904): Copying FileAsset 0x6a0ea870 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  904): Killing 3073:com.example.hello/u0a355 (adj 0): stop com.example.hello
W/ActivityManager(  904): Force removing ActivityRecord{426275e0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  904): Skipping PackageSetting{4228cc60 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  904): Force stopping com.example.hello appid=10355 user=0: pkg removed
,W/InputDispatcher(  904): channel '427f3308 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  904): channel '427f3308 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,D/WifiService(  904): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1106): ApplicationsIntentReceiver replacing:false
,W/InputDispatcher(  904): Attempted to unregister already unregistered input channel '427f3308 com.example.hello.MainActivity (s)'
D/DotMatrix( 1535): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1535): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1535): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowManager(  904): WINDOW DIED Window{427f3308 u0 com.example.hello/com.example.hello.MainActivity}
I/acms    ( 1767): Unregistering com.example.hello
,E/acms    ( 1767): Could not unregister removed application com.example.hello
I/FeedHostManager( 1245): [onResume]
,I/FeedProviderManager( 1245): onResume
I/SocialFeedProvider( 1245): +onResume
I/SocialFeedProvider( 1245): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1245): -onResume
D/PMS     (  904): acquireWL(428430e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1405 10028 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.launcher (1245/10075)
W/GeofencerStateMachine( 1405): Ignoring removeGeofence because network location is disabled.
,I/ConnectivityHelper( 1245): [getCurrentConnectionType] no network connection
W/SystemReader( 1229): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/Prism.ItemManager( 3295): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3295): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(428430e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
W/WindowManager(  904): Failed looking up window
W/WindowManager(  904): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@427f30b8 does not exist
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  904): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  904): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  904): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  904): WIN DEATH: null
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1245): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,E/ExternalAccountType( 1308): Unsupported attribute readOnly
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1218 :
,D/PhoneApp( 1218): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 3073 uid 10355
,I/InputMethodManagerService(  904): Enable input method client, pid=1245
W/Binder  ( 1182): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1182): java.lang.NullPointerException
W/Binder  ( 1182): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1182): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1182): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1182): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42866430 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3682 uid=10080 gids={50080, 5001, 1028, 1015}
,I/SoundPicker( 3682): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3682): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3682): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3682): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3682): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3682): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3682): MODE_GSM access default DB
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3682): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3682): MODE_GSM access default DB
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3339
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3339:com.google.android.talk/u0a111 (adj 15): empty #17
,D/DFPI.PIReciver( 3643): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3643): onHandleIntent
,I/DFPI.ApkInstallService( 3643): Media Scan Finished Case 
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/DFPI.ApkInstallService( 3643): check CID = HTC__032
,I/DFPI.ApkInstallService( 3643): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Resuming delayed broadcast
,I/SoundPicker( 3682): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3682): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3682): SoundPickerReceiver [onReceive] startService
,W/PackageManager(  904): Unable to load service info ResolveInfo{425604c8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  904): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  904): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  904): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  904): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  904): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  904): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  904): 	at dalvik.system.NativeStart.main(Native Method)
I/SoundPicker( 3682): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3682): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3682): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3682): MODE_GSM access default DB
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3682): TurnFileToMediaUriServ,ice [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3682): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3682): MODE_GSM access default DB
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/ActivityManager(  904): Recipient 3339
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3643): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  904): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3643): onHandleIntent
,I/DFPI.ApkInstallService( 3643): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3643): check CID = HTC__032
,I/DFPI.ApkInstallService( 3643): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/SoundPicker( 3682): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3682): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3682): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 3682): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3682): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3682): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3682): MODE_GSM access default DB
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
,I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3682): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3682): MODE_GSM access default DB
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  904): start
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,W/AtomicFile(  904): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
W/AppWidgetServiceImpl(  904): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3682): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3682): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3682): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3682): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  904): Resuming delayed broadcast
,E/SharedPreferencesImpl( 3617): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/SQLiteDatabase( 3617): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 3617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 3617): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 3617): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3617): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3617): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 3617): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3617): threadid=16: thread exiting with uncaught exception (group=0x4169ae30)
,E/ActivityManager(  904): App crashed! Process: com.google.android.music:main
E/AndroidRuntime( 3617): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 3617): Process: com.google.android.music:main, PID: 3617
E/AndroidRuntime( 3617): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3617): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3617): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3617): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 3617): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 3617): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3617): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3617): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
,E/AndroidRuntime( 3617): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3617): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  904): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  904): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  904): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  904): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  904): 	... 5 more

```
