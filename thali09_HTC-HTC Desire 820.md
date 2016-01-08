#### Test 50242285ae22b3b_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3177): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.youtube/cache
D/YouTube ( 3177): apps.youtube.core.transfer.DownloadService$BootReceiver.onReceive:98 boot completed, starting download service
--------- beginning of /dev/log/system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=96
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 3177): [NET] getaddrinfo_proxy-, success
D/YouTube ( 3177): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.offline.a.b with ScheduledExecutorService for repeating execution.
D/YouTube ( 3177): apps.youtube.common.f.j.e:186 Scheduling task com.google.android.apps.youtube.datalib.innertube.f.a with ScheduledExecutorService for repeating execution.
D/YouTube ( 3177): apps.youtube.common.f.j.b:26 Executed scheduled task of type com.google.android.apps.youtube.datalib.innertube.f.a
D/YouTube ( 3177): apps.youtube.common.f.j.a:294 Updating task com.google.android.apps.youtube.datalib.innertube.f.a
,I/GoogleConversionPing( 3177): Ping responded with response code 200
I/HtcModeClient( 1500): handler message = 4011
E/HtcModeClient( 1500): Check connection and retry 3 times.
D/MediaRouter( 3177): getSelectedRoute
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3177/10168)
D/YouTube ( 3177): apps.youtube.common.f.d.a:25 Executing ConditionTask com.google.android.apps.youtube.datalib.offline.a.a
D/YouTube ( 3177): apps.youtube.datalib.offline.a.a.a:35 Network change detected, dispatch offline http requests.
D/YouTube ( 3177): apps.youtube.core.transfer.TransferService.onCreate:116 creating transfer service
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3177/10168)
I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3235 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.youtube (3177/10168)
D/Process (  907): killProcessQuiet, pid=2942
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 2942:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2942
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/dalvikvm( 3235): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3235, uid=10074, userID:0
D/Finsky  ( 3235): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3235/10074)
E/cutils-trace( 3231): Error opening trace file: No such file or directory (2)
W/dalvikvm( 3235): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
W/dalvikvm( 3235): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (3235/10074)
I/GAV2    ( 2974): Thread[GAThread,5,main]: No campaign data found.
D/Finsky  ( 3235): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/dalvikvm( 3235): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
W/Settings( 3235): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 3235): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/dalvikvm( 3235): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3235): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3235): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
W/dalvikvm( 3235): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3235, uid=10074, userID:0
D/Volley  ( 3235): [297] DiskBasedCache.clear: Cache cleared.
D/Process (  907): killProcessQuiet, pid=2974
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/Volley  ( 3235): [304] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  907): Killing 2974:com.google.android.gm/u0a107 (adj 15): empty #17
D/Ads     ( 3235): Skipping gmscore version check
I/ActivityManager(  907): Recipient 2974
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/CustomizationManager( 3231): ====startRecUseTime====
D/htc.customization.log.level( 3231):  is 
W/CustomizationLogLevel( 3231): Level value is invalid, use default level 2
D/Finsky  ( 3235): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3235): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 3235): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  907): Delay finish: com.google.android.gms/.fitness.service.FitnessInitReceiver
D/Finsky  ( 3235): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
D/CustomizationManager( 3231):  Read ACC file spent 0.072 (s)
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3231): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3231): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3231): Parsing tag category name = system
I/CustomizationCIDLoader( 3231): Parsing tag category name = application
I/CustomizationCIDLoader( 3231): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3231): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3231): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3231): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3231): Parsing tag category name = Settings
D/CustomizationManager( 3231):  Read CID file spent 0.111 (s)
D/CustomizationManager( 3231):  All configurations done spent 0.111 (s)
W/HtcNativeFlag( 3231): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3231): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3231): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3231): Fail to get flag for type 'language', use default value: -1
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3231
D/PMS     (  907): acquireHCC(42735e78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
W/asset   (  907): Copying FileAsset 0x62d7eba8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1110989696
I/FeedHostManager( 1288): [onPause]
D/PMS     (  907): acquireHCC(42734f78): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
D/PMS     (  907): acquireWL(426f37f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/FeedProviderManager( 1288): onPause
I/SocialFeedProvider( 1288): +onPause
I/FeedHostManager( 1288): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d70970
I/SocialFeedProvider( 1288): -onPause
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3285 uid=10397 gids={50397, 3003, 5012, 3001, 3002}
W/dalvikvm( 2184): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2184): VFY: unable to resolve static field 118 (SUPPORTED_32_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2184): VFY: unable to resolve static field 119 (SUPPORTED_64_BIT_ABIS) in Landroid/os/Build;
W/dalvikvm( 2184): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
I/TrimMemoryManager( 1288): [trimMemory] 20
W/asset   ( 3285): Copying FileAsset 0x5c8e8428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  907): acquireWL(42688570): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2184 10029 null
D/FileApkUtils( 2184): Spent 26ms computing apk sha1.
V/WebViewChromiumFactoryProvider( 3285): Binding Chromium to main looper Looper (main, tid 1) {41b64288}
I/LibraryLoader( 3285): Expected native library version number "",actual native library version number ""
I/chromium( 3285): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  907): Delay finish: com.google.android.gms/.reminders.notification.NotificationReceiver
D/PMS     (  907): acquireWL(42687978): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/BrowserStartupController( 3285): Initializing chromium process, renderers=0
D/FileApkUtils( 2184): Module already staged or being staged:chimera-modules/MapsModule.apk
D/DexOptUtils( 2184): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk is already optimized. Bailing.
D/PMS     (  907): acquireWL(42683588): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  907): acquireWL(42682798): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/FileApkUtils( 2184): Keeping up-to-date module: module-ca8b2a9144773fc3650c54ed299f2d4558171b12
D/ChimeraCfgMgr( 2184): Reading stored module config
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42311540:true
D/BluetoothAdapter( 3285): 1102552192: getState(). Returning 12
D/PMS     (  907): releaseWL(42683588): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/PMS     (  907): releaseWL(42688570): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  907): releaseWL(42687978): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
D/GmsModuleFndr( 2184): Beginning GMS chimera module scan
I/Adreno-EGL( 3285): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3285): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3285): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3285): Local Branch: 
I/Adreno-EGL( 3285): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3285): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3285):                  aa63bbd948f41d15fc72f585e
W/asset   ( 2184): Copying FileAsset 0x65cf9410 (zip:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-ca8b2a9144773fc3650c54ed299f2d4558171b12/MapsModule.apk:/resources.arsc) to buffer size 370140 to make it aligned.
D/ChimeraCfgMgr( 2184): Beginning module configuration check
D/ChimeraCfgMgr( 2184): Module APKs unchanged, check complete
W/InstanceID/Rpc( 2184): Found 10029
W/chromium( 3285): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3285): VFY: unable to resolve virtual method 172: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3285): VFY: unable to resolve virtual method 167: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3285): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3285): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3285): VFY: unable to resolve virtual method 225: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3285): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3285): VFY: unable to resolve virtual method 183: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3285): VFY: unable to resolve virtual method 188: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3285): CordovaWebView is running on device made by: HTC
I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.verifier.BootCompleteReceiver
E/dalvikvm( 2184): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 2184): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
W/dalvikvm( 2184): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2184): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2184): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2184): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 2184): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/dalvikvm( 2184): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 2184): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
E/dalvikvm( 1227): Could not find class 'android.net.NetworkRequest$Builder', referenced from method com.google.android.gms.common.stats.GmsCoreStatsService.onCreate
W/dalvikvm( 1227): VFY: unable to resolve new-instance 233 (Landroid/net/NetworkRequest$Builder;) in Lcom/google/android/gms/common/stats/GmsCoreStatsService;
E/dalvikvm( 2184): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.CheckinService.d
W/dalvikvm( 2184): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/CheckinService;
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=20 [5][1][0]
W/dalvikvm( 1227): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1227): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
W/dalvikvm( 1227): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1227): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
W/dalvikvm( 1227): VFY: unable to resolve virtual method 1006: Landroid/net/ConnectivityManager;.unregisterNetworkCallback (Landroid/net/ConnectivityManager$NetworkCallback;)V
W/dalvikvm( 1227): Unable to resolve superclass of Lcom/google/android/gms/common/stats/h; (252)
W/dalvikvm( 1227): Link of class 'Lcom/google/android/gms/common/stats/h;' failed
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42513ab8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
E/dalvikvm( 2184): Could not find class 'android.telephony.SubscriptionManager', referenced from method com.google.android.gms.checkin.d.a
W/dalvikvm( 2184): VFY: unable to resolve check-cast 1063 (Landroid/telephony/SubscriptionManager;) in Lcom/google/android/gms/checkin/d;
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/telephony/SubscriptionManager;)
W/dalvikvm( 2184): VFY: unable to resolve virtual method 6547: Landroid/telephony/SubscriptionManager;.getActiveSubscriptionInfoList ()Ljava/util/List;
W/dalvikvm( 2184): VFY: unable to resolve static field 229 (SUPPORTED_ABIS) in Landroid/os/Build;
I/ActivityManager(  907): Delay finish: com.google.android.gms/.tapandpay.receiver.OnBootCompletedReceiver
D/PMS     (  907): acquireWL(41c7d9f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42513ab8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4259dd50): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/GCM     ( 2184): COMPAT: Multi user not supported
D/GCM     ( 1347): COMPAT: Multi user not supported
I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1452248371148 min interval config: 0 actual interval: 12667522
W/dalvikvm( 1347): VFY: unable to resolve virtual method 1473: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/GCoreUlr( 2184): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/GCoreUlr( 1227): DispatchingService.onCreate()
W/AwContents( 3285): nativeOnDraw failed; clearing to background color.
W/dalvikvm( 1347): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
I/CheckinService( 2184): Disabling old GoogleServicesFramework version
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$Receiver, state=2, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$TriggerReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService$SecretCodeReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/SystemUpdateService( 2184): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivity, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.LockscreenActivityPermissionTrampoline, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
W/ResourceType( 3285): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3285): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41bab130, mServedView=org.apache.cordova.engine.SystemWebView{41b70fa0 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/AwContents( 3285): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  907): Disable input method client, pid=1288
I/InputMethodManagerService(  907): Enable input method client, pid=3285
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
W/dalvikvm( 1347): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1347): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1347): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1347): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +389ms
W/dalvikvm( 1347): VFY: unable to resolve instance field 161
D/PMS     (  907): releaseWL(426f37f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.ConnectivityReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GmsRegisteredReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
D/SystemUpdateService( 2184): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GservicesReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmDeviceAdminReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.MdmPhoneWearInitializer, state=1, flag=1, pid=2184, uid=10029, userID:0
W/dalvikvm( 2184): VFY: unable to resolve virtual method 244: Landroid/app/Notification$Builder;.setCategory (Ljava/lang/String;)Landroid/app/Notification$Builder;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.RetryAfterAlarmReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.DeviceManagerApiService, state=1, flag=1, pid=2184, uid=10029, userID:0
D/WifiService(  907): New client listening to asynchronous messages
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.GcmReceiverService, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LocateService, state=1, flag=1, pid=2184, uid=10029, userID:0
I/CheckinService( 2184): Checking schedule, now: 1452261038846 next: 1452771308103
I/CheckinService( 2184): active receiver: disabled
V/AuthZen ( 2184): Handling intent: android.intent.action.BOOT_COMPLETED
D/PMS     (  907): acquireWL(426bba10): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.LockscreenMessageService, state=1, flag=1, pid=2184, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.RingService, state=1, flag=1, pid=2184, uid=10029, userID:0
D/PMS     (  907): acquireWL(42146700): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.services.SitrepService, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.receiver.GoogleAccountChangeReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.GcmReceiverService, state=1, flag=1, pid=2184, uid=10029, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.wifi.gatherer2.service.WifiUpdateRetryTaskService, state=1, flag=1, pid=2184, uid=10029, userID:0
W/dalvikvm( 1347): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
I/SystemUpdateService( 2184): cancelUpdate (empty URL)
I/SystemUpdateService( 2184): active receiver: disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.update.SystemUpdateService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
E/AndroidProtocolHandler( 3285): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3285): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 1347): VFY: unable to resolve virtual method 973: Landroid/os/PowerManager;.isDeviceIdleMode ()Z
D/AuthZenEventHandler( 2184): Handling event: android.intent.action.BOOT_COMPLETED
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.GoogleAccountsAddedReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
I/GCoreUlr( 1227): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
D/PMS     (  907): releaseWL(42146700): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4259dd50): PARTIAL_WAKE_LOCK  SystemUpdateService 0x1 WorkSource{10029 com.google.android.gms}
D/SystemUpdateService( 2184): onDestroy
D/PMS     (  907): releaseWL(41c7d9f0): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
D/JsMessageQueue( 3285): Set native->JS mode to OnlineEventsBridgeMode
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  907): acquireWL(428a96c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
W/BaseAppContext( 2184): Using Auth Proxy for data requests.
D/GCM     ( 1347): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1347): [NET] getaddrinfo-, 1
D/libc    ( 1347): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =ea2f +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET] NOT IN CACHE
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/net/Network;)
W/dalvikvm( 2184): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
E/BaseAppContext( 2184): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/dalvikvm( 2184): VFY: unable to resolve virtual method 1003: Landroid/os/UserManager;.isManagedProfile ()Z
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 180
D/libc    (  365): [NET]res_nsend:resplen=79
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 1347): [NET] getaddrinfo_proxy-, success
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.location.reporting.service.LocationHistoryInjectorService, state=1, flag=1, pid=1227, uid=10029, userID:0
D/jxcore_app_log( 3285): JniHelper::setJavaVM(0x41639048), pthread_self() = 1659140968
D/JX-Cordova( 3285): jxcore cordova android initializing
I/AuthZen ( 2184): Fetching signing key...
I/AuthZen ( 2184): Signing key fetched successfully!
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
W/BaseAppContext( 2184): Using Auth Proxy for data requests.
D/AuthZenTransactionCache( 2184): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2184): Clearing transaction cache
D/libc    ( 1347): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/GCoreUlr( 1227): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=4, mName='GoogleLocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCM     ( 1347): GCM config loaded
D/PMS     (  907): acquireWL(4271f388): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4271f388): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/GCoreUlr( 1227): Unbound from all location providers
I/GCoreUlr( 1227): Place inference reporting - stopped
D/PMS     (  907): releaseWL(426bba10): PARTIAL_WAKE_LOCK  UlrDispSvcFastWL 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/GCoreUlr( 1227): DispatchingService.onDestroy()
I/GCoreUlr( 1227): Stopping handler for UlrDispSvcFast
W/jxcore-log( 3285): Initializing JXcore engine
W/jxcore-log( 3285): JXcore engine is ready
D/PMS     (  907): acquireWL(42683988): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
I/GCoreUlr( 1227): Unbound from all location providers
I/GCoreUlr( 1227): Place inference reporting - stopped
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.api.credentials.sync.CredentialSyncReceiverService$Receiver
D/PMS     (  907): releaseWL(42683988): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1347): VFY: unable to resolve virtual method 15: Landroid/accounts/AccountManager;.removeAccount (Landroid/accounts/Account;Landroid/app/Activity;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 3285): Starting JXcore engine
D/PMS     (  907): acquireWL(426b5508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/PMS     (  907): releaseWL(428a96c8): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/PMS     (  907): releaseWL(426b5508): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
W/dalvikvm( 1347): VFY: unable to resolve virtual method 16: Landroid/accounts/AccountManager;.removeAccountExplicitly (Landroid/accounts/Account;)Z
D/PMS     (  907): acquireWL(426d6d58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/dalvikvm( 1347): VFY: unable to resolve virtual method 13: Landroid/accounts/AccountManager;.notifyAccountAuthenticated (Landroid/accounts/Account;)Z
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
D/PMS     (  907): releaseWL(426d6d58): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
F/libc    ( 3285): Fatal signal 11 (SIGSEGV) at 0x00000000 (code=1), thread 3358 (Thread-306)
I/DEBUG   (  369): Build fingerprint: 'htc/a51ul_htc_europe/htc_a51ul:4.4.4/KTU84P/484493.2:user/release-keys'
I/DEBUG   (  369): Revision: '0'
I/DEBUG   (  369): pid: 3285, tid: 3358, name: Thread-306  >>> com.example.hello <<<
I/DEBUG   (  369): debuggerd: checkTellHTCSettings
I/DEBUG   (  369): debuggerd: buildType: user, roAaReport: com, ro.sf: 1
I/DEBUG   (  369): debuggerd: rosf: 1
I/DEBUG   (  369): debuggerd: [New ROM] isShippingROM: true
I/DEBUG   (  369): signal 11 (SIGSEGV), code 1 (SEGV_MAPERR), fault addr 00000000
V/HtcNativeCrashUtil(  907): Read id1=-1243796867 id2=-217320719, they are start flags. This is HTC header
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4273de38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=11 [9][1][0]
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
I/ActivityManager(  907): Resuming delayed broadcast
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/BootCompletedReceiver( 2184): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 2184): Got an BootCompleted event.
I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/BootCompletedReceiver( 2184): Will NOT schedule AdAttestation signal task because it's disabled.
D/PMS     (  907): acquireWL(4270c908): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 907 1000 WorkSource{10029}
D/PMS     (  907): releaseWL(4273de38): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42751338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(42751338): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
W/dalvikvm( 1347): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
W/Auth    ( 1347): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PMS     (  907): acquireWL(4289c620): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 1347 10029 null
D/PhoneStatusBar( 1115): addIcon slot=sync_active index=7 viewIndex=0 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f0204d5 level=0 visible=true num=0 ) name=stat_sys_sync_anim0 vis=true
D/PMS     (  907): releaseWL(4289c620): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.auth.be.change.LoginAccountsChangedIntentService 0x1 null
D/PersistentNotificationBroadcastReceiver( 1227): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/DEBUG   (  369):     r0 00000000  r1 00000000  r2 00000000  r3 00000000
I/DEBUG   (  369):     r4 674c6fb0  r5 674c6f70  r6 64786538  r7 674c6f70
I/DEBUG   (  369):     r8 00000000  r9 674c6fac  sl 674c8508  fp 674c6f54
I/DEBUG   (  369):     ip 67328ba0  sp 674c6f38  lr 6702f308  pc 40144b7c  cpsr 600d0030
I/DEBUG   (  369):     d0  513802003a373ed5  d1  0000b80c03000051
I/DEBUG   (  369):     d2  88000000560a1067  d3  0000003502000060
I/DEBUG   (  369):     d4  0000008849000000  d5  0a0e000000b80c0c
I/DEBUG   (  369):     d6  01003a0f0000003d  d7  0000885103000057
I/DEBUG   (  369):     d8  0000000000000000  d9  0000000000000000
I/DEBUG   (  369):     d10 0000000000000000  d11 0000000000000000
I/DEBUG   (  369):     d12 0000000000000000  d13 0000000000000000
I/DEBUG   (  369):     d14 0000000000000000  d15 0000000000000000
I/DEBUG   (  369):     d16 796669676e697274  d17 6b636174732e6528
I/DEBUG   (  369):     d18 0000000000000000  d19 0000000000000000
I/DEBUG   (  369):     d20 3e92819b25c7ba0a  d21 3ec722949499b49c
I/DEBUG   (  369):     d22 3efa019fabb79d95  d23 3f2a019f8723aeaa
I/DEBUG   (  369):     d24 3f56c16c16c76a94  d25 3f81111111185da8
I/DEBUG   (  369):     d26 3fa555555555551c  d27 3fc55555555554db
I/DEBUG   (  369):     d28 3fe0000000000000  d29 0000000000000001
I/DEBUG   (  369):     d30 fff0000000000000  d31 0000000000000000
I/DEBUG   (  369):     scr 88000012
I/DEBUG   (  369): 
I/DEBUG   (  369): backtrace:
I/DEBUG   (  369):     #00  pc 00023b7c  /system/lib/libc.so (strlen+83)
I/DEBUG   (  369):     #01  pc 007da304  /data/app-lib/com.example.hello-1/libjxcore.so (MozJS::String::FromUTF8(JSContext*, char const*, int)+40)
I/DEBUG   (  369): 
I/DEBUG   (  369): stack:
I/DEBUG   (  369):          674c6ef8  6762b040  
I/DEBUG   (  369):          674c6efc  63dfacc8  
I/DEBUG   (  369):          674c6f00  647a0330  
I/DEBUG   (  369):          674c6f04  00000001  
I/DEBUG   (  369):          674c6f08  67649160  
I/DEBUG   (  369):          674c6f0c  64786538  
I/DEBUG   (  369):          674c6f10  6764f1c0  
I/DEBUG   (  369):          674c6f14  00000000  
I/DEBUG   (  369):          674c6f18  00000000  
I/DEBUG   (  369):          674c6f1c  00000000  
I/DEBUG   (  369):          674c6f20  00000003  
I/DEBUG   (  369):          674c6f24  000000aa  
I/DEBUG   (  369):          674c6f28  0000006b  
I/DEBUG   (  369):          674c6f2c  0001416e  
I/DEBUG   (  369):          674c6f30  e3a070ad  
I/DEBUG   (  369):          674c6f34  ef9000ad  
I/DEBUG   (  369):     #00  674c6f38  00000000  
I/DEBUG   (  369):          ........  ........
I/DEBUG   (  369):     #01  674c6f38  00000000  
I/DEBUG   (  369):          674c6f3c  674c6f94  [stack:3358]
I/DEBUG   (  369):          674c6f40  674c6fb0  [stack:3358]
I/DEBUG   (  369):          674c6f44  674c6f94  [stack:3358]
I/DEBUG   (  369):          674c6f48  674c6f80  [stack:3358]
I/DEBUG   (  369):          674c6f4c  00000000  
I/DEBUG   (  369):          674c6f50  674c7fcc  [stack:3358]
I/DEBUG   (  369):          674c6f54  670063f0  /data/app-lib/com.example.hello-1/libjxcore.so
I/DEBUG   (  369):          674c6f58  674c6f88  [stack:3358]
I/DEBUG   (  369):          674c6f5c  00000000  
I/DEBUG   (  369):          674c6f60  674c6f7c  [stack:3358]
I/DEBUG   (  369):          674c6f64  66e38184  /data/app-lib/com.example.hello-1/libjxcore.so (js_fun_call(JSContext*, unsigned int, JS::Value*)+172)
I/DEBUG   (  369):          674c6f68  00000000  
I/DEBUG   (  369):          674c6f6c  00000000  
I/DEBUG   (  369):          674c6f70  4017338c  
I/DEBUG   (  369):          674c6f74  00000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r4:
I/DEBUG   (  369):     674c6f90 67651d80 67653b00 64786538 00000000  
I/DEBUG   (  369):     674c6fa0 647a0220 647a0230 00000001 4017002f  
I/DEBUG   (  369):     674c6fb0 00001000 4017338c 00001000 64786538  
I/DEBUG   (  369):     674c6fc0 647a02c8 674c6fd8 674c7354 66f14ab0  
I/DEBUG   (  369):     674c6fd0 00000002 00000000 647a02c8 00000000  
I/DEBUG   (  369):     674c6fe0 6731af28 00000001 67653b00 674c6fd8  
I/DEBUG   (  369):     674c6ff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c7000 00000000 00000000 00000040 674c7450  
I/DEBUG   (  369):     674c7010 6770f860 674c7450 6770f820 40132861  
I/DEBUG   (  369):     674c7020 0000000e 63dfecc8 674c7034 674c7000  
I/DEBUG   (  369):     674c7030 e0000000 00000006 00000000 00000001  
I/DEBUG   (  369):     674c7040 674c7450 00000040 63ce8160 6762b940  
I/DEBUG   (  369):     674c,7050 0000000c 6770f820 674c7450 00000040  
I/DEBUG   (  369):     674c7060 0000000c 66e6da20 674c7548 00000001  
I/DEBUG   (  369):     674c7070 677596d0 00000068 00000000 00000000  
I/DEBUG   (  369):     674c7080 00000000 00000000 674c7098 00000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r5:
I/DEBUG   (  369):     674c6f50 674c7fcc 670063f0 674c6f88 00000000  
I/DEBUG   (  369):     674c6f60 674c6f7c 66e38184 00000000 00000000  
I/DEBUG   (  369):     674c6f70 4017338c 00000000 674c7304 66f14b34  
I/DEBUG   (  369):     674c6f80 64786538 64786538 647a0330 00000001  
I/DEBUG   (  369):     674c6f90 67651d80 67653b00 64786538 00000000  
I/DEBUG   (  369):     674c6fa0 647a0220 647a0230 00000001 4017002f  
I/DEBUG   (  369):     674c6fb0 00001000 4017338c 00001000 64786538  
I/DEBUG   (  369):     674c6fc0 647a02c8 674c6fd8 674c7354 66f14ab0  
I/DEBUG   (  369):     674c6fd0 00000002 00000000 647a02c8 00000000  
I/DEBUG   (  369):     674c6fe0 6731af28 00000001 67653b00 674c6fd8  
I/DEBUG   (  369):     674c6ff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c7000 00000000 00000000 00000040 674c7450  
I/DEBUG   (  369):     674c7010 6770f860 674c7450 6770f820 40132861  
I/DEBUG   (  369):     674c7020 0000000e 63dfecc8 674c7034 674c7000  
I/DEBUG   (  369):     674c7030 e0000000 00000006 00000000 00000001  
I/DEBUG   (  369):     674c7040 674c7450 00000040 63ce8160 6762b940  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r6:
I/DEBUG   (  369):     64786518 63cfbb50 0000001b 5775b6e0 00000006  
I/DEBUG   (  369):     64786528 00000000 00000000 00000025 000000ab  
I/DEBUG   (  369):     64786538 63dfacc8 63ceab50 63ce8160 674c8898  
I/DEBUG   (  369):     64786548 00000000 63dfad14 63ce817c 00000000  
I/DEBUG   (  369):     64786558 00000001 63dfc11c 63dfc11c 2d6f0000  
I/DEBUG   (  369):     64786568 00000000 ffffff82 74650070 00000000  
I/DEBUG   (  369):     64786578 00000003 00000000 646f6e00 6f6d5f65  
I/DEBUG   (  369):     64786588 64786598 00000000 00000001 6f6e2f74  
I/DEBUG   (  369):     64786598 6d5f6564 6c75646f 64786538 67717f00  
I/DEBUG   (  369):     647865a8 00000003 00000000 1e000000 66fb9ef8  
I/DEBUG   (  369):     647865b8 63c56984 00000000 00000001 6473622f  
I/DEBUG   (  369):     647865c8 00000002 ffffff84 736a2e00 00000000  
I/DEBUG   (  369):     647865d8 000000a8 0000001b 576d9ac0 00000008  
I/DEBUG   (  369):     647865e8 00000000 00000000 00000001 0000001b  
I/DEBUG   (  369):     647865f8 576da438 00000014 00000000 00000000  
I/DEBUG   (  369):     64786608 00000001 0000001b 576da5c8 00000032  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r7:
I/DEBUG   (  369):     674c6f50 674c7fcc 670063f0 674c6f88 00000000  
I/DEBUG   (  369):     674c6f60 674c6f7c 66e38184 00000000 00000000  
I/DEBUG   (  369):     674c6f70 4017338c 00000000 674c7304 66f14b34  
I/DEBUG   (  369):     674c6f80 64786538 64786538 647a0330 00000001  
I/DEBUG   (  369):     674c6f90 67651d80 67653b00 64786538 00000000  
I/DEBUG   (  369):     674c6fa0 647a0220 647a0230 00000001 4017002f  
I/DEBUG   (  369):     674c6fb0 00001000 4017338c 00001000 64786538  
I/DEBUG   (  369):     674c6fc0 647a02c8 674c6fd8 674c7354 66f14ab0  
I/DEBUG   (  369):     674c6fd0 00000002 00000000 647a02c8 00000000  
I/DEBUG   (  369):     674c6fe0 6731af28 00000001 67653b00 674c6fd8  
I/DEBUG   (  369):     674c6ff0 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c7000 00000000 00000000 00000040 674c7450  
I/DEBUG   (  369):     674c7010 6770f860 674c7450 6770f820 40132861  
I/DEBUG   (  369):     674c7020 0000000e 63dfecc8 674c7034 674c7000  
I/DEBUG   (  369):     674c7030 e0000000 00000006 00000000 00000001  
I/DEBUG   (  369):     674c7040 674c7450 00000040 63ce8160 6762b940  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near r9:
I/DEBUG   (  369):     674c6f8c 00000001 67651d80 67653b00 64786538  
I/DEBUG   (  369):     674c6f9c 00000000 647a0220 647a0230 00000001  
I/DEBUG   (  369):     674c6fac 4017002f 00001000 4017338c 00001000  
I/DEBUG   (  369):     674c6fbc 64786538 647a02c8 674c6fd8 674c7354  
I/DEBUG   (  369):     674c6fcc 66f14ab0 00000002 00000000 647a02c8  
I/DEBUG   (  369):     674c6fdc 00000000 6731af28 00000001 67653b00  
I/DEBUG   (  369):     674c6fec 674c6fd8 00000000 00000000 00000000  
I/DEBUG   (  369):     674c6ffc 00000000 00000000 00000000 00000040  
I/DEBUG   (  369):     674c700c 674c7450 6770f860 674c7450 6770f820  
I/DEBUG   (  369):     674c701c 40132861 0000000e 63dfecc8 674c7034  
I/DEBUG   (  369):     674c702c 674c7000 e0000000 00000006 00000000  
I/DEBUG   (  369):     674c703c 00000001 674c7450 00000040 63ce8160  
I/DEBUG   (  369):     674c704c 6762b940 0000000c 6770f820 674c7450  
I/DEBUG   (  369):     674c705c 00000040 0000000c 66e6da20 674c7548  
I/DEBUG   (  369):     674c706c 00000001 677596d0 00000068 00000000  
I/DEBUG   (  369):     674c707c 00000000 00000000 00000000 674c7098  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near sl:
I/DEBUG   (  369):     674c84e8 674c88c8 674c8500 674c887c 66f14ab0  
I/DEBUG   (  369):     674c84f8 00000008 6763dd90 674c88c8 00000001  
I/DEBUG   (  369):     674c8508 6731af28 00000001 6762f680 674c8500  
I/DEBUG   (  369):     674c8518 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c8528 00000000 00000000 00000101 00000000  
I/DEBUG   (  369):     674c8538 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c8548 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c8558 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c8568 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c8578 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c8588 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c8598 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c85a8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c85b8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c85c8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c85d8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near fp:
I/DEBUG   (  369):     674c6f34 ef9000ad 00000000 674c6f94 674c6fb0  
I/DEBUG   (  369):     674c6f44 674c6f94 674c6f80 00000000 674c7fcc  
I/DEBUG   (  369):     674c6f54 670063f0 674c6f88 00000000 674c6f7c  
I/DEBUG   (  369):     674c6f64 66e38184 00000000 00000000 4017338c  
I/DEBUG   (  369):     674c6f74 00000000 674c7304 66f14b34 64786538  
I/DEBUG   (  369):     674c6f84 64786538 647a0330 00000001 67651d80  
I/DEBUG   (  369):     674c6f94 67653b00 64786538 00000000 647a0220  
I/DEBUG   (  369):     674c6fa4 647a0230 00000001 4017002f 00001000  
I/DEBUG   (  369):     674c6fb4 4017338c 00001000 64786538 647a02c8  
I/DEBUG   (  369):     674c6fc4 674c6fd8 674c7354 66f14ab0 00000002  
I/DEBUG   (  369):     674c6fd4 00000000 647a02c8 00000000 6731af28  
I/DEBUG   (  369):     674c6fe4 00000001 67653b00 674c6fd8 00000000  
I/DEBUG   (  369):     674c6ff4 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c7004 00000000 00000040 674c7450 6770f860  
I/DEBUG   (  369):     674c7014 674c7450 6770f820 40132861 0000000e  
I/DEBUG   (  369):     674c7024 63dfecc8 674c7034 674c7000 e0000000  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near ip:
I/DEBUG   (  369):     67328b80 4012eb10 4012eaf0 5d95dccd 5d95ddd1  
I/DEBUG   (  369):     67328b90 4012edf1 5d95ddff 4012eddd 5d95dda3  
I/DEBUG   (  369):     67328ba0 40144b29 5d95dc51 40136669 40147929  
I/DEBUG   (  369):     67328bb0 4013684d 40148005 40147f75 401361d5  
I/DEBUG   (  369):     67328bc0 40144548 40143d64 4013e585 40147571  
I/DEBUG   (  369):     67328bd0 4013e6f9 40143fe0 40136189 4013627d  
I/DEBUG   (  369):     67328be0 401478ad 401484e7 4014a8b5 401476b1  
I/DEBUG   (  369):     67328bf0 401478c5 401447e1 401440f1 40135155  
I/DEBUG   (  369):     67328c00 4014d20d 4012fad0 4012fbbc 4012f9cc  
I/DEBUG   (  369):     67328c10 40135a2d 40141c3c 4014251c 4014fac5  
I/DEBUG   (  369):     67328c20 4014f011 40142ba8 40151a41 400fb02d  
I/DEBUG   (  369):     67328c30 400fb0b1 400fb161 40143908 4015d255  
I/DEBUG   (  369):     67328c40 4012fe58 40142da4 4012f69c 4012f6f4  
I/DEBUG   (  369):     67328c50 4012f7a8 4012f6b0 40146410 40137c01  
I/DEBUG   (  369):     67328c60 400fafdd 4012ee19 401424dc 40142188  
I/DEBUG   (  369):     67328c70 40140925 4011dc91 4011dd25 4014294c  
I/DEBUG   (  369): 
I/DEBUG   (  369): memory near sp:
I/DEBUG   (  369):     674c6f18 00000000 00000000 00000003 000000aa  
I/DEBUG   (  369):     674c6f28 0000006b 0001416e e3a070ad ef9000ad  
I/DEBUG   (  369):     674c6f38 00000000 674c6f94 674c6fb0 674c6f94  
I/DEBUG   (  369):     674c6f48 674c6f80 00000000 674c7fcc 670063f0  
I/DEBUG   (  369):     674c6f58 674c6f88 00000000 674c6f7c 66e38184  
I/DEBUG   (  369):     674c6f68 00000000 00000000 4017338c 00000000  
I/DEBUG   (  369):     674c6f78 674c7304 66f14b34 64786538 64786538  
I/DEBUG   (  369):     674c6f88 647a0330 00000001 67651d80 67653b00  
I/DEBUG   (  369):     674c6f98 64786538 00000000 647a0220 647a0230  
I/DEBUG   (  369):     674c6fa8 00000001 4017002f 00001000 4017338c  
I/DEBUG   (  369):     674c6fb8 00001000 64786538 647a02c8 674c6fd8  
I/DEBUG   (  369):     674c6fc8 674c7354 66f14ab0 00000002 00000000  
I/DEBUG   (  369):     674c6fd8 647a02c8 00000000 6731af28 00000001  
I/DEBUG   (  369):     674c6fe8 67653b00 674c6fd8 00000000 00000000  
I/DEBUG   (  369):     674c6ff8 00000000 00000000 00000000 00000000  
I/DEBUG   (  369):     674c7008 00000040 674c7450 6770f860 674c7450  
I/DEBUG   (  369): 
I/DEBUG   (  369): code around pc:
I/DEBUG   (  369):     40144b5c b31a2b01 0f04f013 800af000 3b04f851  
I/DEBUG   (  369):     40144b6c 3c01f1a3 0c03ea2c 3c80f01c 8033f040  
I/DEBUG   (  369):     40144b7c 2302e8f1 f040f891 3c01f1a2 0c02ea2c  
I/DEBUG   (  369):     40144b8c 3c80f01c 800ff040 3c01f1a3 0c03ea2c  
I/DEBUG   (  369):     40144b9c 3c80f01c 801ff040 bfeaf7ff 0000eba1  
I/DEBUG   (  369):     40144bac 0001f1a0 eba14770 ea5f0000 f040434c  
I/DEBUG   (  369):     40144bbc f0808009 ea5f800a f0400c4c f1a08009  
I/DEBUG   (  369):     40144bcc 47700005 0008f1a0 f1a04770 47700007  
I/DEBUG   (  369):     40144bdc 0006f1a0 eba14770 ea5f0000 f040434c  
I/DEBUG   (  369):     40144bec f0808009 ea5f800a f0400c4c f1a08009  
I/DEBUG   (  369):     40144bfc 47700001 0004f1a0 f1a04770 47700003  
I/DEBUG   (  369):     40144c0c 0002f1a0 bf004770 f000f890 b430b501  
I/DEBUG   (  369):     40144c1c 46054696 0404ea84 f0114608 d01d0307  
I/DEBUG   (  369):     40144c2c 0308f1c3 7cc3ea5f f811d002 b3422b01  
I/DEBUG   (  369):     40144c3c f013d308 d0050c02 2b01f811 f811b30a  
I/DEBUG   (  369):     40144c4c b1f22b01 0f04f013 f851d008 f1a33b04  
I/DEBUG   (  369): 
I/DEBUG   (  369): code around lr:
I/DEBUG   (  369):     6702f2e8 e24dd008 e1a08002 e1a07000 e1a06001  
I/DEBUG   (  369):     6702f2f8 11a02003 1a000002 e1a00008 ebe8a1f5  
I/DEBUG   (  369):     6702f308 e1a02000 e3520000 da00000a e1d830d0  
I/DEBUG   (  369):     6702f318 e3530000 ba000012 e288c001 e0884002  
I/DEBUG   (  369):     6702f328 ea000002 e0dce0d1 e35e0000 ba00000c  
I/DEBUG   (  369):     6702f338 e15c0004 1afffffa e1a01008 e1a00006  
I/DEBUG   (  369):     6702f348 ebf76630 e1a02006 e3a03000 e1a01000  
I/DEBUG   (  369):     6702f358 e1a00007 ebffff2b e1a00007 e24bd014  
I/DEBUG   (  369):     6702f368 e8bd89d0 e3a00000 e24b3014 e1a01008  
I/DEBUG   (  369):     6702f378 e5230004 e1a00006 ebfff958 e51b1018  
I/DEBUG   (  369):     6702f388 e3510000 0a000006 e1a02006 e1a00007  
I/DEBUG   (  369):     6702f398 e3a03000 ebffff1b e1a00007 e24bd014  
I/DEBUG   (  369):     6702f3a8 e8bd89d0 e59f0020 e59f2020 e59f3020  
I/DEBUG   (  369):     6702f3b8 e3a01e3f e08f0000 e08f2002 e08f3003  
I/DEBUG   (  369):     6702f3c8 ebe8a299 e51b1018 eaffffee 001f6ed0  
I/DEBUG   (  369):     6702f3d8 002a3448 001f6ef8 e92d4878 e1a05001  
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
D/AutoSetting( 1301): receiver - intent: android.intent.action.USER_PRESENT
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
D/TetherSettings( 3136): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3136): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3136): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3136): Cust_ConnectToPC   : spcsc>false
D/        ( 3136): Cust_ConnectToPC   : IPT>true
D/        ( 3136): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3136): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3136): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3136): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3136): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/PSReceiver( 3136): onReceive:android.intent.action.USER_PRESENT
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/SmartNS_PSService( 3136): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3136): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3136):  defaultType:0
W/ContextImpl( 3136): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Delay finish: com.android.settings/.PSReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(428db1b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/ActivityManager(  907): Resuming delayed broadcast
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
D/PMS     (  907): acquireWL(427193a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 907 1000 WorkSource{10029}
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/ActivityManager(  907): Start proc com.htc.sense.browser for broadcast com.htc.sense.browser/.htc.util.HTCBrowserSimStateChangeReceiver: pid=3375 uid=10012 gids={50012, 5001, 3003, 5012, 1028, 1015, 1023}
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
D/PMS     (  907): releaseWL(428db1b8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(426c4ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(4270c908): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.auth.api.credentials/com.google/***** 0x1 WorkSource{10029}
,D/PMS     (  907): releaseWL(426c4ff8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42755568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(42755568): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(429d9090): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,I/DEBUG   (  369): --- --- --- --- --- --- --- --- --- --- --- --- --- --- --- ---
,I/IntentController( 1115): receive(android.intent.action.SYNC_STATE_CHANGED,1,false)
D/PMS     (  907): releaseWL(427193a8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.chromesync/com.google/***** 0x1 WorkSource{10029}
D/PMS     (  907): releaseWL(429d9090): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/browser ( 3375): Browser versionCode = 760001523 versionName = 7.0.2512153020
,E/ActivityManager(  907): App crashed! Process: com.example.hello
W/ActivityManager(  907):   Force finishing activity com.example.hello/.MainActivity
I/ActivityManager(  907): mThumbnailWidth=360, mThumbnailHeight=640
I/BootReceiver(  907): Copying /data/tombstones/tombstone_00 to DropBox (SYSTEM_TOMBSTONE)
,W/asset   (  907): Copying FileAsset 0x63910928 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/InputDispatcher(  907): channel '426112f8 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher(  907): channel '426112f8 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '426112f8 com.example.hello.MainActivity (s)'
D/PMS     (  907): acquireWL(428a1370): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/WindowManager(  907): WINDOW DIED Window{426112f8 u0 com.example.hello/com.example.hello.MainActivity}
I/ActivityManager(  907): Recipient 3285
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/WindowState(  907): WIN DEATH: Window{426112f8 u0 com.example.hello/com.example.hello.MainActivity EXITING}
,D/PhoneStatusBar( 1115): removeIcon slot=sync_active index=7 viewIndex=0
I/ActivityManager(  907): Process com.example.hello (pid 3285) has died.
,I/FeedHostManager( 1288): [onResume]
,I/FeedProviderManager( 1288): onResume
I/SocialFeedProvider( 1288): +onResume
I/SocialFeedProvider( 1288): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1288): -onResume
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1288/10076)
,W/SWE_UI  ( 3375): SWE using SurfaceView - Multi-Process
,I/LibraryLoader( 3375): Loading: swewebviewchromium
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:58, mTXpacketCount:20, avgLinkspeed:24,mAvgTxRate54
D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
I/LibraryLoader( 3375): Time to load native libraries: 37 ms (timestamps 9771-9808)
D/Zygote  (  370): Process 3285 terminated by signal (11)
I/LibraryLoader( 3375): Expected native library version number "",actual native library version number ""
I/BrowserStartupController( 3375): Initializing chromium process, renderers=9
I/LibraryLoader( 3375): Expected native library version number "",actual native library version number ""
,I/chromium( 3375): [INFO:library_loader_hooks.cc(113)] Chromium logging enabled: level = 0, default verbosity = 0
,D/PMS     (  907): releaseWL(428a1370): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,I/Adreno-EGL( 3375): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3375): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3375): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3375): Local Branch: 
I/Adreno-EGL( 3375): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3375): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3375):                  aa63bbd948f41d15fc72f585e
,V/IccIntentReceiver( 1241): IccIntent: android.intent.action.SIM_STATE_CHANGED icc state: ABSENT phone_type: 1 icc slot: -1
,I/SIMStateChangeReceiver( 1500): SIM state: ABSENT
I/SIMStateChangeReceiver( 1500): phoneType = 0
,I/SIMStateChangeReceiver( 1500): remove notification
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=3421 uid=10032 gids={50032, 3003, 5012}
,I/ActivityManager(  907): Start proc com.htc.contacts for broadcast com.htc.contacts/.BootCompletedReceiver: pid=3433 uid=10044 gids={50044, 3003, 5012, 1028, 1015, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3011
,I/ActivityManager(  907): Killing 3011:com.htc.backup/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3011
,W/SystemReader( 2739): Cannot find message_ambs_application_id, use default value instead
,D/SmsReceiver( 2739): Don't handle ACTION_SIM_STATE_CHANGED not ready action 
D/ExchangePolicystatus( 2739): onReceive()
D/ExchangePolicystatus( 2739): onReceive(): ACTION_SIM_STATE_CHANGED
,D/ExchangePolicystatus( 2739): onReceive(): else
,D/Process (  907): killProcessQuiet, pid=2957
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/HtcBroadcastReceiver( 1257): onReceive: android.intent.action.SIM_STATE_CHANGED
I/ActivityManager(  907): Killing 2957:com.htc.cs.dm/u0a98 (adj 15): empty #17
,W/WeatherUtility( 1115): can't get weather sync account
I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=3449 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/AccTypeManager( 3433): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/WeatherRequest( 1115): request cur loc, but there is no sys cur
,D/CalendarApplication( 3449): onCreate
D/ProviderChangeReceiver( 3449): ---------------------------------------------------
,D/ProviderChangeReceiver( 3449): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 3449): start to updateAlertNotification!
W/AccTypeManager( 3433): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3433): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/AlertService( 3449): No fired or scheduled alerts
,D/HtcAlertUtils( 3449): -- cancelReminderNotification --
,D/HtcAlertUtils( 3449): broadcastExistReminder!
W/ContextImpl( 3111): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  907): Recipient 2957
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.android.settings/.framework.app.HtcDndCommandReceiver
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,E/ExternalAccountType( 3433): Unsupported attribute readOnly
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3467 uid=10041 gids={50041}
,D/Process (  907): killProcessQuiet, pid=3037
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3037:com.google.android.talk/u0a111 (adj 15): empty #17
,D/AccTypeManager( 3433): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/WIFI_ICON( 1115): WifiActivity: 1
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/AccTypeManager( 3433): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 3433): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,E/ExternalAccountType( 3433): Unsupported attribute readOnly
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3480 uid=10078 gids={50078}
,D/Process (  907): killProcessQuiet, pid=2581
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 2581:com.android.defcontainer/u0a19 (adj 15): empty #17
I/ActivityManager(  907): Recipient 2581
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
D/PMS     (  907): releaseHCC(42735e78): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  907): releaseHCC(42734f78): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
I/ActivityManager(  907): Recipient 3037
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SMSBackup( 3480): Got a database change event
,D/Process (  907): killProcessQuiet, pid=3064
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3064:com.htc.backupreset/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3064
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
,D/LocationInitializer( 2184): Restart initialization of location
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,E/MDM     ( 1227): [99] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ActivityManager(  907): Resuming delayed broadcast
D/AuthorizationBluetoothService( 1347): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.WeatherClock4x1: pid=3497 uid=10045 gids={50045, 3002, 3001, 3003, 5012}
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
D/PMS     (  907): acquireWL(4269c430): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4269c430): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,W/WeatherUtility( 3497): can't get weather sync account
,W/WeatherRequest( 3497): request cur loc, but there is no sys cur
,W/Settings( 3497): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1288): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1288): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1288): com.htc.widget.weatherclock 1 12 17
,D/PMS     (  907): releaseWL(42682798): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=3512 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3082
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  907): Killing 3082:com.htc.htccupd/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3082
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/MusicStore( 3512): Database version: 95
,W/ContextImpl( 3512): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3512): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3512): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3512, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 3512): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
I/MediaRouter( 3512): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3512/10154)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1973/10021)
I/NetworkMonitor( 3512): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,I/ActivityManager(  907): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=3531 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3512): getSelectedRoute
,I/NetworkMonitor( 3512): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3512/10154)
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3512, uid=10154, userID:0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/Process (  907): killProcessQuiet, pid=3097
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(42867070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
I/ActivityManager(  907): Killing 3097:com.zoodles.kidmode/u0a149 (adj 15): empty #17
D/PMS     (  907): releaseWL(42867070): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/ACRA    ( 3531): ACRA is enabled for com.facebook.katana, intializing...
,I/ActivityManager(  907): Recipient 3097
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ACRA    ( 3531): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 3531): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 3531): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 3531): Preparing secondary program dexes.
V/DexLibLoader( 3531): Loaded 4 raw lines of metadata.
,V/DexLibLoader( 3531): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 3531): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 3531): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 3531): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary
,W/DexLibLoader( 3531): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock,
V/DexLibLoader( 3531): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar,
V/DexLibLoader( 3531): Dex already copied
D/OdexVerifier( 3531): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3531): Creating class loader,
,V/DexLibLoader( 3531): Finished creating class loader,
V/DexLibLoader( 3531): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar
,V/DexLibLoader( 3531): Dex already copied
,D/OdexVerifier( 3531): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3531): Creating class loader,
,V/DexLibLoader( 3531): Finished creating class loader,
V/DexLibLoader( 3531): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar,
V/DexLibLoader( 3531): Dex already copied,
D/OdexVerifier( 3531): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3531): Creating class loader,
,V/DexLibLoader( 3531): Finished creating class loader
,V/DexLibLoader( 3531): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 3531): Dex already copied
D/OdexVerifier( 3531): Odex verification is skipped. OS version not supported.
,V/DexLibLoader( 3531): Creating class loader
,V/DexLibLoader( 3531): Finished creating class loader
,V/DexLibLoader( 3531): Verifying classes from secondary dexes.
,D/DexLibLoader( 3531): DexLibLoader.ensureDexLoaded took 163 ms
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 4 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,V/AlarmManager(  907): sending alarm PendingIntent{41bf2a58: PendingIntentRecord{424ecc98 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=52042, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{421643b0: PendingIntentRecord{42209d90 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1452261042588, Int=1800000
,W/dalvikvm( 3531): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 3531): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 3531): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,W/fb4a(:<default>):StaticBindingVerifier( 3531): Verify
,D/WifiService(  907): New client listening to asynchronous messages
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3531/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3531): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 3531): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 3531): Grow heap (frag case) to 9.510MB for 73240-byte allocation
,D/Process (  907): killProcessQuiet, pid=3123
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3123:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3123
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/AutoSetting( 1301): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3553 uid=10079 gids={50079, 3003, 5012}
,D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1301): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1301): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1301): service - onStartCommand() REMOVE current location bundle
,D/AutoSetting( 1301): service - handleMessage() setting current location null
,D/AutoSetting( 1301): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1301): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
,D/MobileConnectivityChangeReceiver( 3553): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 3553): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3553): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 3553): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,D/Process (  907): killProcessQuiet, pid=3151
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3566 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 3151:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3553/10079)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3553/10079)
,I/ActivityManager(  907): Recipient 3151
,W/fb4a(:<default>):UserScope( 3531): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 3531): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(4289d048): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3553/10079)
,D/PMS     (  907): acquireWL(42746040): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1452248371148 min interval config: 0 actual interval: 12673028
,D/PMS     (  907): releaseWL(4289d048): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2184): Checking schedule, now: 1452261044181 next: 1452248401103
,I/CheckinService( 2184): active receiver: enabled
,W/fb4a(:<default>):UserScope( 3531): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2184, uid=10029, userID:0
,I/CheckinService( 2184): Preparing to send checkin request
,I/EventLogService( 2184): Accumulating logs since 1452259242332
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3531): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3584 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3165
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3165:com.android.smith/u0a163 (adj 15): empty #17
,E/dalvikvm( 3531): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 3531): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3531): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 3531): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3531): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 3531): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3531): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 3531): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3531): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3531): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 3531): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 3531): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3531): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3531): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3531): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
,W/dalvikvm( 3531): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3531): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
,W/dalvikvm( 3531): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/ActivityManager(  907): Waited long enough for: ServiceRecord{428c7890 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
D/WifiService(  907): New client listening to asynchronous messages
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/GAV2    ( 3584): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,I/dalvikvm-heap( 3531): Grow heap (frag case) to 9.925MB for 39954-byte allocation
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3584): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  907): Recipient 3165
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 3531): Grow heap (frag case) to 10.001MB for 79892-byte allocation
,I/dalvikvm-heap( 3531): Grow heap (frag case) to 10.068MB for 84664-byte allocation
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3584/10151)
,V/WebViewChromiumFactoryProvider( 3584): Binding Chromium to main looper Looper (main, tid 1) {41b64e80}
,I/LibraryLoader( 3584): Expected native library version number "",actual native library version number ""
,I/chromium( 3584): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 3584): Initializing chromium process, renderers=0
,D/PMS     (  907): acquireWL(428d8618): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  907): acquireWL(428bd338): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 3584): BLUETOOTH permission is missing!
D/PMS     (  907): releaseWL(428d8618): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3584): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3584): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3584): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3584): Local Branch: 
I/Adreno-EGL( 3584): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3584): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3584):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 3584): Starting up...
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3584/10151)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3584/10151)
I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3622 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=3177
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3177:com.google.android.youtube/u0a168 (adj 15): empty #17
I/dalvikvm-heap( 3531): Grow heap (frag case) to 10.281MB for 75760-byte allocation
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3531/10027)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42703f48 u0 ReceiverList{41f5df50 3531 com.facebook.katana/10027/u0 remote:4241c118}}
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42703f48 u0 ReceiverList{41f5df50 3531 com.facebook.katana/10027/u0 remote:4241c118}}
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{426e6990 u0 ReceiverList{41f55480 3531 com.facebook.katana/10027/u0 remote:423f9bb0}}
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3531/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3531/10027)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3531/10027)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/dalvikvm( 1347): VFY: unable to resolve virtual method 17: Landroid/accounts/AccountManager;.renameAccount (Landroid/accounts/Account;Ljava/lang/String;Landroid/accounts/AccountManagerCallback;Landroid/os/Handler;)Landroid/accounts/AccountManagerFuture;
,I/ActivityManager(  907): Recipient 3177
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.youtube (pid 3177): Died!
,D/PMS     (  907): acquireWL(425fc858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=100 [1][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(425fc858): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  907): acquireWL(41d0fa18): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3622 10160 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3622/10160)
D/PMS     (  907): acquireWL(4227fa20): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3622 10160 null
D/PMS     (  907): releaseWL(41d0fa18): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,W/dalvikvm( 1347): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 1347): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
,W/dalvikvm( 1347): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
I/SensorManager(  907): mEventCount = 300
,I/SensorManager(  907): mEventCount = 300
,W/dalvikvm( 1347): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/PMS     (  907): releaseWL(4227fa20): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/Process (  907): killProcessQuiet, pid=3235
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3235:com.android.vending/u0a74 (adj 15): empty #17
,I/iu.SyncManager( 2184): SYNC; picasa accounts
D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 1347): [NET] getaddrinfo-, 1
,D/libc    ( 1347): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =1b61 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3235
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3531): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/NetworkLogImpl( 2184): Loaded NetworkSpeedPredictor
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/iu.Environment( 2184): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3531): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/dalvikvm-heap( 3622): Grow heap (frag case) to 15.208MB for 1821008-byte allocation
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1347): [NET] getaddrinfo_proxy-, success
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/iu.UploadsManager( 2184): num queued entries: 0
,I/iu.UploadsManager( 2184): num updated entries: 0
,I/iu.SyncManager( 2184): NEXT; no task
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1347/10029)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
,I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3658 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3658): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3658): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
,I/RestoreService( 3658): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3672 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3136
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3136:com.android.settings/1000 (adj 15): empty #17
,D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
D/libc    ( 1347): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 1347): [NET] getaddrinfo-,err=8
,D/PMS     (  907): acquireWL(426541e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3672 10071 null
,D/PMS     (  907): acquireWL(426a7088): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3672 10071 null
,D/PMS     (  907): releaseWL(426541e0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/TodoTaskshortcut( 3672): update TASK shortcut>
,I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3687 uid=10082 gids={50082, 3003, 5012}
,I/TodoTaskNotifyService( 3672): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/PMS     (  907): releaseWL(426a7088): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,W/NotifyReceiver( 3672): stopSelfResult true
,D/Process (  907): killProcessQuiet, pid=3375
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Recipient 3136
I/ActivityManager(  907): Killing 3375:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3699 uid=10082 gids={50082, 3003, 5012}
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3375
,D/Process (  907): killProcessQuiet, pid=3421
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AlertReceiver( 3449): beginStartingService
,D/Process (  907): killProcessQuiet, pid=3433
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3421:com.google.android.partnersetup/u0a32 (adj 15): empty #17
D/PMS     (  907): acquireWL(426b2368): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3449 10013 null
I/ActivityManager(  907): Killing 3433:com.htc.contacts/u0a44 (adj 15): empty #17
I/ActivityManager(  907): Recipient 3421
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherUtility( 3497): can't get weather sync account
D/PMS     (  907): acquireWL(4267aea8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3672 10071 null
D/PMS     (  907): acquireWL(42850b08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3672 10071 null
D/PMS     (  907): releaseWL(4267aea8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3719 uid=10090 gids={50090, 3003, 5012, 1028}
D/AlertService( 3449): start to updateAlertNotification!
D/TodoTaskshortcut( 3672): update TASK shortcut>
,D/AlertService( 3449): No fired or scheduled alerts
,D/HtcAlertUtils( 3449): -- cancelReminderNotification --
,D/HtcAlertUtils( 3449): broadcastExistReminder!
,I/TodoTaskNotifyService( 3672): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PMS     (  907): releaseWL(426b2368): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/AlertReceiver( 3449): stopSelfResult true
,W/WeatherRequest( 1115): request cur loc, but there is no sys cur
,I/TodoTaskNotifyService( 3672): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3672): stopSelfResult true
D/PMS     (  907): releaseWL(42850b08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,I/WorldClock.Global( 3719): isHtcDevice = true
,W/WeatherRequest( 3497): request cur loc, but there is no sys cur
,W/Settings( 3497): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WorldClock.Global( 3719): isHtcDevice = true
W/ContextImpl( 3111): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/WorldClock.AlarmUtils( 3719): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3719): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3719): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/ActivityManager(  907): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3734 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/IntentController( 1115): receive(android.intent.action.ALARM_CHANGED,1,false)
D/AppWidgetHostView( 1288): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1288): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1288): com.htc.widget.weatherclock 1 10 17
,D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,I/ActivityManager(  907): Recipient 3433
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=10 [10][1][0],
D/MessagingNotification( 2739): New incoming message, can't cancel notification now
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/MessagingNotification( 2739): newMsgCnt: 0, false
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/TimeService( 3734): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452261045313
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3750 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,D/Process (  907): killProcessQuiet, pid=3467
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3467:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,D/PMS     (  907): acquireWL(42741ce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Recipient 3467
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): releaseWL(42741ce0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2184): Checkin interval check for package: unspecified last checkin: 1452248371148 min interval config: 0 actual interval: 12674207
D/WIFI_ICON( 1115): WifiActivity: 3
D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
D/PMS     (  907): acquireWL(428c39a0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4273c480): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428c39a0): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42873690): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 2184 10029 null
,I/EventLogService( 2184): Aggregate from 1452261044265 (log), 1452259242332 (data)
D/PMS     (  907): acquireWL(428dad78): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
D/PMS     (  907): releaseWL(42873690): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.reminders.notification.NotificationService 0x1 null
D/PMS     (  907): releaseWL(428dad78): PARTIAL_WAKE_LOCK  WakefulIntentService[NotificationService] 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3764 uid=10041 gids={50041}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(4273c480): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/SMSBackup( 3480): Got a database change event
,I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3777 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  907): killProcessQuiet, pid=3512
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,W/dalvikvm( 3750): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,I/ActivityManager(  907): Killing 3512:com.google.android.music:main/u0a154 (adj 15): empty #17
W/dalvikvm( 3750): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 3750): VM with version 1.6.0 does not have multidex support
I/MultiDex( 3750): install
I/MultiDex( 3750): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 3750): loading existing secondary dex files
,I/MultiDex( 3750): load found 3 secondary dex files
,I/MultiDex( 3750): install done
,W/dalvikvm( 3750): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 3750): VFY: unable to resolve instance field 36
,W/dalvikvm( 3750): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 3750): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ImageRamCache( 3777): create image Cache, size: 31457280.
I/ImageRamCache( 3777): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3777): create image Cache, size: 12582912.
,I/FeedSettings( 3777): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 3777): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3777): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3777): changeLocale(): en_GB
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MediaRouterService(  907): Client com.google.android.music (pid 3512): Died!
,I/Prism.AllAppsOptionsMa_( 3777): loadSortType() with Custom
,I/ActivityManager(  907): Recipient 3512
I/Prism.AllAppsOptionsMa_( 3777): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3777): [custom highlight] onReceive
,D/CustomHighlightService( 3777): [custom highlight] onHandleIntent
,D/MessagingShortcutReceiver( 2739): keep hiding shortcut bubble
D/MessagingShortcut( 2739): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2739): After query: 0
D/MessagingShortcut( 2739): mPresentUnreadCount: -1
,D/MessagingShortcut( 2739): setMsgShortcutDrawable> 0
,D/NewsDB  ( 3777): set custom highlight []
,D/MessagingShortcut( 2739): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] reorderNotification, total:0
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3672): update TASK shortcut>
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1257): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/ActivityManager(  907): Resuming delayed broadcast
,D/CustomHighlightService( 3777): [custom highlight] set tags 
I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3796 uid=10091 gids={50091, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3531
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3531:com.facebook.katana/u0a27 (adj 15): empty #17
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
,E/MDM     ( 1227): [101] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/ProviderInstaller( 3750): Installed default security provider GmsCore_OpenSSL
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/LocationInitializer( 2184): Restart initialization of location
I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3812 uid=10091 gids={50091, 3003, 5012}
I/ActivityManager(  907): Resuming delayed broadcast
,D/AuthorizationBluetoothService( 1347): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 3750): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 3750): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/MtpReceiver( 1973): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 1973): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 1973): [MTP][handleMessage][startService]
D/MtpReceiver( 1973): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
W/dalvikvm( 3750): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/MtpReceiver( 1973): [MTP][handleMessage]-
E/dalvikvm( 3750): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 3750): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 3750): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 3750): Link of class 'Lcom/google/android/gms/common/j/c;' failed
I/ActivityManager(  907): Recipient 3531
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,D/MtpService( 1973): [MTP] startForeground
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3830 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,D/PMS     (  907): acquireWL(41c2c718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
W/GCoreFlp( 1227): No location to return for getLastLocation()
W/FusedLocationProvider( 1227): location=null
D/MtpService( 1973): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 1973): TotalSize=1918604,MediaCacheLimit=6000
D/PMS     (  907): releaseWL(41c2c718): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1115): com.android.providers.media (false,0)
,D/MtpService( 1973): [isMtpConnected] connected: true
,I/RemoteViews.Performance( 1115): com.android.providers.media 7 1 10
,I/RemoteViews( 1115): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1115): com.android.providers.media 2 1 15
D/PMS     (  907): acquireWL(425300f0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 2184 10029 null
D/PMS     (  907): acquireWL(42472d20): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3622 10160 null
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,D/MdScBoot( 3796): [798.1.] 30@-145017 -> 40@-145045
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/Process (  907): killProcessQuiet, pid=3553
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3553:com.google.android.setupwizard/u0a79 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3553
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0,
,D/SyncApplication( 3830): Loading default preferences
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,W/Resources( 3830): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
D/Process (  907): killProcessQuiet, pid=3566
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/PMS     (  907): releaseWL(42472d20): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,I/ActivityManager(  907): Killing 3566:com.android.chrome/u0a96 (adj 15): empty #17
I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
I/ActivityManager(  907): Recipient 3566
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
I/WVCdm   (  372): CdmEngine::OpenSession
I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,I/iu.UploadsManager( 2184): End new media; added: 0, uploading: 0, time: 54 ms
D/PMS     (  907): releaseWL(425300f0): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService 0x1 null
D/WifiService(  907): New client listening to asynchronous messages
,D/NativeLibraryUtils( 3750): Install completed successfully. count=14 extracted=0
,D/SyncApplication( 3830): Overriding preferences with custom values
,W/dalvikvm( 3750): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,W/dalvikvm( 3750): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3750): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3750): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 3750): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/SyncApplication( 3830): Updating preferences succeeded
,E/SyncApplication( 3830): Application created.
,D/VolumeInfo( 3830): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
D/VolumeInfo( 3830): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3830): Found 0 mount point(s)
,V/VolumeInfo( 3830): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,I/GoogleURLConnFactory( 3750): Using platform SSLCertificateSocketFactory
,D/VolumeInfo( 3830): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3830): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
W/VolumeInfo( 3830): Can not create volume ID for unmounted volume null
,D/WVCdm   (  372): PrepareKeyRequest: nonce=644984879
,D/libc    ( 3750): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3750): [NET] getaddrinfo-,err=8
D/libc    ( 3750): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    ( 3750): [NET] getaddrinfo-, 1
,D/libc    ( 3750): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =4bd6 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,I/CalendarDefines( 3830): getNewCalendarAuthority()...
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3830, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
,D/SyncApplication( 3830): enableAppOperation()+
,D/SyncApplication( 3830): enableAppOperation()-
,D/HTCUtilities( 3830): isNeorSinged() + 
,D/HTCUtilities( 3830): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3830): isNeorSinged() return false
D/CDMountReceiver( 3830): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3830): USB connected to PC
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3830, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/FOTAReceiver( 3830): onReceive() enter 
,D/FOTAReceiver( 3830): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3857 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  365): [NET]res_nsend:resplen=86
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 3750): [NET] getaddrinfo_proxy-, success
,D/Process (  907): killProcessQuiet, pid=3584
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3584:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3584
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3857): -onCreate()
,V/Settings:HtcSettingsApplication( 3857): [3857/3857] onCreate()
,D/TetherSettings( 3857): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3857): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3857): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3857): Cust_ConnectToPC   : spcsc>false
D/        ( 3857): Cust_ConnectToPC   : IPT>true
,D/        ( 3857): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3857): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3857): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
,D/        ( 3857): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3857): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3857): Cust_ConnectToPC   : spcsc>false
D/        ( 3857): Cust_ConnectToPC   : IPT>true
,D/        ( 3857): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3857): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3857): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3857): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3857): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3857): usb_cable_connect = 1
,D/SmartNS_Utility( 3857): usb_denied = 0
I/SmartNS_NSReceiver( 3857): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3857): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3857): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3857): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3857): onReceive:com.htc.intent.action.USB_CONNECT2PC
D/libc    ( 3750): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3750): [NET] getaddrinfo-,err=8
D/libc    ( 3750): [NET] getaddrinfo+,hn 18(0x7777772e676f6f),sn(),family 0,flags 4
D/libc    ( 3750): [NET] getaddrinfo-,err=8
W/Settings( 3857): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3857):  defaultType:0
I/SmartNS_PSService( 3857): fail notificaiton:false
,D/SmartNS_Utility( 3857): usb_cable_connect = 1
D/SmartNS_Utility( 3857): usb_denied = 0
,I/SmartNS_PSService( 3857): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3857/1000)
D/AppWidgetHostView( 1288): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
W/WeatherUtility( 3497): can't get weather sync account
I/RemoteViews( 1288): com.google.android.googlequicksearchbox (false,0)
I/RemoteViews.Performance( 1288): com.google.android.googlequicksearchbox 1 0 5
D/SMSBackup( 3480): Got a database change event
,D/SmartNS_Utility( 3857): usb_cable_connect = 1
D/SmartNS_Utility( 3857): usb_denied = 0
,I/SmartNS_PSService( 3857): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,V/Tethering(  907): bSetPropertyMultiRAB:false
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3857/1000)
I/RemoteViews( 1115): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1115): com.android.settings 1 1 10
D/SmartNS_Utility( 3857): usb_cable_connect = 1
D/SmartNS_Utility( 3857): usb_denied = 0
I/RemoteViews( 1115): com.android.settings (true,33751552)
D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/RemoteViews.Performance( 1115): com.android.settings 1 1 10
I/SmartNS_PSService( 3857): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3857): USB Plugged, Set USBPlugged=  truePSenabled:false
W/WeatherRequest( 3497): request cur loc, but there is no sys cur
,W/Settings( 3497): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/Process (  907): killProcessQuiet, pid=3658
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3658:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,D/AppWidgetHostView( 1288): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1288): com.htc.widget.weatherclock (true,33751552)
I/ActivityManager(  907): Recipient 3658
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews.Performance( 1288): com.htc.widget.weatherclock 1 8 17
,D/PMS     (  907): acquireWL(4236fbd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver: pid=3872 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=6 [15][1][0]
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4236fbd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42562770): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3872 1000 null
,W/ContextImpl( 3872): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3872): call getInstance()
,D/WeatherUtility( 1301): Weather sync is On
,W/WeatherUtility( 1115): can't get weather sync account
,D/WSP     ( 1301): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3889 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherUtility( 3497): can't get weather sync account
,D/PowerUsageList:PowerUsageHelper( 3872): MY_DEBUG = false
,W/WeatherRequest( 3497): request cur loc, but there is no sys cur
,W/Settings( 3497): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1288): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1288): com.htc.widget.weatherclock (true,33751552)
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/RemoteViews.Performance( 1288): com.htc.widget.weatherclock 1 14 17
,D/ContactMessageStore( 1257): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1257): MSG_NOTIFY_CS_TO_SYNC <<
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3909 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3687
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3687:com.htc.stock/u0a82 (adj 15): empty #17
,I/Adreno-EGL( 3750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3750): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3750): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3750): Local Branch: 
I/Adreno-EGL( 3750): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3750): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3750):                  aa63bbd948f41d15fc72f585e
,I/MusicStore( 3909): Database version: 95
,W/ContextImpl( 3909): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/ActivityManager(  907): Recipient 3687
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/ContextImpl( 3909): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,I/Adreno-EGL( 3750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3750): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3750): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3750): Local Branch: 
I/Adreno-EGL( 3750): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3750): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3750):                  aa63bbd948f41d15fc72f585e
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3909): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (3750/10029)
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3909): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 3909): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3909, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 3909): Registered
,I/MediaRouter( 3909): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3909/10154)
I/NetworkMonitor( 3909): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [12][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/MediaRouter( 3909): getSelectedRoute
,I/NetworkMonitor( 3909): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3909/10154)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=3909, uid=10154, userID:0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000),
,D/PMS     (  907): acquireWL(425f61d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/TelephonyReceiver( 1257): bind: true
,D/Process (  907): killProcessQuiet, pid=3699
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(425f61d0): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3699:com.htc.stock:remote/u0a82 (adj 15): empty #17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/GenericMessagesProvider( 2739): query uri: content://htc-messages/wappush/count
I/ActivityManager(  907): Recipient 3699
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/SQLiteLog( 2739): (14) cannot open file at line 30190 of [00bb9c9ce4]
E/SQLiteLog( 2739): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 2739): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 2739): DB info: errno = 2, errno message = No such file or directory
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3931 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 2739): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 2739): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 2739): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 2739): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2739): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2739): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 2739): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 2739): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2739): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 2739): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 2739): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 2739): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 2739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 2739): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 2739): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 2739): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 2739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 2739): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 2739): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 2739): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 2739): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 2739): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 2739): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err( 2739): 	at dalvik.system.NativeStart.run(Native Method)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/TelephonyReceiver( 1257): s,witchBindHtcMsgCursor: null
,D/DFPI.PIReciver( 3931): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3931): onHandleIntent
,I/DFPI.ApkInstallService( 3931): Media Scan Finished Case 
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3931): check CID = HTC__032
,I/DFPI.ApkInstallService( 3931): There is no Demo.apk in sd card or phone storage
,D/Process (  907): killProcessQuiet, pid=3449
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3449:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3946 uid=10053 gids={50053, 1028, 1015, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3946/10053)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3946/10053)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{4264e320 u0 ReceiverList{4264e2c0 3946 com.htc.musicenhancer/10053/u0 remote:4264dfc8}}
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3946): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3449
,W/Settings( 3750): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=826815105
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/AlarmManager(  907): sending alarm PendingIntent{42652d40: PendingIntentRecord{42681810 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452261047389, Int=0
,I/WVCdm   (  372): CdmEngine::CloseSession
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3966 uid=10081 gids={50081, 5001, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3719
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3719:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3719
,D/PMS     (  907): releaseWL(428bd338): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 3750): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3750): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3750): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3750): Local Branch: 
I/Adreno-EGL( 3750): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3750): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3750):                  aa63bbd948f41d15fc72f585e
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/CheckinRequestBuilder( 2184): Classify the device as Phone.
I/SoundPicker( 3966): SoundP,ickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2184): [NET] getaddrinfo-, 1
,D/libc    ( 2184): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =cf7e +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2184): [NET] getaddrinfo_proxy-, success
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3111:com.android.settings:remote/1000 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3111
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/DFPI.PIReciver( 3931): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3931): onHandleIntent
I/DFPI.ApkInstallService( 3931): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3931): check CID = HTC__032
,I/DFPI.ApkInstallService( 3931): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Recipient 3111
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2184): [NET] getaddrinfo-,err=8
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
D/libc    ( 2184): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2184): [NET] getaddrinfo-,err=8
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/CheckinTask( 2184): Sending checkin request (12348 bytes)
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 5 times.
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoTaskReceiver
,I/ActivityManager(  907): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=3988 uid=10064 gids={50064, 3003, 5012, 1023, 1028, 1015}
,D/DFPI.PIReciver( 3931): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3931): onHandleIntent
,I/DFPI.ApkInstallService( 3931): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3931): check CID = HTC__032
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/DFPI.ApkInstallService( 3931): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/EASAppSvc( 3988): [ NA ]- onCreate()
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/EASAppSvc( 3988): [ NA ]> onUpgrade: version = 63
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,D/ORMLib  ( 3672): put()
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/EASAppSvc( 3988): [ NA ]- onDestroy()
,I/EASAppSvc( 3988): [ NA ]> uninitEASService
D/WifiService(  907): New client listening to asynchronous messages
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3988/10064)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3988/10064)
,D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3988/10064)
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/PMS     (  907): releaseWL(42562770): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/MediaStoreImporter( 3909): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,D/DFPI.PIReciver( 3931): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3931): onHandleIntent
I/DFPI.ApkInstallService( 3931): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3931): check CID = HTC__032
,I/DFPI.ApkInstallService( 3931): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3966): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3966): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3966): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3966): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3966): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/262
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/208
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/236
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/242
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/244
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
W/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/238
I/SoundPicker( 3966): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3966): MODE_GSM access default DB
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=1
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
,I/EASRequestController( 3988): [ NA ]release
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/EASAppSvc( 3988): [ NA ]< uninitEASService
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=2
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
I/EASAppSvc( 3988): [ NA ]- onCreate()
I/EASAppSvc( 3988): [ NA ]> onUpgrade: version = 63
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/262 type=3
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/262
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.android.mail (3988/10064)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.htc.android.mail (3988/10064)
,D/ConnectivityService(  907): getNetworkInfo networkType=55 called by com.htc.android.mail (3988/10064)
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/ORMLib  ( 3672): put()
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=4
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3966): getActualDefaultRingtoneUri(context, 4)
,I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/208 type=5
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/208
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/236 type=6
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/236
I/EASAppSvc( 3988): [ NA ]- onDestroy()
,I/EASAppSvc( 3988): [ NA ]> uninitEASService
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/EASRequestController( 3988): [ NA ]release
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/EASAppSvc( 3988): [ NA ]< uninitEASService
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/242 type=7
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/242
,I/ActivityManager(  907): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4026 uid=10068 gids={50068, 3003, 5012}
I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/244 type=8
I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/244
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3966): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/238 type=9
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/238
,I/SoundPicker( 3966): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3966): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/CheckinRequestBuilder( 2184): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  907): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2184): Failed to find provider info for com.google.android.wearable.settings
,D/Process (  907): killProcessQuiet, pid=3734
,I/ActivityManager(  907): Killing 3734:com.qualcomm.timeservice/1000 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  907): Recipient 3734
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ORMLib  ( 3672): put()
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/MediaStoreImporter( 3909): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  907): killProcessQuiet, pid=3777
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3777:com.htc.sense.news/u0a76 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3777
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4047 uid=10032 gids={50032, 3003, 5012}
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2184/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=6 [16][1][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3796
,I/ActivityManager(  907): Killing 3796:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Prism.PackageStateRece_( 1288): action: android.intent.action.PACKAGE_ADDED
I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
,I/CheckinRequestBuilder( 2184): Classify the device as Phone.
,I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Recipient 3796
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,I/CheckinTask( 2184): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2184): Checking schedule, now: 1452261048555 next: 1452783985542
,I/CheckinService( 2184): active receiver: disabled
D/PMS     (  907): acquireWL(426aba50): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,D/CheckinService( 2184): Recording last checkin time for package unspecified as 1452261048581
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(42746040): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426aba50): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423949d0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(423949d0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42165ed0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42165ed0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42528a48): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.CheckinService, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateActivity, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$SecretCodeReceiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService$Receiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/PMS     (  907): releaseWL(42528a48): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(423677a8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(423677a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(41e280e0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(41e280e0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(41e66698): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(41e66698): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(41f9d2d8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(41f9d2d8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(426a0a78): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426a0a78): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1366): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/SystemReader( 1268): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,W/AccTypeManager( 1366): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1366): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
,I/dalvikvm-heap( 1288): Grow heap (frag case) to 13.401MB for 53840-byte allocation
I/Prism.ItemManager( 1288): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1288): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1288): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,W/asset   ( 2856): Copying FileAsset 0x5c7ecc20 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,E/ExternalAccountType( 1366): Unsupported attribute readOnly
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
,D/PhoneApp( 1257): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
D/PMS     (  907): acquireWL(4271d548): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4271d548): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 520 ms] updated apps [took 520 ms] 
D/PMS     (  907): acquireWL(42488b98): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4069 uid=10098 gids={50098, 3003, 5012}
,I/DeviceManagement( 4069): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4069 dbg=false s=true
,I/DeviceManagement( 4069): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,D/Process (  907): killProcessQuiet, pid=3812
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4082 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 3812:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3812
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/PackageManager(  907): Unable to load service info ResolveInfo{42723e20 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/GCoreNlp( 1227): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/PMS     (  907): acquireWL(428ba820): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428ba820): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426cb950): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  907): applying state to connected service
,D/LocationProviderProxy(  907): applying state to connected service
D/PMS     (  907): releaseWL(426cb950): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(426c5050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(426c5050): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(42752238): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42752238): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1301): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1301): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1301): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  907): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4082/10100)
,W/GAV2    ( 4082): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.docs (4082/10100)
,I/ActivityManager(  907): Resuming delayed broadcast
,W/GAV2    ( 4082): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4106 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3622
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3622:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3622
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/Icing   ( 2184): Indexing 5DDFBB04CEF4FFE894538F4951832FAB899ACA77 from com.google.android.googlequicksearchbox
,D/Icing   ( 2184): Loaded CLD2 Version V2.0 - 20141016
,I/htcbackup-core( 4106): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 4106): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
W/ContextImpl( 4106): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,I/DeviceManagement( 4069): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 4069): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.location.fused, com.htc.checkinprovider, com.android.CSDFunctionG, com.htc.backupreset, com.htc.usage, com.htc.feedback, com.android.settings, com.android.keychain, com.qualcomm.privinit, com.htc.guide, com.htc.mirrorlinkserver, com.android.providers.settings, com.htc.lockscreen, com.android.inputdevices, android, com.htc.android.htcsetupwizard, com.htc.backup, com.htc.autobot.cargps.provider, com.htc.cirmodule, com.htc.htcpowermanager, com.htc.home.personalize, com.htc.drive.activator, com.htc.smartdim, com.htc.android.htcloglevel, com.qualcomm.timeservice]
,I/DeviceManagement( 4069): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4124 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  907): killProcessQuiet, pid=3830
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3830:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/DeviceManagement( 4069): WorkflowService: Starting workflow service
I/DeviceManagement( 4069): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b9e400] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 4069): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 4069): ModelRegistry: Loading model meta data from resources...
I/ActivityManager(  907): Recipient 3830
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,I/DeviceManagement( 4069): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4069): SessionStateController: Checking invariants...
,D/HtcCupdReceiver(Provider)( 4124):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  907): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
I/Icing   ( 2184): Indexing done 5DDFBB04CEF4FFE894538F4951832FAB899ACA77
,D/PMS     (  907): releaseWL(42488b98): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/DeviceManagement( 4069): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,I/DeviceManagement( 4069): SessionStateController: Checking invariants...
,I/DeviceManagement( 4069): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4069): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b9e400]
,I/DeviceManagement( 4069): WorkflowService: Stopping workflow service
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4139 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3857
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3857:com.android.settings/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3857
,I/Prism.ItemManager( 1288): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1288): loadItems() com.htc.launcher.pageview.WidgetManager@41bf5d48 +
,I/Prism.WidgetManager( 1288): onLoadItems() +
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(41b728a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4139 10160 null
,D/PMS     (  907): acquireWL(428536c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4139 10160 null
,D/PMS     (  907): releaseWL(41b728a0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackageAddedReceiver
,D/PMS     (  907): acquireWL(42769c58): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4139 10160 null
,D/PMS     (  907): releaseWL(428536c8): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4139/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (4139/10160)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
I/SocialFeedProvider( 1288): +disConnect socialManager
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
I/SocialFeedProvider( 1288): disconnect socialManager
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [1][0][0]
,I/SocialFeedProvider( 1288): -disConnect socialManager
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  907): releaseWL(42769c58): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver: pid=4162 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3764
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3764:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3764
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 4162): -onCreate()
,V/Settings:HtcSettingsApplication( 4162): [4162/4162] onCreate()
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4177 uid=10074 gids={50074, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3480
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3480:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3480
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/Prism.WidgetManager( 1288): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1288): onLoadItems() -
,I/Prism.ItemManager( 1288): loadItems() com.htc.launcher.pageview.WidgetManager@41bf5d48 -
,D/Settings:HtcWirelessFeatureFlags( 4162): id/is att sku: 99/false
,W/SystemReader( 4162): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 4162): Cannot find support_harman, use default value instead
,W/SystemReader( 4162): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 4162): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4162): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4162): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4162): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]support         :false
,W/FingerprintManager( 4162): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 4162): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4162): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 615: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4177, uid=10074, userID:0
,D/PhoneApp( 1257): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1257): -- N1 =0
,D/PhoneApp( 1257): -- N2 =0
,D/PhoneApp( 1257): -- N3 =0
,D/Finsky  ( 4177): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4177/10074)
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 4162): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 4162): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 4162): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 4162): [supportHomeButton]support         :false
,W/FingerprintManager( 4162): hasFingerprint() - sSensorCode = 0
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 548: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,E/Settings:HtcVoWifiWidgetEnabler( 4162): isSupportVoWifi: null
I/ActivityManager(  907): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 4162): Failed to find provider info for com.htc.vowifi
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4177/10074)
,D/Finsky  ( 4177): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 339: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,W/Settings( 4177): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4177): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 20813: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 9032: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4177, uid=10074, userID:0
,D/Ads     ( 4177): Skipping gmscore version check
,D/Finsky  ( 4177): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4177): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  907): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
D/Finsky  ( 4177): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4177): [1] ExternalReferrer.access$200: Package state data is missing for com.example.hello
,D/Finsky  ( 4177): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,I/ActivityManager(  907): Killing 3872:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=3872
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,W/dalvikvm( 2184): VFY: unable to resolve virtual method 174: Landroid/app/admin/DevicePolicyManager;.getProfileOwner ()Landroid/content/ComponentName;
I/ActivityManager(  907): Recipient 3872
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  907): acquireWL(428a27a8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428a27a8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4288e060): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4288e060): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=4221 uid=10076 gids={50076, 3003, 5012, 1028, 1015, 5001, 1023}
,V/AlarmManager(  907): sending alarm PendingIntent{425b1b48: PendingIntentRecord{425ba060 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452261051384, Int=0
,D/PMS     (  907): acquireWL(4288c960): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
,W/dalvikvm( 2184): VFY: unable to resolve virtual method 53: Landroid/app/Activity;.setEnterSharedElementCallback (Landroid/app/SharedElementCallback;)V
W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/app/SharedElementCallback;)
W/dalvikvm( 2184): VFY: unable to resolve virtual method 54: Landroid/app/Activity;.setExitSharedElementCallback (Landroid/app/SharedElementCallback;)V
,W/dalvikvm( 2184): VFY: unable to resolve virtual method 31: Landroid/app/Activity;.finishAfterTransition ()V
W/dalvikvm( 2184): VFY: unable to resolve virtual method 49: Landroid/app/Activity;.postponeEnterTransition ()V
,W/dalvikvm( 2184): VFY: unable to resolve virtual method 61: Landroid/app/Activity;.startPostponedEnterTransition ()V
,I/ImageRamCache( 4221): create image Cache, size: 31457280.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2184, uid=10029, userID:0
I/ImageRamCache( 4221): [resize] ImageRamCache resized to: 12Mb.
I/ImageRamCache( 4221): create image Cache, size: 12582912.
I/FeedSettings( 4221): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: false
I/FeedSettings( 4221): GroupBudget 0.500000 0.380000
I/FeedSettings( 4221): GroupBudget 60 45 15
I/Prism.ExternalStringMa_( 4221): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 4221): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 4221): loadGridSize() with Alternative
,I/PeopleDatabaseHelper( 2184): cleanUpNonGplusAccounts done.
,I/SocialManager[SocialBiLogHelper]( 4221): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 4221): last commit ulog time 1452231696147
,I/SocialManager[SocialBiLogHelper]( 4221): skip commit this time
,D/Process (  907): killProcessQuiet, pid=3497
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3497:com.htc.widget.hmsproc2/u0a45 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3497
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,W/asset   ( 2184): Copying FileAsset 0x5cb269d8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
V/AlarmManager(  907): sending alarm PendingIntent{41b701f8: PendingIntentRecord{42553aa8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=61327, Int=0
,D/PMS     (  907): releaseWL(4288c960): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Loading module APK com.google.android.play.games
,W/dalvikvm( 2184): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,E/dalvikvm( 2184): Could not find class 'com.google.android.gms.common.permission.PermissionUtils$1', referenced from method com.google.android.gms.chimera.GmsModuleInitializer.initializeModuleV0
,W/dalvikvm( 2184): VFY: unable to resolve new-instance 2374 (Lcom/google/android/gms/common/permission/PermissionUtils$1;) in Lcom/google/android/gms/chimera/GmsModuleInitializer;
,W/dalvikvm( 2184): Link of class 'Lcom/google/android/gms/common/permission/PermissionUtils$1;' failed
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
,D/Process (  907): killProcessQuiet, pid=2739
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Killing 2739:com.htc.sense.mms/u0a65 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 2739
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Resuming delayed broadcast
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/Process (  907): killProcessQuiet, pid=3672
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3672:com.htc.task/u0a71 (adj 15): empty #17
,W/BaseAppContext( 2184): Using Auth Proxy for data requests.
,W/BaseAppContext( 2184): Using Auth Proxy for data requests.
,D/AsyncTaskServiceImpl( 2184): Submit a task: k
,D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ActivityManager(  907): Recipient 3672
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.gass.chimera.PackageChangeBroadcastReceiver
D/k       ( 2184): Processing package: com.example.hello
,D/GassUtils( 2184): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/k       ( 2184): Found info for package com.example.hello in db.
,W/BaseAppContext( 2184): Using Auth Proxy for data requests.
,W/BaseAppContext( 2184): Using Auth Proxy for data requests.
W/BaseAppContext( 2184): Using Auth Proxy for data requests.
,W/BaseAppContext( 2184): Using Auth Proxy for data requests.
,W/BaseAppContext( 2184): Using Auth Proxy for data requests.
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 6 times.
,W/dalvikvm( 2184): VFY: unable to find class referenced in signature (Landroid/util/Size;)
,D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  907): Resuming delayed broadcast
,D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/PMS     (  907): acquireWL(4245dc80): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1500 10014 null
,I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  907): releaseWL(4245dc80): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
D/TelephonyReceiver( 1257): bind: false
D/TelephonyReceiver( 1257): switchBindHtcMsgCursor: null
,I/ActivityManager(  907): Start proc com.htc.updater for broadcast com.htc.updater/.UpdaterReceiver: pid=4246 uid=10085 gids={50085, 3003, 5012, 1028, 1015, 1023, 2001, 5006, 5001}
,D/PMS     (  907): acquireWL(426c2520): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
,D/Process (  907): killProcessQuiet, pid=3988
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3988:com.htc.android.mail:sync/u0a64 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3988
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,D/PMS     (  907): releaseWL(426c2520): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=82 rxSum=88} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=21988 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21989 delay=15s
,I/ActivityManager(  907): Start proc com.google.android.gm for broadcast com.google.android.gm/.MailIntentReceiver: pid=4262 uid=10107 gids={50107, 3003, 5012, 1028, 1015}
,W/GAV2    ( 4262): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
,D/PMS     (  907): acquireWL(4260ccd0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4260ccd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427352e8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.updater, id: 2130837512, tag: null, isClearable: false
D/NotificationService(  907): notification sound not played, stream=5 volume=0 always=false
,I/RemoteViews( 1115): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41efd258 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.updater 2 12 0 10
,I/RemoteViews( 1115): com.htc.updater (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41e75908 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
D/PMS     (  907): releaseWL(427352e8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
I/RemoteViews.Performance( 1115): com.htc.updater 1 7 0 10
,D/Process (  907): killProcessQuiet, pid=3931
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3931:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.htc.aurora
,I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Recipient 3931
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.htc.aurora, CONTACTS=MAYBE
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,I/Gmail   ( 4262): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/PMS     (  907): acquireWL(426c22f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 4139 10160 null
D/PMS     (  907): releaseWL(426c22f8): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
I/Gmail   ( 4262): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4262): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4262): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  907): acquireWL(42579ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): releaseWL(42579ec0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,W/dalvikvm( 4177): VFY: unable to resolve virtual method 611: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  907): << updateStatus
,I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 72 ms] updated apps [took 72 ms] 
,D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.htc.aurora
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver: pid=4300 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  907): acquireWL(42743750): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2184, uid=10029, userID:0
,D/PMS     (  907): releaseWL(42743750): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42627958): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/Babel   ( 4300): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4300): MmsConfig.loadMmsSettings
,W/dalvikvm( 4300): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4300): VFY: unable to resolve instance field 36
,W/dalvikvm( 4300): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4300): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  907): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4328 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4300, uid=10111, userID:0
,W/Settings( 4300): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4300, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4300, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4300, uid=10111, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4300, uid=10111, userID:0
,D/MessageFrequencyProvider( 4328): onCreate
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4300, uid=10111, userID:0
D/PMS     (  907): acquireWL(4264b0f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4300 10111 null
,V/GetPrviateResource( 4328): GetPrviateResource
,V/GetPrviateResource( 4328): GetPrviateResource
,D/MmsCustomizationProvider( 4328): query uri: content://htc-mms-customization/mms-ua/ua_string
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
V/AlarmManager(  907): sending alarm PendingIntent{41d0fe40: PendingIntentRecord{425f4a38 com.nero.android.htc.sync broadcastIntent}}, i=com.nero.htc.cd_mount.time_expired, t=0, cnt=1, w=1452261053963, Int=0
,D/MmsCustomizationProvider( 4328): query uri: content://htc-mms-customization/mms-ua/ua_profile
,I/Babel   ( 4300): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,D/Process (  907): killProcessQuiet, pid=3889
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,I/Babel   ( 4300): MmsConfig.loadFromDatabase
I/ActivityManager(  907): Killing 3889:com.htc.mediamanager/u0a34 (adj 15): empty #17
,E/Babel   ( 4300): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4300): MmsConfig.loadFromResources
,E/Babel   ( 4300): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4300): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
D/PMS     (  907): releaseWL(4264b0f0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(426b0de0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4300 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/ProviderInstaller( 4300): Installed default security provider GmsCore_OpenSSL
,D/MessageCustFlag( 4328): sense_version=6.0
,D/BTAccessoryUtil( 4328): createReceiver
,D/BTAccessoryUtil( 4328): registerReceiver return intent = null
D/MessageCustFlag( 4328): sku_id=99
,W/SystemReader( 4328): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 4328): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4328): networkCode: 
,D/MessageCustFlag( 4328): sku_id=99
D/MmsConfig( 4328): SIE smsPri: null
,D/MmsConfig( 4328): networkCode: 
,D/HtcTelephonyCapability( 4328): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4328): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 4328): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4328): Cannot find qct_8960_interface, use default value instead
D/PMS     (  907): releaseWL(426b0de0): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(42851c90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4300 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.realtimechat.RealTimeChatService$AlarmReceiver
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3889
,D/PMS     (  907): releaseWL(42851c90): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3966
I/ActivityManager(  907): Killing 3966:com.htc.sdm/u0a81 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(4272ab38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,I/ActivityManager(  907): Recipient 3966
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(4272ab38): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(4273e0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(4273e0d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
D/PMS     (  907): acquireWL(429e5d80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(429e5d80): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/PMS     (  907): acquireWL(429e17d8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(429d8e00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(429d8e00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(429a8518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(429a8518): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): acquireWL(428cf400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
D/PMS     (  907): releaseWL(429e17d8): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(428cf400): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
D/PMS     (  907): acquireWL(424b4038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(424b4038): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(424f2918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForAndroidIntent: pid=4364 uid=10041 gids={50041}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
I/GAV2    ( 4082): Thread[GAThread,5,main]: No campaign data found.
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(424f2918): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): Sampling interval elapsed, updating statistics ..
,D/Process (  907): killProcessQuiet, pid=4026
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4026:com.htc.task.gtask/u0a68 (adj 15): empty #17
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
I/ActivityManager(  907): Recipient 4026
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  907): Done.
D/ConnectivityService(  907): Setting timer for 720seconds
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=4379 uid=10071 gids={50071, 1023, 3003, 5012, 1028, 1015}
,D/PMS     (  907): acquireWL(4286dc20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4379 10071 null
,D/Process (  907): killProcessQuiet, pid=3909
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  907): acquireWL(42677348): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4379 10071 null
I/ActivityManager(  907): Killing 3909:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Delay finish: com.htc.launcher/.receiver.NotificationReceiver
,D/PMS     (  907): releaseWL(4286dc20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
E/TodoTaskNotifyService( 4379): java.lang.NullPointerException
W/System.err( 4379): java.lang.NullPointerException
W/System.err( 4379): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4379): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4379): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4379): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4379): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PMS     (  907): releaseWL(42677348): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,W/NotifyReceiver( 4379): stopSelfResult true
I/ActivityManager(  907): Recipient 3909
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 3909): Died!
,D/PMS     (  907): acquireWL(423a6810): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4379 10071 null
,D/PMS     (  907): acquireWL(425f3228): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4379 10071 null
,D/PMS     (  907): acquireWL(426d5a48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 4379 10071 null
,E/TodoTaskNotifyService( 4379): java.lang.NullPointerException
W/System.err( 4379): java.lang.NullPointerException
W/System.err( 4379): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4379): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4379): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4379): 	at android.os.Looper.loop(Looper.java:157)
,W/System.err( 4379): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/NotifyReceiver( 4379): stopSelfResult false
E/TodoTaskNotifyService( 4379): java.lang.NullPointerException
,W/System.err( 4379): java.lang.NullPointerException
W/System.err( 4379): 	at com.htc.task.notification.NotifyService.processMessage(NotifyService.java:177)
W/System.err( 4379): 	at com.htc.task.notification.NotifyService$ServiceHandler.handleMessage(NotifyService.java:124)
W/System.err( 4379): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4379): 	at android.os.Looper.loop(Looper.java:157)
W/System.err( 4379): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/NotifyReceiver( 4379): mStartingService is null
,W/NotifyReceiver( 4379): stopSelfResult true
I/ActivityManager(  907): Delay finish: com.htc.task/.notification.NotifyReceiver
D/PMS     (  907): acquireWL(425f3228): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 4379 10071 null
D/PMS     (  907): releaseWL(423a6810): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(426d5a48): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/PMS     (  907): releaseWL(425f3228): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
,E/MDM     ( 1227): [110] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 2184): Restart initialization of location
D/AuthorizationBluetoothService( 1347): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1347): Proximity feature is not enabled.
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.be.account.AccountStatusChecker$InitializeReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.auth.crypto.ChannelBindingBroadcastReceiver
,W/GCoreFlp( 1227): No location to return for getLastLocation()
,W/FusedLocationProvider( 1227): location=null
D/PMS     (  907): acquireWL(4266a4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(4266a4b0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
I/ActivityManager(  907): Resuming delayed broadcast
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
I/WSP     ( 1301): [Receiver] EVENT - ALARM MANAGER (AUTO-SYNC)
D/WeatherUtility( 1301): Weather sync is On
,I/WSP     ( 1301): [Receiver] next auto-sync alarm event is 60 mins later, at time: Fri Jan 08 15:50:54 CET 2016
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1301/10055)
D/PMS     (  907): acquireWL(426f3ba0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 1301 10055 null
,D/TodoTaskshortcut( 4379): update TASK shortcut>
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
D/PMS     (  907): releaseWL(42627958): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:119, mTXpacketCount:58, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB,
,V/AlarmManager(  907): sending alarm PendingIntent{41b5bf40: PendingIntentRecord{424f88d0 com.google.android.gms startService}}, i=null, t=0, cnt=1, w=1452261055748, Int=0
,V/AlarmManager(  907): sending alarm PendingIntent{41bacdd8: PendingIntentRecord{41d4f588 com.google.android.apps.plus startService}}, i=null, t=0, cnt=1, w=1452261055780, Int=0
,I/iu.UploadsManager( 2184): End new media; added: 0, uploading: 0, time: 64 ms
,D/Messaging( 4328): mNeedToUpdateDate2 start
,D/MmsConfig( 4328): packageName: com.htc.vvm.att does not exist
,D/ReportIndicatorCache( 4328): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 4328): 
D/MmsAsyncWorkHandler( 4328): HM tk = 20001
,D/ReportIndicatorCache( 4328): MSG_QUERY_REPORTS >>
D/SettingsManager( 4328): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b70448
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
,D/MmsSmsV2Provider( 1257):  phoneType = -1
I/Messaging( 4328): mccmnc> 
,D/MmsSmsV2Provider( 1257): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4328): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4328): [DraftCache/1] refresh
,D/MmsConfig( 4328): networkCode: 
,D/Messaging( 4328): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 34
,D/MmsSmsV2Provider( 1257):  phoneType = -1
,D/MmsSmsV2Provider( 1257): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/PhoneStorageUtil( 4328): HtcWrapEnvironment.getSupportedStorages() >1
D/PhoneStorageUtil( 4328): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4328): createReceiver
,D/Messaging( 4328): mNeedToUpdateDate2: false
,D/MessageCustFlag( 4328): sense_version=6.0
,D/Jerry   ( 4328): start to preload cursor >>>>>>>
D/TelephUtils( 1257): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 74
V/MmsProvider( 1257): Update uri=content://mms, match=0
,V/MmsProvider( 1257): selection=st=129 AND m_type!=134
,D/Messaging( 4328): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4328): TransactionService is going to be woken up.
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
,D/MmsSmsV2Provider( 1257):  phoneType = -1
I/ActivityManager(  907): Delaying start of: ServiceRecord{42734ad8 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/Messaging( 4328): ViewCache CreatePreload
,D/Messaging( 4328): ViewCache CreatePreloadOnlyMultipleOpsList
,D/Cust_MMSMS( 4328): _has_set_default_values_2=true
,D/MsgPreferenceUtils( 4328): def_index: 0
,D/MsgPreferenceUtils( 4328): globalIndex = 1
D/MsgPreferenceUtils( 4328): phone state: true
D/MsgPreferenceUtils( 4328): sd state: false
,D/MsgPreferenceUtils( 4328): vIndex = 0
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 35
,D/MmsSmsV2Provider( 1257):  phoneType = -1
,D/MmsSmsV2Provider( 1257): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
,D/AccFlag ( 1257): sku_id=99
D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 34
D/MmsSmsV2Provider( 1257):  phoneType = -1
,D/MmsSmsV2Provider( 1257): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/DraftCache( 4328): [DraftCache/436] rebuildCache
,D/Messaging( 4328): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
,D/Jerry   ( 1257): URI_DRAFT
,D/DraftCache( 4328): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4328): [DraftCache/436] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4328): 
D/MmsAsyncWorkHandler( 4328): HM tk = 20002
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 34
,D/AccFlag ( 1257): sku_id=99
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 66
,D/AccFlag ( 1257): sku_id=99
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 7 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/SensorManager(  907): mEventCount = 450
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/GAV2    ( 4262): Thread[GAThread,5,main]: No campaign data found.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.update.SystemUpdateService, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/CheckinService( 2184): Done disabling old GoogleServicesFramework version
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gsf, clsName=com.google.android.gsf.checkin.EventLogService$Receiver, state=2, flag=1, pid=2184, uid=10029, userID:0
,I/GAV4    ( 4300): Thread[GAThread,5,main]: No campaign data found.
,I/CalendarProvider2( 1500): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content: }
,W/ContentResolver( 1500): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,V/TransactionService( 4328): 1-Creating TransactionService
,V/TransactionService( 4328): onStartCommand: 1
,D/MmsSystemEventReceiver( 4328): unRegisterForConnectionStateChanges
V/TransactionService( 4328): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4328): Loading previous transactions.
,D/TelephUtils( 1257): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 35
,D/AccFlag ( 1257): device_type: 1
,D/TransactionService( 4328): Force set service start id to 1
,V/TransactionService( 4328): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4328): unRegisterForConnectionStateChanges
,V/TransactionService( 4328): Destroying TransactionService
,D/TransactionService( 4328): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4328): 4-Handling incoming message: { when=-5ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  907): Resuming delayed broadcast
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2184/10029)
,D/GCM     ( 1347): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PMS     (  907): acquireWL(42718bc8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4300 10111 null
I/ActivityManager(  907): Delay finish: com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver
,D/PMS     (  907): releaseWL(42718bc8): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/PMS     (  907): acquireWL(4288d328): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4288d328): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426b1a90): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/ClockThread( 1115): now=1452261059967 next=33
,D/PMS     (  907): releaseWL(426b1a90): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ClockThread( 1115): now=1452261060000 next=60000
V/AlarmManager(  907): sending alarm PendingIntent{423ac0f8: PendingIntentRecord{4238f138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=68843, Int=0
D/PMS     (  907): acquireWL(429be388): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(429be388): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(429b4110): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429b4110): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(429b8aa0): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429b8aa0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(426c44b8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(426c44b8): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4236d948): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(4236d948): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 320 ms] updated apps [took 320 ms] 
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  907): acquireWL(429d8468): PARTIAL_WAKE_LOCK  AsyncService 0x1 4139 10160 null
,D/PMS     (  907): releaseWL(429d8468): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2184): Null package name or gms related package.  Ignoreing.
,D/PMS     (  907): acquireWL(42772c18): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
,I/Icing   ( 2184): updateResources: need to parse f{com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,I/Icing   ( 2184): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2184): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  907): releaseWL(42772c18): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=4448 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/MusicStore( 4448): Database version: 95
,W/ContextImpl( 4448): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4448): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4448): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4448): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  355): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4448): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
W/Vold    (  355): Returning OperationFailed - no handler for errno 30
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4448, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 4448): Registered
,I/MediaRouter( 4448): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/PMS     (  907): acquireWL(428cc8f0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4448 10154 null
,I/ActivityManager(  907): Delay finish: com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver
,I/NetworkMonitor( 4448): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (4448/10154)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 4448): getSelectedRoute
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,W/ContextImpl( 4448): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (4448/10154)
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
I/NetworkMonitor( 4448): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4448, uid=10154, userID:0
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=2, flag=1, pid=4448, uid=10154, userID:0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,I/MusicLeanback( 4448): Conditions not met for autocaching.
,I/MusicLeanback( 4448): Stop autocaching.
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(4288e060): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
D/PMS     (  907): releaseWL(428cc8f0): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/PMS     (  907): releaseWL(4288e060): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
I/ConfigStore( 4448): Config Database version: 1
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/MusicLeanback( 4448): Stop autocaching.
,I/MusicLeanback( 4448): Stop autocaching.
,I/MusicLeanback( 4448): Stop autocaching.
,I/MusicLeanback( 4448): Stop autocaching.
,I/MusicLeanback( 4448): Stop autocaching.
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(426bb4e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 907 1000 null
,I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMReceiver: pid=4471 uid=10034 gids={50034, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/ContextImpl( 4448): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(426bb440): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 907 1000 null
,D/PMS     (  907): releaseWL(426bb4e0): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(426bb440): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/Process (  907): killProcessQuiet, pid=4047
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4047:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4047
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMReceiver
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4271a978 u0 com.htc.musicenhancer/.EnhancerService}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gm/.MailIntentReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.extremepowersaver.ExtremePowerSaverReceiver: pid=4495 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 4495): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2687 
,D/TetherSettings( 4162): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4162): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4162): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4162): Cust_ConnectToPC   : spcsc>false
D/        ( 4162): Cust_ConnectToPC   : IPT>true
,D/        ( 4162): Cust_ConnectToPC   : Singel_USB>false
D/SmartNS_NSReceiver( 4162): project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
,D/SmartNS_NSReceiver( 4162): Index of the first 1 = -1
,W/Settings( 4162): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/ContextImpl( 4162): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.android.settings.NSReceiver.onReceive:193 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4162): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.content.ContextWrapper.sendBroadcast:372 android.content.ContextWrapper.sendBroadcast:372 com.android.settings.NSReceiver.onReceive:195 android.app.ActivityThread.handleReceiver:2687 
E/SmartNS_Utility( 4162): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4162): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 4162): onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
D/SmartNS_Utility( 4162): [ACC]android_networking:tethering_guard_support=false
W/MediaManager( 4471): [DualLensScanUtil]	mmpCursor count is 0
,I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=4510 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  907): Killing 4082:com.google.android.apps.docs/u0a100 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4082
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,D/Process (  907): killProcessQuiet, pid=4106
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4106:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4106
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4082
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/SyncApplication( 4510): Loading default preferences
,W/Resources( 4510): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/WifiService(  907): New client listening to asynchronous messages
,D/SyncApplication( 4510): Overriding preferences with custom values
,D/SyncApplication( 4510): Updating preferences succeeded
,E/SyncApplication( 4510): Application created.
D/VolumeInfo( 4510): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 4510): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 4510): Found 0 mount point(s)
,V/VolumeInfo( 4510): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 4510): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,I/CalendarDefines( 4510): getNewCalendarAuthority()...
,D/VolumeInfo( 4510): Read the volume-id from the sd card: {FEC0D051-B844-464F-A347-138145D4C31C}
D/SyncApplication( 4510): enableAppOperation()+
,W/VolumeInfo( 4510): Can not create volume ID for unmounted volume null
,D/SyncApplication( 4510): enableAppOperation()-
,D/HTCUtilities( 4510): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=4510, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=4510, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 4510): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 4510): isNeorSinged() return false
,D/CDMountReceiver( 4510): whether to enable CD Auto-mount: true
,D/CDMountReceiver( 4510): showNotification() contentText=If HTC Sync Manager setup doesnt start automatically on your computer, download from www.htc.com/hsm
,D/CDMountReceiver( 4510): enable CD Auto-mount: true
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.nero.android.htc.sync, id: 9999, tag: null, isClearable: true
,D/HTCUtilities( 4510): enable auto-mount
,D/PMS     (  907): releaseWL(4246d9b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10008}
D/HTCUtilities( 4510): enable auto-mount
,I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/Process (  907): killProcessQuiet, pid=4069
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
D/MountService(  907): mountISO: /system/etc/PCTOOL.ISO
,I/ActivityManager(  907): Killing 4069:com.htc.cs.dm/u0a98 (adj 15): empty #17
D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41d04998 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 4 12 3 11
I/RemoteViews( 1115): com.nero.android.htc.sync (false,0)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f22340 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/ActivityManager(  907): Recipient 4069
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/RemoteViews.Performance( 1115): com.nero.android.htc.sync 0 9 3 16
,D/PMS     (  907): acquireWL(42571148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(42571148): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(428ce8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  907): Start proc com.htc.calendar for broadcast com.htc.calendar/.ProviderChangeReceiver: pid=4531 uid=10013 gids={50013, 3003, 5012, 1028, 1015, 1023}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  907): releaseWL(428ce8a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/CalendarApplication( 4531): onCreate
D/ProviderChangeReceiver( 4531): ---------------------------------------------------
,D/ProviderChangeReceiver( 4531): ProviderChangeReceiver onReceive, start to update notification!
,D/AlertService( 4531): start to updateAlertNotification!
,D/Process (  907): killProcessQuiet, pid=4124
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.framework.app.HtcDndCommandReceiver: pid=4545 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Killing 4124:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/AlertService( 4531): No fired or scheduled alerts
,D/HtcAlertUtils( 4531): -- cancelReminderNotification --
,D/HtcAlertUtils( 4531): broadcastExistReminder!
I/ActivityManager(  907): Recipient 4124
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 8 times.
,V/Settings:HtcSettingsApplication( 4545): [4545/4545] onCreate()
W/ContextImpl( 4545): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,D/Process (  907): killProcessQuiet, pid=4221
,I/ActivityManager(  907): Killing 4221:com.htc.sense.news/u0a76 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 4221
,D/PMS     (  907): acquireWL(42561530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42561530): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): releaseWL(426f3ba0): PARTIAL_WAKE_LOCK  HSP_Weather_60 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  907): mEventCount = 600
,D/PMS     (  907): acquireWL(42726fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{42729370: PendingIntentRecord{42724770 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452261066214, Int=0
,D/PMS     (  907): releaseWL(42726fd0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4177): [440] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4177): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/PMS     (  907): acquireWL(42675e30): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 4448 10154 null
,W/ContextImpl( 4448): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 4448): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
I/MusicLeanback( 4448): Conditions not met for autocaching.
,I/MusicLeanback( 4448): Stop autocaching.
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.leanback.AutoCacheSchedulingService$ActionReceiver, state=2, flag=1, pid=4448, uid=10154, userID:0
D/PMS     (  907): releaseWL(42675e30): PARTIAL_WAKE_LOCK  wake:com.google.android.music/.leanback.AutoCacheSchedulingService 0x1 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 9 times.
,D/Finsky  ( 4177): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,W/dalvikvm( 4177): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/PMS     (  907): acquireWL(42775428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
V/AlarmManager(  907): sending alarm PendingIntent{42488d78: PendingIntentRecord{424b3f08 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452261068229, Int=0
D/PMS     (  907): releaseWL(42775428): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.vending (4177/10074)
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4177): [NET] getaddrinfo-,err=8
D/libc    ( 4177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4177): [NET] getaddrinfo-, 1
D/libc    ( 4177): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =b621 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4177): [NET] getaddrinfo_proxy-, success
I/global  ( 4177): call createSocket() return a new socket.
D/libc    ( 4177): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
,D/libc    ( 4177): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall,
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=84 rxSum=89} preTxRxSum={txSum=82 rxSum=88}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  907): onDataStallAlarm: tag=21989 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21990 delay=15s
D/PMS     (  907): acquireWL(4276b898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
V/AlarmManager(  907): sending alarm PendingIntent{41c6dbd8: PendingIntentRecord{4230a778 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=77246, Int=0
D/PMS     (  907): releaseWL(4276b898): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/libc    ( 4177): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 4177): [NET] getaddrinfo-,err=8
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4177): untagSocket(69) failed with errno -22
,D/Finsky  ( 4177): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/NetworkManagementSocketTagger( 4177): untagSocket(69) failed with errno -22
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=10 [28][3][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 120
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:150, mTXpacketCount:119, avgLinkspeed:24,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,W/NetworkManagementSocketTagger( 4177): untagSocket(69) failed with errno -22
,D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.android.vending (4177/10074)
,D/Finsky  ( 4177): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  907): acquireWL(424dc2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{424015e0: PendingIntentRecord{4253af88 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1452261070470, Int=0
,D/PMS     (  907): acquireWL(426a47d0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4177 10074 null
,D/WearableService( 1227): callingUid 10029, callindPid: 1227
,D/PMS     (  907): releaseWL(424dc2b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
D/Finsky  ( 4177): [449] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/DeviceConnectionService( 1227): client connected with version: 8296000
,D/Finsky  ( 4177): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4177): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1347): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4177): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4177): [NET] getaddrinfo-,err=8
D/libc    ( 4177): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4177): [NET] getaddrinfo-, 1
,D/libc    ( 4177): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =e963 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 67
D/libc    (  365): [NET]res_nsend:resplen=87
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4177): [NET] getaddrinfo_proxy-, success
,D/PMS     (  907): releaseWL(426a47d0): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 10 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=10 [49][5][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true,
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1301): service - mHandler: update timezone
,D/AutoSetting( 1301): service - handleMessage() stop self
,D/AutoSetting( 1301): service - handleMessage() quit looper
,D/AutoSetting( 1301): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=3750
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3750:com.google.android.gms.unstable/u0a29 (adj 15): empty #17
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1500): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1500): service - onCreate()
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
W/ActivityManager(  907): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/AutoSetting( 1500): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1500): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1500): service - mHandler: update timezone
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1500): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1500): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1500): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1568): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1115): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1115): release indeterminate drawable android.widget.OnDemandProgressBar{41f8abc0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1115): com.htc.htclocationservice 1 7 3 11
,I/ActivityManager(  907): Recipient 3750
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1115): WifiActivity: 3
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=33 [3][1][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ContactMessageStore( 1257): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1257): MSG_NOTIFY_CS_TO_SYNC <<
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 11 times.
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 67
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  907): mEventCount = 750
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 86
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 12 times.
,D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/PMS     (  907): acquireWL(41c7e688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{424f8bb8: PendingIntentRecord{4230a778 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=92251, Int=0
,D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=160 rxSum=160} preTxRxSum={txSum=84 rxSum=89}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=21990 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21991 delay=15s
D/PMS     (  907): releaseWL(41c7e688): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 105
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:208, mTXpacketCount:150, avgLinkspeed:21,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,I/HtcModeClient( 1500): handler message = 4011
,E/HtcModeClient( 1500): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1500): Don't start project servcice
,D/HtcModeClient( 1500): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1500): connectState: CONNECTION_READY = false
,D/SilentMusic( 1500): call stop
,D/HtcModeClient( 1500): close connection
,W/HtcModeClient( 1500): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1500): read the terminate packet, so break
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 19
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/PMS     (  907): acquireWL(426c5b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10074}
,V/AlarmManager(  907): sending alarm PendingIntent{4271b810: PendingIntentRecord{42724770 com.android.vending startService}}, i=null, t=0, cnt=1, w=1452261084729, Int=0
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4579 uid=10078 gids={50078}
,V/AlarmManager(  907): sending alarm PendingIntent{4236efe0: PendingIntentRecord{426879a8 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1452261088870, Int=60000
,D/PMS     (  907): releaseWL(426c5b18): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4579): SMSBackupAgentService started
,D/SMSBackup( 4579): Checking restore status
,D/SMSBackup( 4579): Restore complete
,D/SMSBackup( 4579): cancelCheckAlarm
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,D/SMSBackup( 4579): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{426e82b0 u0 com.htc.htclocationservice/.AutoSettingService},
,D/Finsky  ( 4177): [440] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4177): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/Process (  907): killProcessQuiet, pid=4246
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4246:com.htc.updater/u0a85 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4246
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/SensorManager(  907): mEventCount = 900
,D/WIFI_ICON( 1115): WifiActivity: 1
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,V/LightsService(  907): setLight #0: color=#3d
,V/LightsService(  907): setLight #0: color=#3a
,V/LightsService(  907): setLight #0: color=#33
,V/LightsService(  907): setLight #0: color=#2d
,V/LightsService(  907): setLight #0: color=#26
,V/LightsService(  907): setLight #0: color=#1f
,V/LightsService(  907): setLight #0: color=#19
,V/LightsService(  907): setLight #0: color=#14
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 38
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 57
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 76
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WIFI_ICON( 1115): WifiActivity: 0
,D/StatusBar.NetworkController( 1115): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/PMS     (  907): Going to sleep due to screen timeout...
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@421081e0
,W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
D/WirelessDisplayService(  907): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/PMS     (  907): mWirelessDisplayManager is null
,W/BatSI   (  907): Couldn't get kernel wake lock stats
W/SensorService(  907): disable: get sensor name = CM36282 Light sensor
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@421081e0, eanble = 0, strlen(mName) = 59
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  907): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fcf2b8
W/SensorService(  907): Listener[1] = com.htc.smartdim.sensor_eye@425f6b90
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  907): setLight #2: color=#0
D/qdlights(  907): set_light_buttons_func: on=0 brightness=0
V/LightsService(  907): setLight #0: color=#0
,D/SurfaceControl(  907): Excessive delay in blankDisplay() while turning screen off: 339ms
D/PMS     (  907): nativeSetInteractive:false
D/PMS     (  907): nativeSetInteractive:false done
D/PMS     (  907): nativeSetAutoSuspend:true
D/PMS     (  907): nativeSetAutoSuspend:true done
D/HABCtrl (  907): TPE algorithm. remove timeout.
I/InputManager(  907): Cancel all due to getting PMS screen off broadcast
,D/NfcService( 1268): ScreenObserver: OFF
,I/IntentController( 1115): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
I/InputMethodManagerService(  907): screenObserver, isScreenOn=false
D/PMS     (  907): OOBE c monitor 11
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3285 uid 10397
D/NfcService( 1268): applyRouting - 0
,V/KeyguardServiceDelegate(  907): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@429e0af0)
,D/NfcService( 1268): applyRouting -2
D/PMN     (  907): wakingUp
D/PMS     (  907): acquireWL(42716580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
I/BatteryService(  907): n_update end
D/PMS     (  907): acquireWL(42717558): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1268 1027 null
D/PMS     (  907): releaseWL(42716580): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,V/KeyguardServiceDelegate(  907): **** SHOWN CALLED ****
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): releaseWL(42717558): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
I/WindowManager(  907): No lock screen! windowToken=null
D/PMN     (  907): onScreenOn
D/HtcPowerSaver(  907): updateBatteryInfo
D/AlarmManager(  907): ACTION_SCREEN_ON
I/AlarmManager(  907): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done recovering
I/AlarmManager(  907): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  907): [AlarmQueuing] done EPS screen off alarm recovering
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,D/WirelessDisplayService(  907): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_ON
,I/HtcPowerSaver(  907): << updateStatus
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=21992 delay=15s
D/MtpService( 1973): [MTP][onReceive]+android.intent.action.USER_PRESENT
D/NfcService( 1268): applyRouting - 0
D/MtpService( 1973): [MTP][onReceive]-
,D/NfcService( 1268): applyRouting -2
D/PMS     (  907): acquireWL(4253da90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1268 1027 null
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
D/PMS     (  907): releaseWL(4253da90): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
,V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  907): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  907): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
,I/ClockThread( 1115): stop update clock
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:On
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1156): BG scan when screen On
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1156): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): Match BG scan, scan!
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  907):    returned true
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
V/NotificationService(  907): batLight: Full, plugged
V/LightsService(  907): setLight #8: color=#c8c800
D/qdlights(  907): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  907): setLight #8: color=#c800
D/qdlights(  907): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  907): [LedInfo] has indicator attribute
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  907): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  907): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
W/ContextImpl( 4495): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
D/NetworkPolicy(  907): updateScreenOn: false
,D/SmartSyncUtils( 4495): isEpsOn(), nState = 0
D/PMS     (  907): acquireWL(4287f4d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4495 1000 null
,D/SmartSyncUtils( 4495): getMobilePolicyEnabled, result = true
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
,D/PMS     (  907): releaseWL(4287f4d8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/AutoSetting( 1301): receiver - intent: android.intent.action.USER_PRESENT
,D/TetherSettings( 4162): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 4162): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 4162): Cust_ConnectToPC   : Modem_Link>false
D/        ( 4162): Cust_ConnectToPC   : spcsc>false
D/        ( 4162): Cust_ConnectToPC   : IPT>true
D/        ( 4162): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 4162): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 4162): hasRemovableStorageSlot: true
D/SmartNS_Utility( 4162): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 4162): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
,D/AutoSetting( 1301): service - onCreate()
,I/PSReceiver( 4162): onReceive:android.intent.action.USER_PRESENT
,I/SmartNS_PSService( 4162): onReceive:android.intent.action.USER_PRESENT
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/Settings( 4162): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 4162):  defaultType:0
W/ContextImpl( 4162): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  907): acquireWL(428b9058): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(428b9058): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/AutoSetting( 1301): service - AddressCache: using context: com.htc.Weather
,D/AutoSetting( 1301): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
,D/LocationManagerService(  907): request 423b4a20 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/PMS     (  907): acquireWL(42897350): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/LocationManagerService(  907): provider request: passive ProviderRequest[ON interval=0]
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOn: false
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOn: 1452261098365
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOn: 1452261098365
D/PMS     (  907): releaseWL(42897350): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fcf2b8
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 2
W/SensorService(  907): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  907): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@41fcf2b8, eanble = 0, strlen(mName) = 91
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  907): Listener[0] = com.htc.smartdim.sensor_eye@425f6b90
,W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
D/PMN     (  907): goingToSleep
I/FeedHostManager( 1288): [onPause]
,I/FeedProviderManager( 1288): onPause
,I/FeedHostManager( 1288): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41d70970
I/SocialFeedProvider( 1288): +onPause
,I/SocialFeedProvider( 1288): -onPause
D/PMS     (  907): acquireWL(4289a9d0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 907 1000 null
D/AlarmManager(  907): ACTION_SCREEN_OFF
I/AlarmManager(  907): [AlarmQueuing] screen off now: 
I/AlarmManager(  907): [AlarmQueuing] data connection: true
,I/AlarmManager(  907): [AlarmQueuing] wifi connection: true
D/WifiDataStallTracker(  907): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=21992 mDataStallAlarmIntent=PendingIntent{426bda10: PendingIntentRecord{4230a778 android broadcastIntent}}
,D/WifiNative-wlan0(  907): doBoolean: SET_SCREEN_ON 0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
D/PMS     (  907): acquireWL(428ab3c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 907 1000 null
,D/PMS     (  907): releaseWL(4289a9d0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,W/ContextImpl( 4495): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4495): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4495): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4495): isEpsOn(), nState = 0
D/WifiService(  907): New client listening to asynchronous messages
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1156): SET_SCREEN_ON:Off
I/wpa_supplicant( 1156): htc_wext_set_keepalive +
I/wpa_supplicant( 1156): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1156): getPrivFuncNum +	
I/wpa_supplicant( 1156): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1156): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1156): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1156): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1156): htc_wext_set_keepalive - ret = 0
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 19
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 95
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1156): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:208, mTXpacketCount:208, avgLinkspeed:19,mAvgTxRate54
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
,D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0,
I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425f6b90
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
,W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 1
W/SensorService(  907): CM36282 Proximity sensor (handle=0x00000001, connections=1),
W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425f6b90, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  907): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  907): disable: get sensor name = CM36282 Proximity sensor,
W/SensorService(  907): pid=907, uid=1000
W/SensorService(  907): Active sensors: size = 0
,W/SensorService(  907): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@425f6b90, eanble = 0, strlen(mName) = 36
W/SensorService(  907): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  907): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  907): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@425f6b90
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
,V/SRS_Proc(  372): ParamSet string: screen_state=off
E/ActivityThread(  907): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425f70d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  907): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@425f70d8 that was originally registered here. Are you missing a call to unregisterReceiver()?
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
D/NetworkPolicy(  907): updateScreenOn: false
,D/ContactMessageStore( 1257): start background delete task...
D/ContactMessageStore( 1257): size: 0 , 0
,D/ContactMessageStore( 1257): Background delete complete
,D/PMS     (  907): acquireWL(42894528): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/PMS     (  907): releaseWL(42894528): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
D/DotMatrix( 1568): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  907): acquireWL(42895a50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOff.
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOff
D/PMS     (  907): releaseWL(42895a50): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1301): service - mHandler: cancel location update
,D/AutoSetting( 1301): service -           changes count: 0
,D/wpa_supplicant( 1156): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  907):    returned true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/PMS     (  907): releaseWL(428ab3c8): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=7 entropy=0
D/wpa_supplicant( 1156): Add randomness: count=8 entropy=1
D/wpa_supplicant( 1156): Add randomness: count=9 entropy=2
D/wpa_supplicant( 1156): Add randomness: count=10 entropy=3
D/wpa_supplicant( 1156): Add randomness: count=11 entropy=4
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplica,nt( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-85
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=12 entropy=5
D/wpa_supplicant( 1156): Add randomness: count=13 entropy=6
D/wpa_supplicant( 1156): Add randomness: count=14 entropy=7
D/wpa_supplicant( 1156): Add randomness: count=15 entropy=8
D/wpa_supplicant( 1156): Add randomness: count=16 entropy=9
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: DISCONNECTED -> INACTIVE
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSID
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6,
I/wpa_supplicant( 1156): reply (631) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000109451599
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000109451638
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
,I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-85
I/wpa_supplicant( 1156): tsf=0000000109451648
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-87
I/wpa_supplicant( 1156): tsf=0000000109451657
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1156): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000109451626
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList,
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147462 obj=android.net.wifi.StateChangeResult@4287bd28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 109451599, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiP2pService(  907): P2pEnabledState{ when=-3ms what=147462 obj=android.net.wifi.StateChangeResult@4287bd28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 109451638, distance: ?(cm), distanceSd: ?(cm)
D/WifiP2pService(  907): DefaultState{ when=-6ms what=147462 obj=android.net.wifi.StateChangeResult@4287bd28 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -85, frequency: 2412, timestamp: 109451648, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -87, frequency: 2437, timestamp: 109451657, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 109451626, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0,
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  73, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-85], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS],
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiManager( 1227): getScanResults enter 
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/AutoSetting( 1500): service - handleMessage() stop self
,D/AutoSetting( 1500): service - onDestroy() END
,D/AutoSetting( 1500): service - handleMessage() quit looper
,D/ContactMessageStore( 1257): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1257): MSG_NOTIFY_CS_TO_SYNC <<
,D/Process (  907): killProcessQuiet, pid=3946
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3946:com.htc.musicenhancer/u0a53 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3946
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{428b8330 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PMS     (  907): acquireWL(42991540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{4264dd60: PendingIntentRecord{42413420 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=123248, Int=0
,D/PMS     (  907): releaseWL(42991540): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(429932d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42999618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42999618): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(429932d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4299f0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(4299f0f0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4277b728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): acquireWL(42784718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4278c8b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1227): Vacuum at: now=1452261114689 tag=VacuumService
,D/PMS     (  907): releaseWL(4277b728): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42784718): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(42797020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
D/PMS     (  907): releaseWL(4278c8b8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(42797020): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(4279b988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(4279b988): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427a2910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(427a2910): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427a6a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/PMS     (  907): releaseWL(427a6a40): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427ad9e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0],
,D/PMS     (  907): acquireWL(427b6998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427b6998): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427be330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): releaseWL(427ad9e8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427c3428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(427c3428): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1227): Scheduling Phenotype for one-off execution 66 seconds from now (1452261115412)
,D/GetConfigurationSnapshotOperation( 1227): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1227): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1227): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1227): Using platform SSLCertificateSocketFactory
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/LocationManagerService(  907): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (1227/10029)
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1227): [NET] getaddrinfo-, 1
,D/libc    ( 1227): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =aeb3 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
,D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1227): [NET] getaddrinfo_proxy-, success,
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL,
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0,
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5,
D/wpa_supplicant( 1156): nl80211: survey data missing!,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0],
,D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
,I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=17 entropy=10
D/wpa_supplicant( 1156): Add randomness: count=18 entropy=11
D/wpa_supplicant( 1156): Add randomness: count=19 entropy=12
,D/wpa_supplicant( 1156): Add randomness: count=20 entropy=13
D/wpa_supplicant( 1156): Add randomness: count=21 entropy=14
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
,D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -57
,D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1156): Start print parameters
,I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
,I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
,D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 4: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
,E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (5 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
,I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-80
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-87
,D/wpa_supplicant( 1156): BSS: last_scan_res_used=5/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=22 entropy=15
D/wpa_supplicant( 1156): Add randomness: count=23 entropy=16
D/wpa_supplicant( 1156): Add randomness: count=24 entropy=17
D/wpa_supplicant( 1156): Add randomness: count=25 entropy=18
D/wpa_supplicant( 1156): Add randomness: count=26 entropy=19
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6,
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
,I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
,I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
,I/wpa_supplicant( 1156): reply (631) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000126543000
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000126543036
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-80
I/wpa_supplicant( 1156): tsf=0000000126543048
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-87
I/wpa_supplicant( 1156): tsf=0000000126543057
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1156): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000126543025
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC,
I/wpa_supplicant( 1156): ####
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 126543000, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 126543036, distance: ?(cm), distanceSd: ?(cm)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -80, frequency: 2412, timestamp: 126543048, distance: ?(cm), distanceSd: ?(cm)
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -87, frequency: 2437, timestamp: 126543057, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 126543025, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  75, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  6 [-80], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
D/libc    ( 1227): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1227): [NET] getaddrinfo-,err=8
,D/PMS     (  907): releaseWL(427be330): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427f7738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
,W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(427f7738): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(427fdee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1347 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1156): environment dirty rate=11 [9][1][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1156): nl80211: survey data missing!
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1156): environment dirty rate=0 [0][0][0]
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360025668
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026107
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026201
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026205
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026208
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360026212
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027691
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360027704
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360030854
W/AlarmManager(  907): Converted elapesd time is over 1 year! when = 315360031792
,D/PMS     (  907): releaseWL(427fdee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  907): acquireWL(428059f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423ac0f8: PendingIntentRecord{4238f138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=128843, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(428059f0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(42807590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42807590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PowerUI ( 1115): closing low battery warning: level=100
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus,
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  907): acquireWL(4280d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  907): sending alarm PendingIntent{42254638: PendingIntentRecord{425bf740 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=138064, Int=0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (1347/10029)
,D/PMS     (  907): releaseWL(4280d0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1301): service - handleMessage() stop self
,D/AutoSetting( 1301): service - handleMessage() quit looper
,D/AutoSetting( 1301): service - onDestroy() END
,D/Process (  907): killProcessQuiet, pid=4364
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 4364:com.htc.widget.hmsproc1/u0a41 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 4364
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(42813880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{421608a8: PendingIntentRecord{423fc308 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=143651, Int=0
,D/GpsLocationProvider(  907): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  907): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  907): acquireWL(42814b68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
D/PMS     (  907): releaseWL(42813880): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-,err=8
D/libc    (  907): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  907): [NET] getaddrinfo-, 1
,D/libc    (  907): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =7987 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=27 entropy=20
D/wpa_supplicant( 1156): Add randomness: count=28 entropy=21
D/wpa_supplicant( 1156): Add randomness: count=29 entropy=22
D/wpa_supplicant( 1156): Add randomness: count=30 entropy=23
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1156): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant(, 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=31 entropy=24
D/wpa_supplicant( 1156): Add randomness: count=32 entropy=25
D/wpa_supplicant( 1156): Add randomness: count=33 entropy=26
D/wpa_supplicant( 1156): Add randomness: count=34 entropy=27
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0,
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6,
I/wpa_supplicant( 1156): reply (631) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000143925851
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000143925889
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-79
I/wpa_supplicant( 1156): tsf=0000000143925899
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
,I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-87
I/wpa_supplicant( 1156): tsf=0000000126543057
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1156): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000143925878
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 143925851, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 143925889, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 143925899, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -87, frequency: 2437, timestamp: 126543057, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 143925878, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 5 to mScanResults
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-87], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59,
D/libc    (  365): [NET]res_nsend:resplen=243
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=10
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
,D/libc    (  907): [NET] getaddrinfo_proxy-, success
I/global  (  907): call createSocket() return a new socket.
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  907): [NET] getaddrinfo-, SUCCESS,
,D/GpsLocationProvider(  907): [handleDownloadXtraData] calling native_inject_xtra_data
,D/GpsLocationProvider(  907): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  907): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  907):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  907): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,D/PMS     (  907): releaseWL(42814b68): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
,I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-88
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=35 entropy=28
D/wpa_supplicant( 1156): Add randomness: count=36 entropy=29
D/wpa_supplicant( 1156): Add randomness: count=37 entropy=30
D/wpa_supplicant( 1156): Add randomness: count=38 entropy=31
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [,NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-88
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=39 entropy=32
D/wpa_supplicant( 1156): Add randomness: count=40 entropy=33
D/wpa_supplicant( 1156): Add randomness: count=41 entropy=34
D/wpa_supplicant( 1156): Add randomness: count=42 entropy=35
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1156): reply (631) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000161325057
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000161325083
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-79
I/wpa_supplicant( 1156): tsf=0000000161325098
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1156): freq=2437
,I/wpa_supplicant( 1156): level=-88
I/wpa_supplicant( 1156): tsf=0000000161325107
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1156): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=4
I/wpa_supplicant( 1156): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000143925878
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1156): ssid=01ABC
I/wpa_supplicant( 1156): ####
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 161325057, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 161325083, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0,
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 161325098, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -88, frequency: 2437, timestamp: 161325107, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 4: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 143925878, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 5 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
,V/ScoreHelper(  907):  + ScoreResult:  94, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  84, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-88], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,V/ScoreHelper(  907):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  6 [2412], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (5) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42a28140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
,D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1115): closing low battery warning: level=100
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/HtcPowerSaver(  907): updateBatteryInfo
D/PMS     (  907): releaseWL(42a28140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  907): acquireWL(42a2e040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{10027}
,V/AlarmManager(  907): sending alarm PendingIntent{425dca10: PendingIntentRecord{42719758 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=173423, Int=0
,D/PMS     (  907): releaseWL(42a2e040): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,D/TelephonyReceiver( 1257): switchBindHtcMsgCursor: null
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
,D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
,D/PMS     (  907): acquireWL(42a2fa10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(42a2fa10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  907): updateBatteryInfo
,D/PowerUI ( 1115): closing low battery warning: level=100
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
,D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
,D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing,
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
,I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
,D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=43 entropy=36
D/wpa_supplicant( 1156): Add randomness: count=44 entropy=37
D/wpa_supplicant( 1156): Add randomness: count=45 entropy=38,
D/wpa_supplicant( 1156): Add randomness: count=46 entropy=39
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1,
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0,
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
,I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
,I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
,I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
,D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
,D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
,I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=47 entropy=40
D/wpa_supplicant( 1156): Add randomness: count=48 entropy=41
D/wpa_supplicant( 1156): Add randomness: count=49 entropy=42
D/wpa_supplicant( 1156): Add randomness: count=50 entropy=43
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
,I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  907): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1156): reply (518) for get BSS: id=0
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000178716338
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
,I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000178716379
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11,
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-79
I/wpa_supplicant( 1156): tsf=0000000178716400
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
I/wpa_supplicant( 1156): bssid=9e:93:4e:3e:ba:c5
,I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-86
I/wpa_supplicant( 1156): tsf=0000000178716418
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1156): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1156): ####
,W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/WifiP2pService(  907): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 178716338, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 178716379, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 178716400, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -86, frequency: 2437, timestamp: 178716418, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
D/WirelessDisplayService(  907): getDiscoveryDongleList
V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-86], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
,D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,V/ScoreHelper(  907):  + computeScore(NG700): 1
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiManager( 1227): getScanResults enter 
D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/PMS     (  907): acquireWL(42a3e7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 907 1000 WorkSource{1000}
,V/AlarmManager(  907): sending alarm PendingIntent{423ac0f8: PendingIntentRecord{4238f138 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=188843, Int=0
,I/IntentController( 1115): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  907): releaseWL(42a3e7d0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  907): acquireWL(429f4ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/PMS     (  907): releaseWL(429f4ed8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/IntentController( 1115): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1568): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1568): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  907): updateBatteryInfo
D/PowerUI ( 1115): closing low battery warning: level=100
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
D/PowerUI ( 1115): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): >> updateStatus
,I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
,I/BatteryController( 1115): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
,D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1156): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1156): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1156): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=51 entropy=44
D/wpa_supplicant( 1156): Add randomness: count=52 entropy=45
D/wpa_supplicant( 1156): Add randomness: count=53 entropy=46
D/wpa_supplicant( 1156): Add randomness: count=54 entropy=47
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): Selecting BSS from priority group 1
I/wpa_supplicant( 1156): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1156): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1156): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1156): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1156):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1156):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1156): Start print parameters
I/wpa_supplicant( 1156): wpa_s->wpa_state is 9
I/wpa_supplicant( 1156): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1156): isConcurrentMode() is 0
I/wpa_supplicant( 1156): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1156): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1156): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1156): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1156): wpa_s->reassociate is 0
I/wpa_supplicant( 1156): wpa_s->is_screen_on 0
I/wpa_supplicant( 1156): wpa_s->ifname wlan0
I/wpa_supplicant( 1156): End print parameters
I/wpa_supplicant( 1156): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1156): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
D/wpa_supplicant( 1156): 3: 9e:93:4e:3e:ba:c5 ssid='DIRECT-qjWorkCentre 3025' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1156): clear disabled list - type=1
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1156): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1156): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1156): nl80211: Survey data missing
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1156): Sorted scan results
I/wpa_supplicant( 1156): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1156): [,NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1156): [NULL] 38:f8:89:11:e9:11 freq=2412 level=-79
I/wpa_supplicant( 1156): [NULL] 9e:93:4e:3e:ba:c5 freq=2437 level=-86
D/wpa_supplicant( 1156): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1156): Add randomness: count=55 entropy=48
D/wpa_supplicant( 1156): Add randomness: count=56 entropy=49
D/wpa_supplicant( 1156): Add randomness: count=57 entropy=50
D/wpa_supplicant( 1156): Add randomness: count=58 entropy=51
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  907): doString: LIST_DONGLES
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
D/wpa_supplicant( 1156): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1156): WPS: AP[2] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1156): wpa_supplicant_pick_network+
I/wpa_supplicant( 1156): clear disabled list - type=1,
I/wpa_supplicant( 1156): No suitable network found
W/wpa_supplicant( 1156): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1156): State: INACTIVE -> INACTIVE
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  907): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1156): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
D/wpa_supplicant( 1156): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1156): WPS: WFA subelement id=1 len=6
I/wpa_supplicant( 1156): reply (518) for get BSS: id=0
,I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1156): freq=5220
I/wpa_supplicant( 1156): level=-47
I/wpa_supplicant( 1156): tsf=0000000196115935
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG7005g
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=1
I/wpa_supplicant( 1156): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-57
I/wpa_supplicant( 1156): tsf=0000000196115974
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1156): ssid=NG700
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=2
I/wpa_supplicant( 1156): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1156): freq=2412
I/wpa_supplicant( 1156): level=-79
I/wpa_supplicant( 1156): tsf=0000000196115994
I/wpa_supplicant( 1156): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1156): ssid=Gonzos
I/wpa_supplicant( 1156): ====
I/wpa_supplicant( 1156): id=3
,I/wpa_supplicant( 1156): bssid=9e:93:4e:3e:ba:c5
I/wpa_supplicant( 1156): freq=2437
I/wpa_supplicant( 1156): level=-86
I/wpa_supplicant( 1156): tsf=0000000196116012
I/wpa_supplicant( 1156): flags=[WPA2-PSK-CCMP][WPS-AUTH][ESS]
I/wpa_supplicant( 1156): ssid=DIRECT-qjWorkCentre 3025
I/wpa_supplicant( 1156): ####
D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiP2pService(  907): InactiveState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  907): DefaultState{ when=0 what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  907): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiStateMachine(  907): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 196115935, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,V/ScoreHelper(  907): Only print Top 10 in ApScanList
V/ScoreHelper(  907):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  907):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 196115974, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -79, frequency: 2412, timestamp: 196115994, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  907): 3: scan result = SSID: DIRECT-qjWorkCentre 3025, BSSID: 9e:93:4e:3e:ba:c5, capabilities: [WPA2-PSK-CCMP][WPS-AUTH][ESS], level: -86, frequency: 2437, timestamp: 196116012, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  907): add 4 to mScanResults
,V/ScoreHelper(  907):  + ScoreResult:  79, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  8 [-79], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  907):  + ScoreResult:  77, AP:         DIRECT-qjWorkCentre 3025 [9e:93:4e:3e:ba:c5], Rssi:  4 [-86], Tx: 13, Freq: 10 [2437], Disconn: 50, Last Used:  0
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  907): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  907):  + computeScore(NG700): 1
D/WifiStateMachine(  907): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  907): == begin of scan result ==
,D/WifiStateMachine(  907): == (4) end of scan result ==
,D/WifiNotificationController(  907): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/WifiManager( 1227): getScanResults enter 
,D/WirelessDisplayService(  907): getDiscoveryDongleList
D/WifiStateMachine(  907): == begin of scan result ==
D/WifiStateMachine(  907): == (4) end of scan result ==
,TIME-OUT KILL (timeout was 150000ms),E/cutils-trace( 4636): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4636): ====startRecUseTime====
D/htc.customization.log.level( 4636):  is 
W/CustomizationLogLevel( 4636): Level value is invalid, use default level 2
D/CustomizationManager( 4636):  Read ACC file spent 0.115 (s)
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4636): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4636): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4636): Parsing tag category name = system
I/CustomizationCIDLoader( 4636): Parsing tag category name = application
I/CustomizationCIDLoader( 4636): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4636): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4636): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4636): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4636): Parsing tag category name = Settings
D/CustomizationManager( 4636):  Read CID file spent 0.169 (s)
D/CustomizationManager( 4636):  All configurations done spent 0.169 (s)
W/HtcNativeFlag( 4636): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4636): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4636): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4636): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=4636, uid=2000 user=0
W/asset   (  907): Copying FileAsset 0x6296ec58 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  907): Force stopping com.example.hello appid=10397 user=-1: uninstall pkg
W/PackageSettings(  907): Skipping PackageSetting{41ddfc80 com.test.thalitest/10389} due to missing metadata
I/ActivityManager(  907): Force stopping com.example.hello appid=10397 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1115): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1568): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1568): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
W/GeofencerStateMachine( 1227): Ignoring removeGeofence because network location is disabled.
D/PMS     (  907): acquireWL(4273b258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1227 10029 WorkSource{10029 com.google.android.gms}
D/AccTypeManager( 1366): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  907): releaseWL(4273b258): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/Prism.ItemManager( 1288): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1288): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/VoicemailCleanupService( 1241): Cleaning up data for package: com.example.hello
W/SQLiteConnectionPool( 2184): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/AccTypeManager( 1366): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1366): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/SystemReader( 1268): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/Launcher( 1288): Deferring update until onResume
D/Launcher( 1288): waitUntilResume // bindAppsRemoved
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/[PluginManager]RegisterService( 1301): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.example.hello
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
I/[PluginManager]RegisterService( 1301): handle notify Blinkfeed plugin client changed
D/Prism.PackageStateRece_( 1288): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
E/ExternalAccountType( 1366): Unsupported attribute readOnly
I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "sms"
I/IcingCorporaProvider( 2856): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4650 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1257 :
D/PhoneApp( 1257): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  907): acquireWL(42441740): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): releaseWL(42441740): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  907): acquireWL(423a8ed8): PARTIAL_WAKE_LOCK  Icing 0x1 2184 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 2856): UpdateCorporaTask done [took 318 ms] updated apps [took 318 ms] 
W/PackageManager(  907): Unable to load service info ResolveInfo{42662278 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
E/SQLiteDatabase( 4650): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4650): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4650): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4650): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4650): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4650): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4650): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4650): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4650): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4650): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4650): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4650): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4650): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4650): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4650): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4650): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4650): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4650): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4650): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4650): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4650): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4650): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4650): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4650): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4650): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4650): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4650): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4650): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4650): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4650): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4650): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4650): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4650): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4650): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4650): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4650): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4650): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4650): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4650): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4650): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4650): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4650): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4650): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4650): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4650): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4650): threadid=11: thread exiting with uncaught exception (group=0x41731e30)
E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4650): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4650): Process: com.google.android.apps.docs, PID: 4650
E/AndroidRuntime( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4650): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4650): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4650): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4650): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4650): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop140.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteDatabase( 4650): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4650): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4650): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4650): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4650): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4650): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4650): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4650): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4650): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4650): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4650): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4650): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4650): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4650): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4650): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4650): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4650): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4650): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4650): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4650): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4650): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4650): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4650): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4650): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4650): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4650): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4650): Opened ClientFlag.db in read-only mode
D/Process ( 4650): killProcess, pid=4650
D/Process ( 4650): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  907): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4668 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  907): Recipient 4650
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  907): killProcessQuiet, pid=4379
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 4379:com.htc.task/u0a71 (adj 15): empty #17
I/ActivityManager(  907): Process com.google.android.apps.docs (pid 4650) has died.
W/ContextImpl( 4668): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
D/RemoteDisplayProvider(  907): start
E/SQLiteDatabase( 4668): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 4668): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4668): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4668): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4668): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4668): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 4668): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 4668): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 4668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4668): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4668): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4668): threadid=10: thread exiting with uncaught exception (group=0x41731e30)
E/AndroidRuntime( 4668): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 4668): Process: com.android.keychain, PID: 4668
E/AndroidRuntime( 4668): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4668): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4668): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4668): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4668): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 4668): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 4668): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 4668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4668): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4668): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  907): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=4683 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/ActivityManager(  907): App crashed! Process: com.android.keychain
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 4668): killProcess, pid=4668
D/Process ( 4668): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/ErrorReport(  907): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  907): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1452261201645.dbox_tmp: open failed: EROFS (Read-only file system)
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
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager(  907): Recipient 4379
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 4668
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.android.keychain (pid 4668) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
D/AppTag  ( 4683): getInstance(Context context)
D/AppTag  ( 4683): getInstance(Context context)
D/AppTag  ( 4683): onCreate()
D/PMS     (  907): acquireWL(426f0770): PARTIAL_WAKE_LOCK  AsyncService 0x1 4139 10160 null
D/PMS     (  907): releaseWL(426f0770): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
W/dalvikvm( 4177): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2184): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
D/AccountUtils( 2184): Clearing selected account for com.example.hello
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
I/ActivityManager(  907): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
D/ChimeraCfgMgr( 2184): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2184): Module APK com.google.android.play.games already loaded
I/LocationSettingsChecker( 2184): Removing dialog suppression flag for package com.example.hello
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2184): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6e246f50
E/SQLiteDBG( 2184): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb24de8
W/dalvikvm( 2184): threadid=48: thread exiting with uncaught exception (group=0x41731e30)
E/DriveAsyncService( 2184): disk I/O error (code 3850)
E/DriveAsyncService( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2184): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2184): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2184): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  907): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2184): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2184): Process: com.google.android.gms, PID: 2184
E/AndroidRuntime( 2184): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2184): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2184): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2184): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2184): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2184): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2184): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2184): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2184): 	at java.lang.Thread.run(Thread.java:864)
D/Process ( 2184): killProcess, pid=2184
D/Process ( 2184): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop142.tmp: open failed: EROFS (Read-only file system)
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
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 2184
I/ActivityManager(  907): Process com.google.android.gms (pid 2184) has died.
D/PMS     (  907): handleWLDeath(423a8ed8): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  907): Client connection lost with reason: 4
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 10999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20999ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 20997ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 30996ms
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 30996ms
I/ActivityManager(  907): Resuming delayed broadcast
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 30991ms
E/SQLiteLog( 1347): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1347): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x64014008
W/dalvikvm( 1347): threadid=1: thread exiting with uncaught exception (group=0x41731e30)
E/AndroidRuntime( 1347): FATAL EXCEPTION: main
E/AndroidRuntime( 1347): Process: com.google.process.gapps, PID: 1347
E/AndroidRuntime( 1347): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1347): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1347): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1347): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1347): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1347): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1347): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1347): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1347): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1347): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1347): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1347): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1347): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1347): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1347): 	... 10 more
E/ActivityManager(  907): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop143.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4717 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1347): killProcess, pid=1347
D/Process ( 1347): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
I/Prism.ItemManager( 1288): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1288): loadItems() com.htc.launcher.pageview.WidgetManager@41bf5d48 +
I/Prism.WidgetManager( 1288): onLoadItems() +
I/DeviceManagement( 4717): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4717 dbg=false s=true
I/DeviceManagement( 4717): PackageUpdateReceiver: vvv Package removed: [com.example.hello]
I/DeviceManagement( 4717): WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.example.hello, operation=3}]]
I/DeviceManagement( 4717): WorkflowService: Starting workflow service
I/DeviceManagement( 4717): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@41b981c0] args=[Bundle[mParcelledData.dataSize=116]]
I/DeviceManagement( 4717): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4717): PackageUpdateWorkflow: Package update: package=com.example.hello, operation=REMOVE
I/DeviceManagement( 4717): PackageUpdateWorkflow: ==================================================
I/DeviceManagement( 4717): ModelRegistry: Loading model meta data from resources...
I/DeviceManagement( 4717): BackgroundController: *** Processing package remove for appID=com.example.hello
I/DeviceManagement( 4717): SessionStateController: Checking invariants...
I/ActivityManager(  907): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4731 uid=10099 gids={50099, 3003, 5012}
I/ActivityManager(  907): Recipient 1347
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Process com.google.process.gapps (pid 1347) has died.
W/ActivityManager(  907): Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 30806ms
D/WifiService(  907): Client connection lost with reason: 4
D/Documents( 4731): Loading roots for com.android.providers.downloads.documents
D/Documents( 4731): Loading roots for com.android.externalstorage.documents
E/SQLiteDatabase( 4731): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 4731): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4731): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/SQLiteDatabase( 4731): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/SQLiteDatabase( 4731): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/SQLiteDatabase( 4731): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/SQLiteDatabase( 4731): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/SQLiteDatabase( 4731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4731): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4731): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4731): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4731): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4731): 	at dalvik.system.NativeStart.main(Native Method)
W/dalvikvm( 4731): threadid=1: thread exiting with uncaught exception (group=0x41731e30)
E/AndroidRuntime( 4731): FATAL EXCEPTION: main
E/AndroidRuntime( 4731): Process: com.android.documentsui, PID: 4731
E/AndroidRuntime( 4731): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 4731): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 4731): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 4731): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 4731): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 4731): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 4731): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 4731): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 4731): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4731): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4731): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4731): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4731): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
E/AndroidRuntime( 4731): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
E/AndroidRuntime( 4731): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:337)
E/AndroidRuntime( 4731): 	at android.content.ContentResolver.call(ContentResolver.java:1378)
E/AndroidRuntime( 4731): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
E/AndroidRuntime( 4731): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 4731): 	... 10 more
I/ActivityManager(  907): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4745 uid=10023 gids={50023, 1028, 1015, 1023}
I/ActivityManager(  907): Start proc com.google.android.gms for broadcast com.google.android.gms/.nearby.settings.NearbyAppUninstallReceiver: pid=4757 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/Process (  907): killProcessQuiet, pid=4328
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 4328:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/Process (  907): killProcessQuiet, pid=4300
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.attachApplicationLocked:5573 
E/ActivityManager(  907): App crashed! Process: com.android.documentsui
I/ActivityManager(  907): Killing 4300:com.google.android.talk/u0a111 (adj 15): empty #17
D/ErrorReport(  907): HtcErrorReportManager Begin---add error logs to dropbox
I/wpa_supplicant( 1156): wpa_supplicant_scan enter
I/wpa_supplicant( 1156): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1156): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1156): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1156): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1156): nl80211: Event message available
D/wpa_supplicant( 1156): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0

```
