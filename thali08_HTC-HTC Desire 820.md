#### Test 55634150e857e16_thali08_HTC-HTC Desire 820 Logs


```
--------- beginning of /dev/log/system
D/WIFI_ICON( 1117): WifiActivity: 1
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
--------- beginning of /dev/log/main
W/dalvikvm( 3486): method Lcom/facebook/feed/reflex/ZoomableImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/reflex/view/AbstractListView;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/reflex/view/GalleryViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/reflex/view/HorizontalScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/reflex/view/ImageViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/reflex/view/ScrollViewAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/reflex/view/ViewPagerAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/reflex/view/FrameLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
W/dalvikvm( 3486): method Lcom/facebook/messaging/reflex/SwipableOverlayLayoutAutoReflex;.invalidate incorrectly overrides package-private method with same name in Landroid/view/View;
E/FbInjectorInitializer( 3486): Multi-binding Key[type=com.facebook.common.init.INeedInit, annotation=[none]] wasn't declared.
W/fb4a(:<default>):StaticBindingVerifier( 3486): Verify
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3486/10026)
,W/fb4a(:<default>):BaseAnalyticsConfig( 3486): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
W/fb4a(:<default>):BaseAnalyticsConfig( 3486): willEventBeLogged() called before shared prefs were initialized! Defaulting to true.
I/dalvikvm-heap( 3486): Grow heap (frag case) to 9.511MB for 73240-byte allocation
D/Process (  906): killProcessQuiet, pid=3282
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/ActivityManager(  906): Killing 3282:com.htc.sense.browser/u0a12 (adj 15): empty #17
D/PMS     (  906): acquireWL(42668fa8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
D/PMS     (  906): acquireWL(423c2d28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10028 null
D/PMS     (  906): releaseWL(42668fa8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
D/GCM     ( 1367): GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): releaseWL(423c2d28): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/ConnectivityService(  906): reportInetCondition for net 1, percentage: 100 by  (1367/10028)
D/ConnectivityService(  906): handleInetConditionChange: net=1, condition=100,mActiveDefaultNetwork=1
D/ConnectivityService(  906): handleInetConditionChange: starting a change hold
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/AutoSetting( 1487): receiver - intent: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  906): Recipient 3282
I/ActivityManager(  906): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=3516 uid=10078 gids={50078, 3003, 5012}
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1487/10053)
D/AutoSetting( 1487): service - onStartCommand() action: com.htc.app.autosetting.requestlocationupdate
D/AutoSetting( 1487): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1487): service - requestNLP() NetworkLocationProvider not enabled
D/AutoSetting( 1487): service - onStartCommand() REMOVE current location bundle
D/AutoSetting( 1487): service - handleMessage() setting current location null
D/AutoSetting( 1487): Util - check NLP state, Allowned:false, Enabled:false
D/AutoSetting( 1487): service - onStartCommand() check timezone in 30000
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.sense.hsp (1487/10053)
W/fb4a(:<default>):UserScope( 3486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 3486): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):UserScope( 3486): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3486): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
D/MobileConnectivityChangeReceiver( 3516): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 3516): onReceive CONNECTIVITY_CHANGE networkType=1
E/PhoneMonitor( 3516): onOtaspChanged old =0, new =3
V/PhoneMonitor( 3516): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3516/10078)
D/Process (  906): killProcessQuiet, pid=2804
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=3534 uid=10096 gids={50096, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 2804:com.android.defcontainer/u0a19 (adj 15): empty #17
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3516/10078)
I/ActivityManager(  906): Recipient 2804
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/PMS     (  906): acquireWL(42899680): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.setupwizard (3516/10078)
D/PMS     (  906): acquireWL(426c5d90): PARTIAL_WAKE_LOCK  Checkin Service 0x1 2228 10028 null
D/PMS     (  906): releaseWL(42899680): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
I/CheckinService( 2228): Preparing to send checkin request
I/EventLogService( 2228): Accumulating logs since 1452528250959
E/dalvikvm( 3486): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketImpl', referenced from method com.facebook.ssl.openssl.check.CheckOpenSSLImplHasRequiredMethods.<clinit>
W/dalvikvm( 3486): VFY: unable to resolve const-class 12124 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketImpl;) in Lcom/facebook/ssl/openssl/check/CheckOpenSSLImplHasRequiredMethods;
E/dalvikvm( 3486): Could not find class 'org.apache.harmony.xnet.provider.jsse.OpenSSLSocketFactoryImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.<clinit>
W/dalvikvm( 3486): VFY: unable to resolve const-class 12123 (Lorg/apache/harmony/xnet/provider/jsse/OpenSSLSocketFactoryImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3486): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLParametersGetter.a
W/dalvikvm( 3486): VFY: unable to resolve check-cast 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLParametersGetter;
E/dalvikvm( 3486): Could not find class 'org.apache.harmony.xnet.provider.jsse.SSLParametersImpl', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.<clinit>
W/dalvikvm( 3486): VFY: unable to resolve const-class 12126 (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3486): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
E/dalvikvm( 3486): Could not find class 'org.apache.harmony.xnet.provider.jsse.ClientSessionContext', referenced from method com.facebook.ssl.openssl.reflect.SSLSessionTimeoutSetter.a
W/dalvikvm( 3486): VFY: unable to resolve check-cast 12122 (Lorg/apache/harmony/xnet/provider/jsse/ClientSessionContext;) in Lcom/facebook/ssl/openssl/reflect/SSLSessionTimeoutSetter;
W/dalvikvm( 3486): VFY: unable to find class referenced in signature (Lorg/apache/harmony/xnet/provider/jsse/SSLParametersImpl;)
W/dalvikvm( 3486): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3486): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
E/cutils-trace( 3509): Error opening trace file: No such file or directory (2)
I/ActivityManager(  906): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=3556 uid=10151 gids={50151, 3003, 5012, 1028, 1015}
I/dalvikvm-heap( 3486): Grow heap (frag case) to 9.964MB for 84664-byte allocation
E/dalvikvm( 3486): Could not find class 'com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper', referenced from method com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketFactoryHelper.a
W/dalvikvm( 3486): VFY: unable to resolve new-instance 9111 (Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;) in Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketFactoryHelper;
W/dalvikvm( 3486): Unable to resolve superclass of Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper; (12125)
W/dalvikvm( 3486): Link of class 'Lcom/facebook/ssl/openssl/TicketEnabledOpenSSLSocketImplWrapper;' failed
I/dalvikvm-heap( 3486): Grow heap (frag case) to 10.019MB for 39954-byte allocation
W/EventLogAggregator( 2228): Unknown tag: install_package_attempt
W/EventLogAggregator( 2228): Unknown tag: snet
W/EventLogAggregator( 2228): Unknown tag: snet_gcore
I/dalvikvm-heap( 3486): Grow heap (frag case) to 10.095MB for 79892-byte allocation
I/GoogleHttpClient( 2228): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 2228): Using GMS GoogleHttpClient
D/CustomizationManager( 3509): ====startRecUseTime====
D/htc.customization.log.level( 3509):  is 
W/CustomizationLogLevel( 3509): Level value is invalid, use default level 2
D/WifiService(  906): New client listening to asynchronous messages
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3556): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3556): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2228/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2228/10028)
W/GAV2    ( 3556): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/dalvikvm-heap( 3486): Grow heap (frag case) to 10.282MB for 75760-byte allocation
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/ContextImpl( 3556): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/cache
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3486/10026)
W/ContextImpl( 3556): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.apps.magazines/files
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42479b48 u0 ReceiverList{423be820 3486 com.facebook.katana/10026/u0 remote:4213f388}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42479b48 u0 ReceiverList{423be820 3486 com.facebook.katana/10026/u0 remote:4213f388}}
W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{42467380 u0 ReceiverList{423b5848 3486 com.facebook.katana/10026/u0 remote:41fa3268}}
D/ConnectivityService(  906): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
D/ConnectivityService(  906): sendGeneralBroadcast, restrictEnable=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3486/10026)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3486/10026)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.facebook.katana (3486/10026)
D/CustomizationManager( 3509):  Read ACC file spent 0.076 (s)
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__001
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__102
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__032
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__016
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__002
D/CIDMapFileReader( 3509): Parsing tag item name = HTC__031
V/CustomizationCIDLoader( 3509): full path : /system/customize/CID/HTC__032.xml
I/CustomizationCIDLoader( 3509): Parsing tag category name = system
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
I/CustomizationCIDLoader( 3509): Parsing tag category name = application
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
I/CustomizationCIDLoader( 3509): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 3509): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 3509): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 3509): Parsing tag category name = ACC
I/CustomizationCIDLoader( 3509): Parsing tag category name = Settings
D/CustomizationManager( 3509):  Read CID file spent 0.128 (s)
D/CustomizationManager( 3509):  All configurations done spent 0.128 (s)
W/HtcNativeFlag( 3509): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 3509): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 3509): Fail to get flag string for type 'language', use default value
W/HtcNativeFlag( 3509): Fail to get flag for type 'language', use default value: -1
D/PMS     (  906): acquireWL(42890530): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1396 10028 null
D/PMS     (  906): releaseWL(42890530): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3556/10151)
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/GCoreFlp( 1396): Unknown pending intent to remove.
W/GLSUser ( 1367): GoogleAccountDataService.getToken()
D/PMS     (  906): acquireWL(42420dd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1396 10028 null
W/CpuWake (  906): >>nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): <<nativeAcquireCpuPerfWakeLock()
W/CpuWake (  906): >>acquire mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<acquire mCpuPerf_cpu_count wakelock
D/PMS     (  906): releaseWL(42420dd0): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
W/CpuWake (  906): >>acquire mCpuPerf_Freq wakelock
W/CpuWake (  906): <<acquire mCpuPerf_Freq wakelock
I/ActivityManager(  906): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3509
D/PMS     (  906): acquireHCC(421602f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 906 1000 null
D/PMS     (  906): acquireHCC(41fcf530): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 906 1000 null
W/asset   (  906): Copying FileAsset 0x6381efe0 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
V/WebViewChromiumFactoryProvider( 3556): Binding Chromium to main looper Looper (main, tid 1) {41b62ce8}
I/Intent  (  906): @test_code: getHtcIntentFlag: 0 obj: 1111980472
I/LibraryLoader( 3556): Expected native library version number "",actual native library version number ""
I/chromium( 3556): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3556): Initializing chromium process, renderers=0
D/PMS     (  906): acquireWL(42196e60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 906 1000 null
I/FeedHostManager( 1269): [onPause]
I/FeedProviderManager( 1269): onPause
I/FeedHostManager( 1269): [onLeaveFeedMode] instance: com.htc.launcher.feeds.FeedHostManager@41c32168
I/SocialFeedProvider( 1269): +onPause
I/SocialFeedProvider( 1269): -onPause
D/PMS     (  906): acquireWL(42343eb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): acquireWL(42240038): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(42343eb0): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
E/AudioManagerAndroid( 3556): BLUETOOTH permission is missing!
I/GoogleHttpClient( 1367): Falling back to old SSLCertificateSocketFactory
I/GoogleHttpClient( 1367): Using GMS GoogleHttpClient
I/ActivityManager(  906): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3587 uid=10356 gids={50356, 3003, 5012, 3001, 3002}
W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
I/Adreno-EGL( 3556): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3556): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3556): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3556): Local Branch: 
I/Adreno-EGL( 3556): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3556): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3556):                  aa63bbd948f41d15fc72f585e
W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
W/asset   ( 3587): Copying FileAsset 0x5c7ec428 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
I/TrimMemoryManager( 1269): [trimMemory] 20
I/NSApplication( 3556): Starting up...
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3556/10151)
V/WebViewChromiumFactoryProvider( 3587): Binding Chromium to main looper Looper (main, tid 1) {41b64138}
I/LibraryLoader( 3587): Expected native library version number "",actual native library version number ""
I/chromium( 3587): [INFO:library_loader_hooks.cc(116)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 3587): Initializing chromium process, renderers=0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.magazines (3556/10151)
I/NotificationStore( 1367): System rebooted after Notification storage file was last written
I/NotificationStore( 1367): Deleting the file
D/PMS     (  906): acquireWL(426d4080): PARTIAL_WAKE_LOCK  AudioMix 0x1 371 1013 null
D/PMS     (  906): releaseWL(426d4080): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
I/ActivityManager(  906): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=3614 uid=10160 gids={50160, 3003, 5012, 3002, 1028, 1015}
D/Process (  906): killProcessQuiet, pid=3323
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@423ed1e0:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
I/ActivityManager(  906): Killing 3323:com.google.android.partnersetup/u0a31 (adj 15): empty #17
D/BluetoothAdapter( 3587): 1102551856: getState(). Returning 12
I/ActivityManager(  906): Recipient 3323
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/Adreno-EGL( 3587): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3587): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3587): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3587): Local Branch: 
I/Adreno-EGL( 3587): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3587): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3587):                  aa63bbd948f41d15fc72f585e
W/CheckinRequestBuilder( 2228): awaiting user notification for token
D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
I/RemoteViews( 1117): com.google.android.gms (false,0)
D/OnDemandProgressBar( 1117): release indeterminate drawable android.widget.OnDemandProgressBar{41bc1790 G.ED.... ......I. 0,0-0,0 #102000d android:id/progress}
W/chromium( 3587): [WARNING:proxy_service.cc(890)] PAC support disabled because there is no system implementation
I/RemoteViews.Performance( 1117): com.google.android.gms 2 8 7 12
W/dalvikvm( 3587): VFY: unable to resolve virtual method 170: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
W/dalvikvm( 3587): VFY: unable to resolve virtual method 165: Landroid/webkit/CookieManager;.flush ()V
W/dalvikvm( 3587): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3587): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 3587): VFY: unable to resolve virtual method 223: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
W/dalvikvm( 3587): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
W/dalvikvm( 3587): VFY: unable to resolve virtual method 181: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
W/dalvikvm( 3587): VFY: unable to resolve virtual method 186: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/SystemWebViewEngine( 3587): CordovaWebView is running on device made by: HTC
I/ActivityManager(  906): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=3641 uid=10028 gids={50028, 3007, 2001, 3003, 5012, 1007, 3006, 1028, 1015, 3002, 3001}
,I/MultiDex( 3641): install
,I/MultiDex( 3641): MultiDexExtractor.load(/system/priv-app/GmsCore.apk, false)
,I/MultiDex( 3641): loading existing secondary dex files
,I/MultiDex( 3641): load found 1 secondary dex files
,I/MultiDex( 3641): install done
,I/ProviderInstaller( 3641): Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,W/AwContents( 3587): nativeOnDraw failed; clearing to background color.
,I/InputMethodManagerService(  906): Disable input method client, pid=1269
,W/ResourceType( 3587): No package identifier when getting name for resource number 0x00000064
,I/InputMethodManager( 3587): [startInputInner] EditorInfo { packageName=com.example.hello, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@41baafa0, mServedView=org.apache.cordova.engine.SystemWebView{41b70e50 VFEDH.C. .F....I. 0,0-720,1134 #64}
W/XT9_C   ( 1207): [T9_ContextBreak] ET9AWSelLstBuild() failed!  (wCoreStatus=4)
W/AwContents( 3587): nativeOnDraw failed; clearing to background color.
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#0
I/XT9_C   ( 1207): [T9_ReleaseBuffer] Reset LDB#1
D/XT9_C   ( 1207): [T9_ReleaseBuffer] Done. Current LdbNum=0x100, First LdbNum=0x100, Second LdbNum=0x0
,I/InputMethodManagerService(  906): Enable input method client, pid=3587
I/ActivityManager(  906): Displayed com.example.hello/.MainActivity: +330ms
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,D/PMS     (  906): acquireWL(420ea1e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 3614 10160 null
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): releaseWL(42196e60): PARTIAL_WAKE_LOCK  ActivityManager-Launch 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3614/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3614/10160)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3614/10160)
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.apps.plus (3614/10160)
D/PMS     (  906): acquireWL(4259c048): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 3614 10160 null
D/PMS     (  906): releaseWL(420ea1e0): PARTIAL_WAKE_LOCK  fingerprint_scanner_static 0x1 null
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/AlertReceiver( 3351): beginStartingService
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/PMS     (  906): acquireWL(4263fb18): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 3351 10013 null
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/PMS     (  906): acquireWL(42896da8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 2228 10028 null
D/PMS     (  906): releaseWL(42896da8): PARTIAL_WAKE_LOCK  Checkin Handoff 0x1 null
,D/AlertService( 3351): start to updateAlertNotification!
,D/AlertService( 3351): No fired or scheduled alerts
,D/HtcAlertUtils( 3351): -- cancelReminderNotification --
,D/HtcAlertUtils( 3351): broadcastExistReminder!
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,W/AlertReceiver( 3351): stopSelfResult true
D/PMS     (  906): releaseWL(4263fb18): PARTIAL_WAKE_LOCK  StartingAlertService_5 0x1 null
,D/PMS     (  906): acquireWL(428bcca0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 3425 10070 null
,D/PMS     (  906): releaseWL(4259c048): PARTIAL_WAKE_LOCK  fingerprint_scanner_local 0x1 null
,D/PMS     (  906): acquireWL(425fa678): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 3425 10070 null
,W/WeatherUtility( 3396): can't get weather sync account
D/PMS     (  906): releaseWL(428bcca0): PARTIAL_WAKE_LOCK  NotificationThreadCreator_3 0x1 null
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC >>
,D/ContactMessageStore( 1241): MSG_NOTIFY_CS_TO_SYNC <<
I/ActivityManager(  906): Start proc com.htc.android.worldclock for broadcast com.htc.android.worldclock/.alarmclock.AlarmReceiver: pid=3686 uid=10090 gids={50090, 3003, 5012, 1028}
,D/TodoTaskshortcut( 3425): update TASK shortcut>
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,W/WeatherRequest( 1117): request cur loc, but there is no sys cur
,I/TodoTaskNotifyService( 3425): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/WeatherRequest( 3396): request cur loc, but there is no sys cur
,W/Settings( 3396): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 2, mLinkspeedSum: 48
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/TodoTaskNotifyService( 3425): Send com.htc.intent.lockscreen.ClearTASKReminder to DotMatrix when clearNotification
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,W/NotifyReceiver( 3425): stopSelfResult true
,D/PMS     (  906): releaseWL(425fa678): PARTIAL_WAKE_LOCK  TaskNotification_3 0x1 null
I/dalvikvm-heap( 3614): Grow heap (frag case) to 15.207MB for 1821008-byte allocation
I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 1 13 17
,I/WorldClock.Global( 3686): isHtcDevice = true
,I/WorldClock.Global( 3686): isHtcDevice = true
W/ContextImpl( 3164): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.framework.app.HtcDndCommandReceiver.onReceive:34 android.app.ActivityThread.handleReceiver:2687 
,I/ActivityManager(  906): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=3702 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,I/WorldClock.AlarmUtils( 3686): Calculate next alarm: id = -1 time = 9223372036854775807(Sun Aug 17 09:12:55 CET 292278994)
,I/chromium( 3587): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,E/AndroidProtocolHandler( 3587): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/WorldClock.AlarmUtils( 3686): Cancel any alarm from alarm manager
,I/WorldClock.AlarmUtils( 3686): broadcast "android.intent.action.ALARM_CHANGED" intent for alarm icon
,I/IntentController( 1117): receive(android.intent.action.ALARM_CHANGED,1,false)
,D/Process (  906): killProcessQuiet, pid=3335
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3335:com.htc.contacts/u0a41 (adj 15): empty #17
,D/JsMessageQueue( 3587): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  906): Recipient 3335
,D/TimeService( 3702): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1452528609942
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Process (  906): killProcessQuiet, pid=3369
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
,I/AdsMeasurementBroadcastReceiver( 2228): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2228): Unauthorized to start the main service
I/ActivityManager(  906): Killing 3369:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3369
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BroadcastQueue(  906): Schedule to resend BroadcastRecord{426935e0 u0 com.htc.mms.DB_CHANGE callingPid=1241 callingUid=1001} for ResolveInfo{42443308 com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent m=0x108000} of com.htc.widget.hmsproc1
,I/ActivityManager(  906): Start proc com.htc.widget.hmsproc1 for broadcast com.htc.htccontactwidgets/.ContactDataChangedReceiverForHtcSmsIntent: pid=3720 uid=10038 gids={50038}
,D/jxcore_app_log( 3587): JniHelper::setJavaVM(0x4163b048), pthread_self() = 1658378896
,D/JX-Cordova( 3587): jxcore cordova android initializing
,W/jxcore-log( 3587): Initializing JXcore engine
,W/jxcore-log( 3587): JXcore engine is ready
,W/jxcore-log( 3587): Starting JXcore engine
,D/SMSBackup( 3382): Got a database change event
,I/ActivityManager(  906): Start proc com.htc.sense.news for broadcast com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver: pid=3734 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,D/Process (  906): killProcessQuiet, pid=3411
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Killing 3411:com.htc.demoflopackageinstaller/u0a20 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3411
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ImageRamCache( 3734): create image Cache, size: 31457280.
I/ImageRamCache( 3734): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3734): create image Cache, size: 12582912.
,I/FeedSettings( 3734): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3734): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3734): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3734): changeLocale(): en_GB
,I/Prism.AllAppsOptionsMa_( 3734): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3734): loadGridSize() with Alternative
,D/CustomHighlightReceiver( 3734): [custom highlight] onReceive
,I/ActivityManager(  906): Delay finish: com.htc.launcher/com.htc.plugin.news.remote.CustomHighlightReceiver
D/CustomHighlightService( 3734): [custom highlight] onHandleIntent
D/NewsDB  ( 3734): set custom highlight []
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3486): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,D/CustomHighlightService( 3734): [custom highlight] set tags 
,D/Process (  906): killProcessQuiet, pid=2763
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 2763:com.htc.sense.mms/u0a64 (adj 15): empty #17
E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
W/ContextImpl( 3486): Failed to ensure directory: /storage/ext_sd/Android/data/com.facebook.katana/cache
,W/jxcore-log( 3587): Platform android
W/jxcore-log( 3587): 
,W/jxcore-log( 3587): Process ARCH arm
W/jxcore-log( 3587): 
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/jxcore-log( 3587): JXcore Cordova bridge is ready!
I/jxcore-log( 3587): 
,W/jxcore-log( 3587): JXcore engine is started
,I/ActivityManager(  906): Recipient 2763
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/BroadcastQueue(  906): Schedule to resend BroadcastRecord{42662d88 u0 com.htc.launcher.action.ACTION_ITEM_ADDED callingPid=1269 callingUid=10075} for ResolveInfo{42651a50 com.htc.sense.mms/.ui.MessagingShortcutReceiver m=0x108000} of com.htc.sense.mms
,E/jxcore-log( 3587): >> HTC-HTC Desire 820
E/jxcore-log( 3587): 
,I/jxcore-log( 3587): Total memory 1964650496
I/jxcore-log( 3587): 
I/jxcore-log( 3587): Free memory 614223872
I/jxcore-log( 3587): 
,I/jxcore-log( 3587): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3587): 
,I/jxcore-log( 3587): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3587): 
,I/ActivityManager(  906): Start proc com.htc.sense.mms for broadcast com.htc.sense.mms/.ui.MessagingShortcutReceiver: pid=3750 uid=10064 gids={50064, 3003, 5012, 1028, 1015, 1023}
W/Settings( 3641): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/jxcore-log( 3587): userPath [ 'www', 'www' ]
I/jxcore-log( 3587): 
I/jxcore-log( 3587): Size 720 1184
I/jxcore-log( 3587): 
I/jxcore-log( 3587): Screen Brightness 10
I/jxcore-log( 3587): 
E/jxcore-log( 3587): Dummy Error Log.
E/jxcore-log( 3587): 
,D/MessageFrequencyProvider( 3750): onCreate
V/GetPrviateResource( 3750): GetPrviateResource
V/GetPrviateResource( 3750): GetPrviateResource
,D/MessageCustFlag( 3750): sense_version=6.0
,D/BTAccessoryUtil( 3750): createReceiver
,D/BTAccessoryUtil( 3750): registerReceiver return intent = null
D/MessageCustFlag( 3750): sku_id=99
,W/SystemReader( 3750): Cannot find message_ambs_application_id, use default value instead
,D/Messaging( 3750): supportCMAS(SIE)/init? false/true
D/MmsConfig( 3750): networkCode: 
,D/MessageCustFlag( 3750): sku_id=99
D/MmsConfig( 3750): SIE smsPri: null
,D/MmsConfig( 3750): networkCode: 
D/HtcTelephonyCapability( 3750): traditional single GSM/CDMA/World-phone
,D/HtcTelephonyCapability( 3750): The project is not dual project , phone_feature_type_stand_by = 0
,D/HtcBuildUtils( 3750): getRATByHtcTelephonyCapability:1
,W/SystemReader( 3750): Cannot find qct_8960_interface, use default value instead
,D/MmsConfig( 3750): packageName: com.htc.vvm.att does not exist
,D/MessagingShortcutReceiver( 3750): keep hiding shortcut bubble
D/MessagingShortcut( 3750): updateMsgShortcut, msg count> -1
D/SettingsManager( 3750): init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@41b74be8
D/MessagingShortcut( 3750): After query: 0
D/MessagingShortcut( 3750): mPresentUnreadCount: -1
D/MessagingShortcut( 3750): setMsgShortcutDrawable> 0
D/MessagingShortcut( 3750): Send UNREAD_MESSAGE_COUNT broadcast: count=0, bubble:2
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1564): [EventService] reorderNotification, total:1
D/DotMatrix( 1564): [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
,D/DotMatrix( 1564): [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
,D/TodoTaskshortcut( 3425): update TASK shortcut>
,D/HtcBroadcastReceiver( 1241): onReceive: com.htc.launcher.action.ACTION_ITEM_ADDED
,D/Process (  906): killProcessQuiet, pid=3440
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3440:com.htc.stock/u0a81 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/ActivityManager(  906): Start proc com.htc.mobiledata:remote for broadcast com.htc.mobiledata/.receivers.ReceiveIntentFromNoPermission: pid=3768 uid=10091 gids={50091, 3003, 5012}
,V/AlarmManager(  906): sending alarm PendingIntent{42482568: PendingIntentRecord{42456468 com.htc.mobiledata startService}}, i=com.htc.mobiledata.intent.REQUEST, t=2, cnt=1, w=52749, Int=0
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/ActivityManager(  906): Start proc com.htc.mobiledata for content provider com.htc.mobiledata/.MobileDataProvider: pid=3786 uid=10091 gids={50091, 3003, 5012}
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.init.InitializeGmsReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
,D/GCM     ( 1367): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/MtpReceiver( 2731): [MTP][MtpReceiver][onReceive]+
D/MtpReceiver( 2731): [MTP][MtpReceiver][onReceive]1-
,D/MtpReceiver( 2731): [MTP][handleMessage][startService]
,D/MtpReceiver( 2731): [MTP][handleMessage][UsbManager.USB_CONNECTED][insert]+
,D/MtpReceiver( 2731): [MTP][handleMessage]-
,I/ActivityManager(  906): Start proc com.nero.android.htc.sync for broadcast com.nero.android.htc.sync/.CDMountReceiver: pid=3799 uid=10008 gids={50008, 1023, 3003, 5012, 1007, 1028, 1015, 1018}
D/MtpService( 2731): [MTP] startForeground
I/RemoteViews( 1117): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1117): com.android.providers.media 2 1 10
I/RemoteViews( 1117): com.android.providers.media (false,0)
I/RemoteViews.Performance( 1117): com.android.providers.media 0 2 15
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false
,D/MtpService( 2731): updating state; isCurrentUser=true, mMtpLocked=false
,D/MtpDatabase( 2731): TotalSize=1918604,MediaCacheLimit=6000
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3440
,D/PMS     (  906): acquireWL(421bba50): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 3614 10160 null
D/MtpService( 2731): [isMtpConnected] connected: true
I/Adreno-EGL( 3641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3641): Local Branch: 
I/Adreno-EGL( 3641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3641):                  aa63bbd948f41d15fc72f585e
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,D/MdScBoot( 3768): [570.1.] 30@-170940 -> 40@-171010
,D/MdScBoot( 3768): [570.2.] 40@-171010
,D/Process (  906): killProcessQuiet, pid=3452
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3452:com.htc.stock:remote/u0a81 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3452
,D/SyncApplication( 3799): Loading default preferences
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 5 times.
,D/Process (  906): killProcessQuiet, pid=3464
,W/Resources( 3799): Converting to string: TypedValue{t=0x12/d=0x0 a=4 r=0x7f0c001a}
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
D/PMS     (  906): releaseWL(421bba50): PARTIAL_WAKE_LOCK  wake:com.google.android.apps.plus/.service.CameraMonitor$MediaTrackerIntentService 0x1 null
I/ActivityManager(  906): Killing 3464:com.google.android.music:main/u0a154 (adj 15): empty #17
,D/WifiService(  906): New client listening to asynchronous messages
,D/SyncApplication( 3799): Overriding preferences with custom values
,I/Adreno-EGL( 3641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3641): Local Branch: 
I/Adreno-EGL( 3641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3641):                  aa63bbd948f41d15fc72f585e
,D/SyncApplication( 3799): Updating preferences succeeded
,E/SyncApplication( 3799): Application created.
D/VolumeInfo( 3799): check the sys-path: /sys/devices/msm_sdcc.2/mmc_host
,D/VolumeInfo( 3799): The sys-path does not exist: /sys/devices/msm_sdcc.2/mmc_host
V/VolumeInfo( 3799): Found 0 mount point(s)
,V/VolumeInfo( 3799): New VolumeInfo with mount point /storage/emulated/0 and sys path null created
,D/VolumeInfo( 3799): read cached Id for /storage/emulated/0/ from the preference: /storage/emulated/0/
I/ActivityManager(  906): Recipient 3464
D/MediaRouterService(  906): Client com.google.android.music (pid 3464): Died!
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/VolumeInfo( 3799): Read the volume-id from the sd card: {61911E1D-261C-4FB6-8207-55BA8B8D5E9C}
W/VolumeInfo( 3799): Can not create volume ID for unmounted volume null
,D/Process (  906): killProcessQuiet, pid=3486
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/CalendarDefines( 3799): getNewCalendarAuthority()...
I/ActivityManager(  906): Killing 3486:com.facebook.katana/u0a26 (adj 15): empty #17
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.Calendar2SyncService, state=1, flag=1, pid=3799, uid=10008, userID:0
W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.Calendar2SyncService does not exist in com.nero.android.htc.sync
I/PackageManager(  906):  setEnabledSetting(), pkgName=com.nero.android.htc.sync, clsName=com.nero.android.neroconnect.accounts.CalendarSyncService, state=2, flag=1, pid=3799, uid=10008, userID:0
,W/PackageManager(  906): Failed setComponentEnabledSetting: component class com.nero.android.neroconnect.accounts.CalendarSyncService does not exist in com.nero.android.htc.sync
D/SyncApplication( 3799): enableAppOperation()+
I/Adreno-EGL( 3641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: MINGHSUC_AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028__release_ENGG ()
I/Adreno-EGL( 3641): OpenGL ES Shader Compiler Version: E031.24.02.07
I/Adreno-EGL( 3641): Build Date: 08/28/14 Thu
I/Adreno-EGL( 3641): Local Branch: 
I/Adreno-EGL( 3641): Remote Branch: refs/tags/AU_LINUX_ANDROID_LNX.LA.3.7.3_RB1.04.04.04.118.028
I/Adreno-EGL( 3641): Local Patches: e2511633f49b49e9395061637feeaa32115fc075 adreno: a4xx: Insert wait for idle to address back to back blits
I/Adreno-EGL( 3641):                  aa63bbd948f41d15fc72f585e
D/SyncApplication( 3799): enableAppOperation()-
,D/HTCUtilities( 3799): isNeorSinged() + 
,D/HTCUtilities( 3799): sb=Certificate subject: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate issuer: OID.1.2.840.113549.1.9.1=#160F616E64726F6964406874632E636F6D, CN=Android, OU=Android, O=Android, L=Taoyuan, ST=Taoyuan, C=TW<br>Certificate serial number: 14307539907619100345<br>
,D/HTCUtilities( 3799): isNeorSinged() return false
D/CDMountReceiver( 3799): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/CDMountReceiver( 3799): USB connected to PC
,D/FOTAReceiver( 3799): onReceive() enter 
,D/FOTAReceiver( 3799): receive action: com.htc.intent.action.USB_CONNECT2PC  connected :true
,D/Process (  906): killProcessQuiet, pid=3516
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.trimApplications:17252 
I/ActivityManager(  906): Start proc com.android.settings for broadcast com.android.settings/.MLReceiver: pid=3823 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
I/ActivityManager(  906): Killing 3516:com.google.android.setupwizard/u0a78 (adj 15): empty #17
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3516
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3486
,D/WifiService(  906): Client connection lost with reason: 4
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (3641/10028)
,D/PMS     (  906): acquireWL(425f6760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1396 10028 null
,D/PMS     (  906): acquireWL(424e4a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 1396 10028 null
,D/PMS     (  906): releaseWL(425f6760): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/PMS     (  906): releaseWL(424e4a30): PARTIAL_WAKE_LOCK  GCoreFlp 0x1 null
,D/HtcFingerPrintQuickLaunchProvider( 3823): -onCreate()
,I/jxcore-log( 3587): getBuffer is called!!!!
I/jxcore-log( 3587): 
,V/Settings:HtcSettingsApplication( 3823): [3823/3823] onCreate()
,D/TetherSettings( 3823): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3823): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3823): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3823): Cust_ConnectToPC   : spcsc>false
D/        ( 3823): Cust_ConnectToPC   : IPT>true
,D/        ( 3823): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinTask( 2228): Sending checkin request (8895 bytes)
D/TetherSettings( 3823): CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
D/        ( 3823): Cust_ConnectToPC   : Internet_Sharing>true
D/        ( 3823): Cust_ConnectToPC   : Modem_Link>false
D/        ( 3823): Cust_ConnectToPC   : spcsc>false
D/        ( 3823): Cust_ConnectToPC   : IPT>true
D/        ( 3823): Cust_ConnectToPC   : Singel_USB>false
,W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SmartNS_Utility( 3823): hasRemovableStorageSlot: true
,D/SmartNS_Utility( 3823): [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
D/SmartNS_NSReceiver( 3823): onReceive : com.htc.intent.action.USB_CONNECT2PC hasTethered:false isNSOpening:false
,D/SmartNS_Utility( 3823): usb_cable_connect = 1
,D/SmartNS_Utility( 3823): usb_denied = 0
I/SmartNS_NSReceiver( 3823): locked:falsesecurity:falseisLocked:false
,D/SmartNS_NSReceiver( 3823): USB = true hasTethered = false isNSOpening: false
,I/PSReceiver( 3823): onReceive:com.htc.intent.action.USB_CONNECT2PC
,I/SmartNS_PSService( 3823): onReceive:com.htc.intent.action.USB_CONNECT2PC
,W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.PSReceiver.onReceive:36 android.app.ActivityThread.handleReceiver:2687 
W/Settings( 3823): Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/SmartNS_PSService( 3823):  defaultType:0
I/SmartNS_PSService( 3823): fail notificaiton:false
,D/SmartNS_Utility( 3823): usb_cable_connect = 1
D/SmartNS_Utility( 3823): usb_denied = 0
,I/SmartNS_PSService( 3823): usb notificaiton:true
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,V/Tethering(  906): bSetPropertyMultiRAB:false
W/ActivityThread( 2228): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3823/1000)
,D/SmartNS_Utility( 3823): usb_cable_connect = 1
D/SmartNS_Utility( 3823): usb_denied = 0
I/SmartNS_PSService( 3823): usb notificaiton:true
,I/RemoteViews( 1117): com.android.settings (true,33751552)
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
,I/RemoteViews.Performance( 1117): com.android.settings 0 1 10
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
D/ConnectivityService(  906): getActiveNetworkInfo called by com.android.settings (3823/1000)
I/ActivityManager(  906): Resuming delayed broadcast
,D/SmartNS_Utility( 3823): usb_cable_connect = 1
,D/SmartNS_Utility( 3823): usb_denied = 0
,D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.android.settings, id: 2130837961, tag: null, isClearable: false
,I/RemoteViews( 1117): com.android.settings (true,33751552)
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,I/ActivityManager(  906): Delay finish: com.htc.widget.weatherclock/.WeatherClock4x1
I/SmartNS_PSService( 3823): KeyGuard locked:falseKeyGuard is secured:false
D/SmartNS_PSService( 3823): USB Plugged, Set USBPlugged=  truePSenabled:false
,I/RemoteViews.Performance( 1117): com.android.settings 1 2 10
,W/WeatherUtility( 3396): can't get weather sync account
I/ActivityManager(  906): Resuming delayed broadcast
,D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2228): [NET] getaddrinfo-,err=8
D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.googlequicksearchbox.SearchWidgetProvider})
D/libc    ( 2228): [NET] getaddrinfo-, 1
D/libc    ( 2228): [NET] getaddrinfo_proxy+
,I/RemoteViews( 1269): com.google.android.googlequicksearchbox (false,0)
D/libc    (  364): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 1024
I/RemoteViews.Performance( 1269): com.google.android.googlequicksearchbox 1 0 5
D/libc    (  364): [NET]_dns_getaddrinfo: iface= v4v6=10 method=1
D/libc    (  364): [NET] +++++ res_nsend xid =17ce +++++
D/libc    (  364): [NET] res_nLookupCache: rstatp->iface =
,D/libc    (  364): [NET] NOT IN CACHE
,I/ActivityManager(  906): Delay finish: pl.k2.droidoaudioteka/.ui.widgets.BigWidgetProvider
W/WeatherRequest( 3396): request cur loc, but there is no sys cur
,W/Settings( 3396): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{pl.k2.droidoaudioteka/pl.k2.droidoaudioteka.ui.widgets.BigWidgetProvider})
,I/RemoteViews( 1269): pl.k2.droidoaudioteka (false,0)
,I/RemoteViews.Performance( 1269): pl.k2.droidoaudioteka 0 1 8
,I/ActivityManager(  906): Resuming delayed broadcast
D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
D/SMSBackup( 3382): Got a database change event
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 2 4 17
I/ActivityManager(  906): Delay finish: com.google.android.gms/.playlog.service.MonitorAlarmReceiver
,D/LocationManagerService(  906): getAllProviders()=[passive, gps, network]
,D/libc    (  364): [NET][SMD][v0204] Extended TTL = 43200, original TTL = 285
D/libc    (  364): [NET]res_nsend:resplen=84
,D/libc    (  364): [NET]res_queryN: exit 3, ancount=2
D/libc    (  364): [NET]_dns_getaddrinfo-, (NS_SUCCESS)
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
,D/libc    ( 2228): [NET] getaddrinfo_proxy-, success
V/AlarmManager(  906): sending alarm PendingIntent{428b5150: PendingIntentRecord{4296c620 com.google.android.gms broadcastIntent}}, i=null, t=1, cnt=1, w=1452528611054, Int=0
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.common.download.DownloadAlarmReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/PMS     (  906): acquireWL(426241d0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 2228 10028 null
,D/libc    ( 2228): [NET] getaddrinfo+,hn 26(0x616e64726f6964),sn(),family 0,flags 4
,D/libc    ( 2228): [NET] getaddrinfo-,err=8
,D/PMS     (  906): releaseWL(426241d0): PARTIAL_WAKE_LOCK  GmsDownloadService 0x1 null
,I/ActivityManager(  906): Resuming delayed broadcast
,W/CpuWake (  906): >>nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): <<nativeReleaseCpuPerfWakeLock()
W/CpuWake (  906): >>release mCpuPerf_cpu_count wakelock
W/CpuWake (  906): <<release mCpuPerf_cpu_count wakelock
,W/CpuWake (  906): >>release mCpuPerf_Freq wakelock
W/CpuWake (  906): <<release mCpuPerf_Freq wakelock
D/PMS     (  906): releaseHCC(421602f8): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x400 null
,D/PMS     (  906): releaseHCC(41fcf530): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x100 null
,I/ActivityManager(  906): Delay finish: com.google.android.gms/.security.snet.SnetBootCompletedReceiver
,V/AlarmManager(  906): sending alarm PendingIntent{426bb498: PendingIntentRecord{42885e98 com.google.android.gms startService}}, i=null, t=0, cnt=17104, w=84918423, Int=84918423
,I/ActivityManager(  906): Resuming delayed broadcast
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,I/AdsMeasurementBroadcastReceiver( 2228): Reporting settings might have changed, alerting AdsMeasurementService
,D/AdsMeasurementBroadcastReceiver( 2228): Unauthorized to start the main service
,D/SnetService( 2228): snet destroyed
,I/ActivityManager(  906): Start proc com.htc.htcpowermanager:remote for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver: pid=3854 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
,W/ContextImpl( 3854): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2687 
,D/PowerUsageService( 3854): call getInstance()
I/ActivityManager(  906): Delay finish: com.htc.htcpowermanager/.battery.PowerUsageReceiver
,D/PowerUsageList:PowerUsageHelper( 3854): MY_DEBUG = false
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/PMS     (  906): acquireWL(42865318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  906): releaseWL(42865318): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,W/BatSI   (  906): Couldn't get kernel wake lock stats
,D/WIFI_ICON( 1117): WifiActivity: 3
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_inandout_4 (gone) T]
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2228/10028)
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=10 [19][2][0]
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2228/10028)
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,W/CheckinRequestBuilder( 2228): awaiting user notification for token
,I/RemoteViews( 1117): com.google.android.gms (false,0)
,I/RemoteViews.Performance( 1117): com.google.android.gms 1 4 12
D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/CheckinTask( 2228): Sending checkin request (2419 bytes)
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Killing 3534:com.android.chrome/u0a96 (adj 15): empty #17
,D/Process (  906): killProcessQuiet, pid=3534
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
D/PMS     (  906): acquireWL(425f6110): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 3854 1000 null
,W/WeatherUtility( 1117): can't get weather sync account
,D/WeatherUtility( 1487): Weather sync is On
I/ActivityManager(  906): Recipient 3534
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WSP     ( 1487): [Receiver] auto sync agent, auto sync is enabled, reset schedule
,I/ActivityManager(  906): Start proc com.htc.mediamanager for broadcast com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver: pid=3871 uid=10032 gids={50032, 1028, 1015, 1023, 3003, 5012, 2001, 3002}
,W/WeatherUtility( 3396): can't get weather sync account
W/AppWidgetServiceImpl(  906): updateAppWidget failed! callbacks null
,W/WeatherRequest( 3396): request cur loc, but there is no sys cur
,W/Settings( 3396): Setting auto_time_zone has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/AppWidgetHostView( 1269): updateAppWidget mInfo = AppWidgetProviderInfo(provider=ComponentInfo{com.htc.widget.weatherclock/com.htc.widget.weatherclock.WeatherClock4x1})
,I/RemoteViews( 1269): com.htc.widget.weatherclock (true,33751552)
,I/RemoteViews.Performance( 1269): com.htc.widget.weatherclock 2 6 17
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,D/PMS     (  906): acquireWL(426ecde8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
,D/PMS     (  906): releaseWL(426ecde8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,D/ConnectivityService(  906): getNetworkInfo networkType=9 called by com.google.android.gms (2228/10028)
,D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.google.android.gms (2228/10028)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=20 [5][1][0]
,W/GLSUser ( 1367): GoogleAccountDataService.getToken()
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/GLSUser ( 1367): GLS error: BadAuthentication thalitester@gmail.com AndroidCheckInServer
,W/GLSActivity( 1367): [aus] Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/PMS     (  906): releaseWL(42240038): PARTIAL_WAKE_LOCK  AudioMix 0x1 null
,I/RemoteViews( 1117): com.google.android.gms (false,0)
W/CheckinRequestBuilder( 2228): awaiting user notification for token
D/DotMatrix( 1564): [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
,D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,I/RemoteViews.Performance( 1117): com.google.android.gms 4 2 12
,I/CheckinTask( 2228): Checkin success: https://android.clients.google.com/checkin (2 requests sent)
,W/GoogleHttpClient( 2228): Unable to close GMS GoogleHttpClient
D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.gms (2228/10028)
,D/PMS     (  906): releaseWL(426c5d90): PARTIAL_WAKE_LOCK  Checkin Service 0x1 null
,D/Process (  906): killProcessQuiet, pid=3351
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/Process (  906): killProcessQuiet, pid=3556
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3351:com.htc.calendar/u0a13 (adj 15): empty #17
I/ActivityManager(  906): Killing 3556:com.google.android.apps.magazines/u0a151 (adj 15): empty #18
E/ActivityThread( 2228): Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b6c290 that was originally bound here
E/ActivityThread( 2228): android.app.ServiceConnectionLeaked: Service com.google.android.gms.checkin.CheckinService has leaked ServiceConnection gbd@41b6c290 that was originally bound here
E/ActivityThread( 2228): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1078)
E/ActivityThread( 2228): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:972)
E/ActivityThread( 2228): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1823)
E/ActivityThread( 2228): 	at android.app.ContextImpl.bindService(ContextImpl.java:1806)
E/ActivityThread( 2228): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:524)
E/ActivityThread( 2228): 	at gbc.<init>(SourceFile:99)
E/ActivityThread( 2228): 	at gay.<init>(SourceFile:226)
E/ActivityThread( 2228): 	at java.lang.reflect.Constructor.constructNative(Native Method)
E/ActivityThread( 2228): 	at java.lang.reflect.Constructor.newInstance(Constructor.java:423)
E/ActivityThread( 2228): 	at xs.<init>(SourceFile:175)
E/ActivityThread( 2228): 	at bkt.a(SourceFile:226)
E/ActivityThread( 2228): 	at bks.a(SourceFile:298)
E/ActivityThread( 2228): 	at bks.doInBackground(SourceFile:288)
E/ActivityThread( 2228): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/ActivityThread( 2228): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/ActivityThread( 2228): 	at java.lang.Thread.run(Thread.java:864)
,I/ActivityManager(  906): Recipient 3351
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/Messaging( 3750): mNeedToUpdateDate2 start
,D/ReportIndicatorCache( 3750): startAsyncQueryReports ---
D/MmsAsyncWorkHandler( 3750): 
D/MmsAsyncWorkHandler( 3750): HM tk = 20001
,D/ReportIndicatorCache( 3750): MSG_QUERY_REPORTS >>
,I/Messaging( 3750): mccmnc> 
D/DraftCache( 3750): [DraftCache/1] DraftCache.constructor
,D/DraftCache( 3750): [DraftCache/1] refresh
,D/MmsConfig( 3750): networkCode: 
,D/Messaging( 3750): ViewCache CreatePreloadOnlyConversationList
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
,D/MessageCustFlag( 3750): sense_version=6.0
D/PhoneStorageUtil( 3750): HtcWrapEnvironment.getSupportedStorages() >1
,D/PhoneStorageUtil( 3750): HtcWrapEnvironment.hasRemovableStorageSlot()() >true
,D/PhoneStorageUtil( 3750): createReceiver
,D/Jerry   ( 3750): start to preload cursor >>>>>>>
D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/Messaging( 3750): mNeedToUpdateDate2: false
,D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/TelephUtils( 1241): UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 71
V/MmsProvider( 1241): Update uri=content://mms, match=0
,V/MmsProvider( 1241): selection=st=129 AND m_type!=134
,D/Messaging( 3750): Reset downloading state: 0
,V/MmsSystemEventReceiver( 3750): TransactionService is going to be woken up.
D/Messaging( 3750): ViewCache CreatePreload
,D/Messaging( 3750): ViewCache CreatePreloadOnlyMultipleOpsList
I/ActivityManager(  906): Delaying start of: ServiceRecord{428d1aa8 u0 com.htc.sense.mms/.transaction.TransactionService}
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): sku_id=99
,D/Cust_MMSMS( 3750): _has_set_default_values_2=true
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Recipient 3556
,D/MsgPreferenceUtils( 3750): def_index: 0
,D/MsgPreferenceUtils( 3750): globalIndex = 1
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
D/MsgPreferenceUtils( 3750): phone state: true
D/MsgPreferenceUtils( 3750): sd state: false
,D/MsgPreferenceUtils( 3750): vIndex = 0
,D/DraftCache( 3750): [DraftCache/376] rebuildCache
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/Jerry   ( 1241): URI_DRAFT
,D/DraftCache( 3750): hasDraft() = false mNeedNotifyChange = true
D/DraftCache( 3750): [DraftCache/376] rebuildCache time: 2
,D/MmsAsyncWorkHandler( 3750): 
D/MmsAsyncWorkHandler( 3750): HM tk = 20002
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
D/MmsSmsV2Provider( 1241):  phoneType = -1
,D/MmsSmsV2Provider( 1241): URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): sku_id=99
,D/Messaging( 3750): mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 63
,D/AccFlag ( 1241): sku_id=99
,V/TransactionService( 3750): 1-Creating TransactionService
V/TransactionService( 3750): onStartCommand: 1
,D/MmsSystemEventReceiver( 3750): unRegisterForConnectionStateChanges
V/TransactionService( 3750): 4-Handling incoming message: { when=0 what=2 arg1=1 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
,V/TransactionService( 3750): Loading previous transactions.
,D/TelephUtils( 1241): QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 32
,D/AccFlag ( 1241): device_type: 1,
,D/TransactionService( 3750): Force set service start id to 1
V/TransactionService( 3750): stopSelfIfIdle: unRegisterForConnectionStateChanges
,D/MmsSystemEventReceiver( 3750): unRegisterForConnectionStateChanges
,V/TransactionService( 3750): Destroying TransactionService
I/ActivityManager(  906): Resuming delayed broadcast
,D/TransactionService( 3750): stopSelfResult: true, mLastHandledServiceId: 1
,D/Process (  906): killProcessQuiet, pid=3686
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,V/TransactionService( 3750): 4-Handling incoming message: { when=-22ms what=100 target=com.htc.sense.mms.transaction.TransactionService$ServiceHandler }
I/ActivityManager(  906): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=3913 uid=10154 gids={50154, 3003, 5012, 1028, 1015}
I/ActivityManager(  906): Killing 3686:com.htc.android.worldclock/u0a90 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3686
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative RSSI = -57 abnormalRssiCnt = 0 newLinkSpeed = 24
,D/WifiStateMachine(  906): fetchRssiAndLinkSpeedNative mLinkspeedCount = 3, mLinkspeedSum: 72
,D/WifiNative-wlan0(  906): doBoolean: SignalStrength 97
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SignalStrength 97"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/wpa_supplicant( 1152): WiFioffload: SignalStrength: =97
,D/WifiNative-wlan0(  906):    returned true
,I/MusicStore( 3913): Database version: 95
,W/ContextImpl( 3913): Implicit intents with startService are not safe: Intent { act=com.google.android.music.NETWORK_MONITOR_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,W/ContextImpl( 3913): Implicit intents with startService are not safe: Intent { act=com.google.android.music.PREFERENCE_SERVICE } android.content.ContextWrapper.bindService:524 com.google.android.music.utils.SafeServiceConnection$ServiceConnectionImp.bindService:98 com.google.android.music.utils.SafeServiceConnection.bindService:259 
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3913): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
V/AlarmManager(  906): sending alarm PendingIntent{42125cf0: PendingIntentRecord{4268d5b0 com.htc.sense.hsp broadcastIntent}}, i=com.htc.sync.provider.weather.START_AUTOSYNC_SERVICE, t=1, cnt=1, w=1452528612802, Int=0
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3913): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/ContextImpl( 3913): Failed to ensure directory: /storage/ext_sd/Android/data/com.google.android.music/files
W/Vold    (  354): Returning OperationFailed - no handler for errno 30
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.android.music.MediaAppWidgetProvider, state=1, flag=1, pid=3913, uid=10154, userID:0
,D/Process (  906): killProcessQuiet, pid=3164
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3164:com.android.settings:remote/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3164
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,D/MediaRouterService(  906): Client com.google.android.music (pid 3913): Registered
,D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=3, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:,
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
,I/MediaRouter( 3913): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=10, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ActivityManager(  906): Start proc com.htc.demoflopackageinstaller for broadcast com.htc.demoflopackageinstaller/.PIReceiver: pid=3933 uid=10020 gids={50020, 3003, 5012, 1028, 1015}
,I/NetworkMonitor( 3913): type=WIFI subType= reason=null isConnected=true
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.google.android.music (3913/10154)
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/DFPI.ApkInstallService( 3933): onHandleIntent
,I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
,I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/ActivityManager(  906): Resuming delayed broadcast
,D/MediaRouter( 3913): getSelectedRoute
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/NetworkMonitor( 3913): type=WIFI subType= reason=null isConnected=true
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3913/10154)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.music, clsName=com.google.android.music.Settings.NetworkUsage, state=1, flag=1, pid=3913, uid=10154, userID:0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Resuming delayed broadcast
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Start proc com.htc.musicenhancer for broadcast com.htc.musicenhancer/.provider.MScannerReceiver: pid=3948 uid=10051 gids={50051, 1028, 1015, 3003, 5012}
,D/Process (  906): killProcessQuiet, pid=3702,
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
D/WifiNative-wlan0(  906): doString: SIGNAL_POLL
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 SIGNAL_POLL"
,I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/ActivityManager(  906): Killing 3702:com.qualcomm.timeservice/1000 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3702
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 17
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: survey data missing!
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 50
,I/wpa_supplicant( 1152): environment dirty rate=0 [0][0][0]
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Delay finish: com.htc.musicenhancer/.provider.MScannerReceiver
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3948/10051)
,D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.musicenhancer (3948/10051)
,W/BroadcastQueue(  906): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.htc.permission.APP_MEDIA due to registered receiver BroadcastFilter{428f2c08 u0 ReceiverList{428f2ba8 3948 com.htc.musicenhancer/10051/u0 remote:428f28c8}}
,E/cutils  (  354): Failed to mkdirat(/storage/ext_sd/Android): Read-only file system
,W/Vold    (  354): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 3948): Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.musicenhancer/cache
,D/HABCtrl (  906): ALG=2, lsvalue=10(0th)->40(1th), last_level=1, lValue=64->64
,D/PMS     (  906): releaseWL(425f6110): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,D/WIFI_ICON( 1117): WifiActivity: 1
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_in_4 (gone) T]
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Start proc com.htc.sdm for broadcast com.htc.sdm/.soundpicker.SoundPickerReceiver: pid=3967 uid=10080 gids={50080, 5001, 1028, 1015}
,D/Process (  906): killProcessQuiet, pid=3734
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3734:com.htc.sense.news/u0a75 (adj 15): empty #17
,I/ActivityManager(  906): Recipient 3734
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/SoundPicker( 3967): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3967): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3967): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3967): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3967): TurnFileToMediaUriService fromMediaScanned = true
,I/SoundPicker( 3967): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
,D/RingtoneManager( 3967): MODE_GSM access default DB
,I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
,D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
,D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3967): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3967): MODE_GSM access default DB
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac,
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
,I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/SocialFeedProvider( 1269): +disConnect socialManager
,I/SocialFeedProvider( 1269): disconnect socialManager
,I/SocialFeedProvider( 1269): -disConnect socialManager
,D/AutoSetting( 1487): service - mRequestRunnable: screen on delay 10s, request NLP now
D/AutoSetting( 1487): Util - check NLP state, Allowned:false, Enabled:false
,D/AutoSetting( 1487): service - requestNLP() NetworkLocationProvider not enabled
,D/WIFI_ICON( 1117): WifiActivity: 0
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null stat_sys_wifi_signal_connected_4 (gone) T]
,I/ActivityManager(  906): Resuming delayed broadcast
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
I/DFPI.ApkInstallService( 3933): onHandleIntent
I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
,I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.htc.album/com.htc.mediamanager.providers.media.MMPReceiver
,I/ActivityManager(  906): Waited long enough for: ServiceRecord{4281c1c8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,I/ActivityManager(  906): Resuming delayed broadcast
,I/SoundPicker( 3967): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3967): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,I/SoundPicker( 3967): SoundPickerReceiver [onReceive] startService
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3967): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3967): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3967): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3967): MODE_GSM access default DB
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3967): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3967): MODE_GSM access default DB
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/ActivityManager(  906): Start proc com.htc.sense.news for service com.htc.launcher/com.htc.plugin.news.SocialBiLogHelper: pid=3985 uid=10075 gids={50075, 3003, 5012, 1028, 1015, 5001, 1023}
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
V/AlarmManager(  906): sending alarm PendingIntent{41c44c60: PendingIntentRecord{425f8360 com.htc.sense.hsp startService}}, i=com.htc.sense.hsp.HANDLE_ULOG, t=1, cnt=1, w=1452528615107, Int=0
I/ActivityManager(  906): Resuming delayed broadcast
,I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,V/AlarmManager(  906): sending alarm PendingIntent{41d10a28: PendingIntentRecord{424ff608 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=57399, Int=0
,I/ActivityManager(  906): Resuming delayed broadcast
,D/PMS     (  906): acquireWL(4288f1e8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 1499 10014 null
,I/ActivityManager(  906): Delay finish: com.android.providers.calendar/.CalendarProviderBroadcastReceiver
,I/ImageRamCache( 3985): create image Cache, size: 31457280.
I/ImageRamCache( 3985): [resize] ImageRamCache resized to: 12Mb.
,I/ImageRamCache( 3985): create image Cache, size: 12582912.
,I/FeedSettings( 3985): [BlinkFeedCommitment]loadSettings, BLINKFEED commitment: true
I/FeedSettings( 3985): GroupBudget 0.500000 0.380000
,I/FeedSettings( 3985): GroupBudget 60 45 15
,I/Prism.ExternalStringMa_( 3985): changeLocale(): en_GB
D/PMS     (  906): releaseWL(4288f1e8): PARTIAL_WAKE_LOCK  ScheduleNextAlarmWakeLock_5 0x1 null
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Delay finish: com.htc.task/.TodoTaskReceiver
,I/Prism.AllAppsOptionsMa_( 3985): loadSortType() with Custom
,I/Prism.AllAppsOptionsMa_( 3985): loadGridSize() with Alternative
,I/SocialManager[SocialBiLogHelper]( 3985): action: com.htc.sense.hsp.HANDLE_ULOG
I/SocialManager[SocialBiLogHelper]( 3985): last commit ulog time 1452491635921
,I/SocialManager[SocialBiLogHelper]( 3985): skip commit this time
,I/SensorManager(  906): mEventCount = 450
I/ActivityManager(  906): Start proc com.htc.android.mail:sync for service com.htc.android.mail/.eassvc.EASAppSvc: pid=4004 uid=10063 gids={50063, 3003, 5012, 1023, 1028, 1015}
,I/ActivityManager(  906): Resuming delayed broadcast
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/DFPI.ApkInstallService( 3933): onHandleIntent
,I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
,I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
,I/EASAppSvc( 4004): [ NA ]- onCreate()
,D/Process (  906): killProcessQuiet, pid=3768
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 ,
I/ActivityManager(  906): Killing 3768:com.htc.mobiledata:remote/u0a91 (adj 15): empty #17
,I/EASAppSvc( 4004): [ NA ]> onUpgrade: version = 63
I/ActivityManager(  906): Recipient 3768
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,D/BluetoothManagerService(  906): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  906): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42481d00 mBinding = false
,W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: bluetooth_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
,W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
,W/Settings:Agent(  906): Process.myTid(): 1472
,W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): 
,W/System.err(  906): java.lang.Throwable: stack dump
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
,W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.persistBluetoothSetting(BluetoothManagerService.java:346)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.disable(BluetoothManagerService.java:583)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
,W/Settings:Agent(  906): << traceCallingStack(): 7(ms)
,D/BluetoothManagerService(  906): Message: MESSAGE_DISABLE
,D/BluetoothManagerService(  906): Sending off request.
,D/BluetoothAdapterState( 1593): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
D/BluetoothAdapterProperties( 1593): Setting state to 13
I/BluetoothAdapterState( 1593): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1593): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=12 new=13
D/BluetoothAdapterProperties( 1593): onBluetoothDisable()
I/BluetoothAdapterState( 1593): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1593): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterProperties( 1593): adapterPropertyChangedCallback with type:7 len:4
I/bt-btm  ( 1593): BTM_SetDiscoverability
I/bt-btm  ( 1593): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1593): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1593): br_edr_supported=0x0
I/bt-btm  ( 1593): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1593): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1593): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1593): btm_ble_update_adv_flag old=0x0
I/bt-btm  ( 1593): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1593): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1593): BTM_SetConnectability
I/bt-btm  ( 1593): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1593): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1593): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 12 -> 13
,I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
V/BluetoothPbapReceiver( 1593): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1593): ***********state = 13
D/WifiManager( 3587): setWifiEnabled: Base Package Name=com.example.hello, uid=10356
,D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothBroadcastReceiver]( 1805): Received state change = 13
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): deinitLeServices: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b8b210
,I/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1805): onDeInitialized
,D/WifiService(  906): setWifiEnabled: false pid=3587, uid=10356
,D/BluetoothMasReceiver( 1593): Bluetooth STATE CHANGED to 13
V/BluetoothSapReceiver( 1593): SapReceiver onReceive 
V/BluetoothSapReceiver( 1593): action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothSapReceiver( 1593):  Bluetooth Adapter state = 13
,V/BluetoothSapReceiver( 1593): Calling SAP service start service with action = android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothAdapterProperties( 1593): Scan Mode:20
V/BluetoothPbapService( 1593): Pbap Service closeService in
E/BTIF_CORE( 1593): NETI system_power_manager_wake : 259 param 1
,I/bt-btif ( 1593): HAL bt_hal_cbacks->wake_state_changed_cb
,D/BluetoothAdapterState( 1593): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,D/WifiStateMachine(  906): WiFiDisplay: getWifidisplayApEnabled=false
W/HtcDLNAServiceManager(  906): Settings:AgentMONITOR_LOG
W/HtcDLNAServiceManager(  906): Settings:Agentname: wifi_on
W/HtcDLNAServiceManager(  906): Settings:Agentvalue: 0
W/Settings:Agent(  906): >> traceCallingStack()
W/Settings:Agent(  906): Process.myPid(): 906
W/Settings:Agent(  906): Process.myTid(): 1343
W/Settings:Agent(  906): Process.myUid(): 1000
W/Settings:Agent(  906): 
W/Settings:Agent(  906): 
W/System.err(  906): java.lang.Throwable: stack dump
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at android.provider.Settings$HtcISettings$Agent.traceCallingStack(Settings$HtcISettings.java:56)
W/System.err(  906): 	at android.provider.Settings$HtcIGlobal$Agent.monitorKey(Settings$HtcIGlobal.java:64)
,W/System.err(  906): 	at android.provider.Settings$Global.putStringForUser(Settings.java:6183)
W/System.err(  906): 	at android.provider.Settings$Global.putString(Settings.java:6170)
W/System.err(  906): 	at android.provider.Settings$Global.putInt(Settings.java:6264)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.persistWifiState(WifiSettingsStore.java:156)
W/System.err(  906): 	at com.android.server.wifi.WifiSettingsStore.handleWifiToggled(WifiSettingsStore.java:114)
W/System.err(  906): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:1216)
W/System.err(  906): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:177)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
W/Settings:Agent(  906): 
E/WifiService(  906): Invoking mWifiStateMachine.setWifiEnabled
D/WifiService(  906): New client listening to asynchronous messages
I/WifiService(  906): isSprintWifiRestricted(): false
I/WifiService(  906): isMdmWifiRestricted(): false
D/WifiSettingsStore(  906): [SetWifiStatePersist] IsWifiStatePersist: true, persist : true
,D/PMS     (  906): acquireWL(4296cc48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3823 1000 null
W/Settings:Agent(  906): << traceCallingStack(): 1(ms)
I/bt-btif ( 1593): BTA_JvDeleteRecord
I/bt-btif ( 1593): BTA_JvRfcommStopServer
D/bt-btm  ( 1593): BTM_FreeSCN 
I/bt-btif ( 1593): BTA_JvDeleteRecord
I/bt-btif ( 1593): BTA_JvRfcommStopServer
D/bt-btm  ( 1593): BTM_FreeSCN 
I/bt-btif ( 1593): BTA_JvDeleteRecord
I/bt-btif ( 1593): BTA_JvRfcommStopServer
D/bt-btm  ( 1593): BTM_FreeSCN 
I/bt-btif ( 1593): BTA_JvDeleteRecord
I/bt-btif ( 1593): BTA_JvRfcommStopServer
D/bt-btm  ( 1593): BTM_FreeSCN 
I/bt-btif ( 1593): BTA_JvDeleteRecord
I/bt-btif ( 1593): BTA_JvRfcommStopServer
D/bt-btm  ( 1593): BTM_FreeSCN 
I/bt-btif ( 1593): BTA_JvDeleteRecord
I/bt-btif ( 1593): BTA_JvRfcommStopServer
D/bt-btm  ( 1593): BTM_FreeSCN 
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:15
E/BtOppRfcommListener( 1593): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
E/bt-btif ( 1593): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1593): BTM_SEC_CLR[13]: id 52
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:14
E/bt-btif ( 1593): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1593): BTM_SEC_CLR[14]: id 53
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:13
E/bt-btif ( 1593): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1593): BTM_SEC_CLR[15]: id 54
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:12
E/bt-btif ( 1593): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1593): BTM_SEC_CLR[16]: id 55
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:11
E/bt-btif ( 1593): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1593): BTM_SEC_CLR[17]: id 56
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:10
E/bt-btif ( 1593): bta_jv_rfcomm_stop_server
I/bt-btm  ( 1593): BTM_SEC_CLR[18]: id 57
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:9
I/bt-btm  ( 1593): Write Extended Inquiry Response to controller
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:8
I/bt-btm  ( 1593): Write Extended Inquiry Response to controller
I/bt-btm  ( 1593): Write Extended Inquiry Response to controller
I/bt-btm  ( 1593): Write Extended Inquiry Response to controller
I/bt-btm  ( 1593): Write Extended Inquiry Response to controller
I/bt-btm  ( 1593): BTM_SetDiscoverability
I/bt-btm  ( 1593): btm_ble_set_discoverability mode=0x0 combined_mode=0x0
D/bt-btm  ( 1593): btm_ble_set_discoverability (BREDR not sup)flag=0x4
D/bt-btm  ( 1593): br_edr_supported=0x0
I/bt-btm  ( 1593): mode == BTM_BLE_NON_DISCOVERABLE 
I/bt-btm  ( 1593): always disable adv in non-discoverable non-connectable mode if no scan rsp 
D/bt-btm  ( 1593): btm_ble_update_adv_flag new=0x4
D/bt-btm  ( 1593): btm_ble_update_adv_flag old=0x4
I/bt-btm  ( 1593): evt_type=0x3 p-cb->evt_type=0x3 
I/bt-btm  ( 1593): BTM_SetDiscoverability: mode 0 [NonDisc-0, Lim-1, Gen-2], window 0x0012, interval 0x0800
I/bt-btm  ( 1593): BTM_SetConnectability
I/bt-btm  ( 1593): btm_ble_set_connectability mode=0x0 combined_mode=0x0
I/bt-btm  ( 1593): always disable adv in non-discoverable non-connectable mode with no scan rsp
I/bt-btm  ( 1593): BTM_SetConnectability: mode 0 [NonConn-0, Conn-1], window 0x0012, interval 0x0800
I/bt-btm  ( 1593): BTM_IsInquiryActive
I/bt-btm  ( 1593): BTM_CancelRemoteDeviceName()
W/bt-btif ( 1593): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:7
D/bt-btm  ( 1593): BTM_FreeSCN 
I/bt-btm  ( 1593): BTM_SEC_CLR[3]: id 12
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:6
D/bt-btm  ( 1593): BTM_FreeSCN 
I/bt-btm  ( 1593): BTM_SEC_CLR[4]: id 29
,D/bt-avp  ( 1593): AVRC_Close handle:0
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:5
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:4
D/bt-sdp  ( 1593): SDP_DeleteRecord ok, num_records:3
W/bt-l2cap( 1593): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1593): L2CAP - PSM: 0x0017 not found for deregistration
I/bt-att  ( 1593): GATT_Deregister gatt_if=3
I/bt-att  ( 1593): GATT_Deregister gatt_if=4
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1805): cancelAllNotification
D/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1805): getNotificationManager
V/BluetoothSapService( 1593): Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothRemoteDevices( 1593): Wake lock Aquired
D/PMS     (  906): acquireWL(426c9748): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 1593 1002 null
W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PMS     (  906): releaseWL(4296cc48): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
W/System.err(  906): java.lang.Throwable: stack dump
D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42659140:true
W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
D/PMS     (  906): acquireWL(426bb1b8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3823 1000 null
I/LocationAgent( 3823): new LocationAgent instance!!
D/ORMLib  ( 3425): put()
D/HtcTagManager( 3823): HtcTagManager construction complete
I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_TURNING_OFF
D/PhoneStatusBar( 1117): removeIcon slot=bluetooth index=12 viewIndex=0
I/jxcore-log( 3587): ****TEST TOOK:  5128  ms ****
I/jxcore-log( 3587): 
D/WirelessDisplayService(  906): getMirrorDisplayStatus:falsecurState:1
I/jxcore-log( 3587): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3587): 
D/WifiPerfLock(  906): release()
D/WifiStateMachine(  906): PerfLock released for exiting ConnectedState
I/ActivityManager(  906): Start proc com.htc.widget.hmsproc3 for broadcast com.htc.htcbtwidget/.BTReceiver: pid=4026 uid=10037 gids={50037, 3002, 3001}
I/ActivityManager(  906): Resuming delayed broadcast
D/ConnectivityService(  906): requestNetworkTransitionWakelock for ConnectedState  by WifiStateMachine Timeout after 60000 msec
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1152): Power_Mode_Type mode = 0
I/wpa_supplicant( 1152): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 61
D/WifiNative-wlan0(  906):    returned true
D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): onScreenOff.
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1805): init: null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ConnectionQueueManager]( 1805):  + initPendingRequestAlarm: false, mContext = null, null
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1805): writeLinkLossAlertLevelAll: 0, false
V/BluetoothPbapService( 1593): successfully stopped pbap service
V/BluetoothPbapService( 1593): Pbap Service closeService out
D/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1805): deinitLeServices_platform
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1805): loadDeviceConfiguration() init =false
V/BluetoothSapService( 1593): action: android.bluetooth.adapter.action.STATE_CHANGED
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfilesGoogle]( 1805):  + mTag.getPrimaryDeviceList() = []
V/BluetoothSapService( 1593): state: 13
D/[HTC_BLE_2013.12.02.SDKBUILD][ProfileServicesGoogle]( 1805): deinit: 0
D/BluetoothAdapter( 1593): 1102592496: getState(). Returning 13
D/BluetoothManagerService(  906): Message: MESSAGE_UNREGISTER_ADAPTER
V/BluetoothSapService( 1593): Stopping SAP server process
D/BluetoothManagerService(  906): Removed callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@425fd380:true
D/WifiNative-wlan0(  906):    returned true
D/PMS     (  906): acquireWL(4268ba10): PARTIAL_WAKE_LOCK  ConnectivityService 0x1 906 1000 null
D/WifiP2pService(  906): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc    (  906): [NET] getaddrinfo+,hn 13(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
D/BluetoothAdapter( 3823): 1102998600: getState(). Returning 13
D/DhcpStateMachine(  906): [RunningState] Stop DHCP
D/BluetoothInputDevice( 3823): BluetoothInputDevice()
D/BluetoothManagerService(  906): registerStateChangeCallback+
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): disableBatteryAlarm
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalBatteryService]( 1805): disableBatteryAlarm: null
D/[HTC_BLE_2013.12.02.SDKBUILD][NotificationHandler]( 1805): init: null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1805): shutdownStateMachine
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1805): init: null
D/[HTC_BLE_2013.12.02.SDKBUILD][GattQueueManager]( 1805): setPendingRequestAlarm: false, mContext = null, null
I/[HTC_BLE_2013.12.02.SDKBUILD][LocalStateMachine]( 1805): Exit IdleState
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 7
V/BluetoothSapService( 1593): Sap Service closeSapService in
V/BluetoothSapService( 1593): Close listen Socket : 
V/BluetoothSapService( 1593): Close rfcomm Socket : 
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
V/BluetoothSapService( 1593): Close sapd  Socket : 
V/BluetoothSapReceiver( 1593): BluetoothSapReceiver deinit
D/BluetoothAdapter( 3823): 1102998600: getState(). Returning 13
D/BluetoothInputDevice( 3823): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 3823): Bluetooth service connected
W/BluetoothInputDevice( 3823): Proxy not attached to service
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING GET
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET"
D/BluetoothPan( 3823): BluetoothPan()
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING GET" Return -1
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/WifiNative-wlan0(  906):    returned null
E/WifiStateMachine(  906): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  906): doString: DRIVER WLS_BATCHING STOP
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/BluetoothManagerService(  906): Registered receivers: 8
E/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd: failed to issue private commands
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER WLS_BATCHING STOP" Return -1
D/WifiDataStallTracker(  906): stopDataStallAlarm: current tag=19046 mDataStallAlarmIntent=PendingIntent{42207d10: PendingIntentRecord{42209630 android broadcastIntent}}
D/libc    (  906): [NET] getaddrinfo+,hn 25(0x666538303a3a38),sn(),family 0,flags 4
D/libc    (  906): [NET] getaddrinfo-, SUCCESS
,D/WifiNative-wlan0(  906):    returned null
I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/BluetoothAdapter( 3823): 1102998600: getState(). Returning 13
D/BluetoothPan( 3823): BluetoothPan(): Fake return onServiceConnected
D/PanProfile( 3823): Bluetooth service connected
,D/BluetoothMap( 3823): Create BluetoothMap proxy object
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
E/BluetoothMap( 3823): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  906): Registered receivers: 9
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
,D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
I/EASAppSvc( 4004): [ NA ]- onDestroy()
,I/EASAppSvc( 4004): [ NA ]> uninitEASService
D/WifiService(  906): New client listening to asynchronous messages
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/ConnectivityService(  906): ConnectivityChange for WIFI/: DISCONNECTED/DISCONNECTED, default=1
D/ConnectivityService(  906): Provision feature enable=false
D/ConnectivityService(  906): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (4004/10063)
D/WifiP2pService(  906): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  906): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 10
D/BluetoothSap( 3823): BluetoothSap() call bindService
I/SoundPicker( 3967): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
,W/ContextImpl( 3967): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
,D/WifiStateMachine(  906): Call handleNetworkDisconnect() in SupplicantStoppingState
V/BluetoothSapService( 1593): successfully stopped Sap service
,V/BluetoothSapService( 1593): Sap Service closeSapService out
,I/BtOppRfcommListener( 1593): stopping Accept Thread
,I/BtOppRfcommListener( 1593): BluetoothSocket listen thread finished
D/UsbnetStateTracker(  906): isAvailable+-
D/UsbnetStateTracker(  906): reconnect
,D/UsbnetStateTracker(  906): isAvailable+-
W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
D/WifiP2pService(  906): P2pDisablingState
D/WifiP2pService(  906): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): p2p socket connection lost
D/WifiP2pService(  906): P2pDisabledState
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (4004/10063)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): tryFailover, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/MDST    (  906): default: reconnect()
D/MDST    (  906): default: setTeardownRequested(false)
,D/MDST    (  906): default: setEnableApn apnType =default , enable=true
D/BluetoothPbap( 3823): BluetoothPbap()
I/SoundPicker( 3967): SoundPickerReceiver [onReceive] startService
D/WifiNative-wlan0(  906): doBoolean: DRIVER POWERMODE 0
,W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER POWERMODE 0"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
I/wpa_supplicant( 1152): Power_Mode_Type mode = 0
I/wpa_supplicant( 1152): Set power mode to POWER_MODE_AUTO due to Active_Mode_Enable = 0x0
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 61
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
,D/libc    (  364): [NET] getaddrinfo-, SUCCESS
V/BluetoothPbapService( 1593): Pbap Service onDestroy
V/BluetoothPbapService( 1593): Pbap Service closeService in
,V/BluetoothPbapService( 1593): Pbap Service closeService out
D/BluetoothManagerService(  906): registerStateChangeCallback+
I/SoundPicker( 3967): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3967): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3967): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3967): MODE_GSM access default DB
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3967): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3967): MODE_GSM access default DB
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/BluetoothManagerService(  906): Registered receivers: 11
D/WifiNative-wlan0(  906):    returned true
,D/WifiNative-wlan0(  906): doBoolean: DRIVER BTCOEXMODE 2
V/BluetoothSapService( 1593): Sap Service onDestroy com.android.bluetooth.sap.BluetoothSapService$BluetoothSapBinder@41bbda28
V/BluetoothSapService( 1593): Sap Service closeSapService in
V/BluetoothSapService( 1593): Close listen Socket : 
V/BluetoothSapService( 1593): Close rfcomm Socket : 
V/BluetoothSapService( 1593): Close sapd  Socket : 
D/ConnectivityService(  906): handleConnectivityChange: netType=1 doReset=true resetMask=3
D/ConnectivityService(  906): updateRoutes: default remove route r=192.168.1.0/24 -> 0.0.0.0
D/ConnectivityService(  906): Removing 192.168.1.0/24 -> 0.0.0.0 for interface wlan0
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
D/WifiDisplayController(  906): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController(  906): updateWfdEnableState, mWifiDisplayOnSetting: true,  mWifiP2pEnabled: false
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController(  906): set mDesiredDevice to null in disconnect()
I/WifiDisplayController(  906): set wifi.miracastlock to 0 for disconnect case
D/WifiP2pService(  906): P2pDisabledState{ when=0 what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=139323 arg2=2 obj=WFD enabled: falseWFD DeviceInfo: 0
D/WifiP2pService(  906):  WFD CtrlPort: 0
D/WifiP2pService(  906):  WFD MaxThroughput: 0 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiDisplayController(  906): updateScanState(): mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
I/WifiDisplayController(  906): updateConnection
I/WifiDisplayController(  906): mConnectingDevice = null,  mDesiredDevice = null
I/WifiDisplayController(  906): updateConnection enter step 4
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '26 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 26 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): updateRoutes: default remove route r=0.0.0.0/0 -> 192.168.1.1
D/WifiDisplayController(  906): Failed to set WFD info with reason 2.
D/WifiDisplayAdapter(  906): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
D/WifiDisplayAdapter(  906):     Client/Owner: Client
D/WifiDisplayAdapter(  906):     GroupId: 
D/WifiDisplayAdapter(  906):     Passphrase: 
D/WifiDisplayAdapter(  906):     SessionId: 0
D/WifiDisplayAdapter(  906):     IP Address: }
D/ConnectivityService(  906): Removing 192.168.1.1/32 -> 0.0.0.0 for interface wlan0
D/WifiP2pService(  906): P2pDisabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  906): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
V/AudioService(  906): Broadcast Receiver: DisplayManager.ACTION_WIFI_DISPLAY_STATUS_CHANGED, WifiDisplayStatus = WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
V/AudioService(  906):     Client/Owner: Client
V/AudioService(  906):     GroupId: 
V/AudioService(  906):     Passphrase: 
V/AudioService(  906):     SessionId: 0
V/AudioService(  906):     IP Address: }
W/WifiHW  (  906): QCOM Debug wifi_send_command "IFNAME=wlan0 DRIVER BTCOEXMODE 2"
I/wpa_supplicant( 1152): Recv Cmd 1: IFNAME=wlan0
D/wpa_supplicant( 1152): wpa_driver_nl80211_driver_cmd BTCOEXMODE 2 len = 0, 12
D/HtcEffectManagerBase(  906): onEventChanged id=5 status=false
D/libc    (  364): [NET] getaddrinfo+,hn 7(0x302e302e302e30),sn(),family 0,flags 4
D/HtcEffectManager(  906): checkBeatsSupport mMirrorOn=false mMiracastOn=false mSubwooferOn=false mSubwooferHeadset=false mHeadsetConnected=false mBTHeadsetConnected=false mBTA2dpHeadset=false mHDMIOn=false mBeatsSpeaker=true
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/HtcEffectManager(  906): convertEffect before=902
D/HtcEffectManager(  906): convertEffect after=902
D/libc    (  364): [NET] getaddrinfo+,hn 11(0x3139322e313638),sn(),family 0,flags 4
D/libc    (  364): [NET] getaddrinfo-, SUCCESS
D/BluetoothAdapter( 3823): 1102998600: getState(). Returning 13
D/BluetoothPbap( 3823): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 3823): Bluetooth service connected
D/LocalBluetoothProfileManager( 3823): LocalBluetoothProfileManager construction complete
D/WifiNative-wlan0(  906):    returned true
V/BluetoothSapService( 1593): Sap Service closeSapService out
V/BluetoothSapService( 1593): ***onDestroyed***
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '27 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 27 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): Removing 0.0.0.0/0 -> 192.168.1.1 for interface wlan0
W/ConnectivityService(  906): Exception trying to remove a route: java.lang.IllegalStateException: command '28 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 28 Failed to remove route from default table (No such process)'
D/ConnectivityService(  906): handleConnectivityChange: resetting
D/ConnectivityService(  906): resetConnections(wlan0, 3)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (4004/10063)
D/PMS     (  906): acquireWL(421ba208): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1367 10028 null
D/ConnectivityService(  906): flush DNS cache for net 1(wlan0)
D/libc    (  364): [NET] entry_id:5   entry:0xb71de7c8  removed 
D/libc    (  364): [NET] entry_id:4   entry:0xb71de718  removed 
D/libc    (  364): [NET] entry_id:2   entry:0xb71de548  removed 
D/libc    (  364): [NET] entry_id:6   entry:0xb71de890  removed 
D/libc    (  364): [NET] entry_id:3   entry:0xb71de610  removed 
D/libc    (  364): [NET] entry_id:1   entry:0xb71de4b0  removed 
D/libc    (  364): *************************
D/libc    (  364): *** DNS CACHE FLUSHED ***
D/libc    (  364): *************************
D/HtcBtWidget_BTWidgetProvider( 4026): onBTStateChanged() for widget: 
D/HtcBtWidget_BTWidgetProvider( 4026): updateWidget(context) for widget: 
D/DockEventReceiver( 3823): finishStartingService: stopping service
D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WISPrService( 3823): >>>>>WISPrService start isConnected = false<<<<<
D/Nat464Xlat(  906): htcRequiresClat: netType=1, hasIPv4=false, mIsClatEnabled=true, isConnected=false
D/Nat464Xlat(  906): htcCheckClatToStartOrStop: needStart=false, isDefaultMobile=false, needStop=false, mIsStarted=false, mIsRunning=false
D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/PMS     (  906): releaseWL(426bb1b8): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
D/ConnectivityService(  906): sendStickyBroadcastDelayed: delayMs=1000, action=android.net.conn.CONNECTIVITY_CHANGE
D/PMS     (  906): acquireWL(42407278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1367 10028 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/PMS     (  906): acquireWL(4240a588): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): handleDisconnect, type=1, ACC=false, null active network=true, mobiledata=true,mActiveDefaultNetwork=-1, mUserEnableNotify=true, mIsConnectedtoDisconnect=true, mIsQuickbootBlockWiFiNotify=false
D/ConnectivityService(  906): delSouceRouteRule info= NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
D/WISPrService( 3823): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: mCurNetworkInterfacewlan0
D/WirelessDisplayService(  906): [WFDERR][1] ConnectivityReceiver: receiver wifi disconnected, wait20000sec
D/WifiNative-p2p0(  906): doBoolean: TERMINATE
W/WifiHW  (  906): QCOM Debug wifi_send_command "TERMINATE"
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
E/wpa_supplicant( 1152): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1152): TDLS: Tear down peers
I/wpa_supplicant( 1152): wpa_driver_nl80211_disconnect(reason_code=3)
D/WifiNative-p2p0(  906):    returned true
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=-9ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
D/WifiService(  906): New client listening to asynchronous messages
D/ConnectivityService(  906): reportInetCondition for net -1, percentage: 0 by  (1367/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
D/PMS     (  906): releaseWL(42407278): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
D/PMS     (  906): releaseWL(421ba208): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WifiStateMachine(  906): startScan Pid: 906 Uid 1000
I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
E/BluetoothFtpService:RfcommSocketAcceptThread( 1593): Shutdown
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
D/WISPrService( 3823): >>>>>WISPrService start isConnected = false<<<<<
D/BluetoothMasReceiver( 1593): Bluetooth STATE CHANGED to 13
D/WISPrService( 3823): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): [MLHD] enter handleMediaLinkEvent DefaultState
E/WifiStateMachine(  906): [MLHD] Error! unhandled message 1 { when=-1ms what=131282 target=com.android.internal.util.StateMachine$SmHandler }
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1805): Received state change = 13
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1367/10028)
E/[HTC_BLE_2013.12.02.SDKBUILD][PlatformService]( 1805): onDestroy: com.htc.bluetooth.le.profiles.gatt.google.BaseLeProfilesGoogle@41b8b210
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): onDestroy() called...
I/[HTC_BLE_2013.12.02.SDKBUILD][BaseLeProfiles]( 1805): deinitLeServices: null
I/ActivityManager(  906): Start proc com.android.settings:remote for broadcast com.android.settings/.widget.SettingsAppWidgetProvider: pid=4050 uid=1000 gids={41000, 5006, 5001, 3006, 1028, 1015, 3002, 3001, 3003, 5012, 9985, 1023, 5011, 1007}
D/Process (  906): killProcessQuiet, pid=3786
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 48
I/wpa_supplicant( 1152): Clean 'force_connect' when disconnect
I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1152): wpa_supplicant_event_disassoc: Set wifi.hotspot.channel to -1
D/HTCRequest(  906): WifiMonitor:handleNetworkStateChange CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1152): TDLS: Remove peers on disassociation
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getNetworkIdFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
,D/HTCRequest(  906): WifiMonitor:getBSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/HTCRequest(  906): WifiMonitor:getBSSIDFromString BSSIDc0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getSSIDFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/HTCRequest(  906): WifiMonitor:getReasonFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
E/wpa_supplicant( 1152): send_and_recv error -67 - cmd 12
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_key: ifindex=22 (wlan0) alg=0 addr=0xb87a5bc4 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 1152):    addr=c0:ff:d4:d3:aa:48
D/HTCRequest(  906): WifiMonitor:getReasonFromEventString() 3
E/wpa_supplicant( 1152): send_and_recv error -2 - cmd 12
D/HTCRequest(  906): WifiMonitor:getLocallyGeneratedInfoFromEventString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1152): State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 1152): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  906): WifiMonitor:getFrequencyFromString CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1 ssid='NG700' freq=2412
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1152): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1152): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:getFreqFromEventString() 2412
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - portValid=0
D/WifiMonitor(  906): notifyNetworkStateChange. wifiSsid ='NG700' freq=2412
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/HTCRequest(  906): WifiMonitor:handleSupplicantStateChange():id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
D/HTCRequest(  906): WifiMonitor:getSSIDFromString id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
I/wpa_supplicant( 1152): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1152): netlink: Operstate: linkmode=-1, operstate=5
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING (0)+
D/HTCRequest(  ,906): WifiMonitor:handleSupplicantStateChange(): SSIDNG700
I/wpa_supplicant( 1152): htc_wext_set_TX_TRACKING - ret = 0
D/wpa_supplicant( 1152): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/WifiMonitor(  906): WifiMonitor: prevSupplicantState =COMPLETED newSupplicantState =DISCONNECTED
I//system/bin/ip(  364): RTNETLINK answers: No such process
I/logwrapper(  364): /system/bin/ip terminated by exit(2)
,I/ActivityManager(  906): Killing 3786:com.htc.mobiledata/u0a91 (adj 15): empty #17
D/Tethering(  906): [isWifi] getHotspotEnabled: false
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/Tethering(  906): [isWifi] getHotspotEnabled: false
,I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/ActivityManager(  906): Recipient 3786
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:0
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLING setEnable:false enableSAA:false
D/ConnectivityService(  906): mActiveDefaultNetwork: -1
D/ConnectivityService(  906): handleInetConditionChange: no active default network - ignore
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,V/Settings:HtcSettingsApplication( 4050): [4050/4050] onCreate()
,D/PMS     (  906): releaseWL(4240a588): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
W/bt-btif ( 1593): ag scb idx 1 not allocated
W/bt-btif ( 1593): ag scb idx 2 not allocated
E/bt-btif ( 1593): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 1593): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1593): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1593): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1593): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 1593): L2CAP - PSM: 0x0019 not found for deregistration
,W/bt-l2cap( 1593): L2CAP - PSM: 0x0017 not found for deregistration
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,D/WifiService(  906): New client listening to asynchronous messages
I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
,E/bt_userial_mct( 1593): userial_close userial_thread_created userial_running is 1 
,I/HtcModeClient( 1499): handler message = 4011
,E/HtcModeClient( 1499): Check connection and retry 6 times.
,D/Process (  906): killProcessQuiet, pid=3614
,I/ActivityManager(  906): Killing 3614:com.google.android.apps.plus/u0a160 (adj 15): empty #17
D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:231 
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/EASRequestController( 4004): [ NA ]release
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/EASAppSvc( 4004): [ NA ]< uninitEASService
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/EASAppSvc( 4004): [ NA ]- onCreate()
,I/EASAppSvc( 4004): [ NA ]> onUpgrade: version = 63
,D/Process (  906): killProcessQuiet, pid=3799
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Killing 3799:com.nero.android.htc.sync/u0a8 (adj 15): empty #17
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.android.mail (4004/10063)
D/ConnectivityService(  906): getNetworkInfo networkType=0 called by com.htc.android.mail (4004/10063)
D/ConnectivityService(  906): getNetworkInfo networkType=55 called by com.htc.android.mail (4004/10063)
I/ActivityManager(  906): Resuming delayed broadcast
,D/ORMLib  ( 3425): put()
I/ActivityManager(  906): Recipient 3799
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
D/WifiService(  906): Client connection lost with reason: 4
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/EASAppSvc( 4004): [ NA ]- onDestroy()
,I/EASAppSvc( 4004): [ NA ]> uninitEASService
,I/EASRequestController( 4004): [ NA ]release
,I/EASAppSvc( 4004): [ NA ]< uninitEASService
,I/ActivityManager(  906): Start proc com.htc.task.gtask for service com.htc.task.gtask/.syncadapter.SyncService: pid=4083 uid=10067 gids={50067, 3003, 5012}
,E/wpa_supplicant( 1152): wlan0: BLACKLIST CLEAR 
E/wpa_supplicant( 1152): wlan0: BLACKLIST REMOVE 00:00:00:00:00:00
I/wpa_supplicant( 1152): nl80211: wpa_driver_nl80211_deinit
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST CLEAR 
,D/WifiMonitor(  906): NETWORK_SELECTION: received BLACKLIST event:BLACKLIST REMOVE 00:00:00:00:00:00
I/ActivityManager(  906): Recipient 3614
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,E/cutils-trace( 4047): Error opening trace file: No such file or directory (2)
,D/Process (  906): killProcessQuiet, pid=3720
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
I/ActivityManager(  906): Killing 3720:com.htc.widget.hmsproc1/u0a38 (adj 15): empty #17
,I/MediaStoreImporter( 3913): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/Process (  906): killProcessQuiet, pid=3382
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16983 com.android.server.am.ActivityManagerService.updateOomAdjLocked:16827 
,D/ORMLib  ( 3425): put()
I/ActivityManager(  906): Resuming delayed broadcast
I/ActivityManager(  906): Recipient 3720
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Killing 3382:com.htc.mms.backupagent/u0a77 (adj 15): empty #17
,D/DFPI.PIReciver( 3933): onReceiver action:android.intent.action.MEDIA_SCANNER_FINISHED
I/ActivityManager(  906): Recipient 3382
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/ActivityManager(  906): Resuming delayed broadcast
D/wpa_supplicant( 1152): netlink: Operstate: linkmode=0, operstate=6
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 5
D/wpa_supplicant( 1152): nl80211: Set mode ifindex 22 iftype 2 (STATION)
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 6
D/wpa_supplicant( 1152): nl80211: Unsubscribe mgmt frames handle 0xb87a6718 (mode change)
I/wpa_supplicant( 1152): htc_wext_command_deinit +
I/wpa_supplicant( 1152): htc_wext_command_deinit -
E/wpa_supplicant( 1152): wlan0: Supplicant Terminat @ wpa_supplicant_deinit_iface function
,I/wpa_supplicant( 1152): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 1152): Control interface directory not empty - leaving it behind
E/wpa_supplicant( 1152): Supplicant Terminat @ wpa_supplicant_deinit function
D/wpa_supplicant( 1152): TDLS: Tear down peers
I/wpa_supplicant( 1152): State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 1152): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 1152): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 1152): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
D/wpa_supplicant( 1152): EAPOL: External notification - portValid=0
D/wpa_supplicant( 1152): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 1152): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/wpa_supplicant( 1152): send_and_recv error 0 - cmd 18
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , pre killSupplicant
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post killSupplicant
W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection pre wifi_close_sockets
I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x6264e108,
I/wpa_ctrl(  906): [wpa_ctrl_close] ctrl=0x6282dca8
,W/WifiHW  (  906): QCOM Debug wifi_close_supplicant_connection post wifi_close_sockets
E/WifiStateMachine(  906): QCOM Debug in handleSupplicantConnectionLoss , post closeSupplicantConn
I/DFPI.ApkInstallService( 3933): onHandleIntent
I/DFPI.ApkInstallService( 3933): Media Scan Finished Case 
D/Tethering(  906): interfaceLinkStateChanged wlan0, false
D/Tethering(  906): interfaceStatusChanged wlan0, false
D/DFPI.ApkInstallService( 3933): check CID = HTC__032
I/DFPI.ApkInstallService( 3933): There is no Demo.apk in sd card or phone storage
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
I/ActivityManager(  906): Delay finish: com.htc.demoflopackageinstaller/.PIReceiver
,I/ActivityManager(  906): Resuming delayed broadcast
D/WifiStateMachine(  906): setAuthErrorNotificationVisible visible=false
D/WifiNative-wlan0(  906): doBoolean: SET_WIFI_ON 0
D/WifiNative-wlan0(  906):    returned false
D/WifiStateMachine(  906): Enter handleNetworkDisconnect
,D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.WIFI_STATE_CHANGED
D/WirelessDisplayService(  906): WifiReceiver: action:android.net.wifi.WIFI_STATE_CHANGEDstate1
D/WirelessDisplayService(  906): WIFI Trun OFF
D/WirelessDisplayService(  906): getDiscoveryDongleList
,I/IntentController( 1117): receive(android.net.wifi.WIFI_STATE_CHANGED,1,false)
,D/WifiStateMachine(  906): [sendNetworkStateChangeBroadcast] NetworkInfo state =DISCONNECTED wifi info = SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
D/WifiStateMachine(  906): Exit handleNetworkDisconnect
,E/WifiStateMachine(  906): [MLHD] Error! unhandled message 6 { when=-16ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WIFI_ICON( 1117): updateWifiState: WIFI_STATE_CHANGED disabled
D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
,D/PMS     (  906): acquireWL(425dc240): PARTIAL_WAKE_LOCK  WifiStateMachine 0x1 906 1000 null
D/WifiDataStallTracker(  906): onReceive: action=android.net.wifi.STATE_CHANGE
D/WifiDataStallTracker(  906): NETWORK_STATE_CHANGED_ACTION: mIsWifiConnected=false
,I/IntentController( 1117): receive(android.net.wifi.STATE_CHANGE,1,false)
,D/WISPrService( 3823): >>>>>WISPrService start isConnected = false<<<<<
D/WifiStateTracker(  906): WifiStateTracker receive NETWORK_STATE_CHANGED_ACTION intent
D/WIFI_ICON( 1117): updateWifiState: NETWORK_STATE_CHANGED disconnected
,D/StatusBar.NetworkController( 1117): dumpIcon[(gone) stat_sys_5signal_null|null (gone) (gone) T]
I/SoundPicker( 3967): SoundPickerReceiver [onReceive] action = android.intent.action.MEDIA_SCANNER_FINISHED
D/WISPrService( 3823): wifi connected:falsemWifiInfo:SSID: <unknown ssid>, BSSID: <none>, Supplicant state: COMPLETED, RSSI: -200, Link speed: -1, Frequency: -1, Net ID: -1, Metered hint: false
W/ContextImpl( 3967): Implicit intents with startService are not safe: Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) } android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.htc.sdm.soundpicker.SoundPickerReceiver.onReceive:34 
I/SoundPicker( 3967): SoundPickerReceiver [onReceive] startService
I/SoundPicker( 3967): TurnFileToMediaUriService onHandleIntent - Intent { act=com.htc.sdm.TurnFileToMediaUriService (has extras) }
V/SoundPicker( 3967): TurnFileToMediaUriService fromMediaScanned = true
I/SoundPicker( 3967): TurnFileToMediaUriService [turnFileUriIntoMediaUri]
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3967): MODE_GSM access default DB
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/112
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/58
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/86
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/92
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/94
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
W/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [turnFileUriIntoMediaUri] already converted uri = content://media/internal/audio/media/88
I/SoundPicker( 3967): TurnFileToMediaUriService [checkFileExistence]
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_gsm)
D/RingtoneManager( 3967): MODE_GSM access default DB
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=1
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
I/ActivityManager(  906): Delay finish: com.htc.sdm/.soundpicker.SoundPickerReceiver
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 1 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_cdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=2
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 2 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 1, mode_wcdma)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/112 type=3
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get current setting uri = content://media/internal/audio/media/112
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/ringtones/Dahlia.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] get original file path = /system/media/audio/ringtones/Dahlia.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 3 [checkFileExistence] fileExisted = /system/media/audio/ringtones/Dahlia.flac
,D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 2)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=4
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/QuickSettingWifi( 1117): receive.wifiState:WIFI_STATE_DISABLED setEnable:true enableSAA:false
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 4 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
D/RingtoneManager( 3967): getActualDefaultRingtoneUri(context, 4)
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/58 type=5
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get current setting uri = content://media/internal/audio/media/58
,I/QuickSettingWifi( 1117): receive.wifiConnect:false wifiAPname:null elapse:1
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] get original file path = /system/media/audio/alarms/Foxglove.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 5 [checkFileExistence] fileExisted = /system/media/audio/alarms/Foxglove.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/86 type=6
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get current setting uri = content://media/internal/audio/media/86
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lilac.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] get original file path = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 6 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lilac.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/92 type=7
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get current setting uri = content://media/internal/audio/media/92
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] get original file path = /system/media/audio/notifications/Orchid.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 7 [checkFileExistence] fileExisted = /system/media/audio/notifications/Orchid.flac
I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/94 type=8
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get current setting uri = content://media/internal/audio/media/94
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] get original file path = /system/media/audio/notifications/Sage.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 8 [checkFileExistence] fileExisted = /system/media/audio/notifications/Sage.flac
,I/SoundPicker( 3967): SoundPickerUtil [getRingtone] uri=content://media/internal/audio/media/88 type=9
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get current setting uri = content://media/internal/audio/media/88
,I/SoundPicker( 3967): SoundPickerUtil [getFilePathByAudioContentUri] filePath = /system/media/audio/notifications/Lotus.flac
I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] get original file path = /system/media/audio/notifications/Lotus.flac
,I/SoundPicker( 3967): TurnFileToMediaUriService [type] = 9 [checkFileExistence] fileExisted = /system/media/audio/notifications/Lotus.flac
I/ActivityManager(  906): Resuming delayed broadcast
,D/CustomizationManager( 4047): ====startRecUseTime====
,D/htc.customization.log.level( 4047):  is 
,W/CustomizationLogLevel( 4047): Level value is invalid, use default level 2
I/ActivityManager(  906): Delay finish: com.google.android.music/.store.MediaStoreImportService$Receiver
,I/MediaStoreImporter( 3913): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/TelephonyReceiver( 1241): bind: true
,I/ActivityManager(  906): Resuming delayed broadcast
D/TelephonyReceiver( 1241): bind: false
D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/GenericMessagesProvider( 3750): query uri: content://htc-messages/wappush/count
E/SQLiteLog( 3750): (14) cannot open file at line 30190 of [00bb9c9ce4]
,E/SQLiteLog( 3750): (14) os_unix.c:30190: (2) open(/data/data/com.htc.sense.mms/databases/wappush.db) - 
E/SQLiteConnection( 3750): DB info: sqlite3_open_v2, path: /data/data/com.htc.sense.mms/databases/wappush.db, flag: 1, ret: 14
,E/SQLiteConnection( 3750): DB info: errno = 2, errno message = No such file or directory
D/PMS     (  906): acquireWL(426626d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 906 1000 null
,E/SQLiteDatabase( 3750): Failed to open database '/data/data/com.htc.sense.mms/databases/wappush.db'.
E/SQLiteDatabase( 3750): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 3750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
E/SQLiteDatabase( 3750): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
E/SQLiteDatabase( 3750): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 3750): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 3750): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
E/SQLiteDatabase( 3750): 	at android.os.Binder.execTransact(Binder.java:412)
E/SQLiteDatabase( 3750): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 3750): android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
W/System.err( 3750): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
W/System.err( 3750): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
,W/System.err( 3750): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
W/System.err( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
W/System.err( 3750): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
W/System.err( 3750): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
W/System.err( 3750): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
W/System.err( 3750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
W/System.err( 3750): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:709)
W/System.err( 3750): 	at com.htc.sense.mms.util.GenericMessagesProvider.query(GenericMessagesProvider.java:251)
W/System.err( 3750): 	at android.content.ContentProvider.query(ContentProvider.java:869)
W/System.err( 3750): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
W/System.err( 3750): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:143)
W/System.err( 3750): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err( 3750): 	at dalvik.system.NativeStart.run(Native Method)
,D/TelephonyReceiver( 1241): switchBindHtcMsgCursor: null
,D/WifiDataStallTracker(  906): onReceive: action=com.android.internal.wifi.data-stall
,D/WifiDataStallTracker(  906): onActionIntentDataStallAlarm: action=com.android.internal.wifi.data-stall
,D/PMS     (  906): releaseWL(426626d8): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
D/WifiDataStallTracker(  906): onDataStallAlarm: ignore, tag=19046 expecting 19047
,D/PackageBroadcastService( 2228): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
,I/bt-btif ( 1593): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothAdapterState( 1593): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,D/HeadsetService( 1593): Received stop request...Stopping profile...
I/ActivityManager(  906): Delay finish: com.google.android.gms/.app.receiver.SystemBroadcastReceiver
,D/BluetoothAdapterState( 1593): Stopping profile services that were post enabled
,D/BluetoothHeadset(  906): Proxy object disconnected
D/BluetoothHeadset( 1117): Proxy object disconnected
D/BluetoothHeadset( 1241): Proxy object disconnected
D/BluetoothPhoneService( 1241): BluetoothHeadset onServiceDisconnected
D/BluetoothHeadset( 1241): Proxy object disconnected
,I/QuickSettingMiniLite( 1117): btListener.disconnect:HEADSET
,D/A2dpService( 1593): Received stop request...Stopping profile...
D/A2dpStateMachine( 1593): doQuit
,D/A2dpStateMachine( 1593): Exit Disconnected: -1
,D/CustomizationManager( 4047):  Read ACC file spent 0.058 (s)
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__001
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__102
,D/CIDMapFileReader( 4047): Parsing tag item name = HTC__Y13
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__A07
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__032
D/BluetoothA2dp(  906): Proxy object disconnected
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__J15
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__016
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__M27
D/CIDMapFileReader( 4047): Parsing tag item name = HTC__002
,D/CIDMapFileReader( 4047): Parsing tag item name = HTC__031
,D/HidService( 1593): Received stop request...Stopping profile...
V/CustomizationCIDLoader( 4047): full path : /system/customize/CID/HTC__032.xml
,I/CustomizationCIDLoader( 4047): Parsing tag category name = system
,I/CustomizationCIDLoader( 4047): Parsing tag category name = application
,I/CustomizationCIDLoader( 4047): Parsing tag category name = SettingsProvider
I/CustomizationCIDLoader( 4047): Parsing tag category name = AutomotiveHome
I/CustomizationCIDLoader( 4047): Parsing tag category name = AudioService
I/CustomizationCIDLoader( 4047): Parsing tag category name = ACC
D/HealthService( 1593): Received stop request...Stopping profile...
,I/CustomizationCIDLoader( 4047): Parsing tag category name = Settings
,D/CustomizationManager( 4047):  Read CID file spent 0.109 (s)
D/CustomizationManager( 4047):  All configurations done spent 0.109 (s)
,D/PanService( 1593): Received stop request...Stopping profile...
D/PanService( 1593): stop
,D/PanService( 1593): stop: mTetherAc send disconnect
,D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECT
D/BluetoothTethering(  906): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  906): attempted to stop reverse tether with nothing tethered
W/HtcNativeFlag( 4047): Fail to get flag string for type 'customer', use default value
W/HtcNativeFlag( 4047): Fail to get flag for type 'customer', use default value: -1
W/HtcNativeFlag( 4047): Fail to get flag string for type 'language', use default value
,W/HtcNativeFlag( 4047): Fail to get flag for type 'language', use default value: -1
,D/BluetoothPan(  906): BluetoothPAN Proxy object disconnected
,D/BtGatt.DebugUtils( 1593): handleDebugAction() action=null
D/BtGatt.GattService( 1593): Received stop request...Stopping profile...
,D/BtGatt.GattService( 1593): stop()
,D/BluetoothAdapterService( 1593): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHeadsetServiceJni( 1593): Cleaning up Bluetooth Handsfree Interface...
,W/BluetoothHeadsetServiceJni( 1593): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1593): Profile still running: com.android.bluetooth.hdp.HealthService
,D/A2dpStateMachine( 1593): cleanup
,D/Avrcp   ( 1593): Unregistering previous receiver
,D/BluetoothAdapterService( 1593): Profile still running: com.android.bluetooth.hdp.HealthService
W/BluetoothHidServiceJni( 1593): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 1593): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1593): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 1593): Profile still running: com.android.bluetooth.pan.PanService
,W/BluetoothHealthServiceJni( 1593): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 1593): Cleaning up Bluetooth Health object
D/PanService( 1593): CMD_CHANNEL_DISCONNECTED
,D/PMS     (  906): acquireWL(41b5a0a0): PARTIAL_WAKE_LOCK  Icing 0x1 2228 10028 null
D/PanService( 1593): CMD_CHANNEL_DISCONNECTED call disconnected
D/BluetoothAdapterService( 1593): Profile still running: com.android.bluetooth.gatt.GattService
W/BluetoothPanServiceJni( 1593): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1593): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterState( 1593): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 1593): Setting state to 10
I/BluetoothAdapterState( 1593): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1593): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  906): +onBluetoothStateChange prev=13 new=10
D/BluetoothManagerService(  906): Message: MESSAGE_BLUETOOTH_STATE_CHANGE
D/BluetoothManagerService(  906): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  906): Broadcasting onBluetoothStateChange(false) to 11 receivers.
I/BluetoothAdapterState( 1593): Entering OffState
D/BluetoothPbap( 3823): onBluetoothStateChange: up=false
,E/BluetoothPbap( 3823): 
E/BluetoothPbap( 3823): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPbap$2@41bfc530
E/BluetoothPbap( 3823): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPbap( 3823): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPbap( 3823): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPbap( 3823): 	at android.bluetooth.BluetoothPbap$1.onBluetoothStateChange(BluetoothPbap.java:122)
E/BluetoothPbap( 3823): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPbap( 3823): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPbap( 3823): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothSap( 3823): onBluetoothStateChange on: false
D/BluetoothMap( 3823): onBluetoothStateChange: up=false
,E/BluetoothMap( 3823): 
E/BluetoothMap( 3823): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothMap$2@41bf5af8
E/BluetoothMap( 3823): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothMap( 3823): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothMap( 3823): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothMap( 3823): 	at android.bluetooth.BluetoothMap$1.onBluetoothStateChange(BluetoothMap.java:66)
E/BluetoothMap( 3823): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothMap( 3823): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothMap( 3823): 	at dalvik.system.NativeStart.run(Native Method)
,E/BluetoothPan( 3823): 
E/BluetoothPan( 3823): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothPan$2@41bf4778
E/BluetoothPan( 3823): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothPan( 3823): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothPan( 3823): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothPan( 3823): 	at android.bluetooth.BluetoothPan$1.onBluetoothStateChange(BluetoothPan.java:213)
E/BluetoothPan( 3823): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothPan( 3823): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothPan( 3823): 	at dalvik.system.NativeStart.run(Native Method)
,D/PMS     (  906): releaseWL(41b5a0a0): PARTIAL_WAKE_LOCK  Icing 0x1 null
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 3823): onBluetoothStateChange: up=false
E/BluetoothInputDevice( 3823): 
E/BluetoothInputDevice( 3823): java.lang.IllegalArgumentException: Service not registered: android.bluetooth.BluetoothInputDevice$2@41bf31e0
E/BluetoothInputDevice( 3823): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1030)
E/BluetoothInputDevice( 3823): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1857)
E/BluetoothInputDevice( 3823): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:536)
E/BluetoothInputDevice( 3823): 	at android.bluetooth.BluetoothInputDevice$1.onBluetoothStateChange(BluetoothInputDevice.java:199)
E/BluetoothInputDevice( 3823): 	at android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact(IBluetoothStateChangeCallback.java:55)
E/BluetoothInputDevice( 3823): 	at android.os.Binder.execTransact(Binder.java:412)
E/BluetoothInputDevice( 3823): 	at dalvik.system.NativeStart.run(Native Method)
D/BluetoothHeadset( 1117): onBluetoothStateChange: up=false
D/BluetoothA2dp(  906): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1241): onBluetoothStateChange: up=false
D/BluetoothHeadset(  906): onBluetoothStateChange: up=false
D/BluetoothManagerService(  906): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  906): Broadcasting onBluetoothServiceDown() to 10 receivers.
D/BluetoothAdapter( 1241): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41e01918
D/BluetoothAdapter( 1241): onBluetoothServiceDown: done
D/BluetoothAdapter( 3587): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b7a598
D/BluetoothAdapter( 3587): onBluetoothServiceDown: done
D/BluetoothAdapter( 1117): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41f4f3c0
D/BluetoothAdapter( 1117): onBluetoothServiceDown: done
D/BluetoothAdapter( 1396): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41cbaf10
D/BluetoothAdapter( 1396): onBluetoothServiceDown: done
D/BluetoothAdapter( 1593): onBluetoothServiceDown: com.android.bluetooth.btservice.AdapterService$AdapterServiceBinder@41b81e60
D/BluetoothDevice( 1593): onBluetoothServiceDown : UnRegister callback
D/BluetoothAdapter( 1593): onBluetoothServiceDown: done
D/BluetoothAdapter(  906): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@42481d00
D/BluetoothAdapter(  906): onBluetoothServiceDown: done
D/BluetoothAdapter( 1832): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c61610
D/BluetoothAdapter( 1832): onBluetoothServiceDown: done
D/BluetoothAdapter( 1252): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41c3be48
D/BluetoothAdapter( 1252): onBluetoothServiceDown: done
D/BluetoothAdapter( 3823): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41be76b0
D/BluetoothAdapter( 3823): onBluetoothServiceDown: done
D/BluetoothAdapter( 1805): onBluetoothServiceDown: android.bluetooth.IBluetooth$Stub$Proxy@41b8bae0
D/BluetoothAdapter( 1805): onBluetoothServiceDown: done
D/BluetoothManagerService(  906): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42481d00 mBinding = false
I/PeopleContactsSync( 2228): CP2 sync disabled
D/BluetoothManagerService(  906): Sending unbind request.
,D/BluetoothManagerService(  906): Bluetooth State Change Intent: 13 -> 10
,I/IntentController( 1117): receive(android.bluetooth.adapter.action.STATE_CHANGED,2,false)
,I/PackageManager(  906):  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=2228, uid=10028, userID:0
D/NfcHandover( 1252): onReceive: mBound=false, BTByNfc=false->false, BTHConnected=false->false
D/LocalBluetoothProfileManager( 3823): setBluetoothStateOff
,D/HtcTagManager( 3823): stopProxy
W/BluetoothEventManager( 3823): unregister mProfileBroadcastReceiver fail
D/BluetoothAdapterService( 1593): Cleaning up adapter native....
,I/bt-btif ( 1593): HAL bt_hal_cbacks->thread_evt_cb
,D/BluetoothAdapterService( 1593): Done cleaning up adapter native....
,D/TetherPref( 3823): persistRestoreBluetoothState false
,D/BluetoothAdapterService(1102574320)( 1593): ****onDestroy()********
D/BtGatt.GattService( 1593): cleanup()
W/bt-btif ( 1593): GATTC Module not enabled/already disabled
,W/bt-btif ( 1593): GATTS Module not enabled/already disabled
,D/PMS     (  906): releaseWL(426c9748): PARTIAL_WAKE_LOCK  ACQUIRE_CAUSES_WAKEUP ON_AFTER_RELEASE BluetoothRemoteDevices 0x30000001 null
,D/BluetoothMasReceiver( 1593): Bluetooth STATE CHANGED to 10
,V/BluetoothMasService( 1593): onDestroy: mIsEmailEnabled: true
,D/HtcBtWidget_BTWidgetProvider( 4026): onBTStateChanged() for widget: 
D/PMS     (  906): acquireWL(42624660): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 3823 1000 null
W/ContextImpl( 3823): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1741 android.content.ContextWrapper.startService:501 android.content.ContextWrapper.startService:501 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:141 com.android.settings.bluetooth.DockEventReceiver.onReceive:121 
D/PackageManager(  906): deletePackageAsUser: pkg=com.example.hello, pid=4047, uid=2000 user=0
,D/PMS     (  906): releaseWL(42624660): PARTIAL_WAKE_LOCK  Start_DockService_30 0x1 null
,D/HtcBtWidget_BTWidgetProvider( 4026): updateWidget(context) for widget: 
,D/DockEventReceiver( 3823): finishStartingService: stopping service
D/PMS     (  906): acquireWL(4288ac60): PARTIAL_WAKE_LOCK  StartingDockService 0x1 3823 1000 null
D/PMS     (  906): releaseWL(4288ac60): PARTIAL_WAKE_LOCK  StartingDockService 0x1 null
,D/BluetoothMasReceiver( 1593): Bluetooth STATE CHANGED to 10
D/Process (  906): killProcessQuiet, pid=3587
,D/Process (  906): com.android.server.am.ActivityManagerService.killUnneededProcessLocked:7520 com.android.server.am.ActivityManagerService.removeProcessLocked:5292 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5100 
,W/asset   (  906): Copying FileAsset 0x62b89a90 (zip:/data/app/com.example.hello-2.apk:/resources.arsc) to buffer size 2472 to make it aligned.
,W/ActivityManager(  906): handleTopAppChanged(): The previous AP is died unexpectedly.
I/ActivityManager(  906): Force stopping com.example.hello appid=10356 user=-1: uninstall pkg
I/ActivityManager(  906): Killing 3587:com.example.hello/u0a356 (adj 0): stop com.example.hello
,W/ActivityManager(  906): Force removing ActivityRecord{41fa18f0 u0 com.example.hello/.MainActivity t2}: app died, no saved state
W/BluetoothHeadset( 1117): Proxy not attached to service
I/QuickSettingMiniLite( 1117): updateLiteState:no connect device!
,W/PackageSettings(  906): Skipping PackageSetting{4222ac10 com.test.thalitest/10348} due to missing metadata
,D/BluetoothAdapter( 1117): 1105271240: getState() :  mService = null. Returning STATE_OFF
,I/QuickSettingBluetooth( 1117): receive.ACTION_STATE_CHANGE:STATE_OFF/(false,false)
I/ActivityManager(  906): Force stopping com.example.hello appid=10356 user=0: pkg removed
,W/InputDispatcher(  906): channel '42644d28 com.example.hello.MainActivity (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher(  906): channel '42644d28 com.example.hello.MainActivity (s)' ~ Channel is unrecoverably broken and will be disposed!
,D/WifiService(  906): Client connection lost with reason: 4
,W/InputDispatcher(  906): Attempted to unregister already unregistered input channel '42644d28 com.example.hello.MainActivity (s)'
I/WindowState(  906): WIN DEATH: Window{42644d28 u0 com.example.hello/com.example.hello.MainActivity}
I/DisplayManagerService(  906): stopWifiDisplayScanLocked(): mWifiDisplayScanRequested = false, mWifiDisplayScanRequestCount = 0
,I/WindowManager(  906): WINDOW DIED Window{42644d28 u0 com.example.hello/com.example.hello.MainActivity}
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, packageName: com.example.hello
D/DotMatrix( 1564): [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
D/DotMatrix( 1564): [EventService] get3rdNotificationByPkgName, com.example.hello does not support DotMatrix
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver action:android.intent.action.PACKAGE_REMOVED
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver packageName:com.example.hello
I/HtcKeyguardAppUpdateMonitor( 1117): ApplicationsIntentReceiver replacing:false
I/acms    ( 1871): Unregistering com.example.hello
E/acms    ( 1871): Could not unregister removed application com.example.hello
W/AccTypeManager( 1329): No authenticator found for type=com.twitter.android.auth.login, ignoring it.
,D/AccTypeManager( 1329): Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,W/GeofencerStateMachine( 1396): Ignoring removeGeofence because network location is disabled.
,I/FeedHostManager( 1269): [onResume]
,I/FeedProviderManager( 1269): onResume
I/SocialFeedProvider( 1269): +onResume
I/SocialFeedProvider( 1269): updateAccounts - Accounts is no change
,I/SocialFeedProvider( 1269): -onResume
,D/PMS     (  906): acquireWL(428f6998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 1396 10028 null
I/Prism.ItemManager( 3985): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,I/Prism.ItemManager( 3985): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.launcher (1269/10075)
,D/PMS     (  906): releaseWL(428f6998): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
I/ConnectivityHelper( 1269): [getCurrentConnectionType] no network connection
D/[HTC_BLE_2013.12.02.SDKBUILD][BluetoothAdapterReceiver]( 1805): Received state change = 10
,D/AccTypeManager( 1329): Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,W/SystemReader( 1252): Cannot find nfc_is_upgrade_to_ar890, use default value instead
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_ADAPTER
,W/System.err(  906): java.lang.Throwable: stack dump
,D/BluetoothManagerService(  906): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@42209708:true
,W/System.err(  906): 	at java.lang.Thread.dumpStack(Thread.java:512)
,W/System.err(  906): 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:412)
,W/System.err(  906): 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
W/System.err(  906): 	at android.os.Binder.execTransact(Binder.java:412)
,W/System.err(  906): 	at dalvik.system.NativeStart.run(Native Method)
,I/LocationAgent( 4050): new LocationAgent instance!!
,D/HtcTagManager( 4050): HtcTagManager construction complete
,D/BluetoothAdapter( 4050): 1102535832: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothInputDevice( 4050): BluetoothInputDevice()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 12
D/BluetoothAdapter( 4050): 1102535832: getState() :  mService = null. Returning STATE_OFF
D/BluetoothInputDevice( 4050): BluetoothInputDevice(): Fake return onServiceConnected
D/HidProfile( 4050): Bluetooth service connected
,W/BluetoothInputDevice( 4050): Proxy not attached to service
D/BluetoothPan( 4050): BluetoothPan()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 13
D/BluetoothAdapter( 4050): 1102535832: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPan( 4050): BluetoothPan(): Fake return onServiceConnected
,D/PanProfile( 4050): Bluetooth service connected
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
D/BluetoothMap( 4050): Create BluetoothMap proxy object
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "sms"
D/BluetoothManagerService(  906): registerStateChangeCallback+
,D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
,D/BluetoothManagerService(  906): Registered receivers: 14
I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,I/Prism.ItemManager( 1269): loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
,E/BluetoothMap( 4050): Could not bind to Bluetooth MAP Service with Intent { act=android.bluetooth.IBluetoothMap }
,D/BluetoothManagerService(  906): registerStateChangeCallback+
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
E/ExternalAccountType( 1329): Unsupported attribute readOnly
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothSap( 4050): BluetoothSap() call bindService
D/BluetoothManagerService(  906): Registered receivers: 15
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
W/ContextImpl( 4050): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1805 android.content.ContextWrapper.bindService:524 android.bluetooth.BluetoothSap.doBind:108 android.bluetooth.BluetoothSap.<init>:101 android.bluetooth.BluetoothAdapter.getProfileProxy:1391 
,D/BluetoothPbap( 4050): BluetoothPbap()
,D/BluetoothManagerService(  906): registerStateChangeCallback+
D/BluetoothManagerService(  906): Message: MESSAGE_REGISTER_STATE_CHANGE_CALLBACK
D/BluetoothManagerService(  906): Registered receivers: 16
D/BluetoothAdapter( 4050): 1102535832: getState() :  mService = null. Returning STATE_OFF
D/BluetoothPbap( 4050): BluetoothPbap(): Fake return onServiceConnected
D/PbapServerProfile( 4050): Bluetooth service connected
D/LocalBluetoothProfileManager( 4050): LocalBluetoothProfileManager construction complete
D/BluetoothAdapter( 4050): 1102535832: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4050): 1102535832: getState() :  mService = null. Returning STATE_OFF
D/LocalBluetoothProfileManager( 4050): setBluetoothStateOff
D/HtcTagManager( 4050): stopProxy
,W/BluetoothEventManager( 4050): unregister mProfileBroadcastReceiver fail
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  906):   Scheme: "sms"
,D/ConnectivityService(  906): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "smsto"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,V/Tethering(  906): mTetherableUsbRegexs:{(usb0)(ncm0)}
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mms"
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,D/Tethering(  906): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,V/Tethering(  906): bSetPropertyMultiRAB:false
,D/Tethering(  906): Tethering got CONNECTIVITY_ACTION type: WIFI, subtype: , status: DISCONNECTED
I/Tethering(  906): Finding IPv4 upstream interface on: LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0
I/Tethering(  906): ipv4Default null
I/Tethering(  906): No IPv4 upstream interface, giving up.
,D/Tethering(  906): TetherMasterSM: InitialState processMessage what=3
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by pl.k2.droidoaudioteka (1832/10178)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (1396/10028)
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.google.android.music (3913/10154)
I/PackageManager(  906):   Action: "android.intent.action.SENDTO"
I/PackageManager(  906):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  906):   Scheme: "mmsto"
,I/NetworkMonitor( 3913): type=WIFI subType= reason=null isConnected=false
I/PackageManager(  906): Adding preferred activity ComponentInfo{com.htc.sense.mms/com.htc.sense.mms.ui.PreHandleIntentActivity} for user 0, uid:1001, pid:1241 :
,I/InputMethodManagerService(  906): [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
W/InputMethodManagerService(  906): Got RemoteException sending setActive(false) notification to pid 3587 uid 10356
,I/InputMethodManagerService(  906): Enable input method client, pid=1269
,W/Netd    (  364): No subsystem found in netlink event
V/Tethering(  906): remove iface:wlan0
D/Tethering(  906): interfaceRemoved wlan0
,E/Tethering(  906): attempting to remove unknown iface (wlan0), ignoring
,W/Binder  ( 1207): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1207): java.lang.NullPointerException
W/Binder  ( 1207): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1207): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1207): 	at android.os.Binder.execTransact(Binder.java:412)
W/Binder  ( 1207): 	at dalvik.system.NativeStart.run(Native Method)
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,D/PhoneApp( 1241): -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,I/ConnectivityHelper( 1269): [onReceive] WIFI(1): DISCONNECTED
D/ConnectivityService(  906): getNetworkInfo networkType=1 called by com.htc.launcher (1269/10075)
D/ConnectivityService(  906): getActiveNetworkInfo called by com.htc.mirrorlinkserver (1871/1000)
,D/Tethering(  906): interfaceLinkStateChanged p2p0, false
,D/Tethering(  906): interfaceStatusChanged p2p0, false
,D/Tethering(  906): [isWifi] getHotspotEnabled: false
,E/SQLiteDatabase( 2228): Failed to open database '/data/data/com.google.android.gms/databases/games_3a3529a.db'.
E/SQLiteDatabase( 2228): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteDatabase( 2228): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteDatabase( 2228): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 2228): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 2228): 	at bxi.query(SourceFile:181)
E/SQLiteDatabase( 2228): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteDatabase( 2228): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteDatabase( 2228): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteDatabase( 2228): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteDatabase( 2228): 	at dtr.a(SourceFile:81)
E/SQLiteDatabase( 2228): 	at dug.g(SourceFile:3454)
E/SQLiteDatabase( 2228): 	at dug.c(SourceFile:3081)
E/SQLiteDatabase( 2228): 	at ezc.a(SourceFile:24)
E/SQLiteDatabase( 2228): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteDatabase( 2228): 	at bpu.run(SourceFile:101)
E/SQLiteDatabase( 2228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2228): 	at java.lang.Thread.run(Thread.java:864)
,E/SQLiteOpenHelper( 2228): Couldn't open games_3a3529a.db for writing (will try read-only):
E/SQLiteOpenHelper( 2228): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:849)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:829)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:734)
E/SQLiteOpenHelper( 2228): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1206)
E/SQLiteOpenHelper( 2228): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:263)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 2228): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 2228): 	at bxi.query(SourceFile:181)
E/SQLiteOpenHelper( 2228): 	at android.content.ContentProvider.query(ContentProvider.java:869)
E/SQLiteOpenHelper( 2228): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:212)
E/SQLiteOpenHelper( 2228): 	at android.content.ContentResolver.query(ContentResolver.java:476)
E/SQLiteOpenHelper( 2228): 	at android.content.ContentResolver.query(ContentResolver.java:419)
E/SQLiteOpenHelper( 2228): 	at dtr.a(SourceFile:81)
E/SQLiteOpenHelper( 2228): 	at dug.g(SourceFile:3454)
E/SQLiteOpenHelper( 2228): 	at dug.c(SourceFile:3081)
E/SQLiteOpenHelper( 2228): 	at ezc.a(SourceFile:24)
E/SQLiteOpenHelper( 2228): 	at com.google.android.gms.games.service.GamesIntentService.a(SourceFile:877)
E/SQLiteOpenHelper( 2228): 	at bpu.run(SourceFile:101)
E/SQLiteOpenHelper( 2228): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteOpenHelper( 2228): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteOpenHelper( 2228): 	at java.lang.Thread.run(Thread.java:864)
,W/SQLiteOpenHelper( 2228): Opened games_3a3529a.db in read-only mode
,W/dalvikvm( 2228): threadid=10: thread exiting with uncaught exception (group=0x41733e30)
,E/ActivityManager(  906): App crashed! Process: com.google.android.gms
E/AndroidRuntime( 2228): FATAL EXCEPTION: GamesProviderWorker
E/AndroidRuntime( 2228): Process: com.google.android.gms, PID: 2228
E/AndroidRuntime( 2228): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:240)
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:221)
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteConnectionPool.reconfigure(SQLiteConnectionPool.java:306)
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteDatabase.reopenReadWrite(SQLiteDatabase.java:818)
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:213)
E/AndroidRuntime( 2228): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 2228): 	at eoj.a(SourceFile:136)
E/AndroidRuntime( 2228): 	at eoj.<init>(SourceFile:65)
E/AndroidRuntime( 2228): 	at eob.b(SourceFile:105)
E/AndroidRuntime( 2228): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1598)
E/AndroidRuntime( 2228): 	at com.google.android.gms.games.provider.GamesContentProvider.a(SourceFile:1579)
E/AndroidRuntime( 2228): 	at elo.handleMessage(SourceFile:1523)
E/AndroidRuntime( 2228): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2228): 	at android.os.Looper.loop(Looper.java:157)
E/AndroidRuntime( 2228): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/DropBoxManagerService(  906): Can't write: system_app_crash
E/DropBoxManagerService(  906): java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  906): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  906): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:226)
E/DropBoxManagerService(  906): 	at android.os.DropBoxManager.addText(DropBoxManager.java:275)
E/DropBoxManagerService(  906): 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:10881)
E/DropBoxManagerService(  906): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  906): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  906): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  906): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService(  906): 	... 5 more
,W/Netd    (  364): No subsystem found in netlink event
,V/Tethering(  906): remove iface:p2p0
D/Tethering(  906): interfaceRemoved p2p0
,E/Tethering(  906): attempting to remove unknown iface (p2p0), ignoring
D/NetlinkEvent(  364): Unexpected netlink message. type=0x11
,W/PackageManager(  906): Unable to load service info ResolveInfo{42648ca8 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
W/PackageManager(  906): org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:449)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:305)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:70)
W/PackageManager(  906): 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:148)
W/PackageManager(  906): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:857)
W/PackageManager(  906): 	at android.os.Handler.handleCallback(Handler.java:733)
W/PackageManager(  906): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/PackageManager(  906): 	at android.os.Looper.loop(Looper.java:157)
W/PackageManager(  906): 	at com.android.server.ServerThread.initAndLoop(SystemServer.java:1464)
W/PackageManager(  906): 	at com.android.server.SystemServer.main(SystemServer.java:1591)
W/PackageManager(  906): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/PackageManager(  906): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:896)
W/PackageManager(  906): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:712)
W/PackageManager(  906): 	at dalvik.system.NativeStart.main(Native Method)
,D/RemoteDisplayProvider(  906): Received package manager broadcast: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 (has extras) }
,D/RemoteDisplayProvider(  906): start
I/AlarmManager(  906): [AlarmQueuing] connectivity wifi: false
,D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - original mNetworkConnected = true
,D/htcCheckinService(  906): ConnectivityReceiver - onReceive() - new mNetworkConnected = false
D/CaptivePortalTracker(  906): DelayedCaptiveCheckState
D/CaptivePortalTracker(  906): Disconnected from active network NetworkInfo: type: WIFI[, type_ext: WIFI], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false, isIpv4Connected: false, isIpv6Connected: false
,D/CaptivePortalTracker(  906): NoActiveNetworkState
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
D/ConnectivityService(  906): getActiveNetworkInfo called by  (906/1000)
,D/ConnectivityService(  906): getNetworkInfo networkType=1 called by  (906/1000)
,W/AtomicFile(  906): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,D/GpsLocationProvider(  906): [handleMessage] UPDATE_NETWORK_STATE
D/GpsLocationProvider(  906): updateNetworkState unavailable info:  NetworkInfo  Type: WIFI Subtype:  NetworkState: DISCONNECTED DetailedState: , roaming: false, failover: false, isAvailable: false
D/GpsLocationProvider(  906): getAGpsConnectionInfo connType - 4
,D/GpsLocationProvider(  906): ignore wifi update if we are not in OPENING or CLOSING
D/PMS     (  906): acquireWL(428e35a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 906 1000 null
W/AppWidgetServiceImpl(  906): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/PMS     (  906): releaseWL(428e35a8): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null

```
