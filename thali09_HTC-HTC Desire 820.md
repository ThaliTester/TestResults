#### Test 55634150e857e16_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
I/ActivityManager(  905): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3205 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
--------- beginning of /dev/log/main
D/Process (  905): killProcessQuiet, pid=2964
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2964:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  905): Recipient 2964
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1527): handler message = 4011
E/HtcModeClient( 1527): Check connection and retry 4 times.
I/GAV2    ( 2993): Thread[GAThread,5,main]: No campaign data found.
I/GAv4-SVC( 2152): Google Analytics 8.4.89 is starting up.
D/WIFI_ICON( 1118): WifiActivity: 1
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
E/YouTube ( 3205): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 3205): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3205): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 3205): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [8][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  905):    returned true
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3205/10168)
E/cutils-trace( 3217): Error opening trace file: No such file or directory (2)
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3205): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/YouTube ( 3205): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3205): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3205): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/CustomizationManager( 3217): ====startRecUseTime====
D/htc.customization.log.level( 3217):  is 
W/CustomizationLogLevel( 3217): Level value is invalid, use default level 2
D/YouTube ( 3205): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/MediaRouterService(  905): Client com.google.android.youtube (pid 3205): Registered
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
I/MediaRouter( 3205): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/YouTube ( 3205): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3205): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1452528597&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  905): getNetworkInfo networkType=0 called by com.google.android.youtube (3205/10168)
D/libc    ( 3205): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3205): [NET] getaddrinfo-,err=8
D/libc    ( 3205): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3205): [NET] getaddrinfo-, 1
D/libc    ( 3205): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =8ab1 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3205): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3205): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 3205): getSelectedRoute
D/CustomizationManager( 3217):  Read ACC file spent 0.062 (s)
D/YouTube ( 3205): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3205): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__032
D/YouTube ( 3205): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3217): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3217): full path : /system/customize/CID/HTC__032.xml
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3205/10168)
I/CustomizationCIDLoader( 3217): Parsing tag category name = system
I/CustomizationCIDLoader( 3217): Parsing tag category name = application
I/CustomizationCIDLoader( 3217): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3217): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3217): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3217): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3217): Parsing tag category name = Settings
D/CustomizationManager( 3217):  Read CID file spent 0.115 (s)
D/CustomizationManager( 3217):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 3217): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3217): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3217): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3217): Fail to get flag for type 'language', use default value: -1
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3205/10168)
D/YouTube ( 3205): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 294
D/libc    (  363): [NET]res_nsend:resplen=96
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3205): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  905): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3268 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.youtube (3205/10168)
D/Process (  905): killProcessQuiet, pid=2993
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2993:com.google.android.gm/u0a107 (adj 15): empty #17
D/YouTube ( 3205): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3205): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3205): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/ActivityManager(  905): Recipient 2993
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/CpuWake (  905): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  905): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  905): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  905): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3217
D/PMS     (  905): acquireHCC(426ff470): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 905 1000 null
W/asset   (  905): Copying FileAsset 0x65c80290 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  905): @test_code: getHtcIntentFlag: 0 obj: 1110864696
D/PMS     (  905): acquireHCC(426f1f48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 905 1000 null
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c12168
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
D/PMS     (  905): acquireWL(4267e3a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 905 1000 null
I/ActivityManager(  905): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3283 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
I/GoogleConversionPing( 3205): Ping responded with response code 200
W/asset   ( 3283): Copying FileAsset 0x5c714428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1273): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3283): Binding Chromium to main looper Looper (main, tid 1) {41aa7458}
I/LibraryLoader( 3283): Expected native library version number "",actual native library version number ""
I/chromium( 3283): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3283): Initializing chromium process, renderers=0
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@421c46c8:true
D/PMS     (  905): acquireWL(4263e7c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): acquireWL(4263e770): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  905): releaseWL(4263e770): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 3283): 1101778512: getState(). Returning 12
I/Adreno-EGL( 3283): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3283): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3283): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3283): Local Branch: 
I/Adreno-EGL( 3283): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3283): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3283):                  aa63bbd948f41d15fc72f585e
W/chromium( 3283): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3268): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/dalvikvm( 3283): VFY: unable to resolve virtual method 170: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3283): VFY: unable to resolve virtual method 165: Landroid/webkit/CookieManager;.flush ()V
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3268, uid=10074, userID:0
W/dalvikvm( 3283): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3283): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3283): VFY: unable to resolve virtual method 223: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3283): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3283): VFY: unable to resolve virtual method 181: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3283): VFY: unable to resolve virtual method 186: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3283): CordovaWebView is running on device made by: HTC
D/Finsky  ( 3268): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3268/10074)
,W/dalvikvm( 3268): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,W/dalvikvm( 3268): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,W/AwContents( 3283): nativeOnDraw failed; clearing to background color.
D/ConnectivityService(  905): getAllNetworkInfo called by com.android.vending (3268/10074)
,D/Finsky  ( 3268): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3268): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/ResourceType( 3283): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3283): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41aee300, mServedView=org.apache.cordova.engine.SystemWebView{41ab4170 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1212): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1212): [T9_ReleaseBuffer] Reset LDB#1
,D/XT9_C   ( 1212): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  905): Disable input method client, pid=1273
,I/InputMethodManagerService(  905): Enable input method client, pid=3283
W/Settings( 3268): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/AwContents( 3283): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  905): Displayed com.example.hello/.MainActivity: +249ms
W/Settings( 3268): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/PMS     (  905): releaseWL(4267e3a0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,W/dalvikvm( 3268): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3268): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3268): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3268): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3268, uid=10074, userID:0
,D/Volley  ( 3268): [310] DiskBasedCache.clear: Cache cleared.
,D/Ads     ( 3268): Skipping gmscore version check
,D/Finsky  ( 3268): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Volley  ( 3268): [303] DiskBasedCache.clear: Cache cleared.
,D/Finsky  ( 3268): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  905): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
,D/Finsky  ( 3268): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 3268): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  905): Resuming delayed broadcast
,D/WIFI_ICON( 1118): WifiActivity: 3
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,E/AndroidProtocolHandler( 3283): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3283): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3283): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3283): JniHelper::setJavaVM(0x4157a048), pthread_self() = 1632766712
D/JX-Cordova( 3283): jxcore cordova android initializing
W/dalvikvm( 2152): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2152): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2152): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2152): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  905): acquireWL(42594798): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2152 10029 null
D/FileApkUtils( 2152): Spent 24ms computing apk sha1.
D/FileApkUtils( 2152): Module already staged or being staged:chimera-modules/MapsModule.apk
I/ActivityManager(  905): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/DexOptUtils( 2152): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/PMS     (  905): acquireWL(42506770): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2152 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42594798): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  905): releaseWL(42506770): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
D/FileApkUtils( 2152): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 2152): Reading stored module config
I/ActivityManager(  905): Resuming delayed broadcast
W/jxcore-log( 3283): Initializing JXcore engine
W/jxcore-log( 3283): JXcore engine is ready
D/GmsModuleFndr( 2152): Beginning GMS chimera module scan
W/jxcore-log( 3283): Starting JXcore engine
W/InstanceID/Rpc( 2152): Found 10029
W/asset   ( 2152): Copying FileAsset 0x6ddfe320 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
D/ChimeraCfgMgr( 2152): Beginning module configuration check
D/ChimeraCfgMgr( 2152): Module APKs unchanged, check complete
D/Process (  905): killProcessQuiet, pid=3027
I/ActivityManager(  905): Killing 3027:com.htc.backup/1000 (adj 15): empty #17
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/dalvikvm( 2152): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 2152): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 2152): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2152): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2152): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2152): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2152): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 2152): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2152): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/ActivityManager(  905): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2152/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2152/10029)
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/dalvikvm( 1225): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1225): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1225): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1225): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1225): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
E/dalvikvm( 2152): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1225): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2152): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
W/dalvikvm( 1225): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=40 [5][2][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1225): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1225): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/ActivityManager(  905): Resuming delayed broadcast
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(423a6810): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2152 10029 WorkSource{10029 com.google.android.gms}
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/dalvikvm( 2152): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 2152): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 2152): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 2152): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
W/dalvikvm( 2152): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
I/ActivityManager(  905): Recipient 3027
I/ActivityManager(  905): Delay finish: com.google.android.gms/.tapandpay.receiver.OnBootCompletedReceiver
D/PMS     (  905): acquireWL(42645488): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2152 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(423a6810): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2152): Checkin interval check for package: unspecified last checkin: 1452528229604 min interval config: 0 actual interval: 369051
D/GCM     ( 2152): COMPAT: Multi user not supported
D/PMS     (  905): acquireWL(425deab8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2152 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2903): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
I/CheckinService( 2152): Disabling old GoogleServicesFramework version
W/dalvikvm( 2903): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 2903): VM with version 1.6.0 does not have multidex support
I/MultiDex( 2903): install
I/MultiDex( 2903): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2152, uid=10029, userID:0
W/dalvikvm( 2152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/GCoreUlr( 2152): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/MultiDex( 2903): loading existing secondary dex files
D/SystemUpdateService( 2152): onCreate
I/MultiDex( 2903): load found 3 secondary dex files
I/GCoreUlr( 1225): DispatchingService.onCreate()
I/MultiDex( 2903): install done
D/SystemUpdateService( 2152): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
W/dalvikvm( 2152): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
W/jxcore-log( 3283): Platform android
W/jxcore-log( 3283): 
W/jxcore-log( 3283): Process ARCH arm
W/jxcore-log( 3283): 
V/AuthZen ( 2152): Handling intent: android.intent.action.BOOT_COMPLETED
W/dalvikvm( 2903): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 2903): VFY: unable to resolve instance field 36
W/dalvikvm( 2903): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
V/JNIHelp ( 2903): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/SystemUpdateService( 2152): cancelUpdate (empty URL)
I/SystemUpdateService( 2152): active receiver: disabled
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2152, uid=10029, userID:0
D/PMS     (  905): acquireWL(4264ce60): PARTIAL_WAKE_LOCK  Icing 0x1 2152 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
W/dalvikvm( 2152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
D/PMS     (  905): releaseWL(4264ce60): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2152, uid=10029, userID:0
D/PMS     (  905): acquireWL(425cf9b0): PARTIAL_WAKE_LOCK  Icing 0x1 2152 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2152, uid=10029, userID:0
I/CheckinService( 2152): Checking schedule, now: 1452528598767 next: 1453051166555
I/CheckinService( 2152): active receiver: disabled
D/AuthZenEventHandler( 2152): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2152, uid=10029, userID:0
D/PMS     (  905): acquireWL(42738910): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2152, uid=10029, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2152/10029)
I/jxcore-log( 3283): JXcore Cordova bridge is ready!
I/jxcore-log( 3283): 
W/jxcore-log( 3283): JXcore engine is started
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2152, uid=10029, userID:0
D/PMS     (  905): releaseWL(425deab8): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2152, uid=10029, userID:0
D/PMS     (  905): releaseWL(425cf9b0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2152, uid=10029, userID:0
D/SystemUpdateService( 2152): onDestroy
D/PMS     (  905): releaseWL(42645488): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1225): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
W/BaseAppContext( 2152): Using Auth Proxy for data requests.
E/jxcore-log( 3283): >> HTC-HTC Desire 820
E/jxcore-log( 3283): 
I/jxcore-log( 3283): Total memory 1964650496
I/jxcore-log( 3283): 
I/jxcore-log( 3283): Free memory 656596992
I/jxcore-log( 3283): 
I/jxcore-log( 3283): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3283): 
I/jxcore-log( 3283): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3283): 
W/dalvikvm( 2152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2152): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2152): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/jxcore-log( 3283): userPath [ 'www', 'www' ]
I/jxcore-log( 3283): 
I/jxcore-log( 3283): Size 720 1184
I/jxcore-log( 3283): 
E/BaseAppContext( 2152): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/jxcore-log( 3283): Screen Brightness 142
I/jxcore-log( 3283): 
E/jxcore-log( 3283): Dummy Error Log.
E/jxcore-log( 3283): 
I/ProviderInstaller( 2903): Installed default security provider GmsCore_OpenSSL
W/dalvikvm( 2152): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/GCM     ( 2903): COMPAT: Multi user not supported
I/AuthZen ( 2152): Fetching signing key...
W/dalvikvm( 2903): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/AuthZen ( 2152): Signing key fetched successfully!
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1225, uid=10029, userID:0
W/dalvikvm( 2903): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
W/BaseAppContext( 2152): Using Auth Proxy for data requests.
D/AuthZenTransactionCache( 2152): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2152): Clearing transaction cache
W/dalvikvm( 2903): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2903): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2903): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2903): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/GCoreUlr( 1225): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
W/dalvikvm( 2903): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
W/dalvikvm( 2903): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/PMS     (  905): acquireWL(427011e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1225): Unbound from all location providers
I/GCoreUlr( 1225): Place inference reporting - stopped
W/dalvikvm( 2903): VFY: unable to resolve instance field 161
D/PMS     (  905): releaseWL(427011e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42738910): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
D/WifiService(  905): New client listening to asynchronous messages
I/GCoreUlr( 1225): DispatchingService.onDestroy()
I/GCoreUlr( 1225): Stopping handler for UlrDispSvcFast
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
I/GCoreUlr( 1225): Unbound from all location providers
I/GCoreUlr( 1225): Place inference reporting - stopped
D/NativeLibraryUtils( 2903): Install completed successfully. count=14 extracted=0
D/PMS     (  905): acquireWL(4273ce78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(4273ce78): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 2903): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,W/dalvikvm( 2903): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,D/PMS     (  905): acquireWL(426d6f28): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 2903 10029 WorkSource{10029 com.google.android.gms}
,D/GCM     ( 2903): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/libc    ( 2903): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2903): [NET] getaddrinfo-,err=8
D/libc    ( 2903): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 2903): [NET] getaddrinfo-, 1
D/libc    ( 2903): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =a461 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2903): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2903): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2903): [NET] getaddrinfo-,err=8
,D/libc    ( 2903): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 2903): [NET] getaddrinfo-,err=8
,W/dalvikvm( 2903): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,V/GLSActivity( 2903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/GCM     ( 2903): GCM config loaded
,V/GLSActivity( 2903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,W/dalvikvm( 2903): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,W/dalvikvm( 2903): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 2903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 2903): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/PMS     (  905): acquireWL(427f38c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2903 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
D/PMS     (  905): releaseWL(426d6f28): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2903/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  905): handleInetConditionChange: starting a change hold
,D/PMS     (  905): releaseWL(427f38c0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): acquireWL(427f0ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2903 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2903/10029)
,D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,D/ConnectivityService(  905): reportInetCondition for net 1, percentage: 100 by  (2903/10029)
D/ConnectivityService(  905): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  905): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024345
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024412
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024416
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024427
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024432
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025734
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025748
,W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028591
,V/AlarmManager(  905): sending alarm PendingIntent{425a0218: PendingIntentRecord{42591098 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=48632, Int=259200000
,V/AlarmManager(  905): sending alarm PendingIntent{41d04a60: PendingIntentRecord{424337b8 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50317, Int=0
,D/PMS     (  905): releaseWL(427f0ba8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/jxcore-log( 3283): getBuffer is called!!!!
I/jxcore-log( 3283): 
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(42735820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=11 [9][1][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/ChimeraCfgMgr( 2152): Loading module com.google.android.gms.gass from APK com.google.android.gms
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/ActivityManager(  905): Resuming delayed broadcast
D/PMS     (  905): acquireWL(42510888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 905 1000 WorkSource{10029}
,D/BootCompletedReceiver( 2152): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
I/IntentController( 1118): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/BootCompletedReceiver( 2152): Got an BootCompleted event.
,D/BootCompletedReceiver( 2152): Will NOT schedule AdAttestation signal task because it's disabled.
D/PMS     (  905): releaseWL(42735820): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(423ac2d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(423ac2d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 2903): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,W/Auth    ( 2903): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 2903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  905): acquireWL(425185b0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 2903 10029 null
,D/PhoneStatusBar( 1118): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
D/PMS     (  905): releaseWL(425185b0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,D/PersistentNotificationBroadcastReceiver( 1225): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,D/AutoSetting( 1319): receiver - intent: android.intent.action.USER_PRESENT
I/ClockThread( 1118): now=1452528599552 next=448
D/TetherSettings( 3157): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3157): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3157): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3157): Cust_ConnectToPC   : spcsc>false
D/        ( 3157): Cust_ConnectToPC   : IPT>true
D/        ( 3157): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3157): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3157): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3157): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3157): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1319): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 3157): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 3157): onReceive:android.intent.action.USER_PRESENT
,W/Settings( 3157): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3157):  defaultType:0
W/ContextImpl( 3157): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3410 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  905): acquireWL(424b64d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  905): acquireWL(424503f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 905 1000 WorkSource{10029}
D/PMS     (  905): releaseWL(424b64d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(422bebe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
D/PMS     (  905): releaseWL(42510888): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  905): releaseWL(422bebe8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(42684478): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(42684478): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/browser ( 3410): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3410): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3410): Loading: swewebviewchromium
,I/LibraryLoader( 3410): Time to load native libraries: 32 ms (timestamps 9637-9669)
,I/LibraryLoader( 3410): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3410): Initializing chromium process, renderers=9
I/LibraryLoader( 3410): Expected native library version number "",actual native library version number ""
,I/chromium( 3410): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/PMS     (  905): acquireWL(423de9c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/PMS     (  905): releaseWL(424503f8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1118): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  905): releaseWL(423de9c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1118): removeIcon slot=sync_active index=7 viewIndex=0
,W/CpuWake (  905): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  905): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  905): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  905): <<release mCpuPerf_Freq wakelock
D/PMS     (  905): releaseHCC(426ff470): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  905): releaseHCC(426f1f48): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/ConnectivityService(  905): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  905): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/Adreno-EGL( 3410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3410): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3410): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3410): Local Branch: 
I/Adreno-EGL( 3410): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3410): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3410):                  aa63bbd948f41d15fc72f585e
,V/IccIntentReceiver( 1289): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1527): SIM state: ABSENT
I/SIMStateChangeReceiver( 1527): phoneType = 0
,I/SIMStateChangeReceiver( 1527): remove notification
,I/ActivityManager(  905): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3451 uid=10032 gids={50032, 3003, 5012}
,I/ClockThread( 1118): now=1452528600001 next=59999
V/AlarmManager(  905): sending alarm PendingIntent{420173d0: PendingIntentRecord{4200a780 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=52763, Int=0
,I/IntentController( 1118): receive(android.intent.action.TIME_TICK,1,false)
,I/ActivityManager(  905): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3463 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  905): killProcessQuiet, pid=2673
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 2673:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2673
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2758): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2758): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2758): onReceive()
D/ExchangePolicystatus( 2758): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2758): onReceive(): else
D/Process (  905): killProcessQuiet, pid=2979
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1242): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  905): Killing 2979:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3478 uid=10041 gids={50041}
,I/ActivityManager(  905): Recipient 2979
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  905): killProcessQuiet, pid=3059
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3493 uid=10078 gids={50078}
I/ActivityManager(  905): Killing 3059:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3463): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/SMSBackup( 3493): Got a database change event
,D/Process (  905): killProcessQuiet, pid=3085
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3085:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3085
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 3463): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3463): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/WeatherUtility( 1118): can't get weather sync account
,I/ActivityManager(  905): Recipient 3059
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3507 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,E/ExternalAccountType( 3463): Unsupported attribute readOnly
,W/WeatherRequest( 1118): request cur loc, but there is no sys cur
,D/AccTypeManager( 3463): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CalendarApplication( 3507): onCreate
D/ProviderChangeReceiver( 3507): ---------------------------------------------------
,D/ProviderChangeReceiver( 3507): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3507): start to updateAlertNotification!
W/AccTypeManager( 3463): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3463): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/ContextImpl( 3132): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  905): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/AlertService( 3507): No fired or scheduled alerts
,D/HtcAlertUtils( 3507): -- cancelReminderNotification --
,D/HtcAlertUtils( 3507): broadcastExistReminder!
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/ExternalAccountType( 3463): Unsupported attribute readOnly
,I/ActivityManager(  905): Resuming delayed broadcast
,D/Process (  905): killProcessQuiet, pid=3103
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  905): Killing 3103:com.htc.htccupd/u0a17 (adj 15): empty #17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=11 [9][1][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 144
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  905): Recipient 3103
,D/WearableService( 1225): callingUid 10029, callindPid: 1225
,I/ActivityManager(  905): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
E/MDM     ( 1225): [95] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2152): Restart initialization of location
I/ActivityManager(  905): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 2903): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/dalvikvm( 2903): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
,E/AuthorizationBluetoothService( 2903): Proximity feature is not enabled.
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1242): MSG_NOTIFY_CS_TO_SYNC <<
,V/GLSActivity( 2903): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1225): No location to return for getLastLocation()
,W/FusedLocationProvider( 1225): location=null
D/PMS     (  905): acquireWL(42595518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  905): releaseWL(42595518): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024345
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024412
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024416
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024427
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024432
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025734
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025748
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028591
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3527 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,I/ActivityManager(  905): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3527): can't get weather sync account
,W/WeatherRequest( 3527): request cur loc, but there is no sys cur
,W/Settings( 3527): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 1 9 17
,D/PMS     (  905): releaseWL(4263e7c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3542 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  905): sending alarm PendingIntent{42328a78: PendingIntentRecord{424f0678 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54155, Int=0
,I/ActivityManager(  905): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3556 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3542): [918.1.] 30@-170931 -> 40@-171001
,D/Process (  905): killProcessQuiet, pid=3118
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3118:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3118
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3568 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3144
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3144:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3144
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DemoRecovery.RestoreReceiver( 3568): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3568): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/ActivityManager(  905): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3568): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3583 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3174
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3174:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3174
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): acquireWL(425e93d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3583 10071 null
,D/PMS     (  905): acquireWL(42676fb0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3583 10071 null
,D/PMS     (  905): releaseWL(425e93d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  905): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3583): update TASK shortcut>
,I/TodoTaskNotifyService( 3583): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3583): stopSelfResult true
D/PMS     (  905): releaseWL(42676fb0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  905): Resuming delayed broadcast
,I/ActivityManager(  905): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3598 uid=10082 gids={50082, 3003, 5012}
,D/Process (  905): killProcessQuiet, pid=3188
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3188:com.android.smith/u0a163 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3188
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  905): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3610 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  905): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3622 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3268
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/Process (  905): killProcessQuiet, pid=3205
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3268:com.android.vending/u0a74 (adj 15): empty #17
I/ActivityManager(  905): Killing 3205:com.google.android.youtube/u0a168 (adj 15): empty #18
,I/HtcModeClient( 1527): handler message = 4011
,E/HtcModeClient( 1527): Check connection and retry 5 times.
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  905): Client com.google.android.youtube (pid 3205): Died!
,I/ActivityManager(  905): Recipient 3205
,I/ActivityManager(  905): Recipient 3268
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3622): Database version: 95
,W/ContextImpl( 3622): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,D/MessagingNotification( 2758): New incoming message, can't cancel notification now
,D/MessagingNotification( 2758): newMsgCnt: 0, false
W/ContextImpl( 3622): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3622): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3622): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3622): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3622, uid=10154, userID:0
,D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/MediaRouterService(  905): Client com.google.android.music (pid 3622): Registered
,I/MediaRouter( 3622): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.music (3622/10154)
,I/NetworkMonitor( 3622): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2456/10021)
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  905): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3643 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,D/MediaRouter( 3622): getSelectedRoute
,I/NetworkMonitor( 3622): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3622/10154)
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3622, uid=10154, userID:0
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/PMS     (  905): acquireWL(4271be48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 905 1000 null
,D/Process (  905): killProcessQuiet, pid=3157
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3157:com.android.settings/1000 (adj 15): empty #17
D/PMS     (  905): releaseWL(4271be48): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  905): Recipient 3157
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 3643): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3643): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3643): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 3643): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3643): Preparing secondary program dexes.
V/DexLibLoader( 3643): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3643): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3643): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3643): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3643): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3643): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3643): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 3643): Dex already copied
D/OdexVerifier( 3643): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3643): Creating class loader
,V/DexLibLoader( 3643): Finished creating class loader
,V/DexLibLoader( 3643): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
V/DexLibLoader( 3643): Dex already copied
D/OdexVerifier( 3643): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3643): Creating class loader
,V/DexLibLoader( 3643): Finished creating class loader
,V/DexLibLoader( 3643): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
,V/DexLibLoader( 3643): Dex already copied
,D/OdexVerifier( 3643): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3643): Creating class loader
,V/DexLibLoader( 3643): Finished creating class loader
,V/DexLibLoader( 3643): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 3643): Dex already copied
D/OdexVerifier( 3643): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3643): Creating class loader
,V/DexLibLoader( 3643): Finished creating class loader
,V/DexLibLoader( 3643): Verifying classes from secondary dexes.
,D/DexLibLoader( 3643): DexLibLoader.ensureDexLoaded took 178 ms
,I/SensorManager(  905): mEventCount = 450
,D/WIFI_ICON( 1118): WifiActivity: 1
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  905): doString: SIGNAL_POLL
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative RSSI = -54 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  905): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  905): doBoolean: SignalStrength 97
,W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  905):    returned true
,W/dalvikvm( 3643): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3643): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3643): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3643): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3643): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3643): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3643): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/BluetoothManagerService(  905): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  905): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4234b8b8 mBinding = false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1318
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
,D/BluetoothManagerService(  905): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  905): Sending off request.
D/BluetoothAdapterState( 1631): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1631): Setting state to 13
I/BluetoothAdapterState( 1631): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1631): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 1631): onBluetoothDisable()
I/bt-btif ( 1631): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1631): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/BluetoothAdapterProperties( 1631): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 1631): BTM_SetDiscoverability
I/bt-btm  ( 1631): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1631): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1631): br_edr_supported=0x0
I/bt-btm  ( 1631): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1631): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1631): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1631): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1631): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1631): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1631): BTM_SetConnectability
I/bt-btm  ( 1631): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1631): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1631): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothAdapterProperties( 1631): Scan Mode:20
E/BTIF_CORE( 1631): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1631): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothAdapterState( 1631): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1631): BTA_JvDeleteRecord
I/bt-btif ( 1631): BTA_JvRfcommStopServer
D/bt-btm  ( 1631): BTM_FreeSCN 
I/bt-btif ( 1631): BTA_JvDeleteRecord
I/bt-btif ( 1631): BTA_JvRfcommStopServer
D/bt-btm  ( 1631): BTM_FreeSCN 
,I/bt-btif ( 1631): BTA_JvDeleteRecord
I/bt-btif ( 1631): BTA_JvRfcommStopServer
D/bt-btm  ( 1631): BTM_FreeSCN ,
I/bt-btif ( 1631): BTA_JvDeleteRecord
I/bt-btif ( 1631): BTA_JvRfcommStopServer
D/bt-btm  ( 1631): BTM_FreeSCN 
I/bt-btif ( 1631): BTA_JvDeleteRecord
I/bt-btif ( 1631): BTA_JvRfcommStopServer
D/bt-btm  ( 1631): BTM_FreeSCN 
I/bt-btif ( 1631): BTA_JvDeleteRecord
I/bt-btif ( 1631): BTA_JvRfcommStopServer
D/bt-btm  ( 1631): BTM_FreeSCN 
E/BtOppRfcommListener( 1631): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothSapService( 1631): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 1631): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1631): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:14
,E/bt-btif ( 1631): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1631): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1631): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1631): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1631): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1631): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1631): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1631): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1631): bta_jv_rfcomm_stop_server
,I/bt-btm  ( 1631): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1631): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1631): Write Extended Inquiry Response to controller
I/bt-btm  ( 1631): Write Extended Inquiry Response to controller
I/bt-btm  ( 1631): Write Extended Inquiry Response to controller
I/bt-btm  ( 1631): Write Extended Inquiry Response to controller
I/bt-btm  ( 1631): BTM_SetDiscoverability
I/bt-btm  ( 1631): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1631): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1631): br_edr_supported=0x0
I/bt-btm  ( 1631): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1631): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1631): btm_ble_update_adv_flag new=0x4
,D/bt-btm  ( 1631): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1631): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1631): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1631): BTM_SetConnectability
I/bt-btm  ( 1631): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1631): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1631): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1631): BTM_IsInquiryActive
I/bt-btm  ( 1631): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1631): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1631): BTM_FreeSCN 
I/bt-btm  ( 1631): BTM_SEC_CLR[3]: id 12
,D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1631): BTM_FreeSCN 
I/bt-btm  ( 1631): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1631): AVRC_Close handle:0
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1631): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1631): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1631): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1631): GATT_Deregister gatt_if=3
I/bt-att  ( 1631): GATT_Deregister gatt_if=4
D/BluetoothRemoteDevices( 1631): Wake lock Aquired
,D/PMS     (  905): acquireWL(4248db60): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1631 1002 null
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  905): Bluetooth State Change Intent: 12 -> 13
I/IntentController( 1118): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/WifiManager( 3283): setWifiEnabled: Base Package Name=com.example.hello, uid=10397
V/BluetoothPbapReceiver( 1631): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1631): ***********state = 13
,D/WifiStateMachine(  905): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  905): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  905): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  905): Settings:Agentvalue: 0
W/Settings:Agent(  905): >> traceCallingStack()
W/Settings:Agent(  905): Process.myPid(): 905
W/Settings:Agent(  905): Process.myTid(): 1103
W/Settings:Agent(  905): Process.myUid(): 1000
W/Settings:Agent(  905): 
W/Settings:Agent(  905): 
W/System.err(  905): java.lang.Throwable: stack dump
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  905): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  905): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  905): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  905): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  905): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  905): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  905): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  905): 
,W/Settings:Agent(  905): << traceCallingStack(): 1(ms)
D/PMS     (  905): acquireWL(4223d8c0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1225 10029 null
D/WifiService(  905): setWifiEnabled: false pid=3283, uid=10397
E/WifiService(  905): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  905): isSprintWifiRestricted(): false
I/WifiService(  905): isMdmWifiRestricted(): false
D/WifiSettingsStore(  905): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/WifiService(  905): New client listening to asynchronous messages
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1775): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ac9330
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1775): onDeInitialized
D/BluetoothMasReceiver( 1631): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1631): SapReceiver onReceive 
V/BluetoothSapReceiver( 1631): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1631):  Bluetooth Adapter state = 13
V/BluetoothSapReceiver( 1631): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED,
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1775): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1775): getNotificationManager
D/PMS     (  905): releaseWL(4223d8c0): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,I/ActivityManager(  905): Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=3659 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/BluetoothPbapService( 1631): Pbap Service closeService in
V/BluetoothPbapService( 1631): successfully stopped pbap service
V/BluetoothPbapService( 1631): Pbap Service closeService out
I/BtOppRfcommListener( 1631): stopping Accept Thread
I/BtOppRfcommListener( 1631): BluetoothSocket listen thread finished
V/BluetoothSapService( 1631): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1631): state: 13
D/BluetoothAdapter( 1631): 1101769560: getState(). Returning 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1775): init: null, null
V/BluetoothSapService( 1631): Stopping SAP server process
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1775):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1775): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1775): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1775): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1775):  + mTag.getPrimaryDeviceList() = []
V/BluetoothSapService( 1631): Sap Service closeSapService in
V/BluetoothSapService( 1631): Close listen Socket : 
V/BluetoothSapService( 1631): Close rfcomm Socket : 
V/BluetoothSapService( 1631): Close sapd  Socket : 
V/BluetoothSapReceiver( 1631): BluetoothSapReceiver deinit
V/BluetoothSapService( 1631): successfully stopped Sap service
V/BluetoothSapService( 1631): Sap Service closeSapService out
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1775): deinit: 0
I/jxcore-log( 3283): ****TEST TOOK:  5118  ms ****
I/jxcore-log( 3283): 
I/jxcore-log( 3283): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3283): 
D/BluetoothManagerService(  905): Message: MESSAGE_UNREGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1775): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1775): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1775): shutdownStateMachine
V/BluetoothPbapService( 1631): Pbap Service onDestroy
V/BluetoothPbapService( 1631): Pbap Service closeService in
V/BluetoothPbapService( 1631): Pbap Service closeService out
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1775): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1775): setPendingRequestAlarm: false, mContext = null, null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1775): Exit IdleState
D/BluetoothManagerService(  905): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41aabd40:true
V/BluetoothSapService( 1631): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41af4ad0
V/BluetoothSapService( 1631): Sap Service closeSapService in
V/BluetoothSapService( 1631): Close listen Socket : 
V/BluetoothSapService( 1631): Close rfcomm Socket : 
V/BluetoothSapService( 1631): Close sapd  Socket : 
D/WirelessDisplayService(  905): getMirrorDisplayStatus:falsecurState:1
D/WifiPerfLock(  905): release()
D/WifiStateMachine(  905): PerfLock released for exiting ConnectedState
V/BluetoothSapService( 1631): Sap Service closeSapService out
,V/BluetoothSapService( 1631): ***onDestroyed***
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/ConnectivityService(  905): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  905): acquireWL(41ab9cf0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 905 1000 null
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  905):    returned true
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/libc    (  905): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  905): stopDataStallAlarm: current tag=20264 mDataStallAlarmIntent=PendingIntent{42310940: PendingIntentRecord{42474620 android broadcastIntent}}
D/WifiP2pService(  905): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024345
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/libc    (  905): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  905): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  905): [RunningState] Stop DHCP
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  905):    returned null
E/WifiStateMachine(  905): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  905): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  905):    returned null
D/HtcFingerPrintQuickLaunchProvider( 3659): -onCreate()
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024412
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024416
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024427
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024432
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025734
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025748
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028591
D/WifiP2pService(  905): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/UsbnetStateTracker(  905): isAvailable+-
D/UsbnetStateTracker(  905): reconnect
D/UsbnetStateTracker(  905): isAvailable+-
D/WifiStateMachine(  905): Call handleNetworkDisconnect() in SupplicantStoppingState
,V/AudioService(  905): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  905):     Client/Owner: Client
V/AudioService(  905):     GroupId: 
V/AudioService(  905):     Passphrase: 
V/AudioService(  905):     SessionId: 0
V/AudioService(  905):     IP Address: }
D/HtcEffectManagerBase(  905): onEventChanged id=5 status=false
D/HtcEffectManager(  905): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
V/Settings:HtcSettingsApplication( 3659): [3659/3659] onCreate()
D/HtcEffectManager(  905): convertEffect before=902
D/HtcEffectManager(  905): convertEffect after=902
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  905): Provision feature enable=false
D/ConnectivityService(  905): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  905): P2pDisablingState
D/WifiDisplayController(  905): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  905): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  905): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  905): set wifi.miracastlock to 0 for disconnect case
I/WifiDisplayController(  905): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  905): updateConnection
I/WifiDisplayController(  905): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  905): updateConnection enter step 4
D/WifiDisplayAdapter(  905): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  905):     Client/Owner: Client
D/WifiDisplayAdapter(  905):     GroupId: 
D/WifiDisplayAdapter(  905):     Passphrase: 
D/WifiDisplayAdapter(  905):     SessionId: 0
D/WifiDisplayAdapter(  905):     IP Address: }
D/WifiP2pService(  905): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): p2p socket connection lost
D/WifiP2pService(  905): P2pDisabledState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/WifiP2pService(  905): P2pDisabledState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  905):  WFD CtrlPort: 0
D/WifiP2pService(  905):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  905):  WFD CtrlPort: 0
D/WifiP2pService(  905):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  905): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  905): default: reconnect()
D/MDST    (  905): default: setTeardownRequested(false)
D/MDST    (  905): default: setEnableApn apnType =default , enable=true
D/WifiDisplayController(  905): Failed to set WFD info with reason 2.
D/ConnectivityService(  905): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  905): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  905): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/WifiNative-wlan0(  905):    returned true
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  905): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  905): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  905):    returned true
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3659): >>>>>WISPrService start isConnected = false<<<<<
D/PMS     (  905): acquireWL(4243ac88): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3659 1000 null
W/ContextImpl( 3659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '26 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 26 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  905): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  905): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  905): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '27 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 27 Failed to remove route from default table (No such process)'
D/ConnectivityService(  905): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  905): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 29 Failed to remove route from default table (No such process)'
I/QuickSettingBluetooth( 1118): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
V/NativeCrypto( 2903): Read error: ssl=0x64efea10: I/O error during system call, Connection timed out
D/PhoneStatusBar( 1118): removeIcon slot=bluetooth index=12 viewIndex=0
D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/NativeCrypto( 2903): SSL shutdown failed: ssl=0x64efea10: I/O error during system call, Broken pipe
D/WISPrService( 3659): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425704b0:true
D/ConnectivityService(  905): handleConnectivityChange: resetting
D/ConnectivityService(  905): resetConnections(wlan0, 3)
D/PMS     (  905): releaseWL(4243ac88): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  905): acquireWL(426372f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 2903 10029 WorkSource{10029 com.google.android.gms}
D/WifiService(  905): New client listening to asynchronous messages
D/PMS     (  905): acquireWL(42577f70): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3659 1000 null
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3659): new LocationAgent instance!!
D/HtcTagManager( 3659): HtcTagManager construction complete
I/ActivityManager(  905): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3674 uid=10040 gids={50040, 3002, 3001}
D/ConnectivityService(  905): flush DNS cache for net 1(wlan0)
D/WifiNative-p2p0(  905): doBoolean: TERMINATE
D/libc    (  363): [NET] entry_id:3   entry:0xb8872860  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb8872320  removed 
D/libc    (  363): [NET] entry_id:5   entry:0xb8872738  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb8872428  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb88720e8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/WifiHW  (  905): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1184): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1184): TDLS: Tear down peers
I/wpa_supplicant( 1184): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiNative-p2p0(  905):    returned true
I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/BluetoothAdapter( 3659): 1101779208: getState(). Returning 13
I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/BluetoothInputDevice( 3659): BluetoothInputDevice()
D/BluetoothManagerService(  905): registerStateChangeCallback+
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024345
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024412
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024416
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024427
D/Nat464Xlat(  905): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  905): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024432
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025734
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025748
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028591
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 7
D/BluetoothAdapter( 3659): 1101779208: getState(). Returning 13
D/BluetoothInputDevice( 3659): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3659): Bluetooth service connected
W/BluetoothInputDevice( 3659): Proxy not attached to service
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=-29ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothPan( 3659): BluetoothPan()
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1118): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 8
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
D/ConnectivityService(  905): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/WIFI_ICON( 1118): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  905): acquireWL(4259a9b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 905 1000 null
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  905): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/BluetoothAdapter( 3659): 1101779208: getState(). Returning 13
D/BluetoothPan( 3659): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3659): Bluetooth service connected
D/BluetoothMap( 3659): Create BluetoothMap proxy object
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 9
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
E/BluetoothMap( 3659): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WirelessDisplayService(  905): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3659): BluetoothSap() call bindService
D/BluetoothManagerService(  905): Registered receivers: 10
D/ConnectivityService(  905): reportInetCondition for net -1, percentage: 0 by  (2903/10029)
D/WifiStateMachine(  905): startScan Pid: 905 Uid 1000
D/BluetoothPbap( 3659): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  905): Registered receivers: 11
D/BluetoothAdapter( 3659): 1101779208: getState(). Returning 13
D/BluetoothPbap( 3659): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3659): Bluetooth service connected
D/LocalBluetoothProfileManager( 3659): LocalBluetoothProfileManager construction complete
W/ContextImpl( 3659): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
D/PMS     (  905): releaseWL(426372f8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1184): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1184): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  905): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  905): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/wpa_supplicant( 1184): TDLS: Remove peers on disassociation
D/HTCRequest(  905): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  905): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  905): WifiMonitor:getReasonFromEventString() 3
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/HTCRequest(  905): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb8edabc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1184): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1184): State: COMPLETED -> DISCONNECTED
D/HTCRequest(  905): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/HTCRequest(  905): WifiMonitor:getFreqFromEventString() 2412
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  905): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/HTCRequ,est(  905): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  905): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  905): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1184): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  905): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/DockEventReceiver( 3659): finishStartingService: stopping service
D/HtcBtWidget_BTWidgetProvider( 3674): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 3674): updateWidget(context) for widget: 
D/WISPrService( 3659): >>>>>WISPrService start isConnected = false<<<<<
D/Process (  905): killProcessQuiet, pid=3410
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/WISPrService( 3659): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  905): [MLHD] enter handleMediaLinkEvent DefaultState
,E/WifiStateMachine(  905): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:0
D/PMS     (  905): releaseWL(42577f70): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
I/ActivityManager(  905): Killing 3410:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/ConnectivityService(  905): mActiveDefaultNetwork: -1
D/ConnectivityService(  905): handleInetConditionChange: no active default network - ignore
,I/QuickSettingWifi( 1118): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,W/bt-btif ( 1631): ag scb idx 1 not allocated
,W/bt-btif ( 1631): ag scb idx 2 not allocated
E/bt-btif ( 1631): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1631): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1631): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1631): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1631): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1631): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1631): L2CAP - PSM: 0x0017 not found for deregistration
,E/bt_userial_mct( 1631): userial_close userial_thread_created userial_running is 1 
,I/ActivityManager(  905): Recipient 3410
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(4259a9b8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/Process (  905): killProcessQuiet, pid=3451
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,E/BluetoothFtpService:RfcommSocketAcceptThread( 1631): Shutdown
,I/ActivityManager(  905): Killing 3451:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,D/BluetoothMasReceiver( 1631): Bluetooth STATE CHANGED to 13
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1775): Received state change = 13
,E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1775): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ac9330
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): onDestroy() called...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1775): deinitLeServices: null
I/ActivityManager(  905): Recipient 3451
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 3643): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WifiService(  905): New client listening to asynchronous messages
,D/Process (  905): killProcessQuiet, pid=3463
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 2903): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  905): Killing 3463:com.htc.contacts/u0a44 (adj 15): empty #17
,E/wpa_supplicant( 1184): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1184): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 1184): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  905): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,W/dalvikvm( 3643): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/cutils-trace( 3686): Error opening trace file: No such file or directory (2)
,I/ActivityManager(  905): Recipient 3463
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/wpa_supplicant( 1184): netlink: Operstate: linkmode=0, operstate=6,
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1184): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1184): nl80211: Unsubscribe mgmt frames handle 0xb8edb718 (mode change)
I/wpa_supplicant( 1184): htc_wext_command_deinit +
I/wpa_supplicant( 1184): htc_wext_command_deinit -
,E/wpa_supplicant( 1184): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1184): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1184): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1184): TDLS: Tear down peers
I/wpa_supplicant( 1184): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/Tethering(  905): interfaceLinkStateChanged wlan0, false
,D/Tethering(  905): interfaceStatusChanged wlan0, false
D/Tethering(  905): [isWifi] getHotspotEnabled: false
,E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,E/FbInjectorInitializer( 3643): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  905): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
,I/wpa_ctrl(  905): [wpa_ctrl_close] ctrl=0x621ab530
,I/wpa_ctrl(  905): [wpa_ctrl_close] ctrl=0x621ab158
W/WifiHW  (  905): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  905): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
D/WifiStateMachine(  905): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  905): doBoolean: SET_WIFI_ON 0
D/WifiNative-wlan0(  905):    returned false
,D/WifiStateMachine(  905): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  905): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/WirelessDisplayService(  905): WIFI Trun OFF
,D/WirelessDisplayService(  905): getDiscoveryDongleList
,D/CustomizationManager( 3686): ====startRecUseTime====
D/htc.customization.log.level( 3686):  is 
,W/CustomizationLogLevel( 3686): Level value is invalid, use default level 2
,I/IntentController( 1118): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiStateMachine(  905): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  905): Exit handleNetworkDisconnect
D/WIFI_ICON( 1118): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiDataStallTracker(  905): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  905): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,E/WifiStateMachine(  905): [MLHD] Error! unhandled message 6 { when=-114ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,W/Settings( 1225): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/IntentController( 1118): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PMS     (  905): acquireWL(4267ef20): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 905 1000 null
D/WifiStateTracker(  905): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1118): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1118): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3659): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3659): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/bt-btif ( 1631): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1631): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1631): Received stop request...Stopping profile...
D/BluetoothHeadset( 1242): Proxy object disconnected
D/BluetoothPhoneService( 1242): BluetoothHeadset onServiceDisconnected
,D/BluetoothHeadset( 1242): Proxy object disconnected
D/BluetoothHeadset(  905): Proxy object disconnected
,D/BluetoothHeadset( 1118): Proxy object disconnected
,I/QuickSettingMiniLite( 1118): btListener.disconnect:HEADSET
D/A2dpService( 1631): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1631): doQuit
D/A2dpStateMachine( 1631): Exit Disconnected: -1
,W/fb4a(:<default>):StaticBindingVerifier( 3643): Verify
D/BluetoothAdapterState( 1631): Stopping profile services that were post enabled
D/BluetoothA2dp(  905): Proxy object disconnected
,D/HidService( 1631): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1631): Profile still running: com.android.bluetooth.hdp.HealthService
,D/HealthService( 1631): Received stop request...Stopping profile...
,W/BluetoothHeadsetServiceJni( 1631): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1631): Cleaning up Bluetooth Handsfree callback object
,D/PanService( 1631): Received stop request...Stopping profile...
D/PanService( 1631): stop
,D/PanService( 1631): stop: mTetherAc send disconnect
,D/BluetoothTethering(  905): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  905): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  905): attempted to stop reverse tether with nothing tethered
,I/QuickSettingWifi( 1118): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,D/BluetoothPan(  905): BluetoothPAN Proxy object disconnected
,D/BtGatt.DebugUtils( 1631): handleDebugAction() action=null
D/BtGatt.GattService( 1631): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1631): stop()
D/BluetoothAdapterService( 1631): Profile still running: com.android.bluetooth.hdp.HealthService
,D/A2dpStateMachine( 1631): cleanup
,D/Avrcp   ( 1631): Unregistering previous receiver
D/BluetoothAdapterService( 1631): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1631): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1631): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1631): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1631): Profile still running: com.android.bluetooth.pan.PanService
,W/BluetoothHealthServiceJni( 1631): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1631): Cleaning up Bluetooth Health object
D/PanService( 1631): CMD_CHANNEL_DISCONNECTED
,D/PanService( 1631): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1631): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1631): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1631): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1631): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1631): Setting state to 10
I/BluetoothAdapterState( 1631): Bluetooth adapter state changed: 13-> 10
,D/BluetoothAdapterService( 1631): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  905): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  905): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
I/BluetoothAdapterState( 1631): Entering OffState
D/BluetoothManagerService(  905): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  905): Broadcasting onBluetoothStateChange(false) to 11 receivers.
,D/BluetoothSap( 3659): onBluetoothStateChange on: false
,D/BluetoothHeadset( 1242): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1118): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1242): onBluetoothStateChange: up=false
,I/QuickSettingWifi( 1118): receive.wifiConnect:false wifiAPname:null elapse:1
,D/BluetoothPbap( 3659): onBluetoothStateChange: up=false
,E/BluetoothPbap( 3659): 
E/BluetoothPbap( 3659): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41ad4260
E/BluetoothPbap( 3659): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3659): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3659): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3659): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3659): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3659): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3659): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothInputDevice( 3659): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 3659): 
E/BluetoothInputDevice( 3659): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41acaf50
E/BluetoothInputDevice( 3659): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3659): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3659): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3659): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3659): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3659): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3659): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset(  905): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  905): onBluetoothStateChange: up=false
,D/BluetoothMap( 3659): onBluetoothStateChange: up=false
E/BluetoothMap( 3659): 
E/BluetoothMap( 3659): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41ace148
E/BluetoothMap( 3659): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3659): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3659): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3659): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3659): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3659): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3659): 	at dalvik.system.NativeStart.run(Native Method)
E/BluetoothPan( 3659): 
E/BluetoothPan( 3659): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41accdc8
E/BluetoothPan( 3659): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3659): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3659): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3659): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3659): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3659): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3659): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  905): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  905): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 1631): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41ab8fc8
D/BluetoothDevice( 1631): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1631): onBluetoothServiceDown: done
D/BluetoothAdapter( 1118): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ea3900
D/BluetoothAdapter( 1118): onBluetoothServiceDown: done
D/BluetoothAdapter( 1242): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d479e8
D/BluetoothAdapter( 1242): onBluetoothServiceDown: done
D/BluetoothAdapter(  905): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4234b8b8
,D/BluetoothAdapter(  905): onBluetoothServiceDown: done
D/BluetoothAdapter( 3659): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41abdb70
D/BluetoothAdapter( 3659): onBluetoothServiceDown: done
D/BluetoothAdapter( 3283): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41abd8b8
,D/BluetoothAdapter( 3283): onBluetoothServiceDown: done
D/BluetoothAdapter( 1225): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41de4538
,D/BluetoothAdapter( 1225): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1256): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b75ba8
,D/BluetoothAdapter( 1256): onBluetoothServiceDown: done
D/BluetoothAdapter( 1775): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ac9c00
D/BluetoothAdapter( 1775): onBluetoothServiceDown: done
,D/BluetoothManagerService(  905): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4234b8b8 mBinding = false
,D/BluetoothManagerService(  905): Sending unbind request.
,D/BluetoothAdapterService( 1631): Cleaning up adapter native....
,D/BluetoothManagerService(  905): Bluetooth State Change Intent: 13 -> 10
,I/bt-btif ( 1631): HAL bt_hal_cbacks->thread_evt_cb
,I/IntentController( 1118): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/LocalBluetoothProfileManager( 3659): setBluetoothStateOff
D/HtcTagManager( 3659): stopProxy
,W/BluetoothEventManager( 3659): unregister mProfileBroadcastReceiver fail
,D/PMS     (  905): releaseWL(4248db60): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/NfcHandover( 1256): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/BluetoothAdapter( 1225): 1105054960: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1225): 1105054960: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapterService( 1631): Done cleaning up adapter native....
,D/BluetoothAdapterService(1101751384)( 1631): ****onDestroy()********
,D/TetherPref( 3659): persistRestoreBluetoothState false
,D/BtGatt.GattService( 1631): cleanup()
,W/bt-btif ( 1631): GATTC Module not enabled/already disabled
W/bt-btif ( 1631): GATTS Module not enabled/already disabled
D/PMS     (  905): acquireWL(4229bfb8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1225 10029 null
D/PMS     (  905): releaseWL(4229bfb8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/PMS     (  905): acquireWL(425716a8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3659 1000 null
,W/ContextImpl( 3659): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/BluetoothMasReceiver( 1631): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 1631): onDestroy: mIsEmailEnabled: true
,D/HtcBtWidget_BTWidgetProvider( 3674): onBTStateChanged() for widget: 
,D/DockEventReceiver( 3659): finishStartingService: stopping service
,D/HtcBtWidget_BTWidgetProvider( 3674): updateWidget(context) for widget: 
D/PMS     (  905): releaseWL(425716a8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  905): acquireWL(425cee60): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3659 1000 null
D/PMS     (  905): releaseWL(425cee60): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 1631): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1775): Received state change = 10
,D/CustomizationManager( 3686):  Read ACC file spent 0.076 (s)
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 3686): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__032
,D/CIDMapFileReader( 3686): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3686): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3686): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3686): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3686): Parsing tag category name = system
,I/CustomizationCIDLoader( 3686): Parsing tag category name = application
,I/CustomizationCIDLoader( 3686): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3686): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 3686): Parsing tag category name = AudioService
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  905): java.lang.Throwable: stack dump
D/BluetoothManagerService(  905): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42423d58:true
W/System.err(  905): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  905): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  905): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  905): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  905): 	at dalvik.system.NativeStart.run(Native Method)
I/CustomizationCIDLoader( 3686): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3686): Parsing tag category name = Settings
I/LocationAgent( 3132): new LocationAgent instance!!
,D/CustomizationManager( 3686):  Read CID file spent 0.128 (s)
,D/CustomizationManager( 3686):  All configurations done spent 0.128 (s)
,D/HtcTagManager( 3132): HtcTagManager construction complete
,D/BluetoothAdapter( 3132): 1101859920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3132): BluetoothInputDevice()
W/HtcNativeFlag( 3686): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3686): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3686): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3686): Fail to get flag for type 'language', use default value: -1
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3132): 1101859920: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 3132): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3132): Bluetooth service connected
,W/BluetoothInputDevice( 3132): Proxy not attached to service
D/BluetoothPan( 3132): BluetoothPan()
D/BluetoothManagerService(  905): Registered receivers: 12
,D/BluetoothAdapter( 1118): 1104599872: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3132): 1101859920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3132): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3132): Bluetooth service connected
,D/BluetoothManagerService(  905): Registered receivers: 13
D/BluetoothMap( 3132): Create BluetoothMap proxy object
I/QuickSettingBluetooth( 1118): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  905): Registered receivers: 14
,E/BluetoothMap( 3132): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
W/BluetoothHeadset( 1118): Proxy not attached to service
,I/QuickSettingMiniLite( 1118): updateLiteState:no connect device!
D/BluetoothManagerService(  905): registerStateChangeCallback+
D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothSap( 3132): BluetoothSap() call bindService
,D/BluetoothManagerService(  905): Registered receivers: 15
,D/BluetoothPbap( 3132): BluetoothPbap()
D/BluetoothManagerService(  905): registerStateChangeCallback+
,D/BluetoothManagerService(  905): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3132): 1101859920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3132): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3132): Bluetooth service connected
D/LocalBluetoothProfileManager( 3132): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3132): 1101859920: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3132): 1101859920: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3132): setBluetoothStateOff
D/HtcTagManager( 3132): stopProxy
W/BluetoothEventManager( 3132): unregister mProfileBroadcastReceiver fail
,D/BluetoothManagerService(  905): Registered receivers: 16
W/ContextImpl( 3132): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/Process (  905): killProcessQuiet, pid=3478
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 2903): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  905): Killing 3478:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3478
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageManager(  905): deletePackageAsUser: pkg=com.example.hello, pid=3686, uid=2000 user=0
,D/WifiService(  905): New client listening to asynchronous messages
,I/ActivityManager(  905): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
,D/Process (  905): killProcessQuiet, pid=3283
,W/asset   (  905): Copying FileAsset 0x63daaac0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  905): Killing 3283:com.example.hello/u0a397 (adj 0): stop com.example.hello
W/ActivityManager(  905): Force removing ActivityRecord{422a0550 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  905): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  905): Skipping PackageSetting{42166140 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  905): Force stopping com.example.hello appid=10397 user=0: pkg removed
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3643/10027)
,W/InputDispatcher(  905): channel '422affb0 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  905): channel '422affb0 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  905): Attempted to unregister already unregistered input channel '422affb0 com.example.hello.MainActivity (s)'
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowManager(  905): WINDOW DIED Window{422affb0 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  905): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1118): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1569): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1569): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/WindowManager(  905): Failed looking up window
W/WindowManager(  905): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@41accb68 does not exist
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  905): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  905): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  905): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  905): 	at dalvik.system.NativeStart.run(Native Method)
,I/FeedHostManager( 1273): [onResume]
,I/FeedProviderManager( 1273): onResume
I/SocialFeedProvider( 1273): +onResume
I/SocialFeedProvider( 1273): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1273): -onResume
,I/ConnectivityHelper( 1273): [getCurrentConnectionType] no network connection
,W/fb4a(:<default>):BaseAnalyticsConfig( 3643): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
D/AccTypeManager( 1342): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/fb4a(:<default>):BaseAnalyticsConfig( 3643): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/GeofencerStateMachine( 1225): Ignoring removeGeofence because network location is disabled.
I/WindowState(  905): WIN DEATH: null
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.launcher (1273/10076)
D/PMS     (  905): acquireWL(427efac8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "sms"
D/PMS     (  905): releaseWL(427efac8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/SystemReader( 1256): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "smsto"
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
W/AccTypeManager( 1342): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1342): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 9.510MB for 73240-byte allocation
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/ActivityManager(  905): Waited long enough for: ServiceRecord{4266ddf8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/Process (  905): killProcessQuiet, pid=3493
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/SocialFeedProvider( 1273): +disConnect socialManager
I/SocialFeedProvider( 1273): disconnect socialManager
I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  905):   Scheme: "sms"
I/ActivityManager(  905): Killing 3493:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/SocialFeedProvider( 1273): -disConnect socialManager
,I/ActivityManager(  905): Recipient 3493
,E/ExternalAccountType( 1342): Unsupported attribute readOnly
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "smsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
I/InputMethodManagerService(  905): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mms"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
W/InputMethodManagerService(  905): Got RemoteException sending setActive(false) notification to pid 3283 uid 10397
,I/InputMethodManagerService(  905): Enable input method client, pid=1273
W/Binder  ( 1212): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1212): java.lang.NullPointerException
W/Binder  ( 1212): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1212): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1212): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1212): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager(  905):   Action: "android.intent.action.SENDTO"
I/PackageManager(  905):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  905):   Scheme: "mmsto"
I/PackageManager(  905): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1242 :
,D/PhoneApp( 1242): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,V/Tethering(  905): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  905): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,D/AutoSetting( 1319): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.backuptransport (1581/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2152/10029)
D/Tethering(  905): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
V/Tethering(  905): bSetPropertyMultiRAB:false
D/Tethering(  905): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  905): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  905): ipv4Default null
I/Tethering(  905): No IPv4 upstream interface, giving up.
D/Tethering(  905): TetherMasterSM: InitialState processMessage what=3
,I/ActivityManager(  905): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3722 uid=10079 gids={50079, 3003, 5012}
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.google.android.music (3622/10154)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2152/10029)
,I/NetworkMonitor( 3622): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (2152/10029)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
,D/AutoSetting( 1319): Util - no network available!
,D/AutoSetting( 1319): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
,D/AutoSetting( 1319): service - mHandler: cancel location update
,D/AutoSetting( 1319): service -           changes count: 0
D/ConnectivityService(  905): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10076)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.htc.sense.hsp (1319/10055)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.gms (1225/10029)
,W/fb4a(:<default>):UserScope( 3643): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3643): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 3643): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3643): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/MobileConnectivityChangeReceiver( 3722): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3722): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3722): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3722): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  905): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3740 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3507
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3507:com.htc.calendar/u0a13 (adj 15): empty #17
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3722/10079)
I/ActivityManager(  905): Recipient 3507
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3722/10079)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.setupwizard (3722/10079)
E/dalvikvm( 3643): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 3643): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3643): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 3643): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3643): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 3643): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3643): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 3643): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3643): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3643): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 3643): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3643): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3643): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3643): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3643): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3643): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3643): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3643): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 9.921MB for 39954-byte allocation
,I/ActivityManager(  905): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3755 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
D/Process (  905): killProcessQuiet, pid=3527
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3527:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,W/PackageManager(  905): Unable to load service info ResolveInfo{425ac720 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  905): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  905): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  905): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  905): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  905): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  905): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  905): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  905): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  905): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  905): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  905): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  905): 	at dalvik.system.NativeStart.main(Native Method)
I/ActivityManager(  905): Recipient 3527
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 9.998MB for 79892-byte allocation
,W/Netd    (  363): No subsystem found in netlink event
,V/Tethering(  905): remove iface:wlan0
D/Tethering(  905): interfaceRemoved wlan0
,E/Tethering(  905): attempting to remove unknown iface (wlan0), ignoring
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 10.068MB for 84664-byte allocation
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/GAV2    ( 3755): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 3755): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3755): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3755): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3755): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 10.095MB for 28144-byte allocation
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3755/10151)
,V/WebViewChromiumFactoryProvider( 3755): Binding Chromium to main looper Looper (main, tid 1) {41aa5498}
,I/LibraryLoader( 3755): Expected native library version number "",actual native library version number ""
,I/chromium( 3755): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3755): Initializing chromium process, renderers=0
,E/NSDepend( 3755): Could not load library: pdflib.dex.jar
E/NSDepend( 3755): java.io.FileNotFoundException: /data/data/com.google.android.apps.magazines/app_dex/pdflib.dex.jar: open failed: EROFS (Read-only file system)
E/NSDepend( 3755): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/NSDepend( 3755): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/NSDepend( 3755): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:217)
E/NSDepend( 3755): 	at com.google.common.io.Files$FileByteSink.openStream(Files.java:205)
E/NSDepend( 3755): 	at com.google.common.io.ByteSink.writeFrom(ByteSink.java:112)
E/NSDepend( 3755): 	at com.google.apps.dots.android.newsstand.NSDepend.dynamicallyLoadLibrary(NSDepend.java:971)
E/NSDepend( 3755): 	at com.google.apps.dots.android.newsstand.NSDepend.getClassLoaderForJar(NSDepend.java:918)
E/NSDepend( 3755): 	at com.google.apps.dots.android.newsstand.NSDepend$1.doInBackground(NSDepend.java:951)
E/NSDepend( 3755): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:56)
E/NSDepend( 3755): 	at com.google.apps.dots.android.newsstand.async.QueueTask$1.call(QueueTask.java:52)
E/NSDepend( 3755): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/NSDepend( 3755): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/NSDepend( 3755): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/NSDepend( 3755): 	at com.google.apps.dots.android.newsstand.async.Queue$3$1.run(Queue.java:162)
E/NSDepend( 3755): 	at java.lang.Thread.run(Thread.java:864)
E/NSDepend( 3755): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/NSDepend( 3755): 	at libcore.io.Posix.open(Native Method)
E/NSDepend( 3755): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/NSDepend( 3755): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/NSDepend( 3755): 	... 14 more
,D/Process (  905): killProcessQuiet, pid=3542
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  905): Killing 3542:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
E/AudioManagerAndroid( 3755): BLUETOOTH permission is missing!
,I/dalvikvm-heap( 3643): Grow heap (frag case) to 10.282MB for 75760-byte allocation
I/ActivityManager(  905): Recipient 3542
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Adreno-EGL( 3755): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3755): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3755): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3755): Local Branch: 
I/Adreno-EGL( 3755): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3755): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3755):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3643/10027)
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425ef730 u0 ReceiverList{425ef610 3643 com.facebook.katana/10027/u0 remote:42776300}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{425ef730 u0 ReceiverList{425ef610 3643 com.facebook.katana/10027/u0 remote:42776300}}
W/BroadcastQueue(  905): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42643450 u0 ReceiverList{426433f0 3643 com.facebook.katana/10027/u0 remote:4261b1e0}}
,E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3643/10027)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3643/10027)
,I/NSApplication( 3755): Starting up...
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.facebook.katana (3643/10027)
D/Tethering(  905): interfaceLinkStateChanged p2p0, false
D/Tethering(  905): interfaceStatusChanged p2p0, false
,D/Tethering(  905): [isWifi] getHotspotEnabled: false
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3755/10151)
,D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.magazines (3755/10151)
E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,I/ActivityManager(  905): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3792 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  905): killProcessQuiet, pid=3556
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  905): Killing 3556:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 3556
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,D/PMS     (  905): acquireWL(42740658): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1225 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  905): releaseWL(42740658): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
D/RemoteDisplayProvider(  905): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  905): start
I/AlarmManager(  905): [AlarmQueuing] connectivity wifi: false
,D/CaptivePortalTracker(  905): DelayedCaptiveCheckState
D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  905): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  905): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  905): NoActiveNetworkState
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (905/1000)
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024099
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024345
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024412
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024416
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024427
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360024432
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025734
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360025748
W/AlarmManager(  905): Converted elapesd time is over 1 year! when = 315360028591
,D/ConnectivityService(  905): getNetworkInfo networkType=1 called by  (905/1000)
,W/AtomicFile(  905): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  905): [handleMessage] UPDATE_NETWORK_STATE
,D/GpsLocationProvider(  905): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  905): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  905): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  905): acquireWL(425f0228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 905 1000 null
W/AppWidgetServiceImpl(  905): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  905): releaseWL(425f0228): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,W/Netd    (  363): No subsystem found in netlink event
,V/Tethering(  905): remove iface:p2p0
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
D/Tethering(  905): interfaceRemoved p2p0
,E/Tethering(  905): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3643): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3643): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,D/PMS     (  905): acquireWL(425bc610): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  905): acquireWL(425bcc80): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,E/SQLiteDatabase( 3792): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3792): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3792): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3792): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3792): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 3792): 	at del.a(PG:264)
E/SQLiteDatabase( 3792): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3792): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteDatabase( 3792): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3792): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3792): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3792): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3792): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3792): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 3792): 	at del.a(PG:264)
E/SQLiteDatabase( 3792): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3792): 	at java.lang.Thread.run(Thread.java:864)
,E/EsApplication( 3792): Failed app initialization
E/EsApplication( 3792): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 3792): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 3792): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 3792): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 3792): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 3792): 	at del.a(PG:264)
E/EsApplication( 3792): 	at eeq.run(PG:187)
E/EsApplication( 3792): 	at java.lang.Thread.run(Thread.java:864)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3792/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3792/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3792/10160)
D/ConnectivityService(  905): getActiveNetworkInfo called by com.google.android.apps.plus (3792/10160)
E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
,I/PackageManager(  905):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2152, uid=10029, userID:0
I/iu.SyncManager( 2152): SYNC; picasa accounts
E/SQLiteLog( 3643): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 3643): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.facebook.katana/databases/prefs_db, handle = 0x64237830
I/ActivityManager(  905): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3816 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
V/AlarmManager(  905): sending alarm PendingIntent{424ea6f8: PendingIntentRecord{426082c8 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452528605789, Int=0
E/SQLiteDatabase( 2152): Failed to open database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite'.
E/SQLiteDatabase( 2152): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2152): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.networkcapability.impl.f.<init>(SourceFile:27)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.networkcapability.impl.d.<init>(SourceFile:52)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:25)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.networkcapability.impl.b.<init>(SourceFile:34)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:23)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.b(SourceFile:121)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.a(SourceFile:43)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.<init>(SourceFile:73)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:53)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver.onReceive(SourceFile:212)
E/SQLiteDatabase( 2152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 2152): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 2152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 2152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2152): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2152): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 2152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 2152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 2152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 2152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 2152): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 2152): threadid=1: thread exiting with uncaught exception (group=0x41672e30)
,E/AndroidRuntime( 2152): FATAL EXCEPTION: main
E/AndroidRuntime( 2152): Process: com.google.android.gms, PID: 2152
E/AndroidRuntime( 2152): java.lang.RuntimeException: Unable to start receiver com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2152): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2152): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2152): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2152): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2152): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2152): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2152): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2152): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2152): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2152): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2152): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2152): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 2152): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 2152): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 2152): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.networkcapability.impl.f.<init>(SourceFile:27)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.networkcapability.impl.d.<init>(SourceFile:52)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:25)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.networkcapability.impl.b.<init>(SourceFile:34)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:23)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.b(SourceFile:121)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.a(SourceFile:43)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.<init>(SourceFile:73)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:53)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2152): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver.onReceive(Source
E/ActivityManager(  905): App crashed! Process: com.google.android.gms
D/Process (  905): killProcessQuiet, pid=3568
D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
W/dalvikvm( 3643): threadid=20: thread exiting with uncaught exception (group=0x41672e30)
E/ACRA    ( 3643): ACRA caught a SQLiteDiskIOException exception for com.facebook.katana. Building report.
I/ActivityManager(  905): Killing 3568:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
E/fb4a(:<default>):ACRA( 3643): Handling exception for crash
E/fb4a(:<default>):ACRA( 3643): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/fb4a(:<default>):ACRA( 3643): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/fb4a(:<default>):ACRA( 3643): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/fb4a(:<default>):ACRA( 3643): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/fb4a(:<default>):ACRA( 3643): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/fb4a(:<default>):ACRA( 3643): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/fb4a(:<default>):ACRA( 3643): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.prefs.shared.FbSharedPreferencesDB$PreferenceDbTransaction.c(FbSharedPreferencesDB.java:229)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.prefs.shared.FbSharedPreferencesDB.a(FbSharedPreferencesDB.java:125)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.prefs.shared.FbSharedPreferencesContentProvider.a(FbSharedPreferencesContentProvider.java:59)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.content.AbstractContentProvider.applyBatch(AbstractContentProvider.java:270)
E/fb4a(:<default>):ACRA( 3643): 	at android.content.ContentProvider$Transport.applyBatch(ContentProvider.java:272)
E/fb4a(:<default>):ACRA( 3643): 	at android.content.ContentProviderClient.applyBatch(ContentProviderClient.java:377)
E/fb4a(:<default>):ACRA( 3643): 	at android.content.ContentResolver.applyBatch(ContentResolver.java:1250)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.a(FbSharedPreferencesImpl.java:886)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.i(FbSharedPreferencesImpl.java:771)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl.c(FbSharedPreferencesImpl.java:89)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.prefs.shared.FbSharedPreferencesImpl$4.run(FbSharedPreferencesImpl.java:746)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.common.executors.SerialExecutorServiceImpl$Worker.run(SerialExecutorServiceImpl.java:59)
E/fb4a(:<default>):ACRA( 3643): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/fb4a(:<default>):ACRA( 3643): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/fb4a(:<default>):ACRA( 3643): 	at com.facebook.common.executors.NamedThreadFactory$1.run(NamedThreadFactory.java:44)
E/fb4a(:<default>):ACRA( 3643): 	at java.lang.Thread.run(Thread.java:864)
D/ACRA    ( 3643): Generating report file for crash
E/DropBoxManagerService(  905): Can't write: system_app_crash
E/DropBoxManagerService(  905): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  905): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  905): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  905): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  905): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  905): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  905): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  905): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  905): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  905): 	... 5 more
I/ActivityManager(  905): Recipient 3568
I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ACRA    ( 3643): An error occurred while creating the report file ...
E/ACRA    ( 3643): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_acra-reports/1452528605842-SQLiteDiskIOException-1698515.temp_stacktrace: open failed: EROFS (Read-only file system)
E/ACRA    ( 3643): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ACRA    ( 3643): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
E/ACRA    ( 3643): 	at org.acra.ErrorReporter.handleExceptionInternal(ErrorReporter.java:1249)
E/ACRA    ( 3643): 	at org.acra.ErrorReporter.handleException(ErrorReporter.java:1167)
E/ACRA    ( 3643): 	at org.acra.ErrorReporter.handleException(ErrorReporter.java:1152)
E/ACRA    ( 3643): 	at org.acra.ErrorReporter.uncaughtException(ErrorReporter.java:999)
E/ACRA    ( 3643): 	at com.facebook.common.errorreporting.memory.MemoryDumpHandler.uncaughtException(MemoryDumpHandler.java:113)
E/ACRA    ( 3643): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
E/ACRA    ( 3643): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
E/ACRA    ( 3643): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ACRA    ( 3643): 	at libcore.io.Posix.open(Native Method)
E/ACRA    ( 3643): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ACRA    ( 3643): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ACRA    ( 3643): 	... 8 more
,I/ImageRamCache( 3816): create image Cache, size: 31457280.
I/ImageRamCache( 3816): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 3816): create image Cache, size: 12582912.
I/FeedSettings( 3816): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3816): GroupBudget 0.500000 0.380000
I/FeedSettings( 3816): GroupBudget 60 45 15
I/ActivityManager(  905): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3831 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
I/Prism.ExternalStringMa_( 3816): changeLocale(): en_GB
D/ConnectivityService(  905): getActiveNetworkInfo called by  (2903/10029)
I/Prism.AllAppsOptionsMa_( 3816): loadSortType() with Custom
I/Prism.AllAppsOptionsMa_( 3816): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 3816): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3816): last commit ulog time 1452509393704
,I/SocialManager[SocialBiLogHelper]( 3816): skip commit this time
,D/Process (  905): killProcessQuiet, pid=2758
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 2758:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  905): Recipient 2758
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/CalendarApplication( 3831): onCreate
,D/AlertReceiver( 3831): beginStartingService
,D/Process (  905): killProcessQuiet, pid=3583
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  905): Killing 3583:com.htc.task/u0a71 (adj 15): empty #17
D/PMS     (  905): acquireWL(42789398): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3831 10013 null
,I/ActivityManager(  905): Recipient 3583
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  905): releaseWL(425bc610): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  905): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=3851 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,W/WeatherRequest( 1118): request cur loc, but there is no sys cur
,D/AlertService( 3831): start to updateAlertNotification!
,D/AlertService( 3831): No fired or scheduled alerts
,D/HtcAlertUtils( 3831): -- cancelReminderNotification --
,W/Settings( 3643): Setting data_roaming_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
D/HtcAlertUtils( 3831): broadcastExistReminder!
,W/Settings( 3643): Setting data_roaming_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3643): Setting data_roaming_guard_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/Settings( 3643): Setting data_roaming_guard_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/AlertReceiver( 3831): stopSelfResult true
D/PMS     (  905): releaseWL(42789398): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  905): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3867 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3851): can't get weather sync account
,W/WeatherRequest( 3851): request cur loc, but there is no sys cur
,W/Settings( 3851): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
,D/PMS     (  905): acquireWL(42766020): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3867 10071 null
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 1 11 17
D/PMS     (  905): acquireWL(42766b68): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3867 10071 null
,D/PMS     (  905): releaseWL(42766020): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/Settings( 3643): Setting sms_roaming_guard_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,E/SQLiteDatabase( 3867): Failed to open database '/data/data/com.htc.task/databases/MyDB.db'.
E/SQLiteDatabase( 3867): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3867): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3867): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3867): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3867): 	at com.htc.task.dm.DBProvider.query(DBProvider.java:505)
E/SQLiteDatabase( 3867): 	at com.htc.task.APICProviderDecorator.query(APICProviderDecorator.java:348)
E/SQLiteDatabase( 3867): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3867): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3867): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 3867): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 3867): 	at com.htc.shared.orm.Query.fetch(Query.java:415)
E/SQLiteDatabase( 3867): 	at com.htc.task.util.QueryHelper.fetch(QueryHelper.java:133)
E/SQLiteDatabase( 3867): 	at com.htc.task.util.QueryHelper.fetch(QueryHelper.java:160)
E/SQLiteDatabase( 3867): 	at com.htc.task.notification.AlarmSchedule.rescheduleMissedAlarms(AlarmSchedule.java:87)
E/SQLiteDatabase( 3867): 	at com.htc.task.notification.NotifyService.doTimeChanged(NotifyService.java:831)
E/SQLiteDatabase( 3867): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:164)
E/SQLiteDatabase( 3867): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
E/SQLiteDatabase( 3867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3867): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3867): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3867): Couldn't open MyDB.db for writing (will try read-only):
E/SQLiteOpenHelper( 3867): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3867): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3867): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3867): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.dm.DBProvider.query(DBProvider.java:505)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.APICProviderDecorator.query(APICProviderDecorator.java:348)
E/SQLiteOpenHelper( 3867): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3867): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3867): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteOpenHelper( 3867): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteOpenHelper( 3867): 	at com.htc.shared.orm.Query.fetch(Query.java:415)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.util.QueryHelper.fetch(QueryHelper.java:133)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.util.QueryHelper.fetch(QueryHelper.java:160)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.notification.AlarmSchedule.rescheduleMissedAlarms(AlarmSchedule.java:87)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.notification.NotifyService.doTimeChanged(NotifyService.java:831)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:164)
E/SQLiteOpenHelper( 3867): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
E/SQLiteOpenHelper( 3867): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3867): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 3867): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ActivityManager(  905): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3882 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 3867): update TASK shortcut>
,W/Settings( 3643): Setting voice_roaming_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3643): Setting voice_roaming_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/SQLiteOpenHelper( 3867): Opened MyDB.db in read-only mode
,W/Settings( 3643): Setting voice_roaming_guard_allowed has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3643): Setting voice_roaming_guard_blocked has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,W/Settings( 3643): Setting vzw_global_roaming_options has moved from android.provider.Settings.System to android.provider.Settings.Secure, returning read-only value.
,I/TodoTaskNotifyService( 3867): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/TodoTaskNotifyService( 3867): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1569): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/Settings( 3643): Setting boot_lock has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3643): Setting data_encryption has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WorldClock.Global( 3882): isHtcDevice = true
,W/NotifyReceiver( 3867): stopSelfResult true
D/PMS     (  905): releaseWL(42766b68): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/Process (  905): killProcessQuiet, pid=3598
,D/Process (  905): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  905): Killing 3598:com.htc.stock/u0a82 (adj 15): empty #17
,W/ContextImpl( 3132): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/WorldClock.Global( 3882): isHtcDevice = true
E/SQLiteDatabase( 3882): Failed to open database '/data/data/com.htc.android.worldclock/databases/alarms.db'.
E/SQLiteDatabase( 3882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmProvider.query(Unknown Source)
E/SQLiteDatabase( 3882): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3882): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3882): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3882): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarmsCursor(Unknown Source)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarms(Unknown Source)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.calculateNextAlert(Unknown Source)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.setNextAlert(Unknown Source)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmService.updateAlarms(Unknown Source)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmService.access$200(Unknown Source)
E/SQLiteDatabase( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmService$1.run(Unknown Source)
E/SQLiteDatabase( 3882): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 3882): Couldn't open alarms.db for writing (will try read-only):
E/SQLiteOpenHelper( 3882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmProvider.query(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3882): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3882): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 3882): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarmsCursor(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarms(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.calculateNextAlert(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.setNextAlert(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmService.updateAlarms(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmService.access$200(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at com.htc.android.worldclock.alarmclock.AlarmService$1.run(Unknown Source)
E/SQLiteOpenHelper( 3882): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  905): Recipient 3598
,I/DisplayManagerService(  905): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SQLiteOpenHelper( 3882): Opened alarms.db in read-only mode
,I/WorldClock.AlarmUtils( 3882): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3882): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3882): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/ActivityManager(  905): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3897 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/IntentController( 1118): receive(android.intent.action.ALARM_CHANGED,1,false)
E/SQLiteLog( 1527): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1527): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.calendar/databases/calendar.db, handle = 0x5c9b7d18
E/DatabaseUtils( 1527): Writing exception to parcel
E/DatabaseUtils( 1527): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 1527): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 1527): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DatabaseUtils( 1527): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 1527): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 1527): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DatabaseUtils( 1527): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DatabaseUtils( 1527): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1642)
E/DatabaseUtils( 1527): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1355)
E/DatabaseUtils( 1527): 	at com.android.providers.calendar.HtcFilterImpl_google.do_Query_INSTANCES(HtcFilterImpl_google.java:219)
E/DatabaseUtils( 1527): 	at com.android.providers.calendar.HtcFilterImpl_google.handle_Query(HtcFilterImpl_google.java:62)
E/DatabaseUtils( 1527): 	at com.android.providers.calendar.HtcCalendarProvider.query(HtcCalendarProvider.java:126)
E/DatabaseUtils( 1527): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/DatabaseUtils( 1527): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/DatabaseUtils( 1527): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/DatabaseUtils( 1527): 	at android.os.Binder.execTransact(Binder.java:412)
E/DatabaseUtils( 1527): 	at dalvik.system.NativeStart.run(Native Method)
,W/dalvikvm( 3132): threadid=11: thread exiting with uncaught exception (group=0x41672e30)
E/AndroidRuntime( 3132): FATAL EXCEPTION: IntentService[HtcDndCommandService]
E/AndroidRuntime( 3132): Process: com.android.settings:remote, PID: 3132
E/AndroidRuntime( 3132): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3132): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 3132): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 3132): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:463)
E/AndroidRuntime( 3132): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/AndroidRuntime( 3132): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/AndroidRuntime( 3132): 	at com.android.settings.framework.core.sound.HtcDndUtils.getCalendarEvent(HtcDndUtils.java:310)
E/AndroidRuntime( 3132): 	at com.android.settings.framework.app.HtcDndCommandService.addCalendarTimeSlot(HtcDndCommandService.java:452)
E/AndroidRuntime( 3132): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleSlotData(HtcDndCommandService.java:511)
E/AndroidRuntime( 3132): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleEventTimer(HtcDndCommandService.java:530)
E/AndroidRuntime( 3132): 	at com.android.settings.framework.app.HtcDndCommandService.onHandleIntent(HtcDndCommandService.java:142)
E/AndroidRuntime( 3132): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3132): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3132): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3132): 	at android.os.HandlerThread.run(HandlerThread.java:61)

```
