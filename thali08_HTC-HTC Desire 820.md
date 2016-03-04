#### Test 61703351a2a4153_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bb30a8 +
I/Prism.WidgetManager( 1247): onLoadItems() +
E/Prism.WidgetManager( 1247): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1247): onLoadItems() -
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bb30a8 -
D/PhoneApp( 1220): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1220): -- N1 =0
D/PhoneApp( 1220): -- N2 =0
D/PhoneApp( 1220): -- N3 =0
D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC <<
W/PackageManager(  904): Unable to load service info ResolveInfo{4258ed30 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/GAV2    ( 2798): Thread[GAThread,5,main]: No campaign data found.
--------- beginning of /dev/log/system
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/RemoteDisplayProvider(  904): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  904): start
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:73 android.app.ActivityThread.handleReceiver:2687 
I/RemoteViews( 1108): com.android.settings (true,33751552)
D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41b794a0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1108): com.android.settings 2 7 0 10
D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  904): Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/com.htc.kddi.uicclock.NfcUiccLockReceiver: pid=2979 uid=9987 gids={49987}
D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews( 1108): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1108): com.android.settings 2 0 10
I/SensorManager(  904): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@425d9400, sensor = {Sensor name="BOSCH BMA250 3-axis Accelerometer", vendor="BOSCH", version=1, type=1, maxRange=39.2266, resolution=0.038307227, power=0.2, minDelay=10000}, delay = 66667, handler = null
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): enable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425d9400, eanble = 1, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42367110
W/SensorService(  904): Listener[1] = com.android.server.power.DisplayPowerController$10@421bff50
W/SensorService(  904): Listener[2] = com.htc.smartdim.sensor_eye@425d9400
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  904): registerListenerImpl: listener = com.htc.smartdim.sensor_eye@425d9400, sensor = {Sensor name="CM36282 Proximity sensor", vendor="Capella Microsystems", version=1, type=8, maxRange=9.0, resolution=9.0, power=0.18, minDelay=0}, delay = 66667, handler = null
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): enable: get sensor name = CM36282 Proximity sensor
W/BroadcastQueue(  904): Permission Denial: broadcasting Intent { act=com.htc.cover.closed flg=0x10 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_DEFAULT due to registered receiver BroadcastFilter{423d8df0 u0 ReceiverList{423d8d90 904 system/1000/u0 local:427937c8}}
V/AlarmManager(  904): sending alarm PendingIntent{42335010: PendingIntentRecord{424ebcd0 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=52873, Int=0
D/NfcUiccLockService( 2979): -- To check whether previous opened channel needed to be closed ...
I/ActivityManager(  904): Start proc com.android.smith for broadcast com.android.smith/.BootCompleteReceiver: pid=2994 uid=10163 gids={50163, 1007, 1028, 1015, 1023}
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 3
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): CM36282 Light sensor (handle=0x00000002, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425d9400, eanble = 1, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 3
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42367110
W/SensorService(  904): Listener[1] = com.android.server.power.DisplayPowerController$10@421bff50
W/SensorService(  904): Listener[2] = com.htc.smartdim.sensor_eye@425d9400
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/MdScBoot( 2766): [2b0.1.] 30@-132155 -> 40@-132225
D/Process (  904): killProcessQuiet, pid=2686
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2686:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/ActivityManager(  904): Recipient 2686
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  904): killProcessQuiet, pid=2734
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3013 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  904): Killing 2734:com.htc.android.worldclock/u0a90 (adj 15): empty #17
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2734
I/HtcModeClient( 1494): handler message = 4011
E/HtcModeClient( 1494): Check connection and retry 5 times.
D/CustomizationManager( 2977): ====startRecUseTime====
D/htc.customization.log.level( 2977):  is 
W/CustomizationLogLevel( 2977): Level value is invalid, use default level 2
D/CustomizationManager( 2977):  Read ACC file spent 0.069 (s)
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2977): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2977): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2977): Parsing tag category name = system
I/CustomizationCIDLoader( 2977): Parsing tag category name = application
I/CustomizationCIDLoader( 2977): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2977): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2977): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2977): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2977): Parsing tag category name = Settings
D/CustomizationManager( 2977):  Read CID file spent 0.114 (s)
D/CustomizationManager( 2977):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 2977): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2977): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2977): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2977): Fail to get flag for type 'language', use default value: -1
E/YouTube ( 3013): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
W/CpuWake (  904): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  904): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  904): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  904): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2977
D/PMS     (  904): acquireHCC(425a18b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 904 1000 null
W/asset   (  904): Copying FileAsset 0x69e25810 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  904): @test_code: getHtcIntentFlag: 0 obj: 1115528120
D/PMS     (  904): acquireHCC(427b04f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 904 1000 null
I/FeedHostManager( 1247): [onPause]
I/FeedProviderManager( 1247): onPause
I/FeedHostManager( 1247): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d85128
I/SocialFeedProvider( 1247): +onPause
I/SocialFeedProvider( 1247): -onPause
E/cutils-trace( 2977): Error opening trace file: No such file or directory (2)
D/PMS     (  904): acquireWL(427cdb80): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 904 1000 null
I/ActivityManager(  904): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3037 uid=10190 gids={50190, 3003, 5012, 3001, 3002}
D/libc    ( 3013): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3013): [NET] getaddrinfo-, SUCCESS
W/asset   ( 3037): Copying FileAsset 0x5d821c88 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/YouTube ( 3013): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
I/TrimMemoryManager( 1247): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3037): Binding Chromium to main looper Looper (main, tid 1) {41b1ca88}
I/LibraryLoader( 3037): Expected native library version number "",actual native library version number ""
I/chromium( 3037): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3037): Initializing chromium process, renderers=0
D/PMS     (  904): acquireWL(4270cc28): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  904): acquireWL(427eea00): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
W/System.err(  904): java.lang.Throwable: stack dump
D/BluetoothManagerService(  904): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  904): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  904): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  904): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  904): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  904): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  904): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428795c8:true
D/BluetoothAdapter( 3037): 1102265712: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  904): releaseWL(4270cc28): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3037): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3037): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3037): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3037): Local Branch: 
I/Adreno-EGL( 3037): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3037): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3037):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.youtube (3013/10168)
W/chromium( 3037): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3013): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 3037): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3037): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3037): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3037): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3037): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3037): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3037): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3037): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3037): CordovaWebView is running on device made by: HTC
D/YouTube ( 3013): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3013): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3013): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
,W/AwContents( 3037): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  904): Disable input method client, pid=1247
,I/ActivityManager(  904): Displayed com.example.hello/.MainActivity: +255ms
W/ResourceType( 3037): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3037): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b650b8, mServedView=org.apache.cordova.engine.SystemWebView{41b2b090 VFEDH.C. .F....I. 0,0-720,1134 #64}
,W/AwContents( 3037): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  904): Enable input method client, pid=3037
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  904): releaseWL(427cdb80): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/YouTube ( 3013): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/MediaRouterService(  904): Client com.google.android.youtube (pid 3013): Registered
,I/MediaRouter( 3013): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/YouTube ( 3013): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
,I/GoogleConversionPing( 3013): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=-Zm9l0GJkxYlG4JM5Qtk9A&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1457094146&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.google.android.youtube (3013/10168)
,D/libc    ( 3013): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
,D/libc    ( 3013): [NET] getaddrinfo-,err=8
D/libc    ( 3013): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3013): [NET] getaddrinfo-, 1
,D/libc    ( 3013): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    ( 3013): [NET] getaddrinfo_proxy-
,E/GoogleConversionPing( 3013): Error sending ping
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3013): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
,D/YouTube ( 3013): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 3013): getSelectedRoute
D/YouTube ( 3013): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.youtube (3013/10168)
W/BroadcastQueue(  904): Permission Denial: receiving Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 (has extras) } to pl.k2.droidoaudioteka/.ford.AppLinkReceiver requires android.permission.RECEIVE_BOOT_COMPLETED due to sender null (uid 1000)
,D/AutoSetting( 1377): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2955): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2955): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2955): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2955): Cust_ConnectToPC   : spcsc>false
D/        ( 2955): Cust_ConnectToPC   : IPT>true
D/        ( 2955): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2955): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2955): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2955): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false,
,D/SmartNS_NSReceiver( 2955): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1377): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 2955): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 2955): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2955): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  904): Delay finish: com.android.settings/.PSReceiver
W/Settings( 2955): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/YouTube ( 3013): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
,I/SmartNS_PSService( 2955):  defaultType:0
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3108 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/YouTube ( 3013): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/Process (  904): killProcessQuiet, pid=2754
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2754:com.htc.mobiledata/u0a91 (adj 15): empty #17
,D/YouTube ( 3013): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
,D/YouTube ( 3013): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/ActivityManager(  904): Recipient 2754
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/AndroidProtocolHandler( 3037): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/chromium( 3037): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,D/JsMessageQueue( 3037): Set native->JS mode to OnlineEventsBridgeMode
,D/browser ( 3108): Browser versionCode = 760001523 versionName = 7.0.2512153020
,D/jxcore_app_log( 3037): JniHelper::setJavaVM(0x415f8048), pthread_self() = 1658462072
,W/SWE_UI  ( 3108): SWE using SurfaceView - Multi-Process
I/LibraryLoader( 3108): Loading: swewebviewchromium
,I/LibraryLoader( 3108): Time to load native libraries: 35 ms (timestamps 6345-6380)
,I/LibraryLoader( 3108): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3108): Initializing chromium process, renderers=9
I/LibraryLoader( 3108): Expected native library version number "",actual native library version number ""
,I/chromium( 3108): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/jxcore-log( 3037): Initializing JXcore engine
,W/jxcore-log( 3037): JXcore engine is ready
,W/jxcore-log( 3037): Starting JXcore engine
,W/jxcore-log( 3037): Platform android
W/jxcore-log( 3037): 
,W/jxcore-log( 3037): Process ARCH arm
W/jxcore-log( 3037): 
,I/jxcore-log( 3037): JXcore Cordova bridge is ready!
I/jxcore-log( 3037): 
,W/jxcore-log( 3037): JXcore engine is started
,W/chromium( 3108): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,E/jxcore  ( 3037): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3037): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/Adreno-EGL( 3108): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3108): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3108): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3108): Local Branch: 
I/Adreno-EGL( 3108): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3108): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3108):                  aa63bbd948f41d15fc72f585e
,D/Process (  904): killProcessQuiet, pid=2798
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,V/IccIntentReceiver( 1274): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
,I/ActivityManager(  904): Killing 2798:com.google.android.gm/u0a107 (adj 15): empty #17
I/SIMStateChangeReceiver( 1494): SIM state: ABSENT
I/SIMStateChangeReceiver( 1494): phoneType = 0
I/SIMStateChangeReceiver( 1494): remove notification
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 2798
,I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3151 uid=10031 gids={50031, 3003, 5012}
,I/SensorManager(  904): mEventCount = 300
,I/ActivityManager(  904): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3164 uid=10041 gids={50041, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  904): killProcessQuiet, pid=2181
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 2181:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2181
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2556): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2556): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2556): onReceive()
D/ExchangePolicystatus( 2556): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2556): onReceive(): else
,D/Process (  904): killProcessQuiet, pid=2835
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1220): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  904): Killing 2835:com.htc.backup/1000 (adj 15): empty #17
,W/WeatherUtility( 1108): can't get weather sync account
,I/ActivityManager(  904): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3181 uid=10038 gids={50038}
,W/WeatherRequest( 1108): request cur loc, but there is no sys cur
,W/AccTypeManager( 3164): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3164): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,D/AccTypeManager( 3164): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3198 uid=10077 gids={50077}
,D/Process (  904): killProcessQuiet, pid=2781
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 2781:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 2835
,D/SMSBackup( 3198): Got a database change event
,E/ExternalAccountType( 3164): Unsupported attribute readOnly
,I/ActivityManager(  904): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3210 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/Process (  904): killProcessQuiet, pid=2858
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 2858:com.google.android.talk/u0a111 (adj 15): empty #17
,W/AccTypeManager( 3164): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3164): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/AccTypeManager( 3164): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 3164): Unsupported attribute readOnly
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2781
,D/CalendarApplication( 3210): onCreate
D/ProviderChangeReceiver( 3210): ---------------------------------------------------
,D/ProviderChangeReceiver( 3210): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3210): start to updateAlertNotification!
,D/GCM     ( 1344): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ContextImpl( 2930): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/AlertService( 3210): No fired or scheduled alerts
,D/HtcAlertUtils( 3210): -- cancelReminderNotification --
,D/HtcAlertUtils( 3210): broadcastExistReminder!
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=2884
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 2884:com.htc.backupreset/1000 (adj 15): empty #17
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2858
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 2884
,I/ActivityManager(  904): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3227 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
,W/WeatherUtility( 3227): can't get weather sync account
I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3243 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 3227): request cur loc, but there is no sys cur
,W/Settings( 3227): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DemoRecovery.RestoreReceiver( 3243): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3243): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RestoreService( 3243): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  904): Resuming delayed broadcast
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 7 17
,I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3257 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=2901
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Killing 2901:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 2901
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(41e76640): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3257 10070 null
,D/PMS     (  904): acquireWL(41c0a038): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3257 10070 null
D/PMS     (  904): releaseWL(41e76640): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3257): update TASK shortcut>
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
,I/TodoTaskNotifyService( 3257): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): releaseWL(41c0a038): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3272 uid=10081 gids={50081, 3003, 5012}
,D/Process (  904): killProcessQuiet, pid=2916
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/NotifyReceiver( 3257): stopSelfResult true
I/ActivityManager(  904): Killing 2916:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 2916
,I/ActivityManager(  904): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3284 uid=10081 gids={50081, 3003, 5012}
,D/Process (  904): killProcessQuiet, pid=2766
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Process (  904): killProcessQuiet, pid=2943
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
I/ActivityManager(  904): Killing 2766:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  904): Killing 2943:com.htc.providers.settings:remote/u0a17 (adj 15): empty #18
D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
,D/SMSBackup( 3198): Got a database change event
I/ActivityManager(  904): Recipient 2943
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Recipient 2766
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3296 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,I/ImageRamCache( 3296): create image Cache, size: 31457280.
I/ImageRamCache( 3296): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3296): create image Cache, size: 12582912.
,I/FeedSettings( 3296): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3296): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3296): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3296): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3296): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3296): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3296): [custom highlight] onReceive
,D/CustomHighlightService( 3296): [custom highlight] onHandleIntent
,D/NewsDB  ( 3296): set custom highlight []
I/ActivityManager(  904): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3296): [custom highlight] set tags 
,D/MessagingShortcutReceiver( 2556): keep hiding shortcut bubble
D/MessagingShortcut( 2556): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2556): After query: 0
D/MessagingShortcut( 2556): mPresentUnreadCount: -1
,D/MessagingShortcut( 2556): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2556): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1538): [EventService] reorderNotification, total:0
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3257): update TASK shortcut>
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1220): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
D/Process (  904): killProcessQuiet, pid=2979
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 2979:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 2979
,I/ActivityManager(  904): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3312 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  904): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  904): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3326 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3312): [8a8.1.] 40@-132225
,D/Process (  904): killProcessQuiet, pid=2994
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/GCM     ( 1344): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Process (  904): killProcessQuiet, pid=3013
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 2994:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  904): Killing 3013:com.google.android.youtube/u0a168 (adj 15): empty #17
D/MessagingNotification( 2556): New incoming message, can't cancel notification now
,D/MessagingNotification( 2556): newMsgCnt: 0, false
I/ActivityManager(  904): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Recipient 2994
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=3339 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/Babel   ( 3339): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3339): MmsConfig.loadMmsSettings
,E/dalvikvm( 3339): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3339): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
E/dalvikvm( 3339): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3339): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3339): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 2556): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 2556): query uri: content://htc-mms-customization/mms-ua/ua_profile
I/Babel   ( 3339): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3339): MmsConfig.loadFromDatabase
E/Babel   ( 3339): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3339): MmsConfig.loadFromResources
,E/Babel   ( 3339): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3339): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/ActivityManager(  904): Recipient 3013
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  904): Client com.google.android.youtube (pid 3013): Died!
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3339, uid=10111, userID:0
,W/CpuWake (  904): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  904): <<nativeReleaseCpuPerfWakeLock()
,W/Settings( 3339): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/CpuWake (  904): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  904): >>release mCpuPerf_Freq wakelock
W/CpuWake (  904): <<release mCpuPerf_Freq wakelock
D/PMS     (  904): releaseHCC(425a18b8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  904): releaseHCC(427b04f8): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3339, uid=10111, userID:0
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3339, uid=10111, userID:0
,D/Process (  904): killProcessQuiet, pid=2955
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/GCM     ( 1344): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  904): Killing 2955:com.android.settings/1000 (adj 15): empty #17
,D/ConnectivityService(  904): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1745/10178)
D/MtpReceiver( 2235): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2235): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2235): [MTP][handleMessage][startService]
D/MtpReceiver( 2235): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2235): [MTP][handleMessage]-
,D/MtpService( 2235): [MTP] startForeground
,I/RemoteViews( 1108): com.android.providers.media (false,0)
,I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3365 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
I/RemoteViews.Performance( 1108): com.android.providers.media 2 1 10
I/RemoteViews( 1108): com.android.providers.media (false,0)
D/MtpService( 2235): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2235): TotalSize=1918604,MediaCacheLimit=6000
I/RemoteViews.Performance( 1108): com.android.providers.media 1 1 15
D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/MtpService( 2235): [isMtpConnected] connected: true
I/ProviderInstaller( 3339): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  904): Recipient 2955
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 3365): Loading default preferences
,W/Resources( 3365): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  904): New client listening to asynchronous messages
,D/SyncApplication( 3365): Overriding preferences with custom values
,D/SyncApplication( 3365): Updating preferences succeeded
,E/SyncApplication( 3365): Application created.
,D/VolumeInfo( 3365): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3365): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3365): Found 0 mount point(s)
,V/VolumeInfo( 3365): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3365): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3365): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3365): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3365): getNewCalendarAuthority()...
,D/SyncApplication( 3365): enableAppOperation()+
,D/SyncApplication( 3365): enableAppOperation()-
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3365, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3365, uid=10008, userID:0
,W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3365): isNeorSinged() + 
,D/HTCUtilities( 3365): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3365): isNeorSinged() return false
,D/CDMountReceiver( 3365): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3365): USB connected to PC
,D/FOTAReceiver( 3365): onReceive() enter 
,D/FOTAReceiver( 3365): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  904): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3384 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  904): killProcessQuiet, pid=3108
,I/ActivityManager(  904): Killing 3108:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  904): Recipient 3108
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=3151
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  904): Killing 3151:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3151
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3384): -onCreate()
,V/Settings:HtcSettingsApplication( 3384): [3384/3384] onCreate()
,D/TetherSettings( 3384): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3384): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3384): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3384): Cust_ConnectToPC   : spcsc>false
D/        ( 3384): Cust_ConnectToPC   : IPT>true
,D/        ( 3384): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3384): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3384): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3384): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3384): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3384): Cust_ConnectToPC   : spcsc>false
D/        ( 3384): Cust_ConnectToPC   : IPT>true
D/        ( 3384): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3384): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3384): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3384): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3384): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
D/SmartNS_Utility( 3384): usb_cable_connect = 1
,D/SmartNS_Utility( 3384): usb_denied = 0
I/SmartNS_NSReceiver( 3384): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3384): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3384): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3384): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3384): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3384):  defaultType:0
I/SmartNS_PSService( 3384): fail notificaiton:false
D/SmartNS_Utility( 3384): usb_cable_connect = 1
D/SmartNS_Utility( 3384): usb_denied = 0
I/SmartNS_PSService( 3384): usb notificaiton:true
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3384/1000)
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  904): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3384): usb_cable_connect = 1
D/SmartNS_Utility( 3384): usb_denied = 0
,I/SmartNS_PSService( 3384): usb notificaiton:true
,V/Tethering(  904): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/RemoteViews( 1108): com.android.settings (true,33751552)
D/Tethering(  904): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  904): bSetPropertyMultiRAB:false
,I/RemoteViews.Performance( 1108): com.android.settings 1 1 10
,D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/ConnectivityService(  904): getActiveNetworkInfo called by com.android.settings (3384/1000)
I/ActivityManager(  904): Resuming delayed broadcast
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
D/SmartNS_Utility( 3384): usb_cable_connect = 1
,D/SmartNS_Utility( 3384): usb_denied = 0
,D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/SmartNS_PSService( 3384): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3384): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  904): Resuming delayed broadcast
I/RemoteViews( 1108): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1108): com.android.settings 1 0 10
W/WeatherUtility( 3227): can't get weather sync account
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1247): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1247): com.google.android.googlequicksearchbox 1 0 5
,I/ActivityManager(  904): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,I/ActivityManager(  904): Resuming delayed broadcast
D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/RemoteViews( 1247): pl.k2.droidoaudioteka (false,0)
I/RemoteViews.Performance( 1247): pl.k2.droidoaudioteka 1 0 8
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  904): getAllProviders()=[passive, gps, network]
W/WeatherRequest( 3227): request cur loc, but there is no sys cur
,W/Settings( 3227): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 9 17
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,V/AlarmManager(  904): sending alarm PendingIntent{4255a948: PendingIntentRecord{42806968 com.google.android.gms startService}}, i=null, t=0, cnt=17158, w=84918423, Int=84918423
,I/ActivityManager(  904): Resuming delayed broadcast
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,I/AdsMeasurementBroadcastReceiver( 1199): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1199): Unauthorized to start the main service
,D/SnetService( 1199): snet destroyed
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  904): acquireWL(42881da8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,I/PeopleContactsSync( 1199): CP2 sync disabled
,D/PMS     (  904): releaseWL(42881da8): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
,D/PMS     (  904): releaseWL(427eea00): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SocialFeedProvider( 1247): +disConnect socialManager
,I/SocialFeedProvider( 1247): disconnect socialManager
,I/SocialFeedProvider( 1247): -disConnect socialManager
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3421 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3164
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3164:com.htc.contacts/u0a41 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1377): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1377): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3437 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3437, uid=10073, userID:0
,I/ActivityManager(  904): Recipient 3164
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Finsky  ( 3437): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3437/10073)
,D/ConnectivityService(  904): getAllNetworkInfo called by com.android.vending (3437/10073)
,D/Finsky  ( 3437): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,D/Process (  904): killProcessQuiet, pid=3210
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3210:com.htc.calendar/u0a13 (adj 15): empty #17
,W/Settings( 3437): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3437): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  904): Recipient 3210
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3437, uid=10073, userID:0
,D/Process (  904): killProcessQuiet, pid=2930
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Finsky  ( 3437): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3437): [1] 2.run: Finished loading 1 libraries.
,I/ActivityManager(  904): Killing 2930:com.android.settings:remote/1000 (adj 15): empty #17
,D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  904): Recipient 2930
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2671): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3470 uid=10098 gids={50098, 3003, 5012}
,D/Finsky  ( 3437): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  904): Delaying start of: ServiceRecord{425e6d78 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
D/PMS     (  904): acquireWL(42592948): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(42592948): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/Finsky  ( 3437): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/PMS     (  904): acquireWL(42369828): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,I/DeviceManagement( 3470): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3470 dbg=false s=true
,I/DeviceManagement( 3470): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  904): killProcessQuiet, pid=3243
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
I/ActivityManager(  904): Killing 3243:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3243
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): releaseWL(42369828): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3487 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/PMS     (  904): acquireWL(420fc5a0): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(420fc5a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(4231a390): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(4231a390): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42079760): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(42079760): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(423da340): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(423da340): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(4204fbb8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(4204fbb8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(4244a578): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(4244a578): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(420cfbb0): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(420cfbb0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(41c3b6a8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(41c3b6a8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(423225f8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(423225f8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(41fd0928): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(41fd0928): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2671): Copying FileAsset 0x5c7ad4c8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/IcingCorporaProvider( 2671): UpdateCorporaTask done [took 466 ms] updated apps [took 466 ms] 
,W/GAV2    ( 3487): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  904): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3507 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/htcbackup-core( 3507): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 3507): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3507): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 3470): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 3470): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.autobot.cargps.provider, com.android.location.fused, com.android.inputdevices, android, com.htc.guide, com.htc.drive.activator, com.qualcomm.timeservice, com.htc.android.htcsetupwizard, com.htc.htcpowermanager, com.htc.home.personalize, com.htc.backupreset, com.qualcomm.privinit, com.htc.checkinprovider, com.android.keychain, com.htc.smartdim, com.htc.mirrorlinkserver, com.htc.cirmodule, com.android.providers.settings, com.htc.usage, com.android.settings, com.htc.lockscreen, com.htc.android.htcloglevel, com.htc.feedback, com.android.CSDFunctionG, com.htc.backup]
,I/DeviceManagement( 3470): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/ActivityManager(  904): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3524 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  904): killProcessQuiet, pid=3272
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  904): Killing 3272:com.htc.stock/u0a81 (adj 15): empty #17
I/DeviceManagement( 3470): WorkflowService: Starting workflow service
I/DeviceManagement( 3470): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b5e570] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3470): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3470): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  904): Recipient 3272
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GAV2    ( 3487): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,I/DeviceManagement( 3470): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3470): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3524):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  904): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3539 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3284
,I/ActivityManager(  904): Killing 3284:com.htc.stock:remote/u0a81 (adj 15): empty #17
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
V/AlarmManager(  904): sending alarm PendingIntent{421e8bb8: PendingIntentRecord{423ba3e8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1457094148971, Int=0
V/AlarmManager(  904): sending alarm PendingIntent{42393048: PendingIntentRecord{427c6480 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457094150357, Int=0
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SocialManager[SocialBiLogHelper]( 3296): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3296): last commit ulog time 1457021779330
,I/SocialManager[SocialBiLogHelper]( 3296): skip commit this time
I/ActivityManager(  904): Recipient 3284
,W/GLSUser ( 1344): GoogleAccountDataService.getToken()
,I/GoogleHttpClient( 1344): Falling back to old SSLCertificateSocketFactory
,I/GoogleHttpClient( 1344): Using GMS GoogleHttpClient
,I/DeviceManagement( 3470): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1344): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/GLSUser ( 1344): GoogleAccountDataService.getToken()
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1344): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 6 times.
I/NotificationStore( 1344): System rebooted after Notification storage file was last written
,I/NotificationStore( 1344): Deleting the file
,D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1538): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/DeviceManagement( 3470): SessionStateController: Checking invariants...
,W/GLSActivity( 1344): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1344): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1344): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1344): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1344): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1344): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1344): 	at android.os.Binder.execTransact(Binder.java:412)
W/GLSActivity( 1344): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/RemoteViews( 1108): com.google.android.gms (false,0)
,E/PlayEventLogger( 3437): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3437): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3437): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3437): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3437): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3437): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3437): 	at android.os.Binder.execTransact(Binder.java:412)
E/PlayEventLogger( 3437): 	at dalvik.system.NativeStart.run(Native Method)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41eafca0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/PMS     (  904): acquireWL(4285fef8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3539 10160 null
,I/RemoteViews.Performance( 1108): com.google.android.gms 2 9 5 12
D/PMS     (  904): releaseWL(4285fef8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
,W/GLSUser ( 1344): GoogleAccountDataService.getToken()
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1344): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,D/libc    ( 3437): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 3437): [NET] getaddrinfo-,err=8
D/libc    ( 3437): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3437): [NET] getaddrinfo-, 1
D/libc    ( 3437): [NET] getaddrinfo_proxy+
,D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    ( 3437): [NET] getaddrinfo_proxy-
,E/PlayEventLogger( 3437): Upload failed class java.net.UnknownHostException(Unable to resolve host "play.googleapis.com": No address associated with hostname)
,D/PMS     (  904): acquireWL(4286f900): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3539 10160 null
W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/DeviceManagement( 3470): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/ActivityManager(  904): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,I/DeviceManagement( 3470): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b5e570]
,I/DeviceManagement( 3470): WorkflowService: Stopping workflow service
,W/Finsky  ( 3437): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): acquireWL(426f67a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3539 10160 null
D/PMS     (  904): releaseWL(4286f900): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3571 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Finsky  ( 3437): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3539/10160)
D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.apps.plus (3539/10160)
,D/Settings:HtcWirelessFeatureFlags( 3384): id/is att sku: 99/false
,W/SystemReader( 3384): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3384): Cannot find support_harman, use default value instead
,W/SystemReader( 3384): Cannot find effect_manager_id, use default value instead
,W/ContextImpl( 3571): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3571): call getInstance()
I/ActivityManager(  904): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,E/Settings:HtcWrapHeaderInfo( 3384): no such activity!
,D/PowerUsageList:PowerUsageHelper( 3571): MY_DEBUG = false
,D/Process (  904): killProcessQuiet, pid=3181
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  904): releaseWL(426f67a8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3181:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3181,
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3384): The wrap header doesn't exist in header list.
,D/PMS     (  904): acquireWL(425c0a08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3571 1000 null
,E/Settings:HtcWrapHeaderInfo( 3384): updateDevelopment, bPrefShow = true
W/BatSI   (  904): Couldn't get kernel wake lock stats
,D/WeatherUtility( 1377): Weather sync is On
,D/WSP     ( 1377): [Receiver] auto sync agent, auto sync is enabled, reset schedule
I/ActivityManager(  904): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/WeatherUtility( 3227): can't get weather sync account
,W/WeatherUtility( 1108): can't get weather sync account
,E/Settings:HtcUmcWidgetEnabler( 3384): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]support         :false
I/ActivityManager(  904): Waited long enough for: ServiceRecord{42878d48 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3593 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/FingerprintManager( 3384): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
,E/Settings:HtcVoWifiWidgetEnabler( 3384): isSupportVoWifi: null
,W/WeatherRequest( 3227): request cur loc, but there is no sys cur
,W/Settings( 3227): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ActivityThread( 3384): Failed to find provider info for com.htc.vowifi
,D/AppWidgetHostView( 1247): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1247): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1247): com.htc.widget.weatherclock 1 9 17
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/BatSI   (  904): Couldn't get kernel wake lock stats
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3384): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3384): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3384): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportRecentAppsButton]support         :false
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3384): [supportHomeButton]support         :false
W/FingerprintManager( 3384): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3384): isSupportVoWifi: null
I/ActivityManager(  904): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3384): Failed to find provider info for com.htc.vowifi
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3610 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,W/GLSUser ( 1344): GoogleAccountDataService.getToken()
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1344): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1344): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3437): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3437): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3437): [1] DailyHygiene.reschedule: Scheduling new run in 9 minutes (failures=1)
,I/MusicStore( 3610): Database version: 95
,D/Process (  904): killProcessQuiet, pid=3198
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/ContextImpl( 3610): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/ActivityManager(  904): Killing 3198:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3198
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3610): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3610): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3610): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3610): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3610, uid=10154, userID:0
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
,D/MediaRouterService(  904): Client com.google.android.music (pid 3610): Registered
,D/WifiDisplayAdapter(  904): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  904):     Client/Owner: Client
D/WifiDisplayAdapter(  904):     GroupId: 
D/WifiDisplayAdapter(  904):     Passphrase: 
D/WifiDisplayAdapter(  904):     SessionId: 0
D/WifiDisplayAdapter(  904):     IP Address: }
I/MediaRouter( 3610): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.music (3610/10154)
,D/MediaRouter( 3610): getSelectedRoute
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3610, uid=10154, userID:0
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3631 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3257
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3257:com.htc.task/u0a70 (adj 15): empty #17
,D/DFPI.PIReciver( 3631): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3631): onHandleIntent
,I/DFPI.ApkInstallService( 3631): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3631): check CID = HTC__032
,I/DFPI.ApkInstallService( 3631): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3312
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3312:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3312
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3645 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3257
,I/ActivityManager(  904): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.musicenhancer (3645/10051)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3645): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,V/AlarmManager(  904): sending alarm PendingIntent{41dc7dd0: PendingIntentRecord{41fdcb60 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1457094152139, Int=0
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3663 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  904): killProcessQuiet, pid=3326
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3326:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3326
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3663): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3663): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3663): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3663): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3663): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/Process (  904): killProcessQuiet, pid=3339
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3339:com.google.android.talk/u0a111 (adj 15): empty #17
,D/DFPI.PIReciver( 3631): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3631): onHandleIntent
,I/DFPI.ApkInstallService( 3631): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3631): check CID = HTC__032
,I/DFPI.ApkInstallService( 3631): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3663): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] startService
,I/SoundPicker( 3663): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3663): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3663): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3663): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.fla,c
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/ActivityManager(  904): Recipient 3339
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  904): Resuming delayed broadcast
,D/DFPI.PIReciver( 3631): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3631): onHandleIntent
,I/DFPI.ApkInstallService( 3631): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3631): check CID = HTC__032
,I/DFPI.ApkInstallService( 3631): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3663): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3663): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3663): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3663): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3663): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3610): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.htc.task for broadcast com.htc.task/.TodoTaskReceiver: pid=3685 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,I/ActivityManager(  904): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  904): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3698 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3631): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  904): Resuming delayed broadcast
I/DFPI.ApkInstallService( 3631): onHandleIntent
,I/DFPI.ApkInstallService( 3631): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3631): check CID = HTC__032
,I/DFPI.ApkInstallService( 3631): There is no Demo.apk in sd card or phone storage
,D/Process (  904): killProcessQuiet, pid=2556
I/ActivityManager(  904): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Killing 2556:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3663): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3663): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3663): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3663): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3663): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3663): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3663): MODE_GSM access default DB
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  904): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3663): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/EASAppSvc( 3698): [ NA ]- onCreate()
,I/EASAppSvc( 3698): [ NA ]> onUpgrade: version = 63
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,D/ORMLib  ( 3685): put()
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3663): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3663): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
D/WifiService(  904): New client listening to asynchronous messages
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3663): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/EASAppSvc( 3698): [ NA ]- onDestroy()
,I/EASAppSvc( 3698): [ NA ]> uninitEASService
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.android.mail (3698/10063)
I/ActivityManager(  904): Recipient 2556
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  904): releaseWL(425c0a08): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.android.mail (3698/10063)
I/ActivityManager(  904): Resuming delayed broadcast
D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.android.mail (3698/10063)
,I/ActivityManager(  904): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3610): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  904): Resuming delayed broadcast
D/TelephonyReceiver( 1220): bind: true
,D/PMS     (  904): acquireWL(4252ae88): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1494 10014 null
,I/ActivityManager(  904): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=3723 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,I/ActivityManager(  904): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  904): releaseWL(4252ae88): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/MessageFrequencyProvider( 3723): onCreate
,V/GetPrviateResource( 3723): GetPrviateResource
V/GetPrviateResource( 3723): GetPrviateResource
,D/GenericMessagesProvider( 3723): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 3723): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 3723): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3723): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 3723): DB info: errno = 2, errno message = No such file or directory
,I/ActivityManager(  904): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3738 uid=10084 gids={50084, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
E/SQLiteDatabase( 3723): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3723): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3723): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3723): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3723): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3723): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3723): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3723): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3723): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3723): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3723): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3723): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 3723): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3723): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3723): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3723): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3723): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3723): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3723): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3723): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3723): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3723): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3723): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 3723): 	at dalvik.system.NativeStart.run(Native Method)
,D/Process (  904): killProcessQuiet, pid=3365
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/ActivityManager(  904): Killing 3365:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/Process (  904): killProcessQuiet, pid=3421
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/TelephonyReceiver( 1220): bind: false
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
I/ActivityManager(  904): Killing 3421:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3421
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3751 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/MessageCustFlag( 3723): sense_version=6.0
,D/BTAccessoryUtil( 3723): createReceiver
,D/BTAccessoryUtil( 3723): registerReceiver return intent = null
D/MessageCustFlag( 3723): sku_id=99
,W/SystemReader( 3723): Cannot find message_ambs_application_id, use default value instead
,I/EASRequestController( 3698): [ NA ]release
,D/Messaging( 3723): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3723): networkCode: 
D/MessageCustFlag( 3723): sku_id=99
,D/MmsConfig( 3723): SIE smsPri: null
,D/MmsConfig( 3723): networkCode: 
,I/EASAppSvc( 3698): [ NA ]< uninitEASService
,I/EASAppSvc( 3698): [ NA ]- onCreate()
,I/EASAppSvc( 3698): [ NA ]> onUpgrade: version = 63
D/HtcTelephonyCapability( 3723): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 3723): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3723): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3723): Cannot find qct_8960_interface, use default value instead
D/ConnectivityService(  904): getNetworkInfo networkType=1 called by com.htc.android.mail (3698/10063)
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
D/ConnectivityService(  904): getNetworkInfo networkType=0 called by com.htc.android.mail (3698/10063)
D/ConnectivityService(  904): getNetworkInfo networkType=55 called by com.htc.android.mail (3698/10063)
,D/ORMLib  ( 3685): put()
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  904): Client connection lost with reason: 4
I/ActivityManager(  904): Recipient 3365
,I/EASAppSvc( 3698): [ NA ]- onDestroy()
,I/EASAppSvc( 3698): [ NA ]> uninitEASService
,I/EASRequestController( 3698): [ NA ]release
,I/EASAppSvc( 3698): [ NA ]< uninitEASService
I/ActivityManager(  904): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3777 uid=10067 gids={50067, 3003, 5012}
,W/GAV2    ( 3751): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  904): acquireWL(41c200b0): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/Process (  904): killProcessQuiet, pid=3487
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3487:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3487
,D/ORMLib  ( 3685): put()
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  904): killProcessQuiet, pid=3507
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3507:com.htc.backup/1000 (adj 15): empty #17
D/PMS     (  904): releaseWL(41c200b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Recipient 3507
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(42452d40): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(42452d40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1108): com.htc.updater (true,33751552)
D/NotificationService(  904): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41b2fd98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.htc.updater 2 6 1 10
,I/RemoteViews( 1108): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41ed0a98 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1108): com.htc.updater 1 6 1 10
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.google.android.gm/.GmailReceiver
,I/Gmail   ( 3751): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3751): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3751): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3751): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.GmailReceiver
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.gm/.GmailReceiver
,I/NotifUtils( 3751): Validating Notification, mapSize: 0 getAttention: true ignoreUnobtrusive: false
,I/NotifUtils( 3751): validateNotifications - cancelling account 61035162 / folder -317575340
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3822 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  904): killProcessQuiet, pid=3470
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3470:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3470
,I/Babel   ( 3822): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3822): MmsConfig.loadMmsSettings
,E/dalvikvm( 3822): dlopen("/data/app-lib/GmsCore/libgmscore.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libgmscore.so" not found
,E/ProviderInstaller( 3822): Unable to load native code from /data/app-lib/GmsCore/libgmscore.so
,E/dalvikvm( 3822): dlopen("/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so") failed: dlopen failed: library "/data/app-lib/GmsCore/libconscrypt_gmscore_jni.so" not found
,E/ProviderInstaller( 3822): Unable to load native code from /data/app-lib/GmsCore/libconscrypt_gmscore_jni.so
,V/JNIHelp ( 3822): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 234 native methods...
,D/MmsCustomizationProvider( 3723): query uri: content://htc-mms-customization/mms-ua/ua_string
,D/MmsCustomizationProvider( 3723): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 3822): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 3822): MmsConfig.loadFromDatabase
,E/Babel   ( 3822): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3822): MmsConfig.loadFromResources
,E/Babel   ( 3822): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3822): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3822, uid=10111, userID:0
,W/Settings( 3822): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3822, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3822, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3822, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3822, uid=10111, userID:0
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3822, uid=10111, userID:0
,D/PMS     (  904): acquireWL(42868a18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3822 10111 null
,I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 3822): Installed default security provider GmsCore_OpenSSL
,D/PMS     (  904): releaseWL(42868a18): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(427d1d60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3822 10111 null
,I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/SensorManager(  904): mEventCount = 450
,D/PMS     (  904): releaseWL(427d1d60): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(4278f4f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 904 1000 null
,D/Process (  904): killProcessQuiet, pid=3524
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3524:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/PMS     (  904): releaseWL(4278f4f0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ActivityManager(  904): Recipient 3524
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  904): acquireWL(425d97a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3822 10111 null
,I/ActivityManager(  904): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  904): releaseWL(425d97a8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3822/10111)
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3822/10111)
,D/PMS     (  904): acquireWL(425cc220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(425cc220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
,D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3822/10111)
,D/Messaging( 3723): mNeedToUpdateDate2 start
,D/MmsConfig( 3723): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 3723): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3723): 
D/MmsAsyncWorkHandler( 3723): HM tk = 20001
,D/ReportIndicatorCache( 3723): MSG_QUERY_REPORTS >>
,D/SettingsManager( 3723): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b274f8
,I/Messaging( 3723): mccmnc> 
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/DraftCache( 3723): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3723): [DraftCache/1] refresh
D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/MmsConfig( 3723): networkCode: 
,D/Messaging( 3723): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1220): sku_id=99
D/PhoneStorageUtil( 3723): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3723): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3723): createReceiver
,D/MessageCustFlag( 3723): sense_version=6.0
,D/Jerry   ( 3723): start to preload cursor >>>>>>>
,D/DraftCache( 3723): [DraftCache/379] rebuildCache
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1220): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
V/MmsProvider( 1220): Update uri=content://mms, match=0
,V/MmsProvider( 1220): selection=st=129 AND m_type!=134
,D/Messaging( 3723): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3723): TransactionService is going to be woken up.
,D/Messaging( 3723): mNeedToUpdateDate2: false
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 70
D/MmsSmsV2Provider( 1220):  phoneType = -1
,D/MmsSmsV2Provider( 1220): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 3723): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/MmsSmsV2Provider( 1220):  phoneType = -1
I/ActivityManager(  904): Delaying start of: ServiceRecord{425ea6d0 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/Messaging( 3723): ViewCache CreatePreload
,D/Messaging( 3723): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 69
,D/Jerry   ( 1220): URI_DRAFT
,D/Cust_MMSMS( 3723): _has_set_default_values_2=true
,D/DraftCache( 3723): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3723): [DraftCache/379] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 3723): 
D/MmsAsyncWorkHandler( 3723): HM tk = 20002
,D/MsgPreferenceUtils( 3723): def_index: 0
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1220): sku_id=99
,D/MsgPreferenceUtils( 3723): globalIndex = 1
D/MsgPreferenceUtils( 3723): phone state: true
D/MsgPreferenceUtils( 3723): sd state: false
,D/MsgPreferenceUtils( 3723): vIndex = 0
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1220): sku_id=99
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 7 times.
,V/AlarmManager(  904): sending alarm PendingIntent{425332b8: PendingIntentRecord{4246e550 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1457094155979, Int=0
,D/AutoSetting( 1377): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1377): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1377): service - requestNLP() NetworkLocationProvider not enabled
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3822/10111)
,V/TransactionService( 3723): 1-Creating TransactionService
,V/TransactionService( 3723): onStartCommand: 1
,D/MmsSystemEventReceiver( 3723): unRegisterForConnectionStateChanges
V/TransactionService( 3723): 4-Handling incoming message: { when=-2ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 3723): Loading previous transactions.
,D/TelephUtils( 1220): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 70
,D/AccFlag ( 1220): device_type: 1
,D/TransactionService( 3723): Force set service start id to 1
,V/TransactionService( 3723): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3723): unRegisterForConnectionStateChanges
V/TransactionService( 3723): Destroying TransactionService
,D/TransactionService( 3723): stopSelfResult: true, mLastHandledServiceId: 1
I/ActivityManager(  904): Resuming delayed broadcast
D/ConnectivityService(  904): Sampling interval elapsed, updating statistics ..
,V/TransactionService( 3723): 4-Handling incoming message: { when=-6ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/ConnectivityService(  904): Done.
I/ActivityManager(  904): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
D/ConnectivityService(  904): Setting timer for 720seconds
,I/PeopleContactsSync( 1199): CP2 sync disabled
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
D/PMS     (  904): acquireWL(42361f08): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
D/PMS     (  904): releaseWL(42361f08): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/[PluginManager]RegisterService( 1377): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1377): handle notify Blinkfeed plugin client changed
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/IcingCorporaProvider( 2671): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,I/IcingCorporaProvider( 2671): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  904): acquireWL(421c8118): PARTIAL_WAKE_LOCK  AsyncService 0x1 3539 10160 null
,D/PMS     (  904): releaseWL(421c8118): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  904): Resuming delayed broadcast
,D/PMS     (  904): acquireWL(42728880): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3685 10070 null
,D/PMS     (  904): acquireWL(4207a6c8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3685 10070 null
,D/PMS     (  904): releaseWL(42728880): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,E/TodoTaskNotifyService( 3685): java.lang.NullPointerException
W/System.err( 3685): java.lang.NullPointerException
,W/System.err( 3685): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3685): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3685): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3685): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3685): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3685): stopSelfResult true
I/ActivityManager(  904): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
D/PMS     (  904): releaseWL(4207a6c8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  904): Resuming delayed broadcast
,I/WSP     ( 1377): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1377): Weather sync is On
,I/WSP     ( 1377): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Mar 04 14:22:37 CET 2016
,W/WSP     ( 1377): [Receiver] can't get active network info
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1377/10053)
I/ActivityManager(  904): Delay finish: com.google.android.gm/.MailIntentReceiver
,V/WSP     ( 1377): [SyncService] no data connection, stop sync service
D/ConnectivityService(  904): getActiveNetworkInfo called by com.htc.sense.hsp (1377/10053)
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3685): update TASK shortcut>
,I/GAV2    ( 3751): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 3822): Thread[GAThread,5,main]: No campaign data found.
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 8 times.
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.talk (3822/10111)
,I/SensorManager(  904): mEventCount = 600
,I/CalendarProvider2( 1494): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1494): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3907 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3907): Loading default preferences
,W/Resources( 3907): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  904): New client listening to asynchronous messages
,D/SyncApplication( 3907): Overriding preferences with custom values
,D/SyncApplication( 3907): Updating preferences succeeded
,E/SyncApplication( 3907): Application created.
D/VolumeInfo( 3907): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3907): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3907): Found 0 mount point(s)
,V/VolumeInfo( 3907): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3907): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
D/VolumeInfo( 3907): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,I/CalendarDefines( 3907): getNewCalendarAuthority()...
,W/VolumeInfo( 3907): Can not create volume ID for unmounted volume null
,D/SyncApplication( 3907): enableAppOperation()+
,D/SyncApplication( 3907): enableAppOperation()-
,D/HTCUtilities( 3907): isNeorSinged() + 
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3907, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3907, uid=10008, userID:0
W/PackageManager(  904): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3907): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3907): isNeorSinged() return false
,D/CDMountReceiver( 3907): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3907): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1538): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/CDMountReceiver( 3907): enable CD Auto-mount: true
,D/HTCUtilities( 3907): enable auto-mount
,D/HTCUtilities( 3907): enable auto-mount
,I/ActivityManager(  904): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,I/RemoteViews( 1108): com.nero.android.htc.sync (false,0)
D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
I/ActivityManager(  904): Resuming delayed broadcast
D/PMS     (  904): releaseWL(42763c58): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41f1da58 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/MountService(  904): mountISO: /system/etc/PCTOOL.ISO
,I/RemoteViews.Performance( 1108): com.nero.android.htc.sync 2 14 4 11
,I/RemoteViews( 1108): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1108): release indeterminate drawable android.widget.OnDemandProgressBar{41f0b8d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/PMS     (  904): acquireWL(426f9908): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3610 10154 null
I/ActivityManager(  904): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/RemoteViews.Performance( 1108): com.nero.android.htc.sync 1 10 3 16
,W/ContextImpl( 3610): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3610): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3610, uid=10154, userID:0
,D/PMS     (  904): releaseWL(426f9908): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/MusicLeanback( 3610): Conditions not met for autocaching.
,I/MusicLeanback( 3610): Stop autocaching.
I/ActivityManager(  904): Resuming delayed broadcast
,I/ActivityManager(  904): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3593): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  904): Resuming delayed broadcast
,D/Process (  904): killProcessQuiet, pid=3296
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  904): Killing 3296:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3296
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3936 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/CalendarApplication( 3936): onCreate
D/ProviderChangeReceiver( 3936): ---------------------------------------------------
,D/ProviderChangeReceiver( 3936): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3936): start to updateAlertNotification!
,D/Process (  904): killProcessQuiet, pid=3571
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  904): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3950 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Killing 3571:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,D/AlertService( 3936): No fired or scheduled alerts
,D/HtcAlertUtils( 3936): -- cancelReminderNotification --
,D/HtcAlertUtils( 3936): broadcastExistReminder!
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  904): Recipient 3571
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Settings:HtcSettingsApplication( 3950): [3950/3950] onCreate()
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/Process (  904): killProcessQuiet, pid=3227
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Resuming delayed broadcast
I/ActivityManager(  904): Killing 3227:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Recipient 3227
,D/PMS     (  904): acquireWL(427dd0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false,
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(427dd0e0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 9 times.
,D/PMS     (  904): acquireWL(425f55a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10073}
,V/AlarmManager(  904): sending alarm PendingIntent{421fb438: PendingIntentRecord{42325da0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1457094165785, Int=0
,D/PMS     (  904): releaseWL(425f55a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10073}
,D/Finsky  ( 3437): [1] 5.onFinished: Installation state replication succeeded.
,D/Process (  904): killProcessQuiet, pid=3631
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3631:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3631
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{42752d08 u0 com.htc.musicenhancer/.EnhancerService}
,I/SensorManager(  904): mEventCount = 750
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 10 times.
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  365): [NET] getaddrinfo-,err=7,
,D/libc    (  904): [NET] getaddrinfo_proxy-
D/PMS     (  904): acquireWL(425a56d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{4222e610: PendingIntentRecord{42409a98 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=80728, Int=0
D/PMS     (  904): releaseWL(425a56d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 11 times.
,D/AutoSetting( 1377): service - handleMessage() stop self
,D/AutoSetting( 1377): service - handleMessage() quit looper
,D/AutoSetting( 1377): service - onDestroy() END
,D/Process (  904): killProcessQuiet, pid=3663
I/ActivityManager(  904): Killing 3663:com.htc.sdm/u0a80 (adj 15): empty #17
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3663
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  904): mEventCount = 900
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  904): acquireWL(41fe6898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41beaa98: PendingIntentRecord{41be40e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=87539, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,I/ClockThread( 1108): now=1457094180014 next=59986
,D/PMS     (  904): releaseWL(41fe6898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 12 times.
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  904): acquireWL(423e5d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): releaseWL(423e5d18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,I/HtcModeClient( 1494): handler message = 4011
,E/HtcModeClient( 1494): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1494): Don't start project servcice
,D/HtcModeClient( 1494): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1494): connectState: CONNECTION_READY = false
,D/SilentMusic( 1494): call stop
,D/HtcModeClient( 1494): close connection
,W/HtcModeClient( 1494): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1494): read the terminate packet, so break
,I/ActivityManager(  904): Killing 3698:com.htc.android.mail:sync/u0a63 (adj 15): empty #17
D/Process (  904): killProcessQuiet, pid=3698
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  904): Client connection lost with reason: 4
,I/ActivityManager(  904): Recipient 3698
,I/SensorManager(  904): mEventCount = 1050
,D/PMS     (  904): acquireWL(41d4f7e8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(41d4f7e8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(41ea3790): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(41ea3790): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(42426070): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(42426070): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  904): acquireWL(424d4fe8): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
,D/PMS     (  904): releaseWL(424d4fe8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  904): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=3973 uid=10077 gids={50077}
,D/PMS     (  904): acquireWL(42386fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{10077}
,V/AlarmManager(  904): sending alarm PendingIntent{41ce5a00: PendingIntentRecord{427cd088 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1457094195646, Int=60000
,D/PMS     (  904): releaseWL(42386fb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10077}
,D/SMSBackup( 3973): SMSBackupAgentService started
,D/SMSBackup( 3973): Checking restore status
,D/SMSBackup( 3973): Restore complete
,D/SMSBackup( 3973): cancelCheckAlarm
,D/SMSBackup( 3973): SMSBackupAgentService completed: completed in 0.0 seconds
,D/Process (  904): killProcessQuiet, pid=3738
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3738:com.htc.updater/u0a84 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3738
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  904): mEventCount = 1200
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1220): MSG_NOTIFY_CS_TO_SYNC <<
,I/SensorManager(  904): mEventCount = 1350
,I/PMS     (  904): Going to sleep due to screen timeout...
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421bff50
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = CM36282 Light sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 2
W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421bff50, eanble = 0, strlen(mName) = 59
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  904): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42367110
W/SensorService(  904): Listener[1] = com.htc.smartdim.sensor_eye@425d9400
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/ActivityManager(  904): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  904): Couldn't get kernel wake lock stats
V/LightsService(  904): setLight #2: color=#0
D/qdlights(  904): set_light_buttons_func: on=0 brightness=0
V/LightsService(  904): setLight #0: color=#0
,D/WirelessDisplayService(  904): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  904): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  904): mWirelessDisplayManager is null
,D/SurfaceControl(  904): Excessive delay in blankDisplay() while turning screen off: 410ms
D/PMS     (  904): nativeSetInteractive:false
D/PMS     (  904): nativeSetInteractive:false done
D/PMS     (  904): nativeSetAutoSuspend:true
D/PMS     (  904): nativeSetAutoSuspend:true done
D/HABCtrl (  904): TPE algorithm. remove timeout.
D/PMS     (  904): OOBE c monitor 11
I/InputManager(  904): Cancel all due to getting PMS screen off broadcast
,V/KeyguardServiceDelegate(  904): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@4288bea0)
D/PMN     (  904): wakingUp
I/IntentController( 1108): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
D/NfcService( 1231): ScreenObserver: OFF
,D/NfcService( 1231): applyRouting - 0
I/InputMethodManagerService(  904): screenObserver, isScreenOn=false
I/InputMethodManagerService(  904): Disable input method client, pid=3037
,V/KeyguardServiceDelegate(  904): **** SHOWN CALLED ****
,D/NfcService( 1231): applyRouting -2
,D/WirelessDisplayService(  904): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  904): acquireWL(425fd208): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
I/WindowManager(  904): No lock screen! windowToken=null
D/PMS     (  904): releaseWL(425fd208): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/PMN     (  904): onScreenOn
D/MtpService( 2235): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1231): applyRouting - 0
,D/MtpService( 2235): [MTP][onReceive]-
D/PMS     (  904): acquireWL(427ff770): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1231 1027 null
D/AlarmManager(  904): ACTION_SCREEN_ON
I/AlarmManager(  904): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done recovering
I/AlarmManager(  904): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  904): [AlarmQueuing] done EPS screen off alarm recovering
,D/AutoSetting( 1377): receiver - intent: android.intent.action.USER_PRESENT
,D/NfcService( 1231): applyRouting -2
D/PMS     (  904): releaseWL(427ff770): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,D/AutoSetting( 1377): service - onCreate()
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  904): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  904): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_ON
D/TetherSettings( 3384): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3384): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3384): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3384): Cust_ConnectToPC   : spcsc>false
D/        ( 3384): Cust_ConnectToPC   : IPT>true
D/        ( 3384): Cust_ConnectToPC   : Singel_USB>false
D/AutoSetting( 1377): service - AddressCache: using context: com.htc.Weather
W/Settings( 3384): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3384): hasRemovableStorageSlot: true
D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 1
D/SmartNS_Utility( 3384): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3384): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/WifiNative-wlan0(  904):    returned false
,I/PSReceiver( 3384): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1377): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,W/ContextImpl( 3384): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3384): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3384): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3384):  defaultType:0
D/LocationManagerService(  904): request 4250b9d0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10053)
D/LocationManagerService(  904): provider request: passive ProviderRequest[ON interval=0]
,I/ClockThread( 1108): stop update clock
V/NotificationService(  904): batLight: Full, plugged
V/LightsService(  904): setLight #8: color=#c8c800
D/qdlights(  904): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  904): setLight #8: color=#c800
D/qdlights(  904): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  904): [LedInfo] has indicator attribute
D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  904): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/SRS_Proc(  372): ParamSet string: screen_state=on
D/WirelessDisplayService(  904): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
,D/NetworkPolicy(  904): updateScreenOn: false
,I/ActivityManager(  904): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=3996 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  904): acquireWL(423d5cf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
D/PMS     (  904): releaseWL(423d5cf0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,I/SensorManager(  904): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42367110
,W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  904): pid=904, uid=1000
,W/SensorService(  904): Active sensors: size = 2
,W/SensorService(  904): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42367110, eanble = 0, strlen(mName) = 91
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  904): Listener[0] = com.htc.smartdim.sensor_eye@425d9400
,W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  904): goingToSleep
W/ContextImpl( 3996): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  904): acquireWL(42361b10): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 904 1000 null
,D/AlarmManager(  904): ACTION_SCREEN_OFF
I/AlarmManager(  904): [AlarmQueuing] screen off now: 
I/AlarmManager(  904): [AlarmQueuing] data connection: true
,I/AlarmManager(  904): [AlarmQueuing] wifi connection: false
D/WifiDataStallTracker(  904): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  904): stopDataStallAlarm: current tag=19374 mDataStallAlarmIntent=null
,D/WifiNative-wlan0(  904): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  904):    returned false
D/PMS     (  904): acquireWL(42605598): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 904 1000 null
D/PMS     (  904): releaseWL(42605598): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
D/PMS     (  904): releaseWL(42361b10): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/SmartSyncUtils( 3996): isEpsOn(), nState = 0
,V/SRS_Proc(  372): ParamSet string: screen_state=off
D/PMS     (  904): acquireWL(425c14e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3996 1000 null
D/NetworkPolicy(  904): updateScreenOn: false
,D/ContactMessageStore( 1220): start background delete task...
D/ContactMessageStore( 1220): size: 0 , 0
,D/ContactMessageStore( 1220): Background delete complete
,D/PMS     (  904): releaseWL(425c14e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/SmartSyncUtils( 3996): getMobilePolicyEnabled, result = true
W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 3996): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 3996): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3996): isEpsOn(), nState = 0
,D/SmartSyncUtils( 3996): getMobilePolicyEnabled, result = true
D/WifiService(  904): New client listening to asynchronous messages
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425d9400
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 1
W/SensorService(  904): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425d9400, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  904): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  904): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  904): pid=904, uid=1000
W/SensorService(  904): Active sensors: size = 0
W/SensorService(  904): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425d9400, eanble = 0, strlen(mName) = 36
W/SensorService(  904): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  904): void android::SensorService::listenerSensor(const char*, int32_t)--:
I/SensorManager(  904): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425d9400
,E/ActivityThread(  904): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42560048 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@42560048 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  904): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  904): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  904): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  904): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  904): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  904): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  904): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  904): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  904): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  904): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  904): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  904): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  904): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  904): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  904): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  904): 	at dalvik.system.NativeStart.main(Native Method)
,D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1538): [EventService] getTotalRam: 1873 Mb
D/PMS     (  904): acquireWL(4260beb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
,D/PMS     (  904): releaseWL(4260beb0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/AutoSetting( 1377): service - mHandler: cancel location update
D/AutoSetting( 1377): service -           changes count: 0
,D/Process (  904): killProcessQuiet, pid=3645
,I/ActivityManager(  904): Killing 3645:com.htc.musicenhancer/u0a51 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  904): Recipient 3645
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 1
,I/ActivityManager(  904): Waited long enough for: ServiceRecord{4273e6a8 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  904): acquireWL(427c5708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/PMS     (  904): releaseWL(427c5708): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  904): acquireWL(42598128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{423af7b8: PendingIntentRecord{423af758 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=140729, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{4222e610: PendingIntentRecord{42409a98 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=140740, Int=0
,V/AlarmManager(  904): sending alarm PendingIntent{422301b0: PendingIntentRecord{42456480 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=144847, Int=0
,D/GpsLocationProvider(  904): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  904): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  904): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  904): acquireWL(4274d228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 904 1000 null
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  904): [NET] getaddrinfo-,err=8
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
,D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
,D/libc    (  904): [NET] getaddrinfo_proxy-
D/PMS     (  904): releaseWL(4274d228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/PMS     (  904): releaseWL(42598128): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10028}
,D/AutoSetting( 1377): service - handleMessage() stop self
,D/AutoSetting( 1377): service - onDestroy() END
,D/AutoSetting( 1377): service - handleMessage() quit looper
,D/Process (  904): killProcessQuiet, pid=3777
,D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Killing 3777:com.htc.task.gtask/u0a67 (adj 15): empty #17
,I/ActivityManager(  904): Recipient 3777
,I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl(  904): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  904): acquireWL(4270efb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  904): sending alarm PendingIntent{41beaa98: PendingIntentRecord{41be40e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=147539, Int=0
,D/PMS     (  904): releaseWL(4270efb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 4
,D/ConnectivityService(  904): getActiveNetworkInfo called by com.google.android.gms (1199/10028)
,D/PMS     (  904): acquireWL(4274fb80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  904): n_update end
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/PMS     (  904): releaseWL(4274fb80): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1108): closing low battery warning: level=100
,D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,D/TelephonyReceiver( 1220): switchBindHtcMsgCursor: null
,D/PMS     (  904): acquireWL(425aeec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/UsbnetService(  904): BroadcastReceiver::onReceive+
,I/IntentController( 1108): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/BatteryService(  904): n_update end
D/UsbnetService(  904): onReceive BATTERY_CHANGED
D/UsbnetService(  904):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  904): BroadcastReceiver::onReceive-
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1538): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1538): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1108): closing low battery warning: level=100
D/PowerUI ( 1108): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  904): updateBatteryInfo
D/PMS     (  904): runPSCheck
D/HtcPowerSaver(  904): Checking...
I/HtcPowerSaver(  904): >> updateStatus
D/PMS     (  904): releaseWL(425aeec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  904): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  904): << updateStatus
,W/AppWidgetServiceImpl(  904): updateAppWidget failed! callbacks null,
,I/BatteryController( 1108): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  412): AtCmdFwd service not published, waiting... retryCnt : 5
,D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  904): [NET] getaddrinfo-,err=8
D/PMS     (  904): acquireWL(427d2a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
V/AlarmManager(  904): sending alarm PendingIntent{4222e610: PendingIntentRecord{42409a98 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=204924, Int=0
,D/PMS     (  904): releaseWL(427d2a50): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  904): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  904): [NET] getaddrinfo-, 1
D/libc    (  904): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  365): [NET] get_iface_protocol fail: 
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  365): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  365): [NET] getaddrinfo-,err=7
D/libc    (  904): [NET] getaddrinfo_proxy-
,D/PMS     (  904): acquireWL(4288b170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 904 1000 WorkSource{1000}
,V/AlarmManager(  904): sending alarm PendingIntent{41beaa98: PendingIntentRecord{41be40e8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=207539, Int=0
,I/IntentController( 1108): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  904): releaseWL(4288b170): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4023): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4023): ====startRecUseTime====
D/htc.customization.log.level( 4023):  is 
W/CustomizationLogLevel( 4023): Level value is invalid, use default level 2
D/CustomizationManager( 4023):  Read ACC file spent 0.102 (s)
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4023): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4023): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4023): Parsing tag category name = system
I/CustomizationCIDLoader( 4023): Parsing tag category name = application
I/CustomizationCIDLoader( 4023): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4023): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4023): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4023): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4023): Parsing tag category name = Settings
D/CustomizationManager( 4023):  Read CID file spent 0.156 (s)
D/CustomizationManager( 4023):  All configurations done spent 0.156 (s)
W/HtcNativeFlag( 4023): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4023): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4023): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4023): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  904): deletePackageAsUser: pkg=com.example.hello, pid=4023, uid=2000 user=0
D/Process (  904): killProcessQuiet, pid=3037
I/ActivityManager(  904): Force stopping com.example.hello appid=10190 user=-1: uninstall pkg
I/ActivityManager(  904): Killing 3037:com.example.hello/u0a190 (adj 0): stop com.example.hello
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/ActivityManager(  904): handleTopAppChanged(): The previous AP is died unexpectedly.
W/asset   (  904): Copying FileAsset 0x6962bf90 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  904):   Force finishing activity ActivityRecord{4254f7e8 u0 com.example.hello/.MainActivity t2}
W/InputDispatcher(  904): channel '42443b50 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  904): channel '42443b50 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  904): channel '4249ef90 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  904): channel '4249ef90 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
W/InputDispatcher(  904): Attempted to unregister already unregistered input channel '42443b50 com.example.hello.MainActivity (s)'
I/WindowManager(  904): WINDOW DIED Window{42443b50 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher(  904): Attempted to unregister already unregistered input channel '4249ef90 com.example.hello.MainActivity (s)'
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowManager(  904): WINDOW DIED Window{4249ef90 u0 com.example.hello/com.example.hello.MainActivity}
W/WindowManager(  904): Failed looking up window
W/WindowManager(  904): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@4249ed40 does not exist
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  904): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  904): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  904): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  904): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  904): WIN DEATH: null
W/PackageSettings(  904): Skipping PackageSetting{421f7518 com.test.thalitest/10189} due to missing metadata
W/InputMethodManagerService(  904): Got RemoteException sending setActive(false) notification to pid 3037 uid 10190
I/ActivityManager(  904): Force stopping com.example.hello appid=10190 user=0: pkg removed
W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
D/DotMatrix( 1538): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1538): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1538): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1108): ApplicationsIntentReceiver replacing:false
I/acms    ( 1763): Unregistering com.example.hello
E/acms    ( 1763): Could not unregister removed application com.example.hello
W/GeofencerStateMachine( 1421): Ignoring removeGeofence because network location is disabled.
D/PMS     (  904): acquireWL(4281d5f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1421 10028 null
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1274): Cleaning up data for package: com.example.hello
W/AccTypeManager( 1308): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1308): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  904): releaseWL(4281d5f8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
W/SystemReader( 1231): Cannot find nfc_is_upgrade_to_ar890, use default value instead
D/PackageBroadcastService( 1199): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/AccTypeManager( 1308): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/Launcher( 1247): Deferring update until onResume
D/Launcher( 1247): waitUntilResume // bindAppsRemoved
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/ActivityManager(  904): Start proc com.google.android.gms.drive for broadcast com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver: pid=4038 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/InputMethodManagerService(  904): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
E/ExternalAccountType( 1308): Unsupported attribute readOnly
I/ActivityManager(  904): Delaying start of: ServiceRecord{425ebcc0 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/MultiDex( 4038): install
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "sms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/MultiDex( 4038): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "smsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
I/MultiDex( 4038): loading existing secondary dex files
I/MultiDex( 4038): load found 1 secondary dex files
I/MultiDex( 4038): install done
I/PeopleContactsSync( 1199): CP2 sync disabled
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mms"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PMS     (  904): acquireWL(4259b078): PARTIAL_WAKE_LOCK  Icing 0x1 1199 10028 null
I/Icing   ( 1199): doRemovePackageData com.example.hello
I/PackageManager(  904):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1199, uid=10028, userID:0
I/PackageManager(  904):   Action: "android.intent.action.SENDTO"
I/PackageManager(  904):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  904):   Scheme: "mmsto"
I/PackageManager(  904): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1220 :
D/PhoneApp( 1220): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  904): releaseWL(4259b078): PARTIAL_WAKE_LOCK  Icing 0x1 null
I/ActivityManager(  904): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableControlService: pid=4057 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
I/ProviderInstaller( 4038): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
I/ActivityManager(  904): Delay finish: com.google.android.gms/.drive.api.DriveSystemBroadcastReceiver
I/MultiDex( 4057): install
I/MultiDex( 4057): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
I/MultiDex( 4057): loading existing secondary dex files
I/MultiDex( 4057): load found 1 secondary dex files
I/MultiDex( 4057): install done
E/SQLiteDatabase( 1199): Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
E/SQLiteDatabase( 1199): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 1199): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 1199): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 1199): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 1199): 	at bxi.delete(SourceFile:258)
E/SQLiteDatabase( 1199): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/SQLiteDatabase( 1199): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/SQLiteDatabase( 1199): 	at aqn.a(SourceFile:27)
E/SQLiteDatabase( 1199): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/SQLiteDatabase( 1199): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 1199): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 1199): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 1199): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ClearPendingStateOp( 1199): Runtime exception while performing operation
E/ClearPendingStateOp( 1199): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/ClearPendingStateOp( 1199): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/ClearPendingStateOp( 1199): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/ClearPendingStateOp( 1199): 	at bxi.delete(SourceFile:258)
E/ClearPendingStateOp( 1199): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/ClearPendingStateOp( 1199): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/ClearPendingStateOp( 1199): 	at aqn.a(SourceFile:27)
E/ClearPendingStateOp( 1199): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
E/ClearPendingStateOp( 1199): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ClearPendingStateOp( 1199): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ClearPendingStateOp( 1199): 	at android.os.Looper.loop(Looper.java:157)
E/ClearPendingStateOp( 1199): 	at android.os.HandlerThread.run(HandlerThread.java:61)
F/ClearPendingStateOp( 1199): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 1199): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
F/ClearPendingStateOp( 1199): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
F/ClearPendingStateOp( 1199): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
F/ClearPendingStateOp( 1199): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
F/ClearPendingStateOp( 1199): 	at bxi.delete(SourceFile:258)
F/ClearPendingStateOp( 1199): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
F/ClearPendingStateOp( 1199): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
F/ClearPendingStateOp( 1199): 	at aqn.a(SourceFile:27)
F/ClearPendingStateOp( 1199): 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
F/ClearPendingStateOp( 1199): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
F/ClearPendingStateOp( 1199): 	at android.os.Handler.dispatchMessage(Handler.java:102)
F/ClearPendingStateOp( 1199): 	at android.os.Looper.loop(Looper.java:157)
F/ClearPendingStateOp( 1199): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ProviderInstaller( 4057): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
W/SQLiteConnectionPool( 1199): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/ActivityManager(  904): Resuming delayed broadcast
E/DropBoxManagerService(  904): Can't write: system_app_wtf
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
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
E/SharedPreferencesImpl( 1185): Couldn't rename file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml to backup file /data/data/com.htc.sense.ime/shared_prefs/com.htc.sense.ime_preferences.xml.bak
W/SQLiteConnectionPool( 1199): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/SQLiteConnectionPool( 1199): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[PluginManager]RegisterService( 1377): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
E/SQLiteLog( 1377): (3850) statement aborts at 44: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
E/SQLiteDBG( 1377): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/user/0/com.htc.sense.hsp/databases/registry.db, handle = 0x5ca34838
W/[PluginManager]RegisterService( 1377): provider may killed!
W/[PluginManager]RegisterService( 1377): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
W/[PluginManager]RegisterService( 1377): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
W/[PluginManager]RegisterService( 1377): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
W/[PluginManager]RegisterService( 1377): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
W/[PluginManager]RegisterService( 1377): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
W/[PluginManager]RegisterService( 1377): 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1645)
W/[PluginManager]RegisterService( 1377): 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1591)
W/[PluginManager]RegisterService( 1377): 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
W/[PluginManager]RegisterService( 1377): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
W/[PluginManager]RegisterService( 1377): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
W/[PluginManager]RegisterService( 1377): 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
W/[PluginManager]RegisterService( 1377): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/[PluginManager]RegisterService( 1377): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/[PluginManager]RegisterService( 1377): 	at android.os.Looper.loop(Looper.java:157)
W/[PluginManager]RegisterService( 1377): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[PluginManager]RegisterService( 1377): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1247): action: android.intent.action.PACKAGE_REMOVED
I/IcingCorporaProvider( 2671): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
D/Process (  904): killProcessQuiet, pid=3822
I/ActivityManager(  904): Killing 3822:com.google.android.talk/u0a111 (adj 15): empty #17
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  904): Recipient 3822
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4077 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
E/SQLiteLog( 2671): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2671): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x63af5190
W/dalvikvm( 2671): threadid=16: thread exiting with uncaught exception (group=0x416f0e30)
E/ActivityManager(  904): App crashed! Process: com.google.android.googlequicksearchbox:search
E/SQLiteDatabase( 4038): Failed to open database '/data/data/com.google.android.gms/databases/DocList.db'.
E/SQLiteDatabase( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4038): 	at ctl.a(SourceFile:968)
E/SQLiteDatabase( 4038): 	at ctl.b(SourceFile:962)
E/SQLiteDatabase( 4038): 	at ctn.run(SourceFile:985)
W/dalvikvm( 4038): threadid=12: thread exiting with uncaught exception (group=0x416f0e30)
E/AndroidRuntime( 2671): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2671): Process: com.google.android.googlequicksearchbox:search, PID: 2671
E/AndroidRuntime( 2671): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2671): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2671): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2671): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2671): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2671): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2671): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2671): 	at cid.d(PG:186)
E/AndroidRuntime( 2671): 	at clo.g(PG:594)
E/AndroidRuntime( 2671): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2671): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2671): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2671): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2671): 	at clr.tL(PG:827)
E/AndroidRuntime( 2671): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2671): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2671): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2671): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/Process ( 2671): killProcess, pid=2671
E/ActivityManager(  904): App crashed! Process: com.google.android.gms.drive
D/Process ( 2671): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/AndroidRuntime( 4038): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4038): Process: com.google.android.gms.drive, PID: 4038
E/AndroidRuntime( 4038): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4038): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4038): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4038): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4038): 	at ctl.a(SourceFile:968)
E/AndroidRuntime( 4038): 	at ctl.b(SourceFile:962)
E/AndroidRuntime( 4038): 	at ctn.run(SourceFile:985)
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
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
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4038): killProcess, pid=4038
D/Process ( 4038): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Recipient 2671
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.googlequicksearchbox:search (pid 2671) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms
D/MediaRouterService(  904): Client com.google.android.googlequicksearchbox (pid 2671): Died!
D/WifiService(  904): Client connection lost with reason: 4
I/ActivityManager(  904): Recipient 4038
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.google.android.gms.drive (pid 4038) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10975ms
E/SQLiteDatabase( 4077): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4077): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4077): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4077): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4077): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4077): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4077): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4077): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4077): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4077): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4077): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4077): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4077): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4077): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4077): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4077): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4077): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4077): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4077): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4077): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4077): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4077): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4077): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4077): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4077): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4077): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4077): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4077): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4077): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4077): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4077): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4077): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4077): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4077): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4077): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4077): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4077): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4077): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4077): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4077): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4077): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4077): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4077): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4077): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4077): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4077): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4077): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4077): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4077): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4077): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4077): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4077): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4077): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4077): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4077): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4077): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4077): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4077): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4077): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4077): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4077): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4077): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4077): threadid=11: thread exiting with uncaught exception (group=0x416f0e30)
E/AndroidRuntime( 4077): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4077): Process: com.google.android.apps.docs, PID: 4077
E/AndroidRuntime( 4077): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4077): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4077): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4077): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4077): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4077): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4077): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4077): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4077): 	at aho.run(AbstractDatabaseInstance.java:455)
E/ActivityManager(  904): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  904): Can't write: system_app_crash
E/DropBoxManagerService(  904): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4077): killProcess, pid=4077
D/Process ( 4077): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  904): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4095 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  904): Recipient 4077
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  904): killProcessQuiet, pid=3723
D/Process (  904): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  904): Killing 3723:com.htc.sense.mms/u0a64 (adj 15): empty #17
I/ActivityManager(  904): Process com.google.android.apps.docs (pid 4077) has died.
I/ActivityManager(  904): Recipient 3723
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/ContextImpl( 4095): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  904): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4108 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 4095): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4095): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4095): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4095): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4095): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4095): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4095): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4095): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4095): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4095): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4095): threadid=10: thread exiting with uncaught exception (group=0x416f0e30)
E/AndroidRuntime( 4095): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4095): Process: com.android.keychain, PID: 4095
E/AndroidRuntime( 4095): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4095): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4095): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4095): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4095): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4095): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4095): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4095): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4095): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4095): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  904): App crashed! Process: com.android.keychain
D/ErrorReport(  904): HtcErrorReportManager Begin---add error logs to dropbox
I/Prism.ItemManager( 1247): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1247): loadItems() com.htc.launcher.pageview.WidgetManager@41bb30a8 +
I/Prism.WidgetManager( 1247): onLoadItems() +
D/AppTag  ( 4108): getInstance(Context context)
D/Process ( 4095): killProcess, pid=4095
D/Process ( 4095): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  904): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  904): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1457094308511.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  904): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  904): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  904): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  904): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  904): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  904): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  904): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  904): 	... 4 more
D/AppTag  ( 4108): getInstance(Context context)
D/AppTag  ( 4108): onCreate()
I/ActivityManager(  904): Recipient 4095
I/DisplayManagerService(  904): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  904): Process com.android.keychain (pid 4095) has died.
W/ActivityManager(  904): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10362ms
D/PMS     (  904): acquireWL(41f3e730): PARTIAL_WAKE_LOCK  AsyncService 0x1 3539 10160 null
D/PMS     (  904): releaseWL(41f3e730): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  904): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4126 uid=10098 gids={50098, 3003, 5012}
W/PackageManager(  904): Unable to load service info ResolveInfo{420e8290 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/DeviceManagement( 4126): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4126 dbg=false s=true
I/DeviceManagement( 4126): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4126): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/DeviceManagement( 4126): WorkflowService: Starting workflow service
I/DeviceManagement( 4126): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b50f50] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4126): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4126): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4126): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4126): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  904): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4140 uid=10099 gids={50099, 3003, 5012}
I/DeviceManagement( 4126): BackgroundController: *** Processing package remove for appID=com.example.hello

```
