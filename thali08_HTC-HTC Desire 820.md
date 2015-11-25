#### Test 503880196dc97cd_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  906):    returned true
D/PhoneApp( 1247): EVENT_QUERY_MO_PACKAGES
D/PhoneApp( 1247): -- N1 =0
D/PhoneApp( 1247): -- N2 =0
D/PhoneApp( 1247): -- N3 =0
,D/Process (  906): killProcessQuiet, pid=3151
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
--------- beginning of /dev/log/system
I/ActivityManager(  906): Killing 3151:com.zoodles.kidmode/u0a149 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3151
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC >>
D/ContactMessageStore( 1247): MSG_NOTIFY_CS_TO_SYNC <<
E/cutils-trace( 3449): Error opening trace file: No such file or directory (2)
D/CustomizationManager( 3449): ====startRecUseTime====
D/htc.customization.log.level( 3449):  is 
W/CustomizationLogLevel( 3449): Level value is invalid, use default level 2
D/CustomizationManager( 3449):  Read ACC file spent 0.066 (s)
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3449): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3449): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3449): Parsing tag category name = system
I/CustomizationCIDLoader( 3449): Parsing tag category name = application
I/CustomizationCIDLoader( 3449): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3449): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3449): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3449): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3449): Parsing tag category name = Settings
D/CustomizationManager( 3449):  Read CID file spent 0.110 (s)
D/CustomizationManager( 3449):  All configurations done spent 0.110 (s)
W/HtcNativeFlag( 3449): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3449): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3449): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3449): Fail to get flag for type 'language', use default value: -1
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
W/dalvikvm( 3431): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3431): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3431): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3431): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3431): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/asset   (  906): Copying FileAsset 0x67833f78 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/dalvikvm( 3431): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1123883448
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3449
D/PMS     (  906): acquireHCC(42f4b508): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(43017870): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/dalvikvm( 3431): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
I/FeedHostManager( 1272): [onPause]
D/PMS     (  906): acquireWL(42ec9ad0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedProviderManager( 1272): onPause
I/FeedHostManager( 1272): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@42896bf8
I/SocialFeedProvider( 1272): +onPause
I/SocialFeedProvider( 1272): -onPause
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3460 uid=10355 gids={50355, 3003, 5012, 3001, 3002}
I/TrimMemoryManager( 1272): [trimMemory] 20
W/asset   ( 3460): Copying FileAsset 0x5c757428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 3460): Binding Chromium to main looper Looper (main, tid 1) {42463d80}
I/LibraryLoader( 3460): Expected native library version number "",actual native library version number ""
I/chromium( 3460): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3460): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(4300f110): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(42fd8048): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42f303b8:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): releaseWL(42fd8048): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothAdapter( 3460): 1111988328: getState(). Returning 12
I/Adreno-EGL( 3460): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3460): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3460): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3460): Local Branch: 
I/Adreno-EGL( 3460): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3460): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3460):                  aa63bbd948f41d15fc72f585e
W/chromium( 3460): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
W/dalvikvm( 3460): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3460): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3460): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3460): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3460): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3460): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3460): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3460): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3460): CordovaWebView is running on device made by: HTC
,W/AwContents( 3460): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  906): Disable input method client, pid=1272
W/ResourceType( 3460): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3460): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@424aacd8, mServedView=org.apache.cordova.engine.SystemWebView{42470b88 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1209): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1209): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1209): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
I/InputMethodManagerService(  906): Enable input method client, pid=3460
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +248ms
W/AwContents( 3460): nativeOnDraw failed; clearing to background color.
D/PMS     (  906): releaseWL(42ec9ad0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
W/dalvikvm( 3431): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/AndroidProtocolHandler( 3460): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/chromium( 3460): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
W/dalvikvm( 3431): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
D/JsMessageQueue( 3460): Set native->JS mode to OnlineEventsBridgeMode
E/FbInjectorInitializer( 3431): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
D/jxcore_app_log( 3460): JniHelper::setJavaVM(0x42020010), pthread_self() = 1658230640
D/JX-Cordova( 3460): jxcore cordova android initializing
W/jxcore-log( 3460): Initializing JXcore engine
W/jxcore-log( 3460): JXcore engine is ready
W/jxcore-log( 3460): Starting JXcore engine
W/fb4a(:<default>):StaticBindingVerifier( 3431): Verify
W/jxcore-log( 3460): Platform android
W/jxcore-log( 3460): 
W/jxcore-log( 3460): Process ARCH arm
W/jxcore-log( 3460): 
I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for service com.htc.mobiledata/.MobileDataService: pid=3506 uid=10091 gids={50091, 3003, 5012}
V/AlarmManager(  906): sending alarm PendingIntent{42c7afc8: PendingIntentRecord{42dc1080 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=54693, Int=0
D/WifiService(  906): New client listening to asynchronous messages
I/jxcore-log( 3460): JXcore Cordova bridge is ready!
I/jxcore-log( 3460): 
W/jxcore-log( 3460): JXcore engine is started
I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3521 uid=10091 gids={50091, 3003, 5012}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3431/10026)
W/fb4a(:<default>):BaseAnalyticsConfig( 3431): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
W/fb4a(:<default>):BaseAnalyticsConfig( 3431): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
E/jxcore-log( 3460): >> HTC-HTC Desire 820
E/jxcore-log( 3460): 
I/jxcore-log( 3460): Total memory 1964650496
I/jxcore-log( 3460): 
I/jxcore-log( 3460): Free memory 637595648
I/jxcore-log( 3460): 
I/jxcore-log( 3460): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3460): 
I/jxcore-log( 3460): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3460): 
I/jxcore-log( 3460): userPath [ 'www' ]
I/jxcore-log( 3460): 
I/jxcore-log( 3460): Size 720 1184
I/jxcore-log( 3460): 
I/jxcore-log( 3460): Screen Brightness 10
I/jxcore-log( 3460): 
E/jxcore-log( 3460): Dummy Error Log.
E/jxcore-log( 3460): 
D/MdScBoot( 3506): [6c8.1.] 30@-151102 -> 40@-151132
D/Process (  906): killProcessQuiet, pid=3177
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/Process (  906): killProcessQuiet, pid=3205
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3177:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
I/ActivityManager(  906): Killing 3205:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
I/dalvikvm-heap( 3431): Grow heap (frag case) to 9.506MB for 73240-byte allocation
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3177
I/ActivityManager(  906): Recipient 3205
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/Process (  906): killProcessQuiet, pid=3219
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3219:com.android.smith/u0a163 (adj 15): empty #17
I/ActivityManager(  906): Recipient 3219
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(432176a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1224 10028 null
D/PMS     (  906): acquireWL(42ffc420): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1224 10028 null
D/PMS     (  906): releaseWL(432176a0): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
D/WIFI_ICON( 1117): WifiActivity: 0
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
D/GCM     ( 1363): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1363/10028)
D/PMS     (  906): releaseWL(42ffc420): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1363/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1363/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1363/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3540 uid=10078 gids={50078, 3003, 5012}
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1399): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1399): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1399): service - handleMessage() setting current location null
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1399): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
I/SensorManager(  906): mEventCount = 301
W/fb4a(:<default>):UserScope( 3431): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 3431): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):UserScope( 3431): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
D/MobileConnectivityChangeReceiver( 3540): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3540): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3540): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3540): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/HtcModeClient( 1525): handler message = 4011
E/HtcModeClient( 1525): Check connection and retry 5 times.
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3555 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3231
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3231:com.google.android.youtube/u0a168 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3540/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3540/10078)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3540/10078)
D/PMS     (  906): acquireWL(42ff2d58): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1224 10028 null
D/PMS     (  906): acquireWL(4312d050): PARTIAL_WAKE_LOCK  Checkin Service 0x1 1224 10028 null
D/PMS     (  906): releaseWL(42ff2d58): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3431): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
I/CheckinService( 1224): Preparing to send checkin request
I/EventLogService( 1224): Accumulating logs since 1448459933473
W/EventLogAggregator( 1224): Unknown tag: install_package_attempt
W/EventLogAggregator( 1224): Unknown tag: snet
W/EventLogAggregator( 1224): Unknown tag: snet_gcore
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3573 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3231
D/MediaRouterService(  906): Client com.google.android.youtube (pid 3231): Died!
I/GoogleHttpClient( 1224): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 1224): Using GMS GoogleHttpClient
I/dalvikvm-heap( 3431): Grow heap (frag case) to 9.958MB for 84664-byte allocation
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1224/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/dalvikvm-heap( 3431): Grow heap (frag case) to 9.973MB for 28144-byte allocation
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [2][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1224/10028)
E/dalvikvm( 3431): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 3431): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3431): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 3431): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3431): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 3431): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3431): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 3431): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3431): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3431): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 3431): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3431): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3431): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3431): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3431): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3431): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3431): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3431): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/dalvikvm-heap( 3431): Grow heap (frag case) to 10.040MB for 39954-byte allocation
I/dalvikvm-heap( 3431): Grow heap (frag case) to 10.116MB for 79892-byte allocation
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 3573): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3573): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 3431): Grow heap (frag case) to 10.281MB for 75760-byte allocation
I/jxcore-log( 3460): getBuffer is called!!!!
I/jxcore-log( 3460): 
W/GLSUser ( 1363): GoogleAccountDataService.getToken()
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3431/10026)
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e8d078 u0 ReceiverList{42e81e88 3431 com.facebook.katana/10026/u0 remote:42b54f50}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e8d078 u0 ReceiverList{42e81e88 3431 com.facebook.katana/10026/u0 remote:42b54f50}}
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42e659e0 u0 ReceiverList{42e11130 3431 com.facebook.katana/10026/u0 remote:42a8b280}}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3573/10151)
I/GoogleHttpClient( 1363): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 1363): Using GMS GoogleHttpClient
V/WebViewChromiumFactoryProvider( 3573): Binding Chromium to main looper Looper (main, tid 1) {42468aa8}
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
I/LibraryLoader( 3573): Expected native library version number "",actual native library version number ""
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/chromium( 3573): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3573): Initializing chromium process, renderers=0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3431/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3431/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3431/10026)
,E/AudioManagerAndroid( 3573): BLUETOOTH permission is missing!
D/PMS     (  906): acquireWL(42fe2e48): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
,D/PMS     (  906): releaseWL(42fe2e48): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1363): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/Adreno-EGL( 3573): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3573): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3573): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3573): Local Branch: 
I/Adreno-EGL( 3573): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3573): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3573):                  aa63bbd948f41d15fc72f585e
D/PMS     (  906): acquireWL(42fdf000): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1414 10028 null
,D/PMS     (  906): releaseWL(42fdf000): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/NotificationStore( 1363): System rebooted after Notification storage file was last written
,I/NotificationStore( 1363): Deleting the file
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/NSApplication( 3573): Starting up...
,D/GCoreFlp( 1414): Unknown pending intent to remove.
D/PMS     (  906): acquireWL(42cc5368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1414 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3573/10151)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3573/10151)
D/PMS     (  906): releaseWL(42cc5368): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/Process (  906): killProcessQuiet, pid=3189
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{4280a5d0 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
,W/CheckinRequestBuilder( 1224): awaiting user notification for token
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3615 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
I/ActivityManager(  906): Killing 3189:com.android.settings/1000 (adj 15): empty #17
I/RemoteViews.Performance( 1117): com.google.android.gms 2 10 3 12
I/ActivityManager(  906): Recipient 3189
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3431): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3431): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3627 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 3627): install
,I/MultiDex( 3627): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 3627): loading existing secondary dex files
,I/MultiDex( 3627): load found 1 secondary dex files
,I/MultiDex( 3627): install done
,I/ProviderInstaller( 3627): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,D/PMS     (  906): acquireWL(4311ada0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3615 10160 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3615/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3615/10160)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3615/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3615/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1856/10178)
D/PMS     (  906): acquireWL(42ee85f8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3615 10160 null
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/AlertReceiver( 3350): beginStartingService
,D/PMS     (  906): releaseWL(4311ada0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42cece98): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3350 10013 null
D/PMS     (  906): acquireWL(42f4db88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(42f4db88): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/PMS     (  906): releaseWL(42ee85f8): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
D/AlertService( 3350): start to updateAlertNotification!
,D/AlertService( 3350): No fired or scheduled alerts
,D/HtcAlertUtils( 3350): -- cancelReminderNotification --
,D/HtcAlertUtils( 3350): broadcastExistReminder!
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3350): stopSelfResult true,
D/Process (  906): killProcessQuiet, pid=3284
D/PMS     (  906): releaseWL(42cece98): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,I/ActivityManager(  906): Killing 3284:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/WeatherUtility( 3395): can't get weather sync account
I/ActivityManager(  906): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3657 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
,W/WeatherRequest( 1117): request cur loc, but there is no sys cur
,I/ActivityManager(  906): Recipient 3284
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherRequest( 3395): request cur loc, but there is no sys cur
,W/Settings( 3395): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(42f4b508): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
D/PMS     (  906): releaseHCC(43017870): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
D/WIFI_ICON( 1117): WifiActivity: 3
D/AppWidgetHostView( 1272): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1272): com.htc.widget.weatherclock (true,33751552)
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,I/RemoteViews.Performance( 1272): com.htc.widget.weatherclock 3 11 17
D/PMS     (  906): acquireWL(42fe0ed8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3657 10070 null
D/PMS     (  906): acquireWL(42cd9c08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3657 10070 null
D/PMS     (  906): releaseWL(42fe0ed8): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3672 uid=10090 gids={50090, 3003, 5012, 1028}
,D/TodoTaskshortcut( 3657): update TASK shortcut>
,I/WorldClock.Global( 3672): isHtcDevice = true
,I/TodoTaskNotifyService( 3657): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,W/ContextImpl( 3165): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,I/WorldClock.Global( 3672): isHtcDevice = true
,I/TodoTaskNotifyService( 3657): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,I/WorldClock.AlarmUtils( 3672): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/WorldClock.AlarmUtils( 3672): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3672): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3687 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/IntentController( 1117): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/PMS     (  906): releaseWL(42cd9c08): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -60 abnormalRssiCnt = 0 newLinkSpeed = 24
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/NotifyReceiver( 3657): stopSelfResult true
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,D/Process (  906): killProcessQuiet, pid=3323
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3323:com.google.android.partnersetup/u0a31 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3323
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TimeService( 3687): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1448460693965
,D/Process (  906): killProcessQuiet, pid=3335
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3335:com.htc.contacts/u0a41 (adj 15): empty #17
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3703 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/DemoRecovery.RestoreReceiver( 3703): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
,W/ContextImpl( 3703): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
,I/RestoreService( 3703): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(43018d20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3657 10070 null
,I/ActivityManager(  906): Recipient 3335
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): acquireWL(42f9ce58): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3657 10070 null
,I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/TodoTaskshortcut( 3657): update TASK shortcut>
D/PMS     (  906): releaseWL(43018d20): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,I/TodoTaskNotifyService( 3657): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  906): releaseWL(42f9ce58): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3368
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,W/NotifyReceiver( 3657): stopSelfResult true
I/ActivityManager(  906): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3720 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  906): Killing 3368:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3368
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3732 uid=10081 gids={50081, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3408
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3408:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=3381
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 1224): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1224): Unauthorized to start the main service
,D/GCM     ( 1363): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  906): Killing 3381:com.htc.mms.backupagent/u0a77 (adj 15): empty #18
I/ActivityManager(  906): Recipient 3381
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3745 uid=10038 gids={50038}
,I/ActivityManager(  906): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3758 uid=10077 gids={50077}
,D/Process (  906): killProcessQuiet, pid=3431
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3431:com.facebook.katana/u0a26 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3408
,D/MediaRouterService(  906): Client com.google.android.music (pid 3408): Died!
,I/ActivityManager(  906): Recipient 3431
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  906): Client connection lost with reason: 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3627/10028)
,D/PMS     (  906): acquireWL(4322d898): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1414 10028 null
,D/PMS     (  906): acquireWL(4322d848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1414 10028 null
,D/PMS     (  906): releaseWL(4322d898): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(4322d848): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/SMSBackup( 3758): Got a database change event
,D/Process (  906): killProcessQuiet, pid=3506
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3773 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
I/ActivityManager(  906): Killing 3506:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3506
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3773): create image Cache, size: 31457280.
I/ImageRamCache( 3773): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3773): create image Cache, size: 12582912.
,I/FeedSettings( 3773): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3773): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3773): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3773): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3773): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3773): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3773): [custom highlight] onReceive
,D/CustomHighlightService( 3773): [custom highlight] onHandleIntent
,D/NewsDB  ( 3773): set custom highlight []
I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/MessagingNotification( 2782): New incoming message, can't cancel notification now
,D/MessagingNotification( 2782): newMsgCnt: 0, false
,D/CustomHighlightService( 3773): [custom highlight] set tags 
I/Adreno-EGL( 3627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3627): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3627): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3627): Local Branch: 
I/Adreno-EGL( 3627): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3627): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3627):                  aa63bbd948f41d15fc72f585e
D/MessagingShortcutReceiver( 2782): keep hiding shortcut bubble
D/MessagingShortcut( 2782): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2782): After query: 0
D/MessagingShortcut( 2782): mPresentUnreadCount: -1
D/MessagingShortcut( 2782): setMsgShortcutDrawable> 0
D/MessagingShortcut( 2782): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
I/ActivityManager(  906): Resuming delayed broadcast
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] reorderNotification, total:0
D/DotMatrix( 1585): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1585): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
D/TodoTaskshortcut( 3657): update TASK shortcut>
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
,D/HtcBroadcastReceiver( 1247): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  906): killProcessQuiet, pid=3521
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3521:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3521
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3792 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3806 uid=10091 gids={50091, 3003, 5012}
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3540:com.google.android.setupwizard/u0a78 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3540
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/GCM     ( 1363): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  906): Recipient 3540
,D/MdScBoot( 3792): [908.1.] 40@-151132
,D/MtpReceiver( 2459): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2459): [MTP][handleMessage][startService]
,D/MtpReceiver( 2459): [MTP][MtpReceiver][onReceive]1-
D/Process (  906): killProcessQuiet, pid=3555
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Killing 3555:com.android.chrome/u0a96 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
D/MtpReceiver( 2459): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
D/MtpReceiver( 2459): [MTP][handleMessage]-
,I/ActivityManager(  906): Recipient 3555
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/MtpService( 2459): [MTP] startForeground
,D/Process (  906): killProcessQuiet, pid=3573
I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3819 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
,I/ActivityManager(  906): Killing 3573:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
I/RemoteViews( 1117): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1117): com.android.providers.media 1 1 10
I/RemoteViews( 1117): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1117): com.android.providers.media 1 1 15
D/MtpService( 2459): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2459): TotalSize=1918604,MediaCacheLimit=6000
,D/PMS     (  906): acquireWL(42c8fb30): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3615 10160 null
D/MtpService( 2459): [isMtpConnected] connected: true
,I/dalvikvm-heap( 3615): Grow heap (frag case) to 15.215MB for 1821008-byte allocation
,D/PMS     (  906): releaseWL(4300f110): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,D/SyncApplication( 3819): Loading default preferences
I/ActivityManager(  906): Recipient 3573
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/Resources( 3819): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/PMS     (  906): releaseWL(42c8fb30): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/WifiService(  906): New client listening to asynchronous messages
,I/Adreno-EGL( 3627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3627): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3627): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3627): Local Branch: 
I/Adreno-EGL( 3627): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3627): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3627):                  aa63bbd948f41d15fc72f585e
,D/SyncApplication( 3819): Overriding preferences with custom values
,D/SyncApplication( 3819): Updating preferences succeeded
,E/SyncApplication( 3819): Application created.
D/VolumeInfo( 3819): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3819): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3819): Found 0 mount point(s)
,V/VolumeInfo( 3819): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3819): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3819): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3819): Can not create volume ID for unmounted volume null
,I/Adreno-EGL( 3627): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3627): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3627): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3627): Local Branch: 
I/Adreno-EGL( 3627): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3627): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3627):                  aa63bbd948f41d15fc72f585e
,I/CalendarDefines( 3819): getNewCalendarAuthority()...
,D/SyncApplication( 3819): enableAppOperation()+
,D/SyncApplication( 3819): enableAppOperation()-
,D/HTCUtilities( 3819): isNeorSinged() + 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3819, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3819, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3819): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3819): isNeorSinged() return false
D/CDMountReceiver( 3819): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3819): USB connected to PC
,W/Settings( 3627): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/FOTAReceiver( 3819): onReceive() enter 
,D/FOTAReceiver( 3819): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3842 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3350
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3350:com.htc.calendar/u0a13 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3350
,I/CheckinTask( 1224): Sending checkin request (8949 bytes)
,D/HtcFingerPrintQuickLaunchProvider( 3842): -onCreate(),
,V/Settings:HtcSettingsApplication( 3842): [3842/3842] onCreate()
,D/TetherSettings( 3842): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3842): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3842): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3842): Cust_ConnectToPC   : spcsc>false
D/        ( 3842): Cust_ConnectToPC   : IPT>true
,D/        ( 3842): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3842): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/TetherSettings( 3842): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3842): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3842): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3842): Cust_ConnectToPC   : spcsc>false
D/        ( 3842): Cust_ConnectToPC   : IPT>true
D/        ( 3842): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3842): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3842): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3842): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,D/SmartNS_NSReceiver( 3842): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3842): usb_cable_connect = 1
,W/ActivityThread( 1224): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/SmartNS_Utility( 3842): usb_denied = 0
I/SmartNS_NSReceiver( 3842): locked:falsesecurity:falseisLocked:false
D/SmartNS_NSReceiver( 3842): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3842): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3842): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
I/SmartNS_PSService( 3842): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/Settings( 3842): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/SmartNS_PSService( 3842):  defaultType:0
,I/SmartNS_PSService( 3842): fail notificaiton:false
D/SmartNS_Utility( 3842): usb_cable_connect = 1
D/SmartNS_Utility( 3842): usb_denied = 0
,I/SmartNS_PSService( 3842): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3842/1000)
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,D/SmartNS_Utility( 3842): usb_cable_connect = 1
,I/RemoteViews( 1117): com.android.settings (true,33751552)
D/SmartNS_Utility( 3842): usb_denied = 0
I/SmartNS_PSService( 3842): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/RemoteViews.Performance( 1117): com.android.settings 2 1 10
,D/libc    ( 1224): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
V/Tethering(  906): bSetPropertyMultiRAB:false
D/libc    ( 1224): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    ( 1224): [NET] getaddrinfo-, 1
,D/libc    ( 1224): [NET] getaddrinfo_proxy+
D/libc    (  363): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
,D/libc    (  363): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  363): [NET] +++++ res_nsend xid =9118 +++++
D/libc    (  363): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  363): [NET] NOT IN CACHE
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3842/1000)
I/ActivityManager(  906): Resuming delayed broadcast
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,D/SmartNS_Utility( 3842): usb_cable_connect = 1
,D/SmartNS_Utility( 3842): usb_denied = 0
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,W/WeatherUtility( 3395): can't get weather sync account
I/SmartNS_PSService( 3842): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3842): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews( 1117): com.android.settings (true,33751552)
I/RemoteViews.Performance( 1117): com.android.settings 2 0 10
,D/AppWidgetHostView( 1272): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
,I/RemoteViews( 1272): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1272): com.google.android.googlequicksearchbox 1 0 5
,W/WeatherRequest( 3395): request cur loc, but there is no sys cur
,W/Settings( 3395): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1272): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
I/ActivityManager(  906): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
,I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews( 1272): pl.k2.droidoaudioteka (false,0)
D/libc    (  363): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 299
D/libc    (  363): [NET]res_nsend:resplen=84
D/libc    (  363): [NET]res_queryN: exit 3, ancount=2
D/libc    (  363): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/RemoteViews.Performance( 1272): pl.k2.droidoaudioteka 2 0 8
D/libc    ( 1224): [NET] getaddrinfo_proxy-, success
,D/SMSBackup( 3758): Got a database change event
,D/PMS     (  906): acquireWL(42c5aee0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/AppWidgetHostView( 1272): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1272): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1272): com.htc.widget.weatherclock 1 5 17
D/PMS     (  906): releaseWL(42c5aee0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/PMS     (  906): acquireWL(42c0d248): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1525 10014 null
I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  906): releaseWL(42c0d248): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
D/libc    ( 1224): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
D/libc    ( 1224): [NET] getaddrinfo-,err=8
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/PMS     (  906): acquireWL(43121f80): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(43121f80): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,V/AlarmManager(  906): sending alarm PendingIntent{42c9ac48: PendingIntentRecord{42c06d30 com.google.android.gms startService}}, i=null, t=0, cnt=17057, w=84918423, Int=84918423
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,I/AdsMeasurementBroadcastReceiver( 1224): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 1224): Unauthorized to start the main service
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/SnetService( 1224): snet destroyed
D/WifiDataStallTracker(  906): updateDataStallInfo: mDataStallTxRxSum={txSum=34 rxSum=24} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  906): updateDataStallInfo: IN/OUT
,D/WifiDataStallTracker(  906): onDataStallAlarm: tag=20505 Sent 0 pkts since last received, < watchdogTrigger=5
,D/WifiDataStallTracker(  906): startDataStallAlarm: tag=20506 delay=15s
,D/PackageBroadcastService( 1224): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  906): acquireWL(42d35648): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(42d35648): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 1224): CP2 sync disabled
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=1224, uid=10028, userID:0
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  906): acquireWL(42f0e0a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10028 null
,D/PMS     (  906): releaseWL(42f0e0a8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1224/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [15][0][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1224/10028)
,W/GLSUser ( 1363): GoogleAccountDataService.getToken()
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1363): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 1224): awaiting user notification for token
D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{42529818 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress},
,I/ActivityManager(  906): Resuming delayed broadcast
I/RemoteViews.Performance( 1117): com.google.android.gms 2 9 3 12
,I/ActivityManager(  906): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=3884 uid=10031 gids={50031, 3003, 5012}
,I/CheckinTask( 1224): Sending checkin request (2418 bytes)
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3672
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3672:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  906): Recipient 3672
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/[PluginManager]RegisterService( 1399): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1399): handle notify Blinkfeed plugin client changed
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=3900 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=3900, uid=10073, userID:0
,D/Finsky  ( 3900): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/SocialFeedProvider( 1272): +disConnect socialManager
,I/SocialFeedProvider( 1272): disconnect socialManager
,I/SocialFeedProvider( 1272): -disConnect socialManager
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3900/10073)
D/ConnectivityService(  906): getAllNetworkInfo called by com.android.vending (3900/10073)
,D/Finsky  ( 3900): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 3900): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3900): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Process (  906): killProcessQuiet, pid=3165
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3165:com.android.settings:remote/1000 (adj 15): empty #17
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=3900, uid=10073, userID:0
,I/ActivityManager(  906): Recipient 3165
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3687
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Killing 3687:com.qualcomm.timeservice/1000 (adj 15): empty #17
D/Prism.PackageStateRece_( 1272): action: android.intent.action.PACKAGE_ADDED
D/Finsky  ( 3900): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3900): [1] 2.run: Finished loading 1 libraries.
I/ActivityManager(  906): Recipient 3687
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/IcingCorporaProvider( 2928): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/ActivityManager(  906): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=3933 uid=10098 gids={50098, 3003, 5012}
,D/PMS     (  906): acquireWL(42f8e7a0): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,I/DeviceManagement( 3933): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=3933 dbg=false s=true
,I/DeviceManagement( 3933): PackageUpdateReceiver: vvv Package added: [com.example.hello]
,I/ActivityManager(  906): Delay finish: com.htc.cs.dm/.receiver.PackageUpdateReceiver
,D/Process (  906): killProcessQuiet, pid=3703
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3703:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
D/PMS     (  906): acquireWL(424575f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10028 null
D/PMS     (  906): releaseWL(424575f8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,I/ActivityManager(  906): Recipient 3703
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PMS     (  906): releaseWL(42f8e7a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=3948 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (1224/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (1224/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/PMS     (  906): acquireWL(431a8750): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1164): environment dirty rate=0 [5][0][0]
,D/Finsky  ( 3900): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  906): Delaying start of: ServiceRecord{42fcd2a8 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,W/GLSUser ( 1363): GoogleAccountDataService.getToken()
,D/PMS     (  906): releaseWL(431a8750): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1363): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,D/PMS     (  906): acquireWL(42ff5b40): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/Finsky  ( 3900): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/DotMatrix( 1585): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 1224): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{425b04d8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,D/PMS     (  906): releaseWL(42ff5b40): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 5 3 12
D/PMS     (  906): acquireWL(42f25250): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,I/CheckinTask( 1224): Checkin success: https://android.clients.google.com/checkin (2 requests sent)
,W/GoogleHttpClient( 1224): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/PMS     (  906): releaseWL(42f25250): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42f0ea00): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (1224/10028)
,D/PMS     (  906): releaseWL(42f0ea00): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42f07b98): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(4312d050): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 1224): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@427781c8 that was originally bound here
E/ActivityThread( 1224): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@427781c8 that was originally bound here
E/ActivityThread( 1224): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 1224): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 1224): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 1224): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 1224): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 1224): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 1224): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 1224): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 1224): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 1224): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 1224): 	at bkt.a(SourceFile:226)
E/ActivityThread( 1224): 	at bks.a(SourceFile:298)
E/ActivityThread( 1224): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 1224): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 1224): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 1224): 	at java.lang.Thread.run(Thread.java:864)
,D/PMS     (  906): releaseWL(42f07b98): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42efde00): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(42efde00): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42dd66c8): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(42dd66c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42d0a9f0): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(42d0a9f0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(4285eb18): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(4285eb18): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  906): acquireWL(42ceffd0): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,D/PMS     (  906): releaseWL(42ceffd0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2928): Copying FileAsset 0x5cbd4168 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/PMS     (  906): acquireWL(42d4c7c8): PARTIAL_WAKE_LOCK  Icing 0x1 1224 10028 null
,I/IcingCorporaProvider( 2928): UpdateCorporaTask done [took 549 ms] updated apps [took 548 ms] 
,I/ActivityManager(  906): Delay finish: com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3948/10100)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3948/10100)
,W/GAV2    ( 3948): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: survey data missing!
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1164): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -61 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 96
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1164): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,V/AlarmManager(  906): sending alarm PendingIntent{42f69d48: PendingIntentRecord{42f28f78 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1448460697001, Int=0
I/SocialManager[SocialBiLogHelper]( 3773): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3773): last commit ulog time 1448443159813
I/SocialManager[SocialBiLogHelper]( 3773): skip commit this time
,I/ActivityManager(  906): Resuming delayed broadcast
,W/GAV2    ( 3948): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  906): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=3977 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
V/AlarmManager(  906): sending alarm PendingIntent{42f904b0: PendingIntentRecord{42ee9828 com.android.vending startService}}, i=null, t=0, cnt=1, w=1448460697158, Int=0
,V/AlarmManager(  906): sending alarm PendingIntent{42755958: PendingIntentRecord{42e1c660 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59522, Int=0
,W/GLSUser ( 1363): GoogleAccountDataService.getToken(),
,I/htcbackup-core( 3977): ModelRegistry: Loading model meta data from resources...
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1363): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/ContextImpl( 3977): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 3977): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/ActivityManager(  906): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=3996 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
,D/Process (  906): killProcessQuiet, pid=3720
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/DeviceManagement( 3933): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
I/ActivityManager(  906): Killing 3720:com.htc.stock/u0a81 (adj 15): empty #17
,I/DeviceManagement( 3933): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.htc.home.personalize, com.htc.feedback, com.qualcomm.privinit, com.android.settings, com.android.CSDFunctionG, com.android.keychain, com.htc.backupreset, com.htc.smartdim, android, com.android.location.fused, com.htc.drive.activator, com.htc.mirrorlinkserver, com.htc.android.htcsetupwizard, com.htc.htcpowermanager, com.htc.autobot.cargps.provider, com.htc.guide, com.android.inputdevices, com.htc.android.htcloglevel, com.htc.cirmodule, com.htc.backup, com.htc.usage, com.htc.checkinprovider, com.android.providers.settings, com.qualcomm.timeservice, com.htc.lockscreen]
,I/DeviceManagement( 3933): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3720
,I/DeviceManagement( 3933): WorkflowService: Starting workflow service
I/DeviceManagement( 3933): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4249c958] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 3933): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DeviceManagement( 3933): ModelRegistry: Loading model meta data from resources...
,W/GLSUser ( 1363): GoogleAccountDataService.getToken()
,D/HtcCupdReceiver(Provider)( 3996):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,I/ActivityManager(  906): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
I/DeviceManagement( 3933): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
I/DeviceManagement( 3933): SessionStateController: Checking invariants...
W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1363): GLS error: BadAuthentication thalitester@gmail.com androidmarket
W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 3900): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 3900): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,I/DeviceManagement( 3933): ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@429c9598 mBinding = false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
,W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1246
W/Settings:Agent(  906): Process.myUid(): 1000
,W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 6(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  906): Sending off request.
D/BluetoothAdapterState( 1613): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1613): Setting state to 13
I/BluetoothAdapterState( 1613): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1613): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  906): +onBluetoothStateChange prev=12 new=13
,D/BluetoothAdapterProperties( 1613): onBluetoothDisable()
D/WifiManager( 3460): setWifiEnabled: Base Package Name=com.example.hello, uid=10355
I/bt-btm  ( 1613): BTM_SetDiscoverability
I/bt-btm  ( 1613): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1613): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1613): br_edr_supported=0x0
I/bt-btm  ( 1613): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1613): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1613): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1613): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1613): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1613): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1613): BTM_SetConnectability
I/bt-btm  ( 1613): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1613): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1613): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
E/BTIF_CORE( 1613): NETI system_power_manager_wake : 259 param 1
I/bt-btif ( 1613): HAL bt_hal_cbacks->wake_state_changed_cb
I/BluetoothAdapterState( 1613): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 12 -> 13
D/BluetoothRemoteDevices( 1613): Wake lock Aquired
I/bt-btif ( 1613): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 1613): adapterPropertyChangedCallback with type:7 len:4
,I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1270
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
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
,W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
D/WifiService(  906): New client listening to asynchronous messages
D/PMS     (  906): acquireWL(42f3e430): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1613 1002 null
D/WifiService(  906): setWifiEnabled: false pid=3460, uid=10355
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
,D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
V/BluetoothPbapReceiver( 1613): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1613): ***********state = 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1823): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1823): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@4248a440
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1823): onDeInitialized
D/BluetoothAdapterProperties( 1613): Scan Mode:20
D/BluetoothAdapterState( 1613): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothMasReceiver( 1613): Bluetooth STATE CHANGED to 13
I/bt-btif ( 1613): BTA_JvDeleteRecord
V/BluetoothSapReceiver( 1613): SapReceiver onReceive 
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1823): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1823): getNotificationManager
V/BluetoothSapReceiver( 1613): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1613):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 1613): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1613): Pbap Service closeService in
D/PMS     (  906): acquireWL(42f57588): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3842 1000 null
I/bt-btif ( 1613): BTA_JvRfcommStopServer
D/bt-btm  ( 1613): BTM_FreeSCN 
I/bt-btif ( 1613): BTA_JvDeleteRecord
I/bt-btif ( 1613): BTA_JvRfcommStopServer
D/bt-btm  ( 1613): BTM_FreeSCN 
I/bt-btif ( 1613): BTA_JvDeleteRecord
I/bt-btif ( 1613): BTA_JvRfcommStopServer
D/bt-btm  ( 1613): BTM_FreeSCN 
I/bt-btif ( 1613): BTA_JvDeleteRecord
I/bt-btif ( 1613): BTA_JvRfcommStopServer
D/bt-btm  ( 1613): BTM_FreeSCN 
I/bt-btif ( 1613): BTA_JvDeleteRecord
I/bt-btif ( 1613): BTA_JvRfcommStopServer
D/bt-btm  ( 1613): BTM_FreeSCN 
I/bt-btif ( 1613): BTA_JvDeleteRecord
I/bt-btif ( 1613): BTA_JvRfcommStopServer
D/bt-btm  ( 1613): BTM_FreeSCN 
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:15
E/bt-btif ( 1613): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1613): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1613): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1613): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1613): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1613): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1613): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1613): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1613): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1613): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1613): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1613): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1613): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1613): Write Extended Inquiry Response to controller
I/bt-btm  ( 1613): Write Extended Inquiry Response to controller
I/bt-btm  ( 1613): Write Extended Inquiry Response to controller
I/bt-btm  ( 1613): Write Extended Inquiry Response to controller
I/bt-btm  ( 1613): BTM_SetDiscoverability
I/bt-btm  ( 1613): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1613): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1613): br_edr_supported=0x0
I/bt-btm  ( 1613): mode == BTM_BLE_NON_DISCOVERABLE 
V/BluetoothSapService( 1613): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/bt-btm  ( 1613): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1613): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1613): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1613): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1613): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1613): BTM_SetConnectability
I/bt-btm  ( 1613): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1613): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1613): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1613): BTM_IsInquiryActive
I/bt-btm  ( 1613): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1613): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1613): BTM_FreeSCN 
I/bt-btm  ( 1613): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1613): BTM_FreeSCN 
I/bt-btm  ( 1613): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1613): AVRC_Close handle:0
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1613): SDP_DeleteRecord ok, num_records:3
,W/bt-l2cap( 1613): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1613): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1613): GATT_Deregister gatt_if=3
I/bt-att  ( 1613): GATT_Deregister gatt_if=4
E/BtOppRfcommListener( 1613): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1823): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1823): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1823):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1823): writeLinkLossAlertLevelAll: 0, false
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1823): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1823): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1823):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1823): deinit: 0
D/BluetoothManagerService(  906): Message: MESSAGE_UNREGISTER_ADAPTER
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1823): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1823): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1823): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1823): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1823): init: null
D/BluetoothManagerService(  906): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42d068b0:true
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1823): setPendingRequestAlarm: false, mContext = null, null
W/ContextImpl( 3842): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
V/BluetoothPbapService( 1613): successfully stopped pbap service
V/BluetoothPbapService( 1613): Pbap Service closeService out
V/BluetoothSapService( 1613): action: android.bluetooth.adapter.action.STATE_CHANGED
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1823): Exit IdleState
V/BluetoothSapService( 1613): state: 13
D/BluetoothAdapter( 1613): 1112026032: getState(). Returning 13
V/BluetoothSapService( 1613): Stopping SAP server process
D/PMS     (  906): releaseWL(42f57588): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  906): acquireWL(42fcccb8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3842 1000 null
I/jxcore-log( 3460): ****TEST TOOK:  5104  ms ****
I/jxcore-log( 3460): 
I/jxcore-log( 3460): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3460): 
D/WirelessDisplayService(  906): getMirrorDisplayStatus:falsecurState:1
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42dc3128:true
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/LocationAgent( 3842): new LocationAgent instance!!
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
D/HtcTagManager( 3842): HtcTagManager construction complete
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  906): acquireWL(42f8a2c8): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
V/BluetoothSapService( 1613): Sap Service closeSapService in
V/BluetoothSapService( 1613): Close listen Socket : 
V/BluetoothSapService( 1613): Close rfcomm Socket : 
V/BluetoothSapService( 1613): Close sapd  Socket : 
V/BluetoothSapReceiver( 1613): BluetoothSapReceiver deinit
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
V/BluetoothSapService( 1613): successfully stopped Sap service
V/BluetoothSapService( 1613): Sap Service closeSapService out
I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
I/BtOppRfcommListener( 1613): stopping Accept Thread
I/BtOppRfcommListener( 1613): BluetoothSocket listen thread finished
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4016 uid=10037 gids={50037, 3002, 3001}
D/WifiP2pService(  906): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/PhoneStatusBar( 1117): removeIcon slot=bluetooth index=12 viewIndex=0
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothPbapService( 1613): Pbap Service onDestroy
V/BluetoothPbapService( 1613): Pbap Service closeService in
V/BluetoothPbapService( 1613): Pbap Service closeService out
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/BluetoothAdapter( 3842): 1112427568: getState(). Returning 13
I/DeviceManagement( 3933): SessionStateController: Checking invariants...
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
D/BluetoothInputDevice( 3842): BluetoothInputDevice()
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=20506 mDataStallAlarmIntent=PendingIntent{42f44ad8: PendingIntentRecord{42c5ad20 android broadcastIntent}}
D/BluetoothManagerService(  906): registerStateChangeCallback+
V/BluetoothSapService( 1613): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@424bccc0
V/BluetoothSapService( 1613): Sap Service closeSapService in
V/BluetoothSapService( 1613): Close listen Socket : 
V/BluetoothSapService( 1613): Close rfcomm Socket : 
V/BluetoothSapService( 1613): Close sapd  Socket : 
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/BluetoothAdapter( 3842): 1112427568: getState(). Returning 13
D/BluetoothInputDevice( 3842): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3842): Bluetooth service connected
W/BluetoothInputDevice( 3842): Proxy not attached to service
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/BluetoothPan( 3842): BluetoothPan()
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
D/BluetoothManagerService(  906): registerStateChangeCallback+
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/BluetoothManagerService(  906): Registered receivers: 8
D/WifiNative-wlan0(  906):    returned null
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
V/BluetoothSapService( 1613): Sap Service closeSapService out
V/BluetoothSapService( 1613): ***onDestroyed***
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  906): Call handleNetworkDisconnect() in SupplicantStoppingState
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1164): Power_Mode_Type mode = 0
I/wpa_supplicant( 1164): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 61
D/BluetoothAdapter( 3842): 1112427568: getState(). Returning 13
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/BluetoothPan( 3842): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3842): Bluetooth service connected
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
D/UsbnetStateTracker(  906): isAvailable+-
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1164): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1164): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  906):    returned true
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/WifiP2pService(  906): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pDisablingState
D/WifiP2pService(  906): P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): p2p socket connection lost
D/WifiP2pService(  906): P2pDisabledState
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WifiDisplayController(  906): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  906): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  906): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  906): set wifi.miracastlock to 0 for disconnect case
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/WifiP2pService(  906): P2pDisabledState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-2ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothMap( 3842): Create BluetoothMap proxy object
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 9
E/BluetoothMap( 3842): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/AudioService(  906): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  906):     Client/Owner: Client
V/AudioService(  906):     GroupId: 
V/AudioService(  906):     Passphrase: 
V/AudioService(  906):     SessionId: 0
V/AudioService(  906):     IP Address: }
D/HtcEffectManagerBase(  906): onEventChanged id=5 status=false
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/HtcEffectManager(  906): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  906): convertEffect before=902
D/HtcEffectManager(  906): convertEffect after=902
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3842): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Registered receivers: 10
D/WifiNative-p2p0(  906): doBoolean: TERMINATE
W/WifiHW  (  906): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1164): Supplicant Terminat @ wpa_supplicant_deinit function
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/wpa_supplicant( 1164): TDLS: Tear down peers
I/wpa_supplicant( 1164): wpa_driver_nl80211_disconnect(reason_code=3)
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  906): updateConnection
I/WifiDisplayController(  906): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  906): updateConnection enter step 4
D/WifiDisplayController(  906): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiNative-p2p0(  906):    returned true
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/BluetoothPbap( 3842): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '30 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 30 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
W/ContextImpl( 3842): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 3842): 1112427568: getState(). Returning 13
D/BluetoothPbap( 3842): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3842): Bluetooth service connected
D/LocalBluetoothProfileManager( 3842): LocalBluetoothProfileManager construction complete
D/BluetoothManagerService(  906): Registered receivers: 11
,I/Icing   ( 1224): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/DockEventReceiver( 3842): finishStartingService: stopping service
D/WISPrService( 3842): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=0 what=131282 target=com.android.internal.util.StateMachine$SmHandler }
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1164): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/wpa_supplicant( 1164): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/WISPrService( 3842): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/wpa_supplicant( 1164): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1164): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb7c52bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1164):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1164): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1164): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1164): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING (0)+
I/wpa_supplicant( 1164): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/PMS     (  906): releaseWL(42fcccb8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/WifiService(  906): New client listening to asynchronous messages
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/WISPrService( 3842): >>>>>WISPrService start isConnected = false<<<<<
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/libc    (  363): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/libc    (  363): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  363): [NET] getaddrinfo-, SUCCESS
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2462
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2462
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/WISPrService( 3842): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/HtcBtWidget_BTWidgetProvider( 4016): onBTStateChanged() for widget: 
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/HtcBtWidget_BTWidgetProvider( 4016): updateWidget(context) for widget: 
D/Tethering(  906): [isWifi] getHotspotEnabled: false
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 31 Failed to remove route from default table (No such process)'
D/C,onnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '32 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 32 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/Process (  906): killProcessQuiet, pid=3732
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/libc    (  363): [NET] entry_id:5   entry:0xb748c818  removed 
D/libc    (  363): [NET] entry_id:3   entry:0xb748c1d0  removed 
D/libc    (  363): [NET] entry_id:2   entry:0xb748c108  removed 
D/libc    (  363): [NET] entry_id:6   entry:0xb748c6f0  removed 
D/libc    (  363): [NET] entry_id:4   entry:0xb748bfd8  removed 
D/libc    (  363): [NET] entry_id:1   entry:0xb748c410  removed 
D/libc    (  363): *************************
D/libc    (  363): *** DNS CACHE FLUSHED ***
D/libc    (  363): *************************
I/ActivityManager(  906): Killing 3732:com.htc.stock:remote/u0a81 (adj 15): empty #17
D/PMS     (  906): acquireWL(42fe7010): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1363 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1363/10028)
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(42ffa060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1363 10028 null
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
E/BluetoothFtpService:RfcommSocketAcceptThread( 1613): Shutdown
I/HtcModeClient( 1525): handler message = 4011
E/HtcModeClient( 1525): Check connection and retry 6 times.
D/BluetoothMasReceiver( 1613): Bluetooth STATE CHANGED to 13
I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
,I//system/bin/ip(  363): RTNETLINK answers: No such process
,I/logwrapper(  363): /system/bin/ip terminated by exit(2)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/PMS     (  906): acquireWL(42d0c450): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1363/10028)
D/PMS     (  906): releaseWL(42fe7010): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  906): releaseWL(42ffa060): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1823): Received state change = 13
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1823): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@4248a440
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1823): onDestroy() called...
,I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1823): deinitLeServices: null
,I/DeviceManagement( 3933): ConfigManagerController: Retrieving config content from cache: appID=com.htc.backup includeMeta=true
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1363/10028)
I/ActivityManager(  906): Recipient 3732
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1363/10028)
,I/DeviceManagement( 3933): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@4249c958]
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4040 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/DeviceManagement( 3933): WorkflowService: Stopping workflow service
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=2782
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 2782:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/PMS     (  906): releaseWL(42d0c450): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,I/ActivityManager(  906): Delay finish: com.google.android.apps.plus/.service.PackagesMediaMonitor
,D/PMS     (  906): acquireWL(43016800): PARTIAL_WAKE_LOCK  AsyncService 0x1 3615 10160 null
,D/PMS     (  906): releaseWL(43016800): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,W/bt-btif ( 1613): ag scb idx 1 not allocated
,W/bt-btif ( 1613): ag scb idx 2 not allocated
E/bt-btif ( 1613): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1613): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1613): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1613): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1613): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1613): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1613): L2CAP - PSM: 0x0017 not found for deregistration
,V/Settings:HtcSettingsApplication( 4040): [4040/4040] onCreate()
I/ActivityManager(  906): Resuming delayed broadcast
,D/WifiService(  906): New client listening to asynchronous messages
,E/bt_userial_mct( 1613): userial_close userial_thread_created userial_running is 1 
,E/wpa_supplicant( 1164): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1164): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 1164): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,D/Process (  906): killProcessQuiet, pid=3657
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3657:com.htc.task/u0a70 (adj 15): empty #17
,W/Parcel  ( 3615): Reading a NULL string not supported here.
,E/cutils-trace( 4034): Error opening trace file: No such file or directory (2)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 2782
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=4063 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  906): killProcessQuiet, pid=3792
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3792:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,D/wpa_supplicant( 1164): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1164): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1164): nl80211: Unsubscribe mgmt frames handle 0xb7c53718 (mode change)
I/wpa_supplicant( 1164): htc_wext_command_deinit +
I/wpa_supplicant( 1164): htc_wext_command_deinit -
E/wpa_supplicant( 1164): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
,I/wpa_supplicant( 1164): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1164): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1164): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1164): TDLS: Tear down peers
I/wpa_supplicant( 1164): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1164): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1164): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1164): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1164): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1164): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1164): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,E/wpa_supplicant( 1164): send_and_recv error 0 - cmd 18
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/ActivityManager(  906): Recipient 3792
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x627969a0
I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x62152970
W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
,D/Settings:HtcWirelessFeatureFlags( 3842): id/is att sku: 99/false
,W/SystemReader( 3842): Cannot find devicepolicy_lower_fp_quality, use default value instead
I/ActivityManager(  906): Recipient 3657
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiStateMachine(  906): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  906): doBoolean: SET_WIFI_ON 0
D/WifiNative-wlan0(  906):    returned false
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WirelessDisplayService(  906): WIFI Trun OFF
,D/WirelessDisplayService(  906): getDiscoveryDongleList
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 6 { when=-103ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
W/SystemReader( 3842): Cannot find support_harman, use default value instead
,W/SystemReader( 3842): Cannot find effect_manager_id, use default value instead
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/CustomizationManager( 4034): ====startRecUseTime====
D/htc.customization.log.level( 4034):  is 
,W/CustomizationLogLevel( 4034): Level value is invalid, use default level 2
,I/Icing   ( 1224): Indexing done 3E78574859FB8ED28F43D3ECB139F4117F00AB29
D/PMS     (  906): acquireWL(43000920): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3842): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3842): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,E/Settings:HtcWrapHeaderInfo( 3842): no such activity!
D/PMS     (  906): releaseWL(42d4c7c8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/ContextImpl( 4063): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3842): The wrap header doesn't exist in header list.
,D/PowerUsageService( 4063): call getInstance()
,E/Settings:HtcWrapHeaderInfo( 3842): updateDevelopment, bPrefShow = true
,I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,W/WeatherUtility( 1117): can't get weather sync account
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
,E/Settings:HtcUmcWidgetEnabler( 3842): isSupportMusicChannel(): false
,D/PMS     (  906): acquireWL(42ff04b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 4063 1000 null
D/PowerUsageList:PowerUsageHelper( 4063): MY_DEBUG = false
D/WeatherUtility( 1399): Weather sync is On
,D/WSP     ( 1399): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]support         :false
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.util.WidgetReceiver
,W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
W/WeatherUtility( 3395): can't get weather sync account
,W/FingerprintManager( 3842): No such file: /sys/module/vfsSpiDrv/parameters/fp_mount
,E/Settings:HtcVoWifiWidgetEnabler( 3842): isSupportVoWifi: null
W/BatSI   (  906): Couldn't get kernel wake lock stats
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
E/ActivityThread( 3842): Failed to find provider info for com.htc.vowifi
,W/WeatherRequest( 3395): request cur loc, but there is no sys cur
,W/Settings( 3395): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1272): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1272): com.htc.widget.weatherclock (true,33751552)
,I/bt-btif ( 1613): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1613): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/CustomizationManager( 4034):  Read ACC file spent 0.067 (s)
D/CIDMapFileReader( 4034): Parsing tag item name = HTC__001
,D/CIDMapFileReader( 4034): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4034): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4034): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4034): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4034): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4034): Parsing tag item name = HTC__016
,D/CIDMapFileReader( 4034): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4034): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4034): Parsing tag item name = HTC__031
,V/CustomizationCIDLoader( 4034): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4034): Parsing tag category name = system
,I/CustomizationCIDLoader( 4034): Parsing tag category name = application
D/HeadsetService( 1613): Received stop request...Stopping profile...
I/CustomizationCIDLoader( 4034): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4034): Parsing tag category name = AutomotiveHome
,I/CustomizationCIDLoader( 4034): Parsing tag category name = AudioService
,I/CustomizationCIDLoader( 4034): Parsing tag category name = ACC
I/CustomizationCIDLoader( 4034): Parsing tag category name = Settings
,D/CustomizationManager( 4034):  Read CID file spent 0.114 (s)
,D/CustomizationManager( 4034):  All configurations done spent 0.115 (s)
W/HtcNativeFlag( 4034): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4034): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4034): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4034): Fail to get flag for type 'language', use default value: -1
,D/BluetoothAdapterState( 1613): Stopping profile services that were post enabled
,D/BluetoothHeadset(  906): Proxy object disconnected
,D/BluetoothHeadset( 1247): Proxy object disconnected
D/BluetoothHeadset( 1117): Proxy object disconnected
,D/BluetoothPhoneService( 1247): BluetoothHeadset onServiceDisconnected
I/QuickSettingMiniLite( 1117): btListener.disconnect:HEADSET
,D/BluetoothHeadset( 1247): Proxy object disconnected
D/A2dpService( 1613): Received stop request...Stopping profile...
D/A2dpStateMachine( 1613): doQuit
D/A2dpStateMachine( 1613): Exit Disconnected: -1
I/RemoteViews.Performance( 1272): com.htc.widget.weatherclock 2 30 17
D/BluetoothA2dp(  906): Proxy object disconnected
,D/HidService( 1613): Received stop request...Stopping profile...
,D/HealthService( 1613): Received stop request...Stopping profile...
D/PanService( 1613): Received stop request...Stopping profile...
D/PanService( 1613): stop
,D/PanService( 1613): stop: mTetherAc send disconnect
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3842): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3842): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3842): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3842): [supportHomeButton]support         :false
,W/FingerprintManager( 3842): hasFingerprint() - sSensorCode = 0
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BluetoothHeadset( 1117): Proxy not attached to service
,I/QuickSettingMiniLite( 1117): updateLiteState:no connect device!
,D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECT
E/Settings:HtcVoWifiWidgetEnabler( 3842): isSupportVoWifi: null
D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  906): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  906): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService( 1613): Profile still running: com.android.bluetooth.hdp.HealthService
,D/BtGatt.DebugUtils( 1613): handleDebugAction() action=null
D/BtGatt.GattService( 1613): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1613): stop()
W/BatSI   (  906): Couldn't get kernel wake lock stats
D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=4034, uid=2000 user=0
I/ActivityManager(  906): Cannot resolve ContentProvider=com.htc.vowifi
,E/ActivityThread( 3842): Failed to find provider info for com.htc.vowifi
W/BluetoothHeadsetServiceJni( 1613): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1613): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1613): Profile still running: com.android.bluetooth.hdp.HealthService
D/A2dpStateMachine( 1613): cleanup
D/Avrcp   ( 1613): Unregistering previous receiver
D/BluetoothAdapterService( 1613): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1613): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1613): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1613): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1613): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1613): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1613): Cleaning up Bluetooth Health object
D/PanService( 1613): CMD_CHANNEL_DISCONNECTED
D/PanService( 1613): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1613): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1613): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1613): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1613): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1613): Setting state to 10
I/BluetoothAdapterState( 1613): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1613): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
I/BluetoothAdapterState( 1613): Entering OffState
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothMap( 3842): onBluetoothStateChange: up=false
E/BluetoothMap( 3842): 
E/BluetoothMap( 3842): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@424f3ae0
E/BluetoothMap( 3842): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3842): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3842): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3842): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3842): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3842): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3842): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothInputDevice( 3842): onBluetoothStateChange: up=false
E/BluetoothInputDevice( 3842): 
E/BluetoothInputDevice( 3842): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@424f11c8
E/BluetoothInputDevice( 3842): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3842): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3842): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3842): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3842): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3842): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3842): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset( 1117): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=false
D/BluetoothHeadset(  906): onBluetoothState,Change: up=false
D/BluetoothHeadset( 1247): onBluetoothStateChange: up=false
D/BluetoothA2dp(  906): onBluetoothStateChange: up=false
D/BluetoothSap( 3842): onBluetoothStateChange on: false
D/Process (  906): killProcessQuiet, pid=3460
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,E/BluetoothPan( 3842): 
E/BluetoothPan( 3842): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@424f2760
E/BluetoothPan( 3842): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3842): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3842): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3842): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3842): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3842): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3842): 	at dalvik.system.NativeStart.run(Native Method)
,W/asset   (  906): Copying FileAsset 0x6c4c1dc8 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=-1: uninstall pkg
I/ActivityManager(  906): Killing 3460:com.example.hello/u0a355 (adj 0): stop com.example.hello
,W/ActivityManager(  906): Force removing ActivityRecord{42f6e7e0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
D/BluetoothPbap( 3842): onBluetoothStateChange: up=false
E/BluetoothPbap( 3842): 
E/BluetoothPbap( 3842): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@424fa7b8
E/BluetoothPbap( 3842): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3842): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3842): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3842): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3842): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3842): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3842): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothManagerService(  906): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1856): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42564320
D/BluetoothAdapter( 1856): onBluetoothServiceDown: done
D/BluetoothAdapter( 1414): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@425c0108
D/BluetoothAdapter( 1414): onBluetoothServiceDown: done
D/BluetoothAdapter( 3842): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424e5698
D/BluetoothAdapter( 3842): onBluetoothServiceDown: done
D/BluetoothAdapter( 1117): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42858848
D/BluetoothAdapter( 1117): onBluetoothServiceDown: done
D/BluetoothAdapter(  906): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@429c9598
D/BluetoothAdapter(  906): onBluetoothServiceDown: done
D/BluetoothAdapter( 1247): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@426e95a0
D/BluetoothAdapter( 1247): onBluetoothServiceDown: done
W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
D/BluetoothAdapter( 1257): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42539bb8
D/BluetoothAdapter( 1257): onBluetoothServiceDown: done
D/BluetoothAdapter( 1613): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@42481020
D/BluetoothDevice( 1613): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1613): onBluetoothServiceDown: done
D/BluetoothAdapter( 1823): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@4248ad10
D/BluetoothAdapter( 1823): onBluetoothServiceDown: done
,D/AutoSetting( 1399): service - mRequestRunnable: screen on delay 10s, request NLP now
W/PackageSettings(  906): Skipping PackageSetting{42c1fdd8 com.test.thalitest/10348} due to missing metadata
,D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1399): service - requestNLP() NetworkLocationProvider not enabled
I/ActivityManager(  906): Waited long enough for: ServiceRecord{42fadc70 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=4092 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,I/ActivityManager(  906): Force stopping com.example.hello appid=10355 user=0: pkg removed
,W/InputDispatcher(  906): channel '42e29ef8 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '42e29ef8 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/BluetoothManagerService(  906): Unable to call onBluetoothServiceDown() on callback #9
E/BluetoothManagerService(  906): android.os.DeadObjectException
E/BluetoothManagerService(  906): 	at android.os.BinderProxy.transact(Native Method)
E/BluetoothManagerService(  906): 	at android.bluetooth.IBluetoothManagerCallback$Stub$Proxy.onBluetoothServiceDown(IBluetoothManagerCallback.java:105)
E/BluetoothManagerService(  906): 	at com.android.server.BluetoothManagerService.sendBluetoothServiceDownCallback(BluetoothManagerService.java:677)
E/BluetoothManagerService(  906): 	at com.android.server.BluetoothManagerService.bluetoothStateChangeHandler(BluetoothManagerService.java:1330)
E/BluetoothManagerService(  906): 	at com.android.server.BluetoothManagerService.access$2900(BluetoothManagerService.java:59)
E/BluetoothManagerService(  906): 	at com.android.server.BluetoothManagerService$BluetoothHandler.handleMessage(BluetoothManagerService.java:1053)
E/BluetoothManagerService(  906): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/BluetoothManagerService(  906): 	at android.os.Looper.loop(Looper.java:157)
E/BluetoothManagerService(  906): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BluetoothManagerService(  906): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@429c9598 mBinding = false
,D/SettingsProvider(  906): User 0 external modification to /data/data/com.android.providers.settings/databases/settings.db; event=2
,D/SettingsProvider(  906): User 0 updating our caches for /data/data/com.android.providers.settings/databases/settings.db
,D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1585): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1585): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
,D/WifiService(  906): Client connection lost with reason: 4
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/BluetoothManagerService(  906): Sending unbind request.
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/acms    ( 1900): Unregistering com.example.hello
,E/acms    ( 1900): Could not unregister removed application com.example.hello
,W/GeofencerStateMachine( 1414): Ignoring removeGeofence because network location is disabled.
I/FeedHostManager( 1272): [onResume]
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42e29ef8 com.example.hello.MainActivity (s)'
,I/FeedProviderManager( 1272): onResume
,I/SocialFeedProvider( 1272): +onResume
,I/SocialFeedProvider( 1272): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1272): -onResume
D/PMS     (  906): acquireWL(4311a928): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1414 10028 null
I/WindowState(  906): WIN DEATH: Window{42e29ef8 u0 com.example.hello/com.example.hello.MainActivity}
,D/PMS     (  906): releaseWL(4311a928): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,W/GLSUser ( 1363): GoogleAccountDataService.getToken()
,I/Prism.ItemManager( 3773): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3773): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/BluetoothAdapterService( 1613): Cleaning up adapter native....
,I/bt-btif ( 1613): HAL bt_hal_cbacks->thread_evt_cb
I/WindowManager(  906): WINDOW DIED Window{42e29ef8 u0 com.example.hello/com.example.hello.MainActivity}
D/PMS     (  906): releaseWL(42f3e430): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,I/ConnectivityHelper( 1272): [getCurrentConnectionType] no network connection
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,D/BluetoothAdapterService( 1613): Done cleaning up adapter native....
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1272/10075)
,D/BluetoothAdapterService(1112007856)( 1613): ****onDestroy()********
D/BtGatt.GattService( 1613): cleanup()
W/bt-btif ( 1613): GATTC Module not enabled/already disabled
,W/bt-btif ( 1613): GATTS Module not enabled/already disabled
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1363): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 13 -> 10
,I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
D/LocalBluetoothProfileManager( 3842): setBluetoothStateOff
,D/HtcTagManager( 3842): stopProxy
,W/BluetoothEventManager( 3842): unregister mProfileBroadcastReceiver fail
,W/GLSActivity( 1363): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/BluetoothMasReceiver( 1613): Bluetooth STATE CHANGED to 10
,D/TetherPref( 3842): persistRestoreBluetoothState false
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1272): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/PMS     (  906): acquireWL(42a51a90): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3842 1000 null
W/ContextImpl( 3842): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
,V/BluetoothMasService( 1613): onDestroy: mIsEmailEnabled: true
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
,D/BluetoothAdapter( 1117): 1114706120: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
D/PMS     (  906): releaseWL(42a51a90): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/PMS     (  906): acquireWL(42f802c8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3842 1000 null
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,D/HtcBtWidget_BTWidgetProvider( 4016): onBTStateChanged() for widget: 
D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "mms"
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/HtcBtWidget_BTWidgetProvider( 4016): updateWidget(context) for widget: 
,D/DockEventReceiver( 3842): finishStartingService: stopping service
D/PMS     (  906): releaseWL(42f802c8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,W/Finsky  ( 3900): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,W/Binder  ( 1209): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1209): java.lang.NullPointerException
W/Binder  ( 1209): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1209): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1209): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1209): 	at dalvik.system.NativeStart.run(Native Method)
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3460 uid 10355
,I/InputMethodManagerService(  906): Enable input method client, pid=1272
D/Finsky  ( 3900): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3900): [1] DailyHygiene.reschedule: Giving up. (failures=6)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (1414/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3948/10100)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1856/10178)
I/ConnectivityHelper( 1272): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1272/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1900/1000)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=4112 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,D/BluetoothMasReceiver( 1613): Bluetooth STATE CHANGED to 10
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.docs (3948/10100)
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,D/Process (  906): killProcessQuiet, pid=3806
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1247 :
I/ActivityManager(  906): Killing 3806:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3806
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PhoneApp( 1247): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1823): Received state change = 10
,W/Netd    (  363): No subsystem found in netlink event
V/Tethering(  906): remove iface:wlan0
D/Tethering(  906): interfaceRemoved wlan0
,E/Tethering(  906): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42fb7108:true
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4040): new LocationAgent instance!!
,D/HtcTagManager( 4040): HtcTagManager construction complete
,D/BluetoothAdapter( 4040): 1111956784: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 4040): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothAdapter( 4040): 1111956784: getState() :  mService = null. Returning STATE_OFF
D/BluetoothManagerService(  906): Registered receivers: 12
D/BluetoothInputDevice( 4040): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4040): Bluetooth service connected
W/BluetoothInputDevice( 4040): Proxy not attached to service
,D/BluetoothPan( 4040): BluetoothPan()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothAdapter( 4040): 1111956784: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 4040): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 4040): Bluetooth service connected
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 13
,D/BluetoothMap( 4040): Create BluetoothMap proxy object
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 14
,E/BluetoothMap( 4040): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 4040): BluetoothSap() call bindService
,D/BluetoothManagerService(  906): Registered receivers: 15
,I/MusicStore( 4112): Database version: 95
,W/ContextImpl( 4040): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 4040): BluetoothPbap()
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4040): 1111956784: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4040): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4040): Bluetooth service connected
D/BluetoothManagerService(  906): Registered receivers: 16
D/LocalBluetoothProfileManager( 4040): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4040): 1111956784: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4040): 1111956784: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4040): setBluetoothStateOff
D/HtcTagManager( 4040): stopProxy
W/BluetoothEventManager( 4040): unregister mProfileBroadcastReceiver fail
W/ContextImpl( 4112): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
,D/Process (  906): killProcessQuiet, pid=3819
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
,E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
,E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
,I/ActivityManager(  906): Killing 3819:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOn,Conflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpo,wermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
W/ContextImpl( 4112): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
W/ContextImpl( 4112): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteData,base.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
I/ActivityManager(  906): Recipient 3819
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
W/ContextImpl( 4112): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4,063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceS,tartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
W/ContextImpl( 4112): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	a,t android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask,.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java,:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync,.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
D/Tethering(  906): interfaceLinkStateChanged p2p0, false
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
D/Tethering(  906): interfaceStatusChanged p2p0, false
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
D/Tethering(  906): [isWifi] getHotspotEnabled: false
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.ja,va:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
W/PackageManager(  906): Unable to load service info ResolveInfo{42d0c310 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	,at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232),
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): ,	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): ,	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	,at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=4112, uid=10154, userID:0
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at an,droid.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run,(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
D/NfcHandover( 1257): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
V/AlarmManager(  906): sending alarm PendingIntent{42de5890: PendingIntentRecord{43142c48 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1448460699297, Int=0
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/MediaRouterService(  906): Client com.google.android.music (pid 4112): Registered
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
I/MediaRouter( 4112): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (4112/10154)
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
D/TelephonyReceiver( 1247): bind: true
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
E/SQLiteLog( 4063): (3850) statement aborts at 27: [INSERT INTO smartsync_golden_wed(Data_Link_Turn_OnOff,Location_Service_Turn_OnOff,time,AutoSync_Turn_OnOff,date) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDBG( 4063): func: executeNonQuery errno = 9, error message = Bad file number, path = /data/data/com.htc.htcpowermanager/databases/SmartSync.db, handle = 0x5ca84518
D/Process (  906): killProcessQuiet, pid=3745
E/SQLiteDatabase( 4063): Error inserting ...
E/SQLiteDatabase( 4063): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:818)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1540)
E/SQLiteDatabase( 4063): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1395)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.insert(SmartSyncProvider.java:295)
E/SQLiteDatabase( 4063): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:232)
E/SQLiteDatabase( 4063): 	at android.content.ContentResolver.insert(ContentResolver.java:1213)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.CheckAndUpdateGoldenTable(SmartSyncScreenOnOffTimeReceiver.java:2202)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.getTodayGoldenTableList(SmartSyncScreenOnOffTimeReceiver.java:2232)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver.access$800(SmartSyncScreenOnOffTimeReceiver.java:26)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:486)
E/SQLiteDatabase( 4063): 	at com.htc.htcpowermanager.smartsync.SmartSyncScreenOnOffTimeReceiver$SmartSyncServiceStartAsyncTask.doInBackground(SmartSyncScreenOnOffTimeReceiver.java:470)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4063): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4063): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4063): 	at java.lang.Thread.run(Thread.java:864)
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Killing 3745:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3745
D/PMS     (  906): releaseWL(42ff04b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  906): Start proc com.htc.sense.mms for content provider com.htc.sense.mms/.util.GenericMessagesProvider: pid=4136 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
,D/MediaRouter( 4112): getSelectedRoute
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=4149 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,W/Netd    (  363): No subsystem found in netlink event
,V/Tethering(  906): remove iface:p2p0
D/Tethering(  906): interfaceRemoved p2p0
,E/Tethering(  906): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  363): Unexpected netlink message. type=0x11
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (4112/10154)
I/NetworkMonitor( 4112): type=WIFI subType= reason=null isConnected=false
,D/DFPI.PIReciver( 4149): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 4149): onHandleIntent
I/DFPI.ApkInstallService( 4149): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4149): check CID = HTC__032
,I/DFPI.ApkInstallService( 4149): There is no Demo.apk in sd card or phone storage
,D/MessageFrequencyProvider( 4136): onCreate
I/ActivityManager(  906): Resuming delayed broadcast
,D/Process (  906): killProcessQuiet, pid=3758
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=4112, uid=10154, userID:0
I/ActivityManager(  906): Killing 3758:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3758
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=4164 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
,V/GetPrviateResource( 4136): GetPrviateResource
,V/GetPrviateResource( 4136): GetPrviateResource
,D/GenericMessagesProvider( 4136): query uri: content://htc-messages/wappush/count
,D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/Process (  906): killProcessQuiet, pid=3884
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
I/ActivityManager(  906): Killing 3884:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
,E/SQLiteLog( 4136): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 4136): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 4136): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 4136): DB info: errno = 2, errno message = No such file or directory
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 4136): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 4136): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4136): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 4136): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 4136): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4136): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4136): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 4136): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 4136): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 4136): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 4136): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 4136): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
W/System.err( 4136): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 4136): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 4136): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 4136): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 4136): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 4136): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 4136): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 4136): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 4136): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 4136): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 4136): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 4136): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  906): Recipient 3884
,D/Process (  906): killProcessQuiet, pid=3948
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/TelephonyReceiver( 1247): switchBindHtcMsgCursor: null
I/ActivityManager(  906): Killing 3948:com.google.android.apps.docs/u0a100 (adj 15): empty #17
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): acquireWL(4317d4e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  906): releaseWL(4317d4e0): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=4181 uid=10080 gids={50080, 5001, 1028, 1015}
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (4164/10051)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{43205710 u0 ReceiverList{432056b0 4164 com.htc.musicenhancer/10051/u0 remote:432053b8}}
,E/cutils  (  346): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  346): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 4164): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,D/MessageCustFlag( 4136): sense_version=6.0
,D/BTAccessoryUtil( 4136): createReceiver
,D/BTAccessoryUtil( 4136): registerReceiver return intent = null
,D/MessageCustFlag( 4136): sku_id=99
,W/SystemReader( 4136): Cannot find message_ambs_application_id, use default value instead
I/ActivityManager(  906): Recipient 3948
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 4181): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4181): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4181): SoundPickerReceiver [onReceive] startService
D/Messaging( 4136): supportCMAS(SIE)/init? false/true
D/MmsConfig( 4136): networkCode: 
,D/MessageCustFlag( 4136): sku_id=99
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/MmsConfig( 4136): SIE smsPri: null
D/MmsConfig( 4136): networkCode: 
I/SoundPicker( 4181): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4181): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4181): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/HtcTelephonyCapability( 4136): traditional single GSM/CDMA/World-phone
D/HtcTelephonyCapability( 4136): The project is not dual project , phone_feature_type_stand_by = 0
D/HtcBuildUtils( 4136): getRATByHtcTelephonyCapability:1
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4181): MODE_GSM access default DB
W/SystemReader( 4136): Cannot find qct_8960_interface, use default value instead
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4181): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4181): MODE_GSM access default DB
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 2)
,I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3773:com.htc.sense.news/u0a75 (adj 15): empty #17
D/Process (  906): killProcessQuiet, pid=3773
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  906): Recipient 3773
,D/DFPI.PIReciver( 4149): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4149): onHandleIntent
,I/DFPI.ApkInstallService( 4149): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4149): check CID = HTC__032
,I/DFPI.ApkInstallService( 4149): There is no Demo.apk in sd card or phone storage
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 4181): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4181): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4181): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4181): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4181): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4181): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4181): MODE_GSM access default DB
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4181): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4181): MODE_GSM access default DB
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
D/DFPI.PIReciver( 4149): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 4149): onHandleIntent
I/DFPI.ApkInstallService( 4149): Media Scan Finished Case 
D/DFPI.ApkInstallService( 4149): check CID = HTC__032
,I/DFPI.ApkInstallService( 4149): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 4181): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 4181): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 4181): SoundPickerReceiver [onReceive] startService
,I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 4181): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 4181): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 4181): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4181): MODE_GSM access default DB
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 4181): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 4181): MODE_GSM access default DB
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/inte,rnal/audio/media/112 type=2
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 4181): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac,
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 4181): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9,
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 4181): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 4181): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  906): Resuming delayed broadcast
,E/SharedPreferencesImpl( 4112): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/SQLiteDatabase( 4112): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 4112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 4112): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 4112): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 4112): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4112): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 4112): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4112): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4112): threadid=16: thread exiting with uncaught exception (group=0x42031e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.music:main
E/AndroidRuntime( 4112): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 4112): Process: com.google.android.music:main, PID: 4112
E/AndroidRuntime( 4112): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4112): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4112): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4112): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 4112): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 4112): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4112): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4112): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 4112): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 4112): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/D,ropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more

```
