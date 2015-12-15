#### Test 5038801913f4183_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/Process (  909): killProcessQuiet, pid=2923
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
--------- beginning of /dev/log/system
I/ActivityManager(  909): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.apps.youtube.core.transfer.DownloadService$BootReceiver: pid=3175 uid=10168 gids={50168, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Killing 2923:com.htc.mobiledata/u0a91 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2923
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/YouTube ( 3175): apps.youtube.mdx.d.b.a:38 YouTube MDx: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc    ( 3175): [NET] getaddrinfo+,hn 9(0x3132372e302e30),sn(),family 0,flags 4
D/libc    ( 3175): [NET] getaddrinfo-, SUCCESS
D/YouTube ( 3175): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.youtube (3175/10168)
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3175): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
E/cutils-trace( 3189): Error opening trace file: No such file or directory (2)
D/YouTube ( 3175): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/YouTube ( 3175): apps.youtube.common.network.m.a:40 HttpClient.UserAgent: com.google.android.youtube/5.9.0.13(Linux; U; Android 4.4.4; en_GB; HTC Desire 820 Build/KTU84P)
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
D/YouTube ( 3175): apps.youtube.common.cache.f.run:163 Cache is below limit, no need to shrink: [size=0, limit=20971520]
D/YouTube ( 3175): apps.youtube.core.player.LocalDirector.c:265 VideoStage: NEW
D/CustomizationManager( 3189): ====startRecUseTime====
D/htc.customization.log.level( 3189):  is 
W/CustomizationLogLevel( 3189): Level value is invalid, use default level 2
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
D/MediaRouterService(  909): Client com.google.android.youtube (pid 3175): Registered
I/MediaRouter( 3175): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
D/YouTube ( 3175): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 3175): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1450198984&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  909): getNetworkInfo networkType=0 called by com.google.android.youtube (3175/10168)
D/libc    ( 3175): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3175): [NET] getaddrinfo-,err=8
D/libc    ( 3175): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3175): [NET] getaddrinfo-, 1
D/libc    ( 3175): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =33b5 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3175): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3175): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/MediaRouter( 3175): getSelectedRoute
D/YouTube ( 3175): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3175): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.youtube (3175/10168)
D/YouTube ( 3175): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 281
D/libc    (  363): [NET]res_nsend:resplen=96
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3175): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.youtube (3175/10168)
D/CustomizationManager( 3189):  Read ACC file spent 0.069 (s)
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3189): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3189): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3189): Parsing tag category name = system
I/CustomizationCIDLoader( 3189): Parsing tag category name = application
I/CustomizationCIDLoader( 3189): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3189): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3189): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3189): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3189): Parsing tag category name = Settings
D/CustomizationManager( 3189):  Read CID file spent 0.121 (s)
D/CustomizationManager( 3189):  All configurations done spent 0.121 (s)
W/HtcNativeFlag( 3189): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3189): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3189): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3189): Fail to get flag for type 'language', use default value: -1
I/ActivityManager(  909): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3235 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.youtube (3175/10168)
D/YouTube ( 3175): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/Process (  909): killProcessQuiet, pid=2935
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 2935:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
W/CpuWake (  909): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  909): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  909): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  909): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3189
D/PMS     (  909): acquireHCC(4258e988): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 909 1000 null
W/asset   (  909): Copying FileAsset 0x680e0958 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  909): @test_code: getHtcIntentFlag: 0 obj: 1114166064
D/PMS     (  909): acquireHCC(42681ed0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 909 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41bfe2a0
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  909): acquireWL(426195e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 909 1000 null
I/ActivityManager(  909): Recipient 2935
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3252 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
I/GoogleConversionPing( 3175): Ping responded with response code 200
D/YouTube ( 3175): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3175): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3175): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
W/asset   ( 3252): Copying FileAsset 0x5c711428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1269): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3252): Binding Chromium to main looper Looper (main, tid 1) {41aa32a0}
I/LibraryLoader( 3252): Expected native library version number "",actual native library version number ""
I/chromium( 3252): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3252): Initializing chromium process, renderers=0
D/PMS     (  909): acquireWL(428d3160): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): acquireWL(425d6c90): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  909): releaseWL(428d3160): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/System.err(  909): java.lang.Throwable: stack dump
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@41b9b308:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3252): 1101761672: getState(). Returning 12
I/Adreno-EGL( 3252): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3252): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3252): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3252): Local Branch: 
I/Adreno-EGL( 3252): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3252): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3252):                  aa63bbd948f41d15fc72f585e
W/dalvikvm( 3235): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
W/chromium( 3252): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3235, uid=10074, userID:0
W/dalvikvm( 3252): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3252): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3252): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
D/Finsky  ( 3235): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
W/dalvikvm( 3252): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3252): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3252): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3252): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3252): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3252): CordovaWebView is running on device made by: HTC
D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (3235/10074)
,W/dalvikvm( 3235): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 3235): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  909): getAllNetworkInfo called by com.android.vending (3235/10074)
W/AwContents( 3252): nativeOnDraw failed; clearing to background color.
D/Finsky  ( 3235): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 3235): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
I/InputMethodManagerService(  909): Disable input method client, pid=1269
W/ResourceType( 3252): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3252): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41aea138, mServedView=org.apache.cordova.engine.SystemWebView{41aaffa8 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/Settings( 3235): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3235): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/InputMethodManagerService(  909): Enable input method client, pid=3252
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/AwContents( 3252): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  909): Displayed com.example.hello/.MainActivity: +272ms
W/dalvikvm( 3235): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/PMS     (  909): releaseWL(426195e8): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/dalvikvm( 3235): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3235): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3235): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3235, uid=10074, userID:0
D/Volley  ( 3235): [297] DiskBasedCache.clear: Cache cleared.
D/Process (  909): killProcessQuiet, pid=2972
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Ads     ( 3235): Skipping gmscore version check
I/ActivityManager(  909): Killing 2972:com.google.android.gm/u0a107 (adj 15): empty #17
D/Finsky  ( 3235): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3235): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 3235): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Volley  ( 3235): [304] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  909): Recipient 2972
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Finsky  ( 3235): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
E/AndroidProtocolHandler( 3252): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3252): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 3252): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 3252): JniHelper::setJavaVM(0x41578048), pthread_self() = 1658047432
D/JX-Cordova( 3252): jxcore cordova android initializing
W/dalvikvm( 2182): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2182): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2182): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2182): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/PMS     (  909): acquireWL(4278ba58): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2182 10029 null
I/ActivityManager(  909): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/PMS     (  909): acquireWL(4268a918): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
D/FileApkUtils( 2182): Spent 22ms computing apk sha1.
D/FileApkUtils( 2182): Module already staged or being staged:chimera-modules/MapsModule.apk
D/DexOptUtils( 2182): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 2182): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 2182): Reading stored module config
D/PMS     (  909): releaseWL(4278ba58): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  909): releaseWL(4268a918): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Resuming delayed broadcast
W/jxcore-log( 3252): Initializing JXcore engine
W/jxcore-log( 3252): JXcore engine is ready
W/jxcore-log( 3252): Starting JXcore engine
D/WIFI_ICON( 1117): WifiActivity: 3
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/GmsModuleFndr( 2182): Beginning GMS chimera module scan
W/asset   ( 2182): Copying FileAsset 0x66b121b8 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
D/ChimeraCfgMgr( 2182): Beginning module configuration check
W/InstanceID/Rpc( 2182): Found 10029
D/ChimeraCfgMgr( 2182): Module APKs unchanged, check complete
E/dalvikvm( 2182): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 2182): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 2182): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2182): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2182): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2182): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2182): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 2182): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2182): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
E/dalvikvm( 2182): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 2182): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
E/dalvikvm( 1224): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1224): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1224): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1224): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1224): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1224): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1224): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [5][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 1224): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1224): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/PMS     (  909): acquireWL(427f7340): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/PMS     (  909): acquireWL(427cec60): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
E/dalvikvm( 2182): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 2182): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 2182): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/jxcore-log( 3252): Platform android
W/jxcore-log( 3252): 
W/jxcore-log( 3252): Process ARCH arm
W/jxcore-log( 3252): 
W/dalvikvm( 2182): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
W/dalvikvm( 2182): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
D/GCM     ( 2182): COMPAT: Multi user not supported
D/GCM     ( 1362): COMPAT: Multi user not supported
D/PMS     (  909): acquireWL(4279e670): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427f7340): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1362): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/CheckinService( 2182): Checkin interval check for package: unspecified last checkin: 1450196925722 min interval config: 0 actual interval: 2060080
I/GCoreUlr( 2182): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
W/dalvikvm( 1362): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
I/GCoreUlr( 1224): DispatchingService.onCreate()
I/CheckinService( 2182): Disabling old GoogleServicesFramework version
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
I/jxcore-log( 3252): JXcore Cordova bridge is ready!
I/jxcore-log( 3252): 
W/jxcore-log( 3252): JXcore engine is started
W/dalvikvm( 2182): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2182): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/SystemUpdateService( 2182): onCreate
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2182, uid=10029, userID:0
D/SystemUpdateService( 2182): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
W/dalvikvm( 2182): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
W/dalvikvm( 1362): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1362): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/AuthZen ( 2182): Handling intent: android.intent.action.BOOT_COMPLETED
W/dalvikvm( 1362): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1362): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
W/dalvikvm( 1362): VFY: unable to resolve instance field 161
D/PMS     (  909): acquireWL(42673780): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
E/jxcore-log( 3252): >> HTC-HTC Desire 820
E/jxcore-log( 3252): 
I/jxcore-log( 3252): Total memory 1964650496
I/jxcore-log( 3252): 
I/jxcore-log( 3252): Free memory 644710400
I/jxcore-log( 3252): 
I/jxcore-log( 3252): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3252): 
I/jxcore-log( 3252): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3252): 
D/PMS     (  909): acquireWL(4265e958): PARTIAL_WAKE_LOCK  Icing 0x1 2182 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
I/jxcore-log( 3252): userPath [ 'www' ]
I/jxcore-log( 3252): 
I/jxcore-log( 3252): Size 720 1184
I/jxcore-log( 3252): 
I/jxcore-log( 3252): Screen Brightness 142
I/jxcore-log( 3252): 
I/SystemUpdateService( 2182): cancelUpdate (empty URL)
I/SystemUpdateService( 2182): active receiver: disabled
E/jxcore-log( 3252): Dummy Error Log.
E/jxcore-log( 3252): 
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
D/WifiService(  909): New client listening to asynchronous messages
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2182, uid=10029, userID:0
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
W/dalvikvm( 2182): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2182, uid=10029, userID:0
D/PMS     (  909): releaseWL(4265e958): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2182): Checking schedule, now: 1450198985909 next: 1450719862690
I/CheckinService( 2182): active receiver: disabled
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
D/PMS     (  909): releaseWL(4279e670): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1224): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2182, uid=10029, userID:0
W/dalvikvm( 1362): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/SystemUpdateService( 2182): onDestroy
D/PMS     (  909): releaseWL(427cec60): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
D/AuthZenEventHandler( 2182): Handling event: android.intent.action.BOOT_COMPLETED
W/dalvikvm( 1362): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  909):    returned true
D/WifiStateMachine(  909): [ScoreAP] + current TXpacket:25, mTXpacketCount:19, avgLinkspeed:72,mAvgTxRate54
D/WifiStateMachine(  909): [ScoreAP] + fetchRssiAndLinkSpeedNative: Update RSSI:-52 and linkspeed:72 in database
D/WifiApDatabaseHandler(  909): updateConnectedAP...
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
W/BaseAppContext( 2182): Using Auth Proxy for data requests.
D/GCM     ( 1362): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
W/dalvikvm( 2182): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2182): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1362): [NET] getaddrinfo-, 1
D/libc    ( 1362): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =f9aa +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  363): [NET] NOT IN CACHE
D/PMS     (  909): acquireWL(42529738): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
W/dalvikvm( 2182): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2182): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
E/BaseAppContext( 2182): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/dalvikvm( 2182): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
I/AuthZen ( 2182): Fetching signing key...
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1224, uid=10029, userID:0
,D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 127
D/libc    (  363): [NET]res_nsend:resplen=79
,D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1362): [NET] getaddrinfo_proxy-, success
,I/AuthZen ( 2182): Signing key fetched successfully!
,W/BaseAppContext( 2182): Using Auth Proxy for data requests.
,D/AuthZenTransactionCache( 2182): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2182): Clearing transaction cache
,D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
,I/GCoreUlr( 1224): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  909): acquireWL(41e8e3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1224): Unbound from all location providers
,I/GCoreUlr( 1224): Place inference reporting - stopped
D/PMS     (  909): releaseWL(41e8e3d0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(42673780): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
,I/GCoreUlr( 1224): DispatchingService.onDestroy()
,I/GCoreUlr( 1224): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1224): Unbound from all location providers
,I/GCoreUlr( 1224): Place inference reporting - stopped
D/libc    ( 1362): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1362): [NET] getaddrinfo-,err=8
D/PMS     (  909): acquireWL(4257ae80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4257ae80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,I/GCM     ( 1362): GCM config loaded
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
W/dalvikvm( 1362): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1362): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 1362): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
,D/PMS     (  909): acquireWL(425cb9b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/PMS     (  909): releaseWL(42529738): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1362/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: starting a change hold
,D/PMS     (  909): releaseWL(425cb9b0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  909): acquireWL(4231f690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1362/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/ConnectivityService(  909): reportInetCondition for net 1, percentage: 100 by  (1362/10029)
D/ConnectivityService(  909): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  909): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024569
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024644
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024652
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024656
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025979
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025999
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029021
,D/PMS     (  909): releaseWL(4231f690): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=55 [9][5][0]
D/PMS     (  909): acquireWL(425d7260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,I/ActivityManager(  909): Resuming delayed broadcast
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/ChimeraCfgMgr( 2182): Loading module com.google.android.gms.gass from APK com.google.android.gms
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/BootCompletedReceiver( 2182): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2182): Got an BootCompleted event.
D/PMS     (  909): acquireWL(427d2b80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 909 1000 WorkSource{10029}
,D/PMS     (  909): releaseWL(425d7260): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/IntentController( 1117): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
,D/BootCompletedReceiver( 2182): Will NOT schedule AdAttestation signal task because it's disabled.
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(426808c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(426808c0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/dalvikvm( 1362): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
,W/Auth    ( 1362): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  909): acquireWL(426a3ec8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1362 10029 null
,D/PMS     (  909): releaseWL(426a3ec8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
D/PhoneStatusBar( 1117): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
,D/PersistentNotificationBroadcastReceiver( 1224): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/jxcore-log( 3252): getBuffer is called!!!!
I/jxcore-log( 3252): 
,D/AutoSetting( 1317): receiver - intent: android.intent.action.USER_PRESENT
D/TetherSettings( 3132): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3132): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3132): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3132): Cust_ConnectToPC   : spcsc>false
D/        ( 3132): Cust_ConnectToPC   : IPT>true
D/        ( 3132): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3132): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3132): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3132): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3132): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/PSReceiver( 3132): onReceive:android.intent.action.USER_PRESENT
W/ContextImpl( 3132): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  909): Delay finish: com.android.settings/.PSReceiver
I/SmartNS_PSService( 3132): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3132): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3132):  defaultType:0
I/ActivityManager(  909): Resuming delayed broadcast
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(424f6c78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,I/ActivityManager(  909): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3372 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/PMS     (  909): acquireWL(42688260): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 909 1000 WorkSource{10029}
,D/PMS     (  909): releaseWL(424f6c78): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(425d5e00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(427d2b80): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  909): releaseWL(425d5e00): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/browser ( 3372): Browser versionCode = 760001523 versionName = 7.0.2512153020
D/PMS     (  909): acquireWL(42632bc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
D/PMS     (  909): releaseWL(42632bc8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,W/SWE_UI  ( 3372): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3372): Loading: swewebviewchromium
,I/LibraryLoader( 3372): Time to load native libraries: 31 ms (timestamps 6538-6569)
,I/LibraryLoader( 3372): Expected native library version number "",actual native library version number ""
,I/BrowserStartupController( 3372): Initializing chromium process, renderers=9
I/LibraryLoader( 3372): Expected native library version number "",actual native library version number ""
,I/chromium( 3372): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,D/PMS     (  909): acquireWL(4278eb58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,D/PMS     (  909): releaseWL(42688260): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
,I/IntentController( 1117): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  909): releaseWL(4278eb58): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PhoneStatusBar( 1117): removeIcon slot=sync_active index=7 viewIndex=0
,D/ConnectivityService(  909): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  909): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/Adreno-EGL( 3372): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3372): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3372): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3372): Local Branch: 
I/Adreno-EGL( 3372): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3372): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3372):                  aa63bbd948f41d15fc72f585e
,V/IccIntentReceiver( 1299): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1530): SIM state: ABSENT
I/SIMStateChangeReceiver( 1530): phoneType = 0
,I/SIMStateChangeReceiver( 1530): remove notification
,I/ActivityManager(  909): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3413 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  909): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3425 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  909): killProcessQuiet, pid=2750
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 2750:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 2750
,W/CpuWake (  909): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  909): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  909): >>release mCpuPerf_Freq wakelock
W/CpuWake (  909): <<release mCpuPerf_Freq wakelock
,D/PMS     (  909): releaseHCC(4258e988): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  909): releaseHCC(42681ed0): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,W/SystemReader( 2724): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2724): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
,D/ExchangePolicystatus( 2724): onReceive()
,D/ExchangePolicystatus( 2724): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2724): onReceive(): else
,D/Process (  909): killProcessQuiet, pid=2950
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1245): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  909): Killing 2950:com.htc.cs.dm/u0a98 (adj 15): empty #17
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3440 uid=10041 gids={50041}
,D/AccTypeManager( 3425): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/Process (  909): killProcessQuiet, pid=3011
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3456 uid=10078 gids={50078}
I/ActivityManager(  909): Killing 3011:com.htc.backup/1000 (adj 15): empty #17
,W/AccTypeManager( 3425): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3425): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,D/SMSBackup( 3456): Got a database change event
,D/Process (  909): killProcessQuiet, pid=3033
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3033:com.google.android.talk/u0a111 (adj 15): empty #17
I/ActivityManager(  909): Recipient 2950
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/ExternalAccountType( 3425): Unsupported attribute readOnly
,D/AccTypeManager( 3425): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/ActivityManager(  909): Recipient 3011
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/AccTypeManager( 3425): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3425): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3468 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/WeatherUtility( 1117): can't get weather sync account
,W/WeatherRequest( 1117): request cur loc, but there is no sys cur
,E/ExternalAccountType( 3425): Unsupported attribute readOnly
,D/CalendarApplication( 3468): onCreate
D/ProviderChangeReceiver( 3468): ---------------------------------------------------
,D/ProviderChangeReceiver( 3468): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3468): start to updateAlertNotification!
W/ContextImpl( 3119): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  909): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
,D/AlertService( 3468): No fired or scheduled alerts
,D/HtcAlertUtils( 3468): -- cancelReminderNotification --
,D/HtcAlertUtils( 3468): broadcastExistReminder!
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ActivityManager(  909): Recipient 3033
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Resuming delayed broadcast
,D/Process (  909): killProcessQuiet, pid=3061
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3061:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3061
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WearableService( 1224): callingUid 10029, callindPid: 1224
,E/MDM     ( 1224): [94] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2182): Restart initialization of location
I/ActivityManager(  909): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1362): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1362): Proximity feature is not enabled.
,V/GLSActivity( 1362): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1224): No location to return for getLastLocation()
,W/FusedLocationProvider( 1224): location=null
D/PMS     (  909): acquireWL(427a6038): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(427a6038): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3489 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024569
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024644
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024652
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024656
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025979
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025999
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029021
,I/ActivityManager(  909): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3489): can't get weather sync account
,W/WeatherRequest( 3489): request cur loc, but there is no sys cur
,W/Settings( 3489): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 7 17
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  909): releaseWL(425d6c90): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  909): Resuming delayed broadcast
,D/Process (  909): killProcessQuiet, pid=3078
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3078:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3078
,I/SensorManager(  909): mEventCount = 300
I/ActivityManager(  909): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3504 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3504): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3504): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3504): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  909): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  909): Resuming delayed broadcast
,I/ActivityManager(  909): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3518 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=3092
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3092:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3092
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  909): acquireWL(4260cac0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3518 10071 null
,D/PMS     (  909): acquireWL(4260c0d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3518 10071 null
,I/ActivityManager(  909): Delay finish: com.htc.task/.TodoReceiver
,D/PMS     (  909): releaseWL(4260cac0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3518): update TASK shortcut>
,I/TodoTaskNotifyService( 3518): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  909): releaseWL(4260c0d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3518): stopSelfResult true
I/ActivityManager(  909): Resuming delayed broadcast
,D/Process (  909): killProcessQuiet, pid=3105
I/ActivityManager(  909): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3533 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  909): Killing 3105:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  909): Recipient 3105
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3545 uid=10082 gids={50082, 3003, 5012}
,I/ActivityManager(  909): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3558 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=3161
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  909): killProcessQuiet, pid=3147
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3161:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  909): Killing 3147:org.simalliance.openmobileapi.service/9987 (adj 15): empty #18
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3161
I/ActivityManager(  909): Recipient 3147
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/HtcModeClient( 1530): handler message = 4011
,E/HtcModeClient( 1530): Check connection and retry 4 times.
,I/MusicStore( 3558): Database version: 95
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/MessagingNotification( 2724): New incoming message, can't cancel notification now
,D/MessagingNotification( 2724): newMsgCnt: 0, false
,W/ContextImpl( 3558): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  909): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 72
,D/WifiNative-wlan0(  909): doBoolean: SignalStrength 97
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1184): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  909):    returned true
,W/ContextImpl( 3558): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3558): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3558): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3558): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3558, uid=10154, userID:0
,D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,D/MediaRouterService(  909): Client com.google.android.music (pid 3558): Registered
,I/MediaRouter( 3558): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.music (3558/10154)
,I/NetworkMonitor( 3558): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (2374/10021)
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  909): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3579 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3558): getSelectedRoute
,I/NetworkMonitor( 3558): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3558/10154)
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3558, uid=10154, userID:0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
,W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
,D/Process (  909): killProcessQuiet, pid=3175
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(42442bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 909 1000 null
,I/ActivityManager(  909): Killing 3175:com.google.android.youtube/u0a168 (adj 15): empty #17
,D/PMS     (  909): releaseWL(42442bc0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  909): doString: SIGNAL_POLL
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: survey data missing!
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1184): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3175
D/MediaRouterService(  909): Client com.google.android.youtube (pid 3175): Died!
,D/ACRA    ( 3579): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 3579): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3579): Looking for error files in /data/data/com.facebook.katana/app_minidumps
V/AlarmManager(  909): sending alarm PendingIntent{4252fdf8: PendingIntentRecord{424eaf90 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=44062, Int=259200000
V/AlarmManager(  909): sending alarm PendingIntent{41d0c660: PendingIntentRecord{42431b00 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=50424, Int=0
,W/SystemClassLoaderAdder( 3579): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3579): Preparing secondary program dexes.
V/DexLibLoader( 3579): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3579): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3579): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3579): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3579): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3579): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 3579): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
V/DexLibLoader( 3579): Dex already copied
D/OdexVerifier( 3579): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3579): Creating class loader
,V/DexLibLoader( 3579): Finished creating class loader
,V/DexLibLoader( 3579): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 3579): Dex already copied
,D/OdexVerifier( 3579): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3579): Creating class loader
,V/DexLibLoader( 3579): Finished creating class loader
,V/DexLibLoader( 3579): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 3579): Dex already copied
D/OdexVerifier( 3579): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3579): Creating class loader
,V/DexLibLoader( 3579): Finished creating class loader
,V/DexLibLoader( 3579): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
,V/DexLibLoader( 3579): Dex already copied
,D/OdexVerifier( 3579): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3579): Creating class loader
,V/DexLibLoader( 3579): Finished creating class loader
,V/DexLibLoader( 3579): Verifying classes from secondary dexes.
,D/DexLibLoader( 3579): DexLibLoader.ensureDexLoaded took 188 ms
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/ActivityManager(  909): Waited long enough for: ServiceRecord{428b1d48 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,W/dalvikvm( 3579): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3579): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3579): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3579): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3579): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3579): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3579): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/dalvikvm( 3579): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/BluetoothManagerService(  909): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  909): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@4243b618 mBinding = false
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  909): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 0
W/Settings:Agent(  909): >> traceCallingStack()
,W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1454
,W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
,W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  909): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  909): 
,W/Settings:Agent(  909): << traceCallingStack(): 6(ms)
,W/dalvikvm( 3579): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,D/BluetoothManagerService(  909): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  909): Sending off request.
D/BluetoothAdapterState( 1626): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1626): Setting state to 13
I/BluetoothAdapterState( 1626): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1626): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  909): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 1626): onBluetoothDisable()
I/BluetoothAdapterState( 1626): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1626): HAL bt_hal_cbacks->adapter_properties_cb
,I/BluetoothAdapterProperties( 1626): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 1626): HAL bt_hal_cbacks->ada
I/bt-btm  ( 1626): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
,D/bt-btm  ( 1626): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1626): br_edr_supported=0x0
I/bt-btm  ( 1626): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1626): always disable adv in non-discoverable non-connectable mode if no scan rsp 
,D/bt-btm  ( 1626): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1626): btm_ble_update_adv_flag old=0x0
,I/bt-btm  ( 1626): evt_type=0x3 p-cb->evt_type=0x3 
D/BluetoothAdapterProperties( 1626): Scan Mode:20
E/BTIF_CORE( 1626): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1626): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothAdapterState( 1626): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 1626): BTA_JvDeleteRecord
I/bt-btif ( 1626): BTA_JvRfcommStopServer
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btif ( 1626): BTA_JvDeleteRecord
I/bt-btif ( 1626): BTA_JvRfcommStopServer
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btif ( 1626): BTA_JvDeleteRecord
I/bt-btif ( 1626): BTA_JvRfcommStopServer
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btif ( 1626): BTA_JvDeleteRecord
I/bt-btif ( 1626): BTA_JvRfcommStopServer
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btif ( 1626): BTA_JvDeleteRecord
I/bt-btif ( 1626): BTA_JvRfcommStopServer
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btif ( 1626): BTA_JvDeleteRecord
I/bt-btif ( 1626): BTA_JvRfcommStopServer
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btm  ( 1626): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1626): BTM_SetConnectability
I/bt-btm  ( 1626): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1626): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1626): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:15
,E/bt-btif ( 1626): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1626): BTM_SEC_CLR[13]: id 52
V/BluetoothSapService( 1626): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:14
,E/bt-btif ( 1626): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1626): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1626): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1626): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1626): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1626): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1626): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1626): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1626): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1626): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:9
,I/bt-btm  ( 1626): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1626): Write Extended Inquiry Response to controller
I/bt-btm  ( 1626): Write Extended Inquiry Response to controller
I/bt-btm  ( 1626): Write Extended Inquiry Response to controller
I/bt-btm  ( 1626): Write Extended Inquiry Response to controller
I/bt-btm  ( 1626): BTM_SetDiscoverability
I/bt-btm  ( 1626): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1626): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1626): br_edr_supported=0x0
I/bt-btm  ( 1626): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1626): always disable adv in non-discoverable non-connectable mode if no scan rsp 
,D/bt-btm  ( 1626): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1626): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1626): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1626): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1626): BTM_SetConnectability
I/bt-btm  ( 1626): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1626): always disable adv in non-discoverable non-connectable mode with no scan rsp
,I/bt-btm  ( 1626): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1626): BTM_IsInquiryActive
I/bt-btm  ( 1626): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1626): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btm  ( 1626): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1626): BTM_FreeSCN 
I/bt-btm  ( 1626): BTM_SEC_CLR[4]: id 29
D/WifiManager( 3252): setWifiEnabled: Base Package Name=com.example.hello, uid=10397
E/BtOppRfcommListener( 1626): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-avp  ( 1626): AVRC_Close handle:0
,D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:4
D/WifiStateMachine(  909): WiFiDisplay: getWifidisplayApEnabled=false
D/bt-sdp  ( 1626): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1626): L2CAP - PSM: 0x0019 not found for deregistration
W/HtcDLNAServiceManager(  909): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  909): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  909): Settings:Agentvalue: 0
W/Settings:Agent(  909): >> traceCallingStack()
W/Settings:Agent(  909): Process.myPid(): 909
W/Settings:Agent(  909): Process.myTid(): 1375
W/Settings:Agent(  909): Process.myUid(): 1000
W/Settings:Agent(  909): 
W/Settings:Agent(  909): 
,W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  909): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  909): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  909): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  909): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
,W/System.err(  909): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  909): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  909): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/bt-l2cap( 1626): L2CAP - PSM: 0x0017 not found for deregistration
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
I/bt-att  ( 1626): GATT_Deregister gatt_if=3
I/bt-att  ( 1626): GATT_Deregister gatt_if=4
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  909): 
W/Settings:Agent(  909): << traceCallingStack(): 1(ms)
D/BluetoothRemoteDevices( 1626): Wake lock Aquired
,D/BluetoothManagerService(  909): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  909): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  909): Bluetooth State Change Intent: 12 -> 13
,D/WifiService(  909): New client listening to asynchronous messages
D/PMS     (  909): acquireWL(425d1478): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1626 1002 null
D/WifiService(  909): setWifiEnabled: false pid=3252, uid=10397
E/WifiService(  909): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  909): isSprintWifiRestricted(): false
I/WifiService(  909): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  909): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 1626): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1745): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1745): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ac7318
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1745): onDeInitialized
V/BluetoothPbapReceiver( 1626): ***********state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1745): cancelAllNotification
,D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1745): getNotificationManager
D/BluetoothMasReceiver( 1626): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1626): SapReceiver onReceive 
,V/BluetoothSapReceiver( 1626): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1626):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 1626): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1626): Pbap Service closeService in
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1745): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1745): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1745):  + initPendingRequestAlarm: false, mContext = null, null
D/PMS     (  909): acquireWL(42358400): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3132 1000 null
D/PMS     (  909): acquireWL(4258b288): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1224 10029 null
W/ContextImpl( 3132): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/PMS     (  909): releaseWL(4258b288): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1745): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1745): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1745): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1745):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1745): deinit: 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1745): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1745): disableBatteryAlarm: null
D/BluetoothManagerService(  909): Message: MESSAGE_UNREGISTER_ADAPTER
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1745): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1745): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1745): init: null
I/jxcore-log( 3252): ****TEST TOOK:  5091  ms ****
I/jxcore-log( 3252): 
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1745): setPendingRequestAlarm: false, mContext = null, null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1745): Exit IdleState
,D/BluetoothManagerService(  909): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@426acb70:true
D/PMS     (  909): releaseWL(42358400): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  909): acquireWL(426ae3f8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3132 1000 null
D/WirelessDisplayService(  909): getMirrorDisplayStatus:falsecurState:1
I/jxcore-log( 3252): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3252): 
D/WifiPerfLock(  909): release()
D/WifiStateMachine(  909): PerfLock released for exiting ConnectedState
W/System.err(  909): java.lang.Throwable: stack dump
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
,D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@428aac98:true
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  909):    returned true
I/LocationAgent( 3132): new LocationAgent instance!!
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
V/BluetoothPbapService( 1626): successfully stopped pbap service
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
V/BluetoothPbapService( 1626): Pbap Service closeService out
V/BluetoothSapService( 1626): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1626): state: 13
D/WifiNative-wlan0(  909):    returned true
D/ConnectivityService(  909): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  909): acquireWL(42363710): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 909 1000 null
I/ActivityManager(  909): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=3596 uid=10040 gids={50040, 3002, 3001}
D/WifiP2pService(  909): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothAdapter( 1626): 1101761312: getState(). Returning 13
V/BluetoothSapService( 1626): Stopping SAP server process
V/BluetoothSapService( 1626): Sap Service closeSapService in
D/libc    (  909): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/HtcTagManager( 3132): HtcTagManager construction complete
V/BluetoothSapService( 1626): Close listen Socket : 
V/BluetoothSapService( 1626): Close rfcomm Socket : 
V/BluetoothSapService( 1626): Close sapd  Socket : 
V/BluetoothSapReceiver( 1626): BluetoothSapReceiver deinit
D/DhcpStateMachine(  909): [RunningState] Stop DHCP
V/BluetoothSapService( 1626): successfully stopped Sap service
V/BluetoothSapService( 1626): Sap Service closeSapService out
I/BtOppRfcommListener( 1626): stopping Accept Thread
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024569
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024644
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024652
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024656
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025979
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025999
,W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029021
I/BtOppRfcommListener( 1626): BluetoothSocket listen thread finished
D/BluetoothAdapter( 3132): 1102130160: getState(). Returning 13
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/BluetoothInputDevice( 3132): BluetoothInputDevice()
V/BluetoothPbapService( 1626): Pbap Service onDestroy
V/BluetoothPbapService( 1626): Pbap Service closeService in
V/BluetoothPbapService( 1626): Pbap Service closeService out
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 7
D/libc    (  909): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  909): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
V/BluetoothSapService( 1626): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41af16f8
V/BluetoothSapService( 1626): Sap Service closeSapService in
V/BluetoothSapService( 1626): Close listen Socket : 
V/BluetoothSapService( 1626): Close rfcomm Socket : 
V/BluetoothSapService( 1626): Close sapd  Socket : 
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
V/BluetoothSapService( 1626): Sap Service closeSapService out
D/WifiDataStallTracker(  909): stopDataStallAlarm: current tag=20370 mDataStallAlarmIntent=PendingIntent{41c4d108: PendingIntentRecord{42542458 android broadcastIntent}}
V/BluetoothSapService( 1626): ***onDestroyed***
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  909):    returned null
E/WifiStateMachine(  909): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  909): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/BluetoothAdapter( 3132): 1102130160: getState(). Returning 13
D/BluetoothInputDevice( 3132): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3132): Bluetooth service connected
W/BluetoothInputDevice( 3132): Proxy not attached to service
E/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  909):    returned null
D/BluetoothPan( 3132): BluetoothPan()
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  909): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  909): Provision feature enable=false
D/ConnectivityService(  909): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 8
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/BluetoothAdapter( 3132): 1102130160: getState(). Returning 13
D/BluetoothPan( 3132): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3132): Bluetooth service connected
D/BluetoothMap( 3132): Create BluetoothMap proxy object
D/UsbnetStateTracker(  909): isAvailable+-
D/UsbnetStateTracker(  909): reconnect
D/UsbnetStateTracker(  909): isAvailable+-
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 9
E/BluetoothMap( 3132): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3132): BluetoothSap() call bindService
D/BluetoothManagerService(  909): Registered receivers: 10
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  909): default: reconnect()
D/MDST    (  909): default: setTeardownRequested(false)
D/MDST    (  909): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  909): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  909): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  909): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  909): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateMachine(  909): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiNative-wlan0(  909): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1184): Power_Mode_Type mode = 0
I/wpa_supplicant( 1184): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 61
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  909):    returned true
D/WifiNative-wlan0(  909): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  909): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1184): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1184): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  909):    returned true
V/AudioService(  909): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  909):     Client/Owner: Client
V/AudioService(  909):     GroupId: 
V/AudioService(  909):     Passphrase: 
V/AudioService(  909):     SessionId: 0
V/AudioService(  909):     IP Address: }
D/HtcEffectManagerBase(  909): onEventChanged id=5 status=false
D/HtcEffectManager(  909): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  909): convertEffect before=902
D/HtcEffectManager(  909): convertEffect after=902
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  909): P2pDisablingState
D/WifiP2pService(  909): P2pDisablingState{ when=-4ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): p2p socket connection lost
D/WifiP2pService(  909): P2pDisabledState
D/WifiDisplayController(  909): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  909): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  909): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  909): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  909): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  909): P2pDisabledState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  909):  WFD CtrlPort: 0
D/WifiP2pService(  909):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  909):  WFD CtrlPort: 0
D/WifiP2pService(  909):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '26 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 26 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  909): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/WifiDisplayController(  909): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  909): updateConnection
I/WifiDisplayController(  909): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  909): updateConnection enter step 4
D/WifiDisplayController(  909): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  909): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  909):     Client/Owner: Client
D/WifiDisplayAdapter(  909):     GroupId: 
D/WifiDisplayAdapter(  909):     Passphrase: 
D/WifiDisplayAdapter(  909):     SessionId: 0
D/WifiDisplayAdapter(  909):     IP Address: }
D/WifiP2pService(  909): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  909): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '27 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 27 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ContextImpl( 3132): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 3132): BluetoothPbap()
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 11
D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-p2p0(  909): doBoolean: TERMINATE
W/WifiHW  (  909): QCOM Debug wifi_send_command "TERMINATE"
V/NativeCrypto( 1362): Read error: ssl=0x66079ff8: I/O error during system call, Connection timed out
E/wpa_supplicant( 1184): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiNative-p2p0(  909):    returned true
D/wpa_supplicant( 1184): TDLS: Tear down peers
I/wpa_supplicant( 1184): wpa_driver_nl80211_disconnect(reason_code=3)
D/BluetoothAdapter( 3132): 1102130160: getState(). Returning 13
D/BluetoothPbap( 3132): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3132): Bluetooth service connected
D/LocalBluetoothProfileManager( 3132): LocalBluetoothProfileManager construction complete
I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/PhoneStatusBar( 1117): removeIcon slot=bluetooth index=12 viewIndex=0
V/NativeCrypto( 1362): SSL shutdown failed: ssl=0x66079ff8: I/O error during system call, Broken pipe
D/libc    (  363): [NET] entry_id:3   entry:0xb731a320  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb7319fd8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb731a428  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb731a0e8  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
W/ConnectivityService(  909): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  909): handleConnectivityChange: resetting
D/ConnectivityService(  909): resetConnections(wlan0, 3)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  909): acquireWL(4268f2d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1362 10029 WorkSource{10029 com.google.android.gms}
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): flush DNS cache for net 1(wlan0)
D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/DockEventReceiver( 3132): finishStartingService: stopping service
I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WISPrService( 3132): >>>>>WISPrService start isConnected = false<<<<<
,D/WirelessDisplayService(  909): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/Nat464Xlat(  909): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  909): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  909): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024569
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024644
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024652
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024656
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025979
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025999
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029021
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/PMS     (  909): acquireWL(426a06a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 909 1000 null
D/ConnectivityService(  909): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  909): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  909): releaseWL(426ae3f8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
E/FbInjectorInitializer( 3579): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  909): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3132): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  909): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  909): startScan Pid: 909 Uid 1000
D/HtcBtWidget_BTWidgetProvider( 3596): onBTStateChanged() for widget: 
D/WISPrService( 3132): >>>>>WISPrService start isConnected = false<<<<<
D/HtcBtWidget_BTWidgetProvider( 3596): updateWidget(context) for widget: 
D/WifiStateMachine(  909): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  909): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiService(  909): New client listening to asynchronous messages
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/ConnectivityService(  909): reportInetCondition for net -1, percentage: 0 by  (1362/10029)
D/WISPrService( 3132): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1184): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1184): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  909): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): TDLS: Remove peers on disassociation
D/HTCRequest(  909): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  909): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1184): send_and_recv error -67 - cmd 12
D/HTCRequest(  909): WifiMonitor:getReasonFromEventString() 3
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb803bbc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1184):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  909): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1184): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1184): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  909): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1184): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/WifiMonitor(  909): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
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
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I//system/bin/ip(  363): RTNETLINK answers: No such process
D/HTCRequest(  909): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/HTCRequest(  909): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  909): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Process (  909): killProcessQuiet, pid=3235
D/Tethering(  909): [isWifi] getHotspotEnabled: false
D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
D/PMS     (  909): releaseWL(4268f2d0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  909): Killing 3235:com.android.vending/u0a74 (adj 15): empty #17
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
E/BluetoothFtpService:RfcommSocketAcceptThread( 1626): Shutdown
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
D/BluetoothMasReceiver( 1626): Bluetooth STATE CHANGED to 13
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1745): Received state change = 13
I/ActivityManager(  909): Recipient 3235
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  909): mActiveDefaultNetwork: -1
,D/ConnectivityService(  909): handleInetConditionChange: no active default network - ignore
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1745): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41ac7318
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1745): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1745): deinitLeServices: null
,I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/PMS     (  909): releaseWL(426a06a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/WifiService(  909): New client listening to asynchronous messages
,D/Process (  909): killProcessQuiet, pid=3372
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1362): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  909): Killing 3372:com.htc.sense.browser/u0a12 (adj 15): empty #17
,W/bt-btif ( 1626): ag scb idx 1 not allocated
,W/bt-btif ( 1626): ag scb idx 2 not allocated
E/bt-btif ( 1626): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1626): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1626): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 1626): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1626): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1626): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1626): L2CAP - PSM: 0x0017 not found for deregistration
,E/bt_userial_mct( 1626): userial_close userial_thread_created userial_running is 1 
,W/fb4a(:<default>):StaticBindingVerifier( 3579): Verify
,I/ActivityManager(  909): Recipient 3372
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/wpa_supplicant( 1184): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1184): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 1184): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  909): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/wpa_supplicant( 1184): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1184): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1184): nl80211: Unsubscribe mgmt frames handle 0xb803c718 (mode change)
I/wpa_supplicant( 1184): htc_wext_command_deinit +
I/wpa_supplicant( 1184): htc_wext_command_deinit -
E/wpa_supplicant( 1184): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
I/wpa_supplicant( 1184): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1184): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1184): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1184): TDLS: Tear down peers
I/wpa_supplicant( 1184): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1184): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1184): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1184): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1184): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1184): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1184): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1184): send_and_recv error 0 - cmd 18
D/Tethering(  909): interfaceLinkStateChanged wlan0, false
D/Tethering(  909): interfaceStatusChanged wlan0, false
D/Tethering(  909): [isWifi] getHotspotEnabled: false
,E/WifiStateMachine(  909): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant,
,E/cutils-trace( 3613): Error opening trace file: No such file or directory (2)
D/WifiService(  909): New client listening to asynchronous messages
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (3579/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3579): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3579): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,E/WifiStateMachine(  909): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  909): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  909): [wpa_ctrl_close] ctrl=0x63f51be8
,I/wpa_ctrl(  909): [wpa_ctrl_close] ctrl=0x63f51cd0
,W/WifiHW  (  909): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  909): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
,D/WifiStateMachine(  909): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  909): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  909):    returned false
,D/WifiStateMachine(  909): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
,D/WirelessDisplayService(  909): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
,D/WirelessDisplayService(  909): WIFI Trun OFF
,D/WirelessDisplayService(  909): getDiscoveryDongleList
,I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
W/Settings( 1224): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiStateMachine(  909): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  909): Exit handleNetworkDisconnect
E/WifiStateMachine(  909): [MLHD] Error! unhandled message 6 { when=-117ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiDataStallTracker(  909): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  909): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  909): acquireWL(4269ffc8): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 909 1000 null
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  909): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3132): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3132): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,I/dalvikvm-heap( 3579): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  909): killProcessQuiet, pid=3413
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3413:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3413
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1317): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
I/ActivityManager(  909): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3635 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1317): Util - no network available!
,D/AutoSetting( 1317): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1317): service - mHandler: cancel location update
,D/AutoSetting( 1317): service -           changes count: 0
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,I/bt-btif ( 1626): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1626): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.sense.hsp (1317/10055)
,D/HeadsetService( 1626): Received stop request...Stopping profile...
D/BluetoothHeadset( 1245): Proxy object disconnected
,D/BluetoothHeadset(  909): Proxy object disconnected
D/BluetoothHeadset( 1245): Proxy object disconnected
D/BluetoothPhoneService( 1245): BluetoothHeadset onServiceDisconnected
,D/BluetoothHeadset( 1117): Proxy object disconnected
D/CustomizationManager( 3613): ====startRecUseTime====
D/htc.customization.log.level( 3613):  is 
,W/CustomizationLogLevel( 3613): Level value is invalid, use default level 2
D/A2dpService( 1626): Received stop request...Stopping profile...
D/A2dpStateMachine( 1626): doQuit
I/QuickSettingMiniLite( 1117): btListener.disconnect:HEADSET
,D/BluetoothAdapterState( 1626): Stopping profile services that were post enabled
,D/A2dpStateMachine( 1626): Exit Disconnected: -1
,D/BluetoothA2dp(  909): Proxy object disconnected
,D/HidService( 1626): Received stop request...Stopping profile...
,D/HealthService( 1626): Received stop request...Stopping profile...
,D/BluetoothAdapterService( 1626): Profile still running: com.android.bluetooth.hdp.HealthService
D/PanService( 1626): Received stop request...Stopping profile...
,D/PanService( 1626): stop
,D/PanService( 1626): stop: mTetherAc send disconnect
,D/BluetoothTethering(  909): got CMD_CHANNEL_DISCONNECT
,D/BluetoothTethering(  909): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  909): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  909): BluetoothPAN Proxy object disconnected
W/BluetoothHeadsetServiceJni( 1626): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1626): Cleaning up Bluetooth Handsfree callback object
,D/BtGatt.DebugUtils( 1626): handleDebugAction() action=null
D/BtGatt.GattService( 1626): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1626): stop()
D/BluetoothAdapterService( 1626): Profile still running: com.android.bluetooth.hdp.HealthService
,D/A2dpStateMachine( 1626): cleanup
,D/Avrcp   ( 1626): Unregistering previous receiver
,D/BluetoothAdapterService( 1626): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1626): Cleaning up Bluetooth HID Interface...
,W/bt-btif ( 1626): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1626): Cleaning up Bluetooth GID callback object
,D/BluetoothAdapterService( 1626): Profile still running: com.android.bluetooth.pan.PanService
,W/BluetoothHealthServiceJni( 1626): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1626): Cleaning up Bluetooth Health object
,D/PanService( 1626): CMD_CHANNEL_DISCONNECTED
D/PanService( 1626): CMD_CHANNEL_DISCONNECTED call disconnected
,D/BluetoothAdapterService( 1626): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1626): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1626): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1626): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1626): Setting state to 10
I/BluetoothAdapterState( 1626): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1626): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  909): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  909): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  909): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  909): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothHeadset( 1245): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1117): onBluetoothStateChange: up=false
D/BluetoothA2dp(  909): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1245): onBluetoothStateChange: up=false
,I/BluetoothAdapterState( 1626): Entering OffState
,D/BluetoothInputDevice( 3132): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 3132): 
E/BluetoothInputDevice( 3132): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41b1e330
E/BluetoothInputDevice( 3132): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3132): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3132): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3132): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3132): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3132): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3132): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset(  909): onBluetoothStateChange: up=false
,D/BluetoothMap( 3132): onBluetoothStateChange: up=false
,E/BluetoothMap( 3132): 
E/BluetoothMap( 3132): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41b21528
E/BluetoothMap( 3132): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3132): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3132): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3132): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3132): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3132): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3132): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothPan( 3132): 
E/BluetoothPan( 3132): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41b1f8c8
E/BluetoothPan( 3132): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3132): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3132): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3132): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3132): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3132): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3132): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothSap( 3132): onBluetoothStateChange on: false
,D/BluetoothPbap( 3132): onBluetoothStateChange: up=false
,E/BluetoothPbap( 3132): 
E/BluetoothPbap( 3132): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41b27640
E/BluetoothPbap( 3132): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3132): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3132): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3132): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3132): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3132): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3132): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  909): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  909): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothAdapter( 1117): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41e86568
D/BluetoothAdapter( 1117): onBluetoothServiceDown: done
D/BluetoothAdapter( 1224): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41deb328
D/BluetoothAdapter( 1224): onBluetoothServiceDown: done
D/BluetoothAdapter(  909): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4243b618
,D/BluetoothAdapter(  909): onBluetoothServiceDown: done
D/BluetoothAdapter( 3132): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b13658
D/BluetoothAdapter( 3132): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1626): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41ab6f90
D/BluetoothDevice( 1626): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 1626): onBluetoothServiceDown: done
D/BluetoothAdapter( 1245): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d45ed8
,D/BluetoothAdapter( 1245): onBluetoothServiceDown: done
D/BluetoothAdapter( 1257): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b73ee8
D/BluetoothAdapter( 1257): onBluetoothServiceDown: done
,D/MobileConnectivityChangeReceiver( 3635): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/BluetoothAdapter( 1745): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ac7be8
D/MobileConnectivityChangeReceiver( 3635): onReceive CONNECTIVITY_CHANGE networkType=1
,D/BluetoothAdapter( 1745): onBluetoothServiceDown: done
E/PhoneMonitor( 3635): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3635): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/BluetoothAdapter( 3252): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41ab96f0
D/BluetoothAdapter( 3252): onBluetoothServiceDown: done
D/BluetoothManagerService(  909): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@4243b618 mBinding = false
,W/fb4a(:<default>):UserScope( 3579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/BluetoothManagerService(  909): Sending unbind request.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3579): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/ActivityManager(  909): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3650 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=3425
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3425:com.htc.contacts/u0a44 (adj 15): empty #17
,D/BluetoothManagerService(  909): Bluetooth State Change Intent: 13 -> 10
,D/BluetoothAdapterService( 1626): Cleaning up adapter native....
D/LocalBluetoothProfileManager( 3132): setBluetoothStateOff
,D/HtcTagManager( 3132): stopProxy
,W/BluetoothEventManager( 3132): unregister mProfileBroadcastReceiver fail
D/BluetoothAdapter( 1224): 1105110328: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothAdapter( 1224): 1105110328: getState() :  mService = null. Returning STATE_OFF
,D/NfcHandover( 1257): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/PMS     (  909): releaseWL(425d1478): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (3635/10079)
,D/PMS     (  909): acquireWL(4264e7c8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 1224 10029 null
I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/TetherPref( 3132): persistRestoreBluetoothState false
,W/fb4a(:<default>):UserScope( 3579): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (3635/10079)
D/PMS     (  909): releaseWL(4264e7c8): PARTIAL_WAKE_LOCK  NlpWakeLock 0x1 null
,W/BluetoothHeadset( 1117): Proxy not attached to service
,I/bt-btif ( 1626): HAL bt_hal_cbacks->thread_evt_cb
D/BluetoothAdapterService( 1626): Done cleaning up adapter native....
,I/QuickSettingMiniLite( 1117): updateLiteState:no connect device!
D/BluetoothAdapterService(1101743136)( 1626): ****onDestroy()********
D/BtGatt.GattService( 1626): cleanup()
W/bt-btif ( 1626): GATTC Module not enabled/already disabled
,W/bt-btif ( 1626): GATTS Module not enabled/already disabled
,D/BluetoothMasReceiver( 1626): Bluetooth STATE CHANGED to 10
,D/CustomizationManager( 3613):  Read ACC file spent 0.067 (s)
,D/CIDMapFileReader( 3613): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3613): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3613): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3613): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3613): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3613): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3613): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 3613): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3613): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3613): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3613): full path : /system/customize/CID/HTC__032.xml
I/ActivityManager(  909): Recipient 3425
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  909): acquireWL(4256a0d8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3132 1000 null
W/ContextImpl( 3132): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (3635/10079)
I/CustomizationCIDLoader( 3613): Parsing tag category name = system
I/CustomizationCIDLoader( 3613): Parsing tag category name = application
V/BluetoothMasService( 1626): onDestroy: mIsEmailEnabled: true
I/CustomizationCIDLoader( 3613): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3613): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3613): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3613): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3613): Parsing tag category name = Settings
D/CustomizationManager( 3613):  Read CID file spent 0.114 (s)
,D/CustomizationManager( 3613):  All configurations done spent 0.114 (s)
,D/HtcBtWidget_BTWidgetProvider( 3596): onBTStateChanged() for widget: 
,D/HtcBtWidget_BTWidgetProvider( 3596): updateWidget(context) for widget: 
W/HtcNativeFlag( 3613): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3613): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3613): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3613): Fail to get flag for type 'language', use default value: -1
D/PMS     (  909): releaseWL(4256a0d8): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  909): acquireWL(4279cc58): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3132 1000 null
,D/DockEventReceiver( 3132): finishStartingService: stopping service
D/PMS     (  909): releaseWL(4279cc58): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 1626): Bluetooth STATE CHANGED to 10
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1745): Received state change = 10
,D/BluetoothAdapter( 1117): 1104472552: getState() :  mService = null. Returning STATE_OFF
E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  909): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  909): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@424181f8:true
W/System.err(  909): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  909): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  909): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  909): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  909): 	at dalvik.system.NativeStart.run(Native Method)
,W/ContextImpl( 3579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,I/LocationAgent( 3119): new LocationAgent instance!!
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
D/HtcTagManager( 3119): HtcTagManager construction complete
,D/BluetoothAdapter( 3119): 1101891608: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 3119): BluetoothInputDevice()
,D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3119): 1101891608: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 3119): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3119): Bluetooth service connected
,W/BluetoothInputDevice( 3119): Proxy not attached to service
,D/BluetoothPan( 3119): BluetoothPan()
,D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Registered receivers: 12
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 13
D/BluetoothAdapter( 3119): 1101891608: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 3119): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3119): Bluetooth service connected
D/BluetoothMap( 3119): Create BluetoothMap proxy object
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  909): Registered receivers: 14
E/BluetoothMap( 3119): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothSap( 3119): BluetoothSap() call bindService
,D/Process (  909): killProcessQuiet, pid=3440
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/BluetoothPbap( 3119): BluetoothPbap()
,D/BluetoothManagerService(  909): registerStateChangeCallback+
D/BluetoothAdapter( 3119): 1101891608: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 3119): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3119): Bluetooth service connected
D/LocalBluetoothProfileManager( 3119): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 3119): 1101891608: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 3119): 1101891608: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 3119): setBluetoothStateOff
D/HtcTagManager( 3119): stopProxy
,W/BluetoothEventManager( 3119): unregister mProfileBroadcastReceiver fail
D/PackageManager(  909): deletePackageAsUser: pkg=com.example.hello, pid=3613, uid=2000 user=0
I/ActivityManager(  909): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3669 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  909): Killing 3440:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
W/ContextImpl( 3119): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/Process (  909): killProcessQuiet, pid=3456
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AuthorizationBluetoothService( 1362): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  909): Killing 3456:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3440
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  909): Recipient 3456
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
,D/Process (  909): killProcessQuiet, pid=3252
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  909): Copying FileAsset 0x68a7f198 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  909): Killing 3252:com.example.hello/u0a397 (adj 0): stop com.example.hello
W/ActivityManager(  909): Force removing ActivityRecord{424402b8 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  909): handleTopAppChanged(): The previous AP is died unexpectedly.
,I/dalvikvm-heap( 3579): Grow heap (frag case) to 9.959MB for 84664-byte allocation
,W/InputDispatcher(  909): channel '427cd540 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  909): channel '427cd540 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  909): Attempted to unregister already unregistered input channel '427cd540 com.example.hello.MainActivity (s)'
D/BluetoothManagerService(  909): Registered receivers: 15
D/BluetoothManagerService(  909): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  909): Registered receivers: 16
I/WindowManager(  909): WINDOW DIED Window{427cd540 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  909): Client connection lost with reason: 4
I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WindowManager(  909): Failed looking up window
W/WindowManager(  909): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@426a96f8 does not exist
W/WindowManager(  909): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  909): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  909): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  909): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  909): 	at dalvik.system.NativeStart.run(Native Method)
I/WindowState(  909): WIN DEATH: null
,I/dalvikvm-heap( 3579): Grow heap (frag case) to 9.972MB for 28144-byte allocation
E/dalvikvm( 3579): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 3579): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3579): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 3579): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3579): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3579): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
,I/ActivityManager(  909): Force stopping com.example.hello appid=10397 user=0: pkg removed
E/dalvikvm( 3579): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 3579): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3579): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3579): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 3579): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3579): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3579): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3579): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3579): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3579): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3579): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3579): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/dalvikvm-heap( 3579): Grow heap (frag case) to 10.044MB for 39954-byte allocation
,I/dalvikvm-heap( 3579): Grow heap (frag case) to 10.121MB for 79892-byte allocation
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,D/AccTypeManager( 1347): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 1347): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1347): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
,D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
,D/DotMatrix( 1559): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1559): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/GeofencerStateMachine( 1224): Ignoring removeGeofence because network location is disabled.
,W/GAV2    ( 3669): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
D/PMS     (  909): acquireWL(4237ea58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  909): releaseWL(4237ea58): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3669): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,I/FeedHostManager( 1269): [onResume]
,I/FeedProviderManager( 1269): onResume
,I/SocialFeedProvider( 1269): +onResume
I/SocialFeedProvider( 1269): updateAccounts - Accounts is no change
I/SocialFeedProvider( 1269): -onResume
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  909):   Scheme: "smsto"
I/ConnectivityHelper( 1269): [getCurrentConnectionType] no network connection
E/ExternalAccountType( 1347): Unsupported attribute readOnly
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
D/ConnectivityService(  909): getActiveNetworkInfo called by com.htc.launcher (1269/10076)
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1245): MSG_NOTIFY_CS_TO_SYNC <<
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/dalvikvm-heap( 3579): Grow heap (frag case) to 10.250MB for 75760-byte allocation
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "sms"
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/InputMethodManagerService(  909): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  909): Got RemoteException sending setActive(false) notification to pid 3252 uid 10397
I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "smsto"
,W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
I/InputMethodManagerService(  909): Enable input method client, pid=1269
,D/ConnectivityService(  909): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mms"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,I/PackageManager(  909):   Action: "android.intent.action.SENDTO"
I/PackageManager(  909):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  909):   Scheme: "mmsto"
I/PackageManager(  909): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1245 :
,D/PhoneApp( 1245): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,V/Tethering(  909): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  909): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  909): bSetPropertyMultiRAB:false
,D/Tethering(  909): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  909): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  909): ipv4Default null
I/Tethering(  909): No IPv4 upstream interface, giving up.
,D/Tethering(  909): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (3579/10027)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.backuptransport (1573/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.setupwizard (3635/10079)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (1224/10029)
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{427f18f0 u0 ReceiverList{427c7bc8 3579 com.facebook.katana/10027/u0 remote:426aba38}}
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{427f18f0 u0 ReceiverList{427c7bc8 3579 com.facebook.katana/10027/u0 remote:426aba38}}
,I/NetworkMonitor( 3558): type=WIFI subType= reason=null isConnected=false
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.google.android.music (3558/10154)
W/BroadcastQueue(  909): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{4252ba00 u0 ReceiverList{424f6ab8 3579 com.facebook.katana/10027/u0 remote:424e23c0}}
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.gms (2182/10029)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (3669/10151)
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10076)
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  909): remove iface:wlan0
D/Tethering(  909): interfaceRemoved wlan0
,E/Tethering(  909): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (3579/10027)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (3579/10027)
,V/WebViewChromiumFactoryProvider( 3669): Binding Chromium to main looper Looper (main, tid 1) {41a9d670}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.facebook.katana (3579/10027)
I/LibraryLoader( 3669): Expected native library version number "",actual native library version number ""
I/chromium( 3669): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3669): Initializing chromium process, renderers=0
,D/PMS     (  909): acquireWL(4233a1e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,D/PMS     (  909): acquireWL(425afae8): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
,E/AudioManagerAndroid( 3669): BLUETOOTH permission is missing!
D/PMS     (  909): releaseWL(4233a1e8): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3669): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3669): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3669): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3669): Local Branch: 
I/Adreno-EGL( 3669): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3669): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3669):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  909): acquireWL(427d2c68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1224 10029 WorkSource{10029 com.google.android.gms}
,I/NSApplication( 3669): Starting up...
D/PMS     (  909): releaseWL(427d2c68): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (3669/10151)
,D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.magazines (3669/10151)
,I/ActivityManager(  909): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3714 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  909): killProcessQuiet, pid=3468
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  909): Killing 3468:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3468
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Tethering(  909): interfaceLinkStateChanged p2p0, false
,D/Tethering(  909): interfaceStatusChanged p2p0, false
,D/Tethering(  909): [isWifi] getHotspotEnabled: false
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  353): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  353): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3579): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  353): Returning OperationFailed - no handler for errno 30
,W/PackageManager(  909): Unable to load service info ResolveInfo{427a1890 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  909): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  909): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  909): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  909): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  909): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  909): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  909): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  909): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  909): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  909): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  909): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  909): 	at dalvik.system.NativeStart.main(Native Method)
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  909): remove iface:p2p0
D/Tethering(  909): interfaceRemoved p2p0
,E/Tethering(  909): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,E/SQLiteDatabase( 3714): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3714): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3714): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3714): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3714): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 3714): 	at del.a(PG:264)
E/SQLiteDatabase( 3714): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3714): 	at java.lang.Thread.run(Thread.java:864)
,D/Process (  909): killProcessQuiet, pid=3489
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3714/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3714/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3714/10160)
D/ConnectivityService(  909): getActiveNetworkInfo called by com.google.android.apps.plus (3714/10160)
I/ActivityManager(  909): Killing 3489:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,E/SQLiteDatabase( 3714): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 3714): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3714): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3714): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3714): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3714): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 3714): 	at del.a(PG:264)
E/SQLiteDatabase( 3714): 	at eeq.run(PG:187)
E/SQLiteDatabase( 3714): 	at java.lang.Thread.run(Thread.java:864)
,E/EsApplication( 3714): Failed app initialization
E/EsApplication( 3714): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 3714): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 3714): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 3714): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 3714): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 3714): 	at del.a(PG:264)
E/EsApplication( 3714): 	at eeq.run(PG:187)
E/EsApplication( 3714): 	at java.lang.Thread.run(Thread.java:864)
,I/PackageManager(  909):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2182, uid=10029, userID:0
,I/iu.SyncManager( 2182): SYNC; picasa accounts
,E/SQLiteDatabase( 2182): Failed to open database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite'.
E/SQLiteDatabase( 2182): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.networkcapability.impl.f.<init>(SourceFile:27)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.networkcapability.impl.d.<init>(SourceFile:52)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:25)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.networkcapability.impl.b.<init>(SourceFile:34)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:23)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.b(SourceFile:121)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.a(SourceFile:43)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.<init>(SourceFile:73)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:53)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/SQLiteDatabase( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/SQLiteDatabase( 2182): 	at com.google.android.librar,ies.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver.onReceive(SourceFile:212)
E/SQLiteDatabase( 2182): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 2182): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 2182): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 2182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2182): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 2182): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 2182): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 2182): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 2182): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 2182): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 2182): 	at dalvik.system.NativeStart.main(Native Method)
,W/dalvikvm( 2182): threadid=1: thread exiting with uncaught exception (group=0x41670e30)
,E/AndroidRuntime( 2182): FATAL EXCEPTION: main
E/AndroidRuntime( 2182): Process: com.google.android.gms, PID: 2182
E/AndroidRuntime( 2182): java.lang.RuntimeException: Unable to start receiver com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2182): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2182): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 2182): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 2182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2182): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2182): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 2182): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2182): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2182): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 2182): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 2182): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2182): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 2182): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 2182): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 2182): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.networkcapability.impl.f.<init>(SourceFile:27)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.networkcapability.impl.d.<init>(SourceFile:52)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:25)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.networkcapability.impl.b.<init>(SourceFile:34)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.networkcapability.impl.NetworkCapabilityModule.a(SourceFile:23)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2182): 	at com.google.android.lib,raries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.b(SourceFile:121)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.a(SourceFile:43)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment.<init>(SourceFile:73)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupModule.a(SourceFile:53)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.g.a(SourceFile:42)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.d(SourceFile:381)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.b(SourceFile:224)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:192)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.a.a.a(SourceFile:446)
E/AndroidRuntime( 2182): 	at com.google.android.libraries.social.autobackup.AutoBackupEnvironment$ConnectivityReceiver.onReceive(Source
,E/ActivityManager(  909): App crashed! Process: com.google.android.gms
,E/DropBoxManagerService(  909): Can't write: system_app_crash
E/DropBoxManagerService(  909): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  909): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  909): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  909): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  909): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  909): 	... 5 more
,I/ActivityManager(  909): Recipient 3489
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/RemoteDisplayProvider(  909): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  909): start
,I/AlarmManager(  909): [AlarmQueuing] connectivity wifi: false
,I/ActivityManager(  909): Start proc com.htc.calendar for broadcast com.htc.calendar/.AlertReceiver: pid=3736 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
,D/CaptivePortalTracker(  909): DelayedCaptiveCheckState
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
D/htcCheckinService(  909): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  909): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  909): NoActiveNetworkState
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (909/1000)
,W/AtomicFile(  909): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  909): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  909): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  909): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  909): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
D/ConnectivityService(  909): getActiveNetworkInfo called by  (1362/10029)
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024406
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024569
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024644
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024648
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024652
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360024656
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025979
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360025999
W/AlarmManager(  909): Converted elapesd time is over 1 year! when = 315360029021
D/ConnectivityService(  909): getNetworkInfo networkType=1 called by  (909/1000)
D/PMS     (  909): acquireWL(42684588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 909 1000 null
W/AppWidgetServiceImpl(  909): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  909): releaseWL(42684588): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/CalendarApplication( 3736): onCreate
,D/AlertReceiver( 3736): beginStartingService
,D/Process (  909): killProcessQuiet, pid=3504
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  909): Killing 3504:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/PMS     (  909): acquireWL(42645610): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3736 10013 null
,I/ActivityManager(  909): Recipient 3504
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AlertService( 3736): start to updateAlertNotification!
,I/ActivityManager(  909): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=3753 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/AlertService( 3736): No fired or scheduled alerts
,D/HtcAlertUtils( 3736): -- cancelReminderNotification --
,D/HtcAlertUtils( 3736): broadcastExistReminder!
,I/ActivityManager(  909): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3766 uid=10091 gids={50091, 3003, 5012}
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
V/AlarmManager(  909): sending alarm PendingIntent{42282ac0: PendingIntentRecord{424c3c00 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=53981, Int=0
,D/PMS     (  909): releaseWL(42645610): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
W/AlertReceiver( 3736): stopSelfResult true
,W/WeatherRequest( 1117): request cur loc, but there is no sys cur
,D/PMS     (  909): acquireWL(428308f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3518 10071 null
,D/PMS     (  909): acquireWL(4282acd0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3518 10071 null
,D/PMS     (  909): releaseWL(428308f8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/TodoTaskNotifyService( 3518): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/ActivityManager(  909): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3786 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 3518): update TASK shortcut>
,W/WeatherUtility( 3753): can't get weather sync account
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/ActivityManager(  909): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3798 uid=10091 gids={50091, 3003, 5012}
,I/TodoTaskNotifyService( 3518): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1559): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3518): stopSelfResult true
,D/PMS     (  909): releaseWL(4282acd0): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
W/WeatherRequest( 3753): request cur loc, but there is no sys cur
W/Settings( 3753): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WorldClock.Global( 3786): isHtcDevice = true
,E/SQLiteDatabase( 3798): Failed to open database '/data/user/0/com.htc.mobiledata/databases/mobiledata.db'.
E/SQLiteDatabase( 3798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3798): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3798): 	at com.htc.apputil.z.a(StatusInProvider.java:1011)
E/SQLiteDatabase( 3798): 	at com.htc.apputil.z.a(StatusInProvider.java:732)
E/SQLiteDatabase( 3798): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:191)
E/SQLiteDatabase( 3798): 	at com.htc.mobiledata.MobileDataProvider.query(MobileDataProvider.java:53)
E/SQLiteDatabase( 3798): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3798): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3798): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3798): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3798): 	at dalvik.system.NativeStart.run(Native Method)
,I/WorldClock.Global( 3786): isHtcDevice = true
,E/SQLiteOpenHelper( 3798): Couldn't open mobiledata.db for writing (will try read-only):
E/SQLiteOpenHelper( 3798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3798): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3798): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3798): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3798): 	at com.htc.apputil.z.a(StatusInProvider.java:1011)
E/SQLiteOpenHelper( 3798): 	at com.htc.apputil.z.a(StatusInProvider.java:732)
E/SQLiteOpenHelper( 3798): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:191)
E/SQLiteOpenHelper( 3798): 	at com.htc.mobiledata.MobileDataProvider.query(MobileDataProvider.java:53)
E/SQLiteOpenHelper( 3798): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3798): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3798): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteOpenHelper( 3798): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteOpenHelper( 3798): 	at dalvik.system.NativeStart.run(Native Method)
,W/ContextImpl( 3119): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
W/SQLiteOpenHelper( 3798): Opened mobiledata.db in read-only mode
E/SQLiteDatabase( 3786): Failed to open database '/data/data/com.htc.android.worldclock/databases/alarms.db'.
E/SQLiteDatabase( 3786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3786): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmProvider.query(Unknown Source)
E/SQLiteDatabase( 3786): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3786): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3786): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 3786): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarmsCursor(Unknown Source)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarms(Unknown Source)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.calculateNextAlert(Unknown Source)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.setNextAlert(Unknown Source)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmService.updateAlarms(Unknown Source)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmService.access$200(Unknown Source)
E/SQLiteDatabase( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmService$1.run(Unknown Source)
E/SQLiteDatabase( 3786): 	at java.lang.Thread.run(Thread.java:864)
D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
E/SQLiteOpenHelper( 3786): Couldn't open alarms.db for writing (will try read-only):
E/SQLiteOpenHelper( 3786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 3786): 	at android.database.s,qlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 3786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 3786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3786): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmProvider.query(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 3786): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 3786): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 3786): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarmsCursor(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.getAlarms(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.calculateNextAlert(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmUtils.setNextAlert(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmService.updateAlarms(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmService.access$200(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at com.htc.android.worldclock.alarmclock.AlarmService$1.run(Unknown Source)
E/SQLiteOpenHelper( 3786): 	at java.lang.Thread.run(Thread.java:864)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 7 17
,W/SQLiteOpenHelper( 3786): Opened alarms.db in read-only mode
,E/DatabaseUtils( 3798): Writing exception to parcel
E/DatabaseUtils( 3798): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/DatabaseUtils( 3798): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DatabaseUtils( 3798): 	at com.htc.apputil.z.b(StatusInProvider.java:1182)
E/DatabaseUtils( 3798): 	at com.htc.apputil.z.a(StatusInProvider.java:737)
E/DatabaseUtils( 3798): 	at com.htc.mobiledata.MobileDataProvider.a(MobileDataProvider.java:490)
E/DatabaseUtils( 3798): 	at com.htc.mobiledata.MobileDataProvider.update(MobileDataProvider.java:61)
E/DatabaseUtils( 3798): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:299)
E/DatabaseUtils( 3798): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:252)
E/DatabaseUtils( 3798): 	at android.os.Binder.execTransact(Binder.java:412)
E/DatabaseUtils( 3798): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  909): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3812 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/MdScBoot( 3766): [b38.1.] 30@-180243 -> 40(X)
D/MdScBoot( 3766): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
D/MdScBoot( 3766): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:181)
D/MdScBoot( 3766): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
D/MdScBoot( 3766): 	at android.content.ContentProviderProxy.update(ContentProviderNative.java:615)
D/MdScBoot( 3766): 	at android.content.ContentProviderClient.update(ContentProviderClient.java:251)
D/MdScBoot( 3766): 	at com.htc.apputil.b.a(ContentProviderSession.java:149)
D/MdScBoot( 3766): 	at com.htc.apputil.y.a(StatusInProvider.java:507)
D/MdScBoot( 3766): 	at com.htc.apputil.y.a(StatusInProvider.java:79)
D/MdScBoot( 3766): 	at com.htc.mobiledata.services.c.a(SvcpBootComplete.java:273)
D/MdScBoot( 3766): 	at com.htc.apputil.k.b(RequestThreadManager.java:1096)
D/MdScBoot( 3766): 	at com.htc.apputil.k.a(RequestThreadManager.java:16)
D/MdScBoot( 3766): 	at com.htc.apputil.p.a(RequestThreadManager.java:1472)
D/MdScBoot( 3766): 	at com.htc.apputil.k.b(RequestThreadManager.java:1096)
D/MdScBoot( 3766): 	at com.htc.apputil.k.a(RequestThreadManager.java:1151)
D/MdScBoot( 3766): 	at com.htc.apputil.k.a(RequestThreadManager.java:16)
D/MdScBoot( 3766): 	at com.htc.apputil.l.handleMessage(RequestThreadManager.java:988)
D/MdScBoot( 3766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/MdScBoot( 3766): 	at android.os.Looper.loop(Looper.java:157)
D/MdScBoot( 3766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 1530): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 1530): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.android.providers.calendar/databases/calendar.db, handle = 0x5c9c99b8
,I/WorldClock.AlarmUtils( 3786): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,E/DatabaseUtils( 1530): Writing exception to parcel
E/DatabaseUtils( 1530): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DatabaseUtils( 1530): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DatabaseUtils( 1530): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DatabaseUtils( 1530): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DatabaseUtils( 1530): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DatabaseUtils( 1530): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DatabaseUtils( 1530): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DatabaseUtils( 1530): 	at com.android.providers.calendar.CalendarProvider2.acquireInstanceRange(CalendarProvider2.java:1642)
E/DatabaseUtils( 1530): 	at com.android.providers.calendar.CalendarProvider2.handleInstanceQuery(CalendarProvider2.java:1355)
E/DatabaseUtils( 1530): 	at com.android.providers.calendar.HtcFilterImpl_google.do_Query_INSTANCES(HtcFilterImpl_google.java:219)
E/DatabaseUtils( 1530): 	at com.android.providers.calendar.HtcFilterImpl_google.handle_Query(HtcFilterImpl_google.java:62)
E/DatabaseUtils( 1530): 	at com.android.providers.calendar.HtcCalendarProvider.query(HtcCalendarProvider.java:126)
E/DatabaseUtils( 1530): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/DatabaseUtils( 1530): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/DatabaseUtils( 1530): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/DatabaseUtils( 1530): 	at android.os.Binder.execTransact(Binder.java:412)
E/DatabaseUtils( 1530): 	at dalvik.system.NativeStart.run(Native Method)
,W/dalvikvm( 3119): threadid=11: thread exiting with uncaught exception (group=0x41670e30)
E/AndroidRuntime( 3119): FATAL EXCEPTION: IntentService[HtcDndCommandService]
E/AndroidRuntime( 3119): Process: com.android.settings:remote, PID: 3119
E/AndroidRuntime( 3119): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3119): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
E/AndroidRuntime( 3119): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
E/AndroidRuntime( 3119): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:463)
E/AndroidRuntime( 3119): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/AndroidRuntime( 3119): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/AndroidRuntime( 3119): 	at com.android.settings.framework.core.sound.HtcDndUtils.getCalendarEvent(HtcDndUtils.java:310)
E/AndroidRuntime( 3119): 	at com.android.settings.framework.app.HtcDndCommandService.addCalendarTimeSlot(HtcDndCommandService.java:452)
E/AndroidRuntime( 3119): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleSlotData(HtcDndCommandService.java:511)
E/AndroidRuntime( 3119): 	at com.android.settings.framework.app.HtcDndCommandService.rescheduleEventTimer(HtcDndCommandService.java:530)
E/AndroidRuntime( 3119): 	at com.android.settings.framework.app.HtcDndCommandService.onHandleIntent(HtcDndCommandService.java:142)
E/AndroidRuntime( 3119): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3119): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3119): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3119): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ActivityManager(  909): App crashed! Process: com.android.settings:remote
,I/WorldClock.AlarmUtils( 3786): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3786): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,D/Process (  909): killProcessQuiet, pid=2724
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ErrorReport(  909): HtcErrorReportManager Begin---add error logs to dropbox
,I/ActivityManager(  909): Killing 2724:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/IntentController( 1117): receive(android.intent.action.ALARM_CHANGED,1,false)
E/ErrorReport(  909): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  909): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1450198993221.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  909): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  909): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  909): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  909): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  909): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  909): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  909): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  909): 	... 4 more
,D/TimeService( 3812): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450198993242
,D/Process (  909): killProcessQuiet, pid=3533
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  909): Killing 3533:com.htc.stock/u0a82 (adj 15): empty #17
,D/Process (  909): killProcessQuiet, pid=3545
,D/Process (  909): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  909): Killing 3545:com.htc.stock:remote/u0a82 (adj 15): empty #17
,I/ActivityManager(  909): Recipient 3533
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  909): Recipient 3545
,I/DisplayManagerService(  909): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0

```
