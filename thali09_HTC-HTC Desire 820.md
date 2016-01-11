#### Test 50242285feafdeb_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/libc    ( 2951): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 2951): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 2951): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
,--------- beginning of /dev/log/system
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (2951/10168)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 2951): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/YouTube ( 2951): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 2951): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 2951): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 2951): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
D/MediaRouterService(  907): Client com.google.android.youtube (pid 2951): Registered
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 2951): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.youtube (2951/10168)
D/YouTube ( 2951): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 2951): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1452552481&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/libc    ( 2951): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2951): [NET] getaddrinfo-,err=8
D/libc    ( 2951): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2951): [NET] getaddrinfo-, 1
D/libc    ( 2951): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2951): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2951): Error sending ping
E/cutils-trace( 2979): Error opening trace file: No such file or directory (2)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 2951): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 2951): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/MediaRouter( 2951): getSelectedRoute
D/YouTube ( 2951): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/YouTube ( 2951): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (2951/10168)
I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3014 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/YouTube ( 2951): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/Process (  907): killProcessQuiet, pid=2711
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2711:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/YouTube ( 2951): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 2951): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
I/ActivityManager(  907): Recipient 2711
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 2979): ====startRecUseTime====
D/htc.customization.log.level( 2979):  is 
W/CustomizationLogLevel( 2979): Level value is invalid, use default level 2
W/dalvikvm( 3014): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3014, uid=10074, userID:0
D/Finsky  ( 3014): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/CustomizationManager( 2979):  Read ACC file spent 0.065 (s)
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3014/10074)
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__001
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__102
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__032
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__016
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__002
D/CIDMapFileReader( 2979): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 2979): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 2979): Parsing tag category name = system
I/CustomizationCIDLoader( 2979): Parsing tag category name = application
I/CustomizationCIDLoader( 2979): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 2979): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 2979): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 2979): Parsing tag category name = ACC
I/CustomizationCIDLoader( 2979): Parsing tag category name = Settings
D/CustomizationManager( 2979):  Read CID file spent 0.110 (s)
D/CustomizationManager( 2979):  All configurations done spent 0.110 (s)
W/HtcNativeFlag( 2979): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 2979): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 2979): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 2979): Fail to get flag for type 'language', use default value: -1
W/dalvikvm( 3014): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 3014): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
W/asset   (  907): Copying FileAsset 0x6819dce0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1115209720
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 2979
D/PMS     (  907): acquireHCC(4268ae80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(428c4310): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/FeedHostManager( 1249): [onPause]
I/FeedProviderManager( 1249): onPause
I/FeedHostManager( 1249): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f36378
I/SocialFeedProvider( 1249): +onPause
I/SocialFeedProvider( 1249): -onPause
D/PMS     (  907): acquireWL(42a455b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3014/10074)
D/Finsky  ( 3014): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 3014): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3047 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
W/Settings( 3014): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3014): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/asset   ( 3047): Copying FileAsset 0x5c6f3648 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/dalvikvm( 3014): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3014): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3014): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
I/TrimMemoryManager( 1249): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3047): Binding Chromium to main looper Looper (main, tid 1) {41dd3ce0}
I/LibraryLoader( 3047): Expected native library version number "",actual native library version number ""
I/chromium( 3047): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3047): Initializing chromium process, renderers=0
D/PMS     (  907): acquireWL(427743f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): acquireWL(428d2eb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  907): releaseWL(427743f8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4259aaa0:true
D/BluetoothAdapter( 3047): 1105120592: getState() :  mService = null. Returning STATE_OFF
W/dalvikvm( 3014): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/Adreno-EGL( 3047): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3047): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3047): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3047): Local Branch: 
I/Adreno-EGL( 3047): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3047): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3047):                  aa63bbd948f41d15fc72f585e
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3014, uid=10074, userID:0
D/Volley  ( 3014): [282] DiskBasedCache.clear: Cache cleared.
D/Volley  ( 3014): [289] DiskBasedCache.clear: Cache cleared.
D/Process (  907): killProcessQuiet, pid=2749
D/Ads     ( 3014): Skipping gmscore version check
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 2749:com.google.android.gm/u0a107 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.google.android.gms/.chimera.container.GmsModuleFinder$Receiver
I/ActivityManager(  907): Recipient 2749
D/Finsky  ( 3014): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Finsky  ( 3014): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 3014): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/chromium( 3047): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3047): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3047): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
D/Finsky  ( 3014): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
W/dalvikvm( 3047): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3047): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3047): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3047): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3047): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3047): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3047): CordovaWebView is running on device made by: HTC
,W/AwContents( 3047): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1249
W/ResourceType( 3047): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3047): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e1e098, mServedView=org.apache.cordova.engine.SystemWebView{41de4070 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1185): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1185): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1185): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  907): Enable input method client, pid=3047
W/AwContents( 3047): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +294ms
D/PMS     (  907): releaseWL(42a455b0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/dalvikvm( 1992): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1992): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1992): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1992): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  907): acquireWL(42add318): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1992 10029 null
I/ActivityManager(  907): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/PMS     (  907): acquireWL(42ae7848): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
D/FileApkUtils( 1992): Spent 23ms computing apk sha1.
D/FileApkUtils( 1992): Module already staged or being staged:chimera-modules/MapsModule.apk
D/DexOptUtils( 1992): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1992): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 1992): Reading stored module config
D/PMS     (  907): releaseWL(42add318): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  907): releaseWL(42ae7848): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
D/GmsModuleFndr( 1992): Beginning GMS chimera module scan
W/asset   ( 1992): Copying FileAsset 0x6580ab68 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
E/AndroidProtocolHandler( 3047): Unable to open asset URL: file:///android_asset/www/jxcore.js
W/InstanceID/Rpc( 1992): Found 10029
D/ChimeraCfgMgr( 1992): Beginning module configuration check
D/ChimeraCfgMgr( 1992): Module APKs unchanged, check complete
I/chromium( 3047): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3047): Set native->JS mode to OnlineEventsBridgeMode
E/dalvikvm( 1992): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1992): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1992): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1992): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1992): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1992): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1992): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 1992): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1992): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1992/10029)
E/dalvikvm( 1198): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1198): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1198): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
E/dalvikvm( 1992): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1992): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
W/dalvikvm( 1198): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1198): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1198): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1198): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 1198): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1198): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/PMS     (  907): acquireWL(42ac0000): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
E/dalvikvm( 1992): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1992): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1992): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
W/dalvikvm( 1992): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
I/ActivityManager(  907): Delay finish: com.google.android.gms/.tapandpay.receiver.OnBootCompletedReceiver
D/PMS     (  907): acquireWL(42c04e38): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42aefef0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42ac0000): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1992): COMPAT: Multi user not supported
D/GCM     ( 1341): COMPAT: Multi user not supported
D/jxcore_app_log( 3047): JniHelper::setJavaVM(0x41998010), pthread_self() = 1657394248
W/dalvikvm( 1341): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/GCoreUlr( 1992): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1198): DispatchingService.onCreate()
I/CheckinService( 1992): Checkin interval check for package: unspecified last checkin: 1452528229604 min interval config: 0 actual interval: 24253044
W/dalvikvm( 1341): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
I/CheckinService( 1992): Disabling old GoogleServicesFramework version
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1992, uid=10029, userID:0
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
D/SystemUpdateService( 1992): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
D/SystemUpdateService( 1992): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
D/PMS     (  907): acquireWL(42a8d2c0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1992, uid=10029, userID:0
W/dalvikvm( 1341): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1341): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1992): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
W/dalvikvm( 1341): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1341): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
W/jxcore-log( 3047): Initializing JXcore engine
W/jxcore-log( 3047): JXcore engine is ready
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1992, uid=10029, userID:0
W/dalvikvm( 1341): VFY: unable to resolve instance field 161
V/AuthZen ( 1992): Handling intent: android.intent.action.BOOT_COMPLETED
I/CheckinService( 1992): Checking schedule, now: 1452552482732 next: 1453051166555
I/CheckinService( 1992): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1992, uid=10029, userID:0
D/PMS     (  907): acquireWL(42a749e8): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1992, uid=10029, userID:0
I/SystemUpdateService( 1992): cancelUpdate (empty URL)
I/SystemUpdateService( 1992): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1992, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1992, uid=10029, userID:0
I/GCoreUlr( 1198): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
D/PMS     (  907): releaseWL(42a749e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1341): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/AuthZenEventHandler( 1992): Handling event: android.intent.action.BOOT_COMPLETED
W/dalvikvm( 1341): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
W/jxcore-log( 3047): Starting JXcore engine
D/SystemUpdateService( 1992): onDestroy
D/PMS     (  907): releaseWL(42aefef0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42c04e38): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
W/BaseAppContext( 1992): Using Auth Proxy for data requests.
D/PMS     (  907): acquireWL(42872f78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1992): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/GCM     ( 1341): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1341): [NET] getaddrinfo-,err=8
D/libc    ( 1341): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1341): [NET] getaddrinfo-, 1
D/libc    ( 1341): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 1341): [NET] getaddrinfo_proxy-
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1341/10029)
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
D/PMS     (  907): releaseWL(42872f78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
E/BaseAppContext( 1992): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1198, uid=10029, userID:0
W/dalvikvm( 1992): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
I/AuthZen ( 1992): Fetching signing key...
W/jxcore-log( 3047): Platform android
W/jxcore-log( 3047): 
W/jxcore-log( 3047): Process ARCH arm
W/jxcore-log( 3047): 
I/AuthZen ( 1992): Signing key fetched successfully!
W/BaseAppContext( 1992): Using Auth Proxy for data requests.
I/jxcore-log( 3047): JXcore Cordova bridge is ready!
I/jxcore-log( 3047): 
W/jxcore-log( 3047): JXcore engine is started
I/GCoreUlr( 1198): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/AuthZenTransactionCache( 1992): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1992): Clearing transaction cache
I/GCoreUlr( 1198): Unbound from all location providers
I/GCoreUlr( 1198): Place inference reporting - stopped
D/PMS     (  907): acquireWL(41ea5200): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(41ea5200): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42a8d2c0): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
E/jxcore  ( 3047): Error!: No such native module /data/data/com.example.hello/files/www/jxcore/app.js
E/jxcore  ( 3047): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
I/GCoreUlr( 1198): DispatchingService.onDestroy()
I/GCoreUlr( 1198): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1198): Unbound from all location providers
I/GCoreUlr( 1198): Place inference reporting - stopped
D/PMS     (  907): acquireWL(4226fd10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4226fd10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
,W/dalvikvm( 1341): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1341): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1341): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(421a9210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(421a9210): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/BootCompletedReceiver( 1992): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 1992): Got an BootCompleted event.
D/BootCompletedReceiver( 1992): Will NOT schedule AdAttestation signal task because it's disabled.
,W/dalvikvm( 1341): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,W/Auth    ( 1341): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
D/PMS     (  907): acquireWL(42913748): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1341 10029 null
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PMS     (  907): releaseWL(42913748): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PersistentNotificationBroadcastReceiver( 1198): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.people.sync.focus.ContactsSyncBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.chromesync.sync.SyncReceiverService$Receiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42a62a88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42a62a88): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 2906): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2906): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2906): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2906): Cust_ConnectToPC   : spcsc>false
D/        ( 2906): Cust_ConnectToPC   : IPT>true
D/        ( 2906): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2906): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2906): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2906): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2906): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/PSReceiver( 2906): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 2906): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Delay finish: com.android.settings/.PSReceiver
I/SmartNS_PSService( 2906): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2906): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 2906):  defaultType:0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3149 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,D/browser ( 3149): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3149): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3149): Loading: swewebviewchromium
,I/LibraryLoader( 3149): Time to load native libraries: 34 ms (timestamps 3412-3446)
,I/LibraryLoader( 3149): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3149): Initializing chromium process, renderers=9
,I/LibraryLoader( 3149): Expected native library version number "",actual native library version number ""
,I/chromium( 3149): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/chromium( 3149): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3149): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3149): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3149): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3149): Local Branch: 
I/Adreno-EGL( 3149): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3149): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3149):                  aa63bbd948f41d15fc72f585e
,V/IccIntentReceiver( 1276): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1470): SIM state: ABSENT
I/SIMStateChangeReceiver( 1470): phoneType = 0
,I/SIMStateChangeReceiver( 1470): remove notification
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3188 uid=10032 gids={50032, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=2788
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3200 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 2788:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2788
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/SystemReader( 2480): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2480): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2480): onReceive()
D/ExchangePolicystatus( 2480): onReceive(): ACTION_SIM_STATE_CHANGED
D/ExchangePolicystatus( 2480): onReceive(): else
,D/Process (  907): killProcessQuiet, pid=2726
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1217): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Killing 2726:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3215 uid=10041 gids={50041}
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3230 uid=10078 gids={50078}
,D/Process (  907): killProcessQuiet, pid=2810
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2810:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3200): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
,W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(4268ae80): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(428c4310): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/SMSBackup( 3230): Got a database change event
,D/Process (  907): killProcessQuiet, pid=2837
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2837:com.htc.backupreset/1000 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2726
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2837
,W/AccTypeManager( 3200): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3200): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3243 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/WeatherUtility( 1107): can't get weather sync account
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2810
,W/WeatherRequest( 1107): request cur loc, but there is no sys cur
,E/ExternalAccountType( 3200): Unsupported attribute readOnly
,D/AccTypeManager( 3200): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CalendarApplication( 3243): onCreate
D/ProviderChangeReceiver( 3243): ---------------------------------------------------
,D/ProviderChangeReceiver( 3243): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3243): start to updateAlertNotification!
W/AccTypeManager( 3200): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3200): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/AlertService( 3243): No fired or scheduled alerts
,D/HtcAlertUtils( 3243): -- cancelReminderNotification --
W/ContextImpl( 2884): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/HtcAlertUtils( 3243): broadcastExistReminder!
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/ExternalAccountType( 3200): Unsupported attribute readOnly
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3260 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=2527
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2527:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2527
,I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3260): can't get weather sync account
,W/WeatherRequest( 3260): request cur loc, but there is no sys cur
,W/Settings( 3260): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 1 10 17
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 4 times.
,D/PMS     (  907): releaseWL(428d2eb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=2854
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3275 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 2854:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2854
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DemoRecovery.RestoreReceiver( 3275): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3275): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3275): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3289 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=2869
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2869:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2869
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(428e73b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3289 10071 null
,D/PMS     (  907): acquireWL(42941330): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3289 10071 null
,D/PMS     (  907): releaseWL(428e73b0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3289): update TASK shortcut>
,I/TodoTaskNotifyService( 3289): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3289): stopSelfResult true
D/PMS     (  907): releaseWL(42941330): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=2897
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3304 uid=10082 gids={50082, 3003, 5012}
I/ActivityManager(  907): Killing 2897:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3316 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  907): Recipient 2897
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3329 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  907): killProcessQuiet, pid=2938
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  907): killProcessQuiet, pid=2924
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/ActivityManager(  907): Killing 2938:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  907): Killing 2924:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
,I/ActivityManager(  907): Recipient 2938
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2924
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3329): create image Cache, size: 31457280.
I/ImageRamCache( 3329): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3329): create image Cache, size: 12582912.
,I/FeedSettings( 3329): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3329): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3329): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3329): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3329): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3329): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3329): [custom highlight] onReceive
,D/CustomHighlightService( 3329): [custom highlight] onHandleIntent
D/MessagingNotification( 2480): New incoming message, can't cancel notification now
,D/MessagingNotification( 2480): newMsgCnt: 0, false
,D/NewsDB  ( 3329): set custom highlight []
I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3329): [custom highlight] set tags 
,I/ActivityManager(  907): Resuming delayed broadcast
D/SMSBackup( 3230): Got a database change event
D/MessagingShortcutReceiver( 2480): keep hiding shortcut bubble
D/MessagingShortcut( 2480): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2480): After query: 0
D/MessagingShortcut( 2480): mPresentUnreadCount: -1
D/MessagingShortcut( 2480): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2480): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderNotification, total:0
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3289): update TASK shortcut>
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1217): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  907): killProcessQuiet, pid=2951
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2951:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 2951
,D/MediaRouterService(  907): Client com.google.android.youtube (pid 2951): Died!
,I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3345 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,V/AlarmManager(  907): sending alarm PendingIntent{4228ad18: PendingIntentRecord{428b4a40 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=21130, Int=1800000
,V/AlarmManager(  907): sending alarm PendingIntent{42a71598: PendingIntentRecord{42a78a68 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=44947, Int=259200000
,V/AlarmManager(  907): sending alarm PendingIntent{420195a0: PendingIntentRecord{4276cb08 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50243, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{41fe86a0: PendingIntentRecord{4288d750 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1452510000000, Int=86400000
,I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3359 uid=10091 gids={50091, 3003, 5012}
,D/MdScBoot( 3345): [878.1.] 30@-234738 -> 40@-234805
I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3014
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  907): killProcessQuiet, pid=2906
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3014:com.android.vending/u0a74 (adj 15): empty #17
I/ActivityManager(  907): Killing 2906:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2906
,D/WearableService( 1198): callingUid 10029, callindPid: 1198
,E/MDM     ( 1198): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/LocationInitializer( 1992): Restart initialization of location
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1341): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1341): Proximity feature is not enabled.
,I/ActivityManager(  907): Recipient 3014
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GCoreFlp( 1198): No location to return for getLastLocation()
,W/FusedLocationProvider( 1198): location=null
D/PMS     (  907): acquireWL(425c3aa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(425c3aa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,E/MDM     ( 1198): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 1992): Restart initialization of location
,D/AuthorizationBluetoothService( 1341): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1341): Proximity feature is not enabled.
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/MtpReceiver( 2197): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2197): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2197): [MTP][handleMessage][startService]
,D/MtpReceiver( 2197): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2197): [MTP][handleMessage]-
,D/MtpService( 2197): [MTP] startForeground
,W/GCoreFlp( 1198): No location to return for getLastLocation()
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3382 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/PMS     (  907): acquireWL(423e19b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
W/FusedLocationProvider( 1198): location=null
,I/RemoteViews( 1107): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1107): com.android.providers.media 3 2 10
I/RemoteViews( 1107): com.android.providers.media (false,0)
,D/MtpService( 2197): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2197): TotalSize=1918604,MediaCacheLimit=6000
,I/RemoteViews.Performance( 1107): com.android.providers.media 1 1 15
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
D/PMS     (  907): releaseWL(423e19b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42314570): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1992 10029 null
,D/MtpService( 2197): [isMtpConnected] connected: true
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/SyncApplication( 3382): Loading default preferences
,I/iu.UploadsManager( 1992): End new media; added: 0, uploading: 0, time: 59 ms
,W/Resources( 3382): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/PMS     (  907): releaseWL(42314570): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,D/WifiService(  907): New client listening to asynchronous messages
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4294cf70 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SyncApplication( 3382): Overriding preferences with custom values
,D/SyncApplication( 3382): Updating preferences succeeded
,E/SyncApplication( 3382): Application created.
D/VolumeInfo( 3382): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3382): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3382): Found 0 mount point(s)
,V/VolumeInfo( 3382): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3382): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3382): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3382): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3382): getNewCalendarAuthority()...
,D/SyncApplication( 3382): enableAppOperation()+
,D/SyncApplication( 3382): enableAppOperation()-
,D/HTCUtilities( 3382): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3382, uid=10008, userID:0
,W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3382, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3382): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3382): isNeorSinged() return false
D/CDMountReceiver( 3382): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3382): USB connected to PC
,D/FOTAReceiver( 3382): onReceive() enter 
,D/FOTAReceiver( 3382): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3402 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3149
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3149:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3149
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3402): -onCreate()
,V/Settings:HtcSettingsApplication( 3402): [3402/3402] onCreate()
,D/TetherSettings( 3402): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3402): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3402): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3402): Cust_ConnectToPC   : spcsc>false
D/        ( 3402): Cust_ConnectToPC   : IPT>true
,D/        ( 3402): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3402): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3402): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3402): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3402): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3402): Cust_ConnectToPC   : spcsc>false
D/        ( 3402): Cust_ConnectToPC   : IPT>true
D/        ( 3402): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3402): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3402): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3402): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3402): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3402): usb_cable_connect = 1
,D/SmartNS_Utility( 3402): usb_denied = 0
I/SmartNS_NSReceiver( 3402): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3402): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3402): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3402): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3402): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3402):  defaultType:0
,I/SmartNS_PSService( 3402): fail notificaiton:false
,D/SmartNS_Utility( 3402): usb_cable_connect = 1
D/SmartNS_Utility( 3402): usb_denied = 0
,I/SmartNS_PSService( 3402): usb notificaiton:true
,W/ContextImpl( 3402): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3402): usb_cable_connect = 1
D/SmartNS_Utility( 3402): usb_denied = 0
,I/SmartNS_PSService( 3402): usb notificaiton:true
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3402/1000)
V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/RemoteViews( 1107): com.android.settings (true,33751552)
,I/RemoteViews.Performance( 1107): com.android.settings 3 0 10
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/SmartNS_Utility( 3402): usb_cable_connect = 1
,D/SmartNS_Utility( 3402): usb_denied = 0
I/ActivityManager(  907): Resuming delayed broadcast
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3402/1000)
,I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews( 1107): com.android.settings (true,33751552)
D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews.Performance( 1107): com.android.settings 1 1 10
I/SmartNS_PSService( 3402): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3402): USB Plugged, Set USBPlugged=  truePSenabled:false
,W/WeatherUtility( 3260): can't get weather sync account
I/ActivityManager(  907): Resuming delayed broadcast
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1249): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1249): com.google.android.googlequicksearchbox 2 2 5
,W/WeatherRequest( 3260): request cur loc, but there is no sys cur
,W/Settings( 3260): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=3419 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 1 77 17
,D/PMS     (  907): acquireWL(427f2540): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3419 1000 null
,W/ContextImpl( 3419): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3419): call getInstance()
I/ActivityManager(  907): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3419): MY_DEBUG = false
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3188
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3188:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,W/WeatherUtility( 1107): can't get weather sync account
,D/WeatherUtility( 1320): Weather sync is On
I/ActivityManager(  907): Recipient 3188
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3436 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
D/WSP     ( 1320): [Receiver] auto sync agent, auto sync is enabled, reset schedule
W/WeatherUtility( 3260): can't get weather sync account
,W/WeatherRequest( 3260): request cur loc, but there is no sys cur
,W/Settings( 3260): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1249): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1249): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1249): com.htc.widget.weatherclock 2 9 17
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3454 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3200
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3200:com.htc.contacts/u0a44 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3200
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3454): Database version: 95
,W/ContextImpl( 3454): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,V/AlarmManager(  907): sending alarm PendingIntent{42065470: PendingIntentRecord{42af5c40 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452552488195, Int=0
,W/ContextImpl( 3454): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3454): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3454): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3454): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
D/Process (  907): killProcessQuiet, pid=3243
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3243:com.htc.calendar/u0a13 (adj 15): empty #17
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3454, uid=10154, userID:0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3243
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 3454): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3454): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/TelephonyReceiver( 1217): bind: true
,D/DFPI.PIReciver( 3275): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3454/10154)
D/GenericMessagesProvider( 2480): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2480): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2480): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2480): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 2480): DB info: errno = 2, errno message = No such file or directory
,E/SQLiteDatabase( 2480): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2480): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2480): ,	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2480): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2480): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2480): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2480): 	at dalvik.system.NativeStart.run(Native Method)
I/DFPI.ApkInstallService( 3275): onHandleIntent
I/DFPI.ApkInstallService( 3275): Media Scan Finished Case 
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
W/System.err( 2480): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
D/DFPI.ApkInstallService( 3275): check CID = HTC__032
W/System.err( 2480): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
I/DFPI.ApkInstallService( 3275): There is no Demo.apk in sd card or phone storage
W/System.err( 2480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2480): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2480): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2480): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2480): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2480): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2480): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2480): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2480): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2480): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2480): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2480): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 2480): 	at dalvik.system.NativeStart.run(Native Method)
D/MediaRouter( 3454): getSelectedRoute
D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3454, uid=10154, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42af8508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(42af8508): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3477 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3477/10053)
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3477): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,D/PMS     (  907): releaseWL(427f2540): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3496 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=2884
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2884:com.android.settings:remote/1000 (adj 15): empty #17
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3496): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3496): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3496): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3496): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
,I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/ActivityManager(  907): Recipient 2884
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 5 times.
,I/ActivityManager(  907): Resuming delayed broadcast
,D/DFPI.PIReciver( 3275): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 3275): onHandleIntent
,I/DFPI.ApkInstallService( 3275): Media Scan Finished Case 
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3275): check CID = HTC__032
,I/DFPI.ApkInstallService( 3275): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3496): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3496): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3496): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3496): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lil,ac.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SensorManager(  907): mEventCount = 300
,I/SocialFeedProvider( 1249): +disConnect socialManager
,I/SocialFeedProvider( 1249): disconnect socialManager
,I/SocialFeedProvider( 1249): -disConnect socialManager
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,V/AlarmManager(  907): sending alarm PendingIntent{426076f0: PendingIntentRecord{427e0020 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452552491889, Int=0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SocialManager[SocialBiLogHelper]( 3329): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3329): last commit ulog time 1452509393704
,I/SocialManager[SocialBiLogHelper]( 3329): skip commit this time
D/PMS     (  907): acquireWL(42a74b50): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1470 10014 null
,I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/Process (  907): killProcessQuiet, pid=3304
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3304:com.htc.stock/u0a82 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3304
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(42a74b50): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3520 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3275): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3275): onHandleIntent
I/DFPI.ApkInstallService( 3275): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3275): check CID = HTC__032
,I/DFPI.ApkInstallService( 3275): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/EASAppSvc( 3520): [ NA ]- onCreate()
,I/EASAppSvc( 3520): [ NA ]> onUpgrade: version = 63
,D/ORMLib  ( 3289): put()
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3520/10064)
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3520/10064)
,D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3520/10064)
,I/EASAppSvc( 3520): [ NA ]- onDestroy()
,I/EASAppSvc( 3520): [ NA ]> uninitEASService
,I/EASRequestController( 3520): [ NA ]release
,I/EASAppSvc( 3520): [ NA ]< uninitEASService
,I/EASAppSvc( 3520): [ NA ]- onCreate()
,I/EASAppSvc( 3520): [ NA ]> onUpgrade: version = 63
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3520/10064)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3520/10064)
D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3520/10064)
,D/ORMLib  ( 3289): put()
,I/EASAppSvc( 3520): [ NA ]- onDestroy()
,I/EASAppSvc( 3520): [ NA ]> uninitEASService
,I/EASRequestController( 3520): [ NA ]release
I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=3552 uid=10068 gids={50068, 3003, 5012}
,I/EASAppSvc( 3520): [ NA ]< uninitEASService
,D/Process (  907): killProcessQuiet, pid=3316
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3316:com.htc.stock:remote/u0a82 (adj 15): empty #17
,D/ORMLib  ( 3289): put()
,I/ActivityManager(  907): Recipient 3316
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=1992, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=1992, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=1992, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=1992, uid=10029, userID:0
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
W/Prism.AllAppsManager( 1249): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/Launcher( 1249): Deferring update until onResume
,D/Launcher( 1249): waitUntilResume // bindAppsUpdated
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/Prism.ItemManager( 3329): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3329): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,E/ExternalAccountType( 1307): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3215
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/PackageManager(  907): Unable to load service info ResolveInfo{42a28510 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,I/ActivityManager(  907): Killing 3215:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
I/SoundPicker( 3496): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3496): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3496): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3496): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3496): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/ActivityManager(  907): Recipient 3215
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtone,s/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3454): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/TelephonyReceiver( 1217): bind: false
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,I/GCoreNlp( 1198): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/AutoSetting( 1320): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1320): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1320): service - requestNLP() NetworkLocationProvider not enabled
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(42a780f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42a780f8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): acquireWL(427d6498): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(427d6498): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42743e08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42743e08): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4286f7c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4286f7c0): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3275): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3275): onHandleIntent
I/DFPI.ApkInstallService( 3275): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3275): check CID = HTC__032
,I/DFPI.ApkInstallService( 3275): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,V/AlarmManager(  907): sending alarm PendingIntent{424ce928: PendingIntentRecord{422d1fe8 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452552494297, Int=0
,I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41e6beb0 +
,I/Prism.WidgetManager( 1249): onLoadItems() +
,I/Prism.ItemManager( 3329): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 3329): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad68 +
,I/Prism.WidgetManager( 3329): onLoadItems() +
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 6 times.
,E/Prism.WidgetManager( 1249): The same lists. No need to update. skip it.
,I/Prism.WidgetManager( 1249): onLoadItems() -
,I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41e6beb0 -
,I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3496): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3496): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3496): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3496): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/Prism.WidgetManager( 3329): onLoadItems() -
I/Prism.ItemManager( 3329): loadItems() com.htc.launcher.pageview.WidgetManager@41e4ad68 -
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,D/PhoneApp( 1217): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1217): -- N1 =0
,D/PhoneApp( 1217): -- N2 =0
,D/PhoneApp( 1217): -- N3 =0
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3454): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=3583 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/Process (  907): killProcessQuiet, pid=3230
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3230:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3230
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3596 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
,I/RemoteViews( 1107): com.htc.updater (true,33751552)
D/NotificationService(  907): notification sound not played, stream=5 volume=0 always=false
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41e9fd48 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.updater 2 7 1 10
,I/ActivityManager(  907): Resuming delayed broadcast
,I/RemoteViews( 1107): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{4215d008 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.htc.updater 1 8 0 10
I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3345
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3345:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_ADDED
I/ActivityManager(  907): Recipient 3345
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2622): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  907): acquireWL(428ab5a0): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428ab5a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42899218): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42899218): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4208fe40): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4208fe40): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4273d488): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4273d488): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426aa1e0): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426aa1e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423c1928): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(423c1928): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(41e96280): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(41e96280): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42247df8): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42247df8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4268a3a0): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4268a3a0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4241d368): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4241d368): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/asset   ( 2622): Copying FileAsset 0x643520d0 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/PMS     (  907): acquireWL(4204e188): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2622): UpdateCorporaTask done [took 435 ms] updated apps [took 435 ms] 
,V/AlarmManager(  907): sending alarm PendingIntent{426bdbe8: PendingIntentRecord{427460b8 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452552496102, Int=0
,I/iu.UploadsManager( 1992): End new media; added: 0, uploading: 0, time: 91 ms
,I/Icing   ( 1992): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
,D/Icing   ( 1992): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 1992): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
,D/PMS     (  907): releaseWL(4204e188): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3622 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 3622): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3622 dbg=false s=true
,I/DeviceManagement( 3622): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3635 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3359
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3359:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3359
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
W/GAV2    ( 3635): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42c09f08 u0 com.google.android.gms/.gcm.GcmService}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3655 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  907): acquireWL(427264f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PMS     (  907): releaseWL(427264f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,I/htcbackup-core( 3655): ModelRegistry: Loading model meta data from resources...
,W/GAV2    ( 3635): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  907): killProcessQuiet, pid=3382
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/ContextImpl( 3655): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
I/ActivityManager(  907): Killing 3382:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
W/ContextImpl( 3655): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/ActivityManager(  907): Recipient 3382
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3673 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  907): killProcessQuiet, pid=3402
,I/DeviceManagement( 3622): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/ActivityManager(  907): Killing 3402:com.android.settings/1000 (adj 15): empty #17
I/DeviceManagement( 3622): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.backup, com.htc.guide, android, com.android.CSDFunctionG, com.htc.backupreset, com.htc.usage, com.android.inputdevices, com.htc.mirrorlinkserver, com.htc.cirmodule, com.qualcomm.privinit, com.htc.home.personalize, com.android.location.fused, com.htc.checkinprovider, com.htc.android.htcloglevel, com.htc.smartdim, com.htc.autobot.cargps.provider, com.htc.feedback, com.htc.drive.activator, com.android.providers.settings, com.qualcomm.timeservice, com.htc.android.htcsetupwizard, com.android.keychain, com.htc.lockscreen, com.android.settings, com.htc.htcpowermanager]
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/DeviceManagement( 3622): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,I/DeviceManagement( 3622): WorkflowService: Starting workflow service
I/DeviceManagement( 3622): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e126c8] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3622): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3622): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 3622): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 3622): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 3673):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=3688 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3402
,I/DeviceManagement( 3622): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(4284eb48): PARTIAL_WAKE_LOCK  AsyncService 0x1 3688 10160 null
,D/PMS     (  907): releaseWL(4284eb48): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/DeviceManagement( 3622): SessionStateController: Checking invariants...
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42aaa968): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3688 10160 null
,I/DeviceManagement( 3622): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackageAddedReceiver
,I/DeviceManagement( 3622): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41e126c8]
,I/DeviceManagement( 3622): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(42840758): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3688 10160 null
D/PMS     (  907): releaseWL(42aaa968): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=3712 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3419
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3419:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3419
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3688/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3688/10160)
,D/PMS     (  907): releaseWL(42840758): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  907): killProcessQuiet, pid=3260
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3260:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3712): -onCreate()
,I/ActivityManager(  907): Recipient 3260
V/Settings:HtcSettingsApplication( 3712): [3712/3712] onCreate()
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3729 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=2480
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2480:com.htc.sense.mms/u0a65 (adj 15): empty #17
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2480
,D/Settings:HtcWirelessFeatureFlags( 3712): id/is att sku: 99/false
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3729, uid=10074, userID:0
,W/SystemReader( 3712): Cannot find devicepolicy_lower_fp_quality, use default value instead
,D/Finsky  ( 3729): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3729/10074)
,W/SystemReader( 3712): Cannot find support_harman, use default value instead
,W/SystemReader( 3712): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3712): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3712): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3712): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3712): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]support         :false
,W/FingerprintManager( 3712): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,E/Settings:HtcVoWifiWidgetEnabler( 3712): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3712): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3729/10074)
,D/Finsky  ( 3729): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 3729): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3729): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3729, uid=10074, userID:0
,D/Ads     ( 3729): Skipping gmscore version check
,D/Finsky  ( 3729): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3729): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 3729): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/Finsky  ( 3729): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,D/Finsky  ( 3729): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/PackageBroadcastService( 1992): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,D/Process (  907): killProcessQuiet, pid=3329
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/dalvikvm( 1992): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3329:com.htc.sense.news/u0a76 (adj 15): empty #17
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3712): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3712): updateDevelopment, bPrefShow = true
,D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1992): Loading module APK com.google.android.play.games
,E/Settings:HtcUmcWidgetEnabler( 3712): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3712): [supportHomeButton]support         :false
,W/FingerprintManager( 3712): hasFingerprint() - sSensorCode = 0
,E/Settings:HtcVoWifiWidgetEnabler( 3712): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3712): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 1992): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 1992): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 1992): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 1992): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,I/ActivityManager(  907): Recipient 3329
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,D/PMS     (  907): acquireWL(42852ff8): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1992): Module APK com.google.android.play.games already loaded
D/PMS     (  907): releaseWL(42852ff8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426d9ed8): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,W/BaseAppContext( 1992): Using Auth Proxy for data requests.
,W/BaseAppContext( 1992): Using Auth Proxy for data requests.
,W/BaseAppContext( 1992): Using Auth Proxy for data requests.
,W/BaseAppContext( 1992): Using Auth Proxy for data requests.
W/BaseAppContext( 1992): Using Auth Proxy for data requests.
,W/BaseAppContext( 1992): Using Auth Proxy for data requests.
,W/BaseAppContext( 1992): Using Auth Proxy for data requests.
,W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 1992): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 1992): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 1992): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 1992): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 1992): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1992, uid=10029, userID:0
,I/PeopleDatabaseHelper( 1992): cleanUpNonGplusAccounts done.
,I/SensorManager(  907): mEventCount = 450
,W/dalvikvm( 1992): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1992): Module APK com.google.android.play.games already loaded
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 7 times.
,I/ActivityManager(  907): Resuming delayed broadcast
,D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 1992): Submit a task: k
,D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/k       ( 1992): Processing package: com.example.hello
I/ActivityManager(  907): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
,D/GassUtils( 1992): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 1992): Found info for package com.example.hello in db.
,I/Icing   ( 1992): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/asset   ( 1992): Copying FileAsset 0x65f9c220 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/Icing   ( 1992): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(426d9ed8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.vision from APK com.google.android.gms
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2622): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/IcingCorporaProvider( 2622): UpdateCorporaTask done [took 42 ms] updated apps [took 42 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(4294b6a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 3688 10160 null
,D/PMS     (  907): releaseWL(4294b6a8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,W/dalvikvm( 3729): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
,D/PackageBroadcastService( 1992): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1992, uid=10029, userID:0
,D/PMS     (  907): acquireWL(4270a318): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4270a318): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=3789 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(428bd960): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,W/GAV2    ( 3789): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=3812 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,D/Process (  907): killProcessQuiet, pid=3289
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3289:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3289
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Gmail   ( 3789): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3789): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 3789): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 3789): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/dalvikvm( 3812): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3812): VFY: unable to resolve instance field 36
,W/dalvikvm( 3812): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3812): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Babel   ( 3812): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 3812): MmsConfig.loadMmsSettings
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=3840 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=3812, uid=10111, userID:0
,W/Settings( 3812): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MessageFrequencyProvider( 3840): onCreate
V/GetPrviateResource( 3840): GetPrviateResource
,D/MmsCustomizationProvider( 3840): query uri: content://htc-mms-customization/mms-ua/ua_string
,V/GetPrviateResource( 3840): GetPrviateResource
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=3812, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=3812, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=3812, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=3812, uid=10111, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=3812, uid=10111, userID:0
D/PMS     (  907): acquireWL(427270e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3812 10111 null
,D/MmsCustomizationProvider( 3840): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
I/Babel   ( 3812): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/Babel   ( 3812): MmsConfig.loadFromDatabase
,E/Babel   ( 3812): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 3812): MmsConfig.loadFromResources
,E/Babel   ( 3812): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3812): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  907): killProcessQuiet, pid=3520
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  907): Killing 3520:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3520
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,I/ProviderInstaller( 3812): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 3840): sense_version=6.0
,D/BTAccessoryUtil( 3840): createReceiver
,D/BTAccessoryUtil( 3840): registerReceiver return intent = null
D/MessageCustFlag( 3840): sku_id=99
,W/SystemReader( 3840): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 3840): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3840): networkCode: 
,D/MessageCustFlag( 3840): sku_id=99
D/MmsConfig( 3840): SIE smsPri: null
,D/MmsConfig( 3840): networkCode: 
,D/HtcTelephonyCapability( 3840): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 3840): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3840): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3840): Cannot find qct_8960_interface, use default value instead
,D/PMS     (  907): releaseWL(427270e8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42a78188): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3812 10111 null
,I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,D/PMS     (  907): releaseWL(42a78188): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3552
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3552:com.htc.task.gtask/u0a68 (adj 15): empty #17
D/PMS     (  907): acquireWL(42aad378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
I/ActivityManager(  907): Recipient 3552
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(42aad378): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42a4b850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1992/10029)
,D/PMS     (  907): releaseWL(42a4b850): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,W/GCoreFlp( 1198): No location to return for getLastLocation()
,W/FusedLocationProvider( 1198): location=null
D/PMS     (  907): acquireWL(42842fa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42842fa8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/GCM     ( 1341): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,D/PMS     (  907): acquireWL(428f4258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(428f4258): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42aa3a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(42aa3a08): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4261edd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(4261edd0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42a02410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(42a02410): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42904e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3875 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(42904e80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42aeeac8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3875 10071 null
,I/ActivityManager(  907): Killing 3275:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3275
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Recipient 3275
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 1992): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1992): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): acquireWL(42a98bf8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3875 10071 null
,D/PMS     (  907): acquireWL(42c1db68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/PMS     (  907): releaseWL(428bd960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/TodoTaskNotifyService( 3875): java.lang.NullPointerException
,W/System.err( 3875): java.lang.NullPointerException
,W/System.err( 3875): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 3875): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 3875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3875): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 3875): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/NotifyReceiver( 3875): stopSelfResult true
D/PMS     (  907): releaseWL(42aeeac8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(42a98bf8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
D/PMS     (  907): releaseWL(42c1db68): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  907): acquireWL(42a9e6f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3812 10111 null
D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,I/WSP     ( 1320): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
,D/WeatherUtility( 1320): Weather sync is On
,I/WSP     ( 1320): [Receiver] next auto-sync alarm event is 60 mins later, at time: Tue Jan 12 00:48:21 CET 2016
,W/WSP     ( 1320): [Receiver] can't get active network info
D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,V/WSP     ( 1320): [SyncService] no data connection, stop sync service
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1320/10055)
,D/PMS     (  907): releaseWL(42a9e6f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3812/10111)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3812/10111)
,W/MediaManager( 3436): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,W/MediaManager( 3436): [DualLensScanUtil],	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3875): update TASK shortcut>
,I/GAV2    ( 3635): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3812/10111)
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=1992, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=1992, uid=10029, userID:0
,I/CheckinService( 1992): Done disabling old GoogleServicesFramework version
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=1992, uid=10029, userID:0
,D/Messaging( 3840): mNeedToUpdateDate2 start
,D/MmsConfig( 3840): packageName: com.htc.vvm.att does not exist
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/ReportIndicatorCache( 3840): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3840): 
D/MmsAsyncWorkHandler( 3840): HM tk = 20001
,D/ReportIndicatorCache( 3840): MSG_QUERY_REPORTS >>
,D/SettingsManager( 3840): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41de2348
,I/Messaging( 3840): mccmnc> 
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
D/MmsSmsV2Provider( 1217):  phoneType = -1
D/DraftCache( 3840): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3840): [DraftCache/1] refresh
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/MmsConfig( 3840): networkCode: 
,D/Messaging( 3840): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 3840): sense_version=6.0
D/PhoneStorageUtil( 3840): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 3840): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3840): createReceiver
,D/Jerry   ( 3840): start to preload cursor >>>>>>>
,D/Messaging( 3840): mNeedToUpdateDate2: false
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 60
,D/AccFlag ( 1217): sku_id=99
,D/TelephUtils( 1217): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,V/MmsProvider( 1217): Update uri=content://mms, match=0
,V/MmsProvider( 1217): selection=st=129 AND m_type!=134
D/DraftCache( 3840): [DraftCache/385] rebuildCache
,D/Messaging( 3840): Reset downloading state: 0
V/MmsSystemEventReceiver( 3840): TransactionService is going to be woken up.
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/MmsSmsV2Provider( 1217):  phoneType = -1
,D/MmsSmsV2Provider( 1217): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,I/ActivityManager(  907): Delaying start of: ServiceRecord{428bcc08 u0 com.htc.sense.mms/.transaction.TransactionService}
D/Messaging( 3840): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/MmsSmsV2Provider( 1217):  phoneType = -1
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/Jerry   ( 1217): URI_DRAFT
D/Messaging( 3840): ViewCache CreatePreload
D/Messaging( 3840): ViewCache CreatePreloadOnlyMultipleOpsList
D/DraftCache( 3840): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3840): [DraftCache/385] rebuildCache time: 1
D/MmsAsyncWorkHandler( 3840): 
D/MmsAsyncWorkHandler( 3840): HM tk = 20002
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
D/AccFlag ( 1217): sku_id=99
D/Cust_MMSMS( 3840): _has_set_default_values_2=true
D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 67
D/AccFlag ( 1217): sku_id=99
D/MsgPreferenceUtils( 3840): def_index: 0
D/MsgPreferenceUtils( 3840): globalIndex = 1
D/MsgPreferenceUtils( 3840): phone state: true
D/MsgPreferenceUtils( 3840): sd state: false
D/MsgPreferenceUtils( 3840): vIndex = 0
,V/TransactionService( 3840): 1-Creating TransactionService
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{428de1d8 u0 com.htc.musicenhancer/.EnhancerService}
V/TransactionService( 3840): onStartCommand: 1
D/MmsSystemEventReceiver( 3840): unRegisterForConnectionStateChanges
V/TransactionService( 3840): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
V/TransactionService( 3840): Loading previous transactions.
,D/TelephUtils( 1217): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1217): device_type: 1
,D/TransactionService( 3840): Force set service start id to 1
V/TransactionService( 3840): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3840): unRegisterForConnectionStateChanges
,V/TransactionService( 3840): Destroying TransactionService
,D/TransactionService( 3840): stopSelfResult: true, mLastHandledServiceId: 1
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(429562b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 3812 10111 null
,V/TransactionService( 3840): 4-Handling incoming message: { when=-15ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  907): releaseWL(429562b0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
,I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2622): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  907): acquireWL(428bb230): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428bb230): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42a21bf8): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42a21bf8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42951578): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42951578): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42af5218): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42af5218): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427ed098): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427ed098): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42a6c3d0): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42a6c3d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42ae0850): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42ae0850): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2622): UpdateCorporaTask done [took 233 ms] updated apps [took 233 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(42279890): PARTIAL_WAKE_LOCK  AsyncService 0x1 3688 10160 null
,D/PMS     (  907): releaseWL(42279890): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 1992): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1992): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/Icing   ( 1992): updateResources: need to parse f{com.google.android.gms}
D/PMS     (  907): acquireWL(42aefef0): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3436): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(42aee958): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 3454 10154 null
,I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,W/ContextImpl( 3454): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=3454, uid=10154, userID:0
,I/MusicLeanback( 3454): Conditions not met for autocaching.
,I/MusicLeanback( 3454): Stop autocaching.
,W/ContextImpl( 3454): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/PMS     (  907): releaseWL(42aee958): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3942 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/SyncApplication( 3942): Loading default preferences
,W/Resources( 3942): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 3942): Overriding preferences with custom values
,D/SyncApplication( 3942): Updating preferences succeeded
,E/SyncApplication( 3942): Application created.
D/VolumeInfo( 3942): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3942): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
,V/VolumeInfo( 3942): Found 0 mount point(s)
,V/VolumeInfo( 3942): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3942): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3942): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3942): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3942): getNewCalendarAuthority()...
,D/SyncApplication( 3942): enableAppOperation()+
,D/SyncApplication( 3942): enableAppOperation()-
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3942, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3942, uid=10008, userID:0
,W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/HTCUtilities( 3942): isNeorSinged() + 
,D/HTCUtilities( 3942): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3942): isNeorSinged() return false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3812/10111)
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 8 times.
,D/CDMountReceiver( 3942): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 3942): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/DotMatrix( 1554): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,I/RemoteViews( 1107): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{41f284d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.nero.android.htc.sync 2 20 6 11
,I/RemoteViews( 1107): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1107): release indeterminate drawable android.widget.OnDemandProgressBar{42183ed8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1107): com.nero.android.htc.sync 1 15 3 16
,D/CDMountReceiver( 3942): enable CD Auto-mount: true
I/ActivityManager(  907): Delay finish: com.nero.android.htc.sync/.CDMountReceiver
,D/HTCUtilities( 3942): enable auto-mount
,D/HTCUtilities( 3942): enable auto-mount
,D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
,D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): releaseWL(4285c728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/Icing   ( 1992): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 1992): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(42aefef0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,W/MediaManager( 3436): [DualLensScanUtil]	mmpCursor count is 0
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(427a2b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(427a2b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42933210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(42933210): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,I/GAV2    ( 3789): Thread[GAThread,5,main]: No campaign data found.
,I/GAV4    ( 3812): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  907): acquireWL(428bd220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(428bd220): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/CalendarProvider2( 1470): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1470): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3973 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/CalendarApplication( 3973): onCreate
D/ProviderChangeReceiver( 3973): ---------------------------------------------------
,D/ProviderChangeReceiver( 3973): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3973): start to updateAlertNotification!
,D/Process (  907): killProcessQuiet, pid=3496
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=3987 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 3496:com.htc.sdm/u0a81 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3496
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 3973): No fired or scheduled alerts
,D/HtcAlertUtils( 3973): -- cancelReminderNotification --
,D/HtcAlertUtils( 3973): broadcastExistReminder!
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,V/Settings:HtcSettingsApplication( 3987): [3987/3987] onCreate()
W/ContextImpl( 3987): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=3583
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3583:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3583
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SensorManager(  907): mEventCount = 600
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.talk (3812/10111)
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 9 times.
,D/Finsky  ( 3729): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 3729): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  907): acquireWL(42873778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
V/AlarmManager(  907): sending alarm PendingIntent{42aae200: PendingIntentRecord{42a3b680 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452552512068, Int=0
D/PMS     (  907): releaseWL(42873778): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1341): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3729): [NET] getaddrinfo-,err=8
D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3729): [NET] getaddrinfo-, 1
D/libc    ( 3729): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3729): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3729): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3729): [NET] getaddrinfo-,err=8
D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3729): [NET] getaddrinfo-, 1
D/libc    ( 3729): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
,D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3729): [NET] getaddrinfo_proxy-
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 3729): [NET] getaddrinfo-,err=8
D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3729): [NET] getaddrinfo-, 1
,D/libc    ( 3729): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3729): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3729): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 3729): [NET] getaddrinfo-,err=8
D/libc    ( 3729): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 3729): [NET] getaddrinfo-, 1
D/libc    ( 3729): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3729): [NET] getaddrinfo_proxy-
,W/Finsky  ( 3729): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (3729/10074)
D/Finsky  ( 3729): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  907): acquireWL(4295f508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{423bb658: PendingIntentRecord{42842e30 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1452552512676, Int=0
,D/Finsky  ( 3729): [1] DailyHygiene.reschedule: Scheduling new run in 733 minutes (failures=5)
,D/PMS     (  907): acquireWL(4203dc68): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 3729 10074 null
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver
D/WearableService( 1198): callingUid 10029, callindPid: 1198
D/Finsky  ( 3729): [405] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1198): client connected with version: 8296000
,D/Finsky  ( 3729): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 3729): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1341): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): releaseWL(4295f508): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/libc    ( 3729): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 3729): [NET] getaddrinfo-,err=8
D/libc    ( 3729): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 3729): [NET] getaddrinfo-, 1
,D/libc    ( 3729): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
,D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    ( 3729): [NET] getaddrinfo_proxy-
D/PMS     (  907): releaseWL(4203dc68): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/AutoSetting( 1320): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3596
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3596:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3596
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=3635
,I/ActivityManager(  907): Killing 3635:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Recipient 3635
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 10 times.
,D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024,
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  907): [NET] getaddrinfo_proxy-,
D/PMS     (  907): acquireWL(42006cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{426ee560: PendingIntentRecord{427ba270 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=81583, Int=0,
D/PMS     (  907): releaseWL(42006cb0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/SensorManager(  907): mEventCount = 750
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 11 times.
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 12 times.
,D/PMS     (  907): acquireWL(425d3620): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(425d3620): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4218eb38): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4218eb38): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4273e908): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4273e908): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms},
,D/PMS     (  907): acquireWL(42a10698): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42a10698): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427cd710): PARTIAL_WAKE_LOCK  Icing 0x1 1992 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427cd710): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/HtcModeClient( 1470): handler message = 4011
,E/HtcModeClient( 1470): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1470): Don't start project servcice
,D/HtcModeClient( 1470): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1470): connectState: CONNECTION_READY = false
,D/SilentMusic( 1470): call stop
,D/HtcModeClient( 1470): close connection
,W/HtcModeClient( 1470): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1470): read the terminate packet, so break
,D/Process (  907): killProcessQuiet, pid=3655
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3655:com.htc.backup/1000 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3655
,D/PMS     (  907): acquireWL(42a248e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{42a51558: PendingIntentRecord{428257b0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452552527416, Int=0
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4019 uid=10078 gids={50078}
,V/AlarmManager(  907): sending alarm PendingIntent{42aa5a10: PendingIntentRecord{42a7a258 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452552530957, Int=60000
,D/PMS     (  907): releaseWL(42a248e0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4019): SMSBackupAgentService started
,D/SMSBackup( 4019): Checking restore status
,D/SMSBackup( 4019): Restore complete
,D/SMSBackup( 4019): cancelCheckAlarm
,D/SMSBackup( 4019): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/Finsky  ( 3729): [395] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3729): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  907): killProcessQuiet, pid=3622
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3622:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3622
,I/SensorManager(  907): mEventCount = 900
,V/LightsService(  907): setLight #0: color=#26
,V/LightsService(  907): setLight #0: color=#1f
,V/LightsService(  907): setLight #0: color=#18
,V/LightsService(  907): setLight #0: color=#14
,D/PMS     (  907): acquireWL(428f4710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e743e0: PendingIntentRecord{423e27f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=105086, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428f4710): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,I/ClockThread( 1107): now=1452552540042 next=59958
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@424fef38
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
W/BatSI   (  907): Couldn't get kernel wake lock stats
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@424fef38, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ddb5c0
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@42721890
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
,D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 327ms
,D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
,D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
,D/PMS     (  907): OOBE c monitor 11
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@42a4d400)
D/NfcService( 1232): ScreenObserver: OFF
,D/NfcService( 1232): applyRouting - 0
,D/NfcService( 1232): applyRouting -2
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/PMN     (  907): wakingUp
I/InputMethodManagerService(  907): Disable input method client, pid=3047
D/PMS     (  907): acquireWL(42ae3e98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMS     (  907): releaseWL(42ae3e98): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/PMN     (  907): onScreenOn
D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
,D/PMS     (  907): acquireWL(42910e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,D/MtpService( 2197): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/NfcService( 1232): applyRouting - 0
,D/AutoSetting( 1320): receiver - intent: android.intent.action.USER_PRESENT
D/MtpService( 2197): [MTP][onReceive]-
,I/IntentController( 1107): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42910e70): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  907): acquireWL(42a55d10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1232 1027 null
,D/NfcService( 1232): applyRouting -2
D/PMS     (  907): releaseWL(42a55d10): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
,D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/AutoSetting( 1320): service - onCreate()
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/TetherSettings( 3712): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3712): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3712): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3712): Cust_ConnectToPC   : spcsc>false
D/        ( 3712): Cust_ConnectToPC   : IPT>true
,D/        ( 3712): Cust_ConnectToPC   : Singel_USB>false
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
,I/HtcPowerSaver(  907): >> updateStatus
D/AutoSetting( 1320): service - AddressCache: using context: com.htc.Weather
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
,W/Settings( 3712): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/WifiNative-wlan0(  907):    returned false
E/SmartNS_Utility( 3712): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3712): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3712): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/LocationManagerService(  907): request 428414a0 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/AutoSetting( 1320): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,I/ClockThread( 1107): stop update clock
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
V/SRS_Proc(  370): ParamSet string: screen_state=on
,I/PSReceiver( 3712): onReceive:android.intent.action.USER_PRESENT
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ContextImpl( 3712): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3712): onReceive:android.intent.action.USER_PRESENT
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
W/Settings( 3712): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3712):  defaultType:0
D/NetworkPolicy(  907): updateScreenOn: false
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): acquireWL(42c1a8c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42c1a8c8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4046 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/PMS     (  907): acquireWL(429ea520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429ea520): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ddb5c0
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41ddb5c0, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@42721890
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
,D/PMS     (  907): acquireWL(42ab3f38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42ab3f38): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl( 4046): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF,
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20186 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
,D/WifiNative-wlan0(  907):    returned false
I/AlarmManager(  907): [AlarmQueuing] wifi connection: false
D/PMS     (  907): acquireWL(42c249b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,V/SRS_Proc(  370): ParamSet string: screen_state=off
D/PMS     (  907): releaseWL(42c249b8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1217): start background delete task...
D/ContactMessageStore( 1217): size: 0 , 0
,D/ContactMessageStore( 1217): Background delete complete
,D/SmartSyncUtils( 4046): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(42a97cd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4046 1000 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4046): getMobilePolicyEnabled, result = true
D/PMS     (  907): releaseWL(42a97cd8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,W/ContextImpl( 4046): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4046): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4046): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4046): isEpsOn(), nState = 0
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] getTotalRam: 1873 Mb
D/WifiService(  907): New client listening to asynchronous messages
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42721890
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42721890, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
,W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42721890, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42721890
D/PMS     (  907): acquireWL(42acf0b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42acf0b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425686f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425686f8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  907): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  907): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  907): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  907): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  907): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  907): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  907): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  907): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  907): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  907): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  907): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  907): 	at dalvik.system.NativeStart.main(Native Method)
D/PMS     (  907): acquireWL(429dff10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429dff10): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1320): service - mHandler: cancel location update
,D/AutoSetting( 1320): service -           changes count: 0
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  907): killProcessQuiet, pid=3477
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3477:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3477
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{42b17cb0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  907): acquireWL(42a89048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/PMS     (  907): releaseWL(42a89048): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1107): closing low battery warning: level=100
,D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(42b0a760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{427ae228: PendingIntentRecord{428218b0 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=137778, Int=0
,D/PMS     (  907): releaseWL(42b0a760): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1320): service - handleMessage() stop self
,D/AutoSetting( 1320): service - onDestroy() END
,D/AutoSetting( 1320): service - handleMessage() quit looper
,D/Process (  907): killProcessQuiet, pid=3673
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3673:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3673
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(42af10c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42804b78: PendingIntentRecord{42a73b48 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=126250, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{426ee560: PendingIntentRecord{427ba270 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=141589, Int=0
,D/PMS     (  907): acquireWL(42b138d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
,D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,V/AlarmManager(  907): sending alarm PendingIntent{4282d370: PendingIntentRecord{42825e60 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=141597, Int=0
D/libc    (  907): [NET] getaddrinfo-, 1
D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    (  907): [NET] getaddrinfo_proxy-
,D/PMS     (  907): releaseWL(42b138d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:false mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(42acb4c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42af10c8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  907): releaseWL(42acb4c0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 3
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,D/PMS     (  907): acquireWL(42ad27d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{41e743e0: PendingIntentRecord{423e27f8 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=165086, Int=0
,I/IntentController( 1107): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42ad27d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42c1b710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/UsbnetService(  907): BroadcastReceiver::onReceive+
I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,
D/PMS     (  907): releaseWL(42c1b710): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo,
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...,
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 4
,D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
,D/PMS     (  907): acquireWL(429fce08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1107): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1554): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1554): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(429fce08): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PowerUI ( 1107): closing low battery warning: level=100
D/PowerUI ( 1107): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1107): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  413): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  907): acquireWL(42a7de80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42942920: PendingIntentRecord{42a73b48 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=186037, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{426ee560: PendingIntentRecord{427ba270 android broadcastIntent}}, i=com.android.server.NetworkTimeUpdateService.action.POLL, t=3, cnt=1, w=201626, Int=0
,D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
,D/PMS     (  907): acquireWL(42c08a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
,D/libc    (  363): [NET] getaddrinfo+,hn 22(0x322e616e64726f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
,D/libc    (  907): [NET] getaddrinfo_proxy-
D/PMS     (  907): releaseWL(42a7de80): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,D/PMS     (  907): acquireWL(42a66460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42c08a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42a66460): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42b09ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(42b09ca8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(429e2c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): acquireWL(42c12270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1198): Vacuum at: now=1452552636830 tag=VacuumService
D/PMS     (  907): releaseWL(429e2c68): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42c12270): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42ac75c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(42ac75c8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42aa8168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1341 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1341/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360023934
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024043
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024115
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024122
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024128
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360024135
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025352
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025370
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360028604
,D/PMS     (  907): releaseWL(42aa8168): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4077): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4077): ====startRecUseTime====
D/htc.customization.log.level( 4077):  is 
W/CustomizationLogLevel( 4077): Level value is invalid, use default level 2
D/CustomizationManager( 4077):  Read ACC file spent 0.095 (s)
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4077): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4077): Parsing tag category name = system
I/CustomizationCIDLoader( 4077): Parsing tag category name = application
I/CustomizationCIDLoader( 4077): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4077): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4077): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4077): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4077): Parsing tag category name = Settings
D/CustomizationManager( 4077):  Read CID file spent 0.144 (s)
D/CustomizationManager( 4077):  All configurations done spent 0.144 (s)
W/HtcNativeFlag( 4077): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4077): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4077): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4077): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=4077, uid=2000 user=0
I/ActivityManager(  907): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
D/Process (  907): killProcessQuiet, pid=3047
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
W/asset   (  907): Copying FileAsset 0x639a6440 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  907): Killing 3047:com.example.hello/u0a397 (adj 0): stop com.example.hello
I/ActivityManager(  907):   Force finishing activity ActivityRecord{42aee270 u0 com.example.hello/.MainActivity t2}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/InputDispatcher(  907): channel '4290fe50 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '4290fe50 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
I/WindowState(  907): WIN DEATH: Window{42c0c800 u0 com.example.hello/com.example.hello.MainActivity}
W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4290fe50 com.example.hello.MainActivity (s)'
I/WindowState(  907): WIN DEATH: Window{4290fe50 u0 com.example.hello/com.example.hello.MainActivity}
I/WindowManager(  907): WINDOW DIED Window{4290fe50 u0 com.example.hello/com.example.hello.MainActivity}
W/PackageSettings(  907): Skipping PackageSetting{424cfd70 com.test.thalitest/10389} due to missing metadata
W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3047 uid 10397
W/Binder  ( 1185): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1185): java.lang.NullPointerException
W/Binder  ( 1185): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1185): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1185): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1185): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  907): Force stopping com.example.hello appid=10397 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1554): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1554): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1107): ApplicationsIntentReceiver replacing:false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/AccTypeManager( 1307): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1198): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(42bad3e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1198 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42bad3e8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/VoicemailCleanupService( 1276): Cleaning up data for package: com.example.hello
I/Launcher( 1249): Deferring update until onResume
D/Launcher( 1249): waitUntilResume // bindAppsRemoved
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
W/AccTypeManager( 1307): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1307): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/[PluginManager]RegisterService( 1320): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/[PluginManager]RegisterService( 1320): handle notify Blinkfeed plugin client changed
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  907):   Scheme: "mmsto"
D/Prism.PackageStateRece_( 1249): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
I/IcingCorporaProvider( 2622): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
F/PackageManager(  907): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  907): java.io.IOException: write failed: EBADF (Bad file number)
F/PackageManager(  907): 	at libcore.io.IoBridge.write(IoBridge.java:455)
F/PackageManager(  907): 	at java.io.FileOutputStream.write(FileOutputStream.java:187)
F/PackageManager(  907): 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
F/PackageManager(  907): 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
F/PackageManager(  907): 	at com.android.internal.util.FastXmlSerializer.flush(FastXmlSerializer.java:254)
F/PackageManager(  907): 	at com.android.internal.util.FastXmlSerializer.append(FastXmlSerializer.java:92)
F/PackageManager(  907): 	at com.android.internal.util.FastXmlSerializer.escapeAndAppendString(FastXmlSerializer.java:145)
F/PackageManager(  907): 	at com.android.internal.util.FastXmlSerializer.attribute(FastXmlSerializer.java:176)
F/PackageManager(  907): 	at com.android.server.PreferredComponent.writeToXml(PreferredComponent.java:189)
F/PackageManager(  907): 	at com.android.server.pm.PreferredActivity.writeToXml(PreferredActivity.java:50)
F/PackageManager(  907): 	at com.android.server.pm.Settings.writePreferredActivitiesLPr(Settings.java:1111)
F/PackageManager(  907): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1212)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  907): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  907): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  907): Caused by: libcore.io.ErrnoException: write failed: EBADF (Bad file number)
F/PackageManager(  907): 	at libcore.io.Posix.writeBytes(Native Method)
F/PackageManager(  907): 	at libcore.io.Posix.write(Posix.java:202)
F/PackageManager(  907): 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:197)
F/PackageManager(  907): 	at libcore.io.IoBridge.write(IoBridge.java:450)
F/PackageManager(  907): 	... 17 more
E/ExternalAccountType( 1307): Unsupported attribute readOnly
D/UserBehaviorLoggingService(  907): [getSecurityProperties] Access Denied, Unknown pacakage name!
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  907): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.lang.IllegalArgumentException: key == null
E/ErrorReport(  907): 	at javax.crypto.spec.SecretKeySpec.<init>(SecretKeySpec.java:59)
E/ErrorReport(  907): 	at com.htc.utils.ulog.io.LogStream$CipherStream.getCipherOutputStream(LogStream.java:223)
E/ErrorReport(  907): 	at com.htc.utils.ulog.io.LogStream.concatenateOutputStream(LogStream.java:101)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:389)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  907): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  907): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  907): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  907): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  907): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  907): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  907): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  907): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  907): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/PackageManager(  907): Preserving older stopped packages backup
F/PackageManager(  907): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  907): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  907): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  907): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  907): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  907): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  907): 	... 9 more
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
I/PackageManager(  907): Failed to clean up mangled file: /data/system/packages-stopped.xml
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452552644626.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  907): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  907): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  907): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  907): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  907): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  907): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  907): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  907): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  907): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 18 more
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
W/PackageManager(  907): Preserving older stopped packages backup
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4095 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
F/PackageManager(  907): Unable to write package manager user packages state,  current changes will be lost at reboot
F/PackageManager(  907): java.io.FileNotFoundException: /data/system/users/0/package-restrictions.xml: open failed: EROFS (Read-only file system)
F/PackageManager(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
F/PackageManager(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
F/PackageManager(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
F/PackageManager(  907): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1145)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
F/PackageManager(  907): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
F/PackageManager(  907): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
F/PackageManager(  907): 	at android.os.Binder.execTransact(Binder.java:412)
F/PackageManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
F/PackageManager(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
F/PackageManager(  907): 	at libcore.io.Posix.open(Native Method)
F/PackageManager(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
F/PackageManager(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
F/PackageManager(  907): 	... 9 more
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
E/SQLiteLog( 2622): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2622): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle = 0x64313398
W/dalvikvm( 2622): threadid=16: thread exiting with uncaught exception (group=0x419a9e30)
E/AndroidRuntime( 2622): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2622): Process: com.google.android.googlequicksearchbox:search, PID: 2622
E/AndroidRuntime( 2622): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2622): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2622): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2622): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2622): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2622): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2622): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/AndroidRuntime( 2622): 	at cid.d(PG:186)
E/AndroidRuntime( 2622): 	at clo.g(PG:594)
E/AndroidRuntime( 2622): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:301)
E/AndroidRuntime( 2622): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/AndroidRuntime( 2622): 	at android.content.ContentResolver.update(ContentResolver.java:1339)
E/AndroidRuntime( 2622): 	at clp.Rl(PG:910)
E/AndroidRuntime( 2622): 	at clr.tL(PG:827)
E/AndroidRuntime( 2622): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1271)
E/AndroidRuntime( 2622): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1204)
E/AndroidRuntime( 2622): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2622): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2622): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/PackageManager(  907): Failed to clean up mangled file: /data/system/packages-stopped.xml
D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/SYSTEM_WTF@1452552644679.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:540)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:227)
E/ErrorReport(  907): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:10800)
E/ErrorReport(  907): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:10685)
E/ErrorReport(  907): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:379)
E/ErrorReport(  907): 	at android.util.Log$1.onTerribleFailure(Log.java:104)
E/ErrorReport(  907): 	at android.util.Log.wtf(Log.java:293)
E/ErrorReport(  907): 	at android.util.Log.wtf(Log.java:286)
E/ErrorReport(  907): 	at com.android.server.pm.Settings.writePackageRestrictionsLPr(Settings.java:1238)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.addPreferredActivityInternal(PackageManagerService.java:11872)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.replacePreferredActivity(PackageManagerService.java:11928)
E/ErrorReport(  907): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:1005)
E/ErrorReport(  907): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2171)
E/ErrorReport(  907): 	at android.os.Binder.execTransact(Binder.java:412)
E/ErrorReport(  907): 	at dalvik.system.NativeStart.run(Native Method)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 18 more
E/ActivityManager(  907): App crashed! Process: com.google.android.googlequicksearchbox:search
D/Process ( 2622): killProcess, pid=2622
D/Process ( 2622): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 frq.uncaughtException:58 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Recipient 2622
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.googlequicksearchbox (pid 2622): Died!
D/WifiService(  907): Client connection lost with reason: 4
I/ActivityManager(  907): Process com.google.android.googlequicksearchbox:search (pid 2622) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10999ms
D/Process (  907): killProcessQuiet, pid=3875
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.appDiedLocked:4131 
I/ActivityManager(  907): Killing 3875:com.htc.task/u0a71 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3875
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/SQLiteDatabase( 4095): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
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
E/SQLiteDatabase( 4095): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4095): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4095): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4095): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4095): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4095): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4095): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4095): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4095): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4095): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4095): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4095): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4095): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4095): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4095): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4095): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4095): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4095): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4095): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4095): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4095): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4095): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4095): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4095): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4095): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4095): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4095): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4095): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4095): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4095): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4095): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4095): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4095): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4095): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4095): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4095): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4095): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4095): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4095): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4095): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4095): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4095): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4095): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4095): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4095): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4095): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4095): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4095): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4095): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4095): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4095): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4095): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4095): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4095): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4095): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4095): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
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
E/SQLiteDatabase( 4095): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4095): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4095): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4095): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4095): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4095): threadid=11: thread exiting with uncaught exception (group=0x419a9e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4095): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4095): Process: com.google.android.apps.docs, PID: 4095
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
E/AndroidRuntime( 4095): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4095): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4095): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4095): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4095): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
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
D/Process ( 4095): killProcess, pid=4095
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4111 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process ( 4095): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/PackageManager(  907): Unable to load service info ResolveInfo{4270efe8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
I/ActivityManager(  907): Recipient 4095
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=3840
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3840:com.htc.sense.mms/u0a65 (adj 15): empty #17
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4095) has died.
W/ContextImpl( 4111): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
E/SQLiteDatabase( 4111): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4111): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4111): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4111): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4111): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4111): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4111): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4111): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4111): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4111): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4111): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4111): threadid=10: thread exiting with uncaught exception (group=0x419a9e30)
E/AndroidRuntime( 4111): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4111): Process: com.android.keychain, PID: 4111
E/AndroidRuntime( 4111): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4111): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4111): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4111): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4111): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4111): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4111): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4111): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4111): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4111): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  907): App crashed! Process: com.android.keychain
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4124 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4111): killProcess, pid=4111
D/Process ( 4111): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452552645371.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  907): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  907): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  907): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  907): 	... 4 more
D/AppTag  ( 4124): getInstance(Context context)
D/AppTag  ( 4124): getInstance(Context context)
D/AppTag  ( 4124): onCreate()
I/ActivityManager(  907): Recipient 4111
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4111) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 10422ms
I/ActivityManager(  907): Recipient 3840
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(42a7d988): PARTIAL_WAKE_LOCK  AsyncService 0x1 3688 10160 null
D/PMS     (  907): releaseWL(42a7d988): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 3729): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 1992): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 1992): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1992): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1992): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1992): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 1992): Removing dialog suppression flag for package com.example.hello
E/SQLiteLog( 1992): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1992): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x65f9c920
W/dalvikvm( 1992): threadid=31: thread exiting with uncaught exception (group=0x419a9e30)
I/Prism.ItemManager( 1249): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1249): loadItems() com.htc.launcher.pageview.WidgetManager@41e6beb0 +
I/Prism.WidgetManager( 1249): onLoadItems() +
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 1992): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 1992): Process: com.google.android.gms, PID: 1992
E/AndroidRuntime( 1992): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1992): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 1992): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 1992): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 1992): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 1992): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 1992): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 1992): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 1992): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 1992): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 1992): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 1992): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 1992): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 1992): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 1992): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 1992): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 1992): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 1992): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 1992): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 1992): killProcess, pid=1992
D/Process ( 1992): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
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
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml

```
