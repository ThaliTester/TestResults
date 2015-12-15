#### Test 5038801913f4183_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/main
,W/dalvikvm( 3435): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3435): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/FbInjectorInitializer( 3435): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
W/fb4a(:<default>):StaticBindingVerifier( 3435): Verify
E/cutils-trace( 3480): Error opening trace file: No such file or directory (2)
--------- beginning of /dev/log/system
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3435/10026)
W/fb4a(:<default>):BaseAnalyticsConfig( 3435): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
W/fb4a(:<default>):BaseAnalyticsConfig( 3435): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
I/dalvikvm-heap( 3435): Grow heap (frag case) to 9.510MB for 73240-byte allocation
D/Process (  907): killProcessQuiet, pid=3209
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3209:com.htc.providers.settings:remote/u0a17 (adj 15): empty #17
D/CustomizationManager( 3480): ====startRecUseTime====
D/htc.customization.log.level( 3480):  is 
W/CustomizationLogLevel( 3480): Level value is invalid, use default level 2
D/PMS     (  907): acquireWL(4270c108): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2222 10028 null
I/ActivityManager(  907): Recipient 3209
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  907): acquireWL(4270c018): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2222 10028 null
D/PMS     (  907): releaseWL(4270c108): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
D/GCM     ( 1371): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(4270c018): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): reportInetCondition for net 1, percentage: 100 by  (1371/10028)
D/ConnectivityService(  907): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  907): handleInetConditionChange: starting a change hold
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
D/AutoSetting( 1399): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  907): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3498 uid=10078 gids={50078, 3003, 5012}
D/AutoSetting( 1399): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1399): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1399): service - onStartCommand() REMOVE current location bundle
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
D/AutoSetting( 1399): service - handleMessage() setting current location null
D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1399): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.sense.hsp (1399/10053)
D/CustomizationManager( 3480):  Read ACC file spent 0.073 (s)
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3480): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3480): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3480): Parsing tag category name = system
I/CustomizationCIDLoader( 3480): Parsing tag category name = application
I/CustomizationCIDLoader( 3480): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3480): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3480): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3480): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3480): Parsing tag category name = Settings
D/CustomizationManager( 3480):  Read CID file spent 0.125 (s)
D/CustomizationManager( 3480):  All configurations done spent 0.125 (s)
W/HtcNativeFlag( 3480): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3480): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3480): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3480): Fail to get flag for type 'language', use default value: -1
W/fb4a(:<default>):UserScope( 3435): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 3435): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):UserScope( 3435): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3435): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/asset   (  907): Copying FileAsset 0x699784b8 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/CpuWake (  907): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  907): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  907): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  907): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3480
D/PMS     (  907): acquireHCC(4262bc88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 907 1000 null
D/PMS     (  907): acquireHCC(42605c88): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 907 1000 null
I/Intent  (  907): @test_code: getHtcIntentFlag: 0 obj: 1109876712
D/MobileConnectivityChangeReceiver( 3498): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3498): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3498): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3498): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
D/PMS     (  907): acquireWL(425ddde0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 907 1000 null
I/ActivityManager(  907): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3518 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=3225
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/FeedHostManager( 1273): [onPause]
I/FeedProviderManager( 1273): onPause
I/FeedHostManager( 1273): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41f9d858
I/SocialFeedProvider( 1273): +onPause
I/SocialFeedProvider( 1273): -onPause
I/ActivityManager(  907): Killing 3225:org.simalliance.openmobileapi.service/9987 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3498/10078)
I/ActivityManager(  907): Recipient 3225
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3531 uid=10356 gids={50356, 3003, 5012, 3001, 3002}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3498/10078)
D/PMS     (  907): acquireWL(41fc3fa8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2222 10028 null
I/TrimMemoryManager( 1273): [trimMemory] 20
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.setupwizard (3498/10078)
D/PMS     (  907): acquireWL(42454508): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2222 10028 null
W/asset   ( 3531): Copying FileAsset 0x5c874428 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
D/PMS     (  907): releaseWL(41fc3fa8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
I/CheckinService( 2222): Preparing to send checkin request
I/EventLogService( 2222): Accumulating logs since 1450197662273
I/dalvikvm-heap( 3435): Grow heap (frag case) to 9.960MB for 84664-byte allocation
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
V/WebViewChromiumFactoryProvider( 3531): Binding Chromium to main looper Looper (main, tid 1) {41ae3a58}
I/LibraryLoader( 3531): Expected native library version number "",actual native library version number ""
I/chromium( 3531): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3531): Initializing chromium process, renderers=0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -52 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 216
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
D/WifiNative-wlan0(  907):    returned true
D/Process (  907): killProcessQuiet, pid=3239
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3546 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/ActivityManager(  907): Killing 3239:com.android.smith/u0a163 (adj 15): empty #17
D/PMS     (  907): acquireWL(423bf160): PARTIAL_WAKE_LOCK  AudioMix 0x1 380 1013 null
D/PMS     (  907): acquireWL(42197ac0): PARTIAL_WAKE_LOCK  AudioMix 0x1 380 1013 null
D/PMS     (  907): releaseWL(423bf160): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42489d88:true
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothAdapter( 3531): 1102025808: getState(). Returning 12
I/dalvikvm-heap( 3435): Grow heap (frag case) to 9.974MB for 28144-byte allocation
E/dalvikvm( 3435): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 3435): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3435): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 3435): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3435): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 3435): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3239
E/dalvikvm( 3435): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 3435): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3435): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3435): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 3435): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3435): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3435): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3435): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/dalvikvm( 3435): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3435): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3435): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3435): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/Adreno-EGL( 3531): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3531): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3531): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3531): Local Branch: 
I/Adreno-EGL( 3531): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3531): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3531):                  aa63bbd948f41d15fc72f585e
W/EventLogAggregator( 2222): Unknown tag: install_package_attempt
W/EventLogAggregator( 2222): Unknown tag: snet
W/EventLogAggregator( 2222): Unknown tag: snet_gcore
I/GoogleHttpClient( 2222): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 2222): Using GMS GoogleHttpClient
I/dalvikvm-heap( 3435): Grow heap (frag case) to 10.024MB for 39954-byte allocation
W/chromium( 3531): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
,W/GAV2    ( 3546): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/dalvikvm( 3531): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3531): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
W/ContextImpl( 3546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/WifiService(  907): New client listening to asynchronous messages
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/dalvikvm( 3531): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3531): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3531): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/ContextImpl( 3546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/dalvikvm( 3531): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3531): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3531): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3531): CordovaWebView is running on device made by: HTC
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
I/dalvikvm-heap( 3435): Grow heap (frag case) to 10.099MB for 79892-byte allocation
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3546): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2222/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (2222/10028)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3546/10151)
D/ConnectivityService(  907): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  907): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
V/WebViewChromiumFactoryProvider( 3546): Binding Chromium to main looper Looper (main, tid 1) {41ae49e8}
W/AwContents( 3531): nativeOnDraw failed; clearing to background color.
I/LibraryLoader( 3546): Expected native library version number "",actual native library version number ""
I/chromium( 3546): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3546): Initializing chromium process, renderers=0
E/AudioManagerAndroid( 3546): BLUETOOTH permission is missing!
I/dalvikvm-heap( 3435): Grow heap (frag case) to 10.282MB for 75760-byte allocation
D/PMS     (  907): acquireWL(42598408): PARTIAL_WAKE_LOCK  AudioMix 0x1 380 1013 null
D/PMS     (  907): releaseWL(42598408): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/InputMethodManagerService(  907): Disable input method client, pid=1273
W/ResourceType( 3531): No package identifier when getting name for resource number 0x00000064
I/InputMethodManager( 3531): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41b2a8c0, mServedView=org.apache.cordova.engine.SystemWebView{41af0770 VFEDH.C. .F....I. 0,0-720,1134 #64}
I/InputMethodManagerService(  907): Enable input method client, pid=3531
W/AwContents( 3531): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  907): Displayed com.example.hello/.MainActivity: +366ms
I/Adreno-EGL( 3546): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3546): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3546): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3546): Local Branch: 
I/Adreno-EGL( 3546): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3546): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3546):                  aa63bbd948f41d15fc72f585e
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3435/10026)
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423c9168 u0 ReceiverList{4276f128 3435 com.facebook.katana/10026/u0 remote:4273d410}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423c9168 u0 ReceiverList{4276f128 3435 com.facebook.katana/10026/u0 remote:4273d410}}
W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{423547e0 u0 ReceiverList{42354780 3435 com.facebook.katana/10026/u0 remote:427ae690}}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
D/PMS     (  907): releaseWL(425ddde0): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3435/10026)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3435/10026)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.facebook.katana (3435/10026)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
I/NSApplication( 3546): Starting up...
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3546/10151)
W/GLSUser ( 1371): GoogleAccountDataService.getToken()
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.magazines (3546/10151)
D/PMS     (  907): acquireWL(424069c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3612 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process (  907): killProcessQuiet, pid=3251
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3251:com.google.android.youtube/u0a168 (adj 15): empty #17
D/PMS     (  907): releaseWL(424069c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/GoogleHttpClient( 1371): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 1371): Using GMS GoogleHttpClient
D/GCoreFlp( 1437): Unknown pending intent to remove.
D/PMS     (  907): acquireWL(4241fba0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
D/PMS     (  907): releaseWL(4241fba0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/HABCtrl (  907): ALG=2, lsvalue=10(0th)->40(1th), last_level=1, lValue=64->64
I/NotificationStore( 1371): System rebooted after Notification storage file was last written
I/NotificationStore( 1371): Deleting the file
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
I/ActivityManager(  907): Recipient 3251
D/MediaRouterService(  907): Client com.google.android.youtube (pid 3251): Died!
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3435): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3435): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
W/CheckinRequestBuilder( 2222): awaiting user notification for token
I/RemoteViews( 1116): com.google.android.gms (false,0)
E/AndroidProtocolHandler( 3531): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41b50bb8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
I/RemoteViews.Performance( 1116): com.google.android.gms 2 9 4 12
I/chromium( 3531): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/PMS     (  907): acquireWL(42570d38): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3612 10160 null
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [2][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3612/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3612/10160)
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3643 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3612/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.apps.plus (3612/10160)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
D/PMS     (  907): acquireWL(427556a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3612 10160 null
D/PMS     (  907): releaseWL(42570d38): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/JsMessageQueue( 3531): Set native->JS mode to OnlineEventsBridgeMode
D/AlertReceiver( 3398): beginStartingService
D/PMS     (  907): acquireWL(4258fb38): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3398 10013 null
D/PMS     (  907): acquireWL(42717f48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2222 10028 null
D/PMS     (  907): releaseWL(42717f48): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
I/MultiDex( 3643): install
I/MultiDex( 3643): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
D/AlertService( 3398): start to updateAlertNotification!
I/MultiDex( 3643): loading existing secondary dex files
I/MultiDex( 3643): load found 1 secondary dex files
I/MultiDex( 3643): install done
D/AlertService( 3398): No fired or scheduled alerts
D/HtcAlertUtils( 3398): -- cancelReminderNotification --
D/HtcAlertUtils( 3398): broadcastExistReminder!
D/PMS     (  907): releaseWL(427556a0): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
I/ProviderInstaller( 3643): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
W/AlertReceiver( 3398): stopSelfResult true
D/Process (  907): killProcessQuiet, pid=3198
D/PMS     (  907): releaseWL(4258fb38): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
I/ActivityManager(  907): Killing 3198:com.android.settings/1000 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.widget.hmsproc2 for broadcast com.htc.widget.weatherclock/.util.WidgetReceiver: pid=3662 uid=10042 gids={50042, 3002, 3001, 3003, 5012}
I/ActivityManager(  907): Recipient 3198
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
W/WeatherRequest( 1116): request cur loc, but there is no sys cur
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/jxcore_app_log( 3531): JniHelper::setJavaVM(0x415b5048), pthread_self() = 1657879504
D/JX-Cordova( 3531): jxcore cordova android initializing
D/WIFI_ICON( 1116): WifiActivity: 3
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
I/ActivityManager(  907): Start proc com.htc.task for broadcast com.htc.task/.notification.NotifyReceiver: pid=3675 uid=10070 gids={50070, 1023, 3003, 5012, 1028, 1015}
W/WeatherUtility( 3662): can't get weather sync account
W/WeatherRequest( 3662): request cur loc, but there is no sys cur
W/Settings( 3662): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/PMS     (  907): acquireWL(427585d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3675 10070 null
D/PMS     (  907): acquireWL(42739428): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3675 10070 null
W/jxcore-log( 3531): Initializing JXcore engine
W/jxcore-log( 3531): JXcore engine is ready
D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
D/PMS     (  907): releaseWL(427585d0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
W/jxcore-log( 3531): Starting JXcore engine
I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 2 11 17
I/ActivityManager(  907): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3692 uid=10090 gids={50090, 3003, 5012, 1028}
D/TodoTaskshortcut( 3675): update TASK shortcut>
I/TodoTaskNotifyService( 3675): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
I/TodoTaskNotifyService( 3675): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
W/NotifyReceiver( 3675): stopSelfResult true
D/Process (  907): killProcessQuiet, pid=3301
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseWL(42739428): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Killing 3301:com.htc.sense.browser/u0a12 (adj 15): empty #17
I/WorldClock.Global( 3692): isHtcDevice = true
I/WorldClock.Global( 3692): isHtcDevice = true
W/ContextImpl( 3185): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
I/WorldClock.AlarmUtils( 3692): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
I/ActivityManager(  907): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3708 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/WorldClock.AlarmUtils( 3692): Cancel any alarm from alarm manager
I/WorldClock.AlarmUtils( 3692): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
I/IntentController( 1116): receive(android.intent.action.ALARM_CHANGED,1,false)
D/Process (  907): killProcessQuiet, pid=3341
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3341:com.google.android.partnersetup/u0a31 (adj 15): empty #17
I/Adreno-EGL( 3643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3643): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3643): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3643): Local Branch: 
I/Adreno-EGL( 3643): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3643): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3643):                  aa63bbd948f41d15fc72f585e
W/jxcore-log( 3531): Platform android
W/jxcore-log( 3531): 
W/jxcore-log( 3531): Process ARCH arm
W/jxcore-log( 3531): 
I/Adreno-EGL( 3643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3643): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3643): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3643): Local Branch: 
I/Adreno-EGL( 3643): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3643): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3643):                  aa63bbd948f41d15fc72f585e
I/jxcore-log( 3531): JXcore Cordova bridge is ready!
I/jxcore-log( 3531): 
W/jxcore-log( 3531): JXcore engine is started
I/ActivityManager(  907): Recipient 3341
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3301
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/TimeService( 3708): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1450199005868
D/Process (  907): killProcessQuiet, pid=3354
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/AdsMeasurementBroadcastReceiver( 2222): Reporting settings might have changed, alerting AdsMeasurementService
D/AdsMeasurementBroadcastReceiver( 2222): Unauthorized to start the main service
I/ActivityManager(  907): Killing 3354:com.htc.contacts/u0a41 (adj 15): empty #17
E/jxcore-log( 3531): >> HTC-HTC Desire 820
E/jxcore-log( 3531): 
I/jxcore-log( 3531): Total memory 1964650496
I/jxcore-log( 3531): 
I/jxcore-log( 3531): Free memory 614522880
I/jxcore-log( 3531): 
I/jxcore-log( 3531): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3531): 
I/jxcore-log( 3531): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3531): 
I/jxcore-log( 3531): userPath [ 'www' ]
I/jxcore-log( 3531): 
I/jxcore-log( 3531): Size 720 1184
I/jxcore-log( 3531): 
I/ActivityManager(  907): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver: pid=3726 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
I/jxcore-log( 3531): Screen Brightness 10
I/jxcore-log( 3531): 
W/WeatherUtility( 3662): can't get weather sync account
E/jxcore-log( 3531): Dummy Error Log.
E/jxcore-log( 3531): 
W/WeatherRequest( 3662): request cur loc, but there is no sys cur
W/Settings( 3662): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/DemoRecovery.RestoreReceiver( 3726): onReceive: com.htc.launcher.intent.LOADING_COMPLETE
I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
W/ContextImpl( 3726): Implicit intents with startService are not safe: Intent { act=com.htc.demorecovery.LOADING_COMPLETE } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.demoflopackageinstaller.demorecovery.RestoreReceiver.onReceive:26 
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.demorecovery.RestoreReceiver
I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 1 6 17
I/RestoreService( 3726): onHandleIntent: com.htc.demorecovery.LOADING_COMPLETE
I/ActivityManager(  907): Resuming delayed broadcast
D/PMS     (  907): acquireWL(4246f040): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3675 10070 null
D/PMS     (  907): acquireWL(424493d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3675 10070 null
D/PMS     (  907): releaseWL(4246f040): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
D/TodoTaskshortcut( 3675): update TASK shortcut>
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
I/TodoTaskNotifyService( 3675): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
D/PMS     (  907): releaseWL(424493d8): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
W/NotifyReceiver( 3675): stopSelfResult true
D/Process (  907): killProcessQuiet, pid=3369
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Start proc com.htc.stock for broadcast com.htc.stock/.receiver.StockReceiver: pid=3744 uid=10081 gids={50081, 3003, 5012}
I/ActivityManager(  907): Killing 3369:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (3643/10028)
W/Settings( 3643): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  907): Recipient 3369
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3354
,I/ActivityManager(  907): Start proc com.htc.stock:remote for content provider com.htc.stock/.provider.StockProvider: pid=3756 uid=10081 gids={50081, 3003, 5012}
,D/Process (  907): killProcessQuiet, pid=3414
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,D/Process (  907): killProcessQuiet, pid=3385
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 2222): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2222): Unauthorized to start the main service
I/ActivityManager(  907): Killing 3414:com.google.android.music:main/u0a154 (adj 15): empty #17
I/ActivityManager(  907): Killing 3385:com.htc.mms.backupagent/u0a77 (adj 15): empty #18
,I/ActivityManager(  907): Recipient 3385
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3768 uid=10038 gids={50038}
,I/ActivityManager(  907): Start proc com.htc.mms.backupagent for broadcast com.htc.mms.backupagent/.SMSBroadcastReceiver: pid=3781 uid=10077 gids={50077}
,D/Process (  907): killProcessQuiet, pid=3435
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3435:com.facebook.katana/u0a26 (adj 15): empty #17
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MediaRouterService(  907): Client com.google.android.music (pid 3414): Died!
I/ActivityManager(  907): Recipient 3414
,D/SMSBackup( 3781): Got a database change event
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3435
,D/WifiService(  907): Client connection lost with reason: 4
,I/ActivityManager(  907): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3794 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  907): killProcessQuiet, pid=3449
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3449:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/PMS     (  907): acquireWL(42253590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
D/PMS     (  907): acquireWL(420931c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1437 10028 null
,D/PMS     (  907): releaseWL(42253590): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  907): releaseWL(420931c0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
I/ActivityManager(  907): Recipient 3449
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3794): create image Cache, size: 31457280.
I/ImageRamCache( 3794): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3794): create image Cache, size: 12582912.
,I/FeedSettings( 3794): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3794): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3794): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3794): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3794): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3794): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3794): [custom highlight] onReceive
,D/CustomHighlightService( 3794): [custom highlight] onHandleIntent
,D/NewsDB  ( 3794): set custom highlight []
I/ActivityManager(  907): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
,D/CustomHighlightService( 3794): [custom highlight] set tags 
,D/Process (  907): killProcessQuiet, pid=3464
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Resuming delayed broadcast
I/ActivityManager(  907): Killing 3464:com.htc.mobiledata/u0a91 (adj 15): empty #17
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  907): Recipient 3464
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
I/ActivityManager(  907): Resuming delayed broadcast
,D/MessagingShortcutReceiver( 2797): keep hiding shortcut bubble
D/MessagingShortcut( 2797): updateMsgShortcut, msg count> -1
D/MessagingShortcut( 2797): After query: 0
D/MessagingShortcut( 2797): mPresentUnreadCount: -1
D/MessagingShortcut( 2797): setMsgShortcutDrawable> 0
,D/MessagingShortcut( 2797): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
I/ActivityManager(  907): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderNotification, total:0
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/TodoTaskshortcut( 3675): update TASK shortcut>
I/ActivityManager(  907): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  907): Resuming delayed broadcast
D/HtcBroadcastReceiver( 1244): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
I/Adreno-EGL( 3643): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3643): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3643): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3643): Local Branch: 
I/Adreno-EGL( 3643): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3643): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3643):                  aa63bbd948f41d15fc72f585e
,I/ActivityManager(  907): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3813 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission
,I/jxcore-log( 3531): getBuffer is called!!!!
I/jxcore-log( 3531): 
,I/ActivityManager(  907): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3827 uid=10091 gids={50091, 3003, 5012}
,D/WIFI_ICON( 1116): WifiActivity: 1
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,D/MessagingNotification( 2797): New incoming message, can't cancel notification now
,D/MessagingNotification( 2797): newMsgCnt: 0, false
,I/SocialFeedProvider( 1273): +disConnect socialManager
,I/SocialFeedProvider( 1273): disconnect socialManager
,I/SocialFeedProvider( 1273): -disConnect socialManager
,D/MdScBoot( 3813): [8b0.1.] 40@-180322
,D/GCM     ( 1371): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  907): Resuming delayed broadcast
W/CpuWake (  907): >>nativeReleaseCpuPerfWakeLock()
I/ActivityManager(  907): Killing 3498:com.google.android.setupwizard/u0a78 (adj 15): empty #17
W/CpuWake (  907): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  907): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): <<release mCpuPerf_cpu_count wakelock
W/CpuWake (  907): >>release mCpuPerf_Freq wakelock
W/CpuWake (  907): <<release mCpuPerf_Freq wakelock
,D/PMS     (  907): releaseHCC(4262bc88): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/Process (  907): killProcessQuiet, pid=3498
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.removeContentProvider:8612 
,D/Process (  907): killProcessQuiet, pid=3518
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  907): releaseHCC(42605c88): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
I/ActivityManager(  907): Killing 3518:com.android.chrome/u0a96 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3518
,D/SMSBackup( 3781): Got a database change event
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/MtpReceiver( 2452): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2452): [MTP][MtpReceiver][onReceive]1-
D/MtpReceiver( 2452): [MTP][handleMessage][startService]
,D/MtpReceiver( 2452): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2452): [MTP][handleMessage]-
I/ActivityManager(  907): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3840 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/MtpService( 2452): [MTP] startForeground
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,I/RemoteViews( 1116): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1116): com.android.providers.media 3 0 10
D/MtpService( 2452): updating state; isCurrentUser=true, mMtpLocked=false
D/MtpDatabase( 2452): TotalSize=1918604,MediaCacheLimit=6000
,I/RemoteViews( 1116): com.android.providers.media (false,0)
,I/RemoteViews.Performance( 1116): com.android.providers.media 3 3 15
,D/MtpService( 2452): [isMtpConnected] connected: true
D/PMS     (  907): acquireWL(422eeb28): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3612 10160 null
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Recipient 3498
,D/PMS     (  907): releaseWL(422eeb28): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
,D/SyncApplication( 3840): Loading default preferences
,W/Resources( 3840): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,I/dalvikvm-heap( 3612): Grow heap (frag case) to 15.220MB for 1821008-byte allocation
,I/CheckinTask( 2222): Sending checkin request (9030 bytes)
,D/WifiService(  907): New client listening to asynchronous messages
,W/ActivityThread( 2222): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/SyncApplication( 3840): Overriding preferences with custom values
,D/SyncApplication( 3840): Updating preferences succeeded
,E/SyncApplication( 3840): Application created.
D/VolumeInfo( 3840): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3840): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3840): Found 0 mount point(s)
,V/VolumeInfo( 3840): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
D/libc    ( 2222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2222): [NET] getaddrinfo-,err=8
D/libc    ( 2222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    ( 2222): [NET] getaddrinfo-, 1
D/libc    ( 2222): [NET] getaddrinfo_proxy+
D/libc    (  365): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/libc    (  365): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  365): [NET] +++++ res_nsend xid =2013 +++++
D/libc    (  365): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  365): [NET] NOT IN CACHE
,D/VolumeInfo( 3840): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
,D/VolumeInfo( 3840): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
,W/VolumeInfo( 3840): Can not create volume ID for unmounted volume null
,I/CalendarDefines( 3840): getNewCalendarAuthority()...
,D/SyncApplication( 3840): enableAppOperation()+
,D/SyncApplication( 3840): enableAppOperation()-
,D/HTCUtilities( 3840): isNeorSinged() + 
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3840, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3840, uid=10008, userID:0
W/PackageManager(  907): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
,D/HTCUtilities( 3840): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3840): isNeorSinged() return false
D/CDMountReceiver( 3840): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
D/libc    (  365): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 260
D/libc    (  365): [NET]res_nsend:resplen=84
,D/libc    (  365): [NET]res_queryN: exit 3, ancount=2
D/libc    (  365): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/CDMountReceiver( 3840): USB connected to PC
,D/libc    ( 2222): [NET] getaddrinfo_proxy-, success
,D/FOTAReceiver( 3840): onReceive() enter 
,D/FOTAReceiver( 3840): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,I/ActivityManager(  907): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3864 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/Process (  907): killProcessQuiet, pid=3546
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
D/libc    ( 2222): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2222): [NET] getaddrinfo-,err=8
I/ActivityManager(  907): Killing 3546:com.google.android.apps.magazines/u0a151 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3546
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  907): killProcessQuiet, pid=3398
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3398:com.htc.calendar/u0a13 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3398
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/HtcFingerPrintQuickLaunchProvider( 3864): -onCreate()
,V/Settings:HtcSettingsApplication( 3864): [3864/3864] onCreate()
,D/TetherSettings( 3864): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3864): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3864): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3864): Cust_ConnectToPC   : spcsc>false
D/        ( 3864): Cust_ConnectToPC   : IPT>true
,D/        ( 3864): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3864): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/TetherSettings( 3864): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3864): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3864): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3864): Cust_ConnectToPC   : spcsc>false
D/        ( 3864): Cust_ConnectToPC   : IPT>true
D/        ( 3864): Cust_ConnectToPC   : Singel_USB>false
W/Settings( 3864): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,E/SmartNS_Utility( 3864): hasRemovableStorageSlot: true
D/SmartNS_Utility( 3864): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3864): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3864): usb_cable_connect = 1
,D/SmartNS_Utility( 3864): usb_denied = 0
,I/SmartNS_NSReceiver( 3864): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3864): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3864): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/ContextImpl( 3864): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
,I/SmartNS_PSService( 3864): onReceive:com.htc.intent.action.USB_CONNECT2PC
W/Settings( 3864): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3864):  defaultType:0
,I/SmartNS_PSService( 3864): fail notificaiton:false
,D/SmartNS_Utility( 3864): usb_cable_connect = 1
D/SmartNS_Utility( 3864): usb_denied = 0
,I/SmartNS_PSService( 3864): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  907): bSetPropertyMultiRAB:false
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3864/1000)
I/ActivityManager(  907): Resuming delayed broadcast
,D/SmartNS_Utility( 3864): usb_cable_connect = 1
D/SmartNS_Utility( 3864): usb_denied = 0
,I/SmartNS_PSService( 3864): usb notificaiton:true
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  907): bSetPropertyMultiRAB:false
,I/RemoteViews( 1116): com.android.settings (true,33751552)
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
I/ActivityManager(  907): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.android.settings (3864/1000)
I/RemoteViews.Performance( 1116): com.android.settings 1 1 10
D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
W/WeatherUtility( 3662): can't get weather sync account
I/RemoteViews( 1116): com.android.settings (true,33751552)
D/SmartNS_Utility( 3864): usb_cable_connect = 1
D/SmartNS_Utility( 3864): usb_denied = 0
I/RemoteViews.Performance( 1116): com.android.settings 1 3 10
D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/SmartNS_PSService( 3864): KeyGuard locked:falseKeyGuard is secured:false
,D/SmartNS_PSService( 3864): USB Plugged, Set USBPlugged=  truePSenabled:false
I/ActivityManager(  907): Resuming delayed broadcast
,W/WeatherRequest( 3662): request cur loc, but there is no sys cur
,W/Settings( 3662): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
I/RemoteViews( 1273): com.google.android.googlequicksearchbox (false,0)
,I/RemoteViews.Performance( 1273): com.google.android.googlequicksearchbox 0 0 5
,I/ActivityManager(  907): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 1 7 17
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
,I/RemoteViews( 1273): pl.k2.droidoaudioteka (false,0)
I/ActivityManager(  907): Resuming delayed broadcast
,D/PMS     (  907): acquireWL(425951a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
I/RemoteViews.Performance( 1273): pl.k2.droidoaudioteka 0 1 8
,D/PMS     (  907): releaseWL(425951a0): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,D/PMS     (  907): acquireWL(4256a470): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1516 10014 null
,I/ActivityManager(  907): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,D/PMS     (  907): releaseWL(4256a470): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/ActivityManager(  907): Resuming delayed broadcast
D/WifiDataStallTracker(  907): onReceive: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
D/WifiDataStallTracker(  907): updateDataStallInfo: mDataStallTxRxSum={txSum=34 rxSum=24} preTxRxSum={txSum=0 rxSum=0}
D/WifiDataStallTracker(  907): updateDataStallInfo: IN/OUT
D/WifiDataStallTracker(  907): onDataStallAlarm: tag=20569 Sent 0 pkts since last received, < watchdogTrigger=5
D/WifiDataStallTracker(  907): startDataStallAlarm: tag=20570 delay=15s
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  907): getAllProviders()=[passive, gps, network]
,D/PMS     (  907): acquireWL(427a4b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null,
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
,D/PMS     (  907): releaseWL(427a4b20): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  907): getNetworkInfo networkType=9 called by com.google.android.gms (2222/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=6 [15][1][0]
D/ConnectivityService(  907): getNetworkInfo networkType=0 called by com.google.android.gms (2222/10028)
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
I/ActivityManager(  907): Resuming delayed broadcast
,V/AlarmManager(  907): sending alarm PendingIntent{41dcea00: PendingIntentRecord{425ba808 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1450199007326, Int=0
,I/SocialManager[SocialBiLogHelper]( 3794): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3794): last commit ulog time 1450189308101
,I/SocialManager[SocialBiLogHelper]( 3794): skip commit this time
I/ActivityManager(  907): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
D/PMS     (  907): acquireWL(427ab198): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2222 10028 null
,D/DotMatrix( 1605): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,W/CheckinRequestBuilder( 2222): awaiting user notification for token
,I/RemoteViews( 1116): com.google.android.gms (false,0)
V/AlarmManager(  907): sending alarm PendingIntent{41cba348: PendingIntentRecord{42479c90 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=59140, Int=0
,D/OnDemandProgressBar( 1116): release indeterminate drawable android.widget.OnDemandProgressBar{41e9e2e8 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
,I/RemoteViews.Performance( 1116): com.google.android.gms 3 10 3 12
,I/CheckinTask( 2222): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,W/GoogleHttpClient( 2222): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
,D/PMS     (  907): releaseWL(42454508): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,E/ActivityThread( 2222): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41df8640 that was originally bound here
E/ActivityThread( 2222): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41df8640 that was originally bound here
E/ActivityThread( 2222): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2222): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2222): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2222): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2222): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2222): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2222): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2222): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2222): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2222): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2222): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2222): 	at bks.a(SourceFile:298)
E/ActivityThread( 2222): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2222): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2222): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2222): 	at java.lang.Thread.run(Thread.java:864)
,D/WIFI_ICON( 1116): WifiActivity: 3
,D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/PMS     (  907): releaseWL(427ab198): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
I/AdsMeasurementBroadcastReceiver( 2222): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2222): Unauthorized to start the main service
V/AlarmManager(  907): sending alarm PendingIntent{424e8ad0: PendingIntentRecord{4258d0d8 com.google.android.gms startService}}, i=null, t=0, cnt=17077, w=84918423, Int=84918423
,I/ActivityManager(  907): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3895 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.gms (2222/10028)
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,D/PMS     (  907): releaseWL(42197ac0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=100 [1][1][0]
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 4, mLinkspeedSum: 288
D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
W/ContextImpl( 3895): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/SnetService( 2222): snet destroyed
,D/PowerUsageService( 3895): call getInstance()
I/ActivityManager(  907): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3895): MY_DEBUG = false
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,W/BatSI   (  907): Couldn't get kernel wake lock stats
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 6 times.
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Killing 3692:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,D/PMS     (  907): acquireWL(425bfb40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3895 1000 null
D/Process (  907): killProcessQuiet, pid=3692
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,W/WeatherUtility( 1116): can't get weather sync account
,D/WeatherUtility( 1399): Weather sync is On
,D/WSP     ( 1399): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
,I/ActivityManager(  907): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3917 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
W/WeatherUtility( 3662): can't get weather sync account
,I/ActivityManager(  907): Recipient 3692
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/WeatherRequest( 3662): request cur loc, but there is no sys cur
,W/Settings( 3662): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1273): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1273): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1273): com.htc.widget.weatherclock 2 9 17
,I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  907): Waited long enough for: ServiceRecord{4272ea48 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3935 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
,I/MusicStore( 3935): Database version: 95
,W/ContextImpl( 3935): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
D/WIFI_ICON( 1116): WifiActivity: 1
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,W/ContextImpl( 3935): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3935): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3935): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 3935): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3935, uid=10154, userID:0
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,D/MediaRouterService(  907): Client com.google.android.music (pid 3935): Registered
,D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
,I/MediaRouter( 3935): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/NetworkMonitor( 3935): type=WIFI subType= reason=null isConnected=true
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  907): getActiveNetworkInfo called by com.google.android.music (3935/10154)
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/MediaRouter( 3935): getSelectedRoute
,I/NetworkMonitor( 3935): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3935/10154)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/DFPI.PIReciver( 3726): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  907): Resuming delayed broadcast
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/DFPI.ApkInstallService( 3726): onHandleIntent
,I/DFPI.ApkInstallService( 3726): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3726): check CID = HTC__032
,I/DFPI.ApkInstallService( 3726): There is no Demo.apk in sd card or phone storage
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3935, uid=10154, userID:0
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/Process (  907): killProcessQuiet, pid=3185
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  907): Killing 3185:com.android.settings:remote/1000 (adj 15): empty #17
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
I/ActivityManager(  907): Recipient 3185
I/ActivityManager(  907): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3957 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3957/10051)
,D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.musicenhancer (3957/10051)
,W/BroadcastQueue(  907): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{42645ad0 u0 ReceiverList{42645a90 3957 com.htc.musicenhancer/10051/u0 remote:426668a8}}
,E/cutils  (  348): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3957): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
W/Vold    (  348): Returning OperationFailed - no handler for errno 30
,V/AlarmManager(  907): sending alarm PendingIntent{423d02a8: PendingIntentRecord{423cb138 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1450199008993, Int=0
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3976 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3708
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  907): Killing 3708:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3708
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3976): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3976): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3976): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3976): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3976): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3976): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3976): MODE_GSM access default DB
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3976): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3976): MODE_GSM access default DB
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3744
,I/ActivityManager(  907): Killing 3744:com.htc.stock/u0a81 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Recipient 3744
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/DFPI.PIReciver( 3726): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3726): onHandleIntent
,I/DFPI.ApkInstallService( 3726): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3726): check CID = HTC__032
,I/DFPI.ApkInstallService( 3726): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  907): Resuming delayed broadcast
,I/SoundPicker( 3976): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3976): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3976): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3976): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3976): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3976): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3976): MODE_GSM access default DB
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3976): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3976): MODE_GSM access default DB
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/PackageBroadcastService( 2222): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
I/ActivityManager(  907): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/PMS     (  907): acquireWL(425fd090): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(425fd090): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/PeopleContactsSync( 2222): CP2 sync disabled
I/PackageManager(  907):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2222, uid=10028, userID:0
,D/PMS     (  907): releaseWL(425bfb40): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,I/ActivityManager(  907): Resuming delayed broadcast,
,I/ActivityManager(  907): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4001 uid=10031 gids={50031, 3003, 5012}
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.RlzPingBroadcastReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Delay finish: com.google.android.partnersetup/.AppInstalledReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
,D/Process (  907): killProcessQuiet, pid=3756
,I/ActivityManager(  907): Killing 3756:com.htc.stock:remote/u0a81 (adj 15): empty #17
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/[PluginManager]RegisterService( 1399): onHandleIntent, action: android.intent.action.PACKAGE_ADDED, data: package:com.example.hello
,I/[PluginManager]RegisterService( 1399): handle notify Blinkfeed plugin client changed
I/ActivityManager(  907): Delay finish: com.htc.sense.hsp/.opensense.pluginmanager.RegisterReceiver
I/ActivityManager(  907): Recipient 3756
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4017 uid=10073 gids={50073, 3003, 5012, 1028, 1015}
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.android.vending.AssetBrowserActivity, state=1, flag=1, pid=4017, uid=10073, userID:0
,D/Finsky  ( 4017): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4017/10073)
,D/ConnectivityService(  907): getAllNetworkInfo called by com.android.vending (4017/10073)
,D/Finsky  ( 4017): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4017): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4017): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/PackageManager(  907):  setEnabledSetting(), pkgName=com.android.vending, clsName=com.google.android.finsky.activities.DebugActivity, state=2, flag=1, pid=4017, uid=10073, userID:0
,D/Process (  907): killProcessQuiet, pid=2797
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/ActivityManager(  907): Killing 2797:com.htc.sense.mms/u0a64 (adj 15): empty #17
D/Prism.PackageStateRece_( 1273): action: android.intent.action.PACKAGE_ADDED
I/SensorManager(  907): mEventCount = 450
D/Finsky  ( 4017): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4017): [1] 2.run: Finished loading 1 libraries.
,I/IcingCorporaProvider( 2918): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
I/ActivityManager(  907): Recipient 2797
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$CorporaChangedReceiver
,D/Finsky  ( 4017): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  907): Delaying start of: ServiceRecord{42531248 u0 com.android.vending/com.google.android.finsky.services.RestoreService}
,D/PMS     (  907): acquireWL(42602c70): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(42602c70): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425ddd90): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(425ddd90): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425a5528): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(425a5528): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4259fb50): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(4259fb50): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4259f620): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(4259f620): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4259d310): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(4259d310): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4258f230): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(4258f230): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4257f7b0): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(4257f7b0): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(4257b318): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(4257b318): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(42579940): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(42579940): PARTIAL_WAKE_LOCK  Icing 0x1 null
,D/PMS     (  907): acquireWL(425737b8): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/PMS     (  907): releaseWL(425737b8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,W/asset   ( 2918): Copying FileAsset 0x5d9b4908 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,D/PMS     (  907): acquireWL(424fe9d8): PARTIAL_WAKE_LOCK  Icing 0x1 2222 10028 null
,D/WifiNative-wlan0(  907): doString: SIGNAL_POLL
,W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: survey data missing!
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1171): environment dirty rate=0 [0][0][0]
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative RSSI = -51 abnormalRssiCnt = 0 newLinkSpeed = 72
,D/WifiStateMachine(  907): fetchRssiAndLinkSpeedNative mLinkspeedCount = 5, mLinkspeedSum: 360
,I/IcingCorporaProvider( 2918): UpdateCorporaTask done [took 442 ms] updated apps [took 442 ms] 
,D/WifiNative-wlan0(  907): doBoolean: SignalStrength 97
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1171): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  907):    returned true
,D/WifiStateMachine(  907): [ScoreAP] + current TXpacket:68, mTXpacketCount:43, avgLinkspeed:72,mAvgTxRate72
,D/WifiStateMachine(  907): [ScoreAP] + TX packet didn't send enough number, don't update TX rate in DB
,D/AutoSetting( 1399): service - mRequestRunnable: screen on delay 10s, request NLP now
,D/AutoSetting( 1399): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1399): service - requestNLP() NetworkLocationProvider not enabled
,D/BluetoothManagerService(  907): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  907): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@424c35d0 mBinding = false
,W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
,W/HtcDLNAServiceManager(  907): Settings:Agentname: bluetooth_on
,W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
,W/Settings:Agent(  907): >> traceCallingStack()
,W/Settings:Agent(  907): Process.myPid(): 907
,W/Settings:Agent(  907): Process.myTid(): 1352
,W/Settings:Agent(  907): Process.myUid(): 1000
,W/Settings:Agent(  907): 
,W/Settings:Agent(  907): 
,W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
,W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
,W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
,W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,W/Settings:Agent(  907): 
,W/Settings:Agent(  907): << traceCallingStack(): 22(ms)
,D/PMS     (  907): acquireWL(42049bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 0 0 null
,I/BatteryService(  907): n_update end
,D/UsbnetService(  907): BroadcastReceiver::onReceive+
D/UsbnetService(  907): onReceive BATTERY_CHANGED
D/UsbnetService(  907):  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
,D/UsbnetService(  907): BroadcastReceiver::onReceive-
D/PMS     (  907): releaseWL(42049bf0): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
D/HtcPowerSaver(  907): updateBatteryInfo
,I/IntentController( 1116): receive(android.intent.action.BATTERY_CHANGED,1,false)
,D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
D/DotMatrix( 1605): [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,D/DotMatrix( 1605): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,D/BluetoothManagerService(  907): Message: MESSAGE_DISABLE
D/PMS     (  907): runPSCheck
D/HtcPowerSaver(  907): Checking...
I/HtcPowerSaver(  907): >> updateStatus
D/PowerUI ( 1116): closing low battery warning: level=100
D/PowerUI ( 1116): plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
I/HtcPowerSaver(  907): updateStatus (8000,100,-1,false,false,false,-1)
,I/HtcPowerSaver(  907): << updateStatus
D/BluetoothManagerService(  907): Sending off request.
D/BluetoothAdapterState( 1633): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1633): Setting state to 13
I/BluetoothAdapterState( 1633): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1633): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 1633): onBluetoothDisable()
I/bt-btm  ( 1633): BTM_SetDiscoverability
I/bt-btif ( 1633): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1633): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiManager( 3531): setWifiEnabled: Base Package Name=com.example.hello, uid=10356
I/bt-btm  ( 1633): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1633): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1633): br_edr_supported=0x0
I/bt-btm  ( 1633): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1633): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1633): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1633): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1633): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1633): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1633): BTM_SetConnectability
I/bt-btm  ( 1633): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1633): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1633): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
,I/BluetoothAdapterProperties( 1633): adapterPropertyChangedCallback with type:7 len:4
D/BluetoothAdapterProperties( 1633): Scan Mode:20
E/BTIF_CORE( 1633): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1633): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothAdapterState( 1633): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  907): Bluetooth State Change Intent: 12 -> 13
,I/bt-btif ( 1633): BTA_JvDeleteRecord
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:15
I/bt-btif ( 1633): BTA_JvRfcommStopServer
,D/BluetoothRemoteDevices( 1633): Wake lock Aquired
,D/WifiStateMachine(  907): WiFiDisplay: getWifidisplayApEnabled=false
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1819): Received state change = 13
V/BluetoothPbapReceiver( 1633): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1633): ***********state = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1819): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b06530
I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1819): onDeInitialized
D/WifiService(  907): New client listening to asynchronous messages
D/PMS     (  907): acquireWL(425813f8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1633 1002 null
D/WifiService(  907): setWifiEnabled: false pid=3531, uid=10356
E/WifiService(  907): Invoking mWifiStateMachine.setWifiEnabled
D/bt-btm  ( 1633): BTM_FreeSCN 
I/bt-btif ( 1633): BTA_JvDeleteRecord
I/bt-btif ( 1633): BTA_JvRfcommStopServer
D/bt-btm  ( 1633): BTM_FreeSCN 
I/bt-btif ( 1633): BTA_JvDeleteRecord
I/bt-btif ( 1633): BTA_JvRfcommStopServer
D/bt-btm  ( 1633): BTM_FreeSCN 
I/bt-btif ( 1633): BTA_JvDeleteRecord
I/bt-btif ( 1633): BTA_JvRfcommStopServer
D/bt-btm  ( 1633): BTM_FreeSCN 
I/bt-btif ( 1633): BTA_JvDeleteRecord
I/bt-btif ( 1633): BTA_JvRfcommStopServer
D/bt-btm  ( 1633): BTM_FreeSCN 
I/bt-btif ( 1633): BTA_JvDeleteRecord
I/bt-btif ( 1633): BTA_JvRfcommStopServer
D/bt-btm  ( 1633): BTM_FreeSCN 
E/BtOppRfcommListener( 1633): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/HtcDLNAServiceManager(  907): Settings:AgentMONITOR_LOG
V/BluetoothSapService( 1633): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
W/HtcDLNAServiceManager(  907): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  907): Settings:Agentvalue: 0
W/Settings:Agent(  907): >> traceCallingStack()
W/Settings:Agent(  907): Process.myPid(): 907
W/Settings:Agent(  907): Process.myTid(): 1101
W/Settings:Agent(  907): Process.myUid(): 1000
W/Settings:Agent(  907): 
W/Settings:Agent(  907): 
,I/IntentController( 1116): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
W/System.err(  907): java.lang.Throwable: stack dump
W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  907): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  907): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  907): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  907): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  907): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  907): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  907): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
,W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  907): 
W/Settings:Agent(  907): << traceCallingStack(): 2(ms)
,E/bt-btif ( 1633): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1633): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1633): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1633): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1633): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1633): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1633): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1633): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1633): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1633): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1633): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1633): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1633): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1633): Write Extended Inquiry Response to controller
I/bt-btm  ( 1633): Write Extended Inquiry Response to controller
I/bt-btm  ( 1633): Write Extended Inquiry Response to controller
I/bt-btm  ( 1633): Write Extended Inquiry Response to controller
I/bt-btm  ( 1633): BTM_SetDiscoverability
I/bt-btm  ( 1633): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1633): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1633): br_edr_supported=0x0
I/bt-btm  ( 1633): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1633): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1633): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1633): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1633): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1633): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1633): BTM_SetConnectability
I/bt-btm  ( 1633): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1633): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1633): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1633): BTM_IsInquiryActive
I/bt-btm  ( 1633): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1633): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1633): BTM_FreeSCN 
I/bt-btm  ( 1633): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1633): BTM_FreeSCN 
I/bt-btm  ( 1633): BTM_SEC_CLR[4]: id 29
D/bt-avp  ( 1633): AVRC_Close handle:0
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1633): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1633): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1633): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1633): GATT_Deregister gatt_if=3
,I/bt-att  ( 1633): GATT_Deregister gatt_if=4
,D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1819): cancelAllNotification
D/BluetoothMasReceiver( 1633): Bluetooth STATE CHANGED to 13
,D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1819): getNotificationManager
V/BluetoothSapReceiver( 1633): SapReceiver onReceive 
V/BluetoothSapReceiver( 1633): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1633):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 1633): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
I/WifiService(  907): isSprintWifiRestricted(): false
I/WifiService(  907): isMdmWifiRestricted(): false
D/WifiSettingsStore(  907): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,V/BluetoothPbapService( 1633): Pbap Service closeService in
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  907): java.lang.Throwable: stack dump
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423680e0:true
W/AppWidgetServiceImpl(  907): updateAppWidget failed! callbacks null
D/PMS     (  907): acquireWL(4231c8c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3864 1000 null
W/ContextImpl( 3864): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  907): releaseWL(4231c8c0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  907): acquireWL(423e8430): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3864 1000 null
I/LocationAgent( 3864): new LocationAgent instance!!
,D/HtcTagManager( 3864): HtcTagManager construction complete
,V/BluetoothPbapService( 1633): successfully stopped pbap service
V/BluetoothPbapService( 1633): Pbap Service closeService out
,I/ActivityManager(  907): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4057 uid=10037 gids={50037, 3002, 3001}
V/BluetoothSapService( 1633): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapService( 1633): state: 13
I/BatteryController( 1116): status:5 level:100 unsupport:false plugged:true
D/BluetoothAdapter( 1633): 1102048312: getState(). Returning 13
V/BluetoothSapService( 1633): Stopping SAP server process
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1819): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1819): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1819):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1819): writeLinkLossAlertLevelAll: 0, false
D/BluetoothAdapter( 3864): 1102453352: getState(). Returning 13
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1819): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1819): loadDeviceConfiguration() init =false
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1819):  + mTag.getPrimaryDeviceList() = []
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1819): deinit: 0
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1819): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1819): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1819): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1819): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1819): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1819): setPendingRequestAlarm: false, mContext = null, null
V/BluetoothSapService( 1633): Sap Service closeSapService in
V/BluetoothSapService( 1633): Close listen Socket : 
D/BluetoothManagerService(  907): Message: MESSAGE_UNREGISTER_ADAPTER
V/BluetoothSapService( 1633): Close rfcomm Socket : 
V/BluetoothSapService( 1633): Close sapd  Socket : 
V/BluetoothSapReceiver( 1633): BluetoothSapReceiver deinit
D/BluetoothInputDevice( 3864): BluetoothInputDevice()
D/BluetoothManagerService(  907): registerStateChangeCallback+
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1819): Exit IdleState
D/BluetoothManagerService(  907): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4205a930:true
I/jxcore-log( 3531): ****TEST TOOK:  5134  ms ****
I/jxcore-log( 3531): 
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 7
I/jxcore-log( 3531): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3531): 
D/BluetoothAdapter( 3864): 1102453352: getState(). Returning 13
D/BluetoothInputDevice( 3864): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3864): Bluetooth service connected
W/BluetoothInputDevice( 3864): Proxy not attached to service
D/WirelessDisplayService(  907): getMirrorDisplayStatus:falsecurState:1
V/BluetoothSapService( 1633): successfully stopped Sap service
V/BluetoothSapService( 1633): Sap Service closeSapService out
D/BluetoothPan( 3864): BluetoothPan()
I/BtOppRfcommListener( 1633): stopping Accept Thread
I/BtOppRfcommListener( 1633): BluetoothSocket listen thread finished
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiPerfLock(  907): release()
D/BluetoothManagerService(  907): Registered receivers: 8
D/WifiStateMachine(  907): PerfLock released for exiting ConnectedState
D/BluetoothAdapter( 3864): 1102453352: getState(). Returning 13
D/BluetoothPan( 3864): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3864): Bluetooth service connected
V/BluetoothPbapService( 1633): Pbap Service onDestroy
V/BluetoothPbapService( 1633): Pbap Service closeService in
V/BluetoothPbapService( 1633): Pbap Service closeService out
D/WifiNative-wlan0(  907,): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
D/BluetoothMap( 3864): Create BluetoothMap proxy object
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/BluetoothManagerService(  907): Registered receivers: 9
D/WifiNative-wlan0(  907):    returned true
V/BluetoothSapService( 1633): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41b37618
V/BluetoothSapService( 1633): Sap Service closeSapService in
V/BluetoothSapService( 1633): Close listen Socket : 
V/BluetoothSapService( 1633): Close rfcomm Socket : 
V/BluetoothSapService( 1633): Close sapd  Socket : 
D/DhcpStateMachine(  907): [RunningState] Stop DHCP
D/libc    (  907): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
E/BluetoothMap( 3864): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
D/ConnectivityService(  907): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/PMS     (  907): acquireWL(422f8ec0): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 907 1000 null
D/WifiP2pService(  907): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  907): registerStateChangeCallback+
V/BluetoothSapService( 1633): Sap Service closeSapService out
V/BluetoothSapService( 1633): ***onDestroyed***
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 3864): BluetoothSap() call bindService
D/BluetoothManagerService(  907): Registered receivers: 10
I/QuickSettingBluetooth( 1116): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1116): removeIcon slot=bluetooth index=12 viewIndex=0
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/libc    (  907): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  907): [NET] getaddrinfo-, SUCCESS
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WifiDataStallTracker(  907): stopDataStallAlarm: current tag=20570 mDataStallAlarmIntent=PendingIntent{4259d808: PendingIntentRecord{4231cba0 android broadcastIntent}}
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
W/ContextImpl( 3864): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/BluetoothPbap( 3864): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING GET
D/BluetoothManagerService(  907): Registered receivers: 11
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiNative-wlan0(  907):    returned null
E/WifiStateMachine(  907): Unexpected BatchedScanResults :null
D/BluetoothAdapter( 3864): 1102453352: getState(). Returning 13
D/WifiNative-wlan0(  907): doString: DRIVER WLS_BATCHING STOP
D/BluetoothPbap( 3864): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3864): Bluetooth service connected
D/LocalBluetoothProfileManager( 3864): LocalBluetoothProfileManager construction complete
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiNative-wlan0(  907):    returned null
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
D/UsbnetStateTracker(  907): isAvailable+-
D/UsbnetStateTracker(  907): reconnect
D/UsbnetStateTracker(  907): isAvailable+-
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  907): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  907): Provision feature enable=false
D/ConnectivityService(  907): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService(  907): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  907): default: reconnect()
D/MDST    (  907): default: setTeardownRequested(false)
D/MDST    (  907): default: setEnableApn apnType =default , enable=true
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WifiStateMachine(  907): Call handleNetworkDisconnect() in SupplicantStoppingState
,D/WifiNative-wlan0(  907): doBoolean: DRIVER POWERMODE 0
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1171): Power_Mode_Type mode = 0
I/wpa_supplicant( 1171): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
D/DockEventReceiver( 3864): finishStartingService: stopping service
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 61
D/ConnectivityService(  907): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  907): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  907): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  907): P2pDisablingState
D/WifiP2pService(  907): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): p2p socket connection lost
D/WifiP2pService(  907): P2pDisabledState
D/WifiDisplayController(  907): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  907): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  907): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  907): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  907): P2pDisabledState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  907):  WFD CtrlPort: 0
D/WifiP2pService(  907):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  907):  WFD CtrlPort: 0
D/WifiP2pService(  907):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/ConnectivityService(  907): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
I/WifiDisplayController(  907): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  907): updateConnection
I/WifiDisplayController(  907): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  907): updateConnection enter step 4
D/WifiDisplayController(  907): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  907): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  907):     Client/Owner: Client
D/WifiDisplayAdapter(  907):     GroupId: 
D/WifiDisplayAdapter(  907):     Passphrase: 
D/WifiDisplayAdapter(  907):     SessionId: 0
D/WifiDisplayAdapter(  907):     IP Address: }
V/AudioService(  907): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  907):     Client/Owner: Client
V/AudioService(  907):     GroupId: 
V/AudioService(  907):     Passphrase: 
V/AudioService(  907):     SessionId: 0
V/AudioService(  907):     IP Address: }
D/HtcEffectManagerBase(  907): onEventChanged id=5 status=false
D/HtcEffectManager(  907): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/HtcEffectManager(  907): convertEffect before=902
D/HtcEffectManager(  907): convertEffect after=902
D/WifiNative-wlan0(  907):    returned true
D/WifiNative-wlan0(  907): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  907): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1171): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1171): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/WifiNative-wlan0(  907):    returned true
D/HtcBtWidget_BTWidgetProvider( 4057): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 4057): updateWidget(context) for widget: 
D/libc    (  365): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/libc    (  365): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  365): [NET] getaddrinfo-, SUCCESS
D/WISPrService( 3864): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiP2pService(  907): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  907): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '29 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 29 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
D/PMS     (  907): releaseWL(423e8430): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
W/ConnectivityService(  907): Exception trying to remove a route: java.lang.IllegalStateException: command '31 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 31 Failed to remove route from default table (No such process)'
D/ConnectivityService(  907): handleConnectivityChange: resetting
D/ConnectivityService(  907): resetConnections(wlan0, 3)
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/WifiNative-p2p0(  907): doBoolean: TERMINATE
W/WifiHW  (  907): QCOM Debug wifi_send_command "TERMINATE"
E/wpa_supplicant( 1171): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1171): TDLS: Tear down peers
I/wpa_supplicant( 1171): wpa_driver_nl80211_disconnect(reason_code=3)
D/WISPrService( 3864): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiNative-p2p0(  907):    returned true
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/libc    (  365): [NET] entry_id:5   entry:0xb80f1190  removed 
D/libc    (  365): [NET] entry_id:4   entry:0xb80f12a0  removed 
D/libc    (  365): [NET] entry_id:1   entry:0xb80f1428  removed 
D/libc    (  365): [NET] entry_id:6   entry:0xb80f1860  removed 
D/libc    (  365): [NET] entry_id:3   entry:0xb80f0fd8  removed 
D/libc    (  365): [NET] entry_id:2   entry:0xb80f10f8  removed 
D/libc    (  365): *************************
D/libc    (  365): *** DNS CACHE FLUSHED ***
D/libc    (  365): *************************
I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiService(  907): New client listening to asynchronous messages
D/ConnectivityService(  907): flush DNS cache for net 1(wlan0)
D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/Nat464Xlat(  907): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  907): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  907): acquireWL(425625e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1371 10028 null
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  907): [MLHD] Error! unhandled message 1 { when=-8ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
E/BluetoothFtpService:RfcommSocketAcceptThread( 1633): Shutdown
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1116): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/ConnectivityService(  907): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  907): acquireWL(42683d70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 907 1000 null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
D/WISPrService( 3864): >>>>>WISPrService start isConnected = false<<<<<
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  907): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiStateMachine(  907): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  907): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
D/WISPrService( 3864): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/WifiStateMachine(  907): startScan Pid: 907 Uid 1000
D/BluetoothMasReceiver( 1633): Bluetooth STATE CHANGED to 13
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/PMS     (  907): acquireWL(42423300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1371 10028 null
D/ConnectivityService(  907): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1116): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  907): reportInetCondition for net -1, percentage: 0 by  (1371/10028)
D/ConnectivityService(  907): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1171): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1171): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  907): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1171): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  907): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  907): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1171): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb71c4bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1171):    addr=c0:ff:d4:d3:aa:48
E/wpa_supplicant( 1171): send_and_recv error -2 - cmd 12
I/wpa_supplicant( 1171): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
D/HTCRequest(  907): WifiMonitor:getReasonFromEventString() 3
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  907): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1171): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  907): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1171): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1171): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1171): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  907): WifiMonitor:getFreqFromEventString() 2412
I/wpa_supplicant( 1171): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1171): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  907): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1171): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1171): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1171): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 18
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
I//system/bin/ip(  365): RTNETLINK answers: No such process
D/HTCRequest(  907): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  907): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/logwrapper(  365): /system/bin/ip terminated by exit(2)
D/WifiMonitor(  907): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1819): Received state change = 13
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Tethering(  907): [isWifi] getHotspotEnabled: false
D/Process (  907): killProcessQuiet, pid=3675
D/PMS     (  907): releaseWL(425625e8): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
D/PMS     (  907): releaseWL(42423300): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
I/ActivityManager(  907): Killing 3675:com.htc.task/u0a70 (adj 15): empty #17
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
D/Tethering(  907): interfaceStatusChanged wlan0, false
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/Tethering(  907): [isWifi] getHotspotEnabled: false
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1819): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b06530
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1819): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1819): deinitLeServices: null
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1371/10028)
D/PMS     (  907): releaseWL(42683d70): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/ConnectivityService(  907): mActiveDefaultNetwork: -1
D/ConnectivityService(  907): handleInetConditionChange: no active default network - ignore
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  907): Recipient 3675
I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,I/QuickSettingWifi( 1116): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
,D/Process (  907): killProcessQuiet, pid=3813
I/ActivityManager(  907): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4081 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/ActivityManager(  907): Killing 3813:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/AlarmManager(  907): sending alarm PendingIntent{42531cf0: PendingIntentRecord{42735e18 com.android.vending startService}}, i=null, t=0, cnt=1, w=1450199011167, Int=0
,V/Settings:HtcSettingsApplication( 4081): [4081/4081] onCreate()
,D/WifiService(  907): New client listening to asynchronous messages
,W/bt-btif ( 1633): ag scb idx 1 not allocated
W/bt-btif ( 1633): ag scb idx 2 not allocated
E/bt-btif ( 1633): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1633): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1633): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1633): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1633): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1633): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1633): L2CAP - PSM: 0x0017 not found for deregistration
,E/bt_userial_mct( 1633): userial_close userial_thread_created userial_running is 1 
,I/ActivityManager(  907): Recipient 3813
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,E/wpa_supplicant( 1171): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1171): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
,I/wpa_supplicant( 1171): nl80211: wpa_driver_nl80211_deinit
D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  907): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/Finsky  ( 4017): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4017): [1] CheckWifiAndAutoUpdate.cancelCheck: Cancelling auto-update wifi check.
,D/wpa_supplicant( 1171): netlink: Operstate: linkmode=0, operstate=6
,E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1171): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1171): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1171): nl80211: Unsubscribe mgmt frames handle 0xb71c5718 (mode change)
I/wpa_supplicant( 1171): htc_wext_command_deinit +
I/wpa_supplicant( 1171): htc_wext_command_deinit -
E/wpa_supplicant( 1171): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
,I/wpa_supplicant( 1171): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  907): interfaceLinkStateChanged wlan0, false
,D/Tethering(  907): interfaceStatusChanged wlan0, false
E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,E/cutils-trace( 4077): Error opening trace file: No such file or directory (2)
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
,W/WifiHW  (  907): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0x627f4e18
,I/wpa_ctrl(  907): [wpa_ctrl_close] ctrl=0x626d75a8
W/WifiHW  (  907): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
,E/WifiStateMachine(  907): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
,D/WifiStateMachine(  907): setAuthErrorNotificationVisible visible=false
,D/WifiNative-wlan0(  907): doBoolean: SET_WIFI_ON 0
,D/WifiNative-wlan0(  907):    returned false
,D/WifiStateMachine(  907): Enter handleNetworkDisconnect
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  907): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
I/IntentController( 1116): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
D/WirelessDisplayService(  907): WIFI Trun OFF
,D/WirelessDisplayService(  907): getDiscoveryDongleList
,D/WifiStateMachine(  907): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  907): Exit handleNetworkDisconnect
,E/WifiStateMachine(  907): [MLHD] Error! unhandled message 6 { when=-114ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiDataStallTracker(  907): onReceive: action=android.net.wifi.STATE_CHANGE
,D/WifiDataStallTracker(  907): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/WIFI_ICON( 1116): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/PMS     (  907): acquireWL(4211d098): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 907 1000 null
,D/WifiStateTracker(  907): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
,I/IntentController( 1116): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WIFI_ICON( 1116): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1116): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/WISPrService( 3864): >>>>>WISPrService start isConnected = false<<<<<
,D/WISPrService( 3864): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
,D/CustomizationManager( 4077): ====startRecUseTime====
,D/htc.customization.log.level( 4077):  is 
,W/CustomizationLogLevel( 4077): Level value is invalid, use default level 2
,I/QuickSettingWifi( 1116): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,W/GLSUser ( 1371): GoogleAccountDataService.getToken()
,I/bt-btif ( 1633): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1633): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,I/QuickSettingWifi( 1116): receive.wifiConnect:false wifiAPname:null elapse:0
,D/HeadsetService( 1633): Received stop request...Stopping profile...
,D/BluetoothHeadset(  907): Proxy object disconnected
D/BluetoothHeadset( 1116): Proxy object disconnected
I/QuickSettingMiniLite( 1116): btListener.disconnect:HEADSET
,D/BluetoothAdapterState( 1633): Stopping profile services that were post enabled
D/A2dpService( 1633): Received stop request...Stopping profile...
,D/A2dpStateMachine( 1633): doQuit
,D/A2dpStateMachine( 1633): Exit Disconnected: -1
,D/BluetoothHeadset( 1244): Proxy object disconnected
,D/BluetoothA2dp(  907): Proxy object disconnected
,D/BluetoothHeadset( 1244): Proxy object disconnected
W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1371): GLS error: BadAuthentication thalitester@gmail.com androidmarket
,D/HidService( 1633): Received stop request...Stopping profile...
,D/HealthService( 1633): Received stop request...Stopping profile...
,D/BluetoothPhoneService( 1244): BluetoothHeadset onServiceDisconnected
D/PanService( 1633): Received stop request...Stopping profile...
D/PanService( 1633): stop
,D/PanService( 1633): stop: mTetherAc send disconnect
,W/GLSActivity( 1371): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/BluetoothTethering(  907): got CMD_CHANNEL_DISCONNECT
,D/BluetoothTethering(  907): got CMD_CHANNEL_DISCONNECTED
,E/BluetoothTethering(  907): attempted to stop reverse tether with nothing tethered
,D/BluetoothPan(  907): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService( 1633): Profile still running: com.android.bluetooth.hdp.HealthService
,D/BtGatt.DebugUtils( 1633): handleDebugAction() action=null
D/BtGatt.GattService( 1633): Received stop request...Stopping profile...
D/BtGatt.GattService( 1633): stop()
,D/BluetoothAdapterService( 1633): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 1633): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 1633): Cleaning up Bluetooth Handsfree callback object
,D/A2dpStateMachine( 1633): cleanup
,D/Avrcp   ( 1633): Unregistering previous receiver
D/BluetoothAdapterService( 1633): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1633): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1633): cleanup: HH disabling or disabled already, status = 0
,W/BluetoothHidServiceJni( 1633): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1633): Profile still running: com.android.bluetooth.pan.PanService
W/BluetoothHealthServiceJni( 1633): Cleaning up Bluetooth Health Interface...
,W/BluetoothHealthServiceJni( 1633): Cleaning up Bluetooth Health object
D/PanService( 1633): CMD_CHANNEL_DISCONNECTED
D/PanService( 1633): CMD_CHANNEL_DISCONNECTED call disconnected
,D/BluetoothAdapterService( 1633): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1633): Cleaning up Bluetooth PAN Interface...
,W/BluetoothPanServiceJni( 1633): Cleaning up Bluetooth PAN callback object
,W/Finsky  ( 4017): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/BluetoothAdapterState( 1633): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1633): Setting state to 10
I/BluetoothAdapterState( 1633): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1633): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  907): +onBluetoothStateChange prev=13 new=10
I/BluetoothAdapterState( 1633): Entering OffState
D/BluetoothManagerService(  907): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  907): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  907): Broadcasting onBluetoothStateChange(false) to 11 receivers.
D/BluetoothMap( 3864): onBluetoothStateChange: up=false
,D/Finsky  ( 4017): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4017): [1] DailyHygiene.reschedule: Scheduling new run in 816 minutes (failures=5)
,E/BluetoothMap( 3864): 
E/BluetoothMap( 3864): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41b70918
E/BluetoothMap( 3864): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3864): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3864): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3864): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3864): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3864): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3864): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1116): onBluetoothStateChange: up=false
,E/BluetoothPan( 3864): 
E/BluetoothPan( 3864): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41b6f598
E/BluetoothPan( 3864): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3864): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3864): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3864): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3864): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3864): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3864): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothPbap( 3864): onBluetoothStateChange: up=false
,E/BluetoothPbap( 3864): 
E/BluetoothPbap( 3864): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41b76fd8
E/BluetoothPbap( 3864): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3864): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3864): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3864): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3864): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3864): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3864): 	at dalvik.system.NativeStart.run(Native Method)
,D/BluetoothHeadset( 1244): onBluetoothStateChange: up=false
,D/BluetoothHeadset( 1244): onBluetoothStateChange: up=false
,D/BluetoothInputDevice( 3864): onBluetoothStateChange: up=false
,E/BluetoothInputDevice( 3864): 
E/BluetoothInputDevice( 3864): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41b6e000
E/BluetoothInputDevice( 3864): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3864): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3864): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3864): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3864): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3864): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3864): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothSap( 3864): onBluetoothStateChange on: false
D/BluetoothHeadset(  907): onBluetoothStateChange: up=false
,D/BluetoothA2dp(  907): onBluetoothStateChange: up=false
D/BluetoothManagerService(  907): Calling onBluetoothServiceDown callbacks
,D/BluetoothManagerService(  907): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1845): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c226f0
D/BluetoothAdapter( 1845): onBluetoothServiceDown: done
D/BluetoothAdapter( 1116): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41eca1a8
,D/BluetoothAdapter( 1116): onBluetoothServiceDown: done
,D/BluetoothAdapter( 3864): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b624d0
,D/BluetoothAdapter( 3864): onBluetoothServiceDown: done
D/BluetoothAdapter( 1244): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41d86eb8
,D/BluetoothAdapter( 1244): onBluetoothServiceDown: done
D/BluetoothAdapter(  907): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@424c35d0
D/BluetoothAdapter(  907): onBluetoothServiceDown: done
D/BluetoothAdapter( 1819): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b06e00
,D/BluetoothAdapter( 1819): onBluetoothServiceDown: done
D/BluetoothAdapter( 3531): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41af9eb8
D/BluetoothAdapter( 3531): onBluetoothServiceDown: done
D/BluetoothAdapter( 1437): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c35d38
D/BluetoothAdapter( 1437): onBluetoothServiceDown: done
,D/BluetoothAdapter( 1633): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41afd0a8
D/BluetoothDevice( 1633): onBluetoothServiceDown : UnRegister callback
,D/BluetoothAdapter( 1633): onBluetoothServiceDown: done
D/BluetoothAdapter( 1257): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41bb5da8
,D/BluetoothAdapter( 1257): onBluetoothServiceDown: done
,D/BluetoothManagerService(  907): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@424c35d0 mBinding = false
,D/Process (  907): killProcessQuiet, pid=3827
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/BluetoothManagerService(  907): Sending unbind request.
,D/BluetoothAdapterService( 1633): Cleaning up adapter native....
,I/bt-btif ( 1633): HAL bt_hal_cbacks->thread_evt_cb
I/ActivityManager(  907): Killing 3827:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/PMS     (  907): releaseWL(425813f8): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/BluetoothAdapterService( 1633): Done cleaning up adapter native....
D/BluetoothAdapterService(1102030136)( 1633): ****onDestroy()********
,D/BluetoothManagerService(  907): Bluetooth State Change Intent: 13 -> 10
D/Process (  907): killProcessQuiet, pid=3768
D/BtGatt.GattService( 1633): cleanup()
W/bt-btif ( 1633): GATTC Module not enabled/already disabled
W/bt-btif ( 1633): GATTS Module not enabled/already disabled
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/IntentController( 1116): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,D/NfcHandover( 1257): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
,D/BluetoothMasReceiver( 1633): Bluetooth STATE CHANGED to 10
I/ActivityManager(  907): Recipient 3827
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  907): Killing 3768:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
D/LocalBluetoothProfileManager( 3864): setBluetoothStateOff
D/HtcTagManager( 3864): stopProxy
V/BluetoothMasService( 1633): onDestroy: mIsEmailEnabled: true
,W/BluetoothEventManager( 3864): unregister mProfileBroadcastReceiver fail
I/ActivityManager(  907): Recipient 3768
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/TetherPref( 3864): persistRestoreBluetoothState false
D/HtcBtWidget_BTWidgetProvider( 4057): onBTStateChanged() for widget: 
,D/CustomizationManager( 4077):  Read ACC file spent 0.062 (s)
D/HtcBtWidget_BTWidgetProvider( 4057): updateWidget(context) for widget: 
,D/CIDMapFileReader( 4077): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__102
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__032
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4077): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4077): Parsing tag item name = HTC__031
D/PMS     (  907): acquireWL(4253a8d0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3864 1000 null
W/ContextImpl( 3864): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  907): releaseWL(4253a8d0): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/PMS     (  907): acquireWL(42721660): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3864 1000 null
V/CustomizationCIDLoader( 4077): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 4077): Parsing tag category name = system
D/DockEventReceiver( 3864): finishStartingService: stopping service
I/CustomizationCIDLoader( 4077): Parsing tag category name = application
I/CustomizationCIDLoader( 4077): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4077): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4077): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4077): Parsing tag category name = ACC
,I/CustomizationCIDLoader( 4077): Parsing tag category name = Settings
D/CustomizationManager( 4077):  Read CID file spent 0.107 (s)
,D/CustomizationManager( 4077):  All configurations done spent 0.107 (s)
,D/BluetoothMasReceiver( 1633): Bluetooth STATE CHANGED to 10
W/HtcNativeFlag( 4077): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4077): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4077): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4077): Fail to get flag for type 'language', use default value: -1
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1819): Received state change = 10
D/PMS     (  907): releaseWL(42721660): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  907): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  907): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42396be8:true
W/BluetoothHeadset( 1116): Proxy not attached to service
,W/System.err(  907): 	at java.lang.Thread.dumpStack(Thread.java:512)
I/QuickSettingMiniLite( 1116): updateLiteState:no connect device!
,W/System.err(  907): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  907): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  907): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4081): new LocationAgent instance!!
,D/HtcTagManager( 4081): HtcTagManager construction complete
,D/BluetoothAdapter( 4081): 1101986496: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 4081): BluetoothInputDevice()
I/Icing   ( 2222): Indexing 3E78574859FB8ED28F43D3ECB139F4117F00AB29 from com.google.android.googlequicksearchbox
,D/BluetoothAdapter( 1116): 1104720128: getState() :  mService = null. Returning STATE_OFF
I/QuickSettingBluetooth( 1116): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 12
D/BluetoothAdapter( 4081): 1101986496: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4081): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4081): Bluetooth service connected
,W/BluetoothInputDevice( 4081): Proxy not attached to service
,D/BluetoothPan( 4081): BluetoothPan()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothAdapter( 4081): 1101986496: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 4081): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 4081): Bluetooth service connected
,D/BluetoothManagerService(  907): Registered receivers: 13
D/BluetoothMap( 4081): Create BluetoothMap proxy object
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 14
,E/BluetoothMap( 4081): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  907): Registered receivers: 15
,D/BluetoothSap( 4081): BluetoothSap() call bindService
,D/BluetoothPbap( 4081): BluetoothPbap()
D/BluetoothManagerService(  907): registerStateChangeCallback+
D/BluetoothManagerService(  907): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  907): Registered receivers: 16
D/BluetoothAdapter( 4081): 1101986496: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4081): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4081): Bluetooth service connected
D/LocalBluetoothProfileManager( 4081): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4081): 1101986496: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4081): 1101986496: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4081): setBluetoothStateOff
,D/HtcTagManager( 4081): stopProxy
,W/BluetoothEventManager( 4081): unregister mProfileBroadcastReceiver fail
W/ContextImpl( 4081): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/Process (  907): killProcessQuiet, pid=3781
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  907): Killing 3781:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3781
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/PackageManager(  907): deletePackageAsUser: pkg=com.example.hello, pid=4077, uid=2000 user=0
,D/Process (  907): killProcessQuiet, pid=3531
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
I/ActivityManager(  907): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
I/ActivityManager(  907): Killing 3531:com.example.hello/u0a356 (adj 0): stop com.example.hello
,W/asset   (  907): Copying FileAsset 0x634d8d68 (zip:/data/app/com.example.hello-1.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,W/ActivityManager(  907): handleTopAppChanged(): The previous AP is died unexpectedly.
W/ActivityManager(  907): Force removing ActivityRecord{4209a400 u0 com.example.hello/.MainActivity t2}: app died, no saved state
,W/PackageSettings(  907): Skipping PackageSetting{42225be0 com.test.thalitest/10348} due to missing metadata
,I/ActivityManager(  907): Force stopping com.example.hello appid=10356 user=0: pkg removed
,W/InputDispatcher(  907): channel '4233b748 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  907): channel '4233b748 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher(  907): Attempted to unregister already unregistered input channel '4233b748 com.example.hello.MainActivity (s)'
D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1605): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
D/DotMatrix( 1605): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver packageName:com.example.hello
,I/HtcKeyguardAppUpdateMonitor( 1116): ApplicationsIntentReceiver replacing:false
,I/acms    ( 1902): Unregistering com.example.hello
,E/acms    ( 1902): Could not unregister removed application com.example.hello
I/WindowManager(  907): WINDOW DIED Window{4233b748 u0 com.example.hello/com.example.hello.MainActivity}
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  907): Client connection lost with reason: 4
,W/GeofencerStateMachine( 1437): Ignoring removeGeofence because network location is disabled.
,I/FeedHostManager( 1273): [onResume]
,I/FeedProviderManager( 1273): onResume
D/PMS     (  907): acquireWL(42758530): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1437 10028 null
W/WindowManager(  907): Failed looking up window
W/WindowManager(  907): java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@427af530 does not exist
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8463)
W/WindowManager(  907): 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:8454)
W/WindowManager(  907): 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1052)
W/WindowManager(  907): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:501)
W/WindowManager(  907): 	at dalvik.system.NativeStart.run(Native Method)
,I/WindowState(  907): WIN DEATH: null
I/SocialFeedProvider( 1273): +onResume
I/SocialFeedProvider( 1273): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1273): -onResume
,I/ConnectivityHelper( 1273): [getCurrentConnectionType] no network connection
D/PMS     (  907): releaseWL(42758530): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.launcher (1273/10075)
,I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
I/Prism.ItemManager( 1273): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
W/AccTypeManager( 1330): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1330): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
I/Prism.ItemManager( 3794): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3794): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,D/Finsky  ( 4017): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/SystemReader( 1257): Cannot find nfc_is_upgrade_to_ar890, use default value instead
I/ActivityManager(  907): Resuming delayed broadcast
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/AccTypeManager( 1330): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  907):   Scheme: "smsto"
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/ActivityManager(  907): Start proc com.htc.cs.dm for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver: pid=4118 uid=10098 gids={50098, 3003, 5012}
D/Process (  907): killProcessQuiet, pid=3612
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3612:com.google.android.apps.plus/u0a160 (adj 15): empty #17
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,E/ExternalAccountType( 1330): Unsupported attribute readOnly
I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "sms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "smsto"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/InputMethodManagerService(  907): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,W/InputMethodManagerService(  907): Got RemoteException sending setActive(false) notification to pid 3531 uid 10356
,I/InputMethodManagerService(  907): Enable input method client, pid=1273
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
,I/PackageManager(  907):   Scheme: "mms"
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,I/PackageManager(  907):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  907):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  907):   Scheme: "mmsto"
,I/DeviceManagement( 4118): DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.1.784944;234300090] pid=4118 dbg=false s=true
,I/DeviceManagement( 4118): PackageUpdateReceiver: vvv Package added: [com.example.hello]
I/PackageManager(  907): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1244 :
,D/PhoneApp( 1244): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ActivityManager(  907): Recipient 3612
,D/ConnectivityService(  907): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,V/Tethering(  907): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/Icing   ( 2222): Indexing done 3E78574859FB8ED28F43D3ECB139F4117F00AB29
,D/PMS     (  907): releaseWL(424fe9d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
,I/ActivityManager(  907): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4131 uid=10100 gids={50100, 3003, 5012, 1028, 1015}
,D/Process (  907): killProcessQuiet, pid=3840
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Killing 3840:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  907): getActiveNetworkInfo called by  (1437/10028)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.google.android.music (3935/10154)
D/ConnectivityService(  907): getNetworkInfo networkType=1 called by com.htc.launcher (1273/10075)
D/ConnectivityService(  907): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1902/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1845/10178)
I/NetworkMonitor( 3935): type=WIFI subType= reason=null isConnected=false
D/Tethering(  907): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  907): bSetPropertyMultiRAB:false
D/Tethering(  907): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  907): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  907): ipv4Default null
I/Tethering(  907): No IPv4 upstream interface, giving up.
,D/Tethering(  907): TetherMasterSM: InitialState processMessage what=3
,I/ConnectivityHelper( 1273): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,I/ActivityManager(  907): Recipient 3840
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiService(  907): Client connection lost with reason: 4
,W/Netd    (  365): No subsystem found in netlink event
V/Tethering(  907): remove iface:wlan0
D/Tethering(  907): interfaceRemoved wlan0
,E/Tethering(  907): attempting to remove unknown iface (wlan0), ignoring
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
,W/PackageManager(  907): Unable to load service info ResolveInfo{4251b490 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
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
,D/Tethering(  907): interfaceLinkStateChanged p2p0, false
,D/Tethering(  907): interfaceStatusChanged p2p0, false
,D/Tethering(  907): [isWifi] getHotspotEnabled: false
,D/RemoteDisplayProvider(  907): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  907): start
I/AlarmManager(  907): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/CaptivePortalTracker(  907): DelayedCaptiveCheckState
D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  907): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  907): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  907): NoActiveNetworkState
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
D/ConnectivityService(  907): getActiveNetworkInfo called by  (907/1000)
,D/ConnectivityService(  907): getNetworkInfo networkType=1 called by  (907/1000)
,D/PMS     (  907): acquireWL(42666e98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 907 1000 null
,W/AtomicFile(  907): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
D/GpsLocationProvider(  907): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  907): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  907): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  907): ignore wifi update if we are not in OPENING or CLOSING
W/AppWidgetServiceImpl(  907): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  907): releaseWL(42666e98): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null
,E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4131): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4131): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteDatabase( 4131): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteDatabase( 4131): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteDatabase( 4131): 	at aJm.a(Scopes.java:65)
E/SQLiteDatabase( 4131): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteDatabase( 4131): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteDatabase( 4131): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteDatabase( 4131): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteDatabase( 4131): 	at aGw.a(GellyInjector.java:117)
E/SQLiteDatabase( 4131): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteDatabase( 4131): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteDatabase( 4131): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4131): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4131): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4131): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4131): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4131): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4131): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 4131): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4131): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4131): 	at Bw.a(ClientFlagsModule.java:32)
E/SQLiteOpenHelper( 4131): 	at Bw.a(ClientFlagsModule.java:23)
E/SQLiteOpenHelper( 4131): 	at aGL.a(GellyInjectorStoreBase.java:136)
E/SQLiteOpenHelper( 4131): 	at aJm.a(Scopes.java:65)
E/SQLiteOpenHelper( 4131): 	at aGR.a(RuntimeProvider.java:116)
E/SQLiteOpenHelper( 4131): 	at fx.a(GellyInjectorStore.java:95)
E/SQLiteOpenHelper( 4131): 	at fx.a(GellyInjectorStore.java:456)
E/SQLiteOpenHelper( 4131): 	at aGN.a(GellyMembersInjector.java:30)
E/SQLiteOpenHelper( 4131): 	at aGw.a(GellyInjector.java:117)
E/SQLiteOpenHelper( 4131): 	at Tk.a(ScopedInjector.java:216)
E/SQLiteOpenHelper( 4131): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:215)
E/SQLiteOpenHelper( 4131): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4131): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4131): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4131): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4131): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4131): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4131): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 4131): Opened ClientFlag.db in read-only mode
,E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4131): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4131): 	at aho.run(AbstractDatabaseInstance.java:455)
,W/dalvikvm( 4131): threadid=11: thread exiting with uncaught exception (group=0x416ade30)
,E/AndroidRuntime( 4131): FATAL EXCEPTION: Open database in background
E/AndroidRuntime( 4131): Process: com.google.android.apps.docs, PID: 4131
E/AndroidRuntime( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime( 4131): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime( 4131): 	at aho.run(AbstractDatabaseInstance.java:455)
,E/ActivityManager(  907): App crashed! Process: com.google.android.apps.docs
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager(  907): Start proc com.htc.backup for broadcast com.htc.backup/.task.restore.PackageInstallReceiver: pid=4149 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/ClientFlag.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 4131): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteDatabase( 4131): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteDatabase( 4131): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteDatabase( 4131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4131): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4131): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteDatabase( 4131): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 4131): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 4131): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteDatabase( 4131): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteDatabase( 4131): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 4131): Couldn't open ClientFlag.db for writing (will try read-only):
E/SQLiteOpenHelper( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 4131): 	at android.database.sqli,te.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 4131): 	at Bk.b(ClientFlagDatabaseImpl.java:149)
E/SQLiteOpenHelper( 4131): 	at com.google.android.apps.docs.DocsApplication.onCreate(DocsApplication.java:222)
E/SQLiteOpenHelper( 4131): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4924)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread.access$1500(ActivityThread.java:153)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1412)
E/SQLiteOpenHelper( 4131): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 4131): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteOpenHelper( 4131): 	at android.app.ActivityThread.main(ActivityThread.java:5633)
E/SQLiteOpenHelper( 4131): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 4131): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 4131): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
E/SQLiteOpenHelper( 4131): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
E/SQLiteOpenHelper( 4131): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 4131): Opened ClientFlag.db in read-only mode
,W/GAV2    ( 4131): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Netd    (  365): No subsystem found in netlink event
,E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4131): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/SQLiteDatabase( 4131): 	at aid.a(DatabaseModelLoader.java:340)
E/SQLiteDatabase( 4131): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/SQLiteDatabase( 4131): 	at fv.run(DocsApplication.java:288)
V/Tethering(  907): remove iface:p2p0
D/Tethering(  907): interfaceRemoved p2p0
,E/Tethering(  907): attempting to remove unknown iface (p2p0), ignoring
E/AbstractDatabaseInstance( 4131): Failed to delete from CachedSearch111
E/AbstractDatabaseInstance( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AbstractDatabaseInstance( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AbstractDatabaseInstance( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AbstractDatabaseInstance( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AbstractDatabaseInstance( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AbstractDatabaseInstance( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AbstractDatabaseInstance( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AbstractDatabaseInstance( 4131): 	at azJ.a(Suppliers.java:125)
E/AbstractDatabaseInstance( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/AbstractDatabaseInstance( 4131): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AbstractDatabaseInstance( 4131): 	at aid.a(DatabaseModelLoader.java:340)
E/AbstractDatabaseInstance( 4131): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AbstractDatabaseInstance( 4131): 	at fv.run(DocsApplication.java:288)
,W/dalvikvm( 4131): threadid=12: thread exiting with uncaught exception (group=0x416ade30)
D/NetlinkEvent(  365): Unexpected netlink message. type=0x11
E/AndroidRuntime_2_crash( 4131): crash in the same process: Background initialization thread
E/AndroidRuntime_2_crash( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime_2_crash( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime_2_crash( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime_2_crash( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime_2_crash( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/AndroidRuntime_2_crash( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/AndroidRuntime_2_crash( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/AndroidRuntime_2_crash( 4131): 	at azJ.a(Suppliers.java:125)
E/AndroidRuntime_2_crash( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/AndroidRuntime_2_crash( 4131): 	at ahl.b(AbstractDatabaseInstance.java:310)
E/AndroidRuntime_2_crash( 4131): 	at aid.a(DatabaseModelLoader.java:340)
E/AndroidRuntime_2_crash( 4131): 	at aiN.a(ObsoleteDataCleanerImpl.java:100)
E/AndroidRuntime_2_crash( 4131): 	at fv.run(DocsApplication.java:288)
,E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4131): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4131): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4131): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4131): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4131): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4131): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4131): 	at java.lang.Thread.run(Thread.java:864)
,W/BroadcastQueue(  907): Skipping deliver [background] BroadcastRecord{425e0bc0 u-1 android.net.conn.CONNECTIVITY_CHANGE callingPid=-1 callingUid=-1} to ReceiverList{425e0a00 4131 com.google.android.apps.docs/10100/u0 remote:4256cd88}: process crashing
,E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4131): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4131): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4131): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4131): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4131): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4131): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4131): 	at java.lang.Thread.run(Thread.java:864)
,I/htcbackup-core( 4149): ModelRegistry: Loading model meta data from resources...
,W/ContextImpl( 4149): Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
W/ContextImpl( 4149): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 com.htc.cs.dm.config.ConfigManager.getConfig:322 
,I/DeviceManagement( 4118): ConfigManagerBoundService: *** getConfig: appID=com.htc.backup options=Bundle[mParcelledData.dataSize=44]
,I/DeviceManagement( 4118): ConfigManagerBoundService: Caller: uid=android.uid.system:1000 (1000) packages=[com.android.location.fused, com.htc.home.personalize, com.htc.backup, com.qualcomm.timeservice, com.android.settings, com.htc.feedback, com.htc.usage, com.htc.htcpowermanager, com.htc.backupreset, com.htc.drive.activator, com.htc.smartdim, com.htc.guide, com.android.keychain, com.android.inputdevices, com.htc.checkinprovider, com.htc.autobot.cargps.provider, com.htc.mirrorlinkserver, com.android.providers.settings, com.htc.android.htcloglevel, com.android.CSDFunctionG, android, com.qualcomm.privinit, com.htc.cirmodule, com.htc.android.htcsetupwizard, com.htc.lockscreen]
,I/DeviceManagement( 4118): WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[mParcelledData.dataSize=44], appID=com.htc.backup}]]
,D/Process (  907): killProcessQuiet, pid=3794
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  907): Start proc com.htc.providers.settings:remote for broadcast com.htc.providers.settings/.HtcCupdReceiver: pid=4172 uid=10017 gids={50017, 3003, 5012, 1028, 1015, 1023, 5011}
I/ActivityManager(  907): Killing 3794:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3794
,I/DeviceManagement( 4118): WorkflowService: Starting workflow service
I/DeviceManagement( 4118): WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b15548] args=[Bundle[mParcelledData.dataSize=144]]
,I/DeviceManagement( 4118): ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=144]
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/DeviceManagement( 4118): ModelRegistry: Loading model meta data from resources...
,I/DeviceManagement( 4118): ConfigManagerController: *** getConfig: appID=com.htc.backup includeMeta=true
,I/DeviceManagement( 4118): SessionStateController: Checking invariants...
,E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4131): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4131): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4131): 	at java.lang.Thread.run(Thread.java:864)
D/HtcCupdReceiver(Provider)( 4172):  @@@@@ receive action=android.intent.action.PACKAGE_ADDED
,E/FixedSizeWorkerPool( 4131): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4131): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4131): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4131): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  907): Delay finish: com.htc.providers.settings/.HtcCupdReceiver
,I/HtcModeClient( 1516): handler message = 4011
,E/HtcModeClient( 1516): Check connection and retry 7 times.
,E/SQLiteDatabase( 4131): Failed to open database '/data/data/com.google.android.apps.docs/databases/DocList.db'.
E/SQLiteDatabase( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/SQLiteDatabase( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/SQLiteDatabase( 4131): 	at azJ.a(Suppliers.java:125)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/SQLiteDatabase( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/SQLiteDatabase( 4131): 	at agA.a(DocListDatabase.java:337)
E/SQLiteDatabase( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/SQLiteDatabase( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/SQLiteDatabase( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/SQLiteDatabase( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4131): 	at java.lang.Thread.run(Thread.java:864)
,E/FixedSizeWorkerPool( 4131): A worker has thrown an exception.
E/FixedSizeWorkerPool( 4131): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/FixedSizeWorkerPool( 4131): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/FixedSizeWorkerPool( 4131): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/FixedSizeWorkerPool( 4131): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/FixedSizeWorkerPool( 4131): 	at ahs.getWritableDatabase(DatabaseHelper.java:236)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:440)
E/FixedSizeWorkerPool( 4131): 	at ahn.a(AbstractDatabaseInstance.java:437)
E/FixedSizeWorkerPool( 4131): 	at azJ.a(Suppliers.java:125)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:93)
E/FixedSizeWorkerPool( 4131): 	at ahl.b(AbstractDatabaseInstance.java:396)
E/FixedSizeWorkerPool( 4131): 	at agA.a(DocListDatabase.java:337)
E/FixedSizeWorkerPool( 4131): 	at aid.a(DatabaseModelLoader.java:2026)
E/FixedSizeWorkerPool( 4131): 	at Rs.c(SyncTaskQueueImpl.java:315)
E/FixedSizeWorkerPool( 4131): 	at Rs.a(SyncTaskQueueImpl.java:195)
E/FixedSizeWorkerPool( 4131): 	at PQ.run(ContentSyncWorker.java:48)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/FixedSizeWorkerPool( 4131): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/FixedSizeWorkerPool( 4131): 	at java.lang.Thread.run(Thread.java:864)
I/ActivityManager(  907): Resuming delayed broadcast
,I/ActivityManager(  907): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4188 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
,W/GAV2    ( 4131): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,D/Process (  907): killProcessQuiet, pid=3895
,D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3895:com.htc.htcpowermanager:remote/1000 (adj 15): empty #17
,I/ActivityManager(  907): Recipient 3895
,I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 4118): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4118): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4118): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4118): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4118): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4118): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4118): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4118): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel,.java:176)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
E/SQLiteDatabase( 4118): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4118): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4118): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4118): 	at java.lang.Thread.run(Thread.java:864)
I/DeviceManagement( 4118): ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/DeviceManagement( 4118): DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/DeviceManagement( 4118): SessionStateController: Checking invariants...
,E/SQLiteDatabase( 4118): Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
E/SQLiteDatabase( 4118): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4118): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4118): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4118): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/SQLiteDatabase( 4118): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 4118): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 4118): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/SQLiteDatabase( 4118): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfig(ConfigManagerController.java:126)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow.doServiceMethod(ConfigManagerServiceGetConfigWorkflow.java:44)
E/SQLiteDatabase( 4118): 	at com.htc.cs.dm.config.service.ConfigManagerServiceWorkflow.invokeServiceMethod(ConfigManagerServiceWorkflow.java:50)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.service.ServiceWorkflow.call(ServiceWorkflow.java:44)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/SQLiteDatabase( 4118): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/SQLiteDatabase( 4118): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentServic,e.java:65)
E/SQLiteDatabase( 4118): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 4118): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 4118): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DeviceManagement( 4118): ServiceWorkflow: Uncaught throwable
E/DeviceManagement( 4118): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/DeviceManagement( 4118): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/DeviceManagement( 4118): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/DeviceManagement( 4118): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
E/DeviceManagement( 4118): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/DeviceManagement( 4118): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/DeviceManagement( 4118): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:128)
E/DeviceManagement( 4118): 	at android.content.ContentProviderClient.query(ContentProviderClient.java:114)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.controller.ConfigManagerController.getConfig(ConfigManagerController.java:126)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow.doServiceMethod(ConfigManagerServiceGetConfigWorkflow.java:44)
E/DeviceManagement( 4118): 	at com.htc.cs.dm.config.service.ConfigManagerServiceWorkflow.invokeServiceMethod(ConfigManagerServiceWorkflow.java:50)
E/DeviceManagement( 4118): 	at com.htc.cs.util.service.ServiceWorkflow.call(ServiceWorkflow.java:44)
E/DeviceManagement( 4118): 	at com.htc.cs.util.w,orkflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
E/DeviceManagement( 4118): 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
E/DeviceManagement( 4118): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/DeviceManagement( 4118): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DeviceManagement( 4118): 	at android.os.Looper.loop(Looper.java:157)
E/DeviceManagement( 4118): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DeviceManagement( 4118): ServiceWorkflow: android.database.sqlite.SQLiteException: message=[not an error (code 0): Could not open the database in read/write mode.]
I/DeviceManagement( 4118): WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@41b15548]
I/DeviceManagement( 4118): WorkflowService: Stopping workflow service
D/Process (  907): killProcessQuiet, pid=3662
D/Process (  907): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  907): Killing 3662:com.htc.widget.hmsproc2/u0a42 (adj 15): empty #17
I/htcbackup-core( 4149): ModelAsyncTask: Caught exception running async model handler: java.lang.IllegalStateException: android.database.sqlite.SQLiteException: message=[not an error (code 0): Could not open the database in read/write mode.]
I/ActivityManager(  907): Recipient 3662
I/DisplayManagerService(  907): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/SQLiteDatabase( 4188): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4188): 	at dek.getWritableDatabase(PG:48)
E/SQLiteDatabase( 4188): 	at del.a(PG:264)
E/SQLiteDatabase( 4188): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4188): 	at java.lang.Thread.run(Thread.java:864)
D/PMS     (  907): acquireWL(42665e90): PARTIAL_WAKE_LOCK  AsyncService 0x1 4188 10160 null
,E/SQLiteDatabase( 4188): Failed to open database '/data/data/com.google.android.apps.plus/databases/trash.db'.
E/SQLiteDatabase( 4188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 4188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 4188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4188): 	at dek.getWritableDatabase(PG:51)
E/SQLiteDatabase( 4188): 	at del.a(PG:264)
E/SQLiteDatabase( 4188): 	at eeq.run(PG:187)
E/SQLiteDatabase( 4188): 	at java.lang.Thread.run(Thread.java:864)
,E/EsApplication( 4188): Failed app initialization
E/EsApplication( 4188): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/EsApplication( 4188): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/EsApplication( 4188): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/EsApplication( 4188): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/EsApplication( 4188): 	at dek.getWritableDatabase(PG:51)
E/EsApplication( 4188): 	at del.a(PG:264)
E/EsApplication( 4188): 	at eeq.run(PG:187)
E/EsApplication( 4188): 	at java.lang.Thread.run(Thread.java:864)
,D/PMS     (  907): releaseWL(42665e90): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,D/DFPI.PIReciver( 3726): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3726): onHandleIntent
,I/DFPI.ApkInstallService( 3726): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3726): check CID = HTC__032
,I/DFPI.ApkInstallService( 3726): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  907): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  907): Resuming delayed broadcast
I/SoundPicker( 3976): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
W/ContextImpl( 3976): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3976): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3976): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3976): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3976): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3976): MODE_GSM access default DB
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
,I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3976): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3976): MODE_GSM access default DB
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/ActivityManager(  907): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3976): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
W/Atfwd_Sendcmd(  415): AtCmdFwd service not published, waiting... retryCnt : 4
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3976): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9,
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3976): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac,
I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3976): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  907): Resuming delayed broadcast
,E/SharedPreferencesImpl( 3935): Couldn't rename file /data/data/com.google.android.music/shared_prefs/store.preferences.xml to backup file /data/data/com.google.android.music/shared_prefs/store.preferences.xml.bak
I/ActivityManager(  907): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,E/SQLiteDatabase( 3935): Failed to open database '/data/data/com.google.android.music/databases/music.db'.
E/SQLiteDatabase( 3935): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 3935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3935): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/SQLiteDatabase( 3935): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/SQLiteDatabase( 3935): 	at android.os.Handler.handleCallback(Handler.java:733)
E/SQLiteDatabase( 3935): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 3935): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/SQLiteDatabase( 3935): 	at android.os.Looper.loop(Looper.java:157)
E/SQLiteDatabase( 3935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3935): threadid=17: thread exiting with uncaught exception (group=0x416ade30)
E/ActivityManager(  907): App crashed! Process: com.google.android.music:main
E/AndroidRuntime( 3935): FATAL EXCEPTION: MediaStoreImportService
E/AndroidRuntime( 3935): Process: com.google.android.music:main, PID: 3935
E/AndroidRuntime( 3935): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/AndroidRuntime( 3935): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/AndroidRuntime( 3935): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 3935): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.Store.getDatabase(Store.java:239)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.BaseStore.beginRead(BaseStore.java:28)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.Store.createDatabase(Store.java:222)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.MediaStoreImporter.doImport(MediaStoreImporter.java:220)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.Store.importMediaStore(Store.java:9229)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.MediaStoreImportService.importMediaStore(MediaStoreImportService.java:75)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.MediaStoreImportService.access$100(MediaStoreImportService.java:34)
E/AndroidRuntime( 3935): 	at com.google.android.music.store.MediaStoreImportService$4.run(MediaStoreImportService.java:140)
E/AndroidRuntime( 3935): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 3935): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 3935): 	at com.google.android.music.utils.LoggableHandler.dispatchMessage(LoggableHandler.java:82)
E/AndroidRuntime( 3935): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 3935): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  907): Can't write: system_app_crash
E/DropBoxManagerService(  907): java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  907): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  907): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  907): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  907): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  907): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  907): 	at libcore.io.Posix.open(Native Method)
E/D,ropBoxManagerService(  907): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  907): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  907): 	... 5 more
D/Settings:HtcWirelessFeatureFlags( 3864): id/is att sku: 99/false
,W/SystemReader( 3864): Cannot find devicepolicy_lower_fp_quality, use default value instead
,W/SystemReader( 3864): Cannot find support_harman, use default value instead
,W/SystemReader( 3864): Cannot find effect_manager_id, use default value instead
,E/Settings:HtcWrapHeaderInfo( 3864): no such activity!
,W/Settings:com.android.settings.framework.activity.HtcIEntryProvider.Stub( 3864): The wrap header doesn't exist in header list.
,E/Settings:HtcWrapHeaderInfo( 3864): updateDevelopment, bPrefShow = true
,E/Settings:HtcUmcWidgetEnabler( 3864): isSupportMusicChannel(): false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportRecentAppsButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportRecentAppsButton]hasRecentAppsKey:false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportRecentAppsButton]support         :false
,V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportHomeButton]hasNavigationBar:true
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportHomeButton]hasMenuKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportHomeButton]hasRecentAppKey :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportHomeButton]hasBackKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportHomeButton]hasHomeKey      :false
V/Settings:com.android.settings.framework.flag.feature.HtcDisplayFeatureFlags( 3864): [supportHomeButton]support         :false

```
