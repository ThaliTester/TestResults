#### Test 50388019831b9e1_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
--------- beginning of /dev/log/main
I/MediaRouter( 2939): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.bj:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/YouTube ( 2939): apps.youtube.core.client.ac.a:115 event [version=5.9.0.13-s2000, action=Startup, label=NORMAL_STARTUP, value=-1]
I/GoogleConversionPing( 2939): Pinging: http://www.googleadservices.com/pagead/conversion/1001680686/?label=4dahCKKczAYQrt7R3QM&value=&muid=ju8NP17ZG6xGg08rfWhudw&bundleid=com.google.android.youtube&appversion=5.9.0.13&osversion=4.4.4&sdkversion=ct-sdk-a-v1.1.0&remarketing_only=1&timestamp=1451921622&data=screen_name%3D%3CAndroid_YT_Open_App%3E
D/ConnectivityService(  910): getNetworkInfo networkType=0 called by com.google.android.youtube (2939/10168)
D/libc    ( 2939): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 2939): [NET] getaddrinfo-,err=8
D/libc    ( 2939): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 2939): [NET] getaddrinfo-, 1
D/libc    ( 2939): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 24(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2939): [NET] getaddrinfo_proxy-
E/GoogleConversionPing( 2939): Error sending ping
E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 2939): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 2939): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
D/MediaRouter( 2939): getSelectedRoute
D/YouTube ( 2939): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/YouTube ( 2939): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.youtube (2939/10168)
I/ActivityManager(  910): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=2992 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/Process (  910): killProcessQuiet, pid=2709
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 2709:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/YouTube ( 2939): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 2939): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 2939): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.offline.a.d
I/ActivityManager(  910): Recipient 2709
D/YouTube ( 2939): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 2939): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.offline.a.d
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/YouTube ( 2939): apps.youtube.datalib.d.b.a:91 Sending from HTTP204 service
W/dalvikvm( 2992): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=2992, uid=10074, userID:0
D/YouTube ( 2939): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.d with ScheduledExecutorService for repeating execution.
D/YouTube ( 2939): apps.youtube.datalib.offline.b.run:89 Queuing stored offline request.
D/Finsky  ( 2992): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.youtube (2939/10168)
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (2992/10074)
W/dalvikvm( 2992): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 2992): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  910): getAllNetworkInfo called by com.android.vending (2992/10074)
D/Finsky  ( 2992): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
W/dalvikvm( 2992): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
E/cutils-trace( 3006): Error opening trace file: No such file or directory (2)
W/Settings( 2992): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 2992): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 2992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 2992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 2992): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 2992): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=2992, uid=10074, userID:0
D/CustomizationManager( 3006): ====startRecUseTime====
D/htc.customization.log.level( 3006):  is 
W/CustomizationLogLevel( 3006): Level value is invalid, use default level 2
I/ActivityManager(  910): Killing 2746:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  910): killProcessQuiet, pid=2746
D/Volley  ( 2992): [283] DiskBasedCache.clear: Cache cleared.
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Finsky  ( 2992): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 2992): [1] Libraries$2.run: Finished loading 1 libraries.
D/Volley  ( 2992): [276] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 2992): Skipping gmscore version check
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025185
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025396
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025401
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025410
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026793
D/Finsky  ( 2992): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029444
D/Finsky  ( 2992): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  910): Recipient 2746
D/libc    ( 2992): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 2992): [NET] getaddrinfo-,err=8
D/libc    ( 2992): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 2992): [NET] getaddrinfo-, 1
D/libc    ( 2992): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 2992): [NET] getaddrinfo_proxy-
D/CustomizationManager( 3006):  Read ACC file spent 0.078 (s)
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3006): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3006): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3006): Parsing tag category name = system
I/CustomizationCIDLoader( 3006): Parsing tag category name = application
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/CustomizationCIDLoader( 3006): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3006): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3006): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3006): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3006): Parsing tag category name = Settings
D/CustomizationManager( 3006):  Read CID file spent 0.124 (s)
D/CustomizationManager( 3006):  All configurations done spent 0.124 (s)
W/HtcNativeFlag( 3006): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3006): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3006): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3006): Fail to get flag for type 'language', use default value: -1
W/CpuWake (  910): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  910): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  910): <<acquire mCpuPerf_Freq wakelock
D/PMS     (  910): acquireHCC(42866500): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 910 1000 null
I/ActivityManager(  910): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3006
D/PMS     (  910): acquireHCC(42864b18): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 910 1000 null
W/asset   (  910): Copying FileAsset 0x62e8f440 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  910): @test_code: getHtcIntentFlag: 0 obj: 1113609536
I/FeedHostManager( 1248): [onPause]
I/FeedProviderManager( 1248): onPause
I/FeedHostManager( 1248): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d49e90
D/PMS     (  910): acquireWL(42843dc0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 910 1000 null
I/SocialFeedProvider( 1248): +onPause
I/SocialFeedProvider( 1248): -onPause
I/ActivityManager(  910): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3048 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
W/asset   ( 3048): Copying FileAsset 0x5c897428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1248): [trimMemory] 20
V/WebViewChromiumFactoryProvider( 3048): Binding Chromium to main looper Looper (main, tid 1) {41b073d0}
I/LibraryLoader( 3048): Expected native library version number "",actual native library version number ""
I/chromium( 3048): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3048): Initializing chromium process, renderers=0
D/PMS     (  910): acquireWL(42792480): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
D/PMS     (  910): acquireWL(4278a0c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 370 1013 null
W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  910): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  910): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  910): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42268410:true
D/BluetoothAdapter( 3048): 1102171592: getState() :  mService = null. Returning STATE_OFF
D/PMS     (  910): releaseWL(42792480): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 3048): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3048): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3048): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3048): Local Branch: 
I/Adreno-EGL( 3048): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3048): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3048):                  aa63bbd948f41d15fc72f585e
W/dalvikvm( 1961): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1961): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1961): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 1961): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/chromium( 3048): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
D/PMS     (  910): acquireWL(42784930): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 1961 10029 null
I/ActivityManager(  910): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/FileApkUtils( 1961): Spent 23ms computing apk sha1.
D/FileApkUtils( 1961): Module already staged or being staged:chimera-modules/MapsModule.apk
D/PMS     (  910): acquireWL(427835b0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 3048): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3048): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/DexOptUtils( 1961): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 1961): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 1961): Reading stored module config
W/dalvikvm( 3048): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3048): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3048): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3048): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3048): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3048): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3048): CordovaWebView is running on device made by: HTC
D/GmsModuleFndr( 1961): Beginning GMS chimera module scan
D/PMS     (  910): releaseWL(42784930): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  910): releaseWL(427835b0): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  910): Resuming delayed broadcast
W/asset   ( 1961): Copying FileAsset 0x6567dd68 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
D/ChimeraCfgMgr( 1961): Beginning module configuration check
D/ChimeraCfgMgr( 1961): Module APKs unchanged, check complete
W/InstanceID/Rpc( 1961): Found 10029
,W/AwContents( 3048): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  910): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
E/dalvikvm( 1961): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1961): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 1961): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1961): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1961): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1961): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1961): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 1961): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1961): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
I/InputMethodManagerService(  910): Disable input method client, pid=1248
W/ResourceType( 3048): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3048): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b4e0d8, mServedView=org.apache.cordova.engine.SystemWebView{41b140e8 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  910): Enable input method client, pid=3048
E/dalvikvm( 1199): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1199): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
E/dalvikvm( 1961): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 1961): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
W/dalvikvm( 1199): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1199): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1199): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1199): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1199): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/AwContents( 3048): nativeOnDraw failed; clearing to background color.
W/dalvikvm( 1199): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1199): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/XT9_C   ( 1186): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1186): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1186): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/ActivityManager(  910): Displayed com.example.hello/.MainActivity: +266ms
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): acquireWL(424d38c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42843dc0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
E/dalvikvm( 1961): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 1961): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 1961): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
W/dalvikvm( 1961): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
I/ActivityManager(  910): Delay finish: com.google.android.gms/.tapandpay.receiver.OnBootCompletedReceiver
D/PMS     (  910): acquireWL(4244a8f0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(42428388): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(424d38c8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): acquireWL(423fc900): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 1961): COMPAT: Multi user not supported
I/CheckinService( 1961): Checkin interval check for package: unspecified last checkin: 1451336015456 min interval config: 0 actual interval: 585608308
D/GCM     ( 1343): COMPAT: Multi user not supported
W/dalvikvm( 1343): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/GCoreUlr( 1961): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/CheckinService( 1961): Disabling old GoogleServicesFramework version
W/dalvikvm( 1343): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
I/GCoreUlr( 1199): DispatchingService.onCreate()
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/PMS     (  910): acquireWL(41ee4b70): PARTIAL_WAKE_LOCK  Event Log Service 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(4244a8f0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/SystemUpdateService( 1961): onCreate
D/SystemUpdateService( 1961): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
W/dalvikvm( 1961): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
V/AuthZen ( 1961): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 1961): cancelUpdate (empty URL)
I/SystemUpdateService( 1961): active receiver: disabled
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
D/PMS     (  910): acquireWL(428bec10): PARTIAL_WAKE_LOCK  Icing 0x1 1961 10029 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1343): VFY: unable to resolve instance field 161
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/CheckinService( 1961): Checking schedule, now: 1451921623879 next: 1451858952413
I/CheckinService( 1961): active receiver: enabled
D/AuthZenEventHandler( 1961): Handling event: android.intent.action.BOOT_COMPLETED
D/WifiService(  910): New client listening to asynchronous messages
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=1961, uid=10029, userID:0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1343/10029)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=1961, uid=10029, userID:0
D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.gms (1961/10029)
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=1961, uid=10029, userID:0
D/PMS     (  910): acquireWL(428c3e98): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=1961, uid=10029, userID:0
D/PMS     (  910): releaseWL(428bec10): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=1961, uid=10029, userID:0
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=1961, uid=10029, userID:0
W/dalvikvm( 1343): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
E/AndroidProtocolHandler( 3048): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/PMS     (  910): releaseWL(42428388): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
I/EventLogService( 1961): Aggregate from 1451919279047 (log), 1451919279047 (data)
D/SystemUpdateService( 1961): onDestroy
D/PMS     (  910): releaseWL(423fc900): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=1961, uid=10029, userID:0
I/chromium( 3048): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/BaseAppContext( 1961): Using Auth Proxy for data requests.
W/dalvikvm( 1343): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=1961, uid=10029, userID:0
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
I/GCoreUlr( 1199): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1343/10029)
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1961): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1961): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
D/JsMessageQueue( 3048): Set native->JS mode to OnlineEventsBridgeMode
D/PMS     (  910): acquireWL(428cec80): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1343 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1343/10029)
D/GCM     ( 1343): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/libc    ( 1343): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1343): [NET] getaddrinfo-,err=8
D/libc    ( 1343): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1343): [NET] getaddrinfo-, 1
D/libc    ( 1343): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  363): [NET] get_iface_protocol fail: 
D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=00 method=3
D/libc    (  363): [NET]_dns_getaddrinfo- 3, (NS_NOTFOUND)
D/libc    (  363): [NET] getaddrinfo-,err=7
D/libc    ( 1343): [NET] getaddrinfo_proxy-
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  910): reportInetCondition for net -1, percentage: 0 by  (1343/10029)
D/ConnectivityService(  910): handleInetConditionChange: no active default network - ignore
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1343/10029)
D/PMS     (  910): releaseWL(428cec80): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1343/10029)
D/ConnectivityService(  910): getActiveNetworkInfo called by  (1343/10029)
E/BaseAppContext( 1961): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/dalvikvm( 1961): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1199, uid=10029, userID:0
I/AuthZen ( 1961): Fetching signing key...
D/jxcore_app_log( 3048): JniHelper::setJavaVM(0x415d8048), pthread_self() = 1658734120
D/JX-Cordova( 3048): jxcore cordova android initializing
I/AuthZen ( 1961): Signing key fetched successfully!
D/PMS     (  910): releaseWL(41ee4b70): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
W/BaseAppContext( 1961): Using Auth Proxy for data requests.
D/AuthZenTransactionCache( 1961): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 1961): Clearing transaction cache
I/GCoreUlr( 1199): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PMS     (  910): acquireWL(4244b640): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1199): Unbound from all location providers
I/GCoreUlr( 1199): Place inference reporting - stopped
D/PMS     (  910): releaseWL(4244b640): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(428c3e98): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
I/GCoreUlr( 1199): DispatchingService.onDestroy()
I/GCoreUlr( 1199): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1199): Unbound from all location providers
I/GCoreUlr( 1199): Place inference reporting - stopped
D/PMS     (  910): acquireWL(42657410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42657410): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/jxcore-log( 3048): Initializing JXcore engine
W/jxcore-log( 3048): JXcore engine is ready
W/jxcore-log( 3048): Starting JXcore engine
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
D/PMS     (  910): acquireWL(425c30f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(425c30f0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ChimeraCfgMgr( 1961): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/BootCompletedReceiver( 1961): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 1961): Got an BootCompleted event.
I/ActivityManager(  910): Resuming delayed broadcast
D/BootCompletedReceiver( 1961): Will NOT schedule AdAttestation signal task because it's disabled.
W/dalvikvm( 1343): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
W/Auth    ( 1343): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  910): acquireWL(4259ca88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1343 10029 null
I/ActivityManager(  910): Delay finish: com.google.android.gms/.auth.be.change.LoginAccountsChangedWakefulBroadcastReceiver
W/jxcore-log( 3048): Platform android
W/jxcore-log( 3048): 
W/jxcore-log( 3048): Process ARCH arm
W/jxcore-log( 3048): 
D/PMS     (  910): releaseWL(4259ca88): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
I/ActivityManager(  910): Resuming delayed broadcast
D/PersistentNotificationBroadcastReceiver( 1199): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/ActivityManager(  910): Delay finish: com.google.android.gms/.people.sync.focus.ContactsSyncBroadcastReceiver
I/jxcore-log( 3048): JXcore Cordova bridge is ready!
I/jxcore-log( 3048): 
W/jxcore-log( 3048): JXcore engine is started
I/ActivityManager(  910): Resuming delayed broadcast
I/ActivityManager(  910): Delay finish: com.google.android.gms/.chromesync.sync.SyncReceiverService$Receiver
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): acquireWL(426000e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/AutoSetting( 1297): receiver - intent: android.intent.action.USER_PRESENT
D/PMS     (  910): releaseWL(426000e0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/TetherSettings( 2898): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 2898): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 2898): Cust_ConnectToPC   : Modem_Link>false
D/        ( 2898): Cust_ConnectToPC   : spcsc>false
D/        ( 2898): Cust_ConnectToPC   : IPT>true
D/        ( 2898): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 2898): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 2898): hasRemovableStorageSlot: true
D/SmartNS_Utility( 2898): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 2898): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1297): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/PSReceiver( 2898): onReceive:android.intent.action.USER_PRESENT
I/SmartNS_PSService( 2898): onReceive:android.intent.action.USER_PRESENT
W/Settings( 2898): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 2898):  defaultType:0
W/ContextImpl( 2898): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  910): Delay finish: com.android.settings/.PSReceiver
I/ActivityManager(  910): Resuming delayed broadcast
E/jxcore-log( 3048): >> HTC-HTC Desire 820
E/jxcore-log( 3048): 
I/jxcore-log( 3048): Total memory 1964650496
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Free memory 676528128
I/jxcore-log( 3048): 
I/jxcore-log( 3048): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3048): 
I/jxcore-log( 3048): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3048): 
I/jxcore-log( 3048): userPath [ 'www' ]
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Size 720 1184
I/jxcore-log( 3048): 
I/jxcore-log( 3048): Screen Brightness 142
I/jxcore-log( 3048): 
E/jxcore-log( 3048): Dummy Error Log.
E/jxcore-log( 3048): 
I/ActivityManager(  910): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3136 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
D/browser ( 3136): Browser versionCode = 760001523 versionName = 7.0.2512153020
,W/SWE_UI  ( 3136): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3136): Loading: swewebviewchromium
,I/LibraryLoader( 3136): Time to load native libraries: 30 ms (timestamps 4541-4571)
,I/LibraryLoader( 3136): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3136): Initializing chromium process, renderers=9
,I/LibraryLoader( 3136): Expected native library version number "",actual native library version number ""
,I/chromium( 3136): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,W/chromium( 3136): [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,I/Adreno-EGL( 3136): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3136): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3136): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3136): Local Branch: 
I/Adreno-EGL( 3136): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3136): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3136):                  aa63bbd948f41d15fc72f585e
,V/IccIntentReceiver( 1276): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
I/SIMStateChangeReceiver( 1490): SIM state: ABSENT
I/SIMStateChangeReceiver( 1490): phoneType = 0
,I/SIMStateChangeReceiver( 1490): remove notification
,I/ActivityManager(  910): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3175 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  910): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3187 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  910): killProcessQuiet, pid=2724
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 2724:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/SystemReader( 2452): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2452): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2452): onReceive()
D/ExchangePolicystatus( 2452): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2452): onReceive(): else
,D/Process (  910): killProcessQuiet, pid=2777
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  910): Killing 2777:com.htc.backup/1000 (adj 15): empty #17
D/HtcBroadcastReceiver( 1217): onReceive: android.intent.action.SIM_STATE_CHANGED
,I/jxcore-log( 3048): getBuffer is called!!!!
I/jxcore-log( 3048): 
,I/ActivityManager(  910): Recipient 2724
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 2777
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 1109): can't get weather sync account
I/ActivityManager(  910): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3205 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,W/WeatherRequest( 1109): request cur loc, but there is no sys cur
,D/AccTypeManager( 3187): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/CalendarApplication( 3205): onCreate
D/ProviderChangeReceiver( 3205): ---------------------------------------------------
,D/ProviderChangeReceiver( 3205): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3205): start to updateAlertNotification!
W/AccTypeManager( 3187): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3187): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/ContextImpl( 2885): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/AlertService( 3205): No fired or scheduled alerts
,D/HtcAlertUtils( 3205): -- cancelReminderNotification --
,I/ActivityManager(  910): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/HtcAlertUtils( 3205): broadcastExistReminder!
D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  910): Resuming delayed broadcast
,E/ExternalAccountType( 3187): Unsupported attribute readOnly
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3221 uid=10041 gids={50041}
,D/Process (  910): killProcessQuiet, pid=2799
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 2799:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3187): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/AccTypeManager( 3187): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3187): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 3187): Unsupported attribute readOnly
,I/ActivityManager(  910): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3234 uid=10078 gids={50078}
,D/Process (  910): killProcessQuiet, pid=2497
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 2497:com.android.defcontainer/u0a19 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2497
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SMSBackup( 3234): Got a database change event
,I/ActivityManager(  910): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3246 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,D/Process (  910): killProcessQuiet, pid=2827
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 2827:com.htc.backupreset/1000 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 2827
,I/ActivityManager(  910): Recipient 2799
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3246): can't get weather sync account
,W/WeatherRequest( 3246): request cur loc, but there is no sys cur
,W/Settings( 3246): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 1 11 17
,W/CpuWake (  910): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  910): >>release mCpuPerf_cpu_count wakelock
,W/CpuWake (  910): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  910): >>release mCpuPerf_Freq wakelock
W/CpuWake (  910): <<release mCpuPerf_Freq wakelock
,D/PMS     (  910): releaseHCC(42866500): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  910): releaseHCC(42864b18): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3261 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=2844
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 2844:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2844
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/DemoRecovery.RestoreReceiver( 3261): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3261): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3261): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3275 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=2858
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 2858:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2858
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  910): acquireWL(42190f80): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3275 10071 null
,D/PMS     (  910): acquireWL(41df0540): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3275 10071 null
,I/ActivityManager(  910): Delay finish: com.htc.task/.notification.NotifyReceiver
,D/PMS     (  910): releaseWL(42190f80): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/PMS     (  910): releaseWL(4278a0c0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/TodoTaskNotifyService( 3275): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  910): releaseWL(41df0540): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3275): stopSelfResult true
I/ActivityManager(  910): Resuming delayed broadcast
,D/TodoTaskshortcut( 3275): update TASK shortcut>
I/ActivityManager(  910): Delay finish: com.htc.task/.TodoReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3290 uid=10082 gids={50082, 3003, 5012}
,D/Process (  910): killProcessQuiet, pid=2871
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 2871:com.zoodles.kidmode/u0a149 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 2871
,I/HtcModeClient( 1490): handler message = 4011
,E/HtcModeClient( 1490): Check connection and retry 4 times.
,I/ActivityManager(  910): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3302 uid=10082 gids={50082, 3003, 5012}
,D/Process (  910): killProcessQuiet, pid=2913
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 2913:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
,D/SMSBackup( 3234): Got a database change event
I/ActivityManager(  910): Recipient 2913
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  910): killProcessQuiet, pid=2927
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3314 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  910): Killing 2927:com.android.smith/u0a163 (adj 15): empty #17
,I/ImageRamCache( 3314): create image Cache, size: 31457280.
I/ImageRamCache( 3314): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3314): create image Cache, size: 12582912.
,I/FeedSettings( 3314): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3314): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3314): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3314): changeLocale(): en_GB
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 2927
,I/Prism.AllAppsOptionsMa_( 3314): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3314): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3314): [custom highlight] onReceive
,D/CustomHighlightService( 3314): [custom highlight] onHandleIntent
,D/NewsDB  ( 3314): set custom highlight []
I/ActivityManager(  910): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3314): [custom highlight] set tags 
,D/MessagingShortcutReceiver( 2452): keep hiding shortcut bubble
D/MessagingShortcut( 2452): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2452): After query: 0
D/MessagingShortcut( 2452): mPresentUnreadCount: -1
D/MessagingShortcut( 2452): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2452): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,I/ActivityManager(  910): Resuming delayed broadcast
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/MessagingNotification( 2452): New incoming message, can't cancel notification now
D/MessagingNotification( 2452): newMsgCnt: 0, false
D/DotMatrix( 1523): [EventService] reorderNotification, total:0
D/DotMatrix( 1523): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1523): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/ActivityManager(  910): Delay finish: com.htc.task/.TodoReceiver
D/TodoTaskshortcut( 3275): update TASK shortcut>
,I/ActivityManager(  910): Resuming delayed broadcast
,D/HtcBroadcastReceiver( 1217): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  910): killProcessQuiet, pid=2939
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 2939:com.google.android.youtube/u0a168 (adj 15): empty #17
,I/ActivityManager(  910): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3330 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  910): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025185
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025396
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025401
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025404
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025410
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026776
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026793
,W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029444
,I/ActivityManager(  910): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3344 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  910): Recipient 2939
,D/MediaRouterService(  910): Client com.google.android.youtube (pid 2939): Died!
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MdScBoot( 3330): [8d0.1.] 30@-163321 -> 40@-163347
I/ActivityManager(  910): Resuming delayed broadcast
,D/Process (  910): killProcessQuiet, pid=2992
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  910): killProcessQuiet, pid=2898
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 2992:com.android.vending/u0a74 (adj 15): empty #17
I/ActivityManager(  910): Killing 2898:com.android.settings/1000 (adj 15): empty #17
,D/WearableService( 1199): callingUid 10029, callindPid: 1199
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 2898
,D/LocationInitializer( 1961): Restart initialization of location
I/ActivityManager(  910): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,E/MDM     ( 1199): [90] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1343): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
,W/GCoreFlp( 1199): No location to return for getLastLocation()
,W/FusedLocationProvider( 1199): location=null
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  910): acquireWL(426934a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(426934a8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025185
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025396
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025401
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025410
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026793
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029444
,D/LocationInitializer( 1961): Restart initialization of location
,D/AuthorizationBluetoothService( 1343): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1343): Proximity feature is not enabled.
,E/MDM     ( 1199): [92] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1343): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1199): No location to return for getLastLocation()
D/MtpReceiver( 2138): [MTP][MtpReceiver][onReceive]+
,D/MtpReceiver( 2138): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2138): [MTP][handleMessage][startService]
,W/FusedLocationProvider( 1199): location=null
D/MtpReceiver( 2138): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2138): [MTP][handleMessage]-
D/PMS     (  910): acquireWL(42648ab0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  910): releaseWL(42648ab0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/MtpService( 2138): [MTP] startForeground
,I/ActivityManager(  910): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3367 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews( 1109): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1109): com.android.providers.media 2 1 10
,D/MtpService( 2138): updating state; isCurrentUser=true, mMtpLocked=false
,I/RemoteViews( 1109): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1109): com.android.providers.media 3 2 15
,D/MtpDatabase( 2138): TotalSize=1918604,MediaCacheLimit=6000
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  910): Recipient 2992
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025185
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025317
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025396
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025401
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025404
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360025410
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026776
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360026793
W/AlarmManager(  910): Converted elapesd time is over 1 year! when = 315360029444
D/PMS     (  910): acquireWL(42599770): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 1961 10029 null
,D/MtpService( 2138): [isMtpConnected] connected: true
,I/iu.UploadsManager( 1961): End new media; added: 0, uploading: 0, time: 48 ms
,D/SyncApplication( 3367): Loading default preferences
D/PMS     (  910): releaseWL(42599770): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
,W/Resources( 3367): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  910): New client listening to asynchronous messages
,D/SyncApplication( 3367): Overriding preferences with custom values
,D/SyncApplication( 3367): Updating preferences succeeded
,E/SyncApplication( 3367): Application created.
D/VolumeInfo( 3367): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3367): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3367): Found 0 mount point(s)
,V/VolumeInfo( 3367): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3367): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3367): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
,W/VolumeInfo( 3367): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3367): getNewCalendarAuthority()...
,D/SyncApplication( 3367): enableAppOperation()+
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3367, uid=10008, userID:0
W/PackageManager(  910): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3367, uid=10008, userID:0
,W/PackageManager(  910): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3367): enableAppOperation()-
D/HTCUtilities( 3367): isNeorSinged() + 
,D/HTCUtilities( 3367): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3367): isNeorSinged() return false
,D/CDMountReceiver( 3367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3367): USB connected to PC
,D/FOTAReceiver( 3367): onReceive() enter 
,D/FOTAReceiver( 3367): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  910): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3387 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  910): killProcessQuiet, pid=3136
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  910): Killing 3136:com.htc.sense.browser/u0a12 (adj 15): empty #17
,I/ActivityManager(  910): Waited long enough for: ServiceRecord{4277c318 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  910): Recipient 3136
,D/HtcFingerPrintQuickLaunchProvider( 3387): -onCreate()
,V/Settings:HtcSettingsApplication( 3387): [3387/3387] onCreate()
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherSettings( 3387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3387): Cust_ConnectToPC   : spcsc>false
D/        ( 3387): Cust_ConnectToPC   : IPT>true
,D/        ( 3387): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3387): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3387): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3387): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3387): Cust_ConnectToPC   : spcsc>false
D/        ( 3387): Cust_ConnectToPC   : IPT>true
D/        ( 3387): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3387): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3387): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3387): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3387): usb_cable_connect = 1
,D/SmartNS_Utility( 3387): usb_denied = 0
V/AlarmManager(  910): sending alarm PendingIntent{42046e38: PendingIntentRecord{425cb1c8 android broadcastIntent}}, i=com.android.server.action.NETWORK_STATS_POLL, t=3, cnt=1, w=22347, Int=1800000
V/AlarmManager(  910): sending alarm PendingIntent{4222d7b0: PendingIntentRecord{423b6838 com.google.android.talk broadcastIntent}}, i=com.google.android.apps.babel.RENEW_ACCOUNT_REGISTRATION, t=2, cnt=1, w=44568, Int=259200000
V/AlarmManager(  910): sending alarm PendingIntent{41d8c300: PendingIntentRecord{42492660 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=51411, Int=0
,V/AlarmManager(  910): sending alarm PendingIntent{424664a8: PendingIntentRecord{424e9c88 com.htc.launcher broadcastIntent}}, i=com.htc.launcher.action.BI_LOG_ALARM, t=1, cnt=1, w=1451905200000, Int=86400000
I/SmartNS_NSReceiver( 3387): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3387): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3387): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3387): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3387): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3387): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3387):  defaultType:0
I/SmartNS_PSService( 3387): fail notificaiton:false
D/SmartNS_Utility( 3387): usb_cable_connect = 1
D/SmartNS_Utility( 3387): usb_denied = 0
,I/SmartNS_PSService( 3387): usb notificaiton:true
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
I/ActivityManager(  910): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  910): getActiveNetworkInfo called by com.android.settings (3387/1000)
,D/SmartNS_Utility( 3387): usb_cable_connect = 1
D/SmartNS_Utility( 3387): usb_denied = 0
I/SmartNS_PSService( 3387): usb notificaiton:true
,I/RemoteViews( 1109): com.android.settings (true,33751552)
,V/Tethering(  910): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/RemoteViews.Performance( 1109): com.android.settings 1 1 10
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
D/Tethering(  910): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  910): bSetPropertyMultiRAB:false
I/ActivityManager(  910): Resuming delayed broadcast
D/ConnectivityService(  910): getActiveNetworkInfo called by com.android.settings (3387/1000)
,D/SmartNS_Utility( 3387): usb_cable_connect = 1
,D/SmartNS_Utility( 3387): usb_denied = 0
,W/WeatherUtility( 3246): can't get weather sync account
,D/DotMatrix( 1523): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1109): com.android.settings (true,33751552)
,I/ActivityManager(  910): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/RemoteViews.Performance( 1109): com.android.settings 2 1 10
I/SmartNS_PSService( 3387): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3387): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  910): Resuming delayed broadcast
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1248): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1248): com.google.android.googlequicksearchbox 1 0 5
,W/WeatherRequest( 3246): request cur loc, but there is no sys cur
,W/Settings( 3246): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  910): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3404 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 1 10 17
,W/ContextImpl( 3404): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  910): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageService( 3404): call getInstance()
,D/PowerUsageList:PowerUsageHelper( 3404): MY_DEBUG = false
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,W/BatSI   (  910): Couldn't get kernel wake lock stats
,I/ActivityManager(  910): Resuming delayed broadcast
,D/Process (  910): killProcessQuiet, pid=3175
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  910): Killing 3175:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  910): acquireWL(4266b548): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3404 1000 null
,W/WeatherUtility( 1109): can't get weather sync account
,D/WeatherUtility( 1297): Weather sync is On
,D/WSP     ( 1297): [Receiver] auto sync agent, auto sync is enabled, reset schedule,
I/ActivityManager(  910): Recipient 3175
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3246): can't get weather sync account
I/ActivityManager(  910): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3421 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherRequest( 3246): request cur loc, but there is no sys cur
,W/Settings( 3246): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1248): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1248): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1248): com.htc.widget.weatherclock 1 7 17
,I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3440 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  910): killProcessQuiet, pid=3187
,I/ActivityManager(  910): Killing 3187:com.htc.contacts/u0a44 (adj 15): empty #17
D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  910): Recipient 3187
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/AlarmManager(  910): sending alarm PendingIntent{42022708: PendingIntentRecord{424b2108 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1451921629257, Int=0
,D/Process (  910): killProcessQuiet, pid=3205
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  910): Killing 3205:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  910): Recipient 3205
,I/MusicStore( 3440): Database version: 95
,W/ContextImpl( 3440): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3440): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3440): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,D/BluetoothManagerService(  910): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  910): disable(): mBluetooth = null mBinding = false
W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  910): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 0
W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1103
W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  910): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  910): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 1(ms)
,D/BluetoothManagerService(  910): Message: MESSAGE_DISABLE
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3440): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,D/WifiManager( 3048): setWifiEnabled: Base Package Name=com.example.hello, uid=10397
E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/HtcDLNAServiceManager(  910): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  910): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  910): Settings:Agentvalue: 0
,W/Settings:Agent(  910): >> traceCallingStack()
W/Settings:Agent(  910): Process.myPid(): 910
W/Settings:Agent(  910): Process.myTid(): 1337
,W/ContextImpl( 3440): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Settings:Agent(  910): Process.myUid(): 1000
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): 
,W/System.err(  910): java.lang.Throwable: stack dump
,W/System.err(  910): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  910): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  910): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
D/WifiService(  910): New client listening to asynchronous messages
D/WifiService(  910): setWifiEnabled: false pid=3048, uid=10397
E/WifiService(  910): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  910): isSprintWifiRestricted(): false
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
I/WifiService(  910): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  910): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
W/System.err(  910): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  910): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  910): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  910): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  910): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  910): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  910): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  910): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  910): 
,W/Settings:Agent(  910): << traceCallingStack(): 10(ms)
,I/jxcore-log( 3048): ****TEST TOOK:  5047  ms ****
I/jxcore-log( 3048): 
,I/jxcore-log( 3048): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3048): 
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3440, uid=10154, userID:0
,D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/MediaRouterService(  910): Client com.google.android.music (pid 3440): Registered
,I/MediaRouter( 3440): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  910): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  910):     Client/Owner: Client
D/WifiDisplayAdapter(  910):     GroupId: 
D/WifiDisplayAdapter(  910):     Passphrase: 
D/WifiDisplayAdapter(  910):     SessionId: 0
D/WifiDisplayAdapter(  910):     IP Address: }
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.google.android.music (3440/10154)
D/TelephonyReceiver( 1217): bind: true
D/DFPI.PIReciver( 3261): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/DFPI.ApkInstallService( 3261): onHandleIntent
,I/DFPI.ApkInstallService( 3261): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3261): check CID = HTC__032
,I/DFPI.ApkInstallService( 3261): There is no Demo.apk in sd card or phone storage
,D/GenericMessagesProvider( 2452): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 2452): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 2452): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2452): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 2452): DB info: errno = 2, errno message = No such file or directory
,D/MediaRouter( 3440): getSelectedRoute
I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  910): Resuming delayed broadcast
,E/SQLiteDatabase( 2452): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2452): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2452): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2452): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2452): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2452): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2452): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2452): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2452): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2452): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2452): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2452): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2452): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2452): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2452): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2452): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2452): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2452): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2452): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2452): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2452): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 2452): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
D/TelephonyReceiver( 1217): switchBindHtcMsgCursor: null
I/PackageManager(  910):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3440, uid=10154, userID:0
D/ConnectivityService(  910): getActiveNetworkInfo called by  (910/1000)
I/ActivityManager(  910): Resuming delayed broadcast
D/PMS     (  910): acquireWL(428b2450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 910 1000 null
D/PMS     (  910): releaseWL(428b2450): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  910): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3466 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  910): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.musicenhancer (3466/10053)
,E/cutils  (  350): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3466): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  350): Returning OperationFailed - no handler for errno 30
,E/cutils-trace( 3464): Error opening trace file: No such file or directory (2)
,D/PMS     (  910): releaseWL(4266b548): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/CustomizationManager( 3464): ====startRecUseTime====
D/htc.customization.log.level( 3464):  is 
,W/CustomizationLogLevel( 3464): Level value is invalid, use default level 2
,D/CustomizationManager( 3464):  Read ACC file spent 0.056 (s)
,D/CIDMapFileReader( 3464): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3464): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3464): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3464): Parsing tag item name = HTC__A07
,D/CIDMapFileReader( 3464): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3464): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3464): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3464): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3464): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 3464): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 3464): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 3464): Parsing tag category name = system
,I/CustomizationCIDLoader( 3464): Parsing tag category name = application
,I/CustomizationCIDLoader( 3464): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3464): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3464): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 3464): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 3464): Parsing tag category name = Settings
,D/CustomizationManager( 3464):  Read CID file spent 0.097 (s)
,D/CustomizationManager( 3464):  All configurations done spent 0.097 (s)
W/HtcNativeFlag( 3464): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3464): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3464): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 3464): Fail to get flag for type 'language', use default value: -1
,D/PackageManager(  910): deletePackageAsUser: pkg=com.example.hello, pid=3464, uid=2000 user=0
,I/ActivityManager(  910): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
,D/Process (  910): killProcessQuiet, pid=3048
,W/asset   (  910): Copying FileAsset 0x62d59d98 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  910): Killing 3048:com.example.hello/u0a397 (adj 0): stop com.example.hello
W/ActivityManager(  910): Force removing ActivityRecord{42623638 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/ActivityManager(  910): handleTopAppChanged(): The previous AP is died unexpectedly.
,W/PackageSettings(  910): Skipping PackageSetting{421db5a0 com.test.thalitest/10389} due to missing metadata
,I/ActivityManager(  910): Force stopping com.example.hello appid=10397 user=0: pkg removed
,W/InputDispatcher(  910): channel '425a8c38 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  910): channel '425a8c38 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  910): Attempted to unregister already unregistered input channel '425a8c38 com.example.hello.MainActivity (s)'
I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowManager(  910): WINDOW DIED Window{425a8c38 u0 com.example.hello/com.example.hello.MainActivity}
D/WifiService(  910): Client connection lost with reason: 4
,W/WindowManager(  910): Failed looking up window
W/WindowManager(  910): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@428b3330 does not exist
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  910): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  910): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  910): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  910): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  910): WIN DEATH: null
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1109): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1523): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,D/DotMatrix( 1523): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,W/GeofencerStateMachine( 1199): Ignoring removeGeofence because network location is disabled.
I/FeedHostManager( 1248): [onResume]
,I/FeedProviderManager( 1248): onResume
I/SocialFeedProvider( 1248): +onResume
I/SocialFeedProvider( 1248): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1248): -onResume
,I/ConnectivityHelper( 1248): [getCurrentConnectionType] no network connection
D/PMS     (  910): acquireWL(42879958): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1199 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  910): getActiveNetworkInfo called by com.htc.launcher (1248/10076)
I/Prism.ItemManager( 3314): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3314): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/SystemReader( 1232): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/AccTypeManager( 1320): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1248): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  910): releaseWL(42879958): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,W/AccTypeManager( 1320): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1320): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "sms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "smsto"
,I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
E/ExternalAccountType( 1320): Unsupported attribute readOnly
I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mms"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,I/PackageManager(  910):   Action: "android.intent.action.SENDTO"
I/PackageManager(  910):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  910):   Scheme: "mmsto"
I/PackageManager(  910): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1217 :
,D/PhoneApp( 1217): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/InputMethodManagerService(  910): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3496 uid=10081 gids={50081, 5001, 1028, 1015}
,W/InputMethodManagerService(  910): Got RemoteException sending setActive(false) notification to pid 3048 uid 10397
,I/InputMethodManagerService(  910): Enable input method client, pid=1248
,D/Process (  910): killProcessQuiet, pid=2885
,D/Process (  910): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/Binder  ( 1186): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1186): java.lang.NullPointerException
W/Binder  ( 1186): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1186): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1186): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1186): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  910): Killing 2885:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  910): Recipient 2885
,I/DisplayManagerService(  910): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3496): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3496): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3496): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3496): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3496): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  910): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
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
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
,I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3496): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3496): MODE_GSM access default DB
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1217): MSG_NOTIFY_CS_TO_SYNC <<
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3496): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
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
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3496): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3496): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3496): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,W/PackageManager(  910): Unable to load service info ResolveInfo{42694048 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  910): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  910): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  910): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  910): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  910): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  910): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  910): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  910): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  910): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  910): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  910): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  910): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/RemoteDisplayProvider(  910): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  910): start
,W/AtomicFile(  910): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl(  910): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/ActivityManager(  910): Resuming delayed broadcast
,D/DFPI.PIReciver( 3261): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3261): onHandleIntent
,I/DFPI.ApkInstallService( 3261): Media Scan Finished Case 
I/ActivityManager(  910): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,D/DFPI.ApkInstallService( 3261): check CID = HTC__032
,I/DFPI.ApkInstallService( 3261): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  910): Resuming delayed broadcast
,I/ActivityManager(  910): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/HtcModeClient( 1490): handler message = 4011
,E/HtcModeClient( 1490): Check connection and retry 5 times.

```
