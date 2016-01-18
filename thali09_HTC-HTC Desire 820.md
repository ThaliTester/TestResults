#### Test 563583788793eb6_thali09_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/PMS     (  916): acquireWL(441831f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{4297e570: PendingIntentRecord{428b1730 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=102654, Int=0
--------- beginning of /dev/log/main
D/Finsky  ( 4135): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/WifiDataStallTracker(  916): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  916): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
W/dalvikvm( 4135): VFY: unable to resolve static field 177 (SUPPORTED_ABIS) in Landroid/os/Build;
V/AlarmManager(  916): sending alarm PendingIntent{4451f7d8: PendingIntentRecord{446194f0 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453134223021, Int=0
D/WifiDataStallTracker(  916): updateDataStallInfo: mDataStallTxRxSum={txSum=34 rxSum=25} preTxRxSum={txSum=34 rxSum=25}
D/WifiDataStallTracker(  916): updateDataStallInfo: NONE
D/WifiDataStallTracker(  916): onDataStallAlarm: tag=22412 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  916): startDataStallAlarm: tag=22413 delay=15s
D/PMS     (  916): releaseWL(441831f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.android.vending (4135/10074)
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc    ( 4135): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4135): [NET] getaddrinfo-,err=8
D/libc    ( 4135): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 4135): [NET] getaddrinfo-, 1
D/libc    ( 4135): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =bb +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4135): [NET] getaddrinfo_proxy-, success
I/global  ( 4135): call createSocket() return a new socket.
D/libc    ( 4135): [NET] getaddrinfo+,hn 13(0x3231362e35382e),sn(),family 0,flags 4
D/libc    ( 4135): [NET] getaddrinfo-, SUCCESS
D/libc    ( 4135): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 4135): [NET] getaddrinfo-,err=8
D/WIFI_ICON( 1164): WifiActivity: 3
D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
E/cutils-trace( 4405): Error opening trace file: No such file or directory (2)
I/HtcModeClient( 1568): handler message = 4011
E/HtcModeClient( 1568): Check connection and retry 11 times.
D/CustomizationManager( 4405): ====startRecUseTime====
D/htc.customization.log.level( 4405):  is 
W/CustomizationLogLevel( 4405): Level value is invalid, use default level 2
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/NetworkManagementSocketTagger( 4135): untagSocket(69) failed with errno -22
D/Finsky  ( 4135): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
D/CustomizationManager( 4405):  Read ACC file spent 0.062 (s)
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4405): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4405): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4405): Parsing tag category name = system
I/CustomizationCIDLoader( 4405): Parsing tag category name = application
I/CustomizationCIDLoader( 4405): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4405): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4405): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4405): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4405): Parsing tag category name = Settings
D/CustomizationManager( 4405):  Read CID file spent 0.107 (s)
D/CustomizationManager( 4405):  All configurations done spent 0.107 (s)
W/HtcNativeFlag( 4405): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4405): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4405): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4405): Fail to get flag for type 'language', use default value: -1
D/PMS     (  916): acquireWL(44676dd0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
W/CpuWake (  916): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  916): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  916): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  916): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  916): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  916): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  916): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4405
D/PMS     (  916): acquireHCC(44650400): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 916 1000 null
D/PMS     (  916): acquireHCC(44637100): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 916 1000 null
W/asset   (  916): Copying FileAsset 0x62b599b0 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/Intent  (  916): @test_code: getHtcIntentFlag: 0 obj: 1146711632
D/PMS     (  916): acquireWL(445f86f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 916 1000 null
I/FeedHostManager( 1303): [onPause]
I/FeedProviderManager( 1303): onPause
I/FeedHostManager( 1303): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41dec198
I/SocialFeedProvider( 1303): +onPause
I/SocialFeedProvider( 1303): -onPause
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  916): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4417 uid=10389 gids={50389, 3003, 5012, 3001, 3002, 1028, 1015}
I/TrimMemoryManager( 1303): [trimMemory] 20
W/asset   ( 4417): Copying FileAsset 0x5c7ec420 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
V/WebViewChromiumFactoryProvider( 4417): Binding Chromium to main looper Looper (main, tid 1) {41dc9f98}
I/LibraryLoader( 4417): Expected native library version number "",actual native library version number ""
I/chromium( 4417): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4417): Initializing chromium process, renderers=0
D/PMS     (  916): releaseWL(44676dd0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(4345a980): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/PMS     (  916): acquireWL(43422920): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
D/BluetoothManagerService(  916): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  916): java.lang.Throwable: stack dump
D/BluetoothManagerService(  916): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4289ba78:true
W/System.err(  916): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  916): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  916): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  916): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  916): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 4417): 1105067536: getState(). Returning 12
D/PMS     (  916): releaseWL(4345a980): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/Adreno-EGL( 4417): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4417): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4417): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4417): Local Branch: 
I/Adreno-EGL( 4417): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4417): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4417):                  aa63bbd948f41d15fc72f585e
W/chromium( 4417): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 4417): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 4417): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 4417): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4417): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4417): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 4417): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 4417): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 4417): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 4417): CordovaWebView is running on device made by: HTC
,W/AwContents( 4417): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  916): Disable input method client, pid=1303
W/ResourceType( 4417): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 4417): [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41e114c0, mServedView=org.apache.cordova.engine.SystemWebView{41dd7128 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/ActivityManager(  916): Displayed com.test.thalitest/.MainActivity: +322ms
W/AwContents( 4417): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  916): Enable input method client, pid=4417
W/XT9_C   ( 1241): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1241): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1241): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1241): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  916): releaseWL(445f86f0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/NetworkManagementSocketTagger( 4135): untagSocket(69) failed with errno -22
D/JsMessageQueue( 4417): Set native->JS mode to OnlineEventsBridgeMode
D/jxcore_app_log( 4417): JniHelper::setJavaVM(0x4198b010), pthread_self() = 1664325152
I/chromium( 4417): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 11.997MB for 42652-byte allocation
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 12.074MB for 95956-byte allocation
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 12.157MB for 143930-byte allocation
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 12.271MB for 215890-byte allocation
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 12.446MB for 323830-byte allocation
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 12.715MB for 485740-byte allocation
,W/NetworkManagementSocketTagger( 4135): untagSocket(69) failed with errno -22
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 13.711MB for 1092904-byte allocation
,D/ConnectivityService(  916): getNetworkInfo networkType=0 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 14.635MB for 1639352-byte allocation
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=4 [65][3][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -58 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 26
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,W/CpuWake (  916): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  916): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  916): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  916): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  916): >>release mCpuPerf_Freq wakelock
,W/CpuWake (  916): <<release mCpuPerf_Freq wakelock
D/PMS     (  916): releaseHCC(44650400): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  916): releaseHCC(44637100): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.android.vending (4135/10074)
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 15.949MB for 2459024-byte allocation
,D/Finsky  ( 4135): [1] DailyHygiene.access$600: Logging device features
,D/PMS     (  916): acquireWL(4407cfa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10074}
,V/AlarmManager(  916): sending alarm PendingIntent{428f5980: PendingIntentRecord{4291b798 com.android.vending broadcastIntent}}, i=null, t=0, cnt=1, w=1453134232292, Int=0
,D/PMS     (  916): acquireWL(42990a50): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 4135 10074 null
,D/WearableService( 1253): callingUid 10029, callindPid: 1253
D/PMS     (  916): releaseWL(4407cfa8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4135): [441] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1253): client connected with version: 8296000
,D/Finsky  ( 4135): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4135): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc    ( 4135): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 4135): [NET] getaddrinfo-,err=8
D/libc    ( 4135): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 4135): [NET] getaddrinfo-, 1
,D/libc    ( 4135): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =7f28 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 204
D/libc    (  364): [NET]res_nsend:resplen=87
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 4135): [NET] getaddrinfo_proxy-, success
,D/PMS     (  916): releaseWL(42990a50): PARTIAL_WAKE_LOCK  wake:com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService 0x1 null
,I/dalvikvm-heap( 4417): Grow heap (frag case) to 18.068MB for 3688532-byte allocation
,W/jxcore-log( 4417): Initializing JXcore engine
,W/jxcore-log( 4417): JXcore engine is ready
,W/jxcore-log( 4417): Starting JXcore engine
,W/jxcore-log( 4417): Platform android
W/jxcore-log( 4417): 
,W/jxcore-log( 4417): Process ARCH arm
W/jxcore-log( 4417): 
,D/PMS     (  916): releaseWL(43422920): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/SensorManager(  916): mEventCount = 900
,D/WIFI_ICON( 1164): WifiActivity: 0
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/jxcore-log( 4417): JXcore Cordova bridge is ready!
I/jxcore-log( 4417): 
,W/jxcore-log( 4417): JXcore engine is started
,E/jxcore  ( 4417): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
E/jxcore  ( 4417): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,I/chromium( 4417): [INFO:CONSOLE(37)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (37)
I/ActivityManager(  916): mThumbnailWidth=360, mThumbnailHeight=640
,D/PMS     (  916): acquireWL(426c01d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 916 1000 null
,I/FeedHostManager( 1303): [onResume]
,I/FeedProviderManager( 1303): onResume
I/SocialFeedProvider( 1303): +onResume
,I/SocialFeedProvider( 1303): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1303): -onResume
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.launcher (1303/10076)
,I/InputMethodManagerService(  916): Disable input method client, pid=4417
,W/IInputConnectionWrapper( 4417): reportFullscreenMode on inactive InputConnection
I/InputMethodManagerService(  916): Enable input method client, pid=1303
,D/PMS     (  916): releaseWL(426c01d0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
,D/Process (  916): killProcessQuiet, pid=4187
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityStack.destroyActivityLocked:3147 
I/ActivityManager(  916): Killing 4187:com.google.android.partnersetup/u0a32 (adj 15): empty #17
,E/libEGL  ( 4417): call to OpenGL ES API with no current context (logged once per thread)
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4187
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/HtcModeClient( 1568): handler message = 4011
,E/HtcModeClient( 1568): Check connection and retry 12 times.
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [13][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 52
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WIFI_ICON( 1164): WifiActivity: 1
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -56 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 78
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WIFI_ICON( 1164): WifiActivity: 0
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/AutoSetting( 1568): service - handleMessage() stop self
,D/AutoSetting( 1568): service - onDestroy() END
,D/AutoSetting( 1568): service - handleMessage() quit looper
,I/HtcModeClient( 1568): handler message = 4011
,E/HtcModeClient( 1568): Check connection and retry 12 times. Stop service and kill this process.
,D/HtcModeClient( 1568): Don't start project servcice
,D/HtcModeClient( 1568): setEject: MEDIA_EJECT_STATE = true
,D/HtcModeClient( 1568): connectState: CONNECTION_READY = false
,D/SilentMusic( 1568): call stop
,D/HtcModeClient( 1568): close connection
,W/HtcModeClient( 1568): leaveProjectMode: It does not enter ProjectMode
,W/CANMesgAgentLocalSocket( 1568): read the terminate packet, so break
,D/Process (  916): killProcessQuiet, pid=4219
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4219:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4219
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): acquireWL(441ae900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=113209, Int=0
,I/dalvikvm-heap( 1303): Grow heap (frag case) to 13.382MB for 50416-byte allocation
,I/ClockThread( 1164): now=1453134240052 next=59948
D/PMS     (  916): releaseWL(441ae900): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 104
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,I/ActivityManager(  916): Start proc com.htc.mms.backupagent for service com.htc.mms.backupagent/.SMSBackupAgentService: pid=4481 uid=10078 gids={50078}
,D/PMS     (  916): acquireWL(440853b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10078}
,V/AlarmManager(  916): sending alarm PendingIntent{4343f860: PendingIntentRecord{445c4f08 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1453134242427, Int=60000
,D/PMS     (  916): releaseWL(440853b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10078}
,D/SMSBackup( 4481): SMSBackupAgentService started
,D/SMSBackup( 4481): Checking restore status
,D/SMSBackup( 4481): Restore complete
,D/SMSBackup( 4481): cancelCheckAlarm
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,D/SMSBackup( 4481): SMSBackupAgentService completed: completed in 0.0 seconds
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/Process (  916): killProcessQuiet, pid=4242
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4242:com.htc.backup/1000 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4242
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WIFI_ICON( 1164): WifiActivity: 1
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 130
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WifiStateMachine(  916): [ScoreAP] + current TXpacket:143, mTXpacketCount:62, avgLinkspeed:26,mAvgTxRate54
,D/WifiStateMachine(  916): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/WifiDataStallTracker(  916): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  916): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  916): updateDataStallInfo: mDataStallTxRxSum={txSum=110 rxSum=99} preTxRxSum={txSum=34 rxSum=25}
D/WifiDataStallTracker(  916): updateDataStallInfo: IN/OUT
D/PMS     (  916): acquireWL(43d28eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{43a77838: PendingIntentRecord{428b1730 android broadcastIntent}}, i=com.android.internal.wifi.data-stall, t=3, cnt=1, w=117672, Int=0
,D/PMS     (  916): releaseWL(43d28eb8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/WifiDataStallTracker(  916): onDataStallAlarm: tag=22413 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  916): startDataStallAlarm: tag=22414 delay=15s
,D/WIFI_ICON( 1164): WifiActivity: 0
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,V/LightsService(  916): setLight #0: color=#25
,V/LightsService(  916): setLight #0: color=#22
,V/LightsService(  916): setLight #0: color=#1b
,V/LightsService(  916): setLight #0: color=#15
,V/LightsService(  916): setLight #0: color=#14
,D/PMS     (  916): acquireWL(428f5160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10074}
,V/AlarmManager(  916): sending alarm PendingIntent{42790518: PendingIntentRecord{4305ad40 com.android.vending startService}}, i=null, t=0, cnt=1, w=1453134246231, Int=0
,D/PMS     (  916): releaseWL(428f5160): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10074}
,D/Finsky  ( 4135): [431] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4135): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/SensorManager(  916): mEventCount = 1050
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 26
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/PMS     (  916): acquireWL(44650f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44650f18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/HtcPowerSaver(  916): updateBatteryInfo
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1164): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1164): closing low battery warning: level=100
D/PowerUI ( 1164): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1164): status:5 level:100 unsupport:false plugged:true
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 52
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,I/PMS     (  916): Going to sleep due to screen timeout...
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.android.server.power.DisplayPowerController$10@42326760,
W/PMS     (  916): mWirelessDisplayManager is null
,W/BatSI   (  916): Couldn't get kernel wake lock stats
D/WirelessDisplayService(  916): Screen File Receiver; callOnGoing: false, Screen On: false
D/WirelessDisplayService(  916): ScreenReceiver: ACTION_SCREEN_OFF && Not in DongleWait nor MirrorEnabling State: REQ_JOIN_GROUP - FALSE
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  916): disable: get sensor name = CM36282 Light sensor
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 2
W/SensorService(  916): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=2)
,W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.android.server.power.DisplayPowerController$10@42326760, eanble = 0, strlen(mName) = 59
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 2
W/SensorService(  916): Listener[0] = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42481758
W/SensorService(  916): Listener[1] = com.htc.smartdim.sensor_eye@42f93f28
,W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
V/LightsService(  916): setLight #2: color=#0
D/qdlights(  916): set_light_buttons_func: on=0 brightness=0
V/LightsService(  916): setLight #0: color=#0
,D/SurfaceControl(  916): Excessive delay in blankDisplay() while turning screen off: 322ms
D/PMS     (  916): nativeSetInteractive:false
D/PMS     (  916): nativeSetInteractive:false done
D/PMS     (  916): nativeSetAutoSuspend:true
D/PMS     (  916): nativeSetAutoSuspend:true done
D/HABCtrl (  916): TPE algorithm. remove timeout.
I/InputManager(  916): Cancel all due to getting PMS screen off broadcast
D/PMS     (  916): OOBE c monitor 11
,V/KeyguardServiceDelegate(  916): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$21@434580b0)
,I/IntentController( 1164): receive(com.htc.server.HtcPMSExtension.ACTUAL_SCREEN_OFF,1,false)
,V/KeyguardServiceDelegate(  916): **** SHOWN CALLED ****
D/NfcService( 1286): ScreenObserver: OFF
,D/NfcService( 1286): applyRouting - 0
D/PMN     (  916): wakingUp
I/InputMethodManagerService(  916): screenObserver, isScreenOn=false
I/WindowManager(  916): No lock screen! windowToken=null
D/PMN     (  916): onScreenOn
I/InputMethodManagerService(  916): Disable input method client, pid=1303
,D/NfcService( 1286): applyRouting -2
D/WirelessDisplayService(  916): ScreenReceiver;com.htc.keyguard.dismiss_when_screen_on,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  916): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
,D/WirelessDisplayService(  916): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
D/PMS     (  916): acquireWL(43782c60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1286 1027 null
D/PMS     (  916): releaseWL(43782c60): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
D/AlarmManager(  916): ACTION_SCREEN_ON
I/AlarmManager(  916): [AlarmQueuing] recover blocked alarms
I/AlarmManager(  916): [AlarmQueuing] done recovering
I/AlarmManager(  916): [AlarmQueuing] recover EPS screen off blocked alarms
I/AlarmManager(  916): [AlarmQueuing] done EPS screen off alarm recovering
,D/WifiDataStallTracker(  916): onReceive: action=android.intent.action.SCREEN_ON
,D/WifiDataStallTracker(  916): startDataStallAlarm: tag=22415 delay=15s
,D/MtpService( 2981): [MTP][onReceive]+android.intent.action.USER_PRESENT
,D/MtpService( 2981): [MTP][onReceive]-
,D/NfcService( 1286): applyRouting - 0
,D/NfcService( 1286): applyRouting -2
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
D/PMS     (  916): acquireWL(42cad650): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 1286 1027 null
D/WirelessDisplayService(  916): ScreenReceiver;android.intent.action.USER_PRESENT,callOnGoing: false, Screen On: false
D/WirelessDisplayService(  916): ScreenReceiver: ACTION_USER_PRESENT: REQ_JOIN_GROUP - TRUE
D/WirelessDisplayService(  916): ScreenReceiver:ACTION_USER_PRESENT: curState1 condState:0
,D/WifiNative-wlan0(  916): doBoolean: SET_SCREEN_ON 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): SET_SCREEN_ON:On
I/wpa_supplicant( 1119): htc_wext_set_keepalive +
I/wpa_supplicant( 1119): htc_wext_set_keepalive: enable=0, type=2, interval=15
D/wpa_supplicant( 1119): getPrivFuncNum +	
I/wpa_supplicant( 1119): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive fnum = 0x8bf6
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
I/wpa_supplicant( 1119): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1119): BG scan when screen On
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING - ret = 0
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): Match BG scan, scan!
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1119): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/WifiNative-wlan0(  916):    returned true
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(42cad650): PARTIAL_WAKE_LOCK  NfcService:mRoutingWakeLock 0x1 null
V/NotificationService(  916): batLight: Full, plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c800
D/qdlights(  916): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,I/ClockThread( 1164): stop update clock
,I/ActivityManager(  916): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncDataLinkTurnOffReceiver: pid=4503 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/NotificationService(  916): batLight: Full, plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c800
D/qdlights(  916): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,V/SRS_Proc(  372): ParamSet string: screen_state=on
,D/WirelessDisplayService(  916): ScreenReceiver;android.intent.action.SCREEN_ON,callOnGoing: false, Screen On: false
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/NetworkPolicy(  916): updateScreenOn: false
,W/ContextImpl( 4503): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  916): acquireWL(4407dd88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(4407dd88): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42a5dd60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/SmartSyncUtils( 4503): isEpsOn(), nState = 0
D/PMS     (  916): releaseWL(42a5dd60): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(445990a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4503 1000 null
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOn: false
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOn: 1453134253488
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOn: 1453134253488
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42481758
,W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
,D/PMS     (  916): releaseWL(445990a0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
W/SensorService(  916): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 2
W/SensorService(  916): BOSCH BMA250 3-axis Accelerometer (handle=0x00000000, connections=1)
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.android.internal.policy.impl.WindowOrientationListener$SensorEventListenerImpl@42481758, eanble = 0, strlen(mName) = 91
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 1
W/SensorService(  916): Listener[0] = com.htc.smartdim.sensor_eye@42f93f28
,W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/FeedHostManager( 1303): [onPause]
I/FeedProviderManager( 1303): onPause
,I/FeedHostManager( 1303): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41dec198
I/SocialFeedProvider( 1303): +onPause
,I/SocialFeedProvider( 1303): -onPause
D/PMN     (  916): goingToSleep
D/PMS     (  916): acquireWL(434edcd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 916 1000 null
,D/AlarmManager(  916): ACTION_SCREEN_OFF
I/AlarmManager(  916): [AlarmQueuing] screen off now: 
I/AlarmManager(  916): [AlarmQueuing] data connection: true
,D/WifiDataStallTracker(  916): onReceive: action=android.intent.action.SCREEN_OFF
,D/WifiDataStallTracker(  916): stopDataStallAlarm: current tag=22415 mDataStallAlarmIntent=PendingIntent{427ada60: PendingIntentRecord{428b1730 android broadcastIntent}}
,D/SmartSyncUtils( 4503): getMobilePolicyEnabled, result = true
I/AlarmManager(  916): [AlarmQueuing] wifi connection: true
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/Process (  916): killProcessQuiet, pid=4206
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/WifiNative-wlan0(  916): doBoolean: SET_SCREEN_ON 0
I/ActivityManager(  916): Killing 4206:com.htc.cs.dm/u0a98 (adj 15): empty #17
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.smartdim.SystemIntentReceiver.onReceive:143 android.app.ActivityThread.handleReceiver:2687 
D/PMS     (  916): releaseWL(434edcd0): PARTIAL_WAKE_LOCK  ActivityManager-Sleep 0x1 null
,D/PMS     (  916): acquireWL(4462fc08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 916 1000 null
D/AutoSetting( 1388): receiver - intent: android.intent.action.USER_PRESENT
,D/AutoSetting( 1388): service - onCreate()
D/TetherSettings( 3821): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3821): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3821): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3821): Cust_ConnectToPC   : spcsc>false
D/        ( 3821): Cust_ConnectToPC   : IPT>true
D/        ( 3821): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3821): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3821): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3821): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3821): onReceive : android.intent.action.USER_PRESENT hasTethered:false isNSOpening:false
I/ActivityManager(  916): Recipient 4206
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PSReceiver( 3821): onReceive:android.intent.action.USER_PRESENT
,D/AutoSetting( 1388): service - AddressCache: using context: com.htc.Weather
I/SmartNS_PSService( 3821): onReceive:android.intent.action.USER_PRESENT
W/Settings( 3821): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3821):  defaultType:0
D/LocationManagerService(  916): request 42745540 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
,D/LocationManagerService(  916): provider request: passive ProviderRequest[ON interval=0]
,D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.delayrequest
W/ContextImpl( 3821): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,W/ContextImpl( 4503): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.smartsync.SmartSyncDataLinkTurnOffReceiver.onReceive:28 android.app.ActivityThread.handleReceiver:2687 
,D/SmartSyncUtils( 4503): isEpsOn(), nState = 0
,D/SmartSyncUtils( 4503): getMobilePolicyEnabled, result = true
,D/SmartSyncUtils( 4503): isEpsOn(), nState = 0
D/WifiService(  916): New client listening to asynchronous messages
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 26
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET_SCREEN_ON 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): SET_SCREEN_ON:Off
I/wpa_supplicant( 1119): htc_wext_set_keepalive +
I/wpa_supplicant( 1119): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1119): getPrivFuncNum +	
I/wpa_supplicant( 1119): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1119): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1119): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1119): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  916):    returned true,
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 78
D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/SensorManager(  916): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f93f28
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed,
W/SensorService(  916): disable: get sensor name = BOSCH BMA250 3-axis Accelerometer
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1747 android.content.ContextWrapper.stopService:506 android.content.ContextWrapper.stopService:506 com.htc.smartdim.SystemIntentReceiver.onReceive:123 android.app.ActivityThread.handleReceiver:2687 
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 1
W/SensorService(  916): CM36282 Proximity sensor (handle=0x00000001, connections=1)
W/SensorService(  916): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f93f28, eanble = 0, strlen(mName) = 36
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
W/SensorService(  916): Following SensorService logs are not warning, just make sure they are printed
W/SensorService(  916): disable: get sensor name = CM36282 Proximity sensor
W/SensorService(  916): pid=916, uid=1000
W/SensorService(  916): Active sensors: size = 0
W/SensorService(  916): SensorService::listenerSensor++: mName = com.htc.smartdim.sensor_eye@42f93f28, eanble = 0, strlen(mName) = 36
W/SensorService(  916): Active Listeners: mActiveListeners.size() = 0
W/SensorService(  916): void android::SensorService::listenerSensor(const char*, int32_t)--:
,I/SensorManager(  916): unregisterListenerImpl++: listener = com.htc.smartdim.sensor_eye@42f93f28
V/SRS_Proc(  372): ParamSet string: screen_state=off
E/ActivityThread(  916): Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276b7a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  916): android.app.IntentReceiverLeaked: Service com.htc.smartdim.sensor_eye has leaked IntentReceiver com.htc.smartdim.sensor_eye$CoverStateReceiver@4276b7a0 that was originally registered here. Are you missing a call to unregisterReceiver()?
E/ActivityThread(  916): 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:904)
E/ActivityThread(  916): 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:673)
E/ActivityThread(  916): 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1692)
E/ActivityThread(  916): 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1672)
E/ActivityThread(  916): 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:481)
E/ActivityThread(  916): 	at com.htc.smartdim.sensor_eye.register(sensor_eye.java:166)
E/ActivityThread(  916): 	at com.htc.smartdim.sensor_eye.onStart(sensor_eye.java:285)
E/ActivityThread(  916): 	at android.app.Service.onStartCommand(Service.java:450)
E/ActivityThread(  916): 	at android.app.ActivityThread.handleServiceArgs(ActivityThread.java:3027)
E/ActivityThread(  916): 	at android.app.ActivityThread.access$2100(ActivityThread.java:153)
E/ActivityThread(  916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1455)
E/ActivityThread(  916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(  916): 	at android.os.Looper.loop(Looper.java:157)
E/ActivityThread(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
E/ActivityThread(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
E/ActivityThread(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/ActivityThread(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/ActivityThread(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/ActivityThread(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/ActivityThread(  916): 	at dalvik.system.NativeStart.main(Native Method)
D/NetworkPolicy(  916): updateScreenOn: false
D/ContactMessageStore( 1270): start background delete task...
D/ContactMessageStore( 1270): size: 0 , 0
D/ContactMessageStore( 1270): Background delete complete
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] getTotalRam: 1873 Mb
,D/PMS     (  916): acquireWL(4408c208): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4408c208): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(43caded8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(43caded8): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1790): onScreenOff.
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): onScreenOff
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1790): disableBatteryAlarm: null
,I/[HTC_BLE_2013.12.02.SDKBUILD][LocalLinkService]( 1790): onScreenOff
,D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
,D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/PMS     (  916): releaseWL(4462fc08): PARTIAL_WAKE_LOCK  WifiSuspend 0x1 null
,D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1119): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1119): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1119): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1119): nl80211: Survey data missing
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1119): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1119): Sorted scan results
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-88
D/wpa_supplicant( 1119): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1119): Add randomness: count=5 entropy=0
D/wpa_supplicant( 1119): Add randomness: count=6 entropy=1
D/wpa_supplicant( 1119): Add randomness: count=7 entropy=2
D/wpa_supplicant( 1119): Add randomness: count=8 entropy=3
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1119): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1119): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1119): wpa_supplicant_pick_network+
I/wpa_supplicant( 1119): Selecting BSS from priority group 1
I/wpa_supplicant( 1119): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1119): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1119): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1119): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1119):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1119):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1119): Start print parameters
I/wpa_supplicant( 1119): wpa_s->wpa_state is 9
I/wpa_supplicant( 1119): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1119): isConcurrentMode() is 0
I/wpa_supplicant( 1119): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1119): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1119): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1119): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1119): wpa_s->reassociate is 0
I/wpa_supplicant( 1119): wpa_s->is_screen_on 0
I/wpa_supplicant( 1119): wpa_s->ifname wlan0
I/wpa_supplicant( 1119): End print parameters
I/wpa_supplicant( 1119): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1119): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1119): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1119): clear disabled list - type=1
I/wpa_supplicant( 1119): No suitable network found
W/wpa_supplicant( 1119): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1119): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1119): nl80211: Survey data missing
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1119): Sorted scan results
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I,/wpa_supplicant( 1119): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-88
D/wpa_supplicant( 1119): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1119): Add randomness: count=9 entropy=4
D/wpa_supplicant( 1119): Add randomness: count=10 entropy=5
D/wpa_supplicant( 1119): Add randomness: count=11 entropy=6
D/wpa_supplicant( 1119): Add randomness: count=12 entropy=7
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1119): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1119): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1119): wpa_supplicant_pick_network+
I/wpa_supplicant( 1119): clear disabled list - type=1
I/wpa_supplicant( 1119): No suitable network found
W/wpa_supplicant( 1119): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1119): State: DISCONNECTED -> INACTIVE
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  916): doString: LIST_DONGLES
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=-1 state=2 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =INACTIVE
,D/WifiP2pService(  916): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): DefaultState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): InactiveState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43d5a800 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43d5a800 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): DefaultState{ when=0 what=147462 obj=android.net.wifi.StateChangeResult@43d5a800 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000),
D/WirelessDisplayService(  916): getDiscoveryDongleList
D/WifiNative-wlan0(  916): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0,
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1119): reply (489) for get BSS: id=0
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1119): freq=5220
I/wpa_supplicant( 1119): level=-47,
I/wpa_supplicant( 1119): tsf=0000000128614950
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG7005g
I/wpa_supplicant( 1119): ====
,I/wpa_supplicant( 1119): id=1
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): freq=2412
I/wpa_supplicant( 1119): level=-57
I/wpa_supplicant( 1119): tsf=0000000128614989,
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG700
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=2
I/wpa_supplicant( 1119): bssid=c2:ff:d4:d3:aa:48,
I/wpa_supplicant( 1119): freq=2412
I/wpa_supplicant( 1119): level=-57
I/wpa_supplicant( 1119): tsf=0000000128614976
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1119): ssid=01ABC
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=3
I/wpa_supplicant( 1119): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1119): freq=2427
I/wpa_supplicant( 1119): level=-88
I/wpa_supplicant( 1119): tsf=0000000128614999
I/wpa_supplicant( 1119): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1119): ssid=Gonzos
I/wpa_supplicant( 1119): ####
,D/WifiStateMachine(  916): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
,D/WifiStateMachine(  916): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 128614950, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 128614989, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 128614976, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2427, timestamp: 128614999, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  916): add 4 to mScanResults
V/ScoreHelper(  916): Only print Top 10 in ApScanList
V/ScoreHelper(  916):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
V/ScoreHelper(  916):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
V/ScoreHelper(  916):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
V/ScoreHelper(  916):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-88], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  916):  + computeScore(NG700): 1
D/WifiStateMachine(  916): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
D/WifiStateMachine(  916): == begin of scan result ==
D/WifiStateMachine(  916): == (4) end of scan result ==
D/WifiManager( 1253): getScanResults enter 
D/WifiStateMachine(  916): == begin of scan result ==
,D/WifiStateMachine(  916): == (4) end of scan result ==
,D/WirelessDisplayService(  916): getDiscoveryDongleList
D/WifiNotificationController(  916): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/PMS     (  916): acquireWL(43cb1590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43cb1590): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(429d79b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  916): sending alarm PendingIntent{430f7e90: PendingIntentRecord{4280e530 com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=133879, Int=0
,D/PMS     (  916): releaseWL(429d79b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(42945470): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/PMS     (  916): acquireWL(4291edf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4291edf8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(42945470): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(43b27340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(43b27340): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(4454def8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/PMS     (  916): acquireWL(445acdd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(445372c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,I/VacuumService( 1253): Vacuum at: now=1453134260868 tag=VacuumService
D/PMS     (  916): releaseWL(4454def8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(445acdd8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(4412eb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(4412eb00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(445372c0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(43e40a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/PMS     (  916): releaseWL(43e40a80): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(445cea78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(445cea78): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(441326d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(441326d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): acquireWL(445c1990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): acquireWL(4463e2d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4463e2d8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(440bc9e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(445c1990): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(445d8ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(445d8ee8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,I/PhenotypeConfigurator( 1253): Scheduling Phenotype for one-off execution 4925 seconds from now (1453134261407)
,D/GetConfigurationSnapshotOperation( 1253): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1253): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 1253): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1253): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1253): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 1253): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,I/GoogleURLConnFactory( 1253): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
,W/dalvikvm( 1253): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/libc    ( 1253): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
D/libc    ( 1253): [NET] getaddrinfo-,err=8
D/libc    ( 1253): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    ( 1253): [NET] getaddrinfo-, 1
,D/libc    ( 1253): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =97c9 +++++
,D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1253): [NET] getaddrinfo_proxy-, success,
,D/libc    ( 1253): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1253): [NET] getaddrinfo-,err=8
D/libc    ( 1253): [NET] getaddrinfo+,hn 19(0x706c61792e676f),sn(),family 0,flags 4
,D/libc    ( 1253): [NET] getaddrinfo-,err=8
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [7][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): releaseWL(440bc9e0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(445db3d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(445db3d0): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(445db158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(445db158): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10029 com.google.android.gms}
,D/AutoSetting( 1388): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1388): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1388): service - requestNLP() NetworkLocationProvider not enabled
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{43baec40 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1119): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1119): nl80211: Event message available
,D/wpa_supplicant( 1119): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1119): Got an original EVENT_SCAN_RESULTS
D/wpa_supplicant( 1119): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1119): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1119): nl80211: Survey data missing
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1119): nl80211: Scan results indicate BSS status with c0:ff:d4:d3:aa:48 as associated
D/wpa_supplicant( 1119): Sorted scan results
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-88
D/wpa_supplicant( 1119): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1119): Add randomness: count=13 entropy=8
D/wpa_supplicant( 1119): Add randomness: count=14 entropy=9
D/wpa_supplicant( 1119): Add randomness: count=15 entropy=10
D/wpa_supplicant( 1119): Add randomness: count=16 entropy=11
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1119): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1119): wpa_supplicant_pick_network+
I/wpa_supplicant( 1119): Selecting BSS from priority group 1
I/wpa_supplicant( 1119): Recent assoc_freq = 2412 rssi = -57
D/wpa_supplicant( 1119): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1119): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1119): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1119):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1119):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1119): Start print parameters
I/wpa_supplicant( 1119): wpa_s->wpa_state is 9
I/wpa_supplicant( 1119): wpa_s->br_have_IP is 1
I/wpa_supplicant( 1119): isConcurrentMode() is 0
I/wpa_supplicant( 1119): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1119): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1119): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1119): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1119): wpa_s->reassociate is 0
I/wpa_supplicant( 1119): wpa_s->is_screen_on 0
I/wpa_supplicant( 1119): wpa_s->ifname wlan0
I/wpa_supplicant( 1119): End print parameters
I/wpa_supplicant( 1119): Do nothing, wait SELECT_BSSID CMD...
D/wpa_supplicant( 1119): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1119): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1119): clear disabled list - type=1
I/wpa_supplicant( 1119): No suitable network found
W/wpa_supplicant( 1119): wlan0: Not restrict scheduled scan for Not WFD CT3
D/wpa_supplicant( 1119): p2p0: Updating scan results from sibling
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1119): nl80211: Survey data missing
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1119): Sorted scan results
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-88
D/wpa_supplicant( 1119): BSS: last_scan_res_used=4/32 ,last_scan_full=0
D/wpa_supplicant( 1119): Add randomness: count=17 entropy=12
D/wpa_supplicant( 1119): Add randomness: count=18 entropy=13
D/wpa_supplicant( 1119): Add randomness: count=19 entropy=14
D/wpa_supplicant( 1119): Add randomness: count=20 entropy=15
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1119): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
I/wpa_supplicant( 1119): wpa_supplicant_pick_network+
I/wpa_supplicant( 1119): clear disabled list - type=1
I/wpa_supplicant( 1119): No suitable network found
W/wpa_supplicant( 1119): p2p0: Not restrict scheduled scan for Not WFD CT3
I/wpa_supplicant( 1119): State: INACTIVE -> INACTIVE
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
,D/WifiNative-wlan0(  916): doString: LIST_DONGLES
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/WifiP2pService(  916): InactiveState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WirelessDisplayService(  916): getDiscoveryDongleList
D/WifiNative-wlan0(  916): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1119): reply (489) for get BSS: id=0
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1119): freq=5220
I/wpa_supplicant( 1119): level=-47
I/wpa_supplicant( 1119): tsf=0000000146044427
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG7005g
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=1
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): freq=2412
I/wpa_supplicant( 1119): level=-57
I/wpa_supplicant( 1119): tsf=0000000146044470
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG700
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=2
I/wpa_supplicant( 1119): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): freq=2412
I/wpa_supplicant( 1119): level=-57
I/wpa_supplicant( 1119): tsf=0000000146044456
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1119): ssid=01ABC
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=3
I/wpa_supplicant( 1119): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1119): freq=2427
I/wpa_supplicant( 1119): level=-88
I/wpa_supplicant( 1119): tsf=0000000128614999
I/wpa_supplicant( 1119): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1119): ssid=Gonzos
I/wpa_supplicant( 1119): ####
D/WifiP2pService(  916): P2pEnabledState{ when=-1ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): DefaultState{ when=-2ms what=147461 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/WifiStateMachine(  916): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 146044427, distance: ?(cm), distanceSd: ?(cm)
,D/WifiStateMachine(  916): [ScoreAP] + roamToTopScoreAP: NG700[c0:ff:d4:d3:aa:48], -57, 0
D/WifiStateMachine(  916): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 146044470, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 146044456, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -88, frequency: 2427, timestamp: 128614999, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): add 4 to mScanResults
,V/ScoreHelper(  916): Only print Top 10 in ApScanList
,V/ScoreHelper(  916):  + ScoreResult:  96, AP:                            NG700 [c0:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used: 10
,V/ScoreHelper(  916):  + ScoreResult:  88, AP:                          NG7005g [c0:ff:d4:d3:aa:4a], Rssi: 15 [-47], Tx: 13, Freq: 10 [5220], Disconn: 50, Last Used:  0
,V/ScoreHelper(  916):  + ScoreResult:  86, AP:                            01ABC [c2:ff:d4:d3:aa:48], Rssi: 15 [-57], Tx: 13, Freq:  8 [2412], Disconn: 50, Last Used:  0
,V/ScoreHelper(  916):  + ScoreResult:  77, AP:                           Gonzos [38:f8:89:11:e9:11], Rssi:  4 [-88], Tx: 13, Freq: 10 [2427], Disconn: 50, Last Used:  0
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
V/ScoreHelper(  916):  + computeScore(NG700): 1
,D/WifiStateMachine(  916): [ScoreAP] + No alternative AP to roam except current AP [1], NG700
,D/WifiStateMachine(  916): == begin of scan result ==
,D/WifiStateMachine(  916): == (4) end of scan result ==
,D/WifiManager( 1253): getScanResults enter 
,D/WifiStateMachine(  916): == begin of scan result ==
D/WifiNotificationController(  916): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/WifiStateMachine(  916): == (4) end of scan result ==
,D/WirelessDisplayService(  916): getDiscoveryDongleList
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=1 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1119): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1119): nl80211: Disconnect event
I/wpa_supplicant( 1119): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1119): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  916): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/HTCRequest(  916): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
I/wpa_supplicant( 1119): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1119): TDLS: Remove peers on disassociation
D/HTCRequest(  916): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/HTCRequest(  916): WifiMonitor:getReasonFromEventString() 0
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  916): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  916): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb85e1bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1119):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  916): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1119): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1119): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1119): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1119): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/WifiStateMachine(  916): Enter handleNetworkDisconnect
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =INACTIVE newSupplicantState =DISCONNECTED
D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1119): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
D/Tethering(  916): interfaceStatusChanged wlan0, false
D/WifiNative-wlan0(  916):    returned true
D/Tethering(  916): [isWifi] getHotspotEnabled: false
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
D/WifiP2pService(  916): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  916): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
D/Tethering(  916): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/WifiNative-wlan0(  916):    returned true
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
,D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/DhcpStateMachine(  916): [RunningState] Stop DHCP
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  916): Exit handleNetworkDisconnect
D/WifiPerfLock(  916): release()
D/WifiStateMachine(  916): PerfLock released for exiting ConnectedState
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
D/libc    (  916): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  916): stopDataStallAlarm: current tag=22416 mDataStallAlarmIntent=null
I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
D/UsbnetStateTracker(  916): isAvailable+-
D/UsbnetStateTracker(  916): reconnect
,D/UsbnetStateTracker(  916): isAvailable+-
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 0
I/wpa_supplicant( 1119): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61
D/ConnectivityService(  916): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/PMS     (  916): acquireWL(4279a460): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 916 1000 null
D/ConnectivityService(  916): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  916): Provision feature enable=false
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/ConnectivityService(  916): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  916): default: reconnect()
D/MDST    (  916): default: setTeardownRequested(false)
D/MDST    (  916): default: setEnableApn apnType =default , enable=true
D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  916):    returned true
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  916): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  916): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  916): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
,D/ConnectivityService(  916): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
,D/WISPrService( 3821): >>>>>WISPrService start isConnected = false<<<<<
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiNative-wlan0(  916): doBoolean: SET pno 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
,D/WISPrService( 3821): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  916): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
,D/WifiService(  916): New client listening to asynchronous messages
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='1'
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1119): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1119): nl80211: Event message available
,D/wpa_supplicant( 1119): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '33 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 33 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiNative-wlan0(  916):    returned true
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,V/NativeCrypto( 1400): Read error: ssl=0x64066900: I/O error during system call, Connection timed out
D/libc    (  364): [NET] entry_id:5   entry:0xb82e7760  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb82e75f8  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb82e7428  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb82e76a8  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb82e74f0  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb82e7828  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '34 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 34 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): handleConnectivityChange: resetting
D/ConnectivityService(  916): resetConnections(wlan0, 3)
D/ConnectivityService(  916): flush DNS cache for net 1(wlan0)
,D/PMS     (  916): acquireWL(4276b580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
V/NativeCrypto( 1400): SSL shutdown failed: ssl=0x64066900: I/O error during system call, Broken pipe
,D/WISPrService( 3821): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,I/QuickSettingWifi( 1164): receive.wifiConnect:false wifiAPname:null elapse:1
,D/WISPrService( 3821): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: DISCONNECTED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =0
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1119): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
,D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSID
,D/Nat464Xlat(  916): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  916): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  916): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  916): acquireWL(439c0e30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/ConnectivityService(  916): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
,D/ConnectivityService(  916): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/WirelessDisplayService(  916): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  916): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  364): RTNETLINK answers: No such process
D/WifiStateMachine(  916): startScan Pid: 916 Uid 1000
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,D/WifiNative-wlan0(  916): doBoolean: SET pno 0
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1119): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
,D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: SCAN
D/ConnectivityService(  916): reportInetCondition for net -1, percentage: 0 by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/PMS     (  916): releaseWL(4276b580): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/BatSI   (  916): WIFI scan started for: 450a0300 uid:1000
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1119): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1119): Failed to initiate AP scan
,I/wpa_supplicant( 1119): Failed to initiate AP scan, Failed_to_scan_counter:1
,D/WifiNative-wlan0(  916):    returned true
,I/QuickSettingWifi( 1164): receive.wifiConnect:false wifiAPname:null elapse:1
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/PMS     (  916): releaseWL(439c0e30): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  916): mActiveDefaultNetwork: -1
D/ConnectivityService(  916): handleInetConditionChange: no active default network - ignore
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,V/Tethering(  916): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/AlarmManager(  916): [AlarmQueuing] connectivity wifi: false
,D/Tethering(  916): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  916): bSetPropertyMultiRAB:false
,D/Tethering(  916): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/PMS     (  916): acquireWL(4306bed0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1616/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.launcher (1303/10076)
I/ConnectivityHelper( 1303): [onReceive] WIFI(1): DISCONNECTED
D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
D/CaptivePortalTracker(  916): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/CaptivePortalTracker(  916): NoActiveNetworkState
,I/NetworkMonitor( 3878): type=WIFI subType= reason=null isConnected=false
,I/Tethering(  916): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  916): ipv4Default null,
I/Tethering(  916): No IPv4 upstream interface, giving up.
D/Tethering(  916): TetherMasterSM: InitialState processMessage what=3
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
,E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1119): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1119): Failed to initiate AP scan
,I/wpa_supplicant( 1119): Failed to initiate AP scan, Failed_to_scan_counter:2
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.google.android.music (3878/10154)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - new mNetworkConnected = false,
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (2981/10021)
,I/ActivityManager(  916): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.vault.service.VaultConnectivityChangeReceiver: pid=4552 uid=10027 gids={50027, 1028, 1015, 3003, 5012}
D/GpsLocationProvider(  916): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  916): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  916): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  916): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  916): releaseWL(4306bed0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/ACRA    ( 4552): ACRA is enabled for com.facebook.katana, intializing...
,D/ACRA    ( 4552): Looking for error files in /data/data/com.facebook.katana/app_acra-reports
,D/ACRA    ( 4552): Looking for error files in /data/data/com.facebook.katana/app_minidumps
,W/SystemClassLoaderAdder( 4552): Could not find zipFile entry corresponding to path /system/priv-app/Facebook_Client.apk
,V/DexLibLoader( 4552): Preparing secondary program dexes.
V/DexLibLoader( 4552): Loaded 4 raw lines of metadata.
V/DexLibLoader( 4552): Secondary program dex metadata: secondary-1.dex.jar ea59162c3d4688c5867ec74b9065721e761155a3 secondary.dex01.Canary
V/DexLibLoader( 4552): Secondary program dex metadata: secondary-2.dex.jar 58ff026e3ba38458e7108c2ff8520807ecf6fd60 secondary.dex02.Canary
V/DexLibLoader( 4552): Secondary program dex metadata: secondary-3.dex.jar 4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6 secondary.dex03.Canary
,V/DexLibLoader( 4552): Secondary program dex metadata: secondary-4.dex.jar 792bc8fa92520ccc1c74299a3ffea523bc10fd3c secondary.dex04.Canary,
,W/DexLibLoader( 4552): Unexpected file in program dex directory: /data/data/com.facebook.katana/app_secondary_program_dex/temp_dex_lock
V/DexLibLoader( 4552): Preparing to extract secondary-1.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-ea59162c3d4688c5867ec74b9065721e761155a3efe4b076.dex.jar
,V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.
V/DexLibLoader( 4552): Creating class loader,
V/DexLibLoader( 4552): Finished creating class loader
V/DexLibLoader( 4552): Preparing to extract secondary-2.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-58ff026e3ba38458e7108c2ff8520807ecf6fd60efe4b076.dex.jar,
V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.,
V/DexLibLoader( 4552): Creating class loader
,V/DexLibLoader( 4552): Finished creating class loader
V/DexLibLoader( 4552): Preparing to extract secondary-3.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-4b26cf545886cdb734ee2f5f7034a7d0fbc12dc6efe4b076.dex.jar
V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.
V/DexLibLoader( 4552): Creating class loader
V/DexLibLoader( 4552): Finished creating class loader
V/DexLibLoader( 4552): Preparing to extract secondary-4.dex.jar to /data/data/com.facebook.katana/app_secondary_program_dex/program-792bc8fa92520ccc1c74299a3ffea523bc10fd3cefe4b076.dex.jar
V/DexLibLoader( 4552): Dex already copied
D/OdexVerifier( 4552): Odex verification is skipped.
,V/DexLibLoader( 4552): Creating class loader
V/DexLibLoader( 4552): Finished creating class loader
,V/DexLibLoader( 4552): Verifying classes from secondary dexes.
,D/DexLibLoader( 4552): DexLibLoader.ensureDexLoaded took 23 ms
,W/dalvikvm( 4552): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;,
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1119): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1119): Failed to initiate AP scan
,I/wpa_supplicant( 1119): Failed to initiate AP scan, Failed_to_scan_counter:3
,W/dalvikvm( 4552): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,W/dalvikvm( 4552): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
,E/FbInjectorInitializer( 4552): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
,D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1119): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Received scan results (4 BSSes)
D/wpa_supplicant( 1119): nl80211: Survey data missing
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1119): Sorted scan results
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-47
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] c2:ff:d4:d3:aa:48 freq=2412 level=-57
I/wpa_supplicant( 1119): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-86
D/wpa_supplicant( 1119): BSS: last_scan_res_used=4/32 last_scan_full=0
D/wpa_supplicant( 1119): Add randomness: count=21 entropy=16
D/wpa_supplicant( 1119): Add randomness: count=22 entropy=17
D/wpa_supplicant( 1119): Add randomness: count=23 entropy=18
D/wpa_supplicant( 1119): Add randomness: count=24 entropy=19
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1119): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1119): wpa_supplicant_pick_network+
I/wpa_supplicant( 1119): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1119): Selecting BSS from priority group 1
I/wpa_supplicant( 1119): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1119): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1119): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1119):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1119): 2: c2:ff:d4:d3:aa:48 ssid='01ABC' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
D/wpa_supplicant( 1119): 3: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1119): No APs found - clear blacklist and try again
E/wpa_supplicant( 1119): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1119): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1119): Selecting BSS from priority group 1
I/wpa_supplicant( 1119): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1119): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1119): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1119): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/wpa_supplicant( 1119):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1119):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-57
I/wpa_supplicant( 1119): Start print parameters
I/wpa_supplicant( 1119): wpa_s->wpa_state is 3
I/wpa_supplicant( 1119): wpa_s->br_have_IP is 0
I/wpa_supplicant( 1119): isConcurrentMode() is 0
I/wpa_supplicant( 1119): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1119): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1119): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1119): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1119): wpa_s->reassociate is 0
I/wpa_supplicant( 1119): wpa_s->is_screen_on 0
I/wpa_supplicant( 1119): wpa_s->ifname wlan0
I/wpa_supplicant( 1119): End print parameters
I/wpa_supplicant( 1119): selected network = 1
D/wpa_supplicant( 1119): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  b,ssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85e34e8  current_ssid=0x0
D/wpa_supplicant( 1119): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1119): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1119): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1119): check if in concurrent case
I/wpa_supplicant( 1119): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/WifiMonitor(  916): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
D/wpa_supplicant( 1119): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1119): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1119): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1119): RSN: PMKSA cache search - network_ctx=0xb85e34e8 try_opportunistic=0
D/wpa_supplicant( 1119): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1119): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1119): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1119): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1119): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1119): nl80211: Unsubscribe mgmt frames handle 0xb85e2718 (mode change)
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1119): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85e2718
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1119):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1119):   * freq=2412
D/wpa_supplicant( 1119):   * Auth Type 0
D/wpa_supplicant( 1119):   * WPA Versions 0x2
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1119): nl80211: Connect request send successfully
D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 1,8
D/WifiNative-wlan0(  916): doBoolean: SET pno 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1119): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  916):    returned false
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  916): doString: LIST_DONGLES
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/WifiNative-wlan0(  916): doString: BSS RANGE=0- MASK=0x21987
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
D/WirelessDisplayService(  916): getDiscoveryDongleList
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1119): reply (489) for get BSS: id=0
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1119): freq=5220
I/wpa_supplicant( 1119): level=-47
I/wpa_supplicant( 1119): tsf=0000000151561482
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG7005g
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=1
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): freq=2412
I/wpa_supplicant( 1119): level=-57
I/wpa_supplicant( 1119): tsf=0000000151561512
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG700
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=2
I/wpa_supplicant( 1119): bssid=c2:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): freq=2412
I/wpa_supplicant( 1119): level=-57
I/wpa_supplicant( 1119): tsf=0000000151561502
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][ESS]
I/wpa_supplicant( 1119): ssid=01ABC
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=3
I/wpa_supplicant( 1119): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1119): freq=2427
I/wpa_supplicant( 1119): level=-86
I/wpa_supplicant( 1119): tsf=0000000151561521
I/wpa_supplicant( 1119): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1119): ssid=Gonzos
I/wpa_supplicant( 1119): ####
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/WifiStateMachine(  916): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -47, frequency: 5220, timestamp: 151561482, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -57, frequency: 2412, timestamp: 151561512, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): == begin of scan result ==
,D/WifiStateMachine(  916): == (4) end of scan result ==
,D/WifiManager( 1253): getScanResults enter 
D/WifiStateMachine(  916): == begin of scan result ==
,D/WifiStateMachine(  916): == (4) end of scan result ==
,D/WirelessDisplayService(  916): getDiscoveryDongleList
D/WifiStateMachine(  916): 2: scan result = SSID: 01ABC, BSSID: c2:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][ESS], level: -57, frequency: 2412, timestamp: 151561502, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 3: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2427, timestamp: 151561521, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): add 4 to mScanResults
D/BatSI   (  916): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  916): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,W/fb4a(:<default>):StaticBindingVerifier( 4552): Verify
,D/WifiService(  916): New client listening to asynchronous messages
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,W/fb4a(:<default>):BaseAnalyticsConfig( 4552): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,W/fb4a(:<default>):BaseAnalyticsConfig( 4552): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 9.509MB for 73240-byte allocation
,I/ActivityManager(  916): Killing 3902:com.htc.musicenhancer/u0a53 (adj 15): empty #17
D/Process (  916): killProcessQuiet, pid=3902
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/AutoSetting( 1388): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/AutoSetting( 1388): Util - no network available!
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
,D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/AutoSetting( 1388): service - mHandler: cancel location update
,D/AutoSetting( 1388): service -           changes count: 0
I/ActivityManager(  916): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4570 uid=10079 gids={50079, 3003, 5012}
,W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 4552): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/MobileConnectivityChangeReceiver( 4570): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4570): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 4570): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4570): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  916): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4584 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
,D/Process (  916): killProcessQuiet, pid=4261
,I/ActivityManager(  916): Killing 4261:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
I/ActivityManager(  916): Recipient 3902
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
I/ActivityManager(  916): Recipient 4261
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  916): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4598 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
,D/Process (  916): killProcessQuiet, pid=4107
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  916): Killing 4107:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
,W/dalvikvm( 4552): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
,I/ActivityManager(  916): Recipient 4107
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 9.955MB for 84664-byte allocation
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
,W/dalvikvm( 4552): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
,W/dalvikvm( 4552): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
,W/dalvikvm( 4552): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
,W/dalvikvm( 4552): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
,D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1119): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1119): nl80211: Connect event
D/wpa_supplicant( 1119): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1119): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1119): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=5
W/GAV2    ( 4598): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/wpa_supplicant( 1119): Add randomness: count=25 entropy=20
I/wpa_supplicant( 1119): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1119): TDLS: Remove peers on association
D/wpa_supplicant( 1119): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1119): EAPOL: enable timer tick
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1119): htc_wext_set_keepalive +
I/wpa_supplicant( 1119): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1119): getPrivFuncNum +	
I/wpa_supplicant( 1119): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1119): State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1119): Get randomness: len=32 entropy=21
D/WifiMonitor(  916): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  916): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  916): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  916): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
D/WifiMonitor(  916): handleAssociatedWithEvent. bLFR =false
D/Tethering(  916): interfaceStatusChanged wlan0, false
,D/WifiMonitor(  916): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/WifiStateMachine(  916): Enter handleAssociatedWithEvent
D/WifiStateMachine(  916): Associated
D/WifiStateMachine(  916): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  916): Exit handleAssociatedWithEvent
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  916): interfaceLinkStateChanged wlan0, true
,D/Tethering(  916): interfaceStatusChanged wlan0, true
,D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
,D/Tethering(  916): [isWifi] getHotspotEnabled: false
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/WifiStateMachine(  916): BSSID was changed, update WiFi database
,D/WifiApDatabaseHandler(  916): updateConnectedAP...
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
I/wpa_supplicant( 1119): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85e29f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1119):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1119): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1119): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f8bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1119):    broadcast key
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 11
D/WifiApDatabaseHandler(  916): updateConnectedAP...
I/wpa_supplicant( 1119): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1119): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1119): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  916): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1119): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/WifiStateMachine(  916): WifiApDatabaseHandler, WiFi AP database Inserting ..
E/wpa_supplicant( 1119): wlan0: Connect to SSID: NG700
,D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1119): set send_ind_to_ndc = 0
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1119): EAPOL: External notification - portValid=1
D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1119): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Authorized
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/wpa_supplicant( 1119): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1119): EAPOL authentication completed successfully
I/wpa_supplicant( 1119): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 79
D/WifiApDatabaseHandler(  916): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
,D/WifiStateMachine(  916): This record is existed, only update it...
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  916): updateConnectedAP...
D/Tethering(  916): interfaceLinkStateChanged wlan0, true
D/Tethering(  916): interfaceStatusChanged wlan0, true
D/Tethering(  916): [isWifi] getHotspotEnabled: false
E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/dalvikvm-heap( 4552): Grow heap (frag case) to 9.969MB for 28144-byte allocation
E/dalvikvm( 4552): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
,W/dalvikvm( 4552): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 4552): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
,W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4598): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/dalvikvm( 4552): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4552): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 4552): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 4552): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 4552): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 4552): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
,D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  916): updateConnectedAP...
,D/WifiStateMachine(  916): fetchFrequency(), freq = 2412
,D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  916): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  916): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  916): This record is existed, only update it...
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  916): updateConnectedAP...
,I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  916): Provision feature enable=false
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/ConnectivityService(  916): mActiveDefaultNetwork: -1
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  916): updateConnectedAP...
D/WISPrService( 3821): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3821): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiNative-wlan0(  916): doBoolean: SET pno 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='0'
,D/WifiNative-wlan0(  916):    returned true
D/DhcpStateMachine(  916): [StoppedState] Start DHCP
,D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
I/dalvikvm-heap( 4552): Grow heap (frag case) to 10.013MB for 39954-byte allocation
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 1
I/wpa_supplicant( 1119): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doString: DRIVER WLS_BATCHING GET
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET",
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1,
D/WifiNative-wlan0(  916):    returned null
E/WifiStateMachine(  916): Unexpected BatchedScanResults :null,
D/WifiNative-wlan0(  916): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd: failed to issue private commands,
D/wpa_supplicant( 1119): nl80211: Event message available
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/wpa_supplicant( 1119): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
,D/wpa_supplicant( 1119): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48
,D/WifiNative-wlan0(  916):    returned null
,D/WifiStateMachine(  916): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  916): acquireWL(43a75268): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 916 1000 null
D/WifiStateMachine(  916): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  916): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42083b90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42083b90 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1164): receive.wifiConnect:false wifiAPname:null elapse:1
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 10.089MB for 79892-byte allocation
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4598/10151)
,V/WebViewChromiumFactoryProvider( 4598): Binding Chromium to main looper Looper (main, tid 1) {41dd0288}
,I/LibraryLoader( 4598): Expected native library version number "",actual native library version number ""
,I/chromium( 4598): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4598): Initializing chromium process, renderers=0
,D/PMS     (  916): acquireWL(4464dd38): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,D/PMS     (  916): acquireWL(428577e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 372 1013 null
,E/AudioManagerAndroid( 4598): BLUETOOTH permission is missing!
D/PMS     (  916): releaseWL(4464dd38): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4598): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4598): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4598): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4598): Local Branch: 
I/Adreno-EGL( 4598): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4598): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4598):                  aa63bbd948f41d15fc72f585e
,I/NSApplication( 4598): Starting up...
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4598/10151)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4598/10151)
,I/ActivityManager(  916): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4635 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,D/Process (  916): killProcessQuiet, pid=4287
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
I/ActivityManager(  916): Killing 4287:com.htc.task/u0a71 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4287
,I/dalvikvm-heap( 4552): Grow heap (frag case) to 10.275MB for 75760-byte allocation
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,W/BroadcastQueue(  916): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{427ad1a0 u0 ReceiverList{427ad080 4552 com.facebook.katana/10027/u0 remote:427accc8}}
,W/BroadcastQueue(  916): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{427ad1a0 u0 ReceiverList{427ad080 4552 com.facebook.katana/10027/u0 remote:427accc8}}
,W/BroadcastQueue(  916): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{440c10a8 u0 ReceiverList{440c1048 4552 com.facebook.katana/10027/u0 remote:43b05260}}
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/PMS     (  916): acquireWL(44180a18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(44180a18): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
,D/PMS     (  916): acquireWL(428cd490): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 4635 10160 null
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
,D/PMS     (  916): acquireWL(43081820): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 4635 10160 null
,D/PMS     (  916): releaseWL(428cd490): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2176): num queued entries: 0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getAllNetworkInfo called by com.test.thalitest (4417/10389)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/PMS     (  916): releaseWL(43081820): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/Process (  916): killProcessQuiet, pid=4330
,I/ActivityManager(  916): Killing 4330:com.htc.mediamanager/u0a34 (adj 15): empty #17
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  916): Recipient 4330
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,I/dalvikvm-heap( 4635): Grow heap (frag case) to 15.209MB for 1821008-byte allocation
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,E/cutils  (  347): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 4552): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
W/Vold    (  347): Returning OperationFailed - no handler for errno 30
,D/wpa_supplicant( 1119): EAPOL: startWhen --> 0
,D/wpa_supplicant( 1119): EAPOL: disable timer tick
,D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  916): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0,
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1119): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  916):    returned true
D/WifiStateMachine(  916): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0,
D/WifiP2pService(  916): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/PMS     (  916): releaseWL(43a75268): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=25 [4][1][0]
D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
,D/WIFI_ICON( 1164): updateWifiState: RSSI_CHANGED -1 -> 3
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
,D/WifiStateMachine(  916): gateway: /192.168.1.1
,D/WifiNative-wlan0(  916): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1119): htc_wext_set_keepalive +
I/wpa_supplicant( 1119): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1119): getPrivFuncNum +	
I/wpa_supplicant( 1119): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1119): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1119): htc_wext_set_keepalive gateway addr = c0a80101
,I/wpa_supplicant( 1119): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  916):    returned true
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  916): VerifyingLinkState enter
D/WifiStateMachine(  916): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  916): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  916): VerifyingLinkState: enableIpv6
D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WifiWatchdogStateMachine(  916): WAN detection
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
D/ConnectivityService(  916): Provision feature enable=false
V/NetworkPolicy(  916): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/ConnectivityService(  916): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  916): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  916): default: teardown()
D/MDST    (  916): default: setTeardownRequested(true)
D/MDST    (  916): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/WISPrService( 3821): >>>>>WISPrService start isConnected = true<<<<<
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/MDST    (  916): default: setTeardownRequested(true)
D/ConnectivityService(  916): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  916): Unexpected mtu value: android.net.wifi.WifiStateTracker@427533a8
,D/ConnectivityService(  916): handleConnectivityChange: netType=1 doReset=false resetMask=0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
I/wpa_supplicant( 1119): Change stage from stage0 to stage3
D/WifiStateMachine(  916): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  916): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  916): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  916): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  916): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  916): handleConnectivityChange: resetting
D/Nat464Xlat(  916): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
D/Nat464Xlat(  916): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  916): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  916): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  916): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  916): acquireWL(4411b338): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
D/WirelessDisplayService(  916): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  916):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/QuickSettingWifi( 1164): receive.wifiConnect:true wifiAPname:NG700 elapse:1
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [1][0][0]
,D/PMS     (  916): acquireWL(4417ad30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
D/PMS     (  916): acquireWL(4307e0f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4417ad30): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1453134176437 min interval config: 0 actual interval: 104256
,I/CheckinService( 2176): Checking schedule, now: 1453134280703 next: 1453134205214
,I/CheckinService( 2176): active receiver: enabled
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1453134172019
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): mActiveDefaultNetwork: WIFI,
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/PMS     (  916): releaseWL(4411b338): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  916): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  916): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  916): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4702 uid=10029 gids={50029, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,W/dalvikvm( 4702): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,W/dalvikvm( 4702): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
I/MultiDex( 4702): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4702): install
,I/MultiDex( 4702): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4702): loading existing secondary dex files
,I/MultiDex( 4702): load found 3 secondary dex files
,I/MultiDex( 4702): install done
,W/dalvikvm( 4702): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
W/dalvikvm( 4702): VFY: unable to resolve instance field 36
,W/dalvikvm( 4702): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4702): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ProviderInstaller( 4702): Installed default security provider GmsCore_OpenSSL
,W/dalvikvm( 4702): VFY: unable to resolve virtual method 141: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,W/dalvikvm( 4702): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,W/dalvikvm( 4702): Link of class 'Lcom/google/android/gms/common/j/c;' failed
E/dalvikvm( 4702): Could not find class 'com.google.android.gms.common.j.c', referenced from method com.google.android.gms.common.j.b.a
W/dalvikvm( 4702): VFY: unable to resolve new-instance 2797 (Lcom/google/android/gms/common/j/c;) in Lcom/google/android/gms/common/j/b;
,W/dalvikvm( 4702): VFY: unable to resolve virtual method 274: Landroid/content/Context;.checkSelfPermission (Ljava/lang/String;)I
,W/dalvikvm( 4702): Link of class 'Lcom/google/android/gms/common/j/c;' failed
,D/LocationInitializer( 2176): Restart initialization of location
,D/WearableService( 1253): callingUid 10029, callindPid: 1253
,E/MDM     ( 1253): [118] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/GCoreFlp( 1253): No location to return for getLastLocation()
,W/FusedLocationProvider( 1253): location=null
D/PMS     (  916): acquireWL(4464d760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(4464d760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,I/WVCdm   (  372): Level3 Library Nov 20 2013 18:09:31
,D/AuthorizationBluetoothService( 1400): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1400): Proximity feature is not enabled.
,W/WVCdm   (  372): Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils( 4702): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  372): PrepareKeyRequest: nonce=1252052693
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/PMS     (  916): releaseWL(4279a460): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  916): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  916): [AlarmQueuing] connectivity wifi: true
,V/Tethering(  916): mTetherableUsbRegexs:{(usb0)(ncm0)}
D/GpsLocationProvider(  916): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  916): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  916): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  916): ignore wifi update if we are not in OPENING or CLOSING
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/CaptivePortalTracker(  916): NoActiveNetworkState
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/PMS     (  916): acquireWL(44618928): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/PMS     (  916): releaseWL(44618928): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.google.android.music (3878/10154)
I/wpa_supplicant( 1119): environment dirty rate=0 [2][0][0]
D/AccTypeManager( 1371): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,I/NetworkMonitor( 3878): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1616/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
,D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.launcher (1303/10076)
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,I/ConnectivityHelper( 1303): [onReceive] WIFI(1): CONNECTED
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,V/Tethering(  916): bSetPropertyMultiRAB:false
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(445df430): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/Tethering(  916): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
W/AccTypeManager( 1371): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1371): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
I/Tethering(  916): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  916): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,I/Tethering(  916): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  916): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  916): Found interface wlan0
D/Tethering(  916): TetherMasterSM: InitialState processMessage what=3
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(445df430): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1616/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (2981/10021)
,E/ExternalAccountType( 1371): Unsupported attribute readOnly
,D/AutoSetting( 1388): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4570): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4570): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
,D/AutoSetting( 1388): service - onStartCommand() screen is off, don't request location
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
,D/AutoSetting( 1388): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1388): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4598/10151)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
,D/PMS     (  916): acquireWL(42771918): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1453134176437 min interval config: 0 actual interval: 105356
D/PMS     (  916): releaseWL(42771918): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/iu.UploadsManager( 2176): num queued entries: 0
I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getAllNetworkInfo called by com.test.thalitest (4417/10389)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/PMS     (  916): acquireWL(426c9b78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1400): [NET] getaddrinfo-,err=8
D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1400): [NET] getaddrinfo-, 1
,D/libc    ( 1400): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =1ff +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 189
D/libc    (  364): [NET]res_nsend:resplen=79
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1400): [NET] getaddrinfo_proxy-, success
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1400): [NET] getaddrinfo-,err=8
,W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):UserScope( 4552): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=16 [6][1][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,W/Settings( 4702): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (4702/10029)
,D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1400): [NET] getaddrinfo-,err=8
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/PMS     (  916): releaseWL(428577e0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/Adreno-EGL( 4702): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4702): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4702): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4702): Local Branch: 
I/Adreno-EGL( 4702): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4702): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4702):                  aa63bbd948f41d15fc72f585e
,D/PMS     (  916): acquireWL(431c5d88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/PMS     (  916): releaseWL(426c9b78): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1400/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  916): handleInetConditionChange: starting a change hold
,D/PMS     (  916): releaseWL(431c5d88): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(44136878): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1400/10029)
,D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  916): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1400/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,I/Adreno-EGL( 4702): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4702): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4702): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4702): Local Branch: 
I/Adreno-EGL( 4702): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4702): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4702):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  916): handleInetConditionChange: currently in hold - not setting new end evt
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
E/fb4a(:<default>):LocalFbBroadcastManager( 4552): Called registerBroadcastReceiver twice.
,D/PMS     (  916): releaseWL(44136878): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/Adreno-EGL( 4702): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4702): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4702): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4702): Local Branch: 
I/Adreno-EGL( 4702): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4702): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4702):                  aa63bbd948f41d15fc72f585e
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/GpsLocationProvider(  916): ALARM_XTRA_TIMEOUT
D/GpsLocationProvider(  916): [handleMessage] DOWNLOAD_XTRA_DATA
,D/GpsLocationProvider(  916): [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
D/PMS     (  916): acquireWL(43a44b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
V/AlarmManager(  916): sending alarm PendingIntent{4286bbc0: PendingIntentRecord{4286d728 android broadcastIntent}}, i=com.htc.location.XTRA_ALARM_TIMEOUT, t=3, cnt=1, w=155404, Int=0
D/PMS     (  916): acquireWL(445e7710): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/PMS     (  916): releaseWL(43a44b00): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/libc    (  916): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-,err=8
D/libc    (  916): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  916): [NET] getaddrinfo-, 1
D/libc    (  916): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 23(0x78747261706174),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =c82c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=3556026974
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 59
D/libc    (  364): [NET]res_nsend:resplen=243
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=10
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo_proxy-, success
I/global  (  916): call createSocket() return a new socket.
D/libc    (  916): [NET] getaddrinfo+,hn 12(0x35342e3233392e),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/GpsLocationProvider(  916): [handleDownloadXtraData] calling native_inject_xtra_data
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =183e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/WifiStateMachine(  916): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  916): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
D/ConnectivityService(  916): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=28 [35][10][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 256
D/libc    (  364): [NET]res_nsend:resplen=84
D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/GpsLocationProvider(  916): [reportHTCStatus] eventMask = 3 , status = 0
,D/GpsLocationProvider(  916): [reportHTCStatus] INJECT_XTRA_DATA, status: 0
,D/GpsLocationProvider(  916):  [handleDownloadXtraData]inject done.
,D/GpsLocationProvider(  916): [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,I/CheckinTask( 2176): Sending checkin request (12462 bytes)
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  916): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  916): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=21 [19][4][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2176): Checking schedule, now: 1453134283516 next: 1453657220510
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,I/CheckinService( 2176): Checking schedule, now: 1453134283547 next: 1453657220510
,I/CheckinService( 2176): active receiver: disabled
,I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1453134283554
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(4307e0f8): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/libc    (  916): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-,err=8
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  916): [NET] getaddrinfo-, 1
,D/libc    (  916): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =647e +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/GCM     ( 1400): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  916): Find DNS Address www.htc.com/104.81.130.175
,I/GAV2    ( 4598): Thread[GAThread,5,main]: No campaign data found.
,D/PMS     (  916): acquireWL(43a55a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10029 com.google.android.gms}
,V/AlarmManager(  916): sending alarm PendingIntent{41dd7e10: PendingIntentRecord{427aa668 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.SEND_IDLE, t=2, cnt=1, w=157421, Int=0
,V/AlarmManager(  916): sending alarm PendingIntent{440d6bc0: PendingIntentRecord{42890918 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1453134282364, Int=1800000
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/PMS     (  916): acquireWL(445c6f38): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(43a55a30): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(44599328): PARTIAL_WAKE_LOCK  Event Log Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(445c6f38): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/EventLogService( 2176): Aggregate from 1453134280740 (log), 1453132482307 (data)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/PMS     (  916): releaseWL(44599328): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(445e7710): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,D/Process (  916): killProcessQuiet, pid=4350
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4350:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4350
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  916): Client connection lost with reason: 4
,I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1371): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "sms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "smsto"
,I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,I/ActivityManager(  916): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.phone.PackageReplacedReceiver: pid=4759 uid=10111 gids={50111, 3003, 5012, 1028, 1015, 3002}
,W/Prism.AllAppsManager( 1303): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,I/Launcher( 1303): Deferring update until onResume
,D/Launcher( 1303): waitUntilResume // bindAppsUpdated
,W/AccTypeManager( 1371): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1371): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,W/SystemReader( 1286): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "sms"
,I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,E/ExternalAccountType( 1371): Unsupported attribute readOnly
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,D/PhoneApp( 1270): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,I/Babel   ( 4759): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4759): MmsConfig.loadMmsSettings
,W/dalvikvm( 4759): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,W/dalvikvm( 4759): VFY: unable to resolve instance field 36
,W/dalvikvm( 4759): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,V/JNIHelp ( 4759): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  916): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.MmsCustomizationProvider: pid=4782 uid=10065 gids={50065, 3003, 5012, 1028, 1015, 1023}
,W/PackageManager(  916): Unable to load service info ResolveInfo{43a55460 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  916): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  916): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  916): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  916): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  916): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  916): 	at dalvik.system.NativeStart.main(Native Method)
,D/MessageFrequencyProvider( 4782): onCreate
,V/GetPrviateResource( 4782): GetPrviateResource
V/GetPrviateResource( 4782): GetPrviateResource
,D/MmsCustomizationProvider( 4782): query uri: content://htc-mms-customization/mms-ua/ua_string
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.phone.ShareIntentSmsOnlyActivity, state=2, flag=1, pid=4759, uid=10111, userID:0
,D/MmsCustomizationProvider( 4782): query uri: content://htc-mms-customization/mms-ua/ua_profile
,W/Settings( 4759): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel   ( 4759): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
,I/Babel   ( 4759): MmsConfig.loadFromDatabase
,E/Babel   ( 4759): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4759): MmsConfig.loadFromResources
,E/Babel   ( 4759): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4759): MmsConfig.loadMmsSettings: mUserAgent=HTC_Desire_820/1.0, mUaProfUrl=http://www.htcmms.com.tw/Android/Common/GC0znJc20B/ua-profile.xml
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.SmsReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.MmsWapPushReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortSmsReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.sms.AbortMmsWapPushReceiver, state=2, flag=1, pid=4759, uid=10111, userID:0
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.talk, clsName=com.google.android.apps.babel.service.NoConfirmationSmsSendService, state=1, flag=1, pid=4759, uid=10111, userID:0
D/PMS     (  916): acquireWL(44172d00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4759 10111 null
,I/[PluginManager]RegisterService( 1388): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1388): handle notify Blinkfeed plugin client changed
,I/IcingCorporaProvider( 3111): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ProviderInstaller( 4759): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  916): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(429d7ac0): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,D/MessageCustFlag( 4782): sense_version=6.0
,D/BTAccessoryUtil( 4782): createReceiver
,D/BTAccessoryUtil( 4782): registerReceiver return intent = null
D/MessageCustFlag( 4782): sku_id=99
,W/SystemReader( 4782): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  916): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
D/Messaging( 4782): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4782): networkCode: 
,D/MessageCustFlag( 4782): sku_id=99
D/MmsConfig( 4782): SIE smsPri: null
,D/MmsConfig( 4782): networkCode: 
D/PMS     (  916): acquireWL(43a3ab20): PARTIAL_WAKE_LOCK  AsyncService 0x1 4635 10160 null
D/PMS     (  916): releaseWL(44172d00): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
D/HtcTelephonyCapability( 4782): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 4782): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4782): getRATByHtcTelephonyCapability:1
,W/SystemReader( 4782): Cannot find qct_8960_interface, use default value instead
D/PMS     (  916): releaseWL(43a3ab20): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/ActivityManager(  916): Resuming delayed broadcast
,D/Process (  916): killProcessQuiet, pid=4371
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  916): Killing 4371:com.htc.calendar/u0a13 (adj 15): empty #17
,D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  916): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
I/ActivityManager(  916): Recipient 4371
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  916): Resuming delayed broadcast
,D/RemoteDisplayProvider(  916): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  916): start
,I/GCoreNlp( 1253): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  916): applying state to connected service
,D/PMS     (  916): acquireWL(441570e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(441570e0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/LocationProviderProxy(  916): applying state to connected service
,D/PMS     (  916): acquireWL(4476d030): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(4476d030): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(44092b00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(44092b00): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,I/IcingCorporaProvider( 3111): UpdateCorporaTask done [took 476 ms] updated apps [took 476 ms] 
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  916): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PMS     (  916): acquireWL(4465a0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{10027}
,V/AlarmManager(  916): sending alarm PendingIntent{42674c68: PendingIntentRecord{4275aed8 com.facebook.katana broadcastIntent}}, i=com.facebook.common.executors.WakingExecutorService.ACTION_ALARM.com.facebook.katana, t=2, cnt=1, w=165341, Int=0
,D/PMS     (  916): releaseWL(4465a0b8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{10027}
,I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1303): loadItems() com.htc.launcher.pageview.WidgetManager@41e5ee78 +
,I/Prism.WidgetManager( 1303): onLoadItems() +
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,D/PMS     (  916): releaseWL(429d7ac0): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,E/Prism.WidgetManager( 1303): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1303): onLoadItems() -
,I/Prism.ItemManager( 1303): loadItems() com.htc.launcher.pageview.WidgetManager@41e5ee78 -
,D/PhoneApp( 1270): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1270): -- N1 =0
,D/PhoneApp( 1270): -- N2 =0
,D/PhoneApp( 1270): -- N3 =0
,D/Messaging( 4782): mNeedToUpdateDate2 start
,D/MmsConfig( 4782): packageName: com.htc.vvm.att does not exist
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/ReportIndicatorCache( 4782): startAsyncQueryReports ---
,D/MmsSmsV2Provider( 1270):  phoneType = -1
D/MmsSmsV2Provider( 1270): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
D/MmsAsyncWorkHandler( 4782): 
D/MmsAsyncWorkHandler( 4782): HM tk = 20001
D/ReportIndicatorCache( 4782): MSG_QUERY_REPORTS >>
,D/SettingsManager( 4782): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41ddd320
,I/Messaging( 4782): mccmnc> 
D/DraftCache( 4782): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 4782): [DraftCache/1] refresh
,D/MmsConfig( 4782): networkCode: 
,D/Messaging( 4782): ViewCache CreatePreloadOnlyConversationList
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/AccFlag ( 1270): sku_id=99
,D/PhoneStorageUtil( 4782): HtcWrapEnvironment.getSupportedStorages() >1
D/MessageCustFlag( 4782): sense_version=6.0
D/PhoneStorageUtil( 4782): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 4782): createReceiver
,D/Jerry   ( 4782): start to preload cursor >>>>>>>
D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
D/MmsSmsV2Provider( 1270):  phoneType = -1
,D/MmsSmsV2Provider( 1270): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/DraftCache( 4782): [DraftCache/475] rebuildCache
,D/Messaging( 4782): mNeedToUpdateDate2: false
D/TelephUtils( 1270): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 56
D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
D/MmsSmsV2Provider( 1270):  phoneType = -1
V/MmsProvider( 1270): Update uri=content://mms, match=0
D/MmsSmsV2Provider( 1270): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,V/MmsProvider( 1270): selection=st=129 AND m_type!=134
,D/Messaging( 4782): Reset downloading state: 0
,V/MmsSystemEventReceiver( 4782): TransactionService is going to be woken up.
,V/TransactionService( 4782): 1-Creating TransactionService
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 29
,D/MmsSmsV2Provider( 1270):  phoneType = -1
V/TransactionService( 4782): onStartCommand: 1
,D/MmsSystemEventReceiver( 4782): unRegisterForConnectionStateChanges
V/TransactionService( 4782): 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 4782): Loading previous transactions.
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
,D/Jerry   ( 1270): URI_DRAFT
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 28
,D/AccFlag ( 1270): device_type: 1
D/DraftCache( 4782): hasDraft() = false mNeedNotifyChange = true
,D/DraftCache( 4782): [DraftCache/475] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 4782): 
D/MmsAsyncWorkHandler( 4782): HM tk = 20002
,D/Messaging( 4782): ViewCache CreatePreload
,D/Messaging( 4782): ViewCache CreatePreloadOnlyMultipleOpsList
,D/TransactionService( 4782): Force set service start id to 1
V/TransactionService( 4782): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 4782): unRegisterForConnectionStateChanges
,D/Cust_MMSMS( 4782): _has_set_default_values_2=true
,V/TransactionService( 4782): Destroying TransactionService
,D/TransactionService( 4782): stopSelfResult: true, mLastHandledServiceId: 1
,V/TransactionService( 4782): 4-Handling incoming message: { when=-4ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,D/MsgPreferenceUtils( 4782): def_index: 0
,D/MsgPreferenceUtils( 4782): globalIndex = 1
D/MsgPreferenceUtils( 4782): phone state: true
D/MsgPreferenceUtils( 4782): sd state: false
,D/MsgPreferenceUtils( 4782): vIndex = 0
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 56
,D/MmsSmsV2Provider( 1270):  phoneType = -1
,D/MmsSmsV2Provider( 1270): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/Messaging( 4782): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 55
,D/AccFlag ( 1270): sku_id=99
,D/TelephUtils( 1270): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 56
,D/AccFlag ( 1270): sku_id=99
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 com.android.server.DeviceStorageMonitorService.cancelSmsStorageNotification:732 com.android.server.DeviceStorageMonitorService.checkAvailableSmsMemory:426 com.android.server.DeviceStorageMonitorService.checkMemory:398 com.android.server.DeviceStorageMonitorService.access$000:96 
,I/GAV4    ( 4759): Thread[GAThread,5,main]: No campaign data found.
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(44651ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=173208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(44651ea0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1388): service - mHandler: update timezone
,D/AutoSetting( 1568): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,D/AutoSetting( 1568): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1568): service - onCreate()
,W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1568): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1568): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
V/NotificationService(  916): batLight: Full, plugged
V/LightsService(  916): setLight #8: color=#c8c800
,D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
D/AutoSetting( 1568): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1568): service - onStartCommand() handle command from HSP: processTimeZoneID
,D/AutoSetting( 1568): service - mHandler: update timezone
,D/DotMatrix( 1605): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/LightsService(  916): setLight #8: color=#c800
D/qdlights(  916): set_color_led color=51200, mode=1, off_min=0, off_sec=0,
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
,D/AutoSetting( 1568): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1568): service - processTimeZoneID() system nitz is valid: false (false)
,D/AutoSetting( 1388): service - handleMessage() stop self
,D/AutoSetting( 1568): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1568): service - showManualTimeZoneSelector() send notification (single)
,D/AutoSetting( 1388): service - handleMessage() quit looper
D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,D/AutoSetting( 1388): service - onDestroy() END
,I/RemoteViews( 1164): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1164): release indeterminate drawable android.widget.OnDemandProgressBar{41e5c8f0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1164): com.htc.htclocationservice 2 7 3 11
,D/TelephonyReceiver( 1270): switchBindHtcMsgCursor: null
,D/Process (  916): killProcessQuiet, pid=4385
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4385:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4385
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): acquireWL(4459f0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): releaseWL(4459f0d0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  916): updateBatteryInfo
D/PowerUI ( 1164): closing low battery warning: level=100
D/PowerUI ( 1164): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
,I/HtcPowerSaver(  916): >> updateStatus
,I/IntentController( 1164): receive(android.intent.action.BATTERY_CHANGED,1,false)
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1164): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(445562b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(445562b0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/ContactMessageStore( 1270): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1270): MSG_NOTIFY_CS_TO_SYNC <<
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{44653118 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1568): service - handleMessage() stop self
,D/AutoSetting( 1568): service - onDestroy() END
,D/AutoSetting( 1568): service - handleMessage() quit looper
,I/ActivityManager(  916): Killing 4013:com.google.android.gm/u0a107 (adj 15): empty #17
D/Process (  916): killProcessQuiet, pid=4013
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  916): Recipient 4013
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ClearcutLoggerApiImpl( 1400): disconnect managed GoogleApiClient
,D/PMS     (  916): acquireWL(445459b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=233208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(445459b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(4452a3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(4452a3c8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(4451d380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=293209, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4451d380): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(44512b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44512b10): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  916): acquireWL(445125e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=353208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(445125e8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(44510a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44510a18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(444e1618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=413209, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(444e1618): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(44250140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44250140): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 1
,D/PMS     (  916): acquireWL(44250050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=473208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(44250050): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 2
,D/PMS     (  916): acquireWL(441b1278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(441b1278): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(441b0ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,I/IntentController( 1164): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): releaseWL(441b0ca0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1164): closing low battery warning: level=100
D/PowerUI ( 1164): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1164): status:5 level:100 unsupport:false plugged:true
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 3
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 4
,D/PMS     (  916): acquireWL(440c2cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=533209, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(440c2cf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,W/Atfwd_Sendcmd(  414): AtCmdFwd service not published, waiting... retryCnt : 5
,D/PMS     (  916): acquireWL(440c06e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(440c06e8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(440ac960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=593208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(440ac960): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(440ab0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(440ab0f0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/ContactMessageStore( 1270): MSG_CHECK_DELETION >>
,D/ContactMessageStore( 1270): mDeleteTask = null, bDeleting = false
D/AccFlag ( 1270): sku_id=99
,D/ContactMessageStore( 1270): MSG_CHECK_DELETION <<
,D/ContactMessageStore( 1270): start background delete task...
D/ContactMessageStore( 1270): size: 0 , 0
,D/ContactMessageStore( 1270): Background delete complete
,D/PMS     (  916): acquireWL(440a8ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=653209, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(440a8ab8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/Process (  916): killProcessQuiet, pid=4481
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4481:com.htc.mms.backupagent/u0a78 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4481
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): acquireWL(43e42fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43e42fe8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4383a0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=713208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4383a0f8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(42919b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(42919b88): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4278e4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=773209, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4278e4b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(426700b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(426700b8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(41de2770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=833208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(41de2770): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(4232ae78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(4232ae78): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4203e728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=893208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4203e728): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(427a7e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(427a7e00): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=1 ifi_flags=0x1003 ([UP])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 48 (NL80211_CMD_DISCONNECT) received for wlan0
D/wpa_supplicant( 1119): nl80211: Disconnect event
I/wpa_supplicant( 1119): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,I/wpa_supplicant( 1119): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
I/wpa_supplicant( 1119): Added BSSID c0:ff:d4:d3:aa:48 into blacklist
D/wpa_supplicant( 1119): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1119): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb85e1bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1119):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1119): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1119): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=0 ifi_flags=0x1043 ([UP][RUNNING])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 1119): Wireless event: cmd=0x8b15 len=20
,D/HTCRequest(  916): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
,D/Tethering(  916): interfaceStatusChanged wlan0, false
D/HTCRequest(  916): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/HTCRequest(  916): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
,D/Tethering(  916): interfaceStatusChanged wlan0, false
D/HTCRequest(  916): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/Tethering(  916): [isWifi] getHotspotEnabled: false
,D/HTCRequest(  916): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getReasonFromEventString() 0
,D/HTCRequest(  916): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
,D/HTCRequest(  916): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=0 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFreqFromEventString() 2412
D/WifiMonitor(  916): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
,D/WifiStateMachine(  916): Enter handleNetworkDisconnect
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
,D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
,D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 0
I/wpa_supplicant( 1119): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
,D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  916):    returned true
D/WifiP2pService(  916): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/DhcpStateMachine(  916): [RunningState] Stop DHCP
,D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  916): Exit handleNetworkDisconnect
D/WifiPerfLock(  916): release()
,D/WifiStateMachine(  916): PerfLock released for exiting ConnectedState
,D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
D/ConnectivityService(  916): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
,D/PMS     (  916): acquireWL(427ea590): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 916 1000 null
D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  916): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiDataStallTracker(  916): stopDataStallAlarm: current tag=22417 mDataStallAlarmIntent=null
D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 0
I/wpa_supplicant( 1119): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61
,D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
D/UsbnetStateTracker(  916): isAvailable+-
D/UsbnetStateTracker(  916): reconnect
D/UsbnetStateTracker(  916): isAvailable+-
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
,D/WifiNative-wlan0(  916):    returned true
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  916): Provision feature enable=false
D/ConnectivityService(  916): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/PMS     (  916): acquireWL(434169d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED disconnected
V/AlarmManager(  916): sending alarm PendingIntent{420a2510: PendingIntentRecord{4275db60 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=792616, Int=0
D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  916): default: reconnect()
D/MDST    (  916): default: setTeardownRequested(false)
D/MDST    (  916): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  916): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/WifiP2pService(  916): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  916): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  916): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  916): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '53 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 53 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  916): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/ActivityManager(  916): Start proc com.htc.aurora for service com.htc.aurora/.bi.SendLogService: pid=4850 uid=10049 gids={50049, 3003, 5012, 1028, 1015, 2001}
V/AlarmManager(  916): sending alarm PendingIntent{42956b08: PendingIntentRecord{426ba068 com.htc.aurora startService}}, i=null, t=1, cnt=1, w=1453134357622, Int=10800000
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  916): doBoolean: SET pno 1
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='1'
,V/NativeCrypto( 1400): Read error: ssl=0x63fb6960: I/O error during system call, Connection timed out
D/PMS     (  916): releaseWL(434169d8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '54 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 54 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  916): Exception trying to remove a route: java.lang.IllegalStateException: command '55 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 55 Failed to remove route from default table (No such process)'
D/ConnectivityService(  916): handleConnectivityChange: resetting
D/ConnectivityService(  916): resetConnections(wlan0, 3)
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WISPrService( 3821): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3821): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 75
D/wpa_supplicant( 1119): nl80211: Sched scan requested (ret=0) - scan interval 75000 msec
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 75 (NL80211_CMD_START_SCHED_SCAN) received for wlan0
D/libc    (  364): [NET] entry_id:1   entry:0xb82e7418  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb82e70b8  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb82e72f0  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb82e7838  removed 
,D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
,D/WifiNative-wlan0(  916):    returned true
D/ConnectivityService(  916): flush DNS cache for net 1(wlan0)
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=DISCONNECTED
,V/NativeCrypto( 1400): SSL shutdown failed: ssl=0x63fb6960: I/O error during system call, Broken pipe
,I/QuickSettingWifi( 1164): receive.wifiConnect:false wifiAPname:null elapse:1
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): State: DISCONNECTED -> SCANNING
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 33
I/wpa_supplicant( 1119): Scan req (ret=0) - timeout 30 secs
D/wpa_supplicant( 1119): nl80211: Event message available
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1119): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSID
,D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =DISCONNECTED newSupplicantState =SCANNING
D/PMS     (  916): acquireWL(427599e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
D/Nat464Xlat(  916): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  916): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
D/ConnectivityService(  916): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
,D/WISPrService( 3821): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3821): wifi connected:falsemWifiInfo:SSID: , BSSID: 00:00:00:00:00:00, Supplicant state: SCANNING, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=SCANNING
D/PMS     (  916): acquireWL(43091398): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  916): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/WirelessDisplayService(  916): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
,D/WirelessDisplayService(  916): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,D/WifiStateMachine(  916): startScan Pid: 916 Uid 1000
D/WifiNative-wlan0(  916): doBoolean: SET pno 0
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='0'
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 76
D/wpa_supplicant( 1119): nl80211: Sched scan stop sent (ret=0)
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 78 (NL80211_CMD_SCHED_SCAN_STOPPED) received for wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: SCAN
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SCAN"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1119): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1119): Failed to initiate AP scan
,I/wpa_supplicant( 1119): Failed to initiate AP scan, Failed_to_scan_counter:1
I//system/bin/ip(  364): RTNETLINK answers: No such process
D/WifiNative-wlan0(  916):    returned true
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  916): reportInetCondition for net -1, percentage: 0 by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/BatSI   (  916): WIFI scan started for: 450a0300 uid:1000
,I/QuickSettingWifi( 1164): receive.wifiConnect:false wifiAPname:null elapse:1
D/PMS     (  916): releaseWL(427599e0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/PMS     (  916): releaseWL(43091398): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/ConnectivityService(  916): mActiveDefaultNetwork: -1
,D/ConnectivityService(  916): Sampling interval elapsed, updating statistics ..
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.aurora (4850/10049)
D/ConnectivityService(  916): Done.
,D/ConnectivityService(  916): Setting timer for 720seconds
,D/ConnectivityService(  916): handleInetConditionChange: no active default network - ignore
,D/Process (  916): killProcessQuiet, pid=4503
,D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  916): Killing 4503:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  916): Recipient 4503
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  916): Client connection lost with reason: 4
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,V/Tethering(  916): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/AlarmManager(  916): [AlarmQueuing] connectivity wifi: false
D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
D/Tethering(  916): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
D/CaptivePortalTracker(  916): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
V/Tethering(  916): bSetPropertyMultiRAB:false
D/CaptivePortalTracker(  916): NoActiveNetworkState
,D/Tethering(  916): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  916): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  916): ipv4Default null
,I/Tethering(  916): No IPv4 upstream interface, giving up.
D/Tethering(  916): TetherMasterSM: InitialState processMessage what=3
D/GpsLocationProvider(  916): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  916): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  916): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  916): ignore wifi update if we are not in OPENING or CLOSING
,I/ConnectivityHelper( 1303): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(42922998): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
D/PMS     (  916): releaseWL(42922998): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.launcher (1303/10076)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,I/NetworkMonitor( 3878): type=WIFI subType= reason=null isConnected=false
I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1119): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1119): Failed to initiate AP scan
,I/wpa_supplicant( 1119): Failed to initiate AP scan, Failed_to_scan_counter:2
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1616/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.google.android.music (3878/10154)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (2981/10021)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
,D/AutoSetting( 1388): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4570): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
,D/MobileConnectivityChangeReceiver( 4570): onReceive CONNECTIVITY_CHANGE networkType=1
,D/AutoSetting( 1388): Util - no network available!
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4598/10151)
D/AutoSetting( 1388): service - onCreate()
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
,D/AutoSetting( 1388): service - AddressCache: using context: com.htc.Weather
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.cancellocationupdate
D/LocationManagerService(  916): request 42745540 passive Request[POWER_NONE passive fastest=+5s0ms] from com.htc.sense.hsp(10055)
D/LocationManagerService(  916): provider request: passive ProviderRequest[ON interval=0]
D/AutoSetting( 1388): service - mHandler: cancel location update
,D/AutoSetting( 1388): service -           changes count: 0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 2176): num queued entries: 0
,I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getAllNetworkInfo called by com.test.thalitest (4417/10389)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,I/wpa_supplicant( 1119): wpa_supplicant_scan enter
I/wpa_supplicant( 1119): ap_scan=1 , scan_req =2
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan +
E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 33
D/wpa_supplicant( 1119): nl80211: Scan trigger failed: ret=-16 (Device or resource busy)
I/wpa_supplicant( 1119): wpa_supplicant_trigger_scan -
W/wpa_supplicant( 1119): Failed to initiate AP scan
,I/wpa_supplicant( 1119): Failed to initiate AP scan, Failed_to_scan_counter:3,
,D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
I/wpa_supplicant( 1119): Got an original EVENT_SCAN_RESULTS
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Received scan results (3 BSSes)
D/wpa_supplicant( 1119): nl80211: Survey data missing
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
D/wpa_supplicant( 1119): Sorted scan results
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:4a freq=5220 level=-46
I/wpa_supplicant( 1119): [NULL] c0:ff:d4:d3:aa:48 freq=2412 level=-58
I/wpa_supplicant( 1119): [NULL] 38:f8:89:11:e9:11 freq=2427 level=-86
D/wpa_supplicant( 1119): BSS: last_scan_res_used=3/32 last_scan_full=0
D/wpa_supplicant( 1119): Add randomness: count=26 entropy=0
D/wpa_supplicant( 1119): Add randomness: count=27 entropy=1
D/wpa_supplicant( 1119): Add randomness: count=28 entropy=2
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 1119): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 1119): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=1
I/wpa_supplicant( 1119): wpa_supplicant_pick_network+
I/wpa_supplicant( 1119): blist: c0:ff:d4:d3:aa:48 count[1]
I/wpa_supplicant( 1119): Selecting BSS from priority group 1
I/wpa_supplicant( 1119): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1119): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1119): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
I/wpa_supplicant( 1119):    skip - blacklisted (count=1 limit=0)
D/wpa_supplicant( 1119): 2: 38:f8:89:11:e9:11 ssid='Gonzos' wpa_ie_len=26 rsn_ie_len=24 wapi_ie_len=0 caps=0x411
I/wpa_supplicant( 1119): No APs found - clear blacklist and try again
E/wpa_supplicant( 1119): wlan0: BLACKLIST CLEAR 
D/wpa_supplicant( 1119): Removed BSSID c0:ff:d4:d3:aa:48 from blacklist (clear)
I/wpa_supplicant( 1119): Selecting BSS from priority group 1
I/wpa_supplicant( 1119): Recent assoc_freq = 0 rssi = 0
D/wpa_supplicant( 1119): 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x511
D/wpa_supplicant( 1119): 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 wapi_ie_len=0 caps=0x431
W/wpa_supplicant( 1119): [EAP-MSG] EAP wpa_supplicant_check_sim@646: eap_methods not available
D/WifiNative-wlan0(  916): doBoolean: SET pno 1
D/wpa_supplicant( 1119):    selected WPA/WAPI AP c0:ff:d4:d3:aa:48 ssid='NG700'
I/wpa_supplicant( 1119):    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412 rssi=-58
I/wpa_supplicant( 1119): Start print parameters
I/wpa_supplicant( 1119): wpa_s->wpa_state is 3
I/wpa_supplicant( 1119): wpa_s->br_have_IP is 0
D/WifiMonitor(  916): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
I/wpa_supplicant( 1119): isConcurrentMode() is 0
I/wpa_supplicant( 1119): wpa_s->br_mirror_status is 0
I/wpa_supplicant( 1119): wpa_s->br_p2p_connected is 0
I/wpa_supplicant( 1119): wpa_s->bt_a2dp_status is 0
I/wpa_supplicant( 1119): wpa_s->bt_sco_status is 0
I/wpa_supplicant( 1119): wpa_s->reassociate is 0
I/wpa_supplicant( 1119): wpa_s->is_screen_on 0
I/wpa_supplicant( 1119): wpa_s->ifname wlan0
I/wpa_supplicant( 1119): End print parameters
I/wpa_supplicant( 1119): selected network = 5
D/wpa_supplicant( 1119): wlan0: Considering connect request: reassociate: 0  selected: c0:ff,:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb85e34e8  current_ssid=0x0
D/wpa_supplicant( 1119): wlan0: Request association with c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): supplicant attached completed, trigger assoc.
D/wpa_supplicant( 1119): wpa_supplicant_set_is_wep_security: 0
D/wpa_supplicant( 1119): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 1119): check if in concurrent case
I/wpa_supplicant( 1119): wlan0: Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1"
D/wpa_supplicant( 1119): wpa_supplicant_associate, 1777
D/wpa_supplicant( 1119): wpa_supplicant_associate, 1780
D/wpa_supplicant( 1119): wpa_supplicant_associate, 1795
D/wpa_supplicant( 1119): RSN: PMKSA cache search - network_ctx=0xb85e34e8 try_opportunistic=0
,D/wpa_supplicant( 1119): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1119): RSN: No PMKSA cache entry found
I/wpa_supplicant( 1119): State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1119): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 1119): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 6
,D/wpa_supplicant( 1119): nl80211: Unsubscribe mgmt frames handle 0xb85e2718 (mode change)
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
D/wpa_supplicant( 1119): nl80211: Subscribe to mgmt frames with non-AP handle 0xb85e2718
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSID
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
,D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =SCANNING newSupplicantState =ASSOCIATING
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Register frame type=0xd0 nl_handle=0xb85e2718
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 58
D/wpa_supplicant( 1119): nl80211: Connect (ifindex=22)
D/wpa_supplicant( 1119):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 1119):   * freq=2412
D/wpa_supplicant( 1119):   * Auth Type 0
D/wpa_supplicant( 1119):   * WPA Versions 0x2
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 46
D/wpa_supplicant( 1119): nl80211: Connect request send successfully
D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - EAP fail=0
,D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='1'
E/wpa_supplicant( 1119): send_and_recv error -16 - cmd 75
D/wpa_supplicant( 1119): nl80211: Sched scan start failed: ret=-16 (Device or resource busy)
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 1" Return -1
D/WifiNative-wlan0(  916):    returned false
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent SupplicantStartedState
D/WifiNative-wlan0(  916): doString: LIST_DONGLES
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 LIST_DONGLES"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/WifiNative-wlan0(  916): doString: BSS RANGE=0- MASK=0x21987
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 BSS RANGE=0- MASK=0x21987"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/WirelessDisplayService(  916): getDiscoveryDongleList
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
,D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
D/wpa_supplicant( 1119): WPS: WFA subelement id=0 len=1
,I/wpa_supplicant( 1119): reply (376) for get BSS: id=4
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:4a
I/wpa_supplicant( 1119): freq=5220
I/wpa_supplicant( 1119): level=-46
I/wpa_supplicant( 1119): tsf=0000000925211693,
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG7005g
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=5
I/wpa_supplicant( 1119): bssid=c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): freq=2412
I/wpa_supplicant( 1119): level=-58
I/wpa_supplicant( 1119): tsf=0000000925211722
I/wpa_supplicant( 1119): flags=[WPA2-PSK-CCMP][WPS][ESS]
I/wpa_supplicant( 1119): ssid=NG700
I/wpa_supplicant( 1119): ====
I/wpa_supplicant( 1119): id=6
I/wpa_supplicant( 1119): bssid=38:f8:89:11:e9:11
I/wpa_supplicant( 1119): freq=2427
I/wpa_supplicant( 1119): level=-86
I/wpa_supplicant( 1119): tsf=0000000925211732
I/wpa_supplicant( 1119): flags=[WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS]
I/wpa_supplicant( 1119): ssid=Gonzos
I/wpa_supplicant( 1119): ####
,W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1385 android.net.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:6054 android.net.wifi.WifiStateMachine.handleMediaLinkEvent:6216 android.net.wifi.WifiStateMachine.access$6000:248 android.net.wifi.WifiStateMachine$SupplicantStartedState.processMessage:7470 
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/WifiStateMachine(  916): == begin of scan result ==
D/WifiStateMachine(  916): == (3) end of scan result ==
D/WirelessDisplayService(  916): getDiscoveryDongleList
,D/WifiManager( 1253): getScanResults enter 
D/WifiStateMachine(  916): == begin of scan result ==
,D/WifiStateMachine(  916): == (3) end of scan result ==,
D/WifiStateMachine(  916): 0: scan result = SSID: NG7005g, BSSID: c0:ff:d4:d3:aa:4a, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -46, frequency: 5220, timestamp: 925211693, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 1: scan result = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, capabilities: [WPA2-PSK-CCMP][WPS][ESS], level: -58, frequency: 2412, timestamp: 925211722, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): 2: scan result = SSID: Gonzos, BSSID: 38:f8:89:11:e9:11, capabilities: [WPA-PSK-CCMP+TKIP][WPA2-PSK-CCMP+TKIP][ESS], level: -86, frequency: 2427, timestamp: 925211732, distance: ?(cm), distanceSd: ?(cm)
D/WifiStateMachine(  916): add 3 to mScanResults
D/BatSI   (  916): WIFI scan stopped for: 440a0300 uid:1000
D/WifiNotificationController(  916): mWifiStateMachine.mSilentHungEnabled = false, mNumScansSinceNetworkStateChange = 0
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=0 ifi_flags=0x1003 ([UP])
,D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 1119): Wireless event: cmd=0x8b15 len=20
D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/Tethering(  916): interfaceLinkStateChanged wlan0, false
D/Tethering(  916): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1119): nl80211: Event message available
D/wpa_supplicant( 1119): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 1119): nl80211: Connect event
D/wpa_supplicant( 1119): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 1119): nl80211: Associated with c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 32
D/wpa_supplicant( 1119): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
I/wpa_supplicant( 1119): State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1119): Add randomness: count=29 entropy=3
,I/wpa_supplicant( 1119): wlan0: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/wpa_supplicant( 1119): TDLS: Remove peers on association
D/wpa_supplicant( 1119): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
,D/wpa_supplicant( 1119): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 1119): EAPOL: enable timer tick
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state IDLE
I/wpa_supplicant( 1119): htc_wext_set_keepalive +
,I/wpa_supplicant( 1119): htc_wext_set_keepalive: enable=1, type=1, interval=30
D/wpa_supplicant( 1119): getPrivFuncNum +	
I/wpa_supplicant( 1119): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive - ret = 0
I/wpa_supplicant( 1119): State: ASSOCIATED -> 4WAY_HANDSHAKE
,D/wpa_supplicant( 1119): Get randomness: len=32 entropy=4
D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
D/Tethering(  916): interfaceLinkStateChanged wlan0, true
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  916): interfaceStatusChanged wlan0, true
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =ASSOCIATING newSupplicantState =ASSOCIATED
,D/WifiMonitor(  916): WifiMonitor: Got associated with event from string: Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  916): handleAssociatedWithEvent. Data= Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/HTCRequest(  916): WifiMonitor:getSSIDFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFrequencyFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:getFreqFromEventString() 2412
D/HTCRequest(  916): WifiMonitor:getMacFromString Associated with c0:ff:d4:d3:aa:48 ssid='NG700' freq=2412
D/WifiMonitor(  916): handleAssociatedWithEvent. Parsed MAC Address =c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb85e29f0 key_idx=0 set_tx=1 seq_len=6 key_len=16
D/wpa_supplicant( 1119):    addr=c0:ff:d4:d3:aa:48
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 11
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 10
D/wpa_supplicant( 1119): EAPOL: External notification - portValid=1
I/wpa_supplicant( 1119): State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=3 addr=0xb6f8bb4a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 1119):    broadcast key
D/WifiMonitor(  916): handleAssociatedWithEvent. bLFR =false
,D/WifiMonitor(  916): handleAssociatedWithEvent. wifiSsid ='NG700' freq=2412
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 11
I/wpa_supplicant( 1119): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
E/wpa_supplicant( 1119): wlan0: BLACKLIST REMOVE c0:ff:d4:d3:aa:48
I/wpa_supplicant( 1119): State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 1119): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd SETROAMMODE 0 len = 0, 13
I/wpa_supplicant( 1119): setConcurrentAPChannel: Set wifi.hotspot.channel to 1
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  916): Enter handleAssociatedWithEvent
E/wpa_supplicant( 1119): wlan0: Connect to SSID: NG700
D/WifiStateMachine(  916): Associated
D/wpa_supplicant( 1119): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 1119): netlink: Operstate: linkmode=-1, operstate=6
I/wpa_supplicant( 1119): set send_ind_to_ndc = 0
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =ASSOCIATED newSupplicantState =FOUR_WAY_HANDSHAKE
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING (1)+
I/wpa_supplicant( 1119): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1119): EAPOL: External notification - portValid=1
,D/wpa_supplicant( 1119): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 1119): EAP: EAP entering state DISABLED
D/wpa_supplicant( 1119): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 1119): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 1119): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1119): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 1119): EAPOL authentication completed successfully
,I/wpa_supplicant( 1119): WPS: cancel wps_retry timer in: wpas_wps_eapol_cb
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 79
D/wpa_supplicant( 1119): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 1119): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 1119): nl80211: if_removed already cleared - ignore event
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/Tethering(  916): interfaceLinkStateChanged wlan0, true
D/Tethering(  916): interfaceStatusChanged wlan0, true
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =FOUR_WAY_HANDSHAKE newSupplicantState =GROUP_HANDSHAKE
D/Tethering(  916): [isWifi] getHotspotEnabled: false
D/WifiMonitor(  916): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE c0:ff:d4:d3:aa:48
,D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange():id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:getSSIDFromString id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  916): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiStateMachine(  916): mAssociatedMacAddress = c0:ff:d4:d3:aa:48
D/WifiStateMachine(  916): Exit handleAssociatedWithEvent
D/WifiMonitor(  916): WifiMonitor: prevSupplicantState =GROUP_HANDSHAKE newSupplicantState =COMPLETED
D/WifiStateMachine(  916): BSSID was changed, update WiFi database
D/WifiApDatabaseHandler(  916): updateConnectedAP...
D/WifiApDatabaseHandler(  916): updateConnectedAP...
,D/WifiStateMachine(  916): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiApDatabaseHandler(  916): isDuplicate in c0:ff:d4:d3:aa:48-0: true
,D/WifiStateMachine(  916): This record is existed, only update it...
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  916): updateConnectedAP...
,D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  916): updateConnectedAP...,
,D/WifiStateMachine(  916): fetchFrequency(), freq = 2412,
D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =OBTAINING_IPADDR wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
,D/WifiStateMachine(  916): WifiApDatabaseHandler, WiFi AP database Inserting ..
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,D/WifiApDatabaseHandler(  916): isDuplicate in c0:ff:d4:d3:aa:48-0: true
D/WifiStateMachine(  916): This record is existed, only update it...
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
,D/WifiApDatabaseHandler(  916): updateConnectedAP...
,I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: CONNECTING/OBTAINING_IPADDR, default=-1
D/ConnectivityService(  916): Provision feature enable=false
D/ConnectivityService(  916): mActiveDefaultNetwork: -1
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WISPrService( 3821): >>>>>WISPrService start isConnected = false<<<<<
D/WISPrService( 3821): wifi connected:falsemWifiInfo:SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: GROUP_HANDSHAKE, RSSI: -200, Link speed: -1, Frequency: 2412, Net ID: 0, Metered hint: false
D/WifiStateMachine(  916): fetchCapability(), capabilities = [WPA2-PSK-CCMP][WPS][ESS]
D/WifiApDatabaseHandler(  916): updateConnectedAP...
,D/WifiNative-wlan0(  916): doBoolean: SET pno 0
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SET pno 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): CTRL_IFACE SET 'pno'='0'
D/WifiNative-wlan0(  916):    returned true
,D/DhcpStateMachine(  916): [StoppedState] Start DHCP
,D/WifiStateMachine(  916): setRSSItoWifiInfo: NetworkDetailedState=OBTAINING_IPADDR
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 1 len = 0, 12
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER SETSUSPENDMODE 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 0 len = 0, 16
D/WifiNative-wlan0(  916):    returned true
D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 1
I/wpa_supplicant( 1119): Set power mode to POWER_MODE_ACTIVE due to Active_Mode_Enable = 0x1
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/wpa_supplicant( 1119): nl80211: Event message available
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/wpa_supplicant( 1119): nl80211: Drv Event 79 (NL80211_CMD_SET_REKEY_OFFLOAD) received for wlan0
D/wpa_supplicant( 1119): nl80211: Rekey offload event for BSSID c0:ff:d4:d3:aa:48,
D/WifiNative-wlan0(  916):    returned null
E/WifiStateMachine(  916): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  916): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
,D/WifiNative-wlan0(  916):    returned null
,D/WifiStateMachine(  916): handlePreDhcpSetup Held wake lock during DHCP
D/PMS     (  916): acquireWL(4465ba88): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 916 1000 null
D/WifiStateMachine(  916): handlePreDhcpSetup mBluetoothConnectionActive: false
D/WifiP2pService(  916): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42083b90 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@42083b90 target=com.android.internal.util.StateMachine$SmHandler }
,I/QuickSettingWifi( 1164): receive.wifiConnect:false wifiAPname:null elapse:1,
,D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  916): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
D/WifiNative-wlan0(  916): doBoolean: DRIVER SETSUSPENDMODE 1
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER SETSUSPENDMODE 1"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd SETSUSPENDMODE 1 len = 0, 16
D/WifiNative-wlan0(  916):    returned true,
D/WifiNative-wlan0(  916): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): Power_Mode_Type mode = 0
,I/wpa_supplicant( 1119): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0,
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 61,
,D/WifiNative-wlan0(  916):    returned true
,D/WifiNative-wlan0(  916): doBoolean: DRIVER BTCOEXMODE 2
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2",
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1119): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12,
D/WifiP2pService(  916): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  916): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiNative-wlan0(  916):    returned true
D/WifiStateMachine(  916): handlePostDhcpSetup release wake lock during DHCP
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0,
D/PMS     (  916): releaseWL(4465ba88): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 null
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17,
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [3][0][0]
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  916): fetchRssiAndLinkSpeedNative mLinkspeedCount = 1, mLinkspeedSum: 24
,D/WifiNative-wlan0(  916): doBoolean: SignalStrength 97
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1119): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  916):    returned true
D/WIFI_ICON( 1164): updateWifiState: RSSI_CHANGED -1 -> 3
D/WifiStateMachine(  916): gateway: /192.168.1.1
,D/WifiNative-wlan0(  916): doBoolean: DRIVER GATEWAY-ADD 16885952
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER GATEWAY-ADD 16885952"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1119): WiFi gateway: 0x101a8c0
I/wpa_supplicant( 1119): htc_wext_set_keepalive +
I/wpa_supplicant( 1119): htc_wext_set_keepalive: enable=1, type=2, interval=15
D/wpa_supplicant( 1119): getPrivFuncNum +	
I/wpa_supplicant( 1119): getPrivFuncNum -, cmd = 0x8bf6
I/wpa_supplicant( 1119): htc_wext_set_keepalive fnum = 0x8bf6
I/wpa_supplicant( 1119): get_ip_address source addr = c0a80175
I/wpa_supplicant( 1119): htc_wext_set_keepalive gateway addr = c0a80101
I/wpa_supplicant( 1119): htc_wext_set_keepalive - ret = 0
D/WifiNative-wlan0(  916):    returned true
D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent L2ConnectedState
D/WifiStateMachine(  916): VerifyingLinkState enter
D/WifiStateMachine(  916): send WifiWatchdogStateMachine.GOOD_LINK_DETECTED at VerifyingLinkState
D/WifiStateMachine(  916): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine(  916): VerifyingLinkState: enableIpv6
,D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_0 (gone) T]
D/WifiStateMachine(  916): [sendNetworkStateChangeBroadcast] NetworkInfo state =CONNECTED wifi info = SSID: NG700, BSSID: c0:ff:d4:d3:aa:48, Supplicant state: COMPLETED, RSSI: -57, Link speed: 24, Frequency: 2412, Net ID: 0, Metered hint: false
I/IntentController( 1164): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  916): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  916): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=true
V/NetworkPolicy(  916): mWifiStateReceiver: meteredHint=false,EPS mode=false
D/WifiStateTracker(  916): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  916): ConnectivityChange for WIFI/: CONNECTED/CONNECTED, default=-1
,D/ConnectivityService(  916): Provision feature enable=false
,D/WifiWatchdogStateMachine(  916): WAN detection
D/ConnectivityService(  916): handleConnect: E newNetType=1 thisIface=wlan0 isFailover=false
V/ConnectivityService(  916): Policy requires mobile/UNKNOWN teardown quickly
D/MDST    (  916): default: teardown()
D/MDST    (  916): default: setTeardownRequested(true)
D/MDST    (  916): default: setEnableApn apnType =default , enable=false
D/WIFI_ICON( 1164): updateWifiState: NETWORK_STATE_CHANGED connected
D/StatusBar.NetworkController( 1164): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/MDST    (  916): default: setTeardownRequested(true)
,D/ConnectivityService(  916): Setting TCP values: [524288,2097152,4194304,262144,524288,1048576] which comes from [net.tcp.buffersize.wifi]
E/ConnectivityService(  916): Unexpected mtu value: android.net.wifi.WifiStateTracker@427533a8
,D/libc    (  916): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WISPrService( 3821): >>>>>WISPrService start isConnected = true<<<<<
,D/ConnectivityService(  916): handleConnectivityChange: netType=1 doReset=false resetMask=0
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [1][0][0]
I/wpa_supplicant( 1119): Change stage from stage0 to stage3
D/WifiStateMachine(  916): SupplicantStartedState - CMD_GET_CONFIGURED_NETWORKS
,D/WifiStateMachine(  916): syncGetConfiguredNetworks
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  916): Adding 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/ConnectivityService(  916): Adding 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/ConnectivityService(  916): Adding 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/ConnectivityService(  916): handleConnectivityChange: resetting
D/Nat464Xlat(  916): htcRequiresClat: netType=1, hasIPv4=true, mIsClatEnabled=true, isConnected=true
,D/Nat464Xlat(  916): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
,D/libc    (  364): [NET] set_iface_protocol: wlan0 is v4,v6=1,0
,I/QuickSettingWifi( 1164): receive.wifiConnect:true wifiAPname:NG700 elapse:1
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
D/WirelessDisplayService(  916): [REVY][0] Wifi disconnet and resume in short time. mCurNetworkInterfacewlan0
D/WirelessDisplayService(  916):  ConnectivityReceiver: receiver wifi connected, check dongle : 0
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  916): sendGeneralBroadcastDelayed, restrictEnable=false
D/ConnectivityService(  916): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  916): setSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: true, isIpv6Connected: false
D/PMS     (  916): acquireWL(428f3440): PARTIAL_WAKE_LOCK  NetworkStats 0x1 916 1000 null
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/PMS     (  916): acquireWL(42988948): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I//system/bin/ip(  364): RTNETLINK answers: No such file or directory
,I/logwrapper(  364): /system/bin/ip terminated by exit(254)
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1453134283554 min interval config: 0 actual interval: 770024
D/PMS     (  916): acquireWL(4408bf98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PMS     (  916): releaseWL(42988948): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinService( 2176): Checking schedule, now: 1453135053587 next: 1453134313510
,I/CheckinService( 2176): active receiver: enabled
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=1, flag=1, pid=2176, uid=10029, userID:0
,I//system/bin/ip(  364): RTNETLINK answers: No such process
,I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/CheckinService( 2176): Preparing to send checkin request
,I/EventLogService( 2176): Accumulating logs since 1453134284257
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): mActiveDefaultNetwork: WIFI
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  916): releaseWL(428f3440): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  916): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  916): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/wpa_supplicant( 1119): EAPOL: startWhen --> 0
D/wpa_supplicant( 1119): EAPOL: disable timer tick
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1400): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=4121439130
,I/WVCdm   (  372): CdmEngine::CloseSession
,W/Settings( 4702): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (4702/10029)
I/Adreno-EGL( 4702): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4702): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4702): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4702): Local Branch: 
I/Adreno-EGL( 4702): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4702): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4702):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4702): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4702): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4702): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4702): Local Branch: 
I/Adreno-EGL( 4702): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4702): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4702):                  aa63bbd948f41d15fc72f585e
,I/Adreno-EGL( 4702): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 4702): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 4702): Build Date: 08/28/14 Thu
I/Adreno-EGL( 4702): Local Branch: 
I/Adreno-EGL( 4702): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 4702): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 4702):                  aa63bbd948f41d15fc72f585e
,I/WVCdm   (  372): CdmEngine::OpenSession
,I/WVCdm   (  372): CdmEngine::QueryKeyControlInfo
,I/WVCdm   (  372): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  372): PrepareKeyRequest: nonce=88713972
,D/PMS     (  916): releaseWL(427ea590): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 null
,D/ConnectivityService(  916): NetTransition Wakelock for ConnectedState released by timeout
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/AlarmManager(  916): [AlarmQueuing] connectivity wifi: true
V/Tethering(  916): mTetherableUsbRegexs:{(usb0)(ncm0)}
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,I/WVCdm   (  372): CdmEngine::CloseSession
,D/CaptivePortalTracker(  916): NoActiveNetworkState
D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - original mNetworkConnected = false
,D/htcCheckinService(  916): ConnectivityReceiver - onReceive() - new mNetworkConnected = true
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.backuptransport (1616/10029)
D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
I/ConnectivityHelper( 1303): [onReceive] WIFI(1): CONNECTED
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.htc.launcher (1303/10076)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
V/Tethering(  916): bSetPropertyMultiRAB:false
D/Tethering(  916): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: CONNECTED
I/Tethering(  916): Finding IPv4 upstream interface on: InterfaceName: wlan0 LinkAddresses: [192.168.1.117/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] 
I/Tethering(  916): lprop.getAllRoutes() 192.168.1.0/24 -> 0.0.0.0
I/NetworkMonitor( 3878): type=WIFI subType= reason=null isConnected=true
I/Tethering(  916): lprop.getAllRoutes() 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  916): ipv4Default 0.0.0.0/0 -> 192.168.1.1
I/Tethering(  916): Found interface wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/Tethering(  916): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by com.google.android.music (3878/10154)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.setupwizard (4570/10079)
D/ConnectivityService(  916): getNetworkInfo networkType=1 called by  (916/1000)
D/PMS     (  916): acquireWL(44537b28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 916 1000 null
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(428cd358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (2981/10021)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
D/PMS     (  916): acquireWL(445d31e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 916 1000 WorkSource{10160}
D/ConnectivityService(  916): getActiveNetworkInfo called by com.facebook.katana (4552/10027)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): acquireWL(43a3cbc8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 916 1000 WorkSource{10029}
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,D/GpsLocationProvider(  916): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  916): updateNetworkState available info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: CONNECTED DetailedState: , roaming: false, failover: false, isAvailable: true
D/GpsLocationProvider(  916): getAGpsConnectionInfo connType - 4
D/GpsLocationProvider(  916): ignore wifi update if we are not in OPENING or CLOSING
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(428cd358): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/PMS     (  916): releaseWL(44537b28): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(445b33d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,D/AutoSetting( 1388): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
,D/MobileConnectivityChangeReceiver( 4570): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4570): onReceive CONNECTIVITY_CHANGE networkType=1
D/PMS     (  916): releaseWL(445b33d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(441b2e20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
D/PMS     (  916): releaseWL(441b2e20): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/PMS     (  916): acquireWL(4381ec40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(4381ec40): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/AutoSetting( 1388): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,D/AutoSetting( 1388): service - onStartCommand() screen is off, don't request location
D/AutoSetting( 1388): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1388): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.magazines (4598/10151)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.htc.sense.hsp (1388/10055)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.apps.plus (4635/10160)
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (1253/10029)
,D/PMS     (  916): acquireWL(430e3260): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
,I/CheckinService( 2176): Checkin interval check for package: unspecified last checkin: 1453134283554 min interval config: 0 actual interval: 771162
D/PMS     (  916): releaseWL(430e3260): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(43e4b120): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.mdm.receivers.AccountsChangedReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  916): releaseWL(445d31e0): PARTIAL_WAKE_LOCK  *sync*/com.google.android.apps.plus.content.EsProvider/com.google/***** 0x1 WorkSource{10160}
D/PMS     (  916): releaseWL(43e4b120): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
I/iu.Environment( 2176): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 2176): num queued entries: 0
I/iu.UploadsManager( 2176): num updated entries: 0
,I/iu.SyncManager( 2176): NEXT; no task
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getAllNetworkInfo called by com.test.thalitest (4417/10389)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
D/libc    ( 1400): [NET] getaddrinfo-,err=8
D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    ( 1400): [NET] getaddrinfo-, 1
,D/libc    ( 1400): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 1024
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =14a9 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
D/PMS     (  916): acquireWL(445ebef0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360927980
,W/AlarmManager(  916): Alarm trigger time is over 1 year: setImplLocked(PendingIntent{42719fb8: PendingIntentRecord{43e5a300 com.google.android.gms startService}}) : type=2 triggerAtTime=315360927980 win=-1 tElapsed=315360927980 maxElapsed=551880927978 interval=0 standalone=false
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 2176): [NET] getaddrinfo-,err=8
,V/NativeCrypto( 2176): SSL shutdown failed: ssl=0x5caef1a8: I/O error during system call, Connection timed out
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
V/NativeCrypto( 2176): SSL shutdown failed: ssl=0x66458008: I/O error during system call, Connection timed out
D/libc    ( 2176): [NET] getaddrinfo-, 1
,D/libc    ( 2176): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =b441 +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2176): [NET] getaddrinfo_proxy-, success
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  364): [NET]res_nsend:resplen=79
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 1400): [NET] getaddrinfo_proxy-, success
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
,D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/libc    ( 2176): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2176): [NET] getaddrinfo-,err=8
D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
D/PMS     (  916): acquireWL(434ef370): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,D/PMS     (  916): releaseWL(43a3cbc8): PARTIAL_WAKE_LOCK  *sync*/com.google.android.gms.fitness/com.google/***** 0x1 WorkSource{10029}
D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1400): [NET] getaddrinfo-,err=8
D/PMS     (  916): releaseWL(434ef370): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/CheckinTask( 2176): Sending checkin request (12590 bytes)
,D/libc    ( 1400): [NET] getaddrinfo+,hn 16(0x6d74616c6b2e67),sn(),family 0,flags 4
,D/libc    ( 1400): [NET] getaddrinfo-,err=8
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/PMS     (  916): acquireWL(429fcbb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/PMS     (  916): releaseWL(445ebef0): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1400/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  916): handleInetConditionChange: starting a change hold
,D/PMS     (  916): releaseWL(429fcbb0): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(429d2128): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1400 10029 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1400/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
,D/ConnectivityService(  916): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
,D/ConnectivityService(  916): reportInetCondition for net 1, percentage: 100 by  (1400/10029)
D/ConnectivityService(  916): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  916): handleInetConditionChange: currently in hold - not setting new end evt
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (1400/10029)
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360927980
,D/PMS     (  916): releaseWL(429d2128): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10029 com.google.android.gms}
,I/CheckinRequestBuilder( 2176): Checkin reason type: 8 attempt count: 1
I/ActivityManager(  916): Cannot resolve ContentProvider=com.google.android.wearable.settings
E/ActivityThread( 2176): Failed to find provider info for com.google.android.wearable.settings
,D/ConnectivityService(  916): getNetworkInfo networkType=9 called by com.google.android.gms (2176/10029)
,D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
,W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1119): environment dirty rate=26 [30][8][0]
D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
D/ConnectivityService(  916): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
D/ConnectivityService(  916): sendGeneralBroadcast, restrictEnable=false
,D/ConnectivityService(  916): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  916): doString: SIGNAL_POLL
W/WifiHW  (  916): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1119): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1119): nl80211: survey data missing!
E/wpa_supplicant( 1119): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1119): environment dirty rate=0 [0][0][0]
,I/CheckinRequestBuilder( 2176): Classify the device as Phone.
,I/CheckinTask( 2176): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 2176): Checking schedule, now: 1453135055890 next: 1453657992884
,I/CheckinService( 2176): active receiver: disabled
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
,W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360927980
I/CheckinService( 2176): Checking schedule, now: 1453135055912 next: 1453657992884
,I/CheckinService( 2176): active receiver: disabled
,D/CheckinService( 2176): Recording last checkin time for package unspecified as 1453135055917
I/PackageManager(  916):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.checkin.CheckinService$ActiveReceiver, state=2, flag=1, pid=2176, uid=10029, userID:0
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038117
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038327
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038412
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038415
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038418
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360038425
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040085
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360040112
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360042474
W/AlarmManager(  916): Converted elapesd time is over 1 year! when = 315360927980
,D/PMS     (  916): releaseWL(4408bf98): PARTIAL_WAKE_LOCK  Checkin Service 0x1 WorkSource{10029 com.google.android.gms}
,D/ConnectivityService(  916): getActiveNetworkInfo called by com.google.android.gms (2176/10029)
,D/GCM     ( 1400): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WifiStateMachine(  916): It's IPV6 link-local unicast address, No need to broadcast it!
,D/libc    (  916): [NET] getaddrinfo+,hn 25(0x666538303a3a62),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-, SUCCESS
,D/WifiStateMachine(  916): [MLHD] enter handleMediaLinkEvent DefaultState
,D/libc    (  916): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 4
,D/libc    (  916): [NET] getaddrinfo-,err=8
D/libc    (  916): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
D/libc    (  916): [NET] getaddrinfo-, 1
D/libc    (  916): [NET] getaddrinfo_proxy+
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x7777772e687463),sn(),family 0,flags 1024
,D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =373c +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 19
D/libc    (  364): [NET]res_nsend:resplen=172
D/libc    (  364): [NET]res_queryN: exit 3, ancount=4
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    (  916): [NET] getaddrinfo_proxy-, success
,D/WifiWatchdogStateMachine(  916): Find DNS Address www.htc.com/104.81.130.175
,I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_CHANGED
I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver packageName:com.google.android.gms
,I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver replacing:false
,D/AccTypeManager( 1371): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
D/PMS     (  916): acquireWL(4416b770): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 4759 10111 null
,W/SystemReader( 1286): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "sms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,D/PMS     (  916): releaseWL(4416b770): PARTIAL_WAKE_LOCK  hangouts_rtcs 0x1 null
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "smsto",
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/ActivityManager(  916): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  916): Resuming delayed broadcast
,I/dalvikvm-heap( 1303): Grow heap (frag case) to 12.650MB for 53840-byte allocation
I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,W/Prism.AllAppsManager( 1303): AllAppsMgr addApps, already exist: ApplicationInfo(id=42, title=Google Settings, componentNameComponentInfo{com.google.android.gms/com.google.android.gms.app.settings.GoogleSettingsActivity} appsContainer=<ALLAPPS>)
,I/[PluginManager]RegisterService( 1388): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.google.android.gms
,I/[PluginManager]RegisterService( 1388): handle notify Blinkfeed plugin client changed
W/AccTypeManager( 1371): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1371): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/Launcher( 1303): Deferring update until onResume
,D/Launcher( 1303): waitUntilResume // bindAppsUpdated
,I/IcingCorporaProvider( 3111): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,I/ActivityManager(  916): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "sms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,D/PMS     (  916): acquireWL(437aaf78): PARTIAL_WAKE_LOCK  AsyncService 0x1 4635 10160 null
,D/PMS     (  916): releaseWL(437aaf78): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "smsto"
,E/ExternalAccountType( 1371): Unsupported attribute readOnly
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/ActivityManager(  916): Resuming delayed broadcast
,I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
,D/PhoneApp( 1270): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_CHANGED
,D/PMS     (  916): acquireWL(43b56620): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Delay finish: com.android.settings/.fpquicklaunch.HtcFingerPrintReceiver
,D/PMS     (  916): releaseWL(43b56620): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,D/PMS     (  916): acquireWL(434f8810): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Delay finish: com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver
,D/PMS     (  916): releaseWL(434f8810): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Resuming delayed broadcast
,I/ActivityManager(  916): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  916): acquireWL(444f5820): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 2176): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 2176): updateResources: need to parse f{com.google.android.gms}
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckState
,D/CaptivePortalTracker(  916): DelayedCaptiveCheckStateDo NOT lookupHost for default captive portal server.
D/ConnectivityService(  916): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/IcingCorporaProvider( 3111): UpdateCorporaTask done [took 1027 ms] updated apps [took 1025 ms] 
I/ActivityManager(  916): Resuming delayed broadcast
,I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1303): loadItems() com.htc.launcher.pageview.WidgetManager@41e5ee78 +
,I/Prism.WidgetManager( 1303): onLoadItems() +
,I/Icing   ( 2176): Indexing 31323E6206FB8147FEA27FFA377F075022B8831A from com.google.android.gms
,I/Icing   ( 2176): Indexing done 31323E6206FB8147FEA27FFA377F075022B8831A
,W/PackageManager(  916): Unable to load service info ResolveInfo{4345af48 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  916): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  916): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  916): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  916): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  916): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  916): 	at dalvik.system.NativeStart.main(Native Method)
,D/PMS     (  916): releaseWL(444f5820): PARTIAL_WAKE_LOCK  Icing 0x1 WorkSource{10029 com.google.android.gms}
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{445417d0 u0 com.htc.sense.hsp/.weather.location.AutoSettingService}
,D/PhoneApp( 1270): EVENT_QUERY_MO_PACKAGES
,D/PhoneApp( 1270): -- N1 =0
,D/PhoneApp( 1270): -- N2 =0
,D/PhoneApp( 1270): -- N3 =0
,E/Prism.WidgetManager( 1303): The same lists. No need to update. skip it.
I/Prism.WidgetManager( 1303): onLoadItems() -
,I/Prism.ItemManager( 1303): loadItems() com.htc.launcher.pageview.WidgetManager@41e5ee78 -
,D/RemoteDisplayProvider(  916): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_CHANGED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  916): start
,I/GCoreNlp( 1253): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  916): applying state to connected service
,D/PMS     (  916): acquireWL(41e06268): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(41e06268): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
D/LocationProviderProxy(  916): applying state to connected service
,D/PMS     (  916): acquireWL(425e3860): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(425e3860): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(422f08b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): releaseWL(422f08b8): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
,D/PMS     (  916): acquireWL(429907b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=953209, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(429907b0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(427e1b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,D/PMS     (  916): acquireWL(4277efb8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 916 1000 null
,V/AlarmManager(  916): sending alarm PendingIntent{41fe1bd0: PendingIntentRecord{427d07c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=957858, Int=0
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/PMS     (  916): acquireWL(4217f1d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,V/AlarmManager(  916): sending alarm PendingIntent{427319d8: PendingIntentRecord{42781bb0 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1453135077988, Int=900000
,D/PMS     (  916): releaseWL(4277efb8): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  916): releaseWL(4217f1d8): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,I/ActivityManager(  916): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4953 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/AutoSetting( 1388): service - has update message, not stop
,D/AutoSetting( 1388): service - mHandler: update timezone
,W/ContextImpl( 4953): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/AutoSetting( 1568): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
D/PMS     (  916): releaseWL(427e1b48): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/AutoSetting( 1568): receiver - intent: com.htc.app.autosetting.hsp.timezone_picker
,D/AutoSetting( 1568): service - onCreate()
,D/PowerUsageService( 4953): call getInstance()
W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
,W/ActivityManager(  916): Unable to start service Intent { cmp=com.htc.htclocationservice/.PhoneStateMonitorService } U=0: not found
D/AutoSetting( 1568): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
,D/AutoSetting( 1568): service - onStartCommand() handle command from HSP: cancelTimeZoneSelector
,D/DotMatrix( 1605): [NotificationService] onNotificationRemoved, pkgName: com.htc.htclocationservice, id: 2130968590
D/PowerUsageList:PowerUsageHelper( 4953): MY_DEBUG = false
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
V/NotificationService(  916): batLight: Full, plugged
V/LightsService(  916): setLight #8: color=#c8c800
D/qdlights(  916): set_color_led color=13158400, mode=255, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute mode=x0ff
V/LightsService(  916): setLight #8: color=#c800
D/qdlights(  916): set_color_led color=51200, mode=1, off_min=0, off_sec=0
D/qdlights(  916): [LedInfo] has indicator attribute
D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/ModeRGB string=100c800,len=7
,D/qdlights(  916): [LedInfo] write attr ok name=/sys/class/leds/indicator/off_timer string=0 0,len=3
D/AutoSetting( 1568): service - onStartCommand() action: com.htc.app.autosetting.timezoneupdate
D/AutoSetting( 1568): service - onStartCommand() handle command from HSP: processTimeZoneID
D/AutoSetting( 1568): service - mHandler: update timezone
,D/AutoSetting( 1568): service - processTimeZoneID() system nitz: 
,D/AutoSetting( 1568): service - processTimeZoneID() system nitz is valid: false (false)
W/BatSI   (  916): Couldn't get kernel wake lock stats
,D/AutoSetting( 1568): service - processTimeZoneID() single-timezone, pop up dialog
,D/AutoSetting( 1568): service - showManualTimeZoneSelector() send notification (single)
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.htc.htclocationservice, id: 2130968590, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.htc.htclocationservice does not support DotMatrix
,I/RemoteViews( 1164): com.htc.htclocationservice (true,33751552)
,D/OnDemandProgressBar( 1164): release indeterminate drawable android.widget.OnDemandProgressBar{421a60d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1164): com.htc.htclocationservice 4 7 2 11
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,W/BatSI   (  916): Couldn't get kernel wake lock stats
,D/PMS     (  916): acquireWL(445d9ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
,I/IntentController( 1164): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/PMS     (  916): releaseWL(445d9ad8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/PowerUI ( 1164): closing low battery warning: level=100
D/PowerUI ( 1164): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1164): status:5 level:100 unsupport:false plugged:true
,I/ActivityManager(  916): Waited long enough for: ServiceRecord{445b8850 u0 com.htc.htclocationservice/.AutoSettingService}
,D/AutoSetting( 1388): service - handleMessage() stop self
,D/AutoSetting( 1388): service - handleMessage() quit looper
,D/AutoSetting( 1388): service - onDestroy() END
,D/AutoSetting( 1568): service - handleMessage() stop self
,D/AutoSetting( 1568): service - onDestroy() END
,D/AutoSetting( 1568): service - handleMessage() quit looper
,D/Process (  916): killProcessQuiet, pid=4782
,I/ActivityManager(  916): Killing 4782:com.htc.sense.mms/u0a65 (adj 15): empty #17
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  916): Recipient 4782
,I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  916): acquireWL(437d4238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1013208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(437d4238): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(434ea1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{420d0fa8: PendingIntentRecord{44531878 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1453135153584, Int=0
,D/PMS     (  916): acquireWL(4310bb18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4953 1000 null
,D/SmartSyncUtils( 4953): isEpsOn(), nState = 0
D/PMS     (  916): releaseWL(434ea1a8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
D/PMS     (  916): releaseWL(4310bb18): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
D/PMS     (  916): acquireWL(440e20e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4953 1000 null
,D/SmartSyncScreenOnOffTimeReceiver( 4953): [updateNmRange] bManual = false
,D/SmartSyncScreenOnOffTimeReceiver( 4953): [updateNmRange] USERNIGHT_TIMESTART = 3, USERNIGHT_TIMEEND = 7, nStart = 3, nEnd = 7, bNormalRange = true
,D/SmartSyncScreenOnOffTimeReceiver( 4953): AlarmOnTime = -1
D/SmartSyncScreenOnOffTimeReceiver( 4953): SettingOnTime = 1453183200000, randomSettingOnTime = 1453181053000
,D/SmartSyncScreenOnOffTimeReceiver( 4953): SettingOffTime = 1453168800000, randomSettingOffTime = 1453173271000
D/SmartSyncScreenOnOffTimeReceiver( 4953): bDayMode = false
D/SmartSyncScreenOnOffTimeReceiver( 4953): bNightMode = true
,D/SmartSyncScreenOnOffTimeReceiver( 4953): bNightModeTurnOffOnce = false
,D/PMS     (  916): releaseWL(440e20e8): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/PMS     (  916): acquireWL(43a2f8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(43a2f8a0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(440acf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(440acf18): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4295edf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{41fe1bd0: PendingIntentRecord{427d07c8 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=1049217, Int=0
,D/PMS     (  916): acquireWL(43a73d70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 916 1000 null
D/PMS     (  916): releaseWL(4295edf8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/ConnectivityService(  916): getActiveNetworkInfo called by  (916/1000)
,D/PMS     (  916): acquireWL(445c9990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 916 1000 null
,D/PMS     (  916): releaseWL(43a73d70): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null
,D/PMS     (  916): releaseWL(445c9990): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,D/PMS     (  916): acquireWL(43072980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1073208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(43072980): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(44666958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44666958): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4414dae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1133208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(4414dae0): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(44016360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44016360): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(4414d300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(4414d300): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/HtcPowerSaver(  916): updateBatteryInfo
I/IntentController( 1164): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PowerUI ( 1164): closing low battery warning: level=100
D/PowerUI ( 1164): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1164): status:5 level:100 unsupport:false plugged:true
,D/PMS     (  916): acquireWL(426cea68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1193208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(426cea68): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(43fd9498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/UsbnetService(  916): BroadcastReceiver::onReceive+
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/PowerUI ( 1164): closing low battery warning: level=100
D/PowerUI ( 1164): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,I/IntentController( 1164): receive(android.intent.action.BATTERY_CHANGED,1,false)
D/UsbnetService(  916): onReceive BATTERY_CHANGED
D/UsbnetService(  916):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  916): BroadcastReceiver::onReceive-
D/HtcPowerSaver(  916): updateBatteryInfo
D/PMS     (  916): runPSCheck
D/HtcPowerSaver(  916): Checking...
I/HtcPowerSaver(  916): >> updateStatus
D/PMS     (  916): releaseWL(43fd9498): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,I/HtcPowerSaver(  916): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  916): << updateStatus
,I/BatteryController( 1164): status:5 level:100 unsupport:false plugged:true
,E/PNP_UPDATERD(  351): inotify_add_watch failed. (No such file or directory)
,D/PMS     (  916): acquireWL(43e30de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1253208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(43e30de8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,D/PMS     (  916): acquireWL(44102de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(44102de0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(440b7b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  916): n_update end
,D/PMS     (  916): releaseWL(440b7b98): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,D/PMS     (  916): acquireWL(439a9ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 916 1000 WorkSource{1000}
,V/AlarmManager(  916): sending alarm PendingIntent{424230b0: PendingIntentRecord{420c9800 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1313208, Int=0
,I/IntentController( 1164): receive(android.intent.action.TIME_TICK,1,false)
,D/PMS     (  916): releaseWL(439a9ac8): PARTIAL_WAKE_LOCK  AlarmManager 0x1 WorkSource{1000}
,TIME-OUT KILL (timeout was 1200000ms),E/cutils-trace( 4979): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 4979): ====startRecUseTime====
D/htc.customization.log.level( 4979):  is 
W/CustomizationLogLevel( 4979): Level value is invalid, use default level 2
D/CustomizationManager( 4979):  Read ACC file spent 0.129 (s)
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__002
D/CIDMapFileReader( 4979): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 4979): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4979): Parsing tag category name = system
I/CustomizationCIDLoader( 4979): Parsing tag category name = application
I/CustomizationCIDLoader( 4979): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4979): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4979): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4979): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4979): Parsing tag category name = Settings
D/CustomizationManager( 4979):  Read CID file spent 0.185 (s)
D/CustomizationManager( 4979):  All configurations done spent 0.185 (s)
W/HtcNativeFlag( 4979): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4979): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4979): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 4979): Fail to get flag for type 'language', use default value: -1
D/PackageManager(  916): deletePackageAsUser: pkg=com.test.thalitest, pid=4979, uid=2000 user=0
I/ActivityManager(  916): Force stopping com.test.thalitest appid=10389 user=-1: uninstall pkg
D/Process (  916): killProcessQuiet, pid=4417
D/Process (  916): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  916): Killing 4417:com.test.thalitest/u0a389 (adj 15): stop com.test.thalitest
W/asset   (  916): Copying FileAsset 0x68586e90 (zip:/data/app/com.test.thalitest-1.apk:/resources.arsc) to buffer size 2468 to make it aligned.
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/PackageSettings(  916): Skipping PackageSetting{425aa410 com.example.hello/10397} due to missing metadata
I/ActivityManager(  916): Force stopping com.test.thalitest appid=10389 user=0: pkg removed
I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver packageName:com.test.thalitest
I/HtcKeyguardAppUpdateMonitor( 1164): ApplicationsIntentReceiver replacing:false
D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.test.thalitest does not support DotMatrix
D/AccTypeManager( 1371): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
W/GeofencerStateMachine( 1253): Ignoring removeGeofence because network location is disabled.
D/PMS     (  916): acquireWL(426ae038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1253 10029 WorkSource{10029 com.google.android.gms}
I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  916): releaseWL(426ae038): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 WorkSource{10029 com.google.android.gms}
I/Launcher( 1303): Deferring update until onResume
D/Launcher( 1303): waitUntilResume // bindAppsRemoved
D/VoicemailCleanupService( 1328): Cleaning up data for package: com.test.thalitest
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "sms"
W/AccTypeManager( 1371): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
D/AccTypeManager( 1371): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
W/SystemReader( 1286): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mms"
I/[PluginManager]RegisterService( 1388): onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/[PluginManager]RegisterService( 1388): handle notify Blinkfeed plugin client changed
E/ExternalAccountType( 1371): Unsupported attribute readOnly
D/Prism.PackageStateRece_( 1303): action: android.intent.action.PACKAGE_REMOVED
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "sms"
I/IcingCorporaProvider( 3111): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "smsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mms"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
I/ActivityManager(  916): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4994 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
I/PackageManager(  916):   Action: "android.intent.action.SENDTO"
I/PackageManager(  916):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  916):   Scheme: "mmsto"
I/PackageManager(  916): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1270 :
D/PhoneApp( 1270): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
D/PMS     (  916): acquireWL(42736668): PARTIAL_WAKE_LOCK  Icing 0x1 2176 10029 WorkSource{10029 com.google.android.gms}
I/IcingCorporaProvider( 3111): UpdateCorporaTask done [took 305 ms] updated apps [took 305 ms] 
I/InputMethodManagerService(  916): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
E/SQLiteDatabase( 4994): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4994): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4994): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4994): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4994): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4994): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4994): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4994): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4994): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4994): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4994): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4994): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4994): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4994): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4994): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4994): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4994): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4994): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4994): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4994): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4994): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4994): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4994): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4994): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4994): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4994): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4994): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4994): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4994): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4994): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4994): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4994): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4994): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4994): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4994): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4994): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4994): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4994): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4994): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4994): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4994): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4994): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4994): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4994): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4994): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4994): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4994): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4994): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4994): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4994): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4994): Opened ClientFlag.db in read-only mode
E/SQLiteDatabase( 4994): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4994): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4994): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4994): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4994): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4994): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4994): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4994): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4994): 	at aho.run(AbstractDatabaseInstance.java:455)
W/dalvikvm( 4994): threadid=11: thread exiting with uncaught exception (group=0x4199ce30)
E/ActivityManager(  916): App crashed! Process: com.google.android.apps.docs
E/AndroidRuntime( 4994): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4994): Process: com.google.android.apps.docs, PID: 4994
E/AndroidRuntime( 4994): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4994): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4994): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4994): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4994): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4994): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4994): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4994): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4994): 	at aho.run(AbstractDatabaseInstance.java:455)
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop144.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
D/Process ( 4994): killProcess, pid=4994
D/Process ( 4994): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
I/ActivityManager(  916): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=5014 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 4994
I/ActivityManager(  916): Process com.google.android.apps.docs (pid 4994) has died.
W/ContextImpl( 5014): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2687 
I/ActivityManager(  916): Start proc com.zoodles.kidmode for broadcast com.zoodles.kidmode/.notification.newapps.AppUninstallReceiver: pid=5027 uid=10149 gids={50149, 3003, 5012, 1028, 1015}
E/SQLiteDatabase( 5014): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 5014): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 5014): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 5014): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5014): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/SQLiteDatabase( 5014): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/SQLiteDatabase( 5014): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5014): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 5014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 5014): threadid=10: thread exiting with uncaught exception (group=0x4199ce30)
E/AndroidRuntime( 5014): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 5014): Process: com.android.keychain, PID: 5014
E/AndroidRuntime( 5014): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 5014): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 5014): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 5014): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 5014): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:286)
E/AndroidRuntime( 5014): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:280)
E/AndroidRuntime( 5014): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 5014): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 5014): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 5014): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/ActivityManager(  916): App crashed! Process: com.android.keychain
D/ErrorReport(  916): HtcErrorReportManager Begin---add error logs to dropbox
D/Process ( 5014): killProcess, pid=5014
D/Process ( 5014): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
E/ErrorReport(  916): HtcErrorReportManager.Error in dumping error information
E/ErrorReport(  916): java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1453135443665.dbox_tmp: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/ErrorReport(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/ErrorReport(  916): 	at com.android.server.am.HtcErrorReportManager$2.run(HtcErrorReportManager.java:387)
E/ErrorReport(  916): 	at java.lang.Thread.run(Thread.java:864)
E/ErrorReport(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/ErrorReport(  916): 	at libcore.io.Posix.open(Native Method)
E/ErrorReport(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/ErrorReport(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/ErrorReport(  916): 	... 4 more
I/ActivityManager(  916): Recipient 5014
I/ActivityManager(  916): Process com.android.keychain (pid 5014) has died.
W/ActivityManager(  916): Scheduling restart of crashed service com.android.keychain/.KeyChainService in 1000ms
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AppTag  ( 5027): getInstance(Context context)
D/AppTag  ( 5027): getInstance(Context context)
D/AppTag  ( 5027): onCreate()
D/PMS     (  916): acquireWL(445476d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 4635 10160 null
D/PMS     (  916): releaseWL(445476d0): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
I/Prism.ItemManager( 1303): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
I/Prism.ItemManager( 1303): loadItems() com.htc.launcher.pageview.WidgetManager@41e5ee78 +
I/Prism.WidgetManager( 1303): onLoadItems() +
W/dalvikvm( 4135): VFY: unable to resolve virtual method 340: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
D/PackageBroadcastService( 2176): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 2176): Clearing selected account for com.test.thalitest
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 2176): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2176): Module APK com.google.android.play.games already loaded
I/ActivityManager(  916): Delay finish: com.google.android.gms/.games.chimera.GamesSystemBroadcastReceiverProxy
I/LocationSettingsChecker( 2176): Removing dialog suppression flag for package com.test.thalitest
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/games_3a3529a.db, handle = 0x6640d008
E/SQLiteLog( 2176): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteDBG( 2176): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/DocList.db, handle = 0x5cb08170
W/dalvikvm( 2176): threadid=44: thread exiting with uncaught exception (group=0x4199ce30)
W/PackageManager(  916): Unable to load service info ResolveInfo{427f6de8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  916): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  916): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  916): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  916): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  916): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  916): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  916): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  916): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  916): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  916): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  916): 	at dalvik.system.NativeStart.main(Native Method)
E/DriveAsyncService( 2176): disk I/O error (code 3850)
E/DriveAsyncService( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/DriveAsyncService( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:456)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 2176): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 2176): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 2176): 	at java.lang.Thread.run(Thread.java:864)
E/AndroidRuntime( 2176): FATAL EXCEPTION: PlayGamesAsyncThread1
E/AndroidRuntime( 2176): Process: com.google.android.gms, PID: 2176
E/AndroidRuntime( 2176): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:591)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:545)
E/AndroidRuntime( 2176): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:509)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 2176): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 2176): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:285)
E/AndroidRuntime( 2176): 	at android.content.ContentResolver.delete(ContentResolver.java:1305)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 2176): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 2176): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 2176): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 2176): 	at java.lang.Thread.run(Thread.java:864)
E/ActivityManager(  916): App crashed! Process: com.google.android.gms
D/Process ( 2176): killProcess, pid=2176
D/Process ( 2176): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop146.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
I/DisplayManagerService(  916): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  916): Recipient 2176
I/ActivityManager(  916): Process com.google.android.gms (pid 2176) has died.
D/PMS     (  916): handleWLDeath(42736668): PARTIAL_WAKE_LOCK  Icing 0x1
D/WifiService(  916): Client connection lost with reason: 4
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 11000ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 20998ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 20997ms
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 20996ms
I/ActivityManager(  916): Resuming delayed broadcast
W/ActivityManager(  916): Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 20989ms
E/SQLiteLog( 1400): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/SQLiteDBG( 1400): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.google.android.gms/databases/gcm_registrar.db, handle = 0x640842b0
W/dalvikvm( 1400): threadid=1: thread exiting with uncaught exception (group=0x4199ce30)
E/AndroidRuntime( 1400): FATAL EXCEPTION: main
E/AndroidRuntime( 1400): Process: com.google.process.gapps, PID: 1400
E/AndroidRuntime( 1400): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1400): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 1400): 	at android.app.ActivityThread.access$1700(ActivityThread.java:153)
E/AndroidRuntime( 1400): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1434)
E/AndroidRuntime( 1400): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 1400): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 1400): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/AndroidRuntime( 1400): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 1400): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 1400): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/AndroidRuntime( 1400): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/AndroidRuntime( 1400): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 1400): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 1400): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 1400): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:770)
E/AndroidRuntime( 1400): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 1400): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 1400): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1568)
E/AndroidRuntime( 1400): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 1400): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 1400): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 1400): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2687)
E/AndroidRuntime( 1400): 	... 10 more
E/ActivityManager(  916): App crashed! Process: com.google.process.gapps
E/DropBoxManagerService(  916): Can't write: system_app_crash
E/DropBoxManagerService(  916): java.io.FileNotFoundException: /data/system/dropbox/drop147.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  916): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  916): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  916): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  916): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  916): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  916): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  916): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  916): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  916): 	... 5 more
I/ActivityManager(  916): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=5056 uid=10098 gids={50098, 3003, 5012}
D/Process ( 1400): killProcess, pid=1400
D/Process ( 1400): com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:136 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 

```
